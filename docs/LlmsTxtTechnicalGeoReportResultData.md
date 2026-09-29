# LlmsTxtTechnicalGeoReportResultData

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**LlmsTxtContent** | Pointer to **string** | Current llms.txt, manual edits included | [optional] 
**LlmsFullTxtContent** | Pointer to **NullableString** | Current llms-full.txt, manual edits included | [optional] 
**ManuallyEditedAt** | Pointer to **NullableTime** | When the files were last edited by hand in the app, the API or MCP; null while they are as generated | [optional] 
**ContentVersion** | Pointer to **string** | Send it back as content_version when editing the files. It changes on every save | [optional] 
**OriginalLlmsTxtContent** | Pointer to **NullableString** | The generated llms.txt, kept from the first manual edit; null while the files are as generated | [optional] 
**OriginalLlmsFullTxtContent** | Pointer to **NullableString** | The generated llms-full.txt, kept from the first manual edit; null while the files are as generated | [optional] 
**CrawlData** | Pointer to **map[string]interface{}** |  | [optional] 
**Metadata** | Pointer to **map[string]interface{}** | Generation details, including output_language_code, the language the files were written in | [optional] 
**PagesCrawled** | Pointer to **NullableInt32** |  | [optional] 
**GenerationTimeMs** | Pointer to **NullableInt32** |  | [optional] 
**OpenaiTokensUsed** | Pointer to **NullableInt32** |  | [optional] 

## Methods

### NewLlmsTxtTechnicalGeoReportResultData

`func NewLlmsTxtTechnicalGeoReportResultData() *LlmsTxtTechnicalGeoReportResultData`

NewLlmsTxtTechnicalGeoReportResultData instantiates a new LlmsTxtTechnicalGeoReportResultData object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewLlmsTxtTechnicalGeoReportResultDataWithDefaults

`func NewLlmsTxtTechnicalGeoReportResultDataWithDefaults() *LlmsTxtTechnicalGeoReportResultData`

NewLlmsTxtTechnicalGeoReportResultDataWithDefaults instantiates a new LlmsTxtTechnicalGeoReportResultData object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetLlmsTxtContent

`func (o *LlmsTxtTechnicalGeoReportResultData) GetLlmsTxtContent() string`

GetLlmsTxtContent returns the LlmsTxtContent field if non-nil, zero value otherwise.

### GetLlmsTxtContentOk

`func (o *LlmsTxtTechnicalGeoReportResultData) GetLlmsTxtContentOk() (*string, bool)`

GetLlmsTxtContentOk returns a tuple with the LlmsTxtContent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLlmsTxtContent

`func (o *LlmsTxtTechnicalGeoReportResultData) SetLlmsTxtContent(v string)`

SetLlmsTxtContent sets LlmsTxtContent field to given value.

### HasLlmsTxtContent

`func (o *LlmsTxtTechnicalGeoReportResultData) HasLlmsTxtContent() bool`

HasLlmsTxtContent returns a boolean if a field has been set.

### GetLlmsFullTxtContent

`func (o *LlmsTxtTechnicalGeoReportResultData) GetLlmsFullTxtContent() string`

GetLlmsFullTxtContent returns the LlmsFullTxtContent field if non-nil, zero value otherwise.

### GetLlmsFullTxtContentOk

`func (o *LlmsTxtTechnicalGeoReportResultData) GetLlmsFullTxtContentOk() (*string, bool)`

GetLlmsFullTxtContentOk returns a tuple with the LlmsFullTxtContent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLlmsFullTxtContent

`func (o *LlmsTxtTechnicalGeoReportResultData) SetLlmsFullTxtContent(v string)`

SetLlmsFullTxtContent sets LlmsFullTxtContent field to given value.

### HasLlmsFullTxtContent

`func (o *LlmsTxtTechnicalGeoReportResultData) HasLlmsFullTxtContent() bool`

HasLlmsFullTxtContent returns a boolean if a field has been set.

### SetLlmsFullTxtContentNil

