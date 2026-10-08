# PromptRecord

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **int32** |  | 
**PromptText** | **string** |  | 
**CollectionId** | **NullableInt32** | Primary tag, when the prompt has one | 
**CollectionIds** | **[]int32** | Every tag the prompt belongs to | 
**Tags** | [**[]TagRef**](TagRef.md) |  | 
**CountryCode** | **NullableString** |  | 
**LanguageCode** | **NullableString** |  | 
**PromptType** | **NullableString** | Search intent: informational, navigational, commercial or transactional. Null until the prompt is classified | 
**BrandKind** | **NullableString** | Brand focus: brand, brand_other or non_brand. Null until the prompt is classified | 
**LastExecutedAt** | **NullableTime** | Null until the prompt has run | 
**AppUrl** | **string** | Opens this prompt in the app. The link names its project, so it opens there for any user with access to that project | 

## Methods

### NewPromptRecord

`func NewPromptRecord(id int32, promptText string, collectionId NullableInt32, collectionIds []int32, tags []TagRef, countryCode NullableString, languageCode NullableString, promptType NullableString, brandKind NullableString, lastExecutedAt NullableTime, appUrl string, ) *PromptRecord`

NewPromptRecord instantiates a new PromptRecord object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPromptRecordWithDefaults

`func NewPromptRecordWithDefaults() *PromptRecord`

