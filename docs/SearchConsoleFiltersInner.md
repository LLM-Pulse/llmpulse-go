# SearchConsoleFiltersInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Dimension** | **string** |  | 
**Operator** | Pointer to **string** |  | [optional] [default to "contains"]
**Expression** | **string** |  | 

## Methods

### NewSearchConsoleFiltersInner

`func NewSearchConsoleFiltersInner(dimension string, expression string, ) *SearchConsoleFiltersInner`

NewSearchConsoleFiltersInner instantiates a new SearchConsoleFiltersInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSearchConsoleFiltersInnerWithDefaults

`func NewSearchConsoleFiltersInnerWithDefaults() *SearchConsoleFiltersInner`

NewSearchConsoleFiltersInnerWithDefaults instantiates a new SearchConsoleFiltersInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDimension

`func (o *SearchConsoleFiltersInner) GetDimension() string`

GetDimension returns the Dimension field if non-nil, zero value otherwise.

### GetDimensionOk

`func (o *SearchConsoleFiltersInner) GetDimensionOk() (*string, bool)`

GetDimensionOk returns a tuple with the Dimension field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDimension

`func (o *SearchConsoleFiltersInner) SetDimension(v string)`

SetDimension sets Dimension field to given value.


### GetOperator

`func (o *SearchConsoleFiltersInner) GetOperator() string`

GetOperator returns the Operator field if non-nil, zero value otherwise.

### GetOperatorOk

`func (o *SearchConsoleFiltersInner) GetOperatorOk() (*string, bool)`

GetOperatorOk returns a tuple with the Operator field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperator

`func (o *SearchConsoleFiltersInner) SetOperator(v string)`

SetOperator sets Operator field to given value.

### HasOperator

`func (o *SearchConsoleFiltersInner) HasOperator() bool`

HasOperator returns a boolean if a field has been set.

### GetExpression

`func (o *SearchConsoleFiltersInner) GetExpression() string`

GetExpression returns the Expression field if non-nil, zero value otherwise.

### GetExpressionOk

`func (o *SearchConsoleFiltersInner) GetExpressionOk() (*string, bool)`

GetExpressionOk returns a tuple with the Expression field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpression

`func (o *SearchConsoleFiltersInner) SetExpression(v string)`

SetExpression sets Expression field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


