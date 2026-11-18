# AiModelDeclinedAnswersResponseSummary

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
**LastDeclinedAt** | Pointer to **NullableTime** | When the latest declined answer of the window was created; null when none was declined | [optional] 

## Methods

### NewAiModelDeclinedAnswersResponseSummary

`func NewAiModelDeclinedAnswersResponseSummary() *AiModelDeclinedAnswersResponseSummary`

NewAiModelDeclinedAnswersResponseSummary instantiates a new AiModelDeclinedAnswersResponseSummary object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAiModelDeclinedAnswersResponseSummaryWithDefaults

`func NewAiModelDeclinedAnswersResponseSummaryWithDefaults() *AiModelDeclinedAnswersResponseSummary`

NewAiModelDeclinedAnswersResponseSummaryWithDefaults instantiates a new AiModelDeclinedAnswersResponseSummary object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAnswers

`func (o *AiModelDeclinedAnswersResponseSummary) GetAnswers() int32`

GetAnswers returns the Answers field if non-nil, zero value otherwise.

### GetAnswersOk

`func (o *AiModelDeclinedAnswersResponseSummary) GetAnswersOk() (*int32, bool)`

GetAnswersOk returns a tuple with the Answers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAnswers

`func (o *AiModelDeclinedAnswersResponseSummary) SetAnswers(v int32)`

SetAnswers sets Answers field to given value.

### HasAnswers

`func (o *AiModelDeclinedAnswersResponseSummary) HasAnswers() bool`

HasAnswers returns a boolean if a field has been set.

### GetDeclined

`func (o *AiModelDeclinedAnswersResponseSummary) GetDeclined() int32`

GetDeclined returns the Declined field if non-nil, zero value otherwise.

### GetDeclinedOk

`func (o *AiModelDeclinedAnswersResponseSummary) GetDeclinedOk() (*int32, bool)`

GetDeclinedOk returns a tuple with the Declined field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeclined

`func (o *AiModelDeclinedAnswersResponseSummary) SetDeclined(v int32)`

SetDeclined sets Declined field to given value.

### HasDeclined

`func (o *AiModelDeclinedAnswersResponseSummary) HasDeclined() bool`

HasDeclined returns a boolean if a field has been set.

### GetDeclineRate

`func (o *AiModelDeclinedAnswersResponseSummary) GetDeclineRate() float32`

GetDeclineRate returns the DeclineRate field if non-nil, zero value otherwise.

### GetDeclineRateOk

`func (o *AiModelDeclinedAnswersResponseSummary) GetDeclineRateOk() (*float32, bool)`

GetDeclineRateOk returns a tuple with the DeclineRate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeclineRate

`func (o *AiModelDeclinedAnswersResponseSummary) SetDeclineRate(v float32)`

SetDeclineRate sets DeclineRate field to given value.

### HasDeclineRate

`func (o *AiModelDeclinedAnswersResponseSummary) HasDeclineRate() bool`

HasDeclineRate returns a boolean if a field has been set.

### SetDeclineRateNil

`func (o *AiModelDeclinedAnswersResponseSummary) SetDeclineRateNil(b bool)`

 SetDeclineRateNil sets the value for DeclineRate to be an explicit nil

### UnsetDeclineRate
`func (o *AiModelDeclinedAnswersResponseSummary) UnsetDeclineRate()`

UnsetDeclineRate ensures that no value is present for DeclineRate, not even an explicit nil
### GetSafetyFilter

`func (o *AiModelDeclinedAnswersResponseSummary) GetSafetyFilter() int32`

GetSafetyFilter returns the SafetyFilter field if non-nil, zero value otherwise.

### GetSafetyFilterOk

`func (o *AiModelDeclinedAnswersResponseSummary) GetSafetyFilterOk() (*int32, bool)`

GetSafetyFilterOk returns a tuple with the SafetyFilter field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSafetyFilter

`func (o *AiModelDeclinedAnswersResponseSummary) SetSafetyFilter(v int32)`

SetSafetyFilter sets SafetyFilter field to given value.

### HasSafetyFilter

`func (o *AiModelDeclinedAnswersResponseSummary) HasSafetyFilter() bool`

HasSafetyFilter returns a boolean if a field has been set.

### GetSafetyFilterRate

`func (o *AiModelDeclinedAnswersResponseSummary) GetSafetyFilterRate() float32`

GetSafetyFilterRate returns the SafetyFilterRate field if non-nil, zero value otherwise.

### GetSafetyFilterRateOk

`func (o *AiModelDeclinedAnswersResponseSummary) GetSafetyFilterRateOk() (*float32, bool)`

