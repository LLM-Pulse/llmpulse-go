# IntelligenceTasksResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ProjectId** | **int32** |  | 
**Page** | **int32** |  | 
**PerPage** | **int32** |  | 
**Total** | **int32** | Rows matching the filters across every page | 
**RequestId** | **string** |  | 
**Data** | [**[]IntelligenceTaskSummary**](IntelligenceTaskSummary.md) |  | 

## Methods

### NewIntelligenceTasksResponse

`func NewIntelligenceTasksResponse(projectId int32, page int32, perPage int32, total int32, requestId string, data []IntelligenceTaskSummary, ) *IntelligenceTasksResponse`

NewIntelligenceTasksResponse instantiates a new IntelligenceTasksResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewIntelligenceTasksResponseWithDefaults

`func NewIntelligenceTasksResponseWithDefaults() *IntelligenceTasksResponse`

NewIntelligenceTasksResponseWithDefaults instantiates a new IntelligenceTasksResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProjectId

`func (o *IntelligenceTasksResponse) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *IntelligenceTasksResponse) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *IntelligenceTasksResponse) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.


### GetPage

`func (o *IntelligenceTasksResponse) GetPage() int32`

GetPage returns the Page field if non-nil, zero value otherwise.

### GetPageOk

`func (o *IntelligenceTasksResponse) GetPageOk() (*int32, bool)`

GetPageOk returns a tuple with the Page field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPage

`func (o *IntelligenceTasksResponse) SetPage(v int32)`

SetPage sets Page field to given value.


### GetPerPage

`func (o *IntelligenceTasksResponse) GetPerPage() int32`

GetPerPage returns the PerPage field if non-nil, zero value otherwise.

### GetPerPageOk

`func (o *IntelligenceTasksResponse) GetPerPageOk() (*int32, bool)`

GetPerPageOk returns a tuple with the PerPage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPerPage

`func (o *IntelligenceTasksResponse) SetPerPage(v int32)`

SetPerPage sets PerPage field to given value.


### GetTotal

`func (o *IntelligenceTasksResponse) GetTotal() int32`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *IntelligenceTasksResponse) GetTotalOk() (*int32, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *IntelligenceTasksResponse) SetTotal(v int32)`

SetTotal sets Total field to given value.


### GetRequestId

`func (o *IntelligenceTasksResponse) GetRequestId() string`

GetRequestId returns the RequestId field if non-nil, zero value otherwise.

### GetRequestIdOk

`func (o *IntelligenceTasksResponse) GetRequestIdOk() (*string, bool)`

GetRequestIdOk returns a tuple with the RequestId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestId

`func (o *IntelligenceTasksResponse) SetRequestId(v string)`

SetRequestId sets RequestId field to given value.


### GetData

`func (o *IntelligenceTasksResponse) GetData() []IntelligenceTaskSummary`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *IntelligenceTasksResponse) GetDataOk() (*[]IntelligenceTaskSummary, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *IntelligenceTasksResponse) SetData(v []IntelligenceTaskSummary)`

SetData sets Data field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


