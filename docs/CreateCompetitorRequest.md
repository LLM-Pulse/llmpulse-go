# CreateCompetitorRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ProjectId** | **int32** |  | 
**BrandName** | **string** |  | 
**Domain** | **string** | URL is accepted and normalised to host (e.g. https://www.openai.com → openai.com) | 
**MatchingNames** | Pointer to **[]string** |  | [optional] 
**CitationMatchMode** | Pointer to **string** | domain includes the registrable domain and all subdomains; host requires the exact hostname; path_prefix also requires citation_match_path | [optional] [default to "domain"]
**CitationMatchPath** | Pointer to **string** | Required when citation_match_mode&#x3D;path_prefix, e.g. /es. Case-sensitive; trailing slash is optional; query and fragment are ignored | [optional] 

## Methods

### NewCreateCompetitorRequest

`func NewCreateCompetitorRequest(projectId int32, brandName string, domain string, ) *CreateCompetitorRequest`

NewCreateCompetitorRequest instantiates a new CreateCompetitorRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateCompetitorRequestWithDefaults

`func NewCreateCompetitorRequestWithDefaults() *CreateCompetitorRequest`

NewCreateCompetitorRequestWithDefaults instantiates a new CreateCompetitorRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProjectId

`func (o *CreateCompetitorRequest) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *CreateCompetitorRequest) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *CreateCompetitorRequest) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.


### GetBrandName

`func (o *CreateCompetitorRequest) GetBrandName() string`

GetBrandName returns the BrandName field if non-nil, zero value otherwise.

### GetBrandNameOk

`func (o *CreateCompetitorRequest) GetBrandNameOk() (*string, bool)`

GetBrandNameOk returns a tuple with the BrandName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBrandName

`func (o *CreateCompetitorRequest) SetBrandName(v string)`

SetBrandName sets BrandName field to given value.


### GetDomain

`func (o *CreateCompetitorRequest) GetDomain() string`

GetDomain returns the Domain field if non-nil, zero value otherwise.

### GetDomainOk

`func (o *CreateCompetitorRequest) GetDomainOk() (*string, bool)`

GetDomainOk returns a tuple with the Domain field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDomain

`func (o *CreateCompetitorRequest) SetDomain(v string)`

SetDomain sets Domain field to given value.


### GetMatchingNames

`func (o *CreateCompetitorRequest) GetMatchingNames() []string`

GetMatchingNames returns the MatchingNames field if non-nil, zero value otherwise.

### GetMatchingNamesOk

`func (o *CreateCompetitorRequest) GetMatchingNamesOk() (*[]string, bool)`

GetMatchingNamesOk returns a tuple with the MatchingNames field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMatchingNames

`func (o *CreateCompetitorRequest) SetMatchingNames(v []string)`

SetMatchingNames sets MatchingNames field to given value.

### HasMatchingNames

`func (o *CreateCompetitorRequest) HasMatchingNames() bool`

HasMatchingNames returns a boolean if a field has been set.

### GetCitationMatchMode

`func (o *CreateCompetitorRequest) GetCitationMatchMode() string`

GetCitationMatchMode returns the CitationMatchMode field if non-nil, zero value otherwise.

### GetCitationMatchModeOk

`func (o *CreateCompetitorRequest) GetCitationMatchModeOk() (*string, bool)`

GetCitationMatchModeOk returns a tuple with the CitationMatchMode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCitationMatchMode

`func (o *CreateCompetitorRequest) SetCitationMatchMode(v string)`

SetCitationMatchMode sets CitationMatchMode field to given value.

### HasCitationMatchMode

`func (o *CreateCompetitorRequest) HasCitationMatchMode() bool`

HasCitationMatchMode returns a boolean if a field has been set.

### GetCitationMatchPath

`func (o *CreateCompetitorRequest) GetCitationMatchPath() string`

GetCitationMatchPath returns the CitationMatchPath field if non-nil, zero value otherwise.

### GetCitationMatchPathOk

`func (o *CreateCompetitorRequest) GetCitationMatchPathOk() (*string, bool)`

GetCitationMatchPathOk returns a tuple with the CitationMatchPath field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCitationMatchPath

`func (o *CreateCompetitorRequest) SetCitationMatchPath(v string)`

SetCitationMatchPath sets CitationMatchPath field to given value.

### HasCitationMatchPath

`func (o *CreateCompetitorRequest) HasCitationMatchPath() bool`

HasCitationMatchPath returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


