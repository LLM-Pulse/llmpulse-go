# RecommendationSummary

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
**Summary** | [**RecommendationSummarySummary**](RecommendationSummarySummary.md) |  | 
**Context** | **map[string]interface{}** | Generation context and run diagnostics as stored; empty until the generation completes. Its keys are not a stable contract | 

## Methods

### NewRecommendationSummary

`func NewRecommendationSummary(id int32, projectId int32, recommendationType string, status string, errorMessage NullableString, generatedAt NullableTime, createdAt time.Time, updatedAt time.Time, totalRecommendations int32, highPriorityCount int32, summary RecommendationSummarySummary, context map[string]interface{}, ) *RecommendationSummary`

NewRecommendationSummary instantiates a new RecommendationSummary object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRecommendationSummaryWithDefaults

`func NewRecommendationSummaryWithDefaults() *RecommendationSummary`

NewRecommendationSummaryWithDefaults instantiates a new RecommendationSummary object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *RecommendationSummary) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *RecommendationSummary) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *RecommendationSummary) SetId(v int32)`

SetId sets Id field to given value.


### GetProjectId

`func (o *RecommendationSummary) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *RecommendationSummary) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *RecommendationSummary) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.


### GetRecommendationType

`func (o *RecommendationSummary) GetRecommendationType() string`

GetRecommendationType returns the RecommendationType field if non-nil, zero value otherwise.

### GetRecommendationTypeOk

`func (o *RecommendationSummary) GetRecommendationTypeOk() (*string, bool)`

GetRecommendationTypeOk returns a tuple with the RecommendationType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRecommendationType

`func (o *RecommendationSummary) SetRecommendationType(v string)`

SetRecommendationType sets RecommendationType field to given value.


### GetStatus

`func (o *RecommendationSummary) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *RecommendationSummary) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *RecommendationSummary) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetErrorMessage

`func (o *RecommendationSummary) GetErrorMessage() string`

GetErrorMessage returns the ErrorMessage field if non-nil, zero value otherwise.

### GetErrorMessageOk

`func (o *RecommendationSummary) GetErrorMessageOk() (*string, bool)`

GetErrorMessageOk returns a tuple with the ErrorMessage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrorMessage

`func (o *RecommendationSummary) SetErrorMessage(v string)`

SetErrorMessage sets ErrorMessage field to given value.


### SetErrorMessageNil

`func (o *RecommendationSummary) SetErrorMessageNil(b bool)`

 SetErrorMessageNil sets the value for ErrorMessage to be an explicit nil

### UnsetErrorMessage
`func (o *RecommendationSummary) UnsetErrorMessage()`

UnsetErrorMessage ensures that no value is present for ErrorMessage, not even an explicit nil
### GetGeneratedAt

`func (o *RecommendationSummary) GetGeneratedAt() time.Time`

GetGeneratedAt returns the GeneratedAt field if non-nil, zero value otherwise.

### GetGeneratedAtOk

`func (o *RecommendationSummary) GetGeneratedAtOk() (*time.Time, bool)`

GetGeneratedAtOk returns a tuple with the GeneratedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGeneratedAt

`func (o *RecommendationSummary) SetGeneratedAt(v time.Time)`

SetGeneratedAt sets GeneratedAt field to given value.


### SetGeneratedAtNil

`func (o *RecommendationSummary) SetGeneratedAtNil(b bool)`

 SetGeneratedAtNil sets the value for GeneratedAt to be an explicit nil

### UnsetGeneratedAt
`func (o *RecommendationSummary) UnsetGeneratedAt()`

UnsetGeneratedAt ensures that no value is present for GeneratedAt, not even an explicit nil
### GetCreatedAt

`func (o *RecommendationSummary) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *RecommendationSummary) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *RecommendationSummary) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetUpdatedAt

`func (o *RecommendationSummary) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *RecommendationSummary) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *RecommendationSummary) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.


### GetTotalRecommendations

`func (o *RecommendationSummary) GetTotalRecommendations() int32`

GetTotalRecommendations returns the TotalRecommendations field if non-nil, zero value otherwise.

### GetTotalRecommendationsOk

`func (o *RecommendationSummary) GetTotalRecommendationsOk() (*int32, bool)`

GetTotalRecommendationsOk returns a tuple with the TotalRecommendations field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalRecommendations

`func (o *RecommendationSummary) SetTotalRecommendations(v int32)`

SetTotalRecommendations sets TotalRecommendations field to given value.


### GetHighPriorityCount

`func (o *RecommendationSummary) GetHighPriorityCount() int32`

GetHighPriorityCount returns the HighPriorityCount field if non-nil, zero value otherwise.

### GetHighPriorityCountOk

`func (o *RecommendationSummary) GetHighPriorityCountOk() (*int32, bool)`

GetHighPriorityCountOk returns a tuple with the HighPriorityCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHighPriorityCount

`func (o *RecommendationSummary) SetHighPriorityCount(v int32)`

SetHighPriorityCount sets HighPriorityCount field to given value.


### GetSummary

`func (o *RecommendationSummary) GetSummary() RecommendationSummarySummary`

GetSummary returns the Summary field if non-nil, zero value otherwise.

### GetSummaryOk

`func (o *RecommendationSummary) GetSummaryOk() (*RecommendationSummarySummary, bool)`

GetSummaryOk returns a tuple with the Summary field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSummary

`func (o *RecommendationSummary) SetSummary(v RecommendationSummarySummary)`

SetSummary sets Summary field to given value.


### GetContext

`func (o *RecommendationSummary) GetContext() map[string]interface{}`

GetContext returns the Context field if non-nil, zero value otherwise.

### GetContextOk

`func (o *RecommendationSummary) GetContextOk() (*map[string]interface{}, bool)`

GetContextOk returns a tuple with the Context field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContext

`func (o *RecommendationSummary) SetContext(v map[string]interface{})`

SetContext sets Context field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


