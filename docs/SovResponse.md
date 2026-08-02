# SovResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ProjectId** | Pointer to **int32** |  | [optional] 
**Periods** | Pointer to [**[]SovResponsePeriodsInner**](SovResponsePeriodsInner.md) | Per-bucket sample size and completeness: mentions is the total the shares were computed on (1-3 mentions produce the 100/50/33.33 low-sample patterns); partial marks buckets still collecting data or clipped by the requested window. | [optional] 
**OverTime** | Pointer to [**[]SovResponseOverTimeInner**](SovResponseOverTimeInner.md) |  | [optional] 
**Current** | Pointer to [**[]SovResponseCurrentInner**](SovResponseCurrentInner.md) |  | [optional] 
**Breakdown** | Pointer to [**[]SovResponseBreakdownInner**](SovResponseBreakdownInner.md) |  | [optional] 
**Others** | Pointer to **[]map[string]interface{}** |  | [optional] 

## Methods

### NewSovResponse

`func NewSovResponse() *SovResponse`

NewSovResponse instantiates a new SovResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSovResponseWithDefaults

`func NewSovResponseWithDefaults() *SovResponse`

NewSovResponseWithDefaults instantiates a new SovResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProjectId

`func (o *SovResponse) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *SovResponse) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *SovResponse) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.

### HasProjectId

`func (o *SovResponse) HasProjectId() bool`

HasProjectId returns a boolean if a field has been set.

### GetPeriods

`func (o *SovResponse) GetPeriods() []SovResponsePeriodsInner`

GetPeriods returns the Periods field if non-nil, zero value otherwise.

### GetPeriodsOk

`func (o *SovResponse) GetPeriodsOk() (*[]SovResponsePeriodsInner, bool)`

GetPeriodsOk returns a tuple with the Periods field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPeriods

`func (o *SovResponse) SetPeriods(v []SovResponsePeriodsInner)`

SetPeriods sets Periods field to given value.

### HasPeriods

`func (o *SovResponse) HasPeriods() bool`

HasPeriods returns a boolean if a field has been set.

### GetOverTime

`func (o *SovResponse) GetOverTime() []SovResponseOverTimeInner`

GetOverTime returns the OverTime field if non-nil, zero value otherwise.

### GetOverTimeOk

`func (o *SovResponse) GetOverTimeOk() (*[]SovResponseOverTimeInner, bool)`

GetOverTimeOk returns a tuple with the OverTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOverTime

`func (o *SovResponse) SetOverTime(v []SovResponseOverTimeInner)`

SetOverTime sets OverTime field to given value.

### HasOverTime

`func (o *SovResponse) HasOverTime() bool`

HasOverTime returns a boolean if a field has been set.

### GetCurrent

`func (o *SovResponse) GetCurrent() []SovResponseCurrentInner`

GetCurrent returns the Current field if non-nil, zero value otherwise.

### GetCurrentOk

`func (o *SovResponse) GetCurrentOk() (*[]SovResponseCurrentInner, bool)`

GetCurrentOk returns a tuple with the Current field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrent

`func (o *SovResponse) SetCurrent(v []SovResponseCurrentInner)`

SetCurrent sets Current field to given value.

### HasCurrent

`func (o *SovResponse) HasCurrent() bool`

HasCurrent returns a boolean if a field has been set.

### GetBreakdown

`func (o *SovResponse) GetBreakdown() []SovResponseBreakdownInner`

GetBreakdown returns the Breakdown field if non-nil, zero value otherwise.

### GetBreakdownOk

`func (o *SovResponse) GetBreakdownOk() (*[]SovResponseBreakdownInner, bool)`

GetBreakdownOk returns a tuple with the Breakdown field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBreakdown

`func (o *SovResponse) SetBreakdown(v []SovResponseBreakdownInner)`

SetBreakdown sets Breakdown field to given value.

### HasBreakdown

`func (o *SovResponse) HasBreakdown() bool`

HasBreakdown returns a boolean if a field has been set.

### GetOthers

`func (o *SovResponse) GetOthers() []map[string]interface{}`

GetOthers returns the Others field if non-nil, zero value otherwise.

### GetOthersOk

`func (o *SovResponse) GetOthersOk() (*[]map[string]interface{}, bool)`

GetOthersOk returns a tuple with the Others field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOthers

`func (o *SovResponse) SetOthers(v []map[string]interface{})`

SetOthers sets Others field to given value.

### HasOthers

`func (o *SovResponse) HasOthers() bool`

HasOthers returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


