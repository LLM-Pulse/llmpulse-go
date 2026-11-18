# AiModelDeclinedAnswersResponseByPromptDataInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Answers** | Pointer to **int32** | Finished runs of the model, declined ones included | [optional] 
**Declined** | Pointer to **int32** | Answers the model declined | [optional] 
**DeclineRate** | Pointer to **NullableFloat32** |  | [optional] 
**SafetyFilter** | Pointer to **int32** | Answers declined by the model&#39;s own safety filters | [optional] 
**SafetyFilterRate** | Pointer to **NullableFloat32** |  | [optional] 
**TopicRefusal** | Pointer to **int32** | Answers that declined the topic itself, such as tobacco, gambling or alcohol | [optional] 
**TopicRefusalRate** | Pointer to **NullableFloat32** |  | [optional] 
**PromptId** | Pointer to **int32** |  | [optional] 
**PromptText** | Pointer to **NullableString** |  | [optional] 
**LastDeclinedAt** | Pointer to **NullableTime** | When the prompt&#39;s latest declined answer of the window was created; null when none was declined | [optional] 

## Methods

### NewAiModelDeclinedAnswersResponseByPromptDataInner

`func NewAiModelDeclinedAnswersResponseByPromptDataInner() *AiModelDeclinedAnswersResponseByPromptDataInner`

NewAiModelDeclinedAnswersResponseByPromptDataInner instantiates a new AiModelDeclinedAnswersResponseByPromptDataInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAiModelDeclinedAnswersResponseByPromptDataInnerWithDefaults

`func NewAiModelDeclinedAnswersResponseByPromptDataInnerWithDefaults() *AiModelDeclinedAnswersResponseByPromptDataInner`

NewAiModelDeclinedAnswersResponseByPromptDataInnerWithDefaults instantiates a new AiModelDeclinedAnswersResponseByPromptDataInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAnswers

`func (o *AiModelDeclinedAnswersResponseByPromptDataInner) GetAnswers() int32`

GetAnswers returns the Answers field if non-nil, zero value otherwise.

### GetAnswersOk

`func (o *AiModelDeclinedAnswersResponseByPromptDataInner) GetAnswersOk() (*int32, bool)`

GetAnswersOk returns a tuple with the Answers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAnswers

`func (o *AiModelDeclinedAnswersResponseByPromptDataInner) SetAnswers(v int32)`

SetAnswers sets Answers field to given value.

### HasAnswers

`func (o *AiModelDeclinedAnswersResponseByPromptDataInner) HasAnswers() bool`

HasAnswers returns a boolean if a field has been set.

### GetDeclined

`func (o *AiModelDeclinedAnswersResponseByPromptDataInner) GetDeclined() int32`

GetDeclined returns the Declined field if non-nil, zero value otherwise.

### GetDeclinedOk

`func (o *AiModelDeclinedAnswersResponseByPromptDataInner) GetDeclinedOk() (*int32, bool)`

GetDeclinedOk returns a tuple with the Declined field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeclined

`func (o *AiModelDeclinedAnswersResponseByPromptDataInner) SetDeclined(v int32)`

SetDeclined sets Declined field to given value.

### HasDeclined

`func (o *AiModelDeclinedAnswersResponseByPromptDataInner) HasDeclined() bool`

HasDeclined returns a boolean if a field has been set.

### GetDeclineRate

`func (o *AiModelDeclinedAnswersResponseByPromptDataInner) GetDeclineRate() float32`

GetDeclineRate returns the DeclineRate field if non-nil, zero value otherwise.

### GetDeclineRateOk

`func (o *AiModelDeclinedAnswersResponseByPromptDataInner) GetDeclineRateOk() (*float32, bool)`

GetDeclineRateOk returns a tuple with the DeclineRate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeclineRate

`func (o *AiModelDeclinedAnswersResponseByPromptDataInner) SetDeclineRate(v float32)`

SetDeclineRate sets DeclineRate field to given value.

### HasDeclineRate

`func (o *AiModelDeclinedAnswersResponseByPromptDataInner) HasDeclineRate() bool`

HasDeclineRate returns a boolean if a field has been set.

### SetDeclineRateNil

