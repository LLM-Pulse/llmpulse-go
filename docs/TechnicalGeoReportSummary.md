# TechnicalGeoReportSummary

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
**AppUrl** | Pointer to **string** | Opens this report in the app | [optional] 

## Methods

### NewTechnicalGeoReportSummary

`func NewTechnicalGeoReportSummary(id int32, reportType string, projectId int32, batchId NullableInt32, url NullableString, domain string, countryCode NullableString, outputLanguageCode NullableString, status string, resultAvailable bool, overallScore NullableFloat32, createdAt time.Time, updatedAt time.Time, ) *TechnicalGeoReportSummary`

NewTechnicalGeoReportSummary instantiates a new TechnicalGeoReportSummary object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTechnicalGeoReportSummaryWithDefaults

`func NewTechnicalGeoReportSummaryWithDefaults() *TechnicalGeoReportSummary`

NewTechnicalGeoReportSummaryWithDefaults instantiates a new TechnicalGeoReportSummary object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *TechnicalGeoReportSummary) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *TechnicalGeoReportSummary) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *TechnicalGeoReportSummary) SetId(v int32)`

SetId sets Id field to given value.


### GetReportType

`func (o *TechnicalGeoReportSummary) GetReportType() string`

GetReportType returns the ReportType field if non-nil, zero value otherwise.

### GetReportTypeOk

`func (o *TechnicalGeoReportSummary) GetReportTypeOk() (*string, bool)`

GetReportTypeOk returns a tuple with the ReportType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReportType

`func (o *TechnicalGeoReportSummary) SetReportType(v string)`

SetReportType sets ReportType field to given value.


### GetProjectId

`func (o *TechnicalGeoReportSummary) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *TechnicalGeoReportSummary) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *TechnicalGeoReportSummary) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.


### GetBatchId

`func (o *TechnicalGeoReportSummary) GetBatchId() int32`

GetBatchId returns the BatchId field if non-nil, zero value otherwise.

### GetBatchIdOk

`func (o *TechnicalGeoReportSummary) GetBatchIdOk() (*int32, bool)`

GetBatchIdOk returns a tuple with the BatchId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBatchId

`func (o *TechnicalGeoReportSummary) SetBatchId(v int32)`

SetBatchId sets BatchId field to given value.


### SetBatchIdNil

`func (o *TechnicalGeoReportSummary) SetBatchIdNil(b bool)`

 SetBatchIdNil sets the value for BatchId to be an explicit nil

### UnsetBatchId
`func (o *TechnicalGeoReportSummary) UnsetBatchId()`

UnsetBatchId ensures that no value is present for BatchId, not even an explicit nil
### GetUrl

`func (o *TechnicalGeoReportSummary) GetUrl() string`

GetUrl returns the Url field if non-nil, zero value otherwise.

### GetUrlOk

`func (o *TechnicalGeoReportSummary) GetUrlOk() (*string, bool)`

GetUrlOk returns a tuple with the Url field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrl

`func (o *TechnicalGeoReportSummary) SetUrl(v string)`

SetUrl sets Url field to given value.


### SetUrlNil

`func (o *TechnicalGeoReportSummary) SetUrlNil(b bool)`

 SetUrlNil sets the value for Url to be an explicit nil

### UnsetUrl
`func (o *TechnicalGeoReportSummary) UnsetUrl()`

UnsetUrl ensures that no value is present for Url, not even an explicit nil
### GetDomain

`func (o *TechnicalGeoReportSummary) GetDomain() string`

GetDomain returns the Domain field if non-nil, zero value otherwise.

### GetDomainOk

`func (o *TechnicalGeoReportSummary) GetDomainOk() (*string, bool)`

GetDomainOk returns a tuple with the Domain field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDomain

`func (o *TechnicalGeoReportSummary) SetDomain(v string)`

SetDomain sets Domain field to given value.


### GetCountryCode

`func (o *TechnicalGeoReportSummary) GetCountryCode() string`

GetCountryCode returns the CountryCode field if non-nil, zero value otherwise.

### GetCountryCodeOk

`func (o *TechnicalGeoReportSummary) GetCountryCodeOk() (*string, bool)`

GetCountryCodeOk returns a tuple with the CountryCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountryCode

