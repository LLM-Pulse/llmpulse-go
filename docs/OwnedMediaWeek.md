# OwnedMediaWeek

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Week** | Pointer to **string** | The Monday that starts the week | [optional] 
**Citations** | Pointer to **int32** |  | [optional] 
**Yours** | Pointer to **NullableInt32** | Null for provider&#x3D;overview, whose rollups have no weekly split | [optional] 
**Other** | Pointer to **NullableInt32** |  | [optional] 

## Methods

### NewOwnedMediaWeek

`func NewOwnedMediaWeek() *OwnedMediaWeek`

NewOwnedMediaWeek instantiates a new OwnedMediaWeek object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOwnedMediaWeekWithDefaults

`func NewOwnedMediaWeekWithDefaults() *OwnedMediaWeek`

NewOwnedMediaWeekWithDefaults instantiates a new OwnedMediaWeek object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetWeek

`func (o *OwnedMediaWeek) GetWeek() string`

GetWeek returns the Week field if non-nil, zero value otherwise.

### GetWeekOk

`func (o *OwnedMediaWeek) GetWeekOk() (*string, bool)`

GetWeekOk returns a tuple with the Week field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWeek

`func (o *OwnedMediaWeek) SetWeek(v string)`

SetWeek sets Week field to given value.

### HasWeek

`func (o *OwnedMediaWeek) HasWeek() bool`

HasWeek returns a boolean if a field has been set.

### GetCitations

`func (o *OwnedMediaWeek) GetCitations() int32`

GetCitations returns the Citations field if non-nil, zero value otherwise.

### GetCitationsOk

`func (o *OwnedMediaWeek) GetCitationsOk() (*int32, bool)`

GetCitationsOk returns a tuple with the Citations field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCitations

`func (o *OwnedMediaWeek) SetCitations(v int32)`

SetCitations sets Citations field to given value.

### HasCitations

`func (o *OwnedMediaWeek) HasCitations() bool`

HasCitations returns a boolean if a field has been set.

### GetYours

`func (o *OwnedMediaWeek) GetYours() int32`

GetYours returns the Yours field if non-nil, zero value otherwise.

### GetYoursOk

`func (o *OwnedMediaWeek) GetYoursOk() (*int32, bool)`

GetYoursOk returns a tuple with the Yours field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetYours

`func (o *OwnedMediaWeek) SetYours(v int32)`

SetYours sets Yours field to given value.

### HasYours

`func (o *OwnedMediaWeek) HasYours() bool`

HasYours returns a boolean if a field has been set.

### SetYoursNil

`func (o *OwnedMediaWeek) SetYoursNil(b bool)`

 SetYoursNil sets the value for Yours to be an explicit nil

### UnsetYours
`func (o *OwnedMediaWeek) UnsetYours()`

UnsetYours ensures that no value is present for Yours, not even an explicit nil
### GetOther

`func (o *OwnedMediaWeek) GetOther() int32`

GetOther returns the Other field if non-nil, zero value otherwise.

### GetOtherOk

`func (o *OwnedMediaWeek) GetOtherOk() (*int32, bool)`

GetOtherOk returns a tuple with the Other field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOther

`func (o *OwnedMediaWeek) SetOther(v int32)`

SetOther sets Other field to given value.

### HasOther

`func (o *OwnedMediaWeek) HasOther() bool`

HasOther returns a boolean if a field has been set.

### SetOtherNil

`func (o *OwnedMediaWeek) SetOtherNil(b bool)`

 SetOtherNil sets the value for Other to be an explicit nil

### UnsetOther
`func (o *OwnedMediaWeek) UnsetOther()`

UnsetOther ensures that no value is present for Other, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


