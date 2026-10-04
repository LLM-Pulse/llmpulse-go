# CatalogProduct

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ExternalId** | **string** | The store&#39;s product id, e.g. gid://shopify/Product/1 | 
**Title** | **string** |  | 
**Handle** | Pointer to **string** |  | [optional] 
**ProductType** | Pointer to **string** |  | [optional] 
**Vendor** | Pointer to **string** |  | [optional] 
**Tags** | Pointer to **[]string** |  | [optional] 
**Collections** | Pointer to **[]string** |  | [optional] 
**Url** | Pointer to **string** |  | [optional] 

## Methods

### NewCatalogProduct

`func NewCatalogProduct(externalId string, title string, ) *CatalogProduct`

NewCatalogProduct instantiates a new CatalogProduct object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCatalogProductWithDefaults

`func NewCatalogProductWithDefaults() *CatalogProduct`

NewCatalogProductWithDefaults instantiates a new CatalogProduct object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetExternalId

`func (o *CatalogProduct) GetExternalId() string`

GetExternalId returns the ExternalId field if non-nil, zero value otherwise.

### GetExternalIdOk

`func (o *CatalogProduct) GetExternalIdOk() (*string, bool)`

GetExternalIdOk returns a tuple with the ExternalId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExternalId

`func (o *CatalogProduct) SetExternalId(v string)`

SetExternalId sets ExternalId field to given value.


### GetTitle

`func (o *CatalogProduct) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *CatalogProduct) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *CatalogProduct) SetTitle(v string)`

SetTitle sets Title field to given value.


### GetHandle

`func (o *CatalogProduct) GetHandle() string`

GetHandle returns the Handle field if non-nil, zero value otherwise.

### GetHandleOk

`func (o *CatalogProduct) GetHandleOk() (*string, bool)`

GetHandleOk returns a tuple with the Handle field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHandle

`func (o *CatalogProduct) SetHandle(v string)`

SetHandle sets Handle field to given value.

### HasHandle

`func (o *CatalogProduct) HasHandle() bool`

HasHandle returns a boolean if a field has been set.

### GetProductType

`func (o *CatalogProduct) GetProductType() string`

GetProductType returns the ProductType field if non-nil, zero value otherwise.

### GetProductTypeOk

`func (o *CatalogProduct) GetProductTypeOk() (*string, bool)`

GetProductTypeOk returns a tuple with the ProductType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProductType

`func (o *CatalogProduct) SetProductType(v string)`

SetProductType sets ProductType field to given value.

### HasProductType

`func (o *CatalogProduct) HasProductType() bool`

HasProductType returns a boolean if a field has been set.

### GetVendor

`func (o *CatalogProduct) GetVendor() string`

GetVendor returns the Vendor field if non-nil, zero value otherwise.

### GetVendorOk

`func (o *CatalogProduct) GetVendorOk() (*string, bool)`

GetVendorOk returns a tuple with the Vendor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVendor

`func (o *CatalogProduct) SetVendor(v string)`

SetVendor sets Vendor field to given value.

### HasVendor

`func (o *CatalogProduct) HasVendor() bool`

HasVendor returns a boolean if a field has been set.

### GetTags

`func (o *CatalogProduct) GetTags() []string`

GetTags returns the Tags field if non-nil, zero value otherwise.

### GetTagsOk

`func (o *CatalogProduct) GetTagsOk() (*[]string, bool)`

GetTagsOk returns a tuple with the Tags field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTags

`func (o *CatalogProduct) SetTags(v []string)`

SetTags sets Tags field to given value.

### HasTags

`func (o *CatalogProduct) HasTags() bool`

HasTags returns a boolean if a field has been set.

### GetCollections

`func (o *CatalogProduct) GetCollections() []string`

GetCollections returns the Collections field if non-nil, zero value otherwise.

### GetCollectionsOk

`func (o *CatalogProduct) GetCollectionsOk() (*[]string, bool)`

GetCollectionsOk returns a tuple with the Collections field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCollections

`func (o *CatalogProduct) SetCollections(v []string)`

SetCollections sets Collections field to given value.

### HasCollections

`func (o *CatalogProduct) HasCollections() bool`

HasCollections returns a boolean if a field has been set.

### GetUrl

`func (o *CatalogProduct) GetUrl() string`

GetUrl returns the Url field if non-nil, zero value otherwise.

### GetUrlOk

`func (o *CatalogProduct) GetUrlOk() (*string, bool)`

GetUrlOk returns a tuple with the Url field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrl

`func (o *CatalogProduct) SetUrl(v string)`

SetUrl sets Url field to given value.

### HasUrl

`func (o *CatalogProduct) HasUrl() bool`

HasUrl returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


