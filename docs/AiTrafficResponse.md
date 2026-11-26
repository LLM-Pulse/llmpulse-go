# AiTrafficResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ProjectId** | **int32** |  | 
**Provider** | **string** | The connected provider: google_analytics, adobe_analytics, adobe_cja, posthog, plausible, matomo or piano | 
**From** | **string** |  | 
**To** | **string** |  | 
**Granularity** | **string** |  | 
**Totals** | [**AiTrafficResponseTotals**](AiTrafficResponseTotals.md) |  | 
**BySource** | [**[]AiTrafficResponseBySourceInner**](AiTrafficResponseBySourceInner.md) | One row per AI source with traffic in the window, most sessions first | 
**Timeseries** | **map[string]map[string]int32** | Sessions keyed by AI source slug, then by the first day of the period (YYYY-MM-DD); a period without traffic is left out | 
**RequestId** | **string** |  | 

## Methods

### NewAiTrafficResponse

`func NewAiTrafficResponse(projectId int32, provider string, from string, to string, granularity string, totals AiTrafficResponseTotals, bySource []AiTrafficResponseBySourceInner, timeseries map[string]map[string]int32, requestId string, ) *AiTrafficResponse`

NewAiTrafficResponse instantiates a new AiTrafficResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAiTrafficResponseWithDefaults

`func NewAiTrafficResponseWithDefaults() *AiTrafficResponse`

NewAiTrafficResponseWithDefaults instantiates a new AiTrafficResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProjectId

`func (o *AiTrafficResponse) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *AiTrafficResponse) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *AiTrafficResponse) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.


### GetProvider

`func (o *AiTrafficResponse) GetProvider() string`

GetProvider returns the Provider field if non-nil, zero value otherwise.

### GetProviderOk

`func (o *AiTrafficResponse) GetProviderOk() (*string, bool)`

GetProviderOk returns a tuple with the Provider field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProvider

`func (o *AiTrafficResponse) SetProvider(v string)`

SetProvider sets Provider field to given value.


### GetFrom

`func (o *AiTrafficResponse) GetFrom() string`

GetFrom returns the From field if non-nil, zero value otherwise.

### GetFromOk

`func (o *AiTrafficResponse) GetFromOk() (*string, bool)`

GetFromOk returns a tuple with the From field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFrom

`func (o *AiTrafficResponse) SetFrom(v string)`

SetFrom sets From field to given value.


### GetTo

`func (o *AiTrafficResponse) GetTo() string`

GetTo returns the To field if non-nil, zero value otherwise.

### GetToOk

`func (o *AiTrafficResponse) GetToOk() (*string, bool)`

GetToOk returns a tuple with the To field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTo

`func (o *AiTrafficResponse) SetTo(v string)`

SetTo sets To field to given value.


### GetGranularity

`func (o *AiTrafficResponse) GetGranularity() string`

GetGranularity returns the Granularity field if non-nil, zero value otherwise.

### GetGranularityOk

`func (o *AiTrafficResponse) GetGranularityOk() (*string, bool)`

GetGranularityOk returns a tuple with the Granularity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGranularity

`func (o *AiTrafficResponse) SetGranularity(v string)`

SetGranularity sets Granularity field to given value.


### GetTotals

`func (o *AiTrafficResponse) GetTotals() AiTrafficResponseTotals`

GetTotals returns the Totals field if non-nil, zero value otherwise.

### GetTotalsOk

`func (o *AiTrafficResponse) GetTotalsOk() (*AiTrafficResponseTotals, bool)`

GetTotalsOk returns a tuple with the Totals field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotals

`func (o *AiTrafficResponse) SetTotals(v AiTrafficResponseTotals)`

SetTotals sets Totals field to given value.


### GetBySource

`func (o *AiTrafficResponse) GetBySource() []AiTrafficResponseBySourceInner`

GetBySource returns the BySource field if non-nil, zero value otherwise.

### GetBySourceOk

`func (o *AiTrafficResponse) GetBySourceOk() (*[]AiTrafficResponseBySourceInner, bool)`

GetBySourceOk returns a tuple with the BySource field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBySource

`func (o *AiTrafficResponse) SetBySource(v []AiTrafficResponseBySourceInner)`

SetBySource sets BySource field to given value.


### GetTimeseries

`func (o *AiTrafficResponse) GetTimeseries() map[string]map[string]int32`

GetTimeseries returns the Timeseries field if non-nil, zero value otherwise.

### GetTimeseriesOk

`func (o *AiTrafficResponse) GetTimeseriesOk() (*map[string]map[string]int32, bool)`

GetTimeseriesOk returns a tuple with the Timeseries field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimeseries

`func (o *AiTrafficResponse) SetTimeseries(v map[string]map[string]int32)`

SetTimeseries sets Timeseries field to given value.


### GetRequestId

`func (o *AiTrafficResponse) GetRequestId() string`

GetRequestId returns the RequestId field if non-nil, zero value otherwise.

### GetRequestIdOk

`func (o *AiTrafficResponse) GetRequestIdOk() (*string, bool)`

GetRequestIdOk returns a tuple with the RequestId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestId

`func (o *AiTrafficResponse) SetRequestId(v string)`

SetRequestId sets RequestId field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


