# OwnedMediaKpis

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Total** | Pointer to **int32** | Citations of the platform in the window, yours and everyone else&#39;s | [optional] 
**Yours** | Pointer to **int32** | Citations of your own profiles and their content | [optional] 
**YourProfile** | Pointer to **NullableInt32** | Citations of your profile or channel pages. Null for mobile_apps and overview | [optional] 
**YourContent** | Pointer to **NullableInt32** | Citations of your posts or videos. Null for mobile_apps and overview | [optional] 
**SharePct** | Pointer to **float32** | yours as a percentage of total (0-100) | [optional] 

## Methods

### NewOwnedMediaKpis

`func NewOwnedMediaKpis() *OwnedMediaKpis`

NewOwnedMediaKpis instantiates a new OwnedMediaKpis object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOwnedMediaKpisWithDefaults

`func NewOwnedMediaKpisWithDefaults() *OwnedMediaKpis`

NewOwnedMediaKpisWithDefaults instantiates a new OwnedMediaKpis object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTotal

`func (o *OwnedMediaKpis) GetTotal() int32`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *OwnedMediaKpis) GetTotalOk() (*int32, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *OwnedMediaKpis) SetTotal(v int32)`

SetTotal sets Total field to given value.

### HasTotal

`func (o *OwnedMediaKpis) HasTotal() bool`

HasTotal returns a boolean if a field has been set.

### GetYours

`func (o *OwnedMediaKpis) GetYours() int32`

GetYours returns the Yours field if non-nil, zero value otherwise.

### GetYoursOk

`func (o *OwnedMediaKpis) GetYoursOk() (*int32, bool)`

GetYoursOk returns a tuple with the Yours field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetYours

`func (o *OwnedMediaKpis) SetYours(v int32)`

SetYours sets Yours field to given value.

### HasYours

`func (o *OwnedMediaKpis) HasYours() bool`

HasYours returns a boolean if a field has been set.

### GetYourProfile

`func (o *OwnedMediaKpis) GetYourProfile() int32`

GetYourProfile returns the YourProfile field if non-nil, zero value otherwise.

### GetYourProfileOk

`func (o *OwnedMediaKpis) GetYourProfileOk() (*int32, bool)`

GetYourProfileOk returns a tuple with the YourProfile field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetYourProfile

`func (o *OwnedMediaKpis) SetYourProfile(v int32)`

SetYourProfile sets YourProfile field to given value.

### HasYourProfile

`func (o *OwnedMediaKpis) HasYourProfile() bool`

HasYourProfile returns a boolean if a field has been set.

### SetYourProfileNil

`func (o *OwnedMediaKpis) SetYourProfileNil(b bool)`

 SetYourProfileNil sets the value for YourProfile to be an explicit nil

### UnsetYourProfile
`func (o *OwnedMediaKpis) UnsetYourProfile()`

UnsetYourProfile ensures that no value is present for YourProfile, not even an explicit nil
### GetYourContent

`func (o *OwnedMediaKpis) GetYourContent() int32`

GetYourContent returns the YourContent field if non-nil, zero value otherwise.

### GetYourContentOk

`func (o *OwnedMediaKpis) GetYourContentOk() (*int32, bool)`

GetYourContentOk returns a tuple with the YourContent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetYourContent

`func (o *OwnedMediaKpis) SetYourContent(v int32)`

SetYourContent sets YourContent field to given value.

### HasYourContent

`func (o *OwnedMediaKpis) HasYourContent() bool`

HasYourContent returns a boolean if a field has been set.

### SetYourContentNil

`func (o *OwnedMediaKpis) SetYourContentNil(b bool)`

 SetYourContentNil sets the value for YourContent to be an explicit nil

### UnsetYourContent
`func (o *OwnedMediaKpis) UnsetYourContent()`

UnsetYourContent ensures that no value is present for YourContent, not even an explicit nil
### GetSharePct

`func (o *OwnedMediaKpis) GetSharePct() float32`

GetSharePct returns the SharePct field if non-nil, zero value otherwise.

### GetSharePctOk

`func (o *OwnedMediaKpis) GetSharePctOk() (*float32, bool)`

GetSharePctOk returns a tuple with the SharePct field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSharePct

`func (o *OwnedMediaKpis) SetSharePct(v float32)`

SetSharePct sets SharePct field to given value.

### HasSharePct

`func (o *OwnedMediaKpis) HasSharePct() bool`

HasSharePct returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


