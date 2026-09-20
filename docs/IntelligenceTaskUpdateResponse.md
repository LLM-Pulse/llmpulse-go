# IntelligenceTaskUpdateResponse

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
**ChangedPaths** | Pointer to **[]string** | Paths whose text actually changed; empty when every value matched the stored text | [optional] 

## Methods

### NewIntelligenceTaskUpdateResponse

`func NewIntelligenceTaskUpdateResponse() *IntelligenceTaskUpdateResponse`

NewIntelligenceTaskUpdateResponse instantiates a new IntelligenceTaskUpdateResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewIntelligenceTaskUpdateResponseWithDefaults

`func NewIntelligenceTaskUpdateResponseWithDefaults() *IntelligenceTaskUpdateResponse`

NewIntelligenceTaskUpdateResponseWithDefaults instantiates a new IntelligenceTaskUpdateResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *IntelligenceTaskUpdateResponse) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *IntelligenceTaskUpdateResponse) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *IntelligenceTaskUpdateResponse) SetId(v int32)`

SetId sets Id field to given value.

### HasId

`func (o *IntelligenceTaskUpdateResponse) HasId() bool`

HasId returns a boolean if a field has been set.

### GetPublicId

`func (o *IntelligenceTaskUpdateResponse) GetPublicId() string`

GetPublicId returns the PublicId field if non-nil, zero value otherwise.

### GetPublicIdOk

`func (o *IntelligenceTaskUpdateResponse) GetPublicIdOk() (*string, bool)`

GetPublicIdOk returns a tuple with the PublicId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPublicId

`func (o *IntelligenceTaskUpdateResponse) SetPublicId(v string)`

SetPublicId sets PublicId field to given value.

### HasPublicId

`func (o *IntelligenceTaskUpdateResponse) HasPublicId() bool`

HasPublicId returns a boolean if a field has been set.

### GetProjectId

`func (o *IntelligenceTaskUpdateResponse) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *IntelligenceTaskUpdateResponse) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *IntelligenceTaskUpdateResponse) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.

### HasProjectId

`func (o *IntelligenceTaskUpdateResponse) HasProjectId() bool`

HasProjectId returns a boolean if a field has been set.

### GetTaskType

`func (o *IntelligenceTaskUpdateResponse) GetTaskType() string`

GetTaskType returns the TaskType field if non-nil, zero value otherwise.

### GetTaskTypeOk

`func (o *IntelligenceTaskUpdateResponse) GetTaskTypeOk() (*string, bool)`

GetTaskTypeOk returns a tuple with the TaskType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaskType

`func (o *IntelligenceTaskUpdateResponse) SetTaskType(v string)`

SetTaskType sets TaskType field to given value.

### HasTaskType

`func (o *IntelligenceTaskUpdateResponse) HasTaskType() bool`

HasTaskType returns a boolean if a field has been set.

### GetTitle

`func (o *IntelligenceTaskUpdateResponse) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *IntelligenceTaskUpdateResponse) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *IntelligenceTaskUpdateResponse) SetTitle(v string)`

SetTitle sets Title field to given value.

### HasTitle

`func (o *IntelligenceTaskUpdateResponse) HasTitle() bool`

HasTitle returns a boolean if a field has been set.

### GetStatus

