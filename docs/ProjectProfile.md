# ProjectProfile

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **int32** |  | 
**Name** | **string** |  | 
**BrandName** | Pointer to **NullableString** |  | [optional] 
**Description** | Pointer to **NullableString** |  | [optional] 
**Industry** | Pointer to **interface{}** | Industry as stored: one key as a string (e.g. SAAS), or an array of key strings. Deliberately untyped so generated clients decode either shape | [optional] 
**BusinessModel** | Pointer to **NullableString** |  | [optional] 
**BusinessModelOther** | Pointer to **NullableString** | Set only when business_model is OTHER | [optional] 
**TargetAudience** | Pointer to **NullableString** |  | [optional] 
**PrimaryProducts** | Pointer to **[]string** |  | [optional] 
**BrandVoice** | Pointer to **NullableString** |  | [optional] 
**Goals** | Pointer to **NullableString** |  | [optional] 
**MatchingNames** | **[]string** |  | 
**AdditionalOwnedDomains** | **[]string** | Other domains the brand owns (at most 10, each a website&#39;s own domain covering its subdomains), whose citations count as owned like the project website. Empty when none | 
**PromptLimit** | **NullableInt32** | The most prompts this project can hold, set by the account owner or a co-owner (Account Settings &gt; Prompt Limits). Null when the project has no limit of its own; the account&#39;s plan allowance applies either way | 

## Methods

### NewProjectProfile

`func NewProjectProfile(id int32, name string, matchingNames []string, additionalOwnedDomains []string, promptLimit NullableInt32, ) *ProjectProfile`

NewProjectProfile instantiates a new ProjectProfile object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProjectProfileWithDefaults

`func NewProjectProfileWithDefaults() *ProjectProfile`

NewProjectProfileWithDefaults instantiates a new ProjectProfile object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *ProjectProfile) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ProjectProfile) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ProjectProfile) SetId(v int32)`

SetId sets Id field to given value.


### GetName

`func (o *ProjectProfile) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ProjectProfile) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ProjectProfile) SetName(v string)`

SetName sets Name field to given value.


### GetBrandName

`func (o *ProjectProfile) GetBrandName() string`

GetBrandName returns the BrandName field if non-nil, zero value otherwise.

### GetBrandNameOk

`func (o *ProjectProfile) GetBrandNameOk() (*string, bool)`

GetBrandNameOk returns a tuple with the BrandName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBrandName

`func (o *ProjectProfile) SetBrandName(v string)`

SetBrandName sets BrandName field to given value.

### HasBrandName

`func (o *ProjectProfile) HasBrandName() bool`

HasBrandName returns a boolean if a field has been set.

### SetBrandNameNil

`func (o *ProjectProfile) SetBrandNameNil(b bool)`

 SetBrandNameNil sets the value for BrandName to be an explicit nil

### UnsetBrandName
`func (o *ProjectProfile) UnsetBrandName()`

UnsetBrandName ensures that no value is present for BrandName, not even an explicit nil
### GetDescription

`func (o *ProjectProfile) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *ProjectProfile) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *ProjectProfile) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *ProjectProfile) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### SetDescriptionNil

`func (o *ProjectProfile) SetDescriptionNil(b bool)`

 SetDescriptionNil sets the value for Description to be an explicit nil

### UnsetDescription
`func (o *ProjectProfile) UnsetDescription()`

UnsetDescription ensures that no value is present for Description, not even an explicit nil
### GetIndustry

`func (o *ProjectProfile) GetIndustry() interface{}`

GetIndustry returns the Industry field if non-nil, zero value otherwise.

### GetIndustryOk

`func (o *ProjectProfile) GetIndustryOk() (*interface{}, bool)`

GetIndustryOk returns a tuple with the Industry field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIndustry

`func (o *ProjectProfile) SetIndustry(v interface{})`

SetIndustry sets Industry field to given value.

### HasIndustry

`func (o *ProjectProfile) HasIndustry() bool`

HasIndustry returns a boolean if a field has been set.

### SetIndustryNil

