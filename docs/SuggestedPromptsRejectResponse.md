# SuggestedPromptsRejectResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ProjectId** | **int32** |  | 
**Rejected** | **int32** |  | 
**Ids** | **[]int32** | The suggestions that were pending and are now rejected | 
**RequestId** | **string** |  | 

## Methods

### NewSuggestedPromptsRejectResponse

`func NewSuggestedPromptsRejectResponse(projectId int32, rejected int32, ids []int32, requestId string, ) *SuggestedPromptsRejectResponse`

NewSuggestedPromptsRejectResponse instantiates a new SuggestedPromptsRejectResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSuggestedPromptsRejectResponseWithDefaults

`func NewSuggestedPromptsRejectResponseWithDefaults() *SuggestedPromptsRejectResponse`

NewSuggestedPromptsRejectResponseWithDefaults instantiates a new SuggestedPromptsRejectResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProjectId

`func (o *SuggestedPromptsRejectResponse) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *SuggestedPromptsRejectResponse) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *SuggestedPromptsRejectResponse) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.


### GetRejected

`func (o *SuggestedPromptsRejectResponse) GetRejected() int32`

GetRejected returns the Rejected field if non-nil, zero value otherwise.

### GetRejectedOk

`func (o *SuggestedPromptsRejectResponse) GetRejectedOk() (*int32, bool)`

GetRejectedOk returns a tuple with the Rejected field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRejected

`func (o *SuggestedPromptsRejectResponse) SetRejected(v int32)`

SetRejected sets Rejected field to given value.


### GetIds

`func (o *SuggestedPromptsRejectResponse) GetIds() []int32`

GetIds returns the Ids field if non-nil, zero value otherwise.

### GetIdsOk

`func (o *SuggestedPromptsRejectResponse) GetIdsOk() (*[]int32, bool)`

GetIdsOk returns a tuple with the Ids field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIds

`func (o *SuggestedPromptsRejectResponse) SetIds(v []int32)`

SetIds sets Ids field to given value.


### GetRequestId

`func (o *SuggestedPromptsRejectResponse) GetRequestId() string`

GetRequestId returns the RequestId field if non-nil, zero value otherwise.

### GetRequestIdOk

`func (o *SuggestedPromptsRejectResponse) GetRequestIdOk() (*string, bool)`

GetRequestIdOk returns a tuple with the RequestId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestId

`func (o *SuggestedPromptsRejectResponse) SetRequestId(v string)`

SetRequestId sets RequestId field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


