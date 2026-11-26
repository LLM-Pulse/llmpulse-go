# AnnotationRecord

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **int32** |  | 
**Title** | **string** |  | 
**Description** | **NullableString** |  | 
**AnnotationDate** | **string** |  | 
**Color** | **NullableString** |  | 
**Category** | **string** | user (written by a person) or system (added by the platform) | 
**Origin** | **string** | manual, platform (a platform-wide event) or automation (a project change recorded automatically) | 
**AnnotationCategory** | [**NullableAnnotationRecordAnnotationCategory**](AnnotationRecordAnnotationCategory.md) |  | 
**Editable** | **bool** | Whether the requesting user may update or delete it | 
**CreatedAt** | **time.Time** |  | 

## Methods

### NewAnnotationRecord

`func NewAnnotationRecord(id int32, title string, description NullableString, annotationDate string, color NullableString, category string, origin string, annotationCategory NullableAnnotationRecordAnnotationCategory, editable bool, createdAt time.Time, ) *AnnotationRecord`

NewAnnotationRecord instantiates a new AnnotationRecord object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAnnotationRecordWithDefaults

`func NewAnnotationRecordWithDefaults() *AnnotationRecord`

NewAnnotationRecordWithDefaults instantiates a new AnnotationRecord object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *AnnotationRecord) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *AnnotationRecord) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *AnnotationRecord) SetId(v int32)`

SetId sets Id field to given value.


### GetTitle

`func (o *AnnotationRecord) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *AnnotationRecord) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *AnnotationRecord) SetTitle(v string)`

SetTitle sets Title field to given value.


### GetDescription

`func (o *AnnotationRecord) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *AnnotationRecord) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *AnnotationRecord) SetDescription(v string)`

SetDescription sets Description field to given value.


### SetDescriptionNil

`func (o *AnnotationRecord) SetDescriptionNil(b bool)`

 SetDescriptionNil sets the value for Description to be an explicit nil

### UnsetDescription
`func (o *AnnotationRecord) UnsetDescription()`

UnsetDescription ensures that no value is present for Description, not even an explicit nil
### GetAnnotationDate

`func (o *AnnotationRecord) GetAnnotationDate() string`

GetAnnotationDate returns the AnnotationDate field if non-nil, zero value otherwise.

### GetAnnotationDateOk

`func (o *AnnotationRecord) GetAnnotationDateOk() (*string, bool)`

GetAnnotationDateOk returns a tuple with the AnnotationDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAnnotationDate

`func (o *AnnotationRecord) SetAnnotationDate(v string)`

SetAnnotationDate sets AnnotationDate field to given value.


### GetColor

`func (o *AnnotationRecord) GetColor() string`

GetColor returns the Color field if non-nil, zero value otherwise.

### GetColorOk

`func (o *AnnotationRecord) GetColorOk() (*string, bool)`

GetColorOk returns a tuple with the Color field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetColor

`func (o *AnnotationRecord) SetColor(v string)`

SetColor sets Color field to given value.


### SetColorNil

`func (o *AnnotationRecord) SetColorNil(b bool)`

 SetColorNil sets the value for Color to be an explicit nil

### UnsetColor
`func (o *AnnotationRecord) UnsetColor()`

UnsetColor ensures that no value is present for Color, not even an explicit nil
### GetCategory

`func (o *AnnotationRecord) GetCategory() string`

GetCategory returns the Category field if non-nil, zero value otherwise.

### GetCategoryOk

`func (o *AnnotationRecord) GetCategoryOk() (*string, bool)`

GetCategoryOk returns a tuple with the Category field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCategory

`func (o *AnnotationRecord) SetCategory(v string)`

SetCategory sets Category field to given value.


### GetOrigin

`func (o *AnnotationRecord) GetOrigin() string`

GetOrigin returns the Origin field if non-nil, zero value otherwise.

### GetOriginOk

`func (o *AnnotationRecord) GetOriginOk() (*string, bool)`

GetOriginOk returns a tuple with the Origin field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrigin

`func (o *AnnotationRecord) SetOrigin(v string)`

SetOrigin sets Origin field to given value.


### GetAnnotationCategory

`func (o *AnnotationRecord) GetAnnotationCategory() AnnotationRecordAnnotationCategory`

GetAnnotationCategory returns the AnnotationCategory field if non-nil, zero value otherwise.

### GetAnnotationCategoryOk

`func (o *AnnotationRecord) GetAnnotationCategoryOk() (*AnnotationRecordAnnotationCategory, bool)`

GetAnnotationCategoryOk returns a tuple with the AnnotationCategory field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAnnotationCategory

`func (o *AnnotationRecord) SetAnnotationCategory(v AnnotationRecordAnnotationCategory)`

SetAnnotationCategory sets AnnotationCategory field to given value.


### SetAnnotationCategoryNil

`func (o *AnnotationRecord) SetAnnotationCategoryNil(b bool)`

 SetAnnotationCategoryNil sets the value for AnnotationCategory to be an explicit nil

### UnsetAnnotationCategory
`func (o *AnnotationRecord) UnsetAnnotationCategory()`

UnsetAnnotationCategory ensures that no value is present for AnnotationCategory, not even an explicit nil
### GetEditable

`func (o *AnnotationRecord) GetEditable() bool`

GetEditable returns the Editable field if non-nil, zero value otherwise.

### GetEditableOk

`func (o *AnnotationRecord) GetEditableOk() (*bool, bool)`

GetEditableOk returns a tuple with the Editable field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEditable

`func (o *AnnotationRecord) SetEditable(v bool)`

SetEditable sets Editable field to given value.


### GetCreatedAt

`func (o *AnnotationRecord) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *AnnotationRecord) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *AnnotationRecord) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


