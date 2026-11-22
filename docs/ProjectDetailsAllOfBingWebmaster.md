# ProjectDetailsAllOfBingWebmaster

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Status** | Pointer to **string** |  | [optional] 
**Site** | Pointer to **NullableString** | The connected site (e.g. https://example.com/), null when not connected | [optional] 
**LastSyncedAt** | Pointer to **NullableTime** | When that site last synced, null before its first sync | [optional] 
**ConnectUrl** | Pointer to **string** | The in-app page where the site is connected or reconnected (Preferences &gt; Project Settings &gt; Connections) | [optional] 

## Methods

### NewProjectDetailsAllOfBingWebmaster

`func NewProjectDetailsAllOfBingWebmaster() *ProjectDetailsAllOfBingWebmaster`

NewProjectDetailsAllOfBingWebmaster instantiates a new ProjectDetailsAllOfBingWebmaster object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProjectDetailsAllOfBingWebmasterWithDefaults

`func NewProjectDetailsAllOfBingWebmasterWithDefaults() *ProjectDetailsAllOfBingWebmaster`

NewProjectDetailsAllOfBingWebmasterWithDefaults instantiates a new ProjectDetailsAllOfBingWebmaster object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetStatus

`func (o *ProjectDetailsAllOfBingWebmaster) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *ProjectDetailsAllOfBingWebmaster) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *ProjectDetailsAllOfBingWebmaster) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *ProjectDetailsAllOfBingWebmaster) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetSite

`func (o *ProjectDetailsAllOfBingWebmaster) GetSite() string`

GetSite returns the Site field if non-nil, zero value otherwise.

### GetSiteOk

`func (o *ProjectDetailsAllOfBingWebmaster) GetSiteOk() (*string, bool)`

GetSiteOk returns a tuple with the Site field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSite

`func (o *ProjectDetailsAllOfBingWebmaster) SetSite(v string)`

SetSite sets Site field to given value.

### HasSite

`func (o *ProjectDetailsAllOfBingWebmaster) HasSite() bool`

HasSite returns a boolean if a field has been set.

### SetSiteNil

`func (o *ProjectDetailsAllOfBingWebmaster) SetSiteNil(b bool)`

 SetSiteNil sets the value for Site to be an explicit nil

### UnsetSite
`func (o *ProjectDetailsAllOfBingWebmaster) UnsetSite()`

UnsetSite ensures that no value is present for Site, not even an explicit nil
### GetLastSyncedAt

`func (o *ProjectDetailsAllOfBingWebmaster) GetLastSyncedAt() time.Time`

GetLastSyncedAt returns the LastSyncedAt field if non-nil, zero value otherwise.

### GetLastSyncedAtOk

`func (o *ProjectDetailsAllOfBingWebmaster) GetLastSyncedAtOk() (*time.Time, bool)`

GetLastSyncedAtOk returns a tuple with the LastSyncedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastSyncedAt

`func (o *ProjectDetailsAllOfBingWebmaster) SetLastSyncedAt(v time.Time)`

SetLastSyncedAt sets LastSyncedAt field to given value.

### HasLastSyncedAt

`func (o *ProjectDetailsAllOfBingWebmaster) HasLastSyncedAt() bool`

HasLastSyncedAt returns a boolean if a field has been set.

### SetLastSyncedAtNil

`func (o *ProjectDetailsAllOfBingWebmaster) SetLastSyncedAtNil(b bool)`

 SetLastSyncedAtNil sets the value for LastSyncedAt to be an explicit nil

### UnsetLastSyncedAt
`func (o *ProjectDetailsAllOfBingWebmaster) UnsetLastSyncedAt()`

UnsetLastSyncedAt ensures that no value is present for LastSyncedAt, not even an explicit nil
### GetConnectUrl

`func (o *ProjectDetailsAllOfBingWebmaster) GetConnectUrl() string`

GetConnectUrl returns the ConnectUrl field if non-nil, zero value otherwise.

### GetConnectUrlOk

`func (o *ProjectDetailsAllOfBingWebmaster) GetConnectUrlOk() (*string, bool)`

GetConnectUrlOk returns a tuple with the ConnectUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConnectUrl

`func (o *ProjectDetailsAllOfBingWebmaster) SetConnectUrl(v string)`

SetConnectUrl sets ConnectUrl field to given value.

### HasConnectUrl

`func (o *ProjectDetailsAllOfBingWebmaster) HasConnectUrl() bool`

HasConnectUrl returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


