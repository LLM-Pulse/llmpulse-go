# GeoAuditRun

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

## Methods

### NewGeoAuditRun

`func NewGeoAuditRun() *GeoAuditRun`

NewGeoAuditRun instantiates a new GeoAuditRun object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGeoAuditRunWithDefaults

`func NewGeoAuditRunWithDefaults() *GeoAuditRun`

NewGeoAuditRunWithDefaults instantiates a new GeoAuditRun object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSequence

`func (o *GeoAuditRun) GetSequence() int32`

GetSequence returns the Sequence field if non-nil, zero value otherwise.

### GetSequenceOk

`func (o *GeoAuditRun) GetSequenceOk() (*int32, bool)`

GetSequenceOk returns a tuple with the Sequence field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSequence

`func (o *GeoAuditRun) SetSequence(v int32)`

SetSequence sets Sequence field to given value.

### HasSequence

`func (o *GeoAuditRun) HasSequence() bool`

HasSequence returns a boolean if a field has been set.

### GetStatus

`func (o *GeoAuditRun) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *GeoAuditRun) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *GeoAuditRun) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *GeoAuditRun) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetTrigger

`func (o *GeoAuditRun) GetTrigger() string`

GetTrigger returns the Trigger field if non-nil, zero value otherwise.

### GetTriggerOk

`func (o *GeoAuditRun) GetTriggerOk() (*string, bool)`

GetTriggerOk returns a tuple with the Trigger field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrigger

`func (o *GeoAuditRun) SetTrigger(v string)`

SetTrigger sets Trigger field to given value.

### HasTrigger

`func (o *GeoAuditRun) HasTrigger() bool`

HasTrigger returns a boolean if a field has been set.

### GetScore

`func (o *GeoAuditRun) GetScore() float32`

GetScore returns the Score field if non-nil, zero value otherwise.

### GetScoreOk

`func (o *GeoAuditRun) GetScoreOk() (*float32, bool)`

GetScoreOk returns a tuple with the Score field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScore

`func (o *GeoAuditRun) SetScore(v float32)`

SetScore sets Score field to given value.

### HasScore

`func (o *GeoAuditRun) HasScore() bool`

HasScore returns a boolean if a field has been set.

### SetScoreNil

`func (o *GeoAuditRun) SetScoreNil(b bool)`

 SetScoreNil sets the value for Score to be an explicit nil

### UnsetScore
`func (o *GeoAuditRun) UnsetScore()`

UnsetScore ensures that no value is present for Score, not even an explicit nil
### GetGrade

`func (o *GeoAuditRun) GetGrade() string`

GetGrade returns the Grade field if non-nil, zero value otherwise.

### GetGradeOk

`func (o *GeoAuditRun) GetGradeOk() (*string, bool)`

GetGradeOk returns a tuple with the Grade field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGrade

`func (o *GeoAuditRun) SetGrade(v string)`

SetGrade sets Grade field to given value.

### HasGrade

`func (o *GeoAuditRun) HasGrade() bool`

HasGrade returns a boolean if a field has been set.

### SetGradeNil

`func (o *GeoAuditRun) SetGradeNil(b bool)`

 SetGradeNil sets the value for Grade to be an explicit nil

### UnsetGrade
`func (o *GeoAuditRun) UnsetGrade()`

UnsetGrade ensures that no value is present for Grade, not even an explicit nil
### GetScoreDelta

`func (o *GeoAuditRun) GetScoreDelta() float32`

GetScoreDelta returns the ScoreDelta field if non-nil, zero value otherwise.

### GetScoreDeltaOk

`func (o *GeoAuditRun) GetScoreDeltaOk() (*float32, bool)`

GetScoreDeltaOk returns a tuple with the ScoreDelta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScoreDelta

`func (o *GeoAuditRun) SetScoreDelta(v float32)`

SetScoreDelta sets ScoreDelta field to given value.

### HasScoreDelta

`func (o *GeoAuditRun) HasScoreDelta() bool`

HasScoreDelta returns a boolean if a field has been set.

### SetScoreDeltaNil

`func (o *GeoAuditRun) SetScoreDeltaNil(b bool)`

 SetScoreDeltaNil sets the value for ScoreDelta to be an explicit nil

### UnsetScoreDelta
`func (o *GeoAuditRun) UnsetScoreDelta()`

UnsetScoreDelta ensures that no value is present for ScoreDelta, not even an explicit nil
### GetComparableToPrevious

`func (o *GeoAuditRun) GetComparableToPrevious() bool`

GetComparableToPrevious returns the ComparableToPrevious field if non-nil, zero value otherwise.

### GetComparableToPreviousOk

`func (o *GeoAuditRun) GetComparableToPreviousOk() (*bool, bool)`

GetComparableToPreviousOk returns a tuple with the ComparableToPrevious field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComparableToPrevious

`func (o *GeoAuditRun) SetComparableToPrevious(v bool)`

SetComparableToPrevious sets ComparableToPrevious field to given value.

### HasComparableToPrevious

`func (o *GeoAuditRun) HasComparableToPrevious() bool`

HasComparableToPrevious returns a boolean if a field has been set.

### GetNewIssues

`func (o *GeoAuditRun) GetNewIssues() int32`

GetNewIssues returns the NewIssues field if non-nil, zero value otherwise.

### GetNewIssuesOk

`func (o *GeoAuditRun) GetNewIssuesOk() (*int32, bool)`

GetNewIssuesOk returns a tuple with the NewIssues field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNewIssues

`func (o *GeoAuditRun) SetNewIssues(v int32)`

SetNewIssues sets NewIssues field to given value.

### HasNewIssues

`func (o *GeoAuditRun) HasNewIssues() bool`

HasNewIssues returns a boolean if a field has been set.

### GetFixedIssues

`func (o *GeoAuditRun) GetFixedIssues() int32`

GetFixedIssues returns the FixedIssues field if non-nil, zero value otherwise.

### GetFixedIssuesOk

`func (o *GeoAuditRun) GetFixedIssuesOk() (*int32, bool)`

GetFixedIssuesOk returns a tuple with the FixedIssues field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFixedIssues

`func (o *GeoAuditRun) SetFixedIssues(v int32)`

SetFixedIssues sets FixedIssues field to given value.

### HasFixedIssues

`func (o *GeoAuditRun) HasFixedIssues() bool`

HasFixedIssues returns a boolean if a field has been set.

### GetRegressedIssues

`func (o *GeoAuditRun) GetRegressedIssues() int32`

GetRegressedIssues returns the RegressedIssues field if non-nil, zero value otherwise.

### GetRegressedIssuesOk

`func (o *GeoAuditRun) GetRegressedIssuesOk() (*int32, bool)`

GetRegressedIssuesOk returns a tuple with the RegressedIssues field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRegressedIssues

`func (o *GeoAuditRun) SetRegressedIssues(v int32)`

SetRegressedIssues sets RegressedIssues field to given value.

### HasRegressedIssues

`func (o *GeoAuditRun) HasRegressedIssues() bool`

HasRegressedIssues returns a boolean if a field has been set.

### GetError

`func (o *GeoAuditRun) GetError() string`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *GeoAuditRun) GetErrorOk() (*string, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *GeoAuditRun) SetError(v string)`

