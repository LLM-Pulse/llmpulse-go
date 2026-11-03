# SearchConsoleAiVisibilityGapsResponse

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
**MinImpressions** | Pointer to **int32** |  | [optional] 
**UnmatchedOnly** | Pointer to **bool** |  | [optional] 
**MatchedCount** | Pointer to **int32** | Queries with at least min_impressions that match a prompt of the project, counted before unmatched_only leaves them out | [optional] 
**Page** | Pointer to **int32** |  | [optional] 
**PerPage** | Pointer to **int32** |  | [optional] 
**Total** | Pointer to **int32** | Rows in the report before paging | [optional] 
**Truncated** | Pointer to **bool** | Present (true) when Google returned its 25,000-row maximum for a property, so the report covers its top rows only | [optional] 
**Data** | Pointer to [**[]SearchConsoleAiVisibilityGapsResponseDataInner**](SearchConsoleAiVisibilityGapsResponseDataInner.md) |  | [optional] 
**RequestId** | Pointer to **string** |  | [optional] 

## Methods

### NewSearchConsoleAiVisibilityGapsResponse

`func NewSearchConsoleAiVisibilityGapsResponse() *SearchConsoleAiVisibilityGapsResponse`

NewSearchConsoleAiVisibilityGapsResponse instantiates a new SearchConsoleAiVisibilityGapsResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSearchConsoleAiVisibilityGapsResponseWithDefaults

`func NewSearchConsoleAiVisibilityGapsResponseWithDefaults() *SearchConsoleAiVisibilityGapsResponse`

NewSearchConsoleAiVisibilityGapsResponseWithDefaults instantiates a new SearchConsoleAiVisibilityGapsResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProjectId

`func (o *SearchConsoleAiVisibilityGapsResponse) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *SearchConsoleAiVisibilityGapsResponse) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *SearchConsoleAiVisibilityGapsResponse) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.

### HasProjectId

`func (o *SearchConsoleAiVisibilityGapsResponse) HasProjectId() bool`

HasProjectId returns a boolean if a field has been set.

### GetProperty

`func (o *SearchConsoleAiVisibilityGapsResponse) GetProperty() SearchConsoleProperty`

GetProperty returns the Property field if non-nil, zero value otherwise.

### GetPropertyOk

`func (o *SearchConsoleAiVisibilityGapsResponse) GetPropertyOk() (*SearchConsoleProperty, bool)`

GetPropertyOk returns a tuple with the Property field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProperty

`func (o *SearchConsoleAiVisibilityGapsResponse) SetProperty(v SearchConsoleProperty)`

SetProperty sets Property field to given value.

### HasProperty

`func (o *SearchConsoleAiVisibilityGapsResponse) HasProperty() bool`

HasProperty returns a boolean if a field has been set.

### GetProperties

`func (o *SearchConsoleAiVisibilityGapsResponse) GetProperties() []SearchConsoleProperty`

GetProperties returns the Properties field if non-nil, zero value otherwise.

### GetPropertiesOk

`func (o *SearchConsoleAiVisibilityGapsResponse) GetPropertiesOk() (*[]SearchConsoleProperty, bool)`

GetPropertiesOk returns a tuple with the Properties field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProperties

`func (o *SearchConsoleAiVisibilityGapsResponse) SetProperties(v []SearchConsoleProperty)`

SetProperties sets Properties field to given value.

### HasProperties

`func (o *SearchConsoleAiVisibilityGapsResponse) HasProperties() bool`

HasProperties returns a boolean if a field has been set.

### GetExcludedProperties

`func (o *SearchConsoleAiVisibilityGapsResponse) GetExcludedProperties() []SearchConsoleExcludedProperty`

GetExcludedProperties returns the ExcludedProperties field if non-nil, zero value otherwise.

### GetExcludedPropertiesOk

`func (o *SearchConsoleAiVisibilityGapsResponse) GetExcludedPropertiesOk() (*[]SearchConsoleExcludedProperty, bool)`

GetExcludedPropertiesOk returns a tuple with the ExcludedProperties field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExcludedProperties

`func (o *SearchConsoleAiVisibilityGapsResponse) SetExcludedProperties(v []SearchConsoleExcludedProperty)`

SetExcludedProperties sets ExcludedProperties field to given value.

### HasExcludedProperties

`func (o *SearchConsoleAiVisibilityGapsResponse) HasExcludedProperties() bool`

HasExcludedProperties returns a boolean if a field has been set.

### GetPropertyErrors

`func (o *SearchConsoleAiVisibilityGapsResponse) GetPropertyErrors() []SearchConsolePropertyError`

GetPropertyErrors returns the PropertyErrors field if non-nil, zero value otherwise.

### GetPropertyErrorsOk

`func (o *SearchConsoleAiVisibilityGapsResponse) GetPropertyErrorsOk() (*[]SearchConsolePropertyError, bool)`

GetPropertyErrorsOk returns a tuple with the PropertyErrors field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPropertyErrors

`func (o *SearchConsoleAiVisibilityGapsResponse) SetPropertyErrors(v []SearchConsolePropertyError)`

SetPropertyErrors sets PropertyErrors field to given value.

### HasPropertyErrors

`func (o *SearchConsoleAiVisibilityGapsResponse) HasPropertyErrors() bool`

HasPropertyErrors returns a boolean if a field has been set.

### GetFrom

`func (o *SearchConsoleAiVisibilityGapsResponse) GetFrom() string`

GetFrom returns the From field if non-nil, zero value otherwise.

### GetFromOk

`func (o *SearchConsoleAiVisibilityGapsResponse) GetFromOk() (*string, bool)`

GetFromOk returns a tuple with the From field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFrom

`func (o *SearchConsoleAiVisibilityGapsResponse) SetFrom(v string)`

SetFrom sets From field to given value.

### HasFrom

`func (o *SearchConsoleAiVisibilityGapsResponse) HasFrom() bool`

HasFrom returns a boolean if a field has been set.

### GetTo

`func (o *SearchConsoleAiVisibilityGapsResponse) GetTo() string`

GetTo returns the To field if non-nil, zero value otherwise.

### GetToOk

`func (o *SearchConsoleAiVisibilityGapsResponse) GetToOk() (*string, bool)`

GetToOk returns a tuple with the To field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTo

`func (o *SearchConsoleAiVisibilityGapsResponse) SetTo(v string)`

SetTo sets To field to given value.

### HasTo

`func (o *SearchConsoleAiVisibilityGapsResponse) HasTo() bool`

HasTo returns a boolean if a field has been set.

### GetDataThrough

`func (o *SearchConsoleAiVisibilityGapsResponse) GetDataThrough() string`

GetDataThrough returns the DataThrough field if non-nil, zero value otherwise.

### GetDataThroughOk

`func (o *SearchConsoleAiVisibilityGapsResponse) GetDataThroughOk() (*string, bool)`

GetDataThroughOk returns a tuple with the DataThrough field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDataThrough

`func (o *SearchConsoleAiVisibilityGapsResponse) SetDataThrough(v string)`

SetDataThrough sets DataThrough field to given value.

### HasDataThrough

`func (o *SearchConsoleAiVisibilityGapsResponse) HasDataThrough() bool`

HasDataThrough returns a boolean if a field has been set.

### SetDataThroughNil

`func (o *SearchConsoleAiVisibilityGapsResponse) SetDataThroughNil(b bool)`

 SetDataThroughNil sets the value for DataThrough to be an explicit nil

### UnsetDataThrough
`func (o *SearchConsoleAiVisibilityGapsResponse) UnsetDataThrough()`

UnsetDataThrough ensures that no value is present for DataThrough, not even an explicit nil
### GetMinImpressions

`func (o *SearchConsoleAiVisibilityGapsResponse) GetMinImpressions() int32`

GetMinImpressions returns the MinImpressions field if non-nil, zero value otherwise.

### GetMinImpressionsOk

`func (o *SearchConsoleAiVisibilityGapsResponse) GetMinImpressionsOk() (*int32, bool)`

GetMinImpressionsOk returns a tuple with the MinImpressions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMinImpressions

`func (o *SearchConsoleAiVisibilityGapsResponse) SetMinImpressions(v int32)`

SetMinImpressions sets MinImpressions field to given value.

### HasMinImpressions

`func (o *SearchConsoleAiVisibilityGapsResponse) HasMinImpressions() bool`

HasMinImpressions returns a boolean if a field has been set.

### GetUnmatchedOnly

`func (o *SearchConsoleAiVisibilityGapsResponse) GetUnmatchedOnly() bool`

GetUnmatchedOnly returns the UnmatchedOnly field if non-nil, zero value otherwise.

### GetUnmatchedOnlyOk

`func (o *SearchConsoleAiVisibilityGapsResponse) GetUnmatchedOnlyOk() (*bool, bool)`

GetUnmatchedOnlyOk returns a tuple with the UnmatchedOnly field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnmatchedOnly

`func (o *SearchConsoleAiVisibilityGapsResponse) SetUnmatchedOnly(v bool)`

SetUnmatchedOnly sets UnmatchedOnly field to given value.

### HasUnmatchedOnly

`func (o *SearchConsoleAiVisibilityGapsResponse) HasUnmatchedOnly() bool`

HasUnmatchedOnly returns a boolean if a field has been set.

### GetMatchedCount

`func (o *SearchConsoleAiVisibilityGapsResponse) GetMatchedCount() int32`

GetMatchedCount returns the MatchedCount field if non-nil, zero value otherwise.

### GetMatchedCountOk

`func (o *SearchConsoleAiVisibilityGapsResponse) GetMatchedCountOk() (*int32, bool)`

GetMatchedCountOk returns a tuple with the MatchedCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMatchedCount

`func (o *SearchConsoleAiVisibilityGapsResponse) SetMatchedCount(v int32)`

SetMatchedCount sets MatchedCount field to given value.

### HasMatchedCount

`func (o *SearchConsoleAiVisibilityGapsResponse) HasMatchedCount() bool`

HasMatchedCount returns a boolean if a field has been set.

### GetPage

`func (o *SearchConsoleAiVisibilityGapsResponse) GetPage() int32`

GetPage returns the Page field if non-nil, zero value otherwise.

### GetPageOk

`func (o *SearchConsoleAiVisibilityGapsResponse) GetPageOk() (*int32, bool)`

GetPageOk returns a tuple with the Page field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPage

`func (o *SearchConsoleAiVisibilityGapsResponse) SetPage(v int32)`

SetPage sets Page field to given value.

### HasPage

`func (o *SearchConsoleAiVisibilityGapsResponse) HasPage() bool`

HasPage returns a boolean if a field has been set.

### GetPerPage

`func (o *SearchConsoleAiVisibilityGapsResponse) GetPerPage() int32`

GetPerPage returns the PerPage field if non-nil, zero value otherwise.

### GetPerPageOk

`func (o *SearchConsoleAiVisibilityGapsResponse) GetPerPageOk() (*int32, bool)`

GetPerPageOk returns a tuple with the PerPage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPerPage

`func (o *SearchConsoleAiVisibilityGapsResponse) SetPerPage(v int32)`

SetPerPage sets PerPage field to given value.

### HasPerPage

`func (o *SearchConsoleAiVisibilityGapsResponse) HasPerPage() bool`

HasPerPage returns a boolean if a field has been set.

### GetTotal

`func (o *SearchConsoleAiVisibilityGapsResponse) GetTotal() int32`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *SearchConsoleAiVisibilityGapsResponse) GetTotalOk() (*int32, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *SearchConsoleAiVisibilityGapsResponse) SetTotal(v int32)`

