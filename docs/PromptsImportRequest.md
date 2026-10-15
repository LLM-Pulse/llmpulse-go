# PromptsImportRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ProjectId** | **int32** |  | 
**Rows** | [**[]PromptsImportRequestRowsInner**](PromptsImportRequestRowsInner.md) | One object per prompt (max 500) | 

## Methods

### NewPromptsImportRequest

`func NewPromptsImportRequest(projectId int32, rows []PromptsImportRequestRowsInner, ) *PromptsImportRequest`

NewPromptsImportRequest instantiates a new PromptsImportRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPromptsImportRequestWithDefaults

`func NewPromptsImportRequestWithDefaults() *PromptsImportRequest`

NewPromptsImportRequestWithDefaults instantiates a new PromptsImportRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProjectId

`func (o *PromptsImportRequest) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *PromptsImportRequest) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *PromptsImportRequest) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.


### GetRows

`func (o *PromptsImportRequest) GetRows() []PromptsImportRequestRowsInner`

GetRows returns the Rows field if non-nil, zero value otherwise.

### GetRowsOk

`func (o *PromptsImportRequest) GetRowsOk() (*[]PromptsImportRequestRowsInner, bool)`

GetRowsOk returns a tuple with the Rows field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRows

`func (o *PromptsImportRequest) SetRows(v []PromptsImportRequestRowsInner)`

SetRows sets Rows field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


