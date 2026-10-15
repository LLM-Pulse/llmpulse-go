# OwnedMediaPlatformProfiles

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Platform** | Pointer to **string** |  | [optional] 
**Connected** | Pointer to **bool** |  | [optional] 
**MaxExtraProfiles** | Pointer to **NullableInt32** | How many extra profiles the platform accepts; null where it takes none | [optional] 
**Profiles** | Pointer to [**[]OwnedMediaProfile**](OwnedMediaProfile.md) |  | [optional] 

## Methods

### NewOwnedMediaPlatformProfiles

`func NewOwnedMediaPlatformProfiles() *OwnedMediaPlatformProfiles`

NewOwnedMediaPlatformProfiles instantiates a new OwnedMediaPlatformProfiles object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOwnedMediaPlatformProfilesWithDefaults

`func NewOwnedMediaPlatformProfilesWithDefaults() *OwnedMediaPlatformProfiles`

NewOwnedMediaPlatformProfilesWithDefaults instantiates a new OwnedMediaPlatformProfiles object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPlatform

`func (o *OwnedMediaPlatformProfiles) GetPlatform() string`

GetPlatform returns the Platform field if non-nil, zero value otherwise.

### GetPlatformOk

`func (o *OwnedMediaPlatformProfiles) GetPlatformOk() (*string, bool)`

GetPlatformOk returns a tuple with the Platform field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlatform

`func (o *OwnedMediaPlatformProfiles) SetPlatform(v string)`

SetPlatform sets Platform field to given value.

### HasPlatform

`func (o *OwnedMediaPlatformProfiles) HasPlatform() bool`

HasPlatform returns a boolean if a field has been set.

### GetConnected

`func (o *OwnedMediaPlatformProfiles) GetConnected() bool`

GetConnected returns the Connected field if non-nil, zero value otherwise.

### GetConnectedOk

`func (o *OwnedMediaPlatformProfiles) GetConnectedOk() (*bool, bool)`

GetConnectedOk returns a tuple with the Connected field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConnected

`func (o *OwnedMediaPlatformProfiles) SetConnected(v bool)`

SetConnected sets Connected field to given value.

### HasConnected

`func (o *OwnedMediaPlatformProfiles) HasConnected() bool`

HasConnected returns a boolean if a field has been set.

### GetMaxExtraProfiles

`func (o *OwnedMediaPlatformProfiles) GetMaxExtraProfiles() int32`

GetMaxExtraProfiles returns the MaxExtraProfiles field if non-nil, zero value otherwise.

### GetMaxExtraProfilesOk

`func (o *OwnedMediaPlatformProfiles) GetMaxExtraProfilesOk() (*int32, bool)`

GetMaxExtraProfilesOk returns a tuple with the MaxExtraProfiles field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxExtraProfiles

`func (o *OwnedMediaPlatformProfiles) SetMaxExtraProfiles(v int32)`

SetMaxExtraProfiles sets MaxExtraProfiles field to given value.

### HasMaxExtraProfiles

`func (o *OwnedMediaPlatformProfiles) HasMaxExtraProfiles() bool`

HasMaxExtraProfiles returns a boolean if a field has been set.

### SetMaxExtraProfilesNil

`func (o *OwnedMediaPlatformProfiles) SetMaxExtraProfilesNil(b bool)`

 SetMaxExtraProfilesNil sets the value for MaxExtraProfiles to be an explicit nil

### UnsetMaxExtraProfiles
`func (o *OwnedMediaPlatformProfiles) UnsetMaxExtraProfiles()`

UnsetMaxExtraProfiles ensures that no value is present for MaxExtraProfiles, not even an explicit nil
### GetProfiles

`func (o *OwnedMediaPlatformProfiles) GetProfiles() []OwnedMediaProfile`

GetProfiles returns the Profiles field if non-nil, zero value otherwise.

### GetProfilesOk

`func (o *OwnedMediaPlatformProfiles) GetProfilesOk() (*[]OwnedMediaProfile, bool)`

GetProfilesOk returns a tuple with the Profiles field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProfiles

`func (o *OwnedMediaPlatformProfiles) SetProfiles(v []OwnedMediaProfile)`

SetProfiles sets Profiles field to given value.

### HasProfiles

`func (o *OwnedMediaPlatformProfiles) HasProfiles() bool`

HasProfiles returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


