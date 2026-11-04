# CmsContentSummary

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **int32** | WordPress post or page id | [optional] 
**Type** | Pointer to **string** |  | [optional] 
**Status** | Pointer to **string** | WordPress status (publish, future, draft, pending or private) | [optional] 
**Slug** | Pointer to **string** |  | [optional] 
**Title** | Pointer to **string** | Plain-text title as the site renders it | [optional] 
**Url** | Pointer to **NullableString** | The public link on the connected site; null when the site names a link on another host | [optional] 
**ModifiedAt** | Pointer to **NullableTime** |  | [optional] 

## Methods

### NewCmsContentSummary

`func NewCmsContentSummary() *CmsContentSummary`

NewCmsContentSummary instantiates a new CmsContentSummary object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCmsContentSummaryWithDefaults

`func NewCmsContentSummaryWithDefaults() *CmsContentSummary`

NewCmsContentSummaryWithDefaults instantiates a new CmsContentSummary object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *CmsContentSummary) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *CmsContentSummary) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *CmsContentSummary) SetId(v int32)`

SetId sets Id field to given value.

### HasId

`func (o *CmsContentSummary) HasId() bool`

HasId returns a boolean if a field has been set.

### GetType

`func (o *CmsContentSummary) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *CmsContentSummary) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *CmsContentSummary) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *CmsContentSummary) HasType() bool`

HasType returns a boolean if a field has been set.

### GetStatus

`func (o *CmsContentSummary) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *CmsContentSummary) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *CmsContentSummary) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *CmsContentSummary) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetSlug

`func (o *CmsContentSummary) GetSlug() string`

GetSlug returns the Slug field if non-nil, zero value otherwise.

### GetSlugOk

`func (o *CmsContentSummary) GetSlugOk() (*string, bool)`

GetSlugOk returns a tuple with the Slug field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSlug

`func (o *CmsContentSummary) SetSlug(v string)`

SetSlug sets Slug field to given value.

### HasSlug

`func (o *CmsContentSummary) HasSlug() bool`

HasSlug returns a boolean if a field has been set.

### GetTitle

`func (o *CmsContentSummary) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *CmsContentSummary) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *CmsContentSummary) SetTitle(v string)`

SetTitle sets Title field to given value.

### HasTitle

`func (o *CmsContentSummary) HasTitle() bool`

HasTitle returns a boolean if a field has been set.

### GetUrl

`func (o *CmsContentSummary) GetUrl() string`

GetUrl returns the Url field if non-nil, zero value otherwise.

### GetUrlOk

`func (o *CmsContentSummary) GetUrlOk() (*string, bool)`

GetUrlOk returns a tuple with the Url field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrl

`func (o *CmsContentSummary) SetUrl(v string)`

SetUrl sets Url field to given value.

### HasUrl

`func (o *CmsContentSummary) HasUrl() bool`

HasUrl returns a boolean if a field has been set.

### SetUrlNil

`func (o *CmsContentSummary) SetUrlNil(b bool)`

 SetUrlNil sets the value for Url to be an explicit nil

### UnsetUrl
`func (o *CmsContentSummary) UnsetUrl()`

UnsetUrl ensures that no value is present for Url, not even an explicit nil
### GetModifiedAt

`func (o *CmsContentSummary) GetModifiedAt() time.Time`

GetModifiedAt returns the ModifiedAt field if non-nil, zero value otherwise.

### GetModifiedAtOk

`func (o *CmsContentSummary) GetModifiedAtOk() (*time.Time, bool)`

GetModifiedAtOk returns a tuple with the ModifiedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModifiedAt

`func (o *CmsContentSummary) SetModifiedAt(v time.Time)`

SetModifiedAt sets ModifiedAt field to given value.

### HasModifiedAt

`func (o *CmsContentSummary) HasModifiedAt() bool`

HasModifiedAt returns a boolean if a field has been set.

### SetModifiedAtNil

`func (o *CmsContentSummary) SetModifiedAtNil(b bool)`

 SetModifiedAtNil sets the value for ModifiedAt to be an explicit nil

### UnsetModifiedAt
`func (o *CmsContentSummary) UnsetModifiedAt()`

UnsetModifiedAt ensures that no value is present for ModifiedAt, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


