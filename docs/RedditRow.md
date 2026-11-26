# RedditRow

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Subreddit** | Pointer to **NullableString** | Subreddit name without the r/ prefix; null on a thread whose subreddit is unknown | [optional] 
**Author** | Pointer to **NullableString** | Reddit username; null on a thread whose author is unknown | [optional] 
**Url** | Pointer to **string** | The subreddit, author profile or thread URL | [optional] 
**Title** | Pointer to **string** | Thread title, read from the post or its URL (view&#x3D;threads) | [optional] 
**Citations** | Pointer to **int32** | Reddit citations of the row in the window | [optional] 
**UniqueAuthors** | Pointer to **int32** | Distinct authors cited in the subreddit (view&#x3D;subreddits) | [optional] 
**Positive** | Pointer to **int32** | Citations in answers with a positive or very positive sentiment | [optional] 
**Negative** | Pointer to **int32** | Citations in answers with a negative or very negative sentiment | [optional] 
**Neutral** | Pointer to **int32** | Citations in answers with a neutral sentiment | [optional] 
**PositivePct** | Pointer to **NullableFloat32** | positive over the rated citations, 0-100; null when none is rated (view&#x3D;subreddits) | [optional] 
**NegativePct** | Pointer to **NullableFloat32** | negative over the rated citations, 0-100; null when none is rated (view&#x3D;subreddits) | [optional] 
**Yours** | Pointer to **bool** | Whether the account claims the subreddit or author as its own (on threads, either of them) | [optional] 
**Subreddits** | Pointer to **[]string** | The first subreddits the author was cited in (view&#x3D;authors) | [optional] 
**ExtraSubreddits** | Pointer to **int32** | Further subreddits the author was cited in, beyond those listed (view&#x3D;authors) | [optional] 
**Leaning** | Pointer to **string** | positive, negative or neutral, whichever sentiment has more of the author&#39;s citations (view&#x3D;authors) | [optional] 
**Brands** | Pointer to [**[]RedditAuthorBrand**](RedditAuthorBrand.md) | Brands the content of the author&#39;s cited posts names, your own first (view&#x3D;authors) | [optional] 
**SubredditYours** | Pointer to **bool** | Whether the account claims the thread&#39;s subreddit (view&#x3D;threads) | [optional] 
**AuthorYours** | Pointer to **bool** | Whether the account claims the thread&#39;s author (view&#x3D;threads) | [optional] 
**LatestCitedAt** | Pointer to **NullableTime** | The thread&#39;s most recent citation (view&#x3D;threads) | [optional] 
**Upvotes** | Pointer to **interface{}** | Upvotes as the scraped post reports them, a number or a numeric string, or null when unknown (view&#x3D;threads) | [optional] 
**Comments** | Pointer to **interface{}** | Comment count as the scraped post reports it, a number or a numeric string, or null when unknown (view&#x3D;threads) | [optional] 
**AvgPosition** | Pointer to **NullableFloat32** | Average rank of the thread&#39;s citations, 1 &#x3D; first; null when no citation has a visible rank (view&#x3D;threads) | [optional] 
**Sentiment** | Pointer to **NullableString** | The most frequent sentiment of the answers that cite the thread; null when none is rated (view&#x3D;threads) | [optional] 
**Archived** | Pointer to **interface{}** | Whether the thread is archived as the scraped post reports it, usually a boolean, or null when unknown (view&#x3D;threads) | [optional] 
**PostedAt** | Pointer to **NullableTime** | When the thread was posted; null when unknown (view&#x3D;threads) | [optional] 
**Breakdown** | Pointer to **string** | sentiment, model or country (view&#x3D;breakdowns) | [optional] 
**Key** | Pointer to **string** | The slice, a sentiment label, a model or an uppercase country code (view&#x3D;breakdowns) | [optional] 
**Count** | Pointer to **int32** | Reddit citations in the slice (view&#x3D;breakdowns) | [optional] 
**Pct** | Pointer to **float32** | Share of the slice within its breakdown, 0-100 (view&#x3D;breakdowns) | [optional] 

## Methods

### NewRedditRow

`func NewRedditRow() *RedditRow`

NewRedditRow instantiates a new RedditRow object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRedditRowWithDefaults

`func NewRedditRowWithDefaults() *RedditRow`

NewRedditRowWithDefaults instantiates a new RedditRow object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSubreddit

`func (o *RedditRow) GetSubreddit() string`

GetSubreddit returns the Subreddit field if non-nil, zero value otherwise.

### GetSubredditOk

`func (o *RedditRow) GetSubredditOk() (*string, bool)`

GetSubredditOk returns a tuple with the Subreddit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubreddit

`func (o *RedditRow) SetSubreddit(v string)`

SetSubreddit sets Subreddit field to given value.

### HasSubreddit

`func (o *RedditRow) HasSubreddit() bool`

HasSubreddit returns a boolean if a field has been set.

### SetSubredditNil

`func (o *RedditRow) SetSubredditNil(b bool)`

 SetSubredditNil sets the value for Subreddit to be an explicit nil

### UnsetSubreddit
`func (o *RedditRow) UnsetSubreddit()`

UnsetSubreddit ensures that no value is present for Subreddit, not even an explicit nil
### GetAuthor

`func (o *RedditRow) GetAuthor() string`

GetAuthor returns the Author field if non-nil, zero value otherwise.

### GetAuthorOk

`func (o *RedditRow) GetAuthorOk() (*string, bool)`

GetAuthorOk returns a tuple with the Author field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAuthor

`func (o *RedditRow) SetAuthor(v string)`

SetAuthor sets Author field to given value.

### HasAuthor

`func (o *RedditRow) HasAuthor() bool`

HasAuthor returns a boolean if a field has been set.

### SetAuthorNil

`func (o *RedditRow) SetAuthorNil(b bool)`

 SetAuthorNil sets the value for Author to be an explicit nil

### UnsetAuthor
`func (o *RedditRow) UnsetAuthor()`

UnsetAuthor ensures that no value is present for Author, not even an explicit nil
### GetUrl

`func (o *RedditRow) GetUrl() string`

GetUrl returns the Url field if non-nil, zero value otherwise.

### GetUrlOk

`func (o *RedditRow) GetUrlOk() (*string, bool)`

GetUrlOk returns a tuple with the Url field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrl

`func (o *RedditRow) SetUrl(v string)`

SetUrl sets Url field to given value.

### HasUrl

`func (o *RedditRow) HasUrl() bool`

HasUrl returns a boolean if a field has been set.

### GetTitle

`func (o *RedditRow) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *RedditRow) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *RedditRow) SetTitle(v string)`

SetTitle sets Title field to given value.

### HasTitle

`func (o *RedditRow) HasTitle() bool`

HasTitle returns a boolean if a field has been set.

### GetCitations

`func (o *RedditRow) GetCitations() int32`

GetCitations returns the Citations field if non-nil, zero value otherwise.

### GetCitationsOk

`func (o *RedditRow) GetCitationsOk() (*int32, bool)`

GetCitationsOk returns a tuple with the Citations field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCitations

`func (o *RedditRow) SetCitations(v int32)`

SetCitations sets Citations field to given value.

### HasCitations

`func (o *RedditRow) HasCitations() bool`

HasCitations returns a boolean if a field has been set.

### GetUniqueAuthors

`func (o *RedditRow) GetUniqueAuthors() int32`

GetUniqueAuthors returns the UniqueAuthors field if non-nil, zero value otherwise.

### GetUniqueAuthorsOk

`func (o *RedditRow) GetUniqueAuthorsOk() (*int32, bool)`

GetUniqueAuthorsOk returns a tuple with the UniqueAuthors field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUniqueAuthors

`func (o *RedditRow) SetUniqueAuthors(v int32)`

SetUniqueAuthors sets UniqueAuthors field to given value.

### HasUniqueAuthors

`func (o *RedditRow) HasUniqueAuthors() bool`

HasUniqueAuthors returns a boolean if a field has been set.

### GetPositive

`func (o *RedditRow) GetPositive() int32`

GetPositive returns the Positive field if non-nil, zero value otherwise.

### GetPositiveOk

`func (o *RedditRow) GetPositiveOk() (*int32, bool)`

GetPositiveOk returns a tuple with the Positive field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPositive

`func (o *RedditRow) SetPositive(v int32)`

SetPositive sets Positive field to given value.

### HasPositive

`func (o *RedditRow) HasPositive() bool`

HasPositive returns a boolean if a field has been set.

### GetNegative

`func (o *RedditRow) GetNegative() int32`

GetNegative returns the Negative field if non-nil, zero value otherwise.

### GetNegativeOk

`func (o *RedditRow) GetNegativeOk() (*int32, bool)`

GetNegativeOk returns a tuple with the Negative field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNegative

`func (o *RedditRow) SetNegative(v int32)`

SetNegative sets Negative field to given value.

### HasNegative

`func (o *RedditRow) HasNegative() bool`

HasNegative returns a boolean if a field has been set.

### GetNeutral

`func (o *RedditRow) GetNeutral() int32`

GetNeutral returns the Neutral field if non-nil, zero value otherwise.

### GetNeutralOk

`func (o *RedditRow) GetNeutralOk() (*int32, bool)`

GetNeutralOk returns a tuple with the Neutral field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNeutral

`func (o *RedditRow) SetNeutral(v int32)`

SetNeutral sets Neutral field to given value.

### HasNeutral

`func (o *RedditRow) HasNeutral() bool`

HasNeutral returns a boolean if a field has been set.

### GetPositivePct

`func (o *RedditRow) GetPositivePct() float32`

GetPositivePct returns the PositivePct field if non-nil, zero value otherwise.

### GetPositivePctOk

`func (o *RedditRow) GetPositivePctOk() (*float32, bool)`

GetPositivePctOk returns a tuple with the PositivePct field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPositivePct

`func (o *RedditRow) SetPositivePct(v float32)`

SetPositivePct sets PositivePct field to given value.

### HasPositivePct

`func (o *RedditRow) HasPositivePct() bool`

HasPositivePct returns a boolean if a field has been set.

### SetPositivePctNil

`func (o *RedditRow) SetPositivePctNil(b bool)`

 SetPositivePctNil sets the value for PositivePct to be an explicit nil

### UnsetPositivePct
`func (o *RedditRow) UnsetPositivePct()`

UnsetPositivePct ensures that no value is present for PositivePct, not even an explicit nil
### GetNegativePct

`func (o *RedditRow) GetNegativePct() float32`

GetNegativePct returns the NegativePct field if non-nil, zero value otherwise.

### GetNegativePctOk

`func (o *RedditRow) GetNegativePctOk() (*float32, bool)`

GetNegativePctOk returns a tuple with the NegativePct field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNegativePct

`func (o *RedditRow) SetNegativePct(v float32)`

SetNegativePct sets NegativePct field to given value.

### HasNegativePct

`func (o *RedditRow) HasNegativePct() bool`

HasNegativePct returns a boolean if a field has been set.

### SetNegativePctNil

`func (o *RedditRow) SetNegativePctNil(b bool)`

 SetNegativePctNil sets the value for NegativePct to be an explicit nil

### UnsetNegativePct
`func (o *RedditRow) UnsetNegativePct()`

UnsetNegativePct ensures that no value is present for NegativePct, not even an explicit nil
### GetYours

`func (o *RedditRow) GetYours() bool`

GetYours returns the Yours field if non-nil, zero value otherwise.

### GetYoursOk

`func (o *RedditRow) GetYoursOk() (*bool, bool)`

GetYoursOk returns a tuple with the Yours field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetYours

`func (o *RedditRow) SetYours(v bool)`

SetYours sets Yours field to given value.

### HasYours

`func (o *RedditRow) HasYours() bool`

HasYours returns a boolean if a field has been set.

### GetSubreddits

`func (o *RedditRow) GetSubreddits() []string`

GetSubreddits returns the Subreddits field if non-nil, zero value otherwise.

### GetSubredditsOk

`func (o *RedditRow) GetSubredditsOk() (*[]string, bool)`

GetSubredditsOk returns a tuple with the Subreddits field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubreddits

`func (o *RedditRow) SetSubreddits(v []string)`

SetSubreddits sets Subreddits field to given value.

### HasSubreddits

`func (o *RedditRow) HasSubreddits() bool`

HasSubreddits returns a boolean if a field has been set.

### GetExtraSubreddits

`func (o *RedditRow) GetExtraSubreddits() int32`

GetExtraSubreddits returns the ExtraSubreddits field if non-nil, zero value otherwise.

### GetExtraSubredditsOk

`func (o *RedditRow) GetExtraSubredditsOk() (*int32, bool)`

GetExtraSubredditsOk returns a tuple with the ExtraSubreddits field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExtraSubreddits

`func (o *RedditRow) SetExtraSubreddits(v int32)`

SetExtraSubreddits sets ExtraSubreddits field to given value.

### HasExtraSubreddits

`func (o *RedditRow) HasExtraSubreddits() bool`

HasExtraSubreddits returns a boolean if a field has been set.

### GetLeaning

`func (o *RedditRow) GetLeaning() string`

GetLeaning returns the Leaning field if non-nil, zero value otherwise.

### GetLeaningOk

`func (o *RedditRow) GetLeaningOk() (*string, bool)`

GetLeaningOk returns a tuple with the Leaning field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLeaning

`func (o *RedditRow) SetLeaning(v string)`

SetLeaning sets Leaning field to given value.

### HasLeaning

`func (o *RedditRow) HasLeaning() bool`

HasLeaning returns a boolean if a field has been set.

### GetBrands

`func (o *RedditRow) GetBrands() []RedditAuthorBrand`

GetBrands returns the Brands field if non-nil, zero value otherwise.

### GetBrandsOk

`func (o *RedditRow) GetBrandsOk() (*[]RedditAuthorBrand, bool)`

GetBrandsOk returns a tuple with the Brands field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBrands

`func (o *RedditRow) SetBrands(v []RedditAuthorBrand)`

SetBrands sets Brands field to given value.

### HasBrands

`func (o *RedditRow) HasBrands() bool`

HasBrands returns a boolean if a field has been set.

### GetSubredditYours

`func (o *RedditRow) GetSubredditYours() bool`

GetSubredditYours returns the SubredditYours field if non-nil, zero value otherwise.

### GetSubredditYoursOk

`func (o *RedditRow) GetSubredditYoursOk() (*bool, bool)`

GetSubredditYoursOk returns a tuple with the SubredditYours field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubredditYours

`func (o *RedditRow) SetSubredditYours(v bool)`

SetSubredditYours sets SubredditYours field to given value.

### HasSubredditYours

`func (o *RedditRow) HasSubredditYours() bool`

HasSubredditYours returns a boolean if a field has been set.

### GetAuthorYours

`func (o *RedditRow) GetAuthorYours() bool`

GetAuthorYours returns the AuthorYours field if non-nil, zero value otherwise.

### GetAuthorYoursOk

`func (o *RedditRow) GetAuthorYoursOk() (*bool, bool)`

GetAuthorYoursOk returns a tuple with the AuthorYours field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAuthorYours

`func (o *RedditRow) SetAuthorYours(v bool)`

SetAuthorYours sets AuthorYours field to given value.

### HasAuthorYours

`func (o *RedditRow) HasAuthorYours() bool`

HasAuthorYours returns a boolean if a field has been set.

### GetLatestCitedAt

`func (o *RedditRow) GetLatestCitedAt() time.Time`

GetLatestCitedAt returns the LatestCitedAt field if non-nil, zero value otherwise.

### GetLatestCitedAtOk

`func (o *RedditRow) GetLatestCitedAtOk() (*time.Time, bool)`

GetLatestCitedAtOk returns a tuple with the LatestCitedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLatestCitedAt

`func (o *RedditRow) SetLatestCitedAt(v time.Time)`

SetLatestCitedAt sets LatestCitedAt field to given value.

### HasLatestCitedAt

`func (o *RedditRow) HasLatestCitedAt() bool`

HasLatestCitedAt returns a boolean if a field has been set.

### SetLatestCitedAtNil

`func (o *RedditRow) SetLatestCitedAtNil(b bool)`

 SetLatestCitedAtNil sets the value for LatestCitedAt to be an explicit nil

### UnsetLatestCitedAt
`func (o *RedditRow) UnsetLatestCitedAt()`

UnsetLatestCitedAt ensures that no value is present for LatestCitedAt, not even an explicit nil
### GetUpvotes

`func (o *RedditRow) GetUpvotes() interface{}`

GetUpvotes returns the Upvotes field if non-nil, zero value otherwise.

### GetUpvotesOk

`func (o *RedditRow) GetUpvotesOk() (*interface{}, bool)`

GetUpvotesOk returns a tuple with the Upvotes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpvotes

`func (o *RedditRow) SetUpvotes(v interface{})`

SetUpvotes sets Upvotes field to given value.

### HasUpvotes

`func (o *RedditRow) HasUpvotes() bool`

HasUpvotes returns a boolean if a field has been set.

### SetUpvotesNil

`func (o *RedditRow) SetUpvotesNil(b bool)`

 SetUpvotesNil sets the value for Upvotes to be an explicit nil

### UnsetUpvotes
`func (o *RedditRow) UnsetUpvotes()`

UnsetUpvotes ensures that no value is present for Upvotes, not even an explicit nil
### GetComments

`func (o *RedditRow) GetComments() interface{}`

GetComments returns the Comments field if non-nil, zero value otherwise.

### GetCommentsOk

`func (o *RedditRow) GetCommentsOk() (*interface{}, bool)`

GetCommentsOk returns a tuple with the Comments field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComments

`func (o *RedditRow) SetComments(v interface{})`

SetComments sets Comments field to given value.

### HasComments

`func (o *RedditRow) HasComments() bool`

HasComments returns a boolean if a field has been set.

### SetCommentsNil

`func (o *RedditRow) SetCommentsNil(b bool)`

 SetCommentsNil sets the value for Comments to be an explicit nil

### UnsetComments
`func (o *RedditRow) UnsetComments()`

UnsetComments ensures that no value is present for Comments, not even an explicit nil
### GetAvgPosition

`func (o *RedditRow) GetAvgPosition() float32`

GetAvgPosition returns the AvgPosition field if non-nil, zero value otherwise.

### GetAvgPositionOk

`func (o *RedditRow) GetAvgPositionOk() (*float32, bool)`

GetAvgPositionOk returns a tuple with the AvgPosition field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAvgPosition

`func (o *RedditRow) SetAvgPosition(v float32)`

SetAvgPosition sets AvgPosition field to given value.

### HasAvgPosition

`func (o *RedditRow) HasAvgPosition() bool`

HasAvgPosition returns a boolean if a field has been set.

### SetAvgPositionNil

`func (o *RedditRow) SetAvgPositionNil(b bool)`

 SetAvgPositionNil sets the value for AvgPosition to be an explicit nil

### UnsetAvgPosition
`func (o *RedditRow) UnsetAvgPosition()`

UnsetAvgPosition ensures that no value is present for AvgPosition, not even an explicit nil
### GetSentiment

`func (o *RedditRow) GetSentiment() string`

GetSentiment returns the Sentiment field if non-nil, zero value otherwise.

### GetSentimentOk

`func (o *RedditRow) GetSentimentOk() (*string, bool)`

GetSentimentOk returns a tuple with the Sentiment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSentiment

`func (o *RedditRow) SetSentiment(v string)`

SetSentiment sets Sentiment field to given value.

### HasSentiment

`func (o *RedditRow) HasSentiment() bool`

HasSentiment returns a boolean if a field has been set.

### SetSentimentNil

`func (o *RedditRow) SetSentimentNil(b bool)`

 SetSentimentNil sets the value for Sentiment to be an explicit nil

### UnsetSentiment
`func (o *RedditRow) UnsetSentiment()`

UnsetSentiment ensures that no value is present for Sentiment, not even an explicit nil
### GetArchived

`func (o *RedditRow) GetArchived() interface{}`

GetArchived returns the Archived field if non-nil, zero value otherwise.

### GetArchivedOk

`func (o *RedditRow) GetArchivedOk() (*interface{}, bool)`

GetArchivedOk returns a tuple with the Archived field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetArchived

`func (o *RedditRow) SetArchived(v interface{})`

SetArchived sets Archived field to given value.

### HasArchived

`func (o *RedditRow) HasArchived() bool`

HasArchived returns a boolean if a field has been set.

### SetArchivedNil

`func (o *RedditRow) SetArchivedNil(b bool)`

 SetArchivedNil sets the value for Archived to be an explicit nil

### UnsetArchived
`func (o *RedditRow) UnsetArchived()`

UnsetArchived ensures that no value is present for Archived, not even an explicit nil
### GetPostedAt

`func (o *RedditRow) GetPostedAt() time.Time`

GetPostedAt returns the PostedAt field if non-nil, zero value otherwise.

### GetPostedAtOk

`func (o *RedditRow) GetPostedAtOk() (*time.Time, bool)`

GetPostedAtOk returns a tuple with the PostedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPostedAt

`func (o *RedditRow) SetPostedAt(v time.Time)`

SetPostedAt sets PostedAt field to given value.

### HasPostedAt

`func (o *RedditRow) HasPostedAt() bool`

HasPostedAt returns a boolean if a field has been set.

### SetPostedAtNil

`func (o *RedditRow) SetPostedAtNil(b bool)`

 SetPostedAtNil sets the value for PostedAt to be an explicit nil

### UnsetPostedAt
`func (o *RedditRow) UnsetPostedAt()`

UnsetPostedAt ensures that no value is present for PostedAt, not even an explicit nil
### GetBreakdown

`func (o *RedditRow) GetBreakdown() string`

GetBreakdown returns the Breakdown field if non-nil, zero value otherwise.

### GetBreakdownOk

`func (o *RedditRow) GetBreakdownOk() (*string, bool)`

GetBreakdownOk returns a tuple with the Breakdown field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBreakdown

`func (o *RedditRow) SetBreakdown(v string)`

SetBreakdown sets Breakdown field to given value.

### HasBreakdown

`func (o *RedditRow) HasBreakdown() bool`

HasBreakdown returns a boolean if a field has been set.

### GetKey

`func (o *RedditRow) GetKey() string`

GetKey returns the Key field if non-nil, zero value otherwise.

### GetKeyOk

`func (o *RedditRow) GetKeyOk() (*string, bool)`

GetKeyOk returns a tuple with the Key field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKey

`func (o *RedditRow) SetKey(v string)`

SetKey sets Key field to given value.

### HasKey

`func (o *RedditRow) HasKey() bool`

HasKey returns a boolean if a field has been set.

### GetCount

`func (o *RedditRow) GetCount() int32`

GetCount returns the Count field if non-nil, zero value otherwise.

### GetCountOk

`func (o *RedditRow) GetCountOk() (*int32, bool)`

GetCountOk returns a tuple with the Count field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCount

`func (o *RedditRow) SetCount(v int32)`

SetCount sets Count field to given value.

### HasCount

`func (o *RedditRow) HasCount() bool`

HasCount returns a boolean if a field has been set.

### GetPct

`func (o *RedditRow) GetPct() float32`

GetPct returns the Pct field if non-nil, zero value otherwise.

### GetPctOk

`func (o *RedditRow) GetPctOk() (*float32, bool)`

GetPctOk returns a tuple with the Pct field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPct

`func (o *RedditRow) SetPct(v float32)`

SetPct sets Pct field to given value.

### HasPct

`func (o *RedditRow) HasPct() bool`

HasPct returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


