# CitationPageMentionsMentionsInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **int32** |  | 
**MatchedKey** | **string** | The name that matched | 
**Snippet** | **NullableString** |  | 
**StartOffset** | **int32** |  | 
**EndOffset** | **int32** |  | 
**Position** | **NullableInt32** |  | 
**ActorType** | **string** | project or competitor | 
**CompetitorId** | **NullableInt32** | Null for the project | 
**ActorName** | **NullableString** |  | 
**ActorDomain** | **NullableString** | The competitor&#39;s domain, or the project&#39;s URL | 

## Methods

### NewCitationPageMentionsMentionsInner

`func NewCitationPageMentionsMentionsInner(id int32, matchedKey string, snippet NullableString, startOffset int32, endOffset int32, position NullableInt32, actorType string, competitorId NullableInt32, actorName NullableString, actorDomain NullableString, ) *CitationPageMentionsMentionsInner`

NewCitationPageMentionsMentionsInner instantiates a new CitationPageMentionsMentionsInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCitationPageMentionsMentionsInnerWithDefaults

`func NewCitationPageMentionsMentionsInnerWithDefaults() *CitationPageMentionsMentionsInner`

NewCitationPageMentionsMentionsInnerWithDefaults instantiates a new CitationPageMentionsMentionsInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *CitationPageMentionsMentionsInner) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *CitationPageMentionsMentionsInner) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *CitationPageMentionsMentionsInner) SetId(v int32)`

SetId sets Id field to given value.


### GetMatchedKey

`func (o *CitationPageMentionsMentionsInner) GetMatchedKey() string`

GetMatchedKey returns the MatchedKey field if non-nil, zero value otherwise.

### GetMatchedKeyOk

`func (o *CitationPageMentionsMentionsInner) GetMatchedKeyOk() (*string, bool)`

GetMatchedKeyOk returns a tuple with the MatchedKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMatchedKey

`func (o *CitationPageMentionsMentionsInner) SetMatchedKey(v string)`

SetMatchedKey sets MatchedKey field to given value.


### GetSnippet

`func (o *CitationPageMentionsMentionsInner) GetSnippet() string`

GetSnippet returns the Snippet field if non-nil, zero value otherwise.

### GetSnippetOk

`func (o *CitationPageMentionsMentionsInner) GetSnippetOk() (*string, bool)`

GetSnippetOk returns a tuple with the Snippet field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSnippet

`func (o *CitationPageMentionsMentionsInner) SetSnippet(v string)`

SetSnippet sets Snippet field to given value.


### SetSnippetNil

`func (o *CitationPageMentionsMentionsInner) SetSnippetNil(b bool)`

 SetSnippetNil sets the value for Snippet to be an explicit nil

### UnsetSnippet
`func (o *CitationPageMentionsMentionsInner) UnsetSnippet()`

UnsetSnippet ensures that no value is present for Snippet, not even an explicit nil
### GetStartOffset

`func (o *CitationPageMentionsMentionsInner) GetStartOffset() int32`

GetStartOffset returns the StartOffset field if non-nil, zero value otherwise.

### GetStartOffsetOk

`func (o *CitationPageMentionsMentionsInner) GetStartOffsetOk() (*int32, bool)`

GetStartOffsetOk returns a tuple with the StartOffset field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartOffset

`func (o *CitationPageMentionsMentionsInner) SetStartOffset(v int32)`

SetStartOffset sets StartOffset field to given value.


### GetEndOffset

`func (o *CitationPageMentionsMentionsInner) GetEndOffset() int32`

GetEndOffset returns the EndOffset field if non-nil, zero value otherwise.

### GetEndOffsetOk

`func (o *CitationPageMentionsMentionsInner) GetEndOffsetOk() (*int32, bool)`

GetEndOffsetOk returns a tuple with the EndOffset field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEndOffset

`func (o *CitationPageMentionsMentionsInner) SetEndOffset(v int32)`

SetEndOffset sets EndOffset field to given value.


### GetPosition

`func (o *CitationPageMentionsMentionsInner) GetPosition() int32`

GetPosition returns the Position field if non-nil, zero value otherwise.

### GetPositionOk

`func (o *CitationPageMentionsMentionsInner) GetPositionOk() (*int32, bool)`

GetPositionOk returns a tuple with the Position field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPosition

`func (o *CitationPageMentionsMentionsInner) SetPosition(v int32)`

SetPosition sets Position field to given value.


### SetPositionNil

`func (o *CitationPageMentionsMentionsInner) SetPositionNil(b bool)`

 SetPositionNil sets the value for Position to be an explicit nil

### UnsetPosition
`func (o *CitationPageMentionsMentionsInner) UnsetPosition()`

UnsetPosition ensures that no value is present for Position, not even an explicit nil
### GetActorType

`func (o *CitationPageMentionsMentionsInner) GetActorType() string`

GetActorType returns the ActorType field if non-nil, zero value otherwise.

### GetActorTypeOk

`func (o *CitationPageMentionsMentionsInner) GetActorTypeOk() (*string, bool)`

GetActorTypeOk returns a tuple with the ActorType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActorType

`func (o *CitationPageMentionsMentionsInner) SetActorType(v string)`

SetActorType sets ActorType field to given value.


### GetCompetitorId

`func (o *CitationPageMentionsMentionsInner) GetCompetitorId() int32`

GetCompetitorId returns the CompetitorId field if non-nil, zero value otherwise.

### GetCompetitorIdOk

`func (o *CitationPageMentionsMentionsInner) GetCompetitorIdOk() (*int32, bool)`

GetCompetitorIdOk returns a tuple with the CompetitorId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompetitorId

`func (o *CitationPageMentionsMentionsInner) SetCompetitorId(v int32)`

SetCompetitorId sets CompetitorId field to given value.


### SetCompetitorIdNil

`func (o *CitationPageMentionsMentionsInner) SetCompetitorIdNil(b bool)`

 SetCompetitorIdNil sets the value for CompetitorId to be an explicit nil

### UnsetCompetitorId
`func (o *CitationPageMentionsMentionsInner) UnsetCompetitorId()`

UnsetCompetitorId ensures that no value is present for CompetitorId, not even an explicit nil
### GetActorName

`func (o *CitationPageMentionsMentionsInner) GetActorName() string`

GetActorName returns the ActorName field if non-nil, zero value otherwise.

### GetActorNameOk

`func (o *CitationPageMentionsMentionsInner) GetActorNameOk() (*string, bool)`

GetActorNameOk returns a tuple with the ActorName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActorName

`func (o *CitationPageMentionsMentionsInner) SetActorName(v string)`

SetActorName sets ActorName field to given value.


### SetActorNameNil

`func (o *CitationPageMentionsMentionsInner) SetActorNameNil(b bool)`

 SetActorNameNil sets the value for ActorName to be an explicit nil

### UnsetActorName
`func (o *CitationPageMentionsMentionsInner) UnsetActorName()`

UnsetActorName ensures that no value is present for ActorName, not even an explicit nil
### GetActorDomain

`func (o *CitationPageMentionsMentionsInner) GetActorDomain() string`

GetActorDomain returns the ActorDomain field if non-nil, zero value otherwise.

### GetActorDomainOk

`func (o *CitationPageMentionsMentionsInner) GetActorDomainOk() (*string, bool)`

GetActorDomainOk returns a tuple with the ActorDomain field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActorDomain

`func (o *CitationPageMentionsMentionsInner) SetActorDomain(v string)`

SetActorDomain sets ActorDomain field to given value.


### SetActorDomainNil

`func (o *CitationPageMentionsMentionsInner) SetActorDomainNil(b bool)`

 SetActorDomainNil sets the value for ActorDomain to be an explicit nil

### UnsetActorDomain
`func (o *CitationPageMentionsMentionsInner) UnsetActorDomain()`

UnsetActorDomain ensures that no value is present for ActorDomain, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


