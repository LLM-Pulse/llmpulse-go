# ListApiKeys200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Page** | Pointer to **int32** |  | [optional] 
**PerPage** | Pointer to **int32** |  | [optional] 
**Total** | Pointer to **int32** |  | [optional] 
**Data** | Pointer to [**[]ApiKeyInfo**](ApiKeyInfo.md) |  | [optional] 
**RequestId** | Pointer to **string** |  | [optional] 

## Methods

### NewListApiKeys200Response

`func NewListApiKeys200Response() *ListApiKeys200Response`

NewListApiKeys200Response instantiates a new ListApiKeys200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewListApiKeys200ResponseWithDefaults

`func NewListApiKeys200ResponseWithDefaults() *ListApiKeys200Response`

NewListApiKeys200ResponseWithDefaults instantiates a new ListApiKeys200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPage

`func (o *ListApiKeys200Response) GetPage() int32`

GetPage returns the Page field if non-nil, zero value otherwise.

### GetPageOk

`func (o *ListApiKeys200Response) GetPageOk() (*int32, bool)`

GetPageOk returns a tuple with the Page field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPage

`func (o *ListApiKeys200Response) SetPage(v int32)`

SetPage sets Page field to given value.

### HasPage

`func (o *ListApiKeys200Response) HasPage() bool`

HasPage returns a boolean if a field has been set.

### GetPerPage

`func (o *ListApiKeys200Response) GetPerPage() int32`

GetPerPage returns the PerPage field if non-nil, zero value otherwise.

### GetPerPageOk

`func (o *ListApiKeys200Response) GetPerPageOk() (*int32, bool)`

GetPerPageOk returns a tuple with the PerPage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPerPage

`func (o *ListApiKeys200Response) SetPerPage(v int32)`

SetPerPage sets PerPage field to given value.

### HasPerPage

`func (o *ListApiKeys200Response) HasPerPage() bool`

HasPerPage returns a boolean if a field has been set.

### GetTotal

`func (o *ListApiKeys200Response) GetTotal() int32`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *ListApiKeys200Response) GetTotalOk() (*int32, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *ListApiKeys200Response) SetTotal(v int32)`

SetTotal sets Total field to given value.

### HasTotal

`func (o *ListApiKeys200Response) HasTotal() bool`

HasTotal returns a boolean if a field has been set.

### GetData

`func (o *ListApiKeys200Response) GetData() []ApiKeyInfo`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *ListApiKeys200Response) GetDataOk() (*[]ApiKeyInfo, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *ListApiKeys200Response) SetData(v []ApiKeyInfo)`

SetData sets Data field to given value.

### HasData

`func (o *ListApiKeys200Response) HasData() bool`

HasData returns a boolean if a field has been set.

### GetRequestId

`func (o *ListApiKeys200Response) GetRequestId() string`

GetRequestId returns the RequestId field if non-nil, zero value otherwise.

### GetRequestIdOk

`func (o *ListApiKeys200Response) GetRequestIdOk() (*string, bool)`

GetRequestIdOk returns a tuple with the RequestId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestId

`func (o *ListApiKeys200Response) SetRequestId(v string)`

SetRequestId sets RequestId field to given value.

### HasRequestId

`func (o *ListApiKeys200Response) HasRequestId() bool`

HasRequestId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


