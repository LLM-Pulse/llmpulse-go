# UrlListEntriesAddResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ProjectId** | **int32** |  | 
**UrlListId** | **int32** |  | 
**Added** | **int32** |  | 
**Updated** | **int32** |  | 
**InvalidEntries** | [**[]UrlListInvalidEntry**](UrlListInvalidEntry.md) |  | 
**EntriesCount** | **int32** |  | 
**RequestId** | **string** |  | 

## Methods

### NewUrlListEntriesAddResponse

`func NewUrlListEntriesAddResponse(projectId int32, urlListId int32, added int32, updated int32, invalidEntries []UrlListInvalidEntry, entriesCount int32, requestId string, ) *UrlListEntriesAddResponse`

NewUrlListEntriesAddResponse instantiates a new UrlListEntriesAddResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUrlListEntriesAddResponseWithDefaults

`func NewUrlListEntriesAddResponseWithDefaults() *UrlListEntriesAddResponse`

NewUrlListEntriesAddResponseWithDefaults instantiates a new UrlListEntriesAddResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProjectId

`func (o *UrlListEntriesAddResponse) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *UrlListEntriesAddResponse) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *UrlListEntriesAddResponse) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.


### GetUrlListId

`func (o *UrlListEntriesAddResponse) GetUrlListId() int32`

GetUrlListId returns the UrlListId field if non-nil, zero value otherwise.

### GetUrlListIdOk

`func (o *UrlListEntriesAddResponse) GetUrlListIdOk() (*int32, bool)`

GetUrlListIdOk returns a tuple with the UrlListId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrlListId

`func (o *UrlListEntriesAddResponse) SetUrlListId(v int32)`

SetUrlListId sets UrlListId field to given value.


### GetAdded

`func (o *UrlListEntriesAddResponse) GetAdded() int32`

GetAdded returns the Added field if non-nil, zero value otherwise.

### GetAddedOk

`func (o *UrlListEntriesAddResponse) GetAddedOk() (*int32, bool)`

GetAddedOk returns a tuple with the Added field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAdded

`func (o *UrlListEntriesAddResponse) SetAdded(v int32)`

SetAdded sets Added field to given value.


### GetUpdated

`func (o *UrlListEntriesAddResponse) GetUpdated() int32`

GetUpdated returns the Updated field if non-nil, zero value otherwise.

### GetUpdatedOk

`func (o *UrlListEntriesAddResponse) GetUpdatedOk() (*int32, bool)`

GetUpdatedOk returns a tuple with the Updated field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdated

`func (o *UrlListEntriesAddResponse) SetUpdated(v int32)`

SetUpdated sets Updated field to given value.


### GetInvalidEntries

`func (o *UrlListEntriesAddResponse) GetInvalidEntries() []UrlListInvalidEntry`

GetInvalidEntries returns the InvalidEntries field if non-nil, zero value otherwise.

### GetInvalidEntriesOk

`func (o *UrlListEntriesAddResponse) GetInvalidEntriesOk() (*[]UrlListInvalidEntry, bool)`

GetInvalidEntriesOk returns a tuple with the InvalidEntries field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInvalidEntries

`func (o *UrlListEntriesAddResponse) SetInvalidEntries(v []UrlListInvalidEntry)`

SetInvalidEntries sets InvalidEntries field to given value.


### GetEntriesCount

`func (o *UrlListEntriesAddResponse) GetEntriesCount() int32`

GetEntriesCount returns the EntriesCount field if non-nil, zero value otherwise.

### GetEntriesCountOk

`func (o *UrlListEntriesAddResponse) GetEntriesCountOk() (*int32, bool)`

GetEntriesCountOk returns a tuple with the EntriesCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEntriesCount

`func (o *UrlListEntriesAddResponse) SetEntriesCount(v int32)`

SetEntriesCount sets EntriesCount field to given value.


### GetRequestId

`func (o *UrlListEntriesAddResponse) GetRequestId() string`

GetRequestId returns the RequestId field if non-nil, zero value otherwise.

### GetRequestIdOk

`func (o *UrlListEntriesAddResponse) GetRequestIdOk() (*string, bool)`

GetRequestIdOk returns a tuple with the RequestId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestId

`func (o *UrlListEntriesAddResponse) SetRequestId(v string)`

SetRequestId sets RequestId field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


