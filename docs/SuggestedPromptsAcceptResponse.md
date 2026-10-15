# SuggestedPromptsAcceptResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ProjectId** | **int32** |  | 
**Accepted** | [**[]SuggestedPromptsAcceptResponseAcceptedInner**](SuggestedPromptsAcceptResponseAcceptedInner.md) |  | 
**Skipped** | [**[]CatalogPromptSuggestionsAcceptResponseSkippedInner**](CatalogPromptSuggestionsAcceptResponseSkippedInner.md) |  | 
**PromptsAvailable** | **NullableInt32** | Prompt slots left on the plan; null when unlimited | 
**RequestId** | **string** |  | 

## Methods

### NewSuggestedPromptsAcceptResponse

`func NewSuggestedPromptsAcceptResponse(projectId int32, accepted []SuggestedPromptsAcceptResponseAcceptedInner, skipped []CatalogPromptSuggestionsAcceptResponseSkippedInner, promptsAvailable NullableInt32, requestId string, ) *SuggestedPromptsAcceptResponse`

NewSuggestedPromptsAcceptResponse instantiates a new SuggestedPromptsAcceptResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSuggestedPromptsAcceptResponseWithDefaults

`func NewSuggestedPromptsAcceptResponseWithDefaults() *SuggestedPromptsAcceptResponse`

NewSuggestedPromptsAcceptResponseWithDefaults instantiates a new SuggestedPromptsAcceptResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProjectId

`func (o *SuggestedPromptsAcceptResponse) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *SuggestedPromptsAcceptResponse) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *SuggestedPromptsAcceptResponse) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.


### GetAccepted

`func (o *SuggestedPromptsAcceptResponse) GetAccepted() []SuggestedPromptsAcceptResponseAcceptedInner`

GetAccepted returns the Accepted field if non-nil, zero value otherwise.

### GetAcceptedOk

`func (o *SuggestedPromptsAcceptResponse) GetAcceptedOk() (*[]SuggestedPromptsAcceptResponseAcceptedInner, bool)`

GetAcceptedOk returns a tuple with the Accepted field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccepted

`func (o *SuggestedPromptsAcceptResponse) SetAccepted(v []SuggestedPromptsAcceptResponseAcceptedInner)`

SetAccepted sets Accepted field to given value.


### GetSkipped

`func (o *SuggestedPromptsAcceptResponse) GetSkipped() []CatalogPromptSuggestionsAcceptResponseSkippedInner`

GetSkipped returns the Skipped field if non-nil, zero value otherwise.

### GetSkippedOk

`func (o *SuggestedPromptsAcceptResponse) GetSkippedOk() (*[]CatalogPromptSuggestionsAcceptResponseSkippedInner, bool)`

GetSkippedOk returns a tuple with the Skipped field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSkipped

`func (o *SuggestedPromptsAcceptResponse) SetSkipped(v []CatalogPromptSuggestionsAcceptResponseSkippedInner)`

SetSkipped sets Skipped field to given value.


### GetPromptsAvailable

`func (o *SuggestedPromptsAcceptResponse) GetPromptsAvailable() int32`

GetPromptsAvailable returns the PromptsAvailable field if non-nil, zero value otherwise.

### GetPromptsAvailableOk

`func (o *SuggestedPromptsAcceptResponse) GetPromptsAvailableOk() (*int32, bool)`

GetPromptsAvailableOk returns a tuple with the PromptsAvailable field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPromptsAvailable

`func (o *SuggestedPromptsAcceptResponse) SetPromptsAvailable(v int32)`

SetPromptsAvailable sets PromptsAvailable field to given value.


### SetPromptsAvailableNil

`func (o *SuggestedPromptsAcceptResponse) SetPromptsAvailableNil(b bool)`

 SetPromptsAvailableNil sets the value for PromptsAvailable to be an explicit nil

### UnsetPromptsAvailable
`func (o *SuggestedPromptsAcceptResponse) UnsetPromptsAvailable()`

UnsetPromptsAvailable ensures that no value is present for PromptsAvailable, not even an explicit nil
### GetRequestId

`func (o *SuggestedPromptsAcceptResponse) GetRequestId() string`

GetRequestId returns the RequestId field if non-nil, zero value otherwise.

### GetRequestIdOk

`func (o *SuggestedPromptsAcceptResponse) GetRequestIdOk() (*string, bool)`

GetRequestIdOk returns a tuple with the RequestId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestId

`func (o *SuggestedPromptsAcceptResponse) SetRequestId(v string)`

SetRequestId sets RequestId field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


