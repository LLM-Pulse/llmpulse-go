# ProjectDraftResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Draft** | [**ProjectDraftRecord**](ProjectDraftRecord.md) |  | 
**Suggestions** | [**ProjectDraftSuggestions**](ProjectDraftSuggestions.md) |  | 
**Limits** | [**ProjectDraftResponseLimits**](ProjectDraftResponseLimits.md) |  | 
**RequestId** | **string** |  | 

## Methods

### NewProjectDraftResponse

`func NewProjectDraftResponse(draft ProjectDraftRecord, suggestions ProjectDraftSuggestions, limits ProjectDraftResponseLimits, requestId string, ) *ProjectDraftResponse`

NewProjectDraftResponse instantiates a new ProjectDraftResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProjectDraftResponseWithDefaults

`func NewProjectDraftResponseWithDefaults() *ProjectDraftResponse`

NewProjectDraftResponseWithDefaults instantiates a new ProjectDraftResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDraft

`func (o *ProjectDraftResponse) GetDraft() ProjectDraftRecord`

GetDraft returns the Draft field if non-nil, zero value otherwise.

### GetDraftOk

`func (o *ProjectDraftResponse) GetDraftOk() (*ProjectDraftRecord, bool)`

GetDraftOk returns a tuple with the Draft field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDraft

`func (o *ProjectDraftResponse) SetDraft(v ProjectDraftRecord)`

SetDraft sets Draft field to given value.


### GetSuggestions

`func (o *ProjectDraftResponse) GetSuggestions() ProjectDraftSuggestions`

GetSuggestions returns the Suggestions field if non-nil, zero value otherwise.

### GetSuggestionsOk

`func (o *ProjectDraftResponse) GetSuggestionsOk() (*ProjectDraftSuggestions, bool)`

GetSuggestionsOk returns a tuple with the Suggestions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuggestions

`func (o *ProjectDraftResponse) SetSuggestions(v ProjectDraftSuggestions)`

SetSuggestions sets Suggestions field to given value.


### GetLimits

`func (o *ProjectDraftResponse) GetLimits() ProjectDraftResponseLimits`

GetLimits returns the Limits field if non-nil, zero value otherwise.

### GetLimitsOk

`func (o *ProjectDraftResponse) GetLimitsOk() (*ProjectDraftResponseLimits, bool)`

GetLimitsOk returns a tuple with the Limits field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLimits

`func (o *ProjectDraftResponse) SetLimits(v ProjectDraftResponseLimits)`

SetLimits sets Limits field to given value.


### GetRequestId

`func (o *ProjectDraftResponse) GetRequestId() string`

GetRequestId returns the RequestId field if non-nil, zero value otherwise.

### GetRequestIdOk

`func (o *ProjectDraftResponse) GetRequestIdOk() (*string, bool)`

GetRequestIdOk returns a tuple with the RequestId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestId

`func (o *ProjectDraftResponse) SetRequestId(v string)`

SetRequestId sets RequestId field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


