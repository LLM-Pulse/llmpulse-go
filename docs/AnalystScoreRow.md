# AnalystScoreRow

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Brand** | **string** | Brand name; the subject name in a custom study | 
**IsProject** | **bool** | Whether it is the project&#39;s own brand; in a custom study, the focus subject | 
**Model** | **string** |  | 
**ReportDate** | **string** |  | 
**Dimension** | **string** | Dimension key, as the dimension filter takes it | 
**DimensionName** | **string** |  | 
**Attribute** | **string** | Attribute key within the dimension | 
**AttributeName** | **string** |  | 
**Score** | **interface{}** | The 0-100 score as the analyst model wrote it, normally a number, or null when it gave none. Deliberately untyped, as the model&#39;s output is stored without coercion | 
**Reasoning** | **NullableString** | Why the model gave this score; null when it gave no reasoning | 

## Methods

### NewAnalystScoreRow

`func NewAnalystScoreRow(brand string, isProject bool, model string, reportDate string, dimension string, dimensionName string, attribute string, attributeName string, score interface{}, reasoning NullableString, ) *AnalystScoreRow`

NewAnalystScoreRow instantiates a new AnalystScoreRow object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAnalystScoreRowWithDefaults

`func NewAnalystScoreRowWithDefaults() *AnalystScoreRow`

NewAnalystScoreRowWithDefaults instantiates a new AnalystScoreRow object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBrand

`func (o *AnalystScoreRow) GetBrand() string`

GetBrand returns the Brand field if non-nil, zero value otherwise.

### GetBrandOk

`func (o *AnalystScoreRow) GetBrandOk() (*string, bool)`

GetBrandOk returns a tuple with the Brand field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBrand

`func (o *AnalystScoreRow) SetBrand(v string)`

SetBrand sets Brand field to given value.


### GetIsProject

`func (o *AnalystScoreRow) GetIsProject() bool`

GetIsProject returns the IsProject field if non-nil, zero value otherwise.

### GetIsProjectOk

`func (o *AnalystScoreRow) GetIsProjectOk() (*bool, bool)`

GetIsProjectOk returns a tuple with the IsProject field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsProject

`func (o *AnalystScoreRow) SetIsProject(v bool)`

SetIsProject sets IsProject field to given value.


### GetModel

`func (o *AnalystScoreRow) GetModel() string`

GetModel returns the Model field if non-nil, zero value otherwise.

### GetModelOk

`func (o *AnalystScoreRow) GetModelOk() (*string, bool)`

GetModelOk returns a tuple with the Model field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModel

`func (o *AnalystScoreRow) SetModel(v string)`

SetModel sets Model field to given value.


### GetReportDate

`func (o *AnalystScoreRow) GetReportDate() string`

GetReportDate returns the ReportDate field if non-nil, zero value otherwise.

### GetReportDateOk

`func (o *AnalystScoreRow) GetReportDateOk() (*string, bool)`

GetReportDateOk returns a tuple with the ReportDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReportDate

`func (o *AnalystScoreRow) SetReportDate(v string)`

SetReportDate sets ReportDate field to given value.


### GetDimension

`func (o *AnalystScoreRow) GetDimension() string`

GetDimension returns the Dimension field if non-nil, zero value otherwise.

### GetDimensionOk

`func (o *AnalystScoreRow) GetDimensionOk() (*string, bool)`

GetDimensionOk returns a tuple with the Dimension field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDimension

`func (o *AnalystScoreRow) SetDimension(v string)`

SetDimension sets Dimension field to given value.


### GetDimensionName

`func (o *AnalystScoreRow) GetDimensionName() string`

GetDimensionName returns the DimensionName field if non-nil, zero value otherwise.

### GetDimensionNameOk

`func (o *AnalystScoreRow) GetDimensionNameOk() (*string, bool)`

GetDimensionNameOk returns a tuple with the DimensionName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDimensionName

`func (o *AnalystScoreRow) SetDimensionName(v string)`

SetDimensionName sets DimensionName field to given value.


### GetAttribute

`func (o *AnalystScoreRow) GetAttribute() string`

GetAttribute returns the Attribute field if non-nil, zero value otherwise.

### GetAttributeOk

`func (o *AnalystScoreRow) GetAttributeOk() (*string, bool)`

GetAttributeOk returns a tuple with the Attribute field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAttribute

`func (o *AnalystScoreRow) SetAttribute(v string)`

SetAttribute sets Attribute field to given value.


### GetAttributeName

`func (o *AnalystScoreRow) GetAttributeName() string`

GetAttributeName returns the AttributeName field if non-nil, zero value otherwise.

### GetAttributeNameOk

`func (o *AnalystScoreRow) GetAttributeNameOk() (*string, bool)`

GetAttributeNameOk returns a tuple with the AttributeName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAttributeName

`func (o *AnalystScoreRow) SetAttributeName(v string)`

SetAttributeName sets AttributeName field to given value.


### GetScore

`func (o *AnalystScoreRow) GetScore() interface{}`

GetScore returns the Score field if non-nil, zero value otherwise.

### GetScoreOk

`func (o *AnalystScoreRow) GetScoreOk() (*interface{}, bool)`

GetScoreOk returns a tuple with the Score field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScore

`func (o *AnalystScoreRow) SetScore(v interface{})`

SetScore sets Score field to given value.


### SetScoreNil

`func (o *AnalystScoreRow) SetScoreNil(b bool)`

 SetScoreNil sets the value for Score to be an explicit nil

### UnsetScore
`func (o *AnalystScoreRow) UnsetScore()`

UnsetScore ensures that no value is present for Score, not even an explicit nil
### GetReasoning

`func (o *AnalystScoreRow) GetReasoning() string`

GetReasoning returns the Reasoning field if non-nil, zero value otherwise.

### GetReasoningOk

`func (o *AnalystScoreRow) GetReasoningOk() (*string, bool)`

GetReasoningOk returns a tuple with the Reasoning field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReasoning

`func (o *AnalystScoreRow) SetReasoning(v string)`

SetReasoning sets Reasoning field to given value.


### SetReasoningNil

`func (o *AnalystScoreRow) SetReasoningNil(b bool)`

 SetReasoningNil sets the value for Reasoning to be an explicit nil

### UnsetReasoning
`func (o *AnalystScoreRow) UnsetReasoning()`

UnsetReasoning ensures that no value is present for Reasoning, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


