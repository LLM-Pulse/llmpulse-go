# UpdateOwnedMediaProfilesRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**YoutubeChannelUrl** | Pointer to **NullableString** | The main YouTube channel URL (@handle, /channel/UC..., /c/... or /user/...). An empty string or null clears it | [optional] 
**AppStoreUrl** | Pointer to **NullableString** | The App Store app URL, with its id number. An empty string or null clears it | [optional] 
**GooglePlayUrl** | Pointer to **NullableString** | The Google Play app URL, or its package name (com.acme.app). An empty string or null clears it | [optional] 
**InstagramProfileUrl** | Pointer to **NullableString** | The main Instagram profile URL. An empty string or null clears it | [optional] 
**FacebookPageUrl** | Pointer to **NullableString** | The main Facebook Page URL. An empty string or null clears it | [optional] 
**TiktokProfileUrl** | Pointer to **NullableString** | The main TikTok profile URL. An empty string or null clears it | [optional] 
**LinkedinCompanyUrl** | Pointer to **NullableString** | The main LinkedIn Company Page URL (/company/...). An empty string or null clears it | [optional] 
**YoutubeExtraProfileUrls** | Pointer to **[]string** | FULL replacement list of extra YouTube channel URLs (at most 10); [] clears it | [optional] 
**MobileAppsExtraProfileUrls** | Pointer to **[]string** | FULL replacement list of extra App Store or Google Play app URLs (at most 10); [] clears it | [optional] 
**InstagramExtraProfileUrls** | Pointer to **[]string** | FULL replacement list of extra Instagram profile URLs (at most 10); [] clears it | [optional] 
**FacebookExtraProfileUrls** | Pointer to **[]string** | FULL replacement list of extra Facebook Page URLs (at most 10); [] clears it | [optional] 
**TiktokExtraProfileUrls** | Pointer to **[]string** | FULL replacement list of extra TikTok profile URLs (at most 10); [] clears it | [optional] 
**LinkedinExtraProfileUrls** | Pointer to **[]string** | FULL replacement list of extra LinkedIn Company Page URLs (at most 10); [] clears it | [optional] 
**RedditSubreddits** | Pointer to **[]string** | FULL replacement list (at most 10) of subreddit names the brand owns, without r/; [] clears it | [optional] 
**RedditUsernames** | Pointer to **[]string** | FULL replacement list (at most 25) of Reddit usernames the brand owns, without u/; [] clears it | [optional] 

## Methods

### NewUpdateOwnedMediaProfilesRequest

`func NewUpdateOwnedMediaProfilesRequest() *UpdateOwnedMediaProfilesRequest`

NewUpdateOwnedMediaProfilesRequest instantiates a new UpdateOwnedMediaProfilesRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUpdateOwnedMediaProfilesRequestWithDefaults

`func NewUpdateOwnedMediaProfilesRequestWithDefaults() *UpdateOwnedMediaProfilesRequest`

NewUpdateOwnedMediaProfilesRequestWithDefaults instantiates a new UpdateOwnedMediaProfilesRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetYoutubeChannelUrl

`func (o *UpdateOwnedMediaProfilesRequest) GetYoutubeChannelUrl() string`

GetYoutubeChannelUrl returns the YoutubeChannelUrl field if non-nil, zero value otherwise.

### GetYoutubeChannelUrlOk

`func (o *UpdateOwnedMediaProfilesRequest) GetYoutubeChannelUrlOk() (*string, bool)`

GetYoutubeChannelUrlOk returns a tuple with the YoutubeChannelUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetYoutubeChannelUrl

`func (o *UpdateOwnedMediaProfilesRequest) SetYoutubeChannelUrl(v string)`

SetYoutubeChannelUrl sets YoutubeChannelUrl field to given value.

### HasYoutubeChannelUrl

`func (o *UpdateOwnedMediaProfilesRequest) HasYoutubeChannelUrl() bool`

HasYoutubeChannelUrl returns a boolean if a field has been set.

### SetYoutubeChannelUrlNil

`func (o *UpdateOwnedMediaProfilesRequest) SetYoutubeChannelUrlNil(b bool)`

 SetYoutubeChannelUrlNil sets the value for YoutubeChannelUrl to be an explicit nil

