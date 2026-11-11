# TrustpilotReplies

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ReviewsHeld** | Pointer to **NullableInt32** | Reviews held for the profile | [optional] 
**RepliedCount** | Pointer to **NullableInt32** | Reviews held that the brand replied to | [optional] 
**NotRepliedCount** | Pointer to **NullableInt32** | Reviews held that the brand has not replied to | [optional] 
**ReplyRatePct** | Pointer to **NullableFloat32** | replied_count over reviews_held, on a 0-100 scale; null when no review is held | [optional] 
**MedianReplyHours** | Pointer to **NullableFloat32** | Median hours from publication to reply over the replied reviews held that carry both dates (a reply dated before its review is left out); null when there is none | [optional] 

## Methods

### NewTrustpilotReplies

`func NewTrustpilotReplies() *TrustpilotReplies`

NewTrustpilotReplies instantiates a new TrustpilotReplies object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTrustpilotRepliesWithDefaults

`func NewTrustpilotRepliesWithDefaults() *TrustpilotReplies`

NewTrustpilotRepliesWithDefaults instantiates a new TrustpilotReplies object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetReviewsHeld

`func (o *TrustpilotReplies) GetReviewsHeld() int32`

GetReviewsHeld returns the ReviewsHeld field if non-nil, zero value otherwise.

### GetReviewsHeldOk

`func (o *TrustpilotReplies) GetReviewsHeldOk() (*int32, bool)`

GetReviewsHeldOk returns a tuple with the ReviewsHeld field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReviewsHeld

`func (o *TrustpilotReplies) SetReviewsHeld(v int32)`

SetReviewsHeld sets ReviewsHeld field to given value.

### HasReviewsHeld

`func (o *TrustpilotReplies) HasReviewsHeld() bool`

HasReviewsHeld returns a boolean if a field has been set.

### SetReviewsHeldNil

`func (o *TrustpilotReplies) SetReviewsHeldNil(b bool)`

 SetReviewsHeldNil sets the value for ReviewsHeld to be an explicit nil

### UnsetReviewsHeld
`func (o *TrustpilotReplies) UnsetReviewsHeld()`

UnsetReviewsHeld ensures that no value is present for ReviewsHeld, not even an explicit nil
### GetRepliedCount

`func (o *TrustpilotReplies) GetRepliedCount() int32`

GetRepliedCount returns the RepliedCount field if non-nil, zero value otherwise.

### GetRepliedCountOk

`func (o *TrustpilotReplies) GetRepliedCountOk() (*int32, bool)`

GetRepliedCountOk returns a tuple with the RepliedCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRepliedCount

`func (o *TrustpilotReplies) SetRepliedCount(v int32)`

SetRepliedCount sets RepliedCount field to given value.

### HasRepliedCount

`func (o *TrustpilotReplies) HasRepliedCount() bool`

HasRepliedCount returns a boolean if a field has been set.

### SetRepliedCountNil

`func (o *TrustpilotReplies) SetRepliedCountNil(b bool)`

 SetRepliedCountNil sets the value for RepliedCount to be an explicit nil

### UnsetRepliedCount
`func (o *TrustpilotReplies) UnsetRepliedCount()`

UnsetRepliedCount ensures that no value is present for RepliedCount, not even an explicit nil
### GetNotRepliedCount

`func (o *TrustpilotReplies) GetNotRepliedCount() int32`

GetNotRepliedCount returns the NotRepliedCount field if non-nil, zero value otherwise.

### GetNotRepliedCountOk

`func (o *TrustpilotReplies) GetNotRepliedCountOk() (*int32, bool)`

GetNotRepliedCountOk returns a tuple with the NotRepliedCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotRepliedCount

`func (o *TrustpilotReplies) SetNotRepliedCount(v int32)`

SetNotRepliedCount sets NotRepliedCount field to given value.

### HasNotRepliedCount

`func (o *TrustpilotReplies) HasNotRepliedCount() bool`

HasNotRepliedCount returns a boolean if a field has been set.

### SetNotRepliedCountNil

`func (o *TrustpilotReplies) SetNotRepliedCountNil(b bool)`

 SetNotRepliedCountNil sets the value for NotRepliedCount to be an explicit nil

### UnsetNotRepliedCount
`func (o *TrustpilotReplies) UnsetNotRepliedCount()`

UnsetNotRepliedCount ensures that no value is present for NotRepliedCount, not even an explicit nil
### GetReplyRatePct

`func (o *TrustpilotReplies) GetReplyRatePct() float32`

GetReplyRatePct returns the ReplyRatePct field if non-nil, zero value otherwise.

### GetReplyRatePctOk

`func (o *TrustpilotReplies) GetReplyRatePctOk() (*float32, bool)`

GetReplyRatePctOk returns a tuple with the ReplyRatePct field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReplyRatePct

`func (o *TrustpilotReplies) SetReplyRatePct(v float32)`

SetReplyRatePct sets ReplyRatePct field to given value.

### HasReplyRatePct

`func (o *TrustpilotReplies) HasReplyRatePct() bool`

HasReplyRatePct returns a boolean if a field has been set.

### SetReplyRatePctNil

`func (o *TrustpilotReplies) SetReplyRatePctNil(b bool)`

 SetReplyRatePctNil sets the value for ReplyRatePct to be an explicit nil

### UnsetReplyRatePct
`func (o *TrustpilotReplies) UnsetReplyRatePct()`

UnsetReplyRatePct ensures that no value is present for ReplyRatePct, not even an explicit nil
### GetMedianReplyHours

`func (o *TrustpilotReplies) GetMedianReplyHours() float32`

GetMedianReplyHours returns the MedianReplyHours field if non-nil, zero value otherwise.

### GetMedianReplyHoursOk

`func (o *TrustpilotReplies) GetMedianReplyHoursOk() (*float32, bool)`

GetMedianReplyHoursOk returns a tuple with the MedianReplyHours field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMedianReplyHours

`func (o *TrustpilotReplies) SetMedianReplyHours(v float32)`

SetMedianReplyHours sets MedianReplyHours field to given value.

### HasMedianReplyHours

`func (o *TrustpilotReplies) HasMedianReplyHours() bool`

HasMedianReplyHours returns a boolean if a field has been set.

### SetMedianReplyHoursNil

`func (o *TrustpilotReplies) SetMedianReplyHoursNil(b bool)`

 SetMedianReplyHoursNil sets the value for MedianReplyHours to be an explicit nil

### UnsetMedianReplyHours
`func (o *TrustpilotReplies) UnsetMedianReplyHours()`

UnsetMedianReplyHours ensures that no value is present for MedianReplyHours, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


