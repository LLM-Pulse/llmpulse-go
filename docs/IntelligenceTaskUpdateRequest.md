# IntelligenceTaskUpdateRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ProjectId** | **int32** |  | 
**Edits** | **map[string]string** | Dotted result_data paths (title, sections.0.content, key_points.2) mapped to their replacement text. Only string fields that already exist are editable; sections cannot be added or removed. | 

## Methods

### NewIntelligenceTaskUpdateRequest

`func NewIntelligenceTaskUpdateRequest(projectId int32, edits map[string]string, ) *IntelligenceTaskUpdateRequest`

NewIntelligenceTaskUpdateRequest instantiates a new IntelligenceTaskUpdateRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewIntelligenceTaskUpdateRequestWithDefaults

`func NewIntelligenceTaskUpdateRequestWithDefaults() *IntelligenceTaskUpdateRequest`

NewIntelligenceTaskUpdateRequestWithDefaults instantiates a new IntelligenceTaskUpdateRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProjectId

`func (o *IntelligenceTaskUpdateRequest) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *IntelligenceTaskUpdateRequest) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *IntelligenceTaskUpdateRequest) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.


### GetEdits

`func (o *IntelligenceTaskUpdateRequest) GetEdits() map[string]string`

GetEdits returns the Edits field if non-nil, zero value otherwise.

### GetEditsOk

`func (o *IntelligenceTaskUpdateRequest) GetEditsOk() (*map[string]string, bool)`

GetEditsOk returns a tuple with the Edits field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEdits

`func (o *IntelligenceTaskUpdateRequest) SetEdits(v map[string]string)`

SetEdits sets Edits field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