### UnsetYoutubeChannelUrl
`func (o *UpdateOwnedMediaProfilesRequest) UnsetYoutubeChannelUrl()`

UnsetYoutubeChannelUrl ensures that no value is present for YoutubeChannelUrl, not even an explicit nil
### GetAppStoreUrl

`func (o *UpdateOwnedMediaProfilesRequest) GetAppStoreUrl() string`

GetAppStoreUrl returns the AppStoreUrl field if non-nil, zero value otherwise.

### GetAppStoreUrlOk

`func (o *UpdateOwnedMediaProfilesRequest) GetAppStoreUrlOk() (*string, bool)`

GetAppStoreUrlOk returns a tuple with the AppStoreUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAppStoreUrl

`func (o *UpdateOwnedMediaProfilesRequest) SetAppStoreUrl(v string)`

SetAppStoreUrl sets AppStoreUrl field to given value.

### HasAppStoreUrl

`func (o *UpdateOwnedMediaProfilesRequest) HasAppStoreUrl() bool`

HasAppStoreUrl returns a boolean if a field has been set.

### SetAppStoreUrlNil

`func (o *UpdateOwnedMediaProfilesRequest) SetAppStoreUrlNil(b bool)`

 SetAppStoreUrlNil sets the value for AppStoreUrl to be an explicit nil

### UnsetAppStoreUrl
`func (o *UpdateOwnedMediaProfilesRequest) UnsetAppStoreUrl()`

UnsetAppStoreUrl ensures that no value is present for AppStoreUrl, not even an explicit nil
### GetGooglePlayUrl

`func (o *UpdateOwnedMediaProfilesRequest) GetGooglePlayUrl() string`

GetGooglePlayUrl returns the GooglePlayUrl field if non-nil, zero value otherwise.

### GetGooglePlayUrlOk

`func (o *UpdateOwnedMediaProfilesRequest) GetGooglePlayUrlOk() (*string, bool)`

GetGooglePlayUrlOk returns a tuple with the GooglePlayUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGooglePlayUrl

`func (o *UpdateOwnedMediaProfilesRequest) SetGooglePlayUrl(v string)`

SetGooglePlayUrl sets GooglePlayUrl field to given value.

### HasGooglePlayUrl

`func (o *UpdateOwnedMediaProfilesRequest) HasGooglePlayUrl() bool`

HasGooglePlayUrl returns a boolean if a field has been set.

### SetGooglePlayUrlNil

`func (o *UpdateOwnedMediaProfilesRequest) SetGooglePlayUrlNil(b bool)`

 SetGooglePlayUrlNil sets the value for GooglePlayUrl to be an explicit nil

### UnsetGooglePlayUrl
`func (o *UpdateOwnedMediaProfilesRequest) UnsetGooglePlayUrl()`

UnsetGooglePlayUrl ensures that no value is present for GooglePlayUrl, not even an explicit nil
### GetInstagramProfileUrl

`func (o *UpdateOwnedMediaProfilesRequest) GetInstagramProfileUrl() string`

GetInstagramProfileUrl returns the InstagramProfileUrl field if non-nil, zero value otherwise.

### GetInstagramProfileUrlOk

`func (o *UpdateOwnedMediaProfilesRequest) GetInstagramProfileUrlOk() (*string, bool)`

GetInstagramProfileUrlOk returns a tuple with the InstagramProfileUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInstagramProfileUrl

`func (o *UpdateOwnedMediaProfilesRequest) SetInstagramProfileUrl(v string)`

SetInstagramProfileUrl sets InstagramProfileUrl field to given value.

### HasInstagramProfileUrl

`func (o *UpdateOwnedMediaProfilesRequest) HasInstagramProfileUrl() bool`

HasInstagramProfileUrl returns a boolean if a field has been set.

### SetInstagramProfileUrlNil

`func (o *UpdateOwnedMediaProfilesRequest) SetInstagramProfileUrlNil(b bool)`

 SetInstagramProfileUrlNil sets the value for InstagramProfileUrl to be an explicit nil

