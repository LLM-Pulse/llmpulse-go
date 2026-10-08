# GeoAudit

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | Stable audit id | [optional] 
**AuditType** | Pointer to **string** |  | [optional] 
**Target** | Pointer to **string** | The audited domain (site-wide types) or page URL, normalized | [optional] 
**CountryCode** | Pointer to **NullableString** |  | [optional] 
**Cadence** | Pointer to **string** |  | [optional] 
**Status** | Pointer to **string** |  | [optional] 
**PausedReason** | Pointer to **NullableString** | user, or unreachable when three runs in a row could not reach the site | [optional] 
**Schedule** | Pointer to [**NullableGeoAuditSchedule**](GeoAuditSchedule.md) |  | [optional] 
**NextRunAt** | Pointer to **NullableTime** |  | [optional] 
**EmailAlerts** | Pointer to **bool** |  | [optional] 
**RecurringAvailable** | Pointer to **bool** | Whether this audit type can run weekly or monthly | [optional] 
**ChecksTracked** | Pointer to **bool** | Whether runs of this type produce findings and issues, or a score only | [optional] 
**LatestRun** | Pointer to [**NullableGeoAuditRun**](GeoAuditRun.md) |  | [optional] 
**OpenIssues** | Pointer to **int32** |  | [optional] 
**OpenCriticalIssues** | Pointer to **int32** |  | [optional] 
**CreatedAt** | Pointer to **time.Time** |  | [optional] 
**AppUrl** | Pointer to **string** |  | [optional] 

## Methods

### NewGeoAudit

`func NewGeoAudit() *GeoAudit`

NewGeoAudit instantiates a new GeoAudit object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGeoAuditWithDefaults

`func NewGeoAuditWithDefaults() *GeoAudit`

NewGeoAuditWithDefaults instantiates a new GeoAudit object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *GeoAudit) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *GeoAudit) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *GeoAudit) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *GeoAudit) HasId() bool`

HasId returns a boolean if a field has been set.

### GetAuditType

`func (o *GeoAudit) GetAuditType() string`

GetAuditType returns the AuditType field if non-nil, zero value otherwise.

### GetAuditTypeOk

`func (o *GeoAudit) GetAuditTypeOk() (*string, bool)`

GetAuditTypeOk returns a tuple with the AuditType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAuditType

`func (o *GeoAudit) SetAuditType(v string)`

SetAuditType sets AuditType field to given value.

### HasAuditType

`func (o *GeoAudit) HasAuditType() bool`

HasAuditType returns a boolean if a field has been set.

### GetTarget

`func (o *GeoAudit) GetTarget() string`

GetTarget returns the Target field if non-nil, zero value otherwise.

### GetTargetOk

`func (o *GeoAudit) GetTargetOk() (*string, bool)`

GetTargetOk returns a tuple with the Target field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTarget

`func (o *GeoAudit) SetTarget(v string)`

SetTarget sets Target field to given value.

### HasTarget

`func (o *GeoAudit) HasTarget() bool`

HasTarget returns a boolean if a field has been set.

### GetCountryCode

`func (o *GeoAudit) GetCountryCode() string`

GetCountryCode returns the CountryCode field if non-nil, zero value otherwise.

### GetCountryCodeOk

`func (o *GeoAudit) GetCountryCodeOk() (*string, bool)`

GetCountryCodeOk returns a tuple with the CountryCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountryCode

`func (o *GeoAudit) SetCountryCode(v string)`

SetCountryCode sets CountryCode field to given value.

### HasCountryCode

`func (o *GeoAudit) HasCountryCode() bool`

HasCountryCode returns a boolean if a field has been set.

### SetCountryCodeNil

`func (o *GeoAudit) SetCountryCodeNil(b bool)`

 SetCountryCodeNil sets the value for CountryCode to be an explicit nil

### UnsetCountryCode
`func (o *GeoAudit) UnsetCountryCode()`

UnsetCountryCode ensures that no value is present for CountryCode, not even an explicit nil
### GetCadence

`func (o *GeoAudit) GetCadence() string`

GetCadence returns the Cadence field if non-nil, zero value otherwise.

### GetCadenceOk

`func (o *GeoAudit) GetCadenceOk() (*string, bool)`

GetCadenceOk returns a tuple with the Cadence field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCadence

`func (o *GeoAudit) SetCadence(v string)`

SetCadence sets Cadence field to given value.

### HasCadence

`func (o *GeoAudit) HasCadence() bool`

HasCadence returns a boolean if a field has been set.

### GetStatus

`func (o *GeoAudit) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *GeoAudit) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *GeoAudit) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *GeoAudit) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetPausedReason

