# AiModelWeightedVisibilityMatrixActor

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Type** | Pointer to **string** |  | [optional] 
**Id** | Pointer to **int32** | Project id, or competitor id | [optional] 
**CompetitorId** | Pointer to **NullableInt32** | Null for the project, the competitor id otherwise | [optional] 
**Name** | Pointer to **string** |  | [optional] 
**Domain** | Pointer to **NullableString** | Bare (scheme-less) domain. Null for the project actor when the project has no URL. | [optional] 
**TotalWeightedVisibilityScore** | Pointer to **float32** | The actor&#39;s AI Visibility Score points summed over the models | [optional] 
**Models** | Pointer to [**map[string]AiModelWeightedVisibilityCell**](AiModelWeightedVisibilityCell.md) | One cell per model, keyed by model | [optional] 

## Methods

### NewAiModelWeightedVisibilityMatrixActor

`func NewAiModelWeightedVisibilityMatrixActor() *AiModelWeightedVisibilityMatrixActor`

NewAiModelWeightedVisibilityMatrixActor instantiates a new AiModelWeightedVisibilityMatrixActor object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAiModelWeightedVisibilityMatrixActorWithDefaults

`func NewAiModelWeightedVisibilityMatrixActorWithDefaults() *AiModelWeightedVisibilityMatrixActor`

NewAiModelWeightedVisibilityMatrixActorWithDefaults instantiates a new AiModelWeightedVisibilityMatrixActor object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetType

`func (o *AiModelWeightedVisibilityMatrixActor) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *AiModelWeightedVisibilityMatrixActor) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *AiModelWeightedVisibilityMatrixActor) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *AiModelWeightedVisibilityMatrixActor) HasType() bool`

HasType returns a boolean if a field has been set.

### GetId

`func (o *AiModelWeightedVisibilityMatrixActor) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *AiModelWeightedVisibilityMatrixActor) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *AiModelWeightedVisibilityMatrixActor) SetId(v int32)`

SetId sets Id field to given value.

### HasId

`func (o *AiModelWeightedVisibilityMatrixActor) HasId() bool`

HasId returns a boolean if a field has been set.

### GetCompetitorId

`func (o *AiModelWeightedVisibilityMatrixActor) GetCompetitorId() int32`

GetCompetitorId returns the CompetitorId field if non-nil, zero value otherwise.

### GetCompetitorIdOk

`func (o *AiModelWeightedVisibilityMatrixActor) GetCompetitorIdOk() (*int32, bool)`

GetCompetitorIdOk returns a tuple with the CompetitorId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompetitorId

`func (o *AiModelWeightedVisibilityMatrixActor) SetCompetitorId(v int32)`

SetCompetitorId sets CompetitorId field to given value.

### HasCompetitorId

`func (o *AiModelWeightedVisibilityMatrixActor) HasCompetitorId() bool`

HasCompetitorId returns a boolean if a field has been set.

### SetCompetitorIdNil

`func (o *AiModelWeightedVisibilityMatrixActor) SetCompetitorIdNil(b bool)`

 SetCompetitorIdNil sets the value for CompetitorId to be an explicit nil

### UnsetCompetitorId
`func (o *AiModelWeightedVisibilityMatrixActor) UnsetCompetitorId()`

UnsetCompetitorId ensures that no value is present for CompetitorId, not even an explicit nil
### GetName

`func (o *AiModelWeightedVisibilityMatrixActor) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *AiModelWeightedVisibilityMatrixActor) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *AiModelWeightedVisibilityMatrixActor) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *AiModelWeightedVisibilityMatrixActor) HasName() bool`

HasName returns a boolean if a field has been set.

### GetDomain

`func (o *AiModelWeightedVisibilityMatrixActor) GetDomain() string`

GetDomain returns the Domain field if non-nil, zero value otherwise.

### GetDomainOk

`func (o *AiModelWeightedVisibilityMatrixActor) GetDomainOk() (*string, bool)`

GetDomainOk returns a tuple with the Domain field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDomain

`func (o *AiModelWeightedVisibilityMatrixActor) SetDomain(v string)`

SetDomain sets Domain field to given value.

### HasDomain

`func (o *AiModelWeightedVisibilityMatrixActor) HasDomain() bool`

HasDomain returns a boolean if a field has been set.

### SetDomainNil

`func (o *AiModelWeightedVisibilityMatrixActor) SetDomainNil(b bool)`

 SetDomainNil sets the value for Domain to be an explicit nil

### UnsetDomain
`func (o *AiModelWeightedVisibilityMatrixActor) UnsetDomain()`

UnsetDomain ensures that no value is present for Domain, not even an explicit nil
### GetTotalWeightedVisibilityScore

`func (o *AiModelWeightedVisibilityMatrixActor) GetTotalWeightedVisibilityScore() float32`

GetTotalWeightedVisibilityScore returns the TotalWeightedVisibilityScore field if non-nil, zero value otherwise.

### GetTotalWeightedVisibilityScoreOk

`func (o *AiModelWeightedVisibilityMatrixActor) GetTotalWeightedVisibilityScoreOk() (*float32, bool)`

GetTotalWeightedVisibilityScoreOk returns a tuple with the TotalWeightedVisibilityScore field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalWeightedVisibilityScore

`func (o *AiModelWeightedVisibilityMatrixActor) SetTotalWeightedVisibilityScore(v float32)`

SetTotalWeightedVisibilityScore sets TotalWeightedVisibilityScore field to given value.

### HasTotalWeightedVisibilityScore

`func (o *AiModelWeightedVisibilityMatrixActor) HasTotalWeightedVisibilityScore() bool`

HasTotalWeightedVisibilityScore returns a boolean if a field has been set.

### GetModels

`func (o *AiModelWeightedVisibilityMatrixActor) GetModels() map[string]AiModelWeightedVisibilityCell`

GetModels returns the Models field if non-nil, zero value otherwise.

### GetModelsOk

`func (o *AiModelWeightedVisibilityMatrixActor) GetModelsOk() (*map[string]AiModelWeightedVisibilityCell, bool)`

GetModelsOk returns a tuple with the Models field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModels

`func (o *AiModelWeightedVisibilityMatrixActor) SetModels(v map[string]AiModelWeightedVisibilityCell)`

SetModels sets Models field to given value.

### HasModels

`func (o *AiModelWeightedVisibilityMatrixActor) HasModels() bool`

HasModels returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


