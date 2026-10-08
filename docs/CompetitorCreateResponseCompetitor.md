# CompetitorCreateResponseCompetitor

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **int32** |  | 
**BrandName** | **string** |  | 
**Domain** | **string** |  | 
**CitationMatchMode** | [**CitationMatchMode**](CitationMatchMode.md) |  | 
**CitationMatchPath** | **NullableString** | Set only when citation_match_mode is path_prefix | 
**Color** | **NullableString** |  | 
**MatchingNames** | **[]string** |  | 

## Methods

### NewCompetitorCreateResponseCompetitor

`func NewCompetitorCreateResponseCompetitor(id int32, brandName string, domain string, citationMatchMode CitationMatchMode, citationMatchPath NullableString, color NullableString, matchingNames []string, ) *CompetitorCreateResponseCompetitor`

NewCompetitorCreateResponseCompetitor instantiates a new CompetitorCreateResponseCompetitor object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCompetitorCreateResponseCompetitorWithDefaults

`func NewCompetitorCreateResponseCompetitorWithDefaults() *CompetitorCreateResponseCompetitor`

NewCompetitorCreateResponseCompetitorWithDefaults instantiates a new CompetitorCreateResponseCompetitor object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *CompetitorCreateResponseCompetitor) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *CompetitorCreateResponseCompetitor) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *CompetitorCreateResponseCompetitor) SetId(v int32)`

SetId sets Id field to given value.


### GetBrandName

`func (o *CompetitorCreateResponseCompetitor) GetBrandName() string`

GetBrandName returns the BrandName field if non-nil, zero value otherwise.

### GetBrandNameOk

`func (o *CompetitorCreateResponseCompetitor) GetBrandNameOk() (*string, bool)`

GetBrandNameOk returns a tuple with the BrandName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBrandName

`func (o *CompetitorCreateResponseCompetitor) SetBrandName(v string)`

SetBrandName sets BrandName field to given value.


### GetDomain

`func (o *CompetitorCreateResponseCompetitor) GetDomain() string`

GetDomain returns the Domain field if non-nil, zero value otherwise.

### GetDomainOk

`func (o *CompetitorCreateResponseCompetitor) GetDomainOk() (*string, bool)`

GetDomainOk returns a tuple with the Domain field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDomain

`func (o *CompetitorCreateResponseCompetitor) SetDomain(v string)`

SetDomain sets Domain field to given value.


### GetCitationMatchMode

`func (o *CompetitorCreateResponseCompetitor) GetCitationMatchMode() CitationMatchMode`

GetCitationMatchMode returns the CitationMatchMode field if non-nil, zero value otherwise.

### GetCitationMatchModeOk

`func (o *CompetitorCreateResponseCompetitor) GetCitationMatchModeOk() (*CitationMatchMode, bool)`

GetCitationMatchModeOk returns a tuple with the CitationMatchMode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCitationMatchMode

`func (o *CompetitorCreateResponseCompetitor) SetCitationMatchMode(v CitationMatchMode)`

SetCitationMatchMode sets CitationMatchMode field to given value.


### GetCitationMatchPath

`func (o *CompetitorCreateResponseCompetitor) GetCitationMatchPath() string`

GetCitationMatchPath returns the CitationMatchPath field if non-nil, zero value otherwise.

### GetCitationMatchPathOk

`func (o *CompetitorCreateResponseCompetitor) GetCitationMatchPathOk() (*string, bool)`

GetCitationMatchPathOk returns a tuple with the CitationMatchPath field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCitationMatchPath

`func (o *CompetitorCreateResponseCompetitor) SetCitationMatchPath(v string)`

SetCitationMatchPath sets CitationMatchPath field to given value.


### SetCitationMatchPathNil

`func (o *CompetitorCreateResponseCompetitor) SetCitationMatchPathNil(b bool)`

 SetCitationMatchPathNil sets the value for CitationMatchPath to be an explicit nil

### UnsetCitationMatchPath
`func (o *CompetitorCreateResponseCompetitor) UnsetCitationMatchPath()`

UnsetCitationMatchPath ensures that no value is present for CitationMatchPath, not even an explicit nil
### GetColor

`func (o *CompetitorCreateResponseCompetitor) GetColor() string`

GetColor returns the Color field if non-nil, zero value otherwise.

### GetColorOk

`func (o *CompetitorCreateResponseCompetitor) GetColorOk() (*string, bool)`

GetColorOk returns a tuple with the Color field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetColor

`func (o *CompetitorCreateResponseCompetitor) SetColor(v string)`

SetColor sets Color field to given value.


### SetColorNil

`func (o *CompetitorCreateResponseCompetitor) SetColorNil(b bool)`

 SetColorNil sets the value for Color to be an explicit nil

### UnsetColor
`func (o *CompetitorCreateResponseCompetitor) UnsetColor()`

UnsetColor ensures that no value is present for Color, not even an explicit nil
### GetMatchingNames

`func (o *CompetitorCreateResponseCompetitor) GetMatchingNames() []string`

GetMatchingNames returns the MatchingNames field if non-nil, zero value otherwise.

### GetMatchingNamesOk

`func (o *CompetitorCreateResponseCompetitor) GetMatchingNamesOk() (*[]string, bool)`

GetMatchingNamesOk returns a tuple with the MatchingNames field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMatchingNames

`func (o *CompetitorCreateResponseCompetitor) SetMatchingNames(v []string)`

SetMatchingNames sets MatchingNames field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


