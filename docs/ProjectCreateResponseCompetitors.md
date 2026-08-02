# ProjectCreateResponseCompetitors

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Created** | Pointer to **int32** |  | [optional] 
**Processing** | Pointer to **bool** | Always false; competitors are ready when the project transaction commits. | [optional] 

## Methods

### NewProjectCreateResponseCompetitors

`func NewProjectCreateResponseCompetitors() *ProjectCreateResponseCompetitors`

NewProjectCreateResponseCompetitors instantiates a new ProjectCreateResponseCompetitors object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProjectCreateResponseCompetitorsWithDefaults

`func NewProjectCreateResponseCompetitorsWithDefaults() *ProjectCreateResponseCompetitors`

NewProjectCreateResponseCompetitorsWithDefaults instantiates a new ProjectCreateResponseCompetitors object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCreated

`func (o *ProjectCreateResponseCompetitors) GetCreated() int32`

GetCreated returns the Created field if non-nil, zero value otherwise.

### GetCreatedOk

`func (o *ProjectCreateResponseCompetitors) GetCreatedOk() (*int32, bool)`

GetCreatedOk returns a tuple with the Created field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreated

`func (o *ProjectCreateResponseCompetitors) SetCreated(v int32)`

SetCreated sets Created field to given value.

### HasCreated

`func (o *ProjectCreateResponseCompetitors) HasCreated() bool`

HasCreated returns a boolean if a field has been set.

### GetProcessing

`func (o *ProjectCreateResponseCompetitors) GetProcessing() bool`

GetProcessing returns the Processing field if non-nil, zero value otherwise.

### GetProcessingOk

`func (o *ProjectCreateResponseCompetitors) GetProcessingOk() (*bool, bool)`

GetProcessingOk returns a tuple with the Processing field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProcessing

`func (o *ProjectCreateResponseCompetitors) SetProcessing(v bool)`

SetProcessing sets Processing field to given value.

### HasProcessing

`func (o *ProjectCreateResponseCompetitors) HasProcessing() bool`

HasProcessing returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


