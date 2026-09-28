# Actor

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Type** | Pointer to **string** |  | [optional] 
**Id** | Pointer to **int32** |  | [optional] 
**CompetitorId** | Pointer to **NullableInt32** |  | [optional] 
**Name** | Pointer to **string** |  | [optional] 
**Domain** | Pointer to **NullableString** | Bare (scheme-less) domain. Null for the project actor when the project has no URL. | [optional] 

## Methods

### NewActor

`func NewActor() *Actor`

NewActor instantiates a new Actor object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewActorWithDefaults

`func NewActorWithDefaults() *Actor`

NewActorWithDefaults instantiates a new Actor object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetType

`func (o *Actor) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *Actor) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *Actor) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *Actor) HasType() bool`

HasType returns a boolean if a field has been set.

### GetId

`func (o *Actor) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *Actor) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *Actor) SetId(v int32)`

SetId sets Id field to given value.

### HasId

`func (o *Actor) HasId() bool`

HasId returns a boolean if a field has been set.

### GetCompetitorId

`func (o *Actor) GetCompetitorId() int32`

GetCompetitorId returns the CompetitorId field if non-nil, zero value otherwise.

### GetCompetitorIdOk

`func (o *Actor) GetCompetitorIdOk() (*int32, bool)`

GetCompetitorIdOk returns a tuple with the CompetitorId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompetitorId

`func (o *Actor) SetCompetitorId(v int32)`

SetCompetitorId sets CompetitorId field to given value.

### HasCompetitorId

`func (o *Actor) HasCompetitorId() bool`

HasCompetitorId returns a boolean if a field has been set.

### SetCompetitorIdNil

`func (o *Actor) SetCompetitorIdNil(b bool)`

 SetCompetitorIdNil sets the value for CompetitorId to be an explicit nil

### UnsetCompetitorId
`func (o *Actor) UnsetCompetitorId()`

UnsetCompetitorId ensures that no value is present for CompetitorId, not even an explicit nil
### GetName

`func (o *Actor) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *Actor) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *Actor) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *Actor) HasName() bool`

HasName returns a boolean if a field has been set.

### GetDomain

`func (o *Actor) GetDomain() string`

GetDomain returns the Domain field if non-nil, zero value otherwise.

### GetDomainOk

`func (o *Actor) GetDomainOk() (*string, bool)`

GetDomainOk returns a tuple with the Domain field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDomain

`func (o *Actor) SetDomain(v string)`

SetDomain sets Domain field to given value.

### HasDomain

`func (o *Actor) HasDomain() bool`

HasDomain returns a boolean if a field has been set.

### SetDomainNil

`func (o *Actor) SetDomainNil(b bool)`

 SetDomainNil sets the value for Domain to be an explicit nil

### UnsetDomain
`func (o *Actor) UnsetDomain()`

UnsetDomain ensures that no value is present for Domain, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


