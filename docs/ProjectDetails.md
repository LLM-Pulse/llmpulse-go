# ProjectDetails

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **int32** |  | [optional] 
**Name** | Pointer to **string** | Internal project label (sidebar, settings, admin) | [optional] 
**BrandName** | Pointer to **NullableString** | LLM-facing brand label (used in prompts and customer-facing charts). Null when not set, in which case prompts and charts use &#x60;name&#x60;. | [optional] 
**Url** | Pointer to **NullableString** |  | [optional] 
**Description** | Pointer to **NullableString** |  | [optional] 
**MatchingNames** | Pointer to **[]string** |  | [optional] 
**Industry** | Pointer to **interface{}** | Industry as stored: one key as a string (e.g. SAAS), or an array of key strings when the project was created with a list or the in-app multi-select. Deliberately untyped so generated clients decode either shape | [optional] 
**BusinessModel** | Pointer to **NullableString** |  | [optional] 
**BusinessModelOther** | Pointer to **NullableString** | Set only when business_model is OTHER | [optional] 
**PrimaryProducts** | Pointer to **[]string** |  | [optional] 
**TargetAudience** | Pointer to **NullableString** |  | [optional] 
**BrandVoice** | Pointer to **NullableString** |  | [optional] 
**Goals** | Pointer to **NullableString** |  | [optional] 
**CountryCode** | Pointer to **string** |  | [optional] 
**LanguageCode** | Pointer to **string** |  | [optional] 
**Paused** | Pointer to **bool** |  | [optional] 
**GooglePlayId** | Pointer to **NullableString** |  | [optional] 
**AppStoreId** | Pointer to **NullableString** |  | [optional] 
**CreatedAt** | Pointer to **time.Time** |  | [optional] 
**Stats** | Pointer to [**ProjectDetailsAllOfStats**](ProjectDetailsAllOfStats.md) |  | [optional] 
**DataCoverage** | Pointer to [**ProjectDetailsAllOfDataCoverage**](ProjectDetailsAllOfDataCoverage.md) |  | [optional] 
**RequestId** | Pointer to **string** |  | [optional] 

## Methods

### NewProjectDetails

`func NewProjectDetails() *ProjectDetails`

NewProjectDetails instantiates a new ProjectDetails object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProjectDetailsWithDefaults

`func NewProjectDetailsWithDefaults() *ProjectDetails`

NewProjectDetailsWithDefaults instantiates a new ProjectDetails object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *ProjectDetails) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ProjectDetails) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ProjectDetails) SetId(v int32)`

SetId sets Id field to given value.

### HasId

`func (o *ProjectDetails) HasId() bool`

HasId returns a boolean if a field has been set.

### GetName

`func (o *ProjectDetails) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ProjectDetails) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ProjectDetails) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *ProjectDetails) HasName() bool`

HasName returns a boolean if a field has been set.

### GetBrandName

`func (o *ProjectDetails) GetBrandName() string`

GetBrandName returns the BrandName field if non-nil, zero value otherwise.

### GetBrandNameOk

`func (o *ProjectDetails) GetBrandNameOk() (*string, bool)`

GetBrandNameOk returns a tuple with the BrandName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBrandName

`func (o *ProjectDetails) SetBrandName(v string)`

SetBrandName sets BrandName field to given value.

### HasBrandName

`func (o *ProjectDetails) HasBrandName() bool`

HasBrandName returns a boolean if a field has been set.

### SetBrandNameNil

`func (o *ProjectDetails) SetBrandNameNil(b bool)`

 SetBrandNameNil sets the value for BrandName to be an explicit nil

### UnsetBrandName
`func (o *ProjectDetails) UnsetBrandName()`

UnsetBrandName ensures that no value is present for BrandName, not even an explicit nil
### GetUrl

`func (o *ProjectDetails) GetUrl() string`

GetUrl returns the Url field if non-nil, zero value otherwise.

### GetUrlOk

`func (o *ProjectDetails) GetUrlOk() (*string, bool)`

GetUrlOk returns a tuple with the Url field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrl

`func (o *ProjectDetails) SetUrl(v string)`

SetUrl sets Url field to given value.

### HasUrl

`func (o *ProjectDetails) HasUrl() bool`

HasUrl returns a boolean if a field has been set.

### SetUrlNil

`func (o *ProjectDetails) SetUrlNil(b bool)`

 SetUrlNil sets the value for Url to be an explicit nil

### UnsetUrl
`func (o *ProjectDetails) UnsetUrl()`

UnsetUrl ensures that no value is present for Url, not even an explicit nil
### GetDescription

`func (o *ProjectDetails) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *ProjectDetails) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *ProjectDetails) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *ProjectDetails) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### SetDescriptionNil

