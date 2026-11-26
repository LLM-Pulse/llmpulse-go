# RedditAuthorBrand

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**IsBrand** | **bool** | True for your own brand | 
**Id** | **NullableInt32** | The competitor&#39;s id; null for your own brand | 
**Name** | **string** |  | 
**Count** | **int32** | The author&#39;s cited posts whose content names the brand | 

## Methods

### NewRedditAuthorBrand

`func NewRedditAuthorBrand(isBrand bool, id NullableInt32, name string, count int32, ) *RedditAuthorBrand`

NewRedditAuthorBrand instantiates a new RedditAuthorBrand object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRedditAuthorBrandWithDefaults

`func NewRedditAuthorBrandWithDefaults() *RedditAuthorBrand`

NewRedditAuthorBrandWithDefaults instantiates a new RedditAuthorBrand object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetIsBrand

`func (o *RedditAuthorBrand) GetIsBrand() bool`

GetIsBrand returns the IsBrand field if non-nil, zero value otherwise.

### GetIsBrandOk

`func (o *RedditAuthorBrand) GetIsBrandOk() (*bool, bool)`

GetIsBrandOk returns a tuple with the IsBrand field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsBrand

`func (o *RedditAuthorBrand) SetIsBrand(v bool)`

SetIsBrand sets IsBrand field to given value.


### GetId

`func (o *RedditAuthorBrand) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *RedditAuthorBrand) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *RedditAuthorBrand) SetId(v int32)`

SetId sets Id field to given value.


### SetIdNil

`func (o *RedditAuthorBrand) SetIdNil(b bool)`

 SetIdNil sets the value for Id to be an explicit nil

### UnsetId
`func (o *RedditAuthorBrand) UnsetId()`

UnsetId ensures that no value is present for Id, not even an explicit nil
### GetName

`func (o *RedditAuthorBrand) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *RedditAuthorBrand) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *RedditAuthorBrand) SetName(v string)`

SetName sets Name field to given value.


### GetCount

`func (o *RedditAuthorBrand) GetCount() int32`

GetCount returns the Count field if non-nil, zero value otherwise.

### GetCountOk

`func (o *RedditAuthorBrand) GetCountOk() (*int32, bool)`

GetCountOk returns a tuple with the Count field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCount

`func (o *RedditAuthorBrand) SetCount(v int32)`

SetCount sets Count field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


