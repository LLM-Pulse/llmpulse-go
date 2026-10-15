# CustomReportDetailResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ProjectId** | **int32** |  | 
**Id** | **int32** |  | 
**Name** | **string** |  | 
**DateRange** | [**CustomReportDateRange**](CustomReportDateRange.md) |  | 
**Schedule** | [**CustomReportSchedule**](CustomReportSchedule.md) |  | 
**RecipientsCount** | Pointer to **int32** |  | [optional] 
**Published** | Pointer to **bool** |  | [optional] 
**PublicLinkActive** | Pointer to **bool** |  | [optional] 
**PasswordProtected** | Pointer to **bool** |  | [optional] 
**PortalOnly** | Pointer to **bool** |  | [optional] 
**LastSentAt** | Pointer to **NullableTime** | When the report was last emailed, on its schedule or with Send now | [optional] 
**CreatedAt** | Pointer to **time.Time** |  | [optional] 
**UpdatedAt** | Pointer to **time.Time** |  | [optional] 
**Filters** | [**CustomReportFilters**](CustomReportFilters.md) |  | 
**ComparePrevious** | Pointer to **bool** |  | [optional] 
**AttachExcel** | Pointer to **bool** |  | [optional] 
**ManualSendAvailableAt** | Pointer to **NullableTime** | When the 10-minute cooldown after the last manual send ends; null when none is running | [optional] 
**GeneratedAt** | **time.Time** |  | 
**Blocks** | [**[]CustomReportBlock**](CustomReportBlock.md) | The report layout in order | 
**Widgets** | [**[]CustomReportWidget**](CustomReportWidget.md) |  | 
**RequestId** | **string** |  | 

## Methods

### NewCustomReportDetailResponse

`func NewCustomReportDetailResponse(projectId int32, id int32, name string, dateRange CustomReportDateRange, schedule CustomReportSchedule, filters CustomReportFilters, generatedAt time.Time, blocks []CustomReportBlock, widgets []CustomReportWidget, requestId string, ) *CustomReportDetailResponse`

NewCustomReportDetailResponse instantiates a new CustomReportDetailResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCustomReportDetailResponseWithDefaults

`func NewCustomReportDetailResponseWithDefaults() *CustomReportDetailResponse`

NewCustomReportDetailResponseWithDefaults instantiates a new CustomReportDetailResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProjectId

`func (o *CustomReportDetailResponse) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *CustomReportDetailResponse) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *CustomReportDetailResponse) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.


### GetId

`func (o *CustomReportDetailResponse) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *CustomReportDetailResponse) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *CustomReportDetailResponse) SetId(v int32)`

SetId sets Id field to given value.


### GetName

`func (o *CustomReportDetailResponse) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *CustomReportDetailResponse) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *CustomReportDetailResponse) SetName(v string)`

SetName sets Name field to given value.


### GetDateRange

`func (o *CustomReportDetailResponse) GetDateRange() CustomReportDateRange`

GetDateRange returns the DateRange field if non-nil, zero value otherwise.

### GetDateRangeOk

`func (o *CustomReportDetailResponse) GetDateRangeOk() (*CustomReportDateRange, bool)`

GetDateRangeOk returns a tuple with the DateRange field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDateRange

`func (o *CustomReportDetailResponse) SetDateRange(v CustomReportDateRange)`

SetDateRange sets DateRange field to given value.


### GetSchedule

`func (o *CustomReportDetailResponse) GetSchedule() CustomReportSchedule`

GetSchedule returns the Schedule field if non-nil, zero value otherwise.

### GetScheduleOk

`func (o *CustomReportDetailResponse) GetScheduleOk() (*CustomReportSchedule, bool)`

GetScheduleOk returns a tuple with the Schedule field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSchedule

`func (o *CustomReportDetailResponse) SetSchedule(v CustomReportSchedule)`

SetSchedule sets Schedule field to given value.


### GetRecipientsCount

`func (o *CustomReportDetailResponse) GetRecipientsCount() int32`

GetRecipientsCount returns the RecipientsCount field if non-nil, zero value otherwise.

### GetRecipientsCountOk

`func (o *CustomReportDetailResponse) GetRecipientsCountOk() (*int32, bool)`

GetRecipientsCountOk returns a tuple with the RecipientsCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRecipientsCount

`func (o *CustomReportDetailResponse) SetRecipientsCount(v int32)`

SetRecipientsCount sets RecipientsCount field to given value.

### HasRecipientsCount

`func (o *CustomReportDetailResponse) HasRecipientsCount() bool`

HasRecipientsCount returns a boolean if a field has been set.

### GetPublished

`func (o *CustomReportDetailResponse) GetPublished() bool`

GetPublished returns the Published field if non-nil, zero value otherwise.

### GetPublishedOk

`func (o *CustomReportDetailResponse) GetPublishedOk() (*bool, bool)`

GetPublishedOk returns a tuple with the Published field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPublished

`func (o *CustomReportDetailResponse) SetPublished(v bool)`

SetPublished sets Published field to given value.

### HasPublished

`func (o *CustomReportDetailResponse) HasPublished() bool`

HasPublished returns a boolean if a field has been set.

### GetPublicLinkActive

`func (o *CustomReportDetailResponse) GetPublicLinkActive() bool`

GetPublicLinkActive returns the PublicLinkActive field if non-nil, zero value otherwise.

### GetPublicLinkActiveOk

`func (o *CustomReportDetailResponse) GetPublicLinkActiveOk() (*bool, bool)`

GetPublicLinkActiveOk returns a tuple with the PublicLinkActive field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPublicLinkActive

`func (o *CustomReportDetailResponse) SetPublicLinkActive(v bool)`

SetPublicLinkActive sets PublicLinkActive field to given value.

### HasPublicLinkActive

`func (o *CustomReportDetailResponse) HasPublicLinkActive() bool`

HasPublicLinkActive returns a boolean if a field has been set.

### GetPasswordProtected

`func (o *CustomReportDetailResponse) GetPasswordProtected() bool`

GetPasswordProtected returns the PasswordProtected field if non-nil, zero value otherwise.

### GetPasswordProtectedOk

`func (o *CustomReportDetailResponse) GetPasswordProtectedOk() (*bool, bool)`

GetPasswordProtectedOk returns a tuple with the PasswordProtected field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPasswordProtected

`func (o *CustomReportDetailResponse) SetPasswordProtected(v bool)`

SetPasswordProtected sets PasswordProtected field to given value.

### HasPasswordProtected

`func (o *CustomReportDetailResponse) HasPasswordProtected() bool`

HasPasswordProtected returns a boolean if a field has been set.

### GetPortalOnly

`func (o *CustomReportDetailResponse) GetPortalOnly() bool`

GetPortalOnly returns the PortalOnly field if non-nil, zero value otherwise.

### GetPortalOnlyOk

`func (o *CustomReportDetailResponse) GetPortalOnlyOk() (*bool, bool)`

GetPortalOnlyOk returns a tuple with the PortalOnly field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPortalOnly

`func (o *CustomReportDetailResponse) SetPortalOnly(v bool)`

SetPortalOnly sets PortalOnly field to given value.

### HasPortalOnly

`func (o *CustomReportDetailResponse) HasPortalOnly() bool`

HasPortalOnly returns a boolean if a field has been set.

### GetLastSentAt

`func (o *CustomReportDetailResponse) GetLastSentAt() time.Time`

GetLastSentAt returns the LastSentAt field if non-nil, zero value otherwise.

### GetLastSentAtOk

`func (o *CustomReportDetailResponse) GetLastSentAtOk() (*time.Time, bool)`

GetLastSentAtOk returns a tuple with the LastSentAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastSentAt

`func (o *CustomReportDetailResponse) SetLastSentAt(v time.Time)`

SetLastSentAt sets LastSentAt field to given value.

### HasLastSentAt

`func (o *CustomReportDetailResponse) HasLastSentAt() bool`

HasLastSentAt returns a boolean if a field has been set.

### SetLastSentAtNil

`func (o *CustomReportDetailResponse) SetLastSentAtNil(b bool)`

 SetLastSentAtNil sets the value for LastSentAt to be an explicit nil

### UnsetLastSentAt
`func (o *CustomReportDetailResponse) UnsetLastSentAt()`

UnsetLastSentAt ensures that no value is present for LastSentAt, not even an explicit nil
### GetCreatedAt

`func (o *CustomReportDetailResponse) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *CustomReportDetailResponse) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *CustomReportDetailResponse) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *CustomReportDetailResponse) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetUpdatedAt

`func (o *CustomReportDetailResponse) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *CustomReportDetailResponse) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *CustomReportDetailResponse) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *CustomReportDetailResponse) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.

### GetFilters

`func (o *CustomReportDetailResponse) GetFilters() CustomReportFilters`

GetFilters returns the Filters field if non-nil, zero value otherwise.

### GetFiltersOk

`func (o *CustomReportDetailResponse) GetFiltersOk() (*CustomReportFilters, bool)`

GetFiltersOk returns a tuple with the Filters field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFilters

`func (o *CustomReportDetailResponse) SetFilters(v CustomReportFilters)`

SetFilters sets Filters field to given value.


### GetComparePrevious

`func (o *CustomReportDetailResponse) GetComparePrevious() bool`

GetComparePrevious returns the ComparePrevious field if non-nil, zero value otherwise.

### GetComparePreviousOk

`func (o *CustomReportDetailResponse) GetComparePreviousOk() (*bool, bool)`

GetComparePreviousOk returns a tuple with the ComparePrevious field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComparePrevious

`func (o *CustomReportDetailResponse) SetComparePrevious(v bool)`

SetComparePrevious sets ComparePrevious field to given value.

### HasComparePrevious

`func (o *CustomReportDetailResponse) HasComparePrevious() bool`

HasComparePrevious returns a boolean if a field has been set.

### GetAttachExcel

`func (o *CustomReportDetailResponse) GetAttachExcel() bool`

GetAttachExcel returns the AttachExcel field if non-nil, zero value otherwise.

### GetAttachExcelOk

`func (o *CustomReportDetailResponse) GetAttachExcelOk() (*bool, bool)`

GetAttachExcelOk returns a tuple with the AttachExcel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAttachExcel

`func (o *CustomReportDetailResponse) SetAttachExcel(v bool)`

SetAttachExcel sets AttachExcel field to given value.

### HasAttachExcel

`func (o *CustomReportDetailResponse) HasAttachExcel() bool`

HasAttachExcel returns a boolean if a field has been set.

### GetManualSendAvailableAt

`func (o *CustomReportDetailResponse) GetManualSendAvailableAt() time.Time`

GetManualSendAvailableAt returns the ManualSendAvailableAt field if non-nil, zero value otherwise.

### GetManualSendAvailableAtOk

`func (o *CustomReportDetailResponse) GetManualSendAvailableAtOk() (*time.Time, bool)`

GetManualSendAvailableAtOk returns a tuple with the ManualSendAvailableAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetManualSendAvailableAt

`func (o *CustomReportDetailResponse) SetManualSendAvailableAt(v time.Time)`

SetManualSendAvailableAt sets ManualSendAvailableAt field to given value.

### HasManualSendAvailableAt

`func (o *CustomReportDetailResponse) HasManualSendAvailableAt() bool`

HasManualSendAvailableAt returns a boolean if a field has been set.

### SetManualSendAvailableAtNil

`func (o *CustomReportDetailResponse) SetManualSendAvailableAtNil(b bool)`

 SetManualSendAvailableAtNil sets the value for ManualSendAvailableAt to be an explicit nil

### UnsetManualSendAvailableAt
`func (o *CustomReportDetailResponse) UnsetManualSendAvailableAt()`

UnsetManualSendAvailableAt ensures that no value is present for ManualSendAvailableAt, not even an explicit nil
### GetGeneratedAt

`func (o *CustomReportDetailResponse) GetGeneratedAt() time.Time`

GetGeneratedAt returns the GeneratedAt field if non-nil, zero value otherwise.

### GetGeneratedAtOk

`func (o *CustomReportDetailResponse) GetGeneratedAtOk() (*time.Time, bool)`

GetGeneratedAtOk returns a tuple with the GeneratedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGeneratedAt

`func (o *CustomReportDetailResponse) SetGeneratedAt(v time.Time)`

SetGeneratedAt sets GeneratedAt field to given value.


### GetBlocks

`func (o *CustomReportDetailResponse) GetBlocks() []CustomReportBlock`

GetBlocks returns the Blocks field if non-nil, zero value otherwise.

### GetBlocksOk

`func (o *CustomReportDetailResponse) GetBlocksOk() (*[]CustomReportBlock, bool)`

GetBlocksOk returns a tuple with the Blocks field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBlocks

`func (o *CustomReportDetailResponse) SetBlocks(v []CustomReportBlock)`

SetBlocks sets Blocks field to given value.


### GetWidgets

`func (o *CustomReportDetailResponse) GetWidgets() []CustomReportWidget`

GetWidgets returns the Widgets field if non-nil, zero value otherwise.

### GetWidgetsOk

`func (o *CustomReportDetailResponse) GetWidgetsOk() (*[]CustomReportWidget, bool)`

GetWidgetsOk returns a tuple with the Widgets field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWidgets

`func (o *CustomReportDetailResponse) SetWidgets(v []CustomReportWidget)`

SetWidgets sets Widgets field to given value.


### GetRequestId

`func (o *CustomReportDetailResponse) GetRequestId() string`

GetRequestId returns the RequestId field if non-nil, zero value otherwise.

### GetRequestIdOk

`func (o *CustomReportDetailResponse) GetRequestIdOk() (*string, bool)`

GetRequestIdOk returns a tuple with the RequestId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestId

`func (o *CustomReportDetailResponse) SetRequestId(v string)`

SetRequestId sets RequestId field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


