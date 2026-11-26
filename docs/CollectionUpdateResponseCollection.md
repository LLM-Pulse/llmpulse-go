# CollectionUpdateResponseCollection

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **int32** |  | 
**Name** | **string** |  | 
**Description** | **NullableString** |  | 
**PromptsCount** | **int32** |  | 

## Methods

### NewCollectionUpdateResponseCollection

`func NewCollectionUpdateResponseCollection(id int32, name string, description NullableString, promptsCount int32, ) *CollectionUpdateResponseCollection`

NewCollectionUpdateResponseCollection instantiates a new CollectionUpdateResponseCollection object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCollectionUpdateResponseCollectionWithDefaults

`func NewCollectionUpdateResponseCollectionWithDefaults() *CollectionUpdateResponseCollection`

NewCollectionUpdateResponseCollectionWithDefaults instantiates a new CollectionUpdateResponseCollection object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *CollectionUpdateResponseCollection) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *CollectionUpdateResponseCollection) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *CollectionUpdateResponseCollection) SetId(v int32)`

SetId sets Id field to given value.


### GetName

`func (o *CollectionUpdateResponseCollection) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *CollectionUpdateResponseCollection) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *CollectionUpdateResponseCollection) SetName(v string)`

SetName sets Name field to given value.


### GetDescription

`func (o *CollectionUpdateResponseCollection) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *CollectionUpdateResponseCollection) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *CollectionUpdateResponseCollection) SetDescription(v string)`

SetDescription sets Description field to given value.


### SetDescriptionNil

`func (o *CollectionUpdateResponseCollection) SetDescriptionNil(b bool)`

 SetDescriptionNil sets the value for Description to be an explicit nil

### UnsetDescription
`func (o *CollectionUpdateResponseCollection) UnsetDescription()`

UnsetDescription ensures that no value is present for Description, not even an explicit nil
### GetPromptsCount

`func (o *CollectionUpdateResponseCollection) GetPromptsCount() int32`

GetPromptsCount returns the PromptsCount field if non-nil, zero value otherwise.

### GetPromptsCountOk

`func (o *CollectionUpdateResponseCollection) GetPromptsCountOk() (*int32, bool)`

GetPromptsCountOk returns a tuple with the PromptsCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPromptsCount

`func (o *CollectionUpdateResponseCollection) SetPromptsCount(v int32)`

SetPromptsCount sets PromptsCount field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