### UnsetInstagramProfileUrl
`func (o *UpdateOwnedMediaProfilesRequest) UnsetInstagramProfileUrl()`

UnsetInstagramProfileUrl ensures that no value is present for InstagramProfileUrl, not even an explicit nil
### GetFacebookPageUrl

`func (o *UpdateOwnedMediaProfilesRequest) GetFacebookPageUrl() string`

GetFacebookPageUrl returns the FacebookPageUrl field if non-nil, zero value otherwise.

### GetFacebookPageUrlOk

`func (o *UpdateOwnedMediaProfilesRequest) GetFacebookPageUrlOk() (*string, bool)`

GetFacebookPageUrlOk returns a tuple with the FacebookPageUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFacebookPageUrl

`func (o *UpdateOwnedMediaProfilesRequest) SetFacebookPageUrl(v string)`

SetFacebookPageUrl sets FacebookPageUrl field to given value.

### HasFacebookPageUrl

`func (o *UpdateOwnedMediaProfilesRequest) HasFacebookPageUrl() bool`

HasFacebookPageUrl returns a boolean if a field has been set.

### SetFacebookPageUrlNil

`func (o *UpdateOwnedMediaProfilesRequest) SetFacebookPageUrlNil(b bool)`

 SetFacebookPageUrlNil sets the value for FacebookPageUrl to be an explicit nil

### UnsetFacebookPageUrl
`func (o *UpdateOwnedMediaProfilesRequest) UnsetFacebookPageUrl()`

UnsetFacebookPageUrl ensures that no value is present for FacebookPageUrl, not even an explicit nil
### GetTiktokProfileUrl

`func (o *UpdateOwnedMediaProfilesRequest) GetTiktokProfileUrl() string`

GetTiktokProfileUrl returns the TiktokProfileUrl field if non-nil, zero value otherwise.

### GetTiktokProfileUrlOk

`func (o *UpdateOwnedMediaProfilesRequest) GetTiktokProfileUrlOk() (*string, bool)`

GetTiktokProfileUrlOk returns a tuple with the TiktokProfileUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTiktokProfileUrl

`func (o *UpdateOwnedMediaProfilesRequest) SetTiktokProfileUrl(v string)`

SetTiktokProfileUrl sets TiktokProfileUrl field to given value.

### HasTiktokProfileUrl

`func (o *UpdateOwnedMediaProfilesRequest) HasTiktokProfileUrl() bool`

HasTiktokProfileUrl returns a boolean if a field has been set.

### SetTiktokProfileUrlNil

`func (o *UpdateOwnedMediaProfilesRequest) SetTiktokProfileUrlNil(b bool)`

 SetTiktokProfileUrlNil sets the value for TiktokProfileUrl to be an explicit nil

### UnsetTiktokProfileUrl
`func (o *UpdateOwnedMediaProfilesRequest) UnsetTiktokProfileUrl()`

UnsetTiktokProfileUrl ensures that no value is present for TiktokProfileUrl, not even an explicit nil
### GetLinkedinCompanyUrl

`func (o *UpdateOwnedMediaProfilesRequest) GetLinkedinCompanyUrl() string`

GetLinkedinCompanyUrl returns the LinkedinCompanyUrl field if non-nil, zero value otherwise.

### GetLinkedinCompanyUrlOk

`func (o *UpdateOwnedMediaProfilesRequest) GetLinkedinCompanyUrlOk() (*string, bool)`

GetLinkedinCompanyUrlOk returns a tuple with the LinkedinCompanyUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLinkedinCompanyUrl

`func (o *UpdateOwnedMediaProfilesRequest) SetLinkedinCompanyUrl(v string)`

SetLinkedinCompanyUrl sets LinkedinCompanyUrl field to given value.

### HasLinkedinCompanyUrl

`func (o *UpdateOwnedMediaProfilesRequest) HasLinkedinCompanyUrl() bool`

HasLinkedinCompanyUrl returns a boolean if a field has been set.

### SetLinkedinCompanyUrlNil

`func (o *UpdateOwnedMediaProfilesRequest) SetLinkedinCompanyUrlNil(b bool)`

 SetLinkedinCompanyUrlNil sets the value for LinkedinCompanyUrl to be an explicit nil