`func (o *ProjectDetails) SetDescriptionNil(b bool)`

 SetDescriptionNil sets the value for Description to be an explicit nil

### UnsetDescription
`func (o *ProjectDetails) UnsetDescription()`

UnsetDescription ensures that no value is present for Description, not even an explicit nil
### GetMatchingNames

`func (o *ProjectDetails) GetMatchingNames() []string`

GetMatchingNames returns the MatchingNames field if non-nil, zero value otherwise.

### GetMatchingNamesOk

`func (o *ProjectDetails) GetMatchingNamesOk() (*[]string, bool)`

GetMatchingNamesOk returns a tuple with the MatchingNames field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMatchingNames

`func (o *ProjectDetails) SetMatchingNames(v []string)`

SetMatchingNames sets MatchingNames field to given value.

### HasMatchingNames

`func (o *ProjectDetails) HasMatchingNames() bool`

HasMatchingNames returns a boolean if a field has been set.

### GetIndustry

`func (o *ProjectDetails) GetIndustry() interface{}`

GetIndustry returns the Industry field if non-nil, zero value otherwise.

### GetIndustryOk

`func (o *ProjectDetails) GetIndustryOk() (*interface{}, bool)`

GetIndustryOk returns a tuple with the Industry field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIndustry

`func (o *ProjectDetails) SetIndustry(v interface{})`

SetIndustry sets Industry field to given value.

### HasIndustry

`func (o *ProjectDetails) HasIndustry() bool`

HasIndustry returns a boolean if a field has been set.

### SetIndustryNil

`func (o *ProjectDetails) SetIndustryNil(b bool)`

 SetIndustryNil sets the value for Industry to be an explicit nil

### UnsetIndustry
`func (o *ProjectDetails) UnsetIndustry()`

UnsetIndustry ensures that no value is present for Industry, not even an explicit nil
### GetBusinessModel

`func (o *ProjectDetails) GetBusinessModel() string`

GetBusinessModel returns the BusinessModel field if non-nil, zero value otherwise.

### GetBusinessModelOk

`func (o *ProjectDetails) GetBusinessModelOk() (*string, bool)`

GetBusinessModelOk returns a tuple with the BusinessModel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBusinessModel

`func (o *ProjectDetails) SetBusinessModel(v string)`

SetBusinessModel sets BusinessModel field to given value.

### HasBusinessModel

`func (o *ProjectDetails) HasBusinessModel() bool`

HasBusinessModel returns a boolean if a field has been set.

### SetBusinessModelNil

`func (o *ProjectDetails) SetBusinessModelNil(b bool)`

 SetBusinessModelNil sets the value for BusinessModel to be an explicit nil

### UnsetBusinessModel
`func (o *ProjectDetails) UnsetBusinessModel()`

UnsetBusinessModel ensures that no value is present for BusinessModel, not even an explicit nil
### GetBusinessModelOther

`func (o *ProjectDetails) GetBusinessModelOther() string`

GetBusinessModelOther returns the BusinessModelOther field if non-nil, zero value otherwise.

### GetBusinessModelOtherOk

`func (o *ProjectDetails) GetBusinessModelOtherOk() (*string, bool)`

GetBusinessModelOtherOk returns a tuple with the BusinessModelOther field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBusinessModelOther

`func (o *ProjectDetails) SetBusinessModelOther(v string)`

SetBusinessModelOther sets BusinessModelOther field to given value.

### HasBusinessModelOther

`func (o *ProjectDetails) HasBusinessModelOther() bool`

HasBusinessModelOther returns a boolean if a field has been set.

### SetBusinessModelOtherNil

`func (o *ProjectDetails) SetBusinessModelOtherNil(b bool)`

 SetBusinessModelOtherNil sets the value for BusinessModelOther to be an explicit nil

### UnsetBusinessModelOther
`func (o *ProjectDetails) UnsetBusinessModelOther()`

UnsetBusinessModelOther ensures that no value is present for BusinessModelOther, not even an explicit nil
### GetPrimaryProducts

`func (o *ProjectDetails) GetPrimaryProducts() []string`

GetPrimaryProducts returns the PrimaryProducts field if non-nil, zero value otherwise.

### GetPrimaryProductsOk

`func (o *ProjectDetails) GetPrimaryProductsOk() (*[]string, bool)`

GetPrimaryProductsOk returns a tuple with the PrimaryProducts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrimaryProducts

