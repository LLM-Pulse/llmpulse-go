# LaunchRecommendationsRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ProjectId** | **int32** |  | 
**RecommendationType** | Pointer to **string** |  | [optional] [default to "ai_visibility"]

## Methods

### NewLaunchRecommendationsRequest

`func NewLaunchRecommendationsRequest(projectId int32, ) *LaunchRecommendationsRequest`

NewLaunchRecommendationsRequest instantiates a new LaunchRecommendationsRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewLaunchRecommendationsRequestWithDefaults

`func NewLaunchRecommendationsRequestWithDefaults() *LaunchRecommendationsRequest`

NewLaunchRecommendationsRequestWithDefaults instantiates a new LaunchRecommendationsRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProjectId

`func (o *LaunchRecommendationsRequest) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *LaunchRecommendationsRequest) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *LaunchRecommendationsRequest) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.


### GetRecommendationType

`func (o *LaunchRecommendationsRequest) GetRecommendationType() string`

GetRecommendationType returns the RecommendationType field if non-nil, zero value otherwise.

### GetRecommendationTypeOk

`func (o *LaunchRecommendationsRequest) GetRecommendationTypeOk() (*string, bool)`

GetRecommendationTypeOk returns a tuple with the RecommendationType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRecommendationType

`func (o *LaunchRecommendationsRequest) SetRecommendationType(v string)`

SetRecommendationType sets RecommendationType field to given value.

### HasRecommendationType

`func (o *LaunchRecommendationsRequest) HasRecommendationType() bool`

HasRecommendationType returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


