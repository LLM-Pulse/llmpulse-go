# SearchConsoleListResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ProjectId** | Pointer to **int32** |  | [optional] 
**Property** | Pointer to [**SearchConsoleProperty**](SearchConsoleProperty.md) |  | [optional] 
**From** | Pointer to **string** |  | [optional] 
**To** | Pointer to **string** |  | [optional] 
**DataThrough** | Pointer to **NullableString** | Latest date Google has published for the property (it lags 2-3 days). Later days are missing, not zero. | [optional] 
**Page** | Pointer to **int32** |  | [optional] 
**PerPage** | Pointer to **int32** |  | [optional] 
**Total** | Pointer to **int32** | Rows in this window (one Google request, at most 25,000) | [optional] 
**Sort** | Pointer to **string** |  | [optional] 
**StartRow** | Pointer to **int32** | Present when start_row was set | [optional] 
**Truncated** | Pointer to **bool** | Present (true) when Google returned 25,000 rows, so more rows exist past this window | [optional] 
**Data** | Pointer to [**[]SearchConsoleListResponseDataInner**](SearchConsoleListResponseDataInner.md) |  | [optional] 
**RequestId** | Pointer to **string** |  | [optional] 

## Methods

### NewSearchConsoleListResponse

`func NewSearchConsoleListResponse() *SearchConsoleListResponse`

NewSearchConsoleListResponse instantiates a new SearchConsoleListResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSearchConsoleListResponseWithDefaults

`func NewSearchConsoleListResponseWithDefaults() *SearchConsoleListResponse`

NewSearchConsoleListResponseWithDefaults instantiates a new SearchConsoleListResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProjectId

`func (o *SearchConsoleListResponse) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *SearchConsoleListResponse) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *SearchConsoleListResponse) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.

### HasProjectId

`func (o *SearchConsoleListResponse) HasProjectId() bool`

HasProjectId returns a boolean if a field has been set.

### GetProperty

`func (o *SearchConsoleListResponse) GetProperty() SearchConsoleProperty`

GetProperty returns the Property field if non-nil, zero value otherwise.

### GetPropertyOk

`func (o *SearchConsoleListResponse) GetPropertyOk() (*SearchConsoleProperty, bool)`

GetPropertyOk returns a tuple with the Property field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProperty

`func (o *SearchConsoleListResponse) SetProperty(v SearchConsoleProperty)`

SetProperty sets Property field to given value.

### HasProperty

`func (o *SearchConsoleListResponse) HasProperty() bool`

HasProperty returns a boolean if a field has been set.

### GetFrom

`func (o *SearchConsoleListResponse) GetFrom() string`

GetFrom returns the From field if non-nil, zero value otherwise.

### GetFromOk

`func (o *SearchConsoleListResponse) GetFromOk() (*string, bool)`

GetFromOk returns a tuple with the From field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFrom

`func (o *SearchConsoleListResponse) SetFrom(v string)`

SetFrom sets From field to given value.

### HasFrom

`func (o *SearchConsoleListResponse) HasFrom() bool`

HasFrom returns a boolean if a field has been set.

### GetTo

`func (o *SearchConsoleListResponse) GetTo() string`

GetTo returns the To field if non-nil, zero value otherwise.

### GetToOk

`func (o *SearchConsoleListResponse) GetToOk() (*string, bool)`

GetToOk returns a tuple with the To field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTo

`func (o *SearchConsoleListResponse) SetTo(v string)`

SetTo sets To field to given value.

### HasTo

`func (o *SearchConsoleListResponse) HasTo() bool`

HasTo returns a boolean if a field has been set.

### GetDataThrough

`func (o *SearchConsoleListResponse) GetDataThrough() string`

GetDataThrough returns the DataThrough field if non-nil, zero value otherwise.

### GetDataThroughOk

`func (o *SearchConsoleListResponse) GetDataThroughOk() (*string, bool)`

GetDataThroughOk returns a tuple with the DataThrough field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDataThrough

`func (o *SearchConsoleListResponse) SetDataThrough(v string)`

SetDataThrough sets DataThrough field to given value.

### HasDataThrough

`func (o *SearchConsoleListResponse) HasDataThrough() bool`

HasDataThrough returns a boolean if a field has been set.

### SetDataThroughNil

`func (o *SearchConsoleListResponse) SetDataThroughNil(b bool)`

 SetDataThroughNil sets the value for DataThrough to be an explicit nil

### UnsetDataThrough
`func (o *SearchConsoleListResponse) UnsetDataThrough()`

UnsetDataThrough ensures that no value is present for DataThrough, not even an explicit nil
### GetPage

`func (o *SearchConsoleListResponse) GetPage() int32`

GetPage returns the Page field if non-nil, zero value otherwise.

### GetPageOk

`func (o *SearchConsoleListResponse) GetPageOk() (*int32, bool)`

GetPageOk returns a tuple with the Page field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPage

`func (o *SearchConsoleListResponse) SetPage(v int32)`

SetPage sets Page field to given value.

### HasPage

`func (o *SearchConsoleListResponse) HasPage() bool`

HasPage returns a boolean if a field has been set.

### GetPerPage

`func (o *SearchConsoleListResponse) GetPerPage() int32`

GetPerPage returns the PerPage field if non-nil, zero value otherwise.

### GetPerPageOk

`func (o *SearchConsoleListResponse) GetPerPageOk() (*int32, bool)`

GetPerPageOk returns a tuple with the PerPage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPerPage

`func (o *SearchConsoleListResponse) SetPerPage(v int32)`

SetPerPage sets PerPage field to given value.

### HasPerPage

`func (o *SearchConsoleListResponse) HasPerPage() bool`

HasPerPage returns a boolean if a field has been set.

### GetTotal

`func (o *SearchConsoleListResponse) GetTotal() int32`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *SearchConsoleListResponse) GetTotalOk() (*int32, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *SearchConsoleListResponse) SetTotal(v int32)`

