# OwnedMediaProfile

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Url** | Pointer to **string** |  | [optional] 
**Handle** | Pointer to **NullableString** | The handle, page id, store app id, subreddit or username | [optional] 
**Kind** | Pointer to **string** |  | [optional] 
**Main** | Pointer to **bool** | True for the main profile of its platform (or store), false for an extra one | [optional] 
**Store** | Pointer to **NullableString** | google_play or app_store for an app; null elsewhere | [optional] 
**Name** | Pointer to **NullableString** |  | [optional] 
**AvatarUrl** | Pointer to **NullableString** |  | [optional] 
**ScrapeStatus** | Pointer to **NullableString** | State of the profile scrape that reads its name and avatar: pending, running, ready, failed or skipped; null when none has started or the platform has none | [optional] 

## Methods

### NewOwnedMediaProfile

`func NewOwnedMediaProfile() *OwnedMediaProfile`

NewOwnedMediaProfile instantiates a new OwnedMediaProfile object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOwnedMediaProfileWithDefaults

`func NewOwnedMediaProfileWithDefaults() *OwnedMediaProfile`

NewOwnedMediaProfileWithDefaults instantiates a new OwnedMediaProfile object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUrl

`func (o *OwnedMediaProfile) GetUrl() string`

GetUrl returns the Url field if non-nil, zero value otherwise.

### GetUrlOk

`func (o *OwnedMediaProfile) GetUrlOk() (*string, bool)`

GetUrlOk returns a tuple with the Url field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrl

`func (o *OwnedMediaProfile) SetUrl(v string)`

SetUrl sets Url field to given value.

### HasUrl

`func (o *OwnedMediaProfile) HasUrl() bool`

HasUrl returns a boolean if a field has been set.

### GetHandle

`func (o *OwnedMediaProfile) GetHandle() string`

GetHandle returns the Handle field if non-nil, zero value otherwise.

### GetHandleOk

`func (o *OwnedMediaProfile) GetHandleOk() (*string, bool)`

GetHandleOk returns a tuple with the Handle field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHandle

`func (o *OwnedMediaProfile) SetHandle(v string)`

SetHandle sets Handle field to given value.

### HasHandle

`func (o *OwnedMediaProfile) HasHandle() bool`

HasHandle returns a boolean if a field has been set.

### SetHandleNil

`func (o *OwnedMediaProfile) SetHandleNil(b bool)`

 SetHandleNil sets the value for Handle to be an explicit nil

### UnsetHandle
`func (o *OwnedMediaProfile) UnsetHandle()`

UnsetHandle ensures that no value is present for Handle, not even an explicit nil
### GetKind

`func (o *OwnedMediaProfile) GetKind() string`

GetKind returns the Kind field if non-nil, zero value otherwise.

### GetKindOk

`func (o *OwnedMediaProfile) GetKindOk() (*string, bool)`

GetKindOk returns a tuple with the Kind field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKind

`func (o *OwnedMediaProfile) SetKind(v string)`

SetKind sets Kind field to given value.

### HasKind

`func (o *OwnedMediaProfile) HasKind() bool`

HasKind returns a boolean if a field has been set.

### GetMain

`func (o *OwnedMediaProfile) GetMain() bool`

GetMain returns the Main field if non-nil, zero value otherwise.

### GetMainOk

`func (o *OwnedMediaProfile) GetMainOk() (*bool, bool)`

GetMainOk returns a tuple with the Main field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMain

`func (o *OwnedMediaProfile) SetMain(v bool)`

SetMain sets Main field to given value.

### HasMain

`func (o *OwnedMediaProfile) HasMain() bool`

HasMain returns a boolean if a field has been set.

### GetStore

`func (o *OwnedMediaProfile) GetStore() string`

GetStore returns the Store field if non-nil, zero value otherwise.

### GetStoreOk

`func (o *OwnedMediaProfile) GetStoreOk() (*string, bool)`

GetStoreOk returns a tuple with the Store field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStore

`func (o *OwnedMediaProfile) SetStore(v string)`

SetStore sets Store field to given value.

### HasStore

`func (o *OwnedMediaProfile) HasStore() bool`

HasStore returns a boolean if a field has been set.

### SetStoreNil

`func (o *OwnedMediaProfile) SetStoreNil(b bool)`

 SetStoreNil sets the value for Store to be an explicit nil

### UnsetStore
`func (o *OwnedMediaProfile) UnsetStore()`

UnsetStore ensures that no value is present for Store, not even an explicit nil
### GetName

`func (o *OwnedMediaProfile) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *OwnedMediaProfile) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *OwnedMediaProfile) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *OwnedMediaProfile) HasName() bool`

HasName returns a boolean if a field has been set.

### SetNameNil

`func (o *OwnedMediaProfile) SetNameNil(b bool)`

 SetNameNil sets the value for Name to be an explicit nil

### UnsetName
`func (o *OwnedMediaProfile) UnsetName()`

UnsetName ensures that no value is present for Name, not even an explicit nil
### GetAvatarUrl

`func (o *OwnedMediaProfile) GetAvatarUrl() string`

GetAvatarUrl returns the AvatarUrl field if non-nil, zero value otherwise.

### GetAvatarUrlOk

`func (o *OwnedMediaProfile) GetAvatarUrlOk() (*string, bool)`

GetAvatarUrlOk returns a tuple with the AvatarUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAvatarUrl

`func (o *OwnedMediaProfile) SetAvatarUrl(v string)`

SetAvatarUrl sets AvatarUrl field to given value.

### HasAvatarUrl

`func (o *OwnedMediaProfile) HasAvatarUrl() bool`

HasAvatarUrl returns a boolean if a field has been set.

### SetAvatarUrlNil

`func (o *OwnedMediaProfile) SetAvatarUrlNil(b bool)`

 SetAvatarUrlNil sets the value for AvatarUrl to be an explicit nil

### UnsetAvatarUrl
`func (o *OwnedMediaProfile) UnsetAvatarUrl()`

UnsetAvatarUrl ensures that no value is present for AvatarUrl, not even an explicit nil
### GetScrapeStatus

`func (o *OwnedMediaProfile) GetScrapeStatus() string`

GetScrapeStatus returns the ScrapeStatus field if non-nil, zero value otherwise.

### GetScrapeStatusOk

`func (o *OwnedMediaProfile) GetScrapeStatusOk() (*string, bool)`

GetScrapeStatusOk returns a tuple with the ScrapeStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScrapeStatus

`func (o *OwnedMediaProfile) SetScrapeStatus(v string)`

SetScrapeStatus sets ScrapeStatus field to given value.

### HasScrapeStatus

`func (o *OwnedMediaProfile) HasScrapeStatus() bool`

HasScrapeStatus returns a boolean if a field has been set.

### SetScrapeStatusNil

`func (o *OwnedMediaProfile) SetScrapeStatusNil(b bool)`

 SetScrapeStatusNil sets the value for ScrapeStatus to be an explicit nil

### UnsetScrapeStatus
`func (o *OwnedMediaProfile) UnsetScrapeStatus()`

UnsetScrapeStatus ensures that no value is present for ScrapeStatus, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


