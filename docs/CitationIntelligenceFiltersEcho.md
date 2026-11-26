# CitationIntelligenceFiltersEcho

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Model** | Pointer to **string** |  | [optional] 
**CollectionId** | Pointer to **string** | The collection_id parameter as sent (one id or a comma-separated list) | [optional] 
**CollectionIds** | Pointer to **[]int32** |  | [optional] 
**Domains** | Pointer to **[]string** | Lowercased domains | [optional] 
**Prompt** | Pointer to **int32** | The prompt id filter | [optional] 
**BrandKind** | Pointer to **string** |  | [optional] 
**CountryCode** | Pointer to **string** |  | [optional] 
**LanguageCode** | Pointer to **string** |  | [optional] 
**From** | Pointer to **string** | As given | [optional] 
**To** | Pointer to **string** | As given | [optional] 
**Key** | Pointer to **string** | The group key, as matched | [optional] 
**Query** | Pointer to **string** |  | [optional] 
**SourceType** | Pointer to **string** |  | [optional] 
**Sentiment** | Pointer to **string** |  | [optional] 
**ContentGap** | Pointer to **string** |  | [optional] 

## Methods

### NewCitationIntelligenceFiltersEcho

`func NewCitationIntelligenceFiltersEcho() *CitationIntelligenceFiltersEcho`

NewCitationIntelligenceFiltersEcho instantiates a new CitationIntelligenceFiltersEcho object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCitationIntelligenceFiltersEchoWithDefaults

`func NewCitationIntelligenceFiltersEchoWithDefaults() *CitationIntelligenceFiltersEcho`

NewCitationIntelligenceFiltersEchoWithDefaults instantiates a new CitationIntelligenceFiltersEcho object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetModel

`func (o *CitationIntelligenceFiltersEcho) GetModel() string`

GetModel returns the Model field if non-nil, zero value otherwise.

### GetModelOk

`func (o *CitationIntelligenceFiltersEcho) GetModelOk() (*string, bool)`

GetModelOk returns a tuple with the Model field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModel

`func (o *CitationIntelligenceFiltersEcho) SetModel(v string)`

SetModel sets Model field to given value.

### HasModel

`func (o *CitationIntelligenceFiltersEcho) HasModel() bool`

HasModel returns a boolean if a field has been set.

### GetCollectionId

`func (o *CitationIntelligenceFiltersEcho) GetCollectionId() string`

GetCollectionId returns the CollectionId field if non-nil, zero value otherwise.

### GetCollectionIdOk

`func (o *CitationIntelligenceFiltersEcho) GetCollectionIdOk() (*string, bool)`

GetCollectionIdOk returns a tuple with the CollectionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCollectionId

`func (o *CitationIntelligenceFiltersEcho) SetCollectionId(v string)`

SetCollectionId sets CollectionId field to given value.

### HasCollectionId

`func (o *CitationIntelligenceFiltersEcho) HasCollectionId() bool`

HasCollectionId returns a boolean if a field has been set.

### GetCollectionIds

`func (o *CitationIntelligenceFiltersEcho) GetCollectionIds() []int32`

GetCollectionIds returns the CollectionIds field if non-nil, zero value otherwise.

### GetCollectionIdsOk

`func (o *CitationIntelligenceFiltersEcho) GetCollectionIdsOk() (*[]int32, bool)`

GetCollectionIdsOk returns a tuple with the CollectionIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCollectionIds

`func (o *CitationIntelligenceFiltersEcho) SetCollectionIds(v []int32)`

SetCollectionIds sets CollectionIds field to given value.

### HasCollectionIds

`func (o *CitationIntelligenceFiltersEcho) HasCollectionIds() bool`

HasCollectionIds returns a boolean if a field has been set.

### GetDomains

`func (o *CitationIntelligenceFiltersEcho) GetDomains() []string`

GetDomains returns the Domains field if non-nil, zero value otherwise.

### GetDomainsOk

`func (o *CitationIntelligenceFiltersEcho) GetDomainsOk() (*[]string, bool)`

GetDomainsOk returns a tuple with the Domains field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDomains

`func (o *CitationIntelligenceFiltersEcho) SetDomains(v []string)`

SetDomains sets Domains field to given value.

### HasDomains

`func (o *CitationIntelligenceFiltersEcho) HasDomains() bool`

HasDomains returns a boolean if a field has been set.

### GetPrompt

`func (o *CitationIntelligenceFiltersEcho) GetPrompt() int32`

GetPrompt returns the Prompt field if non-nil, zero value otherwise.

### GetPromptOk

`func (o *CitationIntelligenceFiltersEcho) GetPromptOk() (*int32, bool)`

GetPromptOk returns a tuple with the Prompt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrompt

`func (o *CitationIntelligenceFiltersEcho) SetPrompt(v int32)`

SetPrompt sets Prompt field to given value.

### HasPrompt

`func (o *CitationIntelligenceFiltersEcho) HasPrompt() bool`

HasPrompt returns a boolean if a field has been set.

### GetBrandKind

`func (o *CitationIntelligenceFiltersEcho) GetBrandKind() string`

GetBrandKind returns the BrandKind field if non-nil, zero value otherwise.

### GetBrandKindOk

`func (o *CitationIntelligenceFiltersEcho) GetBrandKindOk() (*string, bool)`

GetBrandKindOk returns a tuple with the BrandKind field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBrandKind

`func (o *CitationIntelligenceFiltersEcho) SetBrandKind(v string)`

SetBrandKind sets BrandKind field to given value.

### HasBrandKind

`func (o *CitationIntelligenceFiltersEcho) HasBrandKind() bool`

HasBrandKind returns a boolean if a field has been set.

### GetCountryCode

