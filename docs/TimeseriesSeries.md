# TimeseriesSeries

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Actor** | Pointer to [**Actor**](Actor.md) |  | [optional] 
**Metric** | Pointer to **string** |  | [optional] 
**Data** | Pointer to [**[]TimeseriesPoint**](TimeseriesPoint.md) |  | [optional] 

## Methods

### NewTimeseriesSeries

`func NewTimeseriesSeries() *TimeseriesSeries`

NewTimeseriesSeries instantiates a new TimeseriesSeries object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTimeseriesSeriesWithDefaults

`func NewTimeseriesSeriesWithDefaults() *TimeseriesSeries`

NewTimeseriesSeriesWithDefaults instantiates a new TimeseriesSeries object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetActor

`func (o *TimeseriesSeries) GetActor() Actor`

GetActor returns the Actor field if non-nil, zero value otherwise.

### GetActorOk

`func (o *TimeseriesSeries) GetActorOk() (*Actor, bool)`

GetActorOk returns a tuple with the Actor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActor

`func (o *TimeseriesSeries) SetActor(v Actor)`

SetActor sets Actor field to given value.

### HasActor

`func (o *TimeseriesSeries) HasActor() bool`

HasActor returns a boolean if a field has been set.

### GetMetric

`func (o *TimeseriesSeries) GetMetric() string`

GetMetric returns the Metric field if non-nil, zero value otherwise.

### GetMetricOk

`func (o *TimeseriesSeries) GetMetricOk() (*string, bool)`

GetMetricOk returns a tuple with the Metric field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetric

`func (o *TimeseriesSeries) SetMetric(v string)`

SetMetric sets Metric field to given value.

### HasMetric

`func (o *TimeseriesSeries) HasMetric() bool`

HasMetric returns a boolean if a field has been set.

### GetData

`func (o *TimeseriesSeries) GetData() []TimeseriesPoint`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *TimeseriesSeries) GetDataOk() (*[]TimeseriesPoint, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *TimeseriesSeries) SetData(v []TimeseriesPoint)`

SetData sets Data field to given value.

### HasData

`func (o *TimeseriesSeries) HasData() bool`

HasData returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


