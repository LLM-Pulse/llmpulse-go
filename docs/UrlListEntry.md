# UrlListEntry

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **int32** |  | 
**Value** | **string** | The exact URL, \&quot;host/path\&quot; of a prefix, or the host of a domain rule. | 
**MatchType** | **string** |  | 
**Host** | **string** |  | 
**Status** | **string** |  | 
**AddedOn** | **string** |  | 
**Cost** | **NullableFloat32** |  | 
**Channel** | **NullableString** |  | 
**Citations** | **int32** |  | 
**CitedPages** | **int32** |  | 
**FirstCitedAt** | **NullableTime** |  | 
**LastCitedAt** | **NullableTime** |  | 
**DaysToFirstCitation** | **NullableInt32** |  | 
**AvgCitationPosition** | **NullableFloat32** |  | 
**Models** | **[]string** |  | 
**BrandMentioned** | **NullableBool** |  | 

## Methods

### NewUrlListEntry

`func NewUrlListEntry(id int32, value string, matchType string, host string, status string, addedOn string, cost NullableFloat32, channel NullableString, citations int32, citedPages int32, firstCitedAt NullableTime, lastCitedAt NullableTime, daysToFirstCitation NullableInt32, avgCitationPosition NullableFloat32, models []string, brandMentioned NullableBool, ) *UrlListEntry`

NewUrlListEntry instantiates a new UrlListEntry object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUrlListEntryWithDefaults

`func NewUrlListEntryWithDefaults() *UrlListEntry`

NewUrlListEntryWithDefaults instantiates a new UrlListEntry object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *UrlListEntry) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *UrlListEntry) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *UrlListEntry) SetId(v int32)`

SetId sets Id field to given value.


### GetValue

`func (o *UrlListEntry) GetValue() string`

GetValue returns the Value field if non-nil, zero value otherwise.

### GetValueOk

`func (o *UrlListEntry) GetValueOk() (*string, bool)`

GetValueOk returns a tuple with the Value field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValue

`func (o *UrlListEntry) SetValue(v string)`

SetValue sets Value field to given value.


### GetMatchType

`func (o *UrlListEntry) GetMatchType() string`

GetMatchType returns the MatchType field if non-nil, zero value otherwise.

### GetMatchTypeOk

`func (o *UrlListEntry) GetMatchTypeOk() (*string, bool)`

GetMatchTypeOk returns a tuple with the MatchType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMatchType

`func (o *UrlListEntry) SetMatchType(v string)`

SetMatchType sets MatchType field to given value.


### GetHost

`func (o *UrlListEntry) GetHost() string`

GetHost returns the Host field if non-nil, zero value otherwise.

### GetHostOk

`func (o *UrlListEntry) GetHostOk() (*string, bool)`

GetHostOk returns a tuple with the Host field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHost

`func (o *UrlListEntry) SetHost(v string)`

SetHost sets Host field to given value.


### GetStatus

`func (o *UrlListEntry) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *UrlListEntry) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *UrlListEntry) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetAddedOn

`func (o *UrlListEntry) GetAddedOn() string`

GetAddedOn returns the AddedOn field if non-nil, zero value otherwise.

### GetAddedOnOk

`func (o *UrlListEntry) GetAddedOnOk() (*string, bool)`

GetAddedOnOk returns a tuple with the AddedOn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddedOn

`func (o *UrlListEntry) SetAddedOn(v string)`

SetAddedOn sets AddedOn field to given value.


### GetCost

`func (o *UrlListEntry) GetCost() float32`

GetCost returns the Cost field if non-nil, zero value otherwise.

### GetCostOk

`func (o *UrlListEntry) GetCostOk() (*float32, bool)`

GetCostOk returns a tuple with the Cost field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCost

`func (o *UrlListEntry) SetCost(v float32)`

SetCost sets Cost field to given value.


### SetCostNil

`func (o *UrlListEntry) SetCostNil(b bool)`

 SetCostNil sets the value for Cost to be an explicit nil

### UnsetCost
`func (o *UrlListEntry) UnsetCost()`

UnsetCost ensures that no value is present for Cost, not even an explicit nil
### GetChannel

`func (o *UrlListEntry) GetChannel() string`

GetChannel returns the Channel field if non-nil, zero value otherwise.

### GetChannelOk

`func (o *UrlListEntry) GetChannelOk() (*string, bool)`

GetChannelOk returns a tuple with the Channel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChannel

`func (o *UrlListEntry) SetChannel(v string)`

SetChannel sets Channel field to given value.


### SetChannelNil

`func (o *UrlListEntry) SetChannelNil(b bool)`

 SetChannelNil sets the value for Channel to be an explicit nil

### UnsetChannel
`func (o *UrlListEntry) UnsetChannel()`

UnsetChannel ensures that no value is present for Channel, not even an explicit nil
### GetCitations

`func (o *UrlListEntry) GetCitations() int32`

GetCitations returns the Citations field if non-nil, zero value otherwise.

### GetCitationsOk

`func (o *UrlListEntry) GetCitationsOk() (*int32, bool)`

GetCitationsOk returns a tuple with the Citations field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCitations

`func (o *UrlListEntry) SetCitations(v int32)`

SetCitations sets Citations field to given value.


### GetCitedPages

`func (o *UrlListEntry) GetCitedPages() int32`

GetCitedPages returns the CitedPages field if non-nil, zero value otherwise.

### GetCitedPagesOk

`func (o *UrlListEntry) GetCitedPagesOk() (*int32, bool)`

