# GeoAuditRunDetail

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
**Metrics** | Pointer to **map[string]float32** |  | [optional] 
**ResultData** | Pointer to **map[string]interface{}** | The full report of the run, in the shape of the matching technical GEO report type | [optional] 
**RequestId** | Pointer to **string** |  | [optional] 

## Methods

### NewGeoAuditRunDetail

`func NewGeoAuditRunDetail() *GeoAuditRunDetail`

NewGeoAuditRunDetail instantiates a new GeoAuditRunDetail object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGeoAuditRunDetailWithDefaults

`func NewGeoAuditRunDetailWithDefaults() *GeoAuditRunDetail`

NewGeoAuditRunDetailWithDefaults instantiates a new GeoAuditRunDetail object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSequence

`func (o *GeoAuditRunDetail) GetSequence() int32`

GetSequence returns the Sequence field if non-nil, zero value otherwise.

### GetSequenceOk

`func (o *GeoAuditRunDetail) GetSequenceOk() (*int32, bool)`

GetSequenceOk returns a tuple with the Sequence field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSequence

`func (o *GeoAuditRunDetail) SetSequence(v int32)`

SetSequence sets Sequence field to given value.

### HasSequence

`func (o *GeoAuditRunDetail) HasSequence() bool`

HasSequence returns a boolean if a field has been set.

### GetStatus

