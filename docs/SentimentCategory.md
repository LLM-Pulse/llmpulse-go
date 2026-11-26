# SentimentCategory

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Metric** | **string** | The metric key of the level (sentiment_&lt;key&gt;) | 
**Key** | **string** | very_positive, positive, neutral, negative or very_negative | 
**Label** | **string** |  | 
**Color** | **string** | Hex color the app shows the level in | 
**Score** | **float32** | Score of the level, from -1.0 (very_negative) to 1.0 (very_positive) | 

## Methods

### NewSentimentCategory

`func NewSentimentCategory(metric string, key string, label string, color string, score float32, ) *SentimentCategory`

NewSentimentCategory instantiates a new SentimentCategory object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSentimentCategoryWithDefaults

`func NewSentimentCategoryWithDefaults() *SentimentCategory`

NewSentimentCategoryWithDefaults instantiates a new SentimentCategory object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMetric

`func (o *SentimentCategory) GetMetric() string`

GetMetric returns the Metric field if non-nil, zero value otherwise.

### GetMetricOk

`func (o *SentimentCategory) GetMetricOk() (*string, bool)`

GetMetricOk returns a tuple with the Metric field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetric

`func (o *SentimentCategory) SetMetric(v string)`

SetMetric sets Metric field to given value.


### GetKey

`func (o *SentimentCategory) GetKey() string`

GetKey returns the Key field if non-nil, zero value otherwise.

### GetKeyOk

`func (o *SentimentCategory) GetKeyOk() (*string, bool)`

GetKeyOk returns a tuple with the Key field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKey

`func (o *SentimentCategory) SetKey(v string)`

SetKey sets Key field to given value.


### GetLabel

`func (o *SentimentCategory) GetLabel() string`

GetLabel returns the Label field if non-nil, zero value otherwise.

### GetLabelOk

`func (o *SentimentCategory) GetLabelOk() (*string, bool)`

GetLabelOk returns a tuple with the Label field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabel

`func (o *SentimentCategory) SetLabel(v string)`

SetLabel sets Label field to given value.


### GetColor

`func (o *SentimentCategory) GetColor() string`

GetColor returns the Color field if non-nil, zero value otherwise.

### GetColorOk

`func (o *SentimentCategory) GetColorOk() (*string, bool)`

GetColorOk returns a tuple with the Color field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetColor

`func (o *SentimentCategory) SetColor(v string)`

SetColor sets Color field to given value.


### GetScore

`func (o *SentimentCategory) GetScore() float32`

GetScore returns the Score field if non-nil, zero value otherwise.

### GetScoreOk

`func (o *SentimentCategory) GetScoreOk() (*float32, bool)`

GetScoreOk returns a tuple with the Score field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScore

`func (o *SentimentCategory) SetScore(v float32)`

SetScore sets Score field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


