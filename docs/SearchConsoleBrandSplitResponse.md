# SearchConsoleBrandSplitResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ProjectId** | Pointer to **int32** |  | [optional] 
**Property** | Pointer to [**SearchConsoleProperty**](SearchConsoleProperty.md) |  | [optional] 
**Properties** | Pointer to [**[]SearchConsoleProperty**](SearchConsoleProperty.md) | With a list or all in the property parameter, the properties whose data the response holds (instead of property) | [optional] 
**ExcludedProperties** | Pointer to [**[]SearchConsoleExcludedProperty**](SearchConsoleExcludedProperty.md) | With a list or all, selected properties left out because another selected property already counts them | [optional] 
**PropertyErrors** | Pointer to [**[]SearchConsolePropertyError**](SearchConsolePropertyError.md) | With a list or all, selected properties Google refused, left out of the figures | [optional] 
**From** | Pointer to **string** |  | [optional] 
**To** | Pointer to **string** |  | [optional] 
**DataThrough** | Pointer to **NullableString** | Latest date Google has published for the property, or for every combined property (it lags 2-3 days). Later days are missing, not zero. | [optional] 
**BrandTerms** | Pointer to **[]string** | The project&#39;s brand name, matching names, app names and domain, lowercased, each matched as a whole word | [optional] 
**Totals** | Pointer to [**SearchConsoleMetrics**](SearchConsoleMetrics.md) |  | [optional] 
**Branded** | Pointer to [**SearchConsoleMetrics**](SearchConsoleMetrics.md) |  | [optional] 
**NonBranded** | Pointer to [**SearchConsoleMetrics**](SearchConsoleMetrics.md) |  | [optional] 
**Unclassified** | Pointer to [**SearchConsoleBrandSplitResponseUnclassified**](SearchConsoleBrandSplitResponseUnclassified.md) |  | [optional] 
**RequestId** | Pointer to **string** |  | [optional] 

## Methods

### NewSearchConsoleBrandSplitResponse

`func NewSearchConsoleBrandSplitResponse() *SearchConsoleBrandSplitResponse`

NewSearchConsoleBrandSplitResponse instantiates a new SearchConsoleBrandSplitResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSearchConsoleBrandSplitResponseWithDefaults

`func NewSearchConsoleBrandSplitResponseWithDefaults() *SearchConsoleBrandSplitResponse`

NewSearchConsoleBrandSplitResponseWithDefaults instantiates a new SearchConsoleBrandSplitResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProjectId

