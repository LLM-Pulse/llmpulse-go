# AssignPromptTagsRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ProjectId** | **int32** |  | 
**PromptIds** | **[]int32** |  | 
**TagIds** | Pointer to **[]int32** |  | [optional] 
**TagNames** | Pointer to **[]string** |  | [optional] 
**CreateMissing** | Pointer to **bool** |  | [optional] 

## Methods

### NewAssignPromptTagsRequest

`func NewAssignPromptTagsRequest(projectId int32, promptIds []int32, ) *AssignPromptTagsRequest`

NewAssignPromptTagsRequest instantiates a new AssignPromptTagsRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAssignPromptTagsRequestWithDefaults

`func NewAssignPromptTagsRequestWithDefaults() *AssignPromptTagsRequest`

NewAssignPromptTagsRequestWithDefaults instantiates a new AssignPromptTagsRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProjectId

`func (o *AssignPromptTagsRequest) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *AssignPromptTagsRequest) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *AssignPromptTagsRequest) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.


### GetPromptIds

`func (o *AssignPromptTagsRequest) GetPromptIds() []int32`

GetPromptIds returns the PromptIds field if non-nil, zero value otherwise.

### GetPromptIdsOk

`func (o *AssignPromptTagsRequest) GetPromptIdsOk() (*[]int32, bool)`

GetPromptIdsOk returns a tuple with the PromptIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPromptIds

`func (o *AssignPromptTagsRequest) SetPromptIds(v []int32)`

SetPromptIds sets PromptIds field to given value.


### GetTagIds

`func (o *AssignPromptTagsRequest) GetTagIds() []int32`

GetTagIds returns the TagIds field if non-nil, zero value otherwise.

### GetTagIdsOk

`func (o *AssignPromptTagsRequest) GetTagIdsOk() (*[]int32, bool)`

GetTagIdsOk returns a tuple with the TagIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTagIds

`func (o *AssignPromptTagsRequest) SetTagIds(v []int32)`

SetTagIds sets TagIds field to given value.

### HasTagIds

`func (o *AssignPromptTagsRequest) HasTagIds() bool`

HasTagIds returns a boolean if a field has been set.

### GetTagNames

`func (o *AssignPromptTagsRequest) GetTagNames() []string`

GetTagNames returns the TagNames field if non-nil, zero value otherwise.

### GetTagNamesOk

`func (o *AssignPromptTagsRequest) GetTagNamesOk() (*[]string, bool)`

GetTagNamesOk returns a tuple with the TagNames field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTagNames

`func (o *AssignPromptTagsRequest) SetTagNames(v []string)`

SetTagNames sets TagNames field to given value.

### HasTagNames

`func (o *AssignPromptTagsRequest) HasTagNames() bool`

HasTagNames returns a boolean if a field has been set.

### GetCreateMissing

`func (o *AssignPromptTagsRequest) GetCreateMissing() bool`

GetCreateMissing returns the CreateMissing field if non-nil, zero value otherwise.

### GetCreateMissingOk

`func (o *AssignPromptTagsRequest) GetCreateMissingOk() (*bool, bool)`

GetCreateMissingOk returns a tuple with the CreateMissing field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreateMissing

`func (o *AssignPromptTagsRequest) SetCreateMissing(v bool)`

SetCreateMissing sets CreateMissing field to given value.

### HasCreateMissing

`func (o *AssignPromptTagsRequest) HasCreateMissing() bool`

HasCreateMissing returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


