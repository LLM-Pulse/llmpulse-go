# CitedUrlContentResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ProjectId** | **int32** |  | 
**UrlSha256** | **string** |  | 
**Url** | **NullableString** | The URL as first cited | 
**NormalizedUrl** | **string** |  | 
**Domain** | **NullableString** |  | 
**Host** | **NullableString** |  | 
**PageDetails** | [**CitationPageDetails**](CitationPageDetails.md) |  | 
**RequestId** | **string** |  | 

## Methods

### NewCitedUrlContentResponse

`func NewCitedUrlContentResponse(projectId int32, urlSha256 string, url NullableString, normalizedUrl string, domain NullableString, host NullableString, pageDetails CitationPageDetails, requestId string, ) *CitedUrlContentResponse`

NewCitedUrlContentResponse instantiates a new CitedUrlContentResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCitedUrlContentResponseWithDefaults

`func NewCitedUrlContentResponseWithDefaults() *CitedUrlContentResponse`

NewCitedUrlContentResponseWithDefaults instantiates a new CitedUrlContentResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProjectId

`func (o *CitedUrlContentResponse) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *CitedUrlContentResponse) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *CitedUrlContentResponse) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.


### GetUrlSha256

`func (o *CitedUrlContentResponse) GetUrlSha256() string`

GetUrlSha256 returns the UrlSha256 field if non-nil, zero value otherwise.

### GetUrlSha256Ok

`func (o *CitedUrlContentResponse) GetUrlSha256Ok() (*string, bool)`

GetUrlSha256Ok returns a tuple with the UrlSha256 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrlSha256

`func (o *CitedUrlContentResponse) SetUrlSha256(v string)`

SetUrlSha256 sets UrlSha256 field to given value.


### GetUrl

`func (o *CitedUrlContentResponse) GetUrl() string`

GetUrl returns the Url field if non-nil, zero value otherwise.

### GetUrlOk

`func (o *CitedUrlContentResponse) GetUrlOk() (*string, bool)`

GetUrlOk returns a tuple with the Url field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrl

`func (o *CitedUrlContentResponse) SetUrl(v string)`

SetUrl sets Url field to given value.


### SetUrlNil

`func (o *CitedUrlContentResponse) SetUrlNil(b bool)`

 SetUrlNil sets the value for Url to be an explicit nil

### UnsetUrl
`func (o *CitedUrlContentResponse) UnsetUrl()`

UnsetUrl ensures that no value is present for Url, not even an explicit nil
### GetNormalizedUrl

`func (o *CitedUrlContentResponse) GetNormalizedUrl() string`

GetNormalizedUrl returns the NormalizedUrl field if non-nil, zero value otherwise.

### GetNormalizedUrlOk

`func (o *CitedUrlContentResponse) GetNormalizedUrlOk() (*string, bool)`

GetNormalizedUrlOk returns a tuple with the NormalizedUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNormalizedUrl

`func (o *CitedUrlContentResponse) SetNormalizedUrl(v string)`

SetNormalizedUrl sets NormalizedUrl field to given value.


### GetDomain

`func (o *CitedUrlContentResponse) GetDomain() string`

GetDomain returns the Domain field if non-nil, zero value otherwise.

### GetDomainOk

`func (o *CitedUrlContentResponse) GetDomainOk() (*string, bool)`

GetDomainOk returns a tuple with the Domain field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDomain

`func (o *CitedUrlContentResponse) SetDomain(v string)`

SetDomain sets Domain field to given value.


### SetDomainNil

`func (o *CitedUrlContentResponse) SetDomainNil(b bool)`

 SetDomainNil sets the value for Domain to be an explicit nil

### UnsetDomain
`func (o *CitedUrlContentResponse) UnsetDomain()`

UnsetDomain ensures that no value is present for Domain, not even an explicit nil
### GetHost

`func (o *CitedUrlContentResponse) GetHost() string`

GetHost returns the Host field if non-nil, zero value otherwise.

### GetHostOk

`func (o *CitedUrlContentResponse) GetHostOk() (*string, bool)`

GetHostOk returns a tuple with the Host field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHost

`func (o *CitedUrlContentResponse) SetHost(v string)`

SetHost sets Host field to given value.


### SetHostNil

`func (o *CitedUrlContentResponse) SetHostNil(b bool)`

 SetHostNil sets the value for Host to be an explicit nil

### UnsetHost
`func (o *CitedUrlContentResponse) UnsetHost()`

UnsetHost ensures that no value is present for Host, not even an explicit nil
### GetPageDetails

`func (o *CitedUrlContentResponse) GetPageDetails() CitationPageDetails`

GetPageDetails returns the PageDetails field if non-nil, zero value otherwise.

### GetPageDetailsOk

`func (o *CitedUrlContentResponse) GetPageDetailsOk() (*CitationPageDetails, bool)`

GetPageDetailsOk returns a tuple with the PageDetails field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPageDetails

`func (o *CitedUrlContentResponse) SetPageDetails(v CitationPageDetails)`

SetPageDetails sets PageDetails field to given value.


### GetRequestId

`func (o *CitedUrlContentResponse) GetRequestId() string`

GetRequestId returns the RequestId field if non-nil, zero value otherwise.

### GetRequestIdOk

`func (o *CitedUrlContentResponse) GetRequestIdOk() (*string, bool)`

GetRequestIdOk returns a tuple with the RequestId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestId

`func (o *CitedUrlContentResponse) SetRequestId(v string)`

SetRequestId sets RequestId field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


