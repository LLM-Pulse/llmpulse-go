# CollectionUpdateResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ProjectId** | **int32** |  | 
**Collection** | [**CollectionUpdateResponseCollection**](CollectionUpdateResponseCollection.md) |  | 
**RequestId** | **string** |  | 

## Methods

### NewCollectionUpdateResponse

`func NewCollectionUpdateResponse(projectId int32, collection CollectionUpdateResponseCollection, requestId string, ) *CollectionUpdateResponse`

NewCollectionUpdateResponse instantiates a new CollectionUpdateResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCollectionUpdateResponseWithDefaults

`func NewCollectionUpdateResponseWithDefaults() *CollectionUpdateResponse`

NewCollectionUpdateResponseWithDefaults instantiates a new CollectionUpdateResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProjectId

`func (o *CollectionUpdateResponse) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *CollectionUpdateResponse) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *CollectionUpdateResponse) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.


### GetCollection

`func (o *CollectionUpdateResponse) GetCollection() CollectionUpdateResponseCollection`

GetCollection returns the Collection field if non-nil, zero value otherwise.

### GetCollectionOk

`func (o *CollectionUpdateResponse) GetCollectionOk() (*CollectionUpdateResponseCollection, bool)`

GetCollectionOk returns a tuple with the Collection field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCollection

`func (o *CollectionUpdateResponse) SetCollection(v CollectionUpdateResponseCollection)`

SetCollection sets Collection field to given value.


### GetRequestId

`func (o *CollectionUpdateResponse) GetRequestId() string`

GetRequestId returns the RequestId field if non-nil, zero value otherwise.

### GetRequestIdOk

`func (o *CollectionUpdateResponse) GetRequestIdOk() (*string, bool)`

GetRequestIdOk returns a tuple with the RequestId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestId

`func (o *CollectionUpdateResponse) SetRequestId(v string)`

SetRequestId sets RequestId field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


