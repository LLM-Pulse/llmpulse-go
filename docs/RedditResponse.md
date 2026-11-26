# RedditResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ProjectId** | **int32** |  | 
**Page** | **int32** |  | 
**PerPage** | **int32** |  | 
**Total** | **int32** | Rows matching the filters across every page | 
**RequestId** | **string** |  | 
**View** | **string** | subreddits, authors, threads or breakdowns | 
**From** | **time.Time** | Start of the window, 30 days back by default | 
**To** | **time.Time** |  | 
**Citations** | Pointer to **int32** | Reddit citations after the filters (view&#x3D;breakdowns) | [optional] 
**Data** | [**[]RedditRow**](RedditRow.md) |  | 

## Methods

### NewRedditResponse

`func NewRedditResponse(projectId int32, page int32, perPage int32, total int32, requestId string, view string, from time.Time, to time.Time, data []RedditRow, ) *RedditResponse`

NewRedditResponse instantiates a new RedditResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRedditResponseWithDefaults

`func NewRedditResponseWithDefaults() *RedditResponse`

NewRedditResponseWithDefaults instantiates a new RedditResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProjectId

`func (o *RedditResponse) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *RedditResponse) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *RedditResponse) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.


### GetPage

`func (o *RedditResponse) GetPage() int32`

GetPage returns the Page field if non-nil, zero value otherwise.

### GetPageOk

`func (o *RedditResponse) GetPageOk() (*int32, bool)`

GetPageOk returns a tuple with the Page field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPage

`func (o *RedditResponse) SetPage(v int32)`

SetPage sets Page field to given value.


### GetPerPage

`func (o *RedditResponse) GetPerPage() int32`

GetPerPage returns the PerPage field if non-nil, zero value otherwise.

### GetPerPageOk

`func (o *RedditResponse) GetPerPageOk() (*int32, bool)`

GetPerPageOk returns a tuple with the PerPage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPerPage

`func (o *RedditResponse) SetPerPage(v int32)`

SetPerPage sets PerPage field to given value.


### GetTotal

`func (o *RedditResponse) GetTotal() int32`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *RedditResponse) GetTotalOk() (*int32, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *RedditResponse) SetTotal(v int32)`

SetTotal sets Total field to given value.


### GetRequestId

`func (o *RedditResponse) GetRequestId() string`

GetRequestId returns the RequestId field if non-nil, zero value otherwise.

### GetRequestIdOk

`func (o *RedditResponse) GetRequestIdOk() (*string, bool)`

GetRequestIdOk returns a tuple with the RequestId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestId

`func (o *RedditResponse) SetRequestId(v string)`

SetRequestId sets RequestId field to given value.


### GetView

`func (o *RedditResponse) GetView() string`

GetView returns the View field if non-nil, zero value otherwise.

### GetViewOk

`func (o *RedditResponse) GetViewOk() (*string, bool)`

GetViewOk returns a tuple with the View field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetView

`func (o *RedditResponse) SetView(v string)`

SetView sets View field to given value.


### GetFrom

`func (o *RedditResponse) GetFrom() time.Time`

GetFrom returns the From field if non-nil, zero value otherwise.

### GetFromOk

`func (o *RedditResponse) GetFromOk() (*time.Time, bool)`

GetFromOk returns a tuple with the From field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFrom

`func (o *RedditResponse) SetFrom(v time.Time)`

SetFrom sets From field to given value.


### GetTo

`func (o *RedditResponse) GetTo() time.Time`

GetTo returns the To field if non-nil, zero value otherwise.

### GetToOk

`func (o *RedditResponse) GetToOk() (*time.Time, bool)`

GetToOk returns a tuple with the To field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTo

`func (o *RedditResponse) SetTo(v time.Time)`

SetTo sets To field to given value.


### GetCitations

`func (o *RedditResponse) GetCitations() int32`

GetCitations returns the Citations field if non-nil, zero value otherwise.

### GetCitationsOk

`func (o *RedditResponse) GetCitationsOk() (*int32, bool)`

GetCitationsOk returns a tuple with the Citations field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCitations

`func (o *RedditResponse) SetCitations(v int32)`

SetCitations sets Citations field to given value.

### HasCitations

`func (o *RedditResponse) HasCitations() bool`

HasCitations returns a boolean if a field has been set.

### GetData

`func (o *RedditResponse) GetData() []RedditRow`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *RedditResponse) GetDataOk() (*[]RedditRow, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *RedditResponse) SetData(v []RedditRow)`

SetData sets Data field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


