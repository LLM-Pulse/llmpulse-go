# SentimentTagsResponse

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
**Data** | [**[]SentimentTagRow**](SentimentTagRow.md) |  | 

## Methods

### NewSentimentTagsResponse

`func NewSentimentTagsResponse(projectId int32, page int32, perPage int32, total int32, requestId string, from time.Time, to time.Time, brand SentimentBreakdownBrand, sort string, sortDir string, data []SentimentTagRow, ) *SentimentTagsResponse`

NewSentimentTagsResponse instantiates a new SentimentTagsResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSentimentTagsResponseWithDefaults

`func NewSentimentTagsResponseWithDefaults() *SentimentTagsResponse`

NewSentimentTagsResponseWithDefaults instantiates a new SentimentTagsResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProjectId

`func (o *SentimentTagsResponse) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *SentimentTagsResponse) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *SentimentTagsResponse) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.


### GetPage

`func (o *SentimentTagsResponse) GetPage() int32`

GetPage returns the Page field if non-nil, zero value otherwise.

### GetPageOk

`func (o *SentimentTagsResponse) GetPageOk() (*int32, bool)`

GetPageOk returns a tuple with the Page field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPage

`func (o *SentimentTagsResponse) SetPage(v int32)`

SetPage sets Page field to given value.


### GetPerPage

`func (o *SentimentTagsResponse) GetPerPage() int32`

GetPerPage returns the PerPage field if non-nil, zero value otherwise.

### GetPerPageOk

`func (o *SentimentTagsResponse) GetPerPageOk() (*int32, bool)`

GetPerPageOk returns a tuple with the PerPage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPerPage

`func (o *SentimentTagsResponse) SetPerPage(v int32)`

SetPerPage sets PerPage field to given value.


### GetTotal

`func (o *SentimentTagsResponse) GetTotal() int32`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *SentimentTagsResponse) GetTotalOk() (*int32, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *SentimentTagsResponse) SetTotal(v int32)`

SetTotal sets Total field to given value.


### GetRequestId

`func (o *SentimentTagsResponse) GetRequestId() string`

GetRequestId returns the RequestId field if non-nil, zero value otherwise.

### GetRequestIdOk

`func (o *SentimentTagsResponse) GetRequestIdOk() (*string, bool)`

GetRequestIdOk returns a tuple with the RequestId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestId

`func (o *SentimentTagsResponse) SetRequestId(v string)`

SetRequestId sets RequestId field to given value.


### GetFrom

`func (o *SentimentTagsResponse) GetFrom() time.Time`

GetFrom returns the From field if non-nil, zero value otherwise.

### GetFromOk

`func (o *SentimentTagsResponse) GetFromOk() (*time.Time, bool)`

GetFromOk returns a tuple with the From field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFrom

`func (o *SentimentTagsResponse) SetFrom(v time.Time)`

SetFrom sets From field to given value.


### GetTo

`func (o *SentimentTagsResponse) GetTo() time.Time`

GetTo returns the To field if non-nil, zero value otherwise.

### GetToOk

`func (o *SentimentTagsResponse) GetToOk() (*time.Time, bool)`

GetToOk returns a tuple with the To field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTo

`func (o *SentimentTagsResponse) SetTo(v time.Time)`

SetTo sets To field to given value.


### GetBrand

`func (o *SentimentTagsResponse) GetBrand() SentimentBreakdownBrand`

GetBrand returns the Brand field if non-nil, zero value otherwise.

### GetBrandOk

`func (o *SentimentTagsResponse) GetBrandOk() (*SentimentBreakdownBrand, bool)`

GetBrandOk returns a tuple with the Brand field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBrand

`func (o *SentimentTagsResponse) SetBrand(v SentimentBreakdownBrand)`

SetBrand sets Brand field to given value.


### GetSort

`func (o *SentimentTagsResponse) GetSort() string`

GetSort returns the Sort field if non-nil, zero value otherwise.

### GetSortOk

`func (o *SentimentTagsResponse) GetSortOk() (*string, bool)`

GetSortOk returns a tuple with the Sort field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSort

`func (o *SentimentTagsResponse) SetSort(v string)`

SetSort sets Sort field to given value.


### GetSortDir

`func (o *SentimentTagsResponse) GetSortDir() string`

GetSortDir returns the SortDir field if non-nil, zero value otherwise.

### GetSortDirOk

`func (o *SentimentTagsResponse) GetSortDirOk() (*string, bool)`

GetSortDirOk returns a tuple with the SortDir field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSortDir

`func (o *SentimentTagsResponse) SetSortDir(v string)`

SetSortDir sets SortDir field to given value.


### GetData

`func (o *SentimentTagsResponse) GetData() []SentimentTagRow`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *SentimentTagsResponse) GetDataOk() (*[]SentimentTagRow, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *SentimentTagsResponse) SetData(v []SentimentTagRow)`

SetData sets Data field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