`func (o *ProjectDetails) SetPrimaryProducts(v []string)`

SetPrimaryProducts sets PrimaryProducts field to given value.

### HasPrimaryProducts

`func (o *ProjectDetails) HasPrimaryProducts() bool`

HasPrimaryProducts returns a boolean if a field has been set.

### GetTargetAudience

`func (o *ProjectDetails) GetTargetAudience() string`

GetTargetAudience returns the TargetAudience field if non-nil, zero value otherwise.

### GetTargetAudienceOk

`func (o *ProjectDetails) GetTargetAudienceOk() (*string, bool)`

GetTargetAudienceOk returns a tuple with the TargetAudience field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTargetAudience

`func (o *ProjectDetails) SetTargetAudience(v string)`

SetTargetAudience sets TargetAudience field to given value.

### HasTargetAudience

`func (o *ProjectDetails) HasTargetAudience() bool`

HasTargetAudience returns a boolean if a field has been set.

### SetTargetAudienceNil

`func (o *ProjectDetails) SetTargetAudienceNil(b bool)`

 SetTargetAudienceNil sets the value for TargetAudience to be an explicit nil

### UnsetTargetAudience
`func (o *ProjectDetails) UnsetTargetAudience()`

UnsetTargetAudience ensures that no value is present for TargetAudience, not even an explicit nil
### GetBrandVoice

`func (o *ProjectDetails) GetBrandVoice() string`

GetBrandVoice returns the BrandVoice field if non-nil, zero value otherwise.

### GetBrandVoiceOk

`func (o *ProjectDetails) GetBrandVoiceOk() (*string, bool)`

GetBrandVoiceOk returns a tuple with the BrandVoice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBrandVoice

`func (o *ProjectDetails) SetBrandVoice(v string)`

SetBrandVoice sets BrandVoice field to given value.

### HasBrandVoice

`func (o *ProjectDetails) HasBrandVoice() bool`

HasBrandVoice returns a boolean if a field has been set.

### SetBrandVoiceNil

`func (o *ProjectDetails) SetBrandVoiceNil(b bool)`

 SetBrandVoiceNil sets the value for BrandVoice to be an explicit nil

### UnsetBrandVoice
`func (o *ProjectDetails) UnsetBrandVoice()`

UnsetBrandVoice ensures that no value is present for BrandVoice, not even an explicit nil
### GetGoals

`func (o *ProjectDetails) GetGoals() string`

GetGoals returns the Goals field if non-nil, zero value otherwise.

### GetGoalsOk

`func (o *ProjectDetails) GetGoalsOk() (*string, bool)`

GetGoalsOk returns a tuple with the Goals field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGoals

`func (o *ProjectDetails) SetGoals(v string)`

SetGoals sets Goals field to given value.

### HasGoals

`func (o *ProjectDetails) HasGoals() bool`

HasGoals returns a boolean if a field has been set.

### SetGoalsNil

`func (o *ProjectDetails) SetGoalsNil(b bool)`

 SetGoalsNil sets the value for Goals to be an explicit nil

### UnsetGoals
`func (o *ProjectDetails) UnsetGoals()`

UnsetGoals ensures that no value is present for Goals, not even an explicit nil
### GetCountryCode

`func (o *ProjectDetails) GetCountryCode() string`

GetCountryCode returns the CountryCode field if non-nil, zero value otherwise.

### GetCountryCodeOk

`func (o *ProjectDetails) GetCountryCodeOk() (*string, bool)`

GetCountryCodeOk returns a tuple with the CountryCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountryCode

`func (o *ProjectDetails) SetCountryCode(v string)`

SetCountryCode sets CountryCode field to given value.

### HasCountryCode

`func (o *ProjectDetails) HasCountryCode() bool`

HasCountryCode returns a boolean if a field has been set.

### GetLanguageCode

`func (o *ProjectDetails) GetLanguageCode() string`

GetLanguageCode returns the LanguageCode field if non-nil, zero value otherwise.

### GetLanguageCodeOk

`func (o *ProjectDetails) GetLanguageCodeOk() (*string, bool)`

GetLanguageCodeOk returns a tuple with the LanguageCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLanguageCode

`func (o *ProjectDetails) SetLanguageCode(v string)`

SetLanguageCode sets LanguageCode field to given value.

### HasLanguageCode

`func (o *ProjectDetails) HasLanguageCode() bool`

HasLanguageCode returns a boolean if a field has been set.

### GetPaused

`func (o *ProjectDetails) GetPaused() bool`

