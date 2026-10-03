# LocalBusiness

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**BusinessKey** | Pointer to **string** | Stable grouping key: the lowercased name and address | [optional] 
**Title** | Pointer to **string** |  | [optional] 
**Address** | Pointer to **NullableString** |  | [optional] 
**Domain** | Pointer to **NullableString** |  | [optional] 
**Url** | Pointer to **NullableString** |  | [optional] 
**Phone** | Pointer to **NullableString** |  | [optional] 
**AvgRating** | Pointer to **NullableFloat32** |  | [optional] 
**Reviews** | Pointer to **NullableInt32** |  | [optional] 
**AvgPosition** | Pointer to **NullableFloat32** | Average rank of the business in the answer&#39;s list (1 &#x3D; first) | [optional] 
**Prompts** | Pointer to **int32** |  | [optional] 
**Appearances** | Pointer to **int32** |  | [optional] 
**IsClient** | Pointer to **bool** |  | [optional] 
**CompetitorId** | Pointer to **NullableInt32** |  | [optional] 
**CompetitorName** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewLocalBusiness

`func NewLocalBusiness() *LocalBusiness`

NewLocalBusiness instantiates a new LocalBusiness object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewLocalBusinessWithDefaults

`func NewLocalBusinessWithDefaults() *LocalBusiness`

NewLocalBusinessWithDefaults instantiates a new LocalBusiness object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBusinessKey

`func (o *LocalBusiness) GetBusinessKey() string`

GetBusinessKey returns the BusinessKey field if non-nil, zero value otherwise.

### GetBusinessKeyOk

`func (o *LocalBusiness) GetBusinessKeyOk() (*string, bool)`

GetBusinessKeyOk returns a tuple with the BusinessKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBusinessKey

`func (o *LocalBusiness) SetBusinessKey(v string)`

SetBusinessKey sets BusinessKey field to given value.

### HasBusinessKey

`func (o *LocalBusiness) HasBusinessKey() bool`

HasBusinessKey returns a boolean if a field has been set.

### GetTitle

`func (o *LocalBusiness) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *LocalBusiness) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *LocalBusiness) SetTitle(v string)`

SetTitle sets Title field to given value.

### HasTitle

`func (o *LocalBusiness) HasTitle() bool`

HasTitle returns a boolean if a field has been set.

### GetAddress

`func (o *LocalBusiness) GetAddress() string`

GetAddress returns the Address field if non-nil, zero value otherwise.

### GetAddressOk

`func (o *LocalBusiness) GetAddressOk() (*string, bool)`

GetAddressOk returns a tuple with the Address field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddress

`func (o *LocalBusiness) SetAddress(v string)`

SetAddress sets Address field to given value.

### HasAddress

`func (o *LocalBusiness) HasAddress() bool`

HasAddress returns a boolean if a field has been set.

### SetAddressNil

`func (o *LocalBusiness) SetAddressNil(b bool)`

 SetAddressNil sets the value for Address to be an explicit nil

### UnsetAddress
`func (o *LocalBusiness) UnsetAddress()`

UnsetAddress ensures that no value is present for Address, not even an explicit nil
### GetDomain

`func (o *LocalBusiness) GetDomain() string`

GetDomain returns the Domain field if non-nil, zero value otherwise.

### GetDomainOk

`func (o *LocalBusiness) GetDomainOk() (*string, bool)`

GetDomainOk returns a tuple with the Domain field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDomain

`func (o *LocalBusiness) SetDomain(v string)`

SetDomain sets Domain field to given value.

### HasDomain

`func (o *LocalBusiness) HasDomain() bool`

HasDomain returns a boolean if a field has been set.

### SetDomainNil

`func (o *LocalBusiness) SetDomainNil(b bool)`

 SetDomainNil sets the value for Domain to be an explicit nil

### UnsetDomain
`func (o *LocalBusiness) UnsetDomain()`

UnsetDomain ensures that no value is present for Domain, not even an explicit nil
### GetUrl

`func (o *LocalBusiness) GetUrl() string`

GetUrl returns the Url field if non-nil, zero value otherwise.

