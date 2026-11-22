# BingWebmasterTimeseriesResponse

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
**DataThrough** | Pointer to **NullableString** | The last day synced for the site. Later days are missing, not zero. | [optional] 
**Granularity** | Pointer to **string** |  | [optional] 
**Data** | Pointer to [**[]BingWebmasterTimeseriesResponseDataInner**](BingWebmasterTimeseriesResponseDataInner.md) | One bucket per day, week (starting Monday) or month that has synced days. Days without data are left out, not reported as zero. | [optional] 
**RequestId** | Pointer to **string** |  | [optional] 

## Methods

### NewBingWebmasterTimeseriesResponse

`func NewBingWebmasterTimeseriesResponse() *BingWebmasterTimeseriesResponse`

NewBingWebmasterTimeseriesResponse instantiates a new BingWebmasterTimeseriesResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewBingWebmasterTimeseriesResponseWithDefaults

`func NewBingWebmasterTimeseriesResponseWithDefaults() *BingWebmasterTimeseriesResponse`

NewBingWebmasterTimeseriesResponseWithDefaults instantiates a new BingWebmasterTimeseriesResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProjectId

`func (o *BingWebmasterTimeseriesResponse) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *BingWebmasterTimeseriesResponse) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *BingWebmasterTimeseriesResponse) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.

### HasProjectId

`func (o *BingWebmasterTimeseriesResponse) HasProjectId() bool`

HasProjectId returns a boolean if a field has been set.

### GetSite

`func (o *BingWebmasterTimeseriesResponse) GetSite() string`

GetSite returns the Site field if non-nil, zero value otherwise.

### GetSiteOk

`func (o *BingWebmasterTimeseriesResponse) GetSiteOk() (*string, bool)`

GetSiteOk returns a tuple with the Site field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSite

`func (o *BingWebmasterTimeseriesResponse) SetSite(v string)`

SetSite sets Site field to given value.

### HasSite

`func (o *BingWebmasterTimeseriesResponse) HasSite() bool`

HasSite returns a boolean if a field has been set.

### GetSyncStatus

`func (o *BingWebmasterTimeseriesResponse) GetSyncStatus() string`

GetSyncStatus returns the SyncStatus field if non-nil, zero value otherwise.

### GetSyncStatusOk

`func (o *BingWebmasterTimeseriesResponse) GetSyncStatusOk() (*string, bool)`

GetSyncStatusOk returns a tuple with the SyncStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSyncStatus

`func (o *BingWebmasterTimeseriesResponse) SetSyncStatus(v string)`

SetSyncStatus sets SyncStatus field to given value.

### HasSyncStatus

`func (o *BingWebmasterTimeseriesResponse) HasSyncStatus() bool`

HasSyncStatus returns a boolean if a field has been set.

### GetLastSyncedAt

`func (o *BingWebmasterTimeseriesResponse) GetLastSyncedAt() time.Time`

GetLastSyncedAt returns the LastSyncedAt field if non-nil, zero value otherwise.

### GetLastSyncedAtOk

`func (o *BingWebmasterTimeseriesResponse) GetLastSyncedAtOk() (*time.Time, bool)`

GetLastSyncedAtOk returns a tuple with the LastSyncedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastSyncedAt

`func (o *BingWebmasterTimeseriesResponse) SetLastSyncedAt(v time.Time)`

SetLastSyncedAt sets LastSyncedAt field to given value.

### HasLastSyncedAt

`func (o *BingWebmasterTimeseriesResponse) HasLastSyncedAt() bool`

HasLastSyncedAt returns a boolean if a field has been set.

### SetLastSyncedAtNil

`func (o *BingWebmasterTimeseriesResponse) SetLastSyncedAtNil(b bool)`

 SetLastSyncedAtNil sets the value for LastSyncedAt to be an explicit nil

### UnsetLastSyncedAt
`func (o *BingWebmasterTimeseriesResponse) UnsetLastSyncedAt()`

UnsetLastSyncedAt ensures that no value is present for LastSyncedAt, not even an explicit nil
### GetHistoryCurrent

`func (o *BingWebmasterTimeseriesResponse) GetHistoryCurrent() bool`

GetHistoryCurrent returns the HistoryCurrent field if non-nil, zero value otherwise.

### GetHistoryCurrentOk

`func (o *BingWebmasterTimeseriesResponse) GetHistoryCurrentOk() (*bool, bool)`

GetHistoryCurrentOk returns a tuple with the HistoryCurrent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHistoryCurrent

`func (o *BingWebmasterTimeseriesResponse) SetHistoryCurrent(v bool)`

SetHistoryCurrent sets HistoryCurrent field to given value.

### HasHistoryCurrent

`func (o *BingWebmasterTimeseriesResponse) HasHistoryCurrent() bool`

HasHistoryCurrent returns a boolean if a field has been set.

### GetFrom

`func (o *BingWebmasterTimeseriesResponse) GetFrom() string`

GetFrom returns the From field if non-nil, zero value otherwise.

### GetFromOk

`func (o *BingWebmasterTimeseriesResponse) GetFromOk() (*string, bool)`

GetFromOk returns a tuple with the From field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFrom

`func (o *BingWebmasterTimeseriesResponse) SetFrom(v string)`

SetFrom sets From field to given value.

### HasFrom

`func (o *BingWebmasterTimeseriesResponse) HasFrom() bool`

HasFrom returns a boolean if a field has been set.

### GetTo

`func (o *BingWebmasterTimeseriesResponse) GetTo() string`

GetTo returns the To field if non-nil, zero value otherwise.

### GetToOk

`func (o *BingWebmasterTimeseriesResponse) GetToOk() (*string, bool)`

GetToOk returns a tuple with the To field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTo

`func (o *BingWebmasterTimeseriesResponse) SetTo(v string)`

SetTo sets To field to given value.

### HasTo

`func (o *BingWebmasterTimeseriesResponse) HasTo() bool`

HasTo returns a boolean if a field has been set.

### GetDataThrough

`func (o *BingWebmasterTimeseriesResponse) GetDataThrough() string`

GetDataThrough returns the DataThrough field if non-nil, zero value otherwise.

### GetDataThroughOk

`func (o *BingWebmasterTimeseriesResponse) GetDataThroughOk() (*string, bool)`

GetDataThroughOk returns a tuple with the DataThrough field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDataThrough

`func (o *BingWebmasterTimeseriesResponse) SetDataThrough(v string)`

SetDataThrough sets DataThrough field to given value.

### HasDataThrough

`func (o *BingWebmasterTimeseriesResponse) HasDataThrough() bool`

HasDataThrough returns a boolean if a field has been set.

### SetDataThroughNil

`func (o *BingWebmasterTimeseriesResponse) SetDataThroughNil(b bool)`

 SetDataThroughNil sets the value for DataThrough to be an explicit nil

### UnsetDataThrough
`func (o *BingWebmasterTimeseriesResponse) UnsetDataThrough()`

UnsetDataThrough ensures that no value is present for DataThrough, not even an explicit nil
### GetGranularity

`func (o *BingWebmasterTimeseriesResponse) GetGranularity() string`

GetGranularity returns the Granularity field if non-nil, zero value otherwise.

### GetGranularityOk

`func (o *BingWebmasterTimeseriesResponse) GetGranularityOk() (*string, bool)`

GetGranularityOk returns a tuple with the Granularity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGranularity

`func (o *BingWebmasterTimeseriesResponse) SetGranularity(v string)`

SetGranularity sets Granularity field to given value.

### HasGranularity

`func (o *BingWebmasterTimeseriesResponse) HasGranularity() bool`

HasGranularity returns a boolean if a field has been set.

### GetData

`func (o *BingWebmasterTimeseriesResponse) GetData() []BingWebmasterTimeseriesResponseDataInner`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *BingWebmasterTimeseriesResponse) GetDataOk() (*[]BingWebmasterTimeseriesResponseDataInner, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *BingWebmasterTimeseriesResponse) SetData(v []BingWebmasterTimeseriesResponseDataInner)`

SetData sets Data field to given value.

### HasData

`func (o *BingWebmasterTimeseriesResponse) HasData() bool`

HasData returns a boolean if a field has been set.

### GetRequestId

`func (o *BingWebmasterTimeseriesResponse) GetRequestId() string`

GetRequestId returns the RequestId field if non-nil, zero value otherwise.

### GetRequestIdOk

`func (o *BingWebmasterTimeseriesResponse) GetRequestIdOk() (*string, bool)`

GetRequestIdOk returns a tuple with the RequestId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestId

`func (o *BingWebmasterTimeseriesResponse) SetRequestId(v string)`

SetRequestId sets RequestId field to given value.

### HasRequestId

`func (o *BingWebmasterTimeseriesResponse) HasRequestId() bool`

HasRequestId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


