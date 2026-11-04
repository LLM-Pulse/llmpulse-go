# RedditBrandShare

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ActorId** | **int32** |  | 
**ActorName** | **NullableString** |  | 
**IsBrand** | **bool** |  | 
**Citations** | **int32** |  | 
**SharePct** | **float32** | Percentage (0-100) among the tracked brand and competitors with cited mentions | 

## Methods

### NewRedditBrandShare

`func NewRedditBrandShare(actorId int32, actorName NullableString, isBrand bool, citations int32, sharePct float32, ) *RedditBrandShare`

NewRedditBrandShare instantiates a new RedditBrandShare object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRedditBrandShareWithDefaults

`func NewRedditBrandShareWithDefaults() *RedditBrandShare`

NewRedditBrandShareWithDefaults instantiates a new RedditBrandShare object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetActorId

`func (o *RedditBrandShare) GetActorId() int32`

GetActorId returns the ActorId field if non-nil, zero value otherwise.

### GetActorIdOk

`func (o *RedditBrandShare) GetActorIdOk() (*int32, bool)`

GetActorIdOk returns a tuple with the ActorId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActorId

`func (o *RedditBrandShare) SetActorId(v int32)`

SetActorId sets ActorId field to given value.


### GetActorName

`func (o *RedditBrandShare) GetActorName() string`

GetActorName returns the ActorName field if non-nil, zero value otherwise.

### GetActorNameOk

`func (o *RedditBrandShare) GetActorNameOk() (*string, bool)`

GetActorNameOk returns a tuple with the ActorName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActorName

`func (o *RedditBrandShare) SetActorName(v string)`

SetActorName sets ActorName field to given value.


### SetActorNameNil

`func (o *RedditBrandShare) SetActorNameNil(b bool)`

 SetActorNameNil sets the value for ActorName to be an explicit nil

### UnsetActorName
`func (o *RedditBrandShare) UnsetActorName()`

UnsetActorName ensures that no value is present for ActorName, not even an explicit nil
### GetIsBrand

`func (o *RedditBrandShare) GetIsBrand() bool`

GetIsBrand returns the IsBrand field if non-nil, zero value otherwise.

### GetIsBrandOk

`func (o *RedditBrandShare) GetIsBrandOk() (*bool, bool)`

GetIsBrandOk returns a tuple with the IsBrand field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsBrand

`func (o *RedditBrandShare) SetIsBrand(v bool)`

SetIsBrand sets IsBrand field to given value.


### GetCitations

`func (o *RedditBrandShare) GetCitations() int32`

GetCitations returns the Citations field if non-nil, zero value otherwise.

### GetCitationsOk

`func (o *RedditBrandShare) GetCitationsOk() (*int32, bool)`

GetCitationsOk returns a tuple with the Citations field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCitations

`func (o *RedditBrandShare) SetCitations(v int32)`

SetCitations sets Citations field to given value.


### GetSharePct

`func (o *RedditBrandShare) GetSharePct() float32`

GetSharePct returns the SharePct field if non-nil, zero value otherwise.

### GetSharePctOk

`func (o *RedditBrandShare) GetSharePctOk() (*float32, bool)`

GetSharePctOk returns a tuple with the SharePct field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSharePct

`func (o *RedditBrandShare) SetSharePct(v float32)`

SetSharePct sets SharePct field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


