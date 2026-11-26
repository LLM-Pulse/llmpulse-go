# CitedUrlDetailsResponseStats

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**TotalResponses** | **int32** | Answers citing the URL under the filters | 
**TotalCitations** | **int32** |  | 
**CitationRate** | **float32** | total_responses as a percentage (0-100) of citation_rate_denominator | 
**CitationRateDenominator** | **int32** | Answers matching the filters | 
**AvgCitationPosition** | **NullableFloat32** | Null when no visible citation has a rank | 
**FirstSeenAt** | **NullableTime** | Null when no citation matches the filters | 
**LastSeenAt** | **NullableTime** | Null when no citation matches the filters | 
**DistinctUrls** | **int32** | Spellings of the URL cited (tracking parameters, a trailing slash) | 
**SourceTypes** | [**CitedUrlDetailsResponseStatsSourceTypes**](CitedUrlDetailsResponseStatsSourceTypes.md) |  | 
**Models** | **map[string]int32** | Answers citing the URL per AI model, keyed by model | 

## Methods

### NewCitedUrlDetailsResponseStats

`func NewCitedUrlDetailsResponseStats(totalResponses int32, totalCitations int32, citationRate float32, citationRateDenominator int32, avgCitationPosition NullableFloat32, firstSeenAt NullableTime, lastSeenAt NullableTime, distinctUrls int32, sourceTypes CitedUrlDetailsResponseStatsSourceTypes, models map[string]int32, ) *CitedUrlDetailsResponseStats`

NewCitedUrlDetailsResponseStats instantiates a new CitedUrlDetailsResponseStats object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCitedUrlDetailsResponseStatsWithDefaults

`func NewCitedUrlDetailsResponseStatsWithDefaults() *CitedUrlDetailsResponseStats`

NewCitedUrlDetailsResponseStatsWithDefaults instantiates a new CitedUrlDetailsResponseStats object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTotalResponses

`func (o *CitedUrlDetailsResponseStats) GetTotalResponses() int32`

GetTotalResponses returns the TotalResponses field if non-nil, zero value otherwise.

### GetTotalResponsesOk

`func (o *CitedUrlDetailsResponseStats) GetTotalResponsesOk() (*int32, bool)`

GetTotalResponsesOk returns a tuple with the TotalResponses field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalResponses

`func (o *CitedUrlDetailsResponseStats) SetTotalResponses(v int32)`

SetTotalResponses sets TotalResponses field to given value.


### GetTotalCitations

`func (o *CitedUrlDetailsResponseStats) GetTotalCitations() int32`

GetTotalCitations returns the TotalCitations field if non-nil, zero value otherwise.

### GetTotalCitationsOk

`func (o *CitedUrlDetailsResponseStats) GetTotalCitationsOk() (*int32, bool)`

GetTotalCitationsOk returns a tuple with the TotalCitations field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalCitations

`func (o *CitedUrlDetailsResponseStats) SetTotalCitations(v int32)`

SetTotalCitations sets TotalCitations field to given value.


### GetCitationRate

`func (o *CitedUrlDetailsResponseStats) GetCitationRate() float32`

GetCitationRate returns the CitationRate field if non-nil, zero value otherwise.

### GetCitationRateOk

`func (o *CitedUrlDetailsResponseStats) GetCitationRateOk() (*float32, bool)`

GetCitationRateOk returns a tuple with the CitationRate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCitationRate

`func (o *CitedUrlDetailsResponseStats) SetCitationRate(v float32)`

SetCitationRate sets CitationRate field to given value.


### GetCitationRateDenominator

`func (o *CitedUrlDetailsResponseStats) GetCitationRateDenominator() int32`

GetCitationRateDenominator returns the CitationRateDenominator field if non-nil, zero value otherwise.

### GetCitationRateDenominatorOk

`func (o *CitedUrlDetailsResponseStats) GetCitationRateDenominatorOk() (*int32, bool)`

GetCitationRateDenominatorOk returns a tuple with the CitationRateDenominator field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCitationRateDenominator

`func (o *CitedUrlDetailsResponseStats) SetCitationRateDenominator(v int32)`

SetCitationRateDenominator sets CitationRateDenominator field to given value.


### GetAvgCitationPosition

`func (o *CitedUrlDetailsResponseStats) GetAvgCitationPosition() float32`

GetAvgCitationPosition returns the AvgCitationPosition field if non-nil, zero value otherwise.

### GetAvgCitationPositionOk

`func (o *CitedUrlDetailsResponseStats) GetAvgCitationPositionOk() (*float32, bool)`

