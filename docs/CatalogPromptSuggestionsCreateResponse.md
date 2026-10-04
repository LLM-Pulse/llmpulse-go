# CatalogPromptSuggestionsCreateResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ProjectId** | **int32** |  | 
**Created** | **int32** |  | 
**Skipped** | **int32** | Generated prompts not saved because the project already holds them as a suggestion (from any source or product, in any status). | 
**Data** | [**[]CatalogPromptSuggestion**](CatalogPromptSuggestion.md) |  | 
**RequestId** | **string** |  | 

## Methods

### NewCatalogPromptSuggestionsCreateResponse

`func NewCatalogPromptSuggestionsCreateResponse(projectId int32, created int32, skipped int32, data []CatalogPromptSuggestion, requestId string, ) *CatalogPromptSuggestionsCreateResponse`

NewCatalogPromptSuggestionsCreateResponse instantiates a new CatalogPromptSuggestionsCreateResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCatalogPromptSuggestionsCreateResponseWithDefaults

`func NewCatalogPromptSuggestionsCreateResponseWithDefaults() *CatalogPromptSuggestionsCreateResponse`

NewCatalogPromptSuggestionsCreateResponseWithDefaults instantiates a new CatalogPromptSuggestionsCreateResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProjectId

`func (o *CatalogPromptSuggestionsCreateResponse) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *CatalogPromptSuggestionsCreateResponse) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *CatalogPromptSuggestionsCreateResponse) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.


### GetCreated

`func (o *CatalogPromptSuggestionsCreateResponse) GetCreated() int32`

GetCreated returns the Created field if non-nil, zero value otherwise.

### GetCreatedOk

`func (o *CatalogPromptSuggestionsCreateResponse) GetCreatedOk() (*int32, bool)`

GetCreatedOk returns a tuple with the Created field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreated

`func (o *CatalogPromptSuggestionsCreateResponse) SetCreated(v int32)`

SetCreated sets Created field to given value.


### GetSkipped

`func (o *CatalogPromptSuggestionsCreateResponse) GetSkipped() int32`

GetSkipped returns the Skipped field if non-nil, zero value otherwise.

### GetSkippedOk

`func (o *CatalogPromptSuggestionsCreateResponse) GetSkippedOk() (*int32, bool)`

GetSkippedOk returns a tuple with the Skipped field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSkipped

`func (o *CatalogPromptSuggestionsCreateResponse) SetSkipped(v int32)`

SetSkipped sets Skipped field to given value.


### GetData

`func (o *CatalogPromptSuggestionsCreateResponse) GetData() []CatalogPromptSuggestion`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *CatalogPromptSuggestionsCreateResponse) GetDataOk() (*[]CatalogPromptSuggestion, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *CatalogPromptSuggestionsCreateResponse) SetData(v []CatalogPromptSuggestion)`

SetData sets Data field to given value.


### GetRequestId

`func (o *CatalogPromptSuggestionsCreateResponse) GetRequestId() string`

GetRequestId returns the RequestId field if non-nil, zero value otherwise.

### GetRequestIdOk

`func (o *CatalogPromptSuggestionsCreateResponse) GetRequestIdOk() (*string, bool)`

GetRequestIdOk returns a tuple with the RequestId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestId

`func (o *CatalogPromptSuggestionsCreateResponse) SetRequestId(v string)`

SetRequestId sets RequestId field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


