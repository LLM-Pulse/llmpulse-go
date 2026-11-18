# UrlListCreateRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ProjectId** | **int32** |  | 
**Name** | **string** |  | 
**Description** | Pointer to **string** |  | [optional] 
**Currency** | Pointer to **string** |  | [optional] [default to "USD"]
**Entries** | Pointer to [**[]UrlListEntryInput**](UrlListEntryInput.md) |  | [optional] 
**MatchType** | Pointer to **string** | Read every entry without its own match_type as this type. Default detects it from each value. | [optional] 

## Methods

### NewUrlListCreateRequest

`func NewUrlListCreateRequest(projectId int32, name string, ) *UrlListCreateRequest`

NewUrlListCreateRequest instantiates a new UrlListCreateRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUrlListCreateRequestWithDefaults

`func NewUrlListCreateRequestWithDefaults() *UrlListCreateRequest`

NewUrlListCreateRequestWithDefaults instantiates a new UrlListCreateRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProjectId

`func (o *UrlListCreateRequest) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *UrlListCreateRequest) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *UrlListCreateRequest) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.


### GetName

`func (o *UrlListCreateRequest) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *UrlListCreateRequest) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *UrlListCreateRequest) SetName(v string)`

SetName sets Name field to given value.


### GetDescription

`func (o *UrlListCreateRequest) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *UrlListCreateRequest) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *UrlListCreateRequest) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *UrlListCreateRequest) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetCurrency

`func (o *UrlListCreateRequest) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *UrlListCreateRequest) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *UrlListCreateRequest) SetCurrency(v string)`

SetCurrency sets Currency field to given value.

### HasCurrency

`func (o *UrlListCreateRequest) HasCurrency() bool`

HasCurrency returns a boolean if a field has been set.

### GetEntries

`func (o *UrlListCreateRequest) GetEntries() []UrlListEntryInput`

GetEntries returns the Entries field if non-nil, zero value otherwise.

### GetEntriesOk

`func (o *UrlListCreateRequest) GetEntriesOk() (*[]UrlListEntryInput, bool)`

GetEntriesOk returns a tuple with the Entries field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEntries

`func (o *UrlListCreateRequest) SetEntries(v []UrlListEntryInput)`

SetEntries sets Entries field to given value.

### HasEntries

`func (o *UrlListCreateRequest) HasEntries() bool`

HasEntries returns a boolean if a field has been set.

### GetMatchType

`func (o *UrlListCreateRequest) GetMatchType() string`

GetMatchType returns the MatchType field if non-nil, zero value otherwise.

### GetMatchTypeOk

`func (o *UrlListCreateRequest) GetMatchTypeOk() (*string, bool)`

GetMatchTypeOk returns a tuple with the MatchType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMatchType

`func (o *UrlListCreateRequest) SetMatchType(v string)`

SetMatchType sets MatchType field to given value.

### HasMatchType

`func (o *UrlListCreateRequest) HasMatchType() bool`

HasMatchType returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


