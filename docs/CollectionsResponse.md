# CollectionsResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ProjectId** | **int32** |  | 
**Collections** | [**[]TagRef**](TagRef.md) |  | 
**RequestId** | **string** |  | 

## Methods

### NewCollectionsResponse

`func NewCollectionsResponse(projectId int32, collections []TagRef, requestId string, ) *CollectionsResponse`

NewCollectionsResponse instantiates a new CollectionsResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCollectionsResponseWithDefaults

`func NewCollectionsResponseWithDefaults() *CollectionsResponse`

NewCollectionsResponseWithDefaults instantiates a new CollectionsResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProjectId

`func (o *CollectionsResponse) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *CollectionsResponse) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *CollectionsResponse) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.


### GetCollections

`func (o *CollectionsResponse) GetCollections() []TagRef`

GetCollections returns the Collections field if non-nil, zero value otherwise.

### GetCollectionsOk

`func (o *CollectionsResponse) GetCollectionsOk() (*[]TagRef, bool)`

GetCollectionsOk returns a tuple with the Collections field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCollections

`func (o *CollectionsResponse) SetCollections(v []TagRef)`

SetCollections sets Collections field to given value.


### GetRequestId

`func (o *CollectionsResponse) GetRequestId() string`

GetRequestId returns the RequestId field if non-nil, zero value otherwise.

### GetRequestIdOk

`func (o *CollectionsResponse) GetRequestIdOk() (*string, bool)`

GetRequestIdOk returns a tuple with the RequestId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestId

`func (o *CollectionsResponse) SetRequestId(v string)`

SetRequestId sets RequestId field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


