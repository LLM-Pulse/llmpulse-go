# CreateReputationReportRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ProjectId** | **int32** |  | 
**Recalculate** | Pointer to **bool** | Use this month&#39;s one manual recalculation instead of returning the existing report | [optional] [default to false]

## Methods

### NewCreateReputationReportRequest

`func NewCreateReputationReportRequest(projectId int32, ) *CreateReputationReportRequest`

NewCreateReputationReportRequest instantiates a new CreateReputationReportRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateReputationReportRequestWithDefaults

`func NewCreateReputationReportRequestWithDefaults() *CreateReputationReportRequest`

NewCreateReputationReportRequestWithDefaults instantiates a new CreateReputationReportRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProjectId

`func (o *CreateReputationReportRequest) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *CreateReputationReportRequest) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *CreateReputationReportRequest) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.


### GetRecalculate

`func (o *CreateReputationReportRequest) GetRecalculate() bool`

GetRecalculate returns the Recalculate field if non-nil, zero value otherwise.

### GetRecalculateOk

`func (o *CreateReputationReportRequest) GetRecalculateOk() (*bool, bool)`

GetRecalculateOk returns a tuple with the Recalculate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRecalculate

`func (o *CreateReputationReportRequest) SetRecalculate(v bool)`

SetRecalculate sets Recalculate field to given value.

### HasRecalculate

`func (o *CreateReputationReportRequest) HasRecalculate() bool`

HasRecalculate returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


