# OwnedMediaCitingAnswer

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AnswerId** | Pointer to **int32** | The answer (prompt execution) id, readable with GET /answers/{id} | [optional] 
**PromptId** | Pointer to **int32** |  | [optional] 
**PromptText** | Pointer to **string** |  | [optional] 
**Model** | Pointer to **string** |  | [optional] 
**CountryCode** | Pointer to **NullableString** |  | [optional] 
**LanguageCode** | Pointer to **NullableString** |  | [optional] 
**ExecutedAt** | Pointer to **NullableTime** |  | [optional] 
**Excerpt** | Pointer to **NullableString** | The start of the answer as plain text (at most 300 characters) | [optional] 
**AppUrl** | Pointer to **string** | The answer in the app | [optional] 

## Methods

### NewOwnedMediaCitingAnswer

`func NewOwnedMediaCitingAnswer() *OwnedMediaCitingAnswer`

NewOwnedMediaCitingAnswer instantiates a new OwnedMediaCitingAnswer object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOwnedMediaCitingAnswerWithDefaults

`func NewOwnedMediaCitingAnswerWithDefaults() *OwnedMediaCitingAnswer`

NewOwnedMediaCitingAnswerWithDefaults instantiates a new OwnedMediaCitingAnswer object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAnswerId

`func (o *OwnedMediaCitingAnswer) GetAnswerId() int32`

GetAnswerId returns the AnswerId field if non-nil, zero value otherwise.

### GetAnswerIdOk

`func (o *OwnedMediaCitingAnswer) GetAnswerIdOk() (*int32, bool)`

GetAnswerIdOk returns a tuple with the AnswerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAnswerId

`func (o *OwnedMediaCitingAnswer) SetAnswerId(v int32)`

SetAnswerId sets AnswerId field to given value.

### HasAnswerId

`func (o *OwnedMediaCitingAnswer) HasAnswerId() bool`

HasAnswerId returns a boolean if a field has been set.

### GetPromptId

`func (o *OwnedMediaCitingAnswer) GetPromptId() int32`

GetPromptId returns the PromptId field if non-nil, zero value otherwise.

### GetPromptIdOk

`func (o *OwnedMediaCitingAnswer) GetPromptIdOk() (*int32, bool)`

GetPromptIdOk returns a tuple with the PromptId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPromptId

`func (o *OwnedMediaCitingAnswer) SetPromptId(v int32)`

SetPromptId sets PromptId field to given value.

### HasPromptId

`func (o *OwnedMediaCitingAnswer) HasPromptId() bool`

HasPromptId returns a boolean if a field has been set.

### GetPromptText

`func (o *OwnedMediaCitingAnswer) GetPromptText() string`

GetPromptText returns the PromptText field if non-nil, zero value otherwise.

### GetPromptTextOk

`func (o *OwnedMediaCitingAnswer) GetPromptTextOk() (*string, bool)`

GetPromptTextOk returns a tuple with the PromptText field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPromptText

`func (o *OwnedMediaCitingAnswer) SetPromptText(v string)`

SetPromptText sets PromptText field to given value.

### HasPromptText

`func (o *OwnedMediaCitingAnswer) HasPromptText() bool`

HasPromptText returns a boolean if a field has been set.

### GetModel

`func (o *OwnedMediaCitingAnswer) GetModel() string`

GetModel returns the Model field if non-nil, zero value otherwise.

### GetModelOk

`func (o *OwnedMediaCitingAnswer) GetModelOk() (*string, bool)`

GetModelOk returns a tuple with the Model field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModel

`func (o *OwnedMediaCitingAnswer) SetModel(v string)`

SetModel sets Model field to given value.

### HasModel

`func (o *OwnedMediaCitingAnswer) HasModel() bool`

HasModel returns a boolean if a field has been set.

### GetCountryCode

`func (o *OwnedMediaCitingAnswer) GetCountryCode() string`

GetCountryCode returns the CountryCode field if non-nil, zero value otherwise.

### GetCountryCodeOk

`func (o *OwnedMediaCitingAnswer) GetCountryCodeOk() (*string, bool)`

GetCountryCodeOk returns a tuple with the CountryCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountryCode

`func (o *OwnedMediaCitingAnswer) SetCountryCode(v string)`

SetCountryCode sets CountryCode field to given value.

### HasCountryCode

`func (o *OwnedMediaCitingAnswer) HasCountryCode() bool`