NewPromptRecordWithDefaults instantiates a new PromptRecord object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *PromptRecord) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *PromptRecord) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *PromptRecord) SetId(v int32)`

SetId sets Id field to given value.


### GetPromptText

`func (o *PromptRecord) GetPromptText() string`

GetPromptText returns the PromptText field if non-nil, zero value otherwise.

### GetPromptTextOk

`func (o *PromptRecord) GetPromptTextOk() (*string, bool)`

GetPromptTextOk returns a tuple with the PromptText field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPromptText

`func (o *PromptRecord) SetPromptText(v string)`

SetPromptText sets PromptText field to given value.


### GetCollectionId

`func (o *PromptRecord) GetCollectionId() int32`

GetCollectionId returns the CollectionId field if non-nil, zero value otherwise.

### GetCollectionIdOk

`func (o *PromptRecord) GetCollectionIdOk() (*int32, bool)`

GetCollectionIdOk returns a tuple with the CollectionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCollectionId

`func (o *PromptRecord) SetCollectionId(v int32)`

SetCollectionId sets CollectionId field to given value.


### SetCollectionIdNil

`func (o *PromptRecord) SetCollectionIdNil(b bool)`

 SetCollectionIdNil sets the value for CollectionId to be an explicit nil

### UnsetCollectionId
`func (o *PromptRecord) UnsetCollectionId()`

UnsetCollectionId ensures that no value is present for CollectionId, not even an explicit nil
### GetCollectionIds

`func (o *PromptRecord) GetCollectionIds() []int32`

GetCollectionIds returns the CollectionIds field if non-nil, zero value otherwise.

### GetCollectionIdsOk

`func (o *PromptRecord) GetCollectionIdsOk() (*[]int32, bool)`

GetCollectionIdsOk returns a tuple with the CollectionIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCollectionIds

`func (o *PromptRecord) SetCollectionIds(v []int32)`

SetCollectionIds sets CollectionIds field to given value.


### GetTags

`func (o *PromptRecord) GetTags() []TagRef`

GetTags returns the Tags field if non-nil, zero value otherwise.

### GetTagsOk

`func (o *PromptRecord) GetTagsOk() (*[]TagRef, bool)`

GetTagsOk returns a tuple with the Tags field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTags

`func (o *PromptRecord) SetTags(v []TagRef)`

SetTags sets Tags field to given value.


### GetCountryCode

`func (o *PromptRecord) GetCountryCode() string`

GetCountryCode returns the CountryCode field if non-nil, zero value otherwise.

### GetCountryCodeOk

`func (o *PromptRecord) GetCountryCodeOk() (*string, bool)`

GetCountryCodeOk returns a tuple with the CountryCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountryCode

`func (o *PromptRecord) SetCountryCode(v string)`

SetCountryCode sets CountryCode field to given value.


### SetCountryCodeNil

`func (o *PromptRecord) SetCountryCodeNil(b bool)`

 SetCountryCodeNil sets the value for CountryCode to be an explicit nil

### UnsetCountryCode
`func (o *PromptRecord) UnsetCountryCode()`

UnsetCountryCode ensures that no value is present for CountryCode, not even an explicit nil
### GetLanguageCode

`func (o *PromptRecord) GetLanguageCode() string`

GetLanguageCode returns the LanguageCode field if non-nil, zero value otherwise.

### GetLanguageCodeOk

`func (o *PromptRecord) GetLanguageCodeOk() (*string, bool)`

GetLanguageCodeOk returns a tuple with the LanguageCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLanguageCode

`func (o *PromptRecord) SetLanguageCode(v string)`

SetLanguageCode sets LanguageCode field to given value.


### SetLanguageCodeNil

`func (o *PromptRecord) SetLanguageCodeNil(b bool)`

 SetLanguageCodeNil sets the value for LanguageCode to be an explicit nil

### UnsetLanguageCode
`func (o *PromptRecord) UnsetLanguageCode()`

UnsetLanguageCode ensures that no value is present for LanguageCode, not even an explicit nil
### GetPromptType

`func (o *PromptRecord) GetPromptType() string`

GetPromptType returns the PromptType field if non-nil, zero value otherwise.

### GetPromptTypeOk

`func (o *PromptRecord) GetPromptTypeOk() (*string, bool)`

GetPromptTypeOk returns a tuple with the PromptType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPromptType

`func (o *PromptRecord) SetPromptType(v string)`

SetPromptType sets PromptType field to given value.


### SetPromptTypeNil

`func (o *PromptRecord) SetPromptTypeNil(b bool)`

 SetPromptTypeNil sets the value for PromptType to be an explicit nil

### UnsetPromptType
`func (o *PromptRecord) UnsetPromptType()`

UnsetPromptType ensures that no value is present for PromptType, not even an explicit nil
### GetBrandKind

`func (o *PromptRecord) GetBrandKind() string`

GetBrandKind returns the BrandKind field if non-nil, zero value otherwise.

### GetBrandKindOk

`func (o *PromptRecord) GetBrandKindOk() (*string, bool)`

GetBrandKindOk returns a tuple with the BrandKind field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBrandKind

`func (o *PromptRecord) SetBrandKind(v string)`

SetBrandKind sets BrandKind field to given value.


### SetBrandKindNil

`func (o *PromptRecord) SetBrandKindNil(b bool)`

 SetBrandKindNil sets the value for BrandKind to be an explicit nil

### UnsetBrandKind
`func (o *PromptRecord) UnsetBrandKind()`

UnsetBrandKind ensures that no value is present for BrandKind, not even an explicit nil
### GetLastExecutedAt

`func (o *PromptRecord) GetLastExecutedAt() time.Time`

GetLastExecutedAt returns the LastExecutedAt field if non-nil, zero value otherwise.

### GetLastExecutedAtOk

`func (o *PromptRecord) GetLastExecutedAtOk() (*time.Time, bool)`

GetLastExecutedAtOk returns a tuple with the LastExecutedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastExecutedAt

`func (o *PromptRecord) SetLastExecutedAt(v time.Time)`

SetLastExecutedAt sets LastExecutedAt field to given value.


### SetLastExecutedAtNil

`func (o *PromptRecord) SetLastExecutedAtNil(b bool)`

 SetLastExecutedAtNil sets the value for LastExecutedAt to be an explicit nil

### UnsetLastExecutedAt
`func (o *PromptRecord) UnsetLastExecutedAt()`

UnsetLastExecutedAt ensures that no value is present for LastExecutedAt, not even an explicit nil
### GetAppUrl

`func (o *PromptRecord) GetAppUrl() string`

GetAppUrl returns the AppUrl field if non-nil, zero value otherwise.

### GetAppUrlOk

`func (o *PromptRecord) GetAppUrlOk() (*string, bool)`

GetAppUrlOk returns a tuple with the AppUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAppUrl

`func (o *PromptRecord) SetAppUrl(v string)`

SetAppUrl sets AppUrl field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


