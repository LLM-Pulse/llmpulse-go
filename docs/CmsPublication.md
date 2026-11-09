# CmsPublication

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **int32** |  | [optional] 
**Platform** | Pointer to **string** |  | [optional] 
**SiteUrl** | Pointer to **string** |  | [optional] 
**Status** | Pointer to **string** | queued and sending are on their way; unknown means a send timed out and the next attempt looks the draft up before creating one; drafted carries remote_id and edit_url; failed carries error_code | [optional] 
**Title** | Pointer to **string** |  | [optional] 
**Slug** | Pointer to **string** |  | [optional] 
**SourceUrl** | Pointer to **NullableString** | For an update task, the page the draft revises | [optional] 
**RemoteId** | Pointer to **NullableInt32** | WordPress post id of the draft | [optional] 
**RemoteStatus** | Pointer to **NullableString** | WordPress status of the post when the draft was created (draft) | [optional] 
**RemoteUrl** | Pointer to **NullableString** |  | [optional] 
**EditUrl** | Pointer to **NullableString** | The post&#39;s edit screen in the WordPress admin | [optional] 
**ErrorCode** | Pointer to **NullableString** | Why the send failed, the same token as error.meta.reason, for example reconnect_required, authorization_header_lost, missing_capability, firewall_blocked, timeout, unreachable or rejected | [optional] 
**CreatedAt** | Pointer to **time.Time** |  | [optional] 
**SentAt** | Pointer to **NullableTime** |  | [optional] 

## Methods

### NewCmsPublication

`func NewCmsPublication() *CmsPublication`

NewCmsPublication instantiates a new CmsPublication object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCmsPublicationWithDefaults

`func NewCmsPublicationWithDefaults() *CmsPublication`

NewCmsPublicationWithDefaults instantiates a new CmsPublication object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *CmsPublication) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *CmsPublication) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *CmsPublication) SetId(v int32)`

SetId sets Id field to given value.

### HasId

`func (o *CmsPublication) HasId() bool`

HasId returns a boolean if a field has been set.

### GetPlatform

`func (o *CmsPublication) GetPlatform() string`

GetPlatform returns the Platform field if non-nil, zero value otherwise.

### GetPlatformOk

`func (o *CmsPublication) GetPlatformOk() (*string, bool)`

GetPlatformOk returns a tuple with the Platform field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlatform

`func (o *CmsPublication) SetPlatform(v string)`

SetPlatform sets Platform field to given value.

### HasPlatform

`func (o *CmsPublication) HasPlatform() bool`

HasPlatform returns a boolean if a field has been set.

### GetSiteUrl

`func (o *CmsPublication) GetSiteUrl() string`

GetSiteUrl returns the SiteUrl field if non-nil, zero value otherwise.

### GetSiteUrlOk

`func (o *CmsPublication) GetSiteUrlOk() (*string, bool)`

GetSiteUrlOk returns a tuple with the SiteUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSiteUrl

`func (o *CmsPublication) SetSiteUrl(v string)`

SetSiteUrl sets SiteUrl field to given value.

### HasSiteUrl

`func (o *CmsPublication) HasSiteUrl() bool`

HasSiteUrl returns a boolean if a field has been set.

### GetStatus

`func (o *CmsPublication) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *CmsPublication) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *CmsPublication) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *CmsPublication) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetTitle

`func (o *CmsPublication) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *CmsPublication) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *CmsPublication) SetTitle(v string)`

SetTitle sets Title field to given value.

### HasTitle

`func (o *CmsPublication) HasTitle() bool`

HasTitle returns a boolean if a field has been set.

### GetSlug

`func (o *CmsPublication) GetSlug() string`

GetSlug returns the Slug field if non-nil, zero value otherwise.

### GetSlugOk

`func (o *CmsPublication) GetSlugOk() (*string, bool)`

GetSlugOk returns a tuple with the Slug field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSlug

`func (o *CmsPublication) SetSlug(v string)`

SetSlug sets Slug field to given value.

### HasSlug

`func (o *CmsPublication) HasSlug() bool`

HasSlug returns a boolean if a field has been set.

### GetSourceUrl

`func (o *CmsPublication) GetSourceUrl() string`

GetSourceUrl returns the SourceUrl field if non-nil, zero value otherwise.

### GetSourceUrlOk

`func (o *CmsPublication) GetSourceUrlOk() (*string, bool)`

GetSourceUrlOk returns a tuple with the SourceUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSourceUrl

`func (o *CmsPublication) SetSourceUrl(v string)`

SetSourceUrl sets SourceUrl field to given value.

### HasSourceUrl

`func (o *CmsPublication) HasSourceUrl() bool`

HasSourceUrl returns a boolean if a field has been set.

### SetSourceUrlNil

`func (o *CmsPublication) SetSourceUrlNil(b bool)`

 SetSourceUrlNil sets the value for SourceUrl to be an explicit nil

### UnsetSourceUrl
`func (o *CmsPublication) UnsetSourceUrl()`

UnsetSourceUrl ensures that no value is present for SourceUrl, not even an explicit nil
### GetRemoteId

`func (o *CmsPublication) GetRemoteId() int32`

GetRemoteId returns the RemoteId field if non-nil, zero value otherwise.

### GetRemoteIdOk

`func (o *CmsPublication) GetRemoteIdOk() (*int32, bool)`

GetRemoteIdOk returns a tuple with the RemoteId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRemoteId

`func (o *CmsPublication) SetRemoteId(v int32)`

