# PromptGenerationResponseParams

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CountryCode** | Pointer to **string** |  | [optional] 
**LanguageCode** | Pointer to **string** |  | [optional] 
**Query** | Pointer to **string** |  | [optional] 
**Count** | Pointer to **int32** |  | [optional] 
**CompetitorId** | Pointer to **int32** |  | [optional] 
**SearchType** | Pointer to **string** |  | [optional] 
**Keywords** | Pointer to **[]string** |  | [optional] 
**SourceCountryCode** | Pointer to **string** |  | [optional] 
**SourceLanguageCode** | Pointer to **string** |  | [optional] 
**MinWords** | Pointer to **int32** |  | [optional] 
**AllCountries** | Pointer to **bool** |  | [optional] 
**Property** | Pointer to **string** |  | [optional] 

## Methods

### NewPromptGenerationResponseParams

`func NewPromptGenerationResponseParams() *PromptGenerationResponseParams`

NewPromptGenerationResponseParams instantiates a new PromptGenerationResponseParams object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPromptGenerationResponseParamsWithDefaults

`func NewPromptGenerationResponseParamsWithDefaults() *PromptGenerationResponseParams`

NewPromptGenerationResponseParamsWithDefaults instantiates a new PromptGenerationResponseParams object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCountryCode

`func (o *PromptGenerationResponseParams) GetCountryCode() string`

GetCountryCode returns the CountryCode field if non-nil, zero value otherwise.

### GetCountryCodeOk

`func (o *PromptGenerationResponseParams) GetCountryCodeOk() (*string, bool)`

GetCountryCodeOk returns a tuple with the CountryCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountryCode

`func (o *PromptGenerationResponseParams) SetCountryCode(v string)`

SetCountryCode sets CountryCode field to given value.

### HasCountryCode

`func (o *PromptGenerationResponseParams) HasCountryCode() bool`

HasCountryCode returns a boolean if a field has been set.

### GetLanguageCode

`func (o *PromptGenerationResponseParams) GetLanguageCode() string`

GetLanguageCode returns the LanguageCode field if non-nil, zero value otherwise.

### GetLanguageCodeOk

`func (o *PromptGenerationResponseParams) GetLanguageCodeOk() (*string, bool)`

GetLanguageCodeOk returns a tuple with the LanguageCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLanguageCode

`func (o *PromptGenerationResponseParams) SetLanguageCode(v string)`

SetLanguageCode sets LanguageCode field to given value.

### HasLanguageCode

`func (o *PromptGenerationResponseParams) HasLanguageCode() bool`

HasLanguageCode returns a boolean if a field has been set.

### GetQuery

`func (o *PromptGenerationResponseParams) GetQuery() string`

GetQuery returns the Query field if non-nil, zero value otherwise.

### GetQueryOk

`func (o *PromptGenerationResponseParams) GetQueryOk() (*string, bool)`

GetQueryOk returns a tuple with the Query field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuery

`func (o *PromptGenerationResponseParams) SetQuery(v string)`

SetQuery sets Query field to given value.

### HasQuery

`func (o *PromptGenerationResponseParams) HasQuery() bool`

HasQuery returns a boolean if a field has been set.

### GetCount

`func (o *PromptGenerationResponseParams) GetCount() int32`

GetCount returns the Count field if non-nil, zero value otherwise.

### GetCountOk

`func (o *PromptGenerationResponseParams) GetCountOk() (*int32, bool)`

GetCountOk returns a tuple with the Count field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCount

`func (o *PromptGenerationResponseParams) SetCount(v int32)`

SetCount sets Count field to given value.

### HasCount

`func (o *PromptGenerationResponseParams) HasCount() bool`

HasCount returns a boolean if a field has been set.

### GetCompetitorId

`func (o *PromptGenerationResponseParams) GetCompetitorId() int32`

GetCompetitorId returns the CompetitorId field if non-nil, zero value otherwise.

### GetCompetitorIdOk

`func (o *PromptGenerationResponseParams) GetCompetitorIdOk() (*int32, bool)`

GetCompetitorIdOk returns a tuple with the CompetitorId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompetitorId

`func (o *PromptGenerationResponseParams) SetCompetitorId(v int32)`

SetCompetitorId sets CompetitorId field to given value.

### HasCompetitorId

`func (o *PromptGenerationResponseParams) HasCompetitorId() bool`

HasCompetitorId returns a boolean if a field has been set.

### GetSearchType

`func (o *PromptGenerationResponseParams) GetSearchType() string`

