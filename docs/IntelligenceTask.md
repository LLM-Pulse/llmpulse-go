# IntelligenceTask

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **int32** |  | [optional] 
**PublicId** | Pointer to **string** |  | [optional] 
**ProjectId** | Pointer to **int32** |  | [optional] 
**TaskType** | Pointer to **string** |  | [optional] 
**Title** | Pointer to **string** |  | [optional] 
**Status** | Pointer to **string** |  | [optional] 
**PromptId** | Pointer to **NullableInt32** |  | [optional] 
**PromptText** | Pointer to **NullableString** |  | [optional] 
**AgenticMode** | Pointer to **bool** |  | [optional] 
**CustomTopic** | Pointer to **NullableString** |  | [optional] 
**UserInstructions** | Pointer to **NullableString** |  | [optional] 
**OutputLanguageCode** | Pointer to **NullableString** |  | [optional] 
**WordCount** | Pointer to **NullableInt32** |  | [optional] 
**ResultData** | Pointer to **map[string]interface{}** | Only present when status&#x3D;&#39;completed&#39; | [optional] 
**ErrorMessage** | Pointer to **NullableString** |  | [optional] 
**EstimatedTime** | Pointer to **NullableString** |  | [optional] 
**CreatedAt** | Pointer to **time.Time** |  | [optional] 
**ProcessedAt** | Pointer to **NullableTime** |  | [optional] 
**ManuallyEditedAt** | Pointer to **NullableTime** | When the content was last edited by hand; null while the output is as generated | [optional] 
**EditedByUserId** | Pointer to **NullableInt32** | User behind the last manual edit; null for an unedited task or an edit made from an embedded portal | [optional] 
**RequestId** | Pointer to **string** |  | [optional] 

## Methods

### NewIntelligenceTask

`func NewIntelligenceTask() *IntelligenceTask`

NewIntelligenceTask instantiates a new IntelligenceTask object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewIntelligenceTaskWithDefaults

`func NewIntelligenceTaskWithDefaults() *IntelligenceTask`

NewIntelligenceTaskWithDefaults instantiates a new IntelligenceTask object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *IntelligenceTask) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *IntelligenceTask) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *IntelligenceTask) SetId(v int32)`

SetId sets Id field to given value.

### HasId

`func (o *IntelligenceTask) HasId() bool`

HasId returns a boolean if a field has been set.

### GetPublicId

`func (o *IntelligenceTask) GetPublicId() string`

GetPublicId returns the PublicId field if non-nil, zero value otherwise.

### GetPublicIdOk

`func (o *IntelligenceTask) GetPublicIdOk() (*string, bool)`

GetPublicIdOk returns a tuple with the PublicId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPublicId

`func (o *IntelligenceTask) SetPublicId(v string)`

SetPublicId sets PublicId field to given value.

### HasPublicId

`func (o *IntelligenceTask) HasPublicId() bool`

HasPublicId returns a boolean if a field has been set.

### GetProjectId

`func (o *IntelligenceTask) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *IntelligenceTask) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *IntelligenceTask) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.

### HasProjectId

`func (o *IntelligenceTask) HasProjectId() bool`

HasProjectId returns a boolean if a field has been set.

### GetTaskType

`func (o *IntelligenceTask) GetTaskType() string`

GetTaskType returns the TaskType field if non-nil, zero value otherwise.

### GetTaskTypeOk

`func (o *IntelligenceTask) GetTaskTypeOk() (*string, bool)`

GetTaskTypeOk returns a tuple with the TaskType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaskType

`func (o *IntelligenceTask) SetTaskType(v string)`

SetTaskType sets TaskType field to given value.

### HasTaskType

`func (o *IntelligenceTask) HasTaskType() bool`

HasTaskType returns a boolean if a field has been set.

### GetTitle

`func (o *IntelligenceTask) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *IntelligenceTask) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *IntelligenceTask) SetTitle(v string)`

SetTitle sets Title field to given value.

### HasTitle

`func (o *IntelligenceTask) HasTitle() bool`

HasTitle returns a boolean if a field has been set.

### GetStatus

