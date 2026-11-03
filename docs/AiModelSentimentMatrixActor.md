# AiModelSentimentMatrixActor

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Type** | Pointer to **string** |  | [optional] 
**Id** | Pointer to **int32** | Project id, or competitor id | [optional] 
**CompetitorId** | Pointer to **NullableInt32** | Null for the project, the competitor id otherwise | [optional] 
**Name** | Pointer to **string** |  | [optional] 
**Domain** | Pointer to **NullableString** | Bare (scheme-less) domain. Null for the project actor when the project has no URL. | [optional] 
**TotalSentiments** | Pointer to **int32** | The actor&#39;s sentiment verdicts summed over the models | [optional] 
**Models** | Pointer to [**map[string]AiModelSentimentCell**](AiModelSentimentCell.md) | One cell per model, keyed by model | [optional] 

## Methods

### NewAiModelSentimentMatrixActor

`func NewAiModelSentimentMatrixActor() *AiModelSentimentMatrixActor`

NewAiModelSentimentMatrixActor instantiates a new AiModelSentimentMatrixActor object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAiModelSentimentMatrixActorWithDefaults

`func NewAiModelSentimentMatrixActorWithDefaults() *AiModelSentimentMatrixActor`

NewAiModelSentimentMatrixActorWithDefaults instantiates a new AiModelSentimentMatrixActor object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetType

`func (o *AiModelSentimentMatrixActor) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *AiModelSentimentMatrixActor) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *AiModelSentimentMatrixActor) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *AiModelSentimentMatrixActor) HasType() bool`

HasType returns a boolean if a field has been set.

### GetId

`func (o *AiModelSentimentMatrixActor) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *AiModelSentimentMatrixActor) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *AiModelSentimentMatrixActor) SetId(v int32)`

SetId sets Id field to given value.

### HasId

`func (o *AiModelSentimentMatrixActor) HasId() bool`

HasId returns a boolean if a field has been set.

### GetCompetitorId

`func (o *AiModelSentimentMatrixActor) GetCompetitorId() int32`

GetCompetitorId returns the CompetitorId field if non-nil, zero value otherwise.

### GetCompetitorIdOk

`func (o *AiModelSentimentMatrixActor) GetCompetitorIdOk() (*int32, bool)`

GetCompetitorIdOk returns a tuple with the CompetitorId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompetitorId

`func (o *AiModelSentimentMatrixActor) SetCompetitorId(v int32)`

SetCompetitorId sets CompetitorId field to given value.

### HasCompetitorId

`func (o *AiModelSentimentMatrixActor) HasCompetitorId() bool`

HasCompetitorId returns a boolean if a field has been set.

### SetCompetitorIdNil

`func (o *AiModelSentimentMatrixActor) SetCompetitorIdNil(b bool)`

 SetCompetitorIdNil sets the value for CompetitorId to be an explicit nil

### UnsetCompetitorId
`func (o *AiModelSentimentMatrixActor) UnsetCompetitorId()`

UnsetCompetitorId ensures that no value is present for CompetitorId, not even an explicit nil
### GetName

`func (o *AiModelSentimentMatrixActor) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *AiModelSentimentMatrixActor) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *AiModelSentimentMatrixActor) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *AiModelSentimentMatrixActor) HasName() bool`

HasName returns a boolean if a field has been set.

### GetDomain

`func (o *AiModelSentimentMatrixActor) GetDomain() string`

GetDomain returns the Domain field if non-nil, zero value otherwise.

### GetDomainOk

`func (o *AiModelSentimentMatrixActor) GetDomainOk() (*string, bool)`

GetDomainOk returns a tuple with the Domain field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDomain

`func (o *AiModelSentimentMatrixActor) SetDomain(v string)`

SetDomain sets Domain field to given value.

### HasDomain

`func (o *AiModelSentimentMatrixActor) HasDomain() bool`

HasDomain returns a boolean if a field has been set.

### SetDomainNil

`func (o *AiModelSentimentMatrixActor) SetDomainNil(b bool)`

 SetDomainNil sets the value for Domain to be an explicit nil

### UnsetDomain
`func (o *AiModelSentimentMatrixActor) UnsetDomain()`

UnsetDomain ensures that no value is present for Domain, not even an explicit nil
### GetTotalSentiments

`func (o *AiModelSentimentMatrixActor) GetTotalSentiments() int32`

GetTotalSentiments returns the TotalSentiments field if non-nil, zero value otherwise.

### GetTotalSentimentsOk

`func (o *AiModelSentimentMatrixActor) GetTotalSentimentsOk() (*int32, bool)`

GetTotalSentimentsOk returns a tuple with the TotalSentiments field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalSentiments

`func (o *AiModelSentimentMatrixActor) SetTotalSentiments(v int32)`

SetTotalSentiments sets TotalSentiments field to given value.

### HasTotalSentiments

`func (o *AiModelSentimentMatrixActor) HasTotalSentiments() bool`

HasTotalSentiments returns a boolean if a field has been set.

### GetModels

`func (o *AiModelSentimentMatrixActor) GetModels() map[string]AiModelSentimentCell`

GetModels returns the Models field if non-nil, zero value otherwise.

### GetModelsOk

`func (o *AiModelSentimentMatrixActor) GetModelsOk() (*map[string]AiModelSentimentCell, bool)`

GetModelsOk returns a tuple with the Models field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModels

`func (o *AiModelSentimentMatrixActor) SetModels(v map[string]AiModelSentimentCell)`

SetModels sets Models field to given value.

### HasModels

`func (o *AiModelSentimentMatrixActor) HasModels() bool`

HasModels returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


