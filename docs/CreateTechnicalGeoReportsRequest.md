# CreateTechnicalGeoReportsRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ProjectId** | **int32** |  | 
**Url** | **string** |  | 
**CountryCode** | Pointer to **string** | Defaults to the project country | [optional] 

## Methods

### NewCreateTechnicalGeoReportsRequest

`func NewCreateTechnicalGeoReportsRequest(projectId int32, url string, ) *CreateTechnicalGeoReportsRequest`

NewCreateTechnicalGeoReportsRequest instantiates a new CreateTechnicalGeoReportsRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateTechnicalGeoReportsRequestWithDefaults

`func NewCreateTechnicalGeoReportsRequestWithDefaults() *CreateTechnicalGeoReportsRequest`

NewCreateTechnicalGeoReportsRequestWithDefaults instantiates a new CreateTechnicalGeoReportsRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProjectId

`func (o *CreateTechnicalGeoReportsRequest) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *CreateTechnicalGeoReportsRequest) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *CreateTechnicalGeoReportsRequest) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.


### GetUrl

`func (o *CreateTechnicalGeoReportsRequest) GetUrl() string`

GetUrl returns the Url field if non-nil, zero value otherwise.

### GetUrlOk

`func (o *CreateTechnicalGeoReportsRequest) GetUrlOk() (*string, bool)`

GetUrlOk returns a tuple with the Url field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrl

`func (o *CreateTechnicalGeoReportsRequest) SetUrl(v string)`

SetUrl sets Url field to given value.


### GetCountryCode

`func (o *CreateTechnicalGeoReportsRequest) GetCountryCode() string`

GetCountryCode returns the CountryCode field if non-nil, zero value otherwise.

### GetCountryCodeOk

`func (o *CreateTechnicalGeoReportsRequest) GetCountryCodeOk() (*string, bool)`

GetCountryCodeOk returns a tuple with the CountryCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountryCode

`func (o *CreateTechnicalGeoReportsRequest) SetCountryCode(v string)`

SetCountryCode sets CountryCode field to given value.

### HasCountryCode

`func (o *CreateTechnicalGeoReportsRequest) HasCountryCode() bool`

HasCountryCode returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


