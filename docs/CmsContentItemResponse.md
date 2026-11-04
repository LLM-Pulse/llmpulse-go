# CmsContentItemResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ProjectId** | Pointer to **int32** |  | [optional] 
**Site** | Pointer to [**CmsSite**](CmsSite.md) |  | [optional] 
**Data** | Pointer to [**CmsContentItem**](CmsContentItem.md) |  | [optional] 
**RequestId** | Pointer to **string** |  | [optional] 

## Methods

### NewCmsContentItemResponse

`func NewCmsContentItemResponse() *CmsContentItemResponse`

NewCmsContentItemResponse instantiates a new CmsContentItemResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCmsContentItemResponseWithDefaults

`func NewCmsContentItemResponseWithDefaults() *CmsContentItemResponse`

NewCmsContentItemResponseWithDefaults instantiates a new CmsContentItemResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProjectId

`func (o *CmsContentItemResponse) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *CmsContentItemResponse) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *CmsContentItemResponse) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.

### HasProjectId

`func (o *CmsContentItemResponse) HasProjectId() bool`

HasProjectId returns a boolean if a field has been set.

### GetSite

`func (o *CmsContentItemResponse) GetSite() CmsSite`

GetSite returns the Site field if non-nil, zero value otherwise.

### GetSiteOk

`func (o *CmsContentItemResponse) GetSiteOk() (*CmsSite, bool)`

GetSiteOk returns a tuple with the Site field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSite

`func (o *CmsContentItemResponse) SetSite(v CmsSite)`

SetSite sets Site field to given value.

### HasSite

`func (o *CmsContentItemResponse) HasSite() bool`

HasSite returns a boolean if a field has been set.

### GetData

`func (o *CmsContentItemResponse) GetData() CmsContentItem`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *CmsContentItemResponse) GetDataOk() (*CmsContentItem, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *CmsContentItemResponse) SetData(v CmsContentItem)`

SetData sets Data field to given value.

### HasData

`func (o *CmsContentItemResponse) HasData() bool`

HasData returns a boolean if a field has been set.

### GetRequestId

`func (o *CmsContentItemResponse) GetRequestId() string`

GetRequestId returns the RequestId field if non-nil, zero value otherwise.

### GetRequestIdOk

`func (o *CmsContentItemResponse) GetRequestIdOk() (*string, bool)`

GetRequestIdOk returns a tuple with the RequestId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestId

`func (o *CmsContentItemResponse) SetRequestId(v string)`

SetRequestId sets RequestId field to given value.

### HasRequestId

`func (o *CmsContentItemResponse) HasRequestId() bool`

HasRequestId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


