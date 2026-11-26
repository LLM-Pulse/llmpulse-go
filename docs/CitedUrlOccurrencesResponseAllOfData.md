# CitedUrlOccurrencesResponseAllOfData

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**SourceId** | **int32** |  | 
**AnswerId** | **int32** |  | 
**PromptExecutionId** | **int32** | Same as answer_id | 
**PromptId** | **int32** |  | 
**PromptText** | **string** |  | 
**Model** | **string** |  | 
**ExecutedAt** | **NullableTime** |  | 
**CitationPosition** | **int32** | Rank of the citation in the answer; 0 for a background source reference | 
**Url** | **string** | Normalized cited URL | 
**Domain** | **NullableString** |  | 
**SourceType** | **string** | owned, competitor or third_party | 
**ResponseExcerpt** | **string** | The first 600 characters of the answer | 
**ResponseTruncated** | **bool** |  | 
**FanOutQueries** | **[]string** | Sub-queries the model issued while answering; null when the model reports none | 

## Methods

### NewCitedUrlOccurrencesResponseAllOfData

`func NewCitedUrlOccurrencesResponseAllOfData(sourceId int32, answerId int32, promptExecutionId int32, promptId int32, promptText string, model string, executedAt NullableTime, citationPosition int32, url string, domain NullableString, sourceType string, responseExcerpt string, responseTruncated bool, fanOutQueries []string, ) *CitedUrlOccurrencesResponseAllOfData`

NewCitedUrlOccurrencesResponseAllOfData instantiates a new CitedUrlOccurrencesResponseAllOfData object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCitedUrlOccurrencesResponseAllOfDataWithDefaults

`func NewCitedUrlOccurrencesResponseAllOfDataWithDefaults() *CitedUrlOccurrencesResponseAllOfData`

NewCitedUrlOccurrencesResponseAllOfDataWithDefaults instantiates a new CitedUrlOccurrencesResponseAllOfData object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSourceId

`func (o *CitedUrlOccurrencesResponseAllOfData) GetSourceId() int32`

GetSourceId returns the SourceId field if non-nil, zero value otherwise.

### GetSourceIdOk

`func (o *CitedUrlOccurrencesResponseAllOfData) GetSourceIdOk() (*int32, bool)`

GetSourceIdOk returns a tuple with the SourceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSourceId

`func (o *CitedUrlOccurrencesResponseAllOfData) SetSourceId(v int32)`

SetSourceId sets SourceId field to given value.


### GetAnswerId

`func (o *CitedUrlOccurrencesResponseAllOfData) GetAnswerId() int32`

GetAnswerId returns the AnswerId field if non-nil, zero value otherwise.

### GetAnswerIdOk

`func (o *CitedUrlOccurrencesResponseAllOfData) GetAnswerIdOk() (*int32, bool)`

GetAnswerIdOk returns a tuple with the AnswerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAnswerId

`func (o *CitedUrlOccurrencesResponseAllOfData) SetAnswerId(v int32)`

SetAnswerId sets AnswerId field to given value.


### GetPromptExecutionId

`func (o *CitedUrlOccurrencesResponseAllOfData) GetPromptExecutionId() int32`

GetPromptExecutionId returns the PromptExecutionId field if non-nil, zero value otherwise.

### GetPromptExecutionIdOk

`func (o *CitedUrlOccurrencesResponseAllOfData) GetPromptExecutionIdOk() (*int32, bool)`

GetPromptExecutionIdOk returns a tuple with the PromptExecutionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPromptExecutionId

`func (o *CitedUrlOccurrencesResponseAllOfData) SetPromptExecutionId(v int32)`

SetPromptExecutionId sets PromptExecutionId field to given value.


### GetPromptId

`func (o *CitedUrlOccurrencesResponseAllOfData) GetPromptId() int32`

GetPromptId returns the PromptId field if non-nil, zero value otherwise.

### GetPromptIdOk

`func (o *CitedUrlOccurrencesResponseAllOfData) GetPromptIdOk() (*int32, bool)`

GetPromptIdOk returns a tuple with the PromptId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPromptId

`func (o *CitedUrlOccurrencesResponseAllOfData) SetPromptId(v int32)`

SetPromptId sets PromptId field to given value.


### GetPromptText

`func (o *CitedUrlOccurrencesResponseAllOfData) GetPromptText() string`

GetPromptText returns the PromptText field if non-nil, zero value otherwise.

### GetPromptTextOk

`func (o *CitedUrlOccurrencesResponseAllOfData) GetPromptTextOk() (*string, bool)`

GetPromptTextOk returns a tuple with the PromptText field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPromptText

`func (o *CitedUrlOccurrencesResponseAllOfData) SetPromptText(v string)`

SetPromptText sets PromptText field to given value.


### GetModel

`func (o *CitedUrlOccurrencesResponseAllOfData) GetModel() string`

GetModel returns the Model field if non-nil, zero value otherwise.

### GetModelOk

`func (o *CitedUrlOccurrencesResponseAllOfData) GetModelOk() (*string, bool)`

GetModelOk returns a tuple with the Model field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModel

`func (o *CitedUrlOccurrencesResponseAllOfData) SetModel(v string)`

SetModel sets Model field to given value.


### GetExecutedAt

`func (o *CitedUrlOccurrencesResponseAllOfData) GetExecutedAt() time.Time`

GetExecutedAt returns the ExecutedAt field if non-nil, zero value otherwise.

### GetExecutedAtOk

`func (o *CitedUrlOccurrencesResponseAllOfData) GetExecutedAtOk() (*time.Time, bool)`

