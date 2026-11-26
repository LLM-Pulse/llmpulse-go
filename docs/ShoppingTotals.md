# ShoppingTotals

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Products** | **int32** |  | 
**YourProducts** | **int32** |  | 
**Merchants** | **int32** |  | 
**AvgPrice** | **NullableFloat32** | Average price in avg_price_currency | 
**AvgPriceCurrency** | **NullableString** | The currency most prices use | 
**AvgRating** | **NullableFloat32** |  | 
**ExecutionsWithShopping** | **int32** |  | 

## Methods

### NewShoppingTotals

`func NewShoppingTotals(products int32, yourProducts int32, merchants int32, avgPrice NullableFloat32, avgPriceCurrency NullableString, avgRating NullableFloat32, executionsWithShopping int32, ) *ShoppingTotals`

NewShoppingTotals instantiates a new ShoppingTotals object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewShoppingTotalsWithDefaults

`func NewShoppingTotalsWithDefaults() *ShoppingTotals`

NewShoppingTotalsWithDefaults instantiates a new ShoppingTotals object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProducts

`func (o *ShoppingTotals) GetProducts() int32`

GetProducts returns the Products field if non-nil, zero value otherwise.

### GetProductsOk

`func (o *ShoppingTotals) GetProductsOk() (*int32, bool)`

GetProductsOk returns a tuple with the Products field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProducts

`func (o *ShoppingTotals) SetProducts(v int32)`

SetProducts sets Products field to given value.


### GetYourProducts

`func (o *ShoppingTotals) GetYourProducts() int32`

GetYourProducts returns the YourProducts field if non-nil, zero value otherwise.

### GetYourProductsOk

`func (o *ShoppingTotals) GetYourProductsOk() (*int32, bool)`

GetYourProductsOk returns a tuple with the YourProducts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetYourProducts

`func (o *ShoppingTotals) SetYourProducts(v int32)`

SetYourProducts sets YourProducts field to given value.


### GetMerchants

`func (o *ShoppingTotals) GetMerchants() int32`

GetMerchants returns the Merchants field if non-nil, zero value otherwise.

### GetMerchantsOk

`func (o *ShoppingTotals) GetMerchantsOk() (*int32, bool)`

GetMerchantsOk returns a tuple with the Merchants field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMerchants

`func (o *ShoppingTotals) SetMerchants(v int32)`

SetMerchants sets Merchants field to given value.


### GetAvgPrice

`func (o *ShoppingTotals) GetAvgPrice() float32`

GetAvgPrice returns the AvgPrice field if non-nil, zero value otherwise.

### GetAvgPriceOk

`func (o *ShoppingTotals) GetAvgPriceOk() (*float32, bool)`

GetAvgPriceOk returns a tuple with the AvgPrice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAvgPrice

`func (o *ShoppingTotals) SetAvgPrice(v float32)`

SetAvgPrice sets AvgPrice field to given value.


### SetAvgPriceNil

`func (o *ShoppingTotals) SetAvgPriceNil(b bool)`

 SetAvgPriceNil sets the value for AvgPrice to be an explicit nil

### UnsetAvgPrice
`func (o *ShoppingTotals) UnsetAvgPrice()`

UnsetAvgPrice ensures that no value is present for AvgPrice, not even an explicit nil
### GetAvgPriceCurrency

`func (o *ShoppingTotals) GetAvgPriceCurrency() string`

GetAvgPriceCurrency returns the AvgPriceCurrency field if non-nil, zero value otherwise.

### GetAvgPriceCurrencyOk

`func (o *ShoppingTotals) GetAvgPriceCurrencyOk() (*string, bool)`

GetAvgPriceCurrencyOk returns a tuple with the AvgPriceCurrency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAvgPriceCurrency

`func (o *ShoppingTotals) SetAvgPriceCurrency(v string)`

SetAvgPriceCurrency sets AvgPriceCurrency field to given value.


### SetAvgPriceCurrencyNil

`func (o *ShoppingTotals) SetAvgPriceCurrencyNil(b bool)`

 SetAvgPriceCurrencyNil sets the value for AvgPriceCurrency to be an explicit nil

### UnsetAvgPriceCurrency
`func (o *ShoppingTotals) UnsetAvgPriceCurrency()`

UnsetAvgPriceCurrency ensures that no value is present for AvgPriceCurrency, not even an explicit nil
### GetAvgRating

`func (o *ShoppingTotals) GetAvgRating() float32`

GetAvgRating returns the AvgRating field if non-nil, zero value otherwise.

### GetAvgRatingOk

`func (o *ShoppingTotals) GetAvgRatingOk() (*float32, bool)`

GetAvgRatingOk returns a tuple with the AvgRating field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAvgRating

`func (o *ShoppingTotals) SetAvgRating(v float32)`

SetAvgRating sets AvgRating field to given value.


### SetAvgRatingNil

`func (o *ShoppingTotals) SetAvgRatingNil(b bool)`

 SetAvgRatingNil sets the value for AvgRating to be an explicit nil

### UnsetAvgRating
`func (o *ShoppingTotals) UnsetAvgRating()`

UnsetAvgRating ensures that no value is present for AvgRating, not even an explicit nil
### GetExecutionsWithShopping

`func (o *ShoppingTotals) GetExecutionsWithShopping() int32`

GetExecutionsWithShopping returns the ExecutionsWithShopping field if non-nil, zero value otherwise.

### GetExecutionsWithShoppingOk

`func (o *ShoppingTotals) GetExecutionsWithShoppingOk() (*int32, bool)`

GetExecutionsWithShoppingOk returns a tuple with the ExecutionsWithShopping field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExecutionsWithShopping

`func (o *ShoppingTotals) SetExecutionsWithShopping(v int32)`

SetExecutionsWithShopping sets ExecutionsWithShopping field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


