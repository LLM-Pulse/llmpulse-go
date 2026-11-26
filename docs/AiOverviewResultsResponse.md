# AiOverviewResultsResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ProjectId** | **int32** |  | 
**From** | **time.Time** |  | 
**To** | **time.Time** |  | 
**Filters** | [**AiModelInsightsReportFiltersEcho**](AiModelInsightsReportFiltersEcho.md) |  | 
**Granularity** | **string** |  | 
**Summary** | [**AiOverviewResultCounts**](AiOverviewResultCounts.md) |  | 
**Chart** | [**[]AiOverviewResultsResponseChartInner**](AiOverviewResultsResponseChartInner.md) | One point per period of the window, oldest first, 0 included | 
**ByPrompt** | [**AiOverviewResultsResponseByPrompt**](AiOverviewResultsResponseByPrompt.md) |  | 
**RequestId** | **string** |  | 

## Methods

### NewAiOverviewResultsResponse

`func NewAiOverviewResultsResponse(projectId int32, from time.Time, to time.Time, filters AiModelInsightsReportFiltersEcho, granularity string, summary AiOverviewResultCounts, chart []AiOverviewResultsResponseChartInner, byPrompt AiOverviewResultsResponseByPrompt, requestId string, ) *AiOverviewResultsResponse`

NewAiOverviewResultsResponse instantiates a new AiOverviewResultsResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAiOverviewResultsResponseWithDefaults

`func NewAiOverviewResultsResponseWithDefaults() *AiOverviewResultsResponse`

NewAiOverviewResultsResponseWithDefaults instantiates a new AiOverviewResultsResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProjectId

`func (o *AiOverviewResultsResponse) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *AiOverviewResultsResponse) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *AiOverviewResultsResponse) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.


### GetFrom

`func (o *AiOverviewResultsResponse) GetFrom() time.Time`

GetFrom returns the From field if non-nil, zero value otherwise.

### GetFromOk

`func (o *AiOverviewResultsResponse) GetFromOk() (*time.Time, bool)`

GetFromOk returns a tuple with the From field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFrom

`func (o *AiOverviewResultsResponse) SetFrom(v time.Time)`

SetFrom sets From field to given value.


### GetTo

`func (o *AiOverviewResultsResponse) GetTo() time.Time`

GetTo returns the To field if non-nil, zero value otherwise.

### GetToOk

`func (o *AiOverviewResultsResponse) GetToOk() (*time.Time, bool)`

GetToOk returns a tuple with the To field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTo

`func (o *AiOverviewResultsResponse) SetTo(v time.Time)`

SetTo sets To field to given value.


### GetFilters

`func (o *AiOverviewResultsResponse) GetFilters() AiModelInsightsReportFiltersEcho`

GetFilters returns the Filters field if non-nil, zero value otherwise.

### GetFiltersOk

`func (o *AiOverviewResultsResponse) GetFiltersOk() (*AiModelInsightsReportFiltersEcho, bool)`

GetFiltersOk returns a tuple with the Filters field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFilters

`func (o *AiOverviewResultsResponse) SetFilters(v AiModelInsightsReportFiltersEcho)`

SetFilters sets Filters field to given value.


### GetGranularity

`func (o *AiOverviewResultsResponse) GetGranularity() string`

GetGranularity returns the Granularity field if non-nil, zero value otherwise.

### GetGranularityOk

`func (o *AiOverviewResultsResponse) GetGranularityOk() (*string, bool)`

GetGranularityOk returns a tuple with the Granularity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGranularity

`func (o *AiOverviewResultsResponse) SetGranularity(v string)`

SetGranularity sets Granularity field to given value.


### GetSummary

`func (o *AiOverviewResultsResponse) GetSummary() AiOverviewResultCounts`

GetSummary returns the Summary field if non-nil, zero value otherwise.

### GetSummaryOk

`func (o *AiOverviewResultsResponse) GetSummaryOk() (*AiOverviewResultCounts, bool)`

GetSummaryOk returns a tuple with the Summary field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSummary

`func (o *AiOverviewResultsResponse) SetSummary(v AiOverviewResultCounts)`

SetSummary sets Summary field to given value.


### GetChart

`func (o *AiOverviewResultsResponse) GetChart() []AiOverviewResultsResponseChartInner`

GetChart returns the Chart field if non-nil, zero value otherwise.

### GetChartOk

`func (o *AiOverviewResultsResponse) GetChartOk() (*[]AiOverviewResultsResponseChartInner, bool)`

GetChartOk returns a tuple with the Chart field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChart

`func (o *AiOverviewResultsResponse) SetChart(v []AiOverviewResultsResponseChartInner)`

SetChart sets Chart field to given value.


### GetByPrompt

`func (o *AiOverviewResultsResponse) GetByPrompt() AiOverviewResultsResponseByPrompt`

GetByPrompt returns the ByPrompt field if non-nil, zero value otherwise.

### GetByPromptOk

`func (o *AiOverviewResultsResponse) GetByPromptOk() (*AiOverviewResultsResponseByPrompt, bool)`

GetByPromptOk returns a tuple with the ByPrompt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetByPrompt

`func (o *AiOverviewResultsResponse) SetByPrompt(v AiOverviewResultsResponseByPrompt)`

SetByPrompt sets ByPrompt field to given value.


### GetRequestId

`func (o *AiOverviewResultsResponse) GetRequestId() string`

GetRequestId returns the RequestId field if non-nil, zero value otherwise.

### GetRequestIdOk

`func (o *AiOverviewResultsResponse) GetRequestIdOk() (*string, bool)`

GetRequestIdOk returns a tuple with the RequestId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestId

`func (o *AiOverviewResultsResponse) SetRequestId(v string)`

SetRequestId sets RequestId field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


