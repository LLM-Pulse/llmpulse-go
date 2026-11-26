# TechnicalGeoReportsCreateResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ProjectId** | **int32** |  | 
**Url** | **string** | The URL analysed | 
**CountryCode** | **string** | The country used, the project country when none was sent | 
**OutputLanguageCode** | **string** | ISO 639-1 code the llms.txt files are written in, or auto for the website&#39;s own language | 
**BatchId** | **NullableInt32** | Bundle id, for the batch_id filter of GET /technical_geo_reports; null when no report was created | 
**CreatedReports** | **[]string** | The report_type of every report created | 
**ReportIds** | **map[string]int32** | The id of each created report, by report_type | 
**AppUrls** | **map[string]string** | The link that opens each created report in the app, by report_type | 
**FailedReports** | [**[]TechnicalGeoReportsCreateResponseFailedReportsInner**](TechnicalGeoReportsCreateResponseFailedReportsInner.md) | Reports that could not be created, with the reasons | 
**NextEndpoint** | **string** | Path template to poll each created report | 
**PollAfterSeconds** | **int32** | Seconds to wait before the first poll | 
**RequestId** | **string** |  | 

## Methods

### NewTechnicalGeoReportsCreateResponse

`func NewTechnicalGeoReportsCreateResponse(projectId int32, url string, countryCode string, outputLanguageCode string, batchId NullableInt32, createdReports []string, reportIds map[string]int32, appUrls map[string]string, failedReports []TechnicalGeoReportsCreateResponseFailedReportsInner, nextEndpoint string, pollAfterSeconds int32, requestId string, ) *TechnicalGeoReportsCreateResponse`

NewTechnicalGeoReportsCreateResponse instantiates a new TechnicalGeoReportsCreateResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTechnicalGeoReportsCreateResponseWithDefaults

`func NewTechnicalGeoReportsCreateResponseWithDefaults() *TechnicalGeoReportsCreateResponse`

NewTechnicalGeoReportsCreateResponseWithDefaults instantiates a new TechnicalGeoReportsCreateResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProjectId

