# SearchConsoleMetrics

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Impressions** | Pointer to **int32** |  | [optional] 
**Clicks** | Pointer to **int32** |  | [optional] 
**Ctr** | Pointer to **float32** | 0..1 fraction | [optional] 
**Position** | Pointer to **float32** | Impression-weighted average position | [optional] 

## Methods

### NewSearchConsoleMetrics

`func NewSearchConsoleMetrics() *SearchConsoleMetrics`

NewSearchConsoleMetrics instantiates a new SearchConsoleMetrics object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSearchConsoleMetricsWithDefaults

`func NewSearchConsoleMetricsWithDefaults() *SearchConsoleMetrics`

NewSearchConsoleMetricsWithDefaults instantiates a new SearchConsoleMetrics object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetImpressions

`func (o *SearchConsoleMetrics) GetImpressions() int32`

GetImpressions returns the Impressions field if non-nil, zero value otherwise.

### GetImpressionsOk

`func (o *SearchConsoleMetrics) GetImpressionsOk() (*int32, bool)`

GetImpressionsOk returns a tuple with the Impressions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImpressions

`func (o *SearchConsoleMetrics) SetImpressions(v int32)`

SetImpressions sets Impressions field to given value.

### HasImpressions

`func (o *SearchConsoleMetrics) HasImpressions() bool`

HasImpressions returns a boolean if a field has been set.

### GetClicks

`func (o *SearchConsoleMetrics) GetClicks() int32`

GetClicks returns the Clicks field if non-nil, zero value otherwise.

### GetClicksOk

`func (o *SearchConsoleMetrics) GetClicksOk() (*int32, bool)`

GetClicksOk returns a tuple with the Clicks field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClicks

`func (o *SearchConsoleMetrics) SetClicks(v int32)`

SetClicks sets Clicks field to given value.

### HasClicks

`func (o *SearchConsoleMetrics) HasClicks() bool`

HasClicks returns a boolean if a field has been set.

### GetCtr

`func (o *SearchConsoleMetrics) GetCtr() float32`

GetCtr returns the Ctr field if non-nil, zero value otherwise.

### GetCtrOk

`func (o *SearchConsoleMetrics) GetCtrOk() (*float32, bool)`

GetCtrOk returns a tuple with the Ctr field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCtr

`func (o *SearchConsoleMetrics) SetCtr(v float32)`

SetCtr sets Ctr field to given value.

### HasCtr

`func (o *SearchConsoleMetrics) HasCtr() bool`

HasCtr returns a boolean if a field has been set.

### GetPosition

`func (o *SearchConsoleMetrics) GetPosition() float32`

GetPosition returns the Position field if non-nil, zero value otherwise.

### GetPositionOk

`func (o *SearchConsoleMetrics) GetPositionOk() (*float32, bool)`

GetPositionOk returns a tuple with the Position field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPosition

`func (o *SearchConsoleMetrics) SetPosition(v float32)`

SetPosition sets Position field to given value.

### HasPosition

`func (o *SearchConsoleMetrics) HasPosition() bool`

HasPosition returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


