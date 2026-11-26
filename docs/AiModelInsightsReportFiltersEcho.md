# AiModelInsightsReportFiltersEcho

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**From** | **time.Time** |  | 
**To** | **time.Time** |  | 
**Granularity** | **string** |  | 
**CountryCode** | Pointer to **string** | Comma-separated country codes | [optional] 
**LanguageCode** | Pointer to **string** | Comma-separated language codes | [optional] 
**CollectionId** | Pointer to **string** | Comma-separated collection ids | [optional] 
**PromptType** | Pointer to **string** | Comma-separated prompt types | [optional] 
**BrandKind** | Pointer to **string** |  | [optional] 
**Model** | Pointer to **string** | The model filter; always ai_overview on the AI Overview report | [optional] 
**Competitors** | **[]int32** | Competitor ids from the competitors parameter; empty when it was not given | 
**Brand1** | Pointer to **string** | Position distribution only. The id, as a string, of the competitor compared as the first brand; left out for the project brand | [optional] 
**Brand2** | Pointer to **string** | Position distribution only. The id, as a string, of the competitor compared as the second brand, by default the competitor with the most mentions; left out when the project has none to compare | [optional] 

## Methods

### NewAiModelInsightsReportFiltersEcho

`func NewAiModelInsightsReportFiltersEcho(from time.Time, to time.Time, granularity string, competitors []int32, ) *AiModelInsightsReportFiltersEcho`

NewAiModelInsightsReportFiltersEcho instantiates a new AiModelInsightsReportFiltersEcho object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAiModelInsightsReportFiltersEchoWithDefaults

`func NewAiModelInsightsReportFiltersEchoWithDefaults() *AiModelInsightsReportFiltersEcho`

NewAiModelInsightsReportFiltersEchoWithDefaults instantiates a new AiModelInsightsReportFiltersEcho object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetFrom

`func (o *AiModelInsightsReportFiltersEcho) GetFrom() time.Time`

GetFrom returns the From field if non-nil, zero value otherwise.

### GetFromOk

`func (o *AiModelInsightsReportFiltersEcho) GetFromOk() (*time.Time, bool)`

GetFromOk returns a tuple with the From field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFrom

`func (o *AiModelInsightsReportFiltersEcho) SetFrom(v time.Time)`

SetFrom sets From field to given value.


### GetTo

`func (o *AiModelInsightsReportFiltersEcho) GetTo() time.Time`

GetTo returns the To field if non-nil, zero value otherwise.

### GetToOk

`func (o *AiModelInsightsReportFiltersEcho) GetToOk() (*time.Time, bool)`

GetToOk returns a tuple with the To field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTo

`func (o *AiModelInsightsReportFiltersEcho) SetTo(v time.Time)`

SetTo sets To field to given value.


### GetGranularity

`func (o *AiModelInsightsReportFiltersEcho) GetGranularity() string`

GetGranularity returns the Granularity field if non-nil, zero value otherwise.

### GetGranularityOk

`func (o *AiModelInsightsReportFiltersEcho) GetGranularityOk() (*string, bool)`

GetGranularityOk returns a tuple with the Granularity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGranularity

`func (o *AiModelInsightsReportFiltersEcho) SetGranularity(v string)`

SetGranularity sets Granularity field to given value.


### GetCountryCode

`func (o *AiModelInsightsReportFiltersEcho) GetCountryCode() string`

GetCountryCode returns the CountryCode field if non-nil, zero value otherwise.

### GetCountryCodeOk

`func (o *AiModelInsightsReportFiltersEcho) GetCountryCodeOk() (*string, bool)`

GetCountryCodeOk returns a tuple with the CountryCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountryCode

`func (o *AiModelInsightsReportFiltersEcho) SetCountryCode(v string)`

SetCountryCode sets CountryCode field to given value.

### HasCountryCode

`func (o *AiModelInsightsReportFiltersEcho) HasCountryCode() bool`

HasCountryCode returns a boolean if a field has been set.

### GetLanguageCode

`func (o *AiModelInsightsReportFiltersEcho) GetLanguageCode() string`

GetLanguageCode returns the LanguageCode field if non-nil, zero value otherwise.

### GetLanguageCodeOk

`func (o *AiModelInsightsReportFiltersEcho) GetLanguageCodeOk() (*string, bool)`

GetLanguageCodeOk returns a tuple with the LanguageCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLanguageCode

`func (o *AiModelInsightsReportFiltersEcho) SetLanguageCode(v string)`

SetLanguageCode sets LanguageCode field to given value.

### HasLanguageCode

`func (o *AiModelInsightsReportFiltersEcho) HasLanguageCode() bool`

