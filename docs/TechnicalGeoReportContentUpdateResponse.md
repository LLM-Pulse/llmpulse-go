# TechnicalGeoReportContentUpdateResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **int32** |  | [optional] 
**ReportType** | Pointer to **string** | Always llms_txt | [optional] 
**ProjectId** | Pointer to **int32** |  | [optional] 
**BatchId** | Pointer to **NullableInt32** | Bundle the report was created in; null for a report created on its own | [optional] 
**Url** | Pointer to **NullableString** | Always null for llms_txt reports; domain names the website | [optional] 
**Domain** | Pointer to **string** |  | [optional] 
**CountryCode** | Pointer to **NullableString** |  | [optional] 
**OutputLanguageCode** | Pointer to **NullableString** | ISO 639-1 code the files were requested in; null when they are written in the website&#39;s own language | [optional] 
**Status** | Pointer to **string** |  | [optional] 
**ResultAvailable** | Pointer to **bool** |  | [optional] 
**OverallScore** | Pointer to **NullableFloat32** | Always null for llms_txt reports | [optional] 
**CreatedAt** | Pointer to **time.Time** |  | [optional] 
**UpdatedAt** | Pointer to **time.Time** |  | [optional] 
**ResultData** | Pointer to [**NullableLlmsTxtTechnicalGeoReportResultData**](LlmsTxtTechnicalGeoReportResultData.md) |  | [optional] 
**ErrorMessage** | Pointer to **NullableString** |  | [optional] 
**PollAfterSeconds** | Pointer to **NullableInt32** | Seconds to wait before polling again while the report runs; null once it has finished | [optional] 
**AppUrl** | Pointer to **string** | Opens this report in the app | [optional] 
**RequestId** | Pointer to **string** |  | [optional] 
**ChangedFiles** | Pointer to **[]string** | Files whose text actually changed; empty when every file matched the stored text | [optional] 

## Methods

### NewTechnicalGeoReportContentUpdateResponse

`func NewTechnicalGeoReportContentUpdateResponse() *TechnicalGeoReportContentUpdateResponse`

NewTechnicalGeoReportContentUpdateResponse instantiates a new TechnicalGeoReportContentUpdateResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTechnicalGeoReportContentUpdateResponseWithDefaults

`func NewTechnicalGeoReportContentUpdateResponseWithDefaults() *TechnicalGeoReportContentUpdateResponse`

NewTechnicalGeoReportContentUpdateResponseWithDefaults instantiates a new TechnicalGeoReportContentUpdateResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *TechnicalGeoReportContentUpdateResponse) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *TechnicalGeoReportContentUpdateResponse) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *TechnicalGeoReportContentUpdateResponse) SetId(v int32)`

SetId sets Id field to given value.

### HasId

`func (o *TechnicalGeoReportContentUpdateResponse) HasId() bool`

HasId returns a boolean if a field has been set.

### GetReportType

`func (o *TechnicalGeoReportContentUpdateResponse) GetReportType() string`

GetReportType returns the ReportType field if non-nil, zero value otherwise.

### GetReportTypeOk

`func (o *TechnicalGeoReportContentUpdateResponse) GetReportTypeOk() (*string, bool)`

GetReportTypeOk returns a tuple with the ReportType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReportType

`func (o *TechnicalGeoReportContentUpdateResponse) SetReportType(v string)`

SetReportType sets ReportType field to given value.

### HasReportType

`func (o *TechnicalGeoReportContentUpdateResponse) HasReportType() bool`

HasReportType returns a boolean if a field has been set.

### GetProjectId

`func (o *TechnicalGeoReportContentUpdateResponse) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *TechnicalGeoReportContentUpdateResponse) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *TechnicalGeoReportContentUpdateResponse) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.

### HasProjectId

`func (o *TechnicalGeoReportContentUpdateResponse) HasProjectId() bool`

HasProjectId returns a boolean if a field has been set.

### GetBatchId

`func (o *TechnicalGeoReportContentUpdateResponse) GetBatchId() int32`

GetBatchId returns the BatchId field if non-nil, zero value otherwise.

### GetBatchIdOk

`func (o *TechnicalGeoReportContentUpdateResponse) GetBatchIdOk() (*int32, bool)`

GetBatchIdOk returns a tuple with the BatchId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBatchId

`func (o *TechnicalGeoReportContentUpdateResponse) SetBatchId(v int32)`

SetBatchId sets BatchId field to given value.

