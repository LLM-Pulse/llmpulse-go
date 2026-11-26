# StudyResponse

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
**Brief** | **NullableString** | What the study asks the analyst models; null when none was written | 
**Subjects** | **[]string** | Names of the subjects it compares | 
**Dimensions** | **[]string** | Keys of the dimensions it scores, as the dimension filter takes them | 
**Reports** | [**[]ReputationReportSummary**](ReputationReportSummary.md) | The 24 latest reports, newest first | 
**RequestId** | **string** |  | 

## Methods

### NewStudyResponse

`func NewStudyResponse(id int32, title string, studyType string, cadence string, status string, projectId NullableInt32, subjectsCount int32, aiModels []string, outputLanguageCode string, createdAt time.Time, lastReportAt NullableTime, brief NullableString, subjects []string, dimensions []string, reports []ReputationReportSummary, requestId string, ) *StudyResponse`

NewStudyResponse instantiates a new StudyResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewStudyResponseWithDefaults

`func NewStudyResponseWithDefaults() *StudyResponse`

NewStudyResponseWithDefaults instantiates a new StudyResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *StudyResponse) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *StudyResponse) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *StudyResponse) SetId(v int32)`

SetId sets Id field to given value.


### GetTitle

`func (o *StudyResponse) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *StudyResponse) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *StudyResponse) SetTitle(v string)`

SetTitle sets Title field to given value.


### GetStudyType

`func (o *StudyResponse) GetStudyType() string`

GetStudyType returns the StudyType field if non-nil, zero value otherwise.

### GetStudyTypeOk

`func (o *StudyResponse) GetStudyTypeOk() (*string, bool)`

GetStudyTypeOk returns a tuple with the StudyType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStudyType

`func (o *StudyResponse) SetStudyType(v string)`

SetStudyType sets StudyType field to given value.


### GetCadence

`func (o *StudyResponse) GetCadence() string`

GetCadence returns the Cadence field if non-nil, zero value otherwise.

### GetCadenceOk

`func (o *StudyResponse) GetCadenceOk() (*string, bool)`

GetCadenceOk returns a tuple with the Cadence field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCadence

`func (o *StudyResponse) SetCadence(v string)`

SetCadence sets Cadence field to given value.


### GetStatus

`func (o *StudyResponse) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *StudyResponse) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *StudyResponse) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetProjectId

`func (o *StudyResponse) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *StudyResponse) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *StudyResponse) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.


### SetProjectIdNil

`func (o *StudyResponse) SetProjectIdNil(b bool)`

 SetProjectIdNil sets the value for ProjectId to be an explicit nil

### UnsetProjectId
`func (o *StudyResponse) UnsetProjectId()`

UnsetProjectId ensures that no value is present for ProjectId, not even an explicit nil
### GetSubjectsCount

`func (o *StudyResponse) GetSubjectsCount() int32`

GetSubjectsCount returns the SubjectsCount field if non-nil, zero value otherwise.

### GetSubjectsCountOk

`func (o *StudyResponse) GetSubjectsCountOk() (*int32, bool)`

GetSubjectsCountOk returns a tuple with the SubjectsCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubjectsCount

`func (o *StudyResponse) SetSubjectsCount(v int32)`

SetSubjectsCount sets SubjectsCount field to given value.


### GetAiModels

`func (o *StudyResponse) GetAiModels() []string`

GetAiModels returns the AiModels field if non-nil, zero value otherwise.

### GetAiModelsOk

`func (o *StudyResponse) GetAiModelsOk() (*[]string, bool)`

GetAiModelsOk returns a tuple with the AiModels field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAiModels

`func (o *StudyResponse) SetAiModels(v []string)`

SetAiModels sets AiModels field to given value.


### GetOutputLanguageCode

`func (o *StudyResponse) GetOutputLanguageCode() string`

GetOutputLanguageCode returns the OutputLanguageCode field if non-nil, zero value otherwise.

### GetOutputLanguageCodeOk

`func (o *StudyResponse) GetOutputLanguageCodeOk() (*string, bool)`

GetOutputLanguageCodeOk returns a tuple with the OutputLanguageCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOutputLanguageCode

`func (o *StudyResponse) SetOutputLanguageCode(v string)`

SetOutputLanguageCode sets OutputLanguageCode field to given value.


### GetCreatedAt

`func (o *StudyResponse) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *StudyResponse) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *StudyResponse) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetLastReportAt

`func (o *StudyResponse) GetLastReportAt() time.Time`

GetLastReportAt returns the LastReportAt field if non-nil, zero value otherwise.

### GetLastReportAtOk

`func (o *StudyResponse) GetLastReportAtOk() (*time.Time, bool)`

GetLastReportAtOk returns a tuple with the LastReportAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastReportAt

`func (o *StudyResponse) SetLastReportAt(v time.Time)`

SetLastReportAt sets LastReportAt field to given value.


### SetLastReportAtNil

`func (o *StudyResponse) SetLastReportAtNil(b bool)`

 SetLastReportAtNil sets the value for LastReportAt to be an explicit nil

### UnsetLastReportAt
`func (o *StudyResponse) UnsetLastReportAt()`

UnsetLastReportAt ensures that no value is present for LastReportAt, not even an explicit nil
### GetBrief

`func (o *StudyResponse) GetBrief() string`

GetBrief returns the Brief field if non-nil, zero value otherwise.

### GetBriefOk

`func (o *StudyResponse) GetBriefOk() (*string, bool)`

GetBriefOk returns a tuple with the Brief field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBrief

`func (o *StudyResponse) SetBrief(v string)`

SetBrief sets Brief field to given value.


### SetBriefNil

`func (o *StudyResponse) SetBriefNil(b bool)`

 SetBriefNil sets the value for Brief to be an explicit nil

### UnsetBrief
`func (o *StudyResponse) UnsetBrief()`

UnsetBrief ensures that no value is present for Brief, not even an explicit nil
### GetSubjects

`func (o *StudyResponse) GetSubjects() []string`

GetSubjects returns the Subjects field if non-nil, zero value otherwise.

### GetSubjectsOk

`func (o *StudyResponse) GetSubjectsOk() (*[]string, bool)`

GetSubjectsOk returns a tuple with the Subjects field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubjects

`func (o *StudyResponse) SetSubjects(v []string)`

SetSubjects sets Subjects field to given value.


### GetDimensions

`func (o *StudyResponse) GetDimensions() []string`

GetDimensions returns the Dimensions field if non-nil, zero value otherwise.

### GetDimensionsOk

`func (o *StudyResponse) GetDimensionsOk() (*[]string, bool)`

GetDimensionsOk returns a tuple with the Dimensions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDimensions

`func (o *StudyResponse) SetDimensions(v []string)`

SetDimensions sets Dimensions field to given value.


### GetReports

`func (o *StudyResponse) GetReports() []ReputationReportSummary`

GetReports returns the Reports field if non-nil, zero value otherwise.

### GetReportsOk

`func (o *StudyResponse) GetReportsOk() (*[]ReputationReportSummary, bool)`

GetReportsOk returns a tuple with the Reports field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReports

`func (o *StudyResponse) SetReports(v []ReputationReportSummary)`

SetReports sets Reports field to given value.


### GetRequestId

`func (o *StudyResponse) GetRequestId() string`

GetRequestId returns the RequestId field if non-nil, zero value otherwise.

### GetRequestIdOk

`func (o *StudyResponse) GetRequestIdOk() (*string, bool)`

GetRequestIdOk returns a tuple with the RequestId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestId

`func (o *StudyResponse) SetRequestId(v string)`

SetRequestId sets RequestId field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