SetTotal sets Total field to given value.

### HasTotal

`func (o *SearchConsoleAiVisibilityGapsResponse) HasTotal() bool`

HasTotal returns a boolean if a field has been set.

### GetTruncated

`func (o *SearchConsoleAiVisibilityGapsResponse) GetTruncated() bool`

GetTruncated returns the Truncated field if non-nil, zero value otherwise.

### GetTruncatedOk

`func (o *SearchConsoleAiVisibilityGapsResponse) GetTruncatedOk() (*bool, bool)`

GetTruncatedOk returns a tuple with the Truncated field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTruncated

`func (o *SearchConsoleAiVisibilityGapsResponse) SetTruncated(v bool)`

SetTruncated sets Truncated field to given value.

### HasTruncated

`func (o *SearchConsoleAiVisibilityGapsResponse) HasTruncated() bool`

HasTruncated returns a boolean if a field has been set.

### GetData

`func (o *SearchConsoleAiVisibilityGapsResponse) GetData() []SearchConsoleAiVisibilityGapsResponseDataInner`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *SearchConsoleAiVisibilityGapsResponse) GetDataOk() (*[]SearchConsoleAiVisibilityGapsResponseDataInner, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *SearchConsoleAiVisibilityGapsResponse) SetData(v []SearchConsoleAiVisibilityGapsResponseDataInner)`

SetData sets Data field to given value.

### HasData

`func (o *SearchConsoleAiVisibilityGapsResponse) HasData() bool`

HasData returns a boolean if a field has been set.

### GetRequestId

`func (o *SearchConsoleAiVisibilityGapsResponse) GetRequestId() string`

GetRequestId returns the RequestId field if non-nil, zero value otherwise.

### GetRequestIdOk

`func (o *SearchConsoleAiVisibilityGapsResponse) GetRequestIdOk() (*string, bool)`

GetRequestIdOk returns a tuple with the RequestId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestId

`func (o *SearchConsoleAiVisibilityGapsResponse) SetRequestId(v string)`

SetRequestId sets RequestId field to given value.

### HasRequestId

`func (o *SearchConsoleAiVisibilityGapsResponse) HasRequestId() bool`

HasRequestId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


