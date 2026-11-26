# TechnicalGeoReportResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **int32** |  | 
**ReportType** | **string** | The report_type requested (agent_readiness for ai_readiness) | 
**ProjectId** | **int32** |  | 
**BatchId** | **NullableInt32** | Bundle the report was created in; null for a report created on its own | 
**Url** | **NullableString** | The page analysed; null for the domain-level types (robots_txt, agent_readiness, llms_txt, ai_visibility) | 
**Domain** | **string** |  | 
**CountryCode** | **NullableString** | Set only on llms_txt and ai_visibility reports | 
**OutputLanguageCode** | **NullableString** | ISO 639-1 code an llms_txt report was requested in; null for an llms_txt report written in the website&#39;s own language and for every other type | 
**Status** | **string** | Depends on report_type. Every type ends completed or failed; ai_visibility can also end insufficient_data | 
**ResultAvailable** | **bool** | Whether status is completed | 
**OverallScore** | **NullableFloat32** | Null until the report completes, and always for llms_txt | 
**CreatedAt** | **time.Time** |  | 
**UpdatedAt** | **time.Time** |  | 
**ResultData** | **map[string]interface{}** | The full result once the report has completed; null before that. Its shape depends on report_type; an llms_txt report returns its files as LlmsTxtTechnicalGeoReport describes | 
**ErrorMessage** | **NullableString** | Why the report failed, or why an ai_visibility report found insufficient data; null otherwise | 
**PollAfterSeconds** | **NullableInt32** | Seconds to wait before polling again while the report runs; null once it has finished | 
**AppUrl** | Pointer to **string** | Opens this report in the app | [optional] 
**RequestId** | **string** |  | 

## Methods

### NewTechnicalGeoReportResponse

`func NewTechnicalGeoReportResponse(id int32, reportType string, projectId int32, batchId NullableInt32, url NullableString, domain string, countryCode NullableString, outputLanguageCode NullableString, status string, resultAvailable bool, overallScore NullableFloat32, createdAt time.Time, updatedAt time.Time, resultData map[string]interface{}, errorMessage NullableString, pollAfterSeconds NullableInt32, requestId string, ) *TechnicalGeoReportResponse`

NewTechnicalGeoReportResponse instantiates a new TechnicalGeoReportResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTechnicalGeoReportResponseWithDefaults

`func NewTechnicalGeoReportResponseWithDefaults() *TechnicalGeoReportResponse`

NewTechnicalGeoReportResponseWithDefaults instantiates a new TechnicalGeoReportResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *TechnicalGeoReportResponse) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *TechnicalGeoReportResponse) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *TechnicalGeoReportResponse) SetId(v int32)`

SetId sets Id field to given value.


### GetReportType

`func (o *TechnicalGeoReportResponse) GetReportType() string`

GetReportType returns the ReportType field if non-nil, zero value otherwise.

### GetReportTypeOk

`func (o *TechnicalGeoReportResponse) GetReportTypeOk() (*string, bool)`

GetReportTypeOk returns a tuple with the ReportType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReportType

`func (o *TechnicalGeoReportResponse) SetReportType(v string)`

SetReportType sets ReportType field to given value.


### GetProjectId

`func (o *TechnicalGeoReportResponse) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *TechnicalGeoReportResponse) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *TechnicalGeoReportResponse) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.


### GetBatchId

`func (o *TechnicalGeoReportResponse) GetBatchId() int32`

GetBatchId returns the BatchId field if non-nil, zero value otherwise.

### GetBatchIdOk

`func (o *TechnicalGeoReportResponse) GetBatchIdOk() (*int32, bool)`

GetBatchIdOk returns a tuple with the BatchId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBatchId

`func (o *TechnicalGeoReportResponse) SetBatchId(v int32)`

SetBatchId sets BatchId field to given value.


### SetBatchIdNil

`func (o *TechnicalGeoReportResponse) SetBatchIdNil(b bool)`

 SetBatchIdNil sets the value for BatchId to be an explicit nil

### UnsetBatchId
`func (o *TechnicalGeoReportResponse) UnsetBatchId()`

UnsetBatchId ensures that no value is present for BatchId, not even an explicit nil
### GetUrl

`func (o *TechnicalGeoReportResponse) GetUrl() string`

GetUrl returns the Url field if non-nil, zero value otherwise.

### GetUrlOk

`func (o *TechnicalGeoReportResponse) GetUrlOk() (*string, bool)`

