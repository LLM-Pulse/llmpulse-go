# CitationGroupRow

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**SourceId** | **int32** | The group&#39;s first citation | 
**View** | **string** | url, domain or host | 
**Key** | **string** | The URL as cited, the domain or the host | 
**TotalResponses** | **int32** | Answers citing it | 
**TotalCitations** | **int32** |  | 
**CitationRate** | **float32** | total_responses as a percentage (0-100) of citation_rate_denominator | 
**CitationRateDenominator** | **int32** | Answers matching the filters | 
**AvgCitationPosition** | **NullableFloat32** | Null when no visible citation has a rank | 
**FirstSeenAt** | **NullableTime** |  | 
**LastSeenAt** | **NullableTime** |  | 
**Models** | **map[string]int32** | Answers citing it per AI model, keyed by model | 
**Url** | Pointer to **string** | url view only. The URL as cited | [optional] 
**UrlSha256** | Pointer to **NullableString** | url view only. Key of the cited page, shared by the URL&#39;s variants | [optional] 
**NormalizedUrl** | Pointer to **NullableString** | url view only | [optional] 
**PageCache** | Pointer to [**CitationPageCache**](CitationPageCache.md) |  | [optional] 
**PageMentions** | Pointer to [**CitationPageMentions**](CitationPageMentions.md) |  | [optional] 
**Domain** | Pointer to **string** | domain view only | [optional] 
**Host** | Pointer to **string** | host view only | [optional] 
**AggregateDetails** | Pointer to [**CitationGroupRowAggregateDetails**](CitationGroupRowAggregateDetails.md) |  | [optional] 
**CitationSeries** | Pointer to [**CitationSeries**](CitationSeries.md) |  | [optional] 

## Methods

### NewCitationGroupRow

`func NewCitationGroupRow(sourceId int32, view string, key string, totalResponses int32, totalCitations int32, citationRate float32, citationRateDenominator int32, avgCitationPosition NullableFloat32, firstSeenAt NullableTime, lastSeenAt NullableTime, models map[string]int32, ) *CitationGroupRow`

NewCitationGroupRow instantiates a new CitationGroupRow object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCitationGroupRowWithDefaults

`func NewCitationGroupRowWithDefaults() *CitationGroupRow`

NewCitationGroupRowWithDefaults instantiates a new CitationGroupRow object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSourceId

`func (o *CitationGroupRow) GetSourceId() int32`

GetSourceId returns the SourceId field if non-nil, zero value otherwise.

### GetSourceIdOk

`func (o *CitationGroupRow) GetSourceIdOk() (*int32, bool)`

GetSourceIdOk returns a tuple with the SourceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSourceId

`func (o *CitationGroupRow) SetSourceId(v int32)`

SetSourceId sets SourceId field to given value.


### GetView

`func (o *CitationGroupRow) GetView() string`

GetView returns the View field if non-nil, zero value otherwise.

### GetViewOk

`func (o *CitationGroupRow) GetViewOk() (*string, bool)`

GetViewOk returns a tuple with the View field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetView

`func (o *CitationGroupRow) SetView(v string)`

SetView sets View field to given value.


### GetKey

`func (o *CitationGroupRow) GetKey() string`

GetKey returns the Key field if non-nil, zero value otherwise.

### GetKeyOk

`func (o *CitationGroupRow) GetKeyOk() (*string, bool)`

GetKeyOk returns a tuple with the Key field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKey

`func (o *CitationGroupRow) SetKey(v string)`

SetKey sets Key field to given value.


### GetTotalResponses

`func (o *CitationGroupRow) GetTotalResponses() int32`

GetTotalResponses returns the TotalResponses field if non-nil, zero value otherwise.

### GetTotalResponsesOk

`func (o *CitationGroupRow) GetTotalResponsesOk() (*int32, bool)`

GetTotalResponsesOk returns a tuple with the TotalResponses field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalResponses

`func (o *CitationGroupRow) SetTotalResponses(v int32)`

SetTotalResponses sets TotalResponses field to given value.


### GetTotalCitations

`func (o *CitationGroupRow) GetTotalCitations() int32`

GetTotalCitations returns the TotalCitations field if non-nil, zero value otherwise.

### GetTotalCitationsOk

`func (o *CitationGroupRow) GetTotalCitationsOk() (*int32, bool)`

GetTotalCitationsOk returns a tuple with the TotalCitations field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalCitations

`func (o *CitationGroupRow) SetTotalCitations(v int32)`

SetTotalCitations sets TotalCitations field to given value.


### GetCitationRate

`func (o *CitationGroupRow) GetCitationRate() float32`

GetCitationRate returns the CitationRate field if non-nil, zero value otherwise.

### GetCitationRateOk

`func (o *CitationGroupRow) GetCitationRateOk() (*float32, bool)`

GetCitationRateOk returns a tuple with the CitationRate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCitationRate

`func (o *CitationGroupRow) SetCitationRate(v float32)`

SetCitationRate sets CitationRate field to given value.


### GetCitationRateDenominator

`func (o *CitationGroupRow) GetCitationRateDenominator() int32`

GetCitationRateDenominator returns the CitationRateDenominator field if non-nil, zero value otherwise.

