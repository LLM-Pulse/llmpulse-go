# ProjectCreateRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**WebsiteUrl** | **string** | Public HTTP(S) URL with a DNS hostname or public IP address. Credentials, private and special IP addresses, localhost and internal hostnames are rejected. | 
**Name** | **string** |  | 
**MainCountry** | **string** |  | 
**MainLanguage** | **string** |  | 
**BrandName** | Pointer to **string** |  | [optional] 
**Description** | Pointer to **string** |  | [optional] 
**Industry** | Pointer to **[]string** |  | [optional] 
**MatchingNames** | Pointer to **[]string** |  | [optional] 
**Prompts** | Pointer to **[]string** |  | [optional] 
**Competitors** | Pointer to [**[]ProjectCreateRequestCompetitorsInner**](ProjectCreateRequestCompetitorsInner.md) |  | [optional] 
**OwnedMedia** | Pointer to [**ProjectCreateRequestOwnedMedia**](ProjectCreateRequestOwnedMedia.md) |  | [optional] 
**UseSubdomain** | Pointer to **bool** |  | [optional] [default to false]
**WeeklyEmailSubscribed** | Pointer to **bool** |  | [optional] [default to false]
**ExternalIdentifier** | Pointer to **string** | Embed-enabled (Enterprise) accounts only; other accounts receive ERR_PLAN_REQUIRED. Idempotency key and embed-session join key, unique per account | [optional] 
**ExecutePromptsImmediately** | Pointer to **bool** |  | [optional] [default to true]

## Methods

### NewProjectCreateRequest

`func NewProjectCreateRequest(websiteUrl string, name string, mainCountry string, mainLanguage string, ) *ProjectCreateRequest`

NewProjectCreateRequest instantiates a new ProjectCreateRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProjectCreateRequestWithDefaults

`func NewProjectCreateRequestWithDefaults() *ProjectCreateRequest`

NewProjectCreateRequestWithDefaults instantiates a new ProjectCreateRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetWebsiteUrl

`func (o *ProjectCreateRequest) GetWebsiteUrl() string`

GetWebsiteUrl returns the WebsiteUrl field if non-nil, zero value otherwise.

### GetWebsiteUrlOk

`func (o *ProjectCreateRequest) GetWebsiteUrlOk() (*string, bool)`

GetWebsiteUrlOk returns a tuple with the WebsiteUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWebsiteUrl

`func (o *ProjectCreateRequest) SetWebsiteUrl(v string)`

SetWebsiteUrl sets WebsiteUrl field to given value.


### GetName

`func (o *ProjectCreateRequest) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ProjectCreateRequest) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ProjectCreateRequest) SetName(v string)`

SetName sets Name field to given value.


### GetMainCountry

`func (o *ProjectCreateRequest) GetMainCountry() string`

GetMainCountry returns the MainCountry field if non-nil, zero value otherwise.

### GetMainCountryOk

`func (o *ProjectCreateRequest) GetMainCountryOk() (*string, bool)`

GetMainCountryOk returns a tuple with the MainCountry field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMainCountry

`func (o *ProjectCreateRequest) SetMainCountry(v string)`

SetMainCountry sets MainCountry field to given value.


### GetMainLanguage

`func (o *ProjectCreateRequest) GetMainLanguage() string`

GetMainLanguage returns the MainLanguage field if non-nil, zero value otherwise.

### GetMainLanguageOk

`func (o *ProjectCreateRequest) GetMainLanguageOk() (*string, bool)`

GetMainLanguageOk returns a tuple with the MainLanguage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMainLanguage

`func (o *ProjectCreateRequest) SetMainLanguage(v string)`

SetMainLanguage sets MainLanguage field to given value.


### GetBrandName

`func (o *ProjectCreateRequest) GetBrandName() string`

GetBrandName returns the BrandName field if non-nil, zero value otherwise.

### GetBrandNameOk

`func (o *ProjectCreateRequest) GetBrandNameOk() (*string, bool)`

GetBrandNameOk returns a tuple with the BrandName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBrandName

`func (o *ProjectCreateRequest) SetBrandName(v string)`

SetBrandName sets BrandName field to given value.

### HasBrandName

`func (o *ProjectCreateRequest) HasBrandName() bool`

HasBrandName returns a boolean if a field has been set.

### GetDescription

