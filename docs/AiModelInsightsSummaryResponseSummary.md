# AiModelInsightsSummaryResponseSummary

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**MentionsByModel** | Pointer to [**AiModelInsightsSummaryResponseSummaryMentionsByModel**](AiModelInsightsSummaryResponseSummaryMentionsByModel.md) |  | [optional] 
**CitationsByModel** | Pointer to [**AiModelInsightsSummaryResponseSummaryCitationsByModel**](AiModelInsightsSummaryResponseSummaryCitationsByModel.md) |  | [optional] 
**BrandNetSentimentByModel** | Pointer to [**AiModelInsightsSummaryResponseSummaryBrandNetSentimentByModel**](AiModelInsightsSummaryResponseSummaryBrandNetSentimentByModel.md) |  | [optional] 
**WeightedVisibilityByModel** | Pointer to [**AiModelInsightsSummaryResponseSummaryWeightedVisibilityByModel**](AiModelInsightsSummaryResponseSummaryWeightedVisibilityByModel.md) |  | [optional] 
**MentionsMarketShare** | Pointer to [**AiModelRateMatrix**](AiModelRateMatrix.md) |  | [optional] 
**CitationsMarketShare** | Pointer to [**AiModelRateMatrix**](AiModelRateMatrix.md) |  | [optional] 
**SentimentMarketShare** | Pointer to [**AiModelInsightsSummaryResponseSummarySentimentMarketShare**](AiModelInsightsSummaryResponseSummarySentimentMarketShare.md) |  | [optional] 
**WeightedVisibilityMarketShare** | Pointer to [**AiModelInsightsSummaryResponseSummaryWeightedVisibilityMarketShare**](AiModelInsightsSummaryResponseSummaryWeightedVisibilityMarketShare.md) |  | [optional] 

## Methods

### NewAiModelInsightsSummaryResponseSummary

`func NewAiModelInsightsSummaryResponseSummary() *AiModelInsightsSummaryResponseSummary`

NewAiModelInsightsSummaryResponseSummary instantiates a new AiModelInsightsSummaryResponseSummary object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAiModelInsightsSummaryResponseSummaryWithDefaults

`func NewAiModelInsightsSummaryResponseSummaryWithDefaults() *AiModelInsightsSummaryResponseSummary`

NewAiModelInsightsSummaryResponseSummaryWithDefaults instantiates a new AiModelInsightsSummaryResponseSummary object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMentionsByModel

`func (o *AiModelInsightsSummaryResponseSummary) GetMentionsByModel() AiModelInsightsSummaryResponseSummaryMentionsByModel`

GetMentionsByModel returns the MentionsByModel field if non-nil, zero value otherwise.

### GetMentionsByModelOk

`func (o *AiModelInsightsSummaryResponseSummary) GetMentionsByModelOk() (*AiModelInsightsSummaryResponseSummaryMentionsByModel, bool)`

GetMentionsByModelOk returns a tuple with the MentionsByModel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMentionsByModel

`func (o *AiModelInsightsSummaryResponseSummary) SetMentionsByModel(v AiModelInsightsSummaryResponseSummaryMentionsByModel)`

SetMentionsByModel sets MentionsByModel field to given value.

### HasMentionsByModel

`func (o *AiModelInsightsSummaryResponseSummary) HasMentionsByModel() bool`

HasMentionsByModel returns a boolean if a field has been set.

### GetCitationsByModel

`func (o *AiModelInsightsSummaryResponseSummary) GetCitationsByModel() AiModelInsightsSummaryResponseSummaryCitationsByModel`

GetCitationsByModel returns the CitationsByModel field if non-nil, zero value otherwise.

### GetCitationsByModelOk

`func (o *AiModelInsightsSummaryResponseSummary) GetCitationsByModelOk() (*AiModelInsightsSummaryResponseSummaryCitationsByModel, bool)`

GetCitationsByModelOk returns a tuple with the CitationsByModel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCitationsByModel

`func (o *AiModelInsightsSummaryResponseSummary) SetCitationsByModel(v AiModelInsightsSummaryResponseSummaryCitationsByModel)`

SetCitationsByModel sets CitationsByModel field to given value.

### HasCitationsByModel

`func (o *AiModelInsightsSummaryResponseSummary) HasCitationsByModel() bool`

HasCitationsByModel returns a boolean if a field has been set.

### GetBrandNetSentimentByModel

`func (o *AiModelInsightsSummaryResponseSummary) GetBrandNetSentimentByModel() AiModelInsightsSummaryResponseSummaryBrandNetSentimentByModel`

GetBrandNetSentimentByModel returns the BrandNetSentimentByModel field if non-nil, zero value otherwise.

### GetBrandNetSentimentByModelOk

`func (o *AiModelInsightsSummaryResponseSummary) GetBrandNetSentimentByModelOk() (*AiModelInsightsSummaryResponseSummaryBrandNetSentimentByModel, bool)`

GetBrandNetSentimentByModelOk returns a tuple with the BrandNetSentimentByModel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBrandNetSentimentByModel

`func (o *AiModelInsightsSummaryResponseSummary) SetBrandNetSentimentByModel(v AiModelInsightsSummaryResponseSummaryBrandNetSentimentByModel)`

SetBrandNetSentimentByModel sets BrandNetSentimentByModel field to given value.

### HasBrandNetSentimentByModel

`func (o *AiModelInsightsSummaryResponseSummary) HasBrandNetSentimentByModel() bool`

