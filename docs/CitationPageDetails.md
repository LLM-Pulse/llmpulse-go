# CitationPageDetails

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**UrlSha256** | **string** |  | 
**NormalizedUrl** | **NullableString** |  | 
**PageCache** | [**CitationPageCache**](CitationPageCache.md) |  | 
**PageMentions** | [**CitationPageMentions**](CitationPageMentions.md) |  | 
**Content** | Pointer to [**CitationPageDetailsContent**](CitationPageDetailsContent.md) |  | [optional] 

## Methods

### NewCitationPageDetails

`func NewCitationPageDetails(urlSha256 string, normalizedUrl NullableString, pageCache CitationPageCache, pageMentions CitationPageMentions, ) *CitationPageDetails`

NewCitationPageDetails instantiates a new CitationPageDetails object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCitationPageDetailsWithDefaults

`func NewCitationPageDetailsWithDefaults() *CitationPageDetails`

NewCitationPageDetailsWithDefaults instantiates a new CitationPageDetails object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUrlSha256

`func (o *CitationPageDetails) GetUrlSha256() string`

GetUrlSha256 returns the UrlSha256 field if non-nil, zero value otherwise.

### GetUrlSha256Ok

`func (o *CitationPageDetails) GetUrlSha256Ok() (*string, bool)`

GetUrlSha256Ok returns a tuple with the UrlSha256 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrlSha256

`func (o *CitationPageDetails) SetUrlSha256(v string)`

SetUrlSha256 sets UrlSha256 field to given value.


### GetNormalizedUrl

`func (o *CitationPageDetails) GetNormalizedUrl() string`

GetNormalizedUrl returns the NormalizedUrl field if non-nil, zero value otherwise.

### GetNormalizedUrlOk

`func (o *CitationPageDetails) GetNormalizedUrlOk() (*string, bool)`

GetNormalizedUrlOk returns a tuple with the NormalizedUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNormalizedUrl

`func (o *CitationPageDetails) SetNormalizedUrl(v string)`

SetNormalizedUrl sets NormalizedUrl field to given value.


### SetNormalizedUrlNil

`func (o *CitationPageDetails) SetNormalizedUrlNil(b bool)`

 SetNormalizedUrlNil sets the value for NormalizedUrl to be an explicit nil

### UnsetNormalizedUrl
`func (o *CitationPageDetails) UnsetNormalizedUrl()`

UnsetNormalizedUrl ensures that no value is present for NormalizedUrl, not even an explicit nil
### GetPageCache

`func (o *CitationPageDetails) GetPageCache() CitationPageCache`

GetPageCache returns the PageCache field if non-nil, zero value otherwise.

### GetPageCacheOk

`func (o *CitationPageDetails) GetPageCacheOk() (*CitationPageCache, bool)`

GetPageCacheOk returns a tuple with the PageCache field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPageCache

`func (o *CitationPageDetails) SetPageCache(v CitationPageCache)`

SetPageCache sets PageCache field to given value.


### GetPageMentions

`func (o *CitationPageDetails) GetPageMentions() CitationPageMentions`

GetPageMentions returns the PageMentions field if non-nil, zero value otherwise.

### GetPageMentionsOk

`func (o *CitationPageDetails) GetPageMentionsOk() (*CitationPageMentions, bool)`

GetPageMentionsOk returns a tuple with the PageMentions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPageMentions

`func (o *CitationPageDetails) SetPageMentions(v CitationPageMentions)`

SetPageMentions sets PageMentions field to given value.


### GetContent

`func (o *CitationPageDetails) GetContent() CitationPageDetailsContent`

GetContent returns the Content field if non-nil, zero value otherwise.

### GetContentOk

`func (o *CitationPageDetails) GetContentOk() (*CitationPageDetailsContent, bool)`

GetContentOk returns a tuple with the Content field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContent

`func (o *CitationPageDetails) SetContent(v CitationPageDetailsContent)`

SetContent sets Content field to given value.

### HasContent

`func (o *CitationPageDetails) HasContent() bool`

HasContent returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


