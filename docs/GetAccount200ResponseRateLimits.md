# GetAccount200ResponseRateLimits

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**RequestsPerMinute** | Pointer to **int32** | The ceiling enforced for the API key used on this call, which may be above the 300/min default. | [optional] 
**WriteRequestsPerMinute** | Pointer to **int32** | Flat ceiling on write requests, the same for every key. | [optional] 

## Methods

### NewGetAccount200ResponseRateLimits

`func NewGetAccount200ResponseRateLimits() *GetAccount200ResponseRateLimits`

NewGetAccount200ResponseRateLimits instantiates a new GetAccount200ResponseRateLimits object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGetAccount200ResponseRateLimitsWithDefaults

`func NewGetAccount200ResponseRateLimitsWithDefaults() *GetAccount200ResponseRateLimits`

NewGetAccount200ResponseRateLimitsWithDefaults instantiates a new GetAccount200ResponseRateLimits object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetRequestsPerMinute

`func (o *GetAccount200ResponseRateLimits) GetRequestsPerMinute() int32`

GetRequestsPerMinute returns the RequestsPerMinute field if non-nil, zero value otherwise.

### GetRequestsPerMinuteOk

`func (o *GetAccount200ResponseRateLimits) GetRequestsPerMinuteOk() (*int32, bool)`

GetRequestsPerMinuteOk returns a tuple with the RequestsPerMinute field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestsPerMinute

`func (o *GetAccount200ResponseRateLimits) SetRequestsPerMinute(v int32)`

SetRequestsPerMinute sets RequestsPerMinute field to given value.

### HasRequestsPerMinute

`func (o *GetAccount200ResponseRateLimits) HasRequestsPerMinute() bool`

HasRequestsPerMinute returns a boolean if a field has been set.

### GetWriteRequestsPerMinute

`func (o *GetAccount200ResponseRateLimits) GetWriteRequestsPerMinute() int32`

GetWriteRequestsPerMinute returns the WriteRequestsPerMinute field if non-nil, zero value otherwise.

### GetWriteRequestsPerMinuteOk

`func (o *GetAccount200ResponseRateLimits) GetWriteRequestsPerMinuteOk() (*int32, bool)`

GetWriteRequestsPerMinuteOk returns a tuple with the WriteRequestsPerMinute field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWriteRequestsPerMinute

`func (o *GetAccount200ResponseRateLimits) SetWriteRequestsPerMinute(v int32)`

SetWriteRequestsPerMinute sets WriteRequestsPerMinute field to given value.

### HasWriteRequestsPerMinute

`func (o *GetAccount200ResponseRateLimits) HasWriteRequestsPerMinute() bool`

HasWriteRequestsPerMinute returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


