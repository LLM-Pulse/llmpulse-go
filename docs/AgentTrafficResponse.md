# AgentTrafficResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ProjectId** | Pointer to **int32** |  | [optional] 
**From** | Pointer to **string** |  | [optional] 
**To** | Pointer to **string** |  | [optional] 
**GroupBy** | Pointer to **string** |  | [optional] 
**Granularity** | Pointer to **string** |  | [optional] 
**Totals** | Pointer to **map[string]int32** |  | [optional] 
**Timeseries** | Pointer to **map[string]map[string]int32** |  | [optional] 
**RequestId** | Pointer to **string** |  | [optional] 

## Methods

### NewAgentTrafficResponse

`func NewAgentTrafficResponse() *AgentTrafficResponse`

NewAgentTrafficResponse instantiates a new AgentTrafficResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAgentTrafficResponseWithDefaults

`func NewAgentTrafficResponseWithDefaults() *AgentTrafficResponse`

NewAgentTrafficResponseWithDefaults instantiates a new AgentTrafficResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProjectId

`func (o *AgentTrafficResponse) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *AgentTrafficResponse) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *AgentTrafficResponse) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.

### HasProjectId

`func (o *AgentTrafficResponse) HasProjectId() bool`

HasProjectId returns a boolean if a field has been set.

### GetFrom

`func (o *AgentTrafficResponse) GetFrom() string`

GetFrom returns the From field if non-nil, zero value otherwise.

### GetFromOk

`func (o *AgentTrafficResponse) GetFromOk() (*string, bool)`

GetFromOk returns a tuple with the From field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFrom

`func (o *AgentTrafficResponse) SetFrom(v string)`

SetFrom sets From field to given value.

### HasFrom

`func (o *AgentTrafficResponse) HasFrom() bool`

HasFrom returns a boolean if a field has been set.

### GetTo

`func (o *AgentTrafficResponse) GetTo() string`

GetTo returns the To field if non-nil, zero value otherwise.

### GetToOk

`func (o *AgentTrafficResponse) GetToOk() (*string, bool)`

GetToOk returns a tuple with the To field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTo

`func (o *AgentTrafficResponse) SetTo(v string)`

SetTo sets To field to given value.

### HasTo

`func (o *AgentTrafficResponse) HasTo() bool`

HasTo returns a boolean if a field has been set.

### GetGroupBy

`func (o *AgentTrafficResponse) GetGroupBy() string`

GetGroupBy returns the GroupBy field if non-nil, zero value otherwise.

### GetGroupByOk

`func (o *AgentTrafficResponse) GetGroupByOk() (*string, bool)`

GetGroupByOk returns a tuple with the GroupBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGroupBy

`func (o *AgentTrafficResponse) SetGroupBy(v string)`

SetGroupBy sets GroupBy field to given value.

### HasGroupBy

`func (o *AgentTrafficResponse) HasGroupBy() bool`

HasGroupBy returns a boolean if a field has been set.

### GetGranularity

`func (o *AgentTrafficResponse) GetGranularity() string`

GetGranularity returns the Granularity field if non-nil, zero value otherwise.

### GetGranularityOk

`func (o *AgentTrafficResponse) GetGranularityOk() (*string, bool)`

GetGranularityOk returns a tuple with the Granularity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGranularity

`func (o *AgentTrafficResponse) SetGranularity(v string)`

SetGranularity sets Granularity field to given value.

### HasGranularity

`func (o *AgentTrafficResponse) HasGranularity() bool`

HasGranularity returns a boolean if a field has been set.

### GetTotals

`func (o *AgentTrafficResponse) GetTotals() map[string]int32`

GetTotals returns the Totals field if non-nil, zero value otherwise.

### GetTotalsOk

`func (o *AgentTrafficResponse) GetTotalsOk() (*map[string]int32, bool)`

GetTotalsOk returns a tuple with the Totals field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotals

`func (o *AgentTrafficResponse) SetTotals(v map[string]int32)`

SetTotals sets Totals field to given value.

### HasTotals

`func (o *AgentTrafficResponse) HasTotals() bool`

HasTotals returns a boolean if a field has been set.

### GetTimeseries

`func (o *AgentTrafficResponse) GetTimeseries() map[string]map[string]int32`

GetTimeseries returns the Timeseries field if non-nil, zero value otherwise.

### GetTimeseriesOk

`func (o *AgentTrafficResponse) GetTimeseriesOk() (*map[string]map[string]int32, bool)`

GetTimeseriesOk returns a tuple with the Timeseries field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimeseries

`func (o *AgentTrafficResponse) SetTimeseries(v map[string]map[string]int32)`

SetTimeseries sets Timeseries field to given value.

### HasTimeseries

`func (o *AgentTrafficResponse) HasTimeseries() bool`

HasTimeseries returns a boolean if a field has been set.

### GetRequestId

`func (o *AgentTrafficResponse) GetRequestId() string`

GetRequestId returns the RequestId field if non-nil, zero value otherwise.

### GetRequestIdOk

`func (o *AgentTrafficResponse) GetRequestIdOk() (*string, bool)`

GetRequestIdOk returns a tuple with the RequestId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestId

`func (o *AgentTrafficResponse) SetRequestId(v string)`

SetRequestId sets RequestId field to given value.

### HasRequestId

`func (o *AgentTrafficResponse) HasRequestId() bool`

HasRequestId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


