# CatalogPromptSuggestion

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **int32** |  | 
**Prompt** | **string** |  | 
**Status** | **string** | pending, accepted or rejected | 
**Source** | **string** | Always catalog | 
**CountryCode** | **NullableString** |  | 
**LanguageCode** | **NullableString** |  | 
**Product** | [**CatalogPromptSuggestionProduct**](CatalogPromptSuggestionProduct.md) |  | 
**PromptId** | **NullableInt32** | The tracked prompt an accepted suggestion became; null until accepted | 
**AcceptedAt** | **NullableTime** | When the suggestion was accepted; null until then | 
**CreatedAt** | **time.Time** |  | 

## Methods

### NewCatalogPromptSuggestion

`func NewCatalogPromptSuggestion(id int32, prompt string, status string, source string, countryCode NullableString, languageCode NullableString, product CatalogPromptSuggestionProduct, promptId NullableInt32, acceptedAt NullableTime, createdAt time.Time, ) *CatalogPromptSuggestion`

NewCatalogPromptSuggestion instantiates a new CatalogPromptSuggestion object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCatalogPromptSuggestionWithDefaults

`func NewCatalogPromptSuggestionWithDefaults() *CatalogPromptSuggestion`

NewCatalogPromptSuggestionWithDefaults instantiates a new CatalogPromptSuggestion object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *CatalogPromptSuggestion) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *CatalogPromptSuggestion) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *CatalogPromptSuggestion) SetId(v int32)`

SetId sets Id field to given value.


### GetPrompt

`func (o *CatalogPromptSuggestion) GetPrompt() string`

GetPrompt returns the Prompt field if non-nil, zero value otherwise.

### GetPromptOk

`func (o *CatalogPromptSuggestion) GetPromptOk() (*string, bool)`

GetPromptOk returns a tuple with the Prompt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrompt

`func (o *CatalogPromptSuggestion) SetPrompt(v string)`

SetPrompt sets Prompt field to given value.


### GetStatus

`func (o *CatalogPromptSuggestion) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *CatalogPromptSuggestion) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *CatalogPromptSuggestion) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetSource

`func (o *CatalogPromptSuggestion) GetSource() string`

GetSource returns the Source field if non-nil, zero value otherwise.

### GetSourceOk

`func (o *CatalogPromptSuggestion) GetSourceOk() (*string, bool)`

GetSourceOk returns a tuple with the Source field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSource

`func (o *CatalogPromptSuggestion) SetSource(v string)`

SetSource sets Source field to given value.


### GetCountryCode

`func (o *CatalogPromptSuggestion) GetCountryCode() string`

GetCountryCode returns the CountryCode field if non-nil, zero value otherwise.

### GetCountryCodeOk

`func (o *CatalogPromptSuggestion) GetCountryCodeOk() (*string, bool)`

GetCountryCodeOk returns a tuple with the CountryCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountryCode

`func (o *CatalogPromptSuggestion) SetCountryCode(v string)`

SetCountryCode sets CountryCode field to given value.


### SetCountryCodeNil

`func (o *CatalogPromptSuggestion) SetCountryCodeNil(b bool)`

 SetCountryCodeNil sets the value for CountryCode to be an explicit nil

### UnsetCountryCode
`func (o *CatalogPromptSuggestion) UnsetCountryCode()`

UnsetCountryCode ensures that no value is present for CountryCode, not even an explicit nil
### GetLanguageCode

`func (o *CatalogPromptSuggestion) GetLanguageCode() string`

GetLanguageCode returns the LanguageCode field if non-nil, zero value otherwise.

### GetLanguageCodeOk

`func (o *CatalogPromptSuggestion) GetLanguageCodeOk() (*string, bool)`

GetLanguageCodeOk returns a tuple with the LanguageCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLanguageCode

`func (o *CatalogPromptSuggestion) SetLanguageCode(v string)`

SetLanguageCode sets LanguageCode field to given value.


### SetLanguageCodeNil

`func (o *CatalogPromptSuggestion) SetLanguageCodeNil(b bool)`

 SetLanguageCodeNil sets the value for LanguageCode to be an explicit nil

### UnsetLanguageCode
`func (o *CatalogPromptSuggestion) UnsetLanguageCode()`

UnsetLanguageCode ensures that no value is present for LanguageCode, not even an explicit nil
### GetProduct

`func (o *CatalogPromptSuggestion) GetProduct() CatalogPromptSuggestionProduct`

GetProduct returns the Product field if non-nil, zero value otherwise.

### GetProductOk

`func (o *CatalogPromptSuggestion) GetProductOk() (*CatalogPromptSuggestionProduct, bool)`

GetProductOk returns a tuple with the Product field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProduct

`func (o *CatalogPromptSuggestion) SetProduct(v CatalogPromptSuggestionProduct)`

SetProduct sets Product field to given value.


### GetPromptId

`func (o *CatalogPromptSuggestion) GetPromptId() int32`

GetPromptId returns the PromptId field if non-nil, zero value otherwise.

### GetPromptIdOk

`func (o *CatalogPromptSuggestion) GetPromptIdOk() (*int32, bool)`

GetPromptIdOk returns a tuple with the PromptId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPromptId

`func (o *CatalogPromptSuggestion) SetPromptId(v int32)`

SetPromptId sets PromptId field to given value.


### SetPromptIdNil

`func (o *CatalogPromptSuggestion) SetPromptIdNil(b bool)`

 SetPromptIdNil sets the value for PromptId to be an explicit nil

### UnsetPromptId
`func (o *CatalogPromptSuggestion) UnsetPromptId()`

UnsetPromptId ensures that no value is present for PromptId, not even an explicit nil
### GetAcceptedAt

`func (o *CatalogPromptSuggestion) GetAcceptedAt() time.Time`

GetAcceptedAt returns the AcceptedAt field if non-nil, zero value otherwise.

### GetAcceptedAtOk

`func (o *CatalogPromptSuggestion) GetAcceptedAtOk() (*time.Time, bool)`

GetAcceptedAtOk returns a tuple with the AcceptedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAcceptedAt

`func (o *CatalogPromptSuggestion) SetAcceptedAt(v time.Time)`

SetAcceptedAt sets AcceptedAt field to given value.


### SetAcceptedAtNil

`func (o *CatalogPromptSuggestion) SetAcceptedAtNil(b bool)`

 SetAcceptedAtNil sets the value for AcceptedAt to be an explicit nil

### UnsetAcceptedAt
`func (o *CatalogPromptSuggestion) UnsetAcceptedAt()`

UnsetAcceptedAt ensures that no value is present for AcceptedAt, not even an explicit nil
### GetCreatedAt

`func (o *CatalogPromptSuggestion) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *CatalogPromptSuggestion) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *CatalogPromptSuggestion) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


