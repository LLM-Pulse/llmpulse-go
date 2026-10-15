# PromptGenerationResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** | The run id; poll GET /prompt_generations/{id} with it (kept for 24 hours) | 
**ProjectId** | **int32** |  | 
**Source** | **string** |  | 
**Status** | **string** |  | 
**Params** | [**PromptGenerationResponseParams**](PromptGenerationResponseParams.md) |  | 
**CreatedAt** | **time.Time** |  | 
**FinishedAt** | **NullableTime** |  | 
**SuggestionsCount** | **int32** |  | 
**Suggestions** | [**[]SuggestedPrompt**](SuggestedPrompt.md) | The suggestions the run saved to the Suggested prompts queue, with their current status | 
**Error** | [**NullablePromptGenerationResponseError**](PromptGenerationResponseError.md) |  | 
**RequestId** | **string** |  | 

## Methods

### NewPromptGenerationResponse

`func NewPromptGenerationResponse(id string, projectId int32, source string, status string, params PromptGenerationResponseParams, createdAt time.Time, finishedAt NullableTime, suggestionsCount int32, suggestions []SuggestedPrompt, error_ NullablePromptGenerationResponseError, requestId string, ) *PromptGenerationResponse`

NewPromptGenerationResponse instantiates a new PromptGenerationResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPromptGenerationResponseWithDefaults

`func NewPromptGenerationResponseWithDefaults() *PromptGenerationResponse`

NewPromptGenerationResponseWithDefaults instantiates a new PromptGenerationResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *PromptGenerationResponse) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *PromptGenerationResponse) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *PromptGenerationResponse) SetId(v string)`

SetId sets Id field to given value.


### GetProjectId

`func (o *PromptGenerationResponse) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *PromptGenerationResponse) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *PromptGenerationResponse) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.


### GetSource

`func (o *PromptGenerationResponse) GetSource() string`

GetSource returns the Source field if non-nil, zero value otherwise.

### GetSourceOk

`func (o *PromptGenerationResponse) GetSourceOk() (*string, bool)`

GetSourceOk returns a tuple with the Source field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSource

`func (o *PromptGenerationResponse) SetSource(v string)`

SetSource sets Source field to given value.


### GetStatus

`func (o *PromptGenerationResponse) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *PromptGenerationResponse) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *PromptGenerationResponse) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetParams

`func (o *PromptGenerationResponse) GetParams() PromptGenerationResponseParams`

GetParams returns the Params field if non-nil, zero value otherwise.

### GetParamsOk

`func (o *PromptGenerationResponse) GetParamsOk() (*PromptGenerationResponseParams, bool)`

GetParamsOk returns a tuple with the Params field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParams

`func (o *PromptGenerationResponse) SetParams(v PromptGenerationResponseParams)`

SetParams sets Params field to given value.


### GetCreatedAt

`func (o *PromptGenerationResponse) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *PromptGenerationResponse) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *PromptGenerationResponse) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetFinishedAt

`func (o *PromptGenerationResponse) GetFinishedAt() time.Time`

GetFinishedAt returns the FinishedAt field if non-nil, zero value otherwise.

### GetFinishedAtOk

`func (o *PromptGenerationResponse) GetFinishedAtOk() (*time.Time, bool)`

GetFinishedAtOk returns a tuple with the FinishedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFinishedAt

`func (o *PromptGenerationResponse) SetFinishedAt(v time.Time)`

SetFinishedAt sets FinishedAt field to given value.


### SetFinishedAtNil

`func (o *PromptGenerationResponse) SetFinishedAtNil(b bool)`

 SetFinishedAtNil sets the value for FinishedAt to be an explicit nil

### UnsetFinishedAt
`func (o *PromptGenerationResponse) UnsetFinishedAt()`

UnsetFinishedAt ensures that no value is present for FinishedAt, not even an explicit nil
### GetSuggestionsCount

`func (o *PromptGenerationResponse) GetSuggestionsCount() int32`

GetSuggestionsCount returns the SuggestionsCount field if non-nil, zero value otherwise.

### GetSuggestionsCountOk

`func (o *PromptGenerationResponse) GetSuggestionsCountOk() (*int32, bool)`

GetSuggestionsCountOk returns a tuple with the SuggestionsCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuggestionsCount

`func (o *PromptGenerationResponse) SetSuggestionsCount(v int32)`

SetSuggestionsCount sets SuggestionsCount field to given value.


### GetSuggestions

`func (o *PromptGenerationResponse) GetSuggestions() []SuggestedPrompt`

GetSuggestions returns the Suggestions field if non-nil, zero value otherwise.

### GetSuggestionsOk

`func (o *PromptGenerationResponse) GetSuggestionsOk() (*[]SuggestedPrompt, bool)`

GetSuggestionsOk returns a tuple with the Suggestions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuggestions

`func (o *PromptGenerationResponse) SetSuggestions(v []SuggestedPrompt)`

SetSuggestions sets Suggestions field to given value.


### GetError

`func (o *PromptGenerationResponse) GetError() PromptGenerationResponseError`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *PromptGenerationResponse) GetErrorOk() (*PromptGenerationResponseError, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *PromptGenerationResponse) SetError(v PromptGenerationResponseError)`

SetError sets Error field to given value.


### SetErrorNil

`func (o *PromptGenerationResponse) SetErrorNil(b bool)`

 SetErrorNil sets the value for Error to be an explicit nil

### UnsetError
`func (o *PromptGenerationResponse) UnsetError()`

UnsetError ensures that no value is present for Error, not even an explicit nil
### GetRequestId

`func (o *PromptGenerationResponse) GetRequestId() string`

GetRequestId returns the RequestId field if non-nil, zero value otherwise.

### GetRequestIdOk

`func (o *PromptGenerationResponse) GetRequestIdOk() (*string, bool)`

GetRequestIdOk returns a tuple with the RequestId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestId

`func (o *PromptGenerationResponse) SetRequestId(v string)`

SetRequestId sets RequestId field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


