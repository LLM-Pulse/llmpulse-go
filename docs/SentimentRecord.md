# SentimentRecord

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **int32** |  | 
**PromptExecutionId** | **int32** |  | 
**PromptText** | **string** |  | 
**Model** | **string** |  | 
**Analysis** | **string** |  | 
**Score** | **NullableFloat32** | From -1 (very negative) to 1 (very positive) | 
**Comment** | **NullableString** |  | 
**Topics** | **NullableString** | Comma-separated topics | 
**CompetitorId** | **NullableInt32** | Null for a sentiment about the project&#39;s own brand | 
**CompetitorName** | **NullableString** | Null for a sentiment about the project&#39;s own brand | 
**IsBrandSentiment** | **bool** |  | 
**ExecutedAt** | **NullableTime** |  | 
**CreatedAt** | **time.Time** |  | 

## Methods

### NewSentimentRecord

`func NewSentimentRecord(id int32, promptExecutionId int32, promptText string, model string, analysis string, score NullableFloat32, comment NullableString, topics NullableString, competitorId NullableInt32, competitorName NullableString, isBrandSentiment bool, executedAt NullableTime, createdAt time.Time, ) *SentimentRecord`

NewSentimentRecord instantiates a new SentimentRecord object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSentimentRecordWithDefaults

`func NewSentimentRecordWithDefaults() *SentimentRecord`

