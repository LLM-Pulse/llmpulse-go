# MetricsFiltersEcho

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Metrics** | Pointer to **[]string** | Requested metrics after alias resolution (mention_rate is echoed as visibility) | [optional] 
**Granularity** | Pointer to **string** | day, week or month | [optional] 
**Model** | Pointer to **NullableString** | The model filter, or null when absent or not enabled for the account | [optional] 
**CollectionId** | Pointer to **NullableString** | The collection_id parameter as sent (one id or a comma-separated list) | [optional] 
**CollectionIds** | Pointer to **[]int32** |  | [optional] 
**Domains** | Pointer to **[]string** |  | [optional] 
**CountryCode** | Pointer to **NullableString** | Comma-separated country codes | [optional] 
**LanguageCode** | Pointer to **NullableString** | Comma-separated language codes | [optional] 
**Prompt** | Pointer to **NullableInt32** | The prompt id filter | [optional] 
**PromptType** | Pointer to **NullableString** | Comma-separated prompt types | [optional] 
**BrandKind** | Pointer to **NullableString** |  | [optional] 
**Competitors** | Pointer to **[]int32** | Competitor ids from the competitors parameter; empty when it was not given | [optional] 
**IncludeProject** | Pointer to **bool** |  | [optional] 
**Query** | Pointer to **string** | Only present when a query filter was given | [optional] 

## Methods

### NewMetricsFiltersEcho

`func NewMetricsFiltersEcho() *MetricsFiltersEcho`

NewMetricsFiltersEcho instantiates a new MetricsFiltersEcho object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewMetricsFiltersEchoWithDefaults

`func NewMetricsFiltersEchoWithDefaults() *MetricsFiltersEcho`

NewMetricsFiltersEchoWithDefaults instantiates a new MetricsFiltersEcho object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMetrics

`func (o *MetricsFiltersEcho) GetMetrics() []string`

GetMetrics returns the Metrics field if non-nil, zero value otherwise.

### GetMetricsOk

`func (o *MetricsFiltersEcho) GetMetricsOk() (*[]string, bool)`

GetMetricsOk returns a tuple with the Metrics field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetrics

`func (o *MetricsFiltersEcho) SetMetrics(v []string)`

SetMetrics sets Metrics field to given value.

### HasMetrics

`func (o *MetricsFiltersEcho) HasMetrics() bool`

HasMetrics returns a boolean if a field has been set.

### GetGranularity

`func (o *MetricsFiltersEcho) GetGranularity() string`

GetGranularity returns the Granularity field if non-nil, zero value otherwise.

### GetGranularityOk

`func (o *MetricsFiltersEcho) GetGranularityOk() (*string, bool)`

GetGranularityOk returns a tuple with the Granularity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGranularity

`func (o *MetricsFiltersEcho) SetGranularity(v string)`

SetGranularity sets Granularity field to given value.

### HasGranularity

`func (o *MetricsFiltersEcho) HasGranularity() bool`

HasGranularity returns a boolean if a field has been set.

### GetModel

`func (o *MetricsFiltersEcho) GetModel() string`

GetModel returns the Model field if non-nil, zero value otherwise.

### GetModelOk

`func (o *MetricsFiltersEcho) GetModelOk() (*string, bool)`

GetModelOk returns a tuple with the Model field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModel

`func (o *MetricsFiltersEcho) SetModel(v string)`

SetModel sets Model field to given value.

### HasModel

`func (o *MetricsFiltersEcho) HasModel() bool`

HasModel returns a boolean if a field has been set.

### SetModelNil

`func (o *MetricsFiltersEcho) SetModelNil(b bool)`

 SetModelNil sets the value for Model to be an explicit nil

### UnsetModel
`func (o *MetricsFiltersEcho) UnsetModel()`

UnsetModel ensures that no value is present for Model, not even an explicit nil
### GetCollectionId

`func (o *MetricsFiltersEcho) GetCollectionId() string`

GetCollectionId returns the CollectionId field if non-nil, zero value otherwise.

### GetCollectionIdOk

`func (o *MetricsFiltersEcho) GetCollectionIdOk() (*string, bool)`

GetCollectionIdOk returns a tuple with the CollectionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCollectionId

`func (o *MetricsFiltersEcho) SetCollectionId(v string)`

SetCollectionId sets CollectionId field to given value.

### HasCollectionId

`func (o *MetricsFiltersEcho) HasCollectionId() bool`

HasCollectionId returns a boolean if a field has been set.

### SetCollectionIdNil

`func (o *MetricsFiltersEcho) SetCollectionIdNil(b bool)`

 SetCollectionIdNil sets the value for CollectionId to be an explicit nil

