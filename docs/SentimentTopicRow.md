# SentimentTopicRow

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Mentions** | **int32** | Analyzed mentions | 
**Positive** | **int32** | Positive and very positive | 
**Neutral** | **int32** |  | 
**Negative** | **int32** | Negative and very negative | 
**PositivePct** | **float32** |  | 
**NeutralPct** | **float32** |  | 
**NegativePct** | **float32** |  | 
**NetScore** | **float32** | Positive minus negative, divided by mentions, times 100 | 
**Topic** | **string** |  | 

## Methods

### NewSentimentTopicRow

`func NewSentimentTopicRow(mentions int32, positive int32, neutral int32, negative int32, positivePct float32, neutralPct float32, negativePct float32, netScore float32, topic string, ) *SentimentTopicRow`

NewSentimentTopicRow instantiates a new SentimentTopicRow object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSentimentTopicRowWithDefaults

`func NewSentimentTopicRowWithDefaults() *SentimentTopicRow`

NewSentimentTopicRowWithDefaults instantiates a new SentimentTopicRow object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMentions

`func (o *SentimentTopicRow) GetMentions() int32`

GetMentions returns the Mentions field if non-nil, zero value otherwise.

### GetMentionsOk

`func (o *SentimentTopicRow) GetMentionsOk() (*int32, bool)`

GetMentionsOk returns a tuple with the Mentions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMentions

`func (o *SentimentTopicRow) SetMentions(v int32)`

SetMentions sets Mentions field to given value.


### GetPositive

`func (o *SentimentTopicRow) GetPositive() int32`

GetPositive returns the Positive field if non-nil, zero value otherwise.

### GetPositiveOk

`func (o *SentimentTopicRow) GetPositiveOk() (*int32, bool)`

GetPositiveOk returns a tuple with the Positive field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPositive

`func (o *SentimentTopicRow) SetPositive(v int32)`

SetPositive sets Positive field to given value.


### GetNeutral

`func (o *SentimentTopicRow) GetNeutral() int32`

GetNeutral returns the Neutral field if non-nil, zero value otherwise.

### GetNeutralOk

`func (o *SentimentTopicRow) GetNeutralOk() (*int32, bool)`

GetNeutralOk returns a tuple with the Neutral field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNeutral

`func (o *SentimentTopicRow) SetNeutral(v int32)`

SetNeutral sets Neutral field to given value.


### GetNegative

`func (o *SentimentTopicRow) GetNegative() int32`

GetNegative returns the Negative field if non-nil, zero value otherwise.

### GetNegativeOk

`func (o *SentimentTopicRow) GetNegativeOk() (*int32, bool)`

GetNegativeOk returns a tuple with the Negative field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNegative

`func (o *SentimentTopicRow) SetNegative(v int32)`

SetNegative sets Negative field to given value.


### GetPositivePct

`func (o *SentimentTopicRow) GetPositivePct() float32`

GetPositivePct returns the PositivePct field if non-nil, zero value otherwise.

### GetPositivePctOk

`func (o *SentimentTopicRow) GetPositivePctOk() (*float32, bool)`

GetPositivePctOk returns a tuple with the PositivePct field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPositivePct

`func (o *SentimentTopicRow) SetPositivePct(v float32)`

SetPositivePct sets PositivePct field to given value.


### GetNeutralPct

`func (o *SentimentTopicRow) GetNeutralPct() float32`

GetNeutralPct returns the NeutralPct field if non-nil, zero value otherwise.

### GetNeutralPctOk

`func (o *SentimentTopicRow) GetNeutralPctOk() (*float32, bool)`

GetNeutralPctOk returns a tuple with the NeutralPct field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNeutralPct

`func (o *SentimentTopicRow) SetNeutralPct(v float32)`

SetNeutralPct sets NeutralPct field to given value.


### GetNegativePct

`func (o *SentimentTopicRow) GetNegativePct() float32`

GetNegativePct returns the NegativePct field if non-nil, zero value otherwise.

### GetNegativePctOk

`func (o *SentimentTopicRow) GetNegativePctOk() (*float32, bool)`

GetNegativePctOk returns a tuple with the NegativePct field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNegativePct

`func (o *SentimentTopicRow) SetNegativePct(v float32)`

SetNegativePct sets NegativePct field to given value.


### GetNetScore

`func (o *SentimentTopicRow) GetNetScore() float32`

GetNetScore returns the NetScore field if non-nil, zero value otherwise.

### GetNetScoreOk

`func (o *SentimentTopicRow) GetNetScoreOk() (*float32, bool)`

GetNetScoreOk returns a tuple with the NetScore field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNetScore

`func (o *SentimentTopicRow) SetNetScore(v float32)`

SetNetScore sets NetScore field to given value.


### GetTopic

`func (o *SentimentTopicRow) GetTopic() string`

GetTopic returns the Topic field if non-nil, zero value otherwise.

### GetTopicOk

`func (o *SentimentTopicRow) GetTopicOk() (*string, bool)`

GetTopicOk returns a tuple with the Topic field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTopic

`func (o *SentimentTopicRow) SetTopic(v string)`

SetTopic sets Topic field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


