# RecommendationItemUpdateResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ProjectId** | **int32** |  | 
**Item** | [**RecommendationItem**](RecommendationItem.md) |  | 
**RequestId** | **string** |  | 

## Methods

### NewRecommendationItemUpdateResponse

`func NewRecommendationItemUpdateResponse(projectId int32, item RecommendationItem, requestId string, ) *RecommendationItemUpdateResponse`

NewRecommendationItemUpdateResponse instantiates a new RecommendationItemUpdateResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRecommendationItemUpdateResponseWithDefaults

`func NewRecommendationItemUpdateResponseWithDefaults() *RecommendationItemUpdateResponse`

NewRecommendationItemUpdateResponseWithDefaults instantiates a new RecommendationItemUpdateResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProjectId

`func (o *RecommendationItemUpdateResponse) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *RecommendationItemUpdateResponse) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *RecommendationItemUpdateResponse) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.


### GetItem

`func (o *RecommendationItemUpdateResponse) GetItem() RecommendationItem`

GetItem returns the Item field if non-nil, zero value otherwise.

### GetItemOk

`func (o *RecommendationItemUpdateResponse) GetItemOk() (*RecommendationItem, bool)`

GetItemOk returns a tuple with the Item field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetItem

`func (o *RecommendationItemUpdateResponse) SetItem(v RecommendationItem)`

SetItem sets Item field to given value.


### GetRequestId

`func (o *RecommendationItemUpdateResponse) GetRequestId() string`

GetRequestId returns the RequestId field if non-nil, zero value otherwise.

### GetRequestIdOk

`func (o *RecommendationItemUpdateResponse) GetRequestIdOk() (*string, bool)`

GetRequestIdOk returns a tuple with the RequestId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestId

`func (o *RecommendationItemUpdateResponse) SetRequestId(v string)`

SetRequestId sets RequestId field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


