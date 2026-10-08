# PromptExecutionRecord

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **int32** |  | 
**PromptId** | **int32** |  | 
**ExecutedAt** | **NullableTime** | Null while the answer is still pending | 
**DurationMs** | **NullableFloat32** |  | 
**Success** | **NullableBool** | Null while the answer is still pending | 
**Model** | **string** |  | 
**FanOutQueries** | **[]string** | Sub-queries the model issued while answering; null when the model reports none | 
**HasMention** | **bool** |  | 
**HasCitation** | **bool** |  | 
**MentionsCount** | **int32** | 1 when the answer mentions the brand, otherwise 0 | 
**CitationsCount** | **int32** | 1 when the answer cites the brand, otherwise 0 | 
**AppUrl** | **string** | Opens this answer in the app. The link names its project, so it opens there for any user with access to that project | 

## Methods

### NewPromptExecutionRecord

`func NewPromptExecutionRecord(id int32, promptId int32, executedAt NullableTime, durationMs NullableFloat32, success NullableBool, model string, fanOutQueries []string, hasMention bool, hasCitation bool, mentionsCount int32, citationsCount int32, appUrl string, ) *PromptExecutionRecord`

NewPromptExecutionRecord instantiates a new PromptExecutionRecord object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPromptExecutionRecordWithDefaults

`func NewPromptExecutionRecordWithDefaults() *PromptExecutionRecord`

