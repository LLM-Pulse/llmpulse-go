# Competitor

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **int32** |  | [optional] 
**Name** | Pointer to **string** |  | [optional] 
**Domain** | Pointer to **string** |  | [optional] 
**ActorType** | Pointer to **string** | Only present when include_project_brand&#x3D;true | [optional] 
**IsOwn** | Pointer to **bool** | Only present when include_project_brand&#x3D;true | [optional] 

## Methods

### NewCompetitor

`func NewCompetitor() *Competitor`

NewCompetitor instantiates a new Competitor object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCompetitorWithDefaults

`func NewCompetitorWithDefaults() *Competitor`

NewCompetitorWithDefaults instantiates a new Competitor object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *Competitor) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *Competitor) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *Competitor) SetId(v int32)`

SetId sets Id field to given value.

### HasId

`func (o *Competitor) HasId() bool`

HasId returns a boolean if a field has been set.

### GetName

`func (o *Competitor) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *Competitor) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *Competitor) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *Competitor) HasName() bool`

HasName returns a boolean if a field has been set.

### GetDomain

`func (o *Competitor) GetDomain() string`

GetDomain returns the Domain field if non-nil, zero value otherwise.

### GetDomainOk

`func (o *Competitor) GetDomainOk() (*string, bool)`

GetDomainOk returns a tuple with the Domain field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDomain

`func (o *Competitor) SetDomain(v string)`

SetDomain sets Domain field to given value.

### HasDomain

`func (o *Competitor) HasDomain() bool`

HasDomain returns a boolean if a field has been set.

### GetActorType

`func (o *Competitor) GetActorType() string`

GetActorType returns the ActorType field if non-nil, zero value otherwise.

### GetActorTypeOk

`func (o *Competitor) GetActorTypeOk() (*string, bool)`

GetActorTypeOk returns a tuple with the ActorType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActorType

`func (o *Competitor) SetActorType(v string)`

SetActorType sets ActorType field to given value.

### HasActorType

`func (o *Competitor) HasActorType() bool`

HasActorType returns a boolean if a field has been set.

### GetIsOwn

`func (o *Competitor) GetIsOwn() bool`

GetIsOwn returns the IsOwn field if non-nil, zero value otherwise.

### GetIsOwnOk

`func (o *Competitor) GetIsOwnOk() (*bool, bool)`

GetIsOwnOk returns a tuple with the IsOwn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsOwn

`func (o *Competitor) SetIsOwn(v bool)`

SetIsOwn sets IsOwn field to given value.

### HasIsOwn

`func (o *Competitor) HasIsOwn() bool`

HasIsOwn returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


