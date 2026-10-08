# GeoAuditUpdateRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ProjectId** | Pointer to **int32** |  | [optional] 
**Cadence** | Pointer to **string** |  | [optional] 
**ScheduleDay** | Pointer to **int32** | Weekly: 0 (Sunday) to 6. Monthly: 1 to 28. | [optional] 
**ScheduleHour** | Pointer to **int32** | Hour of the day, 0 to 23, in the audit time zone | [optional] 
**Status** | Pointer to **string** | paused stops scheduled runs, active resumes them, archived is the same as DELETE | [optional] 
**EmailAlerts** | Pointer to **bool** |  | [optional] 

## Methods

### NewGeoAuditUpdateRequest

`func NewGeoAuditUpdateRequest() *GeoAuditUpdateRequest`

NewGeoAuditUpdateRequest instantiates a new GeoAuditUpdateRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGeoAuditUpdateRequestWithDefaults

`func NewGeoAuditUpdateRequestWithDefaults() *GeoAuditUpdateRequest`

NewGeoAuditUpdateRequestWithDefaults instantiates a new GeoAuditUpdateRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProjectId

`func (o *GeoAuditUpdateRequest) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *GeoAuditUpdateRequest) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *GeoAuditUpdateRequest) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.

### HasProjectId

`func (o *GeoAuditUpdateRequest) HasProjectId() bool`

HasProjectId returns a boolean if a field has been set.

### GetCadence

`func (o *GeoAuditUpdateRequest) GetCadence() string`

GetCadence returns the Cadence field if non-nil, zero value otherwise.

### GetCadenceOk

`func (o *GeoAuditUpdateRequest) GetCadenceOk() (*string, bool)`

GetCadenceOk returns a tuple with the Cadence field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCadence

`func (o *GeoAuditUpdateRequest) SetCadence(v string)`

SetCadence sets Cadence field to given value.

### HasCadence

`func (o *GeoAuditUpdateRequest) HasCadence() bool`

HasCadence returns a boolean if a field has been set.

### GetScheduleDay

`func (o *GeoAuditUpdateRequest) GetScheduleDay() int32`

GetScheduleDay returns the ScheduleDay field if non-nil, zero value otherwise.

### GetScheduleDayOk

`func (o *GeoAuditUpdateRequest) GetScheduleDayOk() (*int32, bool)`

GetScheduleDayOk returns a tuple with the ScheduleDay field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScheduleDay

`func (o *GeoAuditUpdateRequest) SetScheduleDay(v int32)`

SetScheduleDay sets ScheduleDay field to given value.

### HasScheduleDay

`func (o *GeoAuditUpdateRequest) HasScheduleDay() bool`

HasScheduleDay returns a boolean if a field has been set.

### GetScheduleHour

`func (o *GeoAuditUpdateRequest) GetScheduleHour() int32`

GetScheduleHour returns the ScheduleHour field if non-nil, zero value otherwise.

### GetScheduleHourOk

`func (o *GeoAuditUpdateRequest) GetScheduleHourOk() (*int32, bool)`

GetScheduleHourOk returns a tuple with the ScheduleHour field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScheduleHour

`func (o *GeoAuditUpdateRequest) SetScheduleHour(v int32)`

SetScheduleHour sets ScheduleHour field to given value.

### HasScheduleHour

`func (o *GeoAuditUpdateRequest) HasScheduleHour() bool`

HasScheduleHour returns a boolean if a field has been set.

### GetStatus

`func (o *GeoAuditUpdateRequest) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *GeoAuditUpdateRequest) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *GeoAuditUpdateRequest) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *GeoAuditUpdateRequest) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetEmailAlerts

`func (o *GeoAuditUpdateRequest) GetEmailAlerts() bool`

GetEmailAlerts returns the EmailAlerts field if non-nil, zero value otherwise.

### GetEmailAlertsOk

`func (o *GeoAuditUpdateRequest) GetEmailAlertsOk() (*bool, bool)`

GetEmailAlertsOk returns a tuple with the EmailAlerts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmailAlerts

`func (o *GeoAuditUpdateRequest) SetEmailAlerts(v bool)`

SetEmailAlerts sets EmailAlerts field to given value.

### HasEmailAlerts

`func (o *GeoAuditUpdateRequest) HasEmailAlerts() bool`

HasEmailAlerts returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


