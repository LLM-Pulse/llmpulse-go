# AnswerRecord

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **int32** |  | 
**PromptId** | **int32** |  | 
**PromptText** | **string** |  | 
**Model** | **string** |  | 
**ExecutedAt** | **NullableTime** |  | 
**DurationMs** | **NullableFloat32** | Milliseconds our pipeline spent processing the collected answer, rounded to one decimal place | 
**NoResult** | **bool** | True for a sentinel non-answer (no answer could be collected after all retries, or the model declined to answer, today only Gemini); excluded from platform metrics | 
**NoResultReason** | Pointer to **string** | Present only when no_result is true. declined &#x3D; the model declined to answer and response holds its reply; no_answer &#x3D; no answer could be collected | [optional] 
**MentionsCount** | **int32** | Mentions of your brand in the answer | 
**CitationsCount** | **int32** | Citations of your brand in the answer | 
**AppUrl** | **string** | Opens this answer in the app. The link names its project, so it opens there for any user with access to that project | 
**Response** | Pointer to **string** | The answer text, cut to 10,000 characters (without query) | [optional] 
**ResponseTruncated** | Pointer to **bool** | Whether response was cut (without query) | [optional] 
**Snippet** | Pointer to **string** | The text around the first match (with query) | [optional] 
**MatchCount** | Pointer to **int32** | Matches of query in the answer (with query) | [optional] 

## Methods

### NewAnswerRecord

`func NewAnswerRecord(id int32, promptId int32, promptText string, model string, executedAt NullableTime, durationMs NullableFloat32, noResult bool, mentionsCount int32, citationsCount int32, appUrl string, ) *AnswerRecord`

NewAnswerRecord instantiates a new AnswerRecord object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAnswerRecordWithDefaults

`func NewAnswerRecordWithDefaults() *AnswerRecord`

