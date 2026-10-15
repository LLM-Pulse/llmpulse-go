# SuggestedPromptIdsRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ProjectId** | **int32** |  | 
**Ids** | **[]int32** | Suggestion ids (max 100) | 

## Methods

### NewSuggestedPromptIdsRequest

`func NewSuggestedPromptIdsRequest(projectId int32, ids []int32, ) *SuggestedPromptIdsRequest`

NewSuggestedPromptIdsRequest instantiates a new SuggestedPromptIdsRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSuggestedPromptIdsRequestWithDefaults

`func NewSuggestedPromptIdsRequestWithDefaults() *SuggestedPromptIdsRequest`

NewSuggestedPromptIdsRequestWithDefaults instantiates a new SuggestedPromptIdsRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProjectId

`func (o *SuggestedPromptIdsRequest) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *SuggestedPromptIdsRequest) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *SuggestedPromptIdsRequest) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.


### GetIds

`func (o *SuggestedPromptIdsRequest) GetIds() []int32`

GetIds returns the Ids field if non-nil, zero value otherwise.

### GetIdsOk

`func (o *SuggestedPromptIdsRequest) GetIdsOk() (*[]int32, bool)`

GetIdsOk returns a tuple with the Ids field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIds

`func (o *SuggestedPromptIdsRequest) SetIds(v []int32)`

SetIds sets Ids field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