### HasBatchId

`func (o *TechnicalGeoReportContentUpdateResponse) HasBatchId() bool`

HasBatchId returns a boolean if a field has been set.

### SetBatchIdNil

`func (o *TechnicalGeoReportContentUpdateResponse) SetBatchIdNil(b bool)`

 SetBatchIdNil sets the value for BatchId to be an explicit nil

### UnsetBatchId
`func (o *TechnicalGeoReportContentUpdateResponse) UnsetBatchId()`

UnsetBatchId ensures that no value is present for BatchId, not even an explicit nil
### GetUrl

`func (o *TechnicalGeoReportContentUpdateResponse) GetUrl() string`

GetUrl returns the Url field if non-nil, zero value otherwise.

### GetUrlOk

`func (o *TechnicalGeoReportContentUpdateResponse) GetUrlOk() (*string, bool)`

GetUrlOk returns a tuple with the Url field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrl

`func (o *TechnicalGeoReportContentUpdateResponse) SetUrl(v string)`

SetUrl sets Url field to given value.

### HasUrl

`func (o *TechnicalGeoReportContentUpdateResponse) HasUrl() bool`

HasUrl returns a boolean if a field has been set.

### SetUrlNil

`func (o *TechnicalGeoReportContentUpdateResponse) SetUrlNil(b bool)`

 SetUrlNil sets the value for Url to be an explicit nil

### UnsetUrl
`func (o *TechnicalGeoReportContentUpdateResponse) UnsetUrl()`

UnsetUrl ensures that no value is present for Url, not even an explicit nil
### GetDomain

`func (o *TechnicalGeoReportContentUpdateResponse) GetDomain() string`

GetDomain returns the Domain field if non-nil, zero value otherwise.

### GetDomainOk

`func (o *TechnicalGeoReportContentUpdateResponse) GetDomainOk() (*string, bool)`

GetDomainOk returns a tuple with the Domain field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDomain

`func (o *TechnicalGeoReportContentUpdateResponse) SetDomain(v string)`

SetDomain sets Domain field to given value.

### HasDomain

`func (o *TechnicalGeoReportContentUpdateResponse) HasDomain() bool`

HasDomain returns a boolean if a field has been set.

### GetCountryCode

`func (o *TechnicalGeoReportContentUpdateResponse) GetCountryCode() string`

GetCountryCode returns the CountryCode field if non-nil, zero value otherwise.

### GetCountryCodeOk

`func (o *TechnicalGeoReportContentUpdateResponse) GetCountryCodeOk() (*string, bool)`

GetCountryCodeOk returns a tuple with the CountryCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountryCode

`func (o *TechnicalGeoReportContentUpdateResponse) SetCountryCode(v string)`

SetCountryCode sets CountryCode field to given value.

### HasCountryCode

`func (o *TechnicalGeoReportContentUpdateResponse) HasCountryCode() bool`

HasCountryCode returns a boolean if a field has been set.

### SetCountryCodeNil

`func (o *TechnicalGeoReportContentUpdateResponse) SetCountryCodeNil(b bool)`

 SetCountryCodeNil sets the value for CountryCode to be an explicit nil

### UnsetCountryCode
`func (o *TechnicalGeoReportContentUpdateResponse) UnsetCountryCode()`

UnsetCountryCode ensures that no value is present for CountryCode, not even an explicit nil
### GetOutputLanguageCode

`func (o *TechnicalGeoReportContentUpdateResponse) GetOutputLanguageCode() string`

GetOutputLanguageCode returns the OutputLanguageCode field if non-nil, zero value otherwise.

### GetOutputLanguageCodeOk

`func (o *TechnicalGeoReportContentUpdateResponse) GetOutputLanguageCodeOk() (*string, bool)`

GetOutputLanguageCodeOk returns a tuple with the OutputLanguageCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOutputLanguageCode

`func (o *TechnicalGeoReportContentUpdateResponse) SetOutputLanguageCode(v string)`

SetOutputLanguageCode sets OutputLanguageCode field to given value.

### HasOutputLanguageCode

`func (o *TechnicalGeoReportContentUpdateResponse) HasOutputLanguageCode() bool`

HasOutputLanguageCode returns a boolean if a field has been set.

### SetOutputLanguageCodeNil

`func (o *TechnicalGeoReportContentUpdateResponse) SetOutputLanguageCodeNil(b bool)`

 SetOutputLanguageCodeNil sets the value for OutputLanguageCode to be an explicit nil

