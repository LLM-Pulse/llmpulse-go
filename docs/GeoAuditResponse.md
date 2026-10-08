# GeoAuditResponse

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
**ProjectId** | Pointer to **int32** |  | [optional] 
**RequestId** | Pointer to **string** |  | [optional] 

## Methods

### NewGeoAuditResponse

`func NewGeoAuditResponse() *GeoAuditResponse`

NewGeoAuditResponse instantiates a new GeoAuditResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGeoAuditResponseWithDefaults

`func NewGeoAuditResponseWithDefaults() *GeoAuditResponse`

NewGeoAuditResponseWithDefaults instantiates a new GeoAuditResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *GeoAuditResponse) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *GeoAuditResponse) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *GeoAuditResponse) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *GeoAuditResponse) HasId() bool`

HasId returns a boolean if a field has been set.

### GetAuditType

`func (o *GeoAuditResponse) GetAuditType() string`

GetAuditType returns the AuditType field if non-nil, zero value otherwise.

### GetAuditTypeOk

`func (o *GeoAuditResponse) GetAuditTypeOk() (*string, bool)`

GetAuditTypeOk returns a tuple with the AuditType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAuditType

`func (o *GeoAuditResponse) SetAuditType(v string)`

SetAuditType sets AuditType field to given value.

### HasAuditType

`func (o *GeoAuditResponse) HasAuditType() bool`

HasAuditType returns a boolean if a field has been set.

### GetTarget

`func (o *GeoAuditResponse) GetTarget() string`

GetTarget returns the Target field if non-nil, zero value otherwise.

### GetTargetOk

`func (o *GeoAuditResponse) GetTargetOk() (*string, bool)`

GetTargetOk returns a tuple with the Target field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTarget

`func (o *GeoAuditResponse) SetTarget(v string)`

SetTarget sets Target field to given value.

### HasTarget

`func (o *GeoAuditResponse) HasTarget() bool`

HasTarget returns a boolean if a field has been set.

### GetCountryCode

`func (o *GeoAuditResponse) GetCountryCode() string`

GetCountryCode returns the CountryCode field if non-nil, zero value otherwise.

### GetCountryCodeOk

`func (o *GeoAuditResponse) GetCountryCodeOk() (*string, bool)`

GetCountryCodeOk returns a tuple with the CountryCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountryCode

`func (o *GeoAuditResponse) SetCountryCode(v string)`

SetCountryCode sets CountryCode field to given value.

### HasCountryCode

`func (o *GeoAuditResponse) HasCountryCode() bool`

HasCountryCode returns a boolean if a field has been set.

### SetCountryCodeNil

`func (o *GeoAuditResponse) SetCountryCodeNil(b bool)`

 SetCountryCodeNil sets the value for CountryCode to be an explicit nil

### UnsetCountryCode
`func (o *GeoAuditResponse) UnsetCountryCode()`

UnsetCountryCode ensures that no value is present for CountryCode, not even an explicit nil
### GetCadence

`func (o *GeoAuditResponse) GetCadence() string`

GetCadence returns the Cadence field if non-nil, zero value otherwise.

### GetCadenceOk

`func (o *GeoAuditResponse) GetCadenceOk() (*string, bool)`

GetCadenceOk returns a tuple with the Cadence field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCadence

`func (o *GeoAuditResponse) SetCadence(v string)`

SetCadence sets Cadence field to given value.

### HasCadence

`func (o *GeoAuditResponse) HasCadence() bool`

HasCadence returns a boolean if a field has been set.

### GetStatus

`func (o *GeoAuditResponse) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *GeoAuditResponse) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *GeoAuditResponse) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *GeoAuditResponse) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetPausedReason

`func (o *GeoAuditResponse) GetPausedReason() string`

GetPausedReason returns the PausedReason field if non-nil, zero value otherwise.

### GetPausedReasonOk

`func (o *GeoAuditResponse) GetPausedReasonOk() (*string, bool)`

GetPausedReasonOk returns a tuple with the PausedReason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPausedReason

`func (o *GeoAuditResponse) SetPausedReason(v string)`

SetPausedReason sets PausedReason field to given value.

### HasPausedReason

`func (o *GeoAuditResponse) HasPausedReason() bool`

HasPausedReason returns a boolean if a field has been set.

### SetPausedReasonNil

