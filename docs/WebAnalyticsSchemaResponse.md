# WebAnalyticsSchemaResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ProjectId** | Pointer to **int32** |  | [optional] 
**Provider** | Pointer to **string** | The connected web analytics provider. | [optional] 
**Property** | Pointer to **string** | The property, site, report suite (rsid:...), data view (dataview:...) or project every query runs on. | [optional] 
**QueryLanguage** | Pointer to **string** | The native query format the provider accepts. | [optional] 
**DocsUrl** | Pointer to **string** | The provider&#39;s reference for that format. | [optional] 
**AllowedFields** | Pointer to **[]string** | Top-level query fields that are forwarded. | [optional] 
**Rules** | Pointer to **[]string** | What the bridge enforces and the provider&#39;s main constraints. | [optional] 
**Example** | Pointer to **map[string]interface{}** | A worked query to adapt. | [optional] 
**Fields** | Pointer to **map[string]interface{}** | The provider&#39;s live field list where it offers one: GA4 dimensions and metrics with custom definitions, Adobe ids, Matomo report methods, PostHog event names, the Plausible catalog. Null when the provider did not return it. | [optional] 
**FieldsUnavailable** | Pointer to **string** | Present when the field list could not be read; the format and example still apply. | [optional] 
**RequestId** | Pointer to **string** |  | [optional] 

## Methods

### NewWebAnalyticsSchemaResponse

`func NewWebAnalyticsSchemaResponse() *WebAnalyticsSchemaResponse`

NewWebAnalyticsSchemaResponse instantiates a new WebAnalyticsSchemaResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewWebAnalyticsSchemaResponseWithDefaults

`func NewWebAnalyticsSchemaResponseWithDefaults() *WebAnalyticsSchemaResponse`

NewWebAnalyticsSchemaResponseWithDefaults instantiates a new WebAnalyticsSchemaResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProjectId

`func (o *WebAnalyticsSchemaResponse) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *WebAnalyticsSchemaResponse) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *WebAnalyticsSchemaResponse) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.

### HasProjectId

`func (o *WebAnalyticsSchemaResponse) HasProjectId() bool`

HasProjectId returns a boolean if a field has been set.

### GetProvider

`func (o *WebAnalyticsSchemaResponse) GetProvider() string`

GetProvider returns the Provider field if non-nil, zero value otherwise.

### GetProviderOk

`func (o *WebAnalyticsSchemaResponse) GetProviderOk() (*string, bool)`

GetProviderOk returns a tuple with the Provider field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProvider

`func (o *WebAnalyticsSchemaResponse) SetProvider(v string)`

SetProvider sets Provider field to given value.

### HasProvider

`func (o *WebAnalyticsSchemaResponse) HasProvider() bool`

HasProvider returns a boolean if a field has been set.

### GetProperty

`func (o *WebAnalyticsSchemaResponse) GetProperty() string`

GetProperty returns the Property field if non-nil, zero value otherwise.

### GetPropertyOk

`func (o *WebAnalyticsSchemaResponse) GetPropertyOk() (*string, bool)`

GetPropertyOk returns a tuple with the Property field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProperty

`func (o *WebAnalyticsSchemaResponse) SetProperty(v string)`

SetProperty sets Property field to given value.

### HasProperty

`func (o *WebAnalyticsSchemaResponse) HasProperty() bool`

HasProperty returns a boolean if a field has been set.

### GetQueryLanguage

`func (o *WebAnalyticsSchemaResponse) GetQueryLanguage() string`

GetQueryLanguage returns the QueryLanguage field if non-nil, zero value otherwise.

### GetQueryLanguageOk

`func (o *WebAnalyticsSchemaResponse) GetQueryLanguageOk() (*string, bool)`

GetQueryLanguageOk returns a tuple with the QueryLanguage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQueryLanguage

`func (o *WebAnalyticsSchemaResponse) SetQueryLanguage(v string)`

SetQueryLanguage sets QueryLanguage field to given value.

### HasQueryLanguage

`func (o *WebAnalyticsSchemaResponse) HasQueryLanguage() bool`

HasQueryLanguage returns a boolean if a field has been set.

### GetDocsUrl

`func (o *WebAnalyticsSchemaResponse) GetDocsUrl() string`

GetDocsUrl returns the DocsUrl field if non-nil, zero value otherwise.

### GetDocsUrlOk

`func (o *WebAnalyticsSchemaResponse) GetDocsUrlOk() (*string, bool)`

GetDocsUrlOk returns a tuple with the DocsUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDocsUrl

`func (o *WebAnalyticsSchemaResponse) SetDocsUrl(v string)`

SetDocsUrl sets DocsUrl field to given value.

### HasDocsUrl

`func (o *WebAnalyticsSchemaResponse) HasDocsUrl() bool`

HasDocsUrl returns a boolean if a field has been set.

### GetAllowedFields

`func (o *WebAnalyticsSchemaResponse) GetAllowedFields() []string`

GetAllowedFields returns the AllowedFields field if non-nil, zero value otherwise.

### GetAllowedFieldsOk

`func (o *WebAnalyticsSchemaResponse) GetAllowedFieldsOk() (*[]string, bool)`

GetAllowedFieldsOk returns a tuple with the AllowedFields field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAllowedFields

`func (o *WebAnalyticsSchemaResponse) SetAllowedFields(v []string)`

SetAllowedFields sets AllowedFields field to given value.

### HasAllowedFields

`func (o *WebAnalyticsSchemaResponse) HasAllowedFields() bool`

HasAllowedFields returns a boolean if a field has been set.

### GetRules

`func (o *WebAnalyticsSchemaResponse) GetRules() []string`

GetRules returns the Rules field if non-nil, zero value otherwise.

### GetRulesOk

`func (o *WebAnalyticsSchemaResponse) GetRulesOk() (*[]string, bool)`

GetRulesOk returns a tuple with the Rules field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRules

`func (o *WebAnalyticsSchemaResponse) SetRules(v []string)`

SetRules sets Rules field to given value.

### HasRules

`func (o *WebAnalyticsSchemaResponse) HasRules() bool`

HasRules returns a boolean if a field has been set.

### GetExample

`func (o *WebAnalyticsSchemaResponse) GetExample() map[string]interface{}`

GetExample returns the Example field if non-nil, zero value otherwise.

### GetExampleOk

`func (o *WebAnalyticsSchemaResponse) GetExampleOk() (*map[string]interface{}, bool)`

GetExampleOk returns a tuple with the Example field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExample

`func (o *WebAnalyticsSchemaResponse) SetExample(v map[string]interface{})`

SetExample sets Example field to given value.

### HasExample

`func (o *WebAnalyticsSchemaResponse) HasExample() bool`

HasExample returns a boolean if a field has been set.

### GetFields

`func (o *WebAnalyticsSchemaResponse) GetFields() map[string]interface{}`

GetFields returns the Fields field if non-nil, zero value otherwise.

### GetFieldsOk

`func (o *WebAnalyticsSchemaResponse) GetFieldsOk() (*map[string]interface{}, bool)`

GetFieldsOk returns a tuple with the Fields field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFields

`func (o *WebAnalyticsSchemaResponse) SetFields(v map[string]interface{})`

SetFields sets Fields field to given value.

### HasFields

`func (o *WebAnalyticsSchemaResponse) HasFields() bool`

HasFields returns a boolean if a field has been set.

### SetFieldsNil

`func (o *WebAnalyticsSchemaResponse) SetFieldsNil(b bool)`

 SetFieldsNil sets the value for Fields to be an explicit nil

### UnsetFields
`func (o *WebAnalyticsSchemaResponse) UnsetFields()`

UnsetFields ensures that no value is present for Fields, not even an explicit nil
### GetFieldsUnavailable

`func (o *WebAnalyticsSchemaResponse) GetFieldsUnavailable() string`

GetFieldsUnavailable returns the FieldsUnavailable field if non-nil, zero value otherwise.

### GetFieldsUnavailableOk

`func (o *WebAnalyticsSchemaResponse) GetFieldsUnavailableOk() (*string, bool)`

GetFieldsUnavailableOk returns a tuple with the FieldsUnavailable field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFieldsUnavailable

`func (o *WebAnalyticsSchemaResponse) SetFieldsUnavailable(v string)`

SetFieldsUnavailable sets FieldsUnavailable field to given value.

### HasFieldsUnavailable

`func (o *WebAnalyticsSchemaResponse) HasFieldsUnavailable() bool`

HasFieldsUnavailable returns a boolean if a field has been set.

### GetRequestId

`func (o *WebAnalyticsSchemaResponse) GetRequestId() string`

GetRequestId returns the RequestId field if non-nil, zero value otherwise.

### GetRequestIdOk

`func (o *WebAnalyticsSchemaResponse) GetRequestIdOk() (*string, bool)`

GetRequestIdOk returns a tuple with the RequestId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestId

`func (o *WebAnalyticsSchemaResponse) SetRequestId(v string)`

SetRequestId sets RequestId field to given value.

### HasRequestId

`func (o *WebAnalyticsSchemaResponse) HasRequestId() bool`

HasRequestId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


