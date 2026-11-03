# SearchConsoleOpportunitiesResponse

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
**MinPosition** | Pointer to **float32** |  | [optional] 
**MaxPosition** | Pointer to **float32** |  | [optional] 
**TopCtr** | Pointer to **NullableFloat32** | CTR (0..1) of the property&#39;s queries averaging position 3 or better in the window; null when there are none, and then no potential_clicks | [optional] 
**Page** | Pointer to **int32** |  | [optional] 
**PerPage** | Pointer to **int32** |  | [optional] 
**Total** | Pointer to **int32** | Rows in the report before paging | [optional] 
**Truncated** | Pointer to **bool** | Present (true) when Google returned its 25,000-row maximum for a property, so the report covers its top rows only | [optional] 
**Data** | Pointer to [**[]SearchConsoleOpportunitiesResponseDataInner**](SearchConsoleOpportunitiesResponseDataInner.md) |  | [optional] 
**RequestId** | Pointer to **string** |  | [optional] 

## Methods

### NewSearchConsoleOpportunitiesResponse

`func NewSearchConsoleOpportunitiesResponse() *SearchConsoleOpportunitiesResponse`

NewSearchConsoleOpportunitiesResponse instantiates a new SearchConsoleOpportunitiesResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSearchConsoleOpportunitiesResponseWithDefaults

`func NewSearchConsoleOpportunitiesResponseWithDefaults() *SearchConsoleOpportunitiesResponse`

NewSearchConsoleOpportunitiesResponseWithDefaults instantiates a new SearchConsoleOpportunitiesResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProjectId

