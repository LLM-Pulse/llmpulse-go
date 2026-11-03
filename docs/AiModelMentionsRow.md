# AiModelMentionsRow

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Model** | Pointer to **string** | AI model key, as /dimensions/models lists it | [optional] 
**Label** | Pointer to **string** | Display name of the model | [optional] 
**Color** | Pointer to **string** | Hex color the app charts the model with | [optional] 
**MentionsCount** | Pointer to **int32** | Brand mentions in the model&#39;s answers; 0 when it has none | [optional] 
**ShareOfTotal** | Pointer to **NullableFloat32** | The model&#39;s percentage (0-100) of total_mentions; null when total_mentions is 0 | [optional] 

## Methods

### NewAiModelMentionsRow

`func NewAiModelMentionsRow() *AiModelMentionsRow`

NewAiModelMentionsRow instantiates a new AiModelMentionsRow object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAiModelMentionsRowWithDefaults

`func NewAiModelMentionsRowWithDefaults() *AiModelMentionsRow`

NewAiModelMentionsRowWithDefaults instantiates a new AiModelMentionsRow object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetModel

`func (o *AiModelMentionsRow) GetModel() string`

GetModel returns the Model field if non-nil, zero value otherwise.

### GetModelOk

`func (o *AiModelMentionsRow) GetModelOk() (*string, bool)`

GetModelOk returns a tuple with the Model field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModel

`func (o *AiModelMentionsRow) SetModel(v string)`

SetModel sets Model field to given value.

### HasModel

`func (o *AiModelMentionsRow) HasModel() bool`

HasModel returns a boolean if a field has been set.

### GetLabel

`func (o *AiModelMentionsRow) GetLabel() string`

GetLabel returns the Label field if non-nil, zero value otherwise.

### GetLabelOk

`func (o *AiModelMentionsRow) GetLabelOk() (*string, bool)`

GetLabelOk returns a tuple with the Label field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabel

`func (o *AiModelMentionsRow) SetLabel(v string)`

SetLabel sets Label field to given value.

### HasLabel

`func (o *AiModelMentionsRow) HasLabel() bool`

HasLabel returns a boolean if a field has been set.

### GetColor

`func (o *AiModelMentionsRow) GetColor() string`

GetColor returns the Color field if non-nil, zero value otherwise.

### GetColorOk

`func (o *AiModelMentionsRow) GetColorOk() (*string, bool)`

GetColorOk returns a tuple with the Color field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetColor

`func (o *AiModelMentionsRow) SetColor(v string)`

SetColor sets Color field to given value.

### HasColor

`func (o *AiModelMentionsRow) HasColor() bool`

HasColor returns a boolean if a field has been set.

### GetMentionsCount

`func (o *AiModelMentionsRow) GetMentionsCount() int32`

GetMentionsCount returns the MentionsCount field if non-nil, zero value otherwise.

### GetMentionsCountOk

`func (o *AiModelMentionsRow) GetMentionsCountOk() (*int32, bool)`

GetMentionsCountOk returns a tuple with the MentionsCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMentionsCount

`func (o *AiModelMentionsRow) SetMentionsCount(v int32)`

SetMentionsCount sets MentionsCount field to given value.

### HasMentionsCount

`func (o *AiModelMentionsRow) HasMentionsCount() bool`

HasMentionsCount returns a boolean if a field has been set.

### GetShareOfTotal

`func (o *AiModelMentionsRow) GetShareOfTotal() float32`

GetShareOfTotal returns the ShareOfTotal field if non-nil, zero value otherwise.

### GetShareOfTotalOk

`func (o *AiModelMentionsRow) GetShareOfTotalOk() (*float32, bool)`

GetShareOfTotalOk returns a tuple with the ShareOfTotal field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShareOfTotal

`func (o *AiModelMentionsRow) SetShareOfTotal(v float32)`

SetShareOfTotal sets ShareOfTotal field to given value.

### HasShareOfTotal

`func (o *AiModelMentionsRow) HasShareOfTotal() bool`

HasShareOfTotal returns a boolean if a field has been set.

### SetShareOfTotalNil

`func (o *AiModelMentionsRow) SetShareOfTotalNil(b bool)`

 SetShareOfTotalNil sets the value for ShareOfTotal to be an explicit nil

### UnsetShareOfTotal
`func (o *AiModelMentionsRow) UnsetShareOfTotal()`

UnsetShareOfTotal ensures that no value is present for ShareOfTotal, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