`func (o *LlmsTxtTechnicalGeoReportResultData) SetLlmsFullTxtContentNil(b bool)`

 SetLlmsFullTxtContentNil sets the value for LlmsFullTxtContent to be an explicit nil

### UnsetLlmsFullTxtContent
`func (o *LlmsTxtTechnicalGeoReportResultData) UnsetLlmsFullTxtContent()`

UnsetLlmsFullTxtContent ensures that no value is present for LlmsFullTxtContent, not even an explicit nil
### GetManuallyEditedAt

`func (o *LlmsTxtTechnicalGeoReportResultData) GetManuallyEditedAt() time.Time`

GetManuallyEditedAt returns the ManuallyEditedAt field if non-nil, zero value otherwise.

### GetManuallyEditedAtOk

`func (o *LlmsTxtTechnicalGeoReportResultData) GetManuallyEditedAtOk() (*time.Time, bool)`

GetManuallyEditedAtOk returns a tuple with the ManuallyEditedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetManuallyEditedAt

`func (o *LlmsTxtTechnicalGeoReportResultData) SetManuallyEditedAt(v time.Time)`

SetManuallyEditedAt sets ManuallyEditedAt field to given value.

### HasManuallyEditedAt

`func (o *LlmsTxtTechnicalGeoReportResultData) HasManuallyEditedAt() bool`

HasManuallyEditedAt returns a boolean if a field has been set.

### SetManuallyEditedAtNil

`func (o *LlmsTxtTechnicalGeoReportResultData) SetManuallyEditedAtNil(b bool)`

 SetManuallyEditedAtNil sets the value for ManuallyEditedAt to be an explicit nil

### UnsetManuallyEditedAt
`func (o *LlmsTxtTechnicalGeoReportResultData) UnsetManuallyEditedAt()`

UnsetManuallyEditedAt ensures that no value is present for ManuallyEditedAt, not even an explicit nil
### GetContentVersion

`func (o *LlmsTxtTechnicalGeoReportResultData) GetContentVersion() string`

GetContentVersion returns the ContentVersion field if non-nil, zero value otherwise.

### GetContentVersionOk

`func (o *LlmsTxtTechnicalGeoReportResultData) GetContentVersionOk() (*string, bool)`

GetContentVersionOk returns a tuple with the ContentVersion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContentVersion

`func (o *LlmsTxtTechnicalGeoReportResultData) SetContentVersion(v string)`

SetContentVersion sets ContentVersion field to given value.

### HasContentVersion

`func (o *LlmsTxtTechnicalGeoReportResultData) HasContentVersion() bool`

HasContentVersion returns a boolean if a field has been set.

### GetOriginalLlmsTxtContent

`func (o *LlmsTxtTechnicalGeoReportResultData) GetOriginalLlmsTxtContent() string`

GetOriginalLlmsTxtContent returns the OriginalLlmsTxtContent field if non-nil, zero value otherwise.

### GetOriginalLlmsTxtContentOk

`func (o *LlmsTxtTechnicalGeoReportResultData) GetOriginalLlmsTxtContentOk() (*string, bool)`

GetOriginalLlmsTxtContentOk returns a tuple with the OriginalLlmsTxtContent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOriginalLlmsTxtContent

`func (o *LlmsTxtTechnicalGeoReportResultData) SetOriginalLlmsTxtContent(v string)`

SetOriginalLlmsTxtContent sets OriginalLlmsTxtContent field to given value.

### HasOriginalLlmsTxtContent

`func (o *LlmsTxtTechnicalGeoReportResultData) HasOriginalLlmsTxtContent() bool`

HasOriginalLlmsTxtContent returns a boolean if a field has been set.

### SetOriginalLlmsTxtContentNil

`func (o *LlmsTxtTechnicalGeoReportResultData) SetOriginalLlmsTxtContentNil(b bool)`

 SetOriginalLlmsTxtContentNil sets the value for OriginalLlmsTxtContent to be an explicit nil

### UnsetOriginalLlmsTxtContent
`func (o *LlmsTxtTechnicalGeoReportResultData) UnsetOriginalLlmsTxtContent()`

