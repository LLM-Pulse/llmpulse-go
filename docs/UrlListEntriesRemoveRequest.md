# UrlListEntriesRemoveRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ProjectId** | **int32** |  | 
**EntryIds** | Pointer to **[]int32** |  | [optional] 
**Values** | Pointer to **[]string** |  | [optional] 

## Methods

### NewUrlListEntriesRemoveRequest

`func NewUrlListEntriesRemoveRequest(projectId int32, ) *UrlListEntriesRemoveRequest`

NewUrlListEntriesRemoveRequest instantiates a new UrlListEntriesRemoveRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUrlListEntriesRemoveRequestWithDefaults

`func NewUrlListEntriesRemoveRequestWithDefaults() *UrlListEntriesRemoveRequest`

NewUrlListEntriesRemoveRequestWithDefaults instantiates a new UrlListEntriesRemoveRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProjectId

`func (o *UrlListEntriesRemoveRequest) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *UrlListEntriesRemoveRequest) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *UrlListEntriesRemoveRequest) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.


### GetEntryIds

`func (o *UrlListEntriesRemoveRequest) GetEntryIds() []int32`

GetEntryIds returns the EntryIds field if non-nil, zero value otherwise.

### GetEntryIdsOk

`func (o *UrlListEntriesRemoveRequest) GetEntryIdsOk() (*[]int32, bool)`

GetEntryIdsOk returns a tuple with the EntryIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEntryIds

`func (o *UrlListEntriesRemoveRequest) SetEntryIds(v []int32)`

SetEntryIds sets EntryIds field to given value.

### HasEntryIds

`func (o *UrlListEntriesRemoveRequest) HasEntryIds() bool`

HasEntryIds returns a boolean if a field has been set.

### GetValues

`func (o *UrlListEntriesRemoveRequest) GetValues() []string`

GetValues returns the Values field if non-nil, zero value otherwise.

### GetValuesOk

`func (o *UrlListEntriesRemoveRequest) GetValuesOk() (*[]string, bool)`

GetValuesOk returns a tuple with the Values field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValues

`func (o *UrlListEntriesRemoveRequest) SetValues(v []string)`

SetValues sets Values field to given value.

### HasValues

`func (o *UrlListEntriesRemoveRequest) HasValues() bool`

HasValues returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


