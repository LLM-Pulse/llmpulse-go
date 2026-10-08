# GeoAuditRunResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Sequence** | Pointer to **int32** | Run number within the audit, starting at 1 | [optional] 
**Status** | Pointer to **string** |  | [optional] 
**Trigger** | Pointer to **string** |  | [optional] 
**Score** | Pointer to **NullableFloat32** |  | [optional] 
**Grade** | Pointer to **NullableString** |  | [optional] 
**ScoreDelta** | Pointer to **NullableFloat32** | Score change against the previous completed run | [optional] 
**ComparableToPrevious** | Pointer to **bool** | False when the checks or the audit settings changed since the previous run, so a diff may reflect that change | [optional] 
**NewIssues** | Pointer to **int32** |  | [optional] 
**FixedIssues** | Pointer to **int32** |  | [optional] 
**RegressedIssues** | Pointer to **int32** |  | [optional] 
**Error** | Pointer to **NullableString** |  | [optional] 
**EngineVersion** | Pointer to **NullableString** |  | [optional] 
**CreatedAt** | Pointer to **time.Time** |  | [optional] 
**FinishedAt** | Pointer to **NullableTime** |  | [optional] 
**AppUrl** | Pointer to **string** |  | [optional] 
**ProjectId** | Pointer to **int32** |  | [optional] 
**RequestId** | Pointer to **string** |  | [optional] 

## Methods

### NewGeoAuditRunResponse

`func NewGeoAuditRunResponse() *GeoAuditRunResponse`

NewGeoAuditRunResponse instantiates a new GeoAuditRunResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGeoAuditRunResponseWithDefaults

`func NewGeoAuditRunResponseWithDefaults() *GeoAuditRunResponse`

NewGeoAuditRunResponseWithDefaults instantiates a new GeoAuditRunResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSequence

`func (o *GeoAuditRunResponse) GetSequence() int32`

GetSequence returns the Sequence field if non-nil, zero value otherwise.

### GetSequenceOk

`func (o *GeoAuditRunResponse) GetSequenceOk() (*int32, bool)`

GetSequenceOk returns a tuple with the Sequence field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSequence

`func (o *GeoAuditRunResponse) SetSequence(v int32)`

SetSequence sets Sequence field to given value.

### HasSequence

`func (o *GeoAuditRunResponse) HasSequence() bool`

HasSequence returns a boolean if a field has been set.

### GetStatus

