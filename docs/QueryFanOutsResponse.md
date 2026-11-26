# QueryFanOutsResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ProjectId** | **int32** |  | 
**Page** | **int32** |  | 
**PerPage** | **int32** |  | 
**Total** | **int32** | Rows matching the filters across every page | 
**RequestId** | **string** |  | 
**View** | **string** | query or prompt, the row shape of data | 
**TotalOccurrences** | Pointer to **int32** | Sub-query occurrences across every page (view&#x3D;query) | [optional] 
**Data** | [**[]QueryFanOutRow**](QueryFanOutRow.md) |  | 

## Methods

### NewQueryFanOutsResponse

`func NewQueryFanOutsResponse(projectId int32, page int32, perPage int32, total int32, requestId string, view string, data []QueryFanOutRow, ) *QueryFanOutsResponse`

NewQueryFanOutsResponse instantiates a new QueryFanOutsResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewQueryFanOutsResponseWithDefaults

`func NewQueryFanOutsResponseWithDefaults() *QueryFanOutsResponse`

NewQueryFanOutsResponseWithDefaults instantiates a new QueryFanOutsResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProjectId

`func (o *QueryFanOutsResponse) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *QueryFanOutsResponse) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *QueryFanOutsResponse) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.


### GetPage

`func (o *QueryFanOutsResponse) GetPage() int32`

GetPage returns the Page field if non-nil, zero value otherwise.

### GetPageOk

`func (o *QueryFanOutsResponse) GetPageOk() (*int32, bool)`

GetPageOk returns a tuple with the Page field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPage

`func (o *QueryFanOutsResponse) SetPage(v int32)`

SetPage sets Page field to given value.


### GetPerPage

`func (o *QueryFanOutsResponse) GetPerPage() int32`

GetPerPage returns the PerPage field if non-nil, zero value otherwise.

### GetPerPageOk

`func (o *QueryFanOutsResponse) GetPerPageOk() (*int32, bool)`

GetPerPageOk returns a tuple with the PerPage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPerPage

`func (o *QueryFanOutsResponse) SetPerPage(v int32)`

SetPerPage sets PerPage field to given value.


### GetTotal

`func (o *QueryFanOutsResponse) GetTotal() int32`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *QueryFanOutsResponse) GetTotalOk() (*int32, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *QueryFanOutsResponse) SetTotal(v int32)`

SetTotal sets Total field to given value.


### GetRequestId

`func (o *QueryFanOutsResponse) GetRequestId() string`

GetRequestId returns the RequestId field if non-nil, zero value otherwise.

### GetRequestIdOk

`func (o *QueryFanOutsResponse) GetRequestIdOk() (*string, bool)`

GetRequestIdOk returns a tuple with the RequestId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestId

`func (o *QueryFanOutsResponse) SetRequestId(v string)`

SetRequestId sets RequestId field to given value.


### GetView

`func (o *QueryFanOutsResponse) GetView() string`

GetView returns the View field if non-nil, zero value otherwise.

### GetViewOk

`func (o *QueryFanOutsResponse) GetViewOk() (*string, bool)`

GetViewOk returns a tuple with the View field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetView

`func (o *QueryFanOutsResponse) SetView(v string)`

SetView sets View field to given value.


### GetTotalOccurrences

`func (o *QueryFanOutsResponse) GetTotalOccurrences() int32`

GetTotalOccurrences returns the TotalOccurrences field if non-nil, zero value otherwise.

### GetTotalOccurrencesOk

`func (o *QueryFanOutsResponse) GetTotalOccurrencesOk() (*int32, bool)`

GetTotalOccurrencesOk returns a tuple with the TotalOccurrences field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalOccurrences

`func (o *QueryFanOutsResponse) SetTotalOccurrences(v int32)`

SetTotalOccurrences sets TotalOccurrences field to given value.

### HasTotalOccurrences

`func (o *QueryFanOutsResponse) HasTotalOccurrences() bool`

HasTotalOccurrences returns a boolean if a field has been set.

### GetData

`func (o *QueryFanOutsResponse) GetData() []QueryFanOutRow`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *QueryFanOutsResponse) GetDataOk() (*[]QueryFanOutRow, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *QueryFanOutsResponse) SetData(v []QueryFanOutRow)`

SetData sets Data field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