`func (o *GeoAuditResponse) SetPausedReasonNil(b bool)`

 SetPausedReasonNil sets the value for PausedReason to be an explicit nil

### UnsetPausedReason
`func (o *GeoAuditResponse) UnsetPausedReason()`

UnsetPausedReason ensures that no value is present for PausedReason, not even an explicit nil
### GetSchedule

`func (o *GeoAuditResponse) GetSchedule() GeoAuditSchedule`

GetSchedule returns the Schedule field if non-nil, zero value otherwise.

### GetScheduleOk

`func (o *GeoAuditResponse) GetScheduleOk() (*GeoAuditSchedule, bool)`

GetScheduleOk returns a tuple with the Schedule field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSchedule

`func (o *GeoAuditResponse) SetSchedule(v GeoAuditSchedule)`

SetSchedule sets Schedule field to given value.

### HasSchedule

`func (o *GeoAuditResponse) HasSchedule() bool`

HasSchedule returns a boolean if a field has been set.

### SetScheduleNil

`func (o *GeoAuditResponse) SetScheduleNil(b bool)`

 SetScheduleNil sets the value for Schedule to be an explicit nil

### UnsetSchedule
`func (o *GeoAuditResponse) UnsetSchedule()`

UnsetSchedule ensures that no value is present for Schedule, not even an explicit nil
### GetNextRunAt

`func (o *GeoAuditResponse) GetNextRunAt() time.Time`

GetNextRunAt returns the NextRunAt field if non-nil, zero value otherwise.

### GetNextRunAtOk

`func (o *GeoAuditResponse) GetNextRunAtOk() (*time.Time, bool)`

GetNextRunAtOk returns a tuple with the NextRunAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNextRunAt

`func (o *GeoAuditResponse) SetNextRunAt(v time.Time)`

SetNextRunAt sets NextRunAt field to given value.

### HasNextRunAt

`func (o *GeoAuditResponse) HasNextRunAt() bool`

HasNextRunAt returns a boolean if a field has been set.

### SetNextRunAtNil

`func (o *GeoAuditResponse) SetNextRunAtNil(b bool)`

 SetNextRunAtNil sets the value for NextRunAt to be an explicit nil

### UnsetNextRunAt
`func (o *GeoAuditResponse) UnsetNextRunAt()`

UnsetNextRunAt ensures that no value is present for NextRunAt, not even an explicit nil
### GetEmailAlerts

`func (o *GeoAuditResponse) GetEmailAlerts() bool`

GetEmailAlerts returns the EmailAlerts field if non-nil, zero value otherwise.

### GetEmailAlertsOk

`func (o *GeoAuditResponse) GetEmailAlertsOk() (*bool, bool)`

GetEmailAlertsOk returns a tuple with the EmailAlerts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmailAlerts

`func (o *GeoAuditResponse) SetEmailAlerts(v bool)`

SetEmailAlerts sets EmailAlerts field to given value.

### HasEmailAlerts

`func (o *GeoAuditResponse) HasEmailAlerts() bool`

HasEmailAlerts returns a boolean if a field has been set.

### GetRecurringAvailable

`func (o *GeoAuditResponse) GetRecurringAvailable() bool`

GetRecurringAvailable returns the RecurringAvailable field if non-nil, zero value otherwise.

### GetRecurringAvailableOk

`func (o *GeoAuditResponse) GetRecurringAvailableOk() (*bool, bool)`

GetRecurringAvailableOk returns a tuple with the RecurringAvailable field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRecurringAvailable

`func (o *GeoAuditResponse) SetRecurringAvailable(v bool)`

SetRecurringAvailable sets RecurringAvailable field to given value.

### HasRecurringAvailable

`func (o *GeoAuditResponse) HasRecurringAvailable() bool`

HasRecurringAvailable returns a boolean if a field has been set.

### GetChecksTracked

`func (o *GeoAuditResponse) GetChecksTracked() bool`

GetChecksTracked returns the ChecksTracked field if non-nil, zero value otherwise.

### GetChecksTrackedOk

`func (o *GeoAuditResponse) GetChecksTrackedOk() (*bool, bool)`

GetChecksTrackedOk returns a tuple with the ChecksTracked field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChecksTracked

`func (o *GeoAuditResponse) SetChecksTracked(v bool)`

