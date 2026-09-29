# TechnicalGeoReportContentUpdateRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ProjectId** | **int32** |  | 
**ReportType** | **string** | Only llms_txt reports have editable content | 
**ContentVersion** | **string** | result_data.content_version of the report as last read. It changes on every save; a value that no longer matches is refused as stale | 
**Edits** | [**TechnicalGeoReportContentUpdateRequestEdits**](TechnicalGeoReportContentUpdateRequestEdits.md) |  | 

## Methods

### NewTechnicalGeoReportContentUpdateRequest

`func NewTechnicalGeoReportContentUpdateRequest(projectId int32, reportType string, contentVersion string, edits TechnicalGeoReportContentUpdateRequestEdits, ) *TechnicalGeoReportContentUpdateRequest`

NewTechnicalGeoReportContentUpdateRequest instantiates a new TechnicalGeoReportContentUpdateRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTechnicalGeoReportContentUpdateRequestWithDefaults

`func NewTechnicalGeoReportContentUpdateRequestWithDefaults() *TechnicalGeoReportContentUpdateRequest`

NewTechnicalGeoReportContentUpdateRequestWithDefaults instantiates a new TechnicalGeoReportContentUpdateRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProjectId

`func (o *TechnicalGeoReportContentUpdateRequest) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *TechnicalGeoReportContentUpdateRequest) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *TechnicalGeoReportContentUpdateRequest) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.


### GetReportType

`func (o *TechnicalGeoReportContentUpdateRequest) GetReportType() string`

GetReportType returns the ReportType field if non-nil, zero value otherwise.

### GetReportTypeOk

`func (o *TechnicalGeoReportContentUpdateRequest) GetReportTypeOk() (*string, bool)`

GetReportTypeOk returns a tuple with the ReportType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReportType

`func (o *TechnicalGeoReportContentUpdateRequest) SetReportType(v string)`

SetReportType sets ReportType field to given value.


### GetContentVersion

`func (o *TechnicalGeoReportContentUpdateRequest) GetContentVersion() string`

GetContentVersion returns the ContentVersion field if non-nil, zero value otherwise.

### GetContentVersionOk

`func (o *TechnicalGeoReportContentUpdateRequest) GetContentVersionOk() (*string, bool)`

GetContentVersionOk returns a tuple with the ContentVersion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContentVersion

`func (o *TechnicalGeoReportContentUpdateRequest) SetContentVersion(v string)`

SetContentVersion sets ContentVersion field to given value.


### GetEdits

`func (o *TechnicalGeoReportContentUpdateRequest) GetEdits() TechnicalGeoReportContentUpdateRequestEdits`

GetEdits returns the Edits field if non-nil, zero value otherwise.

### GetEditsOk

`func (o *TechnicalGeoReportContentUpdateRequest) GetEditsOk() (*TechnicalGeoReportContentUpdateRequestEdits, bool)`

GetEditsOk returns a tuple with the Edits field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEdits

`func (o *TechnicalGeoReportContentUpdateRequest) SetEdits(v TechnicalGeoReportContentUpdateRequestEdits)`

SetEdits sets Edits field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