SetError sets Error field to given value.

### HasError

`func (o *GeoAuditRun) HasError() bool`

HasError returns a boolean if a field has been set.

### SetErrorNil

`func (o *GeoAuditRun) SetErrorNil(b bool)`

 SetErrorNil sets the value for Error to be an explicit nil

### UnsetError
`func (o *GeoAuditRun) UnsetError()`

UnsetError ensures that no value is present for Error, not even an explicit nil
### GetEngineVersion

`func (o *GeoAuditRun) GetEngineVersion() string`

GetEngineVersion returns the EngineVersion field if non-nil, zero value otherwise.

### GetEngineVersionOk

`func (o *GeoAuditRun) GetEngineVersionOk() (*string, bool)`

GetEngineVersionOk returns a tuple with the EngineVersion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEngineVersion

`func (o *GeoAuditRun) SetEngineVersion(v string)`

SetEngineVersion sets EngineVersion field to given value.

### HasEngineVersion

`func (o *GeoAuditRun) HasEngineVersion() bool`

HasEngineVersion returns a boolean if a field has been set.

### SetEngineVersionNil

`func (o *GeoAuditRun) SetEngineVersionNil(b bool)`

 SetEngineVersionNil sets the value for EngineVersion to be an explicit nil

### UnsetEngineVersion
`func (o *GeoAuditRun) UnsetEngineVersion()`

UnsetEngineVersion ensures that no value is present for EngineVersion, not even an explicit nil
### GetCreatedAt

`func (o *GeoAuditRun) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *GeoAuditRun) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *GeoAuditRun) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *GeoAuditRun) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetFinishedAt

`func (o *GeoAuditRun) GetFinishedAt() time.Time`

GetFinishedAt returns the FinishedAt field if non-nil, zero value otherwise.

### GetFinishedAtOk

`func (o *GeoAuditRun) GetFinishedAtOk() (*time.Time, bool)`

GetFinishedAtOk returns a tuple with the FinishedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFinishedAt

`func (o *GeoAuditRun) SetFinishedAt(v time.Time)`

SetFinishedAt sets FinishedAt field to given value.

### HasFinishedAt

`func (o *GeoAuditRun) HasFinishedAt() bool`

HasFinishedAt returns a boolean if a field has been set.

### SetFinishedAtNil

`func (o *GeoAuditRun) SetFinishedAtNil(b bool)`

 SetFinishedAtNil sets the value for FinishedAt to be an explicit nil

### UnsetFinishedAt
`func (o *GeoAuditRun) UnsetFinishedAt()`

UnsetFinishedAt ensures that no value is present for FinishedAt, not even an explicit nil
### GetAppUrl

`func (o *GeoAuditRun) GetAppUrl() string`

GetAppUrl returns the AppUrl field if non-nil, zero value otherwise.

### GetAppUrlOk

`func (o *GeoAuditRun) GetAppUrlOk() (*string, bool)`

GetAppUrlOk returns a tuple with the AppUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAppUrl

`func (o *GeoAuditRun) SetAppUrl(v string)`

SetAppUrl sets AppUrl field to given value.

### HasAppUrl

`func (o *GeoAuditRun) HasAppUrl() bool`

HasAppUrl returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