`func (o *ProjectCreateRequest) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *ProjectCreateRequest) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *ProjectCreateRequest) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *ProjectCreateRequest) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetIndustry

`func (o *ProjectCreateRequest) GetIndustry() []string`

GetIndustry returns the Industry field if non-nil, zero value otherwise.

### GetIndustryOk

`func (o *ProjectCreateRequest) GetIndustryOk() (*[]string, bool)`

GetIndustryOk returns a tuple with the Industry field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIndustry

`func (o *ProjectCreateRequest) SetIndustry(v []string)`

SetIndustry sets Industry field to given value.

### HasIndustry

`func (o *ProjectCreateRequest) HasIndustry() bool`

HasIndustry returns a boolean if a field has been set.

### GetMatchingNames

`func (o *ProjectCreateRequest) GetMatchingNames() []string`

GetMatchingNames returns the MatchingNames field if non-nil, zero value otherwise.

### GetMatchingNamesOk

`func (o *ProjectCreateRequest) GetMatchingNamesOk() (*[]string, bool)`

GetMatchingNamesOk returns a tuple with the MatchingNames field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMatchingNames

`func (o *ProjectCreateRequest) SetMatchingNames(v []string)`

SetMatchingNames sets MatchingNames field to given value.

### HasMatchingNames

`func (o *ProjectCreateRequest) HasMatchingNames() bool`

HasMatchingNames returns a boolean if a field has been set.

### GetPrompts

`func (o *ProjectCreateRequest) GetPrompts() []string`

GetPrompts returns the Prompts field if non-nil, zero value otherwise.

### GetPromptsOk

`func (o *ProjectCreateRequest) GetPromptsOk() (*[]string, bool)`

GetPromptsOk returns a tuple with the Prompts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrompts

`func (o *ProjectCreateRequest) SetPrompts(v []string)`

SetPrompts sets Prompts field to given value.

### HasPrompts

`func (o *ProjectCreateRequest) HasPrompts() bool`

HasPrompts returns a boolean if a field has been set.

### GetCompetitors

`func (o *ProjectCreateRequest) GetCompetitors() []ProjectCreateRequestCompetitorsInner`

GetCompetitors returns the Competitors field if non-nil, zero value otherwise.

### GetCompetitorsOk

`func (o *ProjectCreateRequest) GetCompetitorsOk() (*[]ProjectCreateRequestCompetitorsInner, bool)`

GetCompetitorsOk returns a tuple with the Competitors field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompetitors

`func (o *ProjectCreateRequest) SetCompetitors(v []ProjectCreateRequestCompetitorsInner)`

SetCompetitors sets Competitors field to given value.

### HasCompetitors

`func (o *ProjectCreateRequest) HasCompetitors() bool`

HasCompetitors returns a boolean if a field has been set.

### GetOwnedMedia

`func (o *ProjectCreateRequest) GetOwnedMedia() ProjectCreateRequestOwnedMedia`

GetOwnedMedia returns the OwnedMedia field if non-nil, zero value otherwise.

### GetOwnedMediaOk

`func (o *ProjectCreateRequest) GetOwnedMediaOk() (*ProjectCreateRequestOwnedMedia, bool)`

GetOwnedMediaOk returns a tuple with the OwnedMedia field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOwnedMedia

`func (o *ProjectCreateRequest) SetOwnedMedia(v ProjectCreateRequestOwnedMedia)`

SetOwnedMedia sets OwnedMedia field to given value.

### HasOwnedMedia

`func (o *ProjectCreateRequest) HasOwnedMedia() bool`

HasOwnedMedia returns a boolean if a field has been set.

### GetUseSubdomain

`func (o *ProjectCreateRequest) GetUseSubdomain() bool`

GetUseSubdomain returns the UseSubdomain field if non-nil, zero value otherwise.

### GetUseSubdomainOk

`func (o *ProjectCreateRequest) GetUseSubdomainOk() (*bool, bool)`

GetUseSubdomainOk returns a tuple with the UseSubdomain field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUseSubdomain

`func (o *ProjectCreateRequest) SetUseSubdomain(v bool)`

SetUseSubdomain sets UseSubdomain field to given value.

### HasUseSubdomain

`func (o *ProjectCreateRequest) HasUseSubdomain() bool`

HasUseSubdomain returns a boolean if a field has been set.

### GetWeeklyEmailSubscribed

`func (o *ProjectCreateRequest) GetWeeklyEmailSubscribed() bool`

GetWeeklyEmailSubscribed returns the WeeklyEmailSubscribed field if non-nil, zero value otherwise.

### GetWeeklyEmailSubscribedOk

`func (o *ProjectCreateRequest) GetWeeklyEmailSubscribedOk() (*bool, bool)`

GetWeeklyEmailSubscribedOk returns a tuple with the WeeklyEmailSubscribed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWeeklyEmailSubscribed

`func (o *ProjectCreateRequest) SetWeeklyEmailSubscribed(v bool)`

SetWeeklyEmailSubscribed sets WeeklyEmailSubscribed field to given value.

### HasWeeklyEmailSubscribed

`func (o *ProjectCreateRequest) HasWeeklyEmailSubscribed() bool`

HasWeeklyEmailSubscribed returns a boolean if a field has been set.

### GetExternalIdentifier

`func (o *ProjectCreateRequest) GetExternalIdentifier() string`

GetExternalIdentifier returns the ExternalIdentifier field if non-nil, zero value otherwise.

### GetExternalIdentifierOk

`func (o *ProjectCreateRequest) GetExternalIdentifierOk() (*string, bool)`

GetExternalIdentifierOk returns a tuple with the ExternalIdentifier field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExternalIdentifier

`func (o *ProjectCreateRequest) SetExternalIdentifier(v string)`

SetExternalIdentifier sets ExternalIdentifier field to given value.

### HasExternalIdentifier

`func (o *ProjectCreateRequest) HasExternalIdentifier() bool`

HasExternalIdentifier returns a boolean if a field has been set.

### GetExecutePromptsImmediately

`func (o *ProjectCreateRequest) GetExecutePromptsImmediately() bool`

GetExecutePromptsImmediately returns the ExecutePromptsImmediately field if non-nil, zero value otherwise.

### GetExecutePromptsImmediatelyOk

`func (o *ProjectCreateRequest) GetExecutePromptsImmediatelyOk() (*bool, bool)`

GetExecutePromptsImmediatelyOk returns a tuple with the ExecutePromptsImmediately field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExecutePromptsImmediately

`func (o *ProjectCreateRequest) SetExecutePromptsImmediately(v bool)`

SetExecutePromptsImmediately sets ExecutePromptsImmediately field to given value.

### HasExecutePromptsImmediately

`func (o *ProjectCreateRequest) HasExecutePromptsImmediately() bool`

HasExecutePromptsImmediately returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


