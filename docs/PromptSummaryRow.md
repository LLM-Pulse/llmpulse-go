# PromptSummaryRow

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**PromptId** | Pointer to **int32** |  | [optional] 
**PromptText** | Pointer to **string** |  | [optional] 
**Model** | Pointer to **string** | Only present when breakdown&#x3D;model | [optional] 
**Responses** | Pointer to **int32** |  | [optional] 
**Mentions** | Pointer to **int32** |  | [optional] 
**Citations** | Pointer to **int32** |  | [optional] 
**Visibility** | Pointer to **float32** |  | [optional] 
**MentionRate** | Pointer to **float32** |  | [optional] 
**CitationRate** | Pointer to **float32** |  | [optional] 
**AvgMentionPosition** | Pointer to **NullableFloat32** |  | [optional] 
**AvgPosition** | Pointer to **NullableFloat32** |  | [optional] 

## Methods

### NewPromptSummaryRow

`func NewPromptSummaryRow() *PromptSummaryRow`

NewPromptSummaryRow instantiates a new PromptSummaryRow object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPromptSummaryRowWithDefaults

`func NewPromptSummaryRowWithDefaults() *PromptSummaryRow`

NewPromptSummaryRowWithDefaults instantiates a new PromptSummaryRow object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPromptId

`func (o *PromptSummaryRow) GetPromptId() int32`

GetPromptId returns the PromptId field if non-nil, zero value otherwise.

### GetPromptIdOk

`func (o *PromptSummaryRow) GetPromptIdOk() (*int32, bool)`

GetPromptIdOk returns a tuple with the PromptId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPromptId

`func (o *PromptSummaryRow) SetPromptId(v int32)`

SetPromptId sets PromptId field to given value.

### HasPromptId

`func (o *PromptSummaryRow) HasPromptId() bool`

HasPromptId returns a boolean if a field has been set.

### GetPromptText

`func (o *PromptSummaryRow) GetPromptText() string`

GetPromptText returns the PromptText field if non-nil, zero value otherwise.

### GetPromptTextOk

`func (o *PromptSummaryRow) GetPromptTextOk() (*string, bool)`

GetPromptTextOk returns a tuple with the PromptText field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPromptText

`func (o *PromptSummaryRow) SetPromptText(v string)`

SetPromptText sets PromptText field to given value.

### HasPromptText

`func (o *PromptSummaryRow) HasPromptText() bool`

HasPromptText returns a boolean if a field has been set.

### GetModel

`func (o *PromptSummaryRow) GetModel() string`

GetModel returns the Model field if non-nil, zero value otherwise.

### GetModelOk

`func (o *PromptSummaryRow) GetModelOk() (*string, bool)`

GetModelOk returns a tuple with the Model field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModel

`func (o *PromptSummaryRow) SetModel(v string)`

SetModel sets Model field to given value.

### HasModel

`func (o *PromptSummaryRow) HasModel() bool`

HasModel returns a boolean if a field has been set.

### GetResponses

`func (o *PromptSummaryRow) GetResponses() int32`

GetResponses returns the Responses field if non-nil, zero value otherwise.

### GetResponsesOk

`func (o *PromptSummaryRow) GetResponsesOk() (*int32, bool)`

GetResponsesOk returns a tuple with the Responses field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResponses

`func (o *PromptSummaryRow) SetResponses(v int32)`

SetResponses sets Responses field to given value.

### HasResponses

`func (o *PromptSummaryRow) HasResponses() bool`

HasResponses returns a boolean if a field has been set.

### GetMentions

`func (o *PromptSummaryRow) GetMentions() int32`

GetMentions returns the Mentions field if non-nil, zero value otherwise.

### GetMentionsOk

`func (o *PromptSummaryRow) GetMentionsOk() (*int32, bool)`

GetMentionsOk returns a tuple with the Mentions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMentions

`func (o *PromptSummaryRow) SetMentions(v int32)`

SetMentions sets Mentions field to given value.

### HasMentions

`func (o *PromptSummaryRow) HasMentions() bool`

HasMentions returns a boolean if a field has been set.

### GetCitations

`func (o *PromptSummaryRow) GetCitations() int32`

GetCitations returns the Citations field if non-nil, zero value otherwise.

### GetCitationsOk

`func (o *PromptSummaryRow) GetCitationsOk() (*int32, bool)`

