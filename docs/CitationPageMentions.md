# CitationPageMentions

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**BrandMentioned** | **NullableBool** |  | 
**CompetitorMentioned** | **NullableBool** |  | 
**BrandPosition** | **NullableInt32** | Rank of the brand&#39;s first mention on the page; null when it has none | 
**ContentGapStatus** | **string** | missing_page_cache, content_unavailable, mentions_not_processed, mentioned, gap (a competitor but not the brand) or not_mentioned | 
**Brands** | [**[]CitationPageMentionsBrandsInner**](CitationPageMentionsBrandsInner.md) | Each brand the page mentions once, in order of first mention | 
**Mentions** | Pointer to [**[]CitationPageMentionsMentionsInner**](CitationPageMentionsMentionsInner.md) | Every mention on the page with its snippet; not sent on GET /citation_intelligence/groups | [optional] 

## Methods

### NewCitationPageMentions

`func NewCitationPageMentions(brandMentioned NullableBool, competitorMentioned NullableBool, brandPosition NullableInt32, contentGapStatus string, brands []CitationPageMentionsBrandsInner, ) *CitationPageMentions`

NewCitationPageMentions instantiates a new CitationPageMentions object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCitationPageMentionsWithDefaults

`func NewCitationPageMentionsWithDefaults() *CitationPageMentions`

NewCitationPageMentionsWithDefaults instantiates a new CitationPageMentions object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBrandMentioned

`func (o *CitationPageMentions) GetBrandMentioned() bool`

GetBrandMentioned returns the BrandMentioned field if non-nil, zero value otherwise.

### GetBrandMentionedOk

`func (o *CitationPageMentions) GetBrandMentionedOk() (*bool, bool)`

GetBrandMentionedOk returns a tuple with the BrandMentioned field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBrandMentioned

`func (o *CitationPageMentions) SetBrandMentioned(v bool)`

SetBrandMentioned sets BrandMentioned field to given value.


### SetBrandMentionedNil

`func (o *CitationPageMentions) SetBrandMentionedNil(b bool)`

 SetBrandMentionedNil sets the value for BrandMentioned to be an explicit nil

### UnsetBrandMentioned
`func (o *CitationPageMentions) UnsetBrandMentioned()`

UnsetBrandMentioned ensures that no value is present for BrandMentioned, not even an explicit nil
### GetCompetitorMentioned

`func (o *CitationPageMentions) GetCompetitorMentioned() bool`

GetCompetitorMentioned returns the CompetitorMentioned field if non-nil, zero value otherwise.

### GetCompetitorMentionedOk

`func (o *CitationPageMentions) GetCompetitorMentionedOk() (*bool, bool)`

GetCompetitorMentionedOk returns a tuple with the CompetitorMentioned field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompetitorMentioned

`func (o *CitationPageMentions) SetCompetitorMentioned(v bool)`

SetCompetitorMentioned sets CompetitorMentioned field to given value.


### SetCompetitorMentionedNil

`func (o *CitationPageMentions) SetCompetitorMentionedNil(b bool)`

 SetCompetitorMentionedNil sets the value for CompetitorMentioned to be an explicit nil

### UnsetCompetitorMentioned
`func (o *CitationPageMentions) UnsetCompetitorMentioned()`

UnsetCompetitorMentioned ensures that no value is present for CompetitorMentioned, not even an explicit nil
### GetBrandPosition

`func (o *CitationPageMentions) GetBrandPosition() int32`

GetBrandPosition returns the BrandPosition field if non-nil, zero value otherwise.

### GetBrandPositionOk

`func (o *CitationPageMentions) GetBrandPositionOk() (*int32, bool)`

GetBrandPositionOk returns a tuple with the BrandPosition field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBrandPosition

`func (o *CitationPageMentions) SetBrandPosition(v int32)`

SetBrandPosition sets BrandPosition field to given value.


### SetBrandPositionNil

`func (o *CitationPageMentions) SetBrandPositionNil(b bool)`

 SetBrandPositionNil sets the value for BrandPosition to be an explicit nil

### UnsetBrandPosition
`func (o *CitationPageMentions) UnsetBrandPosition()`

UnsetBrandPosition ensures that no value is present for BrandPosition, not even an explicit nil
### GetContentGapStatus

`func (o *CitationPageMentions) GetContentGapStatus() string`

GetContentGapStatus returns the ContentGapStatus field if non-nil, zero value otherwise.

### GetContentGapStatusOk

`func (o *CitationPageMentions) GetContentGapStatusOk() (*string, bool)`

GetContentGapStatusOk returns a tuple with the ContentGapStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContentGapStatus

`func (o *CitationPageMentions) SetContentGapStatus(v string)`

SetContentGapStatus sets ContentGapStatus field to given value.


### GetBrands

`func (o *CitationPageMentions) GetBrands() []CitationPageMentionsBrandsInner`

GetBrands returns the Brands field if non-nil, zero value otherwise.

### GetBrandsOk

`func (o *CitationPageMentions) GetBrandsOk() (*[]CitationPageMentionsBrandsInner, bool)`

GetBrandsOk returns a tuple with the Brands field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBrands

`func (o *CitationPageMentions) SetBrands(v []CitationPageMentionsBrandsInner)`

SetBrands sets Brands field to given value.


### GetMentions

`func (o *CitationPageMentions) GetMentions() []CitationPageMentionsMentionsInner`

GetMentions returns the Mentions field if non-nil, zero value otherwise.

### GetMentionsOk

`func (o *CitationPageMentions) GetMentionsOk() (*[]CitationPageMentionsMentionsInner, bool)`

GetMentionsOk returns a tuple with the Mentions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMentions

`func (o *CitationPageMentions) SetMentions(v []CitationPageMentionsMentionsInner)`

SetMentions sets Mentions field to given value.

### HasMentions

`func (o *CitationPageMentions) HasMentions() bool`

HasMentions returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