HasCountryCode returns a boolean if a field has been set.

### SetCountryCodeNil

`func (o *OwnedMediaCitingAnswer) SetCountryCodeNil(b bool)`

 SetCountryCodeNil sets the value for CountryCode to be an explicit nil

### UnsetCountryCode
`func (o *OwnedMediaCitingAnswer) UnsetCountryCode()`

UnsetCountryCode ensures that no value is present for CountryCode, not even an explicit nil
### GetLanguageCode

`func (o *OwnedMediaCitingAnswer) GetLanguageCode() string`

GetLanguageCode returns the LanguageCode field if non-nil, zero value otherwise.

### GetLanguageCodeOk

`func (o *OwnedMediaCitingAnswer) GetLanguageCodeOk() (*string, bool)`

GetLanguageCodeOk returns a tuple with the LanguageCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLanguageCode

`func (o *OwnedMediaCitingAnswer) SetLanguageCode(v string)`

SetLanguageCode sets LanguageCode field to given value.

### HasLanguageCode

`func (o *OwnedMediaCitingAnswer) HasLanguageCode() bool`

HasLanguageCode returns a boolean if a field has been set.

### SetLanguageCodeNil

`func (o *OwnedMediaCitingAnswer) SetLanguageCodeNil(b bool)`

 SetLanguageCodeNil sets the value for LanguageCode to be an explicit nil

### UnsetLanguageCode
`func (o *OwnedMediaCitingAnswer) UnsetLanguageCode()`

UnsetLanguageCode ensures that no value is present for LanguageCode, not even an explicit nil
### GetExecutedAt

`func (o *OwnedMediaCitingAnswer) GetExecutedAt() time.Time`

GetExecutedAt returns the ExecutedAt field if non-nil, zero value otherwise.

### GetExecutedAtOk

`func (o *OwnedMediaCitingAnswer) GetExecutedAtOk() (*time.Time, bool)`

GetExecutedAtOk returns a tuple with the ExecutedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExecutedAt

`func (o *OwnedMediaCitingAnswer) SetExecutedAt(v time.Time)`

SetExecutedAt sets ExecutedAt field to given value.

### HasExecutedAt

`func (o *OwnedMediaCitingAnswer) HasExecutedAt() bool`

HasExecutedAt returns a boolean if a field has been set.

### SetExecutedAtNil

`func (o *OwnedMediaCitingAnswer) SetExecutedAtNil(b bool)`

 SetExecutedAtNil sets the value for ExecutedAt to be an explicit nil

### UnsetExecutedAt
`func (o *OwnedMediaCitingAnswer) UnsetExecutedAt()`

UnsetExecutedAt ensures that no value is present for ExecutedAt, not even an explicit nil
### GetExcerpt

`func (o *OwnedMediaCitingAnswer) GetExcerpt() string`

GetExcerpt returns the Excerpt field if non-nil, zero value otherwise.

### GetExcerptOk

`func (o *OwnedMediaCitingAnswer) GetExcerptOk() (*string, bool)`

GetExcerptOk returns a tuple with the Excerpt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExcerpt

`func (o *OwnedMediaCitingAnswer) SetExcerpt(v string)`

SetExcerpt sets Excerpt field to given value.

### HasExcerpt

`func (o *OwnedMediaCitingAnswer) HasExcerpt() bool`

HasExcerpt returns a boolean if a field has been set.

### SetExcerptNil

`func (o *OwnedMediaCitingAnswer) SetExcerptNil(b bool)`

 SetExcerptNil sets the value for Excerpt to be an explicit nil

### UnsetExcerpt
`func (o *OwnedMediaCitingAnswer) UnsetExcerpt()`

UnsetExcerpt ensures that no value is present for Excerpt, not even an explicit nil
### GetAppUrl

`func (o *OwnedMediaCitingAnswer) GetAppUrl() string`

GetAppUrl returns the AppUrl field if non-nil, zero value otherwise.

### GetAppUrlOk

`func (o *OwnedMediaCitingAnswer) GetAppUrlOk() (*string, bool)`

GetAppUrlOk returns a tuple with the AppUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAppUrl

`func (o *OwnedMediaCitingAnswer) SetAppUrl(v string)`

SetAppUrl sets AppUrl field to given value.

### HasAppUrl

`func (o *OwnedMediaCitingAnswer) HasAppUrl() bool`

HasAppUrl returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