`func (o *SearchConsoleOpportunitiesResponse) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *SearchConsoleOpportunitiesResponse) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *SearchConsoleOpportunitiesResponse) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.

### HasProjectId

`func (o *SearchConsoleOpportunitiesResponse) HasProjectId() bool`

HasProjectId returns a boolean if a field has been set.

### GetProperty

`func (o *SearchConsoleOpportunitiesResponse) GetProperty() SearchConsoleProperty`

GetProperty returns the Property field if non-nil, zero value otherwise.

### GetPropertyOk

`func (o *SearchConsoleOpportunitiesResponse) GetPropertyOk() (*SearchConsoleProperty, bool)`

GetPropertyOk returns a tuple with the Property field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProperty

`func (o *SearchConsoleOpportunitiesResponse) SetProperty(v SearchConsoleProperty)`

SetProperty sets Property field to given value.

### HasProperty

`func (o *SearchConsoleOpportunitiesResponse) HasProperty() bool`

HasProperty returns a boolean if a field has been set.

### GetProperties

`func (o *SearchConsoleOpportunitiesResponse) GetProperties() []SearchConsoleProperty`

GetProperties returns the Properties field if non-nil, zero value otherwise.

### GetPropertiesOk

`func (o *SearchConsoleOpportunitiesResponse) GetPropertiesOk() (*[]SearchConsoleProperty, bool)`

GetPropertiesOk returns a tuple with the Properties field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProperties

`func (o *SearchConsoleOpportunitiesResponse) SetProperties(v []SearchConsoleProperty)`

SetProperties sets Properties field to given value.

### HasProperties

`func (o *SearchConsoleOpportunitiesResponse) HasProperties() bool`

HasProperties returns a boolean if a field has been set.

### GetExcludedProperties

`func (o *SearchConsoleOpportunitiesResponse) GetExcludedProperties() []SearchConsoleExcludedProperty`

GetExcludedProperties returns the ExcludedProperties field if non-nil, zero value otherwise.

### GetExcludedPropertiesOk

`func (o *SearchConsoleOpportunitiesResponse) GetExcludedPropertiesOk() (*[]SearchConsoleExcludedProperty, bool)`

GetExcludedPropertiesOk returns a tuple with the ExcludedProperties field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExcludedProperties

`func (o *SearchConsoleOpportunitiesResponse) SetExcludedProperties(v []SearchConsoleExcludedProperty)`

SetExcludedProperties sets ExcludedProperties field to given value.

### HasExcludedProperties

`func (o *SearchConsoleOpportunitiesResponse) HasExcludedProperties() bool`

HasExcludedProperties returns a boolean if a field has been set.

### GetPropertyErrors

`func (o *SearchConsoleOpportunitiesResponse) GetPropertyErrors() []SearchConsolePropertyError`

GetPropertyErrors returns the PropertyErrors field if non-nil, zero value otherwise.

### GetPropertyErrorsOk

`func (o *SearchConsoleOpportunitiesResponse) GetPropertyErrorsOk() (*[]SearchConsolePropertyError, bool)`

GetPropertyErrorsOk returns a tuple with the PropertyErrors field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPropertyErrors

`func (o *SearchConsoleOpportunitiesResponse) SetPropertyErrors(v []SearchConsolePropertyError)`

SetPropertyErrors sets PropertyErrors field to given value.

### HasPropertyErrors

`func (o *SearchConsoleOpportunitiesResponse) HasPropertyErrors() bool`

HasPropertyErrors returns a boolean if a field has been set.

### GetFrom

`func (o *SearchConsoleOpportunitiesResponse) GetFrom() string`

GetFrom returns the From field if non-nil, zero value otherwise.

### GetFromOk

`func (o *SearchConsoleOpportunitiesResponse) GetFromOk() (*string, bool)`

GetFromOk returns a tuple with the From field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFrom

`func (o *SearchConsoleOpportunitiesResponse) SetFrom(v string)`

SetFrom sets From field to given value.

### HasFrom

`func (o *SearchConsoleOpportunitiesResponse) HasFrom() bool`

HasFrom returns a boolean if a field has been set.

### GetTo

`func (o *SearchConsoleOpportunitiesResponse) GetTo() string`

GetTo returns the To field if non-nil, zero value otherwise.

### GetToOk

`func (o *SearchConsoleOpportunitiesResponse) GetToOk() (*string, bool)`

GetToOk returns a tuple with the To field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTo

`func (o *SearchConsoleOpportunitiesResponse) SetTo(v string)`

SetTo sets To field to given value.

### HasTo

`func (o *SearchConsoleOpportunitiesResponse) HasTo() bool`

HasTo returns a boolean if a field has been set.

### GetDataThrough

`func (o *SearchConsoleOpportunitiesResponse) GetDataThrough() string`

GetDataThrough returns the DataThrough field if non-nil, zero value otherwise.

### GetDataThroughOk

`func (o *SearchConsoleOpportunitiesResponse) GetDataThroughOk() (*string, bool)`

GetDataThroughOk returns a tuple with the DataThrough field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDataThrough

`func (o *SearchConsoleOpportunitiesResponse) SetDataThrough(v string)`

SetDataThrough sets DataThrough field to given value.

### HasDataThrough

`func (o *SearchConsoleOpportunitiesResponse) HasDataThrough() bool`

HasDataThrough returns a boolean if a field has been set.

### SetDataThroughNil

`func (o *SearchConsoleOpportunitiesResponse) SetDataThroughNil(b bool)`

 SetDataThroughNil sets the value for DataThrough to be an explicit nil

### UnsetDataThrough
`func (o *SearchConsoleOpportunitiesResponse) UnsetDataThrough()`

UnsetDataThrough ensures that no value is present for DataThrough, not even an explicit nil
### GetMinImpressions

`func (o *SearchConsoleOpportunitiesResponse) GetMinImpressions() int32`

GetMinImpressions returns the MinImpressions field if non-nil, zero value otherwise.

### GetMinImpressionsOk

`func (o *SearchConsoleOpportunitiesResponse) GetMinImpressionsOk() (*int32, bool)`

GetMinImpressionsOk returns a tuple with the MinImpressions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMinImpressions

`func (o *SearchConsoleOpportunitiesResponse) SetMinImpressions(v int32)`

SetMinImpressions sets MinImpressions field to given value.

### HasMinImpressions

`func (o *SearchConsoleOpportunitiesResponse) HasMinImpressions() bool`

HasMinImpressions returns a boolean if a field has been set.

### GetMinPosition

`func (o *SearchConsoleOpportunitiesResponse) GetMinPosition() float32`

GetMinPosition returns the MinPosition field if non-nil, zero value otherwise.

### GetMinPositionOk

`func (o *SearchConsoleOpportunitiesResponse) GetMinPositionOk() (*float32, bool)`

GetMinPositionOk returns a tuple with the MinPosition field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMinPosition

`func (o *SearchConsoleOpportunitiesResponse) SetMinPosition(v float32)`

SetMinPosition sets MinPosition field to given value.

### HasMinPosition

`func (o *SearchConsoleOpportunitiesResponse) HasMinPosition() bool`

HasMinPosition returns a boolean if a field has been set.

### GetMaxPosition

`func (o *SearchConsoleOpportunitiesResponse) GetMaxPosition() float32`

GetMaxPosition returns the MaxPosition field if non-nil, zero value otherwise.

### GetMaxPositionOk

`func (o *SearchConsoleOpportunitiesResponse) GetMaxPositionOk() (*float32, bool)`

GetMaxPositionOk returns a tuple with the MaxPosition field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxPosition

`func (o *SearchConsoleOpportunitiesResponse) SetMaxPosition(v float32)`

SetMaxPosition sets MaxPosition field to given value.

### HasMaxPosition

`func (o *SearchConsoleOpportunitiesResponse) HasMaxPosition() bool`

HasMaxPosition returns a boolean if a field has been set.

### GetTopCtr

`func (o *SearchConsoleOpportunitiesResponse) GetTopCtr() float32`

GetTopCtr returns the TopCtr field if non-nil, zero value otherwise.

### GetTopCtrOk

`func (o *SearchConsoleOpportunitiesResponse) GetTopCtrOk() (*float32, bool)`

GetTopCtrOk returns a tuple with the TopCtr field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTopCtr

`func (o *SearchConsoleOpportunitiesResponse) SetTopCtr(v float32)`

SetTopCtr sets TopCtr field to given value.

### HasTopCtr

`func (o *SearchConsoleOpportunitiesResponse) HasTopCtr() bool`

HasTopCtr returns a boolean if a field has been set.

### SetTopCtrNil

`func (o *SearchConsoleOpportunitiesResponse) SetTopCtrNil(b bool)`

 SetTopCtrNil sets the value for TopCtr to be an explicit nil

### UnsetTopCtr
`func (o *SearchConsoleOpportunitiesResponse) UnsetTopCtr()`

UnsetTopCtr ensures that no value is present for TopCtr, not even an explicit nil
### GetPage

`func (o *SearchConsoleOpportunitiesResponse) GetPage() int32`

GetPage returns the Page field if non-nil, zero value otherwise.

### GetPageOk

`func (o *SearchConsoleOpportunitiesResponse) GetPageOk() (*int32, bool)`

GetPageOk returns a tuple with the Page field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPage

`func (o *SearchConsoleOpportunitiesResponse) SetPage(v int32)`

SetPage sets Page field to given value.

### HasPage

`func (o *SearchConsoleOpportunitiesResponse) HasPage() bool`

HasPage returns a boolean if a field has been set.

### GetPerPage

`func (o *SearchConsoleOpportunitiesResponse) GetPerPage() int32`

GetPerPage returns the PerPage field if non-nil, zero value otherwise.

### GetPerPageOk

`func (o *SearchConsoleOpportunitiesResponse) GetPerPageOk() (*int32, bool)`

GetPerPageOk returns a tuple with the PerPage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPerPage

`func (o *SearchConsoleOpportunitiesResponse) SetPerPage(v int32)`

SetPerPage sets PerPage field to given value.

### HasPerPage

`func (o *SearchConsoleOpportunitiesResponse) HasPerPage() bool`

HasPerPage returns a boolean if a field has been set.

### GetTotal

`func (o *SearchConsoleOpportunitiesResponse) GetTotal() int32`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *SearchConsoleOpportunitiesResponse) GetTotalOk() (*int32, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *SearchConsoleOpportunitiesResponse) SetTotal(v int32)`

