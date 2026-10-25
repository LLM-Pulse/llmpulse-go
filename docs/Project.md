# Project

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **int32** |  | [optional] 
**Name** | Pointer to **string** | Internal project label (sidebar, settings, admin) | [optional] 
**BrandName** | Pointer to **NullableString** | LLM-facing brand label (used in prompts and customer-facing charts). Null when not set, in which case prompts and charts use &#x60;name&#x60;. | [optional] 
**Tracked** | Pointer to **bool** | Whether scheduled runs include this project. False when it is paused, or when the plan&#39;s project limit leaves it out (the oldest projects up to the limit run), so its prompts do not run | [optional] 
**UntrackedReason** | Pointer to **NullableString** | Why tracked is false: paused or project_limit. Null when tracked | [optional] 

## Methods

### NewProject

`func NewProject() *Project`

NewProject instantiates a new Project object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProjectWithDefaults

`func NewProjectWithDefaults() *Project`

NewProjectWithDefaults instantiates a new Project object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *Project) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *Project) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *Project) SetId(v int32)`

SetId sets Id field to given value.

### HasId

`func (o *Project) HasId() bool`

HasId returns a boolean if a field has been set.

### GetName

`func (o *Project) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *Project) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *Project) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *Project) HasName() bool`

HasName returns a boolean if a field has been set.

### GetBrandName

`func (o *Project) GetBrandName() string`

GetBrandName returns the BrandName field if non-nil, zero value otherwise.

### GetBrandNameOk

`func (o *Project) GetBrandNameOk() (*string, bool)`

GetBrandNameOk returns a tuple with the BrandName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBrandName

`func (o *Project) SetBrandName(v string)`

SetBrandName sets BrandName field to given value.

### HasBrandName

`func (o *Project) HasBrandName() bool`

HasBrandName returns a boolean if a field has been set.

### SetBrandNameNil

`func (o *Project) SetBrandNameNil(b bool)`

 SetBrandNameNil sets the value for BrandName to be an explicit nil

### UnsetBrandName
`func (o *Project) UnsetBrandName()`

UnsetBrandName ensures that no value is present for BrandName, not even an explicit nil
### GetTracked

`func (o *Project) GetTracked() bool`

GetTracked returns the Tracked field if non-nil, zero value otherwise.

### GetTrackedOk

`func (o *Project) GetTrackedOk() (*bool, bool)`

GetTrackedOk returns a tuple with the Tracked field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTracked

`func (o *Project) SetTracked(v bool)`

SetTracked sets Tracked field to given value.

### HasTracked

`func (o *Project) HasTracked() bool`

HasTracked returns a boolean if a field has been set.

### GetUntrackedReason

`func (o *Project) GetUntrackedReason() string`

GetUntrackedReason returns the UntrackedReason field if non-nil, zero value otherwise.

### GetUntrackedReasonOk

`func (o *Project) GetUntrackedReasonOk() (*string, bool)`

GetUntrackedReasonOk returns a tuple with the UntrackedReason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUntrackedReason

`func (o *Project) SetUntrackedReason(v string)`

SetUntrackedReason sets UntrackedReason field to given value.

### HasUntrackedReason

`func (o *Project) HasUntrackedReason() bool`

HasUntrackedReason returns a boolean if a field has been set.

### SetUntrackedReasonNil

`func (o *Project) SetUntrackedReasonNil(b bool)`

 SetUntrackedReasonNil sets the value for UntrackedReason to be an explicit nil

### UnsetUntrackedReason
`func (o *Project) UnsetUntrackedReason()`

UnsetUntrackedReason ensures that no value is present for UntrackedReason, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


