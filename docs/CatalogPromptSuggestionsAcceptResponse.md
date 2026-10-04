# CatalogPromptSuggestionsAcceptResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ProjectId** | **int32** |  | 
**Accepted** | [**[]CatalogPromptSuggestionsAcceptResponseAcceptedInner**](CatalogPromptSuggestionsAcceptResponseAcceptedInner.md) |  | 
**Skipped** | [**[]CatalogPromptSuggestionsAcceptResponseSkippedInner**](CatalogPromptSuggestionsAcceptResponseSkippedInner.md) |  | 
**PromptsAvailable** | **NullableInt32** | Prompt slots left on the plan; null when unlimited | 
**RequestId** | **string** |  | 

## Methods

### NewCatalogPromptSuggestionsAcceptResponse

`func NewCatalogPromptSuggestionsAcceptResponse(projectId int32, accepted []CatalogPromptSuggestionsAcceptResponseAcceptedInner, skipped []CatalogPromptSuggestionsAcceptResponseSkippedInner, promptsAvailable NullableInt32, requestId string, ) *CatalogPromptSuggestionsAcceptResponse`

NewCatalogPromptSuggestionsAcceptResponse instantiates a new CatalogPromptSuggestionsAcceptResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCatalogPromptSuggestionsAcceptResponseWithDefaults

`func NewCatalogPromptSuggestionsAcceptResponseWithDefaults() *CatalogPromptSuggestionsAcceptResponse`

NewCatalogPromptSuggestionsAcceptResponseWithDefaults instantiates a new CatalogPromptSuggestionsAcceptResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProjectId

`func (o *CatalogPromptSuggestionsAcceptResponse) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *CatalogPromptSuggestionsAcceptResponse) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *CatalogPromptSuggestionsAcceptResponse) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.


### GetAccepted

`func (o *CatalogPromptSuggestionsAcceptResponse) GetAccepted() []CatalogPromptSuggestionsAcceptResponseAcceptedInner`

GetAccepted returns the Accepted field if non-nil, zero value otherwise.

### GetAcceptedOk

`func (o *CatalogPromptSuggestionsAcceptResponse) GetAcceptedOk() (*[]CatalogPromptSuggestionsAcceptResponseAcceptedInner, bool)`

GetAcceptedOk returns a tuple with the Accepted field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccepted

`func (o *CatalogPromptSuggestionsAcceptResponse) SetAccepted(v []CatalogPromptSuggestionsAcceptResponseAcceptedInner)`

SetAccepted sets Accepted field to given value.


### GetSkipped

`func (o *CatalogPromptSuggestionsAcceptResponse) GetSkipped() []CatalogPromptSuggestionsAcceptResponseSkippedInner`

GetSkipped returns the Skipped field if non-nil, zero value otherwise.

### GetSkippedOk

`func (o *CatalogPromptSuggestionsAcceptResponse) GetSkippedOk() (*[]CatalogPromptSuggestionsAcceptResponseSkippedInner, bool)`

GetSkippedOk returns a tuple with the Skipped field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSkipped

`func (o *CatalogPromptSuggestionsAcceptResponse) SetSkipped(v []CatalogPromptSuggestionsAcceptResponseSkippedInner)`

SetSkipped sets Skipped field to given value.


### GetPromptsAvailable

`func (o *CatalogPromptSuggestionsAcceptResponse) GetPromptsAvailable() int32`

GetPromptsAvailable returns the PromptsAvailable field if non-nil, zero value otherwise.

### GetPromptsAvailableOk

`func (o *CatalogPromptSuggestionsAcceptResponse) GetPromptsAvailableOk() (*int32, bool)`

GetPromptsAvailableOk returns a tuple with the PromptsAvailable field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPromptsAvailable

`func (o *CatalogPromptSuggestionsAcceptResponse) SetPromptsAvailable(v int32)`

SetPromptsAvailable sets PromptsAvailable field to given value.


### SetPromptsAvailableNil

`func (o *CatalogPromptSuggestionsAcceptResponse) SetPromptsAvailableNil(b bool)`

 SetPromptsAvailableNil sets the value for PromptsAvailable to be an explicit nil

### UnsetPromptsAvailable
`func (o *CatalogPromptSuggestionsAcceptResponse) UnsetPromptsAvailable()`

UnsetPromptsAvailable ensures that no value is present for PromptsAvailable, not even an explicit nil
### GetRequestId

`func (o *CatalogPromptSuggestionsAcceptResponse) GetRequestId() string`

GetRequestId returns the RequestId field if non-nil, zero value otherwise.

### GetRequestIdOk

`func (o *CatalogPromptSuggestionsAcceptResponse) GetRequestIdOk() (*string, bool)`

GetRequestIdOk returns a tuple with the RequestId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestId

`func (o *CatalogPromptSuggestionsAcceptResponse) SetRequestId(v string)`

SetRequestId sets RequestId field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


