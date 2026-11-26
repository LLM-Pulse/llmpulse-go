# CitationGroupsResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ProjectId** | **int32** |  | 
**Page** | **int32** |  | 
**PerPage** | **int32** |  | 
**Total** | **int32** | Rows matching the filters across every page | 
**RequestId** | **string** |  | 
**View** | **string** | url, domain or host | 
**Filters** | [**CitationIntelligenceFiltersEcho**](CitationIntelligenceFiltersEcho.md) |  | 
**Data** | [**[]CitationGroupRow**](CitationGroupRow.md) |  | 

## Methods

### NewCitationGroupsResponse

`func NewCitationGroupsResponse(projectId int32, page int32, perPage int32, total int32, requestId string, view string, filters CitationIntelligenceFiltersEcho, data []CitationGroupRow, ) *CitationGroupsResponse`

NewCitationGroupsResponse instantiates a new CitationGroupsResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCitationGroupsResponseWithDefaults

`func NewCitationGroupsResponseWithDefaults() *CitationGroupsResponse`

NewCitationGroupsResponseWithDefaults instantiates a new CitationGroupsResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProjectId

`func (o *CitationGroupsResponse) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *CitationGroupsResponse) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *CitationGroupsResponse) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.


### GetPage

`func (o *CitationGroupsResponse) GetPage() int32`

GetPage returns the Page field if non-nil, zero value otherwise.

### GetPageOk

`func (o *CitationGroupsResponse) GetPageOk() (*int32, bool)`

GetPageOk returns a tuple with the Page field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPage

`func (o *CitationGroupsResponse) SetPage(v int32)`

SetPage sets Page field to given value.


### GetPerPage

`func (o *CitationGroupsResponse) GetPerPage() int32`

GetPerPage returns the PerPage field if non-nil, zero value otherwise.

### GetPerPageOk

`func (o *CitationGroupsResponse) GetPerPageOk() (*int32, bool)`

GetPerPageOk returns a tuple with the PerPage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPerPage

`func (o *CitationGroupsResponse) SetPerPage(v int32)`

SetPerPage sets PerPage field to given value.


### GetTotal

`func (o *CitationGroupsResponse) GetTotal() int32`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *CitationGroupsResponse) GetTotalOk() (*int32, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *CitationGroupsResponse) SetTotal(v int32)`

SetTotal sets Total field to given value.


### GetRequestId

`func (o *CitationGroupsResponse) GetRequestId() string`

GetRequestId returns the RequestId field if non-nil, zero value otherwise.

### GetRequestIdOk

`func (o *CitationGroupsResponse) GetRequestIdOk() (*string, bool)`

GetRequestIdOk returns a tuple with the RequestId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestId

`func (o *CitationGroupsResponse) SetRequestId(v string)`

SetRequestId sets RequestId field to given value.


### GetView

`func (o *CitationGroupsResponse) GetView() string`

GetView returns the View field if non-nil, zero value otherwise.

### GetViewOk

`func (o *CitationGroupsResponse) GetViewOk() (*string, bool)`

GetViewOk returns a tuple with the View field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetView

`func (o *CitationGroupsResponse) SetView(v string)`

SetView sets View field to given value.


### GetFilters

`func (o *CitationGroupsResponse) GetFilters() CitationIntelligenceFiltersEcho`

GetFilters returns the Filters field if non-nil, zero value otherwise.

### GetFiltersOk

`func (o *CitationGroupsResponse) GetFiltersOk() (*CitationIntelligenceFiltersEcho, bool)`

GetFiltersOk returns a tuple with the Filters field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFilters

`func (o *CitationGroupsResponse) SetFilters(v CitationIntelligenceFiltersEcho)`

SetFilters sets Filters field to given value.


### GetData

`func (o *CitationGroupsResponse) GetData() []CitationGroupRow`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *CitationGroupsResponse) GetDataOk() (*[]CitationGroupRow, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *CitationGroupsResponse) SetData(v []CitationGroupRow)`

SetData sets Data field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


