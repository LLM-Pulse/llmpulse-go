# AnnotationCreateResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ProjectId** | **int32** |  | 
**Annotation** | [**AnnotationCreateResponseAnnotation**](AnnotationCreateResponseAnnotation.md) |  | 
**RequestId** | **string** |  | 

## Methods

### NewAnnotationCreateResponse

`func NewAnnotationCreateResponse(projectId int32, annotation AnnotationCreateResponseAnnotation, requestId string, ) *AnnotationCreateResponse`

NewAnnotationCreateResponse instantiates a new AnnotationCreateResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAnnotationCreateResponseWithDefaults

`func NewAnnotationCreateResponseWithDefaults() *AnnotationCreateResponse`

NewAnnotationCreateResponseWithDefaults instantiates a new AnnotationCreateResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProjectId

`func (o *AnnotationCreateResponse) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *AnnotationCreateResponse) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *AnnotationCreateResponse) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.


### GetAnnotation

`func (o *AnnotationCreateResponse) GetAnnotation() AnnotationCreateResponseAnnotation`

GetAnnotation returns the Annotation field if non-nil, zero value otherwise.

### GetAnnotationOk

`func (o *AnnotationCreateResponse) GetAnnotationOk() (*AnnotationCreateResponseAnnotation, bool)`

GetAnnotationOk returns a tuple with the Annotation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAnnotation

`func (o *AnnotationCreateResponse) SetAnnotation(v AnnotationCreateResponseAnnotation)`

SetAnnotation sets Annotation field to given value.


### GetRequestId

`func (o *AnnotationCreateResponse) GetRequestId() string`

GetRequestId returns the RequestId field if non-nil, zero value otherwise.

### GetRequestIdOk

`func (o *AnnotationCreateResponse) GetRequestIdOk() (*string, bool)`

GetRequestIdOk returns a tuple with the RequestId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestId

`func (o *AnnotationCreateResponse) SetRequestId(v string)`

SetRequestId sets RequestId field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


