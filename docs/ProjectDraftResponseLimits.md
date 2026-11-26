# ProjectDraftResponseLimits

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**PromptsAvailable** | **NullableInt32** | Prompts the account can still add; null when unlimited | 
**MaxPromptsPerRequest** | **int32** |  | 
**MaxCompetitors** | **int32** | Competitors the plan allows per project | 

## Methods

### NewProjectDraftResponseLimits

`func NewProjectDraftResponseLimits(promptsAvailable NullableInt32, maxPromptsPerRequest int32, maxCompetitors int32, ) *ProjectDraftResponseLimits`

NewProjectDraftResponseLimits instantiates a new ProjectDraftResponseLimits object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProjectDraftResponseLimitsWithDefaults

`func NewProjectDraftResponseLimitsWithDefaults() *ProjectDraftResponseLimits`

NewProjectDraftResponseLimitsWithDefaults instantiates a new ProjectDraftResponseLimits object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPromptsAvailable

`func (o *ProjectDraftResponseLimits) GetPromptsAvailable() int32`

GetPromptsAvailable returns the PromptsAvailable field if non-nil, zero value otherwise.

### GetPromptsAvailableOk

`func (o *ProjectDraftResponseLimits) GetPromptsAvailableOk() (*int32, bool)`

GetPromptsAvailableOk returns a tuple with the PromptsAvailable field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPromptsAvailable

`func (o *ProjectDraftResponseLimits) SetPromptsAvailable(v int32)`

SetPromptsAvailable sets PromptsAvailable field to given value.


### SetPromptsAvailableNil

`func (o *ProjectDraftResponseLimits) SetPromptsAvailableNil(b bool)`

 SetPromptsAvailableNil sets the value for PromptsAvailable to be an explicit nil

### UnsetPromptsAvailable
`func (o *ProjectDraftResponseLimits) UnsetPromptsAvailable()`

UnsetPromptsAvailable ensures that no value is present for PromptsAvailable, not even an explicit nil
### GetMaxPromptsPerRequest

`func (o *ProjectDraftResponseLimits) GetMaxPromptsPerRequest() int32`

GetMaxPromptsPerRequest returns the MaxPromptsPerRequest field if non-nil, zero value otherwise.

### GetMaxPromptsPerRequestOk

`func (o *ProjectDraftResponseLimits) GetMaxPromptsPerRequestOk() (*int32, bool)`

GetMaxPromptsPerRequestOk returns a tuple with the MaxPromptsPerRequest field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxPromptsPerRequest

`func (o *ProjectDraftResponseLimits) SetMaxPromptsPerRequest(v int32)`

SetMaxPromptsPerRequest sets MaxPromptsPerRequest field to given value.


### GetMaxCompetitors

`func (o *ProjectDraftResponseLimits) GetMaxCompetitors() int32`

GetMaxCompetitors returns the MaxCompetitors field if non-nil, zero value otherwise.

### GetMaxCompetitorsOk

`func (o *ProjectDraftResponseLimits) GetMaxCompetitorsOk() (*int32, bool)`

GetMaxCompetitorsOk returns a tuple with the MaxCompetitors field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxCompetitors

`func (o *ProjectDraftResponseLimits) SetMaxCompetitors(v int32)`

SetMaxCompetitors sets MaxCompetitors field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


