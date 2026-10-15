# CompetitorSuggestion

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** | The suggestion key (brands) or the id of one citing source row (citations) | 
**Domain** | **string** |  | 
**BrandName** | Pointer to **NullableString** | The proposed brand name; null for a cited domain | [optional] 
**MatchingNames** | **[]string** | The names a tracked competitor would be matched by; empty for a cited domain | 
**Mentions** | Pointer to **NullableInt32** | Answers naming the brand, when the discovery counted them (brands only) | [optional] 
**Citations** | Pointer to **NullableInt32** | Answers citing the domain (citations only) | [optional] 

## Methods

### NewCompetitorSuggestion

`func NewCompetitorSuggestion(id string, domain string, matchingNames []string, ) *CompetitorSuggestion`

NewCompetitorSuggestion instantiates a new CompetitorSuggestion object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCompetitorSuggestionWithDefaults

`func NewCompetitorSuggestionWithDefaults() *CompetitorSuggestion`

NewCompetitorSuggestionWithDefaults instantiates a new CompetitorSuggestion object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *CompetitorSuggestion) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *CompetitorSuggestion) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *CompetitorSuggestion) SetId(v string)`

SetId sets Id field to given value.


### GetDomain

`func (o *CompetitorSuggestion) GetDomain() string`

GetDomain returns the Domain field if non-nil, zero value otherwise.

### GetDomainOk

`func (o *CompetitorSuggestion) GetDomainOk() (*string, bool)`

GetDomainOk returns a tuple with the Domain field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDomain

`func (o *CompetitorSuggestion) SetDomain(v string)`

SetDomain sets Domain field to given value.


### GetBrandName

`func (o *CompetitorSuggestion) GetBrandName() string`

GetBrandName returns the BrandName field if non-nil, zero value otherwise.

### GetBrandNameOk

`func (o *CompetitorSuggestion) GetBrandNameOk() (*string, bool)`

GetBrandNameOk returns a tuple with the BrandName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBrandName

`func (o *CompetitorSuggestion) SetBrandName(v string)`

SetBrandName sets BrandName field to given value.

### HasBrandName

`func (o *CompetitorSuggestion) HasBrandName() bool`

HasBrandName returns a boolean if a field has been set.

### SetBrandNameNil

`func (o *CompetitorSuggestion) SetBrandNameNil(b bool)`

 SetBrandNameNil sets the value for BrandName to be an explicit nil

### UnsetBrandName
`func (o *CompetitorSuggestion) UnsetBrandName()`

UnsetBrandName ensures that no value is present for BrandName, not even an explicit nil
### GetMatchingNames

`func (o *CompetitorSuggestion) GetMatchingNames() []string`

GetMatchingNames returns the MatchingNames field if non-nil, zero value otherwise.

### GetMatchingNamesOk

`func (o *CompetitorSuggestion) GetMatchingNamesOk() (*[]string, bool)`

GetMatchingNamesOk returns a tuple with the MatchingNames field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMatchingNames

`func (o *CompetitorSuggestion) SetMatchingNames(v []string)`

SetMatchingNames sets MatchingNames field to given value.


### GetMentions

`func (o *CompetitorSuggestion) GetMentions() int32`

GetMentions returns the Mentions field if non-nil, zero value otherwise.

### GetMentionsOk

`func (o *CompetitorSuggestion) GetMentionsOk() (*int32, bool)`

GetMentionsOk returns a tuple with the Mentions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMentions

`func (o *CompetitorSuggestion) SetMentions(v int32)`

SetMentions sets Mentions field to given value.

### HasMentions

`func (o *CompetitorSuggestion) HasMentions() bool`

HasMentions returns a boolean if a field has been set.

### SetMentionsNil

`func (o *CompetitorSuggestion) SetMentionsNil(b bool)`

 SetMentionsNil sets the value for Mentions to be an explicit nil

### UnsetMentions
`func (o *CompetitorSuggestion) UnsetMentions()`

UnsetMentions ensures that no value is present for Mentions, not even an explicit nil
### GetCitations

`func (o *CompetitorSuggestion) GetCitations() int32`

GetCitations returns the Citations field if non-nil, zero value otherwise.

### GetCitationsOk

`func (o *CompetitorSuggestion) GetCitationsOk() (*int32, bool)`

GetCitationsOk returns a tuple with the Citations field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCitations

`func (o *CompetitorSuggestion) SetCitations(v int32)`

SetCitations sets Citations field to given value.

### HasCitations

`func (o *CompetitorSuggestion) HasCitations() bool`

HasCitations returns a boolean if a field has been set.

### SetCitationsNil

`func (o *CompetitorSuggestion) SetCitationsNil(b bool)`

 SetCitationsNil sets the value for Citations to be an explicit nil

### UnsetCitations
`func (o *CompetitorSuggestion) UnsetCitations()`

UnsetCitations ensures that no value is present for Citations, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


