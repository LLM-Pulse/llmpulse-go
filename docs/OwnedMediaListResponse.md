# OwnedMediaListResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ProjectId** | Pointer to **int32** |  | [optional] 
**Provider** | Pointer to **string** |  | [optional] 
**View** | Pointer to **string** |  | [optional] 
**Store** | Pointer to **string** | provider&#x3D;mobile_apps only | [optional] 
**From** | Pointer to **time.Time** |  | [optional] 
**To** | Pointer to **time.Time** |  | [optional] 
**Page** | Pointer to **int32** |  | [optional] 
**PerPage** | Pointer to **int32** |  | [optional] 
**Total** | Pointer to **int32** |  | [optional] 
**Data** | Pointer to [**[]OwnedMediaRow**](OwnedMediaRow.md) |  | [optional] 
**RequestId** | Pointer to **string** |  | [optional] 

## Methods

### NewOwnedMediaListResponse

`func NewOwnedMediaListResponse() *OwnedMediaListResponse`

NewOwnedMediaListResponse instantiates a new OwnedMediaListResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOwnedMediaListResponseWithDefaults

`func NewOwnedMediaListResponseWithDefaults() *OwnedMediaListResponse`

NewOwnedMediaListResponseWithDefaults instantiates a new OwnedMediaListResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProjectId

`func (o *OwnedMediaListResponse) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *OwnedMediaListResponse) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *OwnedMediaListResponse) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.

### HasProjectId

`func (o *OwnedMediaListResponse) HasProjectId() bool`

HasProjectId returns a boolean if a field has been set.

### GetProvider

`func (o *OwnedMediaListResponse) GetProvider() string`

GetProvider returns the Provider field if non-nil, zero value otherwise.

### GetProviderOk

`func (o *OwnedMediaListResponse) GetProviderOk() (*string, bool)`

GetProviderOk returns a tuple with the Provider field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProvider

`func (o *OwnedMediaListResponse) SetProvider(v string)`

SetProvider sets Provider field to given value.

### HasProvider

`func (o *OwnedMediaListResponse) HasProvider() bool`

HasProvider returns a boolean if a field has been set.

### GetView

`func (o *OwnedMediaListResponse) GetView() string`

GetView returns the View field if non-nil, zero value otherwise.

### GetViewOk

`func (o *OwnedMediaListResponse) GetViewOk() (*string, bool)`

GetViewOk returns a tuple with the View field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetView

`func (o *OwnedMediaListResponse) SetView(v string)`

SetView sets View field to given value.

### HasView

`func (o *OwnedMediaListResponse) HasView() bool`

HasView returns a boolean if a field has been set.

### GetStore

`func (o *OwnedMediaListResponse) GetStore() string`

GetStore returns the Store field if non-nil, zero value otherwise.

### GetStoreOk

`func (o *OwnedMediaListResponse) GetStoreOk() (*string, bool)`

GetStoreOk returns a tuple with the Store field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStore

`func (o *OwnedMediaListResponse) SetStore(v string)`

SetStore sets Store field to given value.

### HasStore

`func (o *OwnedMediaListResponse) HasStore() bool`

HasStore returns a boolean if a field has been set.

### GetFrom

`func (o *OwnedMediaListResponse) GetFrom() time.Time`

GetFrom returns the From field if non-nil, zero value otherwise.

### GetFromOk

`func (o *OwnedMediaListResponse) GetFromOk() (*time.Time, bool)`

GetFromOk returns a tuple with the From field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFrom

`func (o *OwnedMediaListResponse) SetFrom(v time.Time)`

SetFrom sets From field to given value.

### HasFrom

`func (o *OwnedMediaListResponse) HasFrom() bool`

HasFrom returns a boolean if a field has been set.

### GetTo

`func (o *OwnedMediaListResponse) GetTo() time.Time`

GetTo returns the To field if non-nil, zero value otherwise.

### GetToOk

`func (o *OwnedMediaListResponse) GetToOk() (*time.Time, bool)`

GetToOk returns a tuple with the To field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTo

`func (o *OwnedMediaListResponse) SetTo(v time.Time)`

SetTo sets To field to given value.

### HasTo

`func (o *OwnedMediaListResponse) HasTo() bool`

HasTo returns a boolean if a field has been set.

### GetPage

`func (o *OwnedMediaListResponse) GetPage() int32`

GetPage returns the Page field if non-nil, zero value otherwise.

### GetPageOk

`func (o *OwnedMediaListResponse) GetPageOk() (*int32, bool)`

GetPageOk returns a tuple with the Page field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPage

`func (o *OwnedMediaListResponse) SetPage(v int32)`

SetPage sets Page field to given value.

### HasPage

`func (o *OwnedMediaListResponse) HasPage() bool`

HasPage returns a boolean if a field has been set.

### GetPerPage

`func (o *OwnedMediaListResponse) GetPerPage() int32`

GetPerPage returns the PerPage field if non-nil, zero value otherwise.

### GetPerPageOk

`func (o *OwnedMediaListResponse) GetPerPageOk() (*int32, bool)`

GetPerPageOk returns a tuple with the PerPage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPerPage

`func (o *OwnedMediaListResponse) SetPerPage(v int32)`

SetPerPage sets PerPage field to given value.

### HasPerPage

`func (o *OwnedMediaListResponse) HasPerPage() bool`

HasPerPage returns a boolean if a field has been set.

### GetTotal

`func (o *OwnedMediaListResponse) GetTotal() int32`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *OwnedMediaListResponse) GetTotalOk() (*int32, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *OwnedMediaListResponse) SetTotal(v int32)`

SetTotal sets Total field to given value.

### HasTotal

`func (o *OwnedMediaListResponse) HasTotal() bool`

HasTotal returns a boolean if a field has been set.

### GetData

`func (o *OwnedMediaListResponse) GetData() []OwnedMediaRow`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *OwnedMediaListResponse) GetDataOk() (*[]OwnedMediaRow, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *OwnedMediaListResponse) SetData(v []OwnedMediaRow)`

SetData sets Data field to given value.

### HasData

`func (o *OwnedMediaListResponse) HasData() bool`

HasData returns a boolean if a field has been set.

### GetRequestId

`func (o *OwnedMediaListResponse) GetRequestId() string`

GetRequestId returns the RequestId field if non-nil, zero value otherwise.

### GetRequestIdOk

`func (o *OwnedMediaListResponse) GetRequestIdOk() (*string, bool)`

GetRequestIdOk returns a tuple with the RequestId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestId

`func (o *OwnedMediaListResponse) SetRequestId(v string)`

SetRequestId sets RequestId field to given value.

### HasRequestId

`func (o *OwnedMediaListResponse) HasRequestId() bool`

HasRequestId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


