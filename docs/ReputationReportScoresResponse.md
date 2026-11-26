# ReputationReportScoresResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ProjectId** | **int32** |  | 
**Page** | **int32** |  | 
**PerPage** | **int32** |  | 
**Total** | **int32** | Rows matching the filters across every page | 
**RequestId** | **string** |  | 
**Report** | [**ReputationReportSummary**](ReputationReportSummary.md) |  | 
**Data** | [**[]AnalystScoreRow**](AnalystScoreRow.md) |  | 

## Methods

### NewReputationReportScoresResponse

`func NewReputationReportScoresResponse(projectId int32, page int32, perPage int32, total int32, requestId string, report ReputationReportSummary, data []AnalystScoreRow, ) *ReputationReportScoresResponse`

NewReputationReportScoresResponse instantiates a new ReputationReportScoresResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewReputationReportScoresResponseWithDefaults

`func NewReputationReportScoresResponseWithDefaults() *ReputationReportScoresResponse`

NewReputationReportScoresResponseWithDefaults instantiates a new ReputationReportScoresResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProjectId

`func (o *ReputationReportScoresResponse) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *ReputationReportScoresResponse) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *ReputationReportScoresResponse) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.


### GetPage

`func (o *ReputationReportScoresResponse) GetPage() int32`

GetPage returns the Page field if non-nil, zero value otherwise.

### GetPageOk

`func (o *ReputationReportScoresResponse) GetPageOk() (*int32, bool)`

GetPageOk returns a tuple with the Page field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPage

`func (o *ReputationReportScoresResponse) SetPage(v int32)`

SetPage sets Page field to given value.


### GetPerPage

`func (o *ReputationReportScoresResponse) GetPerPage() int32`

GetPerPage returns the PerPage field if non-nil, zero value otherwise.

### GetPerPageOk

`func (o *ReputationReportScoresResponse) GetPerPageOk() (*int32, bool)`

GetPerPageOk returns a tuple with the PerPage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPerPage

`func (o *ReputationReportScoresResponse) SetPerPage(v int32)`

SetPerPage sets PerPage field to given value.


### GetTotal

`func (o *ReputationReportScoresResponse) GetTotal() int32`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *ReputationReportScoresResponse) GetTotalOk() (*int32, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *ReputationReportScoresResponse) SetTotal(v int32)`

SetTotal sets Total field to given value.


### GetRequestId

`func (o *ReputationReportScoresResponse) GetRequestId() string`

GetRequestId returns the RequestId field if non-nil, zero value otherwise.

### GetRequestIdOk

`func (o *ReputationReportScoresResponse) GetRequestIdOk() (*string, bool)`

GetRequestIdOk returns a tuple with the RequestId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestId

`func (o *ReputationReportScoresResponse) SetRequestId(v string)`

SetRequestId sets RequestId field to given value.


### GetReport

`func (o *ReputationReportScoresResponse) GetReport() ReputationReportSummary`

GetReport returns the Report field if non-nil, zero value otherwise.

### GetReportOk

`func (o *ReputationReportScoresResponse) GetReportOk() (*ReputationReportSummary, bool)`

GetReportOk returns a tuple with the Report field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReport

`func (o *ReputationReportScoresResponse) SetReport(v ReputationReportSummary)`

SetReport sets Report field to given value.


### GetData

`func (o *ReputationReportScoresResponse) GetData() []AnalystScoreRow`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *ReputationReportScoresResponse) GetDataOk() (*[]AnalystScoreRow, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *ReputationReportScoresResponse) SetData(v []AnalystScoreRow)`

SetData sets Data field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