`func (o *AiModelDeclinedAnswersResponseByPromptDataInner) SetDeclineRateNil(b bool)`

 SetDeclineRateNil sets the value for DeclineRate to be an explicit nil

### UnsetDeclineRate
`func (o *AiModelDeclinedAnswersResponseByPromptDataInner) UnsetDeclineRate()`

UnsetDeclineRate ensures that no value is present for DeclineRate, not even an explicit nil
### GetSafetyFilter

`func (o *AiModelDeclinedAnswersResponseByPromptDataInner) GetSafetyFilter() int32`

GetSafetyFilter returns the SafetyFilter field if non-nil, zero value otherwise.

### GetSafetyFilterOk

`func (o *AiModelDeclinedAnswersResponseByPromptDataInner) GetSafetyFilterOk() (*int32, bool)`

GetSafetyFilterOk returns a tuple with the SafetyFilter field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSafetyFilter

`func (o *AiModelDeclinedAnswersResponseByPromptDataInner) SetSafetyFilter(v int32)`

SetSafetyFilter sets SafetyFilter field to given value.

### HasSafetyFilter

`func (o *AiModelDeclinedAnswersResponseByPromptDataInner) HasSafetyFilter() bool`

HasSafetyFilter returns a boolean if a field has been set.

### GetSafetyFilterRate

`func (o *AiModelDeclinedAnswersResponseByPromptDataInner) GetSafetyFilterRate() float32`

GetSafetyFilterRate returns the SafetyFilterRate field if non-nil, zero value otherwise.

### GetSafetyFilterRateOk

`func (o *AiModelDeclinedAnswersResponseByPromptDataInner) GetSafetyFilterRateOk() (*float32, bool)`

GetSafetyFilterRateOk returns a tuple with the SafetyFilterRate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSafetyFilterRate

`func (o *AiModelDeclinedAnswersResponseByPromptDataInner) SetSafetyFilterRate(v float32)`

SetSafetyFilterRate sets SafetyFilterRate field to given value.

### HasSafetyFilterRate

`func (o *AiModelDeclinedAnswersResponseByPromptDataInner) HasSafetyFilterRate() bool`

HasSafetyFilterRate returns a boolean if a field has been set.

### SetSafetyFilterRateNil

`func (o *AiModelDeclinedAnswersResponseByPromptDataInner) SetSafetyFilterRateNil(b bool)`

 SetSafetyFilterRateNil sets the value for SafetyFilterRate to be an explicit nil

### UnsetSafetyFilterRate
`func (o *AiModelDeclinedAnswersResponseByPromptDataInner) UnsetSafetyFilterRate()`

UnsetSafetyFilterRate ensures that no value is present for SafetyFilterRate, not even an explicit nil
### GetTopicRefusal

`func (o *AiModelDeclinedAnswersResponseByPromptDataInner) GetTopicRefusal() int32`

GetTopicRefusal returns the TopicRefusal field if non-nil, zero value otherwise.

### GetTopicRefusalOk

`func (o *AiModelDeclinedAnswersResponseByPromptDataInner) GetTopicRefusalOk() (*int32, bool)`

GetTopicRefusalOk returns a tuple with the TopicRefusal field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTopicRefusal

`func (o *AiModelDeclinedAnswersResponseByPromptDataInner) SetTopicRefusal(v int32)`

SetTopicRefusal sets TopicRefusal field to given value.

### HasTopicRefusal

`func (o *AiModelDeclinedAnswersResponseByPromptDataInner) HasTopicRefusal() bool`

HasTopicRefusal returns a boolean if a field has been set.

### GetTopicRefusalRate

`func (o *AiModelDeclinedAnswersResponseByPromptDataInner) GetTopicRefusalRate() float32`

GetTopicRefusalRate returns the TopicRefusalRate field if non-nil, zero value otherwise.

### GetTopicRefusalRateOk

`func (o *AiModelDeclinedAnswersResponseByPromptDataInner) GetTopicRefusalRateOk() (*float32, bool)`

GetTopicRefusalRateOk returns a tuple with the TopicRefusalRate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTopicRefusalRate

`func (o *AiModelDeclinedAnswersResponseByPromptDataInner) SetTopicRefusalRate(v float32)`

