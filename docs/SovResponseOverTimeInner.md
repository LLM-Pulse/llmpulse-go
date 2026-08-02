# SovResponseOverTimeInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Actor** | Pointer to [**Actor**](Actor.md) |  | [optional] 
**Data** | Pointer to [**[]TimeseriesPoint**](TimeseriesPoint.md) |  | [optional] 

## Methods

### NewSovResponseOverTimeInner

`func NewSovResponseOverTimeInner() *SovResponseOverTimeInner`

NewSovResponseOverTimeInner instantiates a new SovResponseOverTimeInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSovResponseOverTimeInnerWithDefaults

`func NewSovResponseOverTimeInnerWithDefaults() *SovResponseOverTimeInner`

NewSovResponseOverTimeInnerWithDefaults instantiates a new SovResponseOverTimeInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetActor

`func (o *SovResponseOverTimeInner) GetActor() Actor`

GetActor returns the Actor field if non-nil, zero value otherwise.

### GetActorOk

`func (o *SovResponseOverTimeInner) GetActorOk() (*Actor, bool)`

GetActorOk returns a tuple with the Actor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActor

`func (o *SovResponseOverTimeInner) SetActor(v Actor)`

SetActor sets Actor field to given value.

### HasActor

`func (o *SovResponseOverTimeInner) HasActor() bool`

HasActor returns a boolean if a field has been set.

### GetData

`func (o *SovResponseOverTimeInner) GetData() []TimeseriesPoint`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *SovResponseOverTimeInner) GetDataOk() (*[]TimeseriesPoint, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *SovResponseOverTimeInner) SetData(v []TimeseriesPoint)`

SetData sets Data field to given value.

### HasData

`func (o *SovResponseOverTimeInner) HasData() bool`

HasData returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


