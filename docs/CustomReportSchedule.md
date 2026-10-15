# CustomReportSchedule

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Enabled** | **bool** |  | 
**DayOfWeek** | Pointer to **NullableInt32** | 0 (Sunday) to 6 (Saturday) | [optional] 
**Hour** | Pointer to **NullableInt32** |  | [optional] 
**Timezone** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewCustomReportSchedule

`func NewCustomReportSchedule(enabled bool, ) *CustomReportSchedule`

NewCustomReportSchedule instantiates a new CustomReportSchedule object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCustomReportScheduleWithDefaults

`func NewCustomReportScheduleWithDefaults() *CustomReportSchedule`

NewCustomReportScheduleWithDefaults instantiates a new CustomReportSchedule object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetEnabled

`func (o *CustomReportSchedule) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *CustomReportSchedule) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *CustomReportSchedule) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.


### GetDayOfWeek

`func (o *CustomReportSchedule) GetDayOfWeek() int32`

GetDayOfWeek returns the DayOfWeek field if non-nil, zero value otherwise.

### GetDayOfWeekOk

`func (o *CustomReportSchedule) GetDayOfWeekOk() (*int32, bool)`

GetDayOfWeekOk returns a tuple with the DayOfWeek field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDayOfWeek

`func (o *CustomReportSchedule) SetDayOfWeek(v int32)`

SetDayOfWeek sets DayOfWeek field to given value.

### HasDayOfWeek

`func (o *CustomReportSchedule) HasDayOfWeek() bool`

HasDayOfWeek returns a boolean if a field has been set.

### SetDayOfWeekNil

`func (o *CustomReportSchedule) SetDayOfWeekNil(b bool)`

 SetDayOfWeekNil sets the value for DayOfWeek to be an explicit nil

### UnsetDayOfWeek
`func (o *CustomReportSchedule) UnsetDayOfWeek()`

UnsetDayOfWeek ensures that no value is present for DayOfWeek, not even an explicit nil
### GetHour

`func (o *CustomReportSchedule) GetHour() int32`

GetHour returns the Hour field if non-nil, zero value otherwise.

### GetHourOk

`func (o *CustomReportSchedule) GetHourOk() (*int32, bool)`

GetHourOk returns a tuple with the Hour field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHour

`func (o *CustomReportSchedule) SetHour(v int32)`

SetHour sets Hour field to given value.

### HasHour

`func (o *CustomReportSchedule) HasHour() bool`

HasHour returns a boolean if a field has been set.

### SetHourNil

`func (o *CustomReportSchedule) SetHourNil(b bool)`

 SetHourNil sets the value for Hour to be an explicit nil

### UnsetHour
`func (o *CustomReportSchedule) UnsetHour()`

UnsetHour ensures that no value is present for Hour, not even an explicit nil
### GetTimezone

`func (o *CustomReportSchedule) GetTimezone() string`

GetTimezone returns the Timezone field if non-nil, zero value otherwise.

### GetTimezoneOk

`func (o *CustomReportSchedule) GetTimezoneOk() (*string, bool)`

GetTimezoneOk returns a tuple with the Timezone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimezone

`func (o *CustomReportSchedule) SetTimezone(v string)`

SetTimezone sets Timezone field to given value.

### HasTimezone

`func (o *CustomReportSchedule) HasTimezone() bool`

HasTimezone returns a boolean if a field has been set.

### SetTimezoneNil

`func (o *CustomReportSchedule) SetTimezoneNil(b bool)`

 SetTimezoneNil sets the value for Timezone to be an explicit nil

### UnsetTimezone
`func (o *CustomReportSchedule) UnsetTimezone()`

UnsetTimezone ensures that no value is present for Timezone, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


