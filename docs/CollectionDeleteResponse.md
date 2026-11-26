# CollectionDeleteResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ProjectId** | **int32** |  | 
**Deleted** | **bool** | Always true | 
**Id** | **int32** |  | 
**Name** | **string** |  | 
**PromptsKept** | **int32** | Prompts the collection held; they stay in the project | 
**TotalCollections** | **int32** | Collections left in the project | 
**RequestId** | **string** |  | 

## Methods

### NewCollectionDeleteResponse

`func NewCollectionDeleteResponse(projectId int32, deleted bool, id int32, name string, promptsKept int32, totalCollections int32, requestId string, ) *CollectionDeleteResponse`

NewCollectionDeleteResponse instantiates a new CollectionDeleteResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCollectionDeleteResponseWithDefaults

`func NewCollectionDeleteResponseWithDefaults() *CollectionDeleteResponse`

NewCollectionDeleteResponseWithDefaults instantiates a new CollectionDeleteResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProjectId

`func (o *CollectionDeleteResponse) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *CollectionDeleteResponse) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *CollectionDeleteResponse) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.


### GetDeleted

`func (o *CollectionDeleteResponse) GetDeleted() bool`

GetDeleted returns the Deleted field if non-nil, zero value otherwise.

### GetDeletedOk

`func (o *CollectionDeleteResponse) GetDeletedOk() (*bool, bool)`

GetDeletedOk returns a tuple with the Deleted field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeleted

`func (o *CollectionDeleteResponse) SetDeleted(v bool)`

SetDeleted sets Deleted field to given value.


### GetId

`func (o *CollectionDeleteResponse) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *CollectionDeleteResponse) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *CollectionDeleteResponse) SetId(v int32)`

SetId sets Id field to given value.


### GetName

`func (o *CollectionDeleteResponse) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *CollectionDeleteResponse) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *CollectionDeleteResponse) SetName(v string)`

SetName sets Name field to given value.


### GetPromptsKept

`func (o *CollectionDeleteResponse) GetPromptsKept() int32`

GetPromptsKept returns the PromptsKept field if non-nil, zero value otherwise.

### GetPromptsKeptOk

`func (o *CollectionDeleteResponse) GetPromptsKeptOk() (*int32, bool)`

GetPromptsKeptOk returns a tuple with the PromptsKept field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPromptsKept

`func (o *CollectionDeleteResponse) SetPromptsKept(v int32)`

SetPromptsKept sets PromptsKept field to given value.


### GetTotalCollections

`func (o *CollectionDeleteResponse) GetTotalCollections() int32`

GetTotalCollections returns the TotalCollections field if non-nil, zero value otherwise.

### GetTotalCollectionsOk

`func (o *CollectionDeleteResponse) GetTotalCollectionsOk() (*int32, bool)`

GetTotalCollectionsOk returns a tuple with the TotalCollections field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalCollections

`func (o *CollectionDeleteResponse) SetTotalCollections(v int32)`

SetTotalCollections sets TotalCollections field to given value.


### GetRequestId

`func (o *CollectionDeleteResponse) GetRequestId() string`

GetRequestId returns the RequestId field if non-nil, zero value otherwise.

### GetRequestIdOk

`func (o *CollectionDeleteResponse) GetRequestIdOk() (*string, bool)`

GetRequestIdOk returns a tuple with the RequestId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestId

`func (o *CollectionDeleteResponse) SetRequestId(v string)`

SetRequestId sets RequestId field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


