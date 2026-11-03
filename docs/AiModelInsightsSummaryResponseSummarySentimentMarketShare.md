# AiModelInsightsSummaryResponseSummarySentimentMarketShare

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Actors** | Pointer to [**[]AiModelSentimentMatrixActor**](AiModelSentimentMatrixActor.md) | The project and each competitor with a sentiment verdict in the window (only the competitors given in competitors, when it is given), by total_sentiments descending | [optional] 

## Methods

### NewAiModelInsightsSummaryResponseSummarySentimentMarketShare

`func NewAiModelInsightsSummaryResponseSummarySentimentMarketShare() *AiModelInsightsSummaryResponseSummarySentimentMarketShare`

NewAiModelInsightsSummaryResponseSummarySentimentMarketShare instantiates a new AiModelInsightsSummaryResponseSummarySentimentMarketShare object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAiModelInsightsSummaryResponseSummarySentimentMarketShareWithDefaults

`func NewAiModelInsightsSummaryResponseSummarySentimentMarketShareWithDefaults() *AiModelInsightsSummaryResponseSummarySentimentMarketShare`

NewAiModelInsightsSummaryResponseSummarySentimentMarketShareWithDefaults instantiates a new AiModelInsightsSummaryResponseSummarySentimentMarketShare object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetActors

`func (o *AiModelInsightsSummaryResponseSummarySentimentMarketShare) GetActors() []AiModelSentimentMatrixActor`

GetActors returns the Actors field if non-nil, zero value otherwise.

### GetActorsOk

`func (o *AiModelInsightsSummaryResponseSummarySentimentMarketShare) GetActorsOk() (*[]AiModelSentimentMatrixActor, bool)`

GetActorsOk returns a tuple with the Actors field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActors

`func (o *AiModelInsightsSummaryResponseSummarySentimentMarketShare) SetActors(v []AiModelSentimentMatrixActor)`

SetActors sets Actors field to given value.

### HasActors

`func (o *AiModelInsightsSummaryResponseSummarySentimentMarketShare) HasActors() bool`

HasActors returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


