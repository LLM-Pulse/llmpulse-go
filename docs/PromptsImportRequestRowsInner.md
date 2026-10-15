# PromptsImportRequestRowsInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Prompt** | **string** |  | 
**CountryCode** | Pointer to **string** | ISO 3166-1 alpha-2 code or country name (default the project country) | [optional] 
**LanguageCode** | Pointer to **string** | ISO language code or language name (default the project language) | [optional] 
**Tags** | Pointer to **[]string** | Tag names for this prompt, created when missing | [optional] 

## Methods

### NewPromptsImportRequestRowsInner

`func NewPromptsImportRequestRowsInner(prompt string, ) *PromptsImportRequestRowsInner`

NewPromptsImportRequestRowsInner instantiates a new PromptsImportRequestRowsInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPromptsImportRequestRowsInnerWithDefaults

`func NewPromptsImportRequestRowsInnerWithDefaults() *PromptsImportRequestRowsInner`

NewPromptsImportRequestRowsInnerWithDefaults instantiates a new PromptsImportRequestRowsInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPrompt

`func (o *PromptsImportRequestRowsInner) GetPrompt() string`

GetPrompt returns the Prompt field if non-nil, zero value otherwise.

### GetPromptOk

`func (o *PromptsImportRequestRowsInner) GetPromptOk() (*string, bool)`

GetPromptOk returns a tuple with the Prompt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrompt

`func (o *PromptsImportRequestRowsInner) SetPrompt(v string)`

SetPrompt sets Prompt field to given value.


### GetCountryCode

`func (o *PromptsImportRequestRowsInner) GetCountryCode() string`

GetCountryCode returns the CountryCode field if non-nil, zero value otherwise.

### GetCountryCodeOk

`func (o *PromptsImportRequestRowsInner) GetCountryCodeOk() (*string, bool)`

GetCountryCodeOk returns a tuple with the CountryCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountryCode

`func (o *PromptsImportRequestRowsInner) SetCountryCode(v string)`

SetCountryCode sets CountryCode field to given value.

### HasCountryCode

`func (o *PromptsImportRequestRowsInner) HasCountryCode() bool`

HasCountryCode returns a boolean if a field has been set.

### GetLanguageCode

`func (o *PromptsImportRequestRowsInner) GetLanguageCode() string`

GetLanguageCode returns the LanguageCode field if non-nil, zero value otherwise.

### GetLanguageCodeOk

`func (o *PromptsImportRequestRowsInner) GetLanguageCodeOk() (*string, bool)`

GetLanguageCodeOk returns a tuple with the LanguageCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLanguageCode

`func (o *PromptsImportRequestRowsInner) SetLanguageCode(v string)`

SetLanguageCode sets LanguageCode field to given value.

### HasLanguageCode

`func (o *PromptsImportRequestRowsInner) HasLanguageCode() bool`

HasLanguageCode returns a boolean if a field has been set.

### GetTags

`func (o *PromptsImportRequestRowsInner) GetTags() []string`

GetTags returns the Tags field if non-nil, zero value otherwise.

### GetTagsOk

`func (o *PromptsImportRequestRowsInner) GetTagsOk() (*[]string, bool)`

GetTagsOk returns a tuple with the Tags field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTags

`func (o *PromptsImportRequestRowsInner) SetTags(v []string)`

SetTags sets Tags field to given value.

### HasTags

`func (o *PromptsImportRequestRowsInner) HasTags() bool`

HasTags returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


