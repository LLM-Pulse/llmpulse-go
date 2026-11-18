# UrlListEntryInput

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Value** | **string** | An exact URL, a \&quot;host/path/_*\&quot; prefix or a domain. | 
**MatchType** | Pointer to **string** |  | [optional] 
**AddedOn** | Pointer to **string** | When the URL was published or bought. Default today. | [optional] 
**Cost** | Pointer to **float32** | What the URL cost, in the list currency. | [optional] 
**Channel** | Pointer to **string** | Where it came from, such as a marketplace or PR agency. | [optional] 

## Methods

### NewUrlListEntryInput

`func NewUrlListEntryInput(value string, ) *UrlListEntryInput`

NewUrlListEntryInput instantiates a new UrlListEntryInput object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUrlListEntryInputWithDefaults

`func NewUrlListEntryInputWithDefaults() *UrlListEntryInput`

NewUrlListEntryInputWithDefaults instantiates a new UrlListEntryInput object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetValue

`func (o *UrlListEntryInput) GetValue() string`

GetValue returns the Value field if non-nil, zero value otherwise.

### GetValueOk

`func (o *UrlListEntryInput) GetValueOk() (*string, bool)`

GetValueOk returns a tuple with the Value field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValue

`func (o *UrlListEntryInput) SetValue(v string)`

SetValue sets Value field to given value.


### GetMatchType

`func (o *UrlListEntryInput) GetMatchType() string`

GetMatchType returns the MatchType field if non-nil, zero value otherwise.

### GetMatchTypeOk

`func (o *UrlListEntryInput) GetMatchTypeOk() (*string, bool)`

GetMatchTypeOk returns a tuple with the MatchType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMatchType

`func (o *UrlListEntryInput) SetMatchType(v string)`

SetMatchType sets MatchType field to given value.

### HasMatchType

`func (o *UrlListEntryInput) HasMatchType() bool`

HasMatchType returns a boolean if a field has been set.

### GetAddedOn

`func (o *UrlListEntryInput) GetAddedOn() string`

GetAddedOn returns the AddedOn field if non-nil, zero value otherwise.

### GetAddedOnOk

`func (o *UrlListEntryInput) GetAddedOnOk() (*string, bool)`

GetAddedOnOk returns a tuple with the AddedOn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddedOn

`func (o *UrlListEntryInput) SetAddedOn(v string)`

SetAddedOn sets AddedOn field to given value.

### HasAddedOn

`func (o *UrlListEntryInput) HasAddedOn() bool`

HasAddedOn returns a boolean if a field has been set.

### GetCost

`func (o *UrlListEntryInput) GetCost() float32`

GetCost returns the Cost field if non-nil, zero value otherwise.

### GetCostOk

`func (o *UrlListEntryInput) GetCostOk() (*float32, bool)`

GetCostOk returns a tuple with the Cost field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCost

`func (o *UrlListEntryInput) SetCost(v float32)`

SetCost sets Cost field to given value.

### HasCost

`func (o *UrlListEntryInput) HasCost() bool`

HasCost returns a boolean if a field has been set.

### GetChannel

`func (o *UrlListEntryInput) GetChannel() string`

GetChannel returns the Channel field if non-nil, zero value otherwise.

### GetChannelOk

`func (o *UrlListEntryInput) GetChannelOk() (*string, bool)`

GetChannelOk returns a tuple with the Channel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChannel

`func (o *UrlListEntryInput) SetChannel(v string)`

SetChannel sets Channel field to given value.

### HasChannel

`func (o *UrlListEntryInput) HasChannel() bool`

HasChannel returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


