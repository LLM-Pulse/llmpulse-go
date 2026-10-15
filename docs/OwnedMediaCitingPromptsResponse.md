# OwnedMediaCitingPromptsResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ProjectId** | Pointer to **int32** |  | [optional] 
**Provider** | Pointer to **string** |  | [optional] 
**From** | Pointer to **time.Time** |  | [optional] 
**To** | Pointer to **time.Time** |  | [optional] 
**Item** | Pointer to [**NullableOwnedMediaCitedItem**](OwnedMediaCitedItem.md) |  | [optional] 
**CitationCount** | Pointer to **int32** | Citations of the item in the window | [optional] 
**PromptCount** | Pointer to **int32** | Distinct prompts whose answers cited it | [optional] 
**Page** | Pointer to **int32** |  | [optional] 
**PerPage** | Pointer to **int32** |  | [optional] 
**Total** | Pointer to **int32** | Citing answers | [optional] 
**Data** | Pointer to [**[]OwnedMediaCitingAnswer**](OwnedMediaCitingAnswer.md) |  | [optional] 
**RequestId** | Pointer to **string** |  | [optional] 

## Methods

### NewOwnedMediaCitingPromptsResponse

`func NewOwnedMediaCitingPromptsResponse() *OwnedMediaCitingPromptsResponse`

NewOwnedMediaCitingPromptsResponse instantiates a new OwnedMediaCitingPromptsResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOwnedMediaCitingPromptsResponseWithDefaults

`func NewOwnedMediaCitingPromptsResponseWithDefaults() *OwnedMediaCitingPromptsResponse`

NewOwnedMediaCitingPromptsResponseWithDefaults instantiates a new OwnedMediaCitingPromptsResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProjectId

