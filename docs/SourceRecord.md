# SourceRecord

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **int32** |  | 
**PromptExecutionId** | **int32** |  | 
**Domain** | **NullableString** | Registrable domain of the cited URL | 
**Url** | **NullableString** | Normalized cited URL (tracking parameters and fragment removed) | 
**UrlSha256** | **NullableString** | Key of the cited page, as GET /citation_intelligence/urls/{url_sha256} takes it | 
**Position** | **int32** | Rank of the citation in the answer; 0 for a background source reference with no visible rank | 
**SourceType** | **string** | owned (the project&#39;s domains), competitor or third_party | 
**IsGooglePlayLink** | **bool** |  | 
**IsAppStoreLink** | **bool** |  | 
**CreatedAt** | **time.Time** |  | 

## Methods

### NewSourceRecord

`func NewSourceRecord(id int32, promptExecutionId int32, domain NullableString, url NullableString, urlSha256 NullableString, position int32, sourceType string, isGooglePlayLink bool, isAppStoreLink bool, createdAt time.Time, ) *SourceRecord`

NewSourceRecord instantiates a new SourceRecord object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSourceRecordWithDefaults

`func NewSourceRecordWithDefaults() *SourceRecord`

NewSourceRecordWithDefaults instantiates a new SourceRecord object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *SourceRecord) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *SourceRecord) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *SourceRecord) SetId(v int32)`

SetId sets Id field to given value.


### GetPromptExecutionId

`func (o *SourceRecord) GetPromptExecutionId() int32`

GetPromptExecutionId returns the PromptExecutionId field if non-nil, zero value otherwise.

### GetPromptExecutionIdOk

`func (o *SourceRecord) GetPromptExecutionIdOk() (*int32, bool)`

GetPromptExecutionIdOk returns a tuple with the PromptExecutionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPromptExecutionId

`func (o *SourceRecord) SetPromptExecutionId(v int32)`

SetPromptExecutionId sets PromptExecutionId field to given value.


### GetDomain

`func (o *SourceRecord) GetDomain() string`

GetDomain returns the Domain field if non-nil, zero value otherwise.

### GetDomainOk

`func (o *SourceRecord) GetDomainOk() (*string, bool)`

GetDomainOk returns a tuple with the Domain field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDomain

`func (o *SourceRecord) SetDomain(v string)`

SetDomain sets Domain field to given value.


### SetDomainNil

`func (o *SourceRecord) SetDomainNil(b bool)`

 SetDomainNil sets the value for Domain to be an explicit nil

### UnsetDomain
`func (o *SourceRecord) UnsetDomain()`

UnsetDomain ensures that no value is present for Domain, not even an explicit nil
### GetUrl

`func (o *SourceRecord) GetUrl() string`

GetUrl returns the Url field if non-nil, zero value otherwise.

### GetUrlOk

`func (o *SourceRecord) GetUrlOk() (*string, bool)`

GetUrlOk returns a tuple with the Url field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrl

`func (o *SourceRecord) SetUrl(v string)`

SetUrl sets Url field to given value.


### SetUrlNil

`func (o *SourceRecord) SetUrlNil(b bool)`

 SetUrlNil sets the value for Url to be an explicit nil

### UnsetUrl
`func (o *SourceRecord) UnsetUrl()`

UnsetUrl ensures that no value is present for Url, not even an explicit nil
### GetUrlSha256

`func (o *SourceRecord) GetUrlSha256() string`

GetUrlSha256 returns the UrlSha256 field if non-nil, zero value otherwise.

### GetUrlSha256Ok

`func (o *SourceRecord) GetUrlSha256Ok() (*string, bool)`

GetUrlSha256Ok returns a tuple with the UrlSha256 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrlSha256

`func (o *SourceRecord) SetUrlSha256(v string)`

SetUrlSha256 sets UrlSha256 field to given value.


### SetUrlSha256Nil

`func (o *SourceRecord) SetUrlSha256Nil(b bool)`

 SetUrlSha256Nil sets the value for UrlSha256 to be an explicit nil

### UnsetUrlSha256
`func (o *SourceRecord) UnsetUrlSha256()`

UnsetUrlSha256 ensures that no value is present for UrlSha256, not even an explicit nil
### GetPosition

`func (o *SourceRecord) GetPosition() int32`

GetPosition returns the Position field if non-nil, zero value otherwise.

### GetPositionOk

`func (o *SourceRecord) GetPositionOk() (*int32, bool)`

GetPositionOk returns a tuple with the Position field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPosition

`func (o *SourceRecord) SetPosition(v int32)`

SetPosition sets Position field to given value.


### GetSourceType

`func (o *SourceRecord) GetSourceType() string`

GetSourceType returns the SourceType field if non-nil, zero value otherwise.

### GetSourceTypeOk

`func (o *SourceRecord) GetSourceTypeOk() (*string, bool)`

GetSourceTypeOk returns a tuple with the SourceType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSourceType

`func (o *SourceRecord) SetSourceType(v string)`

SetSourceType sets SourceType field to given value.


### GetIsGooglePlayLink

`func (o *SourceRecord) GetIsGooglePlayLink() bool`

GetIsGooglePlayLink returns the IsGooglePlayLink field if non-nil, zero value otherwise.

### GetIsGooglePlayLinkOk

`func (o *SourceRecord) GetIsGooglePlayLinkOk() (*bool, bool)`

GetIsGooglePlayLinkOk returns a tuple with the IsGooglePlayLink field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsGooglePlayLink

`func (o *SourceRecord) SetIsGooglePlayLink(v bool)`

SetIsGooglePlayLink sets IsGooglePlayLink field to given value.


### GetIsAppStoreLink

`func (o *SourceRecord) GetIsAppStoreLink() bool`

GetIsAppStoreLink returns the IsAppStoreLink field if non-nil, zero value otherwise.

### GetIsAppStoreLinkOk

`func (o *SourceRecord) GetIsAppStoreLinkOk() (*bool, bool)`

GetIsAppStoreLinkOk returns a tuple with the IsAppStoreLink field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsAppStoreLink

`func (o *SourceRecord) SetIsAppStoreLink(v bool)`

SetIsAppStoreLink sets IsAppStoreLink field to given value.


### GetCreatedAt

`func (o *SourceRecord) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *SourceRecord) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *SourceRecord) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


