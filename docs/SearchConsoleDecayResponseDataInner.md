# SearchConsoleDecayResponseDataInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Key** | Pointer to **string** | The page URL or query | [optional] 
**Clicks** | Pointer to **int32** |  | [optional] 
**ClicksPrevious** | Pointer to **int32** |  | [optional] 
**ClicksChange** | Pointer to **int32** | clicks minus clicks_previous (negative) | [optional] 
**ClicksChangePct** | Pointer to **float32** |  | [optional] 
**Impressions** | Pointer to **int32** |  | [optional] 
**ImpressionsPrevious** | Pointer to **int32** |  | [optional] 
**Position** | Pointer to **NullableFloat32** | Null when the key had no impressions in the window | [optional] 
**PositionPrevious** | Pointer to **NullableFloat32** |  | [optional] 

## Methods

### NewSearchConsoleDecayResponseDataInner

`func NewSearchConsoleDecayResponseDataInner() *SearchConsoleDecayResponseDataInner`

NewSearchConsoleDecayResponseDataInner instantiates a new SearchConsoleDecayResponseDataInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSearchConsoleDecayResponseDataInnerWithDefaults

`func NewSearchConsoleDecayResponseDataInnerWithDefaults() *SearchConsoleDecayResponseDataInner`

NewSearchConsoleDecayResponseDataInnerWithDefaults instantiates a new SearchConsoleDecayResponseDataInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetKey

`func (o *SearchConsoleDecayResponseDataInner) GetKey() string`

GetKey returns the Key field if non-nil, zero value otherwise.

### GetKeyOk

`func (o *SearchConsoleDecayResponseDataInner) GetKeyOk() (*string, bool)`

GetKeyOk returns a tuple with the Key field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKey

`func (o *SearchConsoleDecayResponseDataInner) SetKey(v string)`

SetKey sets Key field to given value.

### HasKey

`func (o *SearchConsoleDecayResponseDataInner) HasKey() bool`

HasKey returns a boolean if a field has been set.

### GetClicks

`func (o *SearchConsoleDecayResponseDataInner) GetClicks() int32`

GetClicks returns the Clicks field if non-nil, zero value otherwise.

### GetClicksOk

`func (o *SearchConsoleDecayResponseDataInner) GetClicksOk() (*int32, bool)`

GetClicksOk returns a tuple with the Clicks field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClicks

`func (o *SearchConsoleDecayResponseDataInner) SetClicks(v int32)`

SetClicks sets Clicks field to given value.

### HasClicks

`func (o *SearchConsoleDecayResponseDataInner) HasClicks() bool`

HasClicks returns a boolean if a field has been set.

### GetClicksPrevious

`func (o *SearchConsoleDecayResponseDataInner) GetClicksPrevious() int32`

GetClicksPrevious returns the ClicksPrevious field if non-nil, zero value otherwise.

### GetClicksPreviousOk

`func (o *SearchConsoleDecayResponseDataInner) GetClicksPreviousOk() (*int32, bool)`

GetClicksPreviousOk returns a tuple with the ClicksPrevious field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClicksPrevious

`func (o *SearchConsoleDecayResponseDataInner) SetClicksPrevious(v int32)`

SetClicksPrevious sets ClicksPrevious field to given value.

### HasClicksPrevious

`func (o *SearchConsoleDecayResponseDataInner) HasClicksPrevious() bool`

HasClicksPrevious returns a boolean if a field has been set.

### GetClicksChange

`func (o *SearchConsoleDecayResponseDataInner) GetClicksChange() int32`

GetClicksChange returns the ClicksChange field if non-nil, zero value otherwise.

### GetClicksChangeOk

`func (o *SearchConsoleDecayResponseDataInner) GetClicksChangeOk() (*int32, bool)`

GetClicksChangeOk returns a tuple with the ClicksChange field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClicksChange

`func (o *SearchConsoleDecayResponseDataInner) SetClicksChange(v int32)`

SetClicksChange sets ClicksChange field to given value.

### HasClicksChange

`func (o *SearchConsoleDecayResponseDataInner) HasClicksChange() bool`

HasClicksChange returns a boolean if a field has been set.

### GetClicksChangePct

`func (o *SearchConsoleDecayResponseDataInner) GetClicksChangePct() float32`

GetClicksChangePct returns the ClicksChangePct field if non-nil, zero value otherwise.

