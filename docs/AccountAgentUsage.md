# AccountAgentUsage

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**PercentUsed** | Pointer to **NullableInt32** | Whole percent used, rounded down, from 0 to 100; 100 means the allowance is spent and new questions wait until resets_on. null when unlimited is true | [optional] 
**Unlimited** | Pointer to **bool** |  | [optional] 
**Included** | Pointer to **bool** | Whether the plan includes the in-app AI assistant. false on a plan without it, where percent_used is 100 | [optional] 
**Period** | Pointer to **string** | Always month | [optional] 
**ResetsOn** | Pointer to **string** | The first day of next month, when the allowance starts again | [optional] 

## Methods

### NewAccountAgentUsage

`func NewAccountAgentUsage() *AccountAgentUsage`

NewAccountAgentUsage instantiates a new AccountAgentUsage object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAccountAgentUsageWithDefaults

`func NewAccountAgentUsageWithDefaults() *AccountAgentUsage`

NewAccountAgentUsageWithDefaults instantiates a new AccountAgentUsage object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPercentUsed

`func (o *AccountAgentUsage) GetPercentUsed() int32`

GetPercentUsed returns the PercentUsed field if non-nil, zero value otherwise.

### GetPercentUsedOk

`func (o *AccountAgentUsage) GetPercentUsedOk() (*int32, bool)`

GetPercentUsedOk returns a tuple with the PercentUsed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPercentUsed

`func (o *AccountAgentUsage) SetPercentUsed(v int32)`

SetPercentUsed sets PercentUsed field to given value.

### HasPercentUsed

`func (o *AccountAgentUsage) HasPercentUsed() bool`

HasPercentUsed returns a boolean if a field has been set.

### SetPercentUsedNil

`func (o *AccountAgentUsage) SetPercentUsedNil(b bool)`

 SetPercentUsedNil sets the value for PercentUsed to be an explicit nil

### UnsetPercentUsed
`func (o *AccountAgentUsage) UnsetPercentUsed()`

UnsetPercentUsed ensures that no value is present for PercentUsed, not even an explicit nil
### GetUnlimited

`func (o *AccountAgentUsage) GetUnlimited() bool`

GetUnlimited returns the Unlimited field if non-nil, zero value otherwise.

### GetUnlimitedOk

`func (o *AccountAgentUsage) GetUnlimitedOk() (*bool, bool)`

GetUnlimitedOk returns a tuple with the Unlimited field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnlimited

`func (o *AccountAgentUsage) SetUnlimited(v bool)`

SetUnlimited sets Unlimited field to given value.

### HasUnlimited

`func (o *AccountAgentUsage) HasUnlimited() bool`

HasUnlimited returns a boolean if a field has been set.

### GetIncluded

`func (o *AccountAgentUsage) GetIncluded() bool`

GetIncluded returns the Included field if non-nil, zero value otherwise.

### GetIncludedOk

`func (o *AccountAgentUsage) GetIncludedOk() (*bool, bool)`

GetIncludedOk returns a tuple with the Included field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIncluded

`func (o *AccountAgentUsage) SetIncluded(v bool)`

SetIncluded sets Included field to given value.

### HasIncluded

`func (o *AccountAgentUsage) HasIncluded() bool`

HasIncluded returns a boolean if a field has been set.

### GetPeriod

`func (o *AccountAgentUsage) GetPeriod() string`

GetPeriod returns the Period field if non-nil, zero value otherwise.

### GetPeriodOk

`func (o *AccountAgentUsage) GetPeriodOk() (*string, bool)`

GetPeriodOk returns a tuple with the Period field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPeriod

`func (o *AccountAgentUsage) SetPeriod(v string)`

SetPeriod sets Period field to given value.

### HasPeriod

`func (o *AccountAgentUsage) HasPeriod() bool`

HasPeriod returns a boolean if a field has been set.

### GetResetsOn

`func (o *AccountAgentUsage) GetResetsOn() string`

GetResetsOn returns the ResetsOn field if non-nil, zero value otherwise.

### GetResetsOnOk

`func (o *AccountAgentUsage) GetResetsOnOk() (*string, bool)`

GetResetsOnOk returns a tuple with the ResetsOn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResetsOn

`func (o *AccountAgentUsage) SetResetsOn(v string)`

SetResetsOn sets ResetsOn field to given value.

### HasResetsOn

`func (o *AccountAgentUsage) HasResetsOn() bool`

HasResetsOn returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


