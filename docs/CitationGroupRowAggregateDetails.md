# CitationGroupRowAggregateDetails

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**UniqueUrlsCount** | **int32** |  | 
**CrawledUrlsCount** | **int32** | Pages with usable content | 
**BrandMentionedUrlsCount** | **NullableInt32** | Pages analyzed for the project that mention the brand; null when none is analyzed | 
**CompetitorMentionedUrlsCount** | **NullableInt32** | Pages analyzed for the project that mention a competitor; null when none is analyzed | 
**LastCrawledAt** | **NullableTime** |  | 

## Methods

### NewCitationGroupRowAggregateDetails

`func NewCitationGroupRowAggregateDetails(uniqueUrlsCount int32, crawledUrlsCount int32, brandMentionedUrlsCount NullableInt32, competitorMentionedUrlsCount NullableInt32, lastCrawledAt NullableTime, ) *CitationGroupRowAggregateDetails`

NewCitationGroupRowAggregateDetails instantiates a new CitationGroupRowAggregateDetails object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCitationGroupRowAggregateDetailsWithDefaults

`func NewCitationGroupRowAggregateDetailsWithDefaults() *CitationGroupRowAggregateDetails`

NewCitationGroupRowAggregateDetailsWithDefaults instantiates a new CitationGroupRowAggregateDetails object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUniqueUrlsCount

`func (o *CitationGroupRowAggregateDetails) GetUniqueUrlsCount() int32`

GetUniqueUrlsCount returns the UniqueUrlsCount field if non-nil, zero value otherwise.

### GetUniqueUrlsCountOk

`func (o *CitationGroupRowAggregateDetails) GetUniqueUrlsCountOk() (*int32, bool)`

GetUniqueUrlsCountOk returns a tuple with the UniqueUrlsCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUniqueUrlsCount

`func (o *CitationGroupRowAggregateDetails) SetUniqueUrlsCount(v int32)`

SetUniqueUrlsCount sets UniqueUrlsCount field to given value.


### GetCrawledUrlsCount

`func (o *CitationGroupRowAggregateDetails) GetCrawledUrlsCount() int32`

GetCrawledUrlsCount returns the CrawledUrlsCount field if non-nil, zero value otherwise.

### GetCrawledUrlsCountOk

`func (o *CitationGroupRowAggregateDetails) GetCrawledUrlsCountOk() (*int32, bool)`

GetCrawledUrlsCountOk returns a tuple with the CrawledUrlsCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCrawledUrlsCount

`func (o *CitationGroupRowAggregateDetails) SetCrawledUrlsCount(v int32)`

SetCrawledUrlsCount sets CrawledUrlsCount field to given value.


### GetBrandMentionedUrlsCount

`func (o *CitationGroupRowAggregateDetails) GetBrandMentionedUrlsCount() int32`

GetBrandMentionedUrlsCount returns the BrandMentionedUrlsCount field if non-nil, zero value otherwise.

### GetBrandMentionedUrlsCountOk

`func (o *CitationGroupRowAggregateDetails) GetBrandMentionedUrlsCountOk() (*int32, bool)`

GetBrandMentionedUrlsCountOk returns a tuple with the BrandMentionedUrlsCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBrandMentionedUrlsCount

`func (o *CitationGroupRowAggregateDetails) SetBrandMentionedUrlsCount(v int32)`

SetBrandMentionedUrlsCount sets BrandMentionedUrlsCount field to given value.


### SetBrandMentionedUrlsCountNil

`func (o *CitationGroupRowAggregateDetails) SetBrandMentionedUrlsCountNil(b bool)`

 SetBrandMentionedUrlsCountNil sets the value for BrandMentionedUrlsCount to be an explicit nil

### UnsetBrandMentionedUrlsCount
`func (o *CitationGroupRowAggregateDetails) UnsetBrandMentionedUrlsCount()`

UnsetBrandMentionedUrlsCount ensures that no value is present for BrandMentionedUrlsCount, not even an explicit nil
### GetCompetitorMentionedUrlsCount

`func (o *CitationGroupRowAggregateDetails) GetCompetitorMentionedUrlsCount() int32`

GetCompetitorMentionedUrlsCount returns the CompetitorMentionedUrlsCount field if non-nil, zero value otherwise.

### GetCompetitorMentionedUrlsCountOk

`func (o *CitationGroupRowAggregateDetails) GetCompetitorMentionedUrlsCountOk() (*int32, bool)`

GetCompetitorMentionedUrlsCountOk returns a tuple with the CompetitorMentionedUrlsCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompetitorMentionedUrlsCount

`func (o *CitationGroupRowAggregateDetails) SetCompetitorMentionedUrlsCount(v int32)`

SetCompetitorMentionedUrlsCount sets CompetitorMentionedUrlsCount field to given value.


### SetCompetitorMentionedUrlsCountNil

`func (o *CitationGroupRowAggregateDetails) SetCompetitorMentionedUrlsCountNil(b bool)`

 SetCompetitorMentionedUrlsCountNil sets the value for CompetitorMentionedUrlsCount to be an explicit nil

### UnsetCompetitorMentionedUrlsCount
`func (o *CitationGroupRowAggregateDetails) UnsetCompetitorMentionedUrlsCount()`

UnsetCompetitorMentionedUrlsCount ensures that no value is present for CompetitorMentionedUrlsCount, not even an explicit nil
### GetLastCrawledAt

`func (o *CitationGroupRowAggregateDetails) GetLastCrawledAt() time.Time`

GetLastCrawledAt returns the LastCrawledAt field if non-nil, zero value otherwise.

### GetLastCrawledAtOk

`func (o *CitationGroupRowAggregateDetails) GetLastCrawledAtOk() (*time.Time, bool)`

GetLastCrawledAtOk returns a tuple with the LastCrawledAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastCrawledAt

`func (o *CitationGroupRowAggregateDetails) SetLastCrawledAt(v time.Time)`

SetLastCrawledAt sets LastCrawledAt field to given value.


### SetLastCrawledAtNil

`func (o *CitationGroupRowAggregateDetails) SetLastCrawledAtNil(b bool)`

 SetLastCrawledAtNil sets the value for LastCrawledAt to be an explicit nil

### UnsetLastCrawledAt
`func (o *CitationGroupRowAggregateDetails) UnsetLastCrawledAt()`

UnsetLastCrawledAt ensures that no value is present for LastCrawledAt, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


