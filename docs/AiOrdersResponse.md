# AiOrdersResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ProjectId** | **int32** |  | 
**Platform** | **string** |  | 
**Currency** | **NullableString** | ISO 4217 code of the most recent stored day; null when the window holds no stored order | 
**From** | **string** |  | 
**To** | **string** |  | 
**Totals** | [**AiOrdersResponseTotals**](AiOrdersResponseTotals.md) |  | 
**BySource** | [**[]AiOrdersResponseBySourceInner**](AiOrdersResponseBySourceInner.md) | One row per AI assistant, highest revenue first | 
**Series** | [**[]AiOrdersResponseSeriesInner**](AiOrdersResponseSeriesInner.md) | Days that have stored orders, oldest first | 
**RequestId** | **string** |  | 

## Methods

### NewAiOrdersResponse

`func NewAiOrdersResponse(projectId int32, platform string, currency NullableString, from string, to string, totals AiOrdersResponseTotals, bySource []AiOrdersResponseBySourceInner, series []AiOrdersResponseSeriesInner, requestId string, ) *AiOrdersResponse`

NewAiOrdersResponse instantiates a new AiOrdersResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAiOrdersResponseWithDefaults

`func NewAiOrdersResponseWithDefaults() *AiOrdersResponse`

NewAiOrdersResponseWithDefaults instantiates a new AiOrdersResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProjectId

`func (o *AiOrdersResponse) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *AiOrdersResponse) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *AiOrdersResponse) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.


### GetPlatform

`func (o *AiOrdersResponse) GetPlatform() string`

GetPlatform returns the Platform field if non-nil, zero value otherwise.

### GetPlatformOk

`func (o *AiOrdersResponse) GetPlatformOk() (*string, bool)`

GetPlatformOk returns a tuple with the Platform field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlatform

`func (o *AiOrdersResponse) SetPlatform(v string)`

SetPlatform sets Platform field to given value.


### GetCurrency

`func (o *AiOrdersResponse) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *AiOrdersResponse) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *AiOrdersResponse) SetCurrency(v string)`

SetCurrency sets Currency field to given value.


### SetCurrencyNil

`func (o *AiOrdersResponse) SetCurrencyNil(b bool)`

 SetCurrencyNil sets the value for Currency to be an explicit nil

### UnsetCurrency
`func (o *AiOrdersResponse) UnsetCurrency()`

UnsetCurrency ensures that no value is present for Currency, not even an explicit nil
### GetFrom

`func (o *AiOrdersResponse) GetFrom() string`

GetFrom returns the From field if non-nil, zero value otherwise.

### GetFromOk

`func (o *AiOrdersResponse) GetFromOk() (*string, bool)`

GetFromOk returns a tuple with the From field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFrom

`func (o *AiOrdersResponse) SetFrom(v string)`

SetFrom sets From field to given value.


### GetTo

`func (o *AiOrdersResponse) GetTo() string`

GetTo returns the To field if non-nil, zero value otherwise.

### GetToOk

`func (o *AiOrdersResponse) GetToOk() (*string, bool)`

GetToOk returns a tuple with the To field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTo

`func (o *AiOrdersResponse) SetTo(v string)`

SetTo sets To field to given value.


### GetTotals

`func (o *AiOrdersResponse) GetTotals() AiOrdersResponseTotals`

GetTotals returns the Totals field if non-nil, zero value otherwise.

### GetTotalsOk

`func (o *AiOrdersResponse) GetTotalsOk() (*AiOrdersResponseTotals, bool)`

GetTotalsOk returns a tuple with the Totals field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotals

`func (o *AiOrdersResponse) SetTotals(v AiOrdersResponseTotals)`

SetTotals sets Totals field to given value.


### GetBySource

`func (o *AiOrdersResponse) GetBySource() []AiOrdersResponseBySourceInner`

GetBySource returns the BySource field if non-nil, zero value otherwise.

### GetBySourceOk

`func (o *AiOrdersResponse) GetBySourceOk() (*[]AiOrdersResponseBySourceInner, bool)`

GetBySourceOk returns a tuple with the BySource field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBySource

`func (o *AiOrdersResponse) SetBySource(v []AiOrdersResponseBySourceInner)`

SetBySource sets BySource field to given value.


### GetSeries

`func (o *AiOrdersResponse) GetSeries() []AiOrdersResponseSeriesInner`

GetSeries returns the Series field if non-nil, zero value otherwise.

### GetSeriesOk

`func (o *AiOrdersResponse) GetSeriesOk() (*[]AiOrdersResponseSeriesInner, bool)`

GetSeriesOk returns a tuple with the Series field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSeries

`func (o *AiOrdersResponse) SetSeries(v []AiOrdersResponseSeriesInner)`

SetSeries sets Series field to given value.


### GetRequestId

`func (o *AiOrdersResponse) GetRequestId() string`

GetRequestId returns the RequestId field if non-nil, zero value otherwise.

### GetRequestIdOk

`func (o *AiOrdersResponse) GetRequestIdOk() (*string, bool)`

GetRequestIdOk returns a tuple with the RequestId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestId

`func (o *AiOrdersResponse) SetRequestId(v string)`

SetRequestId sets RequestId field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


