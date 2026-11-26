# CitedUrlDetailsResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ProjectId** | **int32** |  | 
**UrlSha256** | **string** |  | 
**Url** | **NullableString** | The URL as first cited | 
**NormalizedUrl** | **string** |  | 
**Domain** | **NullableString** |  | 
**Host** | **NullableString** |  | 
**Stats** | [**CitedUrlDetailsResponseStats**](CitedUrlDetailsResponseStats.md) |  | 
**Urls** | **[]string** | Up to 20 spellings of the URL as cited, alphabetically | 
**PageDetails** | [**CitationPageDetails**](CitationPageDetails.md) |  | 
**CitationSeries** | Pointer to [**CitationSeries**](CitationSeries.md) |  | [optional] 
**RequestId** | **string** |  | 

## Methods

### NewCitedUrlDetailsResponse

`func NewCitedUrlDetailsResponse(projectId int32, urlSha256 string, url NullableString, normalizedUrl string, domain NullableString, host NullableString, stats CitedUrlDetailsResponseStats, urls []*string, pageDetails CitationPageDetails, requestId string, ) *CitedUrlDetailsResponse`

NewCitedUrlDetailsResponse instantiates a new CitedUrlDetailsResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCitedUrlDetailsResponseWithDefaults

`func NewCitedUrlDetailsResponseWithDefaults() *CitedUrlDetailsResponse`

NewCitedUrlDetailsResponseWithDefaults instantiates a new CitedUrlDetailsResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProjectId

