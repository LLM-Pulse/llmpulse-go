# GetAccount200ResponseSubscription

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Status** | Pointer to **string** |  | [optional] 
**Trialing** | Pointer to **bool** |  | [optional] 
**CurrentPeriodEndsAt** | Pointer to **NullableTime** |  | [optional] 

## Methods

### NewGetAccount200ResponseSubscription

`func NewGetAccount200ResponseSubscription() *GetAccount200ResponseSubscription`

NewGetAccount200ResponseSubscription instantiates a new GetAccount200ResponseSubscription object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGetAccount200ResponseSubscriptionWithDefaults

`func NewGetAccount200ResponseSubscriptionWithDefaults() *GetAccount200ResponseSubscription`

NewGetAccount200ResponseSubscriptionWithDefaults instantiates a new GetAccount200ResponseSubscription object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetStatus

`func (o *GetAccount200ResponseSubscription) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *GetAccount200ResponseSubscription) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *GetAccount200ResponseSubscription) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *GetAccount200ResponseSubscription) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetTrialing

`func (o *GetAccount200ResponseSubscription) GetTrialing() bool`

GetTrialing returns the Trialing field if non-nil, zero value otherwise.

### GetTrialingOk

`func (o *GetAccount200ResponseSubscription) GetTrialingOk() (*bool, bool)`

GetTrialingOk returns a tuple with the Trialing field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrialing

`func (o *GetAccount200ResponseSubscription) SetTrialing(v bool)`

SetTrialing sets Trialing field to given value.

### HasTrialing

`func (o *GetAccount200ResponseSubscription) HasTrialing() bool`

HasTrialing returns a boolean if a field has been set.

### GetCurrentPeriodEndsAt

`func (o *GetAccount200ResponseSubscription) GetCurrentPeriodEndsAt() time.Time`

GetCurrentPeriodEndsAt returns the CurrentPeriodEndsAt field if non-nil, zero value otherwise.

### GetCurrentPeriodEndsAtOk

`func (o *GetAccount200ResponseSubscription) GetCurrentPeriodEndsAtOk() (*time.Time, bool)`

GetCurrentPeriodEndsAtOk returns a tuple with the CurrentPeriodEndsAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrentPeriodEndsAt

`func (o *GetAccount200ResponseSubscription) SetCurrentPeriodEndsAt(v time.Time)`

SetCurrentPeriodEndsAt sets CurrentPeriodEndsAt field to given value.

### HasCurrentPeriodEndsAt

`func (o *GetAccount200ResponseSubscription) HasCurrentPeriodEndsAt() bool`

HasCurrentPeriodEndsAt returns a boolean if a field has been set.

### SetCurrentPeriodEndsAtNil

`func (o *GetAccount200ResponseSubscription) SetCurrentPeriodEndsAtNil(b bool)`

 SetCurrentPeriodEndsAtNil sets the value for CurrentPeriodEndsAt to be an explicit nil

### UnsetCurrentPeriodEndsAt
`func (o *GetAccount200ResponseSubscription) UnsetCurrentPeriodEndsAt()`

UnsetCurrentPeriodEndsAt ensures that no value is present for CurrentPeriodEndsAt, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


