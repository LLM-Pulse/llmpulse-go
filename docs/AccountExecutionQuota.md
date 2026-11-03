# AccountExecutionQuota

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Limit** | Pointer to **NullableInt32** |  | [optional] 
**Used** | Pointer to **int32** |  | [optional] 
**Remaining** | Pointer to **NullableInt32** |  | [optional] 
**Unlimited** | Pointer to **bool** |  | [optional] 
**Period** | Pointer to **string** | The tracking window, from the account&#39;s tracking cadence (week runs Monday to Sunday) | [optional] 
**ResetsAt** | Pointer to **time.Time** | When the next window starts and the allowance is full again (00:00 Europe/Madrid) | [optional] 

## Methods

### NewAccountExecutionQuota

`func NewAccountExecutionQuota() *AccountExecutionQuota`

NewAccountExecutionQuota instantiates a new AccountExecutionQuota object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAccountExecutionQuotaWithDefaults

`func NewAccountExecutionQuotaWithDefaults() *AccountExecutionQuota`

NewAccountExecutionQuotaWithDefaults instantiates a new AccountExecutionQuota object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetLimit

`func (o *AccountExecutionQuota) GetLimit() int32`

GetLimit returns the Limit field if non-nil, zero value otherwise.

### GetLimitOk

`func (o *AccountExecutionQuota) GetLimitOk() (*int32, bool)`

GetLimitOk returns a tuple with the Limit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLimit

`func (o *AccountExecutionQuota) SetLimit(v int32)`

SetLimit sets Limit field to given value.

### HasLimit

`func (o *AccountExecutionQuota) HasLimit() bool`

HasLimit returns a boolean if a field has been set.

### SetLimitNil

`func (o *AccountExecutionQuota) SetLimitNil(b bool)`

 SetLimitNil sets the value for Limit to be an explicit nil

### UnsetLimit
`func (o *AccountExecutionQuota) UnsetLimit()`

UnsetLimit ensures that no value is present for Limit, not even an explicit nil
### GetUsed

`func (o *AccountExecutionQuota) GetUsed() int32`

GetUsed returns the Used field if non-nil, zero value otherwise.

### GetUsedOk

`func (o *AccountExecutionQuota) GetUsedOk() (*int32, bool)`

GetUsedOk returns a tuple with the Used field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsed

`func (o *AccountExecutionQuota) SetUsed(v int32)`

SetUsed sets Used field to given value.

### HasUsed

`func (o *AccountExecutionQuota) HasUsed() bool`

HasUsed returns a boolean if a field has been set.

### GetRemaining

`func (o *AccountExecutionQuota) GetRemaining() int32`

GetRemaining returns the Remaining field if non-nil, zero value otherwise.

### GetRemainingOk

`func (o *AccountExecutionQuota) GetRemainingOk() (*int32, bool)`

GetRemainingOk returns a tuple with the Remaining field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRemaining

`func (o *AccountExecutionQuota) SetRemaining(v int32)`

SetRemaining sets Remaining field to given value.

### HasRemaining

`func (o *AccountExecutionQuota) HasRemaining() bool`

HasRemaining returns a boolean if a field has been set.

### SetRemainingNil

`func (o *AccountExecutionQuota) SetRemainingNil(b bool)`

 SetRemainingNil sets the value for Remaining to be an explicit nil

### UnsetRemaining
`func (o *AccountExecutionQuota) UnsetRemaining()`

UnsetRemaining ensures that no value is present for Remaining, not even an explicit nil
### GetUnlimited

`func (o *AccountExecutionQuota) GetUnlimited() bool`

GetUnlimited returns the Unlimited field if non-nil, zero value otherwise.

### GetUnlimitedOk

`func (o *AccountExecutionQuota) GetUnlimitedOk() (*bool, bool)`

GetUnlimitedOk returns a tuple with the Unlimited field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnlimited

`func (o *AccountExecutionQuota) SetUnlimited(v bool)`

SetUnlimited sets Unlimited field to given value.

### HasUnlimited

`func (o *AccountExecutionQuota) HasUnlimited() bool`

HasUnlimited returns a boolean if a field has been set.

### GetPeriod

`func (o *AccountExecutionQuota) GetPeriod() string`

GetPeriod returns the Period field if non-nil, zero value otherwise.

### GetPeriodOk

`func (o *AccountExecutionQuota) GetPeriodOk() (*string, bool)`

GetPeriodOk returns a tuple with the Period field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPeriod

`func (o *AccountExecutionQuota) SetPeriod(v string)`

SetPeriod sets Period field to given value.

### HasPeriod

`func (o *AccountExecutionQuota) HasPeriod() bool`

HasPeriod returns a boolean if a field has been set.

### GetResetsAt

`func (o *AccountExecutionQuota) GetResetsAt() time.Time`

GetResetsAt returns the ResetsAt field if non-nil, zero value otherwise.

### GetResetsAtOk

`func (o *AccountExecutionQuota) GetResetsAtOk() (*time.Time, bool)`

GetResetsAtOk returns a tuple with the ResetsAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResetsAt

`func (o *AccountExecutionQuota) SetResetsAt(v time.Time)`

SetResetsAt sets ResetsAt field to given value.

### HasResetsAt

`func (o *AccountExecutionQuota) HasResetsAt() bool`

HasResetsAt returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


