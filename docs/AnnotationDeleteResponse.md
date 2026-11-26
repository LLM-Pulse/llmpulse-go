# AnnotationDeleteResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ProjectId** | **int32** |  | 
**Deleted** | **bool** | Always true | 
**Id** | **int32** |  | 
**Title** | **string** |  | 
**RequestId** | **string** |  | 

## Methods

### NewAnnotationDeleteResponse

`func NewAnnotationDeleteResponse(projectId int32, deleted bool, id int32, title string, requestId string, ) *AnnotationDeleteResponse`

NewAnnotationDeleteResponse instantiates a new AnnotationDeleteResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAnnotationDeleteResponseWithDefaults

`func NewAnnotationDeleteResponseWithDefaults() *AnnotationDeleteResponse`

NewAnnotationDeleteResponseWithDefaults instantiates a new AnnotationDeleteResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProjectId

`func (o *AnnotationDeleteResponse) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *AnnotationDeleteResponse) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *AnnotationDeleteResponse) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.


### GetDeleted

`func (o *AnnotationDeleteResponse) GetDeleted() bool`

GetDeleted returns the Deleted field if non-nil, zero value otherwise.

### GetDeletedOk

`func (o *AnnotationDeleteResponse) GetDeletedOk() (*bool, bool)`

GetDeletedOk returns a tuple with the Deleted field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeleted

`func (o *AnnotationDeleteResponse) SetDeleted(v bool)`

SetDeleted sets Deleted field to given value.


### GetId

`func (o *AnnotationDeleteResponse) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *AnnotationDeleteResponse) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *AnnotationDeleteResponse) SetId(v int32)`

SetId sets Id field to given value.


### GetTitle

`func (o *AnnotationDeleteResponse) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *AnnotationDeleteResponse) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *AnnotationDeleteResponse) SetTitle(v string)`

SetTitle sets Title field to given value.


### GetRequestId

`func (o *AnnotationDeleteResponse) GetRequestId() string`

GetRequestId returns the RequestId field if non-nil, zero value otherwise.

### GetRequestIdOk

`func (o *AnnotationDeleteResponse) GetRequestIdOk() (*string, bool)`

GetRequestIdOk returns a tuple with the RequestId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestId

`func (o *AnnotationDeleteResponse) SetRequestId(v string)`

SetRequestId sets RequestId field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


