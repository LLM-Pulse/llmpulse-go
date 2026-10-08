# GeoAuditIssue

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **int32** |  | [optional] 
**CheckKey** | Pointer to **string** |  | [optional] 
**CheckTitle** | Pointer to **NullableString** |  | [optional] 
**SubjectKey** | Pointer to **string** |  | [optional] 
**Subject** | Pointer to **NullableString** |  | [optional] 
**Severity** | Pointer to **string** |  | [optional] 
**State** | Pointer to **string** |  | [optional] 
**Badge** | Pointer to **string** | How the latest comparable run moved the issue | [optional] 
**Accepted** | Pointer to **bool** |  | [optional] 
**AcceptedAt** | Pointer to **NullableTime** |  | [optional] 
**RegressionCount** | Pointer to **int32** |  | [optional] 
**Evidence** | Pointer to **map[string]interface{}** |  | [optional] 
**UpdatedAt** | Pointer to **time.Time** |  | [optional] 

## Methods

### NewGeoAuditIssue

`func NewGeoAuditIssue() *GeoAuditIssue`

NewGeoAuditIssue instantiates a new GeoAuditIssue object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGeoAuditIssueWithDefaults

`func NewGeoAuditIssueWithDefaults() *GeoAuditIssue`

NewGeoAuditIssueWithDefaults instantiates a new GeoAuditIssue object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *GeoAuditIssue) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *GeoAuditIssue) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *GeoAuditIssue) SetId(v int32)`

SetId sets Id field to given value.

### HasId

`func (o *GeoAuditIssue) HasId() bool`

HasId returns a boolean if a field has been set.

### GetCheckKey

`func (o *GeoAuditIssue) GetCheckKey() string`

GetCheckKey returns the CheckKey field if non-nil, zero value otherwise.

### GetCheckKeyOk

`func (o *GeoAuditIssue) GetCheckKeyOk() (*string, bool)`

GetCheckKeyOk returns a tuple with the CheckKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCheckKey

`func (o *GeoAuditIssue) SetCheckKey(v string)`

SetCheckKey sets CheckKey field to given value.

### HasCheckKey

`func (o *GeoAuditIssue) HasCheckKey() bool`

HasCheckKey returns a boolean if a field has been set.

### GetCheckTitle

`func (o *GeoAuditIssue) GetCheckTitle() string`

GetCheckTitle returns the CheckTitle field if non-nil, zero value otherwise.

### GetCheckTitleOk

`func (o *GeoAuditIssue) GetCheckTitleOk() (*string, bool)`

GetCheckTitleOk returns a tuple with the CheckTitle field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCheckTitle

`func (o *GeoAuditIssue) SetCheckTitle(v string)`

SetCheckTitle sets CheckTitle field to given value.

### HasCheckTitle

`func (o *GeoAuditIssue) HasCheckTitle() bool`

HasCheckTitle returns a boolean if a field has been set.

### SetCheckTitleNil

`func (o *GeoAuditIssue) SetCheckTitleNil(b bool)`

 SetCheckTitleNil sets the value for CheckTitle to be an explicit nil

### UnsetCheckTitle
`func (o *GeoAuditIssue) UnsetCheckTitle()`

UnsetCheckTitle ensures that no value is present for CheckTitle, not even an explicit nil
### GetSubjectKey

`func (o *GeoAuditIssue) GetSubjectKey() string`

GetSubjectKey returns the SubjectKey field if non-nil, zero value otherwise.

### GetSubjectKeyOk

`func (o *GeoAuditIssue) GetSubjectKeyOk() (*string, bool)`

GetSubjectKeyOk returns a tuple with the SubjectKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubjectKey

`func (o *GeoAuditIssue) SetSubjectKey(v string)`

SetSubjectKey sets SubjectKey field to given value.

### HasSubjectKey

`func (o *GeoAuditIssue) HasSubjectKey() bool`

HasSubjectKey returns a boolean if a field has been set.

### GetSubject

`func (o *GeoAuditIssue) GetSubject() string`

GetSubject returns the Subject field if non-nil, zero value otherwise.

### GetSubjectOk

`func (o *GeoAuditIssue) GetSubjectOk() (*string, bool)`

GetSubjectOk returns a tuple with the Subject field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubject

`func (o *GeoAuditIssue) SetSubject(v string)`

SetSubject sets Subject field to given value.

### HasSubject

`func (o *GeoAuditIssue) HasSubject() bool`

HasSubject returns a boolean if a field has been set.

### SetSubjectNil

`func (o *GeoAuditIssue) SetSubjectNil(b bool)`

 SetSubjectNil sets the value for Subject to be an explicit nil

### UnsetSubject
`func (o *GeoAuditIssue) UnsetSubject()`

UnsetSubject ensures that no value is present for Subject, not even an explicit nil
### GetSeverity

`func (o *GeoAuditIssue) GetSeverity() string`

GetSeverity returns the Severity field if non-nil, zero value otherwise.

### GetSeverityOk

`func (o *GeoAuditIssue) GetSeverityOk() (*string, bool)`

GetSeverityOk returns a tuple with the Severity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSeverity

`func (o *GeoAuditIssue) SetSeverity(v string)`

SetSeverity sets Severity field to given value.

### HasSeverity

`func (o *GeoAuditIssue) HasSeverity() bool`

HasSeverity returns a boolean if a field has been set.

### GetState

`func (o *GeoAuditIssue) GetState() string`

GetState returns the State field if non-nil, zero value otherwise.

### GetStateOk

`func (o *GeoAuditIssue) GetStateOk() (*string, bool)`

GetStateOk returns a tuple with the State field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetState

`func (o *GeoAuditIssue) SetState(v string)`

SetState sets State field to given value.

### HasState

`func (o *GeoAuditIssue) HasState() bool`

HasState returns a boolean if a field has been set.

### GetBadge

`func (o *GeoAuditIssue) GetBadge() string`

GetBadge returns the Badge field if non-nil, zero value otherwise.

### GetBadgeOk

`func (o *GeoAuditIssue) GetBadgeOk() (*string, bool)`

GetBadgeOk returns a tuple with the Badge field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBadge

`func (o *GeoAuditIssue) SetBadge(v string)`

SetBadge sets Badge field to given value.

### HasBadge

`func (o *GeoAuditIssue) HasBadge() bool`

HasBadge returns a boolean if a field has been set.

### GetAccepted

`func (o *GeoAuditIssue) GetAccepted() bool`

GetAccepted returns the Accepted field if non-nil, zero value otherwise.

### GetAcceptedOk

`func (o *GeoAuditIssue) GetAcceptedOk() (*bool, bool)`

GetAcceptedOk returns a tuple with the Accepted field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccepted

`func (o *GeoAuditIssue) SetAccepted(v bool)`

SetAccepted sets Accepted field to given value.

### HasAccepted

`func (o *GeoAuditIssue) HasAccepted() bool`

HasAccepted returns a boolean if a field has been set.

### GetAcceptedAt

`func (o *GeoAuditIssue) GetAcceptedAt() time.Time`

GetAcceptedAt returns the AcceptedAt field if non-nil, zero value otherwise.

### GetAcceptedAtOk

`func (o *GeoAuditIssue) GetAcceptedAtOk() (*time.Time, bool)`

GetAcceptedAtOk returns a tuple with the AcceptedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAcceptedAt

`func (o *GeoAuditIssue) SetAcceptedAt(v time.Time)`

SetAcceptedAt sets AcceptedAt field to given value.

### HasAcceptedAt

`func (o *GeoAuditIssue) HasAcceptedAt() bool`

HasAcceptedAt returns a boolean if a field has been set.

### SetAcceptedAtNil

`func (o *GeoAuditIssue) SetAcceptedAtNil(b bool)`

 SetAcceptedAtNil sets the value for AcceptedAt to be an explicit nil

### UnsetAcceptedAt
`func (o *GeoAuditIssue) UnsetAcceptedAt()`

UnsetAcceptedAt ensures that no value is present for AcceptedAt, not even an explicit nil
### GetRegressionCount

`func (o *GeoAuditIssue) GetRegressionCount() int32`

GetRegressionCount returns the RegressionCount field if non-nil, zero value otherwise.

### GetRegressionCountOk

`func (o *GeoAuditIssue) GetRegressionCountOk() (*int32, bool)`

GetRegressionCountOk returns a tuple with the RegressionCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRegressionCount

`func (o *GeoAuditIssue) SetRegressionCount(v int32)`

SetRegressionCount sets RegressionCount field to given value.

### HasRegressionCount

`func (o *GeoAuditIssue) HasRegressionCount() bool`

HasRegressionCount returns a boolean if a field has been set.

### GetEvidence

`func (o *GeoAuditIssue) GetEvidence() map[string]interface{}`

GetEvidence returns the Evidence field if non-nil, zero value otherwise.

### GetEvidenceOk

`func (o *GeoAuditIssue) GetEvidenceOk() (*map[string]interface{}, bool)`

GetEvidenceOk returns a tuple with the Evidence field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEvidence

`func (o *GeoAuditIssue) SetEvidence(v map[string]interface{})`

SetEvidence sets Evidence field to given value.

### HasEvidence

`func (o *GeoAuditIssue) HasEvidence() bool`

HasEvidence returns a boolean if a field has been set.

### GetUpdatedAt

`func (o *GeoAuditIssue) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *GeoAuditIssue) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *GeoAuditIssue) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *GeoAuditIssue) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


