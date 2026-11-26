# PeecExportImportResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ProjectId** | **int32** |  | 
**ImportId** | **int32** |  | 
**Status** | **string** | The import was accepted and finishes in the background | 
**Prompts** | **int32** | Distinct prompts of the file, per country and language; each becomes a tracked prompt of the project | 
**NewPrompts** | **int32** | The prompts the project does not hold yet, counted against the plan | 
**PlannedAnswers** | **int32** | Weekly answers the import files (prompts x tracked AI models x weeks) | 
**Models** | **map[string]string** | Each AI model name of the file that is imported, with the tracked AI model its answers are filed under | 
**SkippedModels** | **[]string** | AI model names of the file whose answers are skipped, because the account does not track them | 
**DetectedBrands** | **[]string** | Brand names the export&#39;s mentions column lists (up to 50), none of them created as competitors | 
**AppUrl** | **string** | Opens the project&#39;s prompts in the app | 
**RequestId** | **string** |  | 

## Methods

### NewPeecExportImportResponse

`func NewPeecExportImportResponse(projectId int32, importId int32, status string, prompts int32, newPrompts int32, plannedAnswers int32, models map[string]string, skippedModels []string, detectedBrands []string, appUrl string, requestId string, ) *PeecExportImportResponse`

NewPeecExportImportResponse instantiates a new PeecExportImportResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPeecExportImportResponseWithDefaults

`func NewPeecExportImportResponseWithDefaults() *PeecExportImportResponse`

NewPeecExportImportResponseWithDefaults instantiates a new PeecExportImportResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProjectId

`func (o *PeecExportImportResponse) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *PeecExportImportResponse) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *PeecExportImportResponse) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.


### GetImportId

`func (o *PeecExportImportResponse) GetImportId() int32`

GetImportId returns the ImportId field if non-nil, zero value otherwise.

### GetImportIdOk

`func (o *PeecExportImportResponse) GetImportIdOk() (*int32, bool)`

GetImportIdOk returns a tuple with the ImportId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImportId

`func (o *PeecExportImportResponse) SetImportId(v int32)`

SetImportId sets ImportId field to given value.


### GetStatus

`func (o *PeecExportImportResponse) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *PeecExportImportResponse) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *PeecExportImportResponse) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetPrompts

`func (o *PeecExportImportResponse) GetPrompts() int32`

GetPrompts returns the Prompts field if non-nil, zero value otherwise.

### GetPromptsOk

`func (o *PeecExportImportResponse) GetPromptsOk() (*int32, bool)`

GetPromptsOk returns a tuple with the Prompts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrompts

`func (o *PeecExportImportResponse) SetPrompts(v int32)`

SetPrompts sets Prompts field to given value.


### GetNewPrompts

`func (o *PeecExportImportResponse) GetNewPrompts() int32`

GetNewPrompts returns the NewPrompts field if non-nil, zero value otherwise.

### GetNewPromptsOk

`func (o *PeecExportImportResponse) GetNewPromptsOk() (*int32, bool)`

GetNewPromptsOk returns a tuple with the NewPrompts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNewPrompts

`func (o *PeecExportImportResponse) SetNewPrompts(v int32)`

SetNewPrompts sets NewPrompts field to given value.


### GetPlannedAnswers

`func (o *PeecExportImportResponse) GetPlannedAnswers() int32`

GetPlannedAnswers returns the PlannedAnswers field if non-nil, zero value otherwise.

### GetPlannedAnswersOk

`func (o *PeecExportImportResponse) GetPlannedAnswersOk() (*int32, bool)`

GetPlannedAnswersOk returns a tuple with the PlannedAnswers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlannedAnswers

`func (o *PeecExportImportResponse) SetPlannedAnswers(v int32)`

SetPlannedAnswers sets PlannedAnswers field to given value.


### GetModels

`func (o *PeecExportImportResponse) GetModels() map[string]string`

GetModels returns the Models field if non-nil, zero value otherwise.

### GetModelsOk

`func (o *PeecExportImportResponse) GetModelsOk() (*map[string]string, bool)`

GetModelsOk returns a tuple with the Models field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModels

`func (o *PeecExportImportResponse) SetModels(v map[string]string)`

SetModels sets Models field to given value.


### GetSkippedModels

`func (o *PeecExportImportResponse) GetSkippedModels() []string`

GetSkippedModels returns the SkippedModels field if non-nil, zero value otherwise.

### GetSkippedModelsOk

`func (o *PeecExportImportResponse) GetSkippedModelsOk() (*[]string, bool)`

GetSkippedModelsOk returns a tuple with the SkippedModels field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSkippedModels

`func (o *PeecExportImportResponse) SetSkippedModels(v []string)`

SetSkippedModels sets SkippedModels field to given value.


### GetDetectedBrands

`func (o *PeecExportImportResponse) GetDetectedBrands() []string`

GetDetectedBrands returns the DetectedBrands field if non-nil, zero value otherwise.

### GetDetectedBrandsOk

`func (o *PeecExportImportResponse) GetDetectedBrandsOk() (*[]string, bool)`

GetDetectedBrandsOk returns a tuple with the DetectedBrands field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDetectedBrands

`func (o *PeecExportImportResponse) SetDetectedBrands(v []string)`

SetDetectedBrands sets DetectedBrands field to given value.


### GetAppUrl

`func (o *PeecExportImportResponse) GetAppUrl() string`

GetAppUrl returns the AppUrl field if non-nil, zero value otherwise.

### GetAppUrlOk

`func (o *PeecExportImportResponse) GetAppUrlOk() (*string, bool)`

GetAppUrlOk returns a tuple with the AppUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAppUrl

`func (o *PeecExportImportResponse) SetAppUrl(v string)`

SetAppUrl sets AppUrl field to given value.


### GetRequestId

`func (o *PeecExportImportResponse) GetRequestId() string`

GetRequestId returns the RequestId field if non-nil, zero value otherwise.

### GetRequestIdOk

`func (o *PeecExportImportResponse) GetRequestIdOk() (*string, bool)`

GetRequestIdOk returns a tuple with the RequestId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestId

`func (o *PeecExportImportResponse) SetRequestId(v string)`

SetRequestId sets RequestId field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


