# OwnedMediaKpiChanges

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Total** | Pointer to **NullableFloat32** |  | [optional] 
**Yours** | Pointer to **NullableFloat32** |  | [optional] 
**YourProfile** | Pointer to **NullableFloat32** |  | [optional] 
**YourContent** | Pointer to **NullableFloat32** |  | [optional] 
**SharePct** | Pointer to **NullableFloat32** |  | [optional] 
**UniqueSubreddits** | Pointer to **NullableFloat32** | Percent change in unique subreddits; null when the previous value cannot be compared | [optional] 
**UniqueAuthors** | Pointer to **NullableFloat32** | Percent change in unique authors; null when the previous value cannot be compared | [optional] 
**PositivePct** | Pointer to **NullableFloat32** | Percentage-point change in positive sentiment; null when the previous period has no citations | [optional] 

## Methods

### NewOwnedMediaKpiChanges

`func NewOwnedMediaKpiChanges() *OwnedMediaKpiChanges`

NewOwnedMediaKpiChanges instantiates a new OwnedMediaKpiChanges object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOwnedMediaKpiChangesWithDefaults

`func NewOwnedMediaKpiChangesWithDefaults() *OwnedMediaKpiChanges`

NewOwnedMediaKpiChangesWithDefaults instantiates a new OwnedMediaKpiChanges object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTotal

`func (o *OwnedMediaKpiChanges) GetTotal() float32`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *OwnedMediaKpiChanges) GetTotalOk() (*float32, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *OwnedMediaKpiChanges) SetTotal(v float32)`

SetTotal sets Total field to given value.

### HasTotal

`func (o *OwnedMediaKpiChanges) HasTotal() bool`

HasTotal returns a boolean if a field has been set.

### SetTotalNil

`func (o *OwnedMediaKpiChanges) SetTotalNil(b bool)`

 SetTotalNil sets the value for Total to be an explicit nil

### UnsetTotal
`func (o *OwnedMediaKpiChanges) UnsetTotal()`

UnsetTotal ensures that no value is present for Total, not even an explicit nil
### GetYours

`func (o *OwnedMediaKpiChanges) GetYours() float32`

GetYours returns the Yours field if non-nil, zero value otherwise.

### GetYoursOk

`func (o *OwnedMediaKpiChanges) GetYoursOk() (*float32, bool)`

GetYoursOk returns a tuple with the Yours field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetYours

`func (o *OwnedMediaKpiChanges) SetYours(v float32)`

SetYours sets Yours field to given value.

### HasYours

`func (o *OwnedMediaKpiChanges) HasYours() bool`

HasYours returns a boolean if a field has been set.

### SetYoursNil

`func (o *OwnedMediaKpiChanges) SetYoursNil(b bool)`

 SetYoursNil sets the value for Yours to be an explicit nil

### UnsetYours
`func (o *OwnedMediaKpiChanges) UnsetYours()`

UnsetYours ensures that no value is present for Yours, not even an explicit nil
### GetYourProfile

`func (o *OwnedMediaKpiChanges) GetYourProfile() float32`

GetYourProfile returns the YourProfile field if non-nil, zero value otherwise.

### GetYourProfileOk

`func (o *OwnedMediaKpiChanges) GetYourProfileOk() (*float32, bool)`

GetYourProfileOk returns a tuple with the YourProfile field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetYourProfile

`func (o *OwnedMediaKpiChanges) SetYourProfile(v float32)`

SetYourProfile sets YourProfile field to given value.

### HasYourProfile

`func (o *OwnedMediaKpiChanges) HasYourProfile() bool`

HasYourProfile returns a boolean if a field has been set.

### SetYourProfileNil

`func (o *OwnedMediaKpiChanges) SetYourProfileNil(b bool)`

 SetYourProfileNil sets the value for YourProfile to be an explicit nil

### UnsetYourProfile
`func (o *OwnedMediaKpiChanges) UnsetYourProfile()`

UnsetYourProfile ensures that no value is present for YourProfile, not even an explicit nil
### GetYourContent

`func (o *OwnedMediaKpiChanges) GetYourContent() float32`

GetYourContent returns the YourContent field if non-nil, zero value otherwise.

### GetYourContentOk

`func (o *OwnedMediaKpiChanges) GetYourContentOk() (*float32, bool)`

GetYourContentOk returns a tuple with the YourContent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetYourContent

`func (o *OwnedMediaKpiChanges) SetYourContent(v float32)`

SetYourContent sets YourContent field to given value.

### HasYourContent

`func (o *OwnedMediaKpiChanges) HasYourContent() bool`

HasYourContent returns a boolean if a field has been set.

### SetYourContentNil

`func (o *OwnedMediaKpiChanges) SetYourContentNil(b bool)`

 SetYourContentNil sets the value for YourContent to be an explicit nil

### UnsetYourContent
`func (o *OwnedMediaKpiChanges) UnsetYourContent()`

UnsetYourContent ensures that no value is present for YourContent, not even an explicit nil
### GetSharePct

`func (o *OwnedMediaKpiChanges) GetSharePct() float32`

GetSharePct returns the SharePct field if non-nil, zero value otherwise.

### GetSharePctOk

`func (o *OwnedMediaKpiChanges) GetSharePctOk() (*float32, bool)`

GetSharePctOk returns a tuple with the SharePct field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSharePct

`func (o *OwnedMediaKpiChanges) SetSharePct(v float32)`

SetSharePct sets SharePct field to given value.

### HasSharePct

`func (o *OwnedMediaKpiChanges) HasSharePct() bool`

HasSharePct returns a boolean if a field has been set.

### SetSharePctNil

`func (o *OwnedMediaKpiChanges) SetSharePctNil(b bool)`

 SetSharePctNil sets the value for SharePct to be an explicit nil

### UnsetSharePct
`func (o *OwnedMediaKpiChanges) UnsetSharePct()`

UnsetSharePct ensures that no value is present for SharePct, not even an explicit nil
### GetUniqueSubreddits

`func (o *OwnedMediaKpiChanges) GetUniqueSubreddits() float32`

GetUniqueSubreddits returns the UniqueSubreddits field if non-nil, zero value otherwise.

### GetUniqueSubredditsOk

`func (o *OwnedMediaKpiChanges) GetUniqueSubredditsOk() (*float32, bool)`

GetUniqueSubredditsOk returns a tuple with the UniqueSubreddits field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUniqueSubreddits

`func (o *OwnedMediaKpiChanges) SetUniqueSubreddits(v float32)`

SetUniqueSubreddits sets UniqueSubreddits field to given value.

### HasUniqueSubreddits

`func (o *OwnedMediaKpiChanges) HasUniqueSubreddits() bool`

HasUniqueSubreddits returns a boolean if a field has been set.

### SetUniqueSubredditsNil

`func (o *OwnedMediaKpiChanges) SetUniqueSubredditsNil(b bool)`

 SetUniqueSubredditsNil sets the value for UniqueSubreddits to be an explicit nil

### UnsetUniqueSubreddits
`func (o *OwnedMediaKpiChanges) UnsetUniqueSubreddits()`

UnsetUniqueSubreddits ensures that no value is present for UniqueSubreddits, not even an explicit nil
### GetUniqueAuthors

`func (o *OwnedMediaKpiChanges) GetUniqueAuthors() float32`

GetUniqueAuthors returns the UniqueAuthors field if non-nil, zero value otherwise.

### GetUniqueAuthorsOk

`func (o *OwnedMediaKpiChanges) GetUniqueAuthorsOk() (*float32, bool)`

GetUniqueAuthorsOk returns a tuple with the UniqueAuthors field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUniqueAuthors

`func (o *OwnedMediaKpiChanges) SetUniqueAuthors(v float32)`

SetUniqueAuthors sets UniqueAuthors field to given value.

### HasUniqueAuthors

`func (o *OwnedMediaKpiChanges) HasUniqueAuthors() bool`

HasUniqueAuthors returns a boolean if a field has been set.

### SetUniqueAuthorsNil

`func (o *OwnedMediaKpiChanges) SetUniqueAuthorsNil(b bool)`

 SetUniqueAuthorsNil sets the value for UniqueAuthors to be an explicit nil

### UnsetUniqueAuthors
`func (o *OwnedMediaKpiChanges) UnsetUniqueAuthors()`

UnsetUniqueAuthors ensures that no value is present for UniqueAuthors, not even an explicit nil
### GetPositivePct

`func (o *OwnedMediaKpiChanges) GetPositivePct() float32`

GetPositivePct returns the PositivePct field if non-nil, zero value otherwise.

### GetPositivePctOk

`func (o *OwnedMediaKpiChanges) GetPositivePctOk() (*float32, bool)`

GetPositivePctOk returns a tuple with the PositivePct field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPositivePct

`func (o *OwnedMediaKpiChanges) SetPositivePct(v float32)`

SetPositivePct sets PositivePct field to given value.

### HasPositivePct

`func (o *OwnedMediaKpiChanges) HasPositivePct() bool`

HasPositivePct returns a boolean if a field has been set.

### SetPositivePctNil

`func (o *OwnedMediaKpiChanges) SetPositivePctNil(b bool)`

 SetPositivePctNil sets the value for PositivePct to be an explicit nil

### UnsetPositivePct
`func (o *OwnedMediaKpiChanges) UnsetPositivePct()`

UnsetPositivePct ensures that no value is present for PositivePct, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


