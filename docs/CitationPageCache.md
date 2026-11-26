# CitationPageCache

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Present** | **bool** | Whether the page has a saved copy | 
**LastCrawledAt** | **NullableTime** | When the saved copy was read; null without usable content | 
**StatusCode** | **NullableInt32** | A saved successful response or an observed 404/410; null otherwise | 
**ErrorMessage** | **NullableString** | Always null; crawl errors are not exposed | 
**ContentFormat** | **NullableString** |  | 
**Bytes** | **NullableInt32** |  | 
**HtmlTitle** | **NullableString** |  | 
**MetaTitle** | **NullableString** |  | 
**MetaDescription** | **NullableString** |  | 
**H1** | **NullableString** |  | 
**CanonicalUrl** | **NullableString** |  | 
**Language** | **NullableString** |  | 
**MentionsProcessed** | **bool** | Whether the page&#39;s mention analysis has completed for this project | 
**ContentAvailable** | **bool** |  | 

## Methods

### NewCitationPageCache

`func NewCitationPageCache(present bool, lastCrawledAt NullableTime, statusCode NullableInt32, errorMessage NullableString, contentFormat NullableString, bytes NullableInt32, htmlTitle NullableString, metaTitle NullableString, metaDescription NullableString, h1 NullableString, canonicalUrl NullableString, language NullableString, mentionsProcessed bool, contentAvailable bool, ) *CitationPageCache`

NewCitationPageCache instantiates a new CitationPageCache object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCitationPageCacheWithDefaults

`func NewCitationPageCacheWithDefaults() *CitationPageCache`

NewCitationPageCacheWithDefaults instantiates a new CitationPageCache object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPresent

`func (o *CitationPageCache) GetPresent() bool`

GetPresent returns the Present field if non-nil, zero value otherwise.

### GetPresentOk

`func (o *CitationPageCache) GetPresentOk() (*bool, bool)`

GetPresentOk returns a tuple with the Present field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPresent

`func (o *CitationPageCache) SetPresent(v bool)`

SetPresent sets Present field to given value.


### GetLastCrawledAt

`func (o *CitationPageCache) GetLastCrawledAt() time.Time`

GetLastCrawledAt returns the LastCrawledAt field if non-nil, zero value otherwise.

### GetLastCrawledAtOk

`func (o *CitationPageCache) GetLastCrawledAtOk() (*time.Time, bool)`

GetLastCrawledAtOk returns a tuple with the LastCrawledAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastCrawledAt

`func (o *CitationPageCache) SetLastCrawledAt(v time.Time)`

SetLastCrawledAt sets LastCrawledAt field to given value.


### SetLastCrawledAtNil

`func (o *CitationPageCache) SetLastCrawledAtNil(b bool)`

 SetLastCrawledAtNil sets the value for LastCrawledAt to be an explicit nil

### UnsetLastCrawledAt
`func (o *CitationPageCache) UnsetLastCrawledAt()`

UnsetLastCrawledAt ensures that no value is present for LastCrawledAt, not even an explicit nil
### GetStatusCode

`func (o *CitationPageCache) GetStatusCode() int32`

GetStatusCode returns the StatusCode field if non-nil, zero value otherwise.

### GetStatusCodeOk

`func (o *CitationPageCache) GetStatusCodeOk() (*int32, bool)`

GetStatusCodeOk returns a tuple with the StatusCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatusCode

`func (o *CitationPageCache) SetStatusCode(v int32)`

SetStatusCode sets StatusCode field to given value.


### SetStatusCodeNil

`func (o *CitationPageCache) SetStatusCodeNil(b bool)`

 SetStatusCodeNil sets the value for StatusCode to be an explicit nil

### UnsetStatusCode
`func (o *CitationPageCache) UnsetStatusCode()`

UnsetStatusCode ensures that no value is present for StatusCode, not even an explicit nil
### GetErrorMessage

`func (o *CitationPageCache) GetErrorMessage() string`

GetErrorMessage returns the ErrorMessage field if non-nil, zero value otherwise.

### GetErrorMessageOk

`func (o *CitationPageCache) GetErrorMessageOk() (*string, bool)`

