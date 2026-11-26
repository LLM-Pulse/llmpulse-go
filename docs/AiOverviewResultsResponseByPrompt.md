# AiOverviewResultsResponseByPrompt

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Page** | **int32** |  | 
**PerPage** | **int32** |  | 
**Total** | **int32** | Prompts with an AI Overview run in the window | 
**Data** | [**[]AiOverviewResultsResponseByPromptDataInner**](AiOverviewResultsResponseByPromptDataInner.md) |  | 

## Methods

### NewAiOverviewResultsResponseByPrompt

`func NewAiOverviewResultsResponseByPrompt(page int32, perPage int32, total int32, data []AiOverviewResultsResponseByPromptDataInner, ) *AiOverviewResultsResponseByPrompt`

NewAiOverviewResultsResponseByPrompt instantiates a new AiOverviewResultsResponseByPrompt object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAiOverviewResultsResponseByPromptWithDefaults

`func NewAiOverviewResultsResponseByPromptWithDefaults() *AiOverviewResultsResponseByPrompt`

NewAiOverviewResultsResponseByPromptWithDefaults instantiates a new AiOverviewResultsResponseByPrompt object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPage

`func (o *AiOverviewResultsResponseByPrompt) GetPage() int32`

GetPage returns the Page field if non-nil, zero value otherwise.

### GetPageOk

`func (o *AiOverviewResultsResponseByPrompt) GetPageOk() (*int32, bool)`

GetPageOk returns a tuple with the Page field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPage

`func (o *AiOverviewResultsResponseByPrompt) SetPage(v int32)`

SetPage sets Page field to given value.


### GetPerPage

`func (o *AiOverviewResultsResponseByPrompt) GetPerPage() int32`

GetPerPage returns the PerPage field if non-nil, zero value otherwise.

### GetPerPageOk

`func (o *AiOverviewResultsResponseByPrompt) GetPerPageOk() (*int32, bool)`

GetPerPageOk returns a tuple with the PerPage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPerPage

`func (o *AiOverviewResultsResponseByPrompt) SetPerPage(v int32)`

SetPerPage sets PerPage field to given value.


### GetTotal

`func (o *AiOverviewResultsResponseByPrompt) GetTotal() int32`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *AiOverviewResultsResponseByPrompt) GetTotalOk() (*int32, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *AiOverviewResultsResponseByPrompt) SetTotal(v int32)`

SetTotal sets Total field to given value.


### GetData

`func (o *AiOverviewResultsResponseByPrompt) GetData() []AiOverviewResultsResponseByPromptDataInner`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *AiOverviewResultsResponseByPrompt) GetDataOk() (*[]AiOverviewResultsResponseByPromptDataInner, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *AiOverviewResultsResponseByPrompt) SetData(v []AiOverviewResultsResponseByPromptDataInner)`

SetData sets Data field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


