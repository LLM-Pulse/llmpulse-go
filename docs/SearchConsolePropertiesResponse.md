# SearchConsolePropertiesResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ProjectId** | Pointer to **int32** |  | [optional] 
**MaxProperties** | Pointer to **int32** | How many properties a project can connect | [optional] 
**Data** | Pointer to [**[]SearchConsolePropertiesResponseDataInner**](SearchConsolePropertiesResponseDataInner.md) |  | [optional] 
**RequestId** | Pointer to **string** |  | [optional] 

## Methods

### NewSearchConsolePropertiesResponse

`func NewSearchConsolePropertiesResponse() *SearchConsolePropertiesResponse`

NewSearchConsolePropertiesResponse instantiates a new SearchConsolePropertiesResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSearchConsolePropertiesResponseWithDefaults

`func NewSearchConsolePropertiesResponseWithDefaults() *SearchConsolePropertiesResponse`

NewSearchConsolePropertiesResponseWithDefaults instantiates a new SearchConsolePropertiesResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProjectId

`func (o *SearchConsolePropertiesResponse) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *SearchConsolePropertiesResponse) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *SearchConsolePropertiesResponse) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.

### HasProjectId

`func (o *SearchConsolePropertiesResponse) HasProjectId() bool`

HasProjectId returns a boolean if a field has been set.

### GetMaxProperties

`func (o *SearchConsolePropertiesResponse) GetMaxProperties() int32`

GetMaxProperties returns the MaxProperties field if non-nil, zero value otherwise.

### GetMaxPropertiesOk

`func (o *SearchConsolePropertiesResponse) GetMaxPropertiesOk() (*int32, bool)`

GetMaxPropertiesOk returns a tuple with the MaxProperties field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxProperties

`func (o *SearchConsolePropertiesResponse) SetMaxProperties(v int32)`

SetMaxProperties sets MaxProperties field to given value.

### HasMaxProperties

`func (o *SearchConsolePropertiesResponse) HasMaxProperties() bool`

HasMaxProperties returns a boolean if a field has been set.

### GetData

`func (o *SearchConsolePropertiesResponse) GetData() []SearchConsolePropertiesResponseDataInner`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *SearchConsolePropertiesResponse) GetDataOk() (*[]SearchConsolePropertiesResponseDataInner, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *SearchConsolePropertiesResponse) SetData(v []SearchConsolePropertiesResponseDataInner)`

SetData sets Data field to given value.

### HasData

`func (o *SearchConsolePropertiesResponse) HasData() bool`

HasData returns a boolean if a field has been set.

### GetRequestId

`func (o *SearchConsolePropertiesResponse) GetRequestId() string`

GetRequestId returns the RequestId field if non-nil, zero value otherwise.

### GetRequestIdOk

`func (o *SearchConsolePropertiesResponse) GetRequestIdOk() (*string, bool)`

GetRequestIdOk returns a tuple with the RequestId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestId

`func (o *SearchConsolePropertiesResponse) SetRequestId(v string)`

SetRequestId sets RequestId field to given value.

### HasRequestId

`func (o *SearchConsolePropertiesResponse) HasRequestId() bool`

HasRequestId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


