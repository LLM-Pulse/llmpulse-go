# SearchConsoleAiVisibilityGapsResponseDataInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Query** | Pointer to **string** |  | [optional] 
**Impressions** | Pointer to **int32** |  | [optional] 
**Clicks** | Pointer to **int32** |  | [optional] 
**Ctr** | Pointer to **float32** | 0..1 fraction | [optional] 
**Position** | Pointer to **float32** | Impression-weighted average position | [optional] 
**PromptId** | Pointer to **NullableInt32** | The project&#39;s prompt the query matches (see match_type); null when no prompt matches | [optional] 
**Responses** | Pointer to **NullableInt32** | AI answers the matching prompt got in the window over the account&#39;s enabled models; null when no prompt matches | [optional] 
**BrandVisibility** | Pointer to **NullableFloat32** | Brand Visibility of the matching prompt in the window, percent (0-100) of its AI answers that mention the brand, over the account&#39;s enabled models; null when no prompt matches or it has no answer | [optional] 
**MatchType** | Pointer to **NullableString** | How the query matched: prompt (the same text as the prompt) or fan_out (the same text as a search the prompt&#39;s AI answers ran in the window); null when no prompt matches | [optional] 

## Methods

### NewSearchConsoleAiVisibilityGapsResponseDataInner

`func NewSearchConsoleAiVisibilityGapsResponseDataInner() *SearchConsoleAiVisibilityGapsResponseDataInner`

NewSearchConsoleAiVisibilityGapsResponseDataInner instantiates a new SearchConsoleAiVisibilityGapsResponseDataInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSearchConsoleAiVisibilityGapsResponseDataInnerWithDefaults

`func NewSearchConsoleAiVisibilityGapsResponseDataInnerWithDefaults() *SearchConsoleAiVisibilityGapsResponseDataInner`

NewSearchConsoleAiVisibilityGapsResponseDataInnerWithDefaults instantiates a new SearchConsoleAiVisibilityGapsResponseDataInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetQuery

`func (o *SearchConsoleAiVisibilityGapsResponseDataInner) GetQuery() string`

GetQuery returns the Query field if non-nil, zero value otherwise.

### GetQueryOk

`func (o *SearchConsoleAiVisibilityGapsResponseDataInner) GetQueryOk() (*string, bool)`

GetQueryOk returns a tuple with the Query field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuery

`func (o *SearchConsoleAiVisibilityGapsResponseDataInner) SetQuery(v string)`

SetQuery sets Query field to given value.

### HasQuery

`func (o *SearchConsoleAiVisibilityGapsResponseDataInner) HasQuery() bool`

HasQuery returns a boolean if a field has been set.

### GetImpressions

`func (o *SearchConsoleAiVisibilityGapsResponseDataInner) GetImpressions() int32`

GetImpressions returns the Impressions field if non-nil, zero value otherwise.

### GetImpressionsOk

`func (o *SearchConsoleAiVisibilityGapsResponseDataInner) GetImpressionsOk() (*int32, bool)`

GetImpressionsOk returns a tuple with the Impressions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImpressions

`func (o *SearchConsoleAiVisibilityGapsResponseDataInner) SetImpressions(v int32)`

SetImpressions sets Impressions field to given value.

### HasImpressions

`func (o *SearchConsoleAiVisibilityGapsResponseDataInner) HasImpressions() bool`

HasImpressions returns a boolean if a field has been set.

### GetClicks

`func (o *SearchConsoleAiVisibilityGapsResponseDataInner) GetClicks() int32`

GetClicks returns the Clicks field if non-nil, zero value otherwise.

### GetClicksOk

`func (o *SearchConsoleAiVisibilityGapsResponseDataInner) GetClicksOk() (*int32, bool)`

GetClicksOk returns a tuple with the Clicks field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClicks

`func (o *SearchConsoleAiVisibilityGapsResponseDataInner) SetClicks(v int32)`

SetClicks sets Clicks field to given value.

### HasClicks

`func (o *SearchConsoleAiVisibilityGapsResponseDataInner) HasClicks() bool`

HasClicks returns a boolean if a field has been set.

### GetCtr

`func (o *SearchConsoleAiVisibilityGapsResponseDataInner) GetCtr() float32`

GetCtr returns the Ctr field if non-nil, zero value otherwise.

### GetCtrOk

`func (o *SearchConsoleAiVisibilityGapsResponseDataInner) GetCtrOk() (*float32, bool)`

GetCtrOk returns a tuple with the Ctr field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCtr

`func (o *SearchConsoleAiVisibilityGapsResponseDataInner) SetCtr(v float32)`

SetCtr sets Ctr field to given value.

### HasCtr

`func (o *SearchConsoleAiVisibilityGapsResponseDataInner) HasCtr() bool`

HasCtr returns a boolean if a field has been set.

### GetPosition

`func (o *SearchConsoleAiVisibilityGapsResponseDataInner) GetPosition() float32`

GetPosition returns the Position field if non-nil, zero value otherwise.

### GetPositionOk

`func (o *SearchConsoleAiVisibilityGapsResponseDataInner) GetPositionOk() (*float32, bool)`

GetPositionOk returns a tuple with the Position field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPosition

`func (o *SearchConsoleAiVisibilityGapsResponseDataInner) SetPosition(v float32)`

SetPosition sets Position field to given value.

### HasPosition

`func (o *SearchConsoleAiVisibilityGapsResponseDataInner) HasPosition() bool`

HasPosition returns a boolean if a field has been set.

### GetPromptId

`func (o *SearchConsoleAiVisibilityGapsResponseDataInner) GetPromptId() int32`

GetPromptId returns the PromptId field if non-nil, zero value otherwise.

### GetPromptIdOk

`func (o *SearchConsoleAiVisibilityGapsResponseDataInner) GetPromptIdOk() (*int32, bool)`

GetPromptIdOk returns a tuple with the PromptId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPromptId

`func (o *SearchConsoleAiVisibilityGapsResponseDataInner) SetPromptId(v int32)`

SetPromptId sets PromptId field to given value.

### HasPromptId

`func (o *SearchConsoleAiVisibilityGapsResponseDataInner) HasPromptId() bool`

HasPromptId returns a boolean if a field has been set.

### SetPromptIdNil

`func (o *SearchConsoleAiVisibilityGapsResponseDataInner) SetPromptIdNil(b bool)`

 SetPromptIdNil sets the value for PromptId to be an explicit nil

### UnsetPromptId
`func (o *SearchConsoleAiVisibilityGapsResponseDataInner) UnsetPromptId()`

UnsetPromptId ensures that no value is present for PromptId, not even an explicit nil
### GetResponses

`func (o *SearchConsoleAiVisibilityGapsResponseDataInner) GetResponses() int32`

GetResponses returns the Responses field if non-nil, zero value otherwise.

### GetResponsesOk

`func (o *SearchConsoleAiVisibilityGapsResponseDataInner) GetResponsesOk() (*int32, bool)`

GetResponsesOk returns a tuple with the Responses field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResponses

`func (o *SearchConsoleAiVisibilityGapsResponseDataInner) SetResponses(v int32)`

SetResponses sets Responses field to given value.

### HasResponses

`func (o *SearchConsoleAiVisibilityGapsResponseDataInner) HasResponses() bool`

HasResponses returns a boolean if a field has been set.

### SetResponsesNil

`func (o *SearchConsoleAiVisibilityGapsResponseDataInner) SetResponsesNil(b bool)`

 SetResponsesNil sets the value for Responses to be an explicit nil

### UnsetResponses
`func (o *SearchConsoleAiVisibilityGapsResponseDataInner) UnsetResponses()`

UnsetResponses ensures that no value is present for Responses, not even an explicit nil
### GetBrandVisibility

`func (o *SearchConsoleAiVisibilityGapsResponseDataInner) GetBrandVisibility() float32`

GetBrandVisibility returns the BrandVisibility field if non-nil, zero value otherwise.

### GetBrandVisibilityOk

`func (o *SearchConsoleAiVisibilityGapsResponseDataInner) GetBrandVisibilityOk() (*float32, bool)`

GetBrandVisibilityOk returns a tuple with the BrandVisibility field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBrandVisibility

`func (o *SearchConsoleAiVisibilityGapsResponseDataInner) SetBrandVisibility(v float32)`

SetBrandVisibility sets BrandVisibility field to given value.

### HasBrandVisibility

`func (o *SearchConsoleAiVisibilityGapsResponseDataInner) HasBrandVisibility() bool`

HasBrandVisibility returns a boolean if a field has been set.

### SetBrandVisibilityNil

`func (o *SearchConsoleAiVisibilityGapsResponseDataInner) SetBrandVisibilityNil(b bool)`

 SetBrandVisibilityNil sets the value for BrandVisibility to be an explicit nil

### UnsetBrandVisibility
`func (o *SearchConsoleAiVisibilityGapsResponseDataInner) UnsetBrandVisibility()`

UnsetBrandVisibility ensures that no value is present for BrandVisibility, not even an explicit nil
### GetMatchType

`func (o *SearchConsoleAiVisibilityGapsResponseDataInner) GetMatchType() string`

GetMatchType returns the MatchType field if non-nil, zero value otherwise.

### GetMatchTypeOk

`func (o *SearchConsoleAiVisibilityGapsResponseDataInner) GetMatchTypeOk() (*string, bool)`

GetMatchTypeOk returns a tuple with the MatchType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMatchType

`func (o *SearchConsoleAiVisibilityGapsResponseDataInner) SetMatchType(v string)`

SetMatchType sets MatchType field to given value.

### HasMatchType

`func (o *SearchConsoleAiVisibilityGapsResponseDataInner) HasMatchType() bool`

HasMatchType returns a boolean if a field has been set.

### SetMatchTypeNil

`func (o *SearchConsoleAiVisibilityGapsResponseDataInner) SetMatchTypeNil(b bool)`

 SetMatchTypeNil sets the value for MatchType to be an explicit nil

### UnsetMatchType
`func (o *SearchConsoleAiVisibilityGapsResponseDataInner) UnsetMatchType()`

UnsetMatchType ensures that no value is present for MatchType, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


