# AiModelInsightsSummaryResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ProjectId** | Pointer to **int32** |  | [optional] 
**From** | Pointer to **time.Time** |  | [optional] 
**To** | Pointer to **time.Time** |  | [optional] 
**Filters** | Pointer to [**AiModelInsightsFiltersEcho**](AiModelInsightsFiltersEcho.md) |  | [optional] 
**Models** | Pointer to [**[]AiModelInsightsModel**](AiModelInsightsModel.md) | The AI models the account has enabled or that answered in the window, in the in-app column order | [optional] 
**Summary** | Pointer to [**AiModelInsightsSummaryResponseSummary**](AiModelInsightsSummaryResponseSummary.md) |  | [optional] 
**RequestId** | Pointer to **string** |  | [optional] 

## Methods

### NewAiModelInsightsSummaryResponse

`func NewAiModelInsightsSummaryResponse() *AiModelInsightsSummaryResponse`

NewAiModelInsightsSummaryResponse instantiates a new AiModelInsightsSummaryResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAiModelInsightsSummaryResponseWithDefaults

`func NewAiModelInsightsSummaryResponseWithDefaults() *AiModelInsightsSummaryResponse`

NewAiModelInsightsSummaryResponseWithDefaults instantiates a new AiModelInsightsSummaryResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProjectId

`func (o *AiModelInsightsSummaryResponse) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *AiModelInsightsSummaryResponse) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *AiModelInsightsSummaryResponse) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.

### HasProjectId

`func (o *AiModelInsightsSummaryResponse) HasProjectId() bool`

HasProjectId returns a boolean if a field has been set.

### GetFrom

`func (o *AiModelInsightsSummaryResponse) GetFrom() time.Time`

GetFrom returns the From field if non-nil, zero value otherwise.

### GetFromOk

`func (o *AiModelInsightsSummaryResponse) GetFromOk() (*time.Time, bool)`

GetFromOk returns a tuple with the From field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFrom

`func (o *AiModelInsightsSummaryResponse) SetFrom(v time.Time)`

SetFrom sets From field to given value.

### HasFrom

`func (o *AiModelInsightsSummaryResponse) HasFrom() bool`

HasFrom returns a boolean if a field has been set.

### GetTo

`func (o *AiModelInsightsSummaryResponse) GetTo() time.Time`

GetTo returns the To field if non-nil, zero value otherwise.

### GetToOk

`func (o *AiModelInsightsSummaryResponse) GetToOk() (*time.Time, bool)`

GetToOk returns a tuple with the To field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTo

`func (o *AiModelInsightsSummaryResponse) SetTo(v time.Time)`

SetTo sets To field to given value.

### HasTo

`func (o *AiModelInsightsSummaryResponse) HasTo() bool`

HasTo returns a boolean if a field has been set.

### GetFilters

`func (o *AiModelInsightsSummaryResponse) GetFilters() AiModelInsightsFiltersEcho`

GetFilters returns the Filters field if non-nil, zero value otherwise.

### GetFiltersOk

`func (o *AiModelInsightsSummaryResponse) GetFiltersOk() (*AiModelInsightsFiltersEcho, bool)`

GetFiltersOk returns a tuple with the Filters field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFilters

`func (o *AiModelInsightsSummaryResponse) SetFilters(v AiModelInsightsFiltersEcho)`

SetFilters sets Filters field to given value.

### HasFilters

`func (o *AiModelInsightsSummaryResponse) HasFilters() bool`

HasFilters returns a boolean if a field has been set.

### GetModels

`func (o *AiModelInsightsSummaryResponse) GetModels() []AiModelInsightsModel`

GetModels returns the Models field if non-nil, zero value otherwise.

### GetModelsOk

`func (o *AiModelInsightsSummaryResponse) GetModelsOk() (*[]AiModelInsightsModel, bool)`

GetModelsOk returns a tuple with the Models field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModels

`func (o *AiModelInsightsSummaryResponse) SetModels(v []AiModelInsightsModel)`

SetModels sets Models field to given value.

### HasModels

`func (o *AiModelInsightsSummaryResponse) HasModels() bool`

HasModels returns a boolean if a field has been set.

### GetSummary

`func (o *AiModelInsightsSummaryResponse) GetSummary() AiModelInsightsSummaryResponseSummary`

GetSummary returns the Summary field if non-nil, zero value otherwise.

### GetSummaryOk

`func (o *AiModelInsightsSummaryResponse) GetSummaryOk() (*AiModelInsightsSummaryResponseSummary, bool)`

GetSummaryOk returns a tuple with the Summary field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSummary

`func (o *AiModelInsightsSummaryResponse) SetSummary(v AiModelInsightsSummaryResponseSummary)`

SetSummary sets Summary field to given value.

### HasSummary

`func (o *AiModelInsightsSummaryResponse) HasSummary() bool`

HasSummary returns a boolean if a field has been set.

### GetRequestId

`func (o *AiModelInsightsSummaryResponse) GetRequestId() string`

GetRequestId returns the RequestId field if non-nil, zero value otherwise.

### GetRequestIdOk

`func (o *AiModelInsightsSummaryResponse) GetRequestIdOk() (*string, bool)`

GetRequestIdOk returns a tuple with the RequestId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestId

`func (o *AiModelInsightsSummaryResponse) SetRequestId(v string)`

SetRequestId sets RequestId field to given value.

### HasRequestId

`func (o *AiModelInsightsSummaryResponse) HasRequestId() bool`

HasRequestId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