`func (o *GeoAuditRunDetail) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *GeoAuditRunDetail) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *GeoAuditRunDetail) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *GeoAuditRunDetail) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetTrigger

`func (o *GeoAuditRunDetail) GetTrigger() string`

GetTrigger returns the Trigger field if non-nil, zero value otherwise.

### GetTriggerOk

`func (o *GeoAuditRunDetail) GetTriggerOk() (*string, bool)`

GetTriggerOk returns a tuple with the Trigger field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrigger

`func (o *GeoAuditRunDetail) SetTrigger(v string)`

SetTrigger sets Trigger field to given value.

### HasTrigger

`func (o *GeoAuditRunDetail) HasTrigger() bool`

HasTrigger returns a boolean if a field has been set.

### GetScore

`func (o *GeoAuditRunDetail) GetScore() float32`

GetScore returns the Score field if non-nil, zero value otherwise.

### GetScoreOk

`func (o *GeoAuditRunDetail) GetScoreOk() (*float32, bool)`

GetScoreOk returns a tuple with the Score field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScore

`func (o *GeoAuditRunDetail) SetScore(v float32)`

SetScore sets Score field to given value.

### HasScore

`func (o *GeoAuditRunDetail) HasScore() bool`

HasScore returns a boolean if a field has been set.

### SetScoreNil

`func (o *GeoAuditRunDetail) SetScoreNil(b bool)`

 SetScoreNil sets the value for Score to be an explicit nil

### UnsetScore
`func (o *GeoAuditRunDetail) UnsetScore()`

UnsetScore ensures that no value is present for Score, not even an explicit nil
### GetGrade

`func (o *GeoAuditRunDetail) GetGrade() string`

GetGrade returns the Grade field if non-nil, zero value otherwise.

### GetGradeOk

`func (o *GeoAuditRunDetail) GetGradeOk() (*string, bool)`

GetGradeOk returns a tuple with the Grade field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGrade

`func (o *GeoAuditRunDetail) SetGrade(v string)`

SetGrade sets Grade field to given value.

### HasGrade

`func (o *GeoAuditRunDetail) HasGrade() bool`

HasGrade returns a boolean if a field has been set.

### SetGradeNil

`func (o *GeoAuditRunDetail) SetGradeNil(b bool)`

 SetGradeNil sets the value for Grade to be an explicit nil

### UnsetGrade
`func (o *GeoAuditRunDetail) UnsetGrade()`

UnsetGrade ensures that no value is present for Grade, not even an explicit nil
### GetScoreDelta

`func (o *GeoAuditRunDetail) GetScoreDelta() float32`

GetScoreDelta returns the ScoreDelta field if non-nil, zero value otherwise.

### GetScoreDeltaOk

`func (o *GeoAuditRunDetail) GetScoreDeltaOk() (*float32, bool)`

GetScoreDeltaOk returns a tuple with the ScoreDelta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScoreDelta

`func (o *GeoAuditRunDetail) SetScoreDelta(v float32)`

SetScoreDelta sets ScoreDelta field to given value.

### HasScoreDelta

`func (o *GeoAuditRunDetail) HasScoreDelta() bool`

HasScoreDelta returns a boolean if a field has been set.

### SetScoreDeltaNil

`func (o *GeoAuditRunDetail) SetScoreDeltaNil(b bool)`

 SetScoreDeltaNil sets the value for ScoreDelta to be an explicit nil

### UnsetScoreDelta
`func (o *GeoAuditRunDetail) UnsetScoreDelta()`

UnsetScoreDelta ensures that no value is present for ScoreDelta, not even an explicit nil
### GetComparableToPrevious

`func (o *GeoAuditRunDetail) GetComparableToPrevious() bool`

GetComparableToPrevious returns the ComparableToPrevious field if non-nil, zero value otherwise.

### GetComparableToPreviousOk

`func (o *GeoAuditRunDetail) GetComparableToPreviousOk() (*bool, bool)`

GetComparableToPreviousOk returns a tuple with the ComparableToPrevious field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComparableToPrevious

`func (o *GeoAuditRunDetail) SetComparableToPrevious(v bool)`

SetComparableToPrevious sets ComparableToPrevious field to given value.

### HasComparableToPrevious

`func (o *GeoAuditRunDetail) HasComparableToPrevious() bool`

HasComparableToPrevious returns a boolean if a field has been set.

### GetNewIssues

`func (o *GeoAuditRunDetail) GetNewIssues() int32`

GetNewIssues returns the NewIssues field if non-nil, zero value otherwise.

### GetNewIssuesOk

`func (o *GeoAuditRunDetail) GetNewIssuesOk() (*int32, bool)`

GetNewIssuesOk returns a tuple with the NewIssues field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNewIssues

`func (o *GeoAuditRunDetail) SetNewIssues(v int32)`

SetNewIssues sets NewIssues field to given value.

### HasNewIssues

`func (o *GeoAuditRunDetail) HasNewIssues() bool`

HasNewIssues returns a boolean if a field has been set.

### GetFixedIssues

`func (o *GeoAuditRunDetail) GetFixedIssues() int32`

GetFixedIssues returns the FixedIssues field if non-nil, zero value otherwise.

### GetFixedIssuesOk

`func (o *GeoAuditRunDetail) GetFixedIssuesOk() (*int32, bool)`

GetFixedIssuesOk returns a tuple with the FixedIssues field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFixedIssues

`func (o *GeoAuditRunDetail) SetFixedIssues(v int32)`

SetFixedIssues sets FixedIssues field to given value.

### HasFixedIssues

`func (o *GeoAuditRunDetail) HasFixedIssues() bool`

HasFixedIssues returns a boolean if a field has been set.

### GetRegressedIssues

`func (o *GeoAuditRunDetail) GetRegressedIssues() int32`

GetRegressedIssues returns the RegressedIssues field if non-nil, zero value otherwise.

### GetRegressedIssuesOk

`func (o *GeoAuditRunDetail) GetRegressedIssuesOk() (*int32, bool)`

GetRegressedIssuesOk returns a tuple with the RegressedIssues field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRegressedIssues

`func (o *GeoAuditRunDetail) SetRegressedIssues(v int32)`

SetRegressedIssues sets RegressedIssues field to given value.

### HasRegressedIssues

`func (o *GeoAuditRunDetail) HasRegressedIssues() bool`

HasRegressedIssues returns a boolean if a field has been set.

### GetError

`func (o *GeoAuditRunDetail) GetError() string`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *GeoAuditRunDetail) GetErrorOk() (*string, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *GeoAuditRunDetail) SetError(v string)`

SetError sets Error field to given value.

### HasError

`func (o *GeoAuditRunDetail) HasError() bool`

HasError returns a boolean if a field has been set.

### SetErrorNil

`func (o *GeoAuditRunDetail) SetErrorNil(b bool)`

 SetErrorNil sets the value for Error to be an explicit nil

### UnsetError
`func (o *GeoAuditRunDetail) UnsetError()`

UnsetError ensures that no value is present for Error, not even an explicit nil
### GetEngineVersion

`func (o *GeoAuditRunDetail) GetEngineVersion() string`

GetEngineVersion returns the EngineVersion field if non-nil, zero value otherwise.

### GetEngineVersionOk

`func (o *GeoAuditRunDetail) GetEngineVersionOk() (*string, bool)`

GetEngineVersionOk returns a tuple with the EngineVersion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEngineVersion

`func (o *GeoAuditRunDetail) SetEngineVersion(v string)`

SetEngineVersion sets EngineVersion field to given value.

### HasEngineVersion

`func (o *GeoAuditRunDetail) HasEngineVersion() bool`

HasEngineVersion returns a boolean if a field has been set.

### SetEngineVersionNil

`func (o *GeoAuditRunDetail) SetEngineVersionNil(b bool)`

 SetEngineVersionNil sets the value for EngineVersion to be an explicit nil

