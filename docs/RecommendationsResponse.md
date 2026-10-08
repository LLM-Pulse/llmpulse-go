# RecommendationsResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ProjectId** | **int32** |  | 
**Page** | **int32** |  | 
**PerPage** | **int32** |  | 
**Total** | **int32** | Rows matching the filters across every page | 
**RequestId** | **string** |  | 
**Data** | [**[]RecommendationSummary**](RecommendationSummary.md) |  | 

## Methods

### NewRecommendationsResponse

`func NewRecommendationsResponse(projectId int32, page int32, perPage int32, total int32, requestId string, data []RecommendationSummary, ) *RecommendationsResponse`

NewRecommendationsResponse instantiates a new RecommendationsResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRecommendationsResponseWithDefaults

`func NewRecommendationsResponseWithDefaults() *RecommendationsResponse`

NewRecommendationsResponseWithDefaults instantiates a new RecommendationsResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProjectId

`func (o *RecommendationsResponse) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *RecommendationsResponse) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *RecommendationsResponse) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.


### GetPage

`func (o *RecommendationsResponse) GetPage() int32`

GetPage returns the Page field if non-nil, zero value otherwise.

### GetPageOk

`func (o *RecommendationsResponse) GetPageOk() (*int32, bool)`

GetPageOk returns a tuple with the Page field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPage

`func (o *RecommendationsResponse) SetPage(v int32)`

SetPage sets Page field to given value.


### GetPerPage

`func (o *RecommendationsResponse) GetPerPage() int32`

GetPerPage returns the PerPage field if non-nil, zero value otherwise.

### GetPerPageOk

`func (o *RecommendationsResponse) GetPerPageOk() (*int32, bool)`

GetPerPageOk returns a tuple with the PerPage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPerPage

`func (o *RecommendationsResponse) SetPerPage(v int32)`

SetPerPage sets PerPage field to given value.


### GetTotal

`func (o *RecommendationsResponse) GetTotal() int32`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *RecommendationsResponse) GetTotalOk() (*int32, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *RecommendationsResponse) SetTotal(v int32)`

SetTotal sets Total field to given value.


### GetRequestId

`func (o *RecommendationsResponse) GetRequestId() string`

GetRequestId returns the RequestId field if non-nil, zero value otherwise.

### GetRequestIdOk

`func (o *RecommendationsResponse) GetRequestIdOk() (*string, bool)`

GetRequestIdOk returns a tuple with the RequestId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestId

`func (o *RecommendationsResponse) SetRequestId(v string)`

SetRequestId sets RequestId field to given value.


### GetData

`func (o *RecommendationsResponse) GetData() []RecommendationSummary`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *RecommendationsResponse) GetDataOk() (*[]RecommendationSummary, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *RecommendationsResponse) SetData(v []RecommendationSummary)`

SetData sets Data field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


