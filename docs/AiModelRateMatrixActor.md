# AiModelRateMatrixActor

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Type** | Pointer to **string** |  | [optional] 
**Id** | Pointer to **int32** | Project id, or competitor id | [optional] 
**CompetitorId** | Pointer to **NullableInt32** | Null for the project, the competitor id otherwise | [optional] 
**Name** | Pointer to **string** |  | [optional] 
**Domain** | Pointer to **NullableString** | Bare (scheme-less) domain. Null for the project actor when the project has no URL. | [optional] 
**Total** | Pointer to **int32** | The actor&#39;s numerators summed over the models | [optional] 
**Models** | Pointer to [**map[string]AiModelRateCell**](AiModelRateCell.md) | One cell per model, keyed by model | [optional] 

## Methods

### NewAiModelRateMatrixActor

`func NewAiModelRateMatrixActor() *AiModelRateMatrixActor`

NewAiModelRateMatrixActor instantiates a new AiModelRateMatrixActor object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAiModelRateMatrixActorWithDefaults

`func NewAiModelRateMatrixActorWithDefaults() *AiModelRateMatrixActor`

NewAiModelRateMatrixActorWithDefaults instantiates a new AiModelRateMatrixActor object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetType

`func (o *AiModelRateMatrixActor) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *AiModelRateMatrixActor) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *AiModelRateMatrixActor) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *AiModelRateMatrixActor) HasType() bool`

HasType returns a boolean if a field has been set.

### GetId

`func (o *AiModelRateMatrixActor) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *AiModelRateMatrixActor) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *AiModelRateMatrixActor) SetId(v int32)`

SetId sets Id field to given value.

### HasId

`func (o *AiModelRateMatrixActor) HasId() bool`

HasId returns a boolean if a field has been set.

### GetCompetitorId

`func (o *AiModelRateMatrixActor) GetCompetitorId() int32`

GetCompetitorId returns the CompetitorId field if non-nil, zero value otherwise.

### GetCompetitorIdOk

`func (o *AiModelRateMatrixActor) GetCompetitorIdOk() (*int32, bool)`

GetCompetitorIdOk returns a tuple with the CompetitorId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompetitorId

`func (o *AiModelRateMatrixActor) SetCompetitorId(v int32)`

SetCompetitorId sets CompetitorId field to given value.

### HasCompetitorId

`func (o *AiModelRateMatrixActor) HasCompetitorId() bool`

HasCompetitorId returns a boolean if a field has been set.

### SetCompetitorIdNil

`func (o *AiModelRateMatrixActor) SetCompetitorIdNil(b bool)`

 SetCompetitorIdNil sets the value for CompetitorId to be an explicit nil

### UnsetCompetitorId
`func (o *AiModelRateMatrixActor) UnsetCompetitorId()`

UnsetCompetitorId ensures that no value is present for CompetitorId, not even an explicit nil
### GetName

`func (o *AiModelRateMatrixActor) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *AiModelRateMatrixActor) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *AiModelRateMatrixActor) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *AiModelRateMatrixActor) HasName() bool`

HasName returns a boolean if a field has been set.

### GetDomain

`func (o *AiModelRateMatrixActor) GetDomain() string`

GetDomain returns the Domain field if non-nil, zero value otherwise.

### GetDomainOk

`func (o *AiModelRateMatrixActor) GetDomainOk() (*string, bool)`

GetDomainOk returns a tuple with the Domain field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDomain

`func (o *AiModelRateMatrixActor) SetDomain(v string)`

SetDomain sets Domain field to given value.

### HasDomain

`func (o *AiModelRateMatrixActor) HasDomain() bool`

HasDomain returns a boolean if a field has been set.

### SetDomainNil

`func (o *AiModelRateMatrixActor) SetDomainNil(b bool)`

 SetDomainNil sets the value for Domain to be an explicit nil

### UnsetDomain
`func (o *AiModelRateMatrixActor) UnsetDomain()`

UnsetDomain ensures that no value is present for Domain, not even an explicit nil
### GetTotal

`func (o *AiModelRateMatrixActor) GetTotal() int32`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *AiModelRateMatrixActor) GetTotalOk() (*int32, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *AiModelRateMatrixActor) SetTotal(v int32)`

SetTotal sets Total field to given value.

### HasTotal

`func (o *AiModelRateMatrixActor) HasTotal() bool`

HasTotal returns a boolean if a field has been set.

### GetModels

`func (o *AiModelRateMatrixActor) GetModels() map[string]AiModelRateCell`

GetModels returns the Models field if non-nil, zero value otherwise.

### GetModelsOk

`func (o *AiModelRateMatrixActor) GetModelsOk() (*map[string]AiModelRateCell, bool)`

GetModelsOk returns a tuple with the Models field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModels

`func (o *AiModelRateMatrixActor) SetModels(v map[string]AiModelRateCell)`

SetModels sets Models field to given value.

### HasModels

`func (o *AiModelRateMatrixActor) HasModels() bool`

HasModels returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


