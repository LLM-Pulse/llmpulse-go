# AnnotationCreateResponseAnnotation

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **int32** |  | 
**Title** | **string** |  | 
**AnnotationDate** | **string** |  | 
**Description** | **NullableString** |  | 
**Color** | **NullableString** | Hex color such as &#39;#4F46E5&#39; | 
**AnnotationCategoryId** | **NullableInt32** |  | 

## Methods

### NewAnnotationCreateResponseAnnotation

`func NewAnnotationCreateResponseAnnotation(id int32, title string, annotationDate string, description NullableString, color NullableString, annotationCategoryId NullableInt32, ) *AnnotationCreateResponseAnnotation`

NewAnnotationCreateResponseAnnotation instantiates a new AnnotationCreateResponseAnnotation object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAnnotationCreateResponseAnnotationWithDefaults

`func NewAnnotationCreateResponseAnnotationWithDefaults() *AnnotationCreateResponseAnnotation`

NewAnnotationCreateResponseAnnotationWithDefaults instantiates a new AnnotationCreateResponseAnnotation object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *AnnotationCreateResponseAnnotation) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *AnnotationCreateResponseAnnotation) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *AnnotationCreateResponseAnnotation) SetId(v int32)`

SetId sets Id field to given value.


### GetTitle

`func (o *AnnotationCreateResponseAnnotation) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *AnnotationCreateResponseAnnotation) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *AnnotationCreateResponseAnnotation) SetTitle(v string)`

SetTitle sets Title field to given value.


### GetAnnotationDate

`func (o *AnnotationCreateResponseAnnotation) GetAnnotationDate() string`

GetAnnotationDate returns the AnnotationDate field if non-nil, zero value otherwise.

### GetAnnotationDateOk

`func (o *AnnotationCreateResponseAnnotation) GetAnnotationDateOk() (*string, bool)`

GetAnnotationDateOk returns a tuple with the AnnotationDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAnnotationDate

`func (o *AnnotationCreateResponseAnnotation) SetAnnotationDate(v string)`

SetAnnotationDate sets AnnotationDate field to given value.


### GetDescription

`func (o *AnnotationCreateResponseAnnotation) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *AnnotationCreateResponseAnnotation) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *AnnotationCreateResponseAnnotation) SetDescription(v string)`

SetDescription sets Description field to given value.


### SetDescriptionNil

`func (o *AnnotationCreateResponseAnnotation) SetDescriptionNil(b bool)`

 SetDescriptionNil sets the value for Description to be an explicit nil

### UnsetDescription
`func (o *AnnotationCreateResponseAnnotation) UnsetDescription()`

UnsetDescription ensures that no value is present for Description, not even an explicit nil
### GetColor

`func (o *AnnotationCreateResponseAnnotation) GetColor() string`

GetColor returns the Color field if non-nil, zero value otherwise.

### GetColorOk

`func (o *AnnotationCreateResponseAnnotation) GetColorOk() (*string, bool)`

GetColorOk returns a tuple with the Color field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetColor

`func (o *AnnotationCreateResponseAnnotation) SetColor(v string)`

SetColor sets Color field to given value.


### SetColorNil

`func (o *AnnotationCreateResponseAnnotation) SetColorNil(b bool)`

 SetColorNil sets the value for Color to be an explicit nil

### UnsetColor
`func (o *AnnotationCreateResponseAnnotation) UnsetColor()`

UnsetColor ensures that no value is present for Color, not even an explicit nil
### GetAnnotationCategoryId

`func (o *AnnotationCreateResponseAnnotation) GetAnnotationCategoryId() int32`

GetAnnotationCategoryId returns the AnnotationCategoryId field if non-nil, zero value otherwise.

### GetAnnotationCategoryIdOk

`func (o *AnnotationCreateResponseAnnotation) GetAnnotationCategoryIdOk() (*int32, bool)`

GetAnnotationCategoryIdOk returns a tuple with the AnnotationCategoryId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAnnotationCategoryId

`func (o *AnnotationCreateResponseAnnotation) SetAnnotationCategoryId(v int32)`

SetAnnotationCategoryId sets AnnotationCategoryId field to given value.


### SetAnnotationCategoryIdNil

`func (o *AnnotationCreateResponseAnnotation) SetAnnotationCategoryIdNil(b bool)`

 SetAnnotationCategoryIdNil sets the value for AnnotationCategoryId to be an explicit nil

### UnsetAnnotationCategoryId
`func (o *AnnotationCreateResponseAnnotation) UnsetAnnotationCategoryId()`

UnsetAnnotationCategoryId ensures that no value is present for AnnotationCategoryId, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