`func (o *SearchConsoleBrandSplitResponse) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *SearchConsoleBrandSplitResponse) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *SearchConsoleBrandSplitResponse) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.

### HasProjectId

`func (o *SearchConsoleBrandSplitResponse) HasProjectId() bool`

HasProjectId returns a boolean if a field has been set.

### GetProperty

`func (o *SearchConsoleBrandSplitResponse) GetProperty() SearchConsoleProperty`

GetProperty returns the Property field if non-nil, zero value otherwise.

### GetPropertyOk

`func (o *SearchConsoleBrandSplitResponse) GetPropertyOk() (*SearchConsoleProperty, bool)`

GetPropertyOk returns a tuple with the Property field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProperty

`func (o *SearchConsoleBrandSplitResponse) SetProperty(v SearchConsoleProperty)`

SetProperty sets Property field to given value.

### HasProperty

`func (o *SearchConsoleBrandSplitResponse) HasProperty() bool`

HasProperty returns a boolean if a field has been set.

### GetProperties

`func (o *SearchConsoleBrandSplitResponse) GetProperties() []SearchConsoleProperty`

GetProperties returns the Properties field if non-nil, zero value otherwise.

### GetPropertiesOk

`func (o *SearchConsoleBrandSplitResponse) GetPropertiesOk() (*[]SearchConsoleProperty, bool)`

GetPropertiesOk returns a tuple with the Properties field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProperties

`func (o *SearchConsoleBrandSplitResponse) SetProperties(v []SearchConsoleProperty)`

SetProperties sets Properties field to given value.

### HasProperties

`func (o *SearchConsoleBrandSplitResponse) HasProperties() bool`

HasProperties returns a boolean if a field has been set.

### GetExcludedProperties

`func (o *SearchConsoleBrandSplitResponse) GetExcludedProperties() []SearchConsoleExcludedProperty`

GetExcludedProperties returns the ExcludedProperties field if non-nil, zero value otherwise.

### GetExcludedPropertiesOk

`func (o *SearchConsoleBrandSplitResponse) GetExcludedPropertiesOk() (*[]SearchConsoleExcludedProperty, bool)`

GetExcludedPropertiesOk returns a tuple with the ExcludedProperties field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExcludedProperties

`func (o *SearchConsoleBrandSplitResponse) SetExcludedProperties(v []SearchConsoleExcludedProperty)`

SetExcludedProperties sets ExcludedProperties field to given value.

### HasExcludedProperties

`func (o *SearchConsoleBrandSplitResponse) HasExcludedProperties() bool`

HasExcludedProperties returns a boolean if a field has been set.

### GetPropertyErrors

`func (o *SearchConsoleBrandSplitResponse) GetPropertyErrors() []SearchConsolePropertyError`

GetPropertyErrors returns the PropertyErrors field if non-nil, zero value otherwise.

### GetPropertyErrorsOk

`func (o *SearchConsoleBrandSplitResponse) GetPropertyErrorsOk() (*[]SearchConsolePropertyError, bool)`

GetPropertyErrorsOk returns a tuple with the PropertyErrors field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPropertyErrors

`func (o *SearchConsoleBrandSplitResponse) SetPropertyErrors(v []SearchConsolePropertyError)`

SetPropertyErrors sets PropertyErrors field to given value.

### HasPropertyErrors

`func (o *SearchConsoleBrandSplitResponse) HasPropertyErrors() bool`

HasPropertyErrors returns a boolean if a field has been set.

### GetFrom

`func (o *SearchConsoleBrandSplitResponse) GetFrom() string`

GetFrom returns the From field if non-nil, zero value otherwise.

### GetFromOk

`func (o *SearchConsoleBrandSplitResponse) GetFromOk() (*string, bool)`

GetFromOk returns a tuple with the From field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFrom

`func (o *SearchConsoleBrandSplitResponse) SetFrom(v string)`

SetFrom sets From field to given value.

### HasFrom

`func (o *SearchConsoleBrandSplitResponse) HasFrom() bool`

HasFrom returns a boolean if a field has been set.

### GetTo

`func (o *SearchConsoleBrandSplitResponse) GetTo() string`

GetTo returns the To field if non-nil, zero value otherwise.

### GetToOk

`func (o *SearchConsoleBrandSplitResponse) GetToOk() (*string, bool)`

GetToOk returns a tuple with the To field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTo

`func (o *SearchConsoleBrandSplitResponse) SetTo(v string)`

SetTo sets To field to given value.

### HasTo

`func (o *SearchConsoleBrandSplitResponse) HasTo() bool`

HasTo returns a boolean if a field has been set.

### GetDataThrough

`func (o *SearchConsoleBrandSplitResponse) GetDataThrough() string`

GetDataThrough returns the DataThrough field if non-nil, zero value otherwise.

### GetDataThroughOk

`func (o *SearchConsoleBrandSplitResponse) GetDataThroughOk() (*string, bool)`

GetDataThroughOk returns a tuple with the DataThrough field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDataThrough

`func (o *SearchConsoleBrandSplitResponse) SetDataThrough(v string)`

SetDataThrough sets DataThrough field to given value.

### HasDataThrough

`func (o *SearchConsoleBrandSplitResponse) HasDataThrough() bool`

HasDataThrough returns a boolean if a field has been set.

### SetDataThroughNil

`func (o *SearchConsoleBrandSplitResponse) SetDataThroughNil(b bool)`

 SetDataThroughNil sets the value for DataThrough to be an explicit nil

### UnsetDataThrough
`func (o *SearchConsoleBrandSplitResponse) UnsetDataThrough()`

UnsetDataThrough ensures that no value is present for DataThrough, not even an explicit nil
### GetBrandTerms

`func (o *SearchConsoleBrandSplitResponse) GetBrandTerms() []string`

GetBrandTerms returns the BrandTerms field if non-nil, zero value otherwise.

### GetBrandTermsOk

`func (o *SearchConsoleBrandSplitResponse) GetBrandTermsOk() (*[]string, bool)`

GetBrandTermsOk returns a tuple with the BrandTerms field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBrandTerms

`func (o *SearchConsoleBrandSplitResponse) SetBrandTerms(v []string)`

SetBrandTerms sets BrandTerms field to given value.

### HasBrandTerms

`func (o *SearchConsoleBrandSplitResponse) HasBrandTerms() bool`

HasBrandTerms returns a boolean if a field has been set.

### GetTotals

`func (o *SearchConsoleBrandSplitResponse) GetTotals() SearchConsoleMetrics`

GetTotals returns the Totals field if non-nil, zero value otherwise.

### GetTotalsOk

`func (o *SearchConsoleBrandSplitResponse) GetTotalsOk() (*SearchConsoleMetrics, bool)`

GetTotalsOk returns a tuple with the Totals field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotals

`func (o *SearchConsoleBrandSplitResponse) SetTotals(v SearchConsoleMetrics)`

SetTotals sets Totals field to given value.

### HasTotals

`func (o *SearchConsoleBrandSplitResponse) HasTotals() bool`

HasTotals returns a boolean if a field has been set.

### GetBranded

`func (o *SearchConsoleBrandSplitResponse) GetBranded() SearchConsoleMetrics`

GetBranded returns the Branded field if non-nil, zero value otherwise.

### GetBrandedOk

`func (o *SearchConsoleBrandSplitResponse) GetBrandedOk() (*SearchConsoleMetrics, bool)`

GetBrandedOk returns a tuple with the Branded field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBranded

`func (o *SearchConsoleBrandSplitResponse) SetBranded(v SearchConsoleMetrics)`

SetBranded sets Branded field to given value.

### HasBranded

`func (o *SearchConsoleBrandSplitResponse) HasBranded() bool`

HasBranded returns a boolean if a field has been set.

### GetNonBranded

`func (o *SearchConsoleBrandSplitResponse) GetNonBranded() SearchConsoleMetrics`

GetNonBranded returns the NonBranded field if non-nil, zero value otherwise.

### GetNonBrandedOk

`func (o *SearchConsoleBrandSplitResponse) GetNonBrandedOk() (*SearchConsoleMetrics, bool)`

GetNonBrandedOk returns a tuple with the NonBranded field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNonBranded

`func (o *SearchConsoleBrandSplitResponse) SetNonBranded(v SearchConsoleMetrics)`

SetNonBranded sets NonBranded field to given value.

### HasNonBranded

`func (o *SearchConsoleBrandSplitResponse) HasNonBranded() bool`

HasNonBranded returns a boolean if a field has been set.

### GetUnclassified

`func (o *SearchConsoleBrandSplitResponse) GetUnclassified() SearchConsoleBrandSplitResponseUnclassified`

GetUnclassified returns the Unclassified field if non-nil, zero value otherwise.

### GetUnclassifiedOk

`func (o *SearchConsoleBrandSplitResponse) GetUnclassifiedOk() (*SearchConsoleBrandSplitResponseUnclassified, bool)`

GetUnclassifiedOk returns a tuple with the Unclassified field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnclassified

`func (o *SearchConsoleBrandSplitResponse) SetUnclassified(v SearchConsoleBrandSplitResponseUnclassified)`

SetUnclassified sets Unclassified field to given value.

### HasUnclassified

`func (o *SearchConsoleBrandSplitResponse) HasUnclassified() bool`

HasUnclassified returns a boolean if a field has been set.

### GetRequestId

`func (o *SearchConsoleBrandSplitResponse) GetRequestId() string`

GetRequestId returns the RequestId field if non-nil, zero value otherwise.

### GetRequestIdOk

`func (o *SearchConsoleBrandSplitResponse) GetRequestIdOk() (*string, bool)`

GetRequestIdOk returns a tuple with the RequestId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestId

`func (o *SearchConsoleBrandSplitResponse) SetRequestId(v string)`

SetRequestId sets RequestId field to given value.

### HasRequestId

`func (o *SearchConsoleBrandSplitResponse) HasRequestId() bool`

HasRequestId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