`func (o *IntelligenceTask) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *IntelligenceTask) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *IntelligenceTask) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *IntelligenceTask) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetPromptId

`func (o *IntelligenceTask) GetPromptId() int32`

GetPromptId returns the PromptId field if non-nil, zero value otherwise.

### GetPromptIdOk

`func (o *IntelligenceTask) GetPromptIdOk() (*int32, bool)`

GetPromptIdOk returns a tuple with the PromptId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPromptId

`func (o *IntelligenceTask) SetPromptId(v int32)`

SetPromptId sets PromptId field to given value.

### HasPromptId

`func (o *IntelligenceTask) HasPromptId() bool`

HasPromptId returns a boolean if a field has been set.

### SetPromptIdNil

`func (o *IntelligenceTask) SetPromptIdNil(b bool)`

 SetPromptIdNil sets the value for PromptId to be an explicit nil

### UnsetPromptId
`func (o *IntelligenceTask) UnsetPromptId()`

UnsetPromptId ensures that no value is present for PromptId, not even an explicit nil
### GetPromptText

`func (o *IntelligenceTask) GetPromptText() string`

GetPromptText returns the PromptText field if non-nil, zero value otherwise.

### GetPromptTextOk

`func (o *IntelligenceTask) GetPromptTextOk() (*string, bool)`

GetPromptTextOk returns a tuple with the PromptText field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPromptText

`func (o *IntelligenceTask) SetPromptText(v string)`

SetPromptText sets PromptText field to given value.

### HasPromptText

`func (o *IntelligenceTask) HasPromptText() bool`

HasPromptText returns a boolean if a field has been set.

### SetPromptTextNil

`func (o *IntelligenceTask) SetPromptTextNil(b bool)`

 SetPromptTextNil sets the value for PromptText to be an explicit nil

### UnsetPromptText
`func (o *IntelligenceTask) UnsetPromptText()`

UnsetPromptText ensures that no value is present for PromptText, not even an explicit nil
### GetAgenticMode

`func (o *IntelligenceTask) GetAgenticMode() bool`

GetAgenticMode returns the AgenticMode field if non-nil, zero value otherwise.

### GetAgenticModeOk

`func (o *IntelligenceTask) GetAgenticModeOk() (*bool, bool)`

GetAgenticModeOk returns a tuple with the AgenticMode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAgenticMode

`func (o *IntelligenceTask) SetAgenticMode(v bool)`

SetAgenticMode sets AgenticMode field to given value.

### HasAgenticMode

`func (o *IntelligenceTask) HasAgenticMode() bool`

HasAgenticMode returns a boolean if a field has been set.

### GetCustomTopic

`func (o *IntelligenceTask) GetCustomTopic() string`

GetCustomTopic returns the CustomTopic field if non-nil, zero value otherwise.

### GetCustomTopicOk

`func (o *IntelligenceTask) GetCustomTopicOk() (*string, bool)`

GetCustomTopicOk returns a tuple with the CustomTopic field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomTopic

`func (o *IntelligenceTask) SetCustomTopic(v string)`

SetCustomTopic sets CustomTopic field to given value.

### HasCustomTopic

`func (o *IntelligenceTask) HasCustomTopic() bool`

HasCustomTopic returns a boolean if a field has been set.

### SetCustomTopicNil

`func (o *IntelligenceTask) SetCustomTopicNil(b bool)`

 SetCustomTopicNil sets the value for CustomTopic to be an explicit nil

### UnsetCustomTopic
`func (o *IntelligenceTask) UnsetCustomTopic()`

UnsetCustomTopic ensures that no value is present for CustomTopic, not even an explicit nil
### GetUserInstructions

`func (o *IntelligenceTask) GetUserInstructions() string`

GetUserInstructions returns the UserInstructions field if non-nil, zero value otherwise.

### GetUserInstructionsOk

`func (o *IntelligenceTask) GetUserInstructionsOk() (*string, bool)`

GetUserInstructionsOk returns a tuple with the UserInstructions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserInstructions

`func (o *IntelligenceTask) SetUserInstructions(v string)`

SetUserInstructions sets UserInstructions field to given value.

### HasUserInstructions

`func (o *IntelligenceTask) HasUserInstructions() bool`

HasUserInstructions returns a boolean if a field has been set.

### SetUserInstructionsNil

`func (o *IntelligenceTask) SetUserInstructionsNil(b bool)`

 SetUserInstructionsNil sets the value for UserInstructions to be an explicit nil

### UnsetUserInstructions
`func (o *IntelligenceTask) UnsetUserInstructions()`

UnsetUserInstructions ensures that no value is present for UserInstructions, not even an explicit nil
### GetOutputLanguageCode

`func (o *IntelligenceTask) GetOutputLanguageCode() string`

GetOutputLanguageCode returns the OutputLanguageCode field if non-nil, zero value otherwise.

### GetOutputLanguageCodeOk

`func (o *IntelligenceTask) GetOutputLanguageCodeOk() (*string, bool)`

GetOutputLanguageCodeOk returns a tuple with the OutputLanguageCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOutputLanguageCode

`func (o *IntelligenceTask) SetOutputLanguageCode(v string)`

SetOutputLanguageCode sets OutputLanguageCode field to given value.

### HasOutputLanguageCode

`func (o *IntelligenceTask) HasOutputLanguageCode() bool`

HasOutputLanguageCode returns a boolean if a field has been set.

### SetOutputLanguageCodeNil

`func (o *IntelligenceTask) SetOutputLanguageCodeNil(b bool)`

 SetOutputLanguageCodeNil sets the value for OutputLanguageCode to be an explicit nil

### UnsetOutputLanguageCode
`func (o *IntelligenceTask) UnsetOutputLanguageCode()`

UnsetOutputLanguageCode ensures that no value is present for OutputLanguageCode, not even an explicit nil
### GetWordCount

`func (o *IntelligenceTask) GetWordCount() int32`

GetWordCount returns the WordCount field if non-nil, zero value otherwise.

### GetWordCountOk

`func (o *IntelligenceTask) GetWordCountOk() (*int32, bool)`

GetWordCountOk returns a tuple with the WordCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWordCount

`func (o *IntelligenceTask) SetWordCount(v int32)`

SetWordCount sets WordCount field to given value.

### HasWordCount

`func (o *IntelligenceTask) HasWordCount() bool`

HasWordCount returns a boolean if a field has been set.

### SetWordCountNil

`func (o *IntelligenceTask) SetWordCountNil(b bool)`

 SetWordCountNil sets the value for WordCount to be an explicit nil

### UnsetWordCount
`func (o *IntelligenceTask) UnsetWordCount()`

UnsetWordCount ensures that no value is present for WordCount, not even an explicit nil
### GetResultData

`func (o *IntelligenceTask) GetResultData() map[string]interface{}`

GetResultData returns the ResultData field if non-nil, zero value otherwise.

### GetResultDataOk

`func (o *IntelligenceTask) GetResultDataOk() (*map[string]interface{}, bool)`

GetResultDataOk returns a tuple with the ResultData field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResultData

`func (o *IntelligenceTask) SetResultData(v map[string]interface{})`

SetResultData sets ResultData field to given value.

### HasResultData

`func (o *IntelligenceTask) HasResultData() bool`

HasResultData returns a boolean if a field has been set.

### GetErrorMessage

`func (o *IntelligenceTask) GetErrorMessage() string`

GetErrorMessage returns the ErrorMessage field if non-nil, zero value otherwise.

### GetErrorMessageOk

`func (o *IntelligenceTask) GetErrorMessageOk() (*string, bool)`

GetErrorMessageOk returns a tuple with the ErrorMessage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrorMessage

`func (o *IntelligenceTask) SetErrorMessage(v string)`

SetErrorMessage sets ErrorMessage field to given value.

### HasErrorMessage

`func (o *IntelligenceTask) HasErrorMessage() bool`

HasErrorMessage returns a boolean if a field has been set.

### SetErrorMessageNil

`func (o *IntelligenceTask) SetErrorMessageNil(b bool)`

 SetErrorMessageNil sets the value for ErrorMessage to be an explicit nil

### UnsetErrorMessage
`func (o *IntelligenceTask) UnsetErrorMessage()`

UnsetErrorMessage ensures that no value is present for ErrorMessage, not even an explicit nil
### GetEstimatedTime

`func (o *IntelligenceTask) GetEstimatedTime() string`

GetEstimatedTime returns the EstimatedTime field if non-nil, zero value otherwise.

### GetEstimatedTimeOk

`func (o *IntelligenceTask) GetEstimatedTimeOk() (*string, bool)`

GetEstimatedTimeOk returns a tuple with the EstimatedTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEstimatedTime

`func (o *IntelligenceTask) SetEstimatedTime(v string)`

SetEstimatedTime sets EstimatedTime field to given value.

### HasEstimatedTime

`func (o *IntelligenceTask) HasEstimatedTime() bool`

HasEstimatedTime returns a boolean if a field has been set.

### SetEstimatedTimeNil

`func (o *IntelligenceTask) SetEstimatedTimeNil(b bool)`

 SetEstimatedTimeNil sets the value for EstimatedTime to be an explicit nil

### UnsetEstimatedTime
`func (o *IntelligenceTask) UnsetEstimatedTime()`

UnsetEstimatedTime ensures that no value is present for EstimatedTime, not even an explicit nil
### GetCreatedAt

`func (o *IntelligenceTask) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *IntelligenceTask) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *IntelligenceTask) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *IntelligenceTask) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetProcessedAt

`func (o *IntelligenceTask) GetProcessedAt() time.Time`

GetProcessedAt returns the ProcessedAt field if non-nil, zero value otherwise.

### GetProcessedAtOk

`func (o *IntelligenceTask) GetProcessedAtOk() (*time.Time, bool)`

GetProcessedAtOk returns a tuple with the ProcessedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProcessedAt

`func (o *IntelligenceTask) SetProcessedAt(v time.Time)`

SetProcessedAt sets ProcessedAt field to given value.

### HasProcessedAt

`func (o *IntelligenceTask) HasProcessedAt() bool`

HasProcessedAt returns a boolean if a field has been set.

### SetProcessedAtNil

`func (o *IntelligenceTask) SetProcessedAtNil(b bool)`

 SetProcessedAtNil sets the value for ProcessedAt to be an explicit nil

### UnsetProcessedAt
`func (o *IntelligenceTask) UnsetProcessedAt()`

UnsetProcessedAt ensures that no value is present for ProcessedAt, not even an explicit nil
### GetManuallyEditedAt

`func (o *IntelligenceTask) GetManuallyEditedAt() time.Time`

GetManuallyEditedAt returns the ManuallyEditedAt field if non-nil, zero value otherwise.

### GetManuallyEditedAtOk

`func (o *IntelligenceTask) GetManuallyEditedAtOk() (*time.Time, bool)`