`func (o *CitedUrlDetailsResponse) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *CitedUrlDetailsResponse) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *CitedUrlDetailsResponse) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.


### GetUrlSha256

`func (o *CitedUrlDetailsResponse) GetUrlSha256() string`

GetUrlSha256 returns the UrlSha256 field if non-nil, zero value otherwise.

### GetUrlSha256Ok

`func (o *CitedUrlDetailsResponse) GetUrlSha256Ok() (*string, bool)`

GetUrlSha256Ok returns a tuple with the UrlSha256 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrlSha256

`func (o *CitedUrlDetailsResponse) SetUrlSha256(v string)`

SetUrlSha256 sets UrlSha256 field to given value.


### GetUrl

`func (o *CitedUrlDetailsResponse) GetUrl() string`

GetUrl returns the Url field if non-nil, zero value otherwise.

### GetUrlOk

`func (o *CitedUrlDetailsResponse) GetUrlOk() (*string, bool)`

GetUrlOk returns a tuple with the Url field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrl

`func (o *CitedUrlDetailsResponse) SetUrl(v string)`

SetUrl sets Url field to given value.


### SetUrlNil

`func (o *CitedUrlDetailsResponse) SetUrlNil(b bool)`

 SetUrlNil sets the value for Url to be an explicit nil

### UnsetUrl
`func (o *CitedUrlDetailsResponse) UnsetUrl()`

UnsetUrl ensures that no value is present for Url, not even an explicit nil
### GetNormalizedUrl

`func (o *CitedUrlDetailsResponse) GetNormalizedUrl() string`

GetNormalizedUrl returns the NormalizedUrl field if non-nil, zero value otherwise.

### GetNormalizedUrlOk

`func (o *CitedUrlDetailsResponse) GetNormalizedUrlOk() (*string, bool)`

GetNormalizedUrlOk returns a tuple with the NormalizedUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNormalizedUrl

`func (o *CitedUrlDetailsResponse) SetNormalizedUrl(v string)`

SetNormalizedUrl sets NormalizedUrl field to given value.


### GetDomain

`func (o *CitedUrlDetailsResponse) GetDomain() string`

GetDomain returns the Domain field if non-nil, zero value otherwise.

### GetDomainOk

`func (o *CitedUrlDetailsResponse) GetDomainOk() (*string, bool)`

GetDomainOk returns a tuple with the Domain field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDomain

`func (o *CitedUrlDetailsResponse) SetDomain(v string)`

SetDomain sets Domain field to given value.


### SetDomainNil

`func (o *CitedUrlDetailsResponse) SetDomainNil(b bool)`

 SetDomainNil sets the value for Domain to be an explicit nil

### UnsetDomain
`func (o *CitedUrlDetailsResponse) UnsetDomain()`

UnsetDomain ensures that no value is present for Domain, not even an explicit nil
### GetHost

`func (o *CitedUrlDetailsResponse) GetHost() string`

GetHost returns the Host field if non-nil, zero value otherwise.

### GetHostOk

`func (o *CitedUrlDetailsResponse) GetHostOk() (*string, bool)`

GetHostOk returns a tuple with the Host field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHost

`func (o *CitedUrlDetailsResponse) SetHost(v string)`

SetHost sets Host field to given value.


### SetHostNil

`func (o *CitedUrlDetailsResponse) SetHostNil(b bool)`

 SetHostNil sets the value for Host to be an explicit nil

### UnsetHost
`func (o *CitedUrlDetailsResponse) UnsetHost()`

UnsetHost ensures that no value is present for Host, not even an explicit nil
### GetStats

`func (o *CitedUrlDetailsResponse) GetStats() CitedUrlDetailsResponseStats`

GetStats returns the Stats field if non-nil, zero value otherwise.

### GetStatsOk

`func (o *CitedUrlDetailsResponse) GetStatsOk() (*CitedUrlDetailsResponseStats, bool)`

GetStatsOk returns a tuple with the Stats field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStats

`func (o *CitedUrlDetailsResponse) SetStats(v CitedUrlDetailsResponseStats)`

SetStats sets Stats field to given value.


### GetUrls

`func (o *CitedUrlDetailsResponse) GetUrls() []*string`

GetUrls returns the Urls field if non-nil, zero value otherwise.

### GetUrlsOk

`func (o *CitedUrlDetailsResponse) GetUrlsOk() (*[]*string, bool)`

GetUrlsOk returns a tuple with the Urls field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrls

`func (o *CitedUrlDetailsResponse) SetUrls(v []*string)`

SetUrls sets Urls field to given value.


### GetPageDetails

`func (o *CitedUrlDetailsResponse) GetPageDetails() CitationPageDetails`

GetPageDetails returns the PageDetails field if non-nil, zero value otherwise.

### GetPageDetailsOk

`func (o *CitedUrlDetailsResponse) GetPageDetailsOk() (*CitationPageDetails, bool)`

GetPageDetailsOk returns a tuple with the PageDetails field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPageDetails

`func (o *CitedUrlDetailsResponse) SetPageDetails(v CitationPageDetails)`

SetPageDetails sets PageDetails field to given value.


### GetCitationSeries

`func (o *CitedUrlDetailsResponse) GetCitationSeries() CitationSeries`

GetCitationSeries returns the CitationSeries field if non-nil, zero value otherwise.

### GetCitationSeriesOk

`func (o *CitedUrlDetailsResponse) GetCitationSeriesOk() (*CitationSeries, bool)`

GetCitationSeriesOk returns a tuple with the CitationSeries field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCitationSeries

`func (o *CitedUrlDetailsResponse) SetCitationSeries(v CitationSeries)`

SetCitationSeries sets CitationSeries field to given value.

### HasCitationSeries

`func (o *CitedUrlDetailsResponse) HasCitationSeries() bool`

HasCitationSeries returns a boolean if a field has been set.

### GetRequestId

`func (o *CitedUrlDetailsResponse) GetRequestId() string`

GetRequestId returns the RequestId field if non-nil, zero value otherwise.

### GetRequestIdOk

`func (o *CitedUrlDetailsResponse) GetRequestIdOk() (*string, bool)`

GetRequestIdOk returns a tuple with the RequestId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestId

`func (o *CitedUrlDetailsResponse) SetRequestId(v string)`

SetRequestId sets RequestId field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


