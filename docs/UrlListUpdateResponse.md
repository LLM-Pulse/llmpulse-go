# UrlListUpdateResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ProjectId** | **int32** |  | 
**UrlList** | [**UrlListWithCounts**](UrlListWithCounts.md) |  | 
**RequestId** | **string** |  | 

## Methods

### NewUrlListUpdateResponse

`func NewUrlListUpdateResponse(projectId int32, urlList UrlListWithCounts, requestId string, ) *UrlListUpdateResponse`

NewUrlListUpdateResponse instantiates a new UrlListUpdateResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUrlListUpdateResponseWithDefaults

`func NewUrlListUpdateResponseWithDefaults() *UrlListUpdateResponse`

NewUrlListUpdateResponseWithDefaults instantiates a new UrlListUpdateResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProjectId

`func (o *UrlListUpdateResponse) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *UrlListUpdateResponse) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *UrlListUpdateResponse) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.


### GetUrlList

`func (o *UrlListUpdateResponse) GetUrlList() UrlListWithCounts`

GetUrlList returns the UrlList field if non-nil, zero value otherwise.

### GetUrlListOk

`func (o *UrlListUpdateResponse) GetUrlListOk() (*UrlListWithCounts, bool)`

GetUrlListOk returns a tuple with the UrlList field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrlList

`func (o *UrlListUpdateResponse) SetUrlList(v UrlListWithCounts)`

SetUrlList sets UrlList field to given value.


### GetRequestId

`func (o *UrlListUpdateResponse) GetRequestId() string`

GetRequestId returns the RequestId field if non-nil, zero value otherwise.

### GetRequestIdOk

`func (o *UrlListUpdateResponse) GetRequestIdOk() (*string, bool)`

GetRequestIdOk returns a tuple with the RequestId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestId

`func (o *UrlListUpdateResponse) SetRequestId(v string)`

SetRequestId sets RequestId field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