`func (o *OwnedMediaCitingPromptsResponse) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *OwnedMediaCitingPromptsResponse) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *OwnedMediaCitingPromptsResponse) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.

### HasProjectId

`func (o *OwnedMediaCitingPromptsResponse) HasProjectId() bool`

HasProjectId returns a boolean if a field has been set.

### GetProvider

`func (o *OwnedMediaCitingPromptsResponse) GetProvider() string`

GetProvider returns the Provider field if non-nil, zero value otherwise.

### GetProviderOk

`func (o *OwnedMediaCitingPromptsResponse) GetProviderOk() (*string, bool)`

GetProviderOk returns a tuple with the Provider field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProvider

`func (o *OwnedMediaCitingPromptsResponse) SetProvider(v string)`

SetProvider sets Provider field to given value.

### HasProvider

`func (o *OwnedMediaCitingPromptsResponse) HasProvider() bool`

HasProvider returns a boolean if a field has been set.

### GetFrom

`func (o *OwnedMediaCitingPromptsResponse) GetFrom() time.Time`

GetFrom returns the From field if non-nil, zero value otherwise.

### GetFromOk

`func (o *OwnedMediaCitingPromptsResponse) GetFromOk() (*time.Time, bool)`

GetFromOk returns a tuple with the From field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFrom

`func (o *OwnedMediaCitingPromptsResponse) SetFrom(v time.Time)`

SetFrom sets From field to given value.

### HasFrom

`func (o *OwnedMediaCitingPromptsResponse) HasFrom() bool`

HasFrom returns a boolean if a field has been set.

### GetTo

`func (o *OwnedMediaCitingPromptsResponse) GetTo() time.Time`

GetTo returns the To field if non-nil, zero value otherwise.

### GetToOk

`func (o *OwnedMediaCitingPromptsResponse) GetToOk() (*time.Time, bool)`

GetToOk returns a tuple with the To field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTo

`func (o *OwnedMediaCitingPromptsResponse) SetTo(v time.Time)`

SetTo sets To field to given value.

### HasTo

`func (o *OwnedMediaCitingPromptsResponse) HasTo() bool`

HasTo returns a boolean if a field has been set.

### GetItem

`func (o *OwnedMediaCitingPromptsResponse) GetItem() OwnedMediaCitedItem`

GetItem returns the Item field if non-nil, zero value otherwise.

### GetItemOk

`func (o *OwnedMediaCitingPromptsResponse) GetItemOk() (*OwnedMediaCitedItem, bool)`

GetItemOk returns a tuple with the Item field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetItem

`func (o *OwnedMediaCitingPromptsResponse) SetItem(v OwnedMediaCitedItem)`

SetItem sets Item field to given value.

### HasItem

`func (o *OwnedMediaCitingPromptsResponse) HasItem() bool`

HasItem returns a boolean if a field has been set.

### SetItemNil

`func (o *OwnedMediaCitingPromptsResponse) SetItemNil(b bool)`

 SetItemNil sets the value for Item to be an explicit nil

### UnsetItem
`func (o *OwnedMediaCitingPromptsResponse) UnsetItem()`

UnsetItem ensures that no value is present for Item, not even an explicit nil
### GetCitationCount

`func (o *OwnedMediaCitingPromptsResponse) GetCitationCount() int32`

GetCitationCount returns the CitationCount field if non-nil, zero value otherwise.

### GetCitationCountOk

`func (o *OwnedMediaCitingPromptsResponse) GetCitationCountOk() (*int32, bool)`

GetCitationCountOk returns a tuple with the CitationCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCitationCount

`func (o *OwnedMediaCitingPromptsResponse) SetCitationCount(v int32)`

SetCitationCount sets CitationCount field to given value.

### HasCitationCount

`func (o *OwnedMediaCitingPromptsResponse) HasCitationCount() bool`

HasCitationCount returns a boolean if a field has been set.

### GetPromptCount

`func (o *OwnedMediaCitingPromptsResponse) GetPromptCount() int32`

GetPromptCount returns the PromptCount field if non-nil, zero value otherwise.

### GetPromptCountOk

`func (o *OwnedMediaCitingPromptsResponse) GetPromptCountOk() (*int32, bool)`

GetPromptCountOk returns a tuple with the PromptCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPromptCount

`func (o *OwnedMediaCitingPromptsResponse) SetPromptCount(v int32)`

SetPromptCount sets PromptCount field to given value.

### HasPromptCount

`func (o *OwnedMediaCitingPromptsResponse) HasPromptCount() bool`

HasPromptCount returns a boolean if a field has been set.

### GetPage

`func (o *OwnedMediaCitingPromptsResponse) GetPage() int32`

GetPage returns the Page field if non-nil, zero value otherwise.

### GetPageOk

`func (o *OwnedMediaCitingPromptsResponse) GetPageOk() (*int32, bool)`

GetPageOk returns a tuple with the Page field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPage

`func (o *OwnedMediaCitingPromptsResponse) SetPage(v int32)`

SetPage sets Page field to given value.

### HasPage

`func (o *OwnedMediaCitingPromptsResponse) HasPage() bool`

HasPage returns a boolean if a field has been set.

### GetPerPage

`func (o *OwnedMediaCitingPromptsResponse) GetPerPage() int32`

GetPerPage returns the PerPage field if non-nil, zero value otherwise.

### GetPerPageOk

`func (o *OwnedMediaCitingPromptsResponse) GetPerPageOk() (*int32, bool)`

GetPerPageOk returns a tuple with the PerPage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPerPage

`func (o *OwnedMediaCitingPromptsResponse) SetPerPage(v int32)`

SetPerPage sets PerPage field to given value.

### HasPerPage

`func (o *OwnedMediaCitingPromptsResponse) HasPerPage() bool`

HasPerPage returns a boolean if a field has been set.

### GetTotal

`func (o *OwnedMediaCitingPromptsResponse) GetTotal() int32`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *OwnedMediaCitingPromptsResponse) GetTotalOk() (*int32, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *OwnedMediaCitingPromptsResponse) SetTotal(v int32)`

SetTotal sets Total field to given value.

### HasTotal

`func (o *OwnedMediaCitingPromptsResponse) HasTotal() bool`

HasTotal returns a boolean if a field has been set.

### GetData

`func (o *OwnedMediaCitingPromptsResponse) GetData() []OwnedMediaCitingAnswer`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *OwnedMediaCitingPromptsResponse) GetDataOk() (*[]OwnedMediaCitingAnswer, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *OwnedMediaCitingPromptsResponse) SetData(v []OwnedMediaCitingAnswer)`

SetData sets Data field to given value.

### HasData

`func (o *OwnedMediaCitingPromptsResponse) HasData() bool`

HasData returns a boolean if a field has been set.

### GetRequestId

`func (o *OwnedMediaCitingPromptsResponse) GetRequestId() string`

GetRequestId returns the RequestId field if non-nil, zero value otherwise.

### GetRequestIdOk

`func (o *OwnedMediaCitingPromptsResponse) GetRequestIdOk() (*string, bool)`

GetRequestIdOk returns a tuple with the RequestId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestId

`func (o *OwnedMediaCitingPromptsResponse) SetRequestId(v string)`

SetRequestId sets RequestId field to given value.

### HasRequestId

`func (o *OwnedMediaCitingPromptsResponse) HasRequestId() bool`

HasRequestId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