GetSearchType returns the SearchType field if non-nil, zero value otherwise.

### GetSearchTypeOk

`func (o *PromptGenerationResponseParams) GetSearchTypeOk() (*string, bool)`

GetSearchTypeOk returns a tuple with the SearchType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSearchType

`func (o *PromptGenerationResponseParams) SetSearchType(v string)`

SetSearchType sets SearchType field to given value.

### HasSearchType

`func (o *PromptGenerationResponseParams) HasSearchType() bool`

HasSearchType returns a boolean if a field has been set.

### GetKeywords

`func (o *PromptGenerationResponseParams) GetKeywords() []string`

GetKeywords returns the Keywords field if non-nil, zero value otherwise.

### GetKeywordsOk

`func (o *PromptGenerationResponseParams) GetKeywordsOk() (*[]string, bool)`

GetKeywordsOk returns a tuple with the Keywords field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKeywords

`func (o *PromptGenerationResponseParams) SetKeywords(v []string)`

SetKeywords sets Keywords field to given value.

### HasKeywords

`func (o *PromptGenerationResponseParams) HasKeywords() bool`

HasKeywords returns a boolean if a field has been set.

### GetSourceCountryCode

`func (o *PromptGenerationResponseParams) GetSourceCountryCode() string`

GetSourceCountryCode returns the SourceCountryCode field if non-nil, zero value otherwise.

### GetSourceCountryCodeOk

`func (o *PromptGenerationResponseParams) GetSourceCountryCodeOk() (*string, bool)`

GetSourceCountryCodeOk returns a tuple with the SourceCountryCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSourceCountryCode

`func (o *PromptGenerationResponseParams) SetSourceCountryCode(v string)`

SetSourceCountryCode sets SourceCountryCode field to given value.

### HasSourceCountryCode

`func (o *PromptGenerationResponseParams) HasSourceCountryCode() bool`

HasSourceCountryCode returns a boolean if a field has been set.

### GetSourceLanguageCode

`func (o *PromptGenerationResponseParams) GetSourceLanguageCode() string`

GetSourceLanguageCode returns the SourceLanguageCode field if non-nil, zero value otherwise.

### GetSourceLanguageCodeOk

`func (o *PromptGenerationResponseParams) GetSourceLanguageCodeOk() (*string, bool)`

GetSourceLanguageCodeOk returns a tuple with the SourceLanguageCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSourceLanguageCode

`func (o *PromptGenerationResponseParams) SetSourceLanguageCode(v string)`

SetSourceLanguageCode sets SourceLanguageCode field to given value.

### HasSourceLanguageCode

`func (o *PromptGenerationResponseParams) HasSourceLanguageCode() bool`

HasSourceLanguageCode returns a boolean if a field has been set.

### GetMinWords

`func (o *PromptGenerationResponseParams) GetMinWords() int32`

GetMinWords returns the MinWords field if non-nil, zero value otherwise.

### GetMinWordsOk

`func (o *PromptGenerationResponseParams) GetMinWordsOk() (*int32, bool)`

GetMinWordsOk returns a tuple with the MinWords field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMinWords

`func (o *PromptGenerationResponseParams) SetMinWords(v int32)`

SetMinWords sets MinWords field to given value.

### HasMinWords

`func (o *PromptGenerationResponseParams) HasMinWords() bool`

HasMinWords returns a boolean if a field has been set.

### GetAllCountries

`func (o *PromptGenerationResponseParams) GetAllCountries() bool`

GetAllCountries returns the AllCountries field if non-nil, zero value otherwise.

### GetAllCountriesOk

`func (o *PromptGenerationResponseParams) GetAllCountriesOk() (*bool, bool)`

GetAllCountriesOk returns a tuple with the AllCountries field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAllCountries

`func (o *PromptGenerationResponseParams) SetAllCountries(v bool)`

SetAllCountries sets AllCountries field to given value.

### HasAllCountries

`func (o *PromptGenerationResponseParams) HasAllCountries() bool`

HasAllCountries returns a boolean if a field has been set.

### GetProperty

`func (o *PromptGenerationResponseParams) GetProperty() string`

GetProperty returns the Property field if non-nil, zero value otherwise.

### GetPropertyOk

`func (o *PromptGenerationResponseParams) GetPropertyOk() (*string, bool)`

GetPropertyOk returns a tuple with the Property field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProperty

`func (o *PromptGenerationResponseParams) SetProperty(v string)`

SetProperty sets Property field to given value.

### HasProperty

`func (o *PromptGenerationResponseParams) HasProperty() bool`

HasProperty returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


