# PromptDeleteResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ProjectId** | **int32** |  | 
**Deleted** | **bool** | Always true | 
**Id** | **int32** |  | 
**RawInput** | **string** |  | 
**TotalAfter** | **int32** | Prompts left in the project | 
**RequestId** | **string** |  | 

## Methods

### NewPromptDeleteResponse

`func NewPromptDeleteResponse(projectId int32, deleted bool, id int32, rawInput string, totalAfter int32, requestId string, ) *PromptDeleteResponse`

NewPromptDeleteResponse instantiates a new PromptDeleteResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPromptDeleteResponseWithDefaults

`func NewPromptDeleteResponseWithDefaults() *PromptDeleteResponse`

NewPromptDeleteResponseWithDefaults instantiates a new PromptDeleteResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProjectId

`func (o *PromptDeleteResponse) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *PromptDeleteResponse) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *PromptDeleteResponse) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.


### GetDeleted

`func (o *PromptDeleteResponse) GetDeleted() bool`

GetDeleted returns the Deleted field if non-nil, zero value otherwise.

### GetDeletedOk

`func (o *PromptDeleteResponse) GetDeletedOk() (*bool, bool)`

GetDeletedOk returns a tuple with the Deleted field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeleted

`func (o *PromptDeleteResponse) SetDeleted(v bool)`

SetDeleted sets Deleted field to given value.


### GetId

`func (o *PromptDeleteResponse) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *PromptDeleteResponse) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *PromptDeleteResponse) SetId(v int32)`

SetId sets Id field to given value.


### GetRawInput

`func (o *PromptDeleteResponse) GetRawInput() string`

GetRawInput returns the RawInput field if non-nil, zero value otherwise.

### GetRawInputOk

`func (o *PromptDeleteResponse) GetRawInputOk() (*string, bool)`

GetRawInputOk returns a tuple with the RawInput field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRawInput

`func (o *PromptDeleteResponse) SetRawInput(v string)`

SetRawInput sets RawInput field to given value.


### GetTotalAfter

`func (o *PromptDeleteResponse) GetTotalAfter() int32`

GetTotalAfter returns the TotalAfter field if non-nil, zero value otherwise.

### GetTotalAfterOk

`func (o *PromptDeleteResponse) GetTotalAfterOk() (*int32, bool)`

GetTotalAfterOk returns a tuple with the TotalAfter field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalAfter

`func (o *PromptDeleteResponse) SetTotalAfter(v int32)`

SetTotalAfter sets TotalAfter field to given value.


### GetRequestId

`func (o *PromptDeleteResponse) GetRequestId() string`

GetRequestId returns the RequestId field if non-nil, zero value otherwise.

### GetRequestIdOk

`func (o *PromptDeleteResponse) GetRequestIdOk() (*string, bool)`

GetRequestIdOk returns a tuple with the RequestId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestId

`func (o *PromptDeleteResponse) SetRequestId(v string)`

SetRequestId sets RequestId field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


