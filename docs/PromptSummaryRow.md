# PromptSummaryRow

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**PromptId** | Pointer to **int32** |  | [optional] 
**PromptText** | Pointer to **string** |  | [optional] 
**Model** | Pointer to **string** | Only present when breakdown&#x3D;model | [optional] 
**Responses** | Pointer to **int32** |  | [optional] 
**Mentions** | Pointer to **int32** |  | [optional] 
**Citations** | Pointer to **int32** |  | [optional] 
**Visibility** | Pointer to **float32** |  | [optional] 
**MentionRate** | Pointer to **float32** |  | [optional] 
**CitationRate** | Pointer to **float32** |  | [optional] 
**AvgMentionPosition** | Pointer to **NullableFloat32** |  | [optional] 
**AvgPosition** | Pointer to **NullableFloat32** |  | [optional] 
**AppUrl** | Pointer to **string** | Opens this prompt in the app. The link names its project, so it opens there for any user with access to that project | [optional] 
**CountryCode** | Pointer to **NullableString** | Country of the prompt, as in /dimensions/prompts | [optional] 
**LanguageCode** | Pointer to **NullableString** | Language of the prompt, as in /dimensions/prompts | [optional] 
**PromptType** | Pointer to **NullableString** | Search intent: informational, navigational, commercial or transactional. Null until the prompt is classified | [optional] 
**BrandKind** | Pointer to **NullableString** | Brand focus: brand, brand_other or non_brand. Null until the prompt is classified | [optional] 
**Tags** | Pointer to [**[]TagRef**](TagRef.md) | Every tag the prompt belongs to | [optional] 
**SentimentResponses** | Pointer to **int32** | Responses in the window with a sentiment verdict for the brand, the base of the sentiment percentages (deduplicated like the sentiment timeseries) | [optional] 
**SentimentVeryPositive** | Pointer to **NullableFloat32** | Percentage (0-100) of sentiment_responses whose brand verdict is very positive; null when sentiment_responses is 0 | [optional] 
**SentimentPositive** | Pointer to **NullableFloat32** | Percentage (0-100) of sentiment_responses whose brand verdict is positive; null when sentiment_responses is 0 | [optional] 
**SentimentNeutral** | Pointer to **NullableFloat32** | Percentage (0-100) of sentiment_responses whose brand verdict is neutral; null when sentiment_responses is 0 | [optional] 
**SentimentNegative** | Pointer to **NullableFloat32** | Percentage (0-100) of sentiment_responses whose brand verdict is negative; null when sentiment_responses is 0 | [optional] 
**SentimentVeryNegative** | Pointer to **NullableFloat32** | Percentage (0-100) of sentiment_responses whose brand verdict is very negative; null when sentiment_responses is 0 | [optional] 
**NetSentiment** | Pointer to **NullableFloat32** | Positive minus negative percentages (-100 to 100), neutral counted in the base; null when sentiment_responses is 0 | [optional] 

## Methods

### NewPromptSummaryRow

`func NewPromptSummaryRow() *PromptSummaryRow`

NewPromptSummaryRow instantiates a new PromptSummaryRow object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPromptSummaryRowWithDefaults

`func NewPromptSummaryRowWithDefaults() *PromptSummaryRow`

NewPromptSummaryRowWithDefaults instantiates a new PromptSummaryRow object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPromptId

`func (o *PromptSummaryRow) GetPromptId() int32`

GetPromptId returns the PromptId field if non-nil, zero value otherwise.

### GetPromptIdOk

`func (o *PromptSummaryRow) GetPromptIdOk() (*int32, bool)`

GetPromptIdOk returns a tuple with the PromptId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPromptId

`func (o *PromptSummaryRow) SetPromptId(v int32)`

SetPromptId sets PromptId field to given value.

### HasPromptId

`func (o *PromptSummaryRow) HasPromptId() bool`

HasPromptId returns a boolean if a field has been set.

### GetPromptText

