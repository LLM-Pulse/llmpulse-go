# PromptsCreateRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ProjectId** | **int32** |  | 
**Prompts** | **[]string** |  | 
**CountryCode** | **string** |  | 
**LanguageCode** | **string** |  | 

## Methods

### NewPromptsCreateRequest

`func NewPromptsCreateRequest(projectId int32, prompts []string, countryCode string, languageCode string, ) *PromptsCreateRequest`

NewPromptsCreateRequest instantiates a new PromptsCreateRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPromptsCreateRequestWithDefaults

`func NewPromptsCreateRequestWithDefaults() *PromptsCreateRequest`

NewPromptsCreateRequestWithDefaults instantiates a new PromptsCreateRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProjectId

`func (o *PromptsCreateRequest) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *PromptsCreateRequest) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *PromptsCreateRequest) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.


### GetPrompts

`func (o *PromptsCreateRequest) GetPrompts() []string`

GetPrompts returns the Prompts field if non-nil, zero value otherwise.

### GetPromptsOk

`func (o *PromptsCreateRequest) GetPromptsOk() (*[]string, bool)`

GetPromptsOk returns a tuple with the Prompts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrompts

`func (o *PromptsCreateRequest) SetPrompts(v []string)`

SetPrompts sets Prompts field to given value.


### GetCountryCode

`func (o *PromptsCreateRequest) GetCountryCode() string`

GetCountryCode returns the CountryCode field if non-nil, zero value otherwise.

### GetCountryCodeOk

`func (o *PromptsCreateRequest) GetCountryCodeOk() (*string, bool)`

GetCountryCodeOk returns a tuple with the CountryCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountryCode

`func (o *PromptsCreateRequest) SetCountryCode(v string)`

SetCountryCode sets CountryCode field to given value.


### GetLanguageCode

`func (o *PromptsCreateRequest) GetLanguageCode() string`

GetLanguageCode returns the LanguageCode field if non-nil, zero value otherwise.

### GetLanguageCodeOk

`func (o *PromptsCreateRequest) GetLanguageCodeOk() (*string, bool)`

GetLanguageCodeOk returns a tuple with the LanguageCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLanguageCode

`func (o *PromptsCreateRequest) SetLanguageCode(v string)`

SetLanguageCode sets LanguageCode field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


