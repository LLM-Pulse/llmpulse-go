# SearchConsolePropertiesResponseDataInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | Property id, the value the property parameter takes, e.g. sc-domain:example.com | [optional] 
**Name** | Pointer to **string** |  | [optional] 
**Primary** | Pointer to **bool** | The property read when the property parameter is omitted | [optional] 
**Type** | Pointer to **string** |  | [optional] 
**Status** | Pointer to **string** |  | [optional] 
**LastSyncedAt** | Pointer to **NullableTime** |  | [optional] 

## Methods

### NewSearchConsolePropertiesResponseDataInner

`func NewSearchConsolePropertiesResponseDataInner() *SearchConsolePropertiesResponseDataInner`

NewSearchConsolePropertiesResponseDataInner instantiates a new SearchConsolePropertiesResponseDataInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSearchConsolePropertiesResponseDataInnerWithDefaults

`func NewSearchConsolePropertiesResponseDataInnerWithDefaults() *SearchConsolePropertiesResponseDataInner`

NewSearchConsolePropertiesResponseDataInnerWithDefaults instantiates a new SearchConsolePropertiesResponseDataInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *SearchConsolePropertiesResponseDataInner) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *SearchConsolePropertiesResponseDataInner) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *SearchConsolePropertiesResponseDataInner) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *SearchConsolePropertiesResponseDataInner) HasId() bool`

HasId returns a boolean if a field has been set.

### GetName

`func (o *SearchConsolePropertiesResponseDataInner) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *SearchConsolePropertiesResponseDataInner) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *SearchConsolePropertiesResponseDataInner) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *SearchConsolePropertiesResponseDataInner) HasName() bool`

HasName returns a boolean if a field has been set.

### GetPrimary

`func (o *SearchConsolePropertiesResponseDataInner) GetPrimary() bool`

GetPrimary returns the Primary field if non-nil, zero value otherwise.

### GetPrimaryOk

`func (o *SearchConsolePropertiesResponseDataInner) GetPrimaryOk() (*bool, bool)`

GetPrimaryOk returns a tuple with the Primary field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrimary

`func (o *SearchConsolePropertiesResponseDataInner) SetPrimary(v bool)`

SetPrimary sets Primary field to given value.

### HasPrimary

`func (o *SearchConsolePropertiesResponseDataInner) HasPrimary() bool`

HasPrimary returns a boolean if a field has been set.

### GetType

`func (o *SearchConsolePropertiesResponseDataInner) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *SearchConsolePropertiesResponseDataInner) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *SearchConsolePropertiesResponseDataInner) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *SearchConsolePropertiesResponseDataInner) HasType() bool`

HasType returns a boolean if a field has been set.

### GetStatus

`func (o *SearchConsolePropertiesResponseDataInner) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *SearchConsolePropertiesResponseDataInner) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *SearchConsolePropertiesResponseDataInner) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *SearchConsolePropertiesResponseDataInner) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetLastSyncedAt

`func (o *SearchConsolePropertiesResponseDataInner) GetLastSyncedAt() time.Time`

GetLastSyncedAt returns the LastSyncedAt field if non-nil, zero value otherwise.

### GetLastSyncedAtOk

`func (o *SearchConsolePropertiesResponseDataInner) GetLastSyncedAtOk() (*time.Time, bool)`

GetLastSyncedAtOk returns a tuple with the LastSyncedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastSyncedAt

`func (o *SearchConsolePropertiesResponseDataInner) SetLastSyncedAt(v time.Time)`

SetLastSyncedAt sets LastSyncedAt field to given value.

### HasLastSyncedAt

`func (o *SearchConsolePropertiesResponseDataInner) HasLastSyncedAt() bool`

HasLastSyncedAt returns a boolean if a field has been set.

### SetLastSyncedAtNil

`func (o *SearchConsolePropertiesResponseDataInner) SetLastSyncedAtNil(b bool)`

 SetLastSyncedAtNil sets the value for LastSyncedAt to be an explicit nil

### UnsetLastSyncedAt
`func (o *SearchConsolePropertiesResponseDataInner) UnsetLastSyncedAt()`

UnsetLastSyncedAt ensures that no value is present for LastSyncedAt, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


