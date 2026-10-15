# OwnedMediaRow

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Title** | Pointer to **NullableString** |  | [optional] 
**Url** | Pointer to **NullableString** |  | [optional] 
**ChannelName** | Pointer to **NullableString** |  | [optional] 
**ChannelHandle** | Pointer to **NullableString** | The video&#39;s channel handle, without the @ | [optional] 
**ChannelUrl** | Pointer to **NullableString** |  | [optional] 
**VideoId** | Pointer to **NullableString** |  | [optional] 
**Key** | Pointer to **string** | The channel key (handle:..., channel:... or name:...), accepted as profile by /dimensions/owned_media/citing_prompts | [optional] 
**Name** | Pointer to **NullableString** |  | [optional] 
**Handle** | Pointer to **NullableString** |  | [optional] 
**Caption** | Pointer to **NullableString** |  | [optional] 
**OwnerHandle** | Pointer to **NullableString** |  | [optional] 
**ThumbnailUrl** | Pointer to **NullableString** | The post or video image. Our cached copy where one exists, so the link does not expire | [optional] 
**AvatarUrl** | Pointer to **NullableString** | The profile or channel image. Our cached copy where one exists | [optional] 
**ContentType** | Pointer to **NullableString** | The post format on its platform: reel, post or tv on Instagram, post or pulse on LinkedIn, post elsewhere | [optional] 
**Citations** | Pointer to **int32** |  | [optional] 
**UniqueVideos** | Pointer to **int32** |  | [optional] 
**UniquePosts** | Pointer to **int32** |  | [optional] 
**Followers** | Pointer to **NullableInt32** |  | [optional] 
**Likes** | Pointer to **NullableInt32** |  | [optional] 
**Comments** | Pointer to **NullableInt32** |  | [optional] 
**Views** | Pointer to **interface{}** | View count as the platform reports it, a number or a numeric string, or null when unknown | [optional] 
**PublishedAt** | Pointer to **NullableString** | Publication date as the platform reports it | [optional] 
**PostedAt** | Pointer to **NullableString** | Publication date as the platform reports it (ISO 8601, or Unix seconds on TikTok) | [optional] 
**AvgPosition** | Pointer to **NullableFloat32** | Average position of the citation in the answers (1 &#x3D; first); null when unknown | [optional] 
**Yours** | Pointer to **bool** |  | [optional] 
**CitationDate** | Pointer to **NullableTime** |  | [optional] 
**Position** | Pointer to **NullableInt32** |  | [optional] 
**Model** | Pointer to **NullableString** |  | [optional] 
**Domain** | Pointer to **string** | The app&#39;s store listing URL (provider&#x3D;mobile_apps) | [optional] 
**TotalResponses** | Pointer to **int32** |  | [optional] 
**Rank** | Pointer to **int32** |  | [optional] 
**GlobalRank** | Pointer to **NullableInt32** |  | [optional] 

## Methods

### NewOwnedMediaRow

`func NewOwnedMediaRow() *OwnedMediaRow`

NewOwnedMediaRow instantiates a new OwnedMediaRow object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOwnedMediaRowWithDefaults

`func NewOwnedMediaRowWithDefaults() *OwnedMediaRow`

NewOwnedMediaRowWithDefaults instantiates a new OwnedMediaRow object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTitle

`func (o *OwnedMediaRow) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *OwnedMediaRow) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *OwnedMediaRow) SetTitle(v string)`

SetTitle sets Title field to given value.

### HasTitle

`func (o *OwnedMediaRow) HasTitle() bool`

HasTitle returns a boolean if a field has been set.

### SetTitleNil

`func (o *OwnedMediaRow) SetTitleNil(b bool)`

 SetTitleNil sets the value for Title to be an explicit nil

### UnsetTitle
`func (o *OwnedMediaRow) UnsetTitle()`

UnsetTitle ensures that no value is present for Title, not even an explicit nil
### GetUrl

`func (o *OwnedMediaRow) GetUrl() string`

GetUrl returns the Url field if non-nil, zero value otherwise.

### GetUrlOk

`func (o *OwnedMediaRow) GetUrlOk() (*string, bool)`

GetUrlOk returns a tuple with the Url field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrl

`func (o *OwnedMediaRow) SetUrl(v string)`

SetUrl sets Url field to given value.

### HasUrl

`func (o *OwnedMediaRow) HasUrl() bool`

HasUrl returns a boolean if a field has been set.

### SetUrlNil

`func (o *OwnedMediaRow) SetUrlNil(b bool)`

 SetUrlNil sets the value for Url to be an explicit nil

### UnsetUrl
`func (o *OwnedMediaRow) UnsetUrl()`

UnsetUrl ensures that no value is present for Url, not even an explicit nil
### GetChannelName

`func (o *OwnedMediaRow) GetChannelName() string`

GetChannelName returns the ChannelName field if non-nil, zero value otherwise.

### GetChannelNameOk

`func (o *OwnedMediaRow) GetChannelNameOk() (*string, bool)`

GetChannelNameOk returns a tuple with the ChannelName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChannelName

`func (o *OwnedMediaRow) SetChannelName(v string)`

SetChannelName sets ChannelName field to given value.

### HasChannelName

`func (o *OwnedMediaRow) HasChannelName() bool`

HasChannelName returns a boolean if a field has been set.

### SetChannelNameNil

`func (o *OwnedMediaRow) SetChannelNameNil(b bool)`

 SetChannelNameNil sets the value for ChannelName to be an explicit nil

### UnsetChannelName
`func (o *OwnedMediaRow) UnsetChannelName()`

UnsetChannelName ensures that no value is present for ChannelName, not even an explicit nil
### GetChannelHandle

`func (o *OwnedMediaRow) GetChannelHandle() string`

GetChannelHandle returns the ChannelHandle field if non-nil, zero value otherwise.

### GetChannelHandleOk

`func (o *OwnedMediaRow) GetChannelHandleOk() (*string, bool)`

GetChannelHandleOk returns a tuple with the ChannelHandle field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChannelHandle

`func (o *OwnedMediaRow) SetChannelHandle(v string)`

SetChannelHandle sets ChannelHandle field to given value.

### HasChannelHandle

`func (o *OwnedMediaRow) HasChannelHandle() bool`

HasChannelHandle returns a boolean if a field has been set.

### SetChannelHandleNil

`func (o *OwnedMediaRow) SetChannelHandleNil(b bool)`

 SetChannelHandleNil sets the value for ChannelHandle to be an explicit nil

### UnsetChannelHandle
`func (o *OwnedMediaRow) UnsetChannelHandle()`

UnsetChannelHandle ensures that no value is present for ChannelHandle, not even an explicit nil
### GetChannelUrl

`func (o *OwnedMediaRow) GetChannelUrl() string`

GetChannelUrl returns the ChannelUrl field if non-nil, zero value otherwise.

### GetChannelUrlOk

`func (o *OwnedMediaRow) GetChannelUrlOk() (*string, bool)`

GetChannelUrlOk returns a tuple with the ChannelUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChannelUrl

`func (o *OwnedMediaRow) SetChannelUrl(v string)`

SetChannelUrl sets ChannelUrl field to given value.

### HasChannelUrl

`func (o *OwnedMediaRow) HasChannelUrl() bool`

HasChannelUrl returns a boolean if a field has been set.

### SetChannelUrlNil

`func (o *OwnedMediaRow) SetChannelUrlNil(b bool)`

 SetChannelUrlNil sets the value for ChannelUrl to be an explicit nil

### UnsetChannelUrl
`func (o *OwnedMediaRow) UnsetChannelUrl()`

UnsetChannelUrl ensures that no value is present for ChannelUrl, not even an explicit nil
### GetVideoId

`func (o *OwnedMediaRow) GetVideoId() string`

GetVideoId returns the VideoId field if non-nil, zero value otherwise.

### GetVideoIdOk

`func (o *OwnedMediaRow) GetVideoIdOk() (*string, bool)`

GetVideoIdOk returns a tuple with the VideoId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVideoId

`func (o *OwnedMediaRow) SetVideoId(v string)`

SetVideoId sets VideoId field to given value.

### HasVideoId

`func (o *OwnedMediaRow) HasVideoId() bool`

HasVideoId returns a boolean if a field has been set.

### SetVideoIdNil

`func (o *OwnedMediaRow) SetVideoIdNil(b bool)`

 SetVideoIdNil sets the value for VideoId to be an explicit nil

### UnsetVideoId
`func (o *OwnedMediaRow) UnsetVideoId()`

UnsetVideoId ensures that no value is present for VideoId, not even an explicit nil
### GetKey

`func (o *OwnedMediaRow) GetKey() string`

GetKey returns the Key field if non-nil, zero value otherwise.

### GetKeyOk

`func (o *OwnedMediaRow) GetKeyOk() (*string, bool)`

GetKeyOk returns a tuple with the Key field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKey

`func (o *OwnedMediaRow) SetKey(v string)`

SetKey sets Key field to given value.

### HasKey

`func (o *OwnedMediaRow) HasKey() bool`

HasKey returns a boolean if a field has been set.

### GetName

`func (o *OwnedMediaRow) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *OwnedMediaRow) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *OwnedMediaRow) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *OwnedMediaRow) HasName() bool`

HasName returns a boolean if a field has been set.

### SetNameNil

`func (o *OwnedMediaRow) SetNameNil(b bool)`

 SetNameNil sets the value for Name to be an explicit nil

### UnsetName
`func (o *OwnedMediaRow) UnsetName()`

UnsetName ensures that no value is present for Name, not even an explicit nil
### GetHandle

`func (o *OwnedMediaRow) GetHandle() string`

GetHandle returns the Handle field if non-nil, zero value otherwise.

### GetHandleOk

`func (o *OwnedMediaRow) GetHandleOk() (*string, bool)`

GetHandleOk returns a tuple with the Handle field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHandle

`func (o *OwnedMediaRow) SetHandle(v string)`

SetHandle sets Handle field to given value.

### HasHandle

`func (o *OwnedMediaRow) HasHandle() bool`

HasHandle returns a boolean if a field has been set.

### SetHandleNil

`func (o *OwnedMediaRow) SetHandleNil(b bool)`

 SetHandleNil sets the value for Handle to be an explicit nil

### UnsetHandle
`func (o *OwnedMediaRow) UnsetHandle()`

UnsetHandle ensures that no value is present for Handle, not even an explicit nil
### GetCaption

`func (o *OwnedMediaRow) GetCaption() string`

GetCaption returns the Caption field if non-nil, zero value otherwise.

### GetCaptionOk

`func (o *OwnedMediaRow) GetCaptionOk() (*string, bool)`

GetCaptionOk returns a tuple with the Caption field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCaption

`func (o *OwnedMediaRow) SetCaption(v string)`

SetCaption sets Caption field to given value.

### HasCaption

`func (o *OwnedMediaRow) HasCaption() bool`

HasCaption returns a boolean if a field has been set.

### SetCaptionNil

`func (o *OwnedMediaRow) SetCaptionNil(b bool)`

 SetCaptionNil sets the value for Caption to be an explicit nil

### UnsetCaption
`func (o *OwnedMediaRow) UnsetCaption()`

UnsetCaption ensures that no value is present for Caption, not even an explicit nil
### GetOwnerHandle

`func (o *OwnedMediaRow) GetOwnerHandle() string`

GetOwnerHandle returns the OwnerHandle field if non-nil, zero value otherwise.

### GetOwnerHandleOk

`func (o *OwnedMediaRow) GetOwnerHandleOk() (*string, bool)`

GetOwnerHandleOk returns a tuple with the OwnerHandle field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOwnerHandle

`func (o *OwnedMediaRow) SetOwnerHandle(v string)`

SetOwnerHandle sets OwnerHandle field to given value.

### HasOwnerHandle

`func (o *OwnedMediaRow) HasOwnerHandle() bool`

HasOwnerHandle returns a boolean if a field has been set.

### SetOwnerHandleNil

`func (o *OwnedMediaRow) SetOwnerHandleNil(b bool)`

 SetOwnerHandleNil sets the value for OwnerHandle to be an explicit nil

### UnsetOwnerHandle
`func (o *OwnedMediaRow) UnsetOwnerHandle()`

UnsetOwnerHandle ensures that no value is present for OwnerHandle, not even an explicit nil
### GetThumbnailUrl

`func (o *OwnedMediaRow) GetThumbnailUrl() string`

GetThumbnailUrl returns the ThumbnailUrl field if non-nil, zero value otherwise.

### GetThumbnailUrlOk

`func (o *OwnedMediaRow) GetThumbnailUrlOk() (*string, bool)`

GetThumbnailUrlOk returns a tuple with the ThumbnailUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetThumbnailUrl

`func (o *OwnedMediaRow) SetThumbnailUrl(v string)`

SetThumbnailUrl sets ThumbnailUrl field to given value.

### HasThumbnailUrl

`func (o *OwnedMediaRow) HasThumbnailUrl() bool`

HasThumbnailUrl returns a boolean if a field has been set.

### SetThumbnailUrlNil

`func (o *OwnedMediaRow) SetThumbnailUrlNil(b bool)`

 SetThumbnailUrlNil sets the value for ThumbnailUrl to be an explicit nil

### UnsetThumbnailUrl
`func (o *OwnedMediaRow) UnsetThumbnailUrl()`

UnsetThumbnailUrl ensures that no value is present for ThumbnailUrl, not even an explicit nil
### GetAvatarUrl

`func (o *OwnedMediaRow) GetAvatarUrl() string`

GetAvatarUrl returns the AvatarUrl field if non-nil, zero value otherwise.

### GetAvatarUrlOk

`func (o *OwnedMediaRow) GetAvatarUrlOk() (*string, bool)`

GetAvatarUrlOk returns a tuple with the AvatarUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAvatarUrl

`func (o *OwnedMediaRow) SetAvatarUrl(v string)`

SetAvatarUrl sets AvatarUrl field to given value.

### HasAvatarUrl

`func (o *OwnedMediaRow) HasAvatarUrl() bool`

HasAvatarUrl returns a boolean if a field has been set.

### SetAvatarUrlNil

`func (o *OwnedMediaRow) SetAvatarUrlNil(b bool)`

 SetAvatarUrlNil sets the value for AvatarUrl to be an explicit nil

### UnsetAvatarUrl
`func (o *OwnedMediaRow) UnsetAvatarUrl()`

UnsetAvatarUrl ensures that no value is present for AvatarUrl, not even an explicit nil
### GetContentType

`func (o *OwnedMediaRow) GetContentType() string`

GetContentType returns the ContentType field if non-nil, zero value otherwise.

### GetContentTypeOk

`func (o *OwnedMediaRow) GetContentTypeOk() (*string, bool)`

GetContentTypeOk returns a tuple with the ContentType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContentType

`func (o *OwnedMediaRow) SetContentType(v string)`

SetContentType sets ContentType field to given value.

### HasContentType

`func (o *OwnedMediaRow) HasContentType() bool`

HasContentType returns a boolean if a field has been set.

### SetContentTypeNil

`func (o *OwnedMediaRow) SetContentTypeNil(b bool)`

 SetContentTypeNil sets the value for ContentType to be an explicit nil

### UnsetContentType
`func (o *OwnedMediaRow) UnsetContentType()`

UnsetContentType ensures that no value is present for ContentType, not even an explicit nil
### GetCitations

`func (o *OwnedMediaRow) GetCitations() int32`

GetCitations returns the Citations field if non-nil, zero value otherwise.

### GetCitationsOk

`func (o *OwnedMediaRow) GetCitationsOk() (*int32, bool)`

GetCitationsOk returns a tuple with the Citations field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCitations

`func (o *OwnedMediaRow) SetCitations(v int32)`

SetCitations sets Citations field to given value.

### HasCitations

`func (o *OwnedMediaRow) HasCitations() bool`

HasCitations returns a boolean if a field has been set.

### GetUniqueVideos

`func (o *OwnedMediaRow) GetUniqueVideos() int32`

GetUniqueVideos returns the UniqueVideos field if non-nil, zero value otherwise.

### GetUniqueVideosOk

`func (o *OwnedMediaRow) GetUniqueVideosOk() (*int32, bool)`

GetUniqueVideosOk returns a tuple with the UniqueVideos field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUniqueVideos

`func (o *OwnedMediaRow) SetUniqueVideos(v int32)`

SetUniqueVideos sets UniqueVideos field to given value.

### HasUniqueVideos

`func (o *OwnedMediaRow) HasUniqueVideos() bool`

HasUniqueVideos returns a boolean if a field has been set.

### GetUniquePosts

`func (o *OwnedMediaRow) GetUniquePosts() int32`

GetUniquePosts returns the UniquePosts field if non-nil, zero value otherwise.

### GetUniquePostsOk

`func (o *OwnedMediaRow) GetUniquePostsOk() (*int32, bool)`

GetUniquePostsOk returns a tuple with the UniquePosts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUniquePosts

`func (o *OwnedMediaRow) SetUniquePosts(v int32)`

SetUniquePosts sets UniquePosts field to given value.

### HasUniquePosts

`func (o *OwnedMediaRow) HasUniquePosts() bool`

HasUniquePosts returns a boolean if a field has been set.

### GetFollowers

`func (o *OwnedMediaRow) GetFollowers() int32`

GetFollowers returns the Followers field if non-nil, zero value otherwise.

### GetFollowersOk

`func (o *OwnedMediaRow) GetFollowersOk() (*int32, bool)`

GetFollowersOk returns a tuple with the Followers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFollowers

`func (o *OwnedMediaRow) SetFollowers(v int32)`

SetFollowers sets Followers field to given value.

### HasFollowers

`func (o *OwnedMediaRow) HasFollowers() bool`

HasFollowers returns a boolean if a field has been set.

### SetFollowersNil

`func (o *OwnedMediaRow) SetFollowersNil(b bool)`

 SetFollowersNil sets the value for Followers to be an explicit nil

### UnsetFollowers
`func (o *OwnedMediaRow) UnsetFollowers()`

UnsetFollowers ensures that no value is present for Followers, not even an explicit nil
### GetLikes

`func (o *OwnedMediaRow) GetLikes() int32`

GetLikes returns the Likes field if non-nil, zero value otherwise.

### GetLikesOk

`func (o *OwnedMediaRow) GetLikesOk() (*int32, bool)`

GetLikesOk returns a tuple with the Likes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLikes

`func (o *OwnedMediaRow) SetLikes(v int32)`

SetLikes sets Likes field to given value.

### HasLikes

`func (o *OwnedMediaRow) HasLikes() bool`

HasLikes returns a boolean if a field has been set.

### SetLikesNil

`func (o *OwnedMediaRow) SetLikesNil(b bool)`

 SetLikesNil sets the value for Likes to be an explicit nil

### UnsetLikes
`func (o *OwnedMediaRow) UnsetLikes()`

UnsetLikes ensures that no value is present for Likes, not even an explicit nil
### GetComments

`func (o *OwnedMediaRow) GetComments() int32`

GetComments returns the Comments field if non-nil, zero value otherwise.

### GetCommentsOk

`func (o *OwnedMediaRow) GetCommentsOk() (*int32, bool)`

GetCommentsOk returns a tuple with the Comments field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComments

`func (o *OwnedMediaRow) SetComments(v int32)`

SetComments sets Comments field to given value.

### HasComments

`func (o *OwnedMediaRow) HasComments() bool`

HasComments returns a boolean if a field has been set.

### SetCommentsNil

`func (o *OwnedMediaRow) SetCommentsNil(b bool)`

 SetCommentsNil sets the value for Comments to be an explicit nil

### UnsetComments
`func (o *OwnedMediaRow) UnsetComments()`

UnsetComments ensures that no value is present for Comments, not even an explicit nil
### GetViews

`func (o *OwnedMediaRow) GetViews() interface{}`

GetViews returns the Views field if non-nil, zero value otherwise.

### GetViewsOk

`func (o *OwnedMediaRow) GetViewsOk() (*interface{}, bool)`

GetViewsOk returns a tuple with the Views field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetViews

`func (o *OwnedMediaRow) SetViews(v interface{})`

SetViews sets Views field to given value.

### HasViews

`func (o *OwnedMediaRow) HasViews() bool`

HasViews returns a boolean if a field has been set.

### SetViewsNil

`func (o *OwnedMediaRow) SetViewsNil(b bool)`

 SetViewsNil sets the value for Views to be an explicit nil

### UnsetViews
`func (o *OwnedMediaRow) UnsetViews()`

UnsetViews ensures that no value is present for Views, not even an explicit nil
### GetPublishedAt

`func (o *OwnedMediaRow) GetPublishedAt() string`

GetPublishedAt returns the PublishedAt field if non-nil, zero value otherwise.

### GetPublishedAtOk

`func (o *OwnedMediaRow) GetPublishedAtOk() (*string, bool)`

GetPublishedAtOk returns a tuple with the PublishedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPublishedAt

`func (o *OwnedMediaRow) SetPublishedAt(v string)`

SetPublishedAt sets PublishedAt field to given value.

### HasPublishedAt

`func (o *OwnedMediaRow) HasPublishedAt() bool`

HasPublishedAt returns a boolean if a field has been set.

### SetPublishedAtNil

`func (o *OwnedMediaRow) SetPublishedAtNil(b bool)`

 SetPublishedAtNil sets the value for PublishedAt to be an explicit nil

### UnsetPublishedAt
`func (o *OwnedMediaRow) UnsetPublishedAt()`

UnsetPublishedAt ensures that no value is present for PublishedAt, not even an explicit nil
### GetPostedAt

`func (o *OwnedMediaRow) GetPostedAt() string`

GetPostedAt returns the PostedAt field if non-nil, zero value otherwise.

### GetPostedAtOk

`func (o *OwnedMediaRow) GetPostedAtOk() (*string, bool)`

GetPostedAtOk returns a tuple with the PostedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPostedAt

`func (o *OwnedMediaRow) SetPostedAt(v string)`

SetPostedAt sets PostedAt field to given value.

### HasPostedAt

`func (o *OwnedMediaRow) HasPostedAt() bool`

HasPostedAt returns a boolean if a field has been set.

### SetPostedAtNil

`func (o *OwnedMediaRow) SetPostedAtNil(b bool)`

 SetPostedAtNil sets the value for PostedAt to be an explicit nil

### UnsetPostedAt
`func (o *OwnedMediaRow) UnsetPostedAt()`

UnsetPostedAt ensures that no value is present for PostedAt, not even an explicit nil
### GetAvgPosition

`func (o *OwnedMediaRow) GetAvgPosition() float32`

GetAvgPosition returns the AvgPosition field if non-nil, zero value otherwise.

### GetAvgPositionOk

`func (o *OwnedMediaRow) GetAvgPositionOk() (*float32, bool)`

GetAvgPositionOk returns a tuple with the AvgPosition field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAvgPosition

`func (o *OwnedMediaRow) SetAvgPosition(v float32)`

SetAvgPosition sets AvgPosition field to given value.

### HasAvgPosition

`func (o *OwnedMediaRow) HasAvgPosition() bool`

HasAvgPosition returns a boolean if a field has been set.

### SetAvgPositionNil

`func (o *OwnedMediaRow) SetAvgPositionNil(b bool)`

 SetAvgPositionNil sets the value for AvgPosition to be an explicit nil

### UnsetAvgPosition
`func (o *OwnedMediaRow) UnsetAvgPosition()`

UnsetAvgPosition ensures that no value is present for AvgPosition, not even an explicit nil
### GetYours

`func (o *OwnedMediaRow) GetYours() bool`

GetYours returns the Yours field if non-nil, zero value otherwise.

### GetYoursOk

`func (o *OwnedMediaRow) GetYoursOk() (*bool, bool)`

GetYoursOk returns a tuple with the Yours field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetYours

`func (o *OwnedMediaRow) SetYours(v bool)`

SetYours sets Yours field to given value.

### HasYours

`func (o *OwnedMediaRow) HasYours() bool`

HasYours returns a boolean if a field has been set.

### GetCitationDate

`func (o *OwnedMediaRow) GetCitationDate() time.Time`

GetCitationDate returns the CitationDate field if non-nil, zero value otherwise.

### GetCitationDateOk

`func (o *OwnedMediaRow) GetCitationDateOk() (*time.Time, bool)`

GetCitationDateOk returns a tuple with the CitationDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCitationDate

`func (o *OwnedMediaRow) SetCitationDate(v time.Time)`

SetCitationDate sets CitationDate field to given value.

### HasCitationDate

`func (o *OwnedMediaRow) HasCitationDate() bool`

HasCitationDate returns a boolean if a field has been set.

### SetCitationDateNil

`func (o *OwnedMediaRow) SetCitationDateNil(b bool)`

 SetCitationDateNil sets the value for CitationDate to be an explicit nil

### UnsetCitationDate
`func (o *OwnedMediaRow) UnsetCitationDate()`

UnsetCitationDate ensures that no value is present for CitationDate, not even an explicit nil
### GetPosition

`func (o *OwnedMediaRow) GetPosition() int32`

GetPosition returns the Position field if non-nil, zero value otherwise.

### GetPositionOk

`func (o *OwnedMediaRow) GetPositionOk() (*int32, bool)`

GetPositionOk returns a tuple with the Position field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPosition

`func (o *OwnedMediaRow) SetPosition(v int32)`

SetPosition sets Position field to given value.

### HasPosition

`func (o *OwnedMediaRow) HasPosition() bool`

HasPosition returns a boolean if a field has been set.

### SetPositionNil

`func (o *OwnedMediaRow) SetPositionNil(b bool)`

 SetPositionNil sets the value for Position to be an explicit nil

### UnsetPosition
`func (o *OwnedMediaRow) UnsetPosition()`

UnsetPosition ensures that no value is present for Position, not even an explicit nil
### GetModel

`func (o *OwnedMediaRow) GetModel() string`

GetModel returns the Model field if non-nil, zero value otherwise.

### GetModelOk

`func (o *OwnedMediaRow) GetModelOk() (*string, bool)`

GetModelOk returns a tuple with the Model field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModel

`func (o *OwnedMediaRow) SetModel(v string)`

SetModel sets Model field to given value.

### HasModel

`func (o *OwnedMediaRow) HasModel() bool`

HasModel returns a boolean if a field has been set.

### SetModelNil

`func (o *OwnedMediaRow) SetModelNil(b bool)`

 SetModelNil sets the value for Model to be an explicit nil

### UnsetModel
`func (o *OwnedMediaRow) UnsetModel()`

UnsetModel ensures that no value is present for Model, not even an explicit nil
### GetDomain

`func (o *OwnedMediaRow) GetDomain() string`

GetDomain returns the Domain field if non-nil, zero value otherwise.

### GetDomainOk

`func (o *OwnedMediaRow) GetDomainOk() (*string, bool)`

GetDomainOk returns a tuple with the Domain field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDomain

`func (o *OwnedMediaRow) SetDomain(v string)`

SetDomain sets Domain field to given value.

### HasDomain

`func (o *OwnedMediaRow) HasDomain() bool`

HasDomain returns a boolean if a field has been set.

### GetTotalResponses

`func (o *OwnedMediaRow) GetTotalResponses() int32`

GetTotalResponses returns the TotalResponses field if non-nil, zero value otherwise.

### GetTotalResponsesOk

`func (o *OwnedMediaRow) GetTotalResponsesOk() (*int32, bool)`

GetTotalResponsesOk returns a tuple with the TotalResponses field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalResponses

`func (o *OwnedMediaRow) SetTotalResponses(v int32)`

SetTotalResponses sets TotalResponses field to given value.

### HasTotalResponses

`func (o *OwnedMediaRow) HasTotalResponses() bool`

HasTotalResponses returns a boolean if a field has been set.

### GetRank

`func (o *OwnedMediaRow) GetRank() int32`

GetRank returns the Rank field if non-nil, zero value otherwise.

### GetRankOk

`func (o *OwnedMediaRow) GetRankOk() (*int32, bool)`

GetRankOk returns a tuple with the Rank field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRank

`func (o *OwnedMediaRow) SetRank(v int32)`

SetRank sets Rank field to given value.

### HasRank

`func (o *OwnedMediaRow) HasRank() bool`

HasRank returns a boolean if a field has been set.

### GetGlobalRank

`func (o *OwnedMediaRow) GetGlobalRank() int32`

GetGlobalRank returns the GlobalRank field if non-nil, zero value otherwise.

### GetGlobalRankOk

`func (o *OwnedMediaRow) GetGlobalRankOk() (*int32, bool)`

GetGlobalRankOk returns a tuple with the GlobalRank field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGlobalRank

`func (o *OwnedMediaRow) SetGlobalRank(v int32)`

SetGlobalRank sets GlobalRank field to given value.

### HasGlobalRank

`func (o *OwnedMediaRow) HasGlobalRank() bool`

HasGlobalRank returns a boolean if a field has been set.

### SetGlobalRankNil

`func (o *OwnedMediaRow) SetGlobalRankNil(b bool)`

 SetGlobalRankNil sets the value for GlobalRank to be an explicit nil

### UnsetGlobalRank
`func (o *OwnedMediaRow) UnsetGlobalRank()`

UnsetGlobalRank ensures that no value is present for GlobalRank, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


