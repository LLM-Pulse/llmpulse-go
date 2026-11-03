# AiModelCitationsRow

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Model** | Pointer to **string** | AI model key, as /dimensions/models lists it | [optional] 
**Label** | Pointer to **string** | Display name of the model | [optional] 
**Color** | Pointer to **string** | Hex color the app charts the model with | [optional] 
**CitationsCount** | Pointer to **int32** | Citations of the brand&#39;s URLs in the model&#39;s answers; 0 when it has none | [optional] 
**ShareOfTotal** | Pointer to **NullableFloat32** | The model&#39;s percentage (0-100) of total_citations; null when total_citations is 0 | [optional] 

## Methods

### NewAiModelCitationsRow

`func NewAiModelCitationsRow() *AiModelCitationsRow`

NewAiModelCitationsRow instantiates a new AiModelCitationsRow object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAiModelCitationsRowWithDefaults

`func NewAiModelCitationsRowWithDefaults() *AiModelCitationsRow`

NewAiModelCitationsRowWithDefaults instantiates a new AiModelCitationsRow object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetModel

`func (o *AiModelCitationsRow) GetModel() string`

GetModel returns the Model field if non-nil, zero value otherwise.

### GetModelOk

`func (o *AiModelCitationsRow) GetModelOk() (*string, bool)`

GetModelOk returns a tuple with the Model field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModel

`func (o *AiModelCitationsRow) SetModel(v string)`

SetModel sets Model field to given value.

### HasModel

`func (o *AiModelCitationsRow) HasModel() bool`

HasModel returns a boolean if a field has been set.

### GetLabel

`func (o *AiModelCitationsRow) GetLabel() string`

GetLabel returns the Label field if non-nil, zero value otherwise.

### GetLabelOk

`func (o *AiModelCitationsRow) GetLabelOk() (*string, bool)`

GetLabelOk returns a tuple with the Label field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabel

`func (o *AiModelCitationsRow) SetLabel(v string)`

SetLabel sets Label field to given value.

### HasLabel

`func (o *AiModelCitationsRow) HasLabel() bool`

HasLabel returns a boolean if a field has been set.

### GetColor

`func (o *AiModelCitationsRow) GetColor() string`

GetColor returns the Color field if non-nil, zero value otherwise.

### GetColorOk

`func (o *AiModelCitationsRow) GetColorOk() (*string, bool)`

GetColorOk returns a tuple with the Color field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetColor

`func (o *AiModelCitationsRow) SetColor(v string)`

SetColor sets Color field to given value.

### HasColor

`func (o *AiModelCitationsRow) HasColor() bool`

HasColor returns a boolean if a field has been set.

### GetCitationsCount

`func (o *AiModelCitationsRow) GetCitationsCount() int32`

GetCitationsCount returns the CitationsCount field if non-nil, zero value otherwise.

### GetCitationsCountOk

`func (o *AiModelCitationsRow) GetCitationsCountOk() (*int32, bool)`

GetCitationsCountOk returns a tuple with the CitationsCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCitationsCount

`func (o *AiModelCitationsRow) SetCitationsCount(v int32)`

SetCitationsCount sets CitationsCount field to given value.

### HasCitationsCount

`func (o *AiModelCitationsRow) HasCitationsCount() bool`

HasCitationsCount returns a boolean if a field has been set.

### GetShareOfTotal

`func (o *AiModelCitationsRow) GetShareOfTotal() float32`

GetShareOfTotal returns the ShareOfTotal field if non-nil, zero value otherwise.

### GetShareOfTotalOk

`func (o *AiModelCitationsRow) GetShareOfTotalOk() (*float32, bool)`

GetShareOfTotalOk returns a tuple with the ShareOfTotal field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShareOfTotal

`func (o *AiModelCitationsRow) SetShareOfTotal(v float32)`

SetShareOfTotal sets ShareOfTotal field to given value.

### HasShareOfTotal

`func (o *AiModelCitationsRow) HasShareOfTotal() bool`

HasShareOfTotal returns a boolean if a field has been set.

### SetShareOfTotalNil

`func (o *AiModelCitationsRow) SetShareOfTotalNil(b bool)`

 SetShareOfTotalNil sets the value for ShareOfTotal to be an explicit nil

### UnsetShareOfTotal
`func (o *AiModelCitationsRow) UnsetShareOfTotal()`

UnsetShareOfTotal ensures that no value is present for ShareOfTotal, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


