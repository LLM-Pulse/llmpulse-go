# PromptCategorizationResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ProjectId** | **int32** |  | 
**Prompt** | [**PromptCategorization**](PromptCategorization.md) |  | 
**RequestId** | **string** |  | 

## Methods

### NewPromptCategorizationResponse

`func NewPromptCategorizationResponse(projectId int32, prompt PromptCategorization, requestId string, ) *PromptCategorizationResponse`

NewPromptCategorizationResponse instantiates a new PromptCategorizationResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPromptCategorizationResponseWithDefaults

`func NewPromptCategorizationResponseWithDefaults() *PromptCategorizationResponse`

NewPromptCategorizationResponseWithDefaults instantiates a new PromptCategorizationResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProjectId

`func (o *PromptCategorizationResponse) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *PromptCategorizationResponse) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *PromptCategorizationResponse) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.


### GetPrompt

`func (o *PromptCategorizationResponse) GetPrompt() PromptCategorization`

GetPrompt returns the Prompt field if non-nil, zero value otherwise.

### GetPromptOk

`func (o *PromptCategorizationResponse) GetPromptOk() (*PromptCategorization, bool)`

GetPromptOk returns a tuple with the Prompt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrompt

`func (o *PromptCategorizationResponse) SetPrompt(v PromptCategorization)`

SetPrompt sets Prompt field to given value.


### GetRequestId

`func (o *PromptCategorizationResponse) GetRequestId() string`

GetRequestId returns the RequestId field if non-nil, zero value otherwise.

### GetRequestIdOk

`func (o *PromptCategorizationResponse) GetRequestIdOk() (*string, bool)`

GetRequestIdOk returns a tuple with the RequestId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestId

`func (o *PromptCategorizationResponse) SetRequestId(v string)`

SetRequestId sets RequestId field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


