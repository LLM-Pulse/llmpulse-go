# Ping200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Ok** | Pointer to **bool** |  | [optional] 
**UserId** | Pointer to **int32** |  | [optional] 
**Project** | Pointer to [**Project**](Project.md) |  | [optional] 
**RequestId** | Pointer to **string** |  | [optional] 

## Methods

### NewPing200Response

`func NewPing200Response() *Ping200Response`

NewPing200Response instantiates a new Ping200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPing200ResponseWithDefaults

`func NewPing200ResponseWithDefaults() *Ping200Response`

NewPing200ResponseWithDefaults instantiates a new Ping200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetOk

`func (o *Ping200Response) GetOk() bool`

GetOk returns the Ok field if non-nil, zero value otherwise.

### GetOkOk

`func (o *Ping200Response) GetOkOk() (*bool, bool)`

GetOkOk returns a tuple with the Ok field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOk

`func (o *Ping200Response) SetOk(v bool)`

SetOk sets Ok field to given value.

### HasOk

`func (o *Ping200Response) HasOk() bool`

HasOk returns a boolean if a field has been set.

### GetUserId

`func (o *Ping200Response) GetUserId() int32`

GetUserId returns the UserId field if non-nil, zero value otherwise.

### GetUserIdOk

`func (o *Ping200Response) GetUserIdOk() (*int32, bool)`

GetUserIdOk returns a tuple with the UserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserId

`func (o *Ping200Response) SetUserId(v int32)`

SetUserId sets UserId field to given value.

### HasUserId

`func (o *Ping200Response) HasUserId() bool`

HasUserId returns a boolean if a field has been set.

### GetProject

`func (o *Ping200Response) GetProject() Project`

GetProject returns the Project field if non-nil, zero value otherwise.

### GetProjectOk

`func (o *Ping200Response) GetProjectOk() (*Project, bool)`

GetProjectOk returns a tuple with the Project field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProject

`func (o *Ping200Response) SetProject(v Project)`

SetProject sets Project field to given value.

### HasProject

`func (o *Ping200Response) HasProject() bool`

HasProject returns a boolean if a field has been set.

### GetRequestId

`func (o *Ping200Response) GetRequestId() string`

GetRequestId returns the RequestId field if non-nil, zero value otherwise.

### GetRequestIdOk

`func (o *Ping200Response) GetRequestIdOk() (*string, bool)`

GetRequestIdOk returns a tuple with the RequestId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestId

`func (o *Ping200Response) SetRequestId(v string)`

SetRequestId sets RequestId field to given value.

### HasRequestId

`func (o *Ping200Response) HasRequestId() bool`

HasRequestId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