`func (o *PromptSummaryRow) GetPromptText() string`

GetPromptText returns the PromptText field if non-nil, zero value otherwise.

### GetPromptTextOk

`func (o *PromptSummaryRow) GetPromptTextOk() (*string, bool)`

GetPromptTextOk returns a tuple with the PromptText field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPromptText

`func (o *PromptSummaryRow) SetPromptText(v string)`

SetPromptText sets PromptText field to given value.

### HasPromptText

`func (o *PromptSummaryRow) HasPromptText() bool`

HasPromptText returns a boolean if a field has been set.

### GetModel

`func (o *PromptSummaryRow) GetModel() string`

GetModel returns the Model field if non-nil, zero value otherwise.

### GetModelOk

`func (o *PromptSummaryRow) GetModelOk() (*string, bool)`

GetModelOk returns a tuple with the Model field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModel

`func (o *PromptSummaryRow) SetModel(v string)`

SetModel sets Model field to given value.

### HasModel

`func (o *PromptSummaryRow) HasModel() bool`

HasModel returns a boolean if a field has been set.

### GetResponses

`func (o *PromptSummaryRow) GetResponses() int32`

GetResponses returns the Responses field if non-nil, zero value otherwise.

### GetResponsesOk

`func (o *PromptSummaryRow) GetResponsesOk() (*int32, bool)`

GetResponsesOk returns a tuple with the Responses field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResponses

`func (o *PromptSummaryRow) SetResponses(v int32)`

SetResponses sets Responses field to given value.

### HasResponses

`func (o *PromptSummaryRow) HasResponses() bool`

HasResponses returns a boolean if a field has been set.

### GetMentions

`func (o *PromptSummaryRow) GetMentions() int32`

GetMentions returns the Mentions field if non-nil, zero value otherwise.

### GetMentionsOk

`func (o *PromptSummaryRow) GetMentionsOk() (*int32, bool)`

GetMentionsOk returns a tuple with the Mentions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMentions

`func (o *PromptSummaryRow) SetMentions(v int32)`

SetMentions sets Mentions field to given value.

### HasMentions

`func (o *PromptSummaryRow) HasMentions() bool`

HasMentions returns a boolean if a field has been set.

### GetCitations

`func (o *PromptSummaryRow) GetCitations() int32`

GetCitations returns the Citations field if non-nil, zero value otherwise.

### GetCitationsOk

`func (o *PromptSummaryRow) GetCitationsOk() (*int32, bool)`

GetCitationsOk returns a tuple with the Citations field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCitations

`func (o *PromptSummaryRow) SetCitations(v int32)`

SetCitations sets Citations field to given value.

### HasCitations

`func (o *PromptSummaryRow) HasCitations() bool`

HasCitations returns a boolean if a field has been set.

### GetVisibility

`func (o *PromptSummaryRow) GetVisibility() float32`

GetVisibility returns the Visibility field if non-nil, zero value otherwise.

### GetVisibilityOk

`func (o *PromptSummaryRow) GetVisibilityOk() (*float32, bool)`

GetVisibilityOk returns a tuple with the Visibility field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVisibility

`func (o *PromptSummaryRow) SetVisibility(v float32)`

SetVisibility sets Visibility field to given value.

### HasVisibility

`func (o *PromptSummaryRow) HasVisibility() bool`

HasVisibility returns a boolean if a field has been set.

### GetMentionRate

`func (o *PromptSummaryRow) GetMentionRate() float32`

GetMentionRate returns the MentionRate field if non-nil, zero value otherwise.

### GetMentionRateOk

`func (o *PromptSummaryRow) GetMentionRateOk() (*float32, bool)`

GetMentionRateOk returns a tuple with the MentionRate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMentionRate

`func (o *PromptSummaryRow) SetMentionRate(v float32)`

SetMentionRate sets MentionRate field to given value.

### HasMentionRate

`func (o *PromptSummaryRow) HasMentionRate() bool`

