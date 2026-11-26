# AllCitationRecord

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **int32** | The citation&#39;s id, unique within its actor_type | 
**ActorType** | **string** | project (your brand) or competitor | 
**CompetitorId** | Pointer to **int32** | Competitor rows only | [optional] 
**Name** | **NullableString** | The project&#39;s brand name (its name when no brand name is set), or the competitor&#39;s brand name | 
**Domain** | **NullableString** | On project rows the host of the cited URL without www. (null when it has no parsable host); on competitor rows the competitor&#39;s bare domain | 
**PromptId** | **int32** |  | 
**PromptExecutionId** | **int32** |  | 
**Url** | **string** | Normalized cited URL (tracking parameters and fragment removed) | 
**Position** | **NullableInt32** | Rank of the citation in the answer; 0 for a background source reference with no visible rank | 
**CreatedAt** | **time.Time** |  | 

## Methods

### NewAllCitationRecord

`func NewAllCitationRecord(id int32, actorType string, name NullableString, domain NullableString, promptId int32, promptExecutionId int32, url string, position NullableInt32, createdAt time.Time, ) *AllCitationRecord`

NewAllCitationRecord instantiates a new AllCitationRecord object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAllCitationRecordWithDefaults

`func NewAllCitationRecordWithDefaults() *AllCitationRecord`

NewAllCitationRecordWithDefaults instantiates a new AllCitationRecord object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *AllCitationRecord) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *AllCitationRecord) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *AllCitationRecord) SetId(v int32)`

SetId sets Id field to given value.


### GetActorType

`func (o *AllCitationRecord) GetActorType() string`

GetActorType returns the ActorType field if non-nil, zero value otherwise.

### GetActorTypeOk

`func (o *AllCitationRecord) GetActorTypeOk() (*string, bool)`

GetActorTypeOk returns a tuple with the ActorType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActorType

`func (o *AllCitationRecord) SetActorType(v string)`

SetActorType sets ActorType field to given value.


### GetCompetitorId

`func (o *AllCitationRecord) GetCompetitorId() int32`

GetCompetitorId returns the CompetitorId field if non-nil, zero value otherwise.

### GetCompetitorIdOk

`func (o *AllCitationRecord) GetCompetitorIdOk() (*int32, bool)`

GetCompetitorIdOk returns a tuple with the CompetitorId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompetitorId

`func (o *AllCitationRecord) SetCompetitorId(v int32)`

SetCompetitorId sets CompetitorId field to given value.

### HasCompetitorId

`func (o *AllCitationRecord) HasCompetitorId() bool`

HasCompetitorId returns a boolean if a field has been set.

### GetName

`func (o *AllCitationRecord) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *AllCitationRecord) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *AllCitationRecord) SetName(v string)`

SetName sets Name field to given value.


### SetNameNil

`func (o *AllCitationRecord) SetNameNil(b bool)`

 SetNameNil sets the value for Name to be an explicit nil

### UnsetName
`func (o *AllCitationRecord) UnsetName()`

UnsetName ensures that no value is present for Name, not even an explicit nil
### GetDomain

`func (o *AllCitationRecord) GetDomain() string`

GetDomain returns the Domain field if non-nil, zero value otherwise.

### GetDomainOk

`func (o *AllCitationRecord) GetDomainOk() (*string, bool)`

GetDomainOk returns a tuple with the Domain field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDomain

`func (o *AllCitationRecord) SetDomain(v string)`

SetDomain sets Domain field to given value.


### SetDomainNil

`func (o *AllCitationRecord) SetDomainNil(b bool)`

 SetDomainNil sets the value for Domain to be an explicit nil

### UnsetDomain
`func (o *AllCitationRecord) UnsetDomain()`

UnsetDomain ensures that no value is present for Domain, not even an explicit nil
### GetPromptId

`func (o *AllCitationRecord) GetPromptId() int32`

GetPromptId returns the PromptId field if non-nil, zero value otherwise.

### GetPromptIdOk

`func (o *AllCitationRecord) GetPromptIdOk() (*int32, bool)`

GetPromptIdOk returns a tuple with the PromptId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPromptId

`func (o *AllCitationRecord) SetPromptId(v int32)`

SetPromptId sets PromptId field to given value.


### GetPromptExecutionId

`func (o *AllCitationRecord) GetPromptExecutionId() int32`

GetPromptExecutionId returns the PromptExecutionId field if non-nil, zero value otherwise.

### GetPromptExecutionIdOk

`func (o *AllCitationRecord) GetPromptExecutionIdOk() (*int32, bool)`

GetPromptExecutionIdOk returns a tuple with the PromptExecutionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPromptExecutionId

`func (o *AllCitationRecord) SetPromptExecutionId(v int32)`

SetPromptExecutionId sets PromptExecutionId field to given value.


### GetUrl

`func (o *AllCitationRecord) GetUrl() string`

GetUrl returns the Url field if non-nil, zero value otherwise.

### GetUrlOk

`func (o *AllCitationRecord) GetUrlOk() (*string, bool)`

GetUrlOk returns a tuple with the Url field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrl

`func (o *AllCitationRecord) SetUrl(v string)`

SetUrl sets Url field to given value.


### GetPosition

`func (o *AllCitationRecord) GetPosition() int32`

GetPosition returns the Position field if non-nil, zero value otherwise.

### GetPositionOk

`func (o *AllCitationRecord) GetPositionOk() (*int32, bool)`

GetPositionOk returns a tuple with the Position field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPosition

`func (o *AllCitationRecord) SetPosition(v int32)`

SetPosition sets Position field to given value.


### SetPositionNil

`func (o *AllCitationRecord) SetPositionNil(b bool)`

 SetPositionNil sets the value for Position to be an explicit nil

### UnsetPosition
`func (o *AllCitationRecord) UnsetPosition()`

UnsetPosition ensures that no value is present for Position, not even an explicit nil
### GetCreatedAt

`func (o *AllCitationRecord) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *AllCitationRecord) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *AllCitationRecord) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


