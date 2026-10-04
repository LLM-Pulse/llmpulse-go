# AiOrdersResponseTotals

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Orders** | **int32** |  | 
**Revenue** | **string** | Decimal amount with two decimals, e.g. 1834.20 | 

## Methods

### NewAiOrdersResponseTotals

`func NewAiOrdersResponseTotals(orders int32, revenue string, ) *AiOrdersResponseTotals`

NewAiOrdersResponseTotals instantiates a new AiOrdersResponseTotals object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAiOrdersResponseTotalsWithDefaults

`func NewAiOrdersResponseTotalsWithDefaults() *AiOrdersResponseTotals`

NewAiOrdersResponseTotalsWithDefaults instantiates a new AiOrdersResponseTotals object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetOrders

`func (o *AiOrdersResponseTotals) GetOrders() int32`

GetOrders returns the Orders field if non-nil, zero value otherwise.

### GetOrdersOk

`func (o *AiOrdersResponseTotals) GetOrdersOk() (*int32, bool)`

GetOrdersOk returns a tuple with the Orders field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrders

`func (o *AiOrdersResponseTotals) SetOrders(v int32)`

SetOrders sets Orders field to given value.


### GetRevenue

`func (o *AiOrdersResponseTotals) GetRevenue() string`

GetRevenue returns the Revenue field if non-nil, zero value otherwise.

### GetRevenueOk

`func (o *AiOrdersResponseTotals) GetRevenueOk() (*string, bool)`

GetRevenueOk returns a tuple with the Revenue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRevenue

`func (o *AiOrdersResponseTotals) SetRevenue(v string)`

SetRevenue sets Revenue field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


