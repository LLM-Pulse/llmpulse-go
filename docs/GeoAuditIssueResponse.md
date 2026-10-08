# GeoAuditIssueResponse

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
**ProjectId** | Pointer to **int32** |  | [optional] 
**RequestId** | Pointer to **string** |  | [optional] 

## Methods

### NewGeoAuditIssueResponse

`func NewGeoAuditIssueResponse() *GeoAuditIssueResponse`

NewGeoAuditIssueResponse instantiates a new GeoAuditIssueResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGeoAuditIssueResponseWithDefaults

`func NewGeoAuditIssueResponseWithDefaults() *GeoAuditIssueResponse`

NewGeoAuditIssueResponseWithDefaults instantiates a new GeoAuditIssueResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *GeoAuditIssueResponse) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *GeoAuditIssueResponse) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *GeoAuditIssueResponse) SetId(v int32)`

SetId sets Id field to given value.

### HasId

`func (o *GeoAuditIssueResponse) HasId() bool`

HasId returns a boolean if a field has been set.

### GetCheckKey

`func (o *GeoAuditIssueResponse) GetCheckKey() string`

GetCheckKey returns the CheckKey field if non-nil, zero value otherwise.

### GetCheckKeyOk

`func (o *GeoAuditIssueResponse) GetCheckKeyOk() (*string, bool)`

GetCheckKeyOk returns a tuple with the CheckKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCheckKey

`func (o *GeoAuditIssueResponse) SetCheckKey(v string)`

SetCheckKey sets CheckKey field to given value.

### HasCheckKey

`func (o *GeoAuditIssueResponse) HasCheckKey() bool`

HasCheckKey returns a boolean if a field has been set.

### GetCheckTitle

`func (o *GeoAuditIssueResponse) GetCheckTitle() string`

GetCheckTitle returns the CheckTitle field if non-nil, zero value otherwise.

### GetCheckTitleOk

`func (o *GeoAuditIssueResponse) GetCheckTitleOk() (*string, bool)`

GetCheckTitleOk returns a tuple with the CheckTitle field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCheckTitle

`func (o *GeoAuditIssueResponse) SetCheckTitle(v string)`

SetCheckTitle sets CheckTitle field to given value.

### HasCheckTitle

`func (o *GeoAuditIssueResponse) HasCheckTitle() bool`

HasCheckTitle returns a boolean if a field has been set.

### SetCheckTitleNil

`func (o *GeoAuditIssueResponse) SetCheckTitleNil(b bool)`

 SetCheckTitleNil sets the value for CheckTitle to be an explicit nil

### UnsetCheckTitle
`func (o *GeoAuditIssueResponse) UnsetCheckTitle()`

UnsetCheckTitle ensures that no value is present for CheckTitle, not even an explicit nil
### GetSubjectKey

`func (o *GeoAuditIssueResponse) GetSubjectKey() string`

GetSubjectKey returns the SubjectKey field if non-nil, zero value otherwise.

### GetSubjectKeyOk

`func (o *GeoAuditIssueResponse) GetSubjectKeyOk() (*string, bool)`

GetSubjectKeyOk returns a tuple with the SubjectKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubjectKey

`func (o *GeoAuditIssueResponse) SetSubjectKey(v string)`

SetSubjectKey sets SubjectKey field to given value.

### HasSubjectKey

`func (o *GeoAuditIssueResponse) HasSubjectKey() bool`

HasSubjectKey returns a boolean if a field has been set.

### GetSubject

`func (o *GeoAuditIssueResponse) GetSubject() string`

GetSubject returns the Subject field if non-nil, zero value otherwise.

### GetSubjectOk

`func (o *GeoAuditIssueResponse) GetSubjectOk() (*string, bool)`

GetSubjectOk returns a tuple with the Subject field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubject

`func (o *GeoAuditIssueResponse) SetSubject(v string)`

SetSubject sets Subject field to given value.

### HasSubject

`func (o *GeoAuditIssueResponse) HasSubject() bool`

HasSubject returns a boolean if a field has been set.

### SetSubjectNil

`func (o *GeoAuditIssueResponse) SetSubjectNil(b bool)`

 SetSubjectNil sets the value for Subject to be an explicit nil

### UnsetSubject
`func (o *GeoAuditIssueResponse) UnsetSubject()`

UnsetSubject ensures that no value is present for Subject, not even an explicit nil
### GetSeverity

`func (o *GeoAuditIssueResponse) GetSeverity() string`

GetSeverity returns the Severity field if non-nil, zero value otherwise.

### GetSeverityOk

`func (o *GeoAuditIssueResponse) GetSeverityOk() (*string, bool)`

GetSeverityOk returns a tuple with the Severity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSeverity

`func (o *GeoAuditIssueResponse) SetSeverity(v string)`

SetSeverity sets Severity field to given value.

### HasSeverity

`func (o *GeoAuditIssueResponse) HasSeverity() bool`

HasSeverity returns a boolean if a field has been set.

### GetState

`func (o *GeoAuditIssueResponse) GetState() string`

GetState returns the State field if non-nil, zero value otherwise.

### GetStateOk

`func (o *GeoAuditIssueResponse) GetStateOk() (*string, bool)`

GetStateOk returns a tuple with the State field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetState

`func (o *GeoAuditIssueResponse) SetState(v string)`

SetState sets State field to given value.

### HasState

`func (o *GeoAuditIssueResponse) HasState() bool`

HasState returns a boolean if a field has been set.

### GetBadge

`func (o *GeoAuditIssueResponse) GetBadge() string`

GetBadge returns the Badge field if non-nil, zero value otherwise.

### GetBadgeOk

`func (o *GeoAuditIssueResponse) GetBadgeOk() (*string, bool)`

GetBadgeOk returns a tuple with the Badge field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBadge

`func (o *GeoAuditIssueResponse) SetBadge(v string)`

SetBadge sets Badge field to given value.

### HasBadge

`func (o *GeoAuditIssueResponse) HasBadge() bool`

HasBadge returns a boolean if a field has been set.

### GetAccepted

`func (o *GeoAuditIssueResponse) GetAccepted() bool`

GetAccepted returns the Accepted field if non-nil, zero value otherwise.

### GetAcceptedOk

`func (o *GeoAuditIssueResponse) GetAcceptedOk() (*bool, bool)`

GetAcceptedOk returns a tuple with the Accepted field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccepted

`func (o *GeoAuditIssueResponse) SetAccepted(v bool)`

SetAccepted sets Accepted field to given value.

### HasAccepted

`func (o *GeoAuditIssueResponse) HasAccepted() bool`

HasAccepted returns a boolean if a field has been set.

### GetAcceptedAt

`func (o *GeoAuditIssueResponse) GetAcceptedAt() time.Time`

GetAcceptedAt returns the AcceptedAt field if non-nil, zero value otherwise.

### GetAcceptedAtOk

`func (o *GeoAuditIssueResponse) GetAcceptedAtOk() (*time.Time, bool)`

GetAcceptedAtOk returns a tuple with the AcceptedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAcceptedAt

`func (o *GeoAuditIssueResponse) SetAcceptedAt(v time.Time)`

SetAcceptedAt sets AcceptedAt field to given value.

### HasAcceptedAt

`func (o *GeoAuditIssueResponse) HasAcceptedAt() bool`

HasAcceptedAt returns a boolean if a field has been set.

### SetAcceptedAtNil

`func (o *GeoAuditIssueResponse) SetAcceptedAtNil(b bool)`

 SetAcceptedAtNil sets the value for AcceptedAt to be an explicit nil

### UnsetAcceptedAt
`func (o *GeoAuditIssueResponse) UnsetAcceptedAt()`

UnsetAcceptedAt ensures that no value is present for AcceptedAt, not even an explicit nil
### GetRegressionCount

`func (o *GeoAuditIssueResponse) GetRegressionCount() int32`

GetRegressionCount returns the RegressionCount field if non-nil, zero value otherwise.

### GetRegressionCountOk

`func (o *GeoAuditIssueResponse) GetRegressionCountOk() (*int32, bool)`

GetRegressionCountOk returns a tuple with the RegressionCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRegressionCount

`func (o *GeoAuditIssueResponse) SetRegressionCount(v int32)`

SetRegressionCount sets RegressionCount field to given value.

### HasRegressionCount

`func (o *GeoAuditIssueResponse) HasRegressionCount() bool`

HasRegressionCount returns a boolean if a field has been set.

### GetEvidence

`func (o *GeoAuditIssueResponse) GetEvidence() map[string]interface{}`

GetEvidence returns the Evidence field if non-nil, zero value otherwise.

### GetEvidenceOk

`func (o *GeoAuditIssueResponse) GetEvidenceOk() (*map[string]interface{}, bool)`

GetEvidenceOk returns a tuple with the Evidence field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEvidence

`func (o *GeoAuditIssueResponse) SetEvidence(v map[string]interface{})`

SetEvidence sets Evidence field to given value.

### HasEvidence

`func (o *GeoAuditIssueResponse) HasEvidence() bool`

HasEvidence returns a boolean if a field has been set.

### GetUpdatedAt

`func (o *GeoAuditIssueResponse) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *GeoAuditIssueResponse) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *GeoAuditIssueResponse) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *GeoAuditIssueResponse) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.

### GetProjectId

`func (o *GeoAuditIssueResponse) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *GeoAuditIssueResponse) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *GeoAuditIssueResponse) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.

### HasProjectId

`func (o *GeoAuditIssueResponse) HasProjectId() bool`

HasProjectId returns a boolean if a field has been set.

### GetRequestId

`func (o *GeoAuditIssueResponse) GetRequestId() string`

GetRequestId returns the RequestId field if non-nil, zero value otherwise.

### GetRequestIdOk

`func (o *GeoAuditIssueResponse) GetRequestIdOk() (*string, bool)`

GetRequestIdOk returns a tuple with the RequestId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestId

`func (o *GeoAuditIssueResponse) SetRequestId(v string)`

SetRequestId sets RequestId field to given value.

### HasRequestId

`func (o *GeoAuditIssueResponse) HasRequestId() bool`

HasRequestId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


