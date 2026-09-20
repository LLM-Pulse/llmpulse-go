# AccountCapacity

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Limit** | Pointer to **NullableInt32** |  | [optional] 
**Unlimited** | Pointer to **bool** |  | [optional] 

## Methods

### NewAccountCapacity

`func NewAccountCapacity() *AccountCapacity`

NewAccountCapacity instantiates a new AccountCapacity object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAccountCapacityWithDefaults

`func NewAccountCapacityWithDefaults() *AccountCapacity`

NewAccountCapacityWithDefaults instantiates a new AccountCapacity object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetLimit

`func (o *AccountCapacity) GetLimit() int32`

GetLimit returns the Limit field if non-nil, zero value otherwise.

### GetLimitOk

`func (o *AccountCapacity) GetLimitOk() (*int32, bool)`

GetLimitOk returns a tuple with the Limit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLimit

`func (o *AccountCapacity) SetLimit(v int32)`

SetLimit sets Limit field to given value.

### HasLimit

`func (o *AccountCapacity) HasLimit() bool`

HasLimit returns a boolean if a field has been set.

### SetLimitNil

`func (o *AccountCapacity) SetLimitNil(b bool)`

 SetLimitNil sets the value for Limit to be an explicit nil

### UnsetLimit
`func (o *AccountCapacity) UnsetLimit()`

UnsetLimit ensures that no value is present for Limit, not even an explicit nil
### GetUnlimited

`func (o *AccountCapacity) GetUnlimited() bool`

GetUnlimited returns the Unlimited field if non-nil, zero value otherwise.

### GetUnlimitedOk

`func (o *AccountCapacity) GetUnlimitedOk() (*bool, bool)`

GetUnlimitedOk returns a tuple with the Unlimited field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnlimited

`func (o *AccountCapacity) SetUnlimited(v bool)`

SetUnlimited sets Unlimited field to given value.

### HasUnlimited

`func (o *AccountCapacity) HasUnlimited() bool`

HasUnlimited returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


