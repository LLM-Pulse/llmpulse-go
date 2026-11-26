# ProjectDraftSuggestions

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Step** | Pointer to **string** | The step the suggestions are for (details, prompts or competitors) | [optional] 
**Status** | **string** | ready, none (not requested, or nothing cached yet) or failed | 
**Details** | Pointer to [**ProjectDraftSuggestionsDetails**](ProjectDraftSuggestionsDetails.md) |  | [optional] 
**Prompts** | Pointer to **[]string** |  | [optional] 
**Competitors** | Pointer to [**[]ProjectDraftSuggestionsCompetitorsInner**](ProjectDraftSuggestionsCompetitorsInner.md) |  | [optional] 

## Methods

### NewProjectDraftSuggestions

`func NewProjectDraftSuggestions(status string, ) *ProjectDraftSuggestions`

NewProjectDraftSuggestions instantiates a new ProjectDraftSuggestions object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProjectDraftSuggestionsWithDefaults

`func NewProjectDraftSuggestionsWithDefaults() *ProjectDraftSuggestions`

NewProjectDraftSuggestionsWithDefaults instantiates a new ProjectDraftSuggestions object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetStep

`func (o *ProjectDraftSuggestions) GetStep() string`

GetStep returns the Step field if non-nil, zero value otherwise.

### GetStepOk

`func (o *ProjectDraftSuggestions) GetStepOk() (*string, bool)`

GetStepOk returns a tuple with the Step field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStep

`func (o *ProjectDraftSuggestions) SetStep(v string)`

SetStep sets Step field to given value.

### HasStep

`func (o *ProjectDraftSuggestions) HasStep() bool`

HasStep returns a boolean if a field has been set.

### GetStatus

`func (o *ProjectDraftSuggestions) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *ProjectDraftSuggestions) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *ProjectDraftSuggestions) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetDetails

`func (o *ProjectDraftSuggestions) GetDetails() ProjectDraftSuggestionsDetails`

GetDetails returns the Details field if non-nil, zero value otherwise.

### GetDetailsOk

`func (o *ProjectDraftSuggestions) GetDetailsOk() (*ProjectDraftSuggestionsDetails, bool)`

GetDetailsOk returns a tuple with the Details field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDetails

`func (o *ProjectDraftSuggestions) SetDetails(v ProjectDraftSuggestionsDetails)`

SetDetails sets Details field to given value.

### HasDetails

`func (o *ProjectDraftSuggestions) HasDetails() bool`

HasDetails returns a boolean if a field has been set.

### GetPrompts

`func (o *ProjectDraftSuggestions) GetPrompts() []string`

GetPrompts returns the Prompts field if non-nil, zero value otherwise.

### GetPromptsOk

`func (o *ProjectDraftSuggestions) GetPromptsOk() (*[]string, bool)`

GetPromptsOk returns a tuple with the Prompts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrompts

`func (o *ProjectDraftSuggestions) SetPrompts(v []string)`

SetPrompts sets Prompts field to given value.

### HasPrompts

`func (o *ProjectDraftSuggestions) HasPrompts() bool`

HasPrompts returns a boolean if a field has been set.

### GetCompetitors

`func (o *ProjectDraftSuggestions) GetCompetitors() []ProjectDraftSuggestionsCompetitorsInner`

GetCompetitors returns the Competitors field if non-nil, zero value otherwise.

### GetCompetitorsOk

`func (o *ProjectDraftSuggestions) GetCompetitorsOk() (*[]ProjectDraftSuggestionsCompetitorsInner, bool)`

GetCompetitorsOk returns a tuple with the Competitors field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompetitors

`func (o *ProjectDraftSuggestions) SetCompetitors(v []ProjectDraftSuggestionsCompetitorsInner)`

SetCompetitors sets Competitors field to given value.

### HasCompetitors

`func (o *ProjectDraftSuggestions) HasCompetitors() bool`

HasCompetitors returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