### GetUrlOk

`func (o *LocalBusiness) GetUrlOk() (*string, bool)`

GetUrlOk returns a tuple with the Url field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrl

`func (o *LocalBusiness) SetUrl(v string)`

SetUrl sets Url field to given value.

### HasUrl

`func (o *LocalBusiness) HasUrl() bool`

HasUrl returns a boolean if a field has been set.

### SetUrlNil

`func (o *LocalBusiness) SetUrlNil(b bool)`

 SetUrlNil sets the value for Url to be an explicit nil

### UnsetUrl
`func (o *LocalBusiness) UnsetUrl()`

UnsetUrl ensures that no value is present for Url, not even an explicit nil
### GetPhone

`func (o *LocalBusiness) GetPhone() string`

GetPhone returns the Phone field if non-nil, zero value otherwise.

### GetPhoneOk

`func (o *LocalBusiness) GetPhoneOk() (*string, bool)`

GetPhoneOk returns a tuple with the Phone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPhone

`func (o *LocalBusiness) SetPhone(v string)`

SetPhone sets Phone field to given value.

### HasPhone

`func (o *LocalBusiness) HasPhone() bool`

HasPhone returns a boolean if a field has been set.

### SetPhoneNil

`func (o *LocalBusiness) SetPhoneNil(b bool)`

 SetPhoneNil sets the value for Phone to be an explicit nil

### UnsetPhone
`func (o *LocalBusiness) UnsetPhone()`

UnsetPhone ensures that no value is present for Phone, not even an explicit nil
### GetAvgRating

`func (o *LocalBusiness) GetAvgRating() float32`

GetAvgRating returns the AvgRating field if non-nil, zero value otherwise.

### GetAvgRatingOk

`func (o *LocalBusiness) GetAvgRatingOk() (*float32, bool)`

GetAvgRatingOk returns a tuple with the AvgRating field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAvgRating

`func (o *LocalBusiness) SetAvgRating(v float32)`

SetAvgRating sets AvgRating field to given value.

### HasAvgRating

`func (o *LocalBusiness) HasAvgRating() bool`

HasAvgRating returns a boolean if a field has been set.

### SetAvgRatingNil

`func (o *LocalBusiness) SetAvgRatingNil(b bool)`

 SetAvgRatingNil sets the value for AvgRating to be an explicit nil

### UnsetAvgRating
`func (o *LocalBusiness) UnsetAvgRating()`

UnsetAvgRating ensures that no value is present for AvgRating, not even an explicit nil
### GetReviews

`func (o *LocalBusiness) GetReviews() int32`

GetReviews returns the Reviews field if non-nil, zero value otherwise.

### GetReviewsOk

`func (o *LocalBusiness) GetReviewsOk() (*int32, bool)`

GetReviewsOk returns a tuple with the Reviews field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReviews

`func (o *LocalBusiness) SetReviews(v int32)`

SetReviews sets Reviews field to given value.

### HasReviews

`func (o *LocalBusiness) HasReviews() bool`

HasReviews returns a boolean if a field has been set.

### SetReviewsNil

`func (o *LocalBusiness) SetReviewsNil(b bool)`

 SetReviewsNil sets the value for Reviews to be an explicit nil

### UnsetReviews
`func (o *LocalBusiness) UnsetReviews()`

UnsetReviews ensures that no value is present for Reviews, not even an explicit nil
### GetAvgPosition

`func (o *LocalBusiness) GetAvgPosition() float32`

GetAvgPosition returns the AvgPosition field if non-nil, zero value otherwise.

### GetAvgPositionOk

`func (o *LocalBusiness) GetAvgPositionOk() (*float32, bool)`

GetAvgPositionOk returns a tuple with the AvgPosition field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAvgPosition

`func (o *LocalBusiness) SetAvgPosition(v float32)`

SetAvgPosition sets AvgPosition field to given value.

### HasAvgPosition

`func (o *LocalBusiness) HasAvgPosition() bool`

HasAvgPosition returns a boolean if a field has been set.

### SetAvgPositionNil

