# SearchConsoleOpportunitiesResponseDataInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Query** | Pointer to **string** |  | [optional] 
**Impressions** | Pointer to **int32** |  | [optional] 
**Clicks** | Pointer to **int32** |  | [optional] 
**Ctr** | Pointer to **float32** | 0..1 fraction | [optional] 
**Position** | Pointer to **float32** | Impression-weighted average position | [optional] 
**PotentialClicks** | Pointer to **NullableInt32** | Clicks a move into the top 3 would add at top_ctr (never negative); null when top_ctr is null | [optional] 

## Methods

### NewSearchConsoleOpportunitiesResponseDataInner

`func NewSearchConsoleOpportunitiesResponseDataInner() *SearchConsoleOpportunitiesResponseDataInner`

NewSearchConsoleOpportunitiesResponseDataInner instantiates a new SearchConsoleOpportunitiesResponseDataInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSearchConsoleOpportunitiesResponseDataInnerWithDefaults

`func NewSearchConsoleOpportunitiesResponseDataInnerWithDefaults() *SearchConsoleOpportunitiesResponseDataInner`

NewSearchConsoleOpportunitiesResponseDataInnerWithDefaults instantiates a new SearchConsoleOpportunitiesResponseDataInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetQuery

`func (o *SearchConsoleOpportunitiesResponseDataInner) GetQuery() string`

GetQuery returns the Query field if non-nil, zero value otherwise.

### GetQueryOk

`func (o *SearchConsoleOpportunitiesResponseDataInner) GetQueryOk() (*string, bool)`

GetQueryOk returns a tuple with the Query field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuery

`func (o *SearchConsoleOpportunitiesResponseDataInner) SetQuery(v string)`

SetQuery sets Query field to given value.

### HasQuery

`func (o *SearchConsoleOpportunitiesResponseDataInner) HasQuery() bool`

HasQuery returns a boolean if a field has been set.

### GetImpressions

`func (o *SearchConsoleOpportunitiesResponseDataInner) GetImpressions() int32`

GetImpressions returns the Impressions field if non-nil, zero value otherwise.

### GetImpressionsOk

`func (o *SearchConsoleOpportunitiesResponseDataInner) GetImpressionsOk() (*int32, bool)`

GetImpressionsOk returns a tuple with the Impressions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImpressions

`func (o *SearchConsoleOpportunitiesResponseDataInner) SetImpressions(v int32)`

SetImpressions sets Impressions field to given value.

### HasImpressions

`func (o *SearchConsoleOpportunitiesResponseDataInner) HasImpressions() bool`

HasImpressions returns a boolean if a field has been set.

### GetClicks

`func (o *SearchConsoleOpportunitiesResponseDataInner) GetClicks() int32`

GetClicks returns the Clicks field if non-nil, zero value otherwise.

### GetClicksOk

`func (o *SearchConsoleOpportunitiesResponseDataInner) GetClicksOk() (*int32, bool)`

GetClicksOk returns a tuple with the Clicks field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClicks

`func (o *SearchConsoleOpportunitiesResponseDataInner) SetClicks(v int32)`

SetClicks sets Clicks field to given value.

### HasClicks

`func (o *SearchConsoleOpportunitiesResponseDataInner) HasClicks() bool`

HasClicks returns a boolean if a field has been set.

### GetCtr

`func (o *SearchConsoleOpportunitiesResponseDataInner) GetCtr() float32`

GetCtr returns the Ctr field if non-nil, zero value otherwise.

### GetCtrOk

`func (o *SearchConsoleOpportunitiesResponseDataInner) GetCtrOk() (*float32, bool)`

GetCtrOk returns a tuple with the Ctr field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCtr

`func (o *SearchConsoleOpportunitiesResponseDataInner) SetCtr(v float32)`

SetCtr sets Ctr field to given value.

### HasCtr

`func (o *SearchConsoleOpportunitiesResponseDataInner) HasCtr() bool`

HasCtr returns a boolean if a field has been set.

### GetPosition

`func (o *SearchConsoleOpportunitiesResponseDataInner) GetPosition() float32`

GetPosition returns the Position field if non-nil, zero value otherwise.

### GetPositionOk

`func (o *SearchConsoleOpportunitiesResponseDataInner) GetPositionOk() (*float32, bool)`

GetPositionOk returns a tuple with the Position field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPosition

`func (o *SearchConsoleOpportunitiesResponseDataInner) SetPosition(v float32)`

SetPosition sets Position field to given value.

### HasPosition

`func (o *SearchConsoleOpportunitiesResponseDataInner) HasPosition() bool`

HasPosition returns a boolean if a field has been set.

### GetPotentialClicks

`func (o *SearchConsoleOpportunitiesResponseDataInner) GetPotentialClicks() int32`

GetPotentialClicks returns the PotentialClicks field if non-nil, zero value otherwise.

### GetPotentialClicksOk

`func (o *SearchConsoleOpportunitiesResponseDataInner) GetPotentialClicksOk() (*int32, bool)`

GetPotentialClicksOk returns a tuple with the PotentialClicks field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPotentialClicks

`func (o *SearchConsoleOpportunitiesResponseDataInner) SetPotentialClicks(v int32)`

SetPotentialClicks sets PotentialClicks field to given value.

### HasPotentialClicks

`func (o *SearchConsoleOpportunitiesResponseDataInner) HasPotentialClicks() bool`

HasPotentialClicks returns a boolean if a field has been set.

### SetPotentialClicksNil

`func (o *SearchConsoleOpportunitiesResponseDataInner) SetPotentialClicksNil(b bool)`

 SetPotentialClicksNil sets the value for PotentialClicks to be an explicit nil

### UnsetPotentialClicks
`func (o *SearchConsoleOpportunitiesResponseDataInner) UnsetPotentialClicks()`

UnsetPotentialClicks ensures that no value is present for PotentialClicks, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


