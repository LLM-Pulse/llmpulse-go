# ShoppingResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ProjectId** | **int32** |  | 
**Page** | **int32** |  | 
**PerPage** | **int32** |  | 
**Total** | **int32** | Rows matching the filters across every page | 
**RequestId** | **string** |  | 
**View** | **string** | products or merchants | 
**Totals** | [**ShoppingTotals**](ShoppingTotals.md) |  | 
**Data** | [**[]ShoppingRow**](ShoppingRow.md) |  | 

## Methods

### NewShoppingResponse

`func NewShoppingResponse(projectId int32, page int32, perPage int32, total int32, requestId string, view string, totals ShoppingTotals, data []ShoppingRow, ) *ShoppingResponse`

NewShoppingResponse instantiates a new ShoppingResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewShoppingResponseWithDefaults

`func NewShoppingResponseWithDefaults() *ShoppingResponse`

NewShoppingResponseWithDefaults instantiates a new ShoppingResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProjectId

`func (o *ShoppingResponse) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *ShoppingResponse) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *ShoppingResponse) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.


### GetPage

`func (o *ShoppingResponse) GetPage() int32`

GetPage returns the Page field if non-nil, zero value otherwise.

### GetPageOk

`func (o *ShoppingResponse) GetPageOk() (*int32, bool)`

GetPageOk returns a tuple with the Page field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPage

`func (o *ShoppingResponse) SetPage(v int32)`

SetPage sets Page field to given value.


### GetPerPage

`func (o *ShoppingResponse) GetPerPage() int32`

GetPerPage returns the PerPage field if non-nil, zero value otherwise.

### GetPerPageOk

`func (o *ShoppingResponse) GetPerPageOk() (*int32, bool)`

GetPerPageOk returns a tuple with the PerPage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPerPage

`func (o *ShoppingResponse) SetPerPage(v int32)`

SetPerPage sets PerPage field to given value.


### GetTotal

`func (o *ShoppingResponse) GetTotal() int32`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *ShoppingResponse) GetTotalOk() (*int32, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *ShoppingResponse) SetTotal(v int32)`

SetTotal sets Total field to given value.


### GetRequestId

`func (o *ShoppingResponse) GetRequestId() string`

GetRequestId returns the RequestId field if non-nil, zero value otherwise.

### GetRequestIdOk

`func (o *ShoppingResponse) GetRequestIdOk() (*string, bool)`

GetRequestIdOk returns a tuple with the RequestId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestId

`func (o *ShoppingResponse) SetRequestId(v string)`

SetRequestId sets RequestId field to given value.


### GetView

`func (o *ShoppingResponse) GetView() string`

GetView returns the View field if non-nil, zero value otherwise.

### GetViewOk

`func (o *ShoppingResponse) GetViewOk() (*string, bool)`

GetViewOk returns a tuple with the View field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetView

`func (o *ShoppingResponse) SetView(v string)`

SetView sets View field to given value.


### GetTotals

`func (o *ShoppingResponse) GetTotals() ShoppingTotals`

GetTotals returns the Totals field if non-nil, zero value otherwise.

### GetTotalsOk

`func (o *ShoppingResponse) GetTotalsOk() (*ShoppingTotals, bool)`

GetTotalsOk returns a tuple with the Totals field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotals

`func (o *ShoppingResponse) SetTotals(v ShoppingTotals)`

SetTotals sets Totals field to given value.


### GetData

`func (o *ShoppingResponse) GetData() []ShoppingRow`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *ShoppingResponse) GetDataOk() (*[]ShoppingRow, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *ShoppingResponse) SetData(v []ShoppingRow)`

SetData sets Data field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