### UnsetLinkedinCompanyUrl
`func (o *UpdateOwnedMediaProfilesRequest) UnsetLinkedinCompanyUrl()`

UnsetLinkedinCompanyUrl ensures that no value is present for LinkedinCompanyUrl, not even an explicit nil
### GetYoutubeExtraProfileUrls

`func (o *UpdateOwnedMediaProfilesRequest) GetYoutubeExtraProfileUrls() []string`

GetYoutubeExtraProfileUrls returns the YoutubeExtraProfileUrls field if non-nil, zero value otherwise.

### GetYoutubeExtraProfileUrlsOk

`func (o *UpdateOwnedMediaProfilesRequest) GetYoutubeExtraProfileUrlsOk() (*[]string, bool)`

GetYoutubeExtraProfileUrlsOk returns a tuple with the YoutubeExtraProfileUrls field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetYoutubeExtraProfileUrls

`func (o *UpdateOwnedMediaProfilesRequest) SetYoutubeExtraProfileUrls(v []string)`

SetYoutubeExtraProfileUrls sets YoutubeExtraProfileUrls field to given value.

### HasYoutubeExtraProfileUrls

`func (o *UpdateOwnedMediaProfilesRequest) HasYoutubeExtraProfileUrls() bool`

HasYoutubeExtraProfileUrls returns a boolean if a field has been set.

### GetMobileAppsExtraProfileUrls

`func (o *UpdateOwnedMediaProfilesRequest) GetMobileAppsExtraProfileUrls() []string`

GetMobileAppsExtraProfileUrls returns the MobileAppsExtraProfileUrls field if non-nil, zero value otherwise.

### GetMobileAppsExtraProfileUrlsOk

`func (o *UpdateOwnedMediaProfilesRequest) GetMobileAppsExtraProfileUrlsOk() (*[]string, bool)`

GetMobileAppsExtraProfileUrlsOk returns a tuple with the MobileAppsExtraProfileUrls field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMobileAppsExtraProfileUrls

`func (o *UpdateOwnedMediaProfilesRequest) SetMobileAppsExtraProfileUrls(v []string)`

SetMobileAppsExtraProfileUrls sets MobileAppsExtraProfileUrls field to given value.

### HasMobileAppsExtraProfileUrls

`func (o *UpdateOwnedMediaProfilesRequest) HasMobileAppsExtraProfileUrls() bool`

HasMobileAppsExtraProfileUrls returns a boolean if a field has been set.

### GetInstagramExtraProfileUrls

`func (o *UpdateOwnedMediaProfilesRequest) GetInstagramExtraProfileUrls() []string`

GetInstagramExtraProfileUrls returns the InstagramExtraProfileUrls field if non-nil, zero value otherwise.

### GetInstagramExtraProfileUrlsOk

`func (o *UpdateOwnedMediaProfilesRequest) GetInstagramExtraProfileUrlsOk() (*[]string, bool)`

GetInstagramExtraProfileUrlsOk returns a tuple with the InstagramExtraProfileUrls field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInstagramExtraProfileUrls

`func (o *UpdateOwnedMediaProfilesRequest) SetInstagramExtraProfileUrls(v []string)`

SetInstagramExtraProfileUrls sets InstagramExtraProfileUrls field to given value.

### HasInstagramExtraProfileUrls

`func (o *UpdateOwnedMediaProfilesRequest) HasInstagramExtraProfileUrls() bool`

HasInstagramExtraProfileUrls returns a boolean if a field has been set.

### GetFacebookExtraProfileUrls

`func (o *UpdateOwnedMediaProfilesRequest) GetFacebookExtraProfileUrls() []string`

GetFacebookExtraProfileUrls returns the FacebookExtraProfileUrls field if non-nil, zero value otherwise.

### GetFacebookExtraProfileUrlsOk

`func (o *UpdateOwnedMediaProfilesRequest) GetFacebookExtraProfileUrlsOk() (*[]string, bool)`

GetFacebookExtraProfileUrlsOk returns a tuple with the FacebookExtraProfileUrls field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFacebookExtraProfileUrls

