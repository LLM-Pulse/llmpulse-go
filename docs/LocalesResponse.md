# LocalesResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ProjectId** | **int32** |  | 
**Countries** | **[]string** | Country codes with data | 
**Languages** | **[]string** | Language codes with data | 
**RequestId** | **string** |  | 

## Methods

### NewLocalesResponse

`func NewLocalesResponse(projectId int32, countries []string, languages []string, requestId string, ) *LocalesResponse`

NewLocalesResponse instantiates a new LocalesResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewLocalesResponseWithDefaults

`func NewLocalesResponseWithDefaults() *LocalesResponse`

NewLocalesResponseWithDefaults instantiates a new LocalesResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProjectId

`func (o *LocalesResponse) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *LocalesResponse) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *LocalesResponse) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.


### GetCountries

`func (o *LocalesResponse) GetCountries() []string`

GetCountries returns the Countries field if non-nil, zero value otherwise.

### GetCountriesOk

`func (o *LocalesResponse) GetCountriesOk() (*[]string, bool)`

GetCountriesOk returns a tuple with the Countries field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountries

`func (o *LocalesResponse) SetCountries(v []string)`

SetCountries sets Countries field to given value.


### GetLanguages

`func (o *LocalesResponse) GetLanguages() []string`

GetLanguages returns the Languages field if non-nil, zero value otherwise.

### GetLanguagesOk

`func (o *LocalesResponse) GetLanguagesOk() (*[]string, bool)`

GetLanguagesOk returns a tuple with the Languages field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLanguages

`func (o *LocalesResponse) SetLanguages(v []string)`

SetLanguages sets Languages field to given value.


### GetRequestId

`func (o *LocalesResponse) GetRequestId() string`

GetRequestId returns the RequestId field if non-nil, zero value otherwise.

### GetRequestIdOk

`func (o *LocalesResponse) GetRequestIdOk() (*string, bool)`

GetRequestIdOk returns a tuple with the RequestId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestId

`func (o *LocalesResponse) SetRequestId(v string)`

SetRequestId sets RequestId field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