### GetClicksChangePctOk

`func (o *SearchConsoleDecayResponseDataInner) GetClicksChangePctOk() (*float32, bool)`

GetClicksChangePctOk returns a tuple with the ClicksChangePct field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClicksChangePct

`func (o *SearchConsoleDecayResponseDataInner) SetClicksChangePct(v float32)`

SetClicksChangePct sets ClicksChangePct field to given value.

### HasClicksChangePct

`func (o *SearchConsoleDecayResponseDataInner) HasClicksChangePct() bool`

HasClicksChangePct returns a boolean if a field has been set.

### GetImpressions

`func (o *SearchConsoleDecayResponseDataInner) GetImpressions() int32`

GetImpressions returns the Impressions field if non-nil, zero value otherwise.

### GetImpressionsOk

`func (o *SearchConsoleDecayResponseDataInner) GetImpressionsOk() (*int32, bool)`

GetImpressionsOk returns a tuple with the Impressions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImpressions

`func (o *SearchConsoleDecayResponseDataInner) SetImpressions(v int32)`

SetImpressions sets Impressions field to given value.

### HasImpressions

`func (o *SearchConsoleDecayResponseDataInner) HasImpressions() bool`

HasImpressions returns a boolean if a field has been set.

### GetImpressionsPrevious

`func (o *SearchConsoleDecayResponseDataInner) GetImpressionsPrevious() int32`

GetImpressionsPrevious returns the ImpressionsPrevious field if non-nil, zero value otherwise.

### GetImpressionsPreviousOk

`func (o *SearchConsoleDecayResponseDataInner) GetImpressionsPreviousOk() (*int32, bool)`

GetImpressionsPreviousOk returns a tuple with the ImpressionsPrevious field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImpressionsPrevious

`func (o *SearchConsoleDecayResponseDataInner) SetImpressionsPrevious(v int32)`

SetImpressionsPrevious sets ImpressionsPrevious field to given value.

### HasImpressionsPrevious

`func (o *SearchConsoleDecayResponseDataInner) HasImpressionsPrevious() bool`

HasImpressionsPrevious returns a boolean if a field has been set.

### GetPosition

`func (o *SearchConsoleDecayResponseDataInner) GetPosition() float32`

GetPosition returns the Position field if non-nil, zero value otherwise.

### GetPositionOk

`func (o *SearchConsoleDecayResponseDataInner) GetPositionOk() (*float32, bool)`

GetPositionOk returns a tuple with the Position field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPosition

`func (o *SearchConsoleDecayResponseDataInner) SetPosition(v float32)`

SetPosition sets Position field to given value.

### HasPosition

`func (o *SearchConsoleDecayResponseDataInner) HasPosition() bool`

HasPosition returns a boolean if a field has been set.

### SetPositionNil

`func (o *SearchConsoleDecayResponseDataInner) SetPositionNil(b bool)`

 SetPositionNil sets the value for Position to be an explicit nil

### UnsetPosition
`func (o *SearchConsoleDecayResponseDataInner) UnsetPosition()`

UnsetPosition ensures that no value is present for Position, not even an explicit nil
### GetPositionPrevious

`func (o *SearchConsoleDecayResponseDataInner) GetPositionPrevious() float32`

GetPositionPrevious returns the PositionPrevious field if non-nil, zero value otherwise.

### GetPositionPreviousOk

`func (o *SearchConsoleDecayResponseDataInner) GetPositionPreviousOk() (*float32, bool)`

GetPositionPreviousOk returns a tuple with the PositionPrevious field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPositionPrevious

`func (o *SearchConsoleDecayResponseDataInner) SetPositionPrevious(v float32)`

SetPositionPrevious sets PositionPrevious field to given value.

### HasPositionPrevious

`func (o *SearchConsoleDecayResponseDataInner) HasPositionPrevious() bool`

HasPositionPrevious returns a boolean if a field has been set.

### SetPositionPreviousNil

`func (o *SearchConsoleDecayResponseDataInner) SetPositionPreviousNil(b bool)`

 SetPositionPreviousNil sets the value for PositionPrevious to be an explicit nil

### UnsetPositionPrevious
`func (o *SearchConsoleDecayResponseDataInner) UnsetPositionPrevious()`

UnsetPositionPrevious ensures that no value is present for PositionPrevious, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


