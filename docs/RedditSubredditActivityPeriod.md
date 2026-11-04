# RedditSubredditActivityPeriod

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Date** | **string** | Start date of the actual reporting period | 
**Subreddit** | **NullableString** | Subreddit name, or null for the Others aggregate | 
**IsOthers** | **bool** |  | 
**Citations** | **int32** |  | 

## Methods

### NewRedditSubredditActivityPeriod

`func NewRedditSubredditActivityPeriod(date string, subreddit NullableString, isOthers bool, citations int32, ) *RedditSubredditActivityPeriod`

NewRedditSubredditActivityPeriod instantiates a new RedditSubredditActivityPeriod object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRedditSubredditActivityPeriodWithDefaults

`func NewRedditSubredditActivityPeriodWithDefaults() *RedditSubredditActivityPeriod`

NewRedditSubredditActivityPeriodWithDefaults instantiates a new RedditSubredditActivityPeriod object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDate

`func (o *RedditSubredditActivityPeriod) GetDate() string`

GetDate returns the Date field if non-nil, zero value otherwise.

### GetDateOk

`func (o *RedditSubredditActivityPeriod) GetDateOk() (*string, bool)`

GetDateOk returns a tuple with the Date field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDate

`func (o *RedditSubredditActivityPeriod) SetDate(v string)`

SetDate sets Date field to given value.


### GetSubreddit

`func (o *RedditSubredditActivityPeriod) GetSubreddit() string`

GetSubreddit returns the Subreddit field if non-nil, zero value otherwise.

### GetSubredditOk

`func (o *RedditSubredditActivityPeriod) GetSubredditOk() (*string, bool)`

GetSubredditOk returns a tuple with the Subreddit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubreddit

`func (o *RedditSubredditActivityPeriod) SetSubreddit(v string)`

SetSubreddit sets Subreddit field to given value.


### SetSubredditNil

`func (o *RedditSubredditActivityPeriod) SetSubredditNil(b bool)`

 SetSubredditNil sets the value for Subreddit to be an explicit nil

### UnsetSubreddit
`func (o *RedditSubredditActivityPeriod) UnsetSubreddit()`

UnsetSubreddit ensures that no value is present for Subreddit, not even an explicit nil
### GetIsOthers

`func (o *RedditSubredditActivityPeriod) GetIsOthers() bool`

GetIsOthers returns the IsOthers field if non-nil, zero value otherwise.

### GetIsOthersOk

`func (o *RedditSubredditActivityPeriod) GetIsOthersOk() (*bool, bool)`

GetIsOthersOk returns a tuple with the IsOthers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsOthers

`func (o *RedditSubredditActivityPeriod) SetIsOthers(v bool)`

SetIsOthers sets IsOthers field to given value.


### GetCitations

`func (o *RedditSubredditActivityPeriod) GetCitations() int32`

GetCitations returns the Citations field if non-nil, zero value otherwise.

### GetCitationsOk

`func (o *RedditSubredditActivityPeriod) GetCitationsOk() (*int32, bool)`

GetCitationsOk returns a tuple with the Citations field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCitations

`func (o *RedditSubredditActivityPeriod) SetCitations(v int32)`

SetCitations sets Citations field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


