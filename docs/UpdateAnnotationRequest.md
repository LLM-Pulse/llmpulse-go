# UpdateAnnotationRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ProjectId** | **int32** |  | 
**Title** | Pointer to **string** |  | [optional] 
**Description** | Pointer to **string** |  | [optional] 
**AnnotationDate** | Pointer to **string** |  | [optional] 
**Color** | Pointer to **string** |  | [optional] 
**AnnotationCategoryId** | Pointer to **int32** |  | [optional] 

## Methods

### NewUpdateAnnotationRequest

`func NewUpdateAnnotationRequest(projectId int32, ) *UpdateAnnotationRequest`

NewUpdateAnnotationRequest instantiates a new UpdateAnnotationRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUpdateAnnotationRequestWithDefaults

`func NewUpdateAnnotationRequestWithDefaults() *UpdateAnnotationRequest`

NewUpdateAnnotationRequestWithDefaults instantiates a new UpdateAnnotationRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProjectId

`func (o *UpdateAnnotationRequest) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *UpdateAnnotationRequest) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *UpdateAnnotationRequest) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.


### GetTitle

`func (o *UpdateAnnotationRequest) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *UpdateAnnotationRequest) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *UpdateAnnotationRequest) SetTitle(v string)`

SetTitle sets Title field to given value.

### HasTitle

`func (o *UpdateAnnotationRequest) HasTitle() bool`

HasTitle returns a boolean if a field has been set.

### GetDescription

`func (o *UpdateAnnotationRequest) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *UpdateAnnotationRequest) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *UpdateAnnotationRequest) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *UpdateAnnotationRequest) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetAnnotationDate

`func (o *UpdateAnnotationRequest) GetAnnotationDate() string`

GetAnnotationDate returns the AnnotationDate field if non-nil, zero value otherwise.

### GetAnnotationDateOk

`func (o *UpdateAnnotationRequest) GetAnnotationDateOk() (*string, bool)`

GetAnnotationDateOk returns a tuple with the AnnotationDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAnnotationDate

`func (o *UpdateAnnotationRequest) SetAnnotationDate(v string)`

SetAnnotationDate sets AnnotationDate field to given value.

### HasAnnotationDate

`func (o *UpdateAnnotationRequest) HasAnnotationDate() bool`

HasAnnotationDate returns a boolean if a field has been set.

### GetColor

`func (o *UpdateAnnotationRequest) GetColor() string`

GetColor returns the Color field if non-nil, zero value otherwise.

### GetColorOk

`func (o *UpdateAnnotationRequest) GetColorOk() (*string, bool)`

GetColorOk returns a tuple with the Color field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetColor

`func (o *UpdateAnnotationRequest) SetColor(v string)`

SetColor sets Color field to given value.

### HasColor

`func (o *UpdateAnnotationRequest) HasColor() bool`

HasColor returns a boolean if a field has been set.

### GetAnnotationCategoryId

`func (o *UpdateAnnotationRequest) GetAnnotationCategoryId() int32`

GetAnnotationCategoryId returns the AnnotationCategoryId field if non-nil, zero value otherwise.

### GetAnnotationCategoryIdOk

`func (o *UpdateAnnotationRequest) GetAnnotationCategoryIdOk() (*int32, bool)`

GetAnnotationCategoryIdOk returns a tuple with the AnnotationCategoryId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAnnotationCategoryId

`func (o *UpdateAnnotationRequest) SetAnnotationCategoryId(v int32)`

SetAnnotationCategoryId sets AnnotationCategoryId field to given value.

### HasAnnotationCategoryId

`func (o *UpdateAnnotationRequest) HasAnnotationCategoryId() bool`

HasAnnotationCategoryId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


