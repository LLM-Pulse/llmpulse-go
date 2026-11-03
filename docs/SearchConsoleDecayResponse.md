# SearchConsoleDecayResponse

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
**Dimension** | Pointer to **string** |  | [optional] 
**ComparedThrough** | Pointer to **string** | Last day of the requested window that is compared, to or the last day Google has published when that is earlier | [optional] 
**PreviousFrom** | Pointer to **string** | Start of the window compared against, the same length as from..compared_through and just before it | [optional] 
**PreviousTo** | Pointer to **string** |  | [optional] 
**MinClicks** | Pointer to **int32** |  | [optional] 
**Page** | Pointer to **int32** |  | [optional] 
**PerPage** | Pointer to **int32** |  | [optional] 
**Total** | Pointer to **int32** | Rows in the report before paging | [optional] 
**Truncated** | Pointer to **bool** | Present (true) when Google returned its 25,000-row maximum for a property, so the report covers its top rows only | [optional] 
**Data** | Pointer to [**[]SearchConsoleDecayResponseDataInner**](SearchConsoleDecayResponseDataInner.md) |  | [optional] 
**RequestId** | Pointer to **string** |  | [optional] 

## Methods

### NewSearchConsoleDecayResponse

`func NewSearchConsoleDecayResponse() *SearchConsoleDecayResponse`

NewSearchConsoleDecayResponse instantiates a new SearchConsoleDecayResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSearchConsoleDecayResponseWithDefaults

`func NewSearchConsoleDecayResponseWithDefaults() *SearchConsoleDecayResponse`

NewSearchConsoleDecayResponseWithDefaults instantiates a new SearchConsoleDecayResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProjectId

`func (o *SearchConsoleDecayResponse) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *SearchConsoleDecayResponse) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *SearchConsoleDecayResponse) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.

### HasProjectId

`func (o *SearchConsoleDecayResponse) HasProjectId() bool`

HasProjectId returns a boolean if a field has been set.

### GetProperty

`func (o *SearchConsoleDecayResponse) GetProperty() SearchConsoleProperty`

GetProperty returns the Property field if non-nil, zero value otherwise.

### GetPropertyOk

`func (o *SearchConsoleDecayResponse) GetPropertyOk() (*SearchConsoleProperty, bool)`

GetPropertyOk returns a tuple with the Property field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProperty

`func (o *SearchConsoleDecayResponse) SetProperty(v SearchConsoleProperty)`

SetProperty sets Property field to given value.

### HasProperty

`func (o *SearchConsoleDecayResponse) HasProperty() bool`

HasProperty returns a boolean if a field has been set.

### GetProperties

`func (o *SearchConsoleDecayResponse) GetProperties() []SearchConsoleProperty`

GetProperties returns the Properties field if non-nil, zero value otherwise.

### GetPropertiesOk

`func (o *SearchConsoleDecayResponse) GetPropertiesOk() (*[]SearchConsoleProperty, bool)`

GetPropertiesOk returns a tuple with the Properties field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProperties

`func (o *SearchConsoleDecayResponse) SetProperties(v []SearchConsoleProperty)`

SetProperties sets Properties field to given value.

### HasProperties

`func (o *SearchConsoleDecayResponse) HasProperties() bool`

HasProperties returns a boolean if a field has been set.

### GetExcludedProperties

`func (o *SearchConsoleDecayResponse) GetExcludedProperties() []SearchConsoleExcludedProperty`

GetExcludedProperties returns the ExcludedProperties field if non-nil, zero value otherwise.

### GetExcludedPropertiesOk

`func (o *SearchConsoleDecayResponse) GetExcludedPropertiesOk() (*[]SearchConsoleExcludedProperty, bool)`

GetExcludedPropertiesOk returns a tuple with the ExcludedProperties field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExcludedProperties

`func (o *SearchConsoleDecayResponse) SetExcludedProperties(v []SearchConsoleExcludedProperty)`

SetExcludedProperties sets ExcludedProperties field to given value.

### HasExcludedProperties

`func (o *SearchConsoleDecayResponse) HasExcludedProperties() bool`

HasExcludedProperties returns a boolean if a field has been set.

### GetPropertyErrors

`func (o *SearchConsoleDecayResponse) GetPropertyErrors() []SearchConsolePropertyError`

GetPropertyErrors returns the PropertyErrors field if non-nil, zero value otherwise.

### GetPropertyErrorsOk

`func (o *SearchConsoleDecayResponse) GetPropertyErrorsOk() (*[]SearchConsolePropertyError, bool)`

GetPropertyErrorsOk returns a tuple with the PropertyErrors field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPropertyErrors

`func (o *SearchConsoleDecayResponse) SetPropertyErrors(v []SearchConsolePropertyError)`

SetPropertyErrors sets PropertyErrors field to given value.

### HasPropertyErrors

`func (o *SearchConsoleDecayResponse) HasPropertyErrors() bool`

HasPropertyErrors returns a boolean if a field has been set.

### GetFrom

`func (o *SearchConsoleDecayResponse) GetFrom() string`

GetFrom returns the From field if non-nil, zero value otherwise.

### GetFromOk

`func (o *SearchConsoleDecayResponse) GetFromOk() (*string, bool)`

GetFromOk returns a tuple with the From field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFrom

`func (o *SearchConsoleDecayResponse) SetFrom(v string)`

SetFrom sets From field to given value.

### HasFrom

`func (o *SearchConsoleDecayResponse) HasFrom() bool`

HasFrom returns a boolean if a field has been set.

### GetTo

`func (o *SearchConsoleDecayResponse) GetTo() string`

GetTo returns the To field if non-nil, zero value otherwise.

### GetToOk

`func (o *SearchConsoleDecayResponse) GetToOk() (*string, bool)`

GetToOk returns a tuple with the To field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTo

`func (o *SearchConsoleDecayResponse) SetTo(v string)`

SetTo sets To field to given value.

### HasTo

`func (o *SearchConsoleDecayResponse) HasTo() bool`

HasTo returns a boolean if a field has been set.

### GetDataThrough

`func (o *SearchConsoleDecayResponse) GetDataThrough() string`

GetDataThrough returns the DataThrough field if non-nil, zero value otherwise.

### GetDataThroughOk

`func (o *SearchConsoleDecayResponse) GetDataThroughOk() (*string, bool)`

GetDataThroughOk returns a tuple with the DataThrough field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDataThrough

`func (o *SearchConsoleDecayResponse) SetDataThrough(v string)`

SetDataThrough sets DataThrough field to given value.

### HasDataThrough

`func (o *SearchConsoleDecayResponse) HasDataThrough() bool`

HasDataThrough returns a boolean if a field has been set.

### SetDataThroughNil

`func (o *SearchConsoleDecayResponse) SetDataThroughNil(b bool)`

 SetDataThroughNil sets the value for DataThrough to be an explicit nil

### UnsetDataThrough
`func (o *SearchConsoleDecayResponse) UnsetDataThrough()`

UnsetDataThrough ensures that no value is present for DataThrough, not even an explicit nil
### GetDimension

`func (o *SearchConsoleDecayResponse) GetDimension() string`

GetDimension returns the Dimension field if non-nil, zero value otherwise.

### GetDimensionOk

`func (o *SearchConsoleDecayResponse) GetDimensionOk() (*string, bool)`

GetDimensionOk returns a tuple with the Dimension field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDimension

`func (o *SearchConsoleDecayResponse) SetDimension(v string)`

SetDimension sets Dimension field to given value.

### HasDimension

`func (o *SearchConsoleDecayResponse) HasDimension() bool`

HasDimension returns a boolean if a field has been set.

### GetComparedThrough

`func (o *SearchConsoleDecayResponse) GetComparedThrough() string`

GetComparedThrough returns the ComparedThrough field if non-nil, zero value otherwise.

### GetComparedThroughOk

`func (o *SearchConsoleDecayResponse) GetComparedThroughOk() (*string, bool)`

GetComparedThroughOk returns a tuple with the ComparedThrough field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComparedThrough

`func (o *SearchConsoleDecayResponse) SetComparedThrough(v string)`

SetComparedThrough sets ComparedThrough field to given value.

### HasComparedThrough

`func (o *SearchConsoleDecayResponse) HasComparedThrough() bool`

HasComparedThrough returns a boolean if a field has been set.

### GetPreviousFrom

`func (o *SearchConsoleDecayResponse) GetPreviousFrom() string`

GetPreviousFrom returns the PreviousFrom field if non-nil, zero value otherwise.

### GetPreviousFromOk

`func (o *SearchConsoleDecayResponse) GetPreviousFromOk() (*string, bool)`

GetPreviousFromOk returns a tuple with the PreviousFrom field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPreviousFrom

`func (o *SearchConsoleDecayResponse) SetPreviousFrom(v string)`

SetPreviousFrom sets PreviousFrom field to given value.

### HasPreviousFrom

`func (o *SearchConsoleDecayResponse) HasPreviousFrom() bool`

HasPreviousFrom returns a boolean if a field has been set.

### GetPreviousTo

`func (o *SearchConsoleDecayResponse) GetPreviousTo() string`

GetPreviousTo returns the PreviousTo field if non-nil, zero value otherwise.

### GetPreviousToOk

`func (o *SearchConsoleDecayResponse) GetPreviousToOk() (*string, bool)`

GetPreviousToOk returns a tuple with the PreviousTo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPreviousTo

`func (o *SearchConsoleDecayResponse) SetPreviousTo(v string)`

SetPreviousTo sets PreviousTo field to given value.

### HasPreviousTo

`func (o *SearchConsoleDecayResponse) HasPreviousTo() bool`

HasPreviousTo returns a boolean if a field has been set.

### GetMinClicks

`func (o *SearchConsoleDecayResponse) GetMinClicks() int32`

GetMinClicks returns the MinClicks field if non-nil, zero value otherwise.

### GetMinClicksOk

`func (o *SearchConsoleDecayResponse) GetMinClicksOk() (*int32, bool)`

GetMinClicksOk returns a tuple with the MinClicks field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMinClicks

`func (o *SearchConsoleDecayResponse) SetMinClicks(v int32)`

SetMinClicks sets MinClicks field to given value.

### HasMinClicks

`func (o *SearchConsoleDecayResponse) HasMinClicks() bool`

HasMinClicks returns a boolean if a field has been set.

### GetPage

`func (o *SearchConsoleDecayResponse) GetPage() int32`

GetPage returns the Page field if non-nil, zero value otherwise.

### GetPageOk

`func (o *SearchConsoleDecayResponse) GetPageOk() (*int32, bool)`

GetPageOk returns a tuple with the Page field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPage

`func (o *SearchConsoleDecayResponse) SetPage(v int32)`

SetPage sets Page field to given value.

### HasPage

`func (o *SearchConsoleDecayResponse) HasPage() bool`

HasPage returns a boolean if a field has been set.

### GetPerPage

`func (o *SearchConsoleDecayResponse) GetPerPage() int32`

GetPerPage returns the PerPage field if non-nil, zero value otherwise.

### GetPerPageOk

`func (o *SearchConsoleDecayResponse) GetPerPageOk() (*int32, bool)`

GetPerPageOk returns a tuple with the PerPage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPerPage

`func (o *SearchConsoleDecayResponse) SetPerPage(v int32)`

SetPerPage sets PerPage field to given value.

### HasPerPage

`func (o *SearchConsoleDecayResponse) HasPerPage() bool`

HasPerPage returns a boolean if a field has been set.

### GetTotal

`func (o *SearchConsoleDecayResponse) GetTotal() int32`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *SearchConsoleDecayResponse) GetTotalOk() (*int32, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *SearchConsoleDecayResponse) SetTotal(v int32)`

