# AiModelRateCell

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Value** | Pointer to **NullableFloat32** | numerator as a percentage (0-100) of denominator; null when the model has no answers in the window | [optional] 
**Numerator** | Pointer to **int32** | Mentions of the actor (or answers citing it) in the model&#39;s answers | [optional] 
**Denominator** | Pointer to **int32** | Answers of the model in the window | [optional] 

## Methods

### NewAiModelRateCell

`func NewAiModelRateCell() *AiModelRateCell`

NewAiModelRateCell instantiates a new AiModelRateCell object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAiModelRateCellWithDefaults

`func NewAiModelRateCellWithDefaults() *AiModelRateCell`

NewAiModelRateCellWithDefaults instantiates a new AiModelRateCell object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetValue

`func (o *AiModelRateCell) GetValue() float32`

GetValue returns the Value field if non-nil, zero value otherwise.

### GetValueOk

`func (o *AiModelRateCell) GetValueOk() (*float32, bool)`

GetValueOk returns a tuple with the Value field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValue

`func (o *AiModelRateCell) SetValue(v float32)`

SetValue sets Value field to given value.

### HasValue

`func (o *AiModelRateCell) HasValue() bool`

HasValue returns a boolean if a field has been set.

### SetValueNil

`func (o *AiModelRateCell) SetValueNil(b bool)`

 SetValueNil sets the value for Value to be an explicit nil

### UnsetValue
`func (o *AiModelRateCell) UnsetValue()`

UnsetValue ensures that no value is present for Value, not even an explicit nil
### GetNumerator

`func (o *AiModelRateCell) GetNumerator() int32`

GetNumerator returns the Numerator field if non-nil, zero value otherwise.

### GetNumeratorOk

`func (o *AiModelRateCell) GetNumeratorOk() (*int32, bool)`

GetNumeratorOk returns a tuple with the Numerator field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNumerator

`func (o *AiModelRateCell) SetNumerator(v int32)`

SetNumerator sets Numerator field to given value.

### HasNumerator

`func (o *AiModelRateCell) HasNumerator() bool`

HasNumerator returns a boolean if a field has been set.

### GetDenominator

`func (o *AiModelRateCell) GetDenominator() int32`

GetDenominator returns the Denominator field if non-nil, zero value otherwise.

### GetDenominatorOk

`func (o *AiModelRateCell) GetDenominatorOk() (*int32, bool)`

GetDenominatorOk returns a tuple with the Denominator field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDenominator

`func (o *AiModelRateCell) SetDenominator(v int32)`

SetDenominator sets Denominator field to given value.

### HasDenominator

`func (o *AiModelRateCell) HasDenominator() bool`

HasDenominator returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


