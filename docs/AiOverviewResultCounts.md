# AiOverviewResultCounts

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**TotalResponses** | **int32** | AI Overview runs in the window | 
**ResponsesWithResults** | **int32** | Runs that returned an AI Overview | 
**ResultRate** | **float32** |  | 

## Methods

### NewAiOverviewResultCounts

`func NewAiOverviewResultCounts(totalResponses int32, responsesWithResults int32, resultRate float32, ) *AiOverviewResultCounts`

NewAiOverviewResultCounts instantiates a new AiOverviewResultCounts object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAiOverviewResultCountsWithDefaults

`func NewAiOverviewResultCountsWithDefaults() *AiOverviewResultCounts`

NewAiOverviewResultCountsWithDefaults instantiates a new AiOverviewResultCounts object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTotalResponses

`func (o *AiOverviewResultCounts) GetTotalResponses() int32`

GetTotalResponses returns the TotalResponses field if non-nil, zero value otherwise.

### GetTotalResponsesOk

`func (o *AiOverviewResultCounts) GetTotalResponsesOk() (*int32, bool)`

GetTotalResponsesOk returns a tuple with the TotalResponses field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalResponses

`func (o *AiOverviewResultCounts) SetTotalResponses(v int32)`

SetTotalResponses sets TotalResponses field to given value.


### GetResponsesWithResults

`func (o *AiOverviewResultCounts) GetResponsesWithResults() int32`

GetResponsesWithResults returns the ResponsesWithResults field if non-nil, zero value otherwise.

### GetResponsesWithResultsOk

`func (o *AiOverviewResultCounts) GetResponsesWithResultsOk() (*int32, bool)`

GetResponsesWithResultsOk returns a tuple with the ResponsesWithResults field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResponsesWithResults

`func (o *AiOverviewResultCounts) SetResponsesWithResults(v int32)`

SetResponsesWithResults sets ResponsesWithResults field to given value.


### GetResultRate

`func (o *AiOverviewResultCounts) GetResultRate() float32`

GetResultRate returns the ResultRate field if non-nil, zero value otherwise.

### GetResultRateOk

`func (o *AiOverviewResultCounts) GetResultRateOk() (*float32, bool)`

GetResultRateOk returns a tuple with the ResultRate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResultRate

`func (o *AiOverviewResultCounts) SetResultRate(v float32)`

SetResultRate sets ResultRate field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


