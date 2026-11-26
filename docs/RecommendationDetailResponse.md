# RecommendationDetailResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **int32** |  | 
**ProjectId** | **int32** |  | 
**RecommendationType** | **string** |  | 
**Status** | **string** |  | 
**ErrorMessage** | **NullableString** | Set only when status is failed | 
**GeneratedAt** | **NullableTime** | Null until the generation completes | 
**CreatedAt** | **time.Time** |  | 
**UpdatedAt** | **time.Time** |  | 
**TotalRecommendations** | **int32** |  | 
**HighPriorityCount** | **int32** |  | 
**Summary** | [**RecommendationDetailResponseSummary**](RecommendationDetailResponseSummary.md) |  | 
**Context** | **map[string]interface{}** | Generation context and run diagnostics as stored; empty until the generation completes. Its keys are not a stable contract | 
**ReportData** | **map[string]interface{}** | The stored run, including the evidence indices (prompts_index, citations_index, own_content_index and others) that the source_refs codes of the items point to. Its keys are not a stable contract | 
**ItemCounts** | [**RecommendationDetailResponseItemCounts**](RecommendationDetailResponseItemCounts.md) |  | 
**Items** | [**[]RecommendationItem**](RecommendationItem.md) |  | 
**RequestId** | **string** |  | 

## Methods

### NewRecommendationDetailResponse

`func NewRecommendationDetailResponse(id int32, projectId int32, recommendationType string, status string, errorMessage NullableString, generatedAt NullableTime, createdAt time.Time, updatedAt time.Time, totalRecommendations int32, highPriorityCount int32, summary RecommendationDetailResponseSummary, context map[string]interface{}, reportData map[string]interface{}, itemCounts RecommendationDetailResponseItemCounts, items []RecommendationItem, requestId string, ) *RecommendationDetailResponse`

NewRecommendationDetailResponse instantiates a new RecommendationDetailResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRecommendationDetailResponseWithDefaults

`func NewRecommendationDetailResponseWithDefaults() *RecommendationDetailResponse`

NewRecommendationDetailResponseWithDefaults instantiates a new RecommendationDetailResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *RecommendationDetailResponse) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *RecommendationDetailResponse) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *RecommendationDetailResponse) SetId(v int32)`

SetId sets Id field to given value.


### GetProjectId

`func (o *RecommendationDetailResponse) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *RecommendationDetailResponse) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *RecommendationDetailResponse) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.


### GetRecommendationType

`func (o *RecommendationDetailResponse) GetRecommendationType() string`

GetRecommendationType returns the RecommendationType field if non-nil, zero value otherwise.

### GetRecommendationTypeOk

`func (o *RecommendationDetailResponse) GetRecommendationTypeOk() (*string, bool)`

GetRecommendationTypeOk returns a tuple with the RecommendationType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRecommendationType

`func (o *RecommendationDetailResponse) SetRecommendationType(v string)`

SetRecommendationType sets RecommendationType field to given value.


### GetStatus

`func (o *RecommendationDetailResponse) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *RecommendationDetailResponse) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *RecommendationDetailResponse) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetErrorMessage

`func (o *RecommendationDetailResponse) GetErrorMessage() string`

GetErrorMessage returns the ErrorMessage field if non-nil, zero value otherwise.

### GetErrorMessageOk

`func (o *RecommendationDetailResponse) GetErrorMessageOk() (*string, bool)`

GetErrorMessageOk returns a tuple with the ErrorMessage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrorMessage

`func (o *RecommendationDetailResponse) SetErrorMessage(v string)`

SetErrorMessage sets ErrorMessage field to given value.


### SetErrorMessageNil

`func (o *RecommendationDetailResponse) SetErrorMessageNil(b bool)`

 SetErrorMessageNil sets the value for ErrorMessage to be an explicit nil

### UnsetErrorMessage
`func (o *RecommendationDetailResponse) UnsetErrorMessage()`

UnsetErrorMessage ensures that no value is present for ErrorMessage, not even an explicit nil
### GetGeneratedAt

`func (o *RecommendationDetailResponse) GetGeneratedAt() time.Time`

GetGeneratedAt returns the GeneratedAt field if non-nil, zero value otherwise.

### GetGeneratedAtOk

`func (o *RecommendationDetailResponse) GetGeneratedAtOk() (*time.Time, bool)`

GetGeneratedAtOk returns a tuple with the GeneratedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGeneratedAt

`func (o *RecommendationDetailResponse) SetGeneratedAt(v time.Time)`

SetGeneratedAt sets GeneratedAt field to given value.


### SetGeneratedAtNil

`func (o *RecommendationDetailResponse) SetGeneratedAtNil(b bool)`

 SetGeneratedAtNil sets the value for GeneratedAt to be an explicit nil

### UnsetGeneratedAt
`func (o *RecommendationDetailResponse) UnsetGeneratedAt()`

UnsetGeneratedAt ensures that no value is present for GeneratedAt, not even an explicit nil
### GetCreatedAt

`func (o *RecommendationDetailResponse) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *RecommendationDetailResponse) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *RecommendationDetailResponse) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetUpdatedAt

