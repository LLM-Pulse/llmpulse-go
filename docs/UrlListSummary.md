# UrlListSummary

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**EntriesCount** | **int32** |  | 
**CitedEntries** | **int32** |  | 
**Citations** | **int32** | AI answers citing any entry in the window, each once. | 
**Answers** | **int32** | AI answers in the window, the citation rate&#39;s denominator. | 
**CitationRate** | **float32** | citations over answers, in percent. | 
**AvgCitationPosition** | **NullableFloat32** |  | 
**MedianDaysToFirstCitation** | **NullableInt32** |  | 
**TotalCost** | **NullableFloat32** |  | 
**CostPerCitedEntry** | **NullableFloat32** |  | 

## Methods

### NewUrlListSummary

`func NewUrlListSummary(entriesCount int32, citedEntries int32, citations int32, answers int32, citationRate float32, avgCitationPosition NullableFloat32, medianDaysToFirstCitation NullableInt32, totalCost NullableFloat32, costPerCitedEntry NullableFloat32, ) *UrlListSummary`

NewUrlListSummary instantiates a new UrlListSummary object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUrlListSummaryWithDefaults

`func NewUrlListSummaryWithDefaults() *UrlListSummary`

NewUrlListSummaryWithDefaults instantiates a new UrlListSummary object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetEntriesCount

`func (o *UrlListSummary) GetEntriesCount() int32`

GetEntriesCount returns the EntriesCount field if non-nil, zero value otherwise.

### GetEntriesCountOk

`func (o *UrlListSummary) GetEntriesCountOk() (*int32, bool)`

GetEntriesCountOk returns a tuple with the EntriesCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEntriesCount

`func (o *UrlListSummary) SetEntriesCount(v int32)`

SetEntriesCount sets EntriesCount field to given value.


### GetCitedEntries

`func (o *UrlListSummary) GetCitedEntries() int32`

GetCitedEntries returns the CitedEntries field if non-nil, zero value otherwise.

### GetCitedEntriesOk

`func (o *UrlListSummary) GetCitedEntriesOk() (*int32, bool)`

GetCitedEntriesOk returns a tuple with the CitedEntries field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCitedEntries

`func (o *UrlListSummary) SetCitedEntries(v int32)`

SetCitedEntries sets CitedEntries field to given value.


### GetCitations

`func (o *UrlListSummary) GetCitations() int32`

GetCitations returns the Citations field if non-nil, zero value otherwise.

### GetCitationsOk

`func (o *UrlListSummary) GetCitationsOk() (*int32, bool)`

GetCitationsOk returns a tuple with the Citations field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCitations

`func (o *UrlListSummary) SetCitations(v int32)`

SetCitations sets Citations field to given value.


### GetAnswers

`func (o *UrlListSummary) GetAnswers() int32`

GetAnswers returns the Answers field if non-nil, zero value otherwise.

### GetAnswersOk

`func (o *UrlListSummary) GetAnswersOk() (*int32, bool)`

GetAnswersOk returns a tuple with the Answers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAnswers

`func (o *UrlListSummary) SetAnswers(v int32)`

SetAnswers sets Answers field to given value.


### GetCitationRate

`func (o *UrlListSummary) GetCitationRate() float32`

GetCitationRate returns the CitationRate field if non-nil, zero value otherwise.

### GetCitationRateOk

`func (o *UrlListSummary) GetCitationRateOk() (*float32, bool)`

GetCitationRateOk returns a tuple with the CitationRate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCitationRate

`func (o *UrlListSummary) SetCitationRate(v float32)`

SetCitationRate sets CitationRate field to given value.


### GetAvgCitationPosition

`func (o *UrlListSummary) GetAvgCitationPosition() float32`

GetAvgCitationPosition returns the AvgCitationPosition field if non-nil, zero value otherwise.

### GetAvgCitationPositionOk

`func (o *UrlListSummary) GetAvgCitationPositionOk() (*float32, bool)`

GetAvgCitationPositionOk returns a tuple with the AvgCitationPosition field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAvgCitationPosition

`func (o *UrlListSummary) SetAvgCitationPosition(v float32)`

SetAvgCitationPosition sets AvgCitationPosition field to given value.


### SetAvgCitationPositionNil

`func (o *UrlListSummary) SetAvgCitationPositionNil(b bool)`

 SetAvgCitationPositionNil sets the value for AvgCitationPosition to be an explicit nil

### UnsetAvgCitationPosition
`func (o *UrlListSummary) UnsetAvgCitationPosition()`

UnsetAvgCitationPosition ensures that no value is present for AvgCitationPosition, not even an explicit nil
### GetMedianDaysToFirstCitation

`func (o *UrlListSummary) GetMedianDaysToFirstCitation() int32`

GetMedianDaysToFirstCitation returns the MedianDaysToFirstCitation field if non-nil, zero value otherwise.

### GetMedianDaysToFirstCitationOk

`func (o *UrlListSummary) GetMedianDaysToFirstCitationOk() (*int32, bool)`

GetMedianDaysToFirstCitationOk returns a tuple with the MedianDaysToFirstCitation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMedianDaysToFirstCitation

`func (o *UrlListSummary) SetMedianDaysToFirstCitation(v int32)`

SetMedianDaysToFirstCitation sets MedianDaysToFirstCitation field to given value.


### SetMedianDaysToFirstCitationNil

`func (o *UrlListSummary) SetMedianDaysToFirstCitationNil(b bool)`

 SetMedianDaysToFirstCitationNil sets the value for MedianDaysToFirstCitation to be an explicit nil

### UnsetMedianDaysToFirstCitation
`func (o *UrlListSummary) UnsetMedianDaysToFirstCitation()`

UnsetMedianDaysToFirstCitation ensures that no value is present for MedianDaysToFirstCitation, not even an explicit nil
### GetTotalCost

`func (o *UrlListSummary) GetTotalCost() float32`

GetTotalCost returns the TotalCost field if non-nil, zero value otherwise.

### GetTotalCostOk

`func (o *UrlListSummary) GetTotalCostOk() (*float32, bool)`

GetTotalCostOk returns a tuple with the TotalCost field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalCost

`func (o *UrlListSummary) SetTotalCost(v float32)`

SetTotalCost sets TotalCost field to given value.


### SetTotalCostNil

`func (o *UrlListSummary) SetTotalCostNil(b bool)`

 SetTotalCostNil sets the value for TotalCost to be an explicit nil

### UnsetTotalCost
`func (o *UrlListSummary) UnsetTotalCost()`

UnsetTotalCost ensures that no value is present for TotalCost, not even an explicit nil
### GetCostPerCitedEntry

`func (o *UrlListSummary) GetCostPerCitedEntry() float32`

GetCostPerCitedEntry returns the CostPerCitedEntry field if non-nil, zero value otherwise.

### GetCostPerCitedEntryOk

`func (o *UrlListSummary) GetCostPerCitedEntryOk() (*float32, bool)`

GetCostPerCitedEntryOk returns a tuple with the CostPerCitedEntry field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCostPerCitedEntry

`func (o *UrlListSummary) SetCostPerCitedEntry(v float32)`

SetCostPerCitedEntry sets CostPerCitedEntry field to given value.


### SetCostPerCitedEntryNil

`func (o *UrlListSummary) SetCostPerCitedEntryNil(b bool)`

 SetCostPerCitedEntryNil sets the value for CostPerCitedEntry to be an explicit nil

### UnsetCostPerCitedEntry
`func (o *UrlListSummary) UnsetCostPerCitedEntry()`

UnsetCostPerCitedEntry ensures that no value is present for CostPerCitedEntry, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


