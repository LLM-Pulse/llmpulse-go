# RevokeApiKey200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Revoked** | Pointer to **bool** |  | [optional] 
**Id** | Pointer to **int32** |  | [optional] 
**RevokedAt** | Pointer to **time.Time** |  | [optional] 
**RequestId** | Pointer to **string** |  | [optional] 

## Methods

### NewRevokeApiKey200Response

`func NewRevokeApiKey200Response() *RevokeApiKey200Response`

NewRevokeApiKey200Response instantiates a new RevokeApiKey200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRevokeApiKey200ResponseWithDefaults

`func NewRevokeApiKey200ResponseWithDefaults() *RevokeApiKey200Response`

NewRevokeApiKey200ResponseWithDefaults instantiates a new RevokeApiKey200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetRevoked

`func (o *RevokeApiKey200Response) GetRevoked() bool`

GetRevoked returns the Revoked field if non-nil, zero value otherwise.

### GetRevokedOk

`func (o *RevokeApiKey200Response) GetRevokedOk() (*bool, bool)`

GetRevokedOk returns a tuple with the Revoked field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRevoked

`func (o *RevokeApiKey200Response) SetRevoked(v bool)`

SetRevoked sets Revoked field to given value.

### HasRevoked

`func (o *RevokeApiKey200Response) HasRevoked() bool`

HasRevoked returns a boolean if a field has been set.

### GetId

`func (o *RevokeApiKey200Response) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *RevokeApiKey200Response) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *RevokeApiKey200Response) SetId(v int32)`

SetId sets Id field to given value.

### HasId

`func (o *RevokeApiKey200Response) HasId() bool`

HasId returns a boolean if a field has been set.

### GetRevokedAt

`func (o *RevokeApiKey200Response) GetRevokedAt() time.Time`

GetRevokedAt returns the RevokedAt field if non-nil, zero value otherwise.

### GetRevokedAtOk

`func (o *RevokeApiKey200Response) GetRevokedAtOk() (*time.Time, bool)`

GetRevokedAtOk returns a tuple with the RevokedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRevokedAt

`func (o *RevokeApiKey200Response) SetRevokedAt(v time.Time)`

SetRevokedAt sets RevokedAt field to given value.

### HasRevokedAt

`func (o *RevokeApiKey200Response) HasRevokedAt() bool`

HasRevokedAt returns a boolean if a field has been set.

### GetRequestId

`func (o *RevokeApiKey200Response) GetRequestId() string`

GetRequestId returns the RequestId field if non-nil, zero value otherwise.

### GetRequestIdOk

`func (o *RevokeApiKey200Response) GetRequestIdOk() (*string, bool)`

GetRequestIdOk returns a tuple with the RequestId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestId

`func (o *RevokeApiKey200Response) SetRequestId(v string)`

SetRequestId sets RequestId field to given value.

### HasRequestId

`func (o *RevokeApiKey200Response) HasRequestId() bool`

HasRequestId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


