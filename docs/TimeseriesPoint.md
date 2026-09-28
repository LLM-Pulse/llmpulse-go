# TimeseriesPoint

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Date** | Pointer to **string** | Calendar day in Europe/Madrid (YYYY-MM-DD). With granularity week or month it is the first day of the bucket (the Monday, or the 1st of the month). | [optional] 
**Value** | Pointer to **NullableFloat32** | Null when the metric has no value for the bucket, e.g. a rate, position or sentiment metric on a day without answers. | [optional] 

## Methods

### NewTimeseriesPoint

`func NewTimeseriesPoint() *TimeseriesPoint`

NewTimeseriesPoint instantiates a new TimeseriesPoint object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTimeseriesPointWithDefaults

`func NewTimeseriesPointWithDefaults() *TimeseriesPoint`

NewTimeseriesPointWithDefaults instantiates a new TimeseriesPoint object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDate

`func (o *TimeseriesPoint) GetDate() string`

GetDate returns the Date field if non-nil, zero value otherwise.

### GetDateOk

`func (o *TimeseriesPoint) GetDateOk() (*string, bool)`

GetDateOk returns a tuple with the Date field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDate

`func (o *TimeseriesPoint) SetDate(v string)`

SetDate sets Date field to given value.

### HasDate

`func (o *TimeseriesPoint) HasDate() bool`

HasDate returns a boolean if a field has been set.

### GetValue

`func (o *TimeseriesPoint) GetValue() float32`

GetValue returns the Value field if non-nil, zero value otherwise.

### GetValueOk

`func (o *TimeseriesPoint) GetValueOk() (*float32, bool)`

GetValueOk returns a tuple with the Value field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValue

`func (o *TimeseriesPoint) SetValue(v float32)`

SetValue sets Value field to given value.

### HasValue

`func (o *TimeseriesPoint) HasValue() bool`

HasValue returns a boolean if a field has been set.

### SetValueNil

`func (o *TimeseriesPoint) SetValueNil(b bool)`

 SetValueNil sets the value for Value to be an explicit nil

### UnsetValue
`func (o *TimeseriesPoint) UnsetValue()`

UnsetValue ensures that no value is present for Value, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


