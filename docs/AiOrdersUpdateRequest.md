# AiOrdersUpdateRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ProjectId** | **int32** |  | 
**Platform** | **string** |  | 
**Currency** | **string** | ISO 4217 code, e.g. EUR | 
**From** | **string** | First day of the window this push replaces | 
**To** | **string** | Last day of the window; at most 400 days after from | 
**Days** | [**[]AiOrdersUpdateRequestDaysInner**](AiOrdersUpdateRequestDaysInner.md) |  | 

## Methods

### NewAiOrdersUpdateRequest

`func NewAiOrdersUpdateRequest(projectId int32, platform string, currency string, from string, to string, days []AiOrdersUpdateRequestDaysInner, ) *AiOrdersUpdateRequest`

NewAiOrdersUpdateRequest instantiates a new AiOrdersUpdateRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAiOrdersUpdateRequestWithDefaults

`func NewAiOrdersUpdateRequestWithDefaults() *AiOrdersUpdateRequest`

NewAiOrdersUpdateRequestWithDefaults instantiates a new AiOrdersUpdateRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProjectId

`func (o *AiOrdersUpdateRequest) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *AiOrdersUpdateRequest) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *AiOrdersUpdateRequest) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.


### GetPlatform

`func (o *AiOrdersUpdateRequest) GetPlatform() string`

GetPlatform returns the Platform field if non-nil, zero value otherwise.

### GetPlatformOk

`func (o *AiOrdersUpdateRequest) GetPlatformOk() (*string, bool)`

GetPlatformOk returns a tuple with the Platform field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlatform

`func (o *AiOrdersUpdateRequest) SetPlatform(v string)`

SetPlatform sets Platform field to given value.


### GetCurrency

`func (o *AiOrdersUpdateRequest) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *AiOrdersUpdateRequest) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *AiOrdersUpdateRequest) SetCurrency(v string)`

SetCurrency sets Currency field to given value.


### GetFrom

`func (o *AiOrdersUpdateRequest) GetFrom() string`

GetFrom returns the From field if non-nil, zero value otherwise.

### GetFromOk

`func (o *AiOrdersUpdateRequest) GetFromOk() (*string, bool)`

GetFromOk returns a tuple with the From field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFrom

`func (o *AiOrdersUpdateRequest) SetFrom(v string)`

SetFrom sets From field to given value.


### GetTo

`func (o *AiOrdersUpdateRequest) GetTo() string`

GetTo returns the To field if non-nil, zero value otherwise.

### GetToOk

`func (o *AiOrdersUpdateRequest) GetToOk() (*string, bool)`

GetToOk returns a tuple with the To field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTo

`func (o *AiOrdersUpdateRequest) SetTo(v string)`

SetTo sets To field to given value.


### GetDays

`func (o *AiOrdersUpdateRequest) GetDays() []AiOrdersUpdateRequestDaysInner`

GetDays returns the Days field if non-nil, zero value otherwise.

### GetDaysOk

`func (o *AiOrdersUpdateRequest) GetDaysOk() (*[]AiOrdersUpdateRequestDaysInner, bool)`

GetDaysOk returns a tuple with the Days field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDays

`func (o *AiOrdersUpdateRequest) SetDays(v []AiOrdersUpdateRequestDaysInner)`

SetDays sets Days field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