GetErrorMessageOk returns a tuple with the ErrorMessage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrorMessage

`func (o *CitationPageCache) SetErrorMessage(v string)`

SetErrorMessage sets ErrorMessage field to given value.


### SetErrorMessageNil

`func (o *CitationPageCache) SetErrorMessageNil(b bool)`

 SetErrorMessageNil sets the value for ErrorMessage to be an explicit nil

### UnsetErrorMessage
`func (o *CitationPageCache) UnsetErrorMessage()`

UnsetErrorMessage ensures that no value is present for ErrorMessage, not even an explicit nil
### GetContentFormat

`func (o *CitationPageCache) GetContentFormat() string`

GetContentFormat returns the ContentFormat field if non-nil, zero value otherwise.

### GetContentFormatOk

`func (o *CitationPageCache) GetContentFormatOk() (*string, bool)`

GetContentFormatOk returns a tuple with the ContentFormat field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContentFormat

`func (o *CitationPageCache) SetContentFormat(v string)`

SetContentFormat sets ContentFormat field to given value.


### SetContentFormatNil

`func (o *CitationPageCache) SetContentFormatNil(b bool)`

 SetContentFormatNil sets the value for ContentFormat to be an explicit nil

### UnsetContentFormat
`func (o *CitationPageCache) UnsetContentFormat()`

UnsetContentFormat ensures that no value is present for ContentFormat, not even an explicit nil
### GetBytes

`func (o *CitationPageCache) GetBytes() int32`

GetBytes returns the Bytes field if non-nil, zero value otherwise.

### GetBytesOk

`func (o *CitationPageCache) GetBytesOk() (*int32, bool)`

GetBytesOk returns a tuple with the Bytes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBytes

`func (o *CitationPageCache) SetBytes(v int32)`

SetBytes sets Bytes field to given value.


### SetBytesNil

`func (o *CitationPageCache) SetBytesNil(b bool)`

 SetBytesNil sets the value for Bytes to be an explicit nil

### UnsetBytes
`func (o *CitationPageCache) UnsetBytes()`

UnsetBytes ensures that no value is present for Bytes, not even an explicit nil
### GetHtmlTitle

`func (o *CitationPageCache) GetHtmlTitle() string`

GetHtmlTitle returns the HtmlTitle field if non-nil, zero value otherwise.

### GetHtmlTitleOk

`func (o *CitationPageCache) GetHtmlTitleOk() (*string, bool)`

GetHtmlTitleOk returns a tuple with the HtmlTitle field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHtmlTitle

`func (o *CitationPageCache) SetHtmlTitle(v string)`

SetHtmlTitle sets HtmlTitle field to given value.


### SetHtmlTitleNil

`func (o *CitationPageCache) SetHtmlTitleNil(b bool)`

 SetHtmlTitleNil sets the value for HtmlTitle to be an explicit nil

### UnsetHtmlTitle
`func (o *CitationPageCache) UnsetHtmlTitle()`

UnsetHtmlTitle ensures that no value is present for HtmlTitle, not even an explicit nil
### GetMetaTitle

`func (o *CitationPageCache) GetMetaTitle() string`

GetMetaTitle returns the MetaTitle field if non-nil, zero value otherwise.

### GetMetaTitleOk

`func (o *CitationPageCache) GetMetaTitleOk() (*string, bool)`

GetMetaTitleOk returns a tuple with the MetaTitle field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetaTitle

`func (o *CitationPageCache) SetMetaTitle(v string)`

SetMetaTitle sets MetaTitle field to given value.


### SetMetaTitleNil

`func (o *CitationPageCache) SetMetaTitleNil(b bool)`

 SetMetaTitleNil sets the value for MetaTitle to be an explicit nil

### UnsetMetaTitle
`func (o *CitationPageCache) UnsetMetaTitle()`

UnsetMetaTitle ensures that no value is present for MetaTitle, not even an explicit nil
### GetMetaDescription

`func (o *CitationPageCache) GetMetaDescription() string`

GetMetaDescription returns the MetaDescription field if non-nil, zero value otherwise.

### GetMetaDescriptionOk

