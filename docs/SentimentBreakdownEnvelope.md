# SentimentBreakdownEnvelope

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**From** | **time.Time** |  | 
**To** | **time.Time** |  | 
**Brand** | [**SentimentBreakdownBrand**](SentimentBreakdownBrand.md) |  | 
**Sort** | **string** |  | 
**SortDir** | **string** |  | 

## Methods

### NewSentimentBreakdownEnvelope

`func NewSentimentBreakdownEnvelope(from time.Time, to time.Time, brand SentimentBreakdownBrand, sort string, sortDir string, ) *SentimentBreakdownEnvelope`

NewSentimentBreakdownEnvelope instantiates a new SentimentBreakdownEnvelope object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSentimentBreakdownEnvelopeWithDefaults

`func NewSentimentBreakdownEnvelopeWithDefaults() *SentimentBreakdownEnvelope`

NewSentimentBreakdownEnvelopeWithDefaults instantiates a new SentimentBreakdownEnvelope object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetFrom

`func (o *SentimentBreakdownEnvelope) GetFrom() time.Time`

GetFrom returns the From field if non-nil, zero value otherwise.

### GetFromOk

`func (o *SentimentBreakdownEnvelope) GetFromOk() (*time.Time, bool)`

GetFromOk returns a tuple with the From field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFrom

`func (o *SentimentBreakdownEnvelope) SetFrom(v time.Time)`

SetFrom sets From field to given value.


### GetTo

`func (o *SentimentBreakdownEnvelope) GetTo() time.Time`

GetTo returns the To field if non-nil, zero value otherwise.

### GetToOk

`func (o *SentimentBreakdownEnvelope) GetToOk() (*time.Time, bool)`

GetToOk returns a tuple with the To field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTo

`func (o *SentimentBreakdownEnvelope) SetTo(v time.Time)`

SetTo sets To field to given value.


### GetBrand

`func (o *SentimentBreakdownEnvelope) GetBrand() SentimentBreakdownBrand`

GetBrand returns the Brand field if non-nil, zero value otherwise.

### GetBrandOk

`func (o *SentimentBreakdownEnvelope) GetBrandOk() (*SentimentBreakdownBrand, bool)`

GetBrandOk returns a tuple with the Brand field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBrand

`func (o *SentimentBreakdownEnvelope) SetBrand(v SentimentBreakdownBrand)`

SetBrand sets Brand field to given value.


### GetSort

`func (o *SentimentBreakdownEnvelope) GetSort() string`

GetSort returns the Sort field if non-nil, zero value otherwise.

### GetSortOk

`func (o *SentimentBreakdownEnvelope) GetSortOk() (*string, bool)`

GetSortOk returns a tuple with the Sort field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSort

`func (o *SentimentBreakdownEnvelope) SetSort(v string)`

SetSort sets Sort field to given value.


### GetSortDir

`func (o *SentimentBreakdownEnvelope) GetSortDir() string`

GetSortDir returns the SortDir field if non-nil, zero value otherwise.

### GetSortDirOk

`func (o *SentimentBreakdownEnvelope) GetSortDirOk() (*string, bool)`

GetSortDirOk returns a tuple with the SortDir field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSortDir

`func (o *SentimentBreakdownEnvelope) SetSortDir(v string)`

SetSortDir sets SortDir field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