HasLanguageCode returns a boolean if a field has been set.

### GetCollectionId

`func (o *AiModelInsightsReportFiltersEcho) GetCollectionId() string`

GetCollectionId returns the CollectionId field if non-nil, zero value otherwise.

### GetCollectionIdOk

`func (o *AiModelInsightsReportFiltersEcho) GetCollectionIdOk() (*string, bool)`

GetCollectionIdOk returns a tuple with the CollectionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCollectionId

`func (o *AiModelInsightsReportFiltersEcho) SetCollectionId(v string)`

SetCollectionId sets CollectionId field to given value.

### HasCollectionId

`func (o *AiModelInsightsReportFiltersEcho) HasCollectionId() bool`

HasCollectionId returns a boolean if a field has been set.

### GetPromptType

`func (o *AiModelInsightsReportFiltersEcho) GetPromptType() string`

GetPromptType returns the PromptType field if non-nil, zero value otherwise.

### GetPromptTypeOk

`func (o *AiModelInsightsReportFiltersEcho) GetPromptTypeOk() (*string, bool)`

GetPromptTypeOk returns a tuple with the PromptType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPromptType

`func (o *AiModelInsightsReportFiltersEcho) SetPromptType(v string)`

SetPromptType sets PromptType field to given value.

### HasPromptType

`func (o *AiModelInsightsReportFiltersEcho) HasPromptType() bool`

HasPromptType returns a boolean if a field has been set.

### GetBrandKind

`func (o *AiModelInsightsReportFiltersEcho) GetBrandKind() string`

GetBrandKind returns the BrandKind field if non-nil, zero value otherwise.

### GetBrandKindOk

`func (o *AiModelInsightsReportFiltersEcho) GetBrandKindOk() (*string, bool)`

GetBrandKindOk returns a tuple with the BrandKind field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBrandKind

`func (o *AiModelInsightsReportFiltersEcho) SetBrandKind(v string)`

SetBrandKind sets BrandKind field to given value.

### HasBrandKind

`func (o *AiModelInsightsReportFiltersEcho) HasBrandKind() bool`

HasBrandKind returns a boolean if a field has been set.

### GetModel

`func (o *AiModelInsightsReportFiltersEcho) GetModel() string`

GetModel returns the Model field if non-nil, zero value otherwise.

### GetModelOk

`func (o *AiModelInsightsReportFiltersEcho) GetModelOk() (*string, bool)`

GetModelOk returns a tuple with the Model field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModel

`func (o *AiModelInsightsReportFiltersEcho) SetModel(v string)`

SetModel sets Model field to given value.

### HasModel

`func (o *AiModelInsightsReportFiltersEcho) HasModel() bool`

HasModel returns a boolean if a field has been set.

### GetCompetitors

`func (o *AiModelInsightsReportFiltersEcho) GetCompetitors() []int32`

GetCompetitors returns the Competitors field if non-nil, zero value otherwise.

### GetCompetitorsOk

`func (o *AiModelInsightsReportFiltersEcho) GetCompetitorsOk() (*[]int32, bool)`

GetCompetitorsOk returns a tuple with the Competitors field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompetitors

`func (o *AiModelInsightsReportFiltersEcho) SetCompetitors(v []int32)`

SetCompetitors sets Competitors field to given value.


### GetBrand1

`func (o *AiModelInsightsReportFiltersEcho) GetBrand1() string`

GetBrand1 returns the Brand1 field if non-nil, zero value otherwise.

### GetBrand1Ok

`func (o *AiModelInsightsReportFiltersEcho) GetBrand1Ok() (*string, bool)`

GetBrand1Ok returns a tuple with the Brand1 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBrand1

`func (o *AiModelInsightsReportFiltersEcho) SetBrand1(v string)`

SetBrand1 sets Brand1 field to given value.

### HasBrand1

`func (o *AiModelInsightsReportFiltersEcho) HasBrand1() bool`

HasBrand1 returns a boolean if a field has been set.

### GetBrand2

`func (o *AiModelInsightsReportFiltersEcho) GetBrand2() string`

GetBrand2 returns the Brand2 field if non-nil, zero value otherwise.

### GetBrand2Ok

`func (o *AiModelInsightsReportFiltersEcho) GetBrand2Ok() (*string, bool)`

GetBrand2Ok returns a tuple with the Brand2 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBrand2

`func (o *AiModelInsightsReportFiltersEcho) SetBrand2(v string)`

SetBrand2 sets Brand2 field to given value.

### HasBrand2

`func (o *AiModelInsightsReportFiltersEcho) HasBrand2() bool`

HasBrand2 returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


