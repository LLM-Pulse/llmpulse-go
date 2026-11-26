# RecommendationLaunchResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ProjectId** | **int32** |  | 
**Recommendation** | [**RecommendationLaunchResponseRecommendation**](RecommendationLaunchResponseRecommendation.md) |  | 
**RequestId** | **string** |  | 

## Methods

### NewRecommendationLaunchResponse

`func NewRecommendationLaunchResponse(projectId int32, recommendation RecommendationLaunchResponseRecommendation, requestId string, ) *RecommendationLaunchResponse`

NewRecommendationLaunchResponse instantiates a new RecommendationLaunchResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRecommendationLaunchResponseWithDefaults

`func NewRecommendationLaunchResponseWithDefaults() *RecommendationLaunchResponse`

NewRecommendationLaunchResponseWithDefaults instantiates a new RecommendationLaunchResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProjectId

`func (o *RecommendationLaunchResponse) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *RecommendationLaunchResponse) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *RecommendationLaunchResponse) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.


### GetRecommendation

`func (o *RecommendationLaunchResponse) GetRecommendation() RecommendationLaunchResponseRecommendation`

GetRecommendation returns the Recommendation field if non-nil, zero value otherwise.

### GetRecommendationOk

`func (o *RecommendationLaunchResponse) GetRecommendationOk() (*RecommendationLaunchResponseRecommendation, bool)`

GetRecommendationOk returns a tuple with the Recommendation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRecommendation

`func (o *RecommendationLaunchResponse) SetRecommendation(v RecommendationLaunchResponseRecommendation)`

SetRecommendation sets Recommendation field to given value.


### GetRequestId

`func (o *RecommendationLaunchResponse) GetRequestId() string`

GetRequestId returns the RequestId field if non-nil, zero value otherwise.

### GetRequestIdOk

`func (o *RecommendationLaunchResponse) GetRequestIdOk() (*string, bool)`

GetRequestIdOk returns a tuple with the RequestId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestId

`func (o *RecommendationLaunchResponse) SetRequestId(v string)`

SetRequestId sets RequestId field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