UnsetOriginalLlmsTxtContent ensures that no value is present for OriginalLlmsTxtContent, not even an explicit nil
### GetOriginalLlmsFullTxtContent

`func (o *LlmsTxtTechnicalGeoReportResultData) GetOriginalLlmsFullTxtContent() string`

GetOriginalLlmsFullTxtContent returns the OriginalLlmsFullTxtContent field if non-nil, zero value otherwise.

### GetOriginalLlmsFullTxtContentOk

`func (o *LlmsTxtTechnicalGeoReportResultData) GetOriginalLlmsFullTxtContentOk() (*string, bool)`

GetOriginalLlmsFullTxtContentOk returns a tuple with the OriginalLlmsFullTxtContent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOriginalLlmsFullTxtContent

`func (o *LlmsTxtTechnicalGeoReportResultData) SetOriginalLlmsFullTxtContent(v string)`

SetOriginalLlmsFullTxtContent sets OriginalLlmsFullTxtContent field to given value.

### HasOriginalLlmsFullTxtContent

`func (o *LlmsTxtTechnicalGeoReportResultData) HasOriginalLlmsFullTxtContent() bool`

HasOriginalLlmsFullTxtContent returns a boolean if a field has been set.

### SetOriginalLlmsFullTxtContentNil

`func (o *LlmsTxtTechnicalGeoReportResultData) SetOriginalLlmsFullTxtContentNil(b bool)`

 SetOriginalLlmsFullTxtContentNil sets the value for OriginalLlmsFullTxtContent to be an explicit nil

### UnsetOriginalLlmsFullTxtContent
`func (o *LlmsTxtTechnicalGeoReportResultData) UnsetOriginalLlmsFullTxtContent()`

UnsetOriginalLlmsFullTxtContent ensures that no value is present for OriginalLlmsFullTxtContent, not even an explicit nil
### GetCrawlData

`func (o *LlmsTxtTechnicalGeoReportResultData) GetCrawlData() map[string]interface{}`

GetCrawlData returns the CrawlData field if non-nil, zero value otherwise.

### GetCrawlDataOk

`func (o *LlmsTxtTechnicalGeoReportResultData) GetCrawlDataOk() (*map[string]interface{}, bool)`

GetCrawlDataOk returns a tuple with the CrawlData field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCrawlData

`func (o *LlmsTxtTechnicalGeoReportResultData) SetCrawlData(v map[string]interface{})`

SetCrawlData sets CrawlData field to given value.

### HasCrawlData

`func (o *LlmsTxtTechnicalGeoReportResultData) HasCrawlData() bool`

HasCrawlData returns a boolean if a field has been set.

### SetCrawlDataNil

`func (o *LlmsTxtTechnicalGeoReportResultData) SetCrawlDataNil(b bool)`

 SetCrawlDataNil sets the value for CrawlData to be an explicit nil

### UnsetCrawlData
`func (o *LlmsTxtTechnicalGeoReportResultData) UnsetCrawlData()`

UnsetCrawlData ensures that no value is present for CrawlData, not even an explicit nil
### GetMetadata