GetCitedPagesOk returns a tuple with the CitedPages field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCitedPages

`func (o *UrlListEntry) SetCitedPages(v int32)`

SetCitedPages sets CitedPages field to given value.


### GetFirstCitedAt

`func (o *UrlListEntry) GetFirstCitedAt() time.Time`

GetFirstCitedAt returns the FirstCitedAt field if non-nil, zero value otherwise.

### GetFirstCitedAtOk

`func (o *UrlListEntry) GetFirstCitedAtOk() (*time.Time, bool)`

GetFirstCitedAtOk returns a tuple with the FirstCitedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFirstCitedAt

`func (o *UrlListEntry) SetFirstCitedAt(v time.Time)`

SetFirstCitedAt sets FirstCitedAt field to given value.


### SetFirstCitedAtNil

`func (o *UrlListEntry) SetFirstCitedAtNil(b bool)`

 SetFirstCitedAtNil sets the value for FirstCitedAt to be an explicit nil

### UnsetFirstCitedAt
`func (o *UrlListEntry) UnsetFirstCitedAt()`

UnsetFirstCitedAt ensures that no value is present for FirstCitedAt, not even an explicit nil
### GetLastCitedAt

`func (o *UrlListEntry) GetLastCitedAt() time.Time`

GetLastCitedAt returns the LastCitedAt field if non-nil, zero value otherwise.

### GetLastCitedAtOk

`func (o *UrlListEntry) GetLastCitedAtOk() (*time.Time, bool)`

GetLastCitedAtOk returns a tuple with the LastCitedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastCitedAt

`func (o *UrlListEntry) SetLastCitedAt(v time.Time)`

SetLastCitedAt sets LastCitedAt field to given value.


### SetLastCitedAtNil

`func (o *UrlListEntry) SetLastCitedAtNil(b bool)`

 SetLastCitedAtNil sets the value for LastCitedAt to be an explicit nil

### UnsetLastCitedAt
`func (o *UrlListEntry) UnsetLastCitedAt()`

UnsetLastCitedAt ensures that no value is present for LastCitedAt, not even an explicit nil
### GetDaysToFirstCitation

`func (o *UrlListEntry) GetDaysToFirstCitation() int32`

GetDaysToFirstCitation returns the DaysToFirstCitation field if non-nil, zero value otherwise.

### GetDaysToFirstCitationOk

`func (o *UrlListEntry) GetDaysToFirstCitationOk() (*int32, bool)`

GetDaysToFirstCitationOk returns a tuple with the DaysToFirstCitation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDaysToFirstCitation

`func (o *UrlListEntry) SetDaysToFirstCitation(v int32)`

SetDaysToFirstCitation sets DaysToFirstCitation field to given value.


### SetDaysToFirstCitationNil

`func (o *UrlListEntry) SetDaysToFirstCitationNil(b bool)`

 SetDaysToFirstCitationNil sets the value for DaysToFirstCitation to be an explicit nil

### UnsetDaysToFirstCitation
`func (o *UrlListEntry) UnsetDaysToFirstCitation()`

UnsetDaysToFirstCitation ensures that no value is present for DaysToFirstCitation, not even an explicit nil
### GetAvgCitationPosition

`func (o *UrlListEntry) GetAvgCitationPosition() float32`

GetAvgCitationPosition returns the AvgCitationPosition field if non-nil, zero value otherwise.

### GetAvgCitationPositionOk

`func (o *UrlListEntry) GetAvgCitationPositionOk() (*float32, bool)`

GetAvgCitationPositionOk returns a tuple with the AvgCitationPosition field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAvgCitationPosition

`func (o *UrlListEntry) SetAvgCitationPosition(v float32)`

SetAvgCitationPosition sets AvgCitationPosition field to given value.


### SetAvgCitationPositionNil

`func (o *UrlListEntry) SetAvgCitationPositionNil(b bool)`

 SetAvgCitationPositionNil sets the value for AvgCitationPosition to be an explicit nil

### UnsetAvgCitationPosition
`func (o *UrlListEntry) UnsetAvgCitationPosition()`

UnsetAvgCitationPosition ensures that no value is present for AvgCitationPosition, not even an explicit nil
### GetModels

`func (o *UrlListEntry) GetModels() []string`

GetModels returns the Models field if non-nil, zero value otherwise.

### GetModelsOk

`func (o *UrlListEntry) GetModelsOk() (*[]string, bool)`

GetModelsOk returns a tuple with the Models field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModels

`func (o *UrlListEntry) SetModels(v []string)`

SetModels sets Models field to given value.


### GetBrandMentioned

`func (o *UrlListEntry) GetBrandMentioned() bool`

GetBrandMentioned returns the BrandMentioned field if non-nil, zero value otherwise.

### GetBrandMentionedOk

`func (o *UrlListEntry) GetBrandMentionedOk() (*bool, bool)`

GetBrandMentionedOk returns a tuple with the BrandMentioned field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBrandMentioned

`func (o *UrlListEntry) SetBrandMentioned(v bool)`

SetBrandMentioned sets BrandMentioned field to given value.


### SetBrandMentionedNil

`func (o *UrlListEntry) SetBrandMentionedNil(b bool)`

 SetBrandMentionedNil sets the value for BrandMentioned to be an explicit nil

### UnsetBrandMentioned
`func (o *UrlListEntry) UnsetBrandMentioned()`

UnsetBrandMentioned ensures that no value is present for BrandMentioned, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