`func (o *GeoAudit) GetPausedReason() string`

GetPausedReason returns the PausedReason field if non-nil, zero value otherwise.

### GetPausedReasonOk

`func (o *GeoAudit) GetPausedReasonOk() (*string, bool)`

GetPausedReasonOk returns a tuple with the PausedReason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPausedReason

`func (o *GeoAudit) SetPausedReason(v string)`

SetPausedReason sets PausedReason field to given value.

### HasPausedReason

`func (o *GeoAudit) HasPausedReason() bool`

HasPausedReason returns a boolean if a field has been set.

### SetPausedReasonNil

`func (o *GeoAudit) SetPausedReasonNil(b bool)`

 SetPausedReasonNil sets the value for PausedReason to be an explicit nil

### UnsetPausedReason
`func (o *GeoAudit) UnsetPausedReason()`

UnsetPausedReason ensures that no value is present for PausedReason, not even an explicit nil
### GetSchedule

`func (o *GeoAudit) GetSchedule() GeoAuditSchedule`

GetSchedule returns the Schedule field if non-nil, zero value otherwise.

### GetScheduleOk

`func (o *GeoAudit) GetScheduleOk() (*GeoAuditSchedule, bool)`

GetScheduleOk returns a tuple with the Schedule field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSchedule

`func (o *GeoAudit) SetSchedule(v GeoAuditSchedule)`

SetSchedule sets Schedule field to given value.

### HasSchedule

`func (o *GeoAudit) HasSchedule() bool`

HasSchedule returns a boolean if a field has been set.

### SetScheduleNil

`func (o *GeoAudit) SetScheduleNil(b bool)`

 SetScheduleNil sets the value for Schedule to be an explicit nil

### UnsetSchedule
`func (o *GeoAudit) UnsetSchedule()`

UnsetSchedule ensures that no value is present for Schedule, not even an explicit nil
### GetNextRunAt

`func (o *GeoAudit) GetNextRunAt() time.Time`

GetNextRunAt returns the NextRunAt field if non-nil, zero value otherwise.

### GetNextRunAtOk

`func (o *GeoAudit) GetNextRunAtOk() (*time.Time, bool)`

GetNextRunAtOk returns a tuple with the NextRunAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNextRunAt

`func (o *GeoAudit) SetNextRunAt(v time.Time)`

SetNextRunAt sets NextRunAt field to given value.

### HasNextRunAt

`func (o *GeoAudit) HasNextRunAt() bool`

HasNextRunAt returns a boolean if a field has been set.

### SetNextRunAtNil

`func (o *GeoAudit) SetNextRunAtNil(b bool)`

 SetNextRunAtNil sets the value for NextRunAt to be an explicit nil

### UnsetNextRunAt
`func (o *GeoAudit) UnsetNextRunAt()`

UnsetNextRunAt ensures that no value is present for NextRunAt, not even an explicit nil
### GetEmailAlerts

`func (o *GeoAudit) GetEmailAlerts() bool`

GetEmailAlerts returns the EmailAlerts field if non-nil, zero value otherwise.

### GetEmailAlertsOk

`func (o *GeoAudit) GetEmailAlertsOk() (*bool, bool)`

GetEmailAlertsOk returns a tuple with the EmailAlerts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmailAlerts

`func (o *GeoAudit) SetEmailAlerts(v bool)`

SetEmailAlerts sets EmailAlerts field to given value.

### HasEmailAlerts

`func (o *GeoAudit) HasEmailAlerts() bool`

HasEmailAlerts returns a boolean if a field has been set.

### GetRecurringAvailable

`func (o *GeoAudit) GetRecurringAvailable() bool`

GetRecurringAvailable returns the RecurringAvailable field if non-nil, zero value otherwise.

### GetRecurringAvailableOk

