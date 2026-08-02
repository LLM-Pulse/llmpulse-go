# SummaryResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ProjectId** | Pointer to **int32** |  | [optional] 
**From** | Pointer to **time.Time** |  | [optional] 
**To** | Pointer to **time.Time** |  | [optional] 
**Granularity** | Pointer to **string** |  | [optional] 
**Filters** | Pointer to **map[string]interface{}** |  | [optional] 
**Series** | Pointer to [**map[string][]TimeseriesSeries**](array.md) |  | [optional] 
**RequestId** | Pointer to **string** |  | [optional] 
**Summary** | Pointer to [**map[string][]SummaryResponseAllOfSummaryValueInner**](array.md) |  | [optional] 
**PositionDistribution** | Pointer to [**SummaryResponseAllOfPositionDistribution**](SummaryResponseAllOfPositionDistribution.md) |  | [optional] 

## Methods

### NewSummaryResponse

`func NewSummaryResponse() *SummaryResponse`

NewSummaryResponse instantiates a new SummaryResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSummaryResponseWithDefaults

`func NewSummaryResponseWithDefaults() *SummaryResponse`

NewSummaryResponseWithDefaults instantiates a new SummaryResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProjectId

`func (o *SummaryResponse) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *SummaryResponse) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *SummaryResponse) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.

### HasProjectId

`func (o *SummaryResponse) HasProjectId() bool`

HasProjectId returns a boolean if a field has been set.

### GetFrom

`func (o *SummaryResponse) GetFrom() time.Time`

GetFrom returns the From field if non-nil, zero value otherwise.

### GetFromOk

`func (o *SummaryResponse) GetFromOk() (*time.Time, bool)`

GetFromOk returns a tuple with the From field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFrom

`func (o *SummaryResponse) SetFrom(v time.Time)`

SetFrom sets From field to given value.

### HasFrom

`func (o *SummaryResponse) HasFrom() bool`

HasFrom returns a boolean if a field has been set.

### GetTo

`func (o *SummaryResponse) GetTo() time.Time`

GetTo returns the To field if non-nil, zero value otherwise.

### GetToOk

`func (o *SummaryResponse) GetToOk() (*time.Time, bool)`

GetToOk returns a tuple with the To field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTo

`func (o *SummaryResponse) SetTo(v time.Time)`

SetTo sets To field to given value.

### HasTo

`func (o *SummaryResponse) HasTo() bool`

HasTo returns a boolean if a field has been set.

### GetGranularity

`func (o *SummaryResponse) GetGranularity() string`

GetGranularity returns the Granularity field if non-nil, zero value otherwise.

### GetGranularityOk

`func (o *SummaryResponse) GetGranularityOk() (*string, bool)`

GetGranularityOk returns a tuple with the Granularity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGranularity

`func (o *SummaryResponse) SetGranularity(v string)`

SetGranularity sets Granularity field to given value.

### HasGranularity

`func (o *SummaryResponse) HasGranularity() bool`

HasGranularity returns a boolean if a field has been set.

### GetFilters

`func (o *SummaryResponse) GetFilters() map[string]interface{}`

GetFilters returns the Filters field if non-nil, zero value otherwise.

### GetFiltersOk

`func (o *SummaryResponse) GetFiltersOk() (*map[string]interface{}, bool)`

GetFiltersOk returns a tuple with the Filters field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFilters

`func (o *SummaryResponse) SetFilters(v map[string]interface{})`

SetFilters sets Filters field to given value.

### HasFilters

`func (o *SummaryResponse) HasFilters() bool`

HasFilters returns a boolean if a field has been set.

### GetSeries

`func (o *SummaryResponse) GetSeries() map[string][]TimeseriesSeries`

GetSeries returns the Series field if non-nil, zero value otherwise.

### GetSeriesOk

`func (o *SummaryResponse) GetSeriesOk() (*map[string][]TimeseriesSeries, bool)`

GetSeriesOk returns a tuple with the Series field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSeries

`func (o *SummaryResponse) SetSeries(v map[string][]TimeseriesSeries)`

SetSeries sets Series field to given value.

### HasSeries

`func (o *SummaryResponse) HasSeries() bool`

HasSeries returns a boolean if a field has been set.

### GetRequestId

`func (o *SummaryResponse) GetRequestId() string`

GetRequestId returns the RequestId field if non-nil, zero value otherwise.

### GetRequestIdOk

`func (o *SummaryResponse) GetRequestIdOk() (*string, bool)`

GetRequestIdOk returns a tuple with the RequestId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestId

`func (o *SummaryResponse) SetRequestId(v string)`

SetRequestId sets RequestId field to given value.

### HasRequestId

`func (o *SummaryResponse) HasRequestId() bool`

HasRequestId returns a boolean if a field has been set.

### GetSummary

`func (o *SummaryResponse) GetSummary() map[string][]SummaryResponseAllOfSummaryValueInner`

GetSummary returns the Summary field if non-nil, zero value otherwise.

### GetSummaryOk

`func (o *SummaryResponse) GetSummaryOk() (*map[string][]SummaryResponseAllOfSummaryValueInner, bool)`

GetSummaryOk returns a tuple with the Summary field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSummary

`func (o *SummaryResponse) SetSummary(v map[string][]SummaryResponseAllOfSummaryValueInner)`

SetSummary sets Summary field to given value.

### HasSummary

`func (o *SummaryResponse) HasSummary() bool`

HasSummary returns a boolean if a field has been set.

### GetPositionDistribution

`func (o *SummaryResponse) GetPositionDistribution() SummaryResponseAllOfPositionDistribution`

GetPositionDistribution returns the PositionDistribution field if non-nil, zero value otherwise.

### GetPositionDistributionOk

`func (o *SummaryResponse) GetPositionDistributionOk() (*SummaryResponseAllOfPositionDistribution, bool)`

GetPositionDistributionOk returns a tuple with the PositionDistribution field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPositionDistribution

`func (o *SummaryResponse) SetPositionDistribution(v SummaryResponseAllOfPositionDistribution)`

SetPositionDistribution sets PositionDistribution field to given value.

### HasPositionDistribution

`func (o *SummaryResponse) HasPositionDistribution() bool`

HasPositionDistribution returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


