# CitationsResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ProjectId** | **int32** |  | 
**Page** | **int32** |  | 
**PerPage** | **int32** |  | 
**Total** | **int32** | Rows matching the filters across every page | 
**RequestId** | **string** |  | 
**Data** | [**[]CitationRecord**](CitationRecord.md) |  | 

## Methods

### NewCitationsResponse

`func NewCitationsResponse(projectId int32, page int32, perPage int32, total int32, requestId string, data []CitationRecord, ) *CitationsResponse`

NewCitationsResponse instantiates a new CitationsResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCitationsResponseWithDefaults

`func NewCitationsResponseWithDefaults() *CitationsResponse`

NewCitationsResponseWithDefaults instantiates a new CitationsResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProjectId

`func (o *CitationsResponse) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *CitationsResponse) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *CitationsResponse) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.


### GetPage

`func (o *CitationsResponse) GetPage() int32`

GetPage returns the Page field if non-nil, zero value otherwise.

### GetPageOk

`func (o *CitationsResponse) GetPageOk() (*int32, bool)`

GetPageOk returns a tuple with the Page field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPage

`func (o *CitationsResponse) SetPage(v int32)`

SetPage sets Page field to given value.


### GetPerPage

`func (o *CitationsResponse) GetPerPage() int32`

GetPerPage returns the PerPage field if non-nil, zero value otherwise.

### GetPerPageOk

`func (o *CitationsResponse) GetPerPageOk() (*int32, bool)`

GetPerPageOk returns a tuple with the PerPage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPerPage

`func (o *CitationsResponse) SetPerPage(v int32)`

SetPerPage sets PerPage field to given value.


### GetTotal

`func (o *CitationsResponse) GetTotal() int32`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *CitationsResponse) GetTotalOk() (*int32, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *CitationsResponse) SetTotal(v int32)`

SetTotal sets Total field to given value.


### GetRequestId

`func (o *CitationsResponse) GetRequestId() string`

GetRequestId returns the RequestId field if non-nil, zero value otherwise.

### GetRequestIdOk

`func (o *CitationsResponse) GetRequestIdOk() (*string, bool)`

GetRequestIdOk returns a tuple with the RequestId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestId

`func (o *CitationsResponse) SetRequestId(v string)`

SetRequestId sets RequestId field to given value.


### GetData

`func (o *CitationsResponse) GetData() []CitationRecord`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *CitationsResponse) GetDataOk() (*[]CitationRecord, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *CitationsResponse) SetData(v []CitationRecord)`

SetData sets Data field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