SetTotal sets Total field to given value.

### HasTotal

`func (o *SearchConsoleListResponse) HasTotal() bool`

HasTotal returns a boolean if a field has been set.

### GetSort

`func (o *SearchConsoleListResponse) GetSort() string`

GetSort returns the Sort field if non-nil, zero value otherwise.

### GetSortOk

`func (o *SearchConsoleListResponse) GetSortOk() (*string, bool)`

GetSortOk returns a tuple with the Sort field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSort

`func (o *SearchConsoleListResponse) SetSort(v string)`

SetSort sets Sort field to given value.

### HasSort

`func (o *SearchConsoleListResponse) HasSort() bool`

HasSort returns a boolean if a field has been set.

### GetStartRow

`func (o *SearchConsoleListResponse) GetStartRow() int32`

GetStartRow returns the StartRow field if non-nil, zero value otherwise.

### GetStartRowOk

`func (o *SearchConsoleListResponse) GetStartRowOk() (*int32, bool)`

GetStartRowOk returns a tuple with the StartRow field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartRow

`func (o *SearchConsoleListResponse) SetStartRow(v int32)`

SetStartRow sets StartRow field to given value.

### HasStartRow

`func (o *SearchConsoleListResponse) HasStartRow() bool`

HasStartRow returns a boolean if a field has been set.

### GetTruncated

`func (o *SearchConsoleListResponse) GetTruncated() bool`

GetTruncated returns the Truncated field if non-nil, zero value otherwise.

### GetTruncatedOk

`func (o *SearchConsoleListResponse) GetTruncatedOk() (*bool, bool)`

GetTruncatedOk returns a tuple with the Truncated field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTruncated

`func (o *SearchConsoleListResponse) SetTruncated(v bool)`

SetTruncated sets Truncated field to given value.

### HasTruncated

`func (o *SearchConsoleListResponse) HasTruncated() bool`

HasTruncated returns a boolean if a field has been set.

### GetData

`func (o *SearchConsoleListResponse) GetData() []SearchConsoleListResponseDataInner`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *SearchConsoleListResponse) GetDataOk() (*[]SearchConsoleListResponseDataInner, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *SearchConsoleListResponse) SetData(v []SearchConsoleListResponseDataInner)`

SetData sets Data field to given value.

### HasData

`func (o *SearchConsoleListResponse) HasData() bool`

HasData returns a boolean if a field has been set.

### GetRequestId

`func (o *SearchConsoleListResponse) GetRequestId() string`

GetRequestId returns the RequestId field if non-nil, zero value otherwise.

### GetRequestIdOk

`func (o *SearchConsoleListResponse) GetRequestIdOk() (*string, bool)`

GetRequestIdOk returns a tuple with the RequestId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestId

`func (o *SearchConsoleListResponse) SetRequestId(v string)`

SetRequestId sets RequestId field to given value.

### HasRequestId

`func (o *SearchConsoleListResponse) HasRequestId() bool`

HasRequestId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


