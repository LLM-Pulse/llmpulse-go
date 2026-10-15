# OwnedMediaProfilesResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ProjectId** | Pointer to **int32** |  | [optional] 
**Platforms** | Pointer to [**[]OwnedMediaPlatformProfiles**](OwnedMediaPlatformProfiles.md) |  | [optional] 
**Settings** | Pointer to [**OwnedMediaProfileSettings**](OwnedMediaProfileSettings.md) |  | [optional] 
**RequestId** | Pointer to **string** |  | [optional] 

## Methods

### NewOwnedMediaProfilesResponse

`func NewOwnedMediaProfilesResponse() *OwnedMediaProfilesResponse`

NewOwnedMediaProfilesResponse instantiates a new OwnedMediaProfilesResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOwnedMediaProfilesResponseWithDefaults

`func NewOwnedMediaProfilesResponseWithDefaults() *OwnedMediaProfilesResponse`

NewOwnedMediaProfilesResponseWithDefaults instantiates a new OwnedMediaProfilesResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProjectId

`func (o *OwnedMediaProfilesResponse) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *OwnedMediaProfilesResponse) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *OwnedMediaProfilesResponse) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.

### HasProjectId

`func (o *OwnedMediaProfilesResponse) HasProjectId() bool`

HasProjectId returns a boolean if a field has been set.

### GetPlatforms

`func (o *OwnedMediaProfilesResponse) GetPlatforms() []OwnedMediaPlatformProfiles`

GetPlatforms returns the Platforms field if non-nil, zero value otherwise.

### GetPlatformsOk

`func (o *OwnedMediaProfilesResponse) GetPlatformsOk() (*[]OwnedMediaPlatformProfiles, bool)`

GetPlatformsOk returns a tuple with the Platforms field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlatforms

`func (o *OwnedMediaProfilesResponse) SetPlatforms(v []OwnedMediaPlatformProfiles)`

SetPlatforms sets Platforms field to given value.

### HasPlatforms

`func (o *OwnedMediaProfilesResponse) HasPlatforms() bool`

HasPlatforms returns a boolean if a field has been set.

### GetSettings

`func (o *OwnedMediaProfilesResponse) GetSettings() OwnedMediaProfileSettings`

GetSettings returns the Settings field if non-nil, zero value otherwise.

### GetSettingsOk

`func (o *OwnedMediaProfilesResponse) GetSettingsOk() (*OwnedMediaProfileSettings, bool)`

GetSettingsOk returns a tuple with the Settings field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSettings

`func (o *OwnedMediaProfilesResponse) SetSettings(v OwnedMediaProfileSettings)`

SetSettings sets Settings field to given value.

### HasSettings

`func (o *OwnedMediaProfilesResponse) HasSettings() bool`

HasSettings returns a boolean if a field has been set.

### GetRequestId

`func (o *OwnedMediaProfilesResponse) GetRequestId() string`

GetRequestId returns the RequestId field if non-nil, zero value otherwise.

### GetRequestIdOk

`func (o *OwnedMediaProfilesResponse) GetRequestIdOk() (*string, bool)`

GetRequestIdOk returns a tuple with the RequestId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestId

`func (o *OwnedMediaProfilesResponse) SetRequestId(v string)`

SetRequestId sets RequestId field to given value.

### HasRequestId

`func (o *OwnedMediaProfilesResponse) HasRequestId() bool`

HasRequestId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


