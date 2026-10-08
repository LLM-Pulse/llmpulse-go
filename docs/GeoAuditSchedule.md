# GeoAuditSchedule

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Day** | Pointer to **int32** |  | [optional] 
**Hour** | Pointer to **int32** |  | [optional] 
**Timezone** | Pointer to **string** |  | [optional] 

## Methods

### NewGeoAuditSchedule

`func NewGeoAuditSchedule() *GeoAuditSchedule`

NewGeoAuditSchedule instantiates a new GeoAuditSchedule object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGeoAuditScheduleWithDefaults

`func NewGeoAuditScheduleWithDefaults() *GeoAuditSchedule`

NewGeoAuditScheduleWithDefaults instantiates a new GeoAuditSchedule object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDay

`func (o *GeoAuditSchedule) GetDay() int32`

GetDay returns the Day field if non-nil, zero value otherwise.

### GetDayOk

`func (o *GeoAuditSchedule) GetDayOk() (*int32, bool)`

GetDayOk returns a tuple with the Day field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDay

`func (o *GeoAuditSchedule) SetDay(v int32)`

SetDay sets Day field to given value.

### HasDay

`func (o *GeoAuditSchedule) HasDay() bool`

HasDay returns a boolean if a field has been set.

### GetHour

`func (o *GeoAuditSchedule) GetHour() int32`

GetHour returns the Hour field if non-nil, zero value otherwise.

### GetHourOk

`func (o *GeoAuditSchedule) GetHourOk() (*int32, bool)`

GetHourOk returns a tuple with the Hour field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHour

`func (o *GeoAuditSchedule) SetHour(v int32)`

SetHour sets Hour field to given value.

### HasHour

`func (o *GeoAuditSchedule) HasHour() bool`

HasHour returns a boolean if a field has been set.

### GetTimezone

`func (o *GeoAuditSchedule) GetTimezone() string`

GetTimezone returns the Timezone field if non-nil, zero value otherwise.

### GetTimezoneOk

`func (o *GeoAuditSchedule) GetTimezoneOk() (*string, bool)`

GetTimezoneOk returns a tuple with the Timezone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimezone

`func (o *GeoAuditSchedule) SetTimezone(v string)`

SetTimezone sets Timezone field to given value.

### HasTimezone

`func (o *GeoAuditSchedule) HasTimezone() bool`

HasTimezone returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