`func (o *TechnicalGeoReportsCreateResponse) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *TechnicalGeoReportsCreateResponse) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *TechnicalGeoReportsCreateResponse) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.


### GetUrl

`func (o *TechnicalGeoReportsCreateResponse) GetUrl() string`

GetUrl returns the Url field if non-nil, zero value otherwise.

### GetUrlOk

`func (o *TechnicalGeoReportsCreateResponse) GetUrlOk() (*string, bool)`

GetUrlOk returns a tuple with the Url field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrl

`func (o *TechnicalGeoReportsCreateResponse) SetUrl(v string)`

SetUrl sets Url field to given value.


### GetCountryCode

`func (o *TechnicalGeoReportsCreateResponse) GetCountryCode() string`

GetCountryCode returns the CountryCode field if non-nil, zero value otherwise.

### GetCountryCodeOk

`func (o *TechnicalGeoReportsCreateResponse) GetCountryCodeOk() (*string, bool)`

GetCountryCodeOk returns a tuple with the CountryCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountryCode

`func (o *TechnicalGeoReportsCreateResponse) SetCountryCode(v string)`

SetCountryCode sets CountryCode field to given value.


### GetOutputLanguageCode

`func (o *TechnicalGeoReportsCreateResponse) GetOutputLanguageCode() string`

GetOutputLanguageCode returns the OutputLanguageCode field if non-nil, zero value otherwise.

### GetOutputLanguageCodeOk

`func (o *TechnicalGeoReportsCreateResponse) GetOutputLanguageCodeOk() (*string, bool)`

GetOutputLanguageCodeOk returns a tuple with the OutputLanguageCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOutputLanguageCode

`func (o *TechnicalGeoReportsCreateResponse) SetOutputLanguageCode(v string)`

SetOutputLanguageCode sets OutputLanguageCode field to given value.


### GetBatchId

`func (o *TechnicalGeoReportsCreateResponse) GetBatchId() int32`

GetBatchId returns the BatchId field if non-nil, zero value otherwise.

### GetBatchIdOk

`func (o *TechnicalGeoReportsCreateResponse) GetBatchIdOk() (*int32, bool)`

GetBatchIdOk returns a tuple with the BatchId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBatchId

`func (o *TechnicalGeoReportsCreateResponse) SetBatchId(v int32)`

SetBatchId sets BatchId field to given value.


### SetBatchIdNil

`func (o *TechnicalGeoReportsCreateResponse) SetBatchIdNil(b bool)`

 SetBatchIdNil sets the value for BatchId to be an explicit nil

### UnsetBatchId
`func (o *TechnicalGeoReportsCreateResponse) UnsetBatchId()`

UnsetBatchId ensures that no value is present for BatchId, not even an explicit nil
### GetCreatedReports

`func (o *TechnicalGeoReportsCreateResponse) GetCreatedReports() []string`

GetCreatedReports returns the CreatedReports field if non-nil, zero value otherwise.

### GetCreatedReportsOk

`func (o *TechnicalGeoReportsCreateResponse) GetCreatedReportsOk() (*[]string, bool)`

GetCreatedReportsOk returns a tuple with the CreatedReports field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedReports

`func (o *TechnicalGeoReportsCreateResponse) SetCreatedReports(v []string)`

SetCreatedReports sets CreatedReports field to given value.


### GetReportIds

`func (o *TechnicalGeoReportsCreateResponse) GetReportIds() map[string]int32`

GetReportIds returns the ReportIds field if non-nil, zero value otherwise.

### GetReportIdsOk

`func (o *TechnicalGeoReportsCreateResponse) GetReportIdsOk() (*map[string]int32, bool)`

GetReportIdsOk returns a tuple with the ReportIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReportIds

`func (o *TechnicalGeoReportsCreateResponse) SetReportIds(v map[string]int32)`

SetReportIds sets ReportIds field to given value.


### GetAppUrls

`func (o *TechnicalGeoReportsCreateResponse) GetAppUrls() map[string]string`

GetAppUrls returns the AppUrls field if non-nil, zero value otherwise.

### GetAppUrlsOk

`func (o *TechnicalGeoReportsCreateResponse) GetAppUrlsOk() (*map[string]string, bool)`

GetAppUrlsOk returns a tuple with the AppUrls field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAppUrls

`func (o *TechnicalGeoReportsCreateResponse) SetAppUrls(v map[string]string)`

SetAppUrls sets AppUrls field to given value.


### GetFailedReports

`func (o *TechnicalGeoReportsCreateResponse) GetFailedReports() []TechnicalGeoReportsCreateResponseFailedReportsInner`

GetFailedReports returns the FailedReports field if non-nil, zero value otherwise.

### GetFailedReportsOk

`func (o *TechnicalGeoReportsCreateResponse) GetFailedReportsOk() (*[]TechnicalGeoReportsCreateResponseFailedReportsInner, bool)`

GetFailedReportsOk returns a tuple with the FailedReports field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFailedReports

`func (o *TechnicalGeoReportsCreateResponse) SetFailedReports(v []TechnicalGeoReportsCreateResponseFailedReportsInner)`

SetFailedReports sets FailedReports field to given value.


### GetNextEndpoint

`func (o *TechnicalGeoReportsCreateResponse) GetNextEndpoint() string`

GetNextEndpoint returns the NextEndpoint field if non-nil, zero value otherwise.

### GetNextEndpointOk

`func (o *TechnicalGeoReportsCreateResponse) GetNextEndpointOk() (*string, bool)`

GetNextEndpointOk returns a tuple with the NextEndpoint field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNextEndpoint

`func (o *TechnicalGeoReportsCreateResponse) SetNextEndpoint(v string)`

SetNextEndpoint sets NextEndpoint field to given value.


### GetPollAfterSeconds

`func (o *TechnicalGeoReportsCreateResponse) GetPollAfterSeconds() int32`

GetPollAfterSeconds returns the PollAfterSeconds field if non-nil, zero value otherwise.

### GetPollAfterSecondsOk

`func (o *TechnicalGeoReportsCreateResponse) GetPollAfterSecondsOk() (*int32, bool)`

GetPollAfterSecondsOk returns a tuple with the PollAfterSeconds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPollAfterSeconds

`func (o *TechnicalGeoReportsCreateResponse) SetPollAfterSeconds(v int32)`

SetPollAfterSeconds sets PollAfterSeconds field to given value.


### GetRequestId

`func (o *TechnicalGeoReportsCreateResponse) GetRequestId() string`

GetRequestId returns the RequestId field if non-nil, zero value otherwise.

### GetRequestIdOk

`func (o *TechnicalGeoReportsCreateResponse) GetRequestIdOk() (*string, bool)`

GetRequestIdOk returns a tuple with the RequestId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestId

`func (o *TechnicalGeoReportsCreateResponse) SetRequestId(v string)`

SetRequestId sets RequestId field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