GetSafetyFilterRateOk returns a tuple with the SafetyFilterRate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSafetyFilterRate

`func (o *AiModelDeclinedAnswersResponseSummary) SetSafetyFilterRate(v float32)`

SetSafetyFilterRate sets SafetyFilterRate field to given value.

### HasSafetyFilterRate

`func (o *AiModelDeclinedAnswersResponseSummary) HasSafetyFilterRate() bool`

HasSafetyFilterRate returns a boolean if a field has been set.

### SetSafetyFilterRateNil

`func (o *AiModelDeclinedAnswersResponseSummary) SetSafetyFilterRateNil(b bool)`

 SetSafetyFilterRateNil sets the value for SafetyFilterRate to be an explicit nil

### UnsetSafetyFilterRate
`func (o *AiModelDeclinedAnswersResponseSummary) UnsetSafetyFilterRate()`

UnsetSafetyFilterRate ensures that no value is present for SafetyFilterRate, not even an explicit nil
### GetTopicRefusal

`func (o *AiModelDeclinedAnswersResponseSummary) GetTopicRefusal() int32`

GetTopicRefusal returns the TopicRefusal field if non-nil, zero value otherwise.

### GetTopicRefusalOk

`func (o *AiModelDeclinedAnswersResponseSummary) GetTopicRefusalOk() (*int32, bool)`

GetTopicRefusalOk returns a tuple with the TopicRefusal field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTopicRefusal

`func (o *AiModelDeclinedAnswersResponseSummary) SetTopicRefusal(v int32)`

SetTopicRefusal sets TopicRefusal field to given value.

### HasTopicRefusal

`func (o *AiModelDeclinedAnswersResponseSummary) HasTopicRefusal() bool`

HasTopicRefusal returns a boolean if a field has been set.

### GetTopicRefusalRate

`func (o *AiModelDeclinedAnswersResponseSummary) GetTopicRefusalRate() float32`

GetTopicRefusalRate returns the TopicRefusalRate field if non-nil, zero value otherwise.

### GetTopicRefusalRateOk

`func (o *AiModelDeclinedAnswersResponseSummary) GetTopicRefusalRateOk() (*float32, bool)`

GetTopicRefusalRateOk returns a tuple with the TopicRefusalRate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTopicRefusalRate

`func (o *AiModelDeclinedAnswersResponseSummary) SetTopicRefusalRate(v float32)`

SetTopicRefusalRate sets TopicRefusalRate field to given value.

### HasTopicRefusalRate

`func (o *AiModelDeclinedAnswersResponseSummary) HasTopicRefusalRate() bool`

HasTopicRefusalRate returns a boolean if a field has been set.

### SetTopicRefusalRateNil

`func (o *AiModelDeclinedAnswersResponseSummary) SetTopicRefusalRateNil(b bool)`

 SetTopicRefusalRateNil sets the value for TopicRefusalRate to be an explicit nil

### UnsetTopicRefusalRate
`func (o *AiModelDeclinedAnswersResponseSummary) UnsetTopicRefusalRate()`

UnsetTopicRefusalRate ensures that no value is present for TopicRefusalRate, not even an explicit nil
### GetLastDeclinedAt

`func (o *AiModelDeclinedAnswersResponseSummary) GetLastDeclinedAt() time.Time`

GetLastDeclinedAt returns the LastDeclinedAt field if non-nil, zero value otherwise.

### GetLastDeclinedAtOk

`func (o *AiModelDeclinedAnswersResponseSummary) GetLastDeclinedAtOk() (*time.Time, bool)`

GetLastDeclinedAtOk returns a tuple with the LastDeclinedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastDeclinedAt

`func (o *AiModelDeclinedAnswersResponseSummary) SetLastDeclinedAt(v time.Time)`

SetLastDeclinedAt sets LastDeclinedAt field to given value.

### HasLastDeclinedAt

`func (o *AiModelDeclinedAnswersResponseSummary) HasLastDeclinedAt() bool`

HasLastDeclinedAt returns a boolean if a field has been set.

### SetLastDeclinedAtNil

`func (o *AiModelDeclinedAnswersResponseSummary) SetLastDeclinedAtNil(b bool)`

 SetLastDeclinedAtNil sets the value for LastDeclinedAt to be an explicit nil

### UnsetLastDeclinedAt
`func (o *AiModelDeclinedAnswersResponseSummary) UnsetLastDeclinedAt()`

UnsetLastDeclinedAt ensures that no value is present for LastDeclinedAt, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