GetAvgCitationPositionOk returns a tuple with the AvgCitationPosition field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAvgCitationPosition

`func (o *CitedUrlDetailsResponseStats) SetAvgCitationPosition(v float32)`

SetAvgCitationPosition sets AvgCitationPosition field to given value.


### SetAvgCitationPositionNil

`func (o *CitedUrlDetailsResponseStats) SetAvgCitationPositionNil(b bool)`

 SetAvgCitationPositionNil sets the value for AvgCitationPosition to be an explicit nil

### UnsetAvgCitationPosition
`func (o *CitedUrlDetailsResponseStats) UnsetAvgCitationPosition()`

UnsetAvgCitationPosition ensures that no value is present for AvgCitationPosition, not even an explicit nil
### GetFirstSeenAt

`func (o *CitedUrlDetailsResponseStats) GetFirstSeenAt() time.Time`

GetFirstSeenAt returns the FirstSeenAt field if non-nil, zero value otherwise.

### GetFirstSeenAtOk

`func (o *CitedUrlDetailsResponseStats) GetFirstSeenAtOk() (*time.Time, bool)`

GetFirstSeenAtOk returns a tuple with the FirstSeenAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFirstSeenAt

`func (o *CitedUrlDetailsResponseStats) SetFirstSeenAt(v time.Time)`

SetFirstSeenAt sets FirstSeenAt field to given value.


### SetFirstSeenAtNil

`func (o *CitedUrlDetailsResponseStats) SetFirstSeenAtNil(b bool)`

 SetFirstSeenAtNil sets the value for FirstSeenAt to be an explicit nil

### UnsetFirstSeenAt
`func (o *CitedUrlDetailsResponseStats) UnsetFirstSeenAt()`

UnsetFirstSeenAt ensures that no value is present for FirstSeenAt, not even an explicit nil
### GetLastSeenAt

`func (o *CitedUrlDetailsResponseStats) GetLastSeenAt() time.Time`

GetLastSeenAt returns the LastSeenAt field if non-nil, zero value otherwise.

### GetLastSeenAtOk

`func (o *CitedUrlDetailsResponseStats) GetLastSeenAtOk() (*time.Time, bool)`

GetLastSeenAtOk returns a tuple with the LastSeenAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastSeenAt

`func (o *CitedUrlDetailsResponseStats) SetLastSeenAt(v time.Time)`

SetLastSeenAt sets LastSeenAt field to given value.


### SetLastSeenAtNil

`func (o *CitedUrlDetailsResponseStats) SetLastSeenAtNil(b bool)`

 SetLastSeenAtNil sets the value for LastSeenAt to be an explicit nil

### UnsetLastSeenAt
`func (o *CitedUrlDetailsResponseStats) UnsetLastSeenAt()`

UnsetLastSeenAt ensures that no value is present for LastSeenAt, not even an explicit nil
### GetDistinctUrls

`func (o *CitedUrlDetailsResponseStats) GetDistinctUrls() int32`

GetDistinctUrls returns the DistinctUrls field if non-nil, zero value otherwise.

### GetDistinctUrlsOk

`func (o *CitedUrlDetailsResponseStats) GetDistinctUrlsOk() (*int32, bool)`

GetDistinctUrlsOk returns a tuple with the DistinctUrls field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDistinctUrls

`func (o *CitedUrlDetailsResponseStats) SetDistinctUrls(v int32)`

SetDistinctUrls sets DistinctUrls field to given value.


### GetSourceTypes

`func (o *CitedUrlDetailsResponseStats) GetSourceTypes() CitedUrlDetailsResponseStatsSourceTypes`

GetSourceTypes returns the SourceTypes field if non-nil, zero value otherwise.

### GetSourceTypesOk

`func (o *CitedUrlDetailsResponseStats) GetSourceTypesOk() (*CitedUrlDetailsResponseStatsSourceTypes, bool)`

GetSourceTypesOk returns a tuple with the SourceTypes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSourceTypes

`func (o *CitedUrlDetailsResponseStats) SetSourceTypes(v CitedUrlDetailsResponseStatsSourceTypes)`

SetSourceTypes sets SourceTypes field to given value.


### GetModels

`func (o *CitedUrlDetailsResponseStats) GetModels() map[string]int32`

GetModels returns the Models field if non-nil, zero value otherwise.

### GetModelsOk

`func (o *CitedUrlDetailsResponseStats) GetModelsOk() (*map[string]int32, bool)`

GetModelsOk returns a tuple with the Models field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModels

`func (o *CitedUrlDetailsResponseStats) SetModels(v map[string]int32)`

SetModels sets Models field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