### UnsetCollectionId
`func (o *MetricsFiltersEcho) UnsetCollectionId()`

UnsetCollectionId ensures that no value is present for CollectionId, not even an explicit nil
### GetCollectionIds

`func (o *MetricsFiltersEcho) GetCollectionIds() []int32`

GetCollectionIds returns the CollectionIds field if non-nil, zero value otherwise.

### GetCollectionIdsOk

`func (o *MetricsFiltersEcho) GetCollectionIdsOk() (*[]int32, bool)`

GetCollectionIdsOk returns a tuple with the CollectionIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCollectionIds

`func (o *MetricsFiltersEcho) SetCollectionIds(v []int32)`

SetCollectionIds sets CollectionIds field to given value.

### HasCollectionIds

`func (o *MetricsFiltersEcho) HasCollectionIds() bool`

HasCollectionIds returns a boolean if a field has been set.

### SetCollectionIdsNil

`func (o *MetricsFiltersEcho) SetCollectionIdsNil(b bool)`

 SetCollectionIdsNil sets the value for CollectionIds to be an explicit nil

### UnsetCollectionIds
`func (o *MetricsFiltersEcho) UnsetCollectionIds()`

UnsetCollectionIds ensures that no value is present for CollectionIds, not even an explicit nil
### GetDomains

`func (o *MetricsFiltersEcho) GetDomains() []string`

GetDomains returns the Domains field if non-nil, zero value otherwise.

### GetDomainsOk

`func (o *MetricsFiltersEcho) GetDomainsOk() (*[]string, bool)`

GetDomainsOk returns a tuple with the Domains field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDomains

`func (o *MetricsFiltersEcho) SetDomains(v []string)`

SetDomains sets Domains field to given value.

### HasDomains

`func (o *MetricsFiltersEcho) HasDomains() bool`

HasDomains returns a boolean if a field has been set.

### SetDomainsNil

`func (o *MetricsFiltersEcho) SetDomainsNil(b bool)`

 SetDomainsNil sets the value for Domains to be an explicit nil

### UnsetDomains
`func (o *MetricsFiltersEcho) UnsetDomains()`

UnsetDomains ensures that no value is present for Domains, not even an explicit nil
### GetCountryCode

`func (o *MetricsFiltersEcho) GetCountryCode() string`

GetCountryCode returns the CountryCode field if non-nil, zero value otherwise.

### GetCountryCodeOk

`func (o *MetricsFiltersEcho) GetCountryCodeOk() (*string, bool)`

GetCountryCodeOk returns a tuple with the CountryCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountryCode

`func (o *MetricsFiltersEcho) SetCountryCode(v string)`

SetCountryCode sets CountryCode field to given value.

### HasCountryCode

`func (o *MetricsFiltersEcho) HasCountryCode() bool`

HasCountryCode returns a boolean if a field has been set.

### SetCountryCodeNil

`func (o *MetricsFiltersEcho) SetCountryCodeNil(b bool)`

 SetCountryCodeNil sets the value for CountryCode to be an explicit nil

### UnsetCountryCode
`func (o *MetricsFiltersEcho) UnsetCountryCode()`

UnsetCountryCode ensures that no value is present for CountryCode, not even an explicit nil
### GetLanguageCode

`func (o *MetricsFiltersEcho) GetLanguageCode() string`

GetLanguageCode returns the LanguageCode field if non-nil, zero value otherwise.

### GetLanguageCodeOk

`func (o *MetricsFiltersEcho) GetLanguageCodeOk() (*string, bool)`

GetLanguageCodeOk returns a tuple with the LanguageCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLanguageCode

`func (o *MetricsFiltersEcho) SetLanguageCode(v string)`

SetLanguageCode sets LanguageCode field to given value.

### HasLanguageCode

`func (o *MetricsFiltersEcho) HasLanguageCode() bool`

HasLanguageCode returns a boolean if a field has been set.

### SetLanguageCodeNil

`func (o *MetricsFiltersEcho) SetLanguageCodeNil(b bool)`

 SetLanguageCodeNil sets the value for LanguageCode to be an explicit nil

### UnsetLanguageCode
`func (o *MetricsFiltersEcho) UnsetLanguageCode()`

UnsetLanguageCode ensures that no value is present for LanguageCode, not even an explicit nil
### GetPrompt

`func (o *MetricsFiltersEcho) GetPrompt() int32`

GetPrompt returns the Prompt field if non-nil, zero value otherwise.

### GetPromptOk

