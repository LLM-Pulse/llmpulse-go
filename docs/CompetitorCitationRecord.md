# CompetitorCitationRecord

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **int32** |  | 
**CompetitorId** | **int32** |  | 
**Name** | **string** | The competitor&#39;s brand name | 
**Domain** | **string** | The competitor&#39;s bare domain | 
**PromptExecutionId** | **int32** |  | 
**Url** | **string** | Normalized cited URL (tracking parameters and fragment removed) | 
**Position** | **NullableInt32** | Rank of the citation in the answer; 0 for a background source reference with no visible rank | 
**CreatedAt** | **time.Time** |  | 

## Methods

### NewCompetitorCitationRecord

`func NewCompetitorCitationRecord(id int32, competitorId int32, name string, domain string, promptExecutionId int32, url string, position NullableInt32, createdAt time.Time, ) *CompetitorCitationRecord`

NewCompetitorCitationRecord instantiates a new CompetitorCitationRecord object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCompetitorCitationRecordWithDefaults

`func NewCompetitorCitationRecordWithDefaults() *CompetitorCitationRecord`

NewCompetitorCitationRecordWithDefaults instantiates a new CompetitorCitationRecord object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *CompetitorCitationRecord) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *CompetitorCitationRecord) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *CompetitorCitationRecord) SetId(v int32)`

SetId sets Id field to given value.


### GetCompetitorId

`func (o *CompetitorCitationRecord) GetCompetitorId() int32`

GetCompetitorId returns the CompetitorId field if non-nil, zero value otherwise.

### GetCompetitorIdOk

`func (o *CompetitorCitationRecord) GetCompetitorIdOk() (*int32, bool)`

GetCompetitorIdOk returns a tuple with the CompetitorId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompetitorId

`func (o *CompetitorCitationRecord) SetCompetitorId(v int32)`

SetCompetitorId sets CompetitorId field to given value.


### GetName

`func (o *CompetitorCitationRecord) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *CompetitorCitationRecord) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *CompetitorCitationRecord) SetName(v string)`

SetName sets Name field to given value.


### GetDomain

`func (o *CompetitorCitationRecord) GetDomain() string`

GetDomain returns the Domain field if non-nil, zero value otherwise.

### GetDomainOk

`func (o *CompetitorCitationRecord) GetDomainOk() (*string, bool)`

GetDomainOk returns a tuple with the Domain field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDomain

`func (o *CompetitorCitationRecord) SetDomain(v string)`

SetDomain sets Domain field to given value.


### GetPromptExecutionId

`func (o *CompetitorCitationRecord) GetPromptExecutionId() int32`

GetPromptExecutionId returns the PromptExecutionId field if non-nil, zero value otherwise.

### GetPromptExecutionIdOk

`func (o *CompetitorCitationRecord) GetPromptExecutionIdOk() (*int32, bool)`

GetPromptExecutionIdOk returns a tuple with the PromptExecutionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPromptExecutionId

`func (o *CompetitorCitationRecord) SetPromptExecutionId(v int32)`

SetPromptExecutionId sets PromptExecutionId field to given value.


### GetUrl

`func (o *CompetitorCitationRecord) GetUrl() string`

GetUrl returns the Url field if non-nil, zero value otherwise.

### GetUrlOk

`func (o *CompetitorCitationRecord) GetUrlOk() (*string, bool)`

GetUrlOk returns a tuple with the Url field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrl

`func (o *CompetitorCitationRecord) SetUrl(v string)`

SetUrl sets Url field to given value.


### GetPosition

`func (o *CompetitorCitationRecord) GetPosition() int32`

GetPosition returns the Position field if non-nil, zero value otherwise.

### GetPositionOk

`func (o *CompetitorCitationRecord) GetPositionOk() (*int32, bool)`

GetPositionOk returns a tuple with the Position field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPosition

`func (o *CompetitorCitationRecord) SetPosition(v int32)`

SetPosition sets Position field to given value.


### SetPositionNil

`func (o *CompetitorCitationRecord) SetPositionNil(b bool)`

 SetPositionNil sets the value for Position to be an explicit nil

### UnsetPosition
`func (o *CompetitorCitationRecord) UnsetPosition()`

UnsetPosition ensures that no value is present for Position, not even an explicit nil
### GetCreatedAt

`func (o *CompetitorCitationRecord) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *CompetitorCitationRecord) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *CompetitorCitationRecord) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