SetChecksTracked sets ChecksTracked field to given value.

### HasChecksTracked

`func (o *GeoAuditResponse) HasChecksTracked() bool`

HasChecksTracked returns a boolean if a field has been set.

### GetLatestRun

`func (o *GeoAuditResponse) GetLatestRun() GeoAuditRun`

GetLatestRun returns the LatestRun field if non-nil, zero value otherwise.

### GetLatestRunOk

`func (o *GeoAuditResponse) GetLatestRunOk() (*GeoAuditRun, bool)`

GetLatestRunOk returns a tuple with the LatestRun field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLatestRun

`func (o *GeoAuditResponse) SetLatestRun(v GeoAuditRun)`

SetLatestRun sets LatestRun field to given value.

### HasLatestRun

`func (o *GeoAuditResponse) HasLatestRun() bool`

HasLatestRun returns a boolean if a field has been set.

### SetLatestRunNil

`func (o *GeoAuditResponse) SetLatestRunNil(b bool)`

 SetLatestRunNil sets the value for LatestRun to be an explicit nil

### UnsetLatestRun
`func (o *GeoAuditResponse) UnsetLatestRun()`

UnsetLatestRun ensures that no value is present for LatestRun, not even an explicit nil
### GetOpenIssues

`func (o *GeoAuditResponse) GetOpenIssues() int32`

GetOpenIssues returns the OpenIssues field if non-nil, zero value otherwise.

### GetOpenIssuesOk

`func (o *GeoAuditResponse) GetOpenIssuesOk() (*int32, bool)`

GetOpenIssuesOk returns a tuple with the OpenIssues field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOpenIssues

`func (o *GeoAuditResponse) SetOpenIssues(v int32)`

SetOpenIssues sets OpenIssues field to given value.

### HasOpenIssues

`func (o *GeoAuditResponse) HasOpenIssues() bool`

HasOpenIssues returns a boolean if a field has been set.

### GetOpenCriticalIssues

`func (o *GeoAuditResponse) GetOpenCriticalIssues() int32`

GetOpenCriticalIssues returns the OpenCriticalIssues field if non-nil, zero value otherwise.

### GetOpenCriticalIssuesOk

`func (o *GeoAuditResponse) GetOpenCriticalIssuesOk() (*int32, bool)`

GetOpenCriticalIssuesOk returns a tuple with the OpenCriticalIssues field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOpenCriticalIssues

`func (o *GeoAuditResponse) SetOpenCriticalIssues(v int32)`

SetOpenCriticalIssues sets OpenCriticalIssues field to given value.

### HasOpenCriticalIssues

`func (o *GeoAuditResponse) HasOpenCriticalIssues() bool`

HasOpenCriticalIssues returns a boolean if a field has been set.

### GetCreatedAt

`func (o *GeoAuditResponse) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *GeoAuditResponse) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *GeoAuditResponse) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *GeoAuditResponse) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetAppUrl

`func (o *GeoAuditResponse) GetAppUrl() string`

GetAppUrl returns the AppUrl field if non-nil, zero value otherwise.

### GetAppUrlOk

`func (o *GeoAuditResponse) GetAppUrlOk() (*string, bool)`

GetAppUrlOk returns a tuple with the AppUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAppUrl

`func (o *GeoAuditResponse) SetAppUrl(v string)`

SetAppUrl sets AppUrl field to given value.

### HasAppUrl

`func (o *GeoAuditResponse) HasAppUrl() bool`

HasAppUrl returns a boolean if a field has been set.

### GetProjectId

`func (o *GeoAuditResponse) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *GeoAuditResponse) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *GeoAuditResponse) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.

### HasProjectId

`func (o *GeoAuditResponse) HasProjectId() bool`

HasProjectId returns a boolean if a field has been set.

### GetRequestId

`func (o *GeoAuditResponse) GetRequestId() string`

GetRequestId returns the RequestId field if non-nil, zero value otherwise.

### GetRequestIdOk

`func (o *GeoAuditResponse) GetRequestIdOk() (*string, bool)`

GetRequestIdOk returns a tuple with the RequestId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestId

`func (o *GeoAuditResponse) SetRequestId(v string)`

SetRequestId sets RequestId field to given value.

### HasRequestId

`func (o *GeoAuditResponse) HasRequestId() bool`

HasRequestId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


