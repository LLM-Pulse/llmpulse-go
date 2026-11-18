# UrlListsResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ProjectId** | **int32** |  | 
**Filters** | [**UrlListFilters**](UrlListFilters.md) |  | 
**Total** | **int32** |  | 
**Data** | [**[]UrlListWithStats**](UrlListWithStats.md) |  | 
**RequestId** | **string** |  | 

## Methods

### NewUrlListsResponse

`func NewUrlListsResponse(projectId int32, filters UrlListFilters, total int32, data []UrlListWithStats, requestId string, ) *UrlListsResponse`

NewUrlListsResponse instantiates a new UrlListsResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUrlListsResponseWithDefaults

`func NewUrlListsResponseWithDefaults() *UrlListsResponse`

NewUrlListsResponseWithDefaults instantiates a new UrlListsResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProjectId

`func (o *UrlListsResponse) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *UrlListsResponse) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *UrlListsResponse) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.


### GetFilters

`func (o *UrlListsResponse) GetFilters() UrlListFilters`

GetFilters returns the Filters field if non-nil, zero value otherwise.

### GetFiltersOk

`func (o *UrlListsResponse) GetFiltersOk() (*UrlListFilters, bool)`

GetFiltersOk returns a tuple with the Filters field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFilters

`func (o *UrlListsResponse) SetFilters(v UrlListFilters)`

SetFilters sets Filters field to given value.


### GetTotal

`func (o *UrlListsResponse) GetTotal() int32`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *UrlListsResponse) GetTotalOk() (*int32, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *UrlListsResponse) SetTotal(v int32)`

SetTotal sets Total field to given value.


### GetData

`func (o *UrlListsResponse) GetData() []UrlListWithStats`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *UrlListsResponse) GetDataOk() (*[]UrlListWithStats, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *UrlListsResponse) SetData(v []UrlListWithStats)`

SetData sets Data field to given value.


### GetRequestId

`func (o *UrlListsResponse) GetRequestId() string`

GetRequestId returns the RequestId field if non-nil, zero value otherwise.

### GetRequestIdOk

`func (o *UrlListsResponse) GetRequestIdOk() (*string, bool)`

GetRequestIdOk returns a tuple with the RequestId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestId

`func (o *UrlListsResponse) SetRequestId(v string)`

SetRequestId sets RequestId field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


