# CmsContentListResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ProjectId** | Pointer to **int32** |  | [optional] 
**Site** | Pointer to [**CmsSite**](CmsSite.md) |  | [optional] 
**Type** | Pointer to **string** |  | [optional] 
**Status** | Pointer to **string** |  | [optional] 
**Page** | Pointer to **int32** |  | [optional] 
**PerPage** | Pointer to **int32** |  | [optional] 
**Total** | Pointer to **NullableInt32** |  | [optional] 
**TotalPages** | Pointer to **NullableInt32** |  | [optional] 
**Data** | Pointer to [**[]CmsContentSummary**](CmsContentSummary.md) |  | [optional] 
**RequestId** | Pointer to **string** |  | [optional] 

## Methods

### NewCmsContentListResponse

`func NewCmsContentListResponse() *CmsContentListResponse`

NewCmsContentListResponse instantiates a new CmsContentListResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCmsContentListResponseWithDefaults

`func NewCmsContentListResponseWithDefaults() *CmsContentListResponse`

NewCmsContentListResponseWithDefaults instantiates a new CmsContentListResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProjectId

`func (o *CmsContentListResponse) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *CmsContentListResponse) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *CmsContentListResponse) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.

### HasProjectId

`func (o *CmsContentListResponse) HasProjectId() bool`

HasProjectId returns a boolean if a field has been set.

### GetSite

`func (o *CmsContentListResponse) GetSite() CmsSite`

GetSite returns the Site field if non-nil, zero value otherwise.

### GetSiteOk

`func (o *CmsContentListResponse) GetSiteOk() (*CmsSite, bool)`

GetSiteOk returns a tuple with the Site field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSite

`func (o *CmsContentListResponse) SetSite(v CmsSite)`

SetSite sets Site field to given value.

### HasSite

`func (o *CmsContentListResponse) HasSite() bool`

HasSite returns a boolean if a field has been set.

### GetType

`func (o *CmsContentListResponse) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *CmsContentListResponse) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *CmsContentListResponse) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *CmsContentListResponse) HasType() bool`

HasType returns a boolean if a field has been set.

### GetStatus

`func (o *CmsContentListResponse) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *CmsContentListResponse) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *CmsContentListResponse) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *CmsContentListResponse) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetPage

`func (o *CmsContentListResponse) GetPage() int32`

GetPage returns the Page field if non-nil, zero value otherwise.

### GetPageOk

`func (o *CmsContentListResponse) GetPageOk() (*int32, bool)`

GetPageOk returns a tuple with the Page field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPage

`func (o *CmsContentListResponse) SetPage(v int32)`

SetPage sets Page field to given value.

### HasPage

`func (o *CmsContentListResponse) HasPage() bool`

HasPage returns a boolean if a field has been set.

### GetPerPage

`func (o *CmsContentListResponse) GetPerPage() int32`

GetPerPage returns the PerPage field if non-nil, zero value otherwise.

### GetPerPageOk

`func (o *CmsContentListResponse) GetPerPageOk() (*int32, bool)`

GetPerPageOk returns a tuple with the PerPage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPerPage

`func (o *CmsContentListResponse) SetPerPage(v int32)`

SetPerPage sets PerPage field to given value.

### HasPerPage

`func (o *CmsContentListResponse) HasPerPage() bool`

HasPerPage returns a boolean if a field has been set.

### GetTotal

`func (o *CmsContentListResponse) GetTotal() int32`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *CmsContentListResponse) GetTotalOk() (*int32, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *CmsContentListResponse) SetTotal(v int32)`

SetTotal sets Total field to given value.

### HasTotal

`func (o *CmsContentListResponse) HasTotal() bool`

HasTotal returns a boolean if a field has been set.

### SetTotalNil

`func (o *CmsContentListResponse) SetTotalNil(b bool)`

 SetTotalNil sets the value for Total to be an explicit nil

### UnsetTotal
`func (o *CmsContentListResponse) UnsetTotal()`

UnsetTotal ensures that no value is present for Total, not even an explicit nil
### GetTotalPages

`func (o *CmsContentListResponse) GetTotalPages() int32`

GetTotalPages returns the TotalPages field if non-nil, zero value otherwise.

### GetTotalPagesOk

`func (o *CmsContentListResponse) GetTotalPagesOk() (*int32, bool)`

GetTotalPagesOk returns a tuple with the TotalPages field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalPages

`func (o *CmsContentListResponse) SetTotalPages(v int32)`

SetTotalPages sets TotalPages field to given value.

### HasTotalPages

`func (o *CmsContentListResponse) HasTotalPages() bool`

HasTotalPages returns a boolean if a field has been set.

### SetTotalPagesNil

`func (o *CmsContentListResponse) SetTotalPagesNil(b bool)`

 SetTotalPagesNil sets the value for TotalPages to be an explicit nil

### UnsetTotalPages
`func (o *CmsContentListResponse) UnsetTotalPages()`

UnsetTotalPages ensures that no value is present for TotalPages, not even an explicit nil
### GetData

`func (o *CmsContentListResponse) GetData() []CmsContentSummary`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *CmsContentListResponse) GetDataOk() (*[]CmsContentSummary, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *CmsContentListResponse) SetData(v []CmsContentSummary)`

SetData sets Data field to given value.

### HasData

`func (o *CmsContentListResponse) HasData() bool`

HasData returns a boolean if a field has been set.

### GetRequestId

`func (o *CmsContentListResponse) GetRequestId() string`

GetRequestId returns the RequestId field if non-nil, zero value otherwise.

### GetRequestIdOk

`func (o *CmsContentListResponse) GetRequestIdOk() (*string, bool)`

GetRequestIdOk returns a tuple with the RequestId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestId

`func (o *CmsContentListResponse) SetRequestId(v string)`

SetRequestId sets RequestId field to given value.

### HasRequestId

`func (o *CmsContentListResponse) HasRequestId() bool`

HasRequestId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