`func (o *IntelligenceTaskUpdateResponse) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *IntelligenceTaskUpdateResponse) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *IntelligenceTaskUpdateResponse) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *IntelligenceTaskUpdateResponse) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetPromptId

`func (o *IntelligenceTaskUpdateResponse) GetPromptId() int32`

GetPromptId returns the PromptId field if non-nil, zero value otherwise.

### GetPromptIdOk

`func (o *IntelligenceTaskUpdateResponse) GetPromptIdOk() (*int32, bool)`

GetPromptIdOk returns a tuple with the PromptId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPromptId

`func (o *IntelligenceTaskUpdateResponse) SetPromptId(v int32)`

SetPromptId sets PromptId field to given value.

### HasPromptId

`func (o *IntelligenceTaskUpdateResponse) HasPromptId() bool`

HasPromptId returns a boolean if a field has been set.

### SetPromptIdNil

`func (o *IntelligenceTaskUpdateResponse) SetPromptIdNil(b bool)`

 SetPromptIdNil sets the value for PromptId to be an explicit nil

### UnsetPromptId
`func (o *IntelligenceTaskUpdateResponse) UnsetPromptId()`

UnsetPromptId ensures that no value is present for PromptId, not even an explicit nil
### GetPromptText

`func (o *IntelligenceTaskUpdateResponse) GetPromptText() string`

GetPromptText returns the PromptText field if non-nil, zero value otherwise.

### GetPromptTextOk

`func (o *IntelligenceTaskUpdateResponse) GetPromptTextOk() (*string, bool)`

GetPromptTextOk returns a tuple with the PromptText field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPromptText

`func (o *IntelligenceTaskUpdateResponse) SetPromptText(v string)`

SetPromptText sets PromptText field to given value.

### HasPromptText

`func (o *IntelligenceTaskUpdateResponse) HasPromptText() bool`

HasPromptText returns a boolean if a field has been set.

### SetPromptTextNil

`func (o *IntelligenceTaskUpdateResponse) SetPromptTextNil(b bool)`

 SetPromptTextNil sets the value for PromptText to be an explicit nil

### UnsetPromptText
`func (o *IntelligenceTaskUpdateResponse) UnsetPromptText()`

UnsetPromptText ensures that no value is present for PromptText, not even an explicit nil
### GetAgenticMode

`func (o *IntelligenceTaskUpdateResponse) GetAgenticMode() bool`

GetAgenticMode returns the AgenticMode field if non-nil, zero value otherwise.

### GetAgenticModeOk

`func (o *IntelligenceTaskUpdateResponse) GetAgenticModeOk() (*bool, bool)`

GetAgenticModeOk returns a tuple with the AgenticMode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAgenticMode

`func (o *IntelligenceTaskUpdateResponse) SetAgenticMode(v bool)`

SetAgenticMode sets AgenticMode field to given value.

### HasAgenticMode

`func (o *IntelligenceTaskUpdateResponse) HasAgenticMode() bool`

HasAgenticMode returns a boolean if a field has been set.

### GetCustomTopic

`func (o *IntelligenceTaskUpdateResponse) GetCustomTopic() string`

GetCustomTopic returns the CustomTopic field if non-nil, zero value otherwise.

### GetCustomTopicOk

`func (o *IntelligenceTaskUpdateResponse) GetCustomTopicOk() (*string, bool)`

GetCustomTopicOk returns a tuple with the CustomTopic field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomTopic

`func (o *IntelligenceTaskUpdateResponse) SetCustomTopic(v string)`

SetCustomTopic sets CustomTopic field to given value.

### HasCustomTopic

`func (o *IntelligenceTaskUpdateResponse) HasCustomTopic() bool`

HasCustomTopic returns a boolean if a field has been set.

### SetCustomTopicNil

`func (o *IntelligenceTaskUpdateResponse) SetCustomTopicNil(b bool)`

 SetCustomTopicNil sets the value for CustomTopic to be an explicit nil

### UnsetCustomTopic
`func (o *IntelligenceTaskUpdateResponse) UnsetCustomTopic()`

UnsetCustomTopic ensures that no value is present for CustomTopic, not even an explicit nil
### GetUserInstructions

`func (o *IntelligenceTaskUpdateResponse) GetUserInstructions() string`

GetUserInstructions returns the UserInstructions field if non-nil, zero value otherwise.

### GetUserInstructionsOk

`func (o *IntelligenceTaskUpdateResponse) GetUserInstructionsOk() (*string, bool)`

GetUserInstructionsOk returns a tuple with the UserInstructions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserInstructions

`func (o *IntelligenceTaskUpdateResponse) SetUserInstructions(v string)`

SetUserInstructions sets UserInstructions field to given value.

### HasUserInstructions

`func (o *IntelligenceTaskUpdateResponse) HasUserInstructions() bool`

HasUserInstructions returns a boolean if a field has been set.

### SetUserInstructionsNil

`func (o *IntelligenceTaskUpdateResponse) SetUserInstructionsNil(b bool)`

 SetUserInstructionsNil sets the value for UserInstructions to be an explicit nil

### UnsetUserInstructions
`func (o *IntelligenceTaskUpdateResponse) UnsetUserInstructions()`

UnsetUserInstructions ensures that no value is present for UserInstructions, not even an explicit nil
### GetOutputLanguageCode

`func (o *IntelligenceTaskUpdateResponse) GetOutputLanguageCode() string`

GetOutputLanguageCode returns the OutputLanguageCode field if non-nil, zero value otherwise.

### GetOutputLanguageCodeOk

`func (o *IntelligenceTaskUpdateResponse) GetOutputLanguageCodeOk() (*string, bool)`

GetOutputLanguageCodeOk returns a tuple with the OutputLanguageCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOutputLanguageCode

`func (o *IntelligenceTaskUpdateResponse) SetOutputLanguageCode(v string)`

SetOutputLanguageCode sets OutputLanguageCode field to given value.

### HasOutputLanguageCode

`func (o *IntelligenceTaskUpdateResponse) HasOutputLanguageCode() bool`

HasOutputLanguageCode returns a boolean if a field has been set.

### SetOutputLanguageCodeNil

`func (o *IntelligenceTaskUpdateResponse) SetOutputLanguageCodeNil(b bool)`

 SetOutputLanguageCodeNil sets the value for OutputLanguageCode to be an explicit nil

### UnsetOutputLanguageCode
`func (o *IntelligenceTaskUpdateResponse) UnsetOutputLanguageCode()`

UnsetOutputLanguageCode ensures that no value is present for OutputLanguageCode, not even an explicit nil
### GetWordCount

`func (o *IntelligenceTaskUpdateResponse) GetWordCount() int32`

GetWordCount returns the WordCount field if non-nil, zero value otherwise.

### GetWordCountOk

`func (o *IntelligenceTaskUpdateResponse) GetWordCountOk() (*int32, bool)`

GetWordCountOk returns a tuple with the WordCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWordCount

`func (o *IntelligenceTaskUpdateResponse) SetWordCount(v int32)`

SetWordCount sets WordCount field to given value.

### HasWordCount

`func (o *IntelligenceTaskUpdateResponse) HasWordCount() bool`

HasWordCount returns a boolean if a field has been set.

### SetWordCountNil

`func (o *IntelligenceTaskUpdateResponse) SetWordCountNil(b bool)`

 SetWordCountNil sets the value for WordCount to be an explicit nil

### UnsetWordCount
`func (o *IntelligenceTaskUpdateResponse) UnsetWordCount()`

UnsetWordCount ensures that no value is present for WordCount, not even an explicit nil
### GetResultData

`func (o *IntelligenceTaskUpdateResponse) GetResultData() map[string]interface{}`

GetResultData returns the ResultData field if non-nil, zero value otherwise.

### GetResultDataOk

`func (o *IntelligenceTaskUpdateResponse) GetResultDataOk() (*map[string]interface{}, bool)`

GetResultDataOk returns a tuple with the ResultData field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResultData

`func (o *IntelligenceTaskUpdateResponse) SetResultData(v map[string]interface{})`

SetResultData sets ResultData field to given value.

### HasResultData

`func (o *IntelligenceTaskUpdateResponse) HasResultData() bool`

HasResultData returns a boolean if a field has been set.

### GetErrorMessage

`func (o *IntelligenceTaskUpdateResponse) GetErrorMessage() string`

GetErrorMessage returns the ErrorMessage field if non-nil, zero value otherwise.

### GetErrorMessageOk

`func (o *IntelligenceTaskUpdateResponse) GetErrorMessageOk() (*string, bool)`

GetErrorMessageOk returns a tuple with the ErrorMessage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrorMessage

`func (o *IntelligenceTaskUpdateResponse) SetErrorMessage(v string)`

SetErrorMessage sets ErrorMessage field to given value.

### HasErrorMessage

`func (o *IntelligenceTaskUpdateResponse) HasErrorMessage() bool`

HasErrorMessage returns a boolean if a field has been set.

### SetErrorMessageNil

`func (o *IntelligenceTaskUpdateResponse) SetErrorMessageNil(b bool)`

 SetErrorMessageNil sets the value for ErrorMessage to be an explicit nil

### UnsetErrorMessage
`func (o *IntelligenceTaskUpdateResponse) UnsetErrorMessage()`

UnsetErrorMessage ensures that no value is present for ErrorMessage, not even an explicit nil
### GetEstimatedTime

`func (o *IntelligenceTaskUpdateResponse) GetEstimatedTime() string`

GetEstimatedTime returns the EstimatedTime field if non-nil, zero value otherwise.

### GetEstimatedTimeOk

`func (o *IntelligenceTaskUpdateResponse) GetEstimatedTimeOk() (*string, bool)`

GetEstimatedTimeOk returns a tuple with the EstimatedTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEstimatedTime

`func (o *IntelligenceTaskUpdateResponse) SetEstimatedTime(v string)`

SetEstimatedTime sets EstimatedTime field to given value.

### HasEstimatedTime

`func (o *IntelligenceTaskUpdateResponse) HasEstimatedTime() bool`

HasEstimatedTime returns a boolean if a field has been set.

### SetEstimatedTimeNil

`func (o *IntelligenceTaskUpdateResponse) SetEstimatedTimeNil(b bool)`

 SetEstimatedTimeNil sets the value for EstimatedTime to be an explicit nil

### UnsetEstimatedTime
`func (o *IntelligenceTaskUpdateResponse) UnsetEstimatedTime()`

UnsetEstimatedTime ensures that no value is present for EstimatedTime, not even an explicit nil
### GetCreatedAt

`func (o *IntelligenceTaskUpdateResponse) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *IntelligenceTaskUpdateResponse) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *IntelligenceTaskUpdateResponse) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *IntelligenceTaskUpdateResponse) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetProcessedAt

`func (o *IntelligenceTaskUpdateResponse) GetProcessedAt() time.Time`

GetProcessedAt returns the ProcessedAt field if non-nil, zero value otherwise.

### GetProcessedAtOk

`func (o *IntelligenceTaskUpdateResponse) GetProcessedAtOk() (*time.Time, bool)`

GetProcessedAtOk returns a tuple with the ProcessedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProcessedAt

`func (o *IntelligenceTaskUpdateResponse) SetProcessedAt(v time.Time)`

SetProcessedAt sets ProcessedAt field to given value.

### HasProcessedAt

`func (o *IntelligenceTaskUpdateResponse) HasProcessedAt() bool`

HasProcessedAt returns a boolean if a field has been set.

### SetProcessedAtNil

`func (o *IntelligenceTaskUpdateResponse) SetProcessedAtNil(b bool)`

 SetProcessedAtNil sets the value for ProcessedAt to be an explicit nil

### UnsetProcessedAt
`func (o *IntelligenceTaskUpdateResponse) UnsetProcessedAt()`

UnsetProcessedAt ensures that no value is present for ProcessedAt, not even an explicit nil
### GetManuallyEditedAt

`func (o *IntelligenceTaskUpdateResponse) GetManuallyEditedAt() time.Time`

GetManuallyEditedAt returns the ManuallyEditedAt field if non-nil, zero value otherwise.

