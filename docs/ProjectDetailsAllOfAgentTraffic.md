# ProjectDetailsAllOfAgentTraffic

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Status** | Pointer to **string** |  | [optional] 
**Provider** | Pointer to **NullableString** | The connected source (e.g. cloudflare_graphql, bunny_cdn, s3 or the log drain&#39;s provider), null without a live source | [optional] 
**ConnectUrl** | Pointer to **string** | The in-app Agent Analytics page, where a source is connected or reconnected | [optional] 

## Methods

### NewProjectDetailsAllOfAgentTraffic

`func NewProjectDetailsAllOfAgentTraffic() *ProjectDetailsAllOfAgentTraffic`

NewProjectDetailsAllOfAgentTraffic instantiates a new ProjectDetailsAllOfAgentTraffic object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProjectDetailsAllOfAgentTrafficWithDefaults

`func NewProjectDetailsAllOfAgentTrafficWithDefaults() *ProjectDetailsAllOfAgentTraffic`

NewProjectDetailsAllOfAgentTrafficWithDefaults instantiates a new ProjectDetailsAllOfAgentTraffic object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetStatus

`func (o *ProjectDetailsAllOfAgentTraffic) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *ProjectDetailsAllOfAgentTraffic) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *ProjectDetailsAllOfAgentTraffic) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *ProjectDetailsAllOfAgentTraffic) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetProvider

`func (o *ProjectDetailsAllOfAgentTraffic) GetProvider() string`

GetProvider returns the Provider field if non-nil, zero value otherwise.

### GetProviderOk

`func (o *ProjectDetailsAllOfAgentTraffic) GetProviderOk() (*string, bool)`

GetProviderOk returns a tuple with the Provider field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProvider

`func (o *ProjectDetailsAllOfAgentTraffic) SetProvider(v string)`

SetProvider sets Provider field to given value.

### HasProvider

`func (o *ProjectDetailsAllOfAgentTraffic) HasProvider() bool`

HasProvider returns a boolean if a field has been set.

### SetProviderNil

`func (o *ProjectDetailsAllOfAgentTraffic) SetProviderNil(b bool)`

 SetProviderNil sets the value for Provider to be an explicit nil

### UnsetProvider
`func (o *ProjectDetailsAllOfAgentTraffic) UnsetProvider()`

UnsetProvider ensures that no value is present for Provider, not even an explicit nil
### GetConnectUrl

`func (o *ProjectDetailsAllOfAgentTraffic) GetConnectUrl() string`

GetConnectUrl returns the ConnectUrl field if non-nil, zero value otherwise.

### GetConnectUrlOk

`func (o *ProjectDetailsAllOfAgentTraffic) GetConnectUrlOk() (*string, bool)`

GetConnectUrlOk returns a tuple with the ConnectUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConnectUrl

`func (o *ProjectDetailsAllOfAgentTraffic) SetConnectUrl(v string)`

SetConnectUrl sets ConnectUrl field to given value.

### HasConnectUrl

`func (o *ProjectDetailsAllOfAgentTraffic) HasConnectUrl() bool`

HasConnectUrl returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