`func (o *LocalBusiness) SetAvgPositionNil(b bool)`

 SetAvgPositionNil sets the value for AvgPosition to be an explicit nil

### UnsetAvgPosition
`func (o *LocalBusiness) UnsetAvgPosition()`

UnsetAvgPosition ensures that no value is present for AvgPosition, not even an explicit nil
### GetPrompts

`func (o *LocalBusiness) GetPrompts() int32`

GetPrompts returns the Prompts field if non-nil, zero value otherwise.

### GetPromptsOk

`func (o *LocalBusiness) GetPromptsOk() (*int32, bool)`

GetPromptsOk returns a tuple with the Prompts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrompts

`func (o *LocalBusiness) SetPrompts(v int32)`

SetPrompts sets Prompts field to given value.

### HasPrompts

`func (o *LocalBusiness) HasPrompts() bool`

HasPrompts returns a boolean if a field has been set.

### GetAppearances

`func (o *LocalBusiness) GetAppearances() int32`

GetAppearances returns the Appearances field if non-nil, zero value otherwise.

### GetAppearancesOk

`func (o *LocalBusiness) GetAppearancesOk() (*int32, bool)`

GetAppearancesOk returns a tuple with the Appearances field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAppearances

`func (o *LocalBusiness) SetAppearances(v int32)`

SetAppearances sets Appearances field to given value.

### HasAppearances

`func (o *LocalBusiness) HasAppearances() bool`

HasAppearances returns a boolean if a field has been set.

### GetIsClient

`func (o *LocalBusiness) GetIsClient() bool`

GetIsClient returns the IsClient field if non-nil, zero value otherwise.

### GetIsClientOk

`func (o *LocalBusiness) GetIsClientOk() (*bool, bool)`

GetIsClientOk returns a tuple with the IsClient field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsClient

`func (o *LocalBusiness) SetIsClient(v bool)`

SetIsClient sets IsClient field to given value.

### HasIsClient

`func (o *LocalBusiness) HasIsClient() bool`

HasIsClient returns a boolean if a field has been set.

### GetCompetitorId

`func (o *LocalBusiness) GetCompetitorId() int32`

GetCompetitorId returns the CompetitorId field if non-nil, zero value otherwise.

### GetCompetitorIdOk

`func (o *LocalBusiness) GetCompetitorIdOk() (*int32, bool)`

GetCompetitorIdOk returns a tuple with the CompetitorId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompetitorId

`func (o *LocalBusiness) SetCompetitorId(v int32)`

SetCompetitorId sets CompetitorId field to given value.

### HasCompetitorId

`func (o *LocalBusiness) HasCompetitorId() bool`

HasCompetitorId returns a boolean if a field has been set.

### SetCompetitorIdNil

`func (o *LocalBusiness) SetCompetitorIdNil(b bool)`

 SetCompetitorIdNil sets the value for CompetitorId to be an explicit nil

### UnsetCompetitorId
`func (o *LocalBusiness) UnsetCompetitorId()`

UnsetCompetitorId ensures that no value is present for CompetitorId, not even an explicit nil
### GetCompetitorName

`func (o *LocalBusiness) GetCompetitorName() string`

GetCompetitorName returns the CompetitorName field if non-nil, zero value otherwise.

### GetCompetitorNameOk

`func (o *LocalBusiness) GetCompetitorNameOk() (*string, bool)`

GetCompetitorNameOk returns a tuple with the CompetitorName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompetitorName

`func (o *LocalBusiness) SetCompetitorName(v string)`

SetCompetitorName sets CompetitorName field to given value.

### HasCompetitorName

`func (o *LocalBusiness) HasCompetitorName() bool`

HasCompetitorName returns a boolean if a field has been set.

### SetCompetitorNameNil

`func (o *LocalBusiness) SetCompetitorNameNil(b bool)`

 SetCompetitorNameNil sets the value for CompetitorName to be an explicit nil

### UnsetCompetitorName
`func (o *LocalBusiness) UnsetCompetitorName()`

UnsetCompetitorName ensures that no value is present for CompetitorName, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