HasMentionRate returns a boolean if a field has been set.

### GetCitationRate

`func (o *PromptSummaryRow) GetCitationRate() float32`

GetCitationRate returns the CitationRate field if non-nil, zero value otherwise.

### GetCitationRateOk

`func (o *PromptSummaryRow) GetCitationRateOk() (*float32, bool)`

GetCitationRateOk returns a tuple with the CitationRate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCitationRate

`func (o *PromptSummaryRow) SetCitationRate(v float32)`

SetCitationRate sets CitationRate field to given value.

### HasCitationRate

`func (o *PromptSummaryRow) HasCitationRate() bool`

HasCitationRate returns a boolean if a field has been set.

### GetAvgMentionPosition

`func (o *PromptSummaryRow) GetAvgMentionPosition() float32`

GetAvgMentionPosition returns the AvgMentionPosition field if non-nil, zero value otherwise.

### GetAvgMentionPositionOk

`func (o *PromptSummaryRow) GetAvgMentionPositionOk() (*float32, bool)`

GetAvgMentionPositionOk returns a tuple with the AvgMentionPosition field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAvgMentionPosition

`func (o *PromptSummaryRow) SetAvgMentionPosition(v float32)`

SetAvgMentionPosition sets AvgMentionPosition field to given value.

### HasAvgMentionPosition

`func (o *PromptSummaryRow) HasAvgMentionPosition() bool`

HasAvgMentionPosition returns a boolean if a field has been set.

### SetAvgMentionPositionNil

`func (o *PromptSummaryRow) SetAvgMentionPositionNil(b bool)`

 SetAvgMentionPositionNil sets the value for AvgMentionPosition to be an explicit nil

### UnsetAvgMentionPosition
`func (o *PromptSummaryRow) UnsetAvgMentionPosition()`

UnsetAvgMentionPosition ensures that no value is present for AvgMentionPosition, not even an explicit nil
### GetAvgPosition

`func (o *PromptSummaryRow) GetAvgPosition() float32`

GetAvgPosition returns the AvgPosition field if non-nil, zero value otherwise.

### GetAvgPositionOk

`func (o *PromptSummaryRow) GetAvgPositionOk() (*float32, bool)`

GetAvgPositionOk returns a tuple with the AvgPosition field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAvgPosition

`func (o *PromptSummaryRow) SetAvgPosition(v float32)`

SetAvgPosition sets AvgPosition field to given value.

### HasAvgPosition

`func (o *PromptSummaryRow) HasAvgPosition() bool`

HasAvgPosition returns a boolean if a field has been set.

### SetAvgPositionNil

`func (o *PromptSummaryRow) SetAvgPositionNil(b bool)`

 SetAvgPositionNil sets the value for AvgPosition to be an explicit nil

### UnsetAvgPosition
`func (o *PromptSummaryRow) UnsetAvgPosition()`

UnsetAvgPosition ensures that no value is present for AvgPosition, not even an explicit nil
### GetAppUrl

`func (o *PromptSummaryRow) GetAppUrl() string`

GetAppUrl returns the AppUrl field if non-nil, zero value otherwise.

### GetAppUrlOk

`func (o *PromptSummaryRow) GetAppUrlOk() (*string, bool)`

GetAppUrlOk returns a tuple with the AppUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAppUrl

`func (o *PromptSummaryRow) SetAppUrl(v string)`

SetAppUrl sets AppUrl field to given value.

### HasAppUrl

`func (o *PromptSummaryRow) HasAppUrl() bool`

HasAppUrl returns a boolean if a field has been set.

### GetCountryCode

`func (o *PromptSummaryRow) GetCountryCode() string`

GetCountryCode returns the CountryCode field if non-nil, zero value otherwise.

### GetCountryCodeOk

`func (o *PromptSummaryRow) GetCountryCodeOk() (*string, bool)`

GetCountryCodeOk returns a tuple with the CountryCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountryCode

`func (o *PromptSummaryRow) SetCountryCode(v string)`

