# AccountQuota

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Limit** | Pointer to **NullableInt32** |  | [optional] 
**Used** | Pointer to **int32** |  | [optional] 
**Remaining** | Pointer to **NullableInt32** |  | [optional] 
**Unlimited** | Pointer to **bool** |  | [optional] 
**Period** | Pointer to **string** | Reset window for quotas that reset (e.g. month) | [optional] 

## Methods

### NewAccountQuota

`func NewAccountQuota() *AccountQuota`

NewAccountQuota instantiates a new AccountQuota object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAccountQuotaWithDefaults

`func NewAccountQuotaWithDefaults() *AccountQuota`

NewAccountQuotaWithDefaults instantiates a new AccountQuota object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetLimit

`func (o *AccountQuota) GetLimit() int32`

GetLimit returns the Limit field if non-nil, zero value otherwise.

### GetLimitOk

`func (o *AccountQuota) GetLimitOk() (*int32, bool)`

GetLimitOk returns a tuple with the Limit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLimit

`func (o *AccountQuota) SetLimit(v int32)`

SetLimit sets Limit field to given value.

### HasLimit

`func (o *AccountQuota) HasLimit() bool`

HasLimit returns a boolean if a field has been set.

### SetLimitNil

`func (o *AccountQuota) SetLimitNil(b bool)`

 SetLimitNil sets the value for Limit to be an explicit nil

### UnsetLimit
`func (o *AccountQuota) UnsetLimit()`

UnsetLimit ensures that no value is present for Limit, not even an explicit nil
### GetUsed

`func (o *AccountQuota) GetUsed() int32`

GetUsed returns the Used field if non-nil, zero value otherwise.

### GetUsedOk

`func (o *AccountQuota) GetUsedOk() (*int32, bool)`

GetUsedOk returns a tuple with the Used field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsed

`func (o *AccountQuota) SetUsed(v int32)`

SetUsed sets Used field to given value.

### HasUsed

`func (o *AccountQuota) HasUsed() bool`

HasUsed returns a boolean if a field has been set.

### GetRemaining

`func (o *AccountQuota) GetRemaining() int32`

GetRemaining returns the Remaining field if non-nil, zero value otherwise.

### GetRemainingOk

`func (o *AccountQuota) GetRemainingOk() (*int32, bool)`

GetRemainingOk returns a tuple with the Remaining field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRemaining

`func (o *AccountQuota) SetRemaining(v int32)`

SetRemaining sets Remaining field to given value.

### HasRemaining

`func (o *AccountQuota) HasRemaining() bool`

HasRemaining returns a boolean if a field has been set.

### SetRemainingNil

`func (o *AccountQuota) SetRemainingNil(b bool)`

 SetRemainingNil sets the value for Remaining to be an explicit nil

### UnsetRemaining
`func (o *AccountQuota) UnsetRemaining()`

UnsetRemaining ensures that no value is present for Remaining, not even an explicit nil
### GetUnlimited

`func (o *AccountQuota) GetUnlimited() bool`

GetUnlimited returns the Unlimited field if non-nil, zero value otherwise.

### GetUnlimitedOk

`func (o *AccountQuota) GetUnlimitedOk() (*bool, bool)`

GetUnlimitedOk returns a tuple with the Unlimited field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnlimited

`func (o *AccountQuota) SetUnlimited(v bool)`

SetUnlimited sets Unlimited field to given value.

### HasUnlimited

`func (o *AccountQuota) HasUnlimited() bool`

HasUnlimited returns a boolean if a field has been set.

### GetPeriod

`func (o *AccountQuota) GetPeriod() string`

GetPeriod returns the Period field if non-nil, zero value otherwise.

### GetPeriodOk

`func (o *AccountQuota) GetPeriodOk() (*string, bool)`

GetPeriodOk returns a tuple with the Period field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPeriod

`func (o *AccountQuota) SetPeriod(v string)`

SetPeriod sets Period field to given value.

### HasPeriod

`func (o *AccountQuota) HasPeriod() bool`

HasPeriod returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


