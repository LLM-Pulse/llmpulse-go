# SovResponseCurrentInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Actor** | Pointer to [**Actor**](Actor.md) |  | [optional] 
**Share** | Pointer to **float32** |  | [optional] 
**PreviousShare** | Pointer to **NullableFloat32** | The actor&#39;s share in the last complete bucket before the current one; null without complete history. | [optional] 
**AvgShare** | Pointer to **NullableFloat32** | Mean share across complete buckets with data (partial buckets excluded); null without complete history. | [optional] 

## Methods

### NewSovResponseCurrentInner

`func NewSovResponseCurrentInner() *SovResponseCurrentInner`

NewSovResponseCurrentInner instantiates a new SovResponseCurrentInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSovResponseCurrentInnerWithDefaults

`func NewSovResponseCurrentInnerWithDefaults() *SovResponseCurrentInner`

NewSovResponseCurrentInnerWithDefaults instantiates a new SovResponseCurrentInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetActor

`func (o *SovResponseCurrentInner) GetActor() Actor`

GetActor returns the Actor field if non-nil, zero value otherwise.

### GetActorOk

`func (o *SovResponseCurrentInner) GetActorOk() (*Actor, bool)`

GetActorOk returns a tuple with the Actor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActor

`func (o *SovResponseCurrentInner) SetActor(v Actor)`

SetActor sets Actor field to given value.

### HasActor

`func (o *SovResponseCurrentInner) HasActor() bool`

HasActor returns a boolean if a field has been set.

### GetShare

`func (o *SovResponseCurrentInner) GetShare() float32`

GetShare returns the Share field if non-nil, zero value otherwise.

### GetShareOk

`func (o *SovResponseCurrentInner) GetShareOk() (*float32, bool)`

GetShareOk returns a tuple with the Share field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShare

`func (o *SovResponseCurrentInner) SetShare(v float32)`

SetShare sets Share field to given value.

### HasShare

`func (o *SovResponseCurrentInner) HasShare() bool`

HasShare returns a boolean if a field has been set.

### GetPreviousShare

`func (o *SovResponseCurrentInner) GetPreviousShare() float32`

GetPreviousShare returns the PreviousShare field if non-nil, zero value otherwise.

### GetPreviousShareOk

`func (o *SovResponseCurrentInner) GetPreviousShareOk() (*float32, bool)`

GetPreviousShareOk returns a tuple with the PreviousShare field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPreviousShare

`func (o *SovResponseCurrentInner) SetPreviousShare(v float32)`

SetPreviousShare sets PreviousShare field to given value.

### HasPreviousShare

`func (o *SovResponseCurrentInner) HasPreviousShare() bool`

HasPreviousShare returns a boolean if a field has been set.

### SetPreviousShareNil

`func (o *SovResponseCurrentInner) SetPreviousShareNil(b bool)`

 SetPreviousShareNil sets the value for PreviousShare to be an explicit nil

### UnsetPreviousShare
`func (o *SovResponseCurrentInner) UnsetPreviousShare()`

UnsetPreviousShare ensures that no value is present for PreviousShare, not even an explicit nil
### GetAvgShare

`func (o *SovResponseCurrentInner) GetAvgShare() float32`

GetAvgShare returns the AvgShare field if non-nil, zero value otherwise.

### GetAvgShareOk

`func (o *SovResponseCurrentInner) GetAvgShareOk() (*float32, bool)`

GetAvgShareOk returns a tuple with the AvgShare field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAvgShare

`func (o *SovResponseCurrentInner) SetAvgShare(v float32)`

SetAvgShare sets AvgShare field to given value.

### HasAvgShare

`func (o *SovResponseCurrentInner) HasAvgShare() bool`

HasAvgShare returns a boolean if a field has been set.

### SetAvgShareNil

`func (o *SovResponseCurrentInner) SetAvgShareNil(b bool)`

 SetAvgShareNil sets the value for AvgShare to be an explicit nil

### UnsetAvgShare
`func (o *SovResponseCurrentInner) UnsetAvgShare()`

UnsetAvgShare ensures that no value is present for AvgShare, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