HasBrandNetSentimentByModel returns a boolean if a field has been set.

### GetWeightedVisibilityByModel

`func (o *AiModelInsightsSummaryResponseSummary) GetWeightedVisibilityByModel() AiModelInsightsSummaryResponseSummaryWeightedVisibilityByModel`

GetWeightedVisibilityByModel returns the WeightedVisibilityByModel field if non-nil, zero value otherwise.

### GetWeightedVisibilityByModelOk

`func (o *AiModelInsightsSummaryResponseSummary) GetWeightedVisibilityByModelOk() (*AiModelInsightsSummaryResponseSummaryWeightedVisibilityByModel, bool)`

GetWeightedVisibilityByModelOk returns a tuple with the WeightedVisibilityByModel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWeightedVisibilityByModel

`func (o *AiModelInsightsSummaryResponseSummary) SetWeightedVisibilityByModel(v AiModelInsightsSummaryResponseSummaryWeightedVisibilityByModel)`

SetWeightedVisibilityByModel sets WeightedVisibilityByModel field to given value.

### HasWeightedVisibilityByModel

`func (o *AiModelInsightsSummaryResponseSummary) HasWeightedVisibilityByModel() bool`

HasWeightedVisibilityByModel returns a boolean if a field has been set.

### GetMentionsMarketShare

`func (o *AiModelInsightsSummaryResponseSummary) GetMentionsMarketShare() AiModelRateMatrix`

GetMentionsMarketShare returns the MentionsMarketShare field if non-nil, zero value otherwise.

### GetMentionsMarketShareOk

`func (o *AiModelInsightsSummaryResponseSummary) GetMentionsMarketShareOk() (*AiModelRateMatrix, bool)`

GetMentionsMarketShareOk returns a tuple with the MentionsMarketShare field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMentionsMarketShare

`func (o *AiModelInsightsSummaryResponseSummary) SetMentionsMarketShare(v AiModelRateMatrix)`

SetMentionsMarketShare sets MentionsMarketShare field to given value.

### HasMentionsMarketShare

`func (o *AiModelInsightsSummaryResponseSummary) HasMentionsMarketShare() bool`

HasMentionsMarketShare returns a boolean if a field has been set.

### GetCitationsMarketShare

`func (o *AiModelInsightsSummaryResponseSummary) GetCitationsMarketShare() AiModelRateMatrix`

GetCitationsMarketShare returns the CitationsMarketShare field if non-nil, zero value otherwise.

### GetCitationsMarketShareOk

`func (o *AiModelInsightsSummaryResponseSummary) GetCitationsMarketShareOk() (*AiModelRateMatrix, bool)`

GetCitationsMarketShareOk returns a tuple with the CitationsMarketShare field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCitationsMarketShare

`func (o *AiModelInsightsSummaryResponseSummary) SetCitationsMarketShare(v AiModelRateMatrix)`

SetCitationsMarketShare sets CitationsMarketShare field to given value.

### HasCitationsMarketShare

`func (o *AiModelInsightsSummaryResponseSummary) HasCitationsMarketShare() bool`

HasCitationsMarketShare returns a boolean if a field has been set.

### GetSentimentMarketShare

`func (o *AiModelInsightsSummaryResponseSummary) GetSentimentMarketShare() AiModelInsightsSummaryResponseSummarySentimentMarketShare`

GetSentimentMarketShare returns the SentimentMarketShare field if non-nil, zero value otherwise.

### GetSentimentMarketShareOk

`func (o *AiModelInsightsSummaryResponseSummary) GetSentimentMarketShareOk() (*AiModelInsightsSummaryResponseSummarySentimentMarketShare, bool)`

GetSentimentMarketShareOk returns a tuple with the SentimentMarketShare field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSentimentMarketShare

`func (o *AiModelInsightsSummaryResponseSummary) SetSentimentMarketShare(v AiModelInsightsSummaryResponseSummarySentimentMarketShare)`

SetSentimentMarketShare sets SentimentMarketShare field to given value.

### HasSentimentMarketShare

`func (o *AiModelInsightsSummaryResponseSummary) HasSentimentMarketShare() bool`

HasSentimentMarketShare returns a boolean if a field has been set.

### GetWeightedVisibilityMarketShare

`func (o *AiModelInsightsSummaryResponseSummary) GetWeightedVisibilityMarketShare() AiModelInsightsSummaryResponseSummaryWeightedVisibilityMarketShare`

GetWeightedVisibilityMarketShare returns the WeightedVisibilityMarketShare field if non-nil, zero value otherwise.

### GetWeightedVisibilityMarketShareOk

`func (o *AiModelInsightsSummaryResponseSummary) GetWeightedVisibilityMarketShareOk() (*AiModelInsightsSummaryResponseSummaryWeightedVisibilityMarketShare, bool)`

GetWeightedVisibilityMarketShareOk returns a tuple with the WeightedVisibilityMarketShare field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWeightedVisibilityMarketShare

`func (o *AiModelInsightsSummaryResponseSummary) SetWeightedVisibilityMarketShare(v AiModelInsightsSummaryResponseSummaryWeightedVisibilityMarketShare)`

SetWeightedVisibilityMarketShare sets WeightedVisibilityMarketShare field to given value.

### HasWeightedVisibilityMarketShare

`func (o *AiModelInsightsSummaryResponseSummary) HasWeightedVisibilityMarketShare() bool`

HasWeightedVisibilityMarketShare returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