GetCitationsOk returns a tuple with the Citations field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCitations

`func (o *PromptSummaryRow) SetCitations(v int32)`

SetCitations sets Citations field to given value.

### HasCitations

`func (o *PromptSummaryRow) HasCitations() bool`

HasCitations returns a boolean if a field has been set.

### GetVisibility

`func (o *PromptSummaryRow) GetVisibility() float32`

GetVisibility returns the Visibility field if non-nil, zero value otherwise.

### GetVisibilityOk

`func (o *PromptSummaryRow) GetVisibilityOk() (*float32, bool)`

GetVisibilityOk returns a tuple with the Visibility field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVisibility

`func (o *PromptSummaryRow) SetVisibility(v float32)`

SetVisibility sets Visibility field to given value.

### HasVisibility

`func (o *PromptSummaryRow) HasVisibility() bool`

HasVisibility returns a boolean if a field has been set.

### GetMentionRate

`func (o *PromptSummaryRow) GetMentionRate() float32`

GetMentionRate returns the MentionRate field if non-nil, zero value otherwise.

### GetMentionRateOk

`func (o *PromptSummaryRow) GetMentionRateOk() (*float32, bool)`

GetMentionRateOk returns a tuple with the MentionRate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMentionRate

`func (o *PromptSummaryRow) SetMentionRate(v float32)`

SetMentionRate sets MentionRate field to given value.

### HasMentionRate

`func (o *PromptSummaryRow) HasMentionRate() bool`

HasMentionRate returns a boolean if a field has been set.

### GetCitationRate

`func (o *PromptSummaryRow) GetCitationRate() float32`

GetCitationRate returns the CitationRate field if non-nil, zero value otherwise.

### GetCitationRateOk

`func (o *PromptSummaryRow) GetCitationRateOk() (*float32, bool)`

GetCitationRateOk returns a tuple with the CitationRate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCitationRate

`func (o *PromptSummaryRow) SetCitationRate(v float32)`

SetCitationRate sets CitationRate field to given value.

### HasCitationRate

`func (o *PromptSummaryRow) HasCitationRate() bool`

HasCitationRate returns a boolean if a field has been set.

### GetAvgMentionPosition

`func (o *PromptSummaryRow) GetAvgMentionPosition() float32`

GetAvgMentionPosition returns the AvgMentionPosition field if non-nil, zero value otherwise.

### GetAvgMentionPositionOk

`func (o *PromptSummaryRow) GetAvgMentionPositionOk() (*float32, bool)`

GetAvgMentionPositionOk returns a tuple with the AvgMentionPosition field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAvgMentionPosition

`func (o *PromptSummaryRow) SetAvgMentionPosition(v float32)`

SetAvgMentionPosition sets AvgMentionPosition field to given value.

### HasAvgMentionPosition

`func (o *PromptSummaryRow) HasAvgMentionPosition() bool`

HasAvgMentionPosition returns a boolean if a field has been set.

### SetAvgMentionPositionNil

`func (o *PromptSummaryRow) SetAvgMentionPositionNil(b bool)`

 SetAvgMentionPositionNil sets the value for AvgMentionPosition to be an explicit nil

### UnsetAvgMentionPosition
`func (o *PromptSummaryRow) UnsetAvgMentionPosition()`

UnsetAvgMentionPosition ensures that no value is present for AvgMentionPosition, not even an explicit nil
### GetAvgPosition

`func (o *PromptSummaryRow) GetAvgPosition() float32`

GetAvgPosition returns the AvgPosition field if non-nil, zero value otherwise.

### GetAvgPositionOk

`func (o *PromptSummaryRow) GetAvgPositionOk() (*float32, bool)`

GetAvgPositionOk returns a tuple with the AvgPosition field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAvgPosition

`func (o *PromptSummaryRow) SetAvgPosition(v float32)`

SetAvgPosition sets AvgPosition field to given value.

### HasAvgPosition

`func (o *PromptSummaryRow) HasAvgPosition() bool`

HasAvgPosition returns a boolean if a field has been set.

### SetAvgPositionNil

`func (o *PromptSummaryRow) SetAvgPositionNil(b bool)`

 SetAvgPositionNil sets the value for AvgPosition to be an explicit nil

### UnsetAvgPosition
`func (o *PromptSummaryRow) UnsetAvgPosition()`

UnsetAvgPosition ensures that no value is present for AvgPosition, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


