# ProjectDetailsAllOfSearchConsole

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Status** | Pointer to **string** |  | [optional] 
**Property** | Pointer to **NullableString** | The connected property (e.g. sc-domain:example.com), null when not connected | [optional] 
**ConnectUrl** | Pointer to **string** | The in-app page where the property is connected or reconnected (Preferences &gt; Project Settings &gt; Data Connections) | [optional] 

## Methods

### NewProjectDetailsAllOfSearchConsole

`func NewProjectDetailsAllOfSearchConsole() *ProjectDetailsAllOfSearchConsole`

NewProjectDetailsAllOfSearchConsole instantiates a new ProjectDetailsAllOfSearchConsole object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProjectDetailsAllOfSearchConsoleWithDefaults

`func NewProjectDetailsAllOfSearchConsoleWithDefaults() *ProjectDetailsAllOfSearchConsole`

NewProjectDetailsAllOfSearchConsoleWithDefaults instantiates a new ProjectDetailsAllOfSearchConsole object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetStatus

`func (o *ProjectDetailsAllOfSearchConsole) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *ProjectDetailsAllOfSearchConsole) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *ProjectDetailsAllOfSearchConsole) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *ProjectDetailsAllOfSearchConsole) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetProperty

`func (o *ProjectDetailsAllOfSearchConsole) GetProperty() string`

GetProperty returns the Property field if non-nil, zero value otherwise.

### GetPropertyOk

`func (o *ProjectDetailsAllOfSearchConsole) GetPropertyOk() (*string, bool)`

GetPropertyOk returns a tuple with the Property field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProperty

`func (o *ProjectDetailsAllOfSearchConsole) SetProperty(v string)`

SetProperty sets Property field to given value.

### HasProperty

`func (o *ProjectDetailsAllOfSearchConsole) HasProperty() bool`

HasProperty returns a boolean if a field has been set.

### SetPropertyNil

`func (o *ProjectDetailsAllOfSearchConsole) SetPropertyNil(b bool)`

 SetPropertyNil sets the value for Property to be an explicit nil

### UnsetProperty
`func (o *ProjectDetailsAllOfSearchConsole) UnsetProperty()`

UnsetProperty ensures that no value is present for Property, not even an explicit nil
### GetConnectUrl

`func (o *ProjectDetailsAllOfSearchConsole) GetConnectUrl() string`

GetConnectUrl returns the ConnectUrl field if non-nil, zero value otherwise.

### GetConnectUrlOk

`func (o *ProjectDetailsAllOfSearchConsole) GetConnectUrlOk() (*string, bool)`

GetConnectUrlOk returns a tuple with the ConnectUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConnectUrl

`func (o *ProjectDetailsAllOfSearchConsole) SetConnectUrl(v string)`

SetConnectUrl sets ConnectUrl field to given value.

### HasConnectUrl

`func (o *ProjectDetailsAllOfSearchConsole) HasConnectUrl() bool`

HasConnectUrl returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


