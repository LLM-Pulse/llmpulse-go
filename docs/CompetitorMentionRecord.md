# CompetitorMentionRecord

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **int32** |  | 
**CompetitorId** | **int32** |  | 
**Name** | **string** | The competitor&#39;s brand name | 
**Domain** | **string** | The competitor&#39;s bare domain | 
**PromptExecutionId** | **int32** |  | 
**CreatedAt** | **time.Time** |  | 

## Methods

### NewCompetitorMentionRecord

`func NewCompetitorMentionRecord(id int32, competitorId int32, name string, domain string, promptExecutionId int32, createdAt time.Time, ) *CompetitorMentionRecord`

NewCompetitorMentionRecord instantiates a new CompetitorMentionRecord object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCompetitorMentionRecordWithDefaults

`func NewCompetitorMentionRecordWithDefaults() *CompetitorMentionRecord`

NewCompetitorMentionRecordWithDefaults instantiates a new CompetitorMentionRecord object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *CompetitorMentionRecord) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *CompetitorMentionRecord) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *CompetitorMentionRecord) SetId(v int32)`

SetId sets Id field to given value.


### GetCompetitorId

`func (o *CompetitorMentionRecord) GetCompetitorId() int32`

GetCompetitorId returns the CompetitorId field if non-nil, zero value otherwise.

### GetCompetitorIdOk

`func (o *CompetitorMentionRecord) GetCompetitorIdOk() (*int32, bool)`

GetCompetitorIdOk returns a tuple with the CompetitorId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompetitorId

`func (o *CompetitorMentionRecord) SetCompetitorId(v int32)`

SetCompetitorId sets CompetitorId field to given value.


### GetName

`func (o *CompetitorMentionRecord) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *CompetitorMentionRecord) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *CompetitorMentionRecord) SetName(v string)`

SetName sets Name field to given value.


### GetDomain

`func (o *CompetitorMentionRecord) GetDomain() string`

GetDomain returns the Domain field if non-nil, zero value otherwise.

### GetDomainOk

`func (o *CompetitorMentionRecord) GetDomainOk() (*string, bool)`

GetDomainOk returns a tuple with the Domain field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDomain

`func (o *CompetitorMentionRecord) SetDomain(v string)`

SetDomain sets Domain field to given value.


### GetPromptExecutionId

`func (o *CompetitorMentionRecord) GetPromptExecutionId() int32`

GetPromptExecutionId returns the PromptExecutionId field if non-nil, zero value otherwise.

### GetPromptExecutionIdOk

`func (o *CompetitorMentionRecord) GetPromptExecutionIdOk() (*int32, bool)`

GetPromptExecutionIdOk returns a tuple with the PromptExecutionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPromptExecutionId

`func (o *CompetitorMentionRecord) SetPromptExecutionId(v int32)`

SetPromptExecutionId sets PromptExecutionId field to given value.


### GetCreatedAt

`func (o *CompetitorMentionRecord) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *CompetitorMentionRecord) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *CompetitorMentionRecord) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