`func (o *RecommendationDetailResponse) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *RecommendationDetailResponse) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *RecommendationDetailResponse) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.


### GetTotalRecommendations

`func (o *RecommendationDetailResponse) GetTotalRecommendations() int32`

GetTotalRecommendations returns the TotalRecommendations field if non-nil, zero value otherwise.

### GetTotalRecommendationsOk

`func (o *RecommendationDetailResponse) GetTotalRecommendationsOk() (*int32, bool)`

GetTotalRecommendationsOk returns a tuple with the TotalRecommendations field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalRecommendations

`func (o *RecommendationDetailResponse) SetTotalRecommendations(v int32)`

SetTotalRecommendations sets TotalRecommendations field to given value.


### GetHighPriorityCount

`func (o *RecommendationDetailResponse) GetHighPriorityCount() int32`

GetHighPriorityCount returns the HighPriorityCount field if non-nil, zero value otherwise.

### GetHighPriorityCountOk

`func (o *RecommendationDetailResponse) GetHighPriorityCountOk() (*int32, bool)`

GetHighPriorityCountOk returns a tuple with the HighPriorityCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHighPriorityCount

`func (o *RecommendationDetailResponse) SetHighPriorityCount(v int32)`

SetHighPriorityCount sets HighPriorityCount field to given value.


### GetSummary

`func (o *RecommendationDetailResponse) GetSummary() RecommendationDetailResponseSummary`

GetSummary returns the Summary field if non-nil, zero value otherwise.

### GetSummaryOk

`func (o *RecommendationDetailResponse) GetSummaryOk() (*RecommendationDetailResponseSummary, bool)`

GetSummaryOk returns a tuple with the Summary field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSummary

`func (o *RecommendationDetailResponse) SetSummary(v RecommendationDetailResponseSummary)`

SetSummary sets Summary field to given value.


### GetContext

`func (o *RecommendationDetailResponse) GetContext() map[string]interface{}`

GetContext returns the Context field if non-nil, zero value otherwise.

### GetContextOk

`func (o *RecommendationDetailResponse) GetContextOk() (*map[string]interface{}, bool)`

GetContextOk returns a tuple with the Context field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContext

`func (o *RecommendationDetailResponse) SetContext(v map[string]interface{})`

SetContext sets Context field to given value.


### GetReportData

`func (o *RecommendationDetailResponse) GetReportData() map[string]interface{}`

GetReportData returns the ReportData field if non-nil, zero value otherwise.

### GetReportDataOk

`func (o *RecommendationDetailResponse) GetReportDataOk() (*map[string]interface{}, bool)`

GetReportDataOk returns a tuple with the ReportData field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReportData

`func (o *RecommendationDetailResponse) SetReportData(v map[string]interface{})`

SetReportData sets ReportData field to given value.


### GetItemCounts

`func (o *RecommendationDetailResponse) GetItemCounts() RecommendationDetailResponseItemCounts`

GetItemCounts returns the ItemCounts field if non-nil, zero value otherwise.

### GetItemCountsOk

`func (o *RecommendationDetailResponse) GetItemCountsOk() (*RecommendationDetailResponseItemCounts, bool)`

GetItemCountsOk returns a tuple with the ItemCounts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetItemCounts

`func (o *RecommendationDetailResponse) SetItemCounts(v RecommendationDetailResponseItemCounts)`

SetItemCounts sets ItemCounts field to given value.


### GetItems

`func (o *RecommendationDetailResponse) GetItems() []RecommendationItem`

GetItems returns the Items field if non-nil, zero value otherwise.

### GetItemsOk

`func (o *RecommendationDetailResponse) GetItemsOk() (*[]RecommendationItem, bool)`

GetItemsOk returns a tuple with the Items field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetItems

`func (o *RecommendationDetailResponse) SetItems(v []RecommendationItem)`

SetItems sets Items field to given value.


### GetRequestId

`func (o *RecommendationDetailResponse) GetRequestId() string`

GetRequestId returns the RequestId field if non-nil, zero value otherwise.

### GetRequestIdOk

`func (o *RecommendationDetailResponse) GetRequestIdOk() (*string, bool)`

GetRequestIdOk returns a tuple with the RequestId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestId

`func (o *RecommendationDetailResponse) SetRequestId(v string)`

SetRequestId sets RequestId field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


