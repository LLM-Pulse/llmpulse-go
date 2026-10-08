# CitationRecord

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **int32** |  | 
**Name** | **string** | The project&#39;s brand name (its name when no brand name is set) | 
**Domain** | **NullableString** | Host of the cited URL without www.; null when the URL has no parsable host | 
**PromptId** | **int32** |  | 
**PromptExecutionId** | **int32** |  | 
**Url** | **string** | Normalized cited URL (tracking parameters and fragment removed) | 
**Position** | **NullableInt32** | Rank of the citation in the answer; 0 for a background source reference with no visible rank | 
**CreatedAt** | **time.Time** |  | 

## Methods

### NewCitationRecord

`func NewCitationRecord(id int32, name string, domain NullableString, promptId int32, promptExecutionId int32, url string, position NullableInt32, createdAt time.Time, ) *CitationRecord`

NewCitationRecord instantiates a new CitationRecord object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCitationRecordWithDefaults

`func NewCitationRecordWithDefaults() *CitationRecord`

NewCitationRecordWithDefaults instantiates a new CitationRecord object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *CitationRecord) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *CitationRecord) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *CitationRecord) SetId(v int32)`

SetId sets Id field to given value.


### GetName

`func (o *CitationRecord) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *CitationRecord) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *CitationRecord) SetName(v string)`

SetName sets Name field to given value.


### GetDomain

`func (o *CitationRecord) GetDomain() string`

GetDomain returns the Domain field if non-nil, zero value otherwise.

### GetDomainOk

`func (o *CitationRecord) GetDomainOk() (*string, bool)`

GetDomainOk returns a tuple with the Domain field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDomain

`func (o *CitationRecord) SetDomain(v string)`

SetDomain sets Domain field to given value.


### SetDomainNil

`func (o *CitationRecord) SetDomainNil(b bool)`

 SetDomainNil sets the value for Domain to be an explicit nil

### UnsetDomain
`func (o *CitationRecord) UnsetDomain()`

UnsetDomain ensures that no value is present for Domain, not even an explicit nil
### GetPromptId

`func (o *CitationRecord) GetPromptId() int32`

GetPromptId returns the PromptId field if non-nil, zero value otherwise.

### GetPromptIdOk

`func (o *CitationRecord) GetPromptIdOk() (*int32, bool)`

GetPromptIdOk returns a tuple with the PromptId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPromptId

`func (o *CitationRecord) SetPromptId(v int32)`

SetPromptId sets PromptId field to given value.


### GetPromptExecutionId

`func (o *CitationRecord) GetPromptExecutionId() int32`

GetPromptExecutionId returns the PromptExecutionId field if non-nil, zero value otherwise.

### GetPromptExecutionIdOk

`func (o *CitationRecord) GetPromptExecutionIdOk() (*int32, bool)`

GetPromptExecutionIdOk returns a tuple with the PromptExecutionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPromptExecutionId

`func (o *CitationRecord) SetPromptExecutionId(v int32)`

SetPromptExecutionId sets PromptExecutionId field to given value.


### GetUrl

`func (o *CitationRecord) GetUrl() string`

GetUrl returns the Url field if non-nil, zero value otherwise.

### GetUrlOk

`func (o *CitationRecord) GetUrlOk() (*string, bool)`

GetUrlOk returns a tuple with the Url field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrl

`func (o *CitationRecord) SetUrl(v string)`

SetUrl sets Url field to given value.


### GetPosition

`func (o *CitationRecord) GetPosition() int32`

GetPosition returns the Position field if non-nil, zero value otherwise.

### GetPositionOk

`func (o *CitationRecord) GetPositionOk() (*int32, bool)`

GetPositionOk returns a tuple with the Position field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPosition

`func (o *CitationRecord) SetPosition(v int32)`

SetPosition sets Position field to given value.


### SetPositionNil

`func (o *CitationRecord) SetPositionNil(b bool)`

 SetPositionNil sets the value for Position to be an explicit nil

### UnsetPosition
`func (o *CitationRecord) UnsetPosition()`

UnsetPosition ensures that no value is present for Position, not even an explicit nil
### GetCreatedAt

`func (o *CitationRecord) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *CitationRecord) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *CitationRecord) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


