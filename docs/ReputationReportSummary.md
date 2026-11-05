# ReputationReportSummary

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** | Report id for GET /reputation/reports/{id} | 
**Status** | **string** |  | 
**CreatedAt** | **time.Time** |  | 
**ProcessedAt** | Pointer to **NullableTime** |  | [optional] 
**AvailableModels** | **[]string** | Analyst models that produced data | 
**MissingModels** | **[]string** | Analyst models with no data yet | 
**ErrorMessage** | Pointer to **NullableString** | Why the report failed; null unless status is failed | [optional] 

## Methods

### NewReputationReportSummary

`func NewReputationReportSummary(id string, status string, createdAt time.Time, availableModels []string, missingModels []string, ) *ReputationReportSummary`

NewReputationReportSummary instantiates a new ReputationReportSummary object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewReputationReportSummaryWithDefaults

`func NewReputationReportSummaryWithDefaults() *ReputationReportSummary`

NewReputationReportSummaryWithDefaults instantiates a new ReputationReportSummary object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *ReputationReportSummary) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ReputationReportSummary) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ReputationReportSummary) SetId(v string)`

SetId sets Id field to given value.


### GetStatus

`func (o *ReputationReportSummary) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *ReputationReportSummary) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *ReputationReportSummary) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetCreatedAt

`func (o *ReputationReportSummary) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *ReputationReportSummary) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *ReputationReportSummary) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetProcessedAt

`func (o *ReputationReportSummary) GetProcessedAt() time.Time`

GetProcessedAt returns the ProcessedAt field if non-nil, zero value otherwise.

### GetProcessedAtOk

`func (o *ReputationReportSummary) GetProcessedAtOk() (*time.Time, bool)`

GetProcessedAtOk returns a tuple with the ProcessedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProcessedAt

`func (o *ReputationReportSummary) SetProcessedAt(v time.Time)`

SetProcessedAt sets ProcessedAt field to given value.

### HasProcessedAt

`func (o *ReputationReportSummary) HasProcessedAt() bool`

HasProcessedAt returns a boolean if a field has been set.

### SetProcessedAtNil

`func (o *ReputationReportSummary) SetProcessedAtNil(b bool)`

 SetProcessedAtNil sets the value for ProcessedAt to be an explicit nil

### UnsetProcessedAt
`func (o *ReputationReportSummary) UnsetProcessedAt()`

UnsetProcessedAt ensures that no value is present for ProcessedAt, not even an explicit nil
### GetAvailableModels

`func (o *ReputationReportSummary) GetAvailableModels() []string`

GetAvailableModels returns the AvailableModels field if non-nil, zero value otherwise.

### GetAvailableModelsOk

`func (o *ReputationReportSummary) GetAvailableModelsOk() (*[]string, bool)`

GetAvailableModelsOk returns a tuple with the AvailableModels field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAvailableModels

`func (o *ReputationReportSummary) SetAvailableModels(v []string)`

SetAvailableModels sets AvailableModels field to given value.


### GetMissingModels

`func (o *ReputationReportSummary) GetMissingModels() []string`

GetMissingModels returns the MissingModels field if non-nil, zero value otherwise.

### GetMissingModelsOk

`func (o *ReputationReportSummary) GetMissingModelsOk() (*[]string, bool)`

GetMissingModelsOk returns a tuple with the MissingModels field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMissingModels

`func (o *ReputationReportSummary) SetMissingModels(v []string)`

SetMissingModels sets MissingModels field to given value.


### GetErrorMessage

`func (o *ReputationReportSummary) GetErrorMessage() string`

GetErrorMessage returns the ErrorMessage field if non-nil, zero value otherwise.

### GetErrorMessageOk

`func (o *ReputationReportSummary) GetErrorMessageOk() (*string, bool)`

GetErrorMessageOk returns a tuple with the ErrorMessage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrorMessage

`func (o *ReputationReportSummary) SetErrorMessage(v string)`

SetErrorMessage sets ErrorMessage field to given value.

### HasErrorMessage

`func (o *ReputationReportSummary) HasErrorMessage() bool`

HasErrorMessage returns a boolean if a field has been set.

### SetErrorMessageNil

`func (o *ReputationReportSummary) SetErrorMessageNil(b bool)`

 SetErrorMessageNil sets the value for ErrorMessage to be an explicit nil

### UnsetErrorMessage
`func (o *ReputationReportSummary) UnsetErrorMessage()`

UnsetErrorMessage ensures that no value is present for ErrorMessage, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


