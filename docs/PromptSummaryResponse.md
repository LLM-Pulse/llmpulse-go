# PromptSummaryResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ProjectId** | Pointer to **int32** |  | [optional] 
**From** | Pointer to **time.Time** |  | [optional] 
**To** | Pointer to **time.Time** |  | [optional] 
**Filters** | Pointer to [**MetricsFiltersEcho**](MetricsFiltersEcho.md) |  | [optional] 
**Breakdown** | Pointer to **NullableString** |  | [optional] 
**Sort** | Pointer to **string** |  | [optional] 
**SortDir** | Pointer to **string** |  | [optional] 
**Page** | Pointer to **int32** |  | [optional] 
**PerPage** | Pointer to **int32** |  | [optional] 
**Total** | Pointer to **int32** |  | [optional] 
**Data** | Pointer to [**[]PromptSummaryRow**](PromptSummaryRow.md) |  | [optional] 
**RequestId** | Pointer to **string** |  | [optional] 

## Methods

### NewPromptSummaryResponse

`func NewPromptSummaryResponse() *PromptSummaryResponse`

NewPromptSummaryResponse instantiates a new PromptSummaryResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPromptSummaryResponseWithDefaults

`func NewPromptSummaryResponseWithDefaults() *PromptSummaryResponse`

NewPromptSummaryResponseWithDefaults instantiates a new PromptSummaryResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProjectId

`func (o *PromptSummaryResponse) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *PromptSummaryResponse) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *PromptSummaryResponse) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.

### HasProjectId

`func (o *PromptSummaryResponse) HasProjectId() bool`

HasProjectId returns a boolean if a field has been set.

### GetFrom

`func (o *PromptSummaryResponse) GetFrom() time.Time`

GetFrom returns the From field if non-nil, zero value otherwise.

### GetFromOk

`func (o *PromptSummaryResponse) GetFromOk() (*time.Time, bool)`

GetFromOk returns a tuple with the From field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFrom

`func (o *PromptSummaryResponse) SetFrom(v time.Time)`

SetFrom sets From field to given value.

### HasFrom

`func (o *PromptSummaryResponse) HasFrom() bool`

HasFrom returns a boolean if a field has been set.

### GetTo

`func (o *PromptSummaryResponse) GetTo() time.Time`

GetTo returns the To field if non-nil, zero value otherwise.

### GetToOk

`func (o *PromptSummaryResponse) GetToOk() (*time.Time, bool)`

GetToOk returns a tuple with the To field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTo

`func (o *PromptSummaryResponse) SetTo(v time.Time)`

SetTo sets To field to given value.

### HasTo

`func (o *PromptSummaryResponse) HasTo() bool`

HasTo returns a boolean if a field has been set.

### GetFilters

`func (o *PromptSummaryResponse) GetFilters() MetricsFiltersEcho`

GetFilters returns the Filters field if non-nil, zero value otherwise.

### GetFiltersOk

`func (o *PromptSummaryResponse) GetFiltersOk() (*MetricsFiltersEcho, bool)`

GetFiltersOk returns a tuple with the Filters field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFilters

`func (o *PromptSummaryResponse) SetFilters(v MetricsFiltersEcho)`

SetFilters sets Filters field to given value.

### HasFilters

`func (o *PromptSummaryResponse) HasFilters() bool`

HasFilters returns a boolean if a field has been set.

### GetBreakdown

`func (o *PromptSummaryResponse) GetBreakdown() string`

GetBreakdown returns the Breakdown field if non-nil, zero value otherwise.

### GetBreakdownOk

`func (o *PromptSummaryResponse) GetBreakdownOk() (*string, bool)`

GetBreakdownOk returns a tuple with the Breakdown field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBreakdown

`func (o *PromptSummaryResponse) SetBreakdown(v string)`

SetBreakdown sets Breakdown field to given value.

### HasBreakdown

`func (o *PromptSummaryResponse) HasBreakdown() bool`

HasBreakdown returns a boolean if a field has been set.

### SetBreakdownNil

`func (o *PromptSummaryResponse) SetBreakdownNil(b bool)`

 SetBreakdownNil sets the value for Breakdown to be an explicit nil

### UnsetBreakdown
`func (o *PromptSummaryResponse) UnsetBreakdown()`

UnsetBreakdown ensures that no value is present for Breakdown, not even an explicit nil
### GetSort

`func (o *PromptSummaryResponse) GetSort() string`

GetSort returns the Sort field if non-nil, zero value otherwise.

### GetSortOk

`func (o *PromptSummaryResponse) GetSortOk() (*string, bool)`

GetSortOk returns a tuple with the Sort field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSort

`func (o *PromptSummaryResponse) SetSort(v string)`

SetSort sets Sort field to given value.

### HasSort

`func (o *PromptSummaryResponse) HasSort() bool`

HasSort returns a boolean if a field has been set.

### GetSortDir

`func (o *PromptSummaryResponse) GetSortDir() string`

GetSortDir returns the SortDir field if non-nil, zero value otherwise.

### GetSortDirOk

`func (o *PromptSummaryResponse) GetSortDirOk() (*string, bool)`

GetSortDirOk returns a tuple with the SortDir field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSortDir

`func (o *PromptSummaryResponse) SetSortDir(v string)`

SetSortDir sets SortDir field to given value.

### HasSortDir

`func (o *PromptSummaryResponse) HasSortDir() bool`

HasSortDir returns a boolean if a field has been set.

### GetPage

`func (o *PromptSummaryResponse) GetPage() int32`

GetPage returns the Page field if non-nil, zero value otherwise.

### GetPageOk

`func (o *PromptSummaryResponse) GetPageOk() (*int32, bool)`

GetPageOk returns a tuple with the Page field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPage

`func (o *PromptSummaryResponse) SetPage(v int32)`

SetPage sets Page field to given value.

### HasPage

`func (o *PromptSummaryResponse) HasPage() bool`

HasPage returns a boolean if a field has been set.

### GetPerPage

`func (o *PromptSummaryResponse) GetPerPage() int32`

GetPerPage returns the PerPage field if non-nil, zero value otherwise.

### GetPerPageOk

`func (o *PromptSummaryResponse) GetPerPageOk() (*int32, bool)`

GetPerPageOk returns a tuple with the PerPage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPerPage

`func (o *PromptSummaryResponse) SetPerPage(v int32)`

SetPerPage sets PerPage field to given value.

### HasPerPage

`func (o *PromptSummaryResponse) HasPerPage() bool`

HasPerPage returns a boolean if a field has been set.

### GetTotal

`func (o *PromptSummaryResponse) GetTotal() int32`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *PromptSummaryResponse) GetTotalOk() (*int32, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *PromptSummaryResponse) SetTotal(v int32)`

SetTotal sets Total field to given value.

### HasTotal

`func (o *PromptSummaryResponse) HasTotal() bool`

HasTotal returns a boolean if a field has been set.

### GetData

`func (o *PromptSummaryResponse) GetData() []PromptSummaryRow`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *PromptSummaryResponse) GetDataOk() (*[]PromptSummaryRow, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *PromptSummaryResponse) SetData(v []PromptSummaryRow)`

SetData sets Data field to given value.

### HasData

`func (o *PromptSummaryResponse) HasData() bool`

HasData returns a boolean if a field has been set.

### GetRequestId

`func (o *PromptSummaryResponse) GetRequestId() string`

GetRequestId returns the RequestId field if non-nil, zero value otherwise.

### GetRequestIdOk

`func (o *PromptSummaryResponse) GetRequestIdOk() (*string, bool)`

GetRequestIdOk returns a tuple with the RequestId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestId

`func (o *PromptSummaryResponse) SetRequestId(v string)`

SetRequestId sets RequestId field to given value.

### HasRequestId

`func (o *PromptSummaryResponse) HasRequestId() bool`

HasRequestId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


