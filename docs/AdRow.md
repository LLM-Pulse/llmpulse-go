# AdRow

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Domain** | **NullableString** | Advertising domain; null on a placement that names none (view&#x3D;ads) | 
**Ads** | Pointer to **int32** | Placements of the domain (view&#x3D;advertisers) | [optional] 
**Executions** | Pointer to **int32** | Answers that carried them (view&#x3D;advertisers) | [optional] 
**Prompts** | Pointer to **int32** | Distinct prompts that triggered them (view&#x3D;advertisers) | [optional] 
**AvgPosition** | Pointer to **NullableFloat32** | Average position, 1 is the best slot; null when no placement has one (view&#x3D;advertisers) | [optional] 
**BestPosition** | Pointer to **NullableInt32** | Best position, 1 is the best slot (view&#x3D;advertisers) | [optional] 
**Id** | Pointer to **int32** | The placement (view&#x3D;ads) | [optional] 
**Model** | Pointer to **string** |  | [optional] 
**Title** | Pointer to **string** |  | [optional] 
**Snippet** | Pointer to **NullableString** |  | [optional] 
**Url** | Pointer to **NullableString** |  | [optional] 
**Position** | Pointer to **NullableInt32** | Position of the placement, 1 is the best slot (view&#x3D;ads) | [optional] 
**IsClient** | Pointer to **bool** | Whether the placement is identified as your brand&#39;s own (view&#x3D;ads) | [optional] 
**PromptId** | Pointer to **int32** |  | [optional] 
**PromptText** | Pointer to **NullableString** |  | [optional] 
**PromptExecutionId** | Pointer to **int32** |  | [optional] 
**ExecutedAt** | Pointer to **NullableTime** | When the answer that carried the placement was collected (view&#x3D;ads) | [optional] 

## Methods

### NewAdRow

`func NewAdRow(domain NullableString, ) *AdRow`

NewAdRow instantiates a new AdRow object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAdRowWithDefaults

`func NewAdRowWithDefaults() *AdRow`

NewAdRowWithDefaults instantiates a new AdRow object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDomain

`func (o *AdRow) GetDomain() string`

GetDomain returns the Domain field if non-nil, zero value otherwise.

### GetDomainOk

`func (o *AdRow) GetDomainOk() (*string, bool)`

GetDomainOk returns a tuple with the Domain field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDomain

`func (o *AdRow) SetDomain(v string)`

SetDomain sets Domain field to given value.


### SetDomainNil

`func (o *AdRow) SetDomainNil(b bool)`

 SetDomainNil sets the value for Domain to be an explicit nil

### UnsetDomain
`func (o *AdRow) UnsetDomain()`

UnsetDomain ensures that no value is present for Domain, not even an explicit nil
### GetAds

`func (o *AdRow) GetAds() int32`

GetAds returns the Ads field if non-nil, zero value otherwise.

### GetAdsOk

`func (o *AdRow) GetAdsOk() (*int32, bool)`

GetAdsOk returns a tuple with the Ads field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAds

`func (o *AdRow) SetAds(v int32)`

SetAds sets Ads field to given value.

### HasAds

`func (o *AdRow) HasAds() bool`

HasAds returns a boolean if a field has been set.

### GetExecutions

`func (o *AdRow) GetExecutions() int32`

GetExecutions returns the Executions field if non-nil, zero value otherwise.

### GetExecutionsOk

`func (o *AdRow) GetExecutionsOk() (*int32, bool)`

GetExecutionsOk returns a tuple with the Executions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExecutions

`func (o *AdRow) SetExecutions(v int32)`

SetExecutions sets Executions field to given value.

### HasExecutions

`func (o *AdRow) HasExecutions() bool`

HasExecutions returns a boolean if a field has been set.

### GetPrompts

`func (o *AdRow) GetPrompts() int32`

GetPrompts returns the Prompts field if non-nil, zero value otherwise.

### GetPromptsOk

`func (o *AdRow) GetPromptsOk() (*int32, bool)`

GetPromptsOk returns a tuple with the Prompts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrompts

`func (o *AdRow) SetPrompts(v int32)`

SetPrompts sets Prompts field to given value.

### HasPrompts

`func (o *AdRow) HasPrompts() bool`

HasPrompts returns a boolean if a field has been set.

### GetAvgPosition

`func (o *AdRow) GetAvgPosition() float32`

GetAvgPosition returns the AvgPosition field if non-nil, zero value otherwise.

### GetAvgPositionOk

`func (o *AdRow) GetAvgPositionOk() (*float32, bool)`

GetAvgPositionOk returns a tuple with the AvgPosition field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAvgPosition

`func (o *AdRow) SetAvgPosition(v float32)`

SetAvgPosition sets AvgPosition field to given value.

### HasAvgPosition

`func (o *AdRow) HasAvgPosition() bool`

HasAvgPosition returns a boolean if a field has been set.

### SetAvgPositionNil

`func (o *AdRow) SetAvgPositionNil(b bool)`

 SetAvgPositionNil sets the value for AvgPosition to be an explicit nil

### UnsetAvgPosition
`func (o *AdRow) UnsetAvgPosition()`

UnsetAvgPosition ensures that no value is present for AvgPosition, not even an explicit nil
### GetBestPosition

`func (o *AdRow) GetBestPosition() int32`

GetBestPosition returns the BestPosition field if non-nil, zero value otherwise.

### GetBestPositionOk

`func (o *AdRow) GetBestPositionOk() (*int32, bool)`

GetBestPositionOk returns a tuple with the BestPosition field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBestPosition

`func (o *AdRow) SetBestPosition(v int32)`

SetBestPosition sets BestPosition field to given value.

### HasBestPosition

`func (o *AdRow) HasBestPosition() bool`

HasBestPosition returns a boolean if a field has been set.

### SetBestPositionNil

`func (o *AdRow) SetBestPositionNil(b bool)`

 SetBestPositionNil sets the value for BestPosition to be an explicit nil

### UnsetBestPosition
`func (o *AdRow) UnsetBestPosition()`

UnsetBestPosition ensures that no value is present for BestPosition, not even an explicit nil
### GetId

`func (o *AdRow) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *AdRow) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *AdRow) SetId(v int32)`

SetId sets Id field to given value.

### HasId

`func (o *AdRow) HasId() bool`

HasId returns a boolean if a field has been set.

### GetModel

`func (o *AdRow) GetModel() string`

GetModel returns the Model field if non-nil, zero value otherwise.

### GetModelOk

`func (o *AdRow) GetModelOk() (*string, bool)`

GetModelOk returns a tuple with the Model field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModel

`func (o *AdRow) SetModel(v string)`

SetModel sets Model field to given value.

### HasModel

`func (o *AdRow) HasModel() bool`

HasModel returns a boolean if a field has been set.

### GetTitle

`func (o *AdRow) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *AdRow) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *AdRow) SetTitle(v string)`

SetTitle sets Title field to given value.

### HasTitle

`func (o *AdRow) HasTitle() bool`

HasTitle returns a boolean if a field has been set.

### GetSnippet

`func (o *AdRow) GetSnippet() string`

GetSnippet returns the Snippet field if non-nil, zero value otherwise.

### GetSnippetOk

`func (o *AdRow) GetSnippetOk() (*string, bool)`

GetSnippetOk returns a tuple with the Snippet field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSnippet

`func (o *AdRow) SetSnippet(v string)`

SetSnippet sets Snippet field to given value.

### HasSnippet

`func (o *AdRow) HasSnippet() bool`

HasSnippet returns a boolean if a field has been set.

### SetSnippetNil

`func (o *AdRow) SetSnippetNil(b bool)`

 SetSnippetNil sets the value for Snippet to be an explicit nil

### UnsetSnippet
`func (o *AdRow) UnsetSnippet()`

UnsetSnippet ensures that no value is present for Snippet, not even an explicit nil
### GetUrl

`func (o *AdRow) GetUrl() string`

GetUrl returns the Url field if non-nil, zero value otherwise.

### GetUrlOk

`func (o *AdRow) GetUrlOk() (*string, bool)`

GetUrlOk returns a tuple with the Url field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrl

`func (o *AdRow) SetUrl(v string)`

SetUrl sets Url field to given value.

### HasUrl

`func (o *AdRow) HasUrl() bool`

HasUrl returns a boolean if a field has been set.

### SetUrlNil

`func (o *AdRow) SetUrlNil(b bool)`

 SetUrlNil sets the value for Url to be an explicit nil

### UnsetUrl
`func (o *AdRow) UnsetUrl()`

UnsetUrl ensures that no value is present for Url, not even an explicit nil
### GetPosition

`func (o *AdRow) GetPosition() int32`

GetPosition returns the Position field if non-nil, zero value otherwise.

### GetPositionOk

`func (o *AdRow) GetPositionOk() (*int32, bool)`

GetPositionOk returns a tuple with the Position field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPosition

`func (o *AdRow) SetPosition(v int32)`

SetPosition sets Position field to given value.

### HasPosition

`func (o *AdRow) HasPosition() bool`

HasPosition returns a boolean if a field has been set.

### SetPositionNil

`func (o *AdRow) SetPositionNil(b bool)`

 SetPositionNil sets the value for Position to be an explicit nil

### UnsetPosition
`func (o *AdRow) UnsetPosition()`

UnsetPosition ensures that no value is present for Position, not even an explicit nil
### GetIsClient

`func (o *AdRow) GetIsClient() bool`

GetIsClient returns the IsClient field if non-nil, zero value otherwise.

### GetIsClientOk

`func (o *AdRow) GetIsClientOk() (*bool, bool)`

GetIsClientOk returns a tuple with the IsClient field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsClient

`func (o *AdRow) SetIsClient(v bool)`

SetIsClient sets IsClient field to given value.

### HasIsClient

`func (o *AdRow) HasIsClient() bool`

HasIsClient returns a boolean if a field has been set.

### GetPromptId

`func (o *AdRow) GetPromptId() int32`

GetPromptId returns the PromptId field if non-nil, zero value otherwise.

### GetPromptIdOk

`func (o *AdRow) GetPromptIdOk() (*int32, bool)`

GetPromptIdOk returns a tuple with the PromptId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPromptId

`func (o *AdRow) SetPromptId(v int32)`

SetPromptId sets PromptId field to given value.

### HasPromptId

`func (o *AdRow) HasPromptId() bool`

HasPromptId returns a boolean if a field has been set.

### GetPromptText

`func (o *AdRow) GetPromptText() string`

GetPromptText returns the PromptText field if non-nil, zero value otherwise.

### GetPromptTextOk

`func (o *AdRow) GetPromptTextOk() (*string, bool)`

GetPromptTextOk returns a tuple with the PromptText field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPromptText

`func (o *AdRow) SetPromptText(v string)`

SetPromptText sets PromptText field to given value.

### HasPromptText

`func (o *AdRow) HasPromptText() bool`

HasPromptText returns a boolean if a field has been set.

### SetPromptTextNil

`func (o *AdRow) SetPromptTextNil(b bool)`

 SetPromptTextNil sets the value for PromptText to be an explicit nil

### UnsetPromptText
`func (o *AdRow) UnsetPromptText()`

UnsetPromptText ensures that no value is present for PromptText, not even an explicit nil
### GetPromptExecutionId

`func (o *AdRow) GetPromptExecutionId() int32`

GetPromptExecutionId returns the PromptExecutionId field if non-nil, zero value otherwise.

### GetPromptExecutionIdOk

`func (o *AdRow) GetPromptExecutionIdOk() (*int32, bool)`

GetPromptExecutionIdOk returns a tuple with the PromptExecutionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPromptExecutionId

`func (o *AdRow) SetPromptExecutionId(v int32)`

SetPromptExecutionId sets PromptExecutionId field to given value.

### HasPromptExecutionId

`func (o *AdRow) HasPromptExecutionId() bool`

HasPromptExecutionId returns a boolean if a field has been set.

### GetExecutedAt

`func (o *AdRow) GetExecutedAt() time.Time`

GetExecutedAt returns the ExecutedAt field if non-nil, zero value otherwise.

### GetExecutedAtOk

`func (o *AdRow) GetExecutedAtOk() (*time.Time, bool)`

GetExecutedAtOk returns a tuple with the ExecutedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExecutedAt

`func (o *AdRow) SetExecutedAt(v time.Time)`

SetExecutedAt sets ExecutedAt field to given value.

### HasExecutedAt

`func (o *AdRow) HasExecutedAt() bool`

HasExecutedAt returns a boolean if a field has been set.

### SetExecutedAtNil

`func (o *AdRow) SetExecutedAtNil(b bool)`

 SetExecutedAtNil sets the value for ExecutedAt to be an explicit nil

### UnsetExecutedAt
`func (o *AdRow) UnsetExecutedAt()`

UnsetExecutedAt ensures that no value is present for ExecutedAt, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


