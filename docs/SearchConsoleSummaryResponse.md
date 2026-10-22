# SearchConsoleSummaryResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ProjectId** | Pointer to **int32** |  | [optional] 
**Property** | Pointer to [**SearchConsoleProperty**](SearchConsoleProperty.md) |  | [optional] 
**From** | Pointer to **string** |  | [optional] 
**To** | Pointer to **string** |  | [optional] 
**DataThrough** | Pointer to **NullableString** | Latest date Google has published for the property, or for every combined property (it lags 2-3 days). Later days are missing, not zero. | [optional] 
**Totals** | Pointer to [**SearchConsoleMetrics**](SearchConsoleMetrics.md) |  | [optional] 
**Dimension** | Pointer to **string** | Present when a breakdown was requested | [optional] 
**Breakdown** | Pointer to [**[]SearchConsoleSummaryResponseBreakdownInner**](SearchConsoleSummaryResponseBreakdownInner.md) | Present when a breakdown was requested, sorted by impressions descending | [optional] 
**BreakdownTruncated** | Pointer to **bool** | Present (true) when limit or Google&#39;s 25,000-row maximum left breakdown rows out, so they add up to less than totals | [optional] 
**RequestId** | Pointer to **string** |  | [optional] 
**Properties** | Pointer to [**[]SearchConsoleProperty**](SearchConsoleProperty.md) | With a list or all in the property parameter, the properties whose data the response holds (instead of property) | [optional] 
**ExcludedProperties** | Pointer to [**[]SearchConsoleExcludedProperty**](SearchConsoleExcludedProperty.md) | With a list or all, selected properties left out because another selected property already counts them | [optional] 
**PropertyErrors** | Pointer to [**[]SearchConsolePropertyError**](SearchConsolePropertyError.md) | With a list or all, selected properties Google refused, left out of the figures | [optional] 

## Methods

### NewSearchConsoleSummaryResponse

`func NewSearchConsoleSummaryResponse() *SearchConsoleSummaryResponse`

NewSearchConsoleSummaryResponse instantiates a new SearchConsoleSummaryResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSearchConsoleSummaryResponseWithDefaults

`func NewSearchConsoleSummaryResponseWithDefaults() *SearchConsoleSummaryResponse`

NewSearchConsoleSummaryResponseWithDefaults instantiates a new SearchConsoleSummaryResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProjectId

`func (o *SearchConsoleSummaryResponse) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *SearchConsoleSummaryResponse) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *SearchConsoleSummaryResponse) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.

### HasProjectId

`func (o *SearchConsoleSummaryResponse) HasProjectId() bool`

HasProjectId returns a boolean if a field has been set.

### GetProperty

`func (o *SearchConsoleSummaryResponse) GetProperty() SearchConsoleProperty`

GetProperty returns the Property field if non-nil, zero value otherwise.

### GetPropertyOk

`func (o *SearchConsoleSummaryResponse) GetPropertyOk() (*SearchConsoleProperty, bool)`

GetPropertyOk returns a tuple with the Property field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProperty

`func (o *SearchConsoleSummaryResponse) SetProperty(v SearchConsoleProperty)`

SetProperty sets Property field to given value.

### HasProperty

`func (o *SearchConsoleSummaryResponse) HasProperty() bool`

HasProperty returns a boolean if a field has been set.

### GetFrom

`func (o *SearchConsoleSummaryResponse) GetFrom() string`

GetFrom returns the From field if non-nil, zero value otherwise.

### GetFromOk

`func (o *SearchConsoleSummaryResponse) GetFromOk() (*string, bool)`

GetFromOk returns a tuple with the From field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFrom

`func (o *SearchConsoleSummaryResponse) SetFrom(v string)`

SetFrom sets From field to given value.

### HasFrom

`func (o *SearchConsoleSummaryResponse) HasFrom() bool`

HasFrom returns a boolean if a field has been set.

### GetTo

`func (o *SearchConsoleSummaryResponse) GetTo() string`

GetTo returns the To field if non-nil, zero value otherwise.

### GetToOk

`func (o *SearchConsoleSummaryResponse) GetToOk() (*string, bool)`

GetToOk returns a tuple with the To field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTo

`func (o *SearchConsoleSummaryResponse) SetTo(v string)`

SetTo sets To field to given value.

### HasTo

`func (o *SearchConsoleSummaryResponse) HasTo() bool`

HasTo returns a boolean if a field has been set.

### GetDataThrough

`func (o *SearchConsoleSummaryResponse) GetDataThrough() string`

GetDataThrough returns the DataThrough field if non-nil, zero value otherwise.

### GetDataThroughOk

`func (o *SearchConsoleSummaryResponse) GetDataThroughOk() (*string, bool)`

GetDataThroughOk returns a tuple with the DataThrough field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDataThrough

`func (o *SearchConsoleSummaryResponse) SetDataThrough(v string)`

SetDataThrough sets DataThrough field to given value.

### HasDataThrough

`func (o *SearchConsoleSummaryResponse) HasDataThrough() bool`

HasDataThrough returns a boolean if a field has been set.

### SetDataThroughNil

`func (o *SearchConsoleSummaryResponse) SetDataThroughNil(b bool)`

 SetDataThroughNil sets the value for DataThrough to be an explicit nil

### UnsetDataThrough
`func (o *SearchConsoleSummaryResponse) UnsetDataThrough()`

UnsetDataThrough ensures that no value is present for DataThrough, not even an explicit nil
### GetTotals

`func (o *SearchConsoleSummaryResponse) GetTotals() SearchConsoleMetrics`

GetTotals returns the Totals field if non-nil, zero value otherwise.

### GetTotalsOk

`func (o *SearchConsoleSummaryResponse) GetTotalsOk() (*SearchConsoleMetrics, bool)`

GetTotalsOk returns a tuple with the Totals field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotals

`func (o *SearchConsoleSummaryResponse) SetTotals(v SearchConsoleMetrics)`

SetTotals sets Totals field to given value.

### HasTotals

`func (o *SearchConsoleSummaryResponse) HasTotals() bool`

HasTotals returns a boolean if a field has been set.

### GetDimension

`func (o *SearchConsoleSummaryResponse) GetDimension() string`

GetDimension returns the Dimension field if non-nil, zero value otherwise.

### GetDimensionOk

`func (o *SearchConsoleSummaryResponse) GetDimensionOk() (*string, bool)`

GetDimensionOk returns a tuple with the Dimension field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDimension

`func (o *SearchConsoleSummaryResponse) SetDimension(v string)`

SetDimension sets Dimension field to given value.

### HasDimension

`func (o *SearchConsoleSummaryResponse) HasDimension() bool`

HasDimension returns a boolean if a field has been set.

### GetBreakdown

`func (o *SearchConsoleSummaryResponse) GetBreakdown() []SearchConsoleSummaryResponseBreakdownInner`

GetBreakdown returns the Breakdown field if non-nil, zero value otherwise.

### GetBreakdownOk

`func (o *SearchConsoleSummaryResponse) GetBreakdownOk() (*[]SearchConsoleSummaryResponseBreakdownInner, bool)`

GetBreakdownOk returns a tuple with the Breakdown field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBreakdown

`func (o *SearchConsoleSummaryResponse) SetBreakdown(v []SearchConsoleSummaryResponseBreakdownInner)`

SetBreakdown sets Breakdown field to given value.

### HasBreakdown

`func (o *SearchConsoleSummaryResponse) HasBreakdown() bool`

HasBreakdown returns a boolean if a field has been set.

### GetBreakdownTruncated

`func (o *SearchConsoleSummaryResponse) GetBreakdownTruncated() bool`

GetBreakdownTruncated returns the BreakdownTruncated field if non-nil, zero value otherwise.

### GetBreakdownTruncatedOk

`func (o *SearchConsoleSummaryResponse) GetBreakdownTruncatedOk() (*bool, bool)`

GetBreakdownTruncatedOk returns a tuple with the BreakdownTruncated field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBreakdownTruncated

`func (o *SearchConsoleSummaryResponse) SetBreakdownTruncated(v bool)`

SetBreakdownTruncated sets BreakdownTruncated field to given value.

### HasBreakdownTruncated

`func (o *SearchConsoleSummaryResponse) HasBreakdownTruncated() bool`

HasBreakdownTruncated returns a boolean if a field has been set.

### GetRequestId

`func (o *SearchConsoleSummaryResponse) GetRequestId() string`

GetRequestId returns the RequestId field if non-nil, zero value otherwise.

### GetRequestIdOk

`func (o *SearchConsoleSummaryResponse) GetRequestIdOk() (*string, bool)`

GetRequestIdOk returns a tuple with the RequestId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestId

`func (o *SearchConsoleSummaryResponse) SetRequestId(v string)`

SetRequestId sets RequestId field to given value.

### HasRequestId

`func (o *SearchConsoleSummaryResponse) HasRequestId() bool`

HasRequestId returns a boolean if a field has been set.

### GetProperties

`func (o *SearchConsoleSummaryResponse) GetProperties() []SearchConsoleProperty`

GetProperties returns the Properties field if non-nil, zero value otherwise.

### GetPropertiesOk

`func (o *SearchConsoleSummaryResponse) GetPropertiesOk() (*[]SearchConsoleProperty, bool)`

GetPropertiesOk returns a tuple with the Properties field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProperties

`func (o *SearchConsoleSummaryResponse) SetProperties(v []SearchConsoleProperty)`

SetProperties sets Properties field to given value.

### HasProperties

`func (o *SearchConsoleSummaryResponse) HasProperties() bool`

HasProperties returns a boolean if a field has been set.

### GetExcludedProperties

`func (o *SearchConsoleSummaryResponse) GetExcludedProperties() []SearchConsoleExcludedProperty`

GetExcludedProperties returns the ExcludedProperties field if non-nil, zero value otherwise.

### GetExcludedPropertiesOk

`func (o *SearchConsoleSummaryResponse) GetExcludedPropertiesOk() (*[]SearchConsoleExcludedProperty, bool)`

GetExcludedPropertiesOk returns a tuple with the ExcludedProperties field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExcludedProperties

`func (o *SearchConsoleSummaryResponse) SetExcludedProperties(v []SearchConsoleExcludedProperty)`

SetExcludedProperties sets ExcludedProperties field to given value.

### HasExcludedProperties

`func (o *SearchConsoleSummaryResponse) HasExcludedProperties() bool`

HasExcludedProperties returns a boolean if a field has been set.

### GetPropertyErrors

`func (o *SearchConsoleSummaryResponse) GetPropertyErrors() []SearchConsolePropertyError`

GetPropertyErrors returns the PropertyErrors field if non-nil, zero value otherwise.

### GetPropertyErrorsOk

`func (o *SearchConsoleSummaryResponse) GetPropertyErrorsOk() (*[]SearchConsolePropertyError, bool)`

GetPropertyErrorsOk returns a tuple with the PropertyErrors field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPropertyErrors

`func (o *SearchConsoleSummaryResponse) SetPropertyErrors(v []SearchConsolePropertyError)`

SetPropertyErrors sets PropertyErrors field to given value.

### HasPropertyErrors

`func (o *SearchConsoleSummaryResponse) HasPropertyErrors() bool`

HasPropertyErrors returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