### GetCitationRateDenominatorOk

`func (o *CitationGroupRow) GetCitationRateDenominatorOk() (*int32, bool)`

GetCitationRateDenominatorOk returns a tuple with the CitationRateDenominator field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCitationRateDenominator

`func (o *CitationGroupRow) SetCitationRateDenominator(v int32)`

SetCitationRateDenominator sets CitationRateDenominator field to given value.


### GetAvgCitationPosition

`func (o *CitationGroupRow) GetAvgCitationPosition() float32`

GetAvgCitationPosition returns the AvgCitationPosition field if non-nil, zero value otherwise.

### GetAvgCitationPositionOk

`func (o *CitationGroupRow) GetAvgCitationPositionOk() (*float32, bool)`

GetAvgCitationPositionOk returns a tuple with the AvgCitationPosition field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAvgCitationPosition

`func (o *CitationGroupRow) SetAvgCitationPosition(v float32)`

SetAvgCitationPosition sets AvgCitationPosition field to given value.


### SetAvgCitationPositionNil

`func (o *CitationGroupRow) SetAvgCitationPositionNil(b bool)`

 SetAvgCitationPositionNil sets the value for AvgCitationPosition to be an explicit nil

### UnsetAvgCitationPosition
`func (o *CitationGroupRow) UnsetAvgCitationPosition()`

UnsetAvgCitationPosition ensures that no value is present for AvgCitationPosition, not even an explicit nil
### GetFirstSeenAt

`func (o *CitationGroupRow) GetFirstSeenAt() time.Time`

GetFirstSeenAt returns the FirstSeenAt field if non-nil, zero value otherwise.

### GetFirstSeenAtOk

`func (o *CitationGroupRow) GetFirstSeenAtOk() (*time.Time, bool)`

GetFirstSeenAtOk returns a tuple with the FirstSeenAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFirstSeenAt

`func (o *CitationGroupRow) SetFirstSeenAt(v time.Time)`

SetFirstSeenAt sets FirstSeenAt field to given value.


### SetFirstSeenAtNil

`func (o *CitationGroupRow) SetFirstSeenAtNil(b bool)`

 SetFirstSeenAtNil sets the value for FirstSeenAt to be an explicit nil

### UnsetFirstSeenAt
`func (o *CitationGroupRow) UnsetFirstSeenAt()`

UnsetFirstSeenAt ensures that no value is present for FirstSeenAt, not even an explicit nil
### GetLastSeenAt

`func (o *CitationGroupRow) GetLastSeenAt() time.Time`

GetLastSeenAt returns the LastSeenAt field if non-nil, zero value otherwise.

### GetLastSeenAtOk

`func (o *CitationGroupRow) GetLastSeenAtOk() (*time.Time, bool)`

GetLastSeenAtOk returns a tuple with the LastSeenAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastSeenAt

`func (o *CitationGroupRow) SetLastSeenAt(v time.Time)`

SetLastSeenAt sets LastSeenAt field to given value.


### SetLastSeenAtNil

`func (o *CitationGroupRow) SetLastSeenAtNil(b bool)`

 SetLastSeenAtNil sets the value for LastSeenAt to be an explicit nil

### UnsetLastSeenAt
`func (o *CitationGroupRow) UnsetLastSeenAt()`

UnsetLastSeenAt ensures that no value is present for LastSeenAt, not even an explicit nil
### GetModels

`func (o *CitationGroupRow) GetModels() map[string]int32`

GetModels returns the Models field if non-nil, zero value otherwise.

### GetModelsOk

`func (o *CitationGroupRow) GetModelsOk() (*map[string]int32, bool)`

GetModelsOk returns a tuple with the Models field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModels

`func (o *CitationGroupRow) SetModels(v map[string]int32)`

SetModels sets Models field to given value.


### GetUrl

`func (o *CitationGroupRow) GetUrl() string`

GetUrl returns the Url field if non-nil, zero value otherwise.

### GetUrlOk

`func (o *CitationGroupRow) GetUrlOk() (*string, bool)`

GetUrlOk returns a tuple with the Url field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrl

`func (o *CitationGroupRow) SetUrl(v string)`

SetUrl sets Url field to given value.

### HasUrl

`func (o *CitationGroupRow) HasUrl() bool`

HasUrl returns a boolean if a field has been set.

### GetUrlSha256

`func (o *CitationGroupRow) GetUrlSha256() string`

GetUrlSha256 returns the UrlSha256 field if non-nil, zero value otherwise.

### GetUrlSha256Ok

`func (o *CitationGroupRow) GetUrlSha256Ok() (*string, bool)`

GetUrlSha256Ok returns a tuple with the UrlSha256 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrlSha256

`func (o *CitationGroupRow) SetUrlSha256(v string)`

SetUrlSha256 sets UrlSha256 field to given value.

### HasUrlSha256

`func (o *CitationGroupRow) HasUrlSha256() bool`

HasUrlSha256 returns a boolean if a field has been set.

### SetUrlSha256Nil

`func (o *CitationGroupRow) SetUrlSha256Nil(b bool)`

 SetUrlSha256Nil sets the value for UrlSha256 to be an explicit nil

