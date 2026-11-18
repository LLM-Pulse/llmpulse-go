# UrlListWithCounts

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

## Methods

### NewUrlListWithCounts

`func NewUrlListWithCounts(id int32, name string, description NullableString, currency string, createdAt time.Time, updatedAt time.Time, entriesCount int32, ) *UrlListWithCounts`

NewUrlListWithCounts instantiates a new UrlListWithCounts object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUrlListWithCountsWithDefaults

`func NewUrlListWithCountsWithDefaults() *UrlListWithCounts`

NewUrlListWithCountsWithDefaults instantiates a new UrlListWithCounts object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *UrlListWithCounts) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *UrlListWithCounts) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *UrlListWithCounts) SetId(v int32)`

SetId sets Id field to given value.


### GetName

`func (o *UrlListWithCounts) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *UrlListWithCounts) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *UrlListWithCounts) SetName(v string)`

SetName sets Name field to given value.


### GetDescription

`func (o *UrlListWithCounts) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *UrlListWithCounts) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *UrlListWithCounts) SetDescription(v string)`

SetDescription sets Description field to given value.


### SetDescriptionNil

`func (o *UrlListWithCounts) SetDescriptionNil(b bool)`

 SetDescriptionNil sets the value for Description to be an explicit nil

### UnsetDescription
`func (o *UrlListWithCounts) UnsetDescription()`

UnsetDescription ensures that no value is present for Description, not even an explicit nil
### GetCurrency

`func (o *UrlListWithCounts) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *UrlListWithCounts) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *UrlListWithCounts) SetCurrency(v string)`

SetCurrency sets Currency field to given value.


### GetCreatedAt

`func (o *UrlListWithCounts) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *UrlListWithCounts) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *UrlListWithCounts) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetUpdatedAt

`func (o *UrlListWithCounts) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *UrlListWithCounts) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *UrlListWithCounts) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.


### GetEntriesCount

`func (o *UrlListWithCounts) GetEntriesCount() int32`

GetEntriesCount returns the EntriesCount field if non-nil, zero value otherwise.

### GetEntriesCountOk

`func (o *UrlListWithCounts) GetEntriesCountOk() (*int32, bool)`

GetEntriesCountOk returns a tuple with the EntriesCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEntriesCount

`func (o *UrlListWithCounts) SetEntriesCount(v int32)`

SetEntriesCount sets EntriesCount field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


