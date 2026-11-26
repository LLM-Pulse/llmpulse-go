# StudyReportScoresResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**StudyId** | **int32** |  | 
**Report** | [**ReputationReportSummary**](ReputationReportSummary.md) |  | 
**Page** | **int32** |  | 
**PerPage** | **int32** |  | 
**Total** | **int32** | Score rows matching the filters across every page | 
**Data** | [**[]AnalystScoreRow**](AnalystScoreRow.md) |  | 
**RequestId** | **string** |  | 

## Methods

### NewStudyReportScoresResponse

`func NewStudyReportScoresResponse(studyId int32, report ReputationReportSummary, page int32, perPage int32, total int32, data []AnalystScoreRow, requestId string, ) *StudyReportScoresResponse`

NewStudyReportScoresResponse instantiates a new StudyReportScoresResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewStudyReportScoresResponseWithDefaults

`func NewStudyReportScoresResponseWithDefaults() *StudyReportScoresResponse`

NewStudyReportScoresResponseWithDefaults instantiates a new StudyReportScoresResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetStudyId

`func (o *StudyReportScoresResponse) GetStudyId() int32`

GetStudyId returns the StudyId field if non-nil, zero value otherwise.

### GetStudyIdOk

`func (o *StudyReportScoresResponse) GetStudyIdOk() (*int32, bool)`

GetStudyIdOk returns a tuple with the StudyId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStudyId

`func (o *StudyReportScoresResponse) SetStudyId(v int32)`

SetStudyId sets StudyId field to given value.


### GetReport

`func (o *StudyReportScoresResponse) GetReport() ReputationReportSummary`

GetReport returns the Report field if non-nil, zero value otherwise.

### GetReportOk

`func (o *StudyReportScoresResponse) GetReportOk() (*ReputationReportSummary, bool)`

GetReportOk returns a tuple with the Report field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReport

`func (o *StudyReportScoresResponse) SetReport(v ReputationReportSummary)`

SetReport sets Report field to given value.


### GetPage

`func (o *StudyReportScoresResponse) GetPage() int32`

GetPage returns the Page field if non-nil, zero value otherwise.

### GetPageOk

`func (o *StudyReportScoresResponse) GetPageOk() (*int32, bool)`

GetPageOk returns a tuple with the Page field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPage

`func (o *StudyReportScoresResponse) SetPage(v int32)`

SetPage sets Page field to given value.


### GetPerPage

`func (o *StudyReportScoresResponse) GetPerPage() int32`

GetPerPage returns the PerPage field if non-nil, zero value otherwise.

### GetPerPageOk

`func (o *StudyReportScoresResponse) GetPerPageOk() (*int32, bool)`

GetPerPageOk returns a tuple with the PerPage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPerPage

`func (o *StudyReportScoresResponse) SetPerPage(v int32)`

SetPerPage sets PerPage field to given value.


### GetTotal

`func (o *StudyReportScoresResponse) GetTotal() int32`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *StudyReportScoresResponse) GetTotalOk() (*int32, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *StudyReportScoresResponse) SetTotal(v int32)`

SetTotal sets Total field to given value.


### GetData

`func (o *StudyReportScoresResponse) GetData() []AnalystScoreRow`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *StudyReportScoresResponse) GetDataOk() (*[]AnalystScoreRow, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *StudyReportScoresResponse) SetData(v []AnalystScoreRow)`

SetData sets Data field to given value.


### GetRequestId

`func (o *StudyReportScoresResponse) GetRequestId() string`

GetRequestId returns the RequestId field if non-nil, zero value otherwise.

### GetRequestIdOk

`func (o *StudyReportScoresResponse) GetRequestIdOk() (*string, bool)`

GetRequestIdOk returns a tuple with the RequestId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestId

`func (o *StudyReportScoresResponse) SetRequestId(v string)`

SetRequestId sets RequestId field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


