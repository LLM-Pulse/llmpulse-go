# CompetitorDiscoveryState

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Status** | Pointer to **NullableString** | The last discovery run: pending, processing, completed or failed; null when none ever ran | [optional] 
**Loading** | **bool** | A discovery run is in progress | 
**GeneratedAt** | Pointer to **NullableTime** |  | [optional] 

## Methods

### NewCompetitorDiscoveryState

`func NewCompetitorDiscoveryState(loading bool, ) *CompetitorDiscoveryState`

NewCompetitorDiscoveryState instantiates a new CompetitorDiscoveryState object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCompetitorDiscoveryStateWithDefaults

`func NewCompetitorDiscoveryStateWithDefaults() *CompetitorDiscoveryState`

NewCompetitorDiscoveryStateWithDefaults instantiates a new CompetitorDiscoveryState object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetStatus

`func (o *CompetitorDiscoveryState) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *CompetitorDiscoveryState) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *CompetitorDiscoveryState) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *CompetitorDiscoveryState) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### SetStatusNil

`func (o *CompetitorDiscoveryState) SetStatusNil(b bool)`

 SetStatusNil sets the value for Status to be an explicit nil

### UnsetStatus
`func (o *CompetitorDiscoveryState) UnsetStatus()`

UnsetStatus ensures that no value is present for Status, not even an explicit nil
### GetLoading

`func (o *CompetitorDiscoveryState) GetLoading() bool`

GetLoading returns the Loading field if non-nil, zero value otherwise.

### GetLoadingOk

`func (o *CompetitorDiscoveryState) GetLoadingOk() (*bool, bool)`

GetLoadingOk returns a tuple with the Loading field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLoading

`func (o *CompetitorDiscoveryState) SetLoading(v bool)`

SetLoading sets Loading field to given value.


### GetGeneratedAt

`func (o *CompetitorDiscoveryState) GetGeneratedAt() time.Time`

GetGeneratedAt returns the GeneratedAt field if non-nil, zero value otherwise.

### GetGeneratedAtOk

`func (o *CompetitorDiscoveryState) GetGeneratedAtOk() (*time.Time, bool)`

GetGeneratedAtOk returns a tuple with the GeneratedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGeneratedAt

`func (o *CompetitorDiscoveryState) SetGeneratedAt(v time.Time)`

SetGeneratedAt sets GeneratedAt field to given value.

### HasGeneratedAt

`func (o *CompetitorDiscoveryState) HasGeneratedAt() bool`

HasGeneratedAt returns a boolean if a field has been set.

### SetGeneratedAtNil

`func (o *CompetitorDiscoveryState) SetGeneratedAtNil(b bool)`

 SetGeneratedAtNil sets the value for GeneratedAt to be an explicit nil

### UnsetGeneratedAt
`func (o *CompetitorDiscoveryState) UnsetGeneratedAt()`

UnsetGeneratedAt ensures that no value is present for GeneratedAt, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


