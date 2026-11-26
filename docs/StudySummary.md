# StudySummary

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **int32** |  | 
**Title** | **string** |  | 
**StudyType** | **string** | brand_set, sector, geo, topic or custom | 
**Cadence** | **string** | one_shot or monthly | 
**Status** | **string** | active or archived | 
**ProjectId** | **NullableInt32** | The project the study is attached to; null for an account-level study | 
**SubjectsCount** | **int32** |  | 
**AiModels** | **[]string** | Analyst models the study runs on | 
**OutputLanguageCode** | **string** | ISO 639-1 code of the language the reports are written in | 
**CreatedAt** | **time.Time** |  | 
**LastReportAt** | **NullableTime** | When the latest report started; null before the first one | 

## Methods

### NewStudySummary

`func NewStudySummary(id int32, title string, studyType string, cadence string, status string, projectId NullableInt32, subjectsCount int32, aiModels []string, outputLanguageCode string, createdAt time.Time, lastReportAt NullableTime, ) *StudySummary`

NewStudySummary instantiates a new StudySummary object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewStudySummaryWithDefaults

`func NewStudySummaryWithDefaults() *StudySummary`

NewStudySummaryWithDefaults instantiates a new StudySummary object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *StudySummary) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *StudySummary) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *StudySummary) SetId(v int32)`

SetId sets Id field to given value.


### GetTitle

`func (o *StudySummary) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *StudySummary) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *StudySummary) SetTitle(v string)`

SetTitle sets Title field to given value.


### GetStudyType

`func (o *StudySummary) GetStudyType() string`

GetStudyType returns the StudyType field if non-nil, zero value otherwise.

### GetStudyTypeOk

`func (o *StudySummary) GetStudyTypeOk() (*string, bool)`

GetStudyTypeOk returns a tuple with the StudyType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStudyType

`func (o *StudySummary) SetStudyType(v string)`

SetStudyType sets StudyType field to given value.


### GetCadence

`func (o *StudySummary) GetCadence() string`

GetCadence returns the Cadence field if non-nil, zero value otherwise.

### GetCadenceOk

`func (o *StudySummary) GetCadenceOk() (*string, bool)`

GetCadenceOk returns a tuple with the Cadence field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCadence

`func (o *StudySummary) SetCadence(v string)`

SetCadence sets Cadence field to given value.


### GetStatus

`func (o *StudySummary) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *StudySummary) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *StudySummary) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetProjectId

`func (o *StudySummary) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *StudySummary) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *StudySummary) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.


### SetProjectIdNil

`func (o *StudySummary) SetProjectIdNil(b bool)`

 SetProjectIdNil sets the value for ProjectId to be an explicit nil

### UnsetProjectId
`func (o *StudySummary) UnsetProjectId()`

UnsetProjectId ensures that no value is present for ProjectId, not even an explicit nil
### GetSubjectsCount

`func (o *StudySummary) GetSubjectsCount() int32`

GetSubjectsCount returns the SubjectsCount field if non-nil, zero value otherwise.

### GetSubjectsCountOk

`func (o *StudySummary) GetSubjectsCountOk() (*int32, bool)`

GetSubjectsCountOk returns a tuple with the SubjectsCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubjectsCount

`func (o *StudySummary) SetSubjectsCount(v int32)`

SetSubjectsCount sets SubjectsCount field to given value.


### GetAiModels

`func (o *StudySummary) GetAiModels() []string`

GetAiModels returns the AiModels field if non-nil, zero value otherwise.

### GetAiModelsOk

`func (o *StudySummary) GetAiModelsOk() (*[]string, bool)`

GetAiModelsOk returns a tuple with the AiModels field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAiModels

`func (o *StudySummary) SetAiModels(v []string)`

SetAiModels sets AiModels field to given value.


### GetOutputLanguageCode

`func (o *StudySummary) GetOutputLanguageCode() string`

GetOutputLanguageCode returns the OutputLanguageCode field if non-nil, zero value otherwise.

### GetOutputLanguageCodeOk

`func (o *StudySummary) GetOutputLanguageCodeOk() (*string, bool)`

GetOutputLanguageCodeOk returns a tuple with the OutputLanguageCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOutputLanguageCode

`func (o *StudySummary) SetOutputLanguageCode(v string)`

SetOutputLanguageCode sets OutputLanguageCode field to given value.


### GetCreatedAt

`func (o *StudySummary) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *StudySummary) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *StudySummary) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetLastReportAt

`func (o *StudySummary) GetLastReportAt() time.Time`

GetLastReportAt returns the LastReportAt field if non-nil, zero value otherwise.

### GetLastReportAtOk

`func (o *StudySummary) GetLastReportAtOk() (*time.Time, bool)`

GetLastReportAtOk returns a tuple with the LastReportAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastReportAt

`func (o *StudySummary) SetLastReportAt(v time.Time)`

SetLastReportAt sets LastReportAt field to given value.


### SetLastReportAtNil

`func (o *StudySummary) SetLastReportAtNil(b bool)`

 SetLastReportAtNil sets the value for LastReportAt to be an explicit nil

### UnsetLastReportAt
`func (o *StudySummary) UnsetLastReportAt()`

UnsetLastReportAt ensures that no value is present for LastReportAt, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