SetCountryCode sets CountryCode field to given value.

### HasCountryCode

`func (o *PromptSummaryRow) HasCountryCode() bool`

HasCountryCode returns a boolean if a field has been set.

### SetCountryCodeNil

`func (o *PromptSummaryRow) SetCountryCodeNil(b bool)`

 SetCountryCodeNil sets the value for CountryCode to be an explicit nil

### UnsetCountryCode
`func (o *PromptSummaryRow) UnsetCountryCode()`

UnsetCountryCode ensures that no value is present for CountryCode, not even an explicit nil
### GetLanguageCode

`func (o *PromptSummaryRow) GetLanguageCode() string`

GetLanguageCode returns the LanguageCode field if non-nil, zero value otherwise.

### GetLanguageCodeOk

`func (o *PromptSummaryRow) GetLanguageCodeOk() (*string, bool)`

GetLanguageCodeOk returns a tuple with the LanguageCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLanguageCode

`func (o *PromptSummaryRow) SetLanguageCode(v string)`

SetLanguageCode sets LanguageCode field to given value.

### HasLanguageCode

`func (o *PromptSummaryRow) HasLanguageCode() bool`

HasLanguageCode returns a boolean if a field has been set.

### SetLanguageCodeNil

`func (o *PromptSummaryRow) SetLanguageCodeNil(b bool)`

 SetLanguageCodeNil sets the value for LanguageCode to be an explicit nil

### UnsetLanguageCode
`func (o *PromptSummaryRow) UnsetLanguageCode()`

UnsetLanguageCode ensures that no value is present for LanguageCode, not even an explicit nil
### GetPromptType

`func (o *PromptSummaryRow) GetPromptType() string`

GetPromptType returns the PromptType field if non-nil, zero value otherwise.

### GetPromptTypeOk

`func (o *PromptSummaryRow) GetPromptTypeOk() (*string, bool)`

GetPromptTypeOk returns a tuple with the PromptType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPromptType

`func (o *PromptSummaryRow) SetPromptType(v string)`

SetPromptType sets PromptType field to given value.

### HasPromptType

`func (o *PromptSummaryRow) HasPromptType() bool`

HasPromptType returns a boolean if a field has been set.

### SetPromptTypeNil

`func (o *PromptSummaryRow) SetPromptTypeNil(b bool)`

 SetPromptTypeNil sets the value for PromptType to be an explicit nil

### UnsetPromptType
`func (o *PromptSummaryRow) UnsetPromptType()`

UnsetPromptType ensures that no value is present for PromptType, not even an explicit nil
### GetBrandKind

`func (o *PromptSummaryRow) GetBrandKind() string`

GetBrandKind returns the BrandKind field if non-nil, zero value otherwise.

### GetBrandKindOk

`func (o *PromptSummaryRow) GetBrandKindOk() (*string, bool)`

GetBrandKindOk returns a tuple with the BrandKind field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBrandKind

`func (o *PromptSummaryRow) SetBrandKind(v string)`

SetBrandKind sets BrandKind field to given value.

### HasBrandKind

`func (o *PromptSummaryRow) HasBrandKind() bool`

HasBrandKind returns a boolean if a field has been set.

### SetBrandKindNil

`func (o *PromptSummaryRow) SetBrandKindNil(b bool)`

 SetBrandKindNil sets the value for BrandKind to be an explicit nil

### UnsetBrandKind
`func (o *PromptSummaryRow) UnsetBrandKind()`

UnsetBrandKind ensures that no value is present for BrandKind, not even an explicit nil
### GetTags

`func (o *PromptSummaryRow) GetTags() []TagRef`

GetTags returns the Tags field if non-nil, zero value otherwise.

### GetTagsOk

`func (o *PromptSummaryRow) GetTagsOk() (*[]TagRef, bool)`

GetTagsOk returns a tuple with the Tags field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTags

`func (o *PromptSummaryRow) SetTags(v []TagRef)`

