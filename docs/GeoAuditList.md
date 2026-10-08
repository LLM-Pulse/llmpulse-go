# GeoAuditList

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ProjectId** | Pointer to **int32** |  | [optional] 
**Page** | Pointer to **int32** |  | [optional] 
**PerPage** | Pointer to **int32** |  | [optional] 
**Total** | Pointer to **int32** |  | [optional] 
**Data** | Pointer to [**[]GeoAudit**](GeoAudit.md) |  | [optional] 
**RequestId** | Pointer to **string** |  | [optional] 

## Methods

### NewGeoAuditList

`func NewGeoAuditList() *GeoAuditList`

NewGeoAuditList instantiates a new GeoAuditList object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGeoAuditListWithDefaults

`func NewGeoAuditListWithDefaults() *GeoAuditList`

NewGeoAuditListWithDefaults instantiates a new GeoAuditList object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProjectId

`func (o *GeoAuditList) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *GeoAuditList) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *GeoAuditList) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.

### HasProjectId

`func (o *GeoAuditList) HasProjectId() bool`

HasProjectId returns a boolean if a field has been set.

### GetPage

`func (o *GeoAuditList) GetPage() int32`

GetPage returns the Page field if non-nil, zero value otherwise.

### GetPageOk

`func (o *GeoAuditList) GetPageOk() (*int32, bool)`

GetPageOk returns a tuple with the Page field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPage

`func (o *GeoAuditList) SetPage(v int32)`

SetPage sets Page field to given value.

### HasPage

`func (o *GeoAuditList) HasPage() bool`

HasPage returns a boolean if a field has been set.

### GetPerPage

`func (o *GeoAuditList) GetPerPage() int32`

GetPerPage returns the PerPage field if non-nil, zero value otherwise.

### GetPerPageOk

`func (o *GeoAuditList) GetPerPageOk() (*int32, bool)`

GetPerPageOk returns a tuple with the PerPage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPerPage

`func (o *GeoAuditList) SetPerPage(v int32)`

SetPerPage sets PerPage field to given value.

### HasPerPage

`func (o *GeoAuditList) HasPerPage() bool`

HasPerPage returns a boolean if a field has been set.

### GetTotal

`func (o *GeoAuditList) GetTotal() int32`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *GeoAuditList) GetTotalOk() (*int32, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *GeoAuditList) SetTotal(v int32)`

SetTotal sets Total field to given value.

### HasTotal

`func (o *GeoAuditList) HasTotal() bool`

HasTotal returns a boolean if a field has been set.

### GetData

`func (o *GeoAuditList) GetData() []GeoAudit`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *GeoAuditList) GetDataOk() (*[]GeoAudit, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *GeoAuditList) SetData(v []GeoAudit)`

SetData sets Data field to given value.

### HasData

`func (o *GeoAuditList) HasData() bool`

HasData returns a boolean if a field has been set.

### GetRequestId

`func (o *GeoAuditList) GetRequestId() string`

GetRequestId returns the RequestId field if non-nil, zero value otherwise.

### GetRequestIdOk

`func (o *GeoAuditList) GetRequestIdOk() (*string, bool)`

GetRequestIdOk returns a tuple with the RequestId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestId

`func (o *GeoAuditList) SetRequestId(v string)`

SetRequestId sets RequestId field to given value.

### HasRequestId

`func (o *GeoAuditList) HasRequestId() bool`

HasRequestId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


