# SovResponseSample

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Date** | Pointer to **string** |  | [optional] 
**Mentions** | Pointer to **int32** |  | [optional] 
**Partial** | Pointer to **bool** |  | [optional] 
**Confidence** | Pointer to **string** |  | [optional] 
**MarginOfError** | Pointer to **NullableFloat32** |  | [optional] 

## Methods

### NewSovResponseSample

`func NewSovResponseSample() *SovResponseSample`

NewSovResponseSample instantiates a new SovResponseSample object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSovResponseSampleWithDefaults

`func NewSovResponseSampleWithDefaults() *SovResponseSample`

NewSovResponseSampleWithDefaults instantiates a new SovResponseSample object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDate

`func (o *SovResponseSample) GetDate() string`

GetDate returns the Date field if non-nil, zero value otherwise.

### GetDateOk

`func (o *SovResponseSample) GetDateOk() (*string, bool)`

GetDateOk returns a tuple with the Date field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDate

`func (o *SovResponseSample) SetDate(v string)`

SetDate sets Date field to given value.

### HasDate

`func (o *SovResponseSample) HasDate() bool`

HasDate returns a boolean if a field has been set.

### GetMentions

`func (o *SovResponseSample) GetMentions() int32`

GetMentions returns the Mentions field if non-nil, zero value otherwise.

### GetMentionsOk

`func (o *SovResponseSample) GetMentionsOk() (*int32, bool)`

GetMentionsOk returns a tuple with the Mentions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMentions

`func (o *SovResponseSample) SetMentions(v int32)`

SetMentions sets Mentions field to given value.

### HasMentions

`func (o *SovResponseSample) HasMentions() bool`

HasMentions returns a boolean if a field has been set.

### GetPartial

`func (o *SovResponseSample) GetPartial() bool`

GetPartial returns the Partial field if non-nil, zero value otherwise.

### GetPartialOk

`func (o *SovResponseSample) GetPartialOk() (*bool, bool)`

GetPartialOk returns a tuple with the Partial field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartial

`func (o *SovResponseSample) SetPartial(v bool)`

SetPartial sets Partial field to given value.

### HasPartial

`func (o *SovResponseSample) HasPartial() bool`

HasPartial returns a boolean if a field has been set.

### GetConfidence

`func (o *SovResponseSample) GetConfidence() string`

GetConfidence returns the Confidence field if non-nil, zero value otherwise.

### GetConfidenceOk

`func (o *SovResponseSample) GetConfidenceOk() (*string, bool)`

GetConfidenceOk returns a tuple with the Confidence field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConfidence

`func (o *SovResponseSample) SetConfidence(v string)`

SetConfidence sets Confidence field to given value.

### HasConfidence

`func (o *SovResponseSample) HasConfidence() bool`

HasConfidence returns a boolean if a field has been set.

### GetMarginOfError

`func (o *SovResponseSample) GetMarginOfError() float32`

GetMarginOfError returns the MarginOfError field if non-nil, zero value otherwise.

### GetMarginOfErrorOk

`func (o *SovResponseSample) GetMarginOfErrorOk() (*float32, bool)`

GetMarginOfErrorOk returns a tuple with the MarginOfError field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMarginOfError

`func (o *SovResponseSample) SetMarginOfError(v float32)`

SetMarginOfError sets MarginOfError field to given value.

### HasMarginOfError

`func (o *SovResponseSample) HasMarginOfError() bool`

HasMarginOfError returns a boolean if a field has been set.

### SetMarginOfErrorNil

`func (o *SovResponseSample) SetMarginOfErrorNil(b bool)`

 SetMarginOfErrorNil sets the value for MarginOfError to be an explicit nil

### UnsetMarginOfError
`func (o *SovResponseSample) UnsetMarginOfError()`

UnsetMarginOfError ensures that no value is present for MarginOfError, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


