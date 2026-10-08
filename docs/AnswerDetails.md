# AnswerDetails

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **int32** |  | [optional] 
**PromptId** | Pointer to **int32** |  | [optional] 
**PromptText** | Pointer to **string** |  | [optional] 
**Model** | Pointer to **string** |  | [optional] 
**Response** | Pointer to **NullableString** |  | [optional] 
**ResponseTruncated** | Pointer to **bool** |  | [optional] 
**ExecutedAt** | Pointer to **NullableTime** |  | [optional] 
**DurationMs** | Pointer to **NullableFloat32** | Milliseconds, rounded to one decimal place | [optional] 
**Success** | Pointer to **NullableBool** | Null while the answer is still pending | [optional] 
**NoResult** | Pointer to **bool** | True for a sentinel non-answer (the provider returned nothing after retries); excluded from platform metrics | [optional] 
**FanOutQueries** | Pointer to **[]string** |  | [optional] 
**Mentions** | Pointer to **[]map[string]interface{}** |  | [optional] 
**Citations** | Pointer to **[]map[string]interface{}** |  | [optional] 
**CompetitorMentions** | Pointer to **[]map[string]interface{}** |  | [optional] 
**CompetitorCitations** | Pointer to **[]map[string]interface{}** |  | [optional] 
**Sentiments** | Pointer to **[]map[string]interface{}** |  | [optional] 
**Sources** | Pointer to **[]map[string]interface{}** |  | [optional] 
**ShoppingProducts** | Pointer to **[]map[string]interface{}** |  | [optional] 
**BrandEntities** | Pointer to **[]map[string]interface{}** |  | [optional] 
**LocalBusinesses** | Pointer to **[]map[string]interface{}** |  | [optional] 
**Locale** | Pointer to [**AnswerDetailsLocale**](AnswerDetailsLocale.md) |  | [optional] 
**AppUrl** | Pointer to **string** | Opens this answer in the app. The link names its project, so it opens there for any user with access to that project | [optional] 
**RequestId** | Pointer to **string** |  | [optional] 

## Methods

### NewAnswerDetails

`func NewAnswerDetails() *AnswerDetails`

NewAnswerDetails instantiates a new AnswerDetails object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAnswerDetailsWithDefaults

`func NewAnswerDetailsWithDefaults() *AnswerDetails`

