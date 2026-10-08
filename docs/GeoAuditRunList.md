# GeoAuditRunList

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ProjectId** | Pointer to **int32** |  | [optional] 
**Page** | Pointer to **int32** |  | [optional] 
**PerPage** | Pointer to **int32** |  | [optional] 
**Total** | Pointer to **int32** |  | [optional] 
**Data** | Pointer to [**[]GeoAuditRun**](GeoAuditRun.md) |  | [optional] 
**RequestId** | Pointer to **string** |  | [optional] 

## Methods

### NewGeoAuditRunList

`func NewGeoAuditRunList() *GeoAuditRunList`

NewGeoAuditRunList instantiates a new GeoAuditRunList object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGeoAuditRunListWithDefaults

`func NewGeoAuditRunListWithDefaults() *GeoAuditRunList`

NewGeoAuditRunListWithDefaults instantiates a new GeoAuditRunList object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProjectId

`func (o *GeoAuditRunList) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *GeoAuditRunList) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *GeoAuditRunList) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.

### HasProjectId

`func (o *GeoAuditRunList) HasProjectId() bool`

HasProjectId returns a boolean if a field has been set.

### GetPage

`func (o *GeoAuditRunList) GetPage() int32`

GetPage returns the Page field if non-nil, zero value otherwise.

### GetPageOk

`func (o *GeoAuditRunList) GetPageOk() (*int32, bool)`

GetPageOk returns a tuple with the Page field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPage

`func (o *GeoAuditRunList) SetPage(v int32)`

SetPage sets Page field to given value.

### HasPage

`func (o *GeoAuditRunList) HasPage() bool`

HasPage returns a boolean if a field has been set.

### GetPerPage

`func (o *GeoAuditRunList) GetPerPage() int32`

GetPerPage returns the PerPage field if non-nil, zero value otherwise.

### GetPerPageOk

`func (o *GeoAuditRunList) GetPerPageOk() (*int32, bool)`

GetPerPageOk returns a tuple with the PerPage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPerPage

`func (o *GeoAuditRunList) SetPerPage(v int32)`

SetPerPage sets PerPage field to given value.

### HasPerPage

`func (o *GeoAuditRunList) HasPerPage() bool`

HasPerPage returns a boolean if a field has been set.

### GetTotal

`func (o *GeoAuditRunList) GetTotal() int32`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *GeoAuditRunList) GetTotalOk() (*int32, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *GeoAuditRunList) SetTotal(v int32)`

SetTotal sets Total field to given value.

### HasTotal

`func (o *GeoAuditRunList) HasTotal() bool`

HasTotal returns a boolean if a field has been set.

### GetData

`func (o *GeoAuditRunList) GetData() []GeoAuditRun`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *GeoAuditRunList) GetDataOk() (*[]GeoAuditRun, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *GeoAuditRunList) SetData(v []GeoAuditRun)`

SetData sets Data field to given value.

### HasData

`func (o *GeoAuditRunList) HasData() bool`

HasData returns a boolean if a field has been set.

### GetRequestId

`func (o *GeoAuditRunList) GetRequestId() string`

GetRequestId returns the RequestId field if non-nil, zero value otherwise.

### GetRequestIdOk

`func (o *GeoAuditRunList) GetRequestIdOk() (*string, bool)`

GetRequestIdOk returns a tuple with the RequestId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestId

`func (o *GeoAuditRunList) SetRequestId(v string)`

SetRequestId sets RequestId field to given value.

### HasRequestId

`func (o *GeoAuditRunList) HasRequestId() bool`

HasRequestId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


