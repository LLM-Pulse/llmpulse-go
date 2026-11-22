# BingWebmasterSummaryResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ProjectId** | Pointer to **int32** |  | [optional] 
**Site** | Pointer to **string** | The connected site, as Bing Webmaster Tools names it (e.g. https://example.com/) | [optional] 
**SyncStatus** | Pointer to **string** | State of the daily sync: pending, syncing, completed, failed or on_hold. on_hold means Bing refused the stored API key or the site is no longer verified: the data already synced still answers but stops updating until the site is reconnected in Preferences &gt; Project Settings &gt; Connections. | [optional] 
**LastSyncedAt** | Pointer to **NullableTime** | When the site last synced. Null before its first sync, or while history_current is false. | [optional] 
**HistoryCurrent** | Pointer to **bool** | False right after the site was changed and before its first sync. Until then the response holds no data and data_through is null. | [optional] 
**From** | Pointer to **string** |  | [optional] 
**To** | Pointer to **string** |  | [optional] 
**DataThrough** | Pointer to **NullableString** | The last day synced for the site. Later days are missing, not zero. | [optional] 
**Totals** | Pointer to [**BingWebmasterMetrics**](BingWebmasterMetrics.md) |  | [optional] 
**RequestId** | Pointer to **string** |  | [optional] 

## Methods

### NewBingWebmasterSummaryResponse

`func NewBingWebmasterSummaryResponse() *BingWebmasterSummaryResponse`

NewBingWebmasterSummaryResponse instantiates a new BingWebmasterSummaryResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewBingWebmasterSummaryResponseWithDefaults

`func NewBingWebmasterSummaryResponseWithDefaults() *BingWebmasterSummaryResponse`

NewBingWebmasterSummaryResponseWithDefaults instantiates a new BingWebmasterSummaryResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProjectId

`func (o *BingWebmasterSummaryResponse) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *BingWebmasterSummaryResponse) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *BingWebmasterSummaryResponse) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.

### HasProjectId

`func (o *BingWebmasterSummaryResponse) HasProjectId() bool`

HasProjectId returns a boolean if a field has been set.

### GetSite

`func (o *BingWebmasterSummaryResponse) GetSite() string`

GetSite returns the Site field if non-nil, zero value otherwise.

### GetSiteOk

`func (o *BingWebmasterSummaryResponse) GetSiteOk() (*string, bool)`

GetSiteOk returns a tuple with the Site field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSite

`func (o *BingWebmasterSummaryResponse) SetSite(v string)`

SetSite sets Site field to given value.

### HasSite

`func (o *BingWebmasterSummaryResponse) HasSite() bool`

HasSite returns a boolean if a field has been set.

### GetSyncStatus

`func (o *BingWebmasterSummaryResponse) GetSyncStatus() string`

GetSyncStatus returns the SyncStatus field if non-nil, zero value otherwise.

### GetSyncStatusOk

`func (o *BingWebmasterSummaryResponse) GetSyncStatusOk() (*string, bool)`

GetSyncStatusOk returns a tuple with the SyncStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSyncStatus

`func (o *BingWebmasterSummaryResponse) SetSyncStatus(v string)`

SetSyncStatus sets SyncStatus field to given value.

### HasSyncStatus

`func (o *BingWebmasterSummaryResponse) HasSyncStatus() bool`

HasSyncStatus returns a boolean if a field has been set.

### GetLastSyncedAt

`func (o *BingWebmasterSummaryResponse) GetLastSyncedAt() time.Time`

GetLastSyncedAt returns the LastSyncedAt field if non-nil, zero value otherwise.

### GetLastSyncedAtOk

`func (o *BingWebmasterSummaryResponse) GetLastSyncedAtOk() (*time.Time, bool)`

GetLastSyncedAtOk returns a tuple with the LastSyncedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastSyncedAt

`func (o *BingWebmasterSummaryResponse) SetLastSyncedAt(v time.Time)`

SetLastSyncedAt sets LastSyncedAt field to given value.

### HasLastSyncedAt

`func (o *BingWebmasterSummaryResponse) HasLastSyncedAt() bool`

HasLastSyncedAt returns a boolean if a field has been set.

### SetLastSyncedAtNil

`func (o *BingWebmasterSummaryResponse) SetLastSyncedAtNil(b bool)`

 SetLastSyncedAtNil sets the value for LastSyncedAt to be an explicit nil

### UnsetLastSyncedAt
`func (o *BingWebmasterSummaryResponse) UnsetLastSyncedAt()`

UnsetLastSyncedAt ensures that no value is present for LastSyncedAt, not even an explicit nil
### GetHistoryCurrent

`func (o *BingWebmasterSummaryResponse) GetHistoryCurrent() bool`

GetHistoryCurrent returns the HistoryCurrent field if non-nil, zero value otherwise.

### GetHistoryCurrentOk

`func (o *BingWebmasterSummaryResponse) GetHistoryCurrentOk() (*bool, bool)`

GetHistoryCurrentOk returns a tuple with the HistoryCurrent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHistoryCurrent

`func (o *BingWebmasterSummaryResponse) SetHistoryCurrent(v bool)`

SetHistoryCurrent sets HistoryCurrent field to given value.

### HasHistoryCurrent

`func (o *BingWebmasterSummaryResponse) HasHistoryCurrent() bool`

HasHistoryCurrent returns a boolean if a field has been set.

### GetFrom

`func (o *BingWebmasterSummaryResponse) GetFrom() string`

GetFrom returns the From field if non-nil, zero value otherwise.

### GetFromOk

`func (o *BingWebmasterSummaryResponse) GetFromOk() (*string, bool)`

GetFromOk returns a tuple with the From field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFrom

`func (o *BingWebmasterSummaryResponse) SetFrom(v string)`

SetFrom sets From field to given value.

### HasFrom

`func (o *BingWebmasterSummaryResponse) HasFrom() bool`

HasFrom returns a boolean if a field has been set.

### GetTo

`func (o *BingWebmasterSummaryResponse) GetTo() string`

GetTo returns the To field if non-nil, zero value otherwise.

### GetToOk

`func (o *BingWebmasterSummaryResponse) GetToOk() (*string, bool)`

GetToOk returns a tuple with the To field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTo

`func (o *BingWebmasterSummaryResponse) SetTo(v string)`

SetTo sets To field to given value.

### HasTo

`func (o *BingWebmasterSummaryResponse) HasTo() bool`

HasTo returns a boolean if a field has been set.

### GetDataThrough

`func (o *BingWebmasterSummaryResponse) GetDataThrough() string`

GetDataThrough returns the DataThrough field if non-nil, zero value otherwise.

### GetDataThroughOk

`func (o *BingWebmasterSummaryResponse) GetDataThroughOk() (*string, bool)`

GetDataThroughOk returns a tuple with the DataThrough field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDataThrough

`func (o *BingWebmasterSummaryResponse) SetDataThrough(v string)`

SetDataThrough sets DataThrough field to given value.

### HasDataThrough

`func (o *BingWebmasterSummaryResponse) HasDataThrough() bool`

HasDataThrough returns a boolean if a field has been set.

### SetDataThroughNil

`func (o *BingWebmasterSummaryResponse) SetDataThroughNil(b bool)`

 SetDataThroughNil sets the value for DataThrough to be an explicit nil

### UnsetDataThrough
`func (o *BingWebmasterSummaryResponse) UnsetDataThrough()`

UnsetDataThrough ensures that no value is present for DataThrough, not even an explicit nil
### GetTotals

`func (o *BingWebmasterSummaryResponse) GetTotals() BingWebmasterMetrics`

GetTotals returns the Totals field if non-nil, zero value otherwise.

### GetTotalsOk

`func (o *BingWebmasterSummaryResponse) GetTotalsOk() (*BingWebmasterMetrics, bool)`

GetTotalsOk returns a tuple with the Totals field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotals

`func (o *BingWebmasterSummaryResponse) SetTotals(v BingWebmasterMetrics)`

SetTotals sets Totals field to given value.

### HasTotals

`func (o *BingWebmasterSummaryResponse) HasTotals() bool`

HasTotals returns a boolean if a field has been set.

### GetRequestId

`func (o *BingWebmasterSummaryResponse) GetRequestId() string`

GetRequestId returns the RequestId field if non-nil, zero value otherwise.

### GetRequestIdOk

`func (o *BingWebmasterSummaryResponse) GetRequestIdOk() (*string, bool)`

GetRequestIdOk returns a tuple with the RequestId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestId

`func (o *BingWebmasterSummaryResponse) SetRequestId(v string)`

SetRequestId sets RequestId field to given value.

### HasRequestId

`func (o *BingWebmasterSummaryResponse) HasRequestId() bool`

HasRequestId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


