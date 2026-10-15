# PromptGenerationRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ProjectId** | **int32** |  | 
**Source** | **string** | Which Add prompts generator to run | 
**Query** | Pointer to **string** | keyword: optional keyword or research query. topic and reddit: required topic (reddit: the brand when search_type&#x3D;brand). paa: one keyword, as an alternative to keywords. | [optional] 
**Count** | Pointer to **int32** | keyword and topic: how many suggestions to ask for, capped by the prompt slots left | [optional] [default to 20]
**CountryCode** | Pointer to **string** | ISO 3166-1 alpha-2 country of the suggestions (default the project country) | [optional] 
**LanguageCode** | Pointer to **string** | ISO language code of the suggestions (default the project language) | [optional] 
**CompetitorId** | Pointer to **int32** | keyword: write the suggestions around this competitor of the project | [optional] 
**SearchType** | Pointer to **string** | reddit: search discussions of a topic or a brand | [optional] [default to "topic"]
**Keywords** | Pointer to **[]string** | paa: up to 5 keywords; each is a People Also Ask lookup counted against the account&#39;s 24-hour allowance | [optional] 
**SourceCountryCode** | Pointer to **string** | translate: country of the prompts to translate | [optional] 
**SourceLanguageCode** | Pointer to **string** | translate: language of the prompts to translate | [optional] 
**MinWords** | Pointer to **int32** | search_console: skip queries shorter than this many words | [optional] [default to 0]
**AllCountries** | Pointer to **bool** | search_console: include queries from every country instead of country_code only | [optional] [default to false]

## Methods

### NewPromptGenerationRequest

`func NewPromptGenerationRequest(projectId int32, source string, ) *PromptGenerationRequest`

NewPromptGenerationRequest instantiates a new PromptGenerationRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPromptGenerationRequestWithDefaults

`func NewPromptGenerationRequestWithDefaults() *PromptGenerationRequest`

NewPromptGenerationRequestWithDefaults instantiates a new PromptGenerationRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProjectId

`func (o *PromptGenerationRequest) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *PromptGenerationRequest) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *PromptGenerationRequest) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.


### GetSource

`func (o *PromptGenerationRequest) GetSource() string`

GetSource returns the Source field if non-nil, zero value otherwise.

### GetSourceOk

`func (o *PromptGenerationRequest) GetSourceOk() (*string, bool)`

GetSourceOk returns a tuple with the Source field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSource

`func (o *PromptGenerationRequest) SetSource(v string)`

SetSource sets Source field to given value.


### GetQuery

`func (o *PromptGenerationRequest) GetQuery() string`

GetQuery returns the Query field if non-nil, zero value otherwise.

### GetQueryOk

`func (o *PromptGenerationRequest) GetQueryOk() (*string, bool)`

GetQueryOk returns a tuple with the Query field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuery

`func (o *PromptGenerationRequest) SetQuery(v string)`

SetQuery sets Query field to given value.

### HasQuery

`func (o *PromptGenerationRequest) HasQuery() bool`

HasQuery returns a boolean if a field has been set.

### GetCount

`func (o *PromptGenerationRequest) GetCount() int32`

GetCount returns the Count field if non-nil, zero value otherwise.

### GetCountOk

`func (o *PromptGenerationRequest) GetCountOk() (*int32, bool)`

GetCountOk returns a tuple with the Count field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCount

`func (o *PromptGenerationRequest) SetCount(v int32)`

SetCount sets Count field to given value.

### HasCount

`func (o *PromptGenerationRequest) HasCount() bool`

HasCount returns a boolean if a field has been set.

### GetCountryCode

`func (o *PromptGenerationRequest) GetCountryCode() string`

GetCountryCode returns the CountryCode field if non-nil, zero value otherwise.

### GetCountryCodeOk

`func (o *PromptGenerationRequest) GetCountryCodeOk() (*string, bool)`

GetCountryCodeOk returns a tuple with the CountryCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountryCode

`func (o *PromptGenerationRequest) SetCountryCode(v string)`

SetCountryCode sets CountryCode field to given value.

### HasCountryCode

`func (o *PromptGenerationRequest) HasCountryCode() bool`

HasCountryCode returns a boolean if a field has been set.

### GetLanguageCode

`func (o *PromptGenerationRequest) GetLanguageCode() string`

GetLanguageCode returns the LanguageCode field if non-nil, zero value otherwise.

### GetLanguageCodeOk

`func (o *PromptGenerationRequest) GetLanguageCodeOk() (*string, bool)`

GetLanguageCodeOk returns a tuple with the LanguageCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLanguageCode

`func (o *PromptGenerationRequest) SetLanguageCode(v string)`

SetLanguageCode sets LanguageCode field to given value.

### HasLanguageCode

`func (o *PromptGenerationRequest) HasLanguageCode() bool`

HasLanguageCode returns a boolean if a field has been set.

### GetCompetitorId

`func (o *PromptGenerationRequest) GetCompetitorId() int32`

GetCompetitorId returns the CompetitorId field if non-nil, zero value otherwise.

### GetCompetitorIdOk

`func (o *PromptGenerationRequest) GetCompetitorIdOk() (*int32, bool)`

GetCompetitorIdOk returns a tuple with the CompetitorId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompetitorId

`func (o *PromptGenerationRequest) SetCompetitorId(v int32)`

SetCompetitorId sets CompetitorId field to given value.

### HasCompetitorId

`func (o *PromptGenerationRequest) HasCompetitorId() bool`

HasCompetitorId returns a boolean if a field has been set.

### GetSearchType

`func (o *PromptGenerationRequest) GetSearchType() string`

GetSearchType returns the SearchType field if non-nil, zero value otherwise.

### GetSearchTypeOk

`func (o *PromptGenerationRequest) GetSearchTypeOk() (*string, bool)`

GetSearchTypeOk returns a tuple with the SearchType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSearchType

`func (o *PromptGenerationRequest) SetSearchType(v string)`

SetSearchType sets SearchType field to given value.

### HasSearchType

`func (o *PromptGenerationRequest) HasSearchType() bool`

HasSearchType returns a boolean if a field has been set.

### GetKeywords

`func (o *PromptGenerationRequest) GetKeywords() []string`

GetKeywords returns the Keywords field if non-nil, zero value otherwise.

### GetKeywordsOk

`func (o *PromptGenerationRequest) GetKeywordsOk() (*[]string, bool)`

GetKeywordsOk returns a tuple with the Keywords field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKeywords

`func (o *PromptGenerationRequest) SetKeywords(v []string)`

SetKeywords sets Keywords field to given value.

### HasKeywords

`func (o *PromptGenerationRequest) HasKeywords() bool`

HasKeywords returns a boolean if a field has been set.

### GetSourceCountryCode

`func (o *PromptGenerationRequest) GetSourceCountryCode() string`

GetSourceCountryCode returns the SourceCountryCode field if non-nil, zero value otherwise.

### GetSourceCountryCodeOk

`func (o *PromptGenerationRequest) GetSourceCountryCodeOk() (*string, bool)`

GetSourceCountryCodeOk returns a tuple with the SourceCountryCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSourceCountryCode

`func (o *PromptGenerationRequest) SetSourceCountryCode(v string)`

SetSourceCountryCode sets SourceCountryCode field to given value.

### HasSourceCountryCode

`func (o *PromptGenerationRequest) HasSourceCountryCode() bool`

HasSourceCountryCode returns a boolean if a field has been set.

### GetSourceLanguageCode

`func (o *PromptGenerationRequest) GetSourceLanguageCode() string`

GetSourceLanguageCode returns the SourceLanguageCode field if non-nil, zero value otherwise.

### GetSourceLanguageCodeOk

`func (o *PromptGenerationRequest) GetSourceLanguageCodeOk() (*string, bool)`

GetSourceLanguageCodeOk returns a tuple with the SourceLanguageCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSourceLanguageCode

`func (o *PromptGenerationRequest) SetSourceLanguageCode(v string)`

SetSourceLanguageCode sets SourceLanguageCode field to given value.

### HasSourceLanguageCode

`func (o *PromptGenerationRequest) HasSourceLanguageCode() bool`

HasSourceLanguageCode returns a boolean if a field has been set.

### GetMinWords

`func (o *PromptGenerationRequest) GetMinWords() int32`

GetMinWords returns the MinWords field if non-nil, zero value otherwise.

### GetMinWordsOk

`func (o *PromptGenerationRequest) GetMinWordsOk() (*int32, bool)`

GetMinWordsOk returns a tuple with the MinWords field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMinWords

`func (o *PromptGenerationRequest) SetMinWords(v int32)`

SetMinWords sets MinWords field to given value.

### HasMinWords

`func (o *PromptGenerationRequest) HasMinWords() bool`

HasMinWords returns a boolean if a field has been set.

### GetAllCountries

`func (o *PromptGenerationRequest) GetAllCountries() bool`

GetAllCountries returns the AllCountries field if non-nil, zero value otherwise.

### GetAllCountriesOk

`func (o *PromptGenerationRequest) GetAllCountriesOk() (*bool, bool)`

GetAllCountriesOk returns a tuple with the AllCountries field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAllCountries

`func (o *PromptGenerationRequest) SetAllCountries(v bool)`

SetAllCountries sets AllCountries field to given value.

### HasAllCountries

`func (o *PromptGenerationRequest) HasAllCountries() bool`

HasAllCountries returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


