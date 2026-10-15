# SuggestedPrompt

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **int32** |  | 
**Prompt** | **string** |  | 
**Source** | **string** | The generator that wrote it: website, magic (keyword runs), topic, reddit, paa, reputational, translate, gsc (Search Console) or catalog | 
**Status** | **string** | pending, accepted or rejected | 
**CountryCode** | **NullableString** |  | 
**LanguageCode** | **NullableString** |  | 
**PromptId** | **NullableInt32** | The prompt an accepted suggestion became | 
**AcceptedAt** | **NullableTime** |  | 
**CreatedAt** | **time.Time** |  | 

## Methods

### NewSuggestedPrompt

`func NewSuggestedPrompt(id int32, prompt string, source string, status string, countryCode NullableString, languageCode NullableString, promptId NullableInt32, acceptedAt NullableTime, createdAt time.Time, ) *SuggestedPrompt`

NewSuggestedPrompt instantiates a new SuggestedPrompt object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSuggestedPromptWithDefaults

`func NewSuggestedPromptWithDefaults() *SuggestedPrompt`

NewSuggestedPromptWithDefaults instantiates a new SuggestedPrompt object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *SuggestedPrompt) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *SuggestedPrompt) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *SuggestedPrompt) SetId(v int32)`

SetId sets Id field to given value.


### GetPrompt

`func (o *SuggestedPrompt) GetPrompt() string`

GetPrompt returns the Prompt field if non-nil, zero value otherwise.

### GetPromptOk

`func (o *SuggestedPrompt) GetPromptOk() (*string, bool)`

GetPromptOk returns a tuple with the Prompt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrompt

`func (o *SuggestedPrompt) SetPrompt(v string)`

SetPrompt sets Prompt field to given value.


### GetSource

`func (o *SuggestedPrompt) GetSource() string`

GetSource returns the Source field if non-nil, zero value otherwise.

### GetSourceOk

`func (o *SuggestedPrompt) GetSourceOk() (*string, bool)`

GetSourceOk returns a tuple with the Source field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSource

`func (o *SuggestedPrompt) SetSource(v string)`

SetSource sets Source field to given value.


### GetStatus

`func (o *SuggestedPrompt) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *SuggestedPrompt) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *SuggestedPrompt) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetCountryCode

`func (o *SuggestedPrompt) GetCountryCode() string`

GetCountryCode returns the CountryCode field if non-nil, zero value otherwise.

### GetCountryCodeOk

`func (o *SuggestedPrompt) GetCountryCodeOk() (*string, bool)`

GetCountryCodeOk returns a tuple with the CountryCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountryCode

`func (o *SuggestedPrompt) SetCountryCode(v string)`

SetCountryCode sets CountryCode field to given value.


### SetCountryCodeNil

`func (o *SuggestedPrompt) SetCountryCodeNil(b bool)`

 SetCountryCodeNil sets the value for CountryCode to be an explicit nil

### UnsetCountryCode
`func (o *SuggestedPrompt) UnsetCountryCode()`

UnsetCountryCode ensures that no value is present for CountryCode, not even an explicit nil
### GetLanguageCode

`func (o *SuggestedPrompt) GetLanguageCode() string`

GetLanguageCode returns the LanguageCode field if non-nil, zero value otherwise.

### GetLanguageCodeOk

`func (o *SuggestedPrompt) GetLanguageCodeOk() (*string, bool)`

GetLanguageCodeOk returns a tuple with the LanguageCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLanguageCode

`func (o *SuggestedPrompt) SetLanguageCode(v string)`

SetLanguageCode sets LanguageCode field to given value.


### SetLanguageCodeNil

`func (o *SuggestedPrompt) SetLanguageCodeNil(b bool)`

 SetLanguageCodeNil sets the value for LanguageCode to be an explicit nil

### UnsetLanguageCode
`func (o *SuggestedPrompt) UnsetLanguageCode()`

UnsetLanguageCode ensures that no value is present for LanguageCode, not even an explicit nil
### GetPromptId

`func (o *SuggestedPrompt) GetPromptId() int32`

GetPromptId returns the PromptId field if non-nil, zero value otherwise.

### GetPromptIdOk

`func (o *SuggestedPrompt) GetPromptIdOk() (*int32, bool)`

GetPromptIdOk returns a tuple with the PromptId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPromptId

`func (o *SuggestedPrompt) SetPromptId(v int32)`

SetPromptId sets PromptId field to given value.


### SetPromptIdNil

`func (o *SuggestedPrompt) SetPromptIdNil(b bool)`

 SetPromptIdNil sets the value for PromptId to be an explicit nil

### UnsetPromptId
`func (o *SuggestedPrompt) UnsetPromptId()`

UnsetPromptId ensures that no value is present for PromptId, not even an explicit nil
### GetAcceptedAt

`func (o *SuggestedPrompt) GetAcceptedAt() time.Time`

GetAcceptedAt returns the AcceptedAt field if non-nil, zero value otherwise.

### GetAcceptedAtOk

`func (o *SuggestedPrompt) GetAcceptedAtOk() (*time.Time, bool)`

GetAcceptedAtOk returns a tuple with the AcceptedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAcceptedAt

`func (o *SuggestedPrompt) SetAcceptedAt(v time.Time)`

SetAcceptedAt sets AcceptedAt field to given value.


### SetAcceptedAtNil

`func (o *SuggestedPrompt) SetAcceptedAtNil(b bool)`

 SetAcceptedAtNil sets the value for AcceptedAt to be an explicit nil

### UnsetAcceptedAt
`func (o *SuggestedPrompt) UnsetAcceptedAt()`

UnsetAcceptedAt ensures that no value is present for AcceptedAt, not even an explicit nil
### GetCreatedAt

`func (o *SuggestedPrompt) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *SuggestedPrompt) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *SuggestedPrompt) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


