# AiModelInsightsSummaryResponseSummaryCitationsByModel

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**TotalCitations** | Pointer to **int32** | Citations of the brand&#39;s URLs across the models | [optional] 
**Models** | Pointer to [**[]AiModelCitationsRow**](AiModelCitationsRow.md) |  | [optional] 

## Methods

### NewAiModelInsightsSummaryResponseSummaryCitationsByModel

`func NewAiModelInsightsSummaryResponseSummaryCitationsByModel() *AiModelInsightsSummaryResponseSummaryCitationsByModel`

NewAiModelInsightsSummaryResponseSummaryCitationsByModel instantiates a new AiModelInsightsSummaryResponseSummaryCitationsByModel object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAiModelInsightsSummaryResponseSummaryCitationsByModelWithDefaults

`func NewAiModelInsightsSummaryResponseSummaryCitationsByModelWithDefaults() *AiModelInsightsSummaryResponseSummaryCitationsByModel`

NewAiModelInsightsSummaryResponseSummaryCitationsByModelWithDefaults instantiates a new AiModelInsightsSummaryResponseSummaryCitationsByModel object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTotalCitations

`func (o *AiModelInsightsSummaryResponseSummaryCitationsByModel) GetTotalCitations() int32`

GetTotalCitations returns the TotalCitations field if non-nil, zero value otherwise.

### GetTotalCitationsOk

`func (o *AiModelInsightsSummaryResponseSummaryCitationsByModel) GetTotalCitationsOk() (*int32, bool)`

GetTotalCitationsOk returns a tuple with the TotalCitations field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalCitations

`func (o *AiModelInsightsSummaryResponseSummaryCitationsByModel) SetTotalCitations(v int32)`

SetTotalCitations sets TotalCitations field to given value.

### HasTotalCitations

`func (o *AiModelInsightsSummaryResponseSummaryCitationsByModel) HasTotalCitations() bool`

HasTotalCitations returns a boolean if a field has been set.

### GetModels

`func (o *AiModelInsightsSummaryResponseSummaryCitationsByModel) GetModels() []AiModelCitationsRow`

GetModels returns the Models field if non-nil, zero value otherwise.

### GetModelsOk

`func (o *AiModelInsightsSummaryResponseSummaryCitationsByModel) GetModelsOk() (*[]AiModelCitationsRow, bool)`

GetModelsOk returns a tuple with the Models field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModels

`func (o *AiModelInsightsSummaryResponseSummaryCitationsByModel) SetModels(v []AiModelCitationsRow)`

SetModels sets Models field to given value.

### HasModels

`func (o *AiModelInsightsSummaryResponseSummaryCitationsByModel) HasModels() bool`

HasModels returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


