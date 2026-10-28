# CreateApiKey201Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **int32** |  | 
**Name** | **string** |  | 
**Prefix** | **string** | The visible start of the token, to recognize the key. Never the secret itself. | 
**Scope** | **string** |  | 
**ProjectScoped** | **bool** | True when the key is limited to project_ids; false for an account-wide key. | 
**ProjectIds** | **[]int32** | The projects the key is limited to; empty for an account-wide key. | 
**CreatedAt** | **time.Time** |  | 
**LastUsedAt** | **NullableTime** | Updated at most once a minute. | 
**RevokedAt** | **NullableTime** |  | 
**Token** | **string** | The secret to send as Bearer token. Shown only in this response. | 
**RequestId** | Pointer to **string** |  | [optional] 

## Methods

### NewCreateApiKey201Response

`func NewCreateApiKey201Response(id int32, name string, prefix string, scope string, projectScoped bool, projectIds []int32, createdAt time.Time, lastUsedAt NullableTime, revokedAt NullableTime, token string, ) *CreateApiKey201Response`

NewCreateApiKey201Response instantiates a new CreateApiKey201Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateApiKey201ResponseWithDefaults

`func NewCreateApiKey201ResponseWithDefaults() *CreateApiKey201Response`

NewCreateApiKey201ResponseWithDefaults instantiates a new CreateApiKey201Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *CreateApiKey201Response) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *CreateApiKey201Response) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *CreateApiKey201Response) SetId(v int32)`

SetId sets Id field to given value.


### GetName

`func (o *CreateApiKey201Response) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *CreateApiKey201Response) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *CreateApiKey201Response) SetName(v string)`

SetName sets Name field to given value.


### GetPrefix

`func (o *CreateApiKey201Response) GetPrefix() string`

GetPrefix returns the Prefix field if non-nil, zero value otherwise.

### GetPrefixOk

`func (o *CreateApiKey201Response) GetPrefixOk() (*string, bool)`

GetPrefixOk returns a tuple with the Prefix field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrefix

`func (o *CreateApiKey201Response) SetPrefix(v string)`

SetPrefix sets Prefix field to given value.


### GetScope

`func (o *CreateApiKey201Response) GetScope() string`

GetScope returns the Scope field if non-nil, zero value otherwise.

### GetScopeOk

`func (o *CreateApiKey201Response) GetScopeOk() (*string, bool)`

GetScopeOk returns a tuple with the Scope field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScope

`func (o *CreateApiKey201Response) SetScope(v string)`

SetScope sets Scope field to given value.


### GetProjectScoped

`func (o *CreateApiKey201Response) GetProjectScoped() bool`

GetProjectScoped returns the ProjectScoped field if non-nil, zero value otherwise.

### GetProjectScopedOk

`func (o *CreateApiKey201Response) GetProjectScopedOk() (*bool, bool)`

GetProjectScopedOk returns a tuple with the ProjectScoped field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectScoped

`func (o *CreateApiKey201Response) SetProjectScoped(v bool)`

SetProjectScoped sets ProjectScoped field to given value.


### GetProjectIds

`func (o *CreateApiKey201Response) GetProjectIds() []int32`

GetProjectIds returns the ProjectIds field if non-nil, zero value otherwise.

### GetProjectIdsOk

`func (o *CreateApiKey201Response) GetProjectIdsOk() (*[]int32, bool)`

GetProjectIdsOk returns a tuple with the ProjectIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectIds

`func (o *CreateApiKey201Response) SetProjectIds(v []int32)`

SetProjectIds sets ProjectIds field to given value.


### GetCreatedAt

`func (o *CreateApiKey201Response) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *CreateApiKey201Response) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *CreateApiKey201Response) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetLastUsedAt

`func (o *CreateApiKey201Response) GetLastUsedAt() time.Time`

GetLastUsedAt returns the LastUsedAt field if non-nil, zero value otherwise.

### GetLastUsedAtOk

`func (o *CreateApiKey201Response) GetLastUsedAtOk() (*time.Time, bool)`

GetLastUsedAtOk returns a tuple with the LastUsedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastUsedAt

`func (o *CreateApiKey201Response) SetLastUsedAt(v time.Time)`

SetLastUsedAt sets LastUsedAt field to given value.


### SetLastUsedAtNil

`func (o *CreateApiKey201Response) SetLastUsedAtNil(b bool)`

 SetLastUsedAtNil sets the value for LastUsedAt to be an explicit nil

### UnsetLastUsedAt
`func (o *CreateApiKey201Response) UnsetLastUsedAt()`

UnsetLastUsedAt ensures that no value is present for LastUsedAt, not even an explicit nil
### GetRevokedAt

`func (o *CreateApiKey201Response) GetRevokedAt() time.Time`

GetRevokedAt returns the RevokedAt field if non-nil, zero value otherwise.

### GetRevokedAtOk

`func (o *CreateApiKey201Response) GetRevokedAtOk() (*time.Time, bool)`

GetRevokedAtOk returns a tuple with the RevokedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRevokedAt

`func (o *CreateApiKey201Response) SetRevokedAt(v time.Time)`

SetRevokedAt sets RevokedAt field to given value.


### SetRevokedAtNil

`func (o *CreateApiKey201Response) SetRevokedAtNil(b bool)`

 SetRevokedAtNil sets the value for RevokedAt to be an explicit nil

### UnsetRevokedAt
`func (o *CreateApiKey201Response) UnsetRevokedAt()`

UnsetRevokedAt ensures that no value is present for RevokedAt, not even an explicit nil
### GetToken

`func (o *CreateApiKey201Response) GetToken() string`

GetToken returns the Token field if non-nil, zero value otherwise.

### GetTokenOk

`func (o *CreateApiKey201Response) GetTokenOk() (*string, bool)`

GetTokenOk returns a tuple with the Token field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetToken

`func (o *CreateApiKey201Response) SetToken(v string)`

SetToken sets Token field to given value.


### GetRequestId

`func (o *CreateApiKey201Response) GetRequestId() string`

GetRequestId returns the RequestId field if non-nil, zero value otherwise.

### GetRequestIdOk

`func (o *CreateApiKey201Response) GetRequestIdOk() (*string, bool)`

GetRequestIdOk returns a tuple with the RequestId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestId

`func (o *CreateApiKey201Response) SetRequestId(v string)`

SetRequestId sets RequestId field to given value.

### HasRequestId

`func (o *CreateApiKey201Response) HasRequestId() bool`

HasRequestId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