SetTags sets Tags field to given value.

### HasTags

`func (o *PromptSummaryRow) HasTags() bool`

HasTags returns a boolean if a field has been set.

### GetSentimentResponses

`func (o *PromptSummaryRow) GetSentimentResponses() int32`

GetSentimentResponses returns the SentimentResponses field if non-nil, zero value otherwise.

### GetSentimentResponsesOk

`func (o *PromptSummaryRow) GetSentimentResponsesOk() (*int32, bool)`

GetSentimentResponsesOk returns a tuple with the SentimentResponses field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSentimentResponses

`func (o *PromptSummaryRow) SetSentimentResponses(v int32)`

SetSentimentResponses sets SentimentResponses field to given value.

### HasSentimentResponses

`func (o *PromptSummaryRow) HasSentimentResponses() bool`

HasSentimentResponses returns a boolean if a field has been set.

### GetSentimentVeryPositive

`func (o *PromptSummaryRow) GetSentimentVeryPositive() float32`

GetSentimentVeryPositive returns the SentimentVeryPositive field if non-nil, zero value otherwise.

### GetSentimentVeryPositiveOk

`func (o *PromptSummaryRow) GetSentimentVeryPositiveOk() (*float32, bool)`

GetSentimentVeryPositiveOk returns a tuple with the SentimentVeryPositive field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSentimentVeryPositive

`func (o *PromptSummaryRow) SetSentimentVeryPositive(v float32)`

SetSentimentVeryPositive sets SentimentVeryPositive field to given value.

### HasSentimentVeryPositive

`func (o *PromptSummaryRow) HasSentimentVeryPositive() bool`

HasSentimentVeryPositive returns a boolean if a field has been set.

### SetSentimentVeryPositiveNil

`func (o *PromptSummaryRow) SetSentimentVeryPositiveNil(b bool)`

 SetSentimentVeryPositiveNil sets the value for SentimentVeryPositive to be an explicit nil

### UnsetSentimentVeryPositive
`func (o *PromptSummaryRow) UnsetSentimentVeryPositive()`

UnsetSentimentVeryPositive ensures that no value is present for SentimentVeryPositive, not even an explicit nil
### GetSentimentPositive

`func (o *PromptSummaryRow) GetSentimentPositive() float32`

GetSentimentPositive returns the SentimentPositive field if non-nil, zero value otherwise.

### GetSentimentPositiveOk

`func (o *PromptSummaryRow) GetSentimentPositiveOk() (*float32, bool)`

GetSentimentPositiveOk returns a tuple with the SentimentPositive field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSentimentPositive

`func (o *PromptSummaryRow) SetSentimentPositive(v float32)`

SetSentimentPositive sets SentimentPositive field to given value.

### HasSentimentPositive

`func (o *PromptSummaryRow) HasSentimentPositive() bool`

HasSentimentPositive returns a boolean if a field has been set.

### SetSentimentPositiveNil

`func (o *PromptSummaryRow) SetSentimentPositiveNil(b bool)`

 SetSentimentPositiveNil sets the value for SentimentPositive to be an explicit nil

### UnsetSentimentPositive
`func (o *PromptSummaryRow) UnsetSentimentPositive()`

UnsetSentimentPositive ensures that no value is present for SentimentPositive, not even an explicit nil
### GetSentimentNeutral

`func (o *PromptSummaryRow) GetSentimentNeutral() float32`

GetSentimentNeutral returns the SentimentNeutral field if non-nil, zero value otherwise.

### GetSentimentNeutralOk

`func (o *PromptSummaryRow) GetSentimentNeutralOk() (*float32, bool)`

GetSentimentNeutralOk returns a tuple with the SentimentNeutral field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSentimentNeutral

`func (o *PromptSummaryRow) SetSentimentNeutral(v float32)`

SetSentimentNeutral sets SentimentNeutral field to given value.

### HasSentimentNeutral

`func (o *PromptSummaryRow) HasSentimentNeutral() bool`

