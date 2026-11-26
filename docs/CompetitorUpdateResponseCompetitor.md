# CompetitorUpdateResponseCompetitor

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
**Processing** | **bool** | True while historical mention and citation matching is recalculated in the background | 

## Methods

### NewCompetitorUpdateResponseCompetitor

`func NewCompetitorUpdateResponseCompetitor(id int32, brandName string, domain string, citationMatchMode CitationMatchMode, citationMatchPath NullableString, color NullableString, matchingNames []string, processing bool, ) *CompetitorUpdateResponseCompetitor`

NewCompetitorUpdateResponseCompetitor instantiates a new CompetitorUpdateResponseCompetitor object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCompetitorUpdateResponseCompetitorWithDefaults

`func NewCompetitorUpdateResponseCompetitorWithDefaults() *CompetitorUpdateResponseCompetitor`

NewCompetitorUpdateResponseCompetitorWithDefaults instantiates a new CompetitorUpdateResponseCompetitor object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *CompetitorUpdateResponseCompetitor) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *CompetitorUpdateResponseCompetitor) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *CompetitorUpdateResponseCompetitor) SetId(v int32)`

SetId sets Id field to given value.


### GetBrandName

`func (o *CompetitorUpdateResponseCompetitor) GetBrandName() string`

GetBrandName returns the BrandName field if non-nil, zero value otherwise.

### GetBrandNameOk

`func (o *CompetitorUpdateResponseCompetitor) GetBrandNameOk() (*string, bool)`

GetBrandNameOk returns a tuple with the BrandName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBrandName

`func (o *CompetitorUpdateResponseCompetitor) SetBrandName(v string)`

SetBrandName sets BrandName field to given value.


### GetDomain

`func (o *CompetitorUpdateResponseCompetitor) GetDomain() string`

GetDomain returns the Domain field if non-nil, zero value otherwise.

### GetDomainOk

`func (o *CompetitorUpdateResponseCompetitor) GetDomainOk() (*string, bool)`

GetDomainOk returns a tuple with the Domain field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDomain

`func (o *CompetitorUpdateResponseCompetitor) SetDomain(v string)`

SetDomain sets Domain field to given value.


### GetCitationMatchMode

`func (o *CompetitorUpdateResponseCompetitor) GetCitationMatchMode() CitationMatchMode`

GetCitationMatchMode returns the CitationMatchMode field if non-nil, zero value otherwise.

### GetCitationMatchModeOk

`func (o *CompetitorUpdateResponseCompetitor) GetCitationMatchModeOk() (*CitationMatchMode, bool)`

GetCitationMatchModeOk returns a tuple with the CitationMatchMode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCitationMatchMode

`func (o *CompetitorUpdateResponseCompetitor) SetCitationMatchMode(v CitationMatchMode)`

SetCitationMatchMode sets CitationMatchMode field to given value.


### GetCitationMatchPath

`func (o *CompetitorUpdateResponseCompetitor) GetCitationMatchPath() string`

GetCitationMatchPath returns the CitationMatchPath field if non-nil, zero value otherwise.

### GetCitationMatchPathOk

`func (o *CompetitorUpdateResponseCompetitor) GetCitationMatchPathOk() (*string, bool)`

GetCitationMatchPathOk returns a tuple with the CitationMatchPath field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCitationMatchPath

`func (o *CompetitorUpdateResponseCompetitor) SetCitationMatchPath(v string)`

SetCitationMatchPath sets CitationMatchPath field to given value.


### SetCitationMatchPathNil

`func (o *CompetitorUpdateResponseCompetitor) SetCitationMatchPathNil(b bool)`

 SetCitationMatchPathNil sets the value for CitationMatchPath to be an explicit nil

### UnsetCitationMatchPath
`func (o *CompetitorUpdateResponseCompetitor) UnsetCitationMatchPath()`

UnsetCitationMatchPath ensures that no value is present for CitationMatchPath, not even an explicit nil
### GetColor

`func (o *CompetitorUpdateResponseCompetitor) GetColor() string`

GetColor returns the Color field if non-nil, zero value otherwise.

### GetColorOk

`func (o *CompetitorUpdateResponseCompetitor) GetColorOk() (*string, bool)`

GetColorOk returns a tuple with the Color field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetColor

`func (o *CompetitorUpdateResponseCompetitor) SetColor(v string)`

SetColor sets Color field to given value.


### SetColorNil

`func (o *CompetitorUpdateResponseCompetitor) SetColorNil(b bool)`

 SetColorNil sets the value for Color to be an explicit nil

### UnsetColor
`func (o *CompetitorUpdateResponseCompetitor) UnsetColor()`

UnsetColor ensures that no value is present for Color, not even an explicit nil
### GetMatchingNames

`func (o *CompetitorUpdateResponseCompetitor) GetMatchingNames() []string`

GetMatchingNames returns the MatchingNames field if non-nil, zero value otherwise.

### GetMatchingNamesOk

`func (o *CompetitorUpdateResponseCompetitor) GetMatchingNamesOk() (*[]string, bool)`

GetMatchingNamesOk returns a tuple with the MatchingNames field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMatchingNames

`func (o *CompetitorUpdateResponseCompetitor) SetMatchingNames(v []string)`

SetMatchingNames sets MatchingNames field to given value.


### GetProcessing

`func (o *CompetitorUpdateResponseCompetitor) GetProcessing() bool`

GetProcessing returns the Processing field if non-nil, zero value otherwise.

### GetProcessingOk

`func (o *CompetitorUpdateResponseCompetitor) GetProcessingOk() (*bool, bool)`

GetProcessingOk returns a tuple with the Processing field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProcessing

`func (o *CompetitorUpdateResponseCompetitor) SetProcessing(v bool)`

SetProcessing sets Processing field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


