# UpdateProjectDraftRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Step** | **string** |  | 
**Name** | Pointer to **string** |  | [optional] 
**BrandName** | Pointer to **string** |  | [optional] 
**Description** | Pointer to **string** |  | [optional] 
**Industry** | Pointer to **[]string** |  | [optional] 
**MatchingNames** | Pointer to **[]string** |  | [optional] 
**ExternalIdentifier** | Pointer to **string** |  | [optional] 
**Prompts** | Pointer to **[]string** |  | [optional] 
**Competitors** | Pointer to **[]map[string]interface{}** |  | [optional] 
**YoutubeChannelUrl** | Pointer to **string** |  | [optional] 
**InstagramProfileUrl** | Pointer to **string** |  | [optional] 
**FacebookPageUrl** | Pointer to **string** |  | [optional] 
**TiktokProfileUrl** | Pointer to **string** |  | [optional] 
**AppStoreUrl** | Pointer to **string** |  | [optional] 
**GooglePlayUrl** | Pointer to **string** |  | [optional] 
**Suggest** | Pointer to **bool** |  | [optional] [default to true]

## Methods

### NewUpdateProjectDraftRequest

`func NewUpdateProjectDraftRequest(step string, ) *UpdateProjectDraftRequest`

NewUpdateProjectDraftRequest instantiates a new UpdateProjectDraftRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUpdateProjectDraftRequestWithDefaults

`func NewUpdateProjectDraftRequestWithDefaults() *UpdateProjectDraftRequest`

NewUpdateProjectDraftRequestWithDefaults instantiates a new UpdateProjectDraftRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetStep

`func (o *UpdateProjectDraftRequest) GetStep() string`

GetStep returns the Step field if non-nil, zero value otherwise.

### GetStepOk

`func (o *UpdateProjectDraftRequest) GetStepOk() (*string, bool)`

GetStepOk returns a tuple with the Step field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStep

`func (o *UpdateProjectDraftRequest) SetStep(v string)`

SetStep sets Step field to given value.


### GetName

`func (o *UpdateProjectDraftRequest) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *UpdateProjectDraftRequest) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *UpdateProjectDraftRequest) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *UpdateProjectDraftRequest) HasName() bool`

HasName returns a boolean if a field has been set.

### GetBrandName

`func (o *UpdateProjectDraftRequest) GetBrandName() string`

GetBrandName returns the BrandName field if non-nil, zero value otherwise.

### GetBrandNameOk

`func (o *UpdateProjectDraftRequest) GetBrandNameOk() (*string, bool)`

GetBrandNameOk returns a tuple with the BrandName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBrandName

`func (o *UpdateProjectDraftRequest) SetBrandName(v string)`

SetBrandName sets BrandName field to given value.

### HasBrandName

`func (o *UpdateProjectDraftRequest) HasBrandName() bool`

HasBrandName returns a boolean if a field has been set.

### GetDescription

