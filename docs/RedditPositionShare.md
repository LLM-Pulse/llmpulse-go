# RedditPositionShare

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Bucket** | **string** |  | 
**Citations** | **int32** |  | 
**SharePct** | **float32** | Percentage (0-100) of citations in the included position buckets | 

## Methods

### NewRedditPositionShare

`func NewRedditPositionShare(bucket string, citations int32, sharePct float32, ) *RedditPositionShare`

NewRedditPositionShare instantiates a new RedditPositionShare object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRedditPositionShareWithDefaults

`func NewRedditPositionShareWithDefaults() *RedditPositionShare`

NewRedditPositionShareWithDefaults instantiates a new RedditPositionShare object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBucket

`func (o *RedditPositionShare) GetBucket() string`

GetBucket returns the Bucket field if non-nil, zero value otherwise.

### GetBucketOk

`func (o *RedditPositionShare) GetBucketOk() (*string, bool)`

GetBucketOk returns a tuple with the Bucket field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBucket

`func (o *RedditPositionShare) SetBucket(v string)`

SetBucket sets Bucket field to given value.


### GetCitations

`func (o *RedditPositionShare) GetCitations() int32`

GetCitations returns the Citations field if non-nil, zero value otherwise.

### GetCitationsOk

`func (o *RedditPositionShare) GetCitationsOk() (*int32, bool)`

GetCitationsOk returns a tuple with the Citations field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCitations

`func (o *RedditPositionShare) SetCitations(v int32)`

SetCitations sets Citations field to given value.


### GetSharePct

`func (o *RedditPositionShare) GetSharePct() float32`

GetSharePct returns the SharePct field if non-nil, zero value otherwise.

### GetSharePctOk

`func (o *RedditPositionShare) GetSharePctOk() (*float32, bool)`

GetSharePctOk returns a tuple with the SharePct field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSharePct

`func (o *RedditPositionShare) SetSharePct(v float32)`

SetSharePct sets SharePct field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


