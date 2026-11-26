# ShoppingRow

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ProductKey** | Pointer to **string** | Stable grouping key of the product: its external id, else title: and the lowercased title (view&#x3D;products) | [optional] 
**Title** | Pointer to **string** |  | [optional] 
**Domain** | Pointer to **NullableString** |  | [optional] 
**Url** | Pointer to **NullableString** |  | [optional] 
**Merchants** | Pointer to **NullableString** | The merchants the product card names (view&#x3D;products) | [optional] 
**Merchant** | Pointer to **string** | The merchant (view&#x3D;merchants) | [optional] 
**Products** | Pointer to **int32** | Distinct products the merchant sold (view&#x3D;merchants) | [optional] 
**Currency** | **NullableString** | Currency code the prices are in; null when no price names one | 
**CurrencyCount** | Pointer to **int32** | Currencies the product was priced in; above 1 the row reports its highest-priced listing (view&#x3D;products) | [optional] 
**MinPrice** | **NullableFloat32** |  | 
**MaxPrice** | **NullableFloat32** |  | 
**AvgPrice** | Pointer to **NullableFloat32** | Average price in currency (view&#x3D;merchants) | [optional] 
**AvgRating** | **NullableFloat32** |  | 
**RatingVotes** | Pointer to **NullableInt32** | Most rating votes any listing of the product showed (view&#x3D;products) | [optional] 
**Appearances** | **int32** |  | 
**IsClient** | Pointer to **bool** | Whether the product is identified as your brand&#39;s own (view&#x3D;products) | [optional] 
**BestRank** | Pointer to **NullableInt32** | Best rank the product got in a card list (view&#x3D;products) | [optional] 
**Models** | Pointer to **[]string** | Models that showed the product (view&#x3D;products) | [optional] 
**LastSeenAt** | Pointer to **NullableTime** | The latest answer that showed the product (view&#x3D;products) | [optional] 

## Methods

### NewShoppingRow

`func NewShoppingRow(currency NullableString, minPrice NullableFloat32, maxPrice NullableFloat32, avgRating NullableFloat32, appearances int32, ) *ShoppingRow`

NewShoppingRow instantiates a new ShoppingRow object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewShoppingRowWithDefaults

`func NewShoppingRowWithDefaults() *ShoppingRow`

NewShoppingRowWithDefaults instantiates a new ShoppingRow object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProductKey

`func (o *ShoppingRow) GetProductKey() string`

GetProductKey returns the ProductKey field if non-nil, zero value otherwise.

### GetProductKeyOk

`func (o *ShoppingRow) GetProductKeyOk() (*string, bool)`

GetProductKeyOk returns a tuple with the ProductKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProductKey

`func (o *ShoppingRow) SetProductKey(v string)`

SetProductKey sets ProductKey field to given value.

### HasProductKey

`func (o *ShoppingRow) HasProductKey() bool`

HasProductKey returns a boolean if a field has been set.

### GetTitle

`func (o *ShoppingRow) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *ShoppingRow) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *ShoppingRow) SetTitle(v string)`

SetTitle sets Title field to given value.

### HasTitle

`func (o *ShoppingRow) HasTitle() bool`

HasTitle returns a boolean if a field has been set.

### GetDomain

`func (o *ShoppingRow) GetDomain() string`

GetDomain returns the Domain field if non-nil, zero value otherwise.

### GetDomainOk

`func (o *ShoppingRow) GetDomainOk() (*string, bool)`

GetDomainOk returns a tuple with the Domain field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDomain

`func (o *ShoppingRow) SetDomain(v string)`

SetDomain sets Domain field to given value.

### HasDomain

`func (o *ShoppingRow) HasDomain() bool`

HasDomain returns a boolean if a field has been set.

### SetDomainNil

`func (o *ShoppingRow) SetDomainNil(b bool)`

 SetDomainNil sets the value for Domain to be an explicit nil

### UnsetDomain
`func (o *ShoppingRow) UnsetDomain()`

UnsetDomain ensures that no value is present for Domain, not even an explicit nil
### GetUrl

`func (o *ShoppingRow) GetUrl() string`

GetUrl returns the Url field if non-nil, zero value otherwise.

### GetUrlOk

`func (o *ShoppingRow) GetUrlOk() (*string, bool)`

GetUrlOk returns a tuple with the Url field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrl

`func (o *ShoppingRow) SetUrl(v string)`

SetUrl sets Url field to given value.

### HasUrl

`func (o *ShoppingRow) HasUrl() bool`

HasUrl returns a boolean if a field has been set.

### SetUrlNil

`func (o *ShoppingRow) SetUrlNil(b bool)`

 SetUrlNil sets the value for Url to be an explicit nil

### UnsetUrl
`func (o *ShoppingRow) UnsetUrl()`

UnsetUrl ensures that no value is present for Url, not even an explicit nil
### GetMerchants

`func (o *ShoppingRow) GetMerchants() string`

GetMerchants returns the Merchants field if non-nil, zero value otherwise.

### GetMerchantsOk

`func (o *ShoppingRow) GetMerchantsOk() (*string, bool)`

GetMerchantsOk returns a tuple with the Merchants field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMerchants

`func (o *ShoppingRow) SetMerchants(v string)`

SetMerchants sets Merchants field to given value.

### HasMerchants

`func (o *ShoppingRow) HasMerchants() bool`

HasMerchants returns a boolean if a field has been set.

### SetMerchantsNil

`func (o *ShoppingRow) SetMerchantsNil(b bool)`

 SetMerchantsNil sets the value for Merchants to be an explicit nil

### UnsetMerchants
`func (o *ShoppingRow) UnsetMerchants()`

UnsetMerchants ensures that no value is present for Merchants, not even an explicit nil
### GetMerchant

`func (o *ShoppingRow) GetMerchant() string`

GetMerchant returns the Merchant field if non-nil, zero value otherwise.

### GetMerchantOk

`func (o *ShoppingRow) GetMerchantOk() (*string, bool)`

GetMerchantOk returns a tuple with the Merchant field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMerchant

`func (o *ShoppingRow) SetMerchant(v string)`

SetMerchant sets Merchant field to given value.

### HasMerchant

`func (o *ShoppingRow) HasMerchant() bool`

HasMerchant returns a boolean if a field has been set.

### GetProducts

`func (o *ShoppingRow) GetProducts() int32`

GetProducts returns the Products field if non-nil, zero value otherwise.

### GetProductsOk

`func (o *ShoppingRow) GetProductsOk() (*int32, bool)`

GetProductsOk returns a tuple with the Products field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProducts

`func (o *ShoppingRow) SetProducts(v int32)`

SetProducts sets Products field to given value.

### HasProducts

`func (o *ShoppingRow) HasProducts() bool`

HasProducts returns a boolean if a field has been set.

### GetCurrency

`func (o *ShoppingRow) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *ShoppingRow) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *ShoppingRow) SetCurrency(v string)`

SetCurrency sets Currency field to given value.


### SetCurrencyNil

`func (o *ShoppingRow) SetCurrencyNil(b bool)`

 SetCurrencyNil sets the value for Currency to be an explicit nil

### UnsetCurrency
`func (o *ShoppingRow) UnsetCurrency()`

UnsetCurrency ensures that no value is present for Currency, not even an explicit nil
### GetCurrencyCount

`func (o *ShoppingRow) GetCurrencyCount() int32`

GetCurrencyCount returns the CurrencyCount field if non-nil, zero value otherwise.

### GetCurrencyCountOk

`func (o *ShoppingRow) GetCurrencyCountOk() (*int32, bool)`

GetCurrencyCountOk returns a tuple with the CurrencyCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrencyCount

`func (o *ShoppingRow) SetCurrencyCount(v int32)`

SetCurrencyCount sets CurrencyCount field to given value.

### HasCurrencyCount

`func (o *ShoppingRow) HasCurrencyCount() bool`

HasCurrencyCount returns a boolean if a field has been set.

### GetMinPrice

`func (o *ShoppingRow) GetMinPrice() float32`

GetMinPrice returns the MinPrice field if non-nil, zero value otherwise.

### GetMinPriceOk

`func (o *ShoppingRow) GetMinPriceOk() (*float32, bool)`

GetMinPriceOk returns a tuple with the MinPrice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMinPrice

`func (o *ShoppingRow) SetMinPrice(v float32)`

SetMinPrice sets MinPrice field to given value.


### SetMinPriceNil

`func (o *ShoppingRow) SetMinPriceNil(b bool)`

 SetMinPriceNil sets the value for MinPrice to be an explicit nil

### UnsetMinPrice
`func (o *ShoppingRow) UnsetMinPrice()`

UnsetMinPrice ensures that no value is present for MinPrice, not even an explicit nil
### GetMaxPrice

`func (o *ShoppingRow) GetMaxPrice() float32`

GetMaxPrice returns the MaxPrice field if non-nil, zero value otherwise.

### GetMaxPriceOk

`func (o *ShoppingRow) GetMaxPriceOk() (*float32, bool)`

GetMaxPriceOk returns a tuple with the MaxPrice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxPrice

`func (o *ShoppingRow) SetMaxPrice(v float32)`

SetMaxPrice sets MaxPrice field to given value.


### SetMaxPriceNil

`func (o *ShoppingRow) SetMaxPriceNil(b bool)`

 SetMaxPriceNil sets the value for MaxPrice to be an explicit nil

### UnsetMaxPrice
`func (o *ShoppingRow) UnsetMaxPrice()`

UnsetMaxPrice ensures that no value is present for MaxPrice, not even an explicit nil
### GetAvgPrice

`func (o *ShoppingRow) GetAvgPrice() float32`

GetAvgPrice returns the AvgPrice field if non-nil, zero value otherwise.

### GetAvgPriceOk

`func (o *ShoppingRow) GetAvgPriceOk() (*float32, bool)`

GetAvgPriceOk returns a tuple with the AvgPrice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAvgPrice

`func (o *ShoppingRow) SetAvgPrice(v float32)`

SetAvgPrice sets AvgPrice field to given value.

### HasAvgPrice

`func (o *ShoppingRow) HasAvgPrice() bool`

HasAvgPrice returns a boolean if a field has been set.

### SetAvgPriceNil

`func (o *ShoppingRow) SetAvgPriceNil(b bool)`

 SetAvgPriceNil sets the value for AvgPrice to be an explicit nil

### UnsetAvgPrice
`func (o *ShoppingRow) UnsetAvgPrice()`

UnsetAvgPrice ensures that no value is present for AvgPrice, not even an explicit nil
### GetAvgRating

`func (o *ShoppingRow) GetAvgRating() float32`

GetAvgRating returns the AvgRating field if non-nil, zero value otherwise.

### GetAvgRatingOk

`func (o *ShoppingRow) GetAvgRatingOk() (*float32, bool)`

GetAvgRatingOk returns a tuple with the AvgRating field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAvgRating

`func (o *ShoppingRow) SetAvgRating(v float32)`

SetAvgRating sets AvgRating field to given value.


### SetAvgRatingNil

`func (o *ShoppingRow) SetAvgRatingNil(b bool)`

 SetAvgRatingNil sets the value for AvgRating to be an explicit nil

### UnsetAvgRating
`func (o *ShoppingRow) UnsetAvgRating()`

UnsetAvgRating ensures that no value is present for AvgRating, not even an explicit nil
### GetRatingVotes

`func (o *ShoppingRow) GetRatingVotes() int32`

GetRatingVotes returns the RatingVotes field if non-nil, zero value otherwise.

### GetRatingVotesOk

`func (o *ShoppingRow) GetRatingVotesOk() (*int32, bool)`

GetRatingVotesOk returns a tuple with the RatingVotes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRatingVotes

`func (o *ShoppingRow) SetRatingVotes(v int32)`

SetRatingVotes sets RatingVotes field to given value.

### HasRatingVotes

`func (o *ShoppingRow) HasRatingVotes() bool`

HasRatingVotes returns a boolean if a field has been set.

### SetRatingVotesNil

`func (o *ShoppingRow) SetRatingVotesNil(b bool)`

 SetRatingVotesNil sets the value for RatingVotes to be an explicit nil

### UnsetRatingVotes
`func (o *ShoppingRow) UnsetRatingVotes()`

UnsetRatingVotes ensures that no value is present for RatingVotes, not even an explicit nil
### GetAppearances

`func (o *ShoppingRow) GetAppearances() int32`

GetAppearances returns the Appearances field if non-nil, zero value otherwise.

### GetAppearancesOk

`func (o *ShoppingRow) GetAppearancesOk() (*int32, bool)`

GetAppearancesOk returns a tuple with the Appearances field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAppearances

`func (o *ShoppingRow) SetAppearances(v int32)`

SetAppearances sets Appearances field to given value.


### GetIsClient

`func (o *ShoppingRow) GetIsClient() bool`

GetIsClient returns the IsClient field if non-nil, zero value otherwise.

### GetIsClientOk

`func (o *ShoppingRow) GetIsClientOk() (*bool, bool)`

GetIsClientOk returns a tuple with the IsClient field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsClient

`func (o *ShoppingRow) SetIsClient(v bool)`

SetIsClient sets IsClient field to given value.

### HasIsClient

`func (o *ShoppingRow) HasIsClient() bool`

HasIsClient returns a boolean if a field has been set.

### GetBestRank

`func (o *ShoppingRow) GetBestRank() int32`

GetBestRank returns the BestRank field if non-nil, zero value otherwise.

### GetBestRankOk

`func (o *ShoppingRow) GetBestRankOk() (*int32, bool)`

GetBestRankOk returns a tuple with the BestRank field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBestRank

`func (o *ShoppingRow) SetBestRank(v int32)`

SetBestRank sets BestRank field to given value.

### HasBestRank

`func (o *ShoppingRow) HasBestRank() bool`

HasBestRank returns a boolean if a field has been set.

### SetBestRankNil

`func (o *ShoppingRow) SetBestRankNil(b bool)`

 SetBestRankNil sets the value for BestRank to be an explicit nil

### UnsetBestRank
`func (o *ShoppingRow) UnsetBestRank()`

UnsetBestRank ensures that no value is present for BestRank, not even an explicit nil
### GetModels

`func (o *ShoppingRow) GetModels() []string`

GetModels returns the Models field if non-nil, zero value otherwise.

### GetModelsOk

`func (o *ShoppingRow) GetModelsOk() (*[]string, bool)`

GetModelsOk returns a tuple with the Models field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModels

`func (o *ShoppingRow) SetModels(v []string)`

SetModels sets Models field to given value.

### HasModels

`func (o *ShoppingRow) HasModels() bool`

HasModels returns a boolean if a field has been set.

### GetLastSeenAt

`func (o *ShoppingRow) GetLastSeenAt() time.Time`

GetLastSeenAt returns the LastSeenAt field if non-nil, zero value otherwise.

### GetLastSeenAtOk

`func (o *ShoppingRow) GetLastSeenAtOk() (*time.Time, bool)`

GetLastSeenAtOk returns a tuple with the LastSeenAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastSeenAt

`func (o *ShoppingRow) SetLastSeenAt(v time.Time)`

SetLastSeenAt sets LastSeenAt field to given value.

### HasLastSeenAt

`func (o *ShoppingRow) HasLastSeenAt() bool`

HasLastSeenAt returns a boolean if a field has been set.

### SetLastSeenAtNil

`func (o *ShoppingRow) SetLastSeenAtNil(b bool)`

 SetLastSeenAtNil sets the value for LastSeenAt to be an explicit nil

### UnsetLastSeenAt
`func (o *ShoppingRow) UnsetLastSeenAt()`

UnsetLastSeenAt ensures that no value is present for LastSeenAt, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


