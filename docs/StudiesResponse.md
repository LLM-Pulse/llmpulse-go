# StudiesResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Page** | **int32** |  | 
**PerPage** | **int32** |  | 
**Total** | **int32** | Studies matching the filters across every page | 
**Data** | [**[]StudySummary**](StudySummary.md) |  | 
**RequestId** | **string** |  | 

## Methods

### NewStudiesResponse

`func NewStudiesResponse(page int32, perPage int32, total int32, data []StudySummary, requestId string, ) *StudiesResponse`

NewStudiesResponse instantiates a new StudiesResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewStudiesResponseWithDefaults

`func NewStudiesResponseWithDefaults() *StudiesResponse`

NewStudiesResponseWithDefaults instantiates a new StudiesResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPage

`func (o *StudiesResponse) GetPage() int32`

GetPage returns the Page field if non-nil, zero value otherwise.

### GetPageOk

`func (o *StudiesResponse) GetPageOk() (*int32, bool)`

GetPageOk returns a tuple with the Page field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPage

`func (o *StudiesResponse) SetPage(v int32)`

SetPage sets Page field to given value.


### GetPerPage

`func (o *StudiesResponse) GetPerPage() int32`

GetPerPage returns the PerPage field if non-nil, zero value otherwise.

### GetPerPageOk

`func (o *StudiesResponse) GetPerPageOk() (*int32, bool)`

GetPerPageOk returns a tuple with the PerPage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPerPage

`func (o *StudiesResponse) SetPerPage(v int32)`

SetPerPage sets PerPage field to given value.


### GetTotal

`func (o *StudiesResponse) GetTotal() int32`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *StudiesResponse) GetTotalOk() (*int32, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *StudiesResponse) SetTotal(v int32)`

SetTotal sets Total field to given value.


### GetData

`func (o *StudiesResponse) GetData() []StudySummary`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *StudiesResponse) GetDataOk() (*[]StudySummary, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *StudiesResponse) SetData(v []StudySummary)`

SetData sets Data field to given value.


### GetRequestId

`func (o *StudiesResponse) GetRequestId() string`

GetRequestId returns the RequestId field if non-nil, zero value otherwise.

### GetRequestIdOk

`func (o *StudiesResponse) GetRequestIdOk() (*string, bool)`

GetRequestIdOk returns a tuple with the RequestId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestId

`func (o *StudiesResponse) SetRequestId(v string)`

SetRequestId sets RequestId field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