`func (o *ProjectProfile) SetIndustryNil(b bool)`

 SetIndustryNil sets the value for Industry to be an explicit nil

### UnsetIndustry
`func (o *ProjectProfile) UnsetIndustry()`

UnsetIndustry ensures that no value is present for Industry, not even an explicit nil
### GetBusinessModel

`func (o *ProjectProfile) GetBusinessModel() string`

GetBusinessModel returns the BusinessModel field if non-nil, zero value otherwise.

### GetBusinessModelOk

`func (o *ProjectProfile) GetBusinessModelOk() (*string, bool)`

GetBusinessModelOk returns a tuple with the BusinessModel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBusinessModel

`func (o *ProjectProfile) SetBusinessModel(v string)`

SetBusinessModel sets BusinessModel field to given value.

### HasBusinessModel

`func (o *ProjectProfile) HasBusinessModel() bool`

HasBusinessModel returns a boolean if a field has been set.

### SetBusinessModelNil

`func (o *ProjectProfile) SetBusinessModelNil(b bool)`

 SetBusinessModelNil sets the value for BusinessModel to be an explicit nil

### UnsetBusinessModel
`func (o *ProjectProfile) UnsetBusinessModel()`

UnsetBusinessModel ensures that no value is present for BusinessModel, not even an explicit nil
### GetBusinessModelOther

`func (o *ProjectProfile) GetBusinessModelOther() string`

GetBusinessModelOther returns the BusinessModelOther field if non-nil, zero value otherwise.

### GetBusinessModelOtherOk

`func (o *ProjectProfile) GetBusinessModelOtherOk() (*string, bool)`

GetBusinessModelOtherOk returns a tuple with the BusinessModelOther field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBusinessModelOther

`func (o *ProjectProfile) SetBusinessModelOther(v string)`

SetBusinessModelOther sets BusinessModelOther field to given value.

### HasBusinessModelOther

`func (o *ProjectProfile) HasBusinessModelOther() bool`

HasBusinessModelOther returns a boolean if a field has been set.

### SetBusinessModelOtherNil

`func (o *ProjectProfile) SetBusinessModelOtherNil(b bool)`

 SetBusinessModelOtherNil sets the value for BusinessModelOther to be an explicit nil

### UnsetBusinessModelOther
`func (o *ProjectProfile) UnsetBusinessModelOther()`

UnsetBusinessModelOther ensures that no value is present for BusinessModelOther, not even an explicit nil
### GetTargetAudience

`func (o *ProjectProfile) GetTargetAudience() string`

GetTargetAudience returns the TargetAudience field if non-nil, zero value otherwise.

### GetTargetAudienceOk

`func (o *ProjectProfile) GetTargetAudienceOk() (*string, bool)`

GetTargetAudienceOk returns a tuple with the TargetAudience field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTargetAudience

`func (o *ProjectProfile) SetTargetAudience(v string)`

SetTargetAudience sets TargetAudience field to given value.

### HasTargetAudience

`func (o *ProjectProfile) HasTargetAudience() bool`

HasTargetAudience returns a boolean if a field has been set.

### SetTargetAudienceNil

`func (o *ProjectProfile) SetTargetAudienceNil(b bool)`

 SetTargetAudienceNil sets the value for TargetAudience to be an explicit nil

### UnsetTargetAudience
`func (o *ProjectProfile) UnsetTargetAudience()`

UnsetTargetAudience ensures that no value is present for TargetAudience, not even an explicit nil
### GetPrimaryProducts

`func (o *ProjectProfile) GetPrimaryProducts() []string`

GetPrimaryProducts returns the PrimaryProducts field if non-nil, zero value otherwise.

### GetPrimaryProductsOk

`func (o *ProjectProfile) GetPrimaryProductsOk() (*[]string, bool)`

GetPrimaryProductsOk returns a tuple with the PrimaryProducts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrimaryProducts

`func (o *ProjectProfile) SetPrimaryProducts(v []string)`

SetPrimaryProducts sets PrimaryProducts field to given value.

### HasPrimaryProducts

