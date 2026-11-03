# AiModelInsightsSummaryResponseSummaryMentionsByModel

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**TotalMentions** | Pointer to **int32** | Brand mentions across the models | [optional] 
**Models** | Pointer to [**[]AiModelMentionsRow**](AiModelMentionsRow.md) |  | [optional] 

## Methods

### NewAiModelInsightsSummaryResponseSummaryMentionsByModel

`func NewAiModelInsightsSummaryResponseSummaryMentionsByModel() *AiModelInsightsSummaryResponseSummaryMentionsByModel`

NewAiModelInsightsSummaryResponseSummaryMentionsByModel instantiates a new AiModelInsightsSummaryResponseSummaryMentionsByModel object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAiModelInsightsSummaryResponseSummaryMentionsByModelWithDefaults

`func NewAiModelInsightsSummaryResponseSummaryMentionsByModelWithDefaults() *AiModelInsightsSummaryResponseSummaryMentionsByModel`

NewAiModelInsightsSummaryResponseSummaryMentionsByModelWithDefaults instantiates a new AiModelInsightsSummaryResponseSummaryMentionsByModel object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTotalMentions

`func (o *AiModelInsightsSummaryResponseSummaryMentionsByModel) GetTotalMentions() int32`

GetTotalMentions returns the TotalMentions field if non-nil, zero value otherwise.

### GetTotalMentionsOk

`func (o *AiModelInsightsSummaryResponseSummaryMentionsByModel) GetTotalMentionsOk() (*int32, bool)`

GetTotalMentionsOk returns a tuple with the TotalMentions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalMentions

`func (o *AiModelInsightsSummaryResponseSummaryMentionsByModel) SetTotalMentions(v int32)`

SetTotalMentions sets TotalMentions field to given value.

### HasTotalMentions

`func (o *AiModelInsightsSummaryResponseSummaryMentionsByModel) HasTotalMentions() bool`

HasTotalMentions returns a boolean if a field has been set.

### GetModels

`func (o *AiModelInsightsSummaryResponseSummaryMentionsByModel) GetModels() []AiModelMentionsRow`

GetModels returns the Models field if non-nil, zero value otherwise.

### GetModelsOk

`func (o *AiModelInsightsSummaryResponseSummaryMentionsByModel) GetModelsOk() (*[]AiModelMentionsRow, bool)`

GetModelsOk returns a tuple with the Models field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModels

`func (o *AiModelInsightsSummaryResponseSummaryMentionsByModel) SetModels(v []AiModelMentionsRow)`

SetModels sets Models field to given value.

### HasModels

`func (o *AiModelInsightsSummaryResponseSummaryMentionsByModel) HasModels() bool`

HasModels returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


