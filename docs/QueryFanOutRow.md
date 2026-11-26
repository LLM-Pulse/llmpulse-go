# QueryFanOutRow

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**QueryText** | Pointer to **string** | The sub-query a model issued (view&#x3D;query) | [optional] 
**Count** | Pointer to **int32** | Times it was issued (view&#x3D;query) | [optional] 
**Share** | Pointer to **float32** | Share of all sub-query occurrences, on a 0-100 scale (view&#x3D;query) | [optional] 
**PromptId** | Pointer to **int32** | view&#x3D;prompt | [optional] 
**PromptText** | Pointer to **string** | view&#x3D;prompt | [optional] 
**VariationsCount** | Pointer to **int32** | Distinct sub-queries issued for the prompt (view&#x3D;prompt) | [optional] 
**TotalCount** | Pointer to **int32** | Sub-queries issued for the prompt, repeats included (view&#x3D;prompt) | [optional] 

## Methods

### NewQueryFanOutRow

`func NewQueryFanOutRow() *QueryFanOutRow`

NewQueryFanOutRow instantiates a new QueryFanOutRow object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewQueryFanOutRowWithDefaults

`func NewQueryFanOutRowWithDefaults() *QueryFanOutRow`

NewQueryFanOutRowWithDefaults instantiates a new QueryFanOutRow object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetQueryText

`func (o *QueryFanOutRow) GetQueryText() string`

GetQueryText returns the QueryText field if non-nil, zero value otherwise.

### GetQueryTextOk

`func (o *QueryFanOutRow) GetQueryTextOk() (*string, bool)`

GetQueryTextOk returns a tuple with the QueryText field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQueryText

`func (o *QueryFanOutRow) SetQueryText(v string)`

SetQueryText sets QueryText field to given value.

### HasQueryText

`func (o *QueryFanOutRow) HasQueryText() bool`

HasQueryText returns a boolean if a field has been set.

### GetCount

`func (o *QueryFanOutRow) GetCount() int32`

GetCount returns the Count field if non-nil, zero value otherwise.

### GetCountOk

`func (o *QueryFanOutRow) GetCountOk() (*int32, bool)`

GetCountOk returns a tuple with the Count field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCount

`func (o *QueryFanOutRow) SetCount(v int32)`

SetCount sets Count field to given value.

### HasCount

`func (o *QueryFanOutRow) HasCount() bool`

HasCount returns a boolean if a field has been set.

### GetShare

`func (o *QueryFanOutRow) GetShare() float32`

GetShare returns the Share field if non-nil, zero value otherwise.

### GetShareOk

`func (o *QueryFanOutRow) GetShareOk() (*float32, bool)`

GetShareOk returns a tuple with the Share field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShare

`func (o *QueryFanOutRow) SetShare(v float32)`

SetShare sets Share field to given value.

### HasShare

`func (o *QueryFanOutRow) HasShare() bool`

HasShare returns a boolean if a field has been set.

### GetPromptId

`func (o *QueryFanOutRow) GetPromptId() int32`

GetPromptId returns the PromptId field if non-nil, zero value otherwise.

### GetPromptIdOk

`func (o *QueryFanOutRow) GetPromptIdOk() (*int32, bool)`

GetPromptIdOk returns a tuple with the PromptId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPromptId

`func (o *QueryFanOutRow) SetPromptId(v int32)`

SetPromptId sets PromptId field to given value.

### HasPromptId

`func (o *QueryFanOutRow) HasPromptId() bool`

HasPromptId returns a boolean if a field has been set.

### GetPromptText

`func (o *QueryFanOutRow) GetPromptText() string`

GetPromptText returns the PromptText field if non-nil, zero value otherwise.

### GetPromptTextOk

`func (o *QueryFanOutRow) GetPromptTextOk() (*string, bool)`

GetPromptTextOk returns a tuple with the PromptText field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPromptText

`func (o *QueryFanOutRow) SetPromptText(v string)`

SetPromptText sets PromptText field to given value.

### HasPromptText

`func (o *QueryFanOutRow) HasPromptText() bool`

HasPromptText returns a boolean if a field has been set.

### GetVariationsCount

`func (o *QueryFanOutRow) GetVariationsCount() int32`

GetVariationsCount returns the VariationsCount field if non-nil, zero value otherwise.

### GetVariationsCountOk

`func (o *QueryFanOutRow) GetVariationsCountOk() (*int32, bool)`

GetVariationsCountOk returns a tuple with the VariationsCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVariationsCount

`func (o *QueryFanOutRow) SetVariationsCount(v int32)`

SetVariationsCount sets VariationsCount field to given value.

### HasVariationsCount

`func (o *QueryFanOutRow) HasVariationsCount() bool`

HasVariationsCount returns a boolean if a field has been set.

### GetTotalCount

`func (o *QueryFanOutRow) GetTotalCount() int32`

GetTotalCount returns the TotalCount field if non-nil, zero value otherwise.

### GetTotalCountOk

`func (o *QueryFanOutRow) GetTotalCountOk() (*int32, bool)`

GetTotalCountOk returns a tuple with the TotalCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalCount

`func (o *QueryFanOutRow) SetTotalCount(v int32)`

SetTotalCount sets TotalCount field to given value.

### HasTotalCount

`func (o *QueryFanOutRow) HasTotalCount() bool`

HasTotalCount returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


