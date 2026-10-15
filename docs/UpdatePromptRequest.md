# UpdatePromptRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ProjectId** | **int32** |  | 
**PromptType** | Pointer to **string** | Search intent | [optional] 
**BrandKind** | Pointer to **string** | Brand focus: brand (your own brand or products), brand_other (competing brands), non_brand (generic) | [optional] 

## Methods

### NewUpdatePromptRequest

`func NewUpdatePromptRequest(projectId int32, ) *UpdatePromptRequest`

NewUpdatePromptRequest instantiates a new UpdatePromptRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUpdatePromptRequestWithDefaults

`func NewUpdatePromptRequestWithDefaults() *UpdatePromptRequest`

NewUpdatePromptRequestWithDefaults instantiates a new UpdatePromptRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProjectId

`func (o *UpdatePromptRequest) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *UpdatePromptRequest) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *UpdatePromptRequest) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.


### GetPromptType

`func (o *UpdatePromptRequest) GetPromptType() string`

GetPromptType returns the PromptType field if non-nil, zero value otherwise.

### GetPromptTypeOk

`func (o *UpdatePromptRequest) GetPromptTypeOk() (*string, bool)`

GetPromptTypeOk returns a tuple with the PromptType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPromptType

`func (o *UpdatePromptRequest) SetPromptType(v string)`

SetPromptType sets PromptType field to given value.

### HasPromptType

`func (o *UpdatePromptRequest) HasPromptType() bool`

HasPromptType returns a boolean if a field has been set.

### GetBrandKind

`func (o *UpdatePromptRequest) GetBrandKind() string`

GetBrandKind returns the BrandKind field if non-nil, zero value otherwise.

### GetBrandKindOk

`func (o *UpdatePromptRequest) GetBrandKindOk() (*string, bool)`

GetBrandKindOk returns a tuple with the BrandKind field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBrandKind

`func (o *UpdatePromptRequest) SetBrandKind(v string)`

SetBrandKind sets BrandKind field to given value.

### HasBrandKind

`func (o *UpdatePromptRequest) HasBrandKind() bool`

HasBrandKind returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


