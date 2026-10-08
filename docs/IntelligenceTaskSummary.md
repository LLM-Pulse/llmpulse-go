# IntelligenceTaskSummary

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **int32** |  | 
**PublicId** | **string** |  | 
**TaskType** | **string** |  | 
**Title** | **string** |  | 
**Status** | **string** |  | 
**PromptId** | **NullableInt32** |  | 
**PromptText** | **NullableString** |  | 
**WordCount** | **NullableInt32** |  | 
**ManuallyEditedAt** | **NullableTime** | When the content was last edited by hand; null while the output is as generated | 
**CreatedAt** | **time.Time** |  | 
**ProcessedAt** | **NullableTime** |  | 

## Methods

### NewIntelligenceTaskSummary

`func NewIntelligenceTaskSummary(id int32, publicId string, taskType string, title string, status string, promptId NullableInt32, promptText NullableString, wordCount NullableInt32, manuallyEditedAt NullableTime, createdAt time.Time, processedAt NullableTime, ) *IntelligenceTaskSummary`

NewIntelligenceTaskSummary instantiates a new IntelligenceTaskSummary object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewIntelligenceTaskSummaryWithDefaults

`func NewIntelligenceTaskSummaryWithDefaults() *IntelligenceTaskSummary`

NewIntelligenceTaskSummaryWithDefaults instantiates a new IntelligenceTaskSummary object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *IntelligenceTaskSummary) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *IntelligenceTaskSummary) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *IntelligenceTaskSummary) SetId(v int32)`

SetId sets Id field to given value.


### GetPublicId

`func (o *IntelligenceTaskSummary) GetPublicId() string`

GetPublicId returns the PublicId field if non-nil, zero value otherwise.

### GetPublicIdOk

`func (o *IntelligenceTaskSummary) GetPublicIdOk() (*string, bool)`

GetPublicIdOk returns a tuple with the PublicId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPublicId

`func (o *IntelligenceTaskSummary) SetPublicId(v string)`

SetPublicId sets PublicId field to given value.


### GetTaskType

`func (o *IntelligenceTaskSummary) GetTaskType() string`

GetTaskType returns the TaskType field if non-nil, zero value otherwise.

### GetTaskTypeOk

`func (o *IntelligenceTaskSummary) GetTaskTypeOk() (*string, bool)`

GetTaskTypeOk returns a tuple with the TaskType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaskType

`func (o *IntelligenceTaskSummary) SetTaskType(v string)`

SetTaskType sets TaskType field to given value.


### GetTitle

`func (o *IntelligenceTaskSummary) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *IntelligenceTaskSummary) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *IntelligenceTaskSummary) SetTitle(v string)`

SetTitle sets Title field to given value.


### GetStatus

`func (o *IntelligenceTaskSummary) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *IntelligenceTaskSummary) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *IntelligenceTaskSummary) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetPromptId

`func (o *IntelligenceTaskSummary) GetPromptId() int32`

GetPromptId returns the PromptId field if non-nil, zero value otherwise.

### GetPromptIdOk

`func (o *IntelligenceTaskSummary) GetPromptIdOk() (*int32, bool)`

GetPromptIdOk returns a tuple with the PromptId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPromptId

`func (o *IntelligenceTaskSummary) SetPromptId(v int32)`

SetPromptId sets PromptId field to given value.


### SetPromptIdNil

`func (o *IntelligenceTaskSummary) SetPromptIdNil(b bool)`

 SetPromptIdNil sets the value for PromptId to be an explicit nil

### UnsetPromptId
`func (o *IntelligenceTaskSummary) UnsetPromptId()`

UnsetPromptId ensures that no value is present for PromptId, not even an explicit nil
### GetPromptText

`func (o *IntelligenceTaskSummary) GetPromptText() string`

GetPromptText returns the PromptText field if non-nil, zero value otherwise.

### GetPromptTextOk

`func (o *IntelligenceTaskSummary) GetPromptTextOk() (*string, bool)`

GetPromptTextOk returns a tuple with the PromptText field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPromptText

`func (o *IntelligenceTaskSummary) SetPromptText(v string)`

SetPromptText sets PromptText field to given value.


### SetPromptTextNil

`func (o *IntelligenceTaskSummary) SetPromptTextNil(b bool)`

 SetPromptTextNil sets the value for PromptText to be an explicit nil

### UnsetPromptText
`func (o *IntelligenceTaskSummary) UnsetPromptText()`

UnsetPromptText ensures that no value is present for PromptText, not even an explicit nil
### GetWordCount

`func (o *IntelligenceTaskSummary) GetWordCount() int32`

GetWordCount returns the WordCount field if non-nil, zero value otherwise.

### GetWordCountOk

`func (o *IntelligenceTaskSummary) GetWordCountOk() (*int32, bool)`

GetWordCountOk returns a tuple with the WordCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWordCount

`func (o *IntelligenceTaskSummary) SetWordCount(v int32)`

SetWordCount sets WordCount field to given value.


### SetWordCountNil

`func (o *IntelligenceTaskSummary) SetWordCountNil(b bool)`

 SetWordCountNil sets the value for WordCount to be an explicit nil

### UnsetWordCount
`func (o *IntelligenceTaskSummary) UnsetWordCount()`

UnsetWordCount ensures that no value is present for WordCount, not even an explicit nil
### GetManuallyEditedAt

`func (o *IntelligenceTaskSummary) GetManuallyEditedAt() time.Time`

GetManuallyEditedAt returns the ManuallyEditedAt field if non-nil, zero value otherwise.

### GetManuallyEditedAtOk

`func (o *IntelligenceTaskSummary) GetManuallyEditedAtOk() (*time.Time, bool)`

GetManuallyEditedAtOk returns a tuple with the ManuallyEditedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetManuallyEditedAt

`func (o *IntelligenceTaskSummary) SetManuallyEditedAt(v time.Time)`

SetManuallyEditedAt sets ManuallyEditedAt field to given value.


### SetManuallyEditedAtNil

`func (o *IntelligenceTaskSummary) SetManuallyEditedAtNil(b bool)`

 SetManuallyEditedAtNil sets the value for ManuallyEditedAt to be an explicit nil

### UnsetManuallyEditedAt
`func (o *IntelligenceTaskSummary) UnsetManuallyEditedAt()`

UnsetManuallyEditedAt ensures that no value is present for ManuallyEditedAt, not even an explicit nil
### GetCreatedAt

`func (o *IntelligenceTaskSummary) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *IntelligenceTaskSummary) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *IntelligenceTaskSummary) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetProcessedAt

`func (o *IntelligenceTaskSummary) GetProcessedAt() time.Time`

GetProcessedAt returns the ProcessedAt field if non-nil, zero value otherwise.

### GetProcessedAtOk

`func (o *IntelligenceTaskSummary) GetProcessedAtOk() (*time.Time, bool)`

GetProcessedAtOk returns a tuple with the ProcessedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProcessedAt

`func (o *IntelligenceTaskSummary) SetProcessedAt(v time.Time)`

SetProcessedAt sets ProcessedAt field to given value.


### SetProcessedAtNil

`func (o *IntelligenceTaskSummary) SetProcessedAtNil(b bool)`

 SetProcessedAtNil sets the value for ProcessedAt to be an explicit nil

### UnsetProcessedAt
`func (o *IntelligenceTaskSummary) UnsetProcessedAt()`

UnsetProcessedAt ensures that no value is present for ProcessedAt, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


