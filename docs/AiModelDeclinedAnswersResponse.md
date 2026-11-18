# AiModelDeclinedAnswersResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ProjectId** | **int32** |  | 
**From** | **time.Time** | Start of the tracking period holding the first day asked for | 
**To** | **time.Time** |  | 
**Model** | **string** | The model the counts are for | 
**Cadence** | **string** | The account&#39;s current tracking cadence: daily, weekly or monthly. Chart periods before a switch from weekly to daily stay weekly. | 
**Filters** | Pointer to [**AiModelDeclinedAnswersResponseFilters**](AiModelDeclinedAnswersResponseFilters.md) |  | [optional] 
**Summary** | [**AiModelDeclinedAnswersResponseSummary**](AiModelDeclinedAnswersResponseSummary.md) |  | 
**Chart** | [**[]AiModelDeclinedAnswersResponseChartInner**](AiModelDeclinedAnswersResponseChartInner.md) | One point per tracking period holding an answer, oldest first. A period without answers has no point; a period with answers and no declines is a real 0. | 
**ByPrompt** | [**AiModelDeclinedAnswersResponseByPrompt**](AiModelDeclinedAnswersResponseByPrompt.md) |  | 
**RequestId** | Pointer to **string** |  | [optional] 

## Methods

### NewAiModelDeclinedAnswersResponse

`func NewAiModelDeclinedAnswersResponse(projectId int32, from time.Time, to time.Time, model string, cadence string, summary AiModelDeclinedAnswersResponseSummary, chart []AiModelDeclinedAnswersResponseChartInner, byPrompt AiModelDeclinedAnswersResponseByPrompt, ) *AiModelDeclinedAnswersResponse`

NewAiModelDeclinedAnswersResponse instantiates a new AiModelDeclinedAnswersResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAiModelDeclinedAnswersResponseWithDefaults

`func NewAiModelDeclinedAnswersResponseWithDefaults() *AiModelDeclinedAnswersResponse`

NewAiModelDeclinedAnswersResponseWithDefaults instantiates a new AiModelDeclinedAnswersResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProjectId

`func (o *AiModelDeclinedAnswersResponse) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *AiModelDeclinedAnswersResponse) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *AiModelDeclinedAnswersResponse) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.


### GetFrom

`func (o *AiModelDeclinedAnswersResponse) GetFrom() time.Time`

GetFrom returns the From field if non-nil, zero value otherwise.

### GetFromOk

`func (o *AiModelDeclinedAnswersResponse) GetFromOk() (*time.Time, bool)`

GetFromOk returns a tuple with the From field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFrom

`func (o *AiModelDeclinedAnswersResponse) SetFrom(v time.Time)`

SetFrom sets From field to given value.


### GetTo

`func (o *AiModelDeclinedAnswersResponse) GetTo() time.Time`

GetTo returns the To field if non-nil, zero value otherwise.

### GetToOk

`func (o *AiModelDeclinedAnswersResponse) GetToOk() (*time.Time, bool)`

GetToOk returns a tuple with the To field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTo

`func (o *AiModelDeclinedAnswersResponse) SetTo(v time.Time)`

SetTo sets To field to given value.


### GetModel

`func (o *AiModelDeclinedAnswersResponse) GetModel() string`

GetModel returns the Model field if non-nil, zero value otherwise.

### GetModelOk

`func (o *AiModelDeclinedAnswersResponse) GetModelOk() (*string, bool)`

GetModelOk returns a tuple with the Model field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModel

`func (o *AiModelDeclinedAnswersResponse) SetModel(v string)`

SetModel sets Model field to given value.


### GetCadence

`func (o *AiModelDeclinedAnswersResponse) GetCadence() string`

GetCadence returns the Cadence field if non-nil, zero value otherwise.

### GetCadenceOk

`func (o *AiModelDeclinedAnswersResponse) GetCadenceOk() (*string, bool)`

GetCadenceOk returns a tuple with the Cadence field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCadence

`func (o *AiModelDeclinedAnswersResponse) SetCadence(v string)`

SetCadence sets Cadence field to given value.


### GetFilters

`func (o *AiModelDeclinedAnswersResponse) GetFilters() AiModelDeclinedAnswersResponseFilters`

GetFilters returns the Filters field if non-nil, zero value otherwise.

### GetFiltersOk

`func (o *AiModelDeclinedAnswersResponse) GetFiltersOk() (*AiModelDeclinedAnswersResponseFilters, bool)`

GetFiltersOk returns a tuple with the Filters field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFilters

`func (o *AiModelDeclinedAnswersResponse) SetFilters(v AiModelDeclinedAnswersResponseFilters)`

SetFilters sets Filters field to given value.

### HasFilters

`func (o *AiModelDeclinedAnswersResponse) HasFilters() bool`

HasFilters returns a boolean if a field has been set.

### GetSummary

`func (o *AiModelDeclinedAnswersResponse) GetSummary() AiModelDeclinedAnswersResponseSummary`

GetSummary returns the Summary field if non-nil, zero value otherwise.

### GetSummaryOk

`func (o *AiModelDeclinedAnswersResponse) GetSummaryOk() (*AiModelDeclinedAnswersResponseSummary, bool)`

GetSummaryOk returns a tuple with the Summary field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSummary

`func (o *AiModelDeclinedAnswersResponse) SetSummary(v AiModelDeclinedAnswersResponseSummary)`

SetSummary sets Summary field to given value.


### GetChart

`func (o *AiModelDeclinedAnswersResponse) GetChart() []AiModelDeclinedAnswersResponseChartInner`

GetChart returns the Chart field if non-nil, zero value otherwise.

### GetChartOk

`func (o *AiModelDeclinedAnswersResponse) GetChartOk() (*[]AiModelDeclinedAnswersResponseChartInner, bool)`

GetChartOk returns a tuple with the Chart field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChart

`func (o *AiModelDeclinedAnswersResponse) SetChart(v []AiModelDeclinedAnswersResponseChartInner)`

SetChart sets Chart field to given value.


### GetByPrompt

`func (o *AiModelDeclinedAnswersResponse) GetByPrompt() AiModelDeclinedAnswersResponseByPrompt`

GetByPrompt returns the ByPrompt field if non-nil, zero value otherwise.

### GetByPromptOk

`func (o *AiModelDeclinedAnswersResponse) GetByPromptOk() (*AiModelDeclinedAnswersResponseByPrompt, bool)`

GetByPromptOk returns a tuple with the ByPrompt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetByPrompt

`func (o *AiModelDeclinedAnswersResponse) SetByPrompt(v AiModelDeclinedAnswersResponseByPrompt)`

SetByPrompt sets ByPrompt field to given value.


### GetRequestId

`func (o *AiModelDeclinedAnswersResponse) GetRequestId() string`

GetRequestId returns the RequestId field if non-nil, zero value otherwise.

### GetRequestIdOk

`func (o *AiModelDeclinedAnswersResponse) GetRequestIdOk() (*string, bool)`

GetRequestIdOk returns a tuple with the RequestId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestId

`func (o *AiModelDeclinedAnswersResponse) SetRequestId(v string)`

SetRequestId sets RequestId field to given value.

### HasRequestId

`func (o *AiModelDeclinedAnswersResponse) HasRequestId() bool`

HasRequestId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