SetTopicRefusalRate sets TopicRefusalRate field to given value.

### HasTopicRefusalRate

`func (o *AiModelDeclinedAnswersResponseByPromptDataInner) HasTopicRefusalRate() bool`

HasTopicRefusalRate returns a boolean if a field has been set.

### SetTopicRefusalRateNil

`func (o *AiModelDeclinedAnswersResponseByPromptDataInner) SetTopicRefusalRateNil(b bool)`

 SetTopicRefusalRateNil sets the value for TopicRefusalRate to be an explicit nil

### UnsetTopicRefusalRate
`func (o *AiModelDeclinedAnswersResponseByPromptDataInner) UnsetTopicRefusalRate()`

UnsetTopicRefusalRate ensures that no value is present for TopicRefusalRate, not even an explicit nil
### GetPromptId

`func (o *AiModelDeclinedAnswersResponseByPromptDataInner) GetPromptId() int32`

GetPromptId returns the PromptId field if non-nil, zero value otherwise.

### GetPromptIdOk

`func (o *AiModelDeclinedAnswersResponseByPromptDataInner) GetPromptIdOk() (*int32, bool)`

GetPromptIdOk returns a tuple with the PromptId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPromptId

`func (o *AiModelDeclinedAnswersResponseByPromptDataInner) SetPromptId(v int32)`

SetPromptId sets PromptId field to given value.

### HasPromptId

`func (o *AiModelDeclinedAnswersResponseByPromptDataInner) HasPromptId() bool`

HasPromptId returns a boolean if a field has been set.

### GetPromptText

`func (o *AiModelDeclinedAnswersResponseByPromptDataInner) GetPromptText() string`

GetPromptText returns the PromptText field if non-nil, zero value otherwise.

### GetPromptTextOk

`func (o *AiModelDeclinedAnswersResponseByPromptDataInner) GetPromptTextOk() (*string, bool)`

GetPromptTextOk returns a tuple with the PromptText field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPromptText

`func (o *AiModelDeclinedAnswersResponseByPromptDataInner) SetPromptText(v string)`

SetPromptText sets PromptText field to given value.

### HasPromptText

`func (o *AiModelDeclinedAnswersResponseByPromptDataInner) HasPromptText() bool`

HasPromptText returns a boolean if a field has been set.

### SetPromptTextNil

`func (o *AiModelDeclinedAnswersResponseByPromptDataInner) SetPromptTextNil(b bool)`

 SetPromptTextNil sets the value for PromptText to be an explicit nil

### UnsetPromptText
`func (o *AiModelDeclinedAnswersResponseByPromptDataInner) UnsetPromptText()`

UnsetPromptText ensures that no value is present for PromptText, not even an explicit nil
### GetLastDeclinedAt

`func (o *AiModelDeclinedAnswersResponseByPromptDataInner) GetLastDeclinedAt() time.Time`

GetLastDeclinedAt returns the LastDeclinedAt field if non-nil, zero value otherwise.

### GetLastDeclinedAtOk

`func (o *AiModelDeclinedAnswersResponseByPromptDataInner) GetLastDeclinedAtOk() (*time.Time, bool)`

GetLastDeclinedAtOk returns a tuple with the LastDeclinedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastDeclinedAt

`func (o *AiModelDeclinedAnswersResponseByPromptDataInner) SetLastDeclinedAt(v time.Time)`

SetLastDeclinedAt sets LastDeclinedAt field to given value.

### HasLastDeclinedAt

`func (o *AiModelDeclinedAnswersResponseByPromptDataInner) HasLastDeclinedAt() bool`

HasLastDeclinedAt returns a boolean if a field has been set.

### SetLastDeclinedAtNil

`func (o *AiModelDeclinedAnswersResponseByPromptDataInner) SetLastDeclinedAtNil(b bool)`

 SetLastDeclinedAtNil sets the value for LastDeclinedAt to be an explicit nil

### UnsetLastDeclinedAt
`func (o *AiModelDeclinedAnswersResponseByPromptDataInner) UnsetLastDeclinedAt()`

UnsetLastDeclinedAt ensures that no value is present for LastDeclinedAt, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