GetPaused returns the Paused field if non-nil, zero value otherwise.

### GetPausedOk

`func (o *ProjectDetails) GetPausedOk() (*bool, bool)`

GetPausedOk returns a tuple with the Paused field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaused

`func (o *ProjectDetails) SetPaused(v bool)`

SetPaused sets Paused field to given value.

### HasPaused

`func (o *ProjectDetails) HasPaused() bool`

HasPaused returns a boolean if a field has been set.

### GetGooglePlayId

`func (o *ProjectDetails) GetGooglePlayId() string`

GetGooglePlayId returns the GooglePlayId field if non-nil, zero value otherwise.

### GetGooglePlayIdOk

`func (o *ProjectDetails) GetGooglePlayIdOk() (*string, bool)`

GetGooglePlayIdOk returns a tuple with the GooglePlayId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGooglePlayId

`func (o *ProjectDetails) SetGooglePlayId(v string)`

SetGooglePlayId sets GooglePlayId field to given value.

### HasGooglePlayId

`func (o *ProjectDetails) HasGooglePlayId() bool`

HasGooglePlayId returns a boolean if a field has been set.

### SetGooglePlayIdNil

`func (o *ProjectDetails) SetGooglePlayIdNil(b bool)`

 SetGooglePlayIdNil sets the value for GooglePlayId to be an explicit nil

### UnsetGooglePlayId
`func (o *ProjectDetails) UnsetGooglePlayId()`

UnsetGooglePlayId ensures that no value is present for GooglePlayId, not even an explicit nil
### GetAppStoreId

`func (o *ProjectDetails) GetAppStoreId() string`

GetAppStoreId returns the AppStoreId field if non-nil, zero value otherwise.

### GetAppStoreIdOk

`func (o *ProjectDetails) GetAppStoreIdOk() (*string, bool)`

GetAppStoreIdOk returns a tuple with the AppStoreId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAppStoreId

`func (o *ProjectDetails) SetAppStoreId(v string)`

SetAppStoreId sets AppStoreId field to given value.

### HasAppStoreId

`func (o *ProjectDetails) HasAppStoreId() bool`

HasAppStoreId returns a boolean if a field has been set.

### SetAppStoreIdNil

`func (o *ProjectDetails) SetAppStoreIdNil(b bool)`

 SetAppStoreIdNil sets the value for AppStoreId to be an explicit nil

### UnsetAppStoreId
`func (o *ProjectDetails) UnsetAppStoreId()`

UnsetAppStoreId ensures that no value is present for AppStoreId, not even an explicit nil
### GetCreatedAt

`func (o *ProjectDetails) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *ProjectDetails) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *ProjectDetails) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *ProjectDetails) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetStats

`func (o *ProjectDetails) GetStats() ProjectDetailsAllOfStats`

GetStats returns the Stats field if non-nil, zero value otherwise.

### GetStatsOk

`func (o *ProjectDetails) GetStatsOk() (*ProjectDetailsAllOfStats, bool)`

GetStatsOk returns a tuple with the Stats field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStats

`func (o *ProjectDetails) SetStats(v ProjectDetailsAllOfStats)`

SetStats sets Stats field to given value.

### HasStats

`func (o *ProjectDetails) HasStats() bool`

HasStats returns a boolean if a field has been set.

### GetDataCoverage

`func (o *ProjectDetails) GetDataCoverage() ProjectDetailsAllOfDataCoverage`

GetDataCoverage returns the DataCoverage field if non-nil, zero value otherwise.

### GetDataCoverageOk

`func (o *ProjectDetails) GetDataCoverageOk() (*ProjectDetailsAllOfDataCoverage, bool)`

GetDataCoverageOk returns a tuple with the DataCoverage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDataCoverage

`func (o *ProjectDetails) SetDataCoverage(v ProjectDetailsAllOfDataCoverage)`

SetDataCoverage sets DataCoverage field to given value.

### HasDataCoverage

`func (o *ProjectDetails) HasDataCoverage() bool`

HasDataCoverage returns a boolean if a field has been set.

### GetRequestId

`func (o *ProjectDetails) GetRequestId() string`

GetRequestId returns the RequestId field if non-nil, zero value otherwise.

### GetRequestIdOk

`func (o *ProjectDetails) GetRequestIdOk() (*string, bool)`

GetRequestIdOk returns a tuple with the RequestId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestId

`func (o *ProjectDetails) SetRequestId(v string)`

SetRequestId sets RequestId field to given value.

### HasRequestId

`func (o *ProjectDetails) HasRequestId() bool`

HasRequestId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


