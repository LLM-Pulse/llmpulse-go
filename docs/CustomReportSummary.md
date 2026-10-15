# CustomReportSummary

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **int32** |  | 
**Name** | **string** |  | 
**DateRange** | [**CustomReportDateRange**](CustomReportDateRange.md) |  | 
**Schedule** | [**CustomReportSchedule**](CustomReportSchedule.md) |  | 
**RecipientsCount** | **int32** |  | 
**Published** | **bool** | Whether the shared link is published | 
**PublicLinkActive** | **bool** | Whether the shared link opens (published and not made inside a client portal) | 
**PasswordProtected** | **bool** |  | 
**PortalOnly** | **bool** | Made inside a client portal, so it cannot be shared or emailed | 
**WidgetCount** | **int32** |  | 
**Widgets** | [**[]CustomReportWidgetRef**](CustomReportWidgetRef.md) |  | 
**LastSentAt** | Pointer to **NullableTime** | When the report was last emailed, on its schedule or with Send now | [optional] 
**CreatedAt** | **time.Time** |  | 
**UpdatedAt** | **time.Time** |  | 

## Methods

### NewCustomReportSummary

`func NewCustomReportSummary(id int32, name string, dateRange CustomReportDateRange, schedule CustomReportSchedule, recipientsCount int32, published bool, publicLinkActive bool, passwordProtected bool, portalOnly bool, widgetCount int32, widgets []CustomReportWidgetRef, createdAt time.Time, updatedAt time.Time, ) *CustomReportSummary`

NewCustomReportSummary instantiates a new CustomReportSummary object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCustomReportSummaryWithDefaults

`func NewCustomReportSummaryWithDefaults() *CustomReportSummary`

