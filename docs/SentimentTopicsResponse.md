# SentimentTopicsResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ProjectId** | **int32** |  | 
**Page** | **int32** |  | 
**PerPage** | **int32** |  | 
**Total** | **int32** | Rows matching the filters across every page | 
**RequestId** | **string** |  | 
**From** | **time.Time** |  | 
**To** | **time.Time** |  | 
**Brand** | [**SentimentBreakdownBrand**](SentimentBreakdownBrand.md) |  | 
**Sort** | **string** |  | 
**SortDir** | **string** |  | 
**Data** | [**[]SentimentTopicRow**](SentimentTopicRow.md) |  | 

## Methods

### NewSentimentTopicsResponse

`func NewSentimentTopicsResponse(projectId int32, page int32, perPage int32, total int32, requestId string, from time.Time, to time.Time, brand SentimentBreakdownBrand, sort string, sortDir string, data []SentimentTopicRow, ) *SentimentTopicsResponse`

NewSentimentTopicsResponse instantiates a new SentimentTopicsResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSentimentTopicsResponseWithDefaults

`func NewSentimentTopicsResponseWithDefaults() *SentimentTopicsResponse`

NewSentimentTopicsResponseWithDefaults instantiates a new SentimentTopicsResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProjectId

`func (o *SentimentTopicsResponse) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *SentimentTopicsResponse) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *SentimentTopicsResponse) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.


### GetPage

`func (o *SentimentTopicsResponse) GetPage() int32`

GetPage returns the Page field if non-nil, zero value otherwise.

### GetPageOk

`func (o *SentimentTopicsResponse) GetPageOk() (*int32, bool)`

GetPageOk returns a tuple with the Page field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPage

`func (o *SentimentTopicsResponse) SetPage(v int32)`

SetPage sets Page field to given value.


### GetPerPage

`func (o *SentimentTopicsResponse) GetPerPage() int32`

GetPerPage returns the PerPage field if non-nil, zero value otherwise.

### GetPerPageOk

`func (o *SentimentTopicsResponse) GetPerPageOk() (*int32, bool)`

GetPerPageOk returns a tuple with the PerPage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPerPage

`func (o *SentimentTopicsResponse) SetPerPage(v int32)`

SetPerPage sets PerPage field to given value.


### GetTotal

`func (o *SentimentTopicsResponse) GetTotal() int32`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *SentimentTopicsResponse) GetTotalOk() (*int32, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *SentimentTopicsResponse) SetTotal(v int32)`

SetTotal sets Total field to given value.


### GetRequestId

`func (o *SentimentTopicsResponse) GetRequestId() string`

GetRequestId returns the RequestId field if non-nil, zero value otherwise.

### GetRequestIdOk

`func (o *SentimentTopicsResponse) GetRequestIdOk() (*string, bool)`

GetRequestIdOk returns a tuple with the RequestId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestId

`func (o *SentimentTopicsResponse) SetRequestId(v string)`

SetRequestId sets RequestId field to given value.


### GetFrom

`func (o *SentimentTopicsResponse) GetFrom() time.Time`

GetFrom returns the From field if non-nil, zero value otherwise.

### GetFromOk

`func (o *SentimentTopicsResponse) GetFromOk() (*time.Time, bool)`

GetFromOk returns a tuple with the From field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFrom

`func (o *SentimentTopicsResponse) SetFrom(v time.Time)`

SetFrom sets From field to given value.


### GetTo

`func (o *SentimentTopicsResponse) GetTo() time.Time`

GetTo returns the To field if non-nil, zero value otherwise.

### GetToOk

`func (o *SentimentTopicsResponse) GetToOk() (*time.Time, bool)`

GetToOk returns a tuple with the To field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTo

`func (o *SentimentTopicsResponse) SetTo(v time.Time)`

SetTo sets To field to given value.


### GetBrand

`func (o *SentimentTopicsResponse) GetBrand() SentimentBreakdownBrand`

GetBrand returns the Brand field if non-nil, zero value otherwise.

### GetBrandOk

`func (o *SentimentTopicsResponse) GetBrandOk() (*SentimentBreakdownBrand, bool)`

GetBrandOk returns a tuple with the Brand field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBrand

`func (o *SentimentTopicsResponse) SetBrand(v SentimentBreakdownBrand)`

SetBrand sets Brand field to given value.


### GetSort

`func (o *SentimentTopicsResponse) GetSort() string`

GetSort returns the Sort field if non-nil, zero value otherwise.

### GetSortOk

`func (o *SentimentTopicsResponse) GetSortOk() (*string, bool)`

GetSortOk returns a tuple with the Sort field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSort

`func (o *SentimentTopicsResponse) SetSort(v string)`

SetSort sets Sort field to given value.


### GetSortDir

`func (o *SentimentTopicsResponse) GetSortDir() string`

GetSortDir returns the SortDir field if non-nil, zero value otherwise.

### GetSortDirOk

`func (o *SentimentTopicsResponse) GetSortDirOk() (*string, bool)`

GetSortDirOk returns a tuple with the SortDir field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSortDir

`func (o *SentimentTopicsResponse) SetSortDir(v string)`

SetSortDir sets SortDir field to given value.


### GetData

`func (o *SentimentTopicsResponse) GetData() []SentimentTopicRow`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *SentimentTopicsResponse) GetDataOk() (*[]SentimentTopicRow, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *SentimentTopicsResponse) SetData(v []SentimentTopicRow)`

SetData sets Data field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


