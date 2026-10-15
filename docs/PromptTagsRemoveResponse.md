# PromptTagsRemoveResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ProjectId** | **int32** |  | 
**PromptsTargeted** | **int32** | Prompts of the project among prompt_ids | 
**TagsDetached** | [**[]TagRef**](TagRef.md) |  | 
**LinksRemoved** | **int32** |  | 
**SkippedNotLinked** | **int32** |  | 
**MissingTagNames** | **[]string** | tag_names that matched no tag | 
**IgnoredPromptIds** | **[]int32** | prompt_ids that are not prompts of this project | 
**RequestId** | **string** |  | 

## Methods

### NewPromptTagsRemoveResponse

`func NewPromptTagsRemoveResponse(projectId int32, promptsTargeted int32, tagsDetached []TagRef, linksRemoved int32, skippedNotLinked int32, missingTagNames []string, ignoredPromptIds []int32, requestId string, ) *PromptTagsRemoveResponse`

NewPromptTagsRemoveResponse instantiates a new PromptTagsRemoveResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPromptTagsRemoveResponseWithDefaults

`func NewPromptTagsRemoveResponseWithDefaults() *PromptTagsRemoveResponse`

NewPromptTagsRemoveResponseWithDefaults instantiates a new PromptTagsRemoveResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProjectId

`func (o *PromptTagsRemoveResponse) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *PromptTagsRemoveResponse) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *PromptTagsRemoveResponse) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.


### GetPromptsTargeted

`func (o *PromptTagsRemoveResponse) GetPromptsTargeted() int32`

GetPromptsTargeted returns the PromptsTargeted field if non-nil, zero value otherwise.

### GetPromptsTargetedOk

`func (o *PromptTagsRemoveResponse) GetPromptsTargetedOk() (*int32, bool)`

GetPromptsTargetedOk returns a tuple with the PromptsTargeted field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPromptsTargeted

`func (o *PromptTagsRemoveResponse) SetPromptsTargeted(v int32)`

SetPromptsTargeted sets PromptsTargeted field to given value.


### GetTagsDetached

`func (o *PromptTagsRemoveResponse) GetTagsDetached() []TagRef`

GetTagsDetached returns the TagsDetached field if non-nil, zero value otherwise.

### GetTagsDetachedOk

`func (o *PromptTagsRemoveResponse) GetTagsDetachedOk() (*[]TagRef, bool)`

GetTagsDetachedOk returns a tuple with the TagsDetached field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTagsDetached

`func (o *PromptTagsRemoveResponse) SetTagsDetached(v []TagRef)`

SetTagsDetached sets TagsDetached field to given value.


### GetLinksRemoved

`func (o *PromptTagsRemoveResponse) GetLinksRemoved() int32`

GetLinksRemoved returns the LinksRemoved field if non-nil, zero value otherwise.

### GetLinksRemovedOk

`func (o *PromptTagsRemoveResponse) GetLinksRemovedOk() (*int32, bool)`

GetLinksRemovedOk returns a tuple with the LinksRemoved field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLinksRemoved

`func (o *PromptTagsRemoveResponse) SetLinksRemoved(v int32)`

SetLinksRemoved sets LinksRemoved field to given value.


### GetSkippedNotLinked

`func (o *PromptTagsRemoveResponse) GetSkippedNotLinked() int32`

GetSkippedNotLinked returns the SkippedNotLinked field if non-nil, zero value otherwise.

### GetSkippedNotLinkedOk

`func (o *PromptTagsRemoveResponse) GetSkippedNotLinkedOk() (*int32, bool)`

GetSkippedNotLinkedOk returns a tuple with the SkippedNotLinked field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSkippedNotLinked

`func (o *PromptTagsRemoveResponse) SetSkippedNotLinked(v int32)`

SetSkippedNotLinked sets SkippedNotLinked field to given value.


### GetMissingTagNames

`func (o *PromptTagsRemoveResponse) GetMissingTagNames() []string`

GetMissingTagNames returns the MissingTagNames field if non-nil, zero value otherwise.

### GetMissingTagNamesOk

`func (o *PromptTagsRemoveResponse) GetMissingTagNamesOk() (*[]string, bool)`

GetMissingTagNamesOk returns a tuple with the MissingTagNames field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMissingTagNames

`func (o *PromptTagsRemoveResponse) SetMissingTagNames(v []string)`

SetMissingTagNames sets MissingTagNames field to given value.


### GetIgnoredPromptIds

`func (o *PromptTagsRemoveResponse) GetIgnoredPromptIds() []int32`

GetIgnoredPromptIds returns the IgnoredPromptIds field if non-nil, zero value otherwise.

### GetIgnoredPromptIdsOk

`func (o *PromptTagsRemoveResponse) GetIgnoredPromptIdsOk() (*[]int32, bool)`

GetIgnoredPromptIdsOk returns a tuple with the IgnoredPromptIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIgnoredPromptIds

`func (o *PromptTagsRemoveResponse) SetIgnoredPromptIds(v []int32)`

SetIgnoredPromptIds sets IgnoredPromptIds field to given value.


### GetRequestId

`func (o *PromptTagsRemoveResponse) GetRequestId() string`

GetRequestId returns the RequestId field if non-nil, zero value otherwise.

### GetRequestIdOk

`func (o *PromptTagsRemoveResponse) GetRequestIdOk() (*string, bool)`

GetRequestIdOk returns a tuple with the RequestId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestId

`func (o *PromptTagsRemoveResponse) SetRequestId(v string)`

SetRequestId sets RequestId field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


