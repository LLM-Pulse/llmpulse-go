# PromptTagsAssignResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ProjectId** | **int32** |  | 
**PromptsTargeted** | **int32** | Prompts of the project among prompt_ids | 
**TagsAttached** | [**[]TagRef**](TagRef.md) |  | 
**NewLinksCreated** | **int32** |  | 
**SkippedAlreadyLinked** | **int32** |  | 
**MissingTagNames** | **[]string** | tag_names that matched no tag and were not created | 
**IgnoredPromptIds** | **[]int32** | prompt_ids that are not prompts of this project | 
**RequestId** | **string** |  | 

## Methods

### NewPromptTagsAssignResponse

`func NewPromptTagsAssignResponse(projectId int32, promptsTargeted int32, tagsAttached []TagRef, newLinksCreated int32, skippedAlreadyLinked int32, missingTagNames []string, ignoredPromptIds []int32, requestId string, ) *PromptTagsAssignResponse`

NewPromptTagsAssignResponse instantiates a new PromptTagsAssignResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPromptTagsAssignResponseWithDefaults

`func NewPromptTagsAssignResponseWithDefaults() *PromptTagsAssignResponse`

NewPromptTagsAssignResponseWithDefaults instantiates a new PromptTagsAssignResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProjectId

`func (o *PromptTagsAssignResponse) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *PromptTagsAssignResponse) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *PromptTagsAssignResponse) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.


### GetPromptsTargeted

`func (o *PromptTagsAssignResponse) GetPromptsTargeted() int32`

GetPromptsTargeted returns the PromptsTargeted field if non-nil, zero value otherwise.

### GetPromptsTargetedOk

`func (o *PromptTagsAssignResponse) GetPromptsTargetedOk() (*int32, bool)`

GetPromptsTargetedOk returns a tuple with the PromptsTargeted field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPromptsTargeted

`func (o *PromptTagsAssignResponse) SetPromptsTargeted(v int32)`

SetPromptsTargeted sets PromptsTargeted field to given value.


### GetTagsAttached

`func (o *PromptTagsAssignResponse) GetTagsAttached() []TagRef`

GetTagsAttached returns the TagsAttached field if non-nil, zero value otherwise.

### GetTagsAttachedOk

`func (o *PromptTagsAssignResponse) GetTagsAttachedOk() (*[]TagRef, bool)`

GetTagsAttachedOk returns a tuple with the TagsAttached field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTagsAttached

`func (o *PromptTagsAssignResponse) SetTagsAttached(v []TagRef)`

SetTagsAttached sets TagsAttached field to given value.


### GetNewLinksCreated

`func (o *PromptTagsAssignResponse) GetNewLinksCreated() int32`

GetNewLinksCreated returns the NewLinksCreated field if non-nil, zero value otherwise.

### GetNewLinksCreatedOk

`func (o *PromptTagsAssignResponse) GetNewLinksCreatedOk() (*int32, bool)`

GetNewLinksCreatedOk returns a tuple with the NewLinksCreated field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNewLinksCreated

`func (o *PromptTagsAssignResponse) SetNewLinksCreated(v int32)`

SetNewLinksCreated sets NewLinksCreated field to given value.


### GetSkippedAlreadyLinked

`func (o *PromptTagsAssignResponse) GetSkippedAlreadyLinked() int32`

GetSkippedAlreadyLinked returns the SkippedAlreadyLinked field if non-nil, zero value otherwise.

### GetSkippedAlreadyLinkedOk

`func (o *PromptTagsAssignResponse) GetSkippedAlreadyLinkedOk() (*int32, bool)`

GetSkippedAlreadyLinkedOk returns a tuple with the SkippedAlreadyLinked field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSkippedAlreadyLinked

`func (o *PromptTagsAssignResponse) SetSkippedAlreadyLinked(v int32)`

SetSkippedAlreadyLinked sets SkippedAlreadyLinked field to given value.


### GetMissingTagNames

`func (o *PromptTagsAssignResponse) GetMissingTagNames() []string`

GetMissingTagNames returns the MissingTagNames field if non-nil, zero value otherwise.

### GetMissingTagNamesOk

`func (o *PromptTagsAssignResponse) GetMissingTagNamesOk() (*[]string, bool)`

GetMissingTagNamesOk returns a tuple with the MissingTagNames field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMissingTagNames

`func (o *PromptTagsAssignResponse) SetMissingTagNames(v []string)`

SetMissingTagNames sets MissingTagNames field to given value.


### GetIgnoredPromptIds

`func (o *PromptTagsAssignResponse) GetIgnoredPromptIds() []int32`

GetIgnoredPromptIds returns the IgnoredPromptIds field if non-nil, zero value otherwise.

### GetIgnoredPromptIdsOk

`func (o *PromptTagsAssignResponse) GetIgnoredPromptIdsOk() (*[]int32, bool)`

GetIgnoredPromptIdsOk returns a tuple with the IgnoredPromptIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIgnoredPromptIds

`func (o *PromptTagsAssignResponse) SetIgnoredPromptIds(v []int32)`

SetIgnoredPromptIds sets IgnoredPromptIds field to given value.


### GetRequestId

`func (o *PromptTagsAssignResponse) GetRequestId() string`

GetRequestId returns the RequestId field if non-nil, zero value otherwise.

### GetRequestIdOk

`func (o *PromptTagsAssignResponse) GetRequestIdOk() (*string, bool)`

GetRequestIdOk returns a tuple with the RequestId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestId

`func (o *PromptTagsAssignResponse) SetRequestId(v string)`

SetRequestId sets RequestId field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