SetTotal sets Total field to given value.

### HasTotal

`func (o *SearchConsoleDecayResponse) HasTotal() bool`

HasTotal returns a boolean if a field has been set.

### GetTruncated

`func (o *SearchConsoleDecayResponse) GetTruncated() bool`

GetTruncated returns the Truncated field if non-nil, zero value otherwise.

### GetTruncatedOk

`func (o *SearchConsoleDecayResponse) GetTruncatedOk() (*bool, bool)`

GetTruncatedOk returns a tuple with the Truncated field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTruncated

`func (o *SearchConsoleDecayResponse) SetTruncated(v bool)`

SetTruncated sets Truncated field to given value.

### HasTruncated

`func (o *SearchConsoleDecayResponse) HasTruncated() bool`

HasTruncated returns a boolean if a field has been set.

### GetData

`func (o *SearchConsoleDecayResponse) GetData() []SearchConsoleDecayResponseDataInner`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *SearchConsoleDecayResponse) GetDataOk() (*[]SearchConsoleDecayResponseDataInner, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *SearchConsoleDecayResponse) SetData(v []SearchConsoleDecayResponseDataInner)`

SetData sets Data field to given value.

### HasData

`func (o *SearchConsoleDecayResponse) HasData() bool`

HasData returns a boolean if a field has been set.

### GetRequestId

`func (o *SearchConsoleDecayResponse) GetRequestId() string`

GetRequestId returns the RequestId field if non-nil, zero value otherwise.

### GetRequestIdOk

`func (o *SearchConsoleDecayResponse) GetRequestIdOk() (*string, bool)`

GetRequestIdOk returns a tuple with the RequestId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestId

`func (o *SearchConsoleDecayResponse) SetRequestId(v string)`

SetRequestId sets RequestId field to given value.

### HasRequestId

`func (o *SearchConsoleDecayResponse) HasRequestId() bool`

HasRequestId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


