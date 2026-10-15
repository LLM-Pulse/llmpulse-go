# CustomReportWidget

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Key** | **string** |  | 
**Label** | **string** |  | 
**Kind** | **string** |  | 
**Width** | **string** |  | 
**Available** | **bool** | false when the widget&#39;s data source (web analytics, agent analytics, owned media) is not connected | 
**Data** | Pointer to **map[string]interface{}** | Shaped by kind. timeseries: series [{ name, color, points [{ date, value }] }]. donut: slices [{ name, value, color }]. bar: bars [{ label, value, color }]. kpi_grid: values and changes (null unless the report compares with the previous period). table: rows, one object per row. Null when the widget is not available. | [optional] 

## Methods

### NewCustomReportWidget

`func NewCustomReportWidget(key string, label string, kind string, width string, available bool, ) *CustomReportWidget`

NewCustomReportWidget instantiates a new CustomReportWidget object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCustomReportWidgetWithDefaults

`func NewCustomReportWidgetWithDefaults() *CustomReportWidget`

NewCustomReportWidgetWithDefaults instantiates a new CustomReportWidget object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetKey

`func (o *CustomReportWidget) GetKey() string`

GetKey returns the Key field if non-nil, zero value otherwise.

### GetKeyOk

`func (o *CustomReportWidget) GetKeyOk() (*string, bool)`

GetKeyOk returns a tuple with the Key field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKey

`func (o *CustomReportWidget) SetKey(v string)`

SetKey sets Key field to given value.


### GetLabel

`func (o *CustomReportWidget) GetLabel() string`

GetLabel returns the Label field if non-nil, zero value otherwise.

### GetLabelOk

`func (o *CustomReportWidget) GetLabelOk() (*string, bool)`

GetLabelOk returns a tuple with the Label field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabel

`func (o *CustomReportWidget) SetLabel(v string)`

SetLabel sets Label field to given value.


### GetKind

`func (o *CustomReportWidget) GetKind() string`

GetKind returns the Kind field if non-nil, zero value otherwise.

### GetKindOk

`func (o *CustomReportWidget) GetKindOk() (*string, bool)`

GetKindOk returns a tuple with the Kind field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKind

`func (o *CustomReportWidget) SetKind(v string)`

SetKind sets Kind field to given value.


### GetWidth

`func (o *CustomReportWidget) GetWidth() string`

GetWidth returns the Width field if non-nil, zero value otherwise.

### GetWidthOk

`func (o *CustomReportWidget) GetWidthOk() (*string, bool)`

GetWidthOk returns a tuple with the Width field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWidth

`func (o *CustomReportWidget) SetWidth(v string)`

SetWidth sets Width field to given value.


### GetAvailable

`func (o *CustomReportWidget) GetAvailable() bool`

GetAvailable returns the Available field if non-nil, zero value otherwise.

### GetAvailableOk

`func (o *CustomReportWidget) GetAvailableOk() (*bool, bool)`

GetAvailableOk returns a tuple with the Available field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAvailable

`func (o *CustomReportWidget) SetAvailable(v bool)`

SetAvailable sets Available field to given value.


### GetData

`func (o *CustomReportWidget) GetData() map[string]interface{}`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *CustomReportWidget) GetDataOk() (*map[string]interface{}, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *CustomReportWidget) SetData(v map[string]interface{})`

SetData sets Data field to given value.

### HasData

`func (o *CustomReportWidget) HasData() bool`

HasData returns a boolean if a field has been set.

### SetDataNil

`func (o *CustomReportWidget) SetDataNil(b bool)`

 SetDataNil sets the value for Data to be an explicit nil

### UnsetData
`func (o *CustomReportWidget) UnsetData()`

UnsetData ensures that no value is present for Data, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


