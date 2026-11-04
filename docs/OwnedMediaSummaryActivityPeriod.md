# OwnedMediaSummaryActivityPeriod

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Date** | **string** | Start date of the actual reporting period | 
**Citations** | **int32** |  | 
**Yours** | **NullableInt32** | Citations on owned profiles and content, null for provider&#x3D;overview | 
**Other** | **NullableInt32** | Citations not counted as yours, null for provider&#x3D;overview | 
**Positive** | Pointer to **int32** | Citations whose AI answer sentiment is positive | [optional] 
**Neutral** | Pointer to **int32** | Citations whose AI answer sentiment is neutral or mixed | [optional] 
**Negative** | Pointer to **int32** | Citations whose AI answer sentiment is negative | [optional] 

## Methods

### NewOwnedMediaSummaryActivityPeriod

`func NewOwnedMediaSummaryActivityPeriod(date string, citations int32, yours NullableInt32, other NullableInt32, ) *OwnedMediaSummaryActivityPeriod`

NewOwnedMediaSummaryActivityPeriod instantiates a new OwnedMediaSummaryActivityPeriod object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOwnedMediaSummaryActivityPeriodWithDefaults

`func NewOwnedMediaSummaryActivityPeriodWithDefaults() *OwnedMediaSummaryActivityPeriod`

NewOwnedMediaSummaryActivityPeriodWithDefaults instantiates a new OwnedMediaSummaryActivityPeriod object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDate

`func (o *OwnedMediaSummaryActivityPeriod) GetDate() string`

GetDate returns the Date field if non-nil, zero value otherwise.

### GetDateOk

`func (o *OwnedMediaSummaryActivityPeriod) GetDateOk() (*string, bool)`

GetDateOk returns a tuple with the Date field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDate

`func (o *OwnedMediaSummaryActivityPeriod) SetDate(v string)`

SetDate sets Date field to given value.


### GetCitations

`func (o *OwnedMediaSummaryActivityPeriod) GetCitations() int32`

GetCitations returns the Citations field if non-nil, zero value otherwise.

### GetCitationsOk

`func (o *OwnedMediaSummaryActivityPeriod) GetCitationsOk() (*int32, bool)`

GetCitationsOk returns a tuple with the Citations field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCitations

`func (o *OwnedMediaSummaryActivityPeriod) SetCitations(v int32)`

SetCitations sets Citations field to given value.


### GetYours

`func (o *OwnedMediaSummaryActivityPeriod) GetYours() int32`

GetYours returns the Yours field if non-nil, zero value otherwise.

### GetYoursOk

`func (o *OwnedMediaSummaryActivityPeriod) GetYoursOk() (*int32, bool)`

GetYoursOk returns a tuple with the Yours field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetYours

`func (o *OwnedMediaSummaryActivityPeriod) SetYours(v int32)`

SetYours sets Yours field to given value.


### SetYoursNil

`func (o *OwnedMediaSummaryActivityPeriod) SetYoursNil(b bool)`

 SetYoursNil sets the value for Yours to be an explicit nil

### UnsetYours
`func (o *OwnedMediaSummaryActivityPeriod) UnsetYours()`

UnsetYours ensures that no value is present for Yours, not even an explicit nil
### GetOther

`func (o *OwnedMediaSummaryActivityPeriod) GetOther() int32`

GetOther returns the Other field if non-nil, zero value otherwise.

### GetOtherOk

`func (o *OwnedMediaSummaryActivityPeriod) GetOtherOk() (*int32, bool)`

GetOtherOk returns a tuple with the Other field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOther

`func (o *OwnedMediaSummaryActivityPeriod) SetOther(v int32)`

SetOther sets Other field to given value.


### SetOtherNil

`func (o *OwnedMediaSummaryActivityPeriod) SetOtherNil(b bool)`

 SetOtherNil sets the value for Other to be an explicit nil

### UnsetOther
`func (o *OwnedMediaSummaryActivityPeriod) UnsetOther()`

UnsetOther ensures that no value is present for Other, not even an explicit nil
### GetPositive

`func (o *OwnedMediaSummaryActivityPeriod) GetPositive() int32`

GetPositive returns the Positive field if non-nil, zero value otherwise.

### GetPositiveOk

`func (o *OwnedMediaSummaryActivityPeriod) GetPositiveOk() (*int32, bool)`

GetPositiveOk returns a tuple with the Positive field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPositive

`func (o *OwnedMediaSummaryActivityPeriod) SetPositive(v int32)`

SetPositive sets Positive field to given value.

### HasPositive

`func (o *OwnedMediaSummaryActivityPeriod) HasPositive() bool`

HasPositive returns a boolean if a field has been set.

### GetNeutral

`func (o *OwnedMediaSummaryActivityPeriod) GetNeutral() int32`

GetNeutral returns the Neutral field if non-nil, zero value otherwise.

### GetNeutralOk

`func (o *OwnedMediaSummaryActivityPeriod) GetNeutralOk() (*int32, bool)`

GetNeutralOk returns a tuple with the Neutral field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNeutral

`func (o *OwnedMediaSummaryActivityPeriod) SetNeutral(v int32)`

SetNeutral sets Neutral field to given value.

### HasNeutral

`func (o *OwnedMediaSummaryActivityPeriod) HasNeutral() bool`

HasNeutral returns a boolean if a field has been set.

### GetNegative

`func (o *OwnedMediaSummaryActivityPeriod) GetNegative() int32`

GetNegative returns the Negative field if non-nil, zero value otherwise.

### GetNegativeOk

`func (o *OwnedMediaSummaryActivityPeriod) GetNegativeOk() (*int32, bool)`

GetNegativeOk returns a tuple with the Negative field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNegative

`func (o *OwnedMediaSummaryActivityPeriod) SetNegative(v int32)`

SetNegative sets Negative field to given value.

### HasNegative

`func (o *OwnedMediaSummaryActivityPeriod) HasNegative() bool`

HasNegative returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


