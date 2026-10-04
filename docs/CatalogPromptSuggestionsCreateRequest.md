# CatalogPromptSuggestionsCreateRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ProjectId** | **int32** |  | 
**Platform** | **string** |  | 
**CountryCode** | Pointer to **string** | Defaults to the project country | [optional] 
**LanguageCode** | Pointer to **string** | Defaults to the project language | [optional] 
**Products** | [**[]CatalogProduct**](CatalogProduct.md) |  | 

## Methods

### NewCatalogPromptSuggestionsCreateRequest

`func NewCatalogPromptSuggestionsCreateRequest(projectId int32, platform string, products []CatalogProduct, ) *CatalogPromptSuggestionsCreateRequest`

NewCatalogPromptSuggestionsCreateRequest instantiates a new CatalogPromptSuggestionsCreateRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCatalogPromptSuggestionsCreateRequestWithDefaults

`func NewCatalogPromptSuggestionsCreateRequestWithDefaults() *CatalogPromptSuggestionsCreateRequest`

NewCatalogPromptSuggestionsCreateRequestWithDefaults instantiates a new CatalogPromptSuggestionsCreateRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProjectId

`func (o *CatalogPromptSuggestionsCreateRequest) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *CatalogPromptSuggestionsCreateRequest) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *CatalogPromptSuggestionsCreateRequest) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.


### GetPlatform

`func (o *CatalogPromptSuggestionsCreateRequest) GetPlatform() string`

GetPlatform returns the Platform field if non-nil, zero value otherwise.

### GetPlatformOk

`func (o *CatalogPromptSuggestionsCreateRequest) GetPlatformOk() (*string, bool)`

GetPlatformOk returns a tuple with the Platform field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlatform

`func (o *CatalogPromptSuggestionsCreateRequest) SetPlatform(v string)`

SetPlatform sets Platform field to given value.


### GetCountryCode

`func (o *CatalogPromptSuggestionsCreateRequest) GetCountryCode() string`

GetCountryCode returns the CountryCode field if non-nil, zero value otherwise.

### GetCountryCodeOk

`func (o *CatalogPromptSuggestionsCreateRequest) GetCountryCodeOk() (*string, bool)`

GetCountryCodeOk returns a tuple with the CountryCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountryCode

`func (o *CatalogPromptSuggestionsCreateRequest) SetCountryCode(v string)`

SetCountryCode sets CountryCode field to given value.

### HasCountryCode

`func (o *CatalogPromptSuggestionsCreateRequest) HasCountryCode() bool`

HasCountryCode returns a boolean if a field has been set.

### GetLanguageCode

`func (o *CatalogPromptSuggestionsCreateRequest) GetLanguageCode() string`

GetLanguageCode returns the LanguageCode field if non-nil, zero value otherwise.

### GetLanguageCodeOk

`func (o *CatalogPromptSuggestionsCreateRequest) GetLanguageCodeOk() (*string, bool)`

GetLanguageCodeOk returns a tuple with the LanguageCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLanguageCode

`func (o *CatalogPromptSuggestionsCreateRequest) SetLanguageCode(v string)`

SetLanguageCode sets LanguageCode field to given value.

### HasLanguageCode

`func (o *CatalogPromptSuggestionsCreateRequest) HasLanguageCode() bool`

HasLanguageCode returns a boolean if a field has been set.

### GetProducts

`func (o *CatalogPromptSuggestionsCreateRequest) GetProducts() []CatalogProduct`

GetProducts returns the Products field if non-nil, zero value otherwise.

### GetProductsOk

`func (o *CatalogPromptSuggestionsCreateRequest) GetProductsOk() (*[]CatalogProduct, bool)`

GetProductsOk returns a tuple with the Products field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProducts

`func (o *CatalogPromptSuggestionsCreateRequest) SetProducts(v []CatalogProduct)`

SetProducts sets Products field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


