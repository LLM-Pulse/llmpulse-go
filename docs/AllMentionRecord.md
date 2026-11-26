# AllMentionRecord

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **int32** | The mention&#39;s id, unique within its actor_type | 
**ActorType** | **string** | project (your brand) or competitor | 
**CompetitorId** | Pointer to **int32** | Competitor rows only | [optional] 
**Name** | **NullableString** | The project&#39;s brand name (its name when no brand name is set), or the competitor&#39;s brand name | 
**Domain** | Pointer to **NullableString** | The competitor&#39;s bare domain (competitor rows only) | [optional] 
**PromptId** | **int32** |  | 
**PromptExecutionId** | **int32** |  | 
**CreatedAt** | **time.Time** |  | 

## Methods

### NewAllMentionRecord

`func NewAllMentionRecord(id int32, actorType string, name NullableString, promptId int32, promptExecutionId int32, createdAt time.Time, ) *AllMentionRecord`

NewAllMentionRecord instantiates a new AllMentionRecord object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAllMentionRecordWithDefaults

`func NewAllMentionRecordWithDefaults() *AllMentionRecord`

NewAllMentionRecordWithDefaults instantiates a new AllMentionRecord object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *AllMentionRecord) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *AllMentionRecord) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *AllMentionRecord) SetId(v int32)`

SetId sets Id field to given value.


### GetActorType

`func (o *AllMentionRecord) GetActorType() string`

GetActorType returns the ActorType field if non-nil, zero value otherwise.

### GetActorTypeOk

`func (o *AllMentionRecord) GetActorTypeOk() (*string, bool)`

GetActorTypeOk returns a tuple with the ActorType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActorType

`func (o *AllMentionRecord) SetActorType(v string)`

SetActorType sets ActorType field to given value.


### GetCompetitorId

`func (o *AllMentionRecord) GetCompetitorId() int32`

GetCompetitorId returns the CompetitorId field if non-nil, zero value otherwise.

### GetCompetitorIdOk

`func (o *AllMentionRecord) GetCompetitorIdOk() (*int32, bool)`

GetCompetitorIdOk returns a tuple with the CompetitorId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompetitorId

`func (o *AllMentionRecord) SetCompetitorId(v int32)`

SetCompetitorId sets CompetitorId field to given value.

### HasCompetitorId

`func (o *AllMentionRecord) HasCompetitorId() bool`

HasCompetitorId returns a boolean if a field has been set.

### GetName

`func (o *AllMentionRecord) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *AllMentionRecord) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *AllMentionRecord) SetName(v string)`

SetName sets Name field to given value.


### SetNameNil

`func (o *AllMentionRecord) SetNameNil(b bool)`

 SetNameNil sets the value for Name to be an explicit nil

### UnsetName
`func (o *AllMentionRecord) UnsetName()`

UnsetName ensures that no value is present for Name, not even an explicit nil
### GetDomain

`func (o *AllMentionRecord) GetDomain() string`

GetDomain returns the Domain field if non-nil, zero value otherwise.

### GetDomainOk

`func (o *AllMentionRecord) GetDomainOk() (*string, bool)`

GetDomainOk returns a tuple with the Domain field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDomain

`func (o *AllMentionRecord) SetDomain(v string)`

SetDomain sets Domain field to given value.

### HasDomain

`func (o *AllMentionRecord) HasDomain() bool`

HasDomain returns a boolean if a field has been set.

### SetDomainNil

`func (o *AllMentionRecord) SetDomainNil(b bool)`

 SetDomainNil sets the value for Domain to be an explicit nil

### UnsetDomain
`func (o *AllMentionRecord) UnsetDomain()`

UnsetDomain ensures that no value is present for Domain, not even an explicit nil
### GetPromptId

`func (o *AllMentionRecord) GetPromptId() int32`

GetPromptId returns the PromptId field if non-nil, zero value otherwise.

### GetPromptIdOk

`func (o *AllMentionRecord) GetPromptIdOk() (*int32, bool)`

GetPromptIdOk returns a tuple with the PromptId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPromptId

`func (o *AllMentionRecord) SetPromptId(v int32)`

SetPromptId sets PromptId field to given value.


### GetPromptExecutionId

`func (o *AllMentionRecord) GetPromptExecutionId() int32`

GetPromptExecutionId returns the PromptExecutionId field if non-nil, zero value otherwise.

### GetPromptExecutionIdOk

`func (o *AllMentionRecord) GetPromptExecutionIdOk() (*int32, bool)`

GetPromptExecutionIdOk returns a tuple with the PromptExecutionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPromptExecutionId

`func (o *AllMentionRecord) SetPromptExecutionId(v int32)`

SetPromptExecutionId sets PromptExecutionId field to given value.


### GetCreatedAt

`func (o *AllMentionRecord) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *AllMentionRecord) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *AllMentionRecord) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