GetManuallyEditedAtOk returns a tuple with the ManuallyEditedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetManuallyEditedAt

`func (o *IntelligenceTask) SetManuallyEditedAt(v time.Time)`

SetManuallyEditedAt sets ManuallyEditedAt field to given value.

### HasManuallyEditedAt

`func (o *IntelligenceTask) HasManuallyEditedAt() bool`

HasManuallyEditedAt returns a boolean if a field has been set.

### SetManuallyEditedAtNil

`func (o *IntelligenceTask) SetManuallyEditedAtNil(b bool)`

 SetManuallyEditedAtNil sets the value for ManuallyEditedAt to be an explicit nil

### UnsetManuallyEditedAt
`func (o *IntelligenceTask) UnsetManuallyEditedAt()`

UnsetManuallyEditedAt ensures that no value is present for ManuallyEditedAt, not even an explicit nil
### GetEditedByUserId

`func (o *IntelligenceTask) GetEditedByUserId() int32`

GetEditedByUserId returns the EditedByUserId field if non-nil, zero value otherwise.

### GetEditedByUserIdOk

`func (o *IntelligenceTask) GetEditedByUserIdOk() (*int32, bool)`

GetEditedByUserIdOk returns a tuple with the EditedByUserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEditedByUserId

`func (o *IntelligenceTask) SetEditedByUserId(v int32)`

SetEditedByUserId sets EditedByUserId field to given value.

### HasEditedByUserId

`func (o *IntelligenceTask) HasEditedByUserId() bool`

HasEditedByUserId returns a boolean if a field has been set.

### SetEditedByUserIdNil

`func (o *IntelligenceTask) SetEditedByUserIdNil(b bool)`

 SetEditedByUserIdNil sets the value for EditedByUserId to be an explicit nil

### UnsetEditedByUserId
`func (o *IntelligenceTask) UnsetEditedByUserId()`

UnsetEditedByUserId ensures that no value is present for EditedByUserId, not even an explicit nil
### GetRequestId

`func (o *IntelligenceTask) GetRequestId() string`

GetRequestId returns the RequestId field if non-nil, zero value otherwise.

### GetRequestIdOk

`func (o *IntelligenceTask) GetRequestIdOk() (*string, bool)`

GetRequestIdOk returns a tuple with the RequestId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestId

`func (o *IntelligenceTask) SetRequestId(v string)`

SetRequestId sets RequestId field to given value.

### HasRequestId

`func (o *IntelligenceTask) HasRequestId() bool`

HasRequestId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


