# UrlListEntriesAddRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ProjectId** | **int32** |  | 
**Entries** | [**[]UrlListEntryInput**](UrlListEntryInput.md) |  | 
**MatchType** | Pointer to **string** |  | [optional] 

## Methods

### NewUrlListEntriesAddRequest

`func NewUrlListEntriesAddRequest(projectId int32, entries []UrlListEntryInput, ) *UrlListEntriesAddRequest`

NewUrlListEntriesAddRequest instantiates a new UrlListEntriesAddRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUrlListEntriesAddRequestWithDefaults

`func NewUrlListEntriesAddRequestWithDefaults() *UrlListEntriesAddRequest`

NewUrlListEntriesAddRequestWithDefaults instantiates a new UrlListEntriesAddRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProjectId

`func (o *UrlListEntriesAddRequest) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *UrlListEntriesAddRequest) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *UrlListEntriesAddRequest) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.


### GetEntries

`func (o *UrlListEntriesAddRequest) GetEntries() []UrlListEntryInput`

GetEntries returns the Entries field if non-nil, zero value otherwise.

### GetEntriesOk

`func (o *UrlListEntriesAddRequest) GetEntriesOk() (*[]UrlListEntryInput, bool)`

GetEntriesOk returns a tuple with the Entries field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEntries

`func (o *UrlListEntriesAddRequest) SetEntries(v []UrlListEntryInput)`

SetEntries sets Entries field to given value.


### GetMatchType

`func (o *UrlListEntriesAddRequest) GetMatchType() string`

GetMatchType returns the MatchType field if non-nil, zero value otherwise.

### GetMatchTypeOk

`func (o *UrlListEntriesAddRequest) GetMatchTypeOk() (*string, bool)`

GetMatchTypeOk returns a tuple with the MatchType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMatchType

`func (o *UrlListEntriesAddRequest) SetMatchType(v string)`

SetMatchType sets MatchType field to given value.

### HasMatchType

`func (o *UrlListEntriesAddRequest) HasMatchType() bool`

HasMatchType returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