`func (o *CitationIntelligenceFiltersEcho) GetCountryCode() string`

GetCountryCode returns the CountryCode field if non-nil, zero value otherwise.

### GetCountryCodeOk

`func (o *CitationIntelligenceFiltersEcho) GetCountryCodeOk() (*string, bool)`

GetCountryCodeOk returns a tuple with the CountryCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountryCode

`func (o *CitationIntelligenceFiltersEcho) SetCountryCode(v string)`

SetCountryCode sets CountryCode field to given value.

### HasCountryCode

`func (o *CitationIntelligenceFiltersEcho) HasCountryCode() bool`

HasCountryCode returns a boolean if a field has been set.

### GetLanguageCode

`func (o *CitationIntelligenceFiltersEcho) GetLanguageCode() string`

GetLanguageCode returns the LanguageCode field if non-nil, zero value otherwise.

### GetLanguageCodeOk

`func (o *CitationIntelligenceFiltersEcho) GetLanguageCodeOk() (*string, bool)`

GetLanguageCodeOk returns a tuple with the LanguageCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLanguageCode

`func (o *CitationIntelligenceFiltersEcho) SetLanguageCode(v string)`

SetLanguageCode sets LanguageCode field to given value.

### HasLanguageCode

`func (o *CitationIntelligenceFiltersEcho) HasLanguageCode() bool`

HasLanguageCode returns a boolean if a field has been set.

### GetFrom

`func (o *CitationIntelligenceFiltersEcho) GetFrom() string`

GetFrom returns the From field if non-nil, zero value otherwise.

### GetFromOk

`func (o *CitationIntelligenceFiltersEcho) GetFromOk() (*string, bool)`

GetFromOk returns a tuple with the From field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFrom

`func (o *CitationIntelligenceFiltersEcho) SetFrom(v string)`

SetFrom sets From field to given value.

### HasFrom

`func (o *CitationIntelligenceFiltersEcho) HasFrom() bool`

HasFrom returns a boolean if a field has been set.

### GetTo

`func (o *CitationIntelligenceFiltersEcho) GetTo() string`

GetTo returns the To field if non-nil, zero value otherwise.

### GetToOk

`func (o *CitationIntelligenceFiltersEcho) GetToOk() (*string, bool)`

GetToOk returns a tuple with the To field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTo

`func (o *CitationIntelligenceFiltersEcho) SetTo(v string)`

SetTo sets To field to given value.

### HasTo

`func (o *CitationIntelligenceFiltersEcho) HasTo() bool`

HasTo returns a boolean if a field has been set.

### GetKey

`func (o *CitationIntelligenceFiltersEcho) GetKey() string`

GetKey returns the Key field if non-nil, zero value otherwise.

### GetKeyOk

`func (o *CitationIntelligenceFiltersEcho) GetKeyOk() (*string, bool)`

GetKeyOk returns a tuple with the Key field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKey

`func (o *CitationIntelligenceFiltersEcho) SetKey(v string)`

SetKey sets Key field to given value.

### HasKey

`func (o *CitationIntelligenceFiltersEcho) HasKey() bool`

HasKey returns a boolean if a field has been set.

### GetQuery

`func (o *CitationIntelligenceFiltersEcho) GetQuery() string`

GetQuery returns the Query field if non-nil, zero value otherwise.

### GetQueryOk

`func (o *CitationIntelligenceFiltersEcho) GetQueryOk() (*string, bool)`

GetQueryOk returns a tuple with the Query field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuery

`func (o *CitationIntelligenceFiltersEcho) SetQuery(v string)`

SetQuery sets Query field to given value.

### HasQuery

`func (o *CitationIntelligenceFiltersEcho) HasQuery() bool`

HasQuery returns a boolean if a field has been set.

### GetSourceType

`func (o *CitationIntelligenceFiltersEcho) GetSourceType() string`

GetSourceType returns the SourceType field if non-nil, zero value otherwise.

### GetSourceTypeOk

`func (o *CitationIntelligenceFiltersEcho) GetSourceTypeOk() (*string, bool)`

GetSourceTypeOk returns a tuple with the SourceType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSourceType

`func (o *CitationIntelligenceFiltersEcho) SetSourceType(v string)`

SetSourceType sets SourceType field to given value.

### HasSourceType

`func (o *CitationIntelligenceFiltersEcho) HasSourceType() bool`

HasSourceType returns a boolean if a field has been set.

### GetSentiment

`func (o *CitationIntelligenceFiltersEcho) GetSentiment() string`

GetSentiment returns the Sentiment field if non-nil, zero value otherwise.

### GetSentimentOk

`func (o *CitationIntelligenceFiltersEcho) GetSentimentOk() (*string, bool)`

GetSentimentOk returns a tuple with the Sentiment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSentiment

`func (o *CitationIntelligenceFiltersEcho) SetSentiment(v string)`

SetSentiment sets Sentiment field to given value.

### HasSentiment

`func (o *CitationIntelligenceFiltersEcho) HasSentiment() bool`

HasSentiment returns a boolean if a field has been set.

### GetContentGap

`func (o *CitationIntelligenceFiltersEcho) GetContentGap() string`

GetContentGap returns the ContentGap field if non-nil, zero value otherwise.

### GetContentGapOk

`func (o *CitationIntelligenceFiltersEcho) GetContentGapOk() (*string, bool)`

GetContentGapOk returns a tuple with the ContentGap field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContentGap

`func (o *CitationIntelligenceFiltersEcho) SetContentGap(v string)`

SetContentGap sets ContentGap field to given value.

### HasContentGap

`func (o *CitationIntelligenceFiltersEcho) HasContentGap() bool`

HasContentGap returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


