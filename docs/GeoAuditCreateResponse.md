# GeoAuditCreateResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ProjectId** | Pointer to **int32** |  | [optional] 
**Data** | Pointer to [**[]GeoAudit**](GeoAudit.md) |  | [optional] 
**RequestId** | Pointer to **string** |  | [optional] 

## Methods

### NewGeoAuditCreateResponse

`func NewGeoAuditCreateResponse() *GeoAuditCreateResponse`

NewGeoAuditCreateResponse instantiates a new GeoAuditCreateResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGeoAuditCreateResponseWithDefaults

`func NewGeoAuditCreateResponseWithDefaults() *GeoAuditCreateResponse`

NewGeoAuditCreateResponseWithDefaults instantiates a new GeoAuditCreateResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProjectId

`func (o *GeoAuditCreateResponse) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *GeoAuditCreateResponse) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *GeoAuditCreateResponse) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.

### HasProjectId

`func (o *GeoAuditCreateResponse) HasProjectId() bool`

HasProjectId returns a boolean if a field has been set.

### GetData

`func (o *GeoAuditCreateResponse) GetData() []GeoAudit`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *GeoAuditCreateResponse) GetDataOk() (*[]GeoAudit, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *GeoAuditCreateResponse) SetData(v []GeoAudit)`

SetData sets Data field to given value.

### HasData

`func (o *GeoAuditCreateResponse) HasData() bool`

HasData returns a boolean if a field has been set.

### GetRequestId

`func (o *GeoAuditCreateResponse) GetRequestId() string`

GetRequestId returns the RequestId field if non-nil, zero value otherwise.

### GetRequestIdOk

`func (o *GeoAuditCreateResponse) GetRequestIdOk() (*string, bool)`

GetRequestIdOk returns a tuple with the RequestId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestId

`func (o *GeoAuditCreateResponse) SetRequestId(v string)`

SetRequestId sets RequestId field to given value.

### HasRequestId

`func (o *GeoAuditCreateResponse) HasRequestId() bool`

HasRequestId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