NewPromptExecutionRecordWithDefaults instantiates a new PromptExecutionRecord object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *PromptExecutionRecord) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *PromptExecutionRecord) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *PromptExecutionRecord) SetId(v int32)`

SetId sets Id field to given value.


### GetPromptId

`func (o *PromptExecutionRecord) GetPromptId() int32`

GetPromptId returns the PromptId field if non-nil, zero value otherwise.

### GetPromptIdOk

`func (o *PromptExecutionRecord) GetPromptIdOk() (*int32, bool)`

GetPromptIdOk returns a tuple with the PromptId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPromptId

`func (o *PromptExecutionRecord) SetPromptId(v int32)`

SetPromptId sets PromptId field to given value.


### GetExecutedAt

`func (o *PromptExecutionRecord) GetExecutedAt() time.Time`

GetExecutedAt returns the ExecutedAt field if non-nil, zero value otherwise.

### GetExecutedAtOk

`func (o *PromptExecutionRecord) GetExecutedAtOk() (*time.Time, bool)`

GetExecutedAtOk returns a tuple with the ExecutedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExecutedAt

`func (o *PromptExecutionRecord) SetExecutedAt(v time.Time)`

SetExecutedAt sets ExecutedAt field to given value.


### SetExecutedAtNil

`func (o *PromptExecutionRecord) SetExecutedAtNil(b bool)`

 SetExecutedAtNil sets the value for ExecutedAt to be an explicit nil

### UnsetExecutedAt
`func (o *PromptExecutionRecord) UnsetExecutedAt()`

UnsetExecutedAt ensures that no value is present for ExecutedAt, not even an explicit nil
### GetDurationMs

`func (o *PromptExecutionRecord) GetDurationMs() float32`

GetDurationMs returns the DurationMs field if non-nil, zero value otherwise.

### GetDurationMsOk

`func (o *PromptExecutionRecord) GetDurationMsOk() (*float32, bool)`

GetDurationMsOk returns a tuple with the DurationMs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDurationMs

`func (o *PromptExecutionRecord) SetDurationMs(v float32)`

SetDurationMs sets DurationMs field to given value.


### SetDurationMsNil

`func (o *PromptExecutionRecord) SetDurationMsNil(b bool)`

 SetDurationMsNil sets the value for DurationMs to be an explicit nil

### UnsetDurationMs
`func (o *PromptExecutionRecord) UnsetDurationMs()`

UnsetDurationMs ensures that no value is present for DurationMs, not even an explicit nil
### GetSuccess

`func (o *PromptExecutionRecord) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *PromptExecutionRecord) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *PromptExecutionRecord) SetSuccess(v bool)`

SetSuccess sets Success field to given value.


### SetSuccessNil

`func (o *PromptExecutionRecord) SetSuccessNil(b bool)`

 SetSuccessNil sets the value for Success to be an explicit nil

### UnsetSuccess
`func (o *PromptExecutionRecord) UnsetSuccess()`

UnsetSuccess ensures that no value is present for Success, not even an explicit nil
### GetModel

`func (o *PromptExecutionRecord) GetModel() string`

GetModel returns the Model field if non-nil, zero value otherwise.

### GetModelOk

`func (o *PromptExecutionRecord) GetModelOk() (*string, bool)`

GetModelOk returns a tuple with the Model field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModel

`func (o *PromptExecutionRecord) SetModel(v string)`

SetModel sets Model field to given value.


### GetFanOutQueries

`func (o *PromptExecutionRecord) GetFanOutQueries() []string`

GetFanOutQueries returns the FanOutQueries field if non-nil, zero value otherwise.

### GetFanOutQueriesOk

`func (o *PromptExecutionRecord) GetFanOutQueriesOk() (*[]string, bool)`

GetFanOutQueriesOk returns a tuple with the FanOutQueries field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFanOutQueries

`func (o *PromptExecutionRecord) SetFanOutQueries(v []string)`

SetFanOutQueries sets FanOutQueries field to given value.


### SetFanOutQueriesNil

`func (o *PromptExecutionRecord) SetFanOutQueriesNil(b bool)`

 SetFanOutQueriesNil sets the value for FanOutQueries to be an explicit nil

### UnsetFanOutQueries
`func (o *PromptExecutionRecord) UnsetFanOutQueries()`

UnsetFanOutQueries ensures that no value is present for FanOutQueries, not even an explicit nil
### GetHasMention

`func (o *PromptExecutionRecord) GetHasMention() bool`

GetHasMention returns the HasMention field if non-nil, zero value otherwise.

### GetHasMentionOk

`func (o *PromptExecutionRecord) GetHasMentionOk() (*bool, bool)`

GetHasMentionOk returns a tuple with the HasMention field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHasMention

`func (o *PromptExecutionRecord) SetHasMention(v bool)`

SetHasMention sets HasMention field to given value.


### GetHasCitation

`func (o *PromptExecutionRecord) GetHasCitation() bool`

GetHasCitation returns the HasCitation field if non-nil, zero value otherwise.

### GetHasCitationOk

`func (o *PromptExecutionRecord) GetHasCitationOk() (*bool, bool)`

GetHasCitationOk returns a tuple with the HasCitation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHasCitation

`func (o *PromptExecutionRecord) SetHasCitation(v bool)`

SetHasCitation sets HasCitation field to given value.


### GetMentionsCount

`func (o *PromptExecutionRecord) GetMentionsCount() int32`

GetMentionsCount returns the MentionsCount field if non-nil, zero value otherwise.

### GetMentionsCountOk

`func (o *PromptExecutionRecord) GetMentionsCountOk() (*int32, bool)`

GetMentionsCountOk returns a tuple with the MentionsCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMentionsCount

`func (o *PromptExecutionRecord) SetMentionsCount(v int32)`

SetMentionsCount sets MentionsCount field to given value.


### GetCitationsCount

`func (o *PromptExecutionRecord) GetCitationsCount() int32`

GetCitationsCount returns the CitationsCount field if non-nil, zero value otherwise.

### GetCitationsCountOk

`func (o *PromptExecutionRecord) GetCitationsCountOk() (*int32, bool)`

GetCitationsCountOk returns a tuple with the CitationsCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCitationsCount

`func (o *PromptExecutionRecord) SetCitationsCount(v int32)`

SetCitationsCount sets CitationsCount field to given value.


### GetAppUrl

`func (o *PromptExecutionRecord) GetAppUrl() string`

GetAppUrl returns the AppUrl field if non-nil, zero value otherwise.

### GetAppUrlOk

`func (o *PromptExecutionRecord) GetAppUrlOk() (*string, bool)`

GetAppUrlOk returns a tuple with the AppUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAppUrl

`func (o *PromptExecutionRecord) SetAppUrl(v string)`

SetAppUrl sets AppUrl field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


