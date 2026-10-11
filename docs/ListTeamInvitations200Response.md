# ListTeamInvitations200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Page** | Pointer to **int32** |  | [optional] 
**PerPage** | Pointer to **int32** |  | [optional] 
**Total** | Pointer to **int32** |  | [optional] 
**Data** | Pointer to [**[]TeamInvitation**](TeamInvitation.md) |  | [optional] 
**RequestId** | Pointer to **string** |  | [optional] 

## Methods

### NewListTeamInvitations200Response

`func NewListTeamInvitations200Response() *ListTeamInvitations200Response`

NewListTeamInvitations200Response instantiates a new ListTeamInvitations200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewListTeamInvitations200ResponseWithDefaults

`func NewListTeamInvitations200ResponseWithDefaults() *ListTeamInvitations200Response`

NewListTeamInvitations200ResponseWithDefaults instantiates a new ListTeamInvitations200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPage

`func (o *ListTeamInvitations200Response) GetPage() int32`

GetPage returns the Page field if non-nil, zero value otherwise.

### GetPageOk

`func (o *ListTeamInvitations200Response) GetPageOk() (*int32, bool)`

GetPageOk returns a tuple with the Page field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPage

`func (o *ListTeamInvitations200Response) SetPage(v int32)`

SetPage sets Page field to given value.

### HasPage

`func (o *ListTeamInvitations200Response) HasPage() bool`

HasPage returns a boolean if a field has been set.

### GetPerPage

`func (o *ListTeamInvitations200Response) GetPerPage() int32`

GetPerPage returns the PerPage field if non-nil, zero value otherwise.

### GetPerPageOk

`func (o *ListTeamInvitations200Response) GetPerPageOk() (*int32, bool)`

GetPerPageOk returns a tuple with the PerPage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPerPage

`func (o *ListTeamInvitations200Response) SetPerPage(v int32)`

SetPerPage sets PerPage field to given value.

### HasPerPage

`func (o *ListTeamInvitations200Response) HasPerPage() bool`

HasPerPage returns a boolean if a field has been set.

### GetTotal

`func (o *ListTeamInvitations200Response) GetTotal() int32`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *ListTeamInvitations200Response) GetTotalOk() (*int32, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *ListTeamInvitations200Response) SetTotal(v int32)`

SetTotal sets Total field to given value.

### HasTotal

`func (o *ListTeamInvitations200Response) HasTotal() bool`

HasTotal returns a boolean if a field has been set.

### GetData

`func (o *ListTeamInvitations200Response) GetData() []TeamInvitation`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *ListTeamInvitations200Response) GetDataOk() (*[]TeamInvitation, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *ListTeamInvitations200Response) SetData(v []TeamInvitation)`

SetData sets Data field to given value.

### HasData

`func (o *ListTeamInvitations200Response) HasData() bool`

HasData returns a boolean if a field has been set.

### GetRequestId

`func (o *ListTeamInvitations200Response) GetRequestId() string`

GetRequestId returns the RequestId field if non-nil, zero value otherwise.

### GetRequestIdOk

`func (o *ListTeamInvitations200Response) GetRequestIdOk() (*string, bool)`

GetRequestIdOk returns a tuple with the RequestId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestId

`func (o *ListTeamInvitations200Response) SetRequestId(v string)`

SetRequestId sets RequestId field to given value.

### HasRequestId

`func (o *ListTeamInvitations200Response) HasRequestId() bool`

HasRequestId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


