# GeoAuditCreateRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ProjectId** | **int32** |  | 
**Target** | **string** | The domain (site-wide types) or page URL to audit | 
**AuditTypes** | **[]string** | One or more audit types; each becomes its own audit and starts its first run | 
**Cadence** | Pointer to **string** | once (default), weekly or monthly. Weekly and monthly need a type whose checks are tracked and count against the plan limit of recurring audits | [optional] 

## Methods

### NewGeoAuditCreateRequest

`func NewGeoAuditCreateRequest(projectId int32, target string, auditTypes []string, ) *GeoAuditCreateRequest`

NewGeoAuditCreateRequest instantiates a new GeoAuditCreateRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGeoAuditCreateRequestWithDefaults

`func NewGeoAuditCreateRequestWithDefaults() *GeoAuditCreateRequest`

NewGeoAuditCreateRequestWithDefaults instantiates a new GeoAuditCreateRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProjectId

`func (o *GeoAuditCreateRequest) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *GeoAuditCreateRequest) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *GeoAuditCreateRequest) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.


### GetTarget

`func (o *GeoAuditCreateRequest) GetTarget() string`

GetTarget returns the Target field if non-nil, zero value otherwise.

### GetTargetOk

`func (o *GeoAuditCreateRequest) GetTargetOk() (*string, bool)`

GetTargetOk returns a tuple with the Target field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTarget

`func (o *GeoAuditCreateRequest) SetTarget(v string)`

SetTarget sets Target field to given value.


### GetAuditTypes

`func (o *GeoAuditCreateRequest) GetAuditTypes() []string`

GetAuditTypes returns the AuditTypes field if non-nil, zero value otherwise.

### GetAuditTypesOk

`func (o *GeoAuditCreateRequest) GetAuditTypesOk() (*[]string, bool)`

GetAuditTypesOk returns a tuple with the AuditTypes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAuditTypes

`func (o *GeoAuditCreateRequest) SetAuditTypes(v []string)`

SetAuditTypes sets AuditTypes field to given value.


### GetCadence

`func (o *GeoAuditCreateRequest) GetCadence() string`

GetCadence returns the Cadence field if non-nil, zero value otherwise.

### GetCadenceOk

`func (o *GeoAuditCreateRequest) GetCadenceOk() (*string, bool)`

GetCadenceOk returns a tuple with the Cadence field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCadence

`func (o *GeoAuditCreateRequest) SetCadence(v string)`

SetCadence sets Cadence field to given value.

### HasCadence

`func (o *GeoAuditCreateRequest) HasCadence() bool`

HasCadence returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


