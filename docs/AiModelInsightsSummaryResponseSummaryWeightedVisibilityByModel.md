# AiModelInsightsSummaryResponseSummaryWeightedVisibilityByModel

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**TotalWeightedVisibilityScore** | Pointer to **float32** | The brand&#39;s AI Visibility Score across the enabled models, its points there divided by the days with answers in any of them (the Overview&#39;s number for the same filters; a model that answered while disabled keeps its row but stays out of it); 0 when it has none | [optional] 
**Models** | Pointer to [**[]AiModelWeightedVisibilityRow**](AiModelWeightedVisibilityRow.md) |  | [optional] 

## Methods

### NewAiModelInsightsSummaryResponseSummaryWeightedVisibilityByModel

`func NewAiModelInsightsSummaryResponseSummaryWeightedVisibilityByModel() *AiModelInsightsSummaryResponseSummaryWeightedVisibilityByModel`

NewAiModelInsightsSummaryResponseSummaryWeightedVisibilityByModel instantiates a new AiModelInsightsSummaryResponseSummaryWeightedVisibilityByModel object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAiModelInsightsSummaryResponseSummaryWeightedVisibilityByModelWithDefaults

`func NewAiModelInsightsSummaryResponseSummaryWeightedVisibilityByModelWithDefaults() *AiModelInsightsSummaryResponseSummaryWeightedVisibilityByModel`

NewAiModelInsightsSummaryResponseSummaryWeightedVisibilityByModelWithDefaults instantiates a new AiModelInsightsSummaryResponseSummaryWeightedVisibilityByModel object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTotalWeightedVisibilityScore

`func (o *AiModelInsightsSummaryResponseSummaryWeightedVisibilityByModel) GetTotalWeightedVisibilityScore() float32`

GetTotalWeightedVisibilityScore returns the TotalWeightedVisibilityScore field if non-nil, zero value otherwise.

### GetTotalWeightedVisibilityScoreOk

`func (o *AiModelInsightsSummaryResponseSummaryWeightedVisibilityByModel) GetTotalWeightedVisibilityScoreOk() (*float32, bool)`

GetTotalWeightedVisibilityScoreOk returns a tuple with the TotalWeightedVisibilityScore field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalWeightedVisibilityScore

`func (o *AiModelInsightsSummaryResponseSummaryWeightedVisibilityByModel) SetTotalWeightedVisibilityScore(v float32)`

SetTotalWeightedVisibilityScore sets TotalWeightedVisibilityScore field to given value.

### HasTotalWeightedVisibilityScore

`func (o *AiModelInsightsSummaryResponseSummaryWeightedVisibilityByModel) HasTotalWeightedVisibilityScore() bool`

HasTotalWeightedVisibilityScore returns a boolean if a field has been set.

### GetModels

`func (o *AiModelInsightsSummaryResponseSummaryWeightedVisibilityByModel) GetModels() []AiModelWeightedVisibilityRow`

GetModels returns the Models field if non-nil, zero value otherwise.

### GetModelsOk

`func (o *AiModelInsightsSummaryResponseSummaryWeightedVisibilityByModel) GetModelsOk() (*[]AiModelWeightedVisibilityRow, bool)`

GetModelsOk returns a tuple with the Models field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModels

`func (o *AiModelInsightsSummaryResponseSummaryWeightedVisibilityByModel) SetModels(v []AiModelWeightedVisibilityRow)`

SetModels sets Models field to given value.

### HasModels

`func (o *AiModelInsightsSummaryResponseSummaryWeightedVisibilityByModel) HasModels() bool`

HasModels returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