`func (o *GeoAuditRunResponse) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *GeoAuditRunResponse) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *GeoAuditRunResponse) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *GeoAuditRunResponse) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetTrigger

`func (o *GeoAuditRunResponse) GetTrigger() string`

GetTrigger returns the Trigger field if non-nil, zero value otherwise.

### GetTriggerOk

`func (o *GeoAuditRunResponse) GetTriggerOk() (*string, bool)`

GetTriggerOk returns a tuple with the Trigger field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrigger

`func (o *GeoAuditRunResponse) SetTrigger(v string)`

SetTrigger sets Trigger field to given value.

### HasTrigger

`func (o *GeoAuditRunResponse) HasTrigger() bool`

HasTrigger returns a boolean if a field has been set.

### GetScore

`func (o *GeoAuditRunResponse) GetScore() float32`

GetScore returns the Score field if non-nil, zero value otherwise.

### GetScoreOk

`func (o *GeoAuditRunResponse) GetScoreOk() (*float32, bool)`

GetScoreOk returns a tuple with the Score field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScore

`func (o *GeoAuditRunResponse) SetScore(v float32)`

SetScore sets Score field to given value.

### HasScore

`func (o *GeoAuditRunResponse) HasScore() bool`

HasScore returns a boolean if a field has been set.

### SetScoreNil

`func (o *GeoAuditRunResponse) SetScoreNil(b bool)`

 SetScoreNil sets the value for Score to be an explicit nil

### UnsetScore
`func (o *GeoAuditRunResponse) UnsetScore()`

UnsetScore ensures that no value is present for Score, not even an explicit nil
### GetGrade

`func (o *GeoAuditRunResponse) GetGrade() string`

GetGrade returns the Grade field if non-nil, zero value otherwise.

### GetGradeOk

`func (o *GeoAuditRunResponse) GetGradeOk() (*string, bool)`

GetGradeOk returns a tuple with the Grade field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGrade

`func (o *GeoAuditRunResponse) SetGrade(v string)`

SetGrade sets Grade field to given value.

### HasGrade

`func (o *GeoAuditRunResponse) HasGrade() bool`

HasGrade returns a boolean if a field has been set.

### SetGradeNil

`func (o *GeoAuditRunResponse) SetGradeNil(b bool)`

 SetGradeNil sets the value for Grade to be an explicit nil

### UnsetGrade
`func (o *GeoAuditRunResponse) UnsetGrade()`

UnsetGrade ensures that no value is present for Grade, not even an explicit nil
### GetScoreDelta

`func (o *GeoAuditRunResponse) GetScoreDelta() float32`

GetScoreDelta returns the ScoreDelta field if non-nil, zero value otherwise.

### GetScoreDeltaOk

`func (o *GeoAuditRunResponse) GetScoreDeltaOk() (*float32, bool)`

GetScoreDeltaOk returns a tuple with the ScoreDelta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScoreDelta

`func (o *GeoAuditRunResponse) SetScoreDelta(v float32)`

SetScoreDelta sets ScoreDelta field to given value.

### HasScoreDelta

`func (o *GeoAuditRunResponse) HasScoreDelta() bool`

HasScoreDelta returns a boolean if a field has been set.

### SetScoreDeltaNil

`func (o *GeoAuditRunResponse) SetScoreDeltaNil(b bool)`

 SetScoreDeltaNil sets the value for ScoreDelta to be an explicit nil

### UnsetScoreDelta
`func (o *GeoAuditRunResponse) UnsetScoreDelta()`

UnsetScoreDelta ensures that no value is present for ScoreDelta, not even an explicit nil
### GetComparableToPrevious

`func (o *GeoAuditRunResponse) GetComparableToPrevious() bool`

GetComparableToPrevious returns the ComparableToPrevious field if non-nil, zero value otherwise.

### GetComparableToPreviousOk

`func (o *GeoAuditRunResponse) GetComparableToPreviousOk() (*bool, bool)`

GetComparableToPreviousOk returns a tuple with the ComparableToPrevious field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComparableToPrevious

`func (o *GeoAuditRunResponse) SetComparableToPrevious(v bool)`

SetComparableToPrevious sets ComparableToPrevious field to given value.

### HasComparableToPrevious

`func (o *GeoAuditRunResponse) HasComparableToPrevious() bool`

HasComparableToPrevious returns a boolean if a field has been set.

### GetNewIssues

`func (o *GeoAuditRunResponse) GetNewIssues() int32`

GetNewIssues returns the NewIssues field if non-nil, zero value otherwise.

### GetNewIssuesOk

`func (o *GeoAuditRunResponse) GetNewIssuesOk() (*int32, bool)`

GetNewIssuesOk returns a tuple with the NewIssues field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNewIssues

`func (o *GeoAuditRunResponse) SetNewIssues(v int32)`

SetNewIssues sets NewIssues field to given value.

### HasNewIssues

`func (o *GeoAuditRunResponse) HasNewIssues() bool`

HasNewIssues returns a boolean if a field has been set.

### GetFixedIssues

`func (o *GeoAuditRunResponse) GetFixedIssues() int32`

GetFixedIssues returns the FixedIssues field if non-nil, zero value otherwise.

### GetFixedIssuesOk

`func (o *GeoAuditRunResponse) GetFixedIssuesOk() (*int32, bool)`

GetFixedIssuesOk returns a tuple with the FixedIssues field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFixedIssues

`func (o *GeoAuditRunResponse) SetFixedIssues(v int32)`

SetFixedIssues sets FixedIssues field to given value.

### HasFixedIssues

`func (o *GeoAuditRunResponse) HasFixedIssues() bool`

HasFixedIssues returns a boolean if a field has been set.

### GetRegressedIssues

`func (o *GeoAuditRunResponse) GetRegressedIssues() int32`

GetRegressedIssues returns the RegressedIssues field if non-nil, zero value otherwise.

### GetRegressedIssuesOk

`func (o *GeoAuditRunResponse) GetRegressedIssuesOk() (*int32, bool)`

GetRegressedIssuesOk returns a tuple with the RegressedIssues field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRegressedIssues

`func (o *GeoAuditRunResponse) SetRegressedIssues(v int32)`

SetRegressedIssues sets RegressedIssues field to given value.

### HasRegressedIssues

`func (o *GeoAuditRunResponse) HasRegressedIssues() bool`

HasRegressedIssues returns a boolean if a field has been set.

### GetError

`func (o *GeoAuditRunResponse) GetError() string`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *GeoAuditRunResponse) GetErrorOk() (*string, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *GeoAuditRunResponse) SetError(v string)`