`func (o *UpdateOwnedMediaProfilesRequest) SetFacebookExtraProfileUrls(v []string)`

SetFacebookExtraProfileUrls sets FacebookExtraProfileUrls field to given value.

### HasFacebookExtraProfileUrls

`func (o *UpdateOwnedMediaProfilesRequest) HasFacebookExtraProfileUrls() bool`

HasFacebookExtraProfileUrls returns a boolean if a field has been set.

### GetTiktokExtraProfileUrls

`func (o *UpdateOwnedMediaProfilesRequest) GetTiktokExtraProfileUrls() []string`

GetTiktokExtraProfileUrls returns the TiktokExtraProfileUrls field if non-nil, zero value otherwise.

### GetTiktokExtraProfileUrlsOk

`func (o *UpdateOwnedMediaProfilesRequest) GetTiktokExtraProfileUrlsOk() (*[]string, bool)`

GetTiktokExtraProfileUrlsOk returns a tuple with the TiktokExtraProfileUrls field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTiktokExtraProfileUrls

`func (o *UpdateOwnedMediaProfilesRequest) SetTiktokExtraProfileUrls(v []string)`

SetTiktokExtraProfileUrls sets TiktokExtraProfileUrls field to given value.

### HasTiktokExtraProfileUrls

`func (o *UpdateOwnedMediaProfilesRequest) HasTiktokExtraProfileUrls() bool`

HasTiktokExtraProfileUrls returns a boolean if a field has been set.

### GetLinkedinExtraProfileUrls

`func (o *UpdateOwnedMediaProfilesRequest) GetLinkedinExtraProfileUrls() []string`

GetLinkedinExtraProfileUrls returns the LinkedinExtraProfileUrls field if non-nil, zero value otherwise.

### GetLinkedinExtraProfileUrlsOk

`func (o *UpdateOwnedMediaProfilesRequest) GetLinkedinExtraProfileUrlsOk() (*[]string, bool)`

GetLinkedinExtraProfileUrlsOk returns a tuple with the LinkedinExtraProfileUrls field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLinkedinExtraProfileUrls

`func (o *UpdateOwnedMediaProfilesRequest) SetLinkedinExtraProfileUrls(v []string)`

SetLinkedinExtraProfileUrls sets LinkedinExtraProfileUrls field to given value.

### HasLinkedinExtraProfileUrls

`func (o *UpdateOwnedMediaProfilesRequest) HasLinkedinExtraProfileUrls() bool`

HasLinkedinExtraProfileUrls returns a boolean if a field has been set.

### GetRedditSubreddits

`func (o *UpdateOwnedMediaProfilesRequest) GetRedditSubreddits() []string`

GetRedditSubreddits returns the RedditSubreddits field if non-nil, zero value otherwise.

### GetRedditSubredditsOk

`func (o *UpdateOwnedMediaProfilesRequest) GetRedditSubredditsOk() (*[]string, bool)`

GetRedditSubredditsOk returns a tuple with the RedditSubreddits field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRedditSubreddits

`func (o *UpdateOwnedMediaProfilesRequest) SetRedditSubreddits(v []string)`

SetRedditSubreddits sets RedditSubreddits field to given value.

### HasRedditSubreddits

`func (o *UpdateOwnedMediaProfilesRequest) HasRedditSubreddits() bool`

HasRedditSubreddits returns a boolean if a field has been set.

### GetRedditUsernames

`func (o *UpdateOwnedMediaProfilesRequest) GetRedditUsernames() []string`

GetRedditUsernames returns the RedditUsernames field if non-nil, zero value otherwise.

### GetRedditUsernamesOk

`func (o *UpdateOwnedMediaProfilesRequest) GetRedditUsernamesOk() (*[]string, bool)`

GetRedditUsernamesOk returns a tuple with the RedditUsernames field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRedditUsernames

`func (o *UpdateOwnedMediaProfilesRequest) SetRedditUsernames(v []string)`

SetRedditUsernames sets RedditUsernames field to given value.

### HasRedditUsernames

`func (o *UpdateOwnedMediaProfilesRequest) HasRedditUsernames() bool`

HasRedditUsernames returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


