# ProjectDetailsAllOfAiTraffic

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Status** | Pointer to **string** |  | [optional] 
**Provider** | Pointer to **NullableString** | The connected provider (e.g. google_analytics, adobe_analytics, adobe_cja, posthog, plausible, matomo, piano), null when not connected | [optional] 
**ConnectUrl** | Pointer to **string** | The in-app AI Traffic page, where the provider is connected or reconnected | [optional] 

## Methods

### NewProjectDetailsAllOfAiTraffic

`func NewProjectDetailsAllOfAiTraffic() *ProjectDetailsAllOfAiTraffic`

NewProjectDetailsAllOfAiTraffic instantiates a new ProjectDetailsAllOfAiTraffic object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProjectDetailsAllOfAiTrafficWithDefaults

`func NewProjectDetailsAllOfAiTrafficWithDefaults() *ProjectDetailsAllOfAiTraffic`

NewProjectDetailsAllOfAiTrafficWithDefaults instantiates a new ProjectDetailsAllOfAiTraffic object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetStatus

`func (o *ProjectDetailsAllOfAiTraffic) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *ProjectDetailsAllOfAiTraffic) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *ProjectDetailsAllOfAiTraffic) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *ProjectDetailsAllOfAiTraffic) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetProvider

`func (o *ProjectDetailsAllOfAiTraffic) GetProvider() string`

GetProvider returns the Provider field if non-nil, zero value otherwise.

### GetProviderOk

`func (o *ProjectDetailsAllOfAiTraffic) GetProviderOk() (*string, bool)`

GetProviderOk returns a tuple with the Provider field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProvider

`func (o *ProjectDetailsAllOfAiTraffic) SetProvider(v string)`

SetProvider sets Provider field to given value.

### HasProvider

`func (o *ProjectDetailsAllOfAiTraffic) HasProvider() bool`

HasProvider returns a boolean if a field has been set.

### SetProviderNil

`func (o *ProjectDetailsAllOfAiTraffic) SetProviderNil(b bool)`

 SetProviderNil sets the value for Provider to be an explicit nil

### UnsetProvider
`func (o *ProjectDetailsAllOfAiTraffic) UnsetProvider()`

UnsetProvider ensures that no value is present for Provider, not even an explicit nil
### GetConnectUrl

`func (o *ProjectDetailsAllOfAiTraffic) GetConnectUrl() string`

GetConnectUrl returns the ConnectUrl field if non-nil, zero value otherwise.

### GetConnectUrlOk

`func (o *ProjectDetailsAllOfAiTraffic) GetConnectUrlOk() (*string, bool)`

GetConnectUrlOk returns a tuple with the ConnectUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConnectUrl

`func (o *ProjectDetailsAllOfAiTraffic) SetConnectUrl(v string)`

SetConnectUrl sets ConnectUrl field to given value.

### HasConnectUrl

`func (o *ProjectDetailsAllOfAiTraffic) HasConnectUrl() bool`

HasConnectUrl returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


