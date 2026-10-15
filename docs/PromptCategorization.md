# PromptCategorization

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **int32** |  | 
**RawInput** | **string** |  | 
**PromptType** | Pointer to **NullableString** |  | [optional] 
**BrandKind** | Pointer to **NullableString** |  | [optional] 
**CategorizationSource** | Pointer to **NullableString** | manual after an edit by hand; the prompt page&#39;s revert hands it back to automatic categorization | [optional] 
**ManuallyCategorized** | **bool** |  | 
**CategorizedAt** | Pointer to **NullableTime** |  | [optional] 

## Methods

### NewPromptCategorization

`func NewPromptCategorization(id int32, rawInput string, manuallyCategorized bool, ) *PromptCategorization`

NewPromptCategorization instantiates a new PromptCategorization object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPromptCategorizationWithDefaults

`func NewPromptCategorizationWithDefaults() *PromptCategorization`

NewPromptCategorizationWithDefaults instantiates a new PromptCategorization object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *PromptCategorization) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *PromptCategorization) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *PromptCategorization) SetId(v int32)`

SetId sets Id field to given value.


### GetRawInput

`func (o *PromptCategorization) GetRawInput() string`

GetRawInput returns the RawInput field if non-nil, zero value otherwise.

### GetRawInputOk

`func (o *PromptCategorization) GetRawInputOk() (*string, bool)`

GetRawInputOk returns a tuple with the RawInput field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRawInput

`func (o *PromptCategorization) SetRawInput(v string)`

SetRawInput sets RawInput field to given value.


### GetPromptType

`func (o *PromptCategorization) GetPromptType() string`

GetPromptType returns the PromptType field if non-nil, zero value otherwise.

### GetPromptTypeOk

`func (o *PromptCategorization) GetPromptTypeOk() (*string, bool)`

GetPromptTypeOk returns a tuple with the PromptType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPromptType

`func (o *PromptCategorization) SetPromptType(v string)`

SetPromptType sets PromptType field to given value.

### HasPromptType

`func (o *PromptCategorization) HasPromptType() bool`

HasPromptType returns a boolean if a field has been set.

### SetPromptTypeNil

`func (o *PromptCategorization) SetPromptTypeNil(b bool)`

 SetPromptTypeNil sets the value for PromptType to be an explicit nil

### UnsetPromptType
`func (o *PromptCategorization) UnsetPromptType()`

UnsetPromptType ensures that no value is present for PromptType, not even an explicit nil
### GetBrandKind

`func (o *PromptCategorization) GetBrandKind() string`

GetBrandKind returns the BrandKind field if non-nil, zero value otherwise.

### GetBrandKindOk

`func (o *PromptCategorization) GetBrandKindOk() (*string, bool)`

GetBrandKindOk returns a tuple with the BrandKind field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBrandKind

`func (o *PromptCategorization) SetBrandKind(v string)`

SetBrandKind sets BrandKind field to given value.

### HasBrandKind

`func (o *PromptCategorization) HasBrandKind() bool`

HasBrandKind returns a boolean if a field has been set.

### SetBrandKindNil

`func (o *PromptCategorization) SetBrandKindNil(b bool)`

 SetBrandKindNil sets the value for BrandKind to be an explicit nil

### UnsetBrandKind
`func (o *PromptCategorization) UnsetBrandKind()`

UnsetBrandKind ensures that no value is present for BrandKind, not even an explicit nil
### GetCategorizationSource

`func (o *PromptCategorization) GetCategorizationSource() string`

GetCategorizationSource returns the CategorizationSource field if non-nil, zero value otherwise.

### GetCategorizationSourceOk

`func (o *PromptCategorization) GetCategorizationSourceOk() (*string, bool)`

GetCategorizationSourceOk returns a tuple with the CategorizationSource field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCategorizationSource

`func (o *PromptCategorization) SetCategorizationSource(v string)`

SetCategorizationSource sets CategorizationSource field to given value.

### HasCategorizationSource

`func (o *PromptCategorization) HasCategorizationSource() bool`

HasCategorizationSource returns a boolean if a field has been set.

### SetCategorizationSourceNil

`func (o *PromptCategorization) SetCategorizationSourceNil(b bool)`

 SetCategorizationSourceNil sets the value for CategorizationSource to be an explicit nil

### UnsetCategorizationSource
`func (o *PromptCategorization) UnsetCategorizationSource()`

UnsetCategorizationSource ensures that no value is present for CategorizationSource, not even an explicit nil
### GetManuallyCategorized

`func (o *PromptCategorization) GetManuallyCategorized() bool`

GetManuallyCategorized returns the ManuallyCategorized field if non-nil, zero value otherwise.

### GetManuallyCategorizedOk

`func (o *PromptCategorization) GetManuallyCategorizedOk() (*bool, bool)`

GetManuallyCategorizedOk returns a tuple with the ManuallyCategorized field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetManuallyCategorized

`func (o *PromptCategorization) SetManuallyCategorized(v bool)`

SetManuallyCategorized sets ManuallyCategorized field to given value.


### GetCategorizedAt

`func (o *PromptCategorization) GetCategorizedAt() time.Time`

GetCategorizedAt returns the CategorizedAt field if non-nil, zero value otherwise.

### GetCategorizedAtOk

`func (o *PromptCategorization) GetCategorizedAtOk() (*time.Time, bool)`

GetCategorizedAtOk returns a tuple with the CategorizedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCategorizedAt

`func (o *PromptCategorization) SetCategorizedAt(v time.Time)`

SetCategorizedAt sets CategorizedAt field to given value.

### HasCategorizedAt

`func (o *PromptCategorization) HasCategorizedAt() bool`

HasCategorizedAt returns a boolean if a field has been set.

### SetCategorizedAtNil

`func (o *PromptCategorization) SetCategorizedAtNil(b bool)`

 SetCategorizedAtNil sets the value for CategorizedAt to be an explicit nil

### UnsetCategorizedAt
`func (o *PromptCategorization) UnsetCategorizedAt()`

UnsetCategorizedAt ensures that no value is present for CategorizedAt, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


