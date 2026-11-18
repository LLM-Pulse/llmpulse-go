# UrlListCreateResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ProjectId** | **int32** |  | 
**UrlList** | [**UrlListWithCounts**](UrlListWithCounts.md) |  | 
**EntriesAdded** | **int32** |  | 
**InvalidEntries** | [**[]UrlListInvalidEntry**](UrlListInvalidEntry.md) |  | 
**RequestId** | **string** |  | 

## Methods

### NewUrlListCreateResponse

`func NewUrlListCreateResponse(projectId int32, urlList UrlListWithCounts, entriesAdded int32, invalidEntries []UrlListInvalidEntry, requestId string, ) *UrlListCreateResponse`

NewUrlListCreateResponse instantiates a new UrlListCreateResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUrlListCreateResponseWithDefaults

`func NewUrlListCreateResponseWithDefaults() *UrlListCreateResponse`

NewUrlListCreateResponseWithDefaults instantiates a new UrlListCreateResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProjectId

`func (o *UrlListCreateResponse) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *UrlListCreateResponse) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *UrlListCreateResponse) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.


### GetUrlList

`func (o *UrlListCreateResponse) GetUrlList() UrlListWithCounts`

GetUrlList returns the UrlList field if non-nil, zero value otherwise.

### GetUrlListOk

`func (o *UrlListCreateResponse) GetUrlListOk() (*UrlListWithCounts, bool)`

GetUrlListOk returns a tuple with the UrlList field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrlList

`func (o *UrlListCreateResponse) SetUrlList(v UrlListWithCounts)`

SetUrlList sets UrlList field to given value.


### GetEntriesAdded

`func (o *UrlListCreateResponse) GetEntriesAdded() int32`

GetEntriesAdded returns the EntriesAdded field if non-nil, zero value otherwise.

### GetEntriesAddedOk

`func (o *UrlListCreateResponse) GetEntriesAddedOk() (*int32, bool)`

GetEntriesAddedOk returns a tuple with the EntriesAdded field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEntriesAdded

`func (o *UrlListCreateResponse) SetEntriesAdded(v int32)`

SetEntriesAdded sets EntriesAdded field to given value.


### GetInvalidEntries

`func (o *UrlListCreateResponse) GetInvalidEntries() []UrlListInvalidEntry`

GetInvalidEntries returns the InvalidEntries field if non-nil, zero value otherwise.

### GetInvalidEntriesOk

`func (o *UrlListCreateResponse) GetInvalidEntriesOk() (*[]UrlListInvalidEntry, bool)`

GetInvalidEntriesOk returns a tuple with the InvalidEntries field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInvalidEntries

`func (o *UrlListCreateResponse) SetInvalidEntries(v []UrlListInvalidEntry)`

SetInvalidEntries sets InvalidEntries field to given value.


### GetRequestId

`func (o *UrlListCreateResponse) GetRequestId() string`

GetRequestId returns the RequestId field if non-nil, zero value otherwise.

### GetRequestIdOk

`func (o *UrlListCreateResponse) GetRequestIdOk() (*string, bool)`

GetRequestIdOk returns a tuple with the RequestId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestId

`func (o *UrlListCreateResponse) SetRequestId(v string)`

SetRequestId sets RequestId field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


