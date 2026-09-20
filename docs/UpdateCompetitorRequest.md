# UpdateCompetitorRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ProjectId** | **int32** |  | 
**BrandName** | Pointer to **string** |  | [optional] 
**Domain** | Pointer to **string** | Website domain or host used for citation matching. A full URL is accepted and normalised to its host. | [optional] 
**MatchingNames** | Pointer to **[]string** |  | [optional] 
**Color** | Pointer to **string** | Hex color, e.g. #1a2b3c | [optional] 
**CitationMatchMode** | Pointer to **string** |  | [optional] 
**CitationMatchPath** | Pointer to **string** | Required when changing citation_match_mode to path_prefix | [optional] 

## Methods

### NewUpdateCompetitorRequest

`func NewUpdateCompetitorRequest(projectId int32, ) *UpdateCompetitorRequest`

NewUpdateCompetitorRequest instantiates a new UpdateCompetitorRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUpdateCompetitorRequestWithDefaults

`func NewUpdateCompetitorRequestWithDefaults() *UpdateCompetitorRequest`

NewUpdateCompetitorRequestWithDefaults instantiates a new UpdateCompetitorRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProjectId

`func (o *UpdateCompetitorRequest) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *UpdateCompetitorRequest) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *UpdateCompetitorRequest) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.


### GetBrandName

`func (o *UpdateCompetitorRequest) GetBrandName() string`

GetBrandName returns the BrandName field if non-nil, zero value otherwise.

### GetBrandNameOk

`func (o *UpdateCompetitorRequest) GetBrandNameOk() (*string, bool)`

GetBrandNameOk returns a tuple with the BrandName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBrandName

`func (o *UpdateCompetitorRequest) SetBrandName(v string)`

SetBrandName sets BrandName field to given value.

### HasBrandName

`func (o *UpdateCompetitorRequest) HasBrandName() bool`

HasBrandName returns a boolean if a field has been set.

### GetDomain

`func (o *UpdateCompetitorRequest) GetDomain() string`

GetDomain returns the Domain field if non-nil, zero value otherwise.

### GetDomainOk

`func (o *UpdateCompetitorRequest) GetDomainOk() (*string, bool)`

GetDomainOk returns a tuple with the Domain field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDomain

`func (o *UpdateCompetitorRequest) SetDomain(v string)`

SetDomain sets Domain field to given value.

### HasDomain

`func (o *UpdateCompetitorRequest) HasDomain() bool`

HasDomain returns a boolean if a field has been set.

### GetMatchingNames

`func (o *UpdateCompetitorRequest) GetMatchingNames() []string`

GetMatchingNames returns the MatchingNames field if non-nil, zero value otherwise.

### GetMatchingNamesOk

`func (o *UpdateCompetitorRequest) GetMatchingNamesOk() (*[]string, bool)`

GetMatchingNamesOk returns a tuple with the MatchingNames field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMatchingNames

`func (o *UpdateCompetitorRequest) SetMatchingNames(v []string)`

SetMatchingNames sets MatchingNames field to given value.

### HasMatchingNames

`func (o *UpdateCompetitorRequest) HasMatchingNames() bool`

HasMatchingNames returns a boolean if a field has been set.

### GetColor

`func (o *UpdateCompetitorRequest) GetColor() string`

GetColor returns the Color field if non-nil, zero value otherwise.

### GetColorOk

`func (o *UpdateCompetitorRequest) GetColorOk() (*string, bool)`

GetColorOk returns a tuple with the Color field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetColor

`func (o *UpdateCompetitorRequest) SetColor(v string)`

SetColor sets Color field to given value.

### HasColor

`func (o *UpdateCompetitorRequest) HasColor() bool`

HasColor returns a boolean if a field has been set.

### GetCitationMatchMode

`func (o *UpdateCompetitorRequest) GetCitationMatchMode() string`

GetCitationMatchMode returns the CitationMatchMode field if non-nil, zero value otherwise.

### GetCitationMatchModeOk

`func (o *UpdateCompetitorRequest) GetCitationMatchModeOk() (*string, bool)`

GetCitationMatchModeOk returns a tuple with the CitationMatchMode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCitationMatchMode

`func (o *UpdateCompetitorRequest) SetCitationMatchMode(v string)`

SetCitationMatchMode sets CitationMatchMode field to given value.

### HasCitationMatchMode

`func (o *UpdateCompetitorRequest) HasCitationMatchMode() bool`

HasCitationMatchMode returns a boolean if a field has been set.

### GetCitationMatchPath

`func (o *UpdateCompetitorRequest) GetCitationMatchPath() string`

GetCitationMatchPath returns the CitationMatchPath field if non-nil, zero value otherwise.

### GetCitationMatchPathOk

`func (o *UpdateCompetitorRequest) GetCitationMatchPathOk() (*string, bool)`

GetCitationMatchPathOk returns a tuple with the CitationMatchPath field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCitationMatchPath

`func (o *UpdateCompetitorRequest) SetCitationMatchPath(v string)`

SetCitationMatchPath sets CitationMatchPath field to given value.

### HasCitationMatchPath

`func (o *UpdateCompetitorRequest) HasCitationMatchPath() bool`

HasCitationMatchPath returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