SetError sets Error field to given value.

### HasError

`func (o *GeoAuditRunResponse) HasError() bool`

HasError returns a boolean if a field has been set.

### SetErrorNil

`func (o *GeoAuditRunResponse) SetErrorNil(b bool)`

 SetErrorNil sets the value for Error to be an explicit nil

### UnsetError
`func (o *GeoAuditRunResponse) UnsetError()`

UnsetError ensures that no value is present for Error, not even an explicit nil
### GetEngineVersion

`func (o *GeoAuditRunResponse) GetEngineVersion() string`

GetEngineVersion returns the EngineVersion field if non-nil, zero value otherwise.

### GetEngineVersionOk

`func (o *GeoAuditRunResponse) GetEngineVersionOk() (*string, bool)`

GetEngineVersionOk returns a tuple with the EngineVersion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEngineVersion

`func (o *GeoAuditRunResponse) SetEngineVersion(v string)`

SetEngineVersion sets EngineVersion field to given value.

### HasEngineVersion

`func (o *GeoAuditRunResponse) HasEngineVersion() bool`

HasEngineVersion returns a boolean if a field has been set.

### SetEngineVersionNil

`func (o *GeoAuditRunResponse) SetEngineVersionNil(b bool)`

 SetEngineVersionNil sets the value for EngineVersion to be an explicit nil

### UnsetEngineVersion
`func (o *GeoAuditRunResponse) UnsetEngineVersion()`

UnsetEngineVersion ensures that no value is present for EngineVersion, not even an explicit nil
### GetCreatedAt

`func (o *GeoAuditRunResponse) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *GeoAuditRunResponse) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *GeoAuditRunResponse) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *GeoAuditRunResponse) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetFinishedAt

`func (o *GeoAuditRunResponse) GetFinishedAt() time.Time`

GetFinishedAt returns the FinishedAt field if non-nil, zero value otherwise.

### GetFinishedAtOk

`func (o *GeoAuditRunResponse) GetFinishedAtOk() (*time.Time, bool)`

GetFinishedAtOk returns a tuple with the FinishedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFinishedAt

`func (o *GeoAuditRunResponse) SetFinishedAt(v time.Time)`

SetFinishedAt sets FinishedAt field to given value.

### HasFinishedAt

`func (o *GeoAuditRunResponse) HasFinishedAt() bool`

HasFinishedAt returns a boolean if a field has been set.

### SetFinishedAtNil

`func (o *GeoAuditRunResponse) SetFinishedAtNil(b bool)`

 SetFinishedAtNil sets the value for FinishedAt to be an explicit nil

### UnsetFinishedAt
`func (o *GeoAuditRunResponse) UnsetFinishedAt()`

UnsetFinishedAt ensures that no value is present for FinishedAt, not even an explicit nil
### GetAppUrl

`func (o *GeoAuditRunResponse) GetAppUrl() string`

GetAppUrl returns the AppUrl field if non-nil, zero value otherwise.

### GetAppUrlOk

`func (o *GeoAuditRunResponse) GetAppUrlOk() (*string, bool)`

GetAppUrlOk returns a tuple with the AppUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAppUrl

`func (o *GeoAuditRunResponse) SetAppUrl(v string)`

SetAppUrl sets AppUrl field to given value.

### HasAppUrl

`func (o *GeoAuditRunResponse) HasAppUrl() bool`

HasAppUrl returns a boolean if a field has been set.

### GetProjectId

`func (o *GeoAuditRunResponse) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *GeoAuditRunResponse) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *GeoAuditRunResponse) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.

### HasProjectId

`func (o *GeoAuditRunResponse) HasProjectId() bool`

HasProjectId returns a boolean if a field has been set.

### GetRequestId

`func (o *GeoAuditRunResponse) GetRequestId() string`

GetRequestId returns the RequestId field if non-nil, zero value otherwise.

### GetRequestIdOk

`func (o *GeoAuditRunResponse) GetRequestIdOk() (*string, bool)`

GetRequestIdOk returns a tuple with the RequestId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestId

`func (o *GeoAuditRunResponse) SetRequestId(v string)`

SetRequestId sets RequestId field to given value.

### HasRequestId

`func (o *GeoAuditRunResponse) HasRequestId() bool`

HasRequestId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


