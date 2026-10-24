# UpdateRecommendationItemRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ProjectId** | **int32** |  | 
**Status** | **string** | completed, archived, or active to restore the item | 
**Reason** | Pointer to **string** | Optional, with status archived only. competitor only on a PR &amp; Citation Building item that targets a domain. | [optional] 

## Methods

### NewUpdateRecommendationItemRequest

`func NewUpdateRecommendationItemRequest(projectId int32, status string, ) *UpdateRecommendationItemRequest`

NewUpdateRecommendationItemRequest instantiates a new UpdateRecommendationItemRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUpdateRecommendationItemRequestWithDefaults

`func NewUpdateRecommendationItemRequestWithDefaults() *UpdateRecommendationItemRequest`

NewUpdateRecommendationItemRequestWithDefaults instantiates a new UpdateRecommendationItemRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProjectId

`func (o *UpdateRecommendationItemRequest) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *UpdateRecommendationItemRequest) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *UpdateRecommendationItemRequest) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.


### GetStatus

`func (o *UpdateRecommendationItemRequest) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *UpdateRecommendationItemRequest) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *UpdateRecommendationItemRequest) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetReason

`func (o *UpdateRecommendationItemRequest) GetReason() string`

GetReason returns the Reason field if non-nil, zero value otherwise.

### GetReasonOk

`func (o *UpdateRecommendationItemRequest) GetReasonOk() (*string, bool)`

GetReasonOk returns a tuple with the Reason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReason

`func (o *UpdateRecommendationItemRequest) SetReason(v string)`

SetReason sets Reason field to given value.

### HasReason

`func (o *UpdateRecommendationItemRequest) HasReason() bool`

HasReason returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


