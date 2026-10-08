# GeoAuditComparison

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ProjectId** | Pointer to **int32** |  | [optional] 
**FromRun** | Pointer to [**NullableGeoAuditRun**](GeoAuditRun.md) |  | [optional] 
**ToRun** | Pointer to [**NullableGeoAuditRun**](GeoAuditRun.md) |  | [optional] 
**Comparable** | Pointer to **bool** |  | [optional] 
**ScoreDelta** | Pointer to **NullableFloat32** |  | [optional] 
**MetricDeltas** | Pointer to **map[string]float32** |  | [optional] 
**Counts** | Pointer to **map[string]int32** |  | [optional] 
**Changes** | Pointer to [**[]GeoAuditComparisonChangesInner**](GeoAuditComparisonChangesInner.md) |  | [optional] 
**RequestId** | Pointer to **string** |  | [optional] 

## Methods

### NewGeoAuditComparison

`func NewGeoAuditComparison() *GeoAuditComparison`

NewGeoAuditComparison instantiates a new GeoAuditComparison object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGeoAuditComparisonWithDefaults

`func NewGeoAuditComparisonWithDefaults() *GeoAuditComparison`

NewGeoAuditComparisonWithDefaults instantiates a new GeoAuditComparison object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProjectId

`func (o *GeoAuditComparison) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *GeoAuditComparison) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *GeoAuditComparison) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.

### HasProjectId

`func (o *GeoAuditComparison) HasProjectId() bool`

HasProjectId returns a boolean if a field has been set.

### GetFromRun

`func (o *GeoAuditComparison) GetFromRun() GeoAuditRun`

GetFromRun returns the FromRun field if non-nil, zero value otherwise.

### GetFromRunOk

`func (o *GeoAuditComparison) GetFromRunOk() (*GeoAuditRun, bool)`

GetFromRunOk returns a tuple with the FromRun field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFromRun

`func (o *GeoAuditComparison) SetFromRun(v GeoAuditRun)`

SetFromRun sets FromRun field to given value.

### HasFromRun

`func (o *GeoAuditComparison) HasFromRun() bool`

HasFromRun returns a boolean if a field has been set.

### SetFromRunNil

`func (o *GeoAuditComparison) SetFromRunNil(b bool)`

 SetFromRunNil sets the value for FromRun to be an explicit nil

### UnsetFromRun
`func (o *GeoAuditComparison) UnsetFromRun()`

UnsetFromRun ensures that no value is present for FromRun, not even an explicit nil
### GetToRun

`func (o *GeoAuditComparison) GetToRun() GeoAuditRun`

GetToRun returns the ToRun field if non-nil, zero value otherwise.

### GetToRunOk

`func (o *GeoAuditComparison) GetToRunOk() (*GeoAuditRun, bool)`

GetToRunOk returns a tuple with the ToRun field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetToRun

`func (o *GeoAuditComparison) SetToRun(v GeoAuditRun)`

SetToRun sets ToRun field to given value.

### HasToRun

`func (o *GeoAuditComparison) HasToRun() bool`

HasToRun returns a boolean if a field has been set.

### SetToRunNil

`func (o *GeoAuditComparison) SetToRunNil(b bool)`

 SetToRunNil sets the value for ToRun to be an explicit nil

### UnsetToRun
`func (o *GeoAuditComparison) UnsetToRun()`

UnsetToRun ensures that no value is present for ToRun, not even an explicit nil
### GetComparable

`func (o *GeoAuditComparison) GetComparable() bool`

GetComparable returns the Comparable field if non-nil, zero value otherwise.

### GetComparableOk

`func (o *GeoAuditComparison) GetComparableOk() (*bool, bool)`

GetComparableOk returns a tuple with the Comparable field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComparable

`func (o *GeoAuditComparison) SetComparable(v bool)`

SetComparable sets Comparable field to given value.

### HasComparable

`func (o *GeoAuditComparison) HasComparable() bool`

HasComparable returns a boolean if a field has been set.

### GetScoreDelta

`func (o *GeoAuditComparison) GetScoreDelta() float32`

GetScoreDelta returns the ScoreDelta field if non-nil, zero value otherwise.

### GetScoreDeltaOk

`func (o *GeoAuditComparison) GetScoreDeltaOk() (*float32, bool)`

GetScoreDeltaOk returns a tuple with the ScoreDelta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScoreDelta

`func (o *GeoAuditComparison) SetScoreDelta(v float32)`

SetScoreDelta sets ScoreDelta field to given value.

### HasScoreDelta

`func (o *GeoAuditComparison) HasScoreDelta() bool`

HasScoreDelta returns a boolean if a field has been set.

### SetScoreDeltaNil

`func (o *GeoAuditComparison) SetScoreDeltaNil(b bool)`

 SetScoreDeltaNil sets the value for ScoreDelta to be an explicit nil

### UnsetScoreDelta
`func (o *GeoAuditComparison) UnsetScoreDelta()`

UnsetScoreDelta ensures that no value is present for ScoreDelta, not even an explicit nil
### GetMetricDeltas

`func (o *GeoAuditComparison) GetMetricDeltas() map[string]float32`

GetMetricDeltas returns the MetricDeltas field if non-nil, zero value otherwise.

### GetMetricDeltasOk

`func (o *GeoAuditComparison) GetMetricDeltasOk() (*map[string]float32, bool)`

GetMetricDeltasOk returns a tuple with the MetricDeltas field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetricDeltas

`func (o *GeoAuditComparison) SetMetricDeltas(v map[string]float32)`

SetMetricDeltas sets MetricDeltas field to given value.

### HasMetricDeltas

`func (o *GeoAuditComparison) HasMetricDeltas() bool`

HasMetricDeltas returns a boolean if a field has been set.

### GetCounts

`func (o *GeoAuditComparison) GetCounts() map[string]int32`

GetCounts returns the Counts field if non-nil, zero value otherwise.

### GetCountsOk

`func (o *GeoAuditComparison) GetCountsOk() (*map[string]int32, bool)`

GetCountsOk returns a tuple with the Counts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCounts

`func (o *GeoAuditComparison) SetCounts(v map[string]int32)`

SetCounts sets Counts field to given value.

### HasCounts

`func (o *GeoAuditComparison) HasCounts() bool`

HasCounts returns a boolean if a field has been set.

### GetChanges

`func (o *GeoAuditComparison) GetChanges() []GeoAuditComparisonChangesInner`

GetChanges returns the Changes field if non-nil, zero value otherwise.

### GetChangesOk

`func (o *GeoAuditComparison) GetChangesOk() (*[]GeoAuditComparisonChangesInner, bool)`

GetChangesOk returns a tuple with the Changes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChanges

`func (o *GeoAuditComparison) SetChanges(v []GeoAuditComparisonChangesInner)`

SetChanges sets Changes field to given value.

### HasChanges

`func (o *GeoAuditComparison) HasChanges() bool`

HasChanges returns a boolean if a field has been set.

### GetRequestId

`func (o *GeoAuditComparison) GetRequestId() string`

GetRequestId returns the RequestId field if non-nil, zero value otherwise.

### GetRequestIdOk

`func (o *GeoAuditComparison) GetRequestIdOk() (*string, bool)`

GetRequestIdOk returns a tuple with the RequestId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestId

`func (o *GeoAuditComparison) SetRequestId(v string)`

SetRequestId sets RequestId field to given value.

### HasRequestId

`func (o *GeoAuditComparison) HasRequestId() bool`

HasRequestId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


