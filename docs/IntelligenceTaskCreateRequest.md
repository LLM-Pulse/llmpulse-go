# IntelligenceTaskCreateRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ProjectId** | **int32** |  | 
**TaskType** | **string** | product_listing is API-only: it needs product and returns ready-to-apply product page copy | 
**PromptId** | Pointer to **NullableInt32** | Not used by product_listing; send null or omit it | [optional] 
**CustomTopic** | Pointer to **string** |  | [optional] 
**UserInstructions** | Pointer to **string** |  | [optional] 
**OutputLanguageCode** | Pointer to **string** |  | [optional] 
**ExistingContent** | Pointer to **string** |  | [optional] 
**ExistingContentUrl** | Pointer to **string** |  | [optional] 
**Product** | Pointer to [**IntelligenceTaskProduct**](IntelligenceTaskProduct.md) |  | [optional] 
**PromptIds** | Pointer to **[]int32** | product_listing only: up to 20 project prompts the copy should answer | [optional] 

## Methods

### NewIntelligenceTaskCreateRequest

`func NewIntelligenceTaskCreateRequest(projectId int32, taskType string, ) *IntelligenceTaskCreateRequest`

NewIntelligenceTaskCreateRequest instantiates a new IntelligenceTaskCreateRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewIntelligenceTaskCreateRequestWithDefaults

`func NewIntelligenceTaskCreateRequestWithDefaults() *IntelligenceTaskCreateRequest`

NewIntelligenceTaskCreateRequestWithDefaults instantiates a new IntelligenceTaskCreateRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProjectId

`func (o *IntelligenceTaskCreateRequest) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *IntelligenceTaskCreateRequest) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *IntelligenceTaskCreateRequest) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.


### GetTaskType

`func (o *IntelligenceTaskCreateRequest) GetTaskType() string`

GetTaskType returns the TaskType field if non-nil, zero value otherwise.

### GetTaskTypeOk

`func (o *IntelligenceTaskCreateRequest) GetTaskTypeOk() (*string, bool)`

GetTaskTypeOk returns a tuple with the TaskType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaskType

`func (o *IntelligenceTaskCreateRequest) SetTaskType(v string)`

SetTaskType sets TaskType field to given value.


### GetPromptId

`func (o *IntelligenceTaskCreateRequest) GetPromptId() int32`

GetPromptId returns the PromptId field if non-nil, zero value otherwise.

### GetPromptIdOk

`func (o *IntelligenceTaskCreateRequest) GetPromptIdOk() (*int32, bool)`

GetPromptIdOk returns a tuple with the PromptId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPromptId

`func (o *IntelligenceTaskCreateRequest) SetPromptId(v int32)`

SetPromptId sets PromptId field to given value.

### HasPromptId

`func (o *IntelligenceTaskCreateRequest) HasPromptId() bool`

HasPromptId returns a boolean if a field has been set.

### SetPromptIdNil

`func (o *IntelligenceTaskCreateRequest) SetPromptIdNil(b bool)`

 SetPromptIdNil sets the value for PromptId to be an explicit nil

### UnsetPromptId
`func (o *IntelligenceTaskCreateRequest) UnsetPromptId()`

UnsetPromptId ensures that no value is present for PromptId, not even an explicit nil
### GetCustomTopic

`func (o *IntelligenceTaskCreateRequest) GetCustomTopic() string`

GetCustomTopic returns the CustomTopic field if non-nil, zero value otherwise.

### GetCustomTopicOk

`func (o *IntelligenceTaskCreateRequest) GetCustomTopicOk() (*string, bool)`

GetCustomTopicOk returns a tuple with the CustomTopic field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomTopic

`func (o *IntelligenceTaskCreateRequest) SetCustomTopic(v string)`

SetCustomTopic sets CustomTopic field to given value.

### HasCustomTopic

`func (o *IntelligenceTaskCreateRequest) HasCustomTopic() bool`

HasCustomTopic returns a boolean if a field has been set.

### GetUserInstructions

`func (o *IntelligenceTaskCreateRequest) GetUserInstructions() string`

GetUserInstructions returns the UserInstructions field if non-nil, zero value otherwise.

### GetUserInstructionsOk

`func (o *IntelligenceTaskCreateRequest) GetUserInstructionsOk() (*string, bool)`

GetUserInstructionsOk returns a tuple with the UserInstructions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserInstructions

`func (o *IntelligenceTaskCreateRequest) SetUserInstructions(v string)`

SetUserInstructions sets UserInstructions field to given value.

### HasUserInstructions

`func (o *IntelligenceTaskCreateRequest) HasUserInstructions() bool`

HasUserInstructions returns a boolean if a field has been set.

### GetOutputLanguageCode

`func (o *IntelligenceTaskCreateRequest) GetOutputLanguageCode() string`

GetOutputLanguageCode returns the OutputLanguageCode field if non-nil, zero value otherwise.

### GetOutputLanguageCodeOk

`func (o *IntelligenceTaskCreateRequest) GetOutputLanguageCodeOk() (*string, bool)`

GetOutputLanguageCodeOk returns a tuple with the OutputLanguageCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOutputLanguageCode

`func (o *IntelligenceTaskCreateRequest) SetOutputLanguageCode(v string)`

SetOutputLanguageCode sets OutputLanguageCode field to given value.

### HasOutputLanguageCode

`func (o *IntelligenceTaskCreateRequest) HasOutputLanguageCode() bool`

HasOutputLanguageCode returns a boolean if a field has been set.

### GetExistingContent

`func (o *IntelligenceTaskCreateRequest) GetExistingContent() string`

GetExistingContent returns the ExistingContent field if non-nil, zero value otherwise.

### GetExistingContentOk

`func (o *IntelligenceTaskCreateRequest) GetExistingContentOk() (*string, bool)`

GetExistingContentOk returns a tuple with the ExistingContent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExistingContent

`func (o *IntelligenceTaskCreateRequest) SetExistingContent(v string)`

SetExistingContent sets ExistingContent field to given value.

### HasExistingContent

`func (o *IntelligenceTaskCreateRequest) HasExistingContent() bool`

HasExistingContent returns a boolean if a field has been set.

### GetExistingContentUrl

`func (o *IntelligenceTaskCreateRequest) GetExistingContentUrl() string`

GetExistingContentUrl returns the ExistingContentUrl field if non-nil, zero value otherwise.

### GetExistingContentUrlOk

`func (o *IntelligenceTaskCreateRequest) GetExistingContentUrlOk() (*string, bool)`

GetExistingContentUrlOk returns a tuple with the ExistingContentUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExistingContentUrl

`func (o *IntelligenceTaskCreateRequest) SetExistingContentUrl(v string)`

SetExistingContentUrl sets ExistingContentUrl field to given value.

### HasExistingContentUrl

`func (o *IntelligenceTaskCreateRequest) HasExistingContentUrl() bool`

HasExistingContentUrl returns a boolean if a field has been set.

### GetProduct

`func (o *IntelligenceTaskCreateRequest) GetProduct() IntelligenceTaskProduct`

GetProduct returns the Product field if non-nil, zero value otherwise.

### GetProductOk

`func (o *IntelligenceTaskCreateRequest) GetProductOk() (*IntelligenceTaskProduct, bool)`

GetProductOk returns a tuple with the Product field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProduct

`func (o *IntelligenceTaskCreateRequest) SetProduct(v IntelligenceTaskProduct)`

SetProduct sets Product field to given value.

### HasProduct

`func (o *IntelligenceTaskCreateRequest) HasProduct() bool`

HasProduct returns a boolean if a field has been set.

### GetPromptIds

`func (o *IntelligenceTaskCreateRequest) GetPromptIds() []int32`

GetPromptIds returns the PromptIds field if non-nil, zero value otherwise.

### GetPromptIdsOk

`func (o *IntelligenceTaskCreateRequest) GetPromptIdsOk() (*[]int32, bool)`

GetPromptIdsOk returns a tuple with the PromptIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPromptIds

`func (o *IntelligenceTaskCreateRequest) SetPromptIds(v []int32)`

SetPromptIds sets PromptIds field to given value.

### HasPromptIds

`func (o *IntelligenceTaskCreateRequest) HasPromptIds() bool`

HasPromptIds returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


