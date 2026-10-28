# ProjectDeleteResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ProjectId** | **int32** |  | 
**Deleted** | **bool** | Always true | 
**Name** | **string** | The deleted project&#39;s name | 
**Url** | **NullableString** | The deleted project&#39;s website | 
**Note** | **string** | What happens next; the deletion cannot be undone | 
**RequestId** | **string** |  | 

## Methods

### NewProjectDeleteResponse

`func NewProjectDeleteResponse(projectId int32, deleted bool, name string, url NullableString, note string, requestId string, ) *ProjectDeleteResponse`

NewProjectDeleteResponse instantiates a new ProjectDeleteResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProjectDeleteResponseWithDefaults

`func NewProjectDeleteResponseWithDefaults() *ProjectDeleteResponse`

NewProjectDeleteResponseWithDefaults instantiates a new ProjectDeleteResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProjectId

`func (o *ProjectDeleteResponse) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *ProjectDeleteResponse) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *ProjectDeleteResponse) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.


### GetDeleted

`func (o *ProjectDeleteResponse) GetDeleted() bool`

GetDeleted returns the Deleted field if non-nil, zero value otherwise.

### GetDeletedOk

`func (o *ProjectDeleteResponse) GetDeletedOk() (*bool, bool)`

GetDeletedOk returns a tuple with the Deleted field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeleted

`func (o *ProjectDeleteResponse) SetDeleted(v bool)`

SetDeleted sets Deleted field to given value.


### GetName

`func (o *ProjectDeleteResponse) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ProjectDeleteResponse) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ProjectDeleteResponse) SetName(v string)`

SetName sets Name field to given value.


### GetUrl

`func (o *ProjectDeleteResponse) GetUrl() string`

GetUrl returns the Url field if non-nil, zero value otherwise.

### GetUrlOk

`func (o *ProjectDeleteResponse) GetUrlOk() (*string, bool)`

GetUrlOk returns a tuple with the Url field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrl

`func (o *ProjectDeleteResponse) SetUrl(v string)`

SetUrl sets Url field to given value.


### SetUrlNil

`func (o *ProjectDeleteResponse) SetUrlNil(b bool)`

 SetUrlNil sets the value for Url to be an explicit nil

### UnsetUrl
`func (o *ProjectDeleteResponse) UnsetUrl()`

UnsetUrl ensures that no value is present for Url, not even an explicit nil
### GetNote

`func (o *ProjectDeleteResponse) GetNote() string`

GetNote returns the Note field if non-nil, zero value otherwise.

### GetNoteOk

`func (o *ProjectDeleteResponse) GetNoteOk() (*string, bool)`

GetNoteOk returns a tuple with the Note field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNote

`func (o *ProjectDeleteResponse) SetNote(v string)`

SetNote sets Note field to given value.


### GetRequestId

`func (o *ProjectDeleteResponse) GetRequestId() string`

GetRequestId returns the RequestId field if non-nil, zero value otherwise.

### GetRequestIdOk

`func (o *ProjectDeleteResponse) GetRequestIdOk() (*string, bool)`

GetRequestIdOk returns a tuple with the RequestId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestId

`func (o *ProjectDeleteResponse) SetRequestId(v string)`

SetRequestId sets RequestId field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