SetTotal sets Total field to given value.

### HasTotal

`func (o *SearchConsoleOpportunitiesResponse) HasTotal() bool`

HasTotal returns a boolean if a field has been set.

### GetTruncated

`func (o *SearchConsoleOpportunitiesResponse) GetTruncated() bool`

GetTruncated returns the Truncated field if non-nil, zero value otherwise.

### GetTruncatedOk

`func (o *SearchConsoleOpportunitiesResponse) GetTruncatedOk() (*bool, bool)`

GetTruncatedOk returns a tuple with the Truncated field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTruncated

`func (o *SearchConsoleOpportunitiesResponse) SetTruncated(v bool)`

SetTruncated sets Truncated field to given value.

### HasTruncated

`func (o *SearchConsoleOpportunitiesResponse) HasTruncated() bool`

HasTruncated returns a boolean if a field has been set.

### GetData

`func (o *SearchConsoleOpportunitiesResponse) GetData() []SearchConsoleOpportunitiesResponseDataInner`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *SearchConsoleOpportunitiesResponse) GetDataOk() (*[]SearchConsoleOpportunitiesResponseDataInner, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *SearchConsoleOpportunitiesResponse) SetData(v []SearchConsoleOpportunitiesResponseDataInner)`

SetData sets Data field to given value.

### HasData

`func (o *SearchConsoleOpportunitiesResponse) HasData() bool`

HasData returns a boolean if a field has been set.

### GetRequestId

`func (o *SearchConsoleOpportunitiesResponse) GetRequestId() string`

GetRequestId returns the RequestId field if non-nil, zero value otherwise.

### GetRequestIdOk

`func (o *SearchConsoleOpportunitiesResponse) GetRequestIdOk() (*string, bool)`

GetRequestIdOk returns a tuple with the RequestId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestId

`func (o *SearchConsoleOpportunitiesResponse) SetRequestId(v string)`

SetRequestId sets RequestId field to given value.

### HasRequestId

`func (o *SearchConsoleOpportunitiesResponse) HasRequestId() bool`

HasRequestId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


