# AiModelSentimentCell

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Value** | Pointer to **NullableFloat32** | The actor&#39;s net sentiment in the model, positive_count minus negative_count as a percentage (-100 to 100) of total_sentiments; null when total_sentiments is 0 | [optional] 
**TotalSentiments** | Pointer to **int32** | The actor&#39;s sentiment verdicts in the model&#39;s answers | [optional] 
**PositiveCount** | Pointer to **int32** | Positive and very positive verdicts | [optional] 
**NegativeCount** | Pointer to **int32** | Negative and very negative verdicts | [optional] 

## Methods

### NewAiModelSentimentCell

`func NewAiModelSentimentCell() *AiModelSentimentCell`

NewAiModelSentimentCell instantiates a new AiModelSentimentCell object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAiModelSentimentCellWithDefaults

`func NewAiModelSentimentCellWithDefaults() *AiModelSentimentCell`

NewAiModelSentimentCellWithDefaults instantiates a new AiModelSentimentCell object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetValue

`func (o *AiModelSentimentCell) GetValue() float32`

GetValue returns the Value field if non-nil, zero value otherwise.

### GetValueOk

`func (o *AiModelSentimentCell) GetValueOk() (*float32, bool)`

GetValueOk returns a tuple with the Value field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValue

`func (o *AiModelSentimentCell) SetValue(v float32)`

SetValue sets Value field to given value.

### HasValue

`func (o *AiModelSentimentCell) HasValue() bool`

HasValue returns a boolean if a field has been set.

### SetValueNil

`func (o *AiModelSentimentCell) SetValueNil(b bool)`

 SetValueNil sets the value for Value to be an explicit nil

### UnsetValue
`func (o *AiModelSentimentCell) UnsetValue()`

UnsetValue ensures that no value is present for Value, not even an explicit nil
### GetTotalSentiments

`func (o *AiModelSentimentCell) GetTotalSentiments() int32`

GetTotalSentiments returns the TotalSentiments field if non-nil, zero value otherwise.

### GetTotalSentimentsOk

`func (o *AiModelSentimentCell) GetTotalSentimentsOk() (*int32, bool)`

GetTotalSentimentsOk returns a tuple with the TotalSentiments field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalSentiments

`func (o *AiModelSentimentCell) SetTotalSentiments(v int32)`

SetTotalSentiments sets TotalSentiments field to given value.

### HasTotalSentiments

`func (o *AiModelSentimentCell) HasTotalSentiments() bool`

HasTotalSentiments returns a boolean if a field has been set.

### GetPositiveCount

`func (o *AiModelSentimentCell) GetPositiveCount() int32`

GetPositiveCount returns the PositiveCount field if non-nil, zero value otherwise.

### GetPositiveCountOk

`func (o *AiModelSentimentCell) GetPositiveCountOk() (*int32, bool)`

GetPositiveCountOk returns a tuple with the PositiveCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPositiveCount

`func (o *AiModelSentimentCell) SetPositiveCount(v int32)`

SetPositiveCount sets PositiveCount field to given value.

### HasPositiveCount

`func (o *AiModelSentimentCell) HasPositiveCount() bool`

HasPositiveCount returns a boolean if a field has been set.

### GetNegativeCount

`func (o *AiModelSentimentCell) GetNegativeCount() int32`

GetNegativeCount returns the NegativeCount field if non-nil, zero value otherwise.

### GetNegativeCountOk

`func (o *AiModelSentimentCell) GetNegativeCountOk() (*int32, bool)`

GetNegativeCountOk returns a tuple with the NegativeCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNegativeCount

`func (o *AiModelSentimentCell) SetNegativeCount(v int32)`

SetNegativeCount sets NegativeCount field to given value.

### HasNegativeCount

`func (o *AiModelSentimentCell) HasNegativeCount() bool`

HasNegativeCount returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


