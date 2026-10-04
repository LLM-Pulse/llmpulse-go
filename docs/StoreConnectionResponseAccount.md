# StoreConnectionResponseAccount

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Plan** | Pointer to **NullableString** | Internal plan key of the account, e.g. scale or scaleplus; null for a key limited to some projects | [optional] 

## Methods

### NewStoreConnectionResponseAccount

`func NewStoreConnectionResponseAccount() *StoreConnectionResponseAccount`

NewStoreConnectionResponseAccount instantiates a new StoreConnectionResponseAccount object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewStoreConnectionResponseAccountWithDefaults

`func NewStoreConnectionResponseAccountWithDefaults() *StoreConnectionResponseAccount`

NewStoreConnectionResponseAccountWithDefaults instantiates a new StoreConnectionResponseAccount object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPlan

`func (o *StoreConnectionResponseAccount) GetPlan() string`

GetPlan returns the Plan field if non-nil, zero value otherwise.

### GetPlanOk

`func (o *StoreConnectionResponseAccount) GetPlanOk() (*string, bool)`

GetPlanOk returns a tuple with the Plan field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlan

`func (o *StoreConnectionResponseAccount) SetPlan(v string)`

SetPlan sets Plan field to given value.

### HasPlan

`func (o *StoreConnectionResponseAccount) HasPlan() bool`

HasPlan returns a boolean if a field has been set.

### SetPlanNil

`func (o *StoreConnectionResponseAccount) SetPlanNil(b bool)`

 SetPlanNil sets the value for Plan to be an explicit nil

### UnsetPlan
`func (o *StoreConnectionResponseAccount) UnsetPlan()`

UnsetPlan ensures that no value is present for Plan, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


