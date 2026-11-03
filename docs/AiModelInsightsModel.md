# AiModelInsightsModel

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Model** | Pointer to **string** | AI model key, as /dimensions/models lists it | [optional] 
**Label** | Pointer to **string** | Display name of the model | [optional] 
**Color** | Pointer to **string** | Hex color the app charts the model with | [optional] 

## Methods

### NewAiModelInsightsModel

`func NewAiModelInsightsModel() *AiModelInsightsModel`

NewAiModelInsightsModel instantiates a new AiModelInsightsModel object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAiModelInsightsModelWithDefaults

`func NewAiModelInsightsModelWithDefaults() *AiModelInsightsModel`

NewAiModelInsightsModelWithDefaults instantiates a new AiModelInsightsModel object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetModel

`func (o *AiModelInsightsModel) GetModel() string`

GetModel returns the Model field if non-nil, zero value otherwise.

### GetModelOk

`func (o *AiModelInsightsModel) GetModelOk() (*string, bool)`

GetModelOk returns a tuple with the Model field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModel

`func (o *AiModelInsightsModel) SetModel(v string)`

SetModel sets Model field to given value.

### HasModel

`func (o *AiModelInsightsModel) HasModel() bool`

HasModel returns a boolean if a field has been set.

### GetLabel

`func (o *AiModelInsightsModel) GetLabel() string`

GetLabel returns the Label field if non-nil, zero value otherwise.

### GetLabelOk

`func (o *AiModelInsightsModel) GetLabelOk() (*string, bool)`

GetLabelOk returns a tuple with the Label field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabel

`func (o *AiModelInsightsModel) SetLabel(v string)`

SetLabel sets Label field to given value.

### HasLabel

`func (o *AiModelInsightsModel) HasLabel() bool`

HasLabel returns a boolean if a field has been set.

### GetColor

`func (o *AiModelInsightsModel) GetColor() string`

GetColor returns the Color field if non-nil, zero value otherwise.

### GetColorOk

`func (o *AiModelInsightsModel) GetColorOk() (*string, bool)`

GetColorOk returns a tuple with the Color field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetColor

`func (o *AiModelInsightsModel) SetColor(v string)`

SetColor sets Color field to given value.

### HasColor

`func (o *AiModelInsightsModel) HasColor() bool`

HasColor returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