SetRemoteId sets RemoteId field to given value.

### HasRemoteId

`func (o *CmsPublication) HasRemoteId() bool`

HasRemoteId returns a boolean if a field has been set.

### SetRemoteIdNil

`func (o *CmsPublication) SetRemoteIdNil(b bool)`

 SetRemoteIdNil sets the value for RemoteId to be an explicit nil

### UnsetRemoteId
`func (o *CmsPublication) UnsetRemoteId()`

UnsetRemoteId ensures that no value is present for RemoteId, not even an explicit nil
### GetRemoteStatus

`func (o *CmsPublication) GetRemoteStatus() string`

GetRemoteStatus returns the RemoteStatus field if non-nil, zero value otherwise.

### GetRemoteStatusOk

`func (o *CmsPublication) GetRemoteStatusOk() (*string, bool)`

GetRemoteStatusOk returns a tuple with the RemoteStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRemoteStatus

`func (o *CmsPublication) SetRemoteStatus(v string)`

SetRemoteStatus sets RemoteStatus field to given value.

### HasRemoteStatus

`func (o *CmsPublication) HasRemoteStatus() bool`

HasRemoteStatus returns a boolean if a field has been set.

### SetRemoteStatusNil

`func (o *CmsPublication) SetRemoteStatusNil(b bool)`

 SetRemoteStatusNil sets the value for RemoteStatus to be an explicit nil

### UnsetRemoteStatus
`func (o *CmsPublication) UnsetRemoteStatus()`

UnsetRemoteStatus ensures that no value is present for RemoteStatus, not even an explicit nil
### GetRemoteUrl

`func (o *CmsPublication) GetRemoteUrl() string`

GetRemoteUrl returns the RemoteUrl field if non-nil, zero value otherwise.

### GetRemoteUrlOk

`func (o *CmsPublication) GetRemoteUrlOk() (*string, bool)`

GetRemoteUrlOk returns a tuple with the RemoteUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRemoteUrl

`func (o *CmsPublication) SetRemoteUrl(v string)`

SetRemoteUrl sets RemoteUrl field to given value.

### HasRemoteUrl

`func (o *CmsPublication) HasRemoteUrl() bool`

HasRemoteUrl returns a boolean if a field has been set.

### SetRemoteUrlNil

`func (o *CmsPublication) SetRemoteUrlNil(b bool)`

 SetRemoteUrlNil sets the value for RemoteUrl to be an explicit nil

### UnsetRemoteUrl
`func (o *CmsPublication) UnsetRemoteUrl()`

UnsetRemoteUrl ensures that no value is present for RemoteUrl, not even an explicit nil
### GetEditUrl

`func (o *CmsPublication) GetEditUrl() string`

GetEditUrl returns the EditUrl field if non-nil, zero value otherwise.

### GetEditUrlOk

`func (o *CmsPublication) GetEditUrlOk() (*string, bool)`

GetEditUrlOk returns a tuple with the EditUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEditUrl

`func (o *CmsPublication) SetEditUrl(v string)`

SetEditUrl sets EditUrl field to given value.

### HasEditUrl

`func (o *CmsPublication) HasEditUrl() bool`

HasEditUrl returns a boolean if a field has been set.

### SetEditUrlNil

`func (o *CmsPublication) SetEditUrlNil(b bool)`

 SetEditUrlNil sets the value for EditUrl to be an explicit nil

### UnsetEditUrl
`func (o *CmsPublication) UnsetEditUrl()`

UnsetEditUrl ensures that no value is present for EditUrl, not even an explicit nil
### GetErrorCode

`func (o *CmsPublication) GetErrorCode() string`

GetErrorCode returns the ErrorCode field if non-nil, zero value otherwise.

### GetErrorCodeOk

`func (o *CmsPublication) GetErrorCodeOk() (*string, bool)`

GetErrorCodeOk returns a tuple with the ErrorCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrorCode

`func (o *CmsPublication) SetErrorCode(v string)`

SetErrorCode sets ErrorCode field to given value.

### HasErrorCode

`func (o *CmsPublication) HasErrorCode() bool`

HasErrorCode returns a boolean if a field has been set.

### SetErrorCodeNil

`func (o *CmsPublication) SetErrorCodeNil(b bool)`

 SetErrorCodeNil sets the value for ErrorCode to be an explicit nil

### UnsetErrorCode
`func (o *CmsPublication) UnsetErrorCode()`

UnsetErrorCode ensures that no value is present for ErrorCode, not even an explicit nil
### GetCreatedAt

`func (o *CmsPublication) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *CmsPublication) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *CmsPublication) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *CmsPublication) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetSentAt

`func (o *CmsPublication) GetSentAt() time.Time`

GetSentAt returns the SentAt field if non-nil, zero value otherwise.

### GetSentAtOk

`func (o *CmsPublication) GetSentAtOk() (*time.Time, bool)`

GetSentAtOk returns a tuple with the SentAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSentAt

`func (o *CmsPublication) SetSentAt(v time.Time)`

SetSentAt sets SentAt field to given value.

### HasSentAt

`func (o *CmsPublication) HasSentAt() bool`

HasSentAt returns a boolean if a field has been set.

### SetSentAtNil

`func (o *CmsPublication) SetSentAtNil(b bool)`

 SetSentAtNil sets the value for SentAt to be an explicit nil

### UnsetSentAt
`func (o *CmsPublication) UnsetSentAt()`

UnsetSentAt ensures that no value is present for SentAt, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