NewAnswerDetailsWithDefaults instantiates a new AnswerDetails object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *AnswerDetails) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *AnswerDetails) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *AnswerDetails) SetId(v int32)`

SetId sets Id field to given value.

### HasId

`func (o *AnswerDetails) HasId() bool`

HasId returns a boolean if a field has been set.

### GetPromptId

`func (o *AnswerDetails) GetPromptId() int32`

GetPromptId returns the PromptId field if non-nil, zero value otherwise.

### GetPromptIdOk

`func (o *AnswerDetails) GetPromptIdOk() (*int32, bool)`

GetPromptIdOk returns a tuple with the PromptId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPromptId

`func (o *AnswerDetails) SetPromptId(v int32)`

SetPromptId sets PromptId field to given value.

### HasPromptId

`func (o *AnswerDetails) HasPromptId() bool`

HasPromptId returns a boolean if a field has been set.

### GetPromptText

`func (o *AnswerDetails) GetPromptText() string`

GetPromptText returns the PromptText field if non-nil, zero value otherwise.

### GetPromptTextOk

`func (o *AnswerDetails) GetPromptTextOk() (*string, bool)`

GetPromptTextOk returns a tuple with the PromptText field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPromptText

`func (o *AnswerDetails) SetPromptText(v string)`

SetPromptText sets PromptText field to given value.

### HasPromptText

`func (o *AnswerDetails) HasPromptText() bool`

HasPromptText returns a boolean if a field has been set.

### GetModel

`func (o *AnswerDetails) GetModel() string`

GetModel returns the Model field if non-nil, zero value otherwise.

### GetModelOk

`func (o *AnswerDetails) GetModelOk() (*string, bool)`

GetModelOk returns a tuple with the Model field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModel

`func (o *AnswerDetails) SetModel(v string)`

SetModel sets Model field to given value.

### HasModel

`func (o *AnswerDetails) HasModel() bool`

HasModel returns a boolean if a field has been set.

### GetResponse

`func (o *AnswerDetails) GetResponse() string`

GetResponse returns the Response field if non-nil, zero value otherwise.

### GetResponseOk

`func (o *AnswerDetails) GetResponseOk() (*string, bool)`

GetResponseOk returns a tuple with the Response field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResponse

`func (o *AnswerDetails) SetResponse(v string)`

SetResponse sets Response field to given value.

### HasResponse

`func (o *AnswerDetails) HasResponse() bool`

HasResponse returns a boolean if a field has been set.

### SetResponseNil

`func (o *AnswerDetails) SetResponseNil(b bool)`

 SetResponseNil sets the value for Response to be an explicit nil

### UnsetResponse
`func (o *AnswerDetails) UnsetResponse()`

UnsetResponse ensures that no value is present for Response, not even an explicit nil
### GetResponseTruncated

`func (o *AnswerDetails) GetResponseTruncated() bool`

GetResponseTruncated returns the ResponseTruncated field if non-nil, zero value otherwise.

### GetResponseTruncatedOk

`func (o *AnswerDetails) GetResponseTruncatedOk() (*bool, bool)`

GetResponseTruncatedOk returns a tuple with the ResponseTruncated field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResponseTruncated

`func (o *AnswerDetails) SetResponseTruncated(v bool)`

SetResponseTruncated sets ResponseTruncated field to given value.

### HasResponseTruncated

`func (o *AnswerDetails) HasResponseTruncated() bool`

HasResponseTruncated returns a boolean if a field has been set.

### GetExecutedAt

`func (o *AnswerDetails) GetExecutedAt() time.Time`

GetExecutedAt returns the ExecutedAt field if non-nil, zero value otherwise.

### GetExecutedAtOk

`func (o *AnswerDetails) GetExecutedAtOk() (*time.Time, bool)`

GetExecutedAtOk returns a tuple with the ExecutedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExecutedAt

`func (o *AnswerDetails) SetExecutedAt(v time.Time)`

SetExecutedAt sets ExecutedAt field to given value.

### HasExecutedAt

`func (o *AnswerDetails) HasExecutedAt() bool`

HasExecutedAt returns a boolean if a field has been set.

### SetExecutedAtNil

`func (o *AnswerDetails) SetExecutedAtNil(b bool)`

 SetExecutedAtNil sets the value for ExecutedAt to be an explicit nil

### UnsetExecutedAt
`func (o *AnswerDetails) UnsetExecutedAt()`

UnsetExecutedAt ensures that no value is present for ExecutedAt, not even an explicit nil
### GetDurationMs

`func (o *AnswerDetails) GetDurationMs() float32`

GetDurationMs returns the DurationMs field if non-nil, zero value otherwise.

### GetDurationMsOk

`func (o *AnswerDetails) GetDurationMsOk() (*float32, bool)`

GetDurationMsOk returns a tuple with the DurationMs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDurationMs

`func (o *AnswerDetails) SetDurationMs(v float32)`

SetDurationMs sets DurationMs field to given value.

### HasDurationMs

`func (o *AnswerDetails) HasDurationMs() bool`

HasDurationMs returns a boolean if a field has been set.

### SetDurationMsNil

`func (o *AnswerDetails) SetDurationMsNil(b bool)`

 SetDurationMsNil sets the value for DurationMs to be an explicit nil

### UnsetDurationMs
`func (o *AnswerDetails) UnsetDurationMs()`

UnsetDurationMs ensures that no value is present for DurationMs, not even an explicit nil
### GetSuccess

`func (o *AnswerDetails) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *AnswerDetails) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *AnswerDetails) SetSuccess(v bool)`

SetSuccess sets Success field to given value.

### HasSuccess

`func (o *AnswerDetails) HasSuccess() bool`

HasSuccess returns a boolean if a field has been set.

### SetSuccessNil

`func (o *AnswerDetails) SetSuccessNil(b bool)`

 SetSuccessNil sets the value for Success to be an explicit nil

### UnsetSuccess
`func (o *AnswerDetails) UnsetSuccess()`

UnsetSuccess ensures that no value is present for Success, not even an explicit nil
### GetNoResult

`func (o *AnswerDetails) GetNoResult() bool`

GetNoResult returns the NoResult field if non-nil, zero value otherwise.

### GetNoResultOk

`func (o *AnswerDetails) GetNoResultOk() (*bool, bool)`

GetNoResultOk returns a tuple with the NoResult field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNoResult

`func (o *AnswerDetails) SetNoResult(v bool)`

SetNoResult sets NoResult field to given value.

### HasNoResult

`func (o *AnswerDetails) HasNoResult() bool`

HasNoResult returns a boolean if a field has been set.

### GetFanOutQueries

`func (o *AnswerDetails) GetFanOutQueries() []string`

GetFanOutQueries returns the FanOutQueries field if non-nil, zero value otherwise.

### GetFanOutQueriesOk

`func (o *AnswerDetails) GetFanOutQueriesOk() (*[]string, bool)`

GetFanOutQueriesOk returns a tuple with the FanOutQueries field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFanOutQueries

`func (o *AnswerDetails) SetFanOutQueries(v []string)`

SetFanOutQueries sets FanOutQueries field to given value.

### HasFanOutQueries

`func (o *AnswerDetails) HasFanOutQueries() bool`

HasFanOutQueries returns a boolean if a field has been set.

### SetFanOutQueriesNil

`func (o *AnswerDetails) SetFanOutQueriesNil(b bool)`

 SetFanOutQueriesNil sets the value for FanOutQueries to be an explicit nil

### UnsetFanOutQueries
`func (o *AnswerDetails) UnsetFanOutQueries()`

UnsetFanOutQueries ensures that no value is present for FanOutQueries, not even an explicit nil
### GetMentions

`func (o *AnswerDetails) GetMentions() []map[string]interface{}`

GetMentions returns the Mentions field if non-nil, zero value otherwise.

### GetMentionsOk

`func (o *AnswerDetails) GetMentionsOk() (*[]map[string]interface{}, bool)`

GetMentionsOk returns a tuple with the Mentions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMentions

`func (o *AnswerDetails) SetMentions(v []map[string]interface{})`

SetMentions sets Mentions field to given value.

### HasMentions

`func (o *AnswerDetails) HasMentions() bool`

HasMentions returns a boolean if a field has been set.

### GetCitations

`func (o *AnswerDetails) GetCitations() []map[string]interface{}`

GetCitations returns the Citations field if non-nil, zero value otherwise.

### GetCitationsOk

`func (o *AnswerDetails) GetCitationsOk() (*[]map[string]interface{}, bool)`

GetCitationsOk returns a tuple with the Citations field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCitations

`func (o *AnswerDetails) SetCitations(v []map[string]interface{})`

SetCitations sets Citations field to given value.

### HasCitations

`func (o *AnswerDetails) HasCitations() bool`

HasCitations returns a boolean if a field has been set.

### GetCompetitorMentions

`func (o *AnswerDetails) GetCompetitorMentions() []map[string]interface{}`

GetCompetitorMentions returns the CompetitorMentions field if non-nil, zero value otherwise.

### GetCompetitorMentionsOk

`func (o *AnswerDetails) GetCompetitorMentionsOk() (*[]map[string]interface{}, bool)`

GetCompetitorMentionsOk returns a tuple with the CompetitorMentions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompetitorMentions

`func (o *AnswerDetails) SetCompetitorMentions(v []map[string]interface{})`

SetCompetitorMentions sets CompetitorMentions field to given value.

### HasCompetitorMentions

`func (o *AnswerDetails) HasCompetitorMentions() bool`

HasCompetitorMentions returns a boolean if a field has been set.

### GetCompetitorCitations

`func (o *AnswerDetails) GetCompetitorCitations() []map[string]interface{}`

GetCompetitorCitations returns the CompetitorCitations field if non-nil, zero value otherwise.

### GetCompetitorCitationsOk

`func (o *AnswerDetails) GetCompetitorCitationsOk() (*[]map[string]interface{}, bool)`

GetCompetitorCitationsOk returns a tuple with the CompetitorCitations field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompetitorCitations

`func (o *AnswerDetails) SetCompetitorCitations(v []map[string]interface{})`

SetCompetitorCitations sets CompetitorCitations field to given value.

### HasCompetitorCitations

`func (o *AnswerDetails) HasCompetitorCitations() bool`

HasCompetitorCitations returns a boolean if a field has been set.

### GetSentiments

`func (o *AnswerDetails) GetSentiments() []map[string]interface{}`

GetSentiments returns the Sentiments field if non-nil, zero value otherwise.

### GetSentimentsOk

`func (o *AnswerDetails) GetSentimentsOk() (*[]map[string]interface{}, bool)`

GetSentimentsOk returns a tuple with the Sentiments field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSentiments

`func (o *AnswerDetails) SetSentiments(v []map[string]interface{})`

SetSentiments sets Sentiments field to given value.

### HasSentiments

`func (o *AnswerDetails) HasSentiments() bool`

HasSentiments returns a boolean if a field has been set.

### GetSources

`func (o *AnswerDetails) GetSources() []map[string]interface{}`

GetSources returns the Sources field if non-nil, zero value otherwise.

### GetSourcesOk

`func (o *AnswerDetails) GetSourcesOk() (*[]map[string]interface{}, bool)`

GetSourcesOk returns a tuple with the Sources field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSources

`func (o *AnswerDetails) SetSources(v []map[string]interface{})`

SetSources sets Sources field to given value.

### HasSources

`func (o *AnswerDetails) HasSources() bool`

HasSources returns a boolean if a field has been set.

### GetShoppingProducts

`func (o *AnswerDetails) GetShoppingProducts() []map[string]interface{}`

GetShoppingProducts returns the ShoppingProducts field if non-nil, zero value otherwise.

### GetShoppingProductsOk

`func (o *AnswerDetails) GetShoppingProductsOk() (*[]map[string]interface{}, bool)`

GetShoppingProductsOk returns a tuple with the ShoppingProducts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShoppingProducts

`func (o *AnswerDetails) SetShoppingProducts(v []map[string]interface{})`

SetShoppingProducts sets ShoppingProducts field to given value.

### HasShoppingProducts

`func (o *AnswerDetails) HasShoppingProducts() bool`

HasShoppingProducts returns a boolean if a field has been set.

### GetBrandEntities

`func (o *AnswerDetails) GetBrandEntities() []map[string]interface{}`

GetBrandEntities returns the BrandEntities field if non-nil, zero value otherwise.

### GetBrandEntitiesOk

`func (o *AnswerDetails) GetBrandEntitiesOk() (*[]map[string]interface{}, bool)`

GetBrandEntitiesOk returns a tuple with the BrandEntities field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBrandEntities

`func (o *AnswerDetails) SetBrandEntities(v []map[string]interface{})`

SetBrandEntities sets BrandEntities field to given value.

### HasBrandEntities

`func (o *AnswerDetails) HasBrandEntities() bool`

HasBrandEntities returns a boolean if a field has been set.

### GetLocalBusinesses

`func (o *AnswerDetails) GetLocalBusinesses() []map[string]interface{}`

GetLocalBusinesses returns the LocalBusinesses field if non-nil, zero value otherwise.

### GetLocalBusinessesOk

`func (o *AnswerDetails) GetLocalBusinessesOk() (*[]map[string]interface{}, bool)`

GetLocalBusinessesOk returns a tuple with the LocalBusinesses field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocalBusinesses

`func (o *AnswerDetails) SetLocalBusinesses(v []map[string]interface{})`

SetLocalBusinesses sets LocalBusinesses field to given value.

### HasLocalBusinesses

`func (o *AnswerDetails) HasLocalBusinesses() bool`

HasLocalBusinesses returns a boolean if a field has been set.

### GetLocale

`func (o *AnswerDetails) GetLocale() AnswerDetailsLocale`

GetLocale returns the Locale field if non-nil, zero value otherwise.

### GetLocaleOk

`func (o *AnswerDetails) GetLocaleOk() (*AnswerDetailsLocale, bool)`

GetLocaleOk returns a tuple with the Locale field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocale

`func (o *AnswerDetails) SetLocale(v AnswerDetailsLocale)`

SetLocale sets Locale field to given value.

### HasLocale

`func (o *AnswerDetails) HasLocale() bool`

HasLocale returns a boolean if a field has been set.

### GetAppUrl

`func (o *AnswerDetails) GetAppUrl() string`

GetAppUrl returns the AppUrl field if non-nil, zero value otherwise.

### GetAppUrlOk

`func (o *AnswerDetails) GetAppUrlOk() (*string, bool)`

GetAppUrlOk returns a tuple with the AppUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAppUrl

`func (o *AnswerDetails) SetAppUrl(v string)`

SetAppUrl sets AppUrl field to given value.

### HasAppUrl

`func (o *AnswerDetails) HasAppUrl() bool`

HasAppUrl returns a boolean if a field has been set.

### GetRequestId

`func (o *AnswerDetails) GetRequestId() string`

GetRequestId returns the RequestId field if non-nil, zero value otherwise.

### GetRequestIdOk

`func (o *AnswerDetails) GetRequestIdOk() (*string, bool)`

GetRequestIdOk returns a tuple with the RequestId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestId

`func (o *AnswerDetails) SetRequestId(v string)`

SetRequestId sets RequestId field to given value.

### HasRequestId

`func (o *AnswerDetails) HasRequestId() bool`

HasRequestId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


