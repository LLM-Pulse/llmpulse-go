# SuggestedPromptsAcceptRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ProjectId** | **int32** |  | 
**Ids** | **[]int32** | Suggestion ids to accept (max 100) | 
**TagIds** | Pointer to **[]int32** | One tag id to put the new prompts in | [optional] 
**TagNames** | Pointer to **[]string** | One tag name (case-insensitive) to put the new prompts in | [optional] 
**CreateMissing** | Pointer to **bool** | Create the tag named in tag_names when it does not exist | [optional] [default to false]

## Methods

### NewSuggestedPromptsAcceptRequest

`func NewSuggestedPromptsAcceptRequest(projectId int32, ids []int32, ) *SuggestedPromptsAcceptRequest`

NewSuggestedPromptsAcceptRequest instantiates a new SuggestedPromptsAcceptRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSuggestedPromptsAcceptRequestWithDefaults

`func NewSuggestedPromptsAcceptRequestWithDefaults() *SuggestedPromptsAcceptRequest`

NewSuggestedPromptsAcceptRequestWithDefaults instantiates a new SuggestedPromptsAcceptRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProjectId

`func (o *SuggestedPromptsAcceptRequest) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *SuggestedPromptsAcceptRequest) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *SuggestedPromptsAcceptRequest) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.


### GetIds

`func (o *SuggestedPromptsAcceptRequest) GetIds() []int32`

GetIds returns the Ids field if non-nil, zero value otherwise.

### GetIdsOk

`func (o *SuggestedPromptsAcceptRequest) GetIdsOk() (*[]int32, bool)`

GetIdsOk returns a tuple with the Ids field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIds

`func (o *SuggestedPromptsAcceptRequest) SetIds(v []int32)`

SetIds sets Ids field to given value.


### GetTagIds

`func (o *SuggestedPromptsAcceptRequest) GetTagIds() []int32`

GetTagIds returns the TagIds field if non-nil, zero value otherwise.

### GetTagIdsOk

`func (o *SuggestedPromptsAcceptRequest) GetTagIdsOk() (*[]int32, bool)`

GetTagIdsOk returns a tuple with the TagIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTagIds

`func (o *SuggestedPromptsAcceptRequest) SetTagIds(v []int32)`

SetTagIds sets TagIds field to given value.

### HasTagIds

`func (o *SuggestedPromptsAcceptRequest) HasTagIds() bool`

HasTagIds returns a boolean if a field has been set.

### GetTagNames

`func (o *SuggestedPromptsAcceptRequest) GetTagNames() []string`

GetTagNames returns the TagNames field if non-nil, zero value otherwise.

### GetTagNamesOk

`func (o *SuggestedPromptsAcceptRequest) GetTagNamesOk() (*[]string, bool)`

GetTagNamesOk returns a tuple with the TagNames field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTagNames

`func (o *SuggestedPromptsAcceptRequest) SetTagNames(v []string)`

SetTagNames sets TagNames field to given value.

### HasTagNames

`func (o *SuggestedPromptsAcceptRequest) HasTagNames() bool`

HasTagNames returns a boolean if a field has been set.

### GetCreateMissing

`func (o *SuggestedPromptsAcceptRequest) GetCreateMissing() bool`

GetCreateMissing returns the CreateMissing field if non-nil, zero value otherwise.

### GetCreateMissingOk

`func (o *SuggestedPromptsAcceptRequest) GetCreateMissingOk() (*bool, bool)`

GetCreateMissingOk returns a tuple with the CreateMissing field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreateMissing

`func (o *SuggestedPromptsAcceptRequest) SetCreateMissing(v bool)`

SetCreateMissing sets CreateMissing field to given value.

### HasCreateMissing

`func (o *SuggestedPromptsAcceptRequest) HasCreateMissing() bool`

HasCreateMissing returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


