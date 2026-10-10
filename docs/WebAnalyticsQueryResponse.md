# WebAnalyticsQueryResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ProjectId** | Pointer to **int32** |  | [optional] 
**Provider** | Pointer to **string** |  | [optional] 
**Property** | Pointer to **string** |  | [optional] 
**Columns** | Pointer to [**[]WebAnalyticsQueryResponseColumnsInner**](WebAnalyticsQueryResponseColumnsInner.md) |  | [optional] 
**Rows** | Pointer to **[][]interface{}** | One array per row, values in column order: strings, numbers or null. | [optional] 
**RowCount** | Pointer to **int32** | Rows in this response (at most 5,000). | [optional] 
**TotalRows** | Pointer to **int32** | Rows the provider has for the query, when it reports it. | [optional] 
**Truncated** | Pointer to **bool** | True when the provider has more rows than returned; page with its own offset or page field. | [optional] 
**Totals** | Pointer to **map[string]interface{}** | Metric totals by metric name, when the query asked for them. | [optional] 
**Notes** | Pointer to **[]string** | Provider caveats: sampling, thresholds, more rows available. | [optional] 
**Meta** | Pointer to **map[string]interface{}** | Provider metadata such as GA4 time zone, currency and remaining property quota. | [optional] 
**FetchedAt** | Pointer to **time.Time** | When the provider answered. | [optional] 
**Cached** | Pointer to **bool** | True when the answer came from the 10-minute cache instead of the provider. | [optional] 
**Query** | Pointer to **map[string]interface{}** | The request as sent to the provider, with the connected property forced and limits applied. | [optional] 
**RequestId** | Pointer to **string** |  | [optional] 

## Methods

### NewWebAnalyticsQueryResponse

`func NewWebAnalyticsQueryResponse() *WebAnalyticsQueryResponse`

NewWebAnalyticsQueryResponse instantiates a new WebAnalyticsQueryResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewWebAnalyticsQueryResponseWithDefaults

`func NewWebAnalyticsQueryResponseWithDefaults() *WebAnalyticsQueryResponse`

NewWebAnalyticsQueryResponseWithDefaults instantiates a new WebAnalyticsQueryResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProjectId

