# AiModelSentimentRow

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Model** | Pointer to **string** | AI model key, as /dimensions/models lists it | [optional] 
**Label** | Pointer to **string** | Display name of the model | [optional] 
**Color** | Pointer to **string** | Hex color the app charts the model with | [optional] 
**SentimentsCount** | Pointer to **int32** | Brand sentiment verdicts in the model&#39;s answers | [optional] 
**PositiveCount** | Pointer to **int32** | Positive and very positive verdicts | [optional] 
**NegativeCount** | Pointer to **int32** | Negative and very negative verdicts | [optional] 
**NetSentiment** | Pointer to **NullableFloat32** | positive_count minus negative_count as a percentage (-100 to 100) of sentiments_count, neutral verdicts counted in the base; null when sentiments_count is 0 | [optional] 

## Methods

### NewAiModelSentimentRow

`func NewAiModelSentimentRow() *AiModelSentimentRow`

NewAiModelSentimentRow instantiates a new AiModelSentimentRow object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAiModelSentimentRowWithDefaults

`func NewAiModelSentimentRowWithDefaults() *AiModelSentimentRow`

NewAiModelSentimentRowWithDefaults instantiates a new AiModelSentimentRow object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetModel

`func (o *AiModelSentimentRow) GetModel() string`

GetModel returns the Model field if non-nil, zero value otherwise.

### GetModelOk

`func (o *AiModelSentimentRow) GetModelOk() (*string, bool)`

GetModelOk returns a tuple with the Model field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModel

`func (o *AiModelSentimentRow) SetModel(v string)`

SetModel sets Model field to given value.

### HasModel

`func (o *AiModelSentimentRow) HasModel() bool`

HasModel returns a boolean if a field has been set.

### GetLabel

`func (o *AiModelSentimentRow) GetLabel() string`

GetLabel returns the Label field if non-nil, zero value otherwise.

### GetLabelOk

`func (o *AiModelSentimentRow) GetLabelOk() (*string, bool)`

GetLabelOk returns a tuple with the Label field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabel

`func (o *AiModelSentimentRow) SetLabel(v string)`

SetLabel sets Label field to given value.

### HasLabel

`func (o *AiModelSentimentRow) HasLabel() bool`

HasLabel returns a boolean if a field has been set.

### GetColor

`func (o *AiModelSentimentRow) GetColor() string`

GetColor returns the Color field if non-nil, zero value otherwise.

### GetColorOk

`func (o *AiModelSentimentRow) GetColorOk() (*string, bool)`

GetColorOk returns a tuple with the Color field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetColor

`func (o *AiModelSentimentRow) SetColor(v string)`

SetColor sets Color field to given value.

### HasColor

`func (o *AiModelSentimentRow) HasColor() bool`

HasColor returns a boolean if a field has been set.

### GetSentimentsCount

`func (o *AiModelSentimentRow) GetSentimentsCount() int32`

GetSentimentsCount returns the SentimentsCount field if non-nil, zero value otherwise.

### GetSentimentsCountOk

`func (o *AiModelSentimentRow) GetSentimentsCountOk() (*int32, bool)`

GetSentimentsCountOk returns a tuple with the SentimentsCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSentimentsCount

`func (o *AiModelSentimentRow) SetSentimentsCount(v int32)`

SetSentimentsCount sets SentimentsCount field to given value.

### HasSentimentsCount

`func (o *AiModelSentimentRow) HasSentimentsCount() bool`

HasSentimentsCount returns a boolean if a field has been set.

### GetPositiveCount

`func (o *AiModelSentimentRow) GetPositiveCount() int32`

GetPositiveCount returns the PositiveCount field if non-nil, zero value otherwise.

### GetPositiveCountOk

`func (o *AiModelSentimentRow) GetPositiveCountOk() (*int32, bool)`

GetPositiveCountOk returns a tuple with the PositiveCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPositiveCount

`func (o *AiModelSentimentRow) SetPositiveCount(v int32)`

SetPositiveCount sets PositiveCount field to given value.

### HasPositiveCount

`func (o *AiModelSentimentRow) HasPositiveCount() bool`

HasPositiveCount returns a boolean if a field has been set.

### GetNegativeCount

`func (o *AiModelSentimentRow) GetNegativeCount() int32`

GetNegativeCount returns the NegativeCount field if non-nil, zero value otherwise.

### GetNegativeCountOk

`func (o *AiModelSentimentRow) GetNegativeCountOk() (*int32, bool)`

GetNegativeCountOk returns a tuple with the NegativeCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNegativeCount

`func (o *AiModelSentimentRow) SetNegativeCount(v int32)`

SetNegativeCount sets NegativeCount field to given value.

### HasNegativeCount

`func (o *AiModelSentimentRow) HasNegativeCount() bool`

HasNegativeCount returns a boolean if a field has been set.

### GetNetSentiment

`func (o *AiModelSentimentRow) GetNetSentiment() float32`

GetNetSentiment returns the NetSentiment field if non-nil, zero value otherwise.

### GetNetSentimentOk

`func (o *AiModelSentimentRow) GetNetSentimentOk() (*float32, bool)`

GetNetSentimentOk returns a tuple with the NetSentiment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNetSentiment

`func (o *AiModelSentimentRow) SetNetSentiment(v float32)`

SetNetSentiment sets NetSentiment field to given value.

### HasNetSentiment

`func (o *AiModelSentimentRow) HasNetSentiment() bool`

HasNetSentiment returns a boolean if a field has been set.

### SetNetSentimentNil

`func (o *AiModelSentimentRow) SetNetSentimentNil(b bool)`

 SetNetSentimentNil sets the value for NetSentiment to be an explicit nil

### UnsetNetSentiment
`func (o *AiModelSentimentRow) UnsetNetSentiment()`

UnsetNetSentiment ensures that no value is present for NetSentiment, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


