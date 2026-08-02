# TimeseriesPoint

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Date** | Pointer to **time.Time** |  | [optional] 
**Value** | Pointer to **float32** |  | [optional] 

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

`func (o *TimeseriesPoint) GetDate() time.Time`

GetDate returns the Date field if non-nil, zero value otherwise.

### GetDateOk

`func (o *TimeseriesPoint) GetDateOk() (*time.Time, bool)`

GetDateOk returns a tuple with the Date field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDate

`func (o *TimeseriesPoint) SetDate(v time.Time)`

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


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


