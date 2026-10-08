# CollectionCreateResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ProjectId** | **int32** |  | 
**Collection** | [**CollectionCreateResponseCollection**](CollectionCreateResponseCollection.md) |  | 
**PromptsAttached** | **int32** | Existing prompts attached through prompt_ids | 
**TotalCollections** | **int32** |  | 
**RequestId** | **string** |  | 

## Methods

### NewCollectionCreateResponse

`func NewCollectionCreateResponse(projectId int32, collection CollectionCreateResponseCollection, promptsAttached int32, totalCollections int32, requestId string, ) *CollectionCreateResponse`

NewCollectionCreateResponse instantiates a new CollectionCreateResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCollectionCreateResponseWithDefaults

`func NewCollectionCreateResponseWithDefaults() *CollectionCreateResponse`

NewCollectionCreateResponseWithDefaults instantiates a new CollectionCreateResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProjectId

`func (o *CollectionCreateResponse) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *CollectionCreateResponse) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *CollectionCreateResponse) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.


### GetCollection

`func (o *CollectionCreateResponse) GetCollection() CollectionCreateResponseCollection`

GetCollection returns the Collection field if non-nil, zero value otherwise.

### GetCollectionOk

`func (o *CollectionCreateResponse) GetCollectionOk() (*CollectionCreateResponseCollection, bool)`

GetCollectionOk returns a tuple with the Collection field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCollection

`func (o *CollectionCreateResponse) SetCollection(v CollectionCreateResponseCollection)`

SetCollection sets Collection field to given value.


### GetPromptsAttached

`func (o *CollectionCreateResponse) GetPromptsAttached() int32`

GetPromptsAttached returns the PromptsAttached field if non-nil, zero value otherwise.

### GetPromptsAttachedOk

`func (o *CollectionCreateResponse) GetPromptsAttachedOk() (*int32, bool)`

GetPromptsAttachedOk returns a tuple with the PromptsAttached field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPromptsAttached

`func (o *CollectionCreateResponse) SetPromptsAttached(v int32)`

SetPromptsAttached sets PromptsAttached field to given value.


### GetTotalCollections

`func (o *CollectionCreateResponse) GetTotalCollections() int32`

GetTotalCollections returns the TotalCollections field if non-nil, zero value otherwise.

### GetTotalCollectionsOk

`func (o *CollectionCreateResponse) GetTotalCollectionsOk() (*int32, bool)`

GetTotalCollectionsOk returns a tuple with the TotalCollections field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalCollections

`func (o *CollectionCreateResponse) SetTotalCollections(v int32)`

SetTotalCollections sets TotalCollections field to given value.


### GetRequestId

`func (o *CollectionCreateResponse) GetRequestId() string`

GetRequestId returns the RequestId field if non-nil, zero value otherwise.

### GetRequestIdOk

`func (o *CollectionCreateResponse) GetRequestIdOk() (*string, bool)`

GetRequestIdOk returns a tuple with the RequestId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestId

`func (o *CollectionCreateResponse) SetRequestId(v string)`

SetRequestId sets RequestId field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


