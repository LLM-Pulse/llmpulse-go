# UrlListWithStats

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **int32** |  | 
**Name** | **string** |  | 
**Description** | **NullableString** |  | 
**Currency** | **string** | The currency of the entry costs. | 
**CreatedAt** | **time.Time** |  | 
**UpdatedAt** | **time.Time** |  | 
**EntriesCount** | **int32** |  | 
**CitedEntries** | **int32** | Entries an AI answer cited in the window. | 
**Citations** | **int32** | AI answers citing any entry in the window, each once. | 
**LastCitedAt** | **NullableTime** | The latest answer citing an entry, up to the window&#39;s end. | 

## Methods

### NewUrlListWithStats

`func NewUrlListWithStats(id int32, name string, description NullableString, currency string, createdAt time.Time, updatedAt time.Time, entriesCount int32, citedEntries int32, citations int32, lastCitedAt NullableTime, ) *UrlListWithStats`

NewUrlListWithStats instantiates a new UrlListWithStats object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUrlListWithStatsWithDefaults

`func NewUrlListWithStatsWithDefaults() *UrlListWithStats`

NewUrlListWithStatsWithDefaults instantiates a new UrlListWithStats object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *UrlListWithStats) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *UrlListWithStats) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *UrlListWithStats) SetId(v int32)`

SetId sets Id field to given value.


### GetName

`func (o *UrlListWithStats) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *UrlListWithStats) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *UrlListWithStats) SetName(v string)`

SetName sets Name field to given value.


### GetDescription

`func (o *UrlListWithStats) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *UrlListWithStats) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *UrlListWithStats) SetDescription(v string)`

SetDescription sets Description field to given value.


### SetDescriptionNil

`func (o *UrlListWithStats) SetDescriptionNil(b bool)`

 SetDescriptionNil sets the value for Description to be an explicit nil

### UnsetDescription
`func (o *UrlListWithStats) UnsetDescription()`

UnsetDescription ensures that no value is present for Description, not even an explicit nil
### GetCurrency

`func (o *UrlListWithStats) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *UrlListWithStats) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *UrlListWithStats) SetCurrency(v string)`

SetCurrency sets Currency field to given value.


### GetCreatedAt

`func (o *UrlListWithStats) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *UrlListWithStats) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *UrlListWithStats) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetUpdatedAt

`func (o *UrlListWithStats) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *UrlListWithStats) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *UrlListWithStats) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.


### GetEntriesCount

`func (o *UrlListWithStats) GetEntriesCount() int32`

GetEntriesCount returns the EntriesCount field if non-nil, zero value otherwise.

### GetEntriesCountOk

`func (o *UrlListWithStats) GetEntriesCountOk() (*int32, bool)`

GetEntriesCountOk returns a tuple with the EntriesCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEntriesCount

`func (o *UrlListWithStats) SetEntriesCount(v int32)`

SetEntriesCount sets EntriesCount field to given value.


### GetCitedEntries

`func (o *UrlListWithStats) GetCitedEntries() int32`

GetCitedEntries returns the CitedEntries field if non-nil, zero value otherwise.

### GetCitedEntriesOk

`func (o *UrlListWithStats) GetCitedEntriesOk() (*int32, bool)`

GetCitedEntriesOk returns a tuple with the CitedEntries field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCitedEntries

`func (o *UrlListWithStats) SetCitedEntries(v int32)`

SetCitedEntries sets CitedEntries field to given value.


### GetCitations

`func (o *UrlListWithStats) GetCitations() int32`

GetCitations returns the Citations field if non-nil, zero value otherwise.

### GetCitationsOk

`func (o *UrlListWithStats) GetCitationsOk() (*int32, bool)`

GetCitationsOk returns a tuple with the Citations field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCitations

`func (o *UrlListWithStats) SetCitations(v int32)`

SetCitations sets Citations field to given value.


### GetLastCitedAt

`func (o *UrlListWithStats) GetLastCitedAt() time.Time`

GetLastCitedAt returns the LastCitedAt field if non-nil, zero value otherwise.

### GetLastCitedAtOk

`func (o *UrlListWithStats) GetLastCitedAtOk() (*time.Time, bool)`

GetLastCitedAtOk returns a tuple with the LastCitedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastCitedAt

`func (o *UrlListWithStats) SetLastCitedAt(v time.Time)`

SetLastCitedAt sets LastCitedAt field to given value.


### SetLastCitedAtNil

`func (o *UrlListWithStats) SetLastCitedAtNil(b bool)`

 SetLastCitedAtNil sets the value for LastCitedAt to be an explicit nil

### UnsetLastCitedAt
`func (o *UrlListWithStats) UnsetLastCitedAt()`

UnsetLastCitedAt ensures that no value is present for LastCitedAt, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


