# CitationSeries

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Granularity** | **string** |  | 
**Total** | **int32** | Equal to total_responses | 
**ByModel** | **map[string]int32** | Answers per AI model, keyed by model, largest first | 
**Data** | [**[]AiModelPositionDistributionBrandBucketsInnerDataInner**](AiModelPositionDistributionBrandBucketsInnerDataInner.md) | One point per period holding a filtered answer, oldest first; a zero means answers ran and none cited it | 

## Methods

### NewCitationSeries

`func NewCitationSeries(granularity string, total int32, byModel map[string]int32, data []AiModelPositionDistributionBrandBucketsInnerDataInner, ) *CitationSeries`

NewCitationSeries instantiates a new CitationSeries object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCitationSeriesWithDefaults

`func NewCitationSeriesWithDefaults() *CitationSeries`

NewCitationSeriesWithDefaults instantiates a new CitationSeries object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetGranularity

`func (o *CitationSeries) GetGranularity() string`

GetGranularity returns the Granularity field if non-nil, zero value otherwise.

### GetGranularityOk

`func (o *CitationSeries) GetGranularityOk() (*string, bool)`

GetGranularityOk returns a tuple with the Granularity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGranularity

`func (o *CitationSeries) SetGranularity(v string)`

SetGranularity sets Granularity field to given value.


### GetTotal

`func (o *CitationSeries) GetTotal() int32`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *CitationSeries) GetTotalOk() (*int32, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *CitationSeries) SetTotal(v int32)`

SetTotal sets Total field to given value.


### GetByModel

`func (o *CitationSeries) GetByModel() map[string]int32`

GetByModel returns the ByModel field if non-nil, zero value otherwise.

### GetByModelOk

`func (o *CitationSeries) GetByModelOk() (*map[string]int32, bool)`

GetByModelOk returns a tuple with the ByModel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetByModel

`func (o *CitationSeries) SetByModel(v map[string]int32)`

SetByModel sets ByModel field to given value.


### GetData

`func (o *CitationSeries) GetData() []AiModelPositionDistributionBrandBucketsInnerDataInner`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *CitationSeries) GetDataOk() (*[]AiModelPositionDistributionBrandBucketsInnerDataInner, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *CitationSeries) SetData(v []AiModelPositionDistributionBrandBucketsInnerDataInner)`

SetData sets Data field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


