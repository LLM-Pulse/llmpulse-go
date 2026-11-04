# CmsSendResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ProjectId** | Pointer to **int32** |  | [optional] 
**Created** | Pointer to **bool** | false when this version had already been sent and the existing publication is returned | [optional] 
**Publication** | Pointer to [**CmsPublication**](CmsPublication.md) |  | [optional] 
**RequestId** | Pointer to **string** |  | [optional] 

## Methods

### NewCmsSendResponse

`func NewCmsSendResponse() *CmsSendResponse`

NewCmsSendResponse instantiates a new CmsSendResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCmsSendResponseWithDefaults

`func NewCmsSendResponseWithDefaults() *CmsSendResponse`

NewCmsSendResponseWithDefaults instantiates a new CmsSendResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProjectId

`func (o *CmsSendResponse) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *CmsSendResponse) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *CmsSendResponse) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.

### HasProjectId

`func (o *CmsSendResponse) HasProjectId() bool`

HasProjectId returns a boolean if a field has been set.

### GetCreated

`func (o *CmsSendResponse) GetCreated() bool`

GetCreated returns the Created field if non-nil, zero value otherwise.

### GetCreatedOk

`func (o *CmsSendResponse) GetCreatedOk() (*bool, bool)`

GetCreatedOk returns a tuple with the Created field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreated

`func (o *CmsSendResponse) SetCreated(v bool)`

SetCreated sets Created field to given value.

### HasCreated

`func (o *CmsSendResponse) HasCreated() bool`

HasCreated returns a boolean if a field has been set.

### GetPublication

`func (o *CmsSendResponse) GetPublication() CmsPublication`

GetPublication returns the Publication field if non-nil, zero value otherwise.

### GetPublicationOk

`func (o *CmsSendResponse) GetPublicationOk() (*CmsPublication, bool)`

GetPublicationOk returns a tuple with the Publication field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPublication

`func (o *CmsSendResponse) SetPublication(v CmsPublication)`

SetPublication sets Publication field to given value.

### HasPublication

`func (o *CmsSendResponse) HasPublication() bool`

HasPublication returns a boolean if a field has been set.

### GetRequestId

`func (o *CmsSendResponse) GetRequestId() string`

GetRequestId returns the RequestId field if non-nil, zero value otherwise.

### GetRequestIdOk

`func (o *CmsSendResponse) GetRequestIdOk() (*string, bool)`

GetRequestIdOk returns a tuple with the RequestId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestId

`func (o *CmsSendResponse) SetRequestId(v string)`

SetRequestId sets RequestId field to given value.

### HasRequestId

`func (o *CmsSendResponse) HasRequestId() bool`

HasRequestId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