### GetManuallyEditedAtOk

`func (o *IntelligenceTaskUpdateResponse) GetManuallyEditedAtOk() (*time.Time, bool)`

GetManuallyEditedAtOk returns a tuple with the ManuallyEditedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetManuallyEditedAt

`func (o *IntelligenceTaskUpdateResponse) SetManuallyEditedAt(v time.Time)`

SetManuallyEditedAt sets ManuallyEditedAt field to given value.

### HasManuallyEditedAt

`func (o *IntelligenceTaskUpdateResponse) HasManuallyEditedAt() bool`

HasManuallyEditedAt returns a boolean if a field has been set.

### SetManuallyEditedAtNil

`func (o *IntelligenceTaskUpdateResponse) SetManuallyEditedAtNil(b bool)`

 SetManuallyEditedAtNil sets the value for ManuallyEditedAt to be an explicit nil

### UnsetManuallyEditedAt
`func (o *IntelligenceTaskUpdateResponse) UnsetManuallyEditedAt()`

UnsetManuallyEditedAt ensures that no value is present for ManuallyEditedAt, not even an explicit nil
### GetEditedByUserId

`func (o *IntelligenceTaskUpdateResponse) GetEditedByUserId() int32`

GetEditedByUserId returns the EditedByUserId field if non-nil, zero value otherwise.

### GetEditedByUserIdOk

`func (o *IntelligenceTaskUpdateResponse) GetEditedByUserIdOk() (*int32, bool)`

GetEditedByUserIdOk returns a tuple with the EditedByUserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEditedByUserId

`func (o *IntelligenceTaskUpdateResponse) SetEditedByUserId(v int32)`

SetEditedByUserId sets EditedByUserId field to given value.

### HasEditedByUserId

`func (o *IntelligenceTaskUpdateResponse) HasEditedByUserId() bool`

HasEditedByUserId returns a boolean if a field has been set.

### SetEditedByUserIdNil

`func (o *IntelligenceTaskUpdateResponse) SetEditedByUserIdNil(b bool)`

 SetEditedByUserIdNil sets the value for EditedByUserId to be an explicit nil

### UnsetEditedByUserId
`func (o *IntelligenceTaskUpdateResponse) UnsetEditedByUserId()`

UnsetEditedByUserId ensures that no value is present for EditedByUserId, not even an explicit nil
### GetRequestId

`func (o *IntelligenceTaskUpdateResponse) GetRequestId() string`

GetRequestId returns the RequestId field if non-nil, zero value otherwise.

### GetRequestIdOk

`func (o *IntelligenceTaskUpdateResponse) GetRequestIdOk() (*string, bool)`

GetRequestIdOk returns a tuple with the RequestId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestId

`func (o *IntelligenceTaskUpdateResponse) SetRequestId(v string)`

SetRequestId sets RequestId field to given value.

### HasRequestId

`func (o *IntelligenceTaskUpdateResponse) HasRequestId() bool`

HasRequestId returns a boolean if a field has been set.

### GetChangedPaths

`func (o *IntelligenceTaskUpdateResponse) GetChangedPaths() []string`

GetChangedPaths returns the ChangedPaths field if non-nil, zero value otherwise.

### GetChangedPathsOk

`func (o *IntelligenceTaskUpdateResponse) GetChangedPathsOk() (*[]string, bool)`

GetChangedPathsOk returns a tuple with the ChangedPaths field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChangedPaths

`func (o *IntelligenceTaskUpdateResponse) SetChangedPaths(v []string)`

SetChangedPaths sets ChangedPaths field to given value.

### HasChangedPaths

`func (o *IntelligenceTaskUpdateResponse) HasChangedPaths() bool`

HasChangedPaths returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


