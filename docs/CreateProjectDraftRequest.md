# CreateProjectDraftRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**WebsiteUrl** | **string** | Public HTTP(S) URL with a DNS hostname or public IP address. Credentials, private and special IP addresses, localhost and internal hostnames are rejected. | 
**MainCountry** | **string** |  | 
**MainLanguage** | **string** |  | 
**UseSubdomain** | Pointer to **bool** |  | [optional] [default to false]
**Suggest** | Pointer to **bool** |  | [optional] [default to true]
**ExecutePromptsImmediately** | Pointer to **bool** |  | [optional] [default to true]

## Methods

### NewCreateProjectDraftRequest

`func NewCreateProjectDraftRequest(websiteUrl string, mainCountry string, mainLanguage string, ) *CreateProjectDraftRequest`

NewCreateProjectDraftRequest instantiates a new CreateProjectDraftRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateProjectDraftRequestWithDefaults

`func NewCreateProjectDraftRequestWithDefaults() *CreateProjectDraftRequest`

NewCreateProjectDraftRequestWithDefaults instantiates a new CreateProjectDraftRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetWebsiteUrl

`func (o *CreateProjectDraftRequest) GetWebsiteUrl() string`

GetWebsiteUrl returns the WebsiteUrl field if non-nil, zero value otherwise.

### GetWebsiteUrlOk

`func (o *CreateProjectDraftRequest) GetWebsiteUrlOk() (*string, bool)`

GetWebsiteUrlOk returns a tuple with the WebsiteUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWebsiteUrl

`func (o *CreateProjectDraftRequest) SetWebsiteUrl(v string)`

SetWebsiteUrl sets WebsiteUrl field to given value.


### GetMainCountry

`func (o *CreateProjectDraftRequest) GetMainCountry() string`

GetMainCountry returns the MainCountry field if non-nil, zero value otherwise.

### GetMainCountryOk

`func (o *CreateProjectDraftRequest) GetMainCountryOk() (*string, bool)`

GetMainCountryOk returns a tuple with the MainCountry field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMainCountry

`func (o *CreateProjectDraftRequest) SetMainCountry(v string)`

SetMainCountry sets MainCountry field to given value.


### GetMainLanguage

`func (o *CreateProjectDraftRequest) GetMainLanguage() string`

GetMainLanguage returns the MainLanguage field if non-nil, zero value otherwise.

### GetMainLanguageOk

`func (o *CreateProjectDraftRequest) GetMainLanguageOk() (*string, bool)`

GetMainLanguageOk returns a tuple with the MainLanguage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMainLanguage

`func (o *CreateProjectDraftRequest) SetMainLanguage(v string)`

SetMainLanguage sets MainLanguage field to given value.


### GetUseSubdomain

`func (o *CreateProjectDraftRequest) GetUseSubdomain() bool`

GetUseSubdomain returns the UseSubdomain field if non-nil, zero value otherwise.

### GetUseSubdomainOk

`func (o *CreateProjectDraftRequest) GetUseSubdomainOk() (*bool, bool)`

GetUseSubdomainOk returns a tuple with the UseSubdomain field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUseSubdomain

`func (o *CreateProjectDraftRequest) SetUseSubdomain(v bool)`

SetUseSubdomain sets UseSubdomain field to given value.

### HasUseSubdomain

`func (o *CreateProjectDraftRequest) HasUseSubdomain() bool`

HasUseSubdomain returns a boolean if a field has been set.

### GetSuggest

`func (o *CreateProjectDraftRequest) GetSuggest() bool`

GetSuggest returns the Suggest field if non-nil, zero value otherwise.

### GetSuggestOk

`func (o *CreateProjectDraftRequest) GetSuggestOk() (*bool, bool)`

GetSuggestOk returns a tuple with the Suggest field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuggest

`func (o *CreateProjectDraftRequest) SetSuggest(v bool)`

SetSuggest sets Suggest field to given value.

### HasSuggest

`func (o *CreateProjectDraftRequest) HasSuggest() bool`

HasSuggest returns a boolean if a field has been set.

### GetExecutePromptsImmediately

`func (o *CreateProjectDraftRequest) GetExecutePromptsImmediately() bool`

GetExecutePromptsImmediately returns the ExecutePromptsImmediately field if non-nil, zero value otherwise.

### GetExecutePromptsImmediatelyOk

`func (o *CreateProjectDraftRequest) GetExecutePromptsImmediatelyOk() (*bool, bool)`

GetExecutePromptsImmediatelyOk returns a tuple with the ExecutePromptsImmediately field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExecutePromptsImmediately

`func (o *CreateProjectDraftRequest) SetExecutePromptsImmediately(v bool)`

SetExecutePromptsImmediately sets ExecutePromptsImmediately field to given value.

### HasExecutePromptsImmediately

`func (o *CreateProjectDraftRequest) HasExecutePromptsImmediately() bool`

HasExecutePromptsImmediately returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