`func (o *LlmsTxtTechnicalGeoReportResultData) GetMetadata() map[string]interface{}`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *LlmsTxtTechnicalGeoReportResultData) GetMetadataOk() (*map[string]interface{}, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *LlmsTxtTechnicalGeoReportResultData) SetMetadata(v map[string]interface{})`

SetMetadata sets Metadata field to given value.

### HasMetadata

`func (o *LlmsTxtTechnicalGeoReportResultData) HasMetadata() bool`

HasMetadata returns a boolean if a field has been set.

### SetMetadataNil

`func (o *LlmsTxtTechnicalGeoReportResultData) SetMetadataNil(b bool)`

 SetMetadataNil sets the value for Metadata to be an explicit nil

### UnsetMetadata
`func (o *LlmsTxtTechnicalGeoReportResultData) UnsetMetadata()`

UnsetMetadata ensures that no value is present for Metadata, not even an explicit nil
### GetPagesCrawled

`func (o *LlmsTxtTechnicalGeoReportResultData) GetPagesCrawled() int32`

GetPagesCrawled returns the PagesCrawled field if non-nil, zero value otherwise.

### GetPagesCrawledOk

`func (o *LlmsTxtTechnicalGeoReportResultData) GetPagesCrawledOk() (*int32, bool)`

GetPagesCrawledOk returns a tuple with the PagesCrawled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPagesCrawled

`func (o *LlmsTxtTechnicalGeoReportResultData) SetPagesCrawled(v int32)`

SetPagesCrawled sets PagesCrawled field to given value.

### HasPagesCrawled

`func (o *LlmsTxtTechnicalGeoReportResultData) HasPagesCrawled() bool`

HasPagesCrawled returns a boolean if a field has been set.

### SetPagesCrawledNil

`func (o *LlmsTxtTechnicalGeoReportResultData) SetPagesCrawledNil(b bool)`

 SetPagesCrawledNil sets the value for PagesCrawled to be an explicit nil

### UnsetPagesCrawled
`func (o *LlmsTxtTechnicalGeoReportResultData) UnsetPagesCrawled()`

UnsetPagesCrawled ensures that no value is present for PagesCrawled, not even an explicit nil
### GetGenerationTimeMs

`func (o *LlmsTxtTechnicalGeoReportResultData) GetGenerationTimeMs() int32`

GetGenerationTimeMs returns the GenerationTimeMs field if non-nil, zero value otherwise.

### GetGenerationTimeMsOk

`func (o *LlmsTxtTechnicalGeoReportResultData) GetGenerationTimeMsOk() (*int32, bool)`

GetGenerationTimeMsOk returns a tuple with the GenerationTimeMs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGenerationTimeMs

`func (o *LlmsTxtTechnicalGeoReportResultData) SetGenerationTimeMs(v int32)`

SetGenerationTimeMs sets GenerationTimeMs field to given value.

### HasGenerationTimeMs

`func (o *LlmsTxtTechnicalGeoReportResultData) HasGenerationTimeMs() bool`

HasGenerationTimeMs returns a boolean if a field has been set.

### SetGenerationTimeMsNil

`func (o *LlmsTxtTechnicalGeoReportResultData) SetGenerationTimeMsNil(b bool)`

 SetGenerationTimeMsNil sets the value for GenerationTimeMs to be an explicit nil

### UnsetGenerationTimeMs
`func (o *LlmsTxtTechnicalGeoReportResultData) UnsetGenerationTimeMs()`

UnsetGenerationTimeMs ensures that no value is present for GenerationTimeMs, not even an explicit nil
### GetOpenaiTokensUsed

`func (o *LlmsTxtTechnicalGeoReportResultData) GetOpenaiTokensUsed() int32`

GetOpenaiTokensUsed returns the OpenaiTokensUsed field if non-nil, zero value otherwise.

### GetOpenaiTokensUsedOk

`func (o *LlmsTxtTechnicalGeoReportResultData) GetOpenaiTokensUsedOk() (*int32, bool)`

GetOpenaiTokensUsedOk returns a tuple with the OpenaiTokensUsed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOpenaiTokensUsed

`func (o *LlmsTxtTechnicalGeoReportResultData) SetOpenaiTokensUsed(v int32)`

SetOpenaiTokensUsed sets OpenaiTokensUsed field to given value.

### HasOpenaiTokensUsed

`func (o *LlmsTxtTechnicalGeoReportResultData) HasOpenaiTokensUsed() bool`

HasOpenaiTokensUsed returns a boolean if a field has been set.

### SetOpenaiTokensUsedNil

`func (o *LlmsTxtTechnicalGeoReportResultData) SetOpenaiTokensUsedNil(b bool)`

 SetOpenaiTokensUsedNil sets the value for OpenaiTokensUsed to be an explicit nil

### UnsetOpenaiTokensUsed
`func (o *LlmsTxtTechnicalGeoReportResultData) UnsetOpenaiTokensUsed()`

UnsetOpenaiTokensUsed ensures that no value is present for OpenaiTokensUsed, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


