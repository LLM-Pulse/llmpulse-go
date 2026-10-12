# ProjectUpdateResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Project** | [**ProjectProfile**](ProjectProfile.md) |  | 
**UpdatedFields** | **[]string** | The fields the request sent | 
**Rematching** | **bool** | True when a matching_names or additional_owned_domains change started a background recalculation of past answers; further edits are rejected until it finishes | 
**Note** | **string** | What the change does to mention detection, citation ownership and historical numbers | 
**RequestId** | **string** |  | 

## Methods

### NewProjectUpdateResponse

`func NewProjectUpdateResponse(project ProjectProfile, updatedFields []string, rematching bool, note string, requestId string, ) *ProjectUpdateResponse`

NewProjectUpdateResponse instantiates a new ProjectUpdateResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProjectUpdateResponseWithDefaults

`func NewProjectUpdateResponseWithDefaults() *ProjectUpdateResponse`

NewProjectUpdateResponseWithDefaults instantiates a new ProjectUpdateResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProject

`func (o *ProjectUpdateResponse) GetProject() ProjectProfile`

GetProject returns the Project field if non-nil, zero value otherwise.

### GetProjectOk

`func (o *ProjectUpdateResponse) GetProjectOk() (*ProjectProfile, bool)`

GetProjectOk returns a tuple with the Project field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProject

`func (o *ProjectUpdateResponse) SetProject(v ProjectProfile)`

SetProject sets Project field to given value.


### GetUpdatedFields

`func (o *ProjectUpdateResponse) GetUpdatedFields() []string`

GetUpdatedFields returns the UpdatedFields field if non-nil, zero value otherwise.

### GetUpdatedFieldsOk

`func (o *ProjectUpdateResponse) GetUpdatedFieldsOk() (*[]string, bool)`

GetUpdatedFieldsOk returns a tuple with the UpdatedFields field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedFields

`func (o *ProjectUpdateResponse) SetUpdatedFields(v []string)`

SetUpdatedFields sets UpdatedFields field to given value.


### GetRematching

`func (o *ProjectUpdateResponse) GetRematching() bool`

GetRematching returns the Rematching field if non-nil, zero value otherwise.

### GetRematchingOk

`func (o *ProjectUpdateResponse) GetRematchingOk() (*bool, bool)`

GetRematchingOk returns a tuple with the Rematching field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRematching

`func (o *ProjectUpdateResponse) SetRematching(v bool)`

SetRematching sets Rematching field to given value.


### GetNote

`func (o *ProjectUpdateResponse) GetNote() string`

GetNote returns the Note field if non-nil, zero value otherwise.

### GetNoteOk

`func (o *ProjectUpdateResponse) GetNoteOk() (*string, bool)`

GetNoteOk returns a tuple with the Note field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNote

`func (o *ProjectUpdateResponse) SetNote(v string)`

SetNote sets Note field to given value.


### GetRequestId

`func (o *ProjectUpdateResponse) GetRequestId() string`

GetRequestId returns the RequestId field if non-nil, zero value otherwise.

### GetRequestIdOk

`func (o *ProjectUpdateResponse) GetRequestIdOk() (*string, bool)`

GetRequestIdOk returns a tuple with the RequestId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestId

`func (o *ProjectUpdateResponse) SetRequestId(v string)`

SetRequestId sets RequestId field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


