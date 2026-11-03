# AiModelInsightsFiltersEcho

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**From** | Pointer to **time.Time** |  | [optional] 
**To** | Pointer to **time.Time** |  | [optional] 
**Granularity** | Pointer to **string** | day, week or month; day when not given | [optional] 
**CountryCode** | Pointer to **string** | Comma-separated country codes | [optional] 
**LanguageCode** | Pointer to **string** | Comma-separated language codes | [optional] 
**CollectionId** | Pointer to **string** | Comma-separated collection ids | [optional] 
**PromptType** | Pointer to **string** | Comma-separated prompt types | [optional] 
**BrandKind** | Pointer to **string** |  | [optional] 
**Competitors** | Pointer to **[]int32** | Competitor ids from the competitors parameter; empty when it was not given | [optional] 

## Methods

### NewAiModelInsightsFiltersEcho

`func NewAiModelInsightsFiltersEcho() *AiModelInsightsFiltersEcho`

NewAiModelInsightsFiltersEcho instantiates a new AiModelInsightsFiltersEcho object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAiModelInsightsFiltersEchoWithDefaults

`func NewAiModelInsightsFiltersEchoWithDefaults() *AiModelInsightsFiltersEcho`

NewAiModelInsightsFiltersEchoWithDefaults instantiates a new AiModelInsightsFiltersEcho object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetFrom

`func (o *AiModelInsightsFiltersEcho) GetFrom() time.Time`

GetFrom returns the From field if non-nil, zero value otherwise.

### GetFromOk

`func (o *AiModelInsightsFiltersEcho) GetFromOk() (*time.Time, bool)`

GetFromOk returns a tuple with the From field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFrom

`func (o *AiModelInsightsFiltersEcho) SetFrom(v time.Time)`

SetFrom sets From field to given value.

### HasFrom

`func (o *AiModelInsightsFiltersEcho) HasFrom() bool`

HasFrom returns a boolean if a field has been set.

### GetTo

`func (o *AiModelInsightsFiltersEcho) GetTo() time.Time`

GetTo returns the To field if non-nil, zero value otherwise.

### GetToOk

`func (o *AiModelInsightsFiltersEcho) GetToOk() (*time.Time, bool)`

GetToOk returns a tuple with the To field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTo

`func (o *AiModelInsightsFiltersEcho) SetTo(v time.Time)`

SetTo sets To field to given value.

### HasTo

`func (o *AiModelInsightsFiltersEcho) HasTo() bool`

HasTo returns a boolean if a field has been set.

### GetGranularity

`func (o *AiModelInsightsFiltersEcho) GetGranularity() string`

GetGranularity returns the Granularity field if non-nil, zero value otherwise.

### GetGranularityOk

`func (o *AiModelInsightsFiltersEcho) GetGranularityOk() (*string, bool)`

GetGranularityOk returns a tuple with the Granularity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGranularity

`func (o *AiModelInsightsFiltersEcho) SetGranularity(v string)`

SetGranularity sets Granularity field to given value.

### HasGranularity

`func (o *AiModelInsightsFiltersEcho) HasGranularity() bool`

HasGranularity returns a boolean if a field has been set.

### GetCountryCode

`func (o *AiModelInsightsFiltersEcho) GetCountryCode() string`

GetCountryCode returns the CountryCode field if non-nil, zero value otherwise.

### GetCountryCodeOk

`func (o *AiModelInsightsFiltersEcho) GetCountryCodeOk() (*string, bool)`

GetCountryCodeOk returns a tuple with the CountryCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountryCode

`func (o *AiModelInsightsFiltersEcho) SetCountryCode(v string)`

SetCountryCode sets CountryCode field to given value.

### HasCountryCode

`func (o *AiModelInsightsFiltersEcho) HasCountryCode() bool`

HasCountryCode returns a boolean if a field has been set.

### GetLanguageCode

`func (o *AiModelInsightsFiltersEcho) GetLanguageCode() string`

GetLanguageCode returns the LanguageCode field if non-nil, zero value otherwise.

### GetLanguageCodeOk

`func (o *AiModelInsightsFiltersEcho) GetLanguageCodeOk() (*string, bool)`

GetLanguageCodeOk returns a tuple with the LanguageCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLanguageCode

`func (o *AiModelInsightsFiltersEcho) SetLanguageCode(v string)`

SetLanguageCode sets LanguageCode field to given value.

### HasLanguageCode

`func (o *AiModelInsightsFiltersEcho) HasLanguageCode() bool`

HasLanguageCode returns a boolean if a field has been set.

### GetCollectionId

`func (o *AiModelInsightsFiltersEcho) GetCollectionId() string`

GetCollectionId returns the CollectionId field if non-nil, zero value otherwise.

### GetCollectionIdOk

`func (o *AiModelInsightsFiltersEcho) GetCollectionIdOk() (*string, bool)`

GetCollectionIdOk returns a tuple with the CollectionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCollectionId

`func (o *AiModelInsightsFiltersEcho) SetCollectionId(v string)`

SetCollectionId sets CollectionId field to given value.

### HasCollectionId

`func (o *AiModelInsightsFiltersEcho) HasCollectionId() bool`

HasCollectionId returns a boolean if a field has been set.

### GetPromptType

`func (o *AiModelInsightsFiltersEcho) GetPromptType() string`

GetPromptType returns the PromptType field if non-nil, zero value otherwise.

### GetPromptTypeOk

`func (o *AiModelInsightsFiltersEcho) GetPromptTypeOk() (*string, bool)`

GetPromptTypeOk returns a tuple with the PromptType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPromptType

`func (o *AiModelInsightsFiltersEcho) SetPromptType(v string)`

SetPromptType sets PromptType field to given value.

### HasPromptType

`func (o *AiModelInsightsFiltersEcho) HasPromptType() bool`

HasPromptType returns a boolean if a field has been set.

### GetBrandKind

`func (o *AiModelInsightsFiltersEcho) GetBrandKind() string`

GetBrandKind returns the BrandKind field if non-nil, zero value otherwise.

### GetBrandKindOk

`func (o *AiModelInsightsFiltersEcho) GetBrandKindOk() (*string, bool)`

GetBrandKindOk returns a tuple with the BrandKind field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBrandKind

`func (o *AiModelInsightsFiltersEcho) SetBrandKind(v string)`

SetBrandKind sets BrandKind field to given value.

### HasBrandKind

`func (o *AiModelInsightsFiltersEcho) HasBrandKind() bool`

HasBrandKind returns a boolean if a field has been set.

### GetCompetitors

`func (o *AiModelInsightsFiltersEcho) GetCompetitors() []int32`

GetCompetitors returns the Competitors field if non-nil, zero value otherwise.

### GetCompetitorsOk

`func (o *AiModelInsightsFiltersEcho) GetCompetitorsOk() (*[]int32, bool)`

GetCompetitorsOk returns a tuple with the Competitors field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompetitors

`func (o *AiModelInsightsFiltersEcho) SetCompetitors(v []int32)`

SetCompetitors sets Competitors field to given value.

### HasCompetitors

`func (o *AiModelInsightsFiltersEcho) HasCompetitors() bool`

HasCompetitors returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


