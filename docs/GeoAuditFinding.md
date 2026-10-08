# GeoAuditFinding

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CheckKey** | Pointer to **string** | Stable key of the check within its audit type | [optional] 
**CheckTitle** | Pointer to **NullableString** |  | [optional] 
**SubjectKey** | Pointer to **string** | What the check is about (site for site-wide checks, a bot slug for robots.txt bot checks) | [optional] 
**Subject** | Pointer to **NullableString** |  | [optional] 
**Status** | Pointer to **string** |  | [optional] 
**Severity** | Pointer to **string** |  | [optional] 
**Evidence** | Pointer to **map[string]interface{}** |  | [optional] 

## Methods

### NewGeoAuditFinding

`func NewGeoAuditFinding() *GeoAuditFinding`

NewGeoAuditFinding instantiates a new GeoAuditFinding object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGeoAuditFindingWithDefaults

`func NewGeoAuditFindingWithDefaults() *GeoAuditFinding`

NewGeoAuditFindingWithDefaults instantiates a new GeoAuditFinding object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCheckKey

`func (o *GeoAuditFinding) GetCheckKey() string`

GetCheckKey returns the CheckKey field if non-nil, zero value otherwise.

### GetCheckKeyOk

`func (o *GeoAuditFinding) GetCheckKeyOk() (*string, bool)`

GetCheckKeyOk returns a tuple with the CheckKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCheckKey

`func (o *GeoAuditFinding) SetCheckKey(v string)`

SetCheckKey sets CheckKey field to given value.

### HasCheckKey

`func (o *GeoAuditFinding) HasCheckKey() bool`

HasCheckKey returns a boolean if a field has been set.

### GetCheckTitle

`func (o *GeoAuditFinding) GetCheckTitle() string`

GetCheckTitle returns the CheckTitle field if non-nil, zero value otherwise.

### GetCheckTitleOk

`func (o *GeoAuditFinding) GetCheckTitleOk() (*string, bool)`

GetCheckTitleOk returns a tuple with the CheckTitle field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCheckTitle

`func (o *GeoAuditFinding) SetCheckTitle(v string)`

SetCheckTitle sets CheckTitle field to given value.

### HasCheckTitle

`func (o *GeoAuditFinding) HasCheckTitle() bool`

HasCheckTitle returns a boolean if a field has been set.

### SetCheckTitleNil

`func (o *GeoAuditFinding) SetCheckTitleNil(b bool)`

 SetCheckTitleNil sets the value for CheckTitle to be an explicit nil

### UnsetCheckTitle
`func (o *GeoAuditFinding) UnsetCheckTitle()`

UnsetCheckTitle ensures that no value is present for CheckTitle, not even an explicit nil
### GetSubjectKey

`func (o *GeoAuditFinding) GetSubjectKey() string`

GetSubjectKey returns the SubjectKey field if non-nil, zero value otherwise.

### GetSubjectKeyOk

`func (o *GeoAuditFinding) GetSubjectKeyOk() (*string, bool)`

GetSubjectKeyOk returns a tuple with the SubjectKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubjectKey

`func (o *GeoAuditFinding) SetSubjectKey(v string)`

SetSubjectKey sets SubjectKey field to given value.

### HasSubjectKey

`func (o *GeoAuditFinding) HasSubjectKey() bool`

HasSubjectKey returns a boolean if a field has been set.

### GetSubject

`func (o *GeoAuditFinding) GetSubject() string`

GetSubject returns the Subject field if non-nil, zero value otherwise.

### GetSubjectOk

`func (o *GeoAuditFinding) GetSubjectOk() (*string, bool)`

GetSubjectOk returns a tuple with the Subject field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubject

`func (o *GeoAuditFinding) SetSubject(v string)`

SetSubject sets Subject field to given value.

### HasSubject

`func (o *GeoAuditFinding) HasSubject() bool`

HasSubject returns a boolean if a field has been set.

### SetSubjectNil

`func (o *GeoAuditFinding) SetSubjectNil(b bool)`

 SetSubjectNil sets the value for Subject to be an explicit nil

### UnsetSubject
`func (o *GeoAuditFinding) UnsetSubject()`

UnsetSubject ensures that no value is present for Subject, not even an explicit nil
### GetStatus

`func (o *GeoAuditFinding) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *GeoAuditFinding) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *GeoAuditFinding) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *GeoAuditFinding) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetSeverity

`func (o *GeoAuditFinding) GetSeverity() string`

GetSeverity returns the Severity field if non-nil, zero value otherwise.

### GetSeverityOk

`func (o *GeoAuditFinding) GetSeverityOk() (*string, bool)`

GetSeverityOk returns a tuple with the Severity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSeverity

`func (o *GeoAuditFinding) SetSeverity(v string)`

SetSeverity sets Severity field to given value.

### HasSeverity

`func (o *GeoAuditFinding) HasSeverity() bool`

HasSeverity returns a boolean if a field has been set.

### GetEvidence

`func (o *GeoAuditFinding) GetEvidence() map[string]interface{}`

GetEvidence returns the Evidence field if non-nil, zero value otherwise.

### GetEvidenceOk

`func (o *GeoAuditFinding) GetEvidenceOk() (*map[string]interface{}, bool)`

GetEvidenceOk returns a tuple with the Evidence field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEvidence

`func (o *GeoAuditFinding) SetEvidence(v map[string]interface{})`

SetEvidence sets Evidence field to given value.

### HasEvidence

`func (o *GeoAuditFinding) HasEvidence() bool`

HasEvidence returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


