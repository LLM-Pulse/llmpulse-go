# CreateAnnotationRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ProjectId** | **int32** |  | 
**Title** | **string** |  | 
**AnnotationDate** | Pointer to **string** | ISO YYYY-MM-DD; defaults to today | [optional] 
**Description** | Pointer to **string** |  | [optional] 
**Color** | Pointer to **string** | Hex color, e.g. #2563eb | [optional] 
**AnnotationCategoryId** | Pointer to **int32** |  | [optional] 

## Methods

### NewCreateAnnotationRequest

`func NewCreateAnnotationRequest(projectId int32, title string, ) *CreateAnnotationRequest`

NewCreateAnnotationRequest instantiates a new CreateAnnotationRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateAnnotationRequestWithDefaults

`func NewCreateAnnotationRequestWithDefaults() *CreateAnnotationRequest`

NewCreateAnnotationRequestWithDefaults instantiates a new CreateAnnotationRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProjectId

`func (o *CreateAnnotationRequest) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *CreateAnnotationRequest) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *CreateAnnotationRequest) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.


### GetTitle

`func (o *CreateAnnotationRequest) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *CreateAnnotationRequest) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *CreateAnnotationRequest) SetTitle(v string)`

SetTitle sets Title field to given value.


### GetAnnotationDate

`func (o *CreateAnnotationRequest) GetAnnotationDate() string`

GetAnnotationDate returns the AnnotationDate field if non-nil, zero value otherwise.

### GetAnnotationDateOk

`func (o *CreateAnnotationRequest) GetAnnotationDateOk() (*string, bool)`

GetAnnotationDateOk returns a tuple with the AnnotationDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAnnotationDate

`func (o *CreateAnnotationRequest) SetAnnotationDate(v string)`

SetAnnotationDate sets AnnotationDate field to given value.

### HasAnnotationDate

`func (o *CreateAnnotationRequest) HasAnnotationDate() bool`

HasAnnotationDate returns a boolean if a field has been set.

### GetDescription

`func (o *CreateAnnotationRequest) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *CreateAnnotationRequest) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *CreateAnnotationRequest) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *CreateAnnotationRequest) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetColor

`func (o *CreateAnnotationRequest) GetColor() string`

GetColor returns the Color field if non-nil, zero value otherwise.

### GetColorOk

`func (o *CreateAnnotationRequest) GetColorOk() (*string, bool)`

GetColorOk returns a tuple with the Color field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetColor

`func (o *CreateAnnotationRequest) SetColor(v string)`

SetColor sets Color field to given value.

### HasColor

`func (o *CreateAnnotationRequest) HasColor() bool`

HasColor returns a boolean if a field has been set.

### GetAnnotationCategoryId

`func (o *CreateAnnotationRequest) GetAnnotationCategoryId() int32`

GetAnnotationCategoryId returns the AnnotationCategoryId field if non-nil, zero value otherwise.

### GetAnnotationCategoryIdOk

`func (o *CreateAnnotationRequest) GetAnnotationCategoryIdOk() (*int32, bool)`

GetAnnotationCategoryIdOk returns a tuple with the AnnotationCategoryId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAnnotationCategoryId

`func (o *CreateAnnotationRequest) SetAnnotationCategoryId(v int32)`

SetAnnotationCategoryId sets AnnotationCategoryId field to given value.

### HasAnnotationCategoryId

`func (o *CreateAnnotationRequest) HasAnnotationCategoryId() bool`

HasAnnotationCategoryId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