NewAnswerRecordWithDefaults instantiates a new AnswerRecord object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *AnswerRecord) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *AnswerRecord) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *AnswerRecord) SetId(v int32)`

SetId sets Id field to given value.


### GetPromptId

`func (o *AnswerRecord) GetPromptId() int32`

GetPromptId returns the PromptId field if non-nil, zero value otherwise.

### GetPromptIdOk

`func (o *AnswerRecord) GetPromptIdOk() (*int32, bool)`

GetPromptIdOk returns a tuple with the PromptId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPromptId

`func (o *AnswerRecord) SetPromptId(v int32)`

SetPromptId sets PromptId field to given value.


### GetPromptText

`func (o *AnswerRecord) GetPromptText() string`

GetPromptText returns the PromptText field if non-nil, zero value otherwise.

### GetPromptTextOk

`func (o *AnswerRecord) GetPromptTextOk() (*string, bool)`

GetPromptTextOk returns a tuple with the PromptText field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPromptText

`func (o *AnswerRecord) SetPromptText(v string)`

SetPromptText sets PromptText field to given value.


### GetModel

`func (o *AnswerRecord) GetModel() string`

GetModel returns the Model field if non-nil, zero value otherwise.

### GetModelOk

`func (o *AnswerRecord) GetModelOk() (*string, bool)`

GetModelOk returns a tuple with the Model field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModel

`func (o *AnswerRecord) SetModel(v string)`

SetModel sets Model field to given value.


### GetExecutedAt

`func (o *AnswerRecord) GetExecutedAt() time.Time`

GetExecutedAt returns the ExecutedAt field if non-nil, zero value otherwise.

### GetExecutedAtOk

`func (o *AnswerRecord) GetExecutedAtOk() (*time.Time, bool)`

GetExecutedAtOk returns a tuple with the ExecutedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExecutedAt

`func (o *AnswerRecord) SetExecutedAt(v time.Time)`

SetExecutedAt sets ExecutedAt field to given value.


### SetExecutedAtNil

`func (o *AnswerRecord) SetExecutedAtNil(b bool)`

 SetExecutedAtNil sets the value for ExecutedAt to be an explicit nil

### UnsetExecutedAt
`func (o *AnswerRecord) UnsetExecutedAt()`

UnsetExecutedAt ensures that no value is present for ExecutedAt, not even an explicit nil
### GetDurationMs

`func (o *AnswerRecord) GetDurationMs() float32`

GetDurationMs returns the DurationMs field if non-nil, zero value otherwise.

### GetDurationMsOk

`func (o *AnswerRecord) GetDurationMsOk() (*float32, bool)`

GetDurationMsOk returns a tuple with the DurationMs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDurationMs

`func (o *AnswerRecord) SetDurationMs(v float32)`

SetDurationMs sets DurationMs field to given value.


### SetDurationMsNil

`func (o *AnswerRecord) SetDurationMsNil(b bool)`

 SetDurationMsNil sets the value for DurationMs to be an explicit nil

### UnsetDurationMs
`func (o *AnswerRecord) UnsetDurationMs()`

UnsetDurationMs ensures that no value is present for DurationMs, not even an explicit nil
### GetNoResult

`func (o *AnswerRecord) GetNoResult() bool`

GetNoResult returns the NoResult field if non-nil, zero value otherwise.

### GetNoResultOk

`func (o *AnswerRecord) GetNoResultOk() (*bool, bool)`

GetNoResultOk returns a tuple with the NoResult field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNoResult

`func (o *AnswerRecord) SetNoResult(v bool)`

SetNoResult sets NoResult field to given value.


### GetNoResultReason

`func (o *AnswerRecord) GetNoResultReason() string`

GetNoResultReason returns the NoResultReason field if non-nil, zero value otherwise.

### GetNoResultReasonOk

`func (o *AnswerRecord) GetNoResultReasonOk() (*string, bool)`

GetNoResultReasonOk returns a tuple with the NoResultReason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNoResultReason

`func (o *AnswerRecord) SetNoResultReason(v string)`

SetNoResultReason sets NoResultReason field to given value.

### HasNoResultReason

`func (o *AnswerRecord) HasNoResultReason() bool`

HasNoResultReason returns a boolean if a field has been set.

### GetMentionsCount

`func (o *AnswerRecord) GetMentionsCount() int32`

GetMentionsCount returns the MentionsCount field if non-nil, zero value otherwise.

### GetMentionsCountOk

`func (o *AnswerRecord) GetMentionsCountOk() (*int32, bool)`

GetMentionsCountOk returns a tuple with the MentionsCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMentionsCount

`func (o *AnswerRecord) SetMentionsCount(v int32)`

SetMentionsCount sets MentionsCount field to given value.


### GetCitationsCount

`func (o *AnswerRecord) GetCitationsCount() int32`

GetCitationsCount returns the CitationsCount field if non-nil, zero value otherwise.

### GetCitationsCountOk

`func (o *AnswerRecord) GetCitationsCountOk() (*int32, bool)`

GetCitationsCountOk returns a tuple with the CitationsCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCitationsCount

`func (o *AnswerRecord) SetCitationsCount(v int32)`

SetCitationsCount sets CitationsCount field to given value.


### GetAppUrl

`func (o *AnswerRecord) GetAppUrl() string`

GetAppUrl returns the AppUrl field if non-nil, zero value otherwise.

### GetAppUrlOk

`func (o *AnswerRecord) GetAppUrlOk() (*string, bool)`

GetAppUrlOk returns a tuple with the AppUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAppUrl

`func (o *AnswerRecord) SetAppUrl(v string)`

SetAppUrl sets AppUrl field to given value.


### GetResponse

`func (o *AnswerRecord) GetResponse() string`

GetResponse returns the Response field if non-nil, zero value otherwise.

### GetResponseOk

`func (o *AnswerRecord) GetResponseOk() (*string, bool)`

GetResponseOk returns a tuple with the Response field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResponse

`func (o *AnswerRecord) SetResponse(v string)`

SetResponse sets Response field to given value.

### HasResponse

`func (o *AnswerRecord) HasResponse() bool`

HasResponse returns a boolean if a field has been set.

### GetResponseTruncated

`func (o *AnswerRecord) GetResponseTruncated() bool`

GetResponseTruncated returns the ResponseTruncated field if non-nil, zero value otherwise.

### GetResponseTruncatedOk

`func (o *AnswerRecord) GetResponseTruncatedOk() (*bool, bool)`

GetResponseTruncatedOk returns a tuple with the ResponseTruncated field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResponseTruncated

`func (o *AnswerRecord) SetResponseTruncated(v bool)`

SetResponseTruncated sets ResponseTruncated field to given value.

### HasResponseTruncated

`func (o *AnswerRecord) HasResponseTruncated() bool`

HasResponseTruncated returns a boolean if a field has been set.

### GetSnippet

`func (o *AnswerRecord) GetSnippet() string`

GetSnippet returns the Snippet field if non-nil, zero value otherwise.

### GetSnippetOk

`func (o *AnswerRecord) GetSnippetOk() (*string, bool)`

GetSnippetOk returns a tuple with the Snippet field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSnippet

`func (o *AnswerRecord) SetSnippet(v string)`

SetSnippet sets Snippet field to given value.

### HasSnippet

`func (o *AnswerRecord) HasSnippet() bool`

HasSnippet returns a boolean if a field has been set.

### GetMatchCount

`func (o *AnswerRecord) GetMatchCount() int32`

GetMatchCount returns the MatchCount field if non-nil, zero value otherwise.

### GetMatchCountOk

`func (o *AnswerRecord) GetMatchCountOk() (*int32, bool)`

GetMatchCountOk returns a tuple with the MatchCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMatchCount

`func (o *AnswerRecord) SetMatchCount(v int32)`

SetMatchCount sets MatchCount field to given value.

### HasMatchCount

`func (o *AnswerRecord) HasMatchCount() bool`

HasMatchCount returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


