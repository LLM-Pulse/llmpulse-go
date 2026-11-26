# AiTrafficResponseBySourceInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Source** | **string** | AI source slug, such as chatgpt or perplexity | 
**Name** | **string** | Display name of the source | 
**Users** | **int32** |  | 
**Sessions** | **int32** |  | 
**Conversions** | **int32** |  | 

## Methods

### NewAiTrafficResponseBySourceInner

`func NewAiTrafficResponseBySourceInner(source string, name string, users int32, sessions int32, conversions int32, ) *AiTrafficResponseBySourceInner`

NewAiTrafficResponseBySourceInner instantiates a new AiTrafficResponseBySourceInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAiTrafficResponseBySourceInnerWithDefaults

`func NewAiTrafficResponseBySourceInnerWithDefaults() *AiTrafficResponseBySourceInner`

NewAiTrafficResponseBySourceInnerWithDefaults instantiates a new AiTrafficResponseBySourceInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSource

`func (o *AiTrafficResponseBySourceInner) GetSource() string`

GetSource returns the Source field if non-nil, zero value otherwise.

### GetSourceOk

`func (o *AiTrafficResponseBySourceInner) GetSourceOk() (*string, bool)`

GetSourceOk returns a tuple with the Source field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSource

`func (o *AiTrafficResponseBySourceInner) SetSource(v string)`

SetSource sets Source field to given value.


### GetName

`func (o *AiTrafficResponseBySourceInner) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *AiTrafficResponseBySourceInner) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *AiTrafficResponseBySourceInner) SetName(v string)`

SetName sets Name field to given value.


### GetUsers

`func (o *AiTrafficResponseBySourceInner) GetUsers() int32`

GetUsers returns the Users field if non-nil, zero value otherwise.

### GetUsersOk

`func (o *AiTrafficResponseBySourceInner) GetUsersOk() (*int32, bool)`

GetUsersOk returns a tuple with the Users field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsers

`func (o *AiTrafficResponseBySourceInner) SetUsers(v int32)`

SetUsers sets Users field to given value.


### GetSessions

`func (o *AiTrafficResponseBySourceInner) GetSessions() int32`

GetSessions returns the Sessions field if non-nil, zero value otherwise.

### GetSessionsOk

`func (o *AiTrafficResponseBySourceInner) GetSessionsOk() (*int32, bool)`

GetSessionsOk returns a tuple with the Sessions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSessions

`func (o *AiTrafficResponseBySourceInner) SetSessions(v int32)`

SetSessions sets Sessions field to given value.


### GetConversions

`func (o *AiTrafficResponseBySourceInner) GetConversions() int32`

GetConversions returns the Conversions field if non-nil, zero value otherwise.

### GetConversionsOk

`func (o *AiTrafficResponseBySourceInner) GetConversionsOk() (*int32, bool)`

GetConversionsOk returns a tuple with the Conversions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConversions

`func (o *AiTrafficResponseBySourceInner) SetConversions(v int32)`

SetConversions sets Conversions field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


