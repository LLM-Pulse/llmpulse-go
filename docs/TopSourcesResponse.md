# TopSourcesResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ProjectId** | Pointer to **int32** |  | [optional] 
**From** | Pointer to **time.Time** |  | [optional] 
**To** | Pointer to **time.Time** |  | [optional] 
**Sort** | Pointer to **string** |  | [optional] 
**Page** | Pointer to **int32** |  | [optional] 
**PerPage** | Pointer to **int32** |  | [optional] 
**Total** | Pointer to **int32** |  | [optional] 
**Data** | Pointer to [**[]TopSourcesResponseDataInner**](TopSourcesResponseDataInner.md) |  | [optional] 

## Methods

### NewTopSourcesResponse

`func NewTopSourcesResponse() *TopSourcesResponse`

NewTopSourcesResponse instantiates a new TopSourcesResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTopSourcesResponseWithDefaults

`func NewTopSourcesResponseWithDefaults() *TopSourcesResponse`

NewTopSourcesResponseWithDefaults instantiates a new TopSourcesResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProjectId

`func (o *TopSourcesResponse) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *TopSourcesResponse) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *TopSourcesResponse) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.

### HasProjectId

`func (o *TopSourcesResponse) HasProjectId() bool`

HasProjectId returns a boolean if a field has been set.

### GetFrom

`func (o *TopSourcesResponse) GetFrom() time.Time`

GetFrom returns the From field if non-nil, zero value otherwise.

### GetFromOk

`func (o *TopSourcesResponse) GetFromOk() (*time.Time, bool)`

GetFromOk returns a tuple with the From field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFrom

`func (o *TopSourcesResponse) SetFrom(v time.Time)`

SetFrom sets From field to given value.

### HasFrom

`func (o *TopSourcesResponse) HasFrom() bool`

HasFrom returns a boolean if a field has been set.

### GetTo

`func (o *TopSourcesResponse) GetTo() time.Time`

GetTo returns the To field if non-nil, zero value otherwise.

### GetToOk

`func (o *TopSourcesResponse) GetToOk() (*time.Time, bool)`

GetToOk returns a tuple with the To field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTo

`func (o *TopSourcesResponse) SetTo(v time.Time)`

SetTo sets To field to given value.

### HasTo

`func (o *TopSourcesResponse) HasTo() bool`

HasTo returns a boolean if a field has been set.

### GetSort

`func (o *TopSourcesResponse) GetSort() string`

GetSort returns the Sort field if non-nil, zero value otherwise.

### GetSortOk

`func (o *TopSourcesResponse) GetSortOk() (*string, bool)`

GetSortOk returns a tuple with the Sort field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSort

`func (o *TopSourcesResponse) SetSort(v string)`

SetSort sets Sort field to given value.

### HasSort

`func (o *TopSourcesResponse) HasSort() bool`

HasSort returns a boolean if a field has been set.

### GetPage

`func (o *TopSourcesResponse) GetPage() int32`

GetPage returns the Page field if non-nil, zero value otherwise.

### GetPageOk

`func (o *TopSourcesResponse) GetPageOk() (*int32, bool)`

GetPageOk returns a tuple with the Page field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPage

`func (o *TopSourcesResponse) SetPage(v int32)`

SetPage sets Page field to given value.

### HasPage

`func (o *TopSourcesResponse) HasPage() bool`

HasPage returns a boolean if a field has been set.

### GetPerPage

`func (o *TopSourcesResponse) GetPerPage() int32`

GetPerPage returns the PerPage field if non-nil, zero value otherwise.

### GetPerPageOk

`func (o *TopSourcesResponse) GetPerPageOk() (*int32, bool)`

GetPerPageOk returns a tuple with the PerPage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPerPage

`func (o *TopSourcesResponse) SetPerPage(v int32)`

SetPerPage sets PerPage field to given value.

### HasPerPage

`func (o *TopSourcesResponse) HasPerPage() bool`

HasPerPage returns a boolean if a field has been set.

### GetTotal

`func (o *TopSourcesResponse) GetTotal() int32`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *TopSourcesResponse) GetTotalOk() (*int32, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *TopSourcesResponse) SetTotal(v int32)`

SetTotal sets Total field to given value.

### HasTotal

`func (o *TopSourcesResponse) HasTotal() bool`

HasTotal returns a boolean if a field has been set.

### GetData

`func (o *TopSourcesResponse) GetData() []TopSourcesResponseDataInner`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *TopSourcesResponse) GetDataOk() (*[]TopSourcesResponseDataInner, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *TopSourcesResponse) SetData(v []TopSourcesResponseDataInner)`

SetData sets Data field to given value.

### HasData

`func (o *TopSourcesResponse) HasData() bool`

HasData returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


