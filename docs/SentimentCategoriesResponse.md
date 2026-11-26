# SentimentCategoriesResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ProjectId** | **int32** |  | 
**Sentiments** | [**[]SentimentCategory**](SentimentCategory.md) |  | 
**RequestId** | **string** |  | 

## Methods

### NewSentimentCategoriesResponse

`func NewSentimentCategoriesResponse(projectId int32, sentiments []SentimentCategory, requestId string, ) *SentimentCategoriesResponse`

NewSentimentCategoriesResponse instantiates a new SentimentCategoriesResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSentimentCategoriesResponseWithDefaults

`func NewSentimentCategoriesResponseWithDefaults() *SentimentCategoriesResponse`

NewSentimentCategoriesResponseWithDefaults instantiates a new SentimentCategoriesResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProjectId

`func (o *SentimentCategoriesResponse) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *SentimentCategoriesResponse) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *SentimentCategoriesResponse) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.


### GetSentiments

`func (o *SentimentCategoriesResponse) GetSentiments() []SentimentCategory`

GetSentiments returns the Sentiments field if non-nil, zero value otherwise.

### GetSentimentsOk

`func (o *SentimentCategoriesResponse) GetSentimentsOk() (*[]SentimentCategory, bool)`

GetSentimentsOk returns a tuple with the Sentiments field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSentiments

`func (o *SentimentCategoriesResponse) SetSentiments(v []SentimentCategory)`

SetSentiments sets Sentiments field to given value.


### GetRequestId

`func (o *SentimentCategoriesResponse) GetRequestId() string`

GetRequestId returns the RequestId field if non-nil, zero value otherwise.

### GetRequestIdOk

`func (o *SentimentCategoriesResponse) GetRequestIdOk() (*string, bool)`

GetRequestIdOk returns a tuple with the RequestId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestId

`func (o *SentimentCategoriesResponse) SetRequestId(v string)`

SetRequestId sets RequestId field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


