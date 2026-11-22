# BingWebmasterListResponseDataInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Key** | Pointer to **string** | The page URL or the query | [optional] 
**Impressions** | Pointer to **int32** |  | [optional] 
**Clicks** | Pointer to **int32** |  | [optional] 
**Ctr** | Pointer to **float32** | 0..1 fraction | [optional] 
**AvgImpressionPosition** | Pointer to **NullableFloat32** | Average position when shown, weighted by impressions (lower is better) | [optional] 
**AvgClickPosition** | Pointer to **NullableFloat32** | Average position when clicked, weighted by clicks. Null without clicks. | [optional] 

## Methods

### NewBingWebmasterListResponseDataInner

`func NewBingWebmasterListResponseDataInner() *BingWebmasterListResponseDataInner`

NewBingWebmasterListResponseDataInner instantiates a new BingWebmasterListResponseDataInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewBingWebmasterListResponseDataInnerWithDefaults

`func NewBingWebmasterListResponseDataInnerWithDefaults() *BingWebmasterListResponseDataInner`

NewBingWebmasterListResponseDataInnerWithDefaults instantiates a new BingWebmasterListResponseDataInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetKey

`func (o *BingWebmasterListResponseDataInner) GetKey() string`

GetKey returns the Key field if non-nil, zero value otherwise.

### GetKeyOk

`func (o *BingWebmasterListResponseDataInner) GetKeyOk() (*string, bool)`

GetKeyOk returns a tuple with the Key field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKey

`func (o *BingWebmasterListResponseDataInner) SetKey(v string)`

SetKey sets Key field to given value.

### HasKey

`func (o *BingWebmasterListResponseDataInner) HasKey() bool`

HasKey returns a boolean if a field has been set.

### GetImpressions

`func (o *BingWebmasterListResponseDataInner) GetImpressions() int32`

GetImpressions returns the Impressions field if non-nil, zero value otherwise.

### GetImpressionsOk

`func (o *BingWebmasterListResponseDataInner) GetImpressionsOk() (*int32, bool)`

GetImpressionsOk returns a tuple with the Impressions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImpressions

`func (o *BingWebmasterListResponseDataInner) SetImpressions(v int32)`

SetImpressions sets Impressions field to given value.

### HasImpressions

`func (o *BingWebmasterListResponseDataInner) HasImpressions() bool`

HasImpressions returns a boolean if a field has been set.

### GetClicks

`func (o *BingWebmasterListResponseDataInner) GetClicks() int32`

GetClicks returns the Clicks field if non-nil, zero value otherwise.

### GetClicksOk

`func (o *BingWebmasterListResponseDataInner) GetClicksOk() (*int32, bool)`

GetClicksOk returns a tuple with the Clicks field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClicks

`func (o *BingWebmasterListResponseDataInner) SetClicks(v int32)`

SetClicks sets Clicks field to given value.

### HasClicks

`func (o *BingWebmasterListResponseDataInner) HasClicks() bool`

HasClicks returns a boolean if a field has been set.

### GetCtr

`func (o *BingWebmasterListResponseDataInner) GetCtr() float32`

GetCtr returns the Ctr field if non-nil, zero value otherwise.

### GetCtrOk

`func (o *BingWebmasterListResponseDataInner) GetCtrOk() (*float32, bool)`

GetCtrOk returns a tuple with the Ctr field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCtr

`func (o *BingWebmasterListResponseDataInner) SetCtr(v float32)`

SetCtr sets Ctr field to given value.

### HasCtr

`func (o *BingWebmasterListResponseDataInner) HasCtr() bool`

HasCtr returns a boolean if a field has been set.

### GetAvgImpressionPosition

`func (o *BingWebmasterListResponseDataInner) GetAvgImpressionPosition() float32`

GetAvgImpressionPosition returns the AvgImpressionPosition field if non-nil, zero value otherwise.

### GetAvgImpressionPositionOk

`func (o *BingWebmasterListResponseDataInner) GetAvgImpressionPositionOk() (*float32, bool)`

GetAvgImpressionPositionOk returns a tuple with the AvgImpressionPosition field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAvgImpressionPosition

`func (o *BingWebmasterListResponseDataInner) SetAvgImpressionPosition(v float32)`

SetAvgImpressionPosition sets AvgImpressionPosition field to given value.

### HasAvgImpressionPosition

`func (o *BingWebmasterListResponseDataInner) HasAvgImpressionPosition() bool`

HasAvgImpressionPosition returns a boolean if a field has been set.

### SetAvgImpressionPositionNil

`func (o *BingWebmasterListResponseDataInner) SetAvgImpressionPositionNil(b bool)`

 SetAvgImpressionPositionNil sets the value for AvgImpressionPosition to be an explicit nil

### UnsetAvgImpressionPosition
`func (o *BingWebmasterListResponseDataInner) UnsetAvgImpressionPosition()`

UnsetAvgImpressionPosition ensures that no value is present for AvgImpressionPosition, not even an explicit nil
### GetAvgClickPosition

`func (o *BingWebmasterListResponseDataInner) GetAvgClickPosition() float32`

GetAvgClickPosition returns the AvgClickPosition field if non-nil, zero value otherwise.

### GetAvgClickPositionOk

`func (o *BingWebmasterListResponseDataInner) GetAvgClickPositionOk() (*float32, bool)`

GetAvgClickPositionOk returns a tuple with the AvgClickPosition field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAvgClickPosition

`func (o *BingWebmasterListResponseDataInner) SetAvgClickPosition(v float32)`

SetAvgClickPosition sets AvgClickPosition field to given value.

### HasAvgClickPosition

`func (o *BingWebmasterListResponseDataInner) HasAvgClickPosition() bool`

HasAvgClickPosition returns a boolean if a field has been set.

### SetAvgClickPositionNil

`func (o *BingWebmasterListResponseDataInner) SetAvgClickPositionNil(b bool)`

 SetAvgClickPositionNil sets the value for AvgClickPosition to be an explicit nil

### UnsetAvgClickPosition
`func (o *BingWebmasterListResponseDataInner) UnsetAvgClickPosition()`

UnsetAvgClickPosition ensures that no value is present for AvgClickPosition, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