`func (o *GeoAudit) GetRecurringAvailableOk() (*bool, bool)`

GetRecurringAvailableOk returns a tuple with the RecurringAvailable field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRecurringAvailable

`func (o *GeoAudit) SetRecurringAvailable(v bool)`

SetRecurringAvailable sets RecurringAvailable field to given value.

### HasRecurringAvailable

`func (o *GeoAudit) HasRecurringAvailable() bool`

HasRecurringAvailable returns a boolean if a field has been set.

### GetChecksTracked

`func (o *GeoAudit) GetChecksTracked() bool`

GetChecksTracked returns the ChecksTracked field if non-nil, zero value otherwise.

### GetChecksTrackedOk

`func (o *GeoAudit) GetChecksTrackedOk() (*bool, bool)`

GetChecksTrackedOk returns a tuple with the ChecksTracked field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChecksTracked

`func (o *GeoAudit) SetChecksTracked(v bool)`

SetChecksTracked sets ChecksTracked field to given value.

### HasChecksTracked

`func (o *GeoAudit) HasChecksTracked() bool`

HasChecksTracked returns a boolean if a field has been set.

### GetLatestRun

`func (o *GeoAudit) GetLatestRun() GeoAuditRun`

GetLatestRun returns the LatestRun field if non-nil, zero value otherwise.

### GetLatestRunOk

`func (o *GeoAudit) GetLatestRunOk() (*GeoAuditRun, bool)`

GetLatestRunOk returns a tuple with the LatestRun field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLatestRun

`func (o *GeoAudit) SetLatestRun(v GeoAuditRun)`

SetLatestRun sets LatestRun field to given value.

### HasLatestRun

`func (o *GeoAudit) HasLatestRun() bool`

HasLatestRun returns a boolean if a field has been set.

### SetLatestRunNil

`func (o *GeoAudit) SetLatestRunNil(b bool)`

 SetLatestRunNil sets the value for LatestRun to be an explicit nil

### UnsetLatestRun
`func (o *GeoAudit) UnsetLatestRun()`

UnsetLatestRun ensures that no value is present for LatestRun, not even an explicit nil
### GetOpenIssues

`func (o *GeoAudit) GetOpenIssues() int32`

GetOpenIssues returns the OpenIssues field if non-nil, zero value otherwise.

### GetOpenIssuesOk

`func (o *GeoAudit) GetOpenIssuesOk() (*int32, bool)`

GetOpenIssuesOk returns a tuple with the OpenIssues field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOpenIssues

`func (o *GeoAudit) SetOpenIssues(v int32)`

SetOpenIssues sets OpenIssues field to given value.

### HasOpenIssues

`func (o *GeoAudit) HasOpenIssues() bool`

HasOpenIssues returns a boolean if a field has been set.

### GetOpenCriticalIssues

`func (o *GeoAudit) GetOpenCriticalIssues() int32`

GetOpenCriticalIssues returns the OpenCriticalIssues field if non-nil, zero value otherwise.

### GetOpenCriticalIssuesOk

`func (o *GeoAudit) GetOpenCriticalIssuesOk() (*int32, bool)`

GetOpenCriticalIssuesOk returns a tuple with the OpenCriticalIssues field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOpenCriticalIssues

`func (o *GeoAudit) SetOpenCriticalIssues(v int32)`

SetOpenCriticalIssues sets OpenCriticalIssues field to given value.

### HasOpenCriticalIssues

`func (o *GeoAudit) HasOpenCriticalIssues() bool`

HasOpenCriticalIssues returns a boolean if a field has been set.

### GetCreatedAt

`func (o *GeoAudit) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *GeoAudit) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *GeoAudit) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *GeoAudit) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetAppUrl

`func (o *GeoAudit) GetAppUrl() string`

GetAppUrl returns the AppUrl field if non-nil, zero value otherwise.

### GetAppUrlOk

`func (o *GeoAudit) GetAppUrlOk() (*string, bool)`

GetAppUrlOk returns a tuple with the AppUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAppUrl

`func (o *GeoAudit) SetAppUrl(v string)`

SetAppUrl sets AppUrl field to given value.

### HasAppUrl

`func (o *GeoAudit) HasAppUrl() bool`

HasAppUrl returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


