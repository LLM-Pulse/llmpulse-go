# OwnedMediaCitedItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Kind** | Pointer to **string** | post covers posts and videos, profile covers profiles and channels | [optional] 
**Title** | Pointer to **NullableString** |  | [optional] 
**Subtitle** | Pointer to **NullableString** |  | [optional] 
**Url** | Pointer to **NullableString** |  | [optional] 
**ImageUrl** | Pointer to **NullableString** |  | [optional] 
**Yours** | Pointer to **bool** |  | [optional] 
**Date** | Pointer to **NullableTime** | Publication date of a post or video | [optional] 
**Stats** | Pointer to [**OwnedMediaCitedItemStats**](OwnedMediaCitedItemStats.md) |  | [optional] 

## Methods

### NewOwnedMediaCitedItem

`func NewOwnedMediaCitedItem() *OwnedMediaCitedItem`

NewOwnedMediaCitedItem instantiates a new OwnedMediaCitedItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOwnedMediaCitedItemWithDefaults

`func NewOwnedMediaCitedItemWithDefaults() *OwnedMediaCitedItem`

NewOwnedMediaCitedItemWithDefaults instantiates a new OwnedMediaCitedItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetKind

`func (o *OwnedMediaCitedItem) GetKind() string`

GetKind returns the Kind field if non-nil, zero value otherwise.

### GetKindOk

`func (o *OwnedMediaCitedItem) GetKindOk() (*string, bool)`

GetKindOk returns a tuple with the Kind field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKind

`func (o *OwnedMediaCitedItem) SetKind(v string)`

SetKind sets Kind field to given value.

### HasKind

`func (o *OwnedMediaCitedItem) HasKind() bool`

HasKind returns a boolean if a field has been set.

### GetTitle

`func (o *OwnedMediaCitedItem) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *OwnedMediaCitedItem) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *OwnedMediaCitedItem) SetTitle(v string)`

SetTitle sets Title field to given value.

### HasTitle

`func (o *OwnedMediaCitedItem) HasTitle() bool`

HasTitle returns a boolean if a field has been set.

### SetTitleNil

`func (o *OwnedMediaCitedItem) SetTitleNil(b bool)`

 SetTitleNil sets the value for Title to be an explicit nil

### UnsetTitle
`func (o *OwnedMediaCitedItem) UnsetTitle()`

UnsetTitle ensures that no value is present for Title, not even an explicit nil
### GetSubtitle

`func (o *OwnedMediaCitedItem) GetSubtitle() string`

GetSubtitle returns the Subtitle field if non-nil, zero value otherwise.

### GetSubtitleOk

`func (o *OwnedMediaCitedItem) GetSubtitleOk() (*string, bool)`

GetSubtitleOk returns a tuple with the Subtitle field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubtitle

`func (o *OwnedMediaCitedItem) SetSubtitle(v string)`

SetSubtitle sets Subtitle field to given value.

### HasSubtitle

`func (o *OwnedMediaCitedItem) HasSubtitle() bool`

HasSubtitle returns a boolean if a field has been set.

### SetSubtitleNil

`func (o *OwnedMediaCitedItem) SetSubtitleNil(b bool)`

 SetSubtitleNil sets the value for Subtitle to be an explicit nil

### UnsetSubtitle
`func (o *OwnedMediaCitedItem) UnsetSubtitle()`

UnsetSubtitle ensures that no value is present for Subtitle, not even an explicit nil
### GetUrl

`func (o *OwnedMediaCitedItem) GetUrl() string`

GetUrl returns the Url field if non-nil, zero value otherwise.

### GetUrlOk

`func (o *OwnedMediaCitedItem) GetUrlOk() (*string, bool)`

GetUrlOk returns a tuple with the Url field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrl

`func (o *OwnedMediaCitedItem) SetUrl(v string)`

SetUrl sets Url field to given value.

### HasUrl

`func (o *OwnedMediaCitedItem) HasUrl() bool`

HasUrl returns a boolean if a field has been set.

### SetUrlNil

`func (o *OwnedMediaCitedItem) SetUrlNil(b bool)`

 SetUrlNil sets the value for Url to be an explicit nil

### UnsetUrl
`func (o *OwnedMediaCitedItem) UnsetUrl()`

UnsetUrl ensures that no value is present for Url, not even an explicit nil
### GetImageUrl

`func (o *OwnedMediaCitedItem) GetImageUrl() string`

GetImageUrl returns the ImageUrl field if non-nil, zero value otherwise.

### GetImageUrlOk

`func (o *OwnedMediaCitedItem) GetImageUrlOk() (*string, bool)`

GetImageUrlOk returns a tuple with the ImageUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImageUrl

`func (o *OwnedMediaCitedItem) SetImageUrl(v string)`

SetImageUrl sets ImageUrl field to given value.

### HasImageUrl

`func (o *OwnedMediaCitedItem) HasImageUrl() bool`

HasImageUrl returns a boolean if a field has been set.

### SetImageUrlNil

`func (o *OwnedMediaCitedItem) SetImageUrlNil(b bool)`

 SetImageUrlNil sets the value for ImageUrl to be an explicit nil

### UnsetImageUrl
`func (o *OwnedMediaCitedItem) UnsetImageUrl()`

UnsetImageUrl ensures that no value is present for ImageUrl, not even an explicit nil
### GetYours

`func (o *OwnedMediaCitedItem) GetYours() bool`

GetYours returns the Yours field if non-nil, zero value otherwise.

### GetYoursOk

`func (o *OwnedMediaCitedItem) GetYoursOk() (*bool, bool)`

GetYoursOk returns a tuple with the Yours field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetYours

`func (o *OwnedMediaCitedItem) SetYours(v bool)`

SetYours sets Yours field to given value.

### HasYours

`func (o *OwnedMediaCitedItem) HasYours() bool`

HasYours returns a boolean if a field has been set.

### GetDate

`func (o *OwnedMediaCitedItem) GetDate() time.Time`

GetDate returns the Date field if non-nil, zero value otherwise.

### GetDateOk

`func (o *OwnedMediaCitedItem) GetDateOk() (*time.Time, bool)`

GetDateOk returns a tuple with the Date field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDate

`func (o *OwnedMediaCitedItem) SetDate(v time.Time)`

SetDate sets Date field to given value.

### HasDate

`func (o *OwnedMediaCitedItem) HasDate() bool`

HasDate returns a boolean if a field has been set.

### SetDateNil

`func (o *OwnedMediaCitedItem) SetDateNil(b bool)`

 SetDateNil sets the value for Date to be an explicit nil

### UnsetDate
`func (o *OwnedMediaCitedItem) UnsetDate()`

UnsetDate ensures that no value is present for Date, not even an explicit nil
### GetStats

`func (o *OwnedMediaCitedItem) GetStats() OwnedMediaCitedItemStats`

GetStats returns the Stats field if non-nil, zero value otherwise.

### GetStatsOk

`func (o *OwnedMediaCitedItem) GetStatsOk() (*OwnedMediaCitedItemStats, bool)`

GetStatsOk returns a tuple with the Stats field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStats

`func (o *OwnedMediaCitedItem) SetStats(v OwnedMediaCitedItemStats)`

SetStats sets Stats field to given value.

### HasStats

`func (o *OwnedMediaCitedItem) HasStats() bool`

HasStats returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


