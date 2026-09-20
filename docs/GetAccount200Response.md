# GetAccount200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Plan** | Pointer to **string** | Plan key (starter, growth, scale, ...) | [optional] 
**TrackingFrequency** | Pointer to **string** | How often prompts run (weekly, daily, monthly, ...) | [optional] 
**Role** | Pointer to **string** | Whether the key belongs to the account owner or a team member | [optional] 
**Subscription** | Pointer to [**GetAccount200ResponseSubscription**](GetAccount200ResponseSubscription.md) |  | [optional] 
**Limits** | Pointer to [**GetAccount200ResponseLimits**](GetAccount200ResponseLimits.md) |  | [optional] 
**RateLimits** | Pointer to [**GetAccount200ResponseRateLimits**](GetAccount200ResponseRateLimits.md) |  | [optional] 
**RequestId** | Pointer to **string** |  | [optional] 

## Methods

### NewGetAccount200Response

`func NewGetAccount200Response() *GetAccount200Response`

NewGetAccount200Response instantiates a new GetAccount200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGetAccount200ResponseWithDefaults

`func NewGetAccount200ResponseWithDefaults() *GetAccount200Response`

NewGetAccount200ResponseWithDefaults instantiates a new GetAccount200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPlan

`func (o *GetAccount200Response) GetPlan() string`

GetPlan returns the Plan field if non-nil, zero value otherwise.

### GetPlanOk

`func (o *GetAccount200Response) GetPlanOk() (*string, bool)`

GetPlanOk returns a tuple with the Plan field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlan

`func (o *GetAccount200Response) SetPlan(v string)`

SetPlan sets Plan field to given value.

### HasPlan

`func (o *GetAccount200Response) HasPlan() bool`

HasPlan returns a boolean if a field has been set.

### GetTrackingFrequency

`func (o *GetAccount200Response) GetTrackingFrequency() string`

GetTrackingFrequency returns the TrackingFrequency field if non-nil, zero value otherwise.

### GetTrackingFrequencyOk

`func (o *GetAccount200Response) GetTrackingFrequencyOk() (*string, bool)`

GetTrackingFrequencyOk returns a tuple with the TrackingFrequency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrackingFrequency

`func (o *GetAccount200Response) SetTrackingFrequency(v string)`

SetTrackingFrequency sets TrackingFrequency field to given value.

### HasTrackingFrequency

`func (o *GetAccount200Response) HasTrackingFrequency() bool`

HasTrackingFrequency returns a boolean if a field has been set.

### GetRole

`func (o *GetAccount200Response) GetRole() string`

GetRole returns the Role field if non-nil, zero value otherwise.

### GetRoleOk

`func (o *GetAccount200Response) GetRoleOk() (*string, bool)`

GetRoleOk returns a tuple with the Role field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRole

`func (o *GetAccount200Response) SetRole(v string)`

SetRole sets Role field to given value.

### HasRole

`func (o *GetAccount200Response) HasRole() bool`

HasRole returns a boolean if a field has been set.

### GetSubscription

`func (o *GetAccount200Response) GetSubscription() GetAccount200ResponseSubscription`

GetSubscription returns the Subscription field if non-nil, zero value otherwise.

### GetSubscriptionOk

`func (o *GetAccount200Response) GetSubscriptionOk() (*GetAccount200ResponseSubscription, bool)`

GetSubscriptionOk returns a tuple with the Subscription field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubscription

`func (o *GetAccount200Response) SetSubscription(v GetAccount200ResponseSubscription)`

SetSubscription sets Subscription field to given value.

### HasSubscription

`func (o *GetAccount200Response) HasSubscription() bool`

HasSubscription returns a boolean if a field has been set.

### GetLimits

`func (o *GetAccount200Response) GetLimits() GetAccount200ResponseLimits`

GetLimits returns the Limits field if non-nil, zero value otherwise.

### GetLimitsOk

`func (o *GetAccount200Response) GetLimitsOk() (*GetAccount200ResponseLimits, bool)`

GetLimitsOk returns a tuple with the Limits field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLimits

`func (o *GetAccount200Response) SetLimits(v GetAccount200ResponseLimits)`

SetLimits sets Limits field to given value.

### HasLimits

`func (o *GetAccount200Response) HasLimits() bool`

HasLimits returns a boolean if a field has been set.

### GetRateLimits

`func (o *GetAccount200Response) GetRateLimits() GetAccount200ResponseRateLimits`

GetRateLimits returns the RateLimits field if non-nil, zero value otherwise.

### GetRateLimitsOk

`func (o *GetAccount200Response) GetRateLimitsOk() (*GetAccount200ResponseRateLimits, bool)`

GetRateLimitsOk returns a tuple with the RateLimits field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRateLimits

`func (o *GetAccount200Response) SetRateLimits(v GetAccount200ResponseRateLimits)`

SetRateLimits sets RateLimits field to given value.

### HasRateLimits

`func (o *GetAccount200Response) HasRateLimits() bool`

HasRateLimits returns a boolean if a field has been set.

### GetRequestId

`func (o *GetAccount200Response) GetRequestId() string`

GetRequestId returns the RequestId field if non-nil, zero value otherwise.

### GetRequestIdOk

`func (o *GetAccount200Response) GetRequestIdOk() (*string, bool)`

GetRequestIdOk returns a tuple with the RequestId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestId

`func (o *GetAccount200Response) SetRequestId(v string)`

SetRequestId sets RequestId field to given value.

### HasRequestId

`func (o *GetAccount200Response) HasRequestId() bool`

HasRequestId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


