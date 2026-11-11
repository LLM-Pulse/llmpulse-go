# AccountPitchQuota

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Limit** | Pointer to **NullableInt32** |  | [optional] 
**Used** | Pointer to **int32** |  | [optional] 
**Remaining** | Pointer to **NullableInt32** |  | [optional] 
**Unlimited** | Pointer to **bool** |  | [optional] 
**Period** | Pointer to **string** | Always month | [optional] 
**ResetsOn** | Pointer to **string** | The first day of next month, when the allowance starts again | [optional] 
**Access** | Pointer to **string** | Whether the account may create pitch projects, which are for agency and platform accounts (the account type, which the account owner or an account admin changes in Account Settings &gt; Profile). none means the account is not an agency; approved access goes dormant while the account is below the Scale tier, on a trial, has a payment problem, is set to cancel or has an allowance of 0; revoked means our team turned it off. pending and rejected are no longer returned | [optional] 

## Methods

### NewAccountPitchQuota

`func NewAccountPitchQuota() *AccountPitchQuota`

NewAccountPitchQuota instantiates a new AccountPitchQuota object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAccountPitchQuotaWithDefaults

`func NewAccountPitchQuotaWithDefaults() *AccountPitchQuota`

NewAccountPitchQuotaWithDefaults instantiates a new AccountPitchQuota object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetLimit

`func (o *AccountPitchQuota) GetLimit() int32`

GetLimit returns the Limit field if non-nil, zero value otherwise.

### GetLimitOk

`func (o *AccountPitchQuota) GetLimitOk() (*int32, bool)`

GetLimitOk returns a tuple with the Limit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLimit

`func (o *AccountPitchQuota) SetLimit(v int32)`

SetLimit sets Limit field to given value.

### HasLimit

`func (o *AccountPitchQuota) HasLimit() bool`

HasLimit returns a boolean if a field has been set.

### SetLimitNil

`func (o *AccountPitchQuota) SetLimitNil(b bool)`

 SetLimitNil sets the value for Limit to be an explicit nil

### UnsetLimit
`func (o *AccountPitchQuota) UnsetLimit()`

UnsetLimit ensures that no value is present for Limit, not even an explicit nil
### GetUsed

`func (o *AccountPitchQuota) GetUsed() int32`

GetUsed returns the Used field if non-nil, zero value otherwise.

### GetUsedOk

`func (o *AccountPitchQuota) GetUsedOk() (*int32, bool)`

GetUsedOk returns a tuple with the Used field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsed

`func (o *AccountPitchQuota) SetUsed(v int32)`

SetUsed sets Used field to given value.

### HasUsed

`func (o *AccountPitchQuota) HasUsed() bool`

HasUsed returns a boolean if a field has been set.

### GetRemaining

`func (o *AccountPitchQuota) GetRemaining() int32`

GetRemaining returns the Remaining field if non-nil, zero value otherwise.

### GetRemainingOk

`func (o *AccountPitchQuota) GetRemainingOk() (*int32, bool)`

GetRemainingOk returns a tuple with the Remaining field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRemaining

`func (o *AccountPitchQuota) SetRemaining(v int32)`

SetRemaining sets Remaining field to given value.

### HasRemaining

`func (o *AccountPitchQuota) HasRemaining() bool`

HasRemaining returns a boolean if a field has been set.

### SetRemainingNil

`func (o *AccountPitchQuota) SetRemainingNil(b bool)`

 SetRemainingNil sets the value for Remaining to be an explicit nil

### UnsetRemaining
`func (o *AccountPitchQuota) UnsetRemaining()`

UnsetRemaining ensures that no value is present for Remaining, not even an explicit nil
### GetUnlimited

`func (o *AccountPitchQuota) GetUnlimited() bool`

GetUnlimited returns the Unlimited field if non-nil, zero value otherwise.

### GetUnlimitedOk

`func (o *AccountPitchQuota) GetUnlimitedOk() (*bool, bool)`

GetUnlimitedOk returns a tuple with the Unlimited field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnlimited

`func (o *AccountPitchQuota) SetUnlimited(v bool)`

SetUnlimited sets Unlimited field to given value.

### HasUnlimited

`func (o *AccountPitchQuota) HasUnlimited() bool`

HasUnlimited returns a boolean if a field has been set.

### GetPeriod

`func (o *AccountPitchQuota) GetPeriod() string`

GetPeriod returns the Period field if non-nil, zero value otherwise.

### GetPeriodOk

`func (o *AccountPitchQuota) GetPeriodOk() (*string, bool)`

GetPeriodOk returns a tuple with the Period field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPeriod

`func (o *AccountPitchQuota) SetPeriod(v string)`

SetPeriod sets Period field to given value.

### HasPeriod

`func (o *AccountPitchQuota) HasPeriod() bool`

HasPeriod returns a boolean if a field has been set.

### GetResetsOn

`func (o *AccountPitchQuota) GetResetsOn() string`

GetResetsOn returns the ResetsOn field if non-nil, zero value otherwise.

### GetResetsOnOk

`func (o *AccountPitchQuota) GetResetsOnOk() (*string, bool)`

GetResetsOnOk returns a tuple with the ResetsOn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResetsOn

`func (o *AccountPitchQuota) SetResetsOn(v string)`

SetResetsOn sets ResetsOn field to given value.

### HasResetsOn

`func (o *AccountPitchQuota) HasResetsOn() bool`

HasResetsOn returns a boolean if a field has been set.

### GetAccess

`func (o *AccountPitchQuota) GetAccess() string`

GetAccess returns the Access field if non-nil, zero value otherwise.

### GetAccessOk

`func (o *AccountPitchQuota) GetAccessOk() (*string, bool)`

GetAccessOk returns a tuple with the Access field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccess

`func (o *AccountPitchQuota) SetAccess(v string)`

SetAccess sets Access field to given value.

### HasAccess

`func (o *AccountPitchQuota) HasAccess() bool`

HasAccess returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