`func (o *MetricsFiltersEcho) GetPromptOk() (*int32, bool)`

GetPromptOk returns a tuple with the Prompt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrompt

`func (o *MetricsFiltersEcho) SetPrompt(v int32)`

SetPrompt sets Prompt field to given value.

### HasPrompt

`func (o *MetricsFiltersEcho) HasPrompt() bool`

HasPrompt returns a boolean if a field has been set.

### SetPromptNil

`func (o *MetricsFiltersEcho) SetPromptNil(b bool)`

 SetPromptNil sets the value for Prompt to be an explicit nil

### UnsetPrompt
`func (o *MetricsFiltersEcho) UnsetPrompt()`

UnsetPrompt ensures that no value is present for Prompt, not even an explicit nil
### GetPromptType

`func (o *MetricsFiltersEcho) GetPromptType() string`

GetPromptType returns the PromptType field if non-nil, zero value otherwise.

### GetPromptTypeOk

`func (o *MetricsFiltersEcho) GetPromptTypeOk() (*string, bool)`

GetPromptTypeOk returns a tuple with the PromptType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPromptType

`func (o *MetricsFiltersEcho) SetPromptType(v string)`

SetPromptType sets PromptType field to given value.

### HasPromptType

`func (o *MetricsFiltersEcho) HasPromptType() bool`

HasPromptType returns a boolean if a field has been set.

### SetPromptTypeNil

`func (o *MetricsFiltersEcho) SetPromptTypeNil(b bool)`

 SetPromptTypeNil sets the value for PromptType to be an explicit nil

### UnsetPromptType
`func (o *MetricsFiltersEcho) UnsetPromptType()`

UnsetPromptType ensures that no value is present for PromptType, not even an explicit nil
### GetBrandKind

`func (o *MetricsFiltersEcho) GetBrandKind() string`

GetBrandKind returns the BrandKind field if non-nil, zero value otherwise.

### GetBrandKindOk

`func (o *MetricsFiltersEcho) GetBrandKindOk() (*string, bool)`

GetBrandKindOk returns a tuple with the BrandKind field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBrandKind

`func (o *MetricsFiltersEcho) SetBrandKind(v string)`

SetBrandKind sets BrandKind field to given value.

### HasBrandKind

`func (o *MetricsFiltersEcho) HasBrandKind() bool`

HasBrandKind returns a boolean if a field has been set.

### SetBrandKindNil

`func (o *MetricsFiltersEcho) SetBrandKindNil(b bool)`

 SetBrandKindNil sets the value for BrandKind to be an explicit nil

### UnsetBrandKind
`func (o *MetricsFiltersEcho) UnsetBrandKind()`

UnsetBrandKind ensures that no value is present for BrandKind, not even an explicit nil
### GetCompetitors

`func (o *MetricsFiltersEcho) GetCompetitors() []int32`

GetCompetitors returns the Competitors field if non-nil, zero value otherwise.

### GetCompetitorsOk

`func (o *MetricsFiltersEcho) GetCompetitorsOk() (*[]int32, bool)`

GetCompetitorsOk returns a tuple with the Competitors field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompetitors

`func (o *MetricsFiltersEcho) SetCompetitors(v []int32)`

SetCompetitors sets Competitors field to given value.

### HasCompetitors

`func (o *MetricsFiltersEcho) HasCompetitors() bool`

HasCompetitors returns a boolean if a field has been set.

### GetIncludeProject

`func (o *MetricsFiltersEcho) GetIncludeProject() bool`

GetIncludeProject returns the IncludeProject field if non-nil, zero value otherwise.

### GetIncludeProjectOk

`func (o *MetricsFiltersEcho) GetIncludeProjectOk() (*bool, bool)`

GetIncludeProjectOk returns a tuple with the IncludeProject field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIncludeProject

`func (o *MetricsFiltersEcho) SetIncludeProject(v bool)`

SetIncludeProject sets IncludeProject field to given value.

### HasIncludeProject

`func (o *MetricsFiltersEcho) HasIncludeProject() bool`

HasIncludeProject returns a boolean if a field has been set.

### GetQuery

`func (o *MetricsFiltersEcho) GetQuery() string`

GetQuery returns the Query field if non-nil, zero value otherwise.

### GetQueryOk

`func (o *MetricsFiltersEcho) GetQueryOk() (*string, bool)`

GetQueryOk returns a tuple with the Query field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuery

`func (o *MetricsFiltersEcho) SetQuery(v string)`

SetQuery sets Query field to given value.

### HasQuery

`func (o *MetricsFiltersEcho) HasQuery() bool`

HasQuery returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