### UnsetUrlSha256
`func (o *CitationGroupRow) UnsetUrlSha256()`

UnsetUrlSha256 ensures that no value is present for UrlSha256, not even an explicit nil
### GetNormalizedUrl

`func (o *CitationGroupRow) GetNormalizedUrl() string`

GetNormalizedUrl returns the NormalizedUrl field if non-nil, zero value otherwise.

### GetNormalizedUrlOk

`func (o *CitationGroupRow) GetNormalizedUrlOk() (*string, bool)`

GetNormalizedUrlOk returns a tuple with the NormalizedUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNormalizedUrl

`func (o *CitationGroupRow) SetNormalizedUrl(v string)`

SetNormalizedUrl sets NormalizedUrl field to given value.

### HasNormalizedUrl

`func (o *CitationGroupRow) HasNormalizedUrl() bool`

HasNormalizedUrl returns a boolean if a field has been set.

### SetNormalizedUrlNil

`func (o *CitationGroupRow) SetNormalizedUrlNil(b bool)`

 SetNormalizedUrlNil sets the value for NormalizedUrl to be an explicit nil

### UnsetNormalizedUrl
`func (o *CitationGroupRow) UnsetNormalizedUrl()`

UnsetNormalizedUrl ensures that no value is present for NormalizedUrl, not even an explicit nil
### GetPageCache

`func (o *CitationGroupRow) GetPageCache() CitationPageCache`

GetPageCache returns the PageCache field if non-nil, zero value otherwise.

### GetPageCacheOk

`func (o *CitationGroupRow) GetPageCacheOk() (*CitationPageCache, bool)`

GetPageCacheOk returns a tuple with the PageCache field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPageCache

`func (o *CitationGroupRow) SetPageCache(v CitationPageCache)`

SetPageCache sets PageCache field to given value.

### HasPageCache

`func (o *CitationGroupRow) HasPageCache() bool`

HasPageCache returns a boolean if a field has been set.

### GetPageMentions

`func (o *CitationGroupRow) GetPageMentions() CitationPageMentions`

GetPageMentions returns the PageMentions field if non-nil, zero value otherwise.

### GetPageMentionsOk

`func (o *CitationGroupRow) GetPageMentionsOk() (*CitationPageMentions, bool)`

GetPageMentionsOk returns a tuple with the PageMentions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPageMentions

`func (o *CitationGroupRow) SetPageMentions(v CitationPageMentions)`

SetPageMentions sets PageMentions field to given value.

### HasPageMentions

`func (o *CitationGroupRow) HasPageMentions() bool`

HasPageMentions returns a boolean if a field has been set.

### GetDomain

`func (o *CitationGroupRow) GetDomain() string`

GetDomain returns the Domain field if non-nil, zero value otherwise.

### GetDomainOk

`func (o *CitationGroupRow) GetDomainOk() (*string, bool)`

GetDomainOk returns a tuple with the Domain field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDomain

`func (o *CitationGroupRow) SetDomain(v string)`

SetDomain sets Domain field to given value.

### HasDomain

`func (o *CitationGroupRow) HasDomain() bool`

HasDomain returns a boolean if a field has been set.

### GetHost

`func (o *CitationGroupRow) GetHost() string`

GetHost returns the Host field if non-nil, zero value otherwise.

### GetHostOk

`func (o *CitationGroupRow) GetHostOk() (*string, bool)`

GetHostOk returns a tuple with the Host field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHost

`func (o *CitationGroupRow) SetHost(v string)`

SetHost sets Host field to given value.

### HasHost

`func (o *CitationGroupRow) HasHost() bool`

HasHost returns a boolean if a field has been set.

### GetAggregateDetails

`func (o *CitationGroupRow) GetAggregateDetails() CitationGroupRowAggregateDetails`

GetAggregateDetails returns the AggregateDetails field if non-nil, zero value otherwise.

### GetAggregateDetailsOk

`func (o *CitationGroupRow) GetAggregateDetailsOk() (*CitationGroupRowAggregateDetails, bool)`

GetAggregateDetailsOk returns a tuple with the AggregateDetails field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAggregateDetails

`func (o *CitationGroupRow) SetAggregateDetails(v CitationGroupRowAggregateDetails)`

SetAggregateDetails sets AggregateDetails field to given value.

### HasAggregateDetails

`func (o *CitationGroupRow) HasAggregateDetails() bool`

HasAggregateDetails returns a boolean if a field has been set.

### GetCitationSeries

`func (o *CitationGroupRow) GetCitationSeries() CitationSeries`

GetCitationSeries returns the CitationSeries field if non-nil, zero value otherwise.

### GetCitationSeriesOk

`func (o *CitationGroupRow) GetCitationSeriesOk() (*CitationSeries, bool)`

GetCitationSeriesOk returns a tuple with the CitationSeries field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCitationSeries

`func (o *CitationGroupRow) SetCitationSeries(v CitationSeries)`

SetCitationSeries sets CitationSeries field to given value.

### HasCitationSeries

`func (o *CitationGroupRow) HasCitationSeries() bool`

HasCitationSeries returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