`func (o *UpdateProjectDraftRequest) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *UpdateProjectDraftRequest) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *UpdateProjectDraftRequest) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *UpdateProjectDraftRequest) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetIndustry

`func (o *UpdateProjectDraftRequest) GetIndustry() []string`

GetIndustry returns the Industry field if non-nil, zero value otherwise.

### GetIndustryOk

`func (o *UpdateProjectDraftRequest) GetIndustryOk() (*[]string, bool)`

GetIndustryOk returns a tuple with the Industry field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIndustry

`func (o *UpdateProjectDraftRequest) SetIndustry(v []string)`

SetIndustry sets Industry field to given value.

### HasIndustry

`func (o *UpdateProjectDraftRequest) HasIndustry() bool`

HasIndustry returns a boolean if a field has been set.

### GetMatchingNames

`func (o *UpdateProjectDraftRequest) GetMatchingNames() []string`

GetMatchingNames returns the MatchingNames field if non-nil, zero value otherwise.

### GetMatchingNamesOk

`func (o *UpdateProjectDraftRequest) GetMatchingNamesOk() (*[]string, bool)`

GetMatchingNamesOk returns a tuple with the MatchingNames field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMatchingNames

`func (o *UpdateProjectDraftRequest) SetMatchingNames(v []string)`

SetMatchingNames sets MatchingNames field to given value.

### HasMatchingNames

`func (o *UpdateProjectDraftRequest) HasMatchingNames() bool`

HasMatchingNames returns a boolean if a field has been set.

### GetExternalIdentifier

`func (o *UpdateProjectDraftRequest) GetExternalIdentifier() string`

GetExternalIdentifier returns the ExternalIdentifier field if non-nil, zero value otherwise.

### GetExternalIdentifierOk

`func (o *UpdateProjectDraftRequest) GetExternalIdentifierOk() (*string, bool)`

GetExternalIdentifierOk returns a tuple with the ExternalIdentifier field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExternalIdentifier

`func (o *UpdateProjectDraftRequest) SetExternalIdentifier(v string)`

SetExternalIdentifier sets ExternalIdentifier field to given value.

### HasExternalIdentifier

`func (o *UpdateProjectDraftRequest) HasExternalIdentifier() bool`

HasExternalIdentifier returns a boolean if a field has been set.

### GetPrompts

`func (o *UpdateProjectDraftRequest) GetPrompts() []string`

GetPrompts returns the Prompts field if non-nil, zero value otherwise.

### GetPromptsOk

`func (o *UpdateProjectDraftRequest) GetPromptsOk() (*[]string, bool)`

GetPromptsOk returns a tuple with the Prompts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrompts

`func (o *UpdateProjectDraftRequest) SetPrompts(v []string)`

SetPrompts sets Prompts field to given value.

### HasPrompts

`func (o *UpdateProjectDraftRequest) HasPrompts() bool`

HasPrompts returns a boolean if a field has been set.

### GetCompetitors

`func (o *UpdateProjectDraftRequest) GetCompetitors() []map[string]interface{}`

GetCompetitors returns the Competitors field if non-nil, zero value otherwise.

### GetCompetitorsOk

`func (o *UpdateProjectDraftRequest) GetCompetitorsOk() (*[]map[string]interface{}, bool)`

GetCompetitorsOk returns a tuple with the Competitors field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompetitors

`func (o *UpdateProjectDraftRequest) SetCompetitors(v []map[string]interface{})`

SetCompetitors sets Competitors field to given value.

### HasCompetitors

`func (o *UpdateProjectDraftRequest) HasCompetitors() bool`

HasCompetitors returns a boolean if a field has been set.

### GetYoutubeChannelUrl

`func (o *UpdateProjectDraftRequest) GetYoutubeChannelUrl() string`

GetYoutubeChannelUrl returns the YoutubeChannelUrl field if non-nil, zero value otherwise.

### GetYoutubeChannelUrlOk

`func (o *UpdateProjectDraftRequest) GetYoutubeChannelUrlOk() (*string, bool)`

GetYoutubeChannelUrlOk returns a tuple with the YoutubeChannelUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetYoutubeChannelUrl

`func (o *UpdateProjectDraftRequest) SetYoutubeChannelUrl(v string)`

SetYoutubeChannelUrl sets YoutubeChannelUrl field to given value.

### HasYoutubeChannelUrl

`func (o *UpdateProjectDraftRequest) HasYoutubeChannelUrl() bool`

HasYoutubeChannelUrl returns a boolean if a field has been set.

### GetInstagramProfileUrl

`func (o *UpdateProjectDraftRequest) GetInstagramProfileUrl() string`

GetInstagramProfileUrl returns the InstagramProfileUrl field if non-nil, zero value otherwise.

### GetInstagramProfileUrlOk

`func (o *UpdateProjectDraftRequest) GetInstagramProfileUrlOk() (*string, bool)`

GetInstagramProfileUrlOk returns a tuple with the InstagramProfileUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInstagramProfileUrl

`func (o *UpdateProjectDraftRequest) SetInstagramProfileUrl(v string)`

SetInstagramProfileUrl sets InstagramProfileUrl field to given value.

### HasInstagramProfileUrl

`func (o *UpdateProjectDraftRequest) HasInstagramProfileUrl() bool`

HasInstagramProfileUrl returns a boolean if a field has been set.

### GetFacebookPageUrl

`func (o *UpdateProjectDraftRequest) GetFacebookPageUrl() string`

GetFacebookPageUrl returns the FacebookPageUrl field if non-nil, zero value otherwise.

### GetFacebookPageUrlOk

`func (o *UpdateProjectDraftRequest) GetFacebookPageUrlOk() (*string, bool)`

GetFacebookPageUrlOk returns a tuple with the FacebookPageUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFacebookPageUrl

`func (o *UpdateProjectDraftRequest) SetFacebookPageUrl(v string)`

SetFacebookPageUrl sets FacebookPageUrl field to given value.

### HasFacebookPageUrl

`func (o *UpdateProjectDraftRequest) HasFacebookPageUrl() bool`

HasFacebookPageUrl returns a boolean if a field has been set.

### GetTiktokProfileUrl

`func (o *UpdateProjectDraftRequest) GetTiktokProfileUrl() string`

GetTiktokProfileUrl returns the TiktokProfileUrl field if non-nil, zero value otherwise.

### GetTiktokProfileUrlOk

`func (o *UpdateProjectDraftRequest) GetTiktokProfileUrlOk() (*string, bool)`

GetTiktokProfileUrlOk returns a tuple with the TiktokProfileUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTiktokProfileUrl

`func (o *UpdateProjectDraftRequest) SetTiktokProfileUrl(v string)`

SetTiktokProfileUrl sets TiktokProfileUrl field to given value.

### HasTiktokProfileUrl

`func (o *UpdateProjectDraftRequest) HasTiktokProfileUrl() bool`

HasTiktokProfileUrl returns a boolean if a field has been set.

### GetAppStoreUrl

`func (o *UpdateProjectDraftRequest) GetAppStoreUrl() string`

GetAppStoreUrl returns the AppStoreUrl field if non-nil, zero value otherwise.

### GetAppStoreUrlOk

`func (o *UpdateProjectDraftRequest) GetAppStoreUrlOk() (*string, bool)`

GetAppStoreUrlOk returns a tuple with the AppStoreUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAppStoreUrl

`func (o *UpdateProjectDraftRequest) SetAppStoreUrl(v string)`

SetAppStoreUrl sets AppStoreUrl field to given value.

### HasAppStoreUrl

`func (o *UpdateProjectDraftRequest) HasAppStoreUrl() bool`

HasAppStoreUrl returns a boolean if a field has been set.

### GetGooglePlayUrl

`func (o *UpdateProjectDraftRequest) GetGooglePlayUrl() string`

GetGooglePlayUrl returns the GooglePlayUrl field if non-nil, zero value otherwise.

### GetGooglePlayUrlOk

`func (o *UpdateProjectDraftRequest) GetGooglePlayUrlOk() (*string, bool)`

GetGooglePlayUrlOk returns a tuple with the GooglePlayUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGooglePlayUrl

`func (o *UpdateProjectDraftRequest) SetGooglePlayUrl(v string)`

SetGooglePlayUrl sets GooglePlayUrl field to given value.

### HasGooglePlayUrl

`func (o *UpdateProjectDraftRequest) HasGooglePlayUrl() bool`

HasGooglePlayUrl returns a boolean if a field has been set.

### GetSuggest

`func (o *UpdateProjectDraftRequest) GetSuggest() bool`

GetSuggest returns the Suggest field if non-nil, zero value otherwise.

### GetSuggestOk

`func (o *UpdateProjectDraftRequest) GetSuggestOk() (*bool, bool)`

GetSuggestOk returns a tuple with the Suggest field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuggest

`func (o *UpdateProjectDraftRequest) SetSuggest(v bool)`

SetSuggest sets Suggest field to given value.

### HasSuggest

`func (o *UpdateProjectDraftRequest) HasSuggest() bool`

HasSuggest returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


