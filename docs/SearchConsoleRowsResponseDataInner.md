# SearchConsoleRowsResponseDataInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Date** | Pointer to **string** |  | [optional] 
**Country** | Pointer to **string** |  | [optional] 
**Device** | Pointer to **string** |  | [optional] 
**Page** | Pointer to **string** |  | [optional] 
**Query** | Pointer to **string** |  | [optional] 
**SearchAppearance** | Pointer to **string** |  | [optional] 
**Impressions** | Pointer to **int32** |  | [optional] 
**Clicks** | Pointer to **int32** |  | [optional] 
**Ctr** | Pointer to **float32** | 0..1 fraction | [optional] 
**Position** | Pointer to **float32** | Impression-weighted average position | [optional] 
**Property** | Pointer to **string** | Present when grouped by property | [optional] 

## Methods

### NewSearchConsoleRowsResponseDataInner

`func NewSearchConsoleRowsResponseDataInner() *SearchConsoleRowsResponseDataInner`

NewSearchConsoleRowsResponseDataInner instantiates a new SearchConsoleRowsResponseDataInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSearchConsoleRowsResponseDataInnerWithDefaults

`func NewSearchConsoleRowsResponseDataInnerWithDefaults() *SearchConsoleRowsResponseDataInner`

NewSearchConsoleRowsResponseDataInnerWithDefaults instantiates a new SearchConsoleRowsResponseDataInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDate

`func (o *SearchConsoleRowsResponseDataInner) GetDate() string`

GetDate returns the Date field if non-nil, zero value otherwise.

### GetDateOk

`func (o *SearchConsoleRowsResponseDataInner) GetDateOk() (*string, bool)`

GetDateOk returns a tuple with the Date field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDate

`func (o *SearchConsoleRowsResponseDataInner) SetDate(v string)`

SetDate sets Date field to given value.

### HasDate

`func (o *SearchConsoleRowsResponseDataInner) HasDate() bool`

HasDate returns a boolean if a field has been set.

### GetCountry

`func (o *SearchConsoleRowsResponseDataInner) GetCountry() string`

GetCountry returns the Country field if non-nil, zero value otherwise.

### GetCountryOk

`func (o *SearchConsoleRowsResponseDataInner) GetCountryOk() (*string, bool)`

GetCountryOk returns a tuple with the Country field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountry

`func (o *SearchConsoleRowsResponseDataInner) SetCountry(v string)`

SetCountry sets Country field to given value.

### HasCountry

`func (o *SearchConsoleRowsResponseDataInner) HasCountry() bool`

HasCountry returns a boolean if a field has been set.

### GetDevice

`func (o *SearchConsoleRowsResponseDataInner) GetDevice() string`

GetDevice returns the Device field if non-nil, zero value otherwise.

### GetDeviceOk

`func (o *SearchConsoleRowsResponseDataInner) GetDeviceOk() (*string, bool)`

GetDeviceOk returns a tuple with the Device field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDevice

`func (o *SearchConsoleRowsResponseDataInner) SetDevice(v string)`

SetDevice sets Device field to given value.

### HasDevice

`func (o *SearchConsoleRowsResponseDataInner) HasDevice() bool`

HasDevice returns a boolean if a field has been set.

### GetPage

`func (o *SearchConsoleRowsResponseDataInner) GetPage() string`

GetPage returns the Page field if non-nil, zero value otherwise.

### GetPageOk

`func (o *SearchConsoleRowsResponseDataInner) GetPageOk() (*string, bool)`

GetPageOk returns a tuple with the Page field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPage

`func (o *SearchConsoleRowsResponseDataInner) SetPage(v string)`

SetPage sets Page field to given value.

### HasPage

`func (o *SearchConsoleRowsResponseDataInner) HasPage() bool`

HasPage returns a boolean if a field has been set.

### GetQuery

`func (o *SearchConsoleRowsResponseDataInner) GetQuery() string`

GetQuery returns the Query field if non-nil, zero value otherwise.

### GetQueryOk

`func (o *SearchConsoleRowsResponseDataInner) GetQueryOk() (*string, bool)`

GetQueryOk returns a tuple with the Query field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuery

`func (o *SearchConsoleRowsResponseDataInner) SetQuery(v string)`

SetQuery sets Query field to given value.

### HasQuery

`func (o *SearchConsoleRowsResponseDataInner) HasQuery() bool`

HasQuery returns a boolean if a field has been set.

### GetSearchAppearance

`func (o *SearchConsoleRowsResponseDataInner) GetSearchAppearance() string`

GetSearchAppearance returns the SearchAppearance field if non-nil, zero value otherwise.

### GetSearchAppearanceOk

`func (o *SearchConsoleRowsResponseDataInner) GetSearchAppearanceOk() (*string, bool)`

GetSearchAppearanceOk returns a tuple with the SearchAppearance field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSearchAppearance

`func (o *SearchConsoleRowsResponseDataInner) SetSearchAppearance(v string)`

SetSearchAppearance sets SearchAppearance field to given value.

### HasSearchAppearance

`func (o *SearchConsoleRowsResponseDataInner) HasSearchAppearance() bool`

HasSearchAppearance returns a boolean if a field has been set.

### GetImpressions

`func (o *SearchConsoleRowsResponseDataInner) GetImpressions() int32`

GetImpressions returns the Impressions field if non-nil, zero value otherwise.

### GetImpressionsOk

`func (o *SearchConsoleRowsResponseDataInner) GetImpressionsOk() (*int32, bool)`

GetImpressionsOk returns a tuple with the Impressions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImpressions

`func (o *SearchConsoleRowsResponseDataInner) SetImpressions(v int32)`

SetImpressions sets Impressions field to given value.

### HasImpressions

`func (o *SearchConsoleRowsResponseDataInner) HasImpressions() bool`

HasImpressions returns a boolean if a field has been set.

### GetClicks

`func (o *SearchConsoleRowsResponseDataInner) GetClicks() int32`

GetClicks returns the Clicks field if non-nil, zero value otherwise.

### GetClicksOk

`func (o *SearchConsoleRowsResponseDataInner) GetClicksOk() (*int32, bool)`

GetClicksOk returns a tuple with the Clicks field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClicks

`func (o *SearchConsoleRowsResponseDataInner) SetClicks(v int32)`

SetClicks sets Clicks field to given value.

### HasClicks

`func (o *SearchConsoleRowsResponseDataInner) HasClicks() bool`

HasClicks returns a boolean if a field has been set.

### GetCtr

`func (o *SearchConsoleRowsResponseDataInner) GetCtr() float32`

GetCtr returns the Ctr field if non-nil, zero value otherwise.

### GetCtrOk

`func (o *SearchConsoleRowsResponseDataInner) GetCtrOk() (*float32, bool)`

GetCtrOk returns a tuple with the Ctr field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCtr

`func (o *SearchConsoleRowsResponseDataInner) SetCtr(v float32)`

SetCtr sets Ctr field to given value.

### HasCtr

`func (o *SearchConsoleRowsResponseDataInner) HasCtr() bool`

HasCtr returns a boolean if a field has been set.

### GetPosition

`func (o *SearchConsoleRowsResponseDataInner) GetPosition() float32`

GetPosition returns the Position field if non-nil, zero value otherwise.

### GetPositionOk

`func (o *SearchConsoleRowsResponseDataInner) GetPositionOk() (*float32, bool)`

GetPositionOk returns a tuple with the Position field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPosition

`func (o *SearchConsoleRowsResponseDataInner) SetPosition(v float32)`

SetPosition sets Position field to given value.

### HasPosition

`func (o *SearchConsoleRowsResponseDataInner) HasPosition() bool`

HasPosition returns a boolean if a field has been set.

### GetProperty

`func (o *SearchConsoleRowsResponseDataInner) GetProperty() string`

GetProperty returns the Property field if non-nil, zero value otherwise.

### GetPropertyOk

`func (o *SearchConsoleRowsResponseDataInner) GetPropertyOk() (*string, bool)`

GetPropertyOk returns a tuple with the Property field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProperty

`func (o *SearchConsoleRowsResponseDataInner) SetProperty(v string)`

SetProperty sets Property field to given value.

### HasProperty

`func (o *SearchConsoleRowsResponseDataInner) HasProperty() bool`

HasProperty returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