### UnsetEngineVersion
`func (o *GeoAuditRunDetail) UnsetEngineVersion()`

UnsetEngineVersion ensures that no value is present for EngineVersion, not even an explicit nil
### GetCreatedAt

`func (o *GeoAuditRunDetail) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *GeoAuditRunDetail) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *GeoAuditRunDetail) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *GeoAuditRunDetail) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetFinishedAt

`func (o *GeoAuditRunDetail) GetFinishedAt() time.Time`

GetFinishedAt returns the FinishedAt field if non-nil, zero value otherwise.

### GetFinishedAtOk

`func (o *GeoAuditRunDetail) GetFinishedAtOk() (*time.Time, bool)`

GetFinishedAtOk returns a tuple with the FinishedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFinishedAt

`func (o *GeoAuditRunDetail) SetFinishedAt(v time.Time)`

SetFinishedAt sets FinishedAt field to given value.

### HasFinishedAt

`func (o *GeoAuditRunDetail) HasFinishedAt() bool`

HasFinishedAt returns a boolean if a field has been set.

### SetFinishedAtNil

`func (o *GeoAuditRunDetail) SetFinishedAtNil(b bool)`

 SetFinishedAtNil sets the value for FinishedAt to be an explicit nil

### UnsetFinishedAt
`func (o *GeoAuditRunDetail) UnsetFinishedAt()`

UnsetFinishedAt ensures that no value is present for FinishedAt, not even an explicit nil
### GetAppUrl

`func (o *GeoAuditRunDetail) GetAppUrl() string`

GetAppUrl returns the AppUrl field if non-nil, zero value otherwise.

### GetAppUrlOk

`func (o *GeoAuditRunDetail) GetAppUrlOk() (*string, bool)`

GetAppUrlOk returns a tuple with the AppUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAppUrl

`func (o *GeoAuditRunDetail) SetAppUrl(v string)`

SetAppUrl sets AppUrl field to given value.

### HasAppUrl

`func (o *GeoAuditRunDetail) HasAppUrl() bool`

HasAppUrl returns a boolean if a field has been set.

### GetProjectId

`func (o *GeoAuditRunDetail) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *GeoAuditRunDetail) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *GeoAuditRunDetail) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.

### HasProjectId

`func (o *GeoAuditRunDetail) HasProjectId() bool`

HasProjectId returns a boolean if a field has been set.

### GetMetrics

`func (o *GeoAuditRunDetail) GetMetrics() map[string]float32`

GetMetrics returns the Metrics field if non-nil, zero value otherwise.

### GetMetricsOk

`func (o *GeoAuditRunDetail) GetMetricsOk() (*map[string]float32, bool)`

GetMetricsOk returns a tuple with the Metrics field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetrics

`func (o *GeoAuditRunDetail) SetMetrics(v map[string]float32)`

SetMetrics sets Metrics field to given value.

### HasMetrics

`func (o *GeoAuditRunDetail) HasMetrics() bool`

HasMetrics returns a boolean if a field has been set.

### GetResultData

`func (o *GeoAuditRunDetail) GetResultData() map[string]interface{}`

GetResultData returns the ResultData field if non-nil, zero value otherwise.

### GetResultDataOk

`func (o *GeoAuditRunDetail) GetResultDataOk() (*map[string]interface{}, bool)`

GetResultDataOk returns a tuple with the ResultData field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResultData

`func (o *GeoAuditRunDetail) SetResultData(v map[string]interface{})`

SetResultData sets ResultData field to given value.

### HasResultData

`func (o *GeoAuditRunDetail) HasResultData() bool`

HasResultData returns a boolean if a field has been set.

### SetResultDataNil

`func (o *GeoAuditRunDetail) SetResultDataNil(b bool)`

 SetResultDataNil sets the value for ResultData to be an explicit nil

### UnsetResultData
`func (o *GeoAuditRunDetail) UnsetResultData()`

UnsetResultData ensures that no value is present for ResultData, not even an explicit nil
### GetRequestId

`func (o *GeoAuditRunDetail) GetRequestId() string`

GetRequestId returns the RequestId field if non-nil, zero value otherwise.

### GetRequestIdOk

`func (o *GeoAuditRunDetail) GetRequestIdOk() (*string, bool)`

GetRequestIdOk returns a tuple with the RequestId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestId

`func (o *GeoAuditRunDetail) SetRequestId(v string)`

SetRequestId sets RequestId field to given value.

### HasRequestId

`func (o *GeoAuditRunDetail) HasRequestId() bool`

HasRequestId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


