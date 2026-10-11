# SearchConsoleTimeseriesResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ProjectId** | Pointer to **int32** |  | [optional] 
**Property** | Pointer to [**SearchConsoleProperty**](SearchConsoleProperty.md) |  | [optional] 
**From** | Pointer to **string** |  | [optional] 
**To** | Pointer to **string** |  | [optional] 
**DataThrough** | Pointer to **NullableString** | Latest date Google has published for the property (it lags 2-3 days). Later days are missing, not zero. | [optional] 
**Granularity** | Pointer to **string** |  | [optional] 
**Data** | Pointer to [**[]SearchConsoleTimeseriesResponseDataInner**](SearchConsoleTimeseriesResponseDataInner.md) |  | [optional] 
**RequestId** | Pointer to **string** |  | [optional] 

## Methods

### NewSearchConsoleTimeseriesResponse

`func NewSearchConsoleTimeseriesResponse() *SearchConsoleTimeseriesResponse`

NewSearchConsoleTimeseriesResponse instantiates a new SearchConsoleTimeseriesResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSearchConsoleTimeseriesResponseWithDefaults

`func NewSearchConsoleTimeseriesResponseWithDefaults() *SearchConsoleTimeseriesResponse`

NewSearchConsoleTimeseriesResponseWithDefaults instantiates a new SearchConsoleTimeseriesResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProjectId

`func (o *SearchConsoleTimeseriesResponse) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *SearchConsoleTimeseriesResponse) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *SearchConsoleTimeseriesResponse) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.

### HasProjectId

`func (o *SearchConsoleTimeseriesResponse) HasProjectId() bool`

HasProjectId returns a boolean if a field has been set.

### GetProperty

`func (o *SearchConsoleTimeseriesResponse) GetProperty() SearchConsoleProperty`

GetProperty returns the Property field if non-nil, zero value otherwise.

### GetPropertyOk

`func (o *SearchConsoleTimeseriesResponse) GetPropertyOk() (*SearchConsoleProperty, bool)`

GetPropertyOk returns a tuple with the Property field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProperty

`func (o *SearchConsoleTimeseriesResponse) SetProperty(v SearchConsoleProperty)`

SetProperty sets Property field to given value.

### HasProperty

`func (o *SearchConsoleTimeseriesResponse) HasProperty() bool`

HasProperty returns a boolean if a field has been set.

### GetFrom

`func (o *SearchConsoleTimeseriesResponse) GetFrom() string`

GetFrom returns the From field if non-nil, zero value otherwise.

### GetFromOk

`func (o *SearchConsoleTimeseriesResponse) GetFromOk() (*string, bool)`

GetFromOk returns a tuple with the From field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFrom

`func (o *SearchConsoleTimeseriesResponse) SetFrom(v string)`

SetFrom sets From field to given value.

### HasFrom

`func (o *SearchConsoleTimeseriesResponse) HasFrom() bool`

HasFrom returns a boolean if a field has been set.

### GetTo

`func (o *SearchConsoleTimeseriesResponse) GetTo() string`

GetTo returns the To field if non-nil, zero value otherwise.

### GetToOk

`func (o *SearchConsoleTimeseriesResponse) GetToOk() (*string, bool)`

GetToOk returns a tuple with the To field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTo

`func (o *SearchConsoleTimeseriesResponse) SetTo(v string)`

SetTo sets To field to given value.

### HasTo

`func (o *SearchConsoleTimeseriesResponse) HasTo() bool`

HasTo returns a boolean if a field has been set.

### GetDataThrough

`func (o *SearchConsoleTimeseriesResponse) GetDataThrough() string`

GetDataThrough returns the DataThrough field if non-nil, zero value otherwise.

### GetDataThroughOk

`func (o *SearchConsoleTimeseriesResponse) GetDataThroughOk() (*string, bool)`

GetDataThroughOk returns a tuple with the DataThrough field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDataThrough

`func (o *SearchConsoleTimeseriesResponse) SetDataThrough(v string)`

SetDataThrough sets DataThrough field to given value.

### HasDataThrough

`func (o *SearchConsoleTimeseriesResponse) HasDataThrough() bool`

HasDataThrough returns a boolean if a field has been set.

### SetDataThroughNil

`func (o *SearchConsoleTimeseriesResponse) SetDataThroughNil(b bool)`

 SetDataThroughNil sets the value for DataThrough to be an explicit nil

### UnsetDataThrough
`func (o *SearchConsoleTimeseriesResponse) UnsetDataThrough()`

UnsetDataThrough ensures that no value is present for DataThrough, not even an explicit nil
### GetGranularity

`func (o *SearchConsoleTimeseriesResponse) GetGranularity() string`

GetGranularity returns the Granularity field if non-nil, zero value otherwise.

### GetGranularityOk

`func (o *SearchConsoleTimeseriesResponse) GetGranularityOk() (*string, bool)`

GetGranularityOk returns a tuple with the Granularity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGranularity

`func (o *SearchConsoleTimeseriesResponse) SetGranularity(v string)`

SetGranularity sets Granularity field to given value.

### HasGranularity

`func (o *SearchConsoleTimeseriesResponse) HasGranularity() bool`

HasGranularity returns a boolean if a field has been set.

### GetData

`func (o *SearchConsoleTimeseriesResponse) GetData() []SearchConsoleTimeseriesResponseDataInner`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *SearchConsoleTimeseriesResponse) GetDataOk() (*[]SearchConsoleTimeseriesResponseDataInner, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *SearchConsoleTimeseriesResponse) SetData(v []SearchConsoleTimeseriesResponseDataInner)`

SetData sets Data field to given value.

### HasData

`func (o *SearchConsoleTimeseriesResponse) HasData() bool`

HasData returns a boolean if a field has been set.

### GetRequestId

`func (o *SearchConsoleTimeseriesResponse) GetRequestId() string`

GetRequestId returns the RequestId field if non-nil, zero value otherwise.

### GetRequestIdOk

`func (o *SearchConsoleTimeseriesResponse) GetRequestIdOk() (*string, bool)`

GetRequestIdOk returns a tuple with the RequestId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestId

`func (o *SearchConsoleTimeseriesResponse) SetRequestId(v string)`

SetRequestId sets RequestId field to given value.

### HasRequestId

`func (o *SearchConsoleTimeseriesResponse) HasRequestId() bool`

HasRequestId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