`func (o *ProjectProfile) HasPrimaryProducts() bool`

HasPrimaryProducts returns a boolean if a field has been set.

### GetBrandVoice

`func (o *ProjectProfile) GetBrandVoice() string`

GetBrandVoice returns the BrandVoice field if non-nil, zero value otherwise.

### GetBrandVoiceOk

`func (o *ProjectProfile) GetBrandVoiceOk() (*string, bool)`

GetBrandVoiceOk returns a tuple with the BrandVoice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBrandVoice

`func (o *ProjectProfile) SetBrandVoice(v string)`

SetBrandVoice sets BrandVoice field to given value.

### HasBrandVoice

`func (o *ProjectProfile) HasBrandVoice() bool`

HasBrandVoice returns a boolean if a field has been set.

### SetBrandVoiceNil

`func (o *ProjectProfile) SetBrandVoiceNil(b bool)`

 SetBrandVoiceNil sets the value for BrandVoice to be an explicit nil

### UnsetBrandVoice
`func (o *ProjectProfile) UnsetBrandVoice()`

UnsetBrandVoice ensures that no value is present for BrandVoice, not even an explicit nil
### GetGoals

`func (o *ProjectProfile) GetGoals() string`

GetGoals returns the Goals field if non-nil, zero value otherwise.

### GetGoalsOk

`func (o *ProjectProfile) GetGoalsOk() (*string, bool)`

GetGoalsOk returns a tuple with the Goals field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGoals

`func (o *ProjectProfile) SetGoals(v string)`

SetGoals sets Goals field to given value.

### HasGoals

`func (o *ProjectProfile) HasGoals() bool`

HasGoals returns a boolean if a field has been set.

### SetGoalsNil

`func (o *ProjectProfile) SetGoalsNil(b bool)`

 SetGoalsNil sets the value for Goals to be an explicit nil

### UnsetGoals
`func (o *ProjectProfile) UnsetGoals()`

UnsetGoals ensures that no value is present for Goals, not even an explicit nil
### GetMatchingNames

`func (o *ProjectProfile) GetMatchingNames() []string`

GetMatchingNames returns the MatchingNames field if non-nil, zero value otherwise.

### GetMatchingNamesOk

`func (o *ProjectProfile) GetMatchingNamesOk() (*[]string, bool)`

GetMatchingNamesOk returns a tuple with the MatchingNames field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMatchingNames

`func (o *ProjectProfile) SetMatchingNames(v []string)`

SetMatchingNames sets MatchingNames field to given value.


### GetAdditionalOwnedDomains

`func (o *ProjectProfile) GetAdditionalOwnedDomains() []string`

GetAdditionalOwnedDomains returns the AdditionalOwnedDomains field if non-nil, zero value otherwise.

### GetAdditionalOwnedDomainsOk

`func (o *ProjectProfile) GetAdditionalOwnedDomainsOk() (*[]string, bool)`

GetAdditionalOwnedDomainsOk returns a tuple with the AdditionalOwnedDomains field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAdditionalOwnedDomains

`func (o *ProjectProfile) SetAdditionalOwnedDomains(v []string)`

SetAdditionalOwnedDomains sets AdditionalOwnedDomains field to given value.


### GetPromptLimit

`func (o *ProjectProfile) GetPromptLimit() int32`

GetPromptLimit returns the PromptLimit field if non-nil, zero value otherwise.

### GetPromptLimitOk

`func (o *ProjectProfile) GetPromptLimitOk() (*int32, bool)`

GetPromptLimitOk returns a tuple with the PromptLimit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPromptLimit

`func (o *ProjectProfile) SetPromptLimit(v int32)`

SetPromptLimit sets PromptLimit field to given value.


### SetPromptLimitNil

`func (o *ProjectProfile) SetPromptLimitNil(b bool)`

 SetPromptLimitNil sets the value for PromptLimit to be an explicit nil

### UnsetPromptLimit
`func (o *ProjectProfile) UnsetPromptLimit()`

UnsetPromptLimit ensures that no value is present for PromptLimit, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


