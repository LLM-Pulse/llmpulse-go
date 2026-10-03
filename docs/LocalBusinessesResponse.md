# LocalBusinessesResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ProjectId** | Pointer to **int32** |  | [optional] 
**Page** | Pointer to **int32** |  | [optional] 
**PerPage** | Pointer to **int32** |  | [optional] 
**Total** | Pointer to **int32** |  | [optional] 
**Totals** | Pointer to [**LocalBusinessesTotals**](LocalBusinessesTotals.md) |  | [optional] 
**Data** | Pointer to [**[]LocalBusiness**](LocalBusiness.md) |  | [optional] 
**RequestId** | Pointer to **string** |  | [optional] 

## Methods

### NewLocalBusinessesResponse

`func NewLocalBusinessesResponse() *LocalBusinessesResponse`

NewLocalBusinessesResponse instantiates a new LocalBusinessesResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewLocalBusinessesResponseWithDefaults

`func NewLocalBusinessesResponseWithDefaults() *LocalBusinessesResponse`

NewLocalBusinessesResponseWithDefaults instantiates a new LocalBusinessesResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProjectId

`func (o *LocalBusinessesResponse) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *LocalBusinessesResponse) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *LocalBusinessesResponse) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.

### HasProjectId

`func (o *LocalBusinessesResponse) HasProjectId() bool`

HasProjectId returns a boolean if a field has been set.

### GetPage

`func (o *LocalBusinessesResponse) GetPage() int32`

GetPage returns the Page field if non-nil, zero value otherwise.

### GetPageOk

`func (o *LocalBusinessesResponse) GetPageOk() (*int32, bool)`

GetPageOk returns a tuple with the Page field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPage

`func (o *LocalBusinessesResponse) SetPage(v int32)`

SetPage sets Page field to given value.

### HasPage

`func (o *LocalBusinessesResponse) HasPage() bool`

HasPage returns a boolean if a field has been set.

### GetPerPage

`func (o *LocalBusinessesResponse) GetPerPage() int32`

GetPerPage returns the PerPage field if non-nil, zero value otherwise.

### GetPerPageOk

`func (o *LocalBusinessesResponse) GetPerPageOk() (*int32, bool)`

GetPerPageOk returns a tuple with the PerPage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPerPage

`func (o *LocalBusinessesResponse) SetPerPage(v int32)`

SetPerPage sets PerPage field to given value.

### HasPerPage

`func (o *LocalBusinessesResponse) HasPerPage() bool`

HasPerPage returns a boolean if a field has been set.

### GetTotal

`func (o *LocalBusinessesResponse) GetTotal() int32`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *LocalBusinessesResponse) GetTotalOk() (*int32, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *LocalBusinessesResponse) SetTotal(v int32)`

SetTotal sets Total field to given value.

### HasTotal

`func (o *LocalBusinessesResponse) HasTotal() bool`

HasTotal returns a boolean if a field has been set.

### GetTotals

`func (o *LocalBusinessesResponse) GetTotals() LocalBusinessesTotals`

GetTotals returns the Totals field if non-nil, zero value otherwise.

### GetTotalsOk

`func (o *LocalBusinessesResponse) GetTotalsOk() (*LocalBusinessesTotals, bool)`

GetTotalsOk returns a tuple with the Totals field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotals

`func (o *LocalBusinessesResponse) SetTotals(v LocalBusinessesTotals)`

SetTotals sets Totals field to given value.

### HasTotals

`func (o *LocalBusinessesResponse) HasTotals() bool`

HasTotals returns a boolean if a field has been set.

### GetData

`func (o *LocalBusinessesResponse) GetData() []LocalBusiness`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *LocalBusinessesResponse) GetDataOk() (*[]LocalBusiness, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *LocalBusinessesResponse) SetData(v []LocalBusiness)`

SetData sets Data field to given value.

### HasData

`func (o *LocalBusinessesResponse) HasData() bool`

HasData returns a boolean if a field has been set.

### GetRequestId

`func (o *LocalBusinessesResponse) GetRequestId() string`

GetRequestId returns the RequestId field if non-nil, zero value otherwise.

### GetRequestIdOk

`func (o *LocalBusinessesResponse) GetRequestIdOk() (*string, bool)`

GetRequestIdOk returns a tuple with the RequestId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestId

`func (o *LocalBusinessesResponse) SetRequestId(v string)`

SetRequestId sets RequestId field to given value.

### HasRequestId

`func (o *LocalBusinessesResponse) HasRequestId() bool`

HasRequestId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