HasSentimentNeutral returns a boolean if a field has been set.

### SetSentimentNeutralNil

`func (o *PromptSummaryRow) SetSentimentNeutralNil(b bool)`

 SetSentimentNeutralNil sets the value for SentimentNeutral to be an explicit nil

### UnsetSentimentNeutral
`func (o *PromptSummaryRow) UnsetSentimentNeutral()`

UnsetSentimentNeutral ensures that no value is present for SentimentNeutral, not even an explicit nil
### GetSentimentNegative

`func (o *PromptSummaryRow) GetSentimentNegative() float32`

GetSentimentNegative returns the SentimentNegative field if non-nil, zero value otherwise.

### GetSentimentNegativeOk

`func (o *PromptSummaryRow) GetSentimentNegativeOk() (*float32, bool)`

GetSentimentNegativeOk returns a tuple with the SentimentNegative field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSentimentNegative

`func (o *PromptSummaryRow) SetSentimentNegative(v float32)`

SetSentimentNegative sets SentimentNegative field to given value.

### HasSentimentNegative

`func (o *PromptSummaryRow) HasSentimentNegative() bool`

HasSentimentNegative returns a boolean if a field has been set.

### SetSentimentNegativeNil

`func (o *PromptSummaryRow) SetSentimentNegativeNil(b bool)`

 SetSentimentNegativeNil sets the value for SentimentNegative to be an explicit nil

### UnsetSentimentNegative
`func (o *PromptSummaryRow) UnsetSentimentNegative()`

UnsetSentimentNegative ensures that no value is present for SentimentNegative, not even an explicit nil
### GetSentimentVeryNegative

`func (o *PromptSummaryRow) GetSentimentVeryNegative() float32`

GetSentimentVeryNegative returns the SentimentVeryNegative field if non-nil, zero value otherwise.

### GetSentimentVeryNegativeOk

`func (o *PromptSummaryRow) GetSentimentVeryNegativeOk() (*float32, bool)`

GetSentimentVeryNegativeOk returns a tuple with the SentimentVeryNegative field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSentimentVeryNegative

`func (o *PromptSummaryRow) SetSentimentVeryNegative(v float32)`

SetSentimentVeryNegative sets SentimentVeryNegative field to given value.

### HasSentimentVeryNegative

`func (o *PromptSummaryRow) HasSentimentVeryNegative() bool`

HasSentimentVeryNegative returns a boolean if a field has been set.

### SetSentimentVeryNegativeNil

`func (o *PromptSummaryRow) SetSentimentVeryNegativeNil(b bool)`

 SetSentimentVeryNegativeNil sets the value for SentimentVeryNegative to be an explicit nil

### UnsetSentimentVeryNegative
`func (o *PromptSummaryRow) UnsetSentimentVeryNegative()`

UnsetSentimentVeryNegative ensures that no value is present for SentimentVeryNegative, not even an explicit nil
### GetNetSentiment

`func (o *PromptSummaryRow) GetNetSentiment() float32`

GetNetSentiment returns the NetSentiment field if non-nil, zero value otherwise.

### GetNetSentimentOk

`func (o *PromptSummaryRow) GetNetSentimentOk() (*float32, bool)`

GetNetSentimentOk returns a tuple with the NetSentiment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNetSentiment

`func (o *PromptSummaryRow) SetNetSentiment(v float32)`

SetNetSentiment sets NetSentiment field to given value.

### HasNetSentiment

`func (o *PromptSummaryRow) HasNetSentiment() bool`

HasNetSentiment returns a boolean if a field has been set.

### SetNetSentimentNil

`func (o *PromptSummaryRow) SetNetSentimentNil(b bool)`

 SetNetSentimentNil sets the value for NetSentiment to be an explicit nil

### UnsetNetSentiment
`func (o *PromptSummaryRow) UnsetNetSentiment()`

UnsetNetSentiment ensures that no value is present for NetSentiment, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


