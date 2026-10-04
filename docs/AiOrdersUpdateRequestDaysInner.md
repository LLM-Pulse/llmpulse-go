# AiOrdersUpdateRequestDaysInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Day** | **string** | Must fall inside from..to | 
**Referrer** | **string** | Raw referring host or utm_source of the order&#39;s first visit, e.g. chatgpt.com. Entries that are not an AI assistant are ignored | 
**Orders** | **int32** |  | 
**Revenue** | **string** | Non-negative decimal amount in currency, e.g. 120.50. A JSON number is accepted too | 

## Methods

### NewAiOrdersUpdateRequestDaysInner

`func NewAiOrdersUpdateRequestDaysInner(day string, referrer string, orders int32, revenue string, ) *AiOrdersUpdateRequestDaysInner`

NewAiOrdersUpdateRequestDaysInner instantiates a new AiOrdersUpdateRequestDaysInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAiOrdersUpdateRequestDaysInnerWithDefaults

`func NewAiOrdersUpdateRequestDaysInnerWithDefaults() *AiOrdersUpdateRequestDaysInner`

NewAiOrdersUpdateRequestDaysInnerWithDefaults instantiates a new AiOrdersUpdateRequestDaysInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDay

`func (o *AiOrdersUpdateRequestDaysInner) GetDay() string`

GetDay returns the Day field if non-nil, zero value otherwise.

### GetDayOk

`func (o *AiOrdersUpdateRequestDaysInner) GetDayOk() (*string, bool)`

GetDayOk returns a tuple with the Day field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDay

`func (o *AiOrdersUpdateRequestDaysInner) SetDay(v string)`

SetDay sets Day field to given value.


### GetReferrer

`func (o *AiOrdersUpdateRequestDaysInner) GetReferrer() string`

GetReferrer returns the Referrer field if non-nil, zero value otherwise.

### GetReferrerOk

`func (o *AiOrdersUpdateRequestDaysInner) GetReferrerOk() (*string, bool)`

GetReferrerOk returns a tuple with the Referrer field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReferrer

`func (o *AiOrdersUpdateRequestDaysInner) SetReferrer(v string)`

SetReferrer sets Referrer field to given value.


### GetOrders

`func (o *AiOrdersUpdateRequestDaysInner) GetOrders() int32`

GetOrders returns the Orders field if non-nil, zero value otherwise.

### GetOrdersOk

`func (o *AiOrdersUpdateRequestDaysInner) GetOrdersOk() (*int32, bool)`

GetOrdersOk returns a tuple with the Orders field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrders

`func (o *AiOrdersUpdateRequestDaysInner) SetOrders(v int32)`

SetOrders sets Orders field to given value.


### GetRevenue

`func (o *AiOrdersUpdateRequestDaysInner) GetRevenue() string`

GetRevenue returns the Revenue field if non-nil, zero value otherwise.

### GetRevenueOk

`func (o *AiOrdersUpdateRequestDaysInner) GetRevenueOk() (*string, bool)`

GetRevenueOk returns a tuple with the Revenue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRevenue

`func (o *AiOrdersUpdateRequestDaysInner) SetRevenue(v string)`

SetRevenue sets Revenue field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