`func (o *WebAnalyticsQueryResponse) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *WebAnalyticsQueryResponse) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *WebAnalyticsQueryResponse) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.

### HasProjectId

`func (o *WebAnalyticsQueryResponse) HasProjectId() bool`

HasProjectId returns a boolean if a field has been set.

### GetProvider

`func (o *WebAnalyticsQueryResponse) GetProvider() string`

GetProvider returns the Provider field if non-nil, zero value otherwise.

### GetProviderOk

`func (o *WebAnalyticsQueryResponse) GetProviderOk() (*string, bool)`

GetProviderOk returns a tuple with the Provider field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProvider

`func (o *WebAnalyticsQueryResponse) SetProvider(v string)`

SetProvider sets Provider field to given value.

### HasProvider

`func (o *WebAnalyticsQueryResponse) HasProvider() bool`

HasProvider returns a boolean if a field has been set.

### GetProperty

`func (o *WebAnalyticsQueryResponse) GetProperty() string`

GetProperty returns the Property field if non-nil, zero value otherwise.

### GetPropertyOk

`func (o *WebAnalyticsQueryResponse) GetPropertyOk() (*string, bool)`

GetPropertyOk returns a tuple with the Property field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProperty

`func (o *WebAnalyticsQueryResponse) SetProperty(v string)`

SetProperty sets Property field to given value.

### HasProperty

`func (o *WebAnalyticsQueryResponse) HasProperty() bool`

HasProperty returns a boolean if a field has been set.

### GetColumns

`func (o *WebAnalyticsQueryResponse) GetColumns() []WebAnalyticsQueryResponseColumnsInner`

GetColumns returns the Columns field if non-nil, zero value otherwise.

### GetColumnsOk

`func (o *WebAnalyticsQueryResponse) GetColumnsOk() (*[]WebAnalyticsQueryResponseColumnsInner, bool)`

GetColumnsOk returns a tuple with the Columns field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetColumns

`func (o *WebAnalyticsQueryResponse) SetColumns(v []WebAnalyticsQueryResponseColumnsInner)`

SetColumns sets Columns field to given value.

### HasColumns

`func (o *WebAnalyticsQueryResponse) HasColumns() bool`

HasColumns returns a boolean if a field has been set.

### GetRows

`func (o *WebAnalyticsQueryResponse) GetRows() [][]interface{}`

GetRows returns the Rows field if non-nil, zero value otherwise.

### GetRowsOk

`func (o *WebAnalyticsQueryResponse) GetRowsOk() (*[][]interface{}, bool)`

GetRowsOk returns a tuple with the Rows field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRows

`func (o *WebAnalyticsQueryResponse) SetRows(v [][]interface{})`

SetRows sets Rows field to given value.

### HasRows

`func (o *WebAnalyticsQueryResponse) HasRows() bool`

HasRows returns a boolean if a field has been set.

### GetRowCount

`func (o *WebAnalyticsQueryResponse) GetRowCount() int32`

GetRowCount returns the RowCount field if non-nil, zero value otherwise.

### GetRowCountOk

`func (o *WebAnalyticsQueryResponse) GetRowCountOk() (*int32, bool)`

GetRowCountOk returns a tuple with the RowCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRowCount

`func (o *WebAnalyticsQueryResponse) SetRowCount(v int32)`

SetRowCount sets RowCount field to given value.

### HasRowCount

`func (o *WebAnalyticsQueryResponse) HasRowCount() bool`

HasRowCount returns a boolean if a field has been set.

### GetTotalRows

`func (o *WebAnalyticsQueryResponse) GetTotalRows() int32`

GetTotalRows returns the TotalRows field if non-nil, zero value otherwise.

### GetTotalRowsOk

`func (o *WebAnalyticsQueryResponse) GetTotalRowsOk() (*int32, bool)`

GetTotalRowsOk returns a tuple with the TotalRows field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalRows

`func (o *WebAnalyticsQueryResponse) SetTotalRows(v int32)`

SetTotalRows sets TotalRows field to given value.

### HasTotalRows

`func (o *WebAnalyticsQueryResponse) HasTotalRows() bool`

HasTotalRows returns a boolean if a field has been set.

### GetTruncated

`func (o *WebAnalyticsQueryResponse) GetTruncated() bool`

GetTruncated returns the Truncated field if non-nil, zero value otherwise.

### GetTruncatedOk

`func (o *WebAnalyticsQueryResponse) GetTruncatedOk() (*bool, bool)`

GetTruncatedOk returns a tuple with the Truncated field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTruncated

`func (o *WebAnalyticsQueryResponse) SetTruncated(v bool)`

SetTruncated sets Truncated field to given value.

### HasTruncated

`func (o *WebAnalyticsQueryResponse) HasTruncated() bool`

HasTruncated returns a boolean if a field has been set.

### GetTotals

`func (o *WebAnalyticsQueryResponse) GetTotals() map[string]interface{}`

GetTotals returns the Totals field if non-nil, zero value otherwise.

### GetTotalsOk

`func (o *WebAnalyticsQueryResponse) GetTotalsOk() (*map[string]interface{}, bool)`

GetTotalsOk returns a tuple with the Totals field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotals

`func (o *WebAnalyticsQueryResponse) SetTotals(v map[string]interface{})`

SetTotals sets Totals field to given value.

### HasTotals

`func (o *WebAnalyticsQueryResponse) HasTotals() bool`

HasTotals returns a boolean if a field has been set.

### GetNotes

`func (o *WebAnalyticsQueryResponse) GetNotes() []string`

GetNotes returns the Notes field if non-nil, zero value otherwise.

### GetNotesOk

`func (o *WebAnalyticsQueryResponse) GetNotesOk() (*[]string, bool)`

GetNotesOk returns a tuple with the Notes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotes

`func (o *WebAnalyticsQueryResponse) SetNotes(v []string)`

SetNotes sets Notes field to given value.

### HasNotes

`func (o *WebAnalyticsQueryResponse) HasNotes() bool`

HasNotes returns a boolean if a field has been set.

### GetMeta

`func (o *WebAnalyticsQueryResponse) GetMeta() map[string]interface{}`

GetMeta returns the Meta field if non-nil, zero value otherwise.

### GetMetaOk

`func (o *WebAnalyticsQueryResponse) GetMetaOk() (*map[string]interface{}, bool)`

GetMetaOk returns a tuple with the Meta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMeta

`func (o *WebAnalyticsQueryResponse) SetMeta(v map[string]interface{})`

SetMeta sets Meta field to given value.

### HasMeta

`func (o *WebAnalyticsQueryResponse) HasMeta() bool`

HasMeta returns a boolean if a field has been set.

### GetFetchedAt

`func (o *WebAnalyticsQueryResponse) GetFetchedAt() time.Time`

GetFetchedAt returns the FetchedAt field if non-nil, zero value otherwise.

### GetFetchedAtOk

`func (o *WebAnalyticsQueryResponse) GetFetchedAtOk() (*time.Time, bool)`

GetFetchedAtOk returns a tuple with the FetchedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFetchedAt

`func (o *WebAnalyticsQueryResponse) SetFetchedAt(v time.Time)`

SetFetchedAt sets FetchedAt field to given value.

### HasFetchedAt

`func (o *WebAnalyticsQueryResponse) HasFetchedAt() bool`

HasFetchedAt returns a boolean if a field has been set.

### GetCached

`func (o *WebAnalyticsQueryResponse) GetCached() bool`

GetCached returns the Cached field if non-nil, zero value otherwise.

### GetCachedOk

`func (o *WebAnalyticsQueryResponse) GetCachedOk() (*bool, bool)`

GetCachedOk returns a tuple with the Cached field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCached

`func (o *WebAnalyticsQueryResponse) SetCached(v bool)`

SetCached sets Cached field to given value.

### HasCached

`func (o *WebAnalyticsQueryResponse) HasCached() bool`

HasCached returns a boolean if a field has been set.

### GetQuery

`func (o *WebAnalyticsQueryResponse) GetQuery() map[string]interface{}`

GetQuery returns the Query field if non-nil, zero value otherwise.

### GetQueryOk

`func (o *WebAnalyticsQueryResponse) GetQueryOk() (*map[string]interface{}, bool)`

GetQueryOk returns a tuple with the Query field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuery

`func (o *WebAnalyticsQueryResponse) SetQuery(v map[string]interface{})`

SetQuery sets Query field to given value.

### HasQuery

`func (o *WebAnalyticsQueryResponse) HasQuery() bool`

HasQuery returns a boolean if a field has been set.

### GetRequestId

`func (o *WebAnalyticsQueryResponse) GetRequestId() string`

GetRequestId returns the RequestId field if non-nil, zero value otherwise.

### GetRequestIdOk

`func (o *WebAnalyticsQueryResponse) GetRequestIdOk() (*string, bool)`

GetRequestIdOk returns a tuple with the RequestId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestId

`func (o *WebAnalyticsQueryResponse) SetRequestId(v string)`

SetRequestId sets RequestId field to given value.

### HasRequestId

`func (o *WebAnalyticsQueryResponse) HasRequestId() bool`

HasRequestId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


