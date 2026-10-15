# OwnedMediaProfilesUpdateResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ProjectId** | Pointer to **int32** |  | [optional] 
**Platforms** | Pointer to [**[]OwnedMediaPlatformProfiles**](OwnedMediaPlatformProfiles.md) |  | [optional] 
**Settings** | Pointer to [**OwnedMediaProfileSettings**](OwnedMediaProfileSettings.md) |  | [optional] 
**RequestId** | Pointer to **string** |  | [optional] 
**UpdatedFields** | Pointer to **[]string** | The fields this request set | [optional] 
**ProfileScrapesQueued** | Pointer to **[]string** | Platforms whose new profile is being scraped in the background for its name and avatar | [optional] 

## Methods

### NewOwnedMediaProfilesUpdateResponse

`func NewOwnedMediaProfilesUpdateResponse() *OwnedMediaProfilesUpdateResponse`

NewOwnedMediaProfilesUpdateResponse instantiates a new OwnedMediaProfilesUpdateResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOwnedMediaProfilesUpdateResponseWithDefaults

`func NewOwnedMediaProfilesUpdateResponseWithDefaults() *OwnedMediaProfilesUpdateResponse`

NewOwnedMediaProfilesUpdateResponseWithDefaults instantiates a new OwnedMediaProfilesUpdateResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProjectId

`func (o *OwnedMediaProfilesUpdateResponse) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *OwnedMediaProfilesUpdateResponse) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *OwnedMediaProfilesUpdateResponse) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.

### HasProjectId

`func (o *OwnedMediaProfilesUpdateResponse) HasProjectId() bool`

HasProjectId returns a boolean if a field has been set.

### GetPlatforms

`func (o *OwnedMediaProfilesUpdateResponse) GetPlatforms() []OwnedMediaPlatformProfiles`

GetPlatforms returns the Platforms field if non-nil, zero value otherwise.

### GetPlatformsOk

`func (o *OwnedMediaProfilesUpdateResponse) GetPlatformsOk() (*[]OwnedMediaPlatformProfiles, bool)`

GetPlatformsOk returns a tuple with the Platforms field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlatforms

`func (o *OwnedMediaProfilesUpdateResponse) SetPlatforms(v []OwnedMediaPlatformProfiles)`

SetPlatforms sets Platforms field to given value.

### HasPlatforms

`func (o *OwnedMediaProfilesUpdateResponse) HasPlatforms() bool`

HasPlatforms returns a boolean if a field has been set.

### GetSettings

`func (o *OwnedMediaProfilesUpdateResponse) GetSettings() OwnedMediaProfileSettings`

GetSettings returns the Settings field if non-nil, zero value otherwise.

### GetSettingsOk

`func (o *OwnedMediaProfilesUpdateResponse) GetSettingsOk() (*OwnedMediaProfileSettings, bool)`

GetSettingsOk returns a tuple with the Settings field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSettings

`func (o *OwnedMediaProfilesUpdateResponse) SetSettings(v OwnedMediaProfileSettings)`

SetSettings sets Settings field to given value.

### HasSettings

`func (o *OwnedMediaProfilesUpdateResponse) HasSettings() bool`

HasSettings returns a boolean if a field has been set.

### GetRequestId

`func (o *OwnedMediaProfilesUpdateResponse) GetRequestId() string`

GetRequestId returns the RequestId field if non-nil, zero value otherwise.

### GetRequestIdOk

`func (o *OwnedMediaProfilesUpdateResponse) GetRequestIdOk() (*string, bool)`

GetRequestIdOk returns a tuple with the RequestId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestId

`func (o *OwnedMediaProfilesUpdateResponse) SetRequestId(v string)`

SetRequestId sets RequestId field to given value.

### HasRequestId

`func (o *OwnedMediaProfilesUpdateResponse) HasRequestId() bool`

HasRequestId returns a boolean if a field has been set.

### GetUpdatedFields

`func (o *OwnedMediaProfilesUpdateResponse) GetUpdatedFields() []string`

GetUpdatedFields returns the UpdatedFields field if non-nil, zero value otherwise.

### GetUpdatedFieldsOk

`func (o *OwnedMediaProfilesUpdateResponse) GetUpdatedFieldsOk() (*[]string, bool)`

GetUpdatedFieldsOk returns a tuple with the UpdatedFields field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedFields

`func (o *OwnedMediaProfilesUpdateResponse) SetUpdatedFields(v []string)`

SetUpdatedFields sets UpdatedFields field to given value.

### HasUpdatedFields

`func (o *OwnedMediaProfilesUpdateResponse) HasUpdatedFields() bool`

HasUpdatedFields returns a boolean if a field has been set.

### GetProfileScrapesQueued

`func (o *OwnedMediaProfilesUpdateResponse) GetProfileScrapesQueued() []string`

GetProfileScrapesQueued returns the ProfileScrapesQueued field if non-nil, zero value otherwise.

### GetProfileScrapesQueuedOk

`func (o *OwnedMediaProfilesUpdateResponse) GetProfileScrapesQueuedOk() (*[]string, bool)`

GetProfileScrapesQueuedOk returns a tuple with the ProfileScrapesQueued field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProfileScrapesQueued

`func (o *OwnedMediaProfilesUpdateResponse) SetProfileScrapesQueued(v []string)`

SetProfileScrapesQueued sets ProfileScrapesQueued field to given value.

### HasProfileScrapesQueued

`func (o *OwnedMediaProfilesUpdateResponse) HasProfileScrapesQueued() bool`

HasProfileScrapesQueued returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


