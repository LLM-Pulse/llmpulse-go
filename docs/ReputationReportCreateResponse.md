# ReputationReportCreateResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ProjectId** | **int32** |  | 
**Created** | **bool** | True when this request started a new report; false when it returned the one that already holds the month | 
**Report** | [**ReputationReportSummary**](ReputationReportSummary.md) |  | 
**RequestId** | Pointer to **string** |  | [optional] 

## Methods

### NewReputationReportCreateResponse

`func NewReputationReportCreateResponse(projectId int32, created bool, report ReputationReportSummary, ) *ReputationReportCreateResponse`

NewReputationReportCreateResponse instantiates a new ReputationReportCreateResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewReputationReportCreateResponseWithDefaults

`func NewReputationReportCreateResponseWithDefaults() *ReputationReportCreateResponse`

NewReputationReportCreateResponseWithDefaults instantiates a new ReputationReportCreateResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProjectId

`func (o *ReputationReportCreateResponse) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *ReputationReportCreateResponse) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *ReputationReportCreateResponse) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.


### GetCreated

`func (o *ReputationReportCreateResponse) GetCreated() bool`

GetCreated returns the Created field if non-nil, zero value otherwise.

### GetCreatedOk

`func (o *ReputationReportCreateResponse) GetCreatedOk() (*bool, bool)`

GetCreatedOk returns a tuple with the Created field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreated

`func (o *ReputationReportCreateResponse) SetCreated(v bool)`

SetCreated sets Created field to given value.


### GetReport

`func (o *ReputationReportCreateResponse) GetReport() ReputationReportSummary`

GetReport returns the Report field if non-nil, zero value otherwise.

### GetReportOk

`func (o *ReputationReportCreateResponse) GetReportOk() (*ReputationReportSummary, bool)`

GetReportOk returns a tuple with the Report field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReport

`func (o *ReputationReportCreateResponse) SetReport(v ReputationReportSummary)`

SetReport sets Report field to given value.


### GetRequestId

`func (o *ReputationReportCreateResponse) GetRequestId() string`

GetRequestId returns the RequestId field if non-nil, zero value otherwise.

### GetRequestIdOk

`func (o *ReputationReportCreateResponse) GetRequestIdOk() (*string, bool)`

GetRequestIdOk returns a tuple with the RequestId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestId

`func (o *ReputationReportCreateResponse) SetRequestId(v string)`

SetRequestId sets RequestId field to given value.

### HasRequestId

`func (o *ReputationReportCreateResponse) HasRequestId() bool`

HasRequestId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


