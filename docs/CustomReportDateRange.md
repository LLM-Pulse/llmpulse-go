# CustomReportDateRange

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Type** | **string** | rolling (the last range_days days), previous_month (the previous calendar month), previous_3_months (the 3 calendar months before the current one) or custom (fixed dates, custom_from to custom_to) | 
**RangeDays** | **NullableInt32** | Length of a rolling window; null for the other types | 
**CustomFrom** | **NullableString** | First day chosen for a custom range; null for the other types | 
**CustomTo** | **NullableString** | Last day chosen for a custom range, which can be after today; null for the other types | 
**From** | Pointer to **string** | First day of the window as of now (detail only) | [optional] 
**To** | Pointer to **string** | Last day of the window as of now (detail only); a custom range stops at today | [optional] 
**Label** | Pointer to **string** | The window as the report shows it (detail only) | [optional] 

## Methods

### NewCustomReportDateRange

`func NewCustomReportDateRange(type_ string, rangeDays NullableInt32, customFrom NullableString, customTo NullableString, ) *CustomReportDateRange`

NewCustomReportDateRange instantiates a new CustomReportDateRange object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCustomReportDateRangeWithDefaults

`func NewCustomReportDateRangeWithDefaults() *CustomReportDateRange`

NewCustomReportDateRangeWithDefaults instantiates a new CustomReportDateRange object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetType

`func (o *CustomReportDateRange) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *CustomReportDateRange) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *CustomReportDateRange) SetType(v string)`

SetType sets Type field to given value.


### GetRangeDays

`func (o *CustomReportDateRange) GetRangeDays() int32`

GetRangeDays returns the RangeDays field if non-nil, zero value otherwise.

### GetRangeDaysOk

`func (o *CustomReportDateRange) GetRangeDaysOk() (*int32, bool)`

GetRangeDaysOk returns a tuple with the RangeDays field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRangeDays

`func (o *CustomReportDateRange) SetRangeDays(v int32)`

SetRangeDays sets RangeDays field to given value.


### SetRangeDaysNil

`func (o *CustomReportDateRange) SetRangeDaysNil(b bool)`

 SetRangeDaysNil sets the value for RangeDays to be an explicit nil

### UnsetRangeDays
`func (o *CustomReportDateRange) UnsetRangeDays()`

UnsetRangeDays ensures that no value is present for RangeDays, not even an explicit nil
### GetCustomFrom

`func (o *CustomReportDateRange) GetCustomFrom() string`

GetCustomFrom returns the CustomFrom field if non-nil, zero value otherwise.

### GetCustomFromOk

`func (o *CustomReportDateRange) GetCustomFromOk() (*string, bool)`

GetCustomFromOk returns a tuple with the CustomFrom field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomFrom

`func (o *CustomReportDateRange) SetCustomFrom(v string)`

SetCustomFrom sets CustomFrom field to given value.


### SetCustomFromNil

`func (o *CustomReportDateRange) SetCustomFromNil(b bool)`

 SetCustomFromNil sets the value for CustomFrom to be an explicit nil

### UnsetCustomFrom
`func (o *CustomReportDateRange) UnsetCustomFrom()`

UnsetCustomFrom ensures that no value is present for CustomFrom, not even an explicit nil
### GetCustomTo

`func (o *CustomReportDateRange) GetCustomTo() string`

GetCustomTo returns the CustomTo field if non-nil, zero value otherwise.

### GetCustomToOk

`func (o *CustomReportDateRange) GetCustomToOk() (*string, bool)`

GetCustomToOk returns a tuple with the CustomTo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomTo

`func (o *CustomReportDateRange) SetCustomTo(v string)`

SetCustomTo sets CustomTo field to given value.


### SetCustomToNil

`func (o *CustomReportDateRange) SetCustomToNil(b bool)`

 SetCustomToNil sets the value for CustomTo to be an explicit nil

### UnsetCustomTo
`func (o *CustomReportDateRange) UnsetCustomTo()`

UnsetCustomTo ensures that no value is present for CustomTo, not even an explicit nil
### GetFrom

`func (o *CustomReportDateRange) GetFrom() string`

GetFrom returns the From field if non-nil, zero value otherwise.

### GetFromOk

`func (o *CustomReportDateRange) GetFromOk() (*string, bool)`

GetFromOk returns a tuple with the From field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFrom

`func (o *CustomReportDateRange) SetFrom(v string)`

SetFrom sets From field to given value.

### HasFrom

`func (o *CustomReportDateRange) HasFrom() bool`

HasFrom returns a boolean if a field has been set.

### GetTo

`func (o *CustomReportDateRange) GetTo() string`

GetTo returns the To field if non-nil, zero value otherwise.

### GetToOk

`func (o *CustomReportDateRange) GetToOk() (*string, bool)`

GetToOk returns a tuple with the To field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTo

`func (o *CustomReportDateRange) SetTo(v string)`

SetTo sets To field to given value.

### HasTo

`func (o *CustomReportDateRange) HasTo() bool`

HasTo returns a boolean if a field has been set.

### GetLabel

`func (o *CustomReportDateRange) GetLabel() string`

GetLabel returns the Label field if non-nil, zero value otherwise.

### GetLabelOk

`func (o *CustomReportDateRange) GetLabelOk() (*string, bool)`

GetLabelOk returns a tuple with the Label field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabel

`func (o *CustomReportDateRange) SetLabel(v string)`

SetLabel sets Label field to given value.

### HasLabel

`func (o *CustomReportDateRange) HasLabel() bool`

HasLabel returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