GetUrlOk returns a tuple with the Url field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrl

`func (o *TechnicalGeoReportResponse) SetUrl(v string)`

SetUrl sets Url field to given value.


### SetUrlNil

`func (o *TechnicalGeoReportResponse) SetUrlNil(b bool)`

 SetUrlNil sets the value for Url to be an explicit nil

### UnsetUrl
`func (o *TechnicalGeoReportResponse) UnsetUrl()`

UnsetUrl ensures that no value is present for Url, not even an explicit nil
### GetDomain

`func (o *TechnicalGeoReportResponse) GetDomain() string`

GetDomain returns the Domain field if non-nil, zero value otherwise.

### GetDomainOk

`func (o *TechnicalGeoReportResponse) GetDomainOk() (*string, bool)`

GetDomainOk returns a tuple with the Domain field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDomain

`func (o *TechnicalGeoReportResponse) SetDomain(v string)`

SetDomain sets Domain field to given value.


### GetCountryCode

`func (o *TechnicalGeoReportResponse) GetCountryCode() string`

GetCountryCode returns the CountryCode field if non-nil, zero value otherwise.

### GetCountryCodeOk

`func (o *TechnicalGeoReportResponse) GetCountryCodeOk() (*string, bool)`

GetCountryCodeOk returns a tuple with the CountryCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountryCode

`func (o *TechnicalGeoReportResponse) SetCountryCode(v string)`

SetCountryCode sets CountryCode field to given value.


### SetCountryCodeNil

`func (o *TechnicalGeoReportResponse) SetCountryCodeNil(b bool)`

 SetCountryCodeNil sets the value for CountryCode to be an explicit nil

### UnsetCountryCode
`func (o *TechnicalGeoReportResponse) UnsetCountryCode()`

UnsetCountryCode ensures that no value is present for CountryCode, not even an explicit nil
### GetOutputLanguageCode

`func (o *TechnicalGeoReportResponse) GetOutputLanguageCode() string`

GetOutputLanguageCode returns the OutputLanguageCode field if non-nil, zero value otherwise.

### GetOutputLanguageCodeOk

`func (o *TechnicalGeoReportResponse) GetOutputLanguageCodeOk() (*string, bool)`

GetOutputLanguageCodeOk returns a tuple with the OutputLanguageCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOutputLanguageCode

`func (o *TechnicalGeoReportResponse) SetOutputLanguageCode(v string)`

SetOutputLanguageCode sets OutputLanguageCode field to given value.


### SetOutputLanguageCodeNil

`func (o *TechnicalGeoReportResponse) SetOutputLanguageCodeNil(b bool)`

 SetOutputLanguageCodeNil sets the value for OutputLanguageCode to be an explicit nil

### UnsetOutputLanguageCode
`func (o *TechnicalGeoReportResponse) UnsetOutputLanguageCode()`

UnsetOutputLanguageCode ensures that no value is present for OutputLanguageCode, not even an explicit nil
### GetStatus

`func (o *TechnicalGeoReportResponse) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *TechnicalGeoReportResponse) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *TechnicalGeoReportResponse) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetResultAvailable

`func (o *TechnicalGeoReportResponse) GetResultAvailable() bool`

GetResultAvailable returns the ResultAvailable field if non-nil, zero value otherwise.

### GetResultAvailableOk

`func (o *TechnicalGeoReportResponse) GetResultAvailableOk() (*bool, bool)`

GetResultAvailableOk returns a tuple with the ResultAvailable field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResultAvailable

`func (o *TechnicalGeoReportResponse) SetResultAvailable(v bool)`

SetResultAvailable sets ResultAvailable field to given value.


### GetOverallScore

`func (o *TechnicalGeoReportResponse) GetOverallScore() float32`

GetOverallScore returns the OverallScore field if non-nil, zero value otherwise.

### GetOverallScoreOk

`func (o *TechnicalGeoReportResponse) GetOverallScoreOk() (*float32, bool)`

GetOverallScoreOk returns a tuple with the OverallScore field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOverallScore

`func (o *TechnicalGeoReportResponse) SetOverallScore(v float32)`

SetOverallScore sets OverallScore field to given value.


### SetOverallScoreNil

`func (o *TechnicalGeoReportResponse) SetOverallScoreNil(b bool)`

 SetOverallScoreNil sets the value for OverallScore to be an explicit nil

### UnsetOverallScore
`func (o *TechnicalGeoReportResponse) UnsetOverallScore()`

UnsetOverallScore ensures that no value is present for OverallScore, not even an explicit nil
### GetCreatedAt

`func (o *TechnicalGeoReportResponse) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *TechnicalGeoReportResponse) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *TechnicalGeoReportResponse) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetUpdatedAt

`func (o *TechnicalGeoReportResponse) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *TechnicalGeoReportResponse) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *TechnicalGeoReportResponse) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.


### GetResultData

`func (o *TechnicalGeoReportResponse) GetResultData() map[string]interface{}`

GetResultData returns the ResultData field if non-nil, zero value otherwise.

### GetResultDataOk

`func (o *TechnicalGeoReportResponse) GetResultDataOk() (*map[string]interface{}, bool)`

GetResultDataOk returns a tuple with the ResultData field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResultData

`func (o *TechnicalGeoReportResponse) SetResultData(v map[string]interface{})`

SetResultData sets ResultData field to given value.


### SetResultDataNil

`func (o *TechnicalGeoReportResponse) SetResultDataNil(b bool)`

 SetResultDataNil sets the value for ResultData to be an explicit nil

### UnsetResultData
`func (o *TechnicalGeoReportResponse) UnsetResultData()`

UnsetResultData ensures that no value is present for ResultData, not even an explicit nil
### GetErrorMessage

`func (o *TechnicalGeoReportResponse) GetErrorMessage() string`

GetErrorMessage returns the ErrorMessage field if non-nil, zero value otherwise.

### GetErrorMessageOk

`func (o *TechnicalGeoReportResponse) GetErrorMessageOk() (*string, bool)`

GetErrorMessageOk returns a tuple with the ErrorMessage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrorMessage

`func (o *TechnicalGeoReportResponse) SetErrorMessage(v string)`

SetErrorMessage sets ErrorMessage field to given value.


### SetErrorMessageNil

`func (o *TechnicalGeoReportResponse) SetErrorMessageNil(b bool)`

 SetErrorMessageNil sets the value for ErrorMessage to be an explicit nil

### UnsetErrorMessage
`func (o *TechnicalGeoReportResponse) UnsetErrorMessage()`

UnsetErrorMessage ensures that no value is present for ErrorMessage, not even an explicit nil
### GetPollAfterSeconds

`func (o *TechnicalGeoReportResponse) GetPollAfterSeconds() int32`

GetPollAfterSeconds returns the PollAfterSeconds field if non-nil, zero value otherwise.

### GetPollAfterSecondsOk

`func (o *TechnicalGeoReportResponse) GetPollAfterSecondsOk() (*int32, bool)`

GetPollAfterSecondsOk returns a tuple with the PollAfterSeconds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPollAfterSeconds

`func (o *TechnicalGeoReportResponse) SetPollAfterSeconds(v int32)`

SetPollAfterSeconds sets PollAfterSeconds field to given value.


### SetPollAfterSecondsNil

`func (o *TechnicalGeoReportResponse) SetPollAfterSecondsNil(b bool)`

 SetPollAfterSecondsNil sets the value for PollAfterSeconds to be an explicit nil

### UnsetPollAfterSeconds
`func (o *TechnicalGeoReportResponse) UnsetPollAfterSeconds()`

UnsetPollAfterSeconds ensures that no value is present for PollAfterSeconds, not even an explicit nil
### GetAppUrl

`func (o *TechnicalGeoReportResponse) GetAppUrl() string`

GetAppUrl returns the AppUrl field if non-nil, zero value otherwise.

### GetAppUrlOk

`func (o *TechnicalGeoReportResponse) GetAppUrlOk() (*string, bool)`

GetAppUrlOk returns a tuple with the AppUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAppUrl

`func (o *TechnicalGeoReportResponse) SetAppUrl(v string)`

SetAppUrl sets AppUrl field to given value.

### HasAppUrl

`func (o *TechnicalGeoReportResponse) HasAppUrl() bool`

HasAppUrl returns a boolean if a field has been set.

### GetRequestId

`func (o *TechnicalGeoReportResponse) GetRequestId() string`

GetRequestId returns the RequestId field if non-nil, zero value otherwise.

### GetRequestIdOk

`func (o *TechnicalGeoReportResponse) GetRequestIdOk() (*string, bool)`

GetRequestIdOk returns a tuple with the RequestId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestId

`func (o *TechnicalGeoReportResponse) SetRequestId(v string)`

SetRequestId sets RequestId field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