### UnsetOutputLanguageCode
`func (o *TechnicalGeoReportContentUpdateResponse) UnsetOutputLanguageCode()`

UnsetOutputLanguageCode ensures that no value is present for OutputLanguageCode, not even an explicit nil
### GetStatus

`func (o *TechnicalGeoReportContentUpdateResponse) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *TechnicalGeoReportContentUpdateResponse) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *TechnicalGeoReportContentUpdateResponse) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *TechnicalGeoReportContentUpdateResponse) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetResultAvailable

`func (o *TechnicalGeoReportContentUpdateResponse) GetResultAvailable() bool`

GetResultAvailable returns the ResultAvailable field if non-nil, zero value otherwise.

### GetResultAvailableOk

`func (o *TechnicalGeoReportContentUpdateResponse) GetResultAvailableOk() (*bool, bool)`

GetResultAvailableOk returns a tuple with the ResultAvailable field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResultAvailable

`func (o *TechnicalGeoReportContentUpdateResponse) SetResultAvailable(v bool)`

SetResultAvailable sets ResultAvailable field to given value.

### HasResultAvailable

`func (o *TechnicalGeoReportContentUpdateResponse) HasResultAvailable() bool`

HasResultAvailable returns a boolean if a field has been set.

### GetOverallScore

`func (o *TechnicalGeoReportContentUpdateResponse) GetOverallScore() float32`

GetOverallScore returns the OverallScore field if non-nil, zero value otherwise.

### GetOverallScoreOk

`func (o *TechnicalGeoReportContentUpdateResponse) GetOverallScoreOk() (*float32, bool)`

GetOverallScoreOk returns a tuple with the OverallScore field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOverallScore

`func (o *TechnicalGeoReportContentUpdateResponse) SetOverallScore(v float32)`

SetOverallScore sets OverallScore field to given value.

### HasOverallScore

`func (o *TechnicalGeoReportContentUpdateResponse) HasOverallScore() bool`

HasOverallScore returns a boolean if a field has been set.

### SetOverallScoreNil

`func (o *TechnicalGeoReportContentUpdateResponse) SetOverallScoreNil(b bool)`

 SetOverallScoreNil sets the value for OverallScore to be an explicit nil

### UnsetOverallScore
`func (o *TechnicalGeoReportContentUpdateResponse) UnsetOverallScore()`

UnsetOverallScore ensures that no value is present for OverallScore, not even an explicit nil
### GetCreatedAt

`func (o *TechnicalGeoReportContentUpdateResponse) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *TechnicalGeoReportContentUpdateResponse) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *TechnicalGeoReportContentUpdateResponse) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *TechnicalGeoReportContentUpdateResponse) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetUpdatedAt

`func (o *TechnicalGeoReportContentUpdateResponse) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *TechnicalGeoReportContentUpdateResponse) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *TechnicalGeoReportContentUpdateResponse) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *TechnicalGeoReportContentUpdateResponse) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.

### GetResultData

`func (o *TechnicalGeoReportContentUpdateResponse) GetResultData() LlmsTxtTechnicalGeoReportResultData`

GetResultData returns the ResultData field if non-nil, zero value otherwise.

### GetResultDataOk

`func (o *TechnicalGeoReportContentUpdateResponse) GetResultDataOk() (*LlmsTxtTechnicalGeoReportResultData, bool)`

GetResultDataOk returns a tuple with the ResultData field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResultData

`func (o *TechnicalGeoReportContentUpdateResponse) SetResultData(v LlmsTxtTechnicalGeoReportResultData)`

SetResultData sets ResultData field to given value.

### HasResultData

`func (o *TechnicalGeoReportContentUpdateResponse) HasResultData() bool`

HasResultData returns a boolean if a field has been set.

### SetResultDataNil

`func (o *TechnicalGeoReportContentUpdateResponse) SetResultDataNil(b bool)`

 SetResultDataNil sets the value for ResultData to be an explicit nil

### UnsetResultData
`func (o *TechnicalGeoReportContentUpdateResponse) UnsetResultData()`

UnsetResultData ensures that no value is present for ResultData, not even an explicit nil
### GetErrorMessage

`func (o *TechnicalGeoReportContentUpdateResponse) GetErrorMessage() string`

GetErrorMessage returns the ErrorMessage field if non-nil, zero value otherwise.

### GetErrorMessageOk

`func (o *TechnicalGeoReportContentUpdateResponse) GetErrorMessageOk() (*string, bool)`

GetErrorMessageOk returns a tuple with the ErrorMessage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrorMessage

`func (o *TechnicalGeoReportContentUpdateResponse) SetErrorMessage(v string)`

SetErrorMessage sets ErrorMessage field to given value.

### HasErrorMessage

`func (o *TechnicalGeoReportContentUpdateResponse) HasErrorMessage() bool`

HasErrorMessage returns a boolean if a field has been set.

### SetErrorMessageNil

`func (o *TechnicalGeoReportContentUpdateResponse) SetErrorMessageNil(b bool)`

 SetErrorMessageNil sets the value for ErrorMessage to be an explicit nil

### UnsetErrorMessage
`func (o *TechnicalGeoReportContentUpdateResponse) UnsetErrorMessage()`

UnsetErrorMessage ensures that no value is present for ErrorMessage, not even an explicit nil
### GetPollAfterSeconds

`func (o *TechnicalGeoReportContentUpdateResponse) GetPollAfterSeconds() int32`

GetPollAfterSeconds returns the PollAfterSeconds field if non-nil, zero value otherwise.

### GetPollAfterSecondsOk

`func (o *TechnicalGeoReportContentUpdateResponse) GetPollAfterSecondsOk() (*int32, bool)`

GetPollAfterSecondsOk returns a tuple with the PollAfterSeconds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPollAfterSeconds

`func (o *TechnicalGeoReportContentUpdateResponse) SetPollAfterSeconds(v int32)`

SetPollAfterSeconds sets PollAfterSeconds field to given value.

### HasPollAfterSeconds

`func (o *TechnicalGeoReportContentUpdateResponse) HasPollAfterSeconds() bool`

HasPollAfterSeconds returns a boolean if a field has been set.

### SetPollAfterSecondsNil

`func (o *TechnicalGeoReportContentUpdateResponse) SetPollAfterSecondsNil(b bool)`

 SetPollAfterSecondsNil sets the value for PollAfterSeconds to be an explicit nil

### UnsetPollAfterSeconds
`func (o *TechnicalGeoReportContentUpdateResponse) UnsetPollAfterSeconds()`

UnsetPollAfterSeconds ensures that no value is present for PollAfterSeconds, not even an explicit nil
### GetAppUrl

`func (o *TechnicalGeoReportContentUpdateResponse) GetAppUrl() string`

GetAppUrl returns the AppUrl field if non-nil, zero value otherwise.

### GetAppUrlOk

`func (o *TechnicalGeoReportContentUpdateResponse) GetAppUrlOk() (*string, bool)`

GetAppUrlOk returns a tuple with the AppUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAppUrl

`func (o *TechnicalGeoReportContentUpdateResponse) SetAppUrl(v string)`

SetAppUrl sets AppUrl field to given value.

### HasAppUrl

`func (o *TechnicalGeoReportContentUpdateResponse) HasAppUrl() bool`

HasAppUrl returns a boolean if a field has been set.

### GetRequestId

`func (o *TechnicalGeoReportContentUpdateResponse) GetRequestId() string`

GetRequestId returns the RequestId field if non-nil, zero value otherwise.

### GetRequestIdOk

`func (o *TechnicalGeoReportContentUpdateResponse) GetRequestIdOk() (*string, bool)`

GetRequestIdOk returns a tuple with the RequestId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestId

`func (o *TechnicalGeoReportContentUpdateResponse) SetRequestId(v string)`

SetRequestId sets RequestId field to given value.

### HasRequestId

`func (o *TechnicalGeoReportContentUpdateResponse) HasRequestId() bool`

HasRequestId returns a boolean if a field has been set.

### GetChangedFiles

`func (o *TechnicalGeoReportContentUpdateResponse) GetChangedFiles() []string`

GetChangedFiles returns the ChangedFiles field if non-nil, zero value otherwise.

### GetChangedFilesOk

`func (o *TechnicalGeoReportContentUpdateResponse) GetChangedFilesOk() (*[]string, bool)`

GetChangedFilesOk returns a tuple with the ChangedFiles field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChangedFiles

`func (o *TechnicalGeoReportContentUpdateResponse) SetChangedFiles(v []string)`

SetChangedFiles sets ChangedFiles field to given value.

### HasChangedFiles

`func (o *TechnicalGeoReportContentUpdateResponse) HasChangedFiles() bool`

HasChangedFiles returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


