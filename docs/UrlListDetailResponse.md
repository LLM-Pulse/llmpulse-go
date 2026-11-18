# UrlListDetailResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ProjectId** | **int32** |  | 
**UrlList** | [**UrlList**](UrlList.md) |  | 
**Filters** | [**UrlListFilters**](UrlListFilters.md) |  | 
**Summary** | [**UrlListSummary**](UrlListSummary.md) |  | 
**StatusCounts** | [**UrlListStatusCounts**](UrlListStatusCounts.md) |  | 
**Page** | **int32** |  | 
**PerPage** | **int32** |  | 
**Total** | **int32** |  | 
**Entries** | [**[]UrlListEntry**](UrlListEntry.md) |  | 
**RequestId** | **string** |  | 

## Methods

### NewUrlListDetailResponse

`func NewUrlListDetailResponse(projectId int32, urlList UrlList, filters UrlListFilters, summary UrlListSummary, statusCounts UrlListStatusCounts, page int32, perPage int32, total int32, entries []UrlListEntry, requestId string, ) *UrlListDetailResponse`

NewUrlListDetailResponse instantiates a new UrlListDetailResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUrlListDetailResponseWithDefaults

`func NewUrlListDetailResponseWithDefaults() *UrlListDetailResponse`

NewUrlListDetailResponseWithDefaults instantiates a new UrlListDetailResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProjectId

`func (o *UrlListDetailResponse) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *UrlListDetailResponse) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *UrlListDetailResponse) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.


### GetUrlList

`func (o *UrlListDetailResponse) GetUrlList() UrlList`

GetUrlList returns the UrlList field if non-nil, zero value otherwise.

### GetUrlListOk

`func (o *UrlListDetailResponse) GetUrlListOk() (*UrlList, bool)`

GetUrlListOk returns a tuple with the UrlList field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrlList

`func (o *UrlListDetailResponse) SetUrlList(v UrlList)`

SetUrlList sets UrlList field to given value.


### GetFilters

`func (o *UrlListDetailResponse) GetFilters() UrlListFilters`

GetFilters returns the Filters field if non-nil, zero value otherwise.

### GetFiltersOk

`func (o *UrlListDetailResponse) GetFiltersOk() (*UrlListFilters, bool)`

GetFiltersOk returns a tuple with the Filters field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFilters

`func (o *UrlListDetailResponse) SetFilters(v UrlListFilters)`

SetFilters sets Filters field to given value.


### GetSummary

`func (o *UrlListDetailResponse) GetSummary() UrlListSummary`

GetSummary returns the Summary field if non-nil, zero value otherwise.

### GetSummaryOk

`func (o *UrlListDetailResponse) GetSummaryOk() (*UrlListSummary, bool)`

GetSummaryOk returns a tuple with the Summary field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSummary

`func (o *UrlListDetailResponse) SetSummary(v UrlListSummary)`

SetSummary sets Summary field to given value.


### GetStatusCounts

`func (o *UrlListDetailResponse) GetStatusCounts() UrlListStatusCounts`

GetStatusCounts returns the StatusCounts field if non-nil, zero value otherwise.

### GetStatusCountsOk

`func (o *UrlListDetailResponse) GetStatusCountsOk() (*UrlListStatusCounts, bool)`

GetStatusCountsOk returns a tuple with the StatusCounts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatusCounts

`func (o *UrlListDetailResponse) SetStatusCounts(v UrlListStatusCounts)`

SetStatusCounts sets StatusCounts field to given value.


### GetPage

`func (o *UrlListDetailResponse) GetPage() int32`

GetPage returns the Page field if non-nil, zero value otherwise.

### GetPageOk

`func (o *UrlListDetailResponse) GetPageOk() (*int32, bool)`

GetPageOk returns a tuple with the Page field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPage

`func (o *UrlListDetailResponse) SetPage(v int32)`

SetPage sets Page field to given value.


### GetPerPage

`func (o *UrlListDetailResponse) GetPerPage() int32`

GetPerPage returns the PerPage field if non-nil, zero value otherwise.

### GetPerPageOk

`func (o *UrlListDetailResponse) GetPerPageOk() (*int32, bool)`

GetPerPageOk returns a tuple with the PerPage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPerPage

`func (o *UrlListDetailResponse) SetPerPage(v int32)`

SetPerPage sets PerPage field to given value.


### GetTotal

`func (o *UrlListDetailResponse) GetTotal() int32`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *UrlListDetailResponse) GetTotalOk() (*int32, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *UrlListDetailResponse) SetTotal(v int32)`

SetTotal sets Total field to given value.


### GetEntries

`func (o *UrlListDetailResponse) GetEntries() []UrlListEntry`

GetEntries returns the Entries field if non-nil, zero value otherwise.

### GetEntriesOk

`func (o *UrlListDetailResponse) GetEntriesOk() (*[]UrlListEntry, bool)`

GetEntriesOk returns a tuple with the Entries field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEntries

`func (o *UrlListDetailResponse) SetEntries(v []UrlListEntry)`

SetEntries sets Entries field to given value.


### GetRequestId

`func (o *UrlListDetailResponse) GetRequestId() string`

GetRequestId returns the RequestId field if non-nil, zero value otherwise.

### GetRequestIdOk

`func (o *UrlListDetailResponse) GetRequestIdOk() (*string, bool)`

GetRequestIdOk returns a tuple with the RequestId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestId

`func (o *UrlListDetailResponse) SetRequestId(v string)`

SetRequestId sets RequestId field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