NewSentimentRecordWithDefaults instantiates a new SentimentRecord object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *SentimentRecord) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *SentimentRecord) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *SentimentRecord) SetId(v int32)`

SetId sets Id field to given value.


### GetPromptExecutionId

`func (o *SentimentRecord) GetPromptExecutionId() int32`

GetPromptExecutionId returns the PromptExecutionId field if non-nil, zero value otherwise.

### GetPromptExecutionIdOk

`func (o *SentimentRecord) GetPromptExecutionIdOk() (*int32, bool)`

GetPromptExecutionIdOk returns a tuple with the PromptExecutionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPromptExecutionId

`func (o *SentimentRecord) SetPromptExecutionId(v int32)`

SetPromptExecutionId sets PromptExecutionId field to given value.


### GetPromptText

`func (o *SentimentRecord) GetPromptText() string`

GetPromptText returns the PromptText field if non-nil, zero value otherwise.

### GetPromptTextOk

`func (o *SentimentRecord) GetPromptTextOk() (*string, bool)`

GetPromptTextOk returns a tuple with the PromptText field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPromptText

`func (o *SentimentRecord) SetPromptText(v string)`

SetPromptText sets PromptText field to given value.


### GetModel

`func (o *SentimentRecord) GetModel() string`

GetModel returns the Model field if non-nil, zero value otherwise.

### GetModelOk

`func (o *SentimentRecord) GetModelOk() (*string, bool)`

GetModelOk returns a tuple with the Model field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModel

`func (o *SentimentRecord) SetModel(v string)`

SetModel sets Model field to given value.


### GetAnalysis

`func (o *SentimentRecord) GetAnalysis() string`

GetAnalysis returns the Analysis field if non-nil, zero value otherwise.

### GetAnalysisOk

`func (o *SentimentRecord) GetAnalysisOk() (*string, bool)`

GetAnalysisOk returns a tuple with the Analysis field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAnalysis

`func (o *SentimentRecord) SetAnalysis(v string)`

SetAnalysis sets Analysis field to given value.


### GetScore

`func (o *SentimentRecord) GetScore() float32`

GetScore returns the Score field if non-nil, zero value otherwise.

### GetScoreOk

`func (o *SentimentRecord) GetScoreOk() (*float32, bool)`

GetScoreOk returns a tuple with the Score field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScore

`func (o *SentimentRecord) SetScore(v float32)`

SetScore sets Score field to given value.


### SetScoreNil

`func (o *SentimentRecord) SetScoreNil(b bool)`

 SetScoreNil sets the value for Score to be an explicit nil

### UnsetScore
`func (o *SentimentRecord) UnsetScore()`

UnsetScore ensures that no value is present for Score, not even an explicit nil
### GetComment

`func (o *SentimentRecord) GetComment() string`

GetComment returns the Comment field if non-nil, zero value otherwise.

### GetCommentOk

`func (o *SentimentRecord) GetCommentOk() (*string, bool)`

GetCommentOk returns a tuple with the Comment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComment

`func (o *SentimentRecord) SetComment(v string)`

SetComment sets Comment field to given value.


### SetCommentNil

`func (o *SentimentRecord) SetCommentNil(b bool)`

 SetCommentNil sets the value for Comment to be an explicit nil

### UnsetComment
`func (o *SentimentRecord) UnsetComment()`

UnsetComment ensures that no value is present for Comment, not even an explicit nil
### GetTopics

`func (o *SentimentRecord) GetTopics() string`

GetTopics returns the Topics field if non-nil, zero value otherwise.

### GetTopicsOk

`func (o *SentimentRecord) GetTopicsOk() (*string, bool)`

GetTopicsOk returns a tuple with the Topics field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTopics

`func (o *SentimentRecord) SetTopics(v string)`

SetTopics sets Topics field to given value.


### SetTopicsNil

`func (o *SentimentRecord) SetTopicsNil(b bool)`

 SetTopicsNil sets the value for Topics to be an explicit nil

### UnsetTopics
`func (o *SentimentRecord) UnsetTopics()`

UnsetTopics ensures that no value is present for Topics, not even an explicit nil
### GetCompetitorId

`func (o *SentimentRecord) GetCompetitorId() int32`

GetCompetitorId returns the CompetitorId field if non-nil, zero value otherwise.

### GetCompetitorIdOk

`func (o *SentimentRecord) GetCompetitorIdOk() (*int32, bool)`

GetCompetitorIdOk returns a tuple with the CompetitorId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompetitorId

`func (o *SentimentRecord) SetCompetitorId(v int32)`

SetCompetitorId sets CompetitorId field to given value.


### SetCompetitorIdNil

`func (o *SentimentRecord) SetCompetitorIdNil(b bool)`

 SetCompetitorIdNil sets the value for CompetitorId to be an explicit nil

### UnsetCompetitorId
`func (o *SentimentRecord) UnsetCompetitorId()`

UnsetCompetitorId ensures that no value is present for CompetitorId, not even an explicit nil
### GetCompetitorName

`func (o *SentimentRecord) GetCompetitorName() string`

GetCompetitorName returns the CompetitorName field if non-nil, zero value otherwise.

### GetCompetitorNameOk

`func (o *SentimentRecord) GetCompetitorNameOk() (*string, bool)`

GetCompetitorNameOk returns a tuple with the CompetitorName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompetitorName

`func (o *SentimentRecord) SetCompetitorName(v string)`

SetCompetitorName sets CompetitorName field to given value.


### SetCompetitorNameNil

`func (o *SentimentRecord) SetCompetitorNameNil(b bool)`

 SetCompetitorNameNil sets the value for CompetitorName to be an explicit nil

### UnsetCompetitorName
`func (o *SentimentRecord) UnsetCompetitorName()`

UnsetCompetitorName ensures that no value is present for CompetitorName, not even an explicit nil
### GetIsBrandSentiment

`func (o *SentimentRecord) GetIsBrandSentiment() bool`

GetIsBrandSentiment returns the IsBrandSentiment field if non-nil, zero value otherwise.

### GetIsBrandSentimentOk

`func (o *SentimentRecord) GetIsBrandSentimentOk() (*bool, bool)`

GetIsBrandSentimentOk returns a tuple with the IsBrandSentiment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsBrandSentiment

`func (o *SentimentRecord) SetIsBrandSentiment(v bool)`

SetIsBrandSentiment sets IsBrandSentiment field to given value.


### GetExecutedAt

`func (o *SentimentRecord) GetExecutedAt() time.Time`

GetExecutedAt returns the ExecutedAt field if non-nil, zero value otherwise.

### GetExecutedAtOk

`func (o *SentimentRecord) GetExecutedAtOk() (*time.Time, bool)`

GetExecutedAtOk returns a tuple with the ExecutedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExecutedAt

`func (o *SentimentRecord) SetExecutedAt(v time.Time)`

SetExecutedAt sets ExecutedAt field to given value.


### SetExecutedAtNil

`func (o *SentimentRecord) SetExecutedAtNil(b bool)`

 SetExecutedAtNil sets the value for ExecutedAt to be an explicit nil

### UnsetExecutedAt
`func (o *SentimentRecord) UnsetExecutedAt()`

UnsetExecutedAt ensures that no value is present for ExecutedAt, not even an explicit nil
### GetCreatedAt

`func (o *SentimentRecord) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *SentimentRecord) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *SentimentRecord) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


