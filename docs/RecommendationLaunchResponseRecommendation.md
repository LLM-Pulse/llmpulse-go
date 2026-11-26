# RecommendationLaunchResponseRecommendation

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **int32** | Poll GET /recommendations/{id} with it | 
**RecommendationType** | **string** |  | 
**Status** | **string** | Always pending | 
**CreatedAt** | **time.Time** |  | 

## Methods

### NewRecommendationLaunchResponseRecommendation

`func NewRecommendationLaunchResponseRecommendation(id int32, recommendationType string, status string, createdAt time.Time, ) *RecommendationLaunchResponseRecommendation`

NewRecommendationLaunchResponseRecommendation instantiates a new RecommendationLaunchResponseRecommendation object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRecommendationLaunchResponseRecommendationWithDefaults

`func NewRecommendationLaunchResponseRecommendationWithDefaults() *RecommendationLaunchResponseRecommendation`

NewRecommendationLaunchResponseRecommendationWithDefaults instantiates a new RecommendationLaunchResponseRecommendation object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *RecommendationLaunchResponseRecommendation) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *RecommendationLaunchResponseRecommendation) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *RecommendationLaunchResponseRecommendation) SetId(v int32)`

SetId sets Id field to given value.


### GetRecommendationType

`func (o *RecommendationLaunchResponseRecommendation) GetRecommendationType() string`

GetRecommendationType returns the RecommendationType field if non-nil, zero value otherwise.

### GetRecommendationTypeOk

`func (o *RecommendationLaunchResponseRecommendation) GetRecommendationTypeOk() (*string, bool)`

GetRecommendationTypeOk returns a tuple with the RecommendationType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRecommendationType

`func (o *RecommendationLaunchResponseRecommendation) SetRecommendationType(v string)`

SetRecommendationType sets RecommendationType field to given value.


### GetStatus

`func (o *RecommendationLaunchResponseRecommendation) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *RecommendationLaunchResponseRecommendation) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *RecommendationLaunchResponseRecommendation) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetCreatedAt

`func (o *RecommendationLaunchResponseRecommendation) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *RecommendationLaunchResponseRecommendation) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *RecommendationLaunchResponseRecommendation) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