GetExecutedAtOk returns a tuple with the ExecutedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExecutedAt

`func (o *CitedUrlOccurrencesResponseAllOfData) SetExecutedAt(v time.Time)`

SetExecutedAt sets ExecutedAt field to given value.


### SetExecutedAtNil

`func (o *CitedUrlOccurrencesResponseAllOfData) SetExecutedAtNil(b bool)`

 SetExecutedAtNil sets the value for ExecutedAt to be an explicit nil

### UnsetExecutedAt
`func (o *CitedUrlOccurrencesResponseAllOfData) UnsetExecutedAt()`

UnsetExecutedAt ensures that no value is present for ExecutedAt, not even an explicit nil
### GetCitationPosition

`func (o *CitedUrlOccurrencesResponseAllOfData) GetCitationPosition() int32`

GetCitationPosition returns the CitationPosition field if non-nil, zero value otherwise.

### GetCitationPositionOk

`func (o *CitedUrlOccurrencesResponseAllOfData) GetCitationPositionOk() (*int32, bool)`

GetCitationPositionOk returns a tuple with the CitationPosition field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCitationPosition

`func (o *CitedUrlOccurrencesResponseAllOfData) SetCitationPosition(v int32)`

SetCitationPosition sets CitationPosition field to given value.


### GetUrl

`func (o *CitedUrlOccurrencesResponseAllOfData) GetUrl() string`

GetUrl returns the Url field if non-nil, zero value otherwise.

### GetUrlOk

`func (o *CitedUrlOccurrencesResponseAllOfData) GetUrlOk() (*string, bool)`

GetUrlOk returns a tuple with the Url field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrl

`func (o *CitedUrlOccurrencesResponseAllOfData) SetUrl(v string)`

SetUrl sets Url field to given value.


### GetDomain

`func (o *CitedUrlOccurrencesResponseAllOfData) GetDomain() string`

GetDomain returns the Domain field if non-nil, zero value otherwise.

### GetDomainOk

`func (o *CitedUrlOccurrencesResponseAllOfData) GetDomainOk() (*string, bool)`

GetDomainOk returns a tuple with the Domain field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDomain

`func (o *CitedUrlOccurrencesResponseAllOfData) SetDomain(v string)`

SetDomain sets Domain field to given value.


### SetDomainNil

`func (o *CitedUrlOccurrencesResponseAllOfData) SetDomainNil(b bool)`

 SetDomainNil sets the value for Domain to be an explicit nil

### UnsetDomain
`func (o *CitedUrlOccurrencesResponseAllOfData) UnsetDomain()`

UnsetDomain ensures that no value is present for Domain, not even an explicit nil
### GetSourceType

`func (o *CitedUrlOccurrencesResponseAllOfData) GetSourceType() string`

GetSourceType returns the SourceType field if non-nil, zero value otherwise.

### GetSourceTypeOk

`func (o *CitedUrlOccurrencesResponseAllOfData) GetSourceTypeOk() (*string, bool)`

GetSourceTypeOk returns a tuple with the SourceType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSourceType

`func (o *CitedUrlOccurrencesResponseAllOfData) SetSourceType(v string)`

SetSourceType sets SourceType field to given value.


### GetResponseExcerpt

`func (o *CitedUrlOccurrencesResponseAllOfData) GetResponseExcerpt() string`

GetResponseExcerpt returns the ResponseExcerpt field if non-nil, zero value otherwise.

### GetResponseExcerptOk

`func (o *CitedUrlOccurrencesResponseAllOfData) GetResponseExcerptOk() (*string, bool)`

GetResponseExcerptOk returns a tuple with the ResponseExcerpt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResponseExcerpt

`func (o *CitedUrlOccurrencesResponseAllOfData) SetResponseExcerpt(v string)`

SetResponseExcerpt sets ResponseExcerpt field to given value.


### GetResponseTruncated

`func (o *CitedUrlOccurrencesResponseAllOfData) GetResponseTruncated() bool`

GetResponseTruncated returns the ResponseTruncated field if non-nil, zero value otherwise.

### GetResponseTruncatedOk

`func (o *CitedUrlOccurrencesResponseAllOfData) GetResponseTruncatedOk() (*bool, bool)`

GetResponseTruncatedOk returns a tuple with the ResponseTruncated field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResponseTruncated

`func (o *CitedUrlOccurrencesResponseAllOfData) SetResponseTruncated(v bool)`

SetResponseTruncated sets ResponseTruncated field to given value.


### GetFanOutQueries

`func (o *CitedUrlOccurrencesResponseAllOfData) GetFanOutQueries() []string`

GetFanOutQueries returns the FanOutQueries field if non-nil, zero value otherwise.

### GetFanOutQueriesOk

`func (o *CitedUrlOccurrencesResponseAllOfData) GetFanOutQueriesOk() (*[]string, bool)`

GetFanOutQueriesOk returns a tuple with the FanOutQueries field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFanOutQueries

`func (o *CitedUrlOccurrencesResponseAllOfData) SetFanOutQueries(v []string)`

SetFanOutQueries sets FanOutQueries field to given value.


### SetFanOutQueriesNil

`func (o *CitedUrlOccurrencesResponseAllOfData) SetFanOutQueriesNil(b bool)`

 SetFanOutQueriesNil sets the value for FanOutQueries to be an explicit nil

### UnsetFanOutQueries
`func (o *CitedUrlOccurrencesResponseAllOfData) UnsetFanOutQueries()`

UnsetFanOutQueries ensures that no value is present for FanOutQueries, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


