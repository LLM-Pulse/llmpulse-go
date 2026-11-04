# CmsContentItem

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
**Excerpt** | Pointer to **string** | Plain-text excerpt, up to 2,000 characters | [optional] 
**ContentHtml** | Pointer to **string** | Sanitized HTML (headings, paragraphs, lists, tables, quotes, code, links with href only), up to 200,000 characters | [optional] 
**ContentTruncated** | Pointer to **bool** |  | [optional] 

## Methods

### NewCmsContentItem

`func NewCmsContentItem() *CmsContentItem`

NewCmsContentItem instantiates a new CmsContentItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCmsContentItemWithDefaults

`func NewCmsContentItemWithDefaults() *CmsContentItem`

NewCmsContentItemWithDefaults instantiates a new CmsContentItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *CmsContentItem) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *CmsContentItem) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *CmsContentItem) SetId(v int32)`

SetId sets Id field to given value.

### HasId

`func (o *CmsContentItem) HasId() bool`

HasId returns a boolean if a field has been set.

### GetType

`func (o *CmsContentItem) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *CmsContentItem) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *CmsContentItem) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *CmsContentItem) HasType() bool`

HasType returns a boolean if a field has been set.

### GetStatus

`func (o *CmsContentItem) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *CmsContentItem) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *CmsContentItem) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *CmsContentItem) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetSlug

`func (o *CmsContentItem) GetSlug() string`

GetSlug returns the Slug field if non-nil, zero value otherwise.

### GetSlugOk

`func (o *CmsContentItem) GetSlugOk() (*string, bool)`

GetSlugOk returns a tuple with the Slug field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSlug

`func (o *CmsContentItem) SetSlug(v string)`

SetSlug sets Slug field to given value.

### HasSlug

`func (o *CmsContentItem) HasSlug() bool`

HasSlug returns a boolean if a field has been set.

### GetTitle

`func (o *CmsContentItem) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *CmsContentItem) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *CmsContentItem) SetTitle(v string)`

SetTitle sets Title field to given value.

### HasTitle

`func (o *CmsContentItem) HasTitle() bool`

HasTitle returns a boolean if a field has been set.

### GetUrl

`func (o *CmsContentItem) GetUrl() string`

GetUrl returns the Url field if non-nil, zero value otherwise.

### GetUrlOk

`func (o *CmsContentItem) GetUrlOk() (*string, bool)`

GetUrlOk returns a tuple with the Url field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrl

`func (o *CmsContentItem) SetUrl(v string)`

SetUrl sets Url field to given value.

### HasUrl

`func (o *CmsContentItem) HasUrl() bool`

HasUrl returns a boolean if a field has been set.

### SetUrlNil

`func (o *CmsContentItem) SetUrlNil(b bool)`

 SetUrlNil sets the value for Url to be an explicit nil

### UnsetUrl
`func (o *CmsContentItem) UnsetUrl()`

UnsetUrl ensures that no value is present for Url, not even an explicit nil
### GetModifiedAt

`func (o *CmsContentItem) GetModifiedAt() time.Time`

GetModifiedAt returns the ModifiedAt field if non-nil, zero value otherwise.

### GetModifiedAtOk

`func (o *CmsContentItem) GetModifiedAtOk() (*time.Time, bool)`

GetModifiedAtOk returns a tuple with the ModifiedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModifiedAt

`func (o *CmsContentItem) SetModifiedAt(v time.Time)`

SetModifiedAt sets ModifiedAt field to given value.

### HasModifiedAt

`func (o *CmsContentItem) HasModifiedAt() bool`

HasModifiedAt returns a boolean if a field has been set.

### SetModifiedAtNil

`func (o *CmsContentItem) SetModifiedAtNil(b bool)`

 SetModifiedAtNil sets the value for ModifiedAt to be an explicit nil

### UnsetModifiedAt
`func (o *CmsContentItem) UnsetModifiedAt()`

UnsetModifiedAt ensures that no value is present for ModifiedAt, not even an explicit nil
### GetExcerpt

`func (o *CmsContentItem) GetExcerpt() string`

GetExcerpt returns the Excerpt field if non-nil, zero value otherwise.

### GetExcerptOk

`func (o *CmsContentItem) GetExcerptOk() (*string, bool)`

GetExcerptOk returns a tuple with the Excerpt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExcerpt

`func (o *CmsContentItem) SetExcerpt(v string)`

SetExcerpt sets Excerpt field to given value.

### HasExcerpt

`func (o *CmsContentItem) HasExcerpt() bool`

HasExcerpt returns a boolean if a field has been set.

### GetContentHtml

`func (o *CmsContentItem) GetContentHtml() string`

GetContentHtml returns the ContentHtml field if non-nil, zero value otherwise.

### GetContentHtmlOk

`func (o *CmsContentItem) GetContentHtmlOk() (*string, bool)`

GetContentHtmlOk returns a tuple with the ContentHtml field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContentHtml

`func (o *CmsContentItem) SetContentHtml(v string)`

SetContentHtml sets ContentHtml field to given value.

### HasContentHtml

`func (o *CmsContentItem) HasContentHtml() bool`

HasContentHtml returns a boolean if a field has been set.

### GetContentTruncated

`func (o *CmsContentItem) GetContentTruncated() bool`

GetContentTruncated returns the ContentTruncated field if non-nil, zero value otherwise.

### GetContentTruncatedOk

`func (o *CmsContentItem) GetContentTruncatedOk() (*bool, bool)`

GetContentTruncatedOk returns a tuple with the ContentTruncated field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContentTruncated

`func (o *CmsContentItem) SetContentTruncated(v bool)`

SetContentTruncated sets ContentTruncated field to given value.

### HasContentTruncated

`func (o *CmsContentItem) HasContentTruncated() bool`

HasContentTruncated returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


