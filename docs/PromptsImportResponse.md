# PromptsImportResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ProjectId** | **int32** |  | 
**ProcessedRows** | **int32** | Distinct rows imported or matched to an existing prompt | 
**Created** | **int32** |  | 
**Duplicates** | **int32** | Rows that matched an existing prompt (they still get the row&#39;s tags) | 
**Tagged** | **int32** | New prompt-tag links | 
**CreatedTags** | **int32** |  | 
**RowErrors** | [**[]PromptsImportResponseRowErrorsInner**](PromptsImportResponseRowErrorsInner.md) | Rows that were skipped, by their index in rows | 
**LengthWarning** | **NullableString** | Which tracked AI models will skip new prompts that are too long for them | 
**PromptsAvailable** | **NullableInt32** | Prompt slots left on the plan; null when unlimited | 
**RequestId** | **string** |  | 

## Methods

### NewPromptsImportResponse

`func NewPromptsImportResponse(projectId int32, processedRows int32, created int32, duplicates int32, tagged int32, createdTags int32, rowErrors []PromptsImportResponseRowErrorsInner, lengthWarning NullableString, promptsAvailable NullableInt32, requestId string, ) *PromptsImportResponse`

NewPromptsImportResponse instantiates a new PromptsImportResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPromptsImportResponseWithDefaults

`func NewPromptsImportResponseWithDefaults() *PromptsImportResponse`

NewPromptsImportResponseWithDefaults instantiates a new PromptsImportResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProjectId

`func (o *PromptsImportResponse) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *PromptsImportResponse) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *PromptsImportResponse) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.


### GetProcessedRows

`func (o *PromptsImportResponse) GetProcessedRows() int32`

GetProcessedRows returns the ProcessedRows field if non-nil, zero value otherwise.

### GetProcessedRowsOk

`func (o *PromptsImportResponse) GetProcessedRowsOk() (*int32, bool)`

GetProcessedRowsOk returns a tuple with the ProcessedRows field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProcessedRows

`func (o *PromptsImportResponse) SetProcessedRows(v int32)`

SetProcessedRows sets ProcessedRows field to given value.


### GetCreated

`func (o *PromptsImportResponse) GetCreated() int32`

GetCreated returns the Created field if non-nil, zero value otherwise.

### GetCreatedOk

`func (o *PromptsImportResponse) GetCreatedOk() (*int32, bool)`

GetCreatedOk returns a tuple with the Created field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreated

`func (o *PromptsImportResponse) SetCreated(v int32)`

SetCreated sets Created field to given value.


### GetDuplicates

`func (o *PromptsImportResponse) GetDuplicates() int32`

GetDuplicates returns the Duplicates field if non-nil, zero value otherwise.

### GetDuplicatesOk

`func (o *PromptsImportResponse) GetDuplicatesOk() (*int32, bool)`

GetDuplicatesOk returns a tuple with the Duplicates field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDuplicates

`func (o *PromptsImportResponse) SetDuplicates(v int32)`

SetDuplicates sets Duplicates field to given value.


### GetTagged

`func (o *PromptsImportResponse) GetTagged() int32`

GetTagged returns the Tagged field if non-nil, zero value otherwise.

### GetTaggedOk

`func (o *PromptsImportResponse) GetTaggedOk() (*int32, bool)`

GetTaggedOk returns a tuple with the Tagged field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTagged

`func (o *PromptsImportResponse) SetTagged(v int32)`

SetTagged sets Tagged field to given value.


### GetCreatedTags

`func (o *PromptsImportResponse) GetCreatedTags() int32`

GetCreatedTags returns the CreatedTags field if non-nil, zero value otherwise.

### GetCreatedTagsOk

`func (o *PromptsImportResponse) GetCreatedTagsOk() (*int32, bool)`

GetCreatedTagsOk returns a tuple with the CreatedTags field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedTags

`func (o *PromptsImportResponse) SetCreatedTags(v int32)`

SetCreatedTags sets CreatedTags field to given value.


### GetRowErrors

`func (o *PromptsImportResponse) GetRowErrors() []PromptsImportResponseRowErrorsInner`

GetRowErrors returns the RowErrors field if non-nil, zero value otherwise.

### GetRowErrorsOk

`func (o *PromptsImportResponse) GetRowErrorsOk() (*[]PromptsImportResponseRowErrorsInner, bool)`

GetRowErrorsOk returns a tuple with the RowErrors field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRowErrors

`func (o *PromptsImportResponse) SetRowErrors(v []PromptsImportResponseRowErrorsInner)`

SetRowErrors sets RowErrors field to given value.


### GetLengthWarning

`func (o *PromptsImportResponse) GetLengthWarning() string`

GetLengthWarning returns the LengthWarning field if non-nil, zero value otherwise.

### GetLengthWarningOk

`func (o *PromptsImportResponse) GetLengthWarningOk() (*string, bool)`

GetLengthWarningOk returns a tuple with the LengthWarning field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLengthWarning

`func (o *PromptsImportResponse) SetLengthWarning(v string)`

SetLengthWarning sets LengthWarning field to given value.


### SetLengthWarningNil

`func (o *PromptsImportResponse) SetLengthWarningNil(b bool)`

 SetLengthWarningNil sets the value for LengthWarning to be an explicit nil

### UnsetLengthWarning
`func (o *PromptsImportResponse) UnsetLengthWarning()`

UnsetLengthWarning ensures that no value is present for LengthWarning, not even an explicit nil
### GetPromptsAvailable

`func (o *PromptsImportResponse) GetPromptsAvailable() int32`

GetPromptsAvailable returns the PromptsAvailable field if non-nil, zero value otherwise.

### GetPromptsAvailableOk

`func (o *PromptsImportResponse) GetPromptsAvailableOk() (*int32, bool)`

GetPromptsAvailableOk returns a tuple with the PromptsAvailable field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPromptsAvailable

`func (o *PromptsImportResponse) SetPromptsAvailable(v int32)`

SetPromptsAvailable sets PromptsAvailable field to given value.


### SetPromptsAvailableNil

`func (o *PromptsImportResponse) SetPromptsAvailableNil(b bool)`

 SetPromptsAvailableNil sets the value for PromptsAvailable to be an explicit nil

### UnsetPromptsAvailable
`func (o *PromptsImportResponse) UnsetPromptsAvailable()`

UnsetPromptsAvailable ensures that no value is present for PromptsAvailable, not even an explicit nil
### GetRequestId

`func (o *PromptsImportResponse) GetRequestId() string`

GetRequestId returns the RequestId field if non-nil, zero value otherwise.

### GetRequestIdOk

`func (o *PromptsImportResponse) GetRequestIdOk() (*string, bool)`

GetRequestIdOk returns a tuple with the RequestId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestId

`func (o *PromptsImportResponse) SetRequestId(v string)`

SetRequestId sets RequestId field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


