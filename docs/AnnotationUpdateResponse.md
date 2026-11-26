# AnnotationUpdateResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ProjectId** | **int32** |  | 
**Annotation** | [**AnnotationRecord**](AnnotationRecord.md) |  | 
**RequestId** | **string** |  | 

## Methods

### NewAnnotationUpdateResponse

`func NewAnnotationUpdateResponse(projectId int32, annotation AnnotationRecord, requestId string, ) *AnnotationUpdateResponse`

NewAnnotationUpdateResponse instantiates a new AnnotationUpdateResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAnnotationUpdateResponseWithDefaults

`func NewAnnotationUpdateResponseWithDefaults() *AnnotationUpdateResponse`

NewAnnotationUpdateResponseWithDefaults instantiates a new AnnotationUpdateResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProjectId

`func (o *AnnotationUpdateResponse) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *AnnotationUpdateResponse) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *AnnotationUpdateResponse) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.


### GetAnnotation

`func (o *AnnotationUpdateResponse) GetAnnotation() AnnotationRecord`

GetAnnotation returns the Annotation field if non-nil, zero value otherwise.

### GetAnnotationOk

`func (o *AnnotationUpdateResponse) GetAnnotationOk() (*AnnotationRecord, bool)`

GetAnnotationOk returns a tuple with the Annotation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAnnotation

`func (o *AnnotationUpdateResponse) SetAnnotation(v AnnotationRecord)`

SetAnnotation sets Annotation field to given value.


### GetRequestId

`func (o *AnnotationUpdateResponse) GetRequestId() string`

GetRequestId returns the RequestId field if non-nil, zero value otherwise.

### GetRequestIdOk

`func (o *AnnotationUpdateResponse) GetRequestIdOk() (*string, bool)`

GetRequestIdOk returns a tuple with the RequestId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestId

`func (o *AnnotationUpdateResponse) SetRequestId(v string)`

SetRequestId sets RequestId field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


