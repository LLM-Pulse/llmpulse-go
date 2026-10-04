# AiOrdersResponseBySourceInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Source** | **string** | AI assistant slug, e.g. chatgpt or perplexity | 
**Name** | **string** | Display name, e.g. ChatGPT | 
**Orders** | **int32** |  | 
**Revenue** | **string** |  | 

## Methods

### NewAiOrdersResponseBySourceInner

`func NewAiOrdersResponseBySourceInner(source string, name string, orders int32, revenue string, ) *AiOrdersResponseBySourceInner`

NewAiOrdersResponseBySourceInner instantiates a new AiOrdersResponseBySourceInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAiOrdersResponseBySourceInnerWithDefaults

`func NewAiOrdersResponseBySourceInnerWithDefaults() *AiOrdersResponseBySourceInner`

NewAiOrdersResponseBySourceInnerWithDefaults instantiates a new AiOrdersResponseBySourceInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSource

`func (o *AiOrdersResponseBySourceInner) GetSource() string`

GetSource returns the Source field if non-nil, zero value otherwise.

### GetSourceOk

`func (o *AiOrdersResponseBySourceInner) GetSourceOk() (*string, bool)`

GetSourceOk returns a tuple with the Source field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSource

`func (o *AiOrdersResponseBySourceInner) SetSource(v string)`

SetSource sets Source field to given value.


### GetName

`func (o *AiOrdersResponseBySourceInner) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *AiOrdersResponseBySourceInner) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *AiOrdersResponseBySourceInner) SetName(v string)`

SetName sets Name field to given value.


### GetOrders

`func (o *AiOrdersResponseBySourceInner) GetOrders() int32`

GetOrders returns the Orders field if non-nil, zero value otherwise.

### GetOrdersOk

`func (o *AiOrdersResponseBySourceInner) GetOrdersOk() (*int32, bool)`

GetOrdersOk returns a tuple with the Orders field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrders

`func (o *AiOrdersResponseBySourceInner) SetOrders(v int32)`

SetOrders sets Orders field to given value.


### GetRevenue

`func (o *AiOrdersResponseBySourceInner) GetRevenue() string`

GetRevenue returns the Revenue field if non-nil, zero value otherwise.

### GetRevenueOk

`func (o *AiOrdersResponseBySourceInner) GetRevenueOk() (*string, bool)`

GetRevenueOk returns a tuple with the Revenue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRevenue

`func (o *AiOrdersResponseBySourceInner) SetRevenue(v string)`

SetRevenue sets Revenue field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