NewCustomReportSummaryWithDefaults instantiates a new CustomReportSummary object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *CustomReportSummary) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *CustomReportSummary) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *CustomReportSummary) SetId(v int32)`

SetId sets Id field to given value.


### GetName

`func (o *CustomReportSummary) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *CustomReportSummary) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *CustomReportSummary) SetName(v string)`

SetName sets Name field to given value.


### GetDateRange

`func (o *CustomReportSummary) GetDateRange() CustomReportDateRange`

GetDateRange returns the DateRange field if non-nil, zero value otherwise.

### GetDateRangeOk

`func (o *CustomReportSummary) GetDateRangeOk() (*CustomReportDateRange, bool)`

GetDateRangeOk returns a tuple with the DateRange field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDateRange

`func (o *CustomReportSummary) SetDateRange(v CustomReportDateRange)`

SetDateRange sets DateRange field to given value.


### GetSchedule

`func (o *CustomReportSummary) GetSchedule() CustomReportSchedule`

GetSchedule returns the Schedule field if non-nil, zero value otherwise.

### GetScheduleOk

`func (o *CustomReportSummary) GetScheduleOk() (*CustomReportSchedule, bool)`

GetScheduleOk returns a tuple with the Schedule field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSchedule

`func (o *CustomReportSummary) SetSchedule(v CustomReportSchedule)`

SetSchedule sets Schedule field to given value.


### GetRecipientsCount

`func (o *CustomReportSummary) GetRecipientsCount() int32`

GetRecipientsCount returns the RecipientsCount field if non-nil, zero value otherwise.

### GetRecipientsCountOk

`func (o *CustomReportSummary) GetRecipientsCountOk() (*int32, bool)`

GetRecipientsCountOk returns a tuple with the RecipientsCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRecipientsCount

`func (o *CustomReportSummary) SetRecipientsCount(v int32)`

SetRecipientsCount sets RecipientsCount field to given value.


### GetPublished

`func (o *CustomReportSummary) GetPublished() bool`

GetPublished returns the Published field if non-nil, zero value otherwise.

### GetPublishedOk

`func (o *CustomReportSummary) GetPublishedOk() (*bool, bool)`

GetPublishedOk returns a tuple with the Published field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPublished

`func (o *CustomReportSummary) SetPublished(v bool)`

SetPublished sets Published field to given value.


### GetPublicLinkActive

`func (o *CustomReportSummary) GetPublicLinkActive() bool`

GetPublicLinkActive returns the PublicLinkActive field if non-nil, zero value otherwise.

### GetPublicLinkActiveOk

`func (o *CustomReportSummary) GetPublicLinkActiveOk() (*bool, bool)`

GetPublicLinkActiveOk returns a tuple with the PublicLinkActive field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPublicLinkActive

`func (o *CustomReportSummary) SetPublicLinkActive(v bool)`

SetPublicLinkActive sets PublicLinkActive field to given value.


### GetPasswordProtected

`func (o *CustomReportSummary) GetPasswordProtected() bool`

GetPasswordProtected returns the PasswordProtected field if non-nil, zero value otherwise.

### GetPasswordProtectedOk

`func (o *CustomReportSummary) GetPasswordProtectedOk() (*bool, bool)`

GetPasswordProtectedOk returns a tuple with the PasswordProtected field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPasswordProtected

`func (o *CustomReportSummary) SetPasswordProtected(v bool)`

SetPasswordProtected sets PasswordProtected field to given value.


### GetPortalOnly

`func (o *CustomReportSummary) GetPortalOnly() bool`

GetPortalOnly returns the PortalOnly field if non-nil, zero value otherwise.

### GetPortalOnlyOk

`func (o *CustomReportSummary) GetPortalOnlyOk() (*bool, bool)`

GetPortalOnlyOk returns a tuple with the PortalOnly field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPortalOnly

`func (o *CustomReportSummary) SetPortalOnly(v bool)`

SetPortalOnly sets PortalOnly field to given value.


### GetWidgetCount

`func (o *CustomReportSummary) GetWidgetCount() int32`

GetWidgetCount returns the WidgetCount field if non-nil, zero value otherwise.

### GetWidgetCountOk

`func (o *CustomReportSummary) GetWidgetCountOk() (*int32, bool)`

GetWidgetCountOk returns a tuple with the WidgetCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWidgetCount

`func (o *CustomReportSummary) SetWidgetCount(v int32)`

SetWidgetCount sets WidgetCount field to given value.


### GetWidgets

`func (o *CustomReportSummary) GetWidgets() []CustomReportWidgetRef`

GetWidgets returns the Widgets field if non-nil, zero value otherwise.

### GetWidgetsOk

`func (o *CustomReportSummary) GetWidgetsOk() (*[]CustomReportWidgetRef, bool)`

GetWidgetsOk returns a tuple with the Widgets field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWidgets

`func (o *CustomReportSummary) SetWidgets(v []CustomReportWidgetRef)`

SetWidgets sets Widgets field to given value.


### GetLastSentAt

`func (o *CustomReportSummary) GetLastSentAt() time.Time`

GetLastSentAt returns the LastSentAt field if non-nil, zero value otherwise.

### GetLastSentAtOk

`func (o *CustomReportSummary) GetLastSentAtOk() (*time.Time, bool)`

GetLastSentAtOk returns a tuple with the LastSentAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastSentAt

`func (o *CustomReportSummary) SetLastSentAt(v time.Time)`

SetLastSentAt sets LastSentAt field to given value.

### HasLastSentAt

`func (o *CustomReportSummary) HasLastSentAt() bool`

HasLastSentAt returns a boolean if a field has been set.

### SetLastSentAtNil

`func (o *CustomReportSummary) SetLastSentAtNil(b bool)`

 SetLastSentAtNil sets the value for LastSentAt to be an explicit nil

### UnsetLastSentAt
`func (o *CustomReportSummary) UnsetLastSentAt()`

UnsetLastSentAt ensures that no value is present for LastSentAt, not even an explicit nil
### GetCreatedAt

`func (o *CustomReportSummary) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *CustomReportSummary) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *CustomReportSummary) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetUpdatedAt

`func (o *CustomReportSummary) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *CustomReportSummary) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *CustomReportSummary) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


