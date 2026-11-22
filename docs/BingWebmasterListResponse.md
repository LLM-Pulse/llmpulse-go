# BingWebmasterListResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ProjectId** | Pointer to **int32** |  | [optional] 
**Site** | Pointer to **string** | The connected site, as Bing Webmaster Tools names it (e.g. https://example.com/) | [optional] 
**SyncStatus** | Pointer to **string** | State of the daily sync: pending, syncing, completed, failed or on_hold (the data already synced still answers, but stops updating until the site is reconnected) | [optional] 
**LastSyncedAt** | Pointer to **NullableTime** | When the site last synced. Null before its first sync, or while history_current is false. | [optional] 
**HistoryCurrent** | Pointer to **bool** | False right after the site was changed and before its first sync. Until then data is empty and data_through is null. | [optional] 
**From** | Pointer to **string** |  | [optional] 
**To** | Pointer to **string** |  | [optional] 
**DataThrough** | Pointer to **NullableString** | The last week_ending synced for the site (the Friday that closes a Bing week) | [optional] 
**Page** | Pointer to **int32** |  | [optional] 
**PerPage** | Pointer to **int32** |  | [optional] 
**Total** | Pointer to **int32** | Distinct pages or queries found in the weeks of the window | [optional] 
**Sort** | Pointer to **string** |  | [optional] 
**WeeksCovered** | Pointer to **int32** | Weeks with data whose week_ending falls in the window | [optional] 
**Data** | Pointer to [**[]BingWebmasterListResponseDataInner**](BingWebmasterListResponseDataInner.md) |  | [optional] 
**RequestId** | Pointer to **string** |  | [optional] 

## Methods

### NewBingWebmasterListResponse

`func NewBingWebmasterListResponse() *BingWebmasterListResponse`

NewBingWebmasterListResponse instantiates a new BingWebmasterListResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewBingWebmasterListResponseWithDefaults

`func NewBingWebmasterListResponseWithDefaults() *BingWebmasterListResponse`

NewBingWebmasterListResponseWithDefaults instantiates a new BingWebmasterListResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProjectId

`func (o *BingWebmasterListResponse) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *BingWebmasterListResponse) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *BingWebmasterListResponse) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.

### HasProjectId

`func (o *BingWebmasterListResponse) HasProjectId() bool`

HasProjectId returns a boolean if a field has been set.

### GetSite

`func (o *BingWebmasterListResponse) GetSite() string`

GetSite returns the Site field if non-nil, zero value otherwise.

### GetSiteOk

`func (o *BingWebmasterListResponse) GetSiteOk() (*string, bool)`

GetSiteOk returns a tuple with the Site field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSite

`func (o *BingWebmasterListResponse) SetSite(v string)`

SetSite sets Site field to given value.

### HasSite

`func (o *BingWebmasterListResponse) HasSite() bool`

HasSite returns a boolean if a field has been set.

### GetSyncStatus

`func (o *BingWebmasterListResponse) GetSyncStatus() string`

GetSyncStatus returns the SyncStatus field if non-nil, zero value otherwise.

### GetSyncStatusOk

`func (o *BingWebmasterListResponse) GetSyncStatusOk() (*string, bool)`

GetSyncStatusOk returns a tuple with the SyncStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSyncStatus

`func (o *BingWebmasterListResponse) SetSyncStatus(v string)`

SetSyncStatus sets SyncStatus field to given value.

### HasSyncStatus

`func (o *BingWebmasterListResponse) HasSyncStatus() bool`

HasSyncStatus returns a boolean if a field has been set.

### GetLastSyncedAt

`func (o *BingWebmasterListResponse) GetLastSyncedAt() time.Time`

GetLastSyncedAt returns the LastSyncedAt field if non-nil, zero value otherwise.

### GetLastSyncedAtOk

`func (o *BingWebmasterListResponse) GetLastSyncedAtOk() (*time.Time, bool)`

GetLastSyncedAtOk returns a tuple with the LastSyncedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastSyncedAt

`func (o *BingWebmasterListResponse) SetLastSyncedAt(v time.Time)`

SetLastSyncedAt sets LastSyncedAt field to given value.

### HasLastSyncedAt

`func (o *BingWebmasterListResponse) HasLastSyncedAt() bool`

HasLastSyncedAt returns a boolean if a field has been set.

### SetLastSyncedAtNil

`func (o *BingWebmasterListResponse) SetLastSyncedAtNil(b bool)`

 SetLastSyncedAtNil sets the value for LastSyncedAt to be an explicit nil

### UnsetLastSyncedAt
`func (o *BingWebmasterListResponse) UnsetLastSyncedAt()`

UnsetLastSyncedAt ensures that no value is present for LastSyncedAt, not even an explicit nil
### GetHistoryCurrent

`func (o *BingWebmasterListResponse) GetHistoryCurrent() bool`

GetHistoryCurrent returns the HistoryCurrent field if non-nil, zero value otherwise.

### GetHistoryCurrentOk

`func (o *BingWebmasterListResponse) GetHistoryCurrentOk() (*bool, bool)`

GetHistoryCurrentOk returns a tuple with the HistoryCurrent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHistoryCurrent

`func (o *BingWebmasterListResponse) SetHistoryCurrent(v bool)`

SetHistoryCurrent sets HistoryCurrent field to given value.

### HasHistoryCurrent

`func (o *BingWebmasterListResponse) HasHistoryCurrent() bool`

HasHistoryCurrent returns a boolean if a field has been set.

### GetFrom

`func (o *BingWebmasterListResponse) GetFrom() string`

GetFrom returns the From field if non-nil, zero value otherwise.

### GetFromOk

`func (o *BingWebmasterListResponse) GetFromOk() (*string, bool)`

GetFromOk returns a tuple with the From field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFrom

`func (o *BingWebmasterListResponse) SetFrom(v string)`

SetFrom sets From field to given value.

### HasFrom

`func (o *BingWebmasterListResponse) HasFrom() bool`

HasFrom returns a boolean if a field has been set.

### GetTo

`func (o *BingWebmasterListResponse) GetTo() string`

GetTo returns the To field if non-nil, zero value otherwise.

### GetToOk

`func (o *BingWebmasterListResponse) GetToOk() (*string, bool)`

GetToOk returns a tuple with the To field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTo

`func (o *BingWebmasterListResponse) SetTo(v string)`

SetTo sets To field to given value.

### HasTo

`func (o *BingWebmasterListResponse) HasTo() bool`

HasTo returns a boolean if a field has been set.

### GetDataThrough

`func (o *BingWebmasterListResponse) GetDataThrough() string`

GetDataThrough returns the DataThrough field if non-nil, zero value otherwise.

### GetDataThroughOk

`func (o *BingWebmasterListResponse) GetDataThroughOk() (*string, bool)`

GetDataThroughOk returns a tuple with the DataThrough field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDataThrough

`func (o *BingWebmasterListResponse) SetDataThrough(v string)`

SetDataThrough sets DataThrough field to given value.

### HasDataThrough

`func (o *BingWebmasterListResponse) HasDataThrough() bool`

HasDataThrough returns a boolean if a field has been set.

### SetDataThroughNil

`func (o *BingWebmasterListResponse) SetDataThroughNil(b bool)`

 SetDataThroughNil sets the value for DataThrough to be an explicit nil

### UnsetDataThrough
`func (o *BingWebmasterListResponse) UnsetDataThrough()`

UnsetDataThrough ensures that no value is present for DataThrough, not even an explicit nil
### GetPage

`func (o *BingWebmasterListResponse) GetPage() int32`

GetPage returns the Page field if non-nil, zero value otherwise.

### GetPageOk

`func (o *BingWebmasterListResponse) GetPageOk() (*int32, bool)`

GetPageOk returns a tuple with the Page field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPage

`func (o *BingWebmasterListResponse) SetPage(v int32)`

SetPage sets Page field to given value.

### HasPage

`func (o *BingWebmasterListResponse) HasPage() bool`

HasPage returns a boolean if a field has been set.

### GetPerPage

`func (o *BingWebmasterListResponse) GetPerPage() int32`

GetPerPage returns the PerPage field if non-nil, zero value otherwise.

### GetPerPageOk

`func (o *BingWebmasterListResponse) GetPerPageOk() (*int32, bool)`

GetPerPageOk returns a tuple with the PerPage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPerPage

`func (o *BingWebmasterListResponse) SetPerPage(v int32)`

SetPerPage sets PerPage field to given value.

### HasPerPage

`func (o *BingWebmasterListResponse) HasPerPage() bool`

HasPerPage returns a boolean if a field has been set.

### GetTotal

`func (o *BingWebmasterListResponse) GetTotal() int32`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *BingWebmasterListResponse) GetTotalOk() (*int32, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *BingWebmasterListResponse) SetTotal(v int32)`

SetTotal sets Total field to given value.

### HasTotal

`func (o *BingWebmasterListResponse) HasTotal() bool`

HasTotal returns a boolean if a field has been set.

### GetSort

`func (o *BingWebmasterListResponse) GetSort() string`

GetSort returns the Sort field if non-nil, zero value otherwise.

### GetSortOk

`func (o *BingWebmasterListResponse) GetSortOk() (*string, bool)`

GetSortOk returns a tuple with the Sort field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSort

`func (o *BingWebmasterListResponse) SetSort(v string)`

SetSort sets Sort field to given value.

### HasSort

`func (o *BingWebmasterListResponse) HasSort() bool`

HasSort returns a boolean if a field has been set.

### GetWeeksCovered

`func (o *BingWebmasterListResponse) GetWeeksCovered() int32`

GetWeeksCovered returns the WeeksCovered field if non-nil, zero value otherwise.

### GetWeeksCoveredOk

`func (o *BingWebmasterListResponse) GetWeeksCoveredOk() (*int32, bool)`

GetWeeksCoveredOk returns a tuple with the WeeksCovered field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWeeksCovered

`func (o *BingWebmasterListResponse) SetWeeksCovered(v int32)`

SetWeeksCovered sets WeeksCovered field to given value.

### HasWeeksCovered

`func (o *BingWebmasterListResponse) HasWeeksCovered() bool`

HasWeeksCovered returns a boolean if a field has been set.

### GetData

`func (o *BingWebmasterListResponse) GetData() []BingWebmasterListResponseDataInner`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *BingWebmasterListResponse) GetDataOk() (*[]BingWebmasterListResponseDataInner, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *BingWebmasterListResponse) SetData(v []BingWebmasterListResponseDataInner)`

SetData sets Data field to given value.

### HasData

`func (o *BingWebmasterListResponse) HasData() bool`

HasData returns a boolean if a field has been set.

### GetRequestId

`func (o *BingWebmasterListResponse) GetRequestId() string`

GetRequestId returns the RequestId field if non-nil, zero value otherwise.

### GetRequestIdOk

`func (o *BingWebmasterListResponse) GetRequestIdOk() (*string, bool)`

GetRequestIdOk returns a tuple with the RequestId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestId

`func (o *BingWebmasterListResponse) SetRequestId(v string)`

SetRequestId sets RequestId field to given value.

### HasRequestId

`func (o *BingWebmasterListResponse) HasRequestId() bool`

HasRequestId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


