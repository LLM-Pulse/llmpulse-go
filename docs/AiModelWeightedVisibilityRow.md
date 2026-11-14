# AiModelWeightedVisibilityRow

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Model** | Pointer to **string** | AI model key, as /dimensions/models lists it | [optional] 
**Label** | Pointer to **string** | Display name of the model | [optional] 
**Color** | Pointer to **string** | Hex color the app charts the model with | [optional] 
**WeightedVisibilityScore** | Pointer to **float32** | The brand&#39;s AI Visibility Score in the model, its points there divided by the days the model answered; 0 when it has none | [optional] 
**ShareOfTotal** | Pointer to **NullableFloat32** | The model&#39;s percentage (0-100) of the brand&#39;s AI Visibility Score points; null when the brand has none | [optional] 

## Methods

### NewAiModelWeightedVisibilityRow

`func NewAiModelWeightedVisibilityRow() *AiModelWeightedVisibilityRow`

NewAiModelWeightedVisibilityRow instantiates a new AiModelWeightedVisibilityRow object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAiModelWeightedVisibilityRowWithDefaults

`func NewAiModelWeightedVisibilityRowWithDefaults() *AiModelWeightedVisibilityRow`

NewAiModelWeightedVisibilityRowWithDefaults instantiates a new AiModelWeightedVisibilityRow object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetModel

`func (o *AiModelWeightedVisibilityRow) GetModel() string`

GetModel returns the Model field if non-nil, zero value otherwise.

### GetModelOk

`func (o *AiModelWeightedVisibilityRow) GetModelOk() (*string, bool)`

GetModelOk returns a tuple with the Model field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModel

`func (o *AiModelWeightedVisibilityRow) SetModel(v string)`

SetModel sets Model field to given value.

### HasModel

`func (o *AiModelWeightedVisibilityRow) HasModel() bool`

HasModel returns a boolean if a field has been set.

### GetLabel

`func (o *AiModelWeightedVisibilityRow) GetLabel() string`

GetLabel returns the Label field if non-nil, zero value otherwise.

### GetLabelOk

`func (o *AiModelWeightedVisibilityRow) GetLabelOk() (*string, bool)`

GetLabelOk returns a tuple with the Label field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabel

`func (o *AiModelWeightedVisibilityRow) SetLabel(v string)`

SetLabel sets Label field to given value.

### HasLabel

`func (o *AiModelWeightedVisibilityRow) HasLabel() bool`

HasLabel returns a boolean if a field has been set.

### GetColor

`func (o *AiModelWeightedVisibilityRow) GetColor() string`

GetColor returns the Color field if non-nil, zero value otherwise.

### GetColorOk

`func (o *AiModelWeightedVisibilityRow) GetColorOk() (*string, bool)`

GetColorOk returns a tuple with the Color field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetColor

`func (o *AiModelWeightedVisibilityRow) SetColor(v string)`

SetColor sets Color field to given value.

### HasColor

`func (o *AiModelWeightedVisibilityRow) HasColor() bool`

HasColor returns a boolean if a field has been set.

### GetWeightedVisibilityScore

`func (o *AiModelWeightedVisibilityRow) GetWeightedVisibilityScore() float32`

GetWeightedVisibilityScore returns the WeightedVisibilityScore field if non-nil, zero value otherwise.

### GetWeightedVisibilityScoreOk

`func (o *AiModelWeightedVisibilityRow) GetWeightedVisibilityScoreOk() (*float32, bool)`

GetWeightedVisibilityScoreOk returns a tuple with the WeightedVisibilityScore field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWeightedVisibilityScore

`func (o *AiModelWeightedVisibilityRow) SetWeightedVisibilityScore(v float32)`

SetWeightedVisibilityScore sets WeightedVisibilityScore field to given value.

### HasWeightedVisibilityScore

`func (o *AiModelWeightedVisibilityRow) HasWeightedVisibilityScore() bool`

HasWeightedVisibilityScore returns a boolean if a field has been set.

### GetShareOfTotal

`func (o *AiModelWeightedVisibilityRow) GetShareOfTotal() float32`

GetShareOfTotal returns the ShareOfTotal field if non-nil, zero value otherwise.

### GetShareOfTotalOk

`func (o *AiModelWeightedVisibilityRow) GetShareOfTotalOk() (*float32, bool)`

GetShareOfTotalOk returns a tuple with the ShareOfTotal field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShareOfTotal

`func (o *AiModelWeightedVisibilityRow) SetShareOfTotal(v float32)`

SetShareOfTotal sets ShareOfTotal field to given value.

### HasShareOfTotal

`func (o *AiModelWeightedVisibilityRow) HasShareOfTotal() bool`

HasShareOfTotal returns a boolean if a field has been set.

### SetShareOfTotalNil

`func (o *AiModelWeightedVisibilityRow) SetShareOfTotalNil(b bool)`

 SetShareOfTotalNil sets the value for ShareOfTotal to be an explicit nil

### UnsetShareOfTotal
`func (o *AiModelWeightedVisibilityRow) UnsetShareOfTotal()`

UnsetShareOfTotal ensures that no value is present for ShareOfTotal, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


