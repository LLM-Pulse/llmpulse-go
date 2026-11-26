# AiModelPositionDistributionResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ProjectId** | **int32** |  | 
**From** | **time.Time** |  | 
**To** | **time.Time** |  | 
**Filters** | [**AiModelInsightsReportFiltersEcho**](AiModelInsightsReportFiltersEcho.md) |  | 
**Granularity** | **string** |  | 
**Brands** | [**[]AiModelPositionDistributionBrand**](AiModelPositionDistributionBrand.md) | The first brand (brand1, else the project) and the second (brand2, else the competitor with the most mentions, else the project), each left out when it has no mention in the window | 
**MaxStackedValue** | **int32** | The largest mentions count of one period across the brands, for a shared chart axis | 
**RequestId** | **string** |  | 

## Methods

### NewAiModelPositionDistributionResponse

`func NewAiModelPositionDistributionResponse(projectId int32, from time.Time, to time.Time, filters AiModelInsightsReportFiltersEcho, granularity string, brands []AiModelPositionDistributionBrand, maxStackedValue int32, requestId string, ) *AiModelPositionDistributionResponse`

NewAiModelPositionDistributionResponse instantiates a new AiModelPositionDistributionResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAiModelPositionDistributionResponseWithDefaults

`func NewAiModelPositionDistributionResponseWithDefaults() *AiModelPositionDistributionResponse`

NewAiModelPositionDistributionResponseWithDefaults instantiates a new AiModelPositionDistributionResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProjectId

`func (o *AiModelPositionDistributionResponse) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *AiModelPositionDistributionResponse) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *AiModelPositionDistributionResponse) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.


### GetFrom

`func (o *AiModelPositionDistributionResponse) GetFrom() time.Time`

GetFrom returns the From field if non-nil, zero value otherwise.

### GetFromOk

`func (o *AiModelPositionDistributionResponse) GetFromOk() (*time.Time, bool)`

GetFromOk returns a tuple with the From field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFrom

`func (o *AiModelPositionDistributionResponse) SetFrom(v time.Time)`

SetFrom sets From field to given value.


### GetTo

`func (o *AiModelPositionDistributionResponse) GetTo() time.Time`

GetTo returns the To field if non-nil, zero value otherwise.

### GetToOk

`func (o *AiModelPositionDistributionResponse) GetToOk() (*time.Time, bool)`

GetToOk returns a tuple with the To field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTo

`func (o *AiModelPositionDistributionResponse) SetTo(v time.Time)`

SetTo sets To field to given value.


### GetFilters

`func (o *AiModelPositionDistributionResponse) GetFilters() AiModelInsightsReportFiltersEcho`

GetFilters returns the Filters field if non-nil, zero value otherwise.

### GetFiltersOk

`func (o *AiModelPositionDistributionResponse) GetFiltersOk() (*AiModelInsightsReportFiltersEcho, bool)`

GetFiltersOk returns a tuple with the Filters field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFilters

`func (o *AiModelPositionDistributionResponse) SetFilters(v AiModelInsightsReportFiltersEcho)`

SetFilters sets Filters field to given value.


### GetGranularity

`func (o *AiModelPositionDistributionResponse) GetGranularity() string`

GetGranularity returns the Granularity field if non-nil, zero value otherwise.

### GetGranularityOk

`func (o *AiModelPositionDistributionResponse) GetGranularityOk() (*string, bool)`

GetGranularityOk returns a tuple with the Granularity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGranularity

`func (o *AiModelPositionDistributionResponse) SetGranularity(v string)`

SetGranularity sets Granularity field to given value.


### GetBrands

`func (o *AiModelPositionDistributionResponse) GetBrands() []AiModelPositionDistributionBrand`

GetBrands returns the Brands field if non-nil, zero value otherwise.

### GetBrandsOk

`func (o *AiModelPositionDistributionResponse) GetBrandsOk() (*[]AiModelPositionDistributionBrand, bool)`

GetBrandsOk returns a tuple with the Brands field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBrands

`func (o *AiModelPositionDistributionResponse) SetBrands(v []AiModelPositionDistributionBrand)`

SetBrands sets Brands field to given value.


### GetMaxStackedValue

`func (o *AiModelPositionDistributionResponse) GetMaxStackedValue() int32`

GetMaxStackedValue returns the MaxStackedValue field if non-nil, zero value otherwise.

### GetMaxStackedValueOk

`func (o *AiModelPositionDistributionResponse) GetMaxStackedValueOk() (*int32, bool)`

GetMaxStackedValueOk returns a tuple with the MaxStackedValue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxStackedValue

`func (o *AiModelPositionDistributionResponse) SetMaxStackedValue(v int32)`

SetMaxStackedValue sets MaxStackedValue field to given value.


### GetRequestId

`func (o *AiModelPositionDistributionResponse) GetRequestId() string`

GetRequestId returns the RequestId field if non-nil, zero value otherwise.

### GetRequestIdOk

`func (o *AiModelPositionDistributionResponse) GetRequestIdOk() (*string, bool)`

GetRequestIdOk returns a tuple with the RequestId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestId

`func (o *AiModelPositionDistributionResponse) SetRequestId(v string)`

SetRequestId sets RequestId field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