`func (o *CitationPageCache) GetMetaDescriptionOk() (*string, bool)`

GetMetaDescriptionOk returns a tuple with the MetaDescription field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetaDescription

`func (o *CitationPageCache) SetMetaDescription(v string)`

SetMetaDescription sets MetaDescription field to given value.


### SetMetaDescriptionNil

`func (o *CitationPageCache) SetMetaDescriptionNil(b bool)`

 SetMetaDescriptionNil sets the value for MetaDescription to be an explicit nil

### UnsetMetaDescription
`func (o *CitationPageCache) UnsetMetaDescription()`

UnsetMetaDescription ensures that no value is present for MetaDescription, not even an explicit nil
### GetH1

`func (o *CitationPageCache) GetH1() string`

GetH1 returns the H1 field if non-nil, zero value otherwise.

### GetH1Ok

`func (o *CitationPageCache) GetH1Ok() (*string, bool)`

GetH1Ok returns a tuple with the H1 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetH1

`func (o *CitationPageCache) SetH1(v string)`

SetH1 sets H1 field to given value.


### SetH1Nil

`func (o *CitationPageCache) SetH1Nil(b bool)`

 SetH1Nil sets the value for H1 to be an explicit nil

### UnsetH1
`func (o *CitationPageCache) UnsetH1()`

UnsetH1 ensures that no value is present for H1, not even an explicit nil
### GetCanonicalUrl

`func (o *CitationPageCache) GetCanonicalUrl() string`

GetCanonicalUrl returns the CanonicalUrl field if non-nil, zero value otherwise.

### GetCanonicalUrlOk

`func (o *CitationPageCache) GetCanonicalUrlOk() (*string, bool)`

GetCanonicalUrlOk returns a tuple with the CanonicalUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCanonicalUrl

`func (o *CitationPageCache) SetCanonicalUrl(v string)`

SetCanonicalUrl sets CanonicalUrl field to given value.


### SetCanonicalUrlNil

`func (o *CitationPageCache) SetCanonicalUrlNil(b bool)`

 SetCanonicalUrlNil sets the value for CanonicalUrl to be an explicit nil

### UnsetCanonicalUrl
`func (o *CitationPageCache) UnsetCanonicalUrl()`

UnsetCanonicalUrl ensures that no value is present for CanonicalUrl, not even an explicit nil
### GetLanguage

`func (o *CitationPageCache) GetLanguage() string`

GetLanguage returns the Language field if non-nil, zero value otherwise.

### GetLanguageOk

`func (o *CitationPageCache) GetLanguageOk() (*string, bool)`

GetLanguageOk returns a tuple with the Language field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLanguage

`func (o *CitationPageCache) SetLanguage(v string)`

SetLanguage sets Language field to given value.


### SetLanguageNil

`func (o *CitationPageCache) SetLanguageNil(b bool)`

 SetLanguageNil sets the value for Language to be an explicit nil

### UnsetLanguage
`func (o *CitationPageCache) UnsetLanguage()`

UnsetLanguage ensures that no value is present for Language, not even an explicit nil
### GetMentionsProcessed

`func (o *CitationPageCache) GetMentionsProcessed() bool`

GetMentionsProcessed returns the MentionsProcessed field if non-nil, zero value otherwise.

### GetMentionsProcessedOk

`func (o *CitationPageCache) GetMentionsProcessedOk() (*bool, bool)`

GetMentionsProcessedOk returns a tuple with the MentionsProcessed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMentionsProcessed

`func (o *CitationPageCache) SetMentionsProcessed(v bool)`

SetMentionsProcessed sets MentionsProcessed field to given value.


### GetContentAvailable

`func (o *CitationPageCache) GetContentAvailable() bool`

GetContentAvailable returns the ContentAvailable field if non-nil, zero value otherwise.

### GetContentAvailableOk

`func (o *CitationPageCache) GetContentAvailableOk() (*bool, bool)`

GetContentAvailableOk returns a tuple with the ContentAvailable field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContentAvailable

`func (o *CitationPageCache) SetContentAvailable(v bool)`

SetContentAvailable sets ContentAvailable field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