`func (o *TechnicalGeoReportSummary) SetCountryCode(v string)`

SetCountryCode sets CountryCode field to given value.


### SetCountryCodeNil

`func (o *TechnicalGeoReportSummary) SetCountryCodeNil(b bool)`

 SetCountryCodeNil sets the value for CountryCode to be an explicit nil

### UnsetCountryCode
`func (o *TechnicalGeoReportSummary) UnsetCountryCode()`

UnsetCountryCode ensures that no value is present for CountryCode, not even an explicit nil
### GetOutputLanguageCode

`func (o *TechnicalGeoReportSummary) GetOutputLanguageCode() string`

GetOutputLanguageCode returns the OutputLanguageCode field if non-nil, zero value otherwise.

### GetOutputLanguageCodeOk

`func (o *TechnicalGeoReportSummary) GetOutputLanguageCodeOk() (*string, bool)`

GetOutputLanguageCodeOk returns a tuple with the OutputLanguageCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOutputLanguageCode

`func (o *TechnicalGeoReportSummary) SetOutputLanguageCode(v string)`

SetOutputLanguageCode sets OutputLanguageCode field to given value.


### SetOutputLanguageCodeNil

`func (o *TechnicalGeoReportSummary) SetOutputLanguageCodeNil(b bool)`

 SetOutputLanguageCodeNil sets the value for OutputLanguageCode to be an explicit nil

### UnsetOutputLanguageCode
`func (o *TechnicalGeoReportSummary) UnsetOutputLanguageCode()`

UnsetOutputLanguageCode ensures that no value is present for OutputLanguageCode, not even an explicit nil
### GetStatus

`func (o *TechnicalGeoReportSummary) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *TechnicalGeoReportSummary) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *TechnicalGeoReportSummary) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetResultAvailable

`func (o *TechnicalGeoReportSummary) GetResultAvailable() bool`

GetResultAvailable returns the ResultAvailable field if non-nil, zero value otherwise.

### GetResultAvailableOk

`func (o *TechnicalGeoReportSummary) GetResultAvailableOk() (*bool, bool)`

GetResultAvailableOk returns a tuple with the ResultAvailable field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResultAvailable

`func (o *TechnicalGeoReportSummary) SetResultAvailable(v bool)`

SetResultAvailable sets ResultAvailable field to given value.


### GetOverallScore

`func (o *TechnicalGeoReportSummary) GetOverallScore() float32`

GetOverallScore returns the OverallScore field if non-nil, zero value otherwise.

### GetOverallScoreOk

`func (o *TechnicalGeoReportSummary) GetOverallScoreOk() (*float32, bool)`

GetOverallScoreOk returns a tuple with the OverallScore field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOverallScore

`func (o *TechnicalGeoReportSummary) SetOverallScore(v float32)`

SetOverallScore sets OverallScore field to given value.


### SetOverallScoreNil

`func (o *TechnicalGeoReportSummary) SetOverallScoreNil(b bool)`

 SetOverallScoreNil sets the value for OverallScore to be an explicit nil

### UnsetOverallScore
`func (o *TechnicalGeoReportSummary) UnsetOverallScore()`

UnsetOverallScore ensures that no value is present for OverallScore, not even an explicit nil
### GetCreatedAt

`func (o *TechnicalGeoReportSummary) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *TechnicalGeoReportSummary) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *TechnicalGeoReportSummary) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetUpdatedAt

`func (o *TechnicalGeoReportSummary) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *TechnicalGeoReportSummary) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *TechnicalGeoReportSummary) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.


### GetAppUrl

`func (o *TechnicalGeoReportSummary) GetAppUrl() string`

GetAppUrl returns the AppUrl field if non-nil, zero value otherwise.

### GetAppUrlOk

`func (o *TechnicalGeoReportSummary) GetAppUrlOk() (*string, bool)`

GetAppUrlOk returns a tuple with the AppUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAppUrl

`func (o *TechnicalGeoReportSummary) SetAppUrl(v string)`

SetAppUrl sets AppUrl field to given value.

### HasAppUrl

`func (o *TechnicalGeoReportSummary) HasAppUrl() bool`

HasAppUrl returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


