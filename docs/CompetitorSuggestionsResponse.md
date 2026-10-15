# CompetitorSuggestionsResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ProjectId** | **int32** |  | 
**Page** | **int32** |  | 
**PerPage** | **int32** |  | 
**Total** | **int32** | Rows matching the filters across every page | 
**RequestId** | **string** |  | 
**Basis** | **string** |  | 
**Discovery** | [**CompetitorDiscoveryState**](CompetitorDiscoveryState.md) |  | 
**Data** | [**[]CompetitorSuggestion**](CompetitorSuggestion.md) |  | 

## Methods

### NewCompetitorSuggestionsResponse

`func NewCompetitorSuggestionsResponse(projectId int32, page int32, perPage int32, total int32, requestId string, basis string, discovery CompetitorDiscoveryState, data []CompetitorSuggestion, ) *CompetitorSuggestionsResponse`

NewCompetitorSuggestionsResponse instantiates a new CompetitorSuggestionsResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCompetitorSuggestionsResponseWithDefaults

`func NewCompetitorSuggestionsResponseWithDefaults() *CompetitorSuggestionsResponse`

NewCompetitorSuggestionsResponseWithDefaults instantiates a new CompetitorSuggestionsResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProjectId

`func (o *CompetitorSuggestionsResponse) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *CompetitorSuggestionsResponse) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *CompetitorSuggestionsResponse) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.


### GetPage

`func (o *CompetitorSuggestionsResponse) GetPage() int32`

GetPage returns the Page field if non-nil, zero value otherwise.

### GetPageOk

`func (o *CompetitorSuggestionsResponse) GetPageOk() (*int32, bool)`

GetPageOk returns a tuple with the Page field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPage

`func (o *CompetitorSuggestionsResponse) SetPage(v int32)`

SetPage sets Page field to given value.


### GetPerPage

`func (o *CompetitorSuggestionsResponse) GetPerPage() int32`

GetPerPage returns the PerPage field if non-nil, zero value otherwise.

### GetPerPageOk

`func (o *CompetitorSuggestionsResponse) GetPerPageOk() (*int32, bool)`

GetPerPageOk returns a tuple with the PerPage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPerPage

`func (o *CompetitorSuggestionsResponse) SetPerPage(v int32)`

SetPerPage sets PerPage field to given value.


### GetTotal

`func (o *CompetitorSuggestionsResponse) GetTotal() int32`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *CompetitorSuggestionsResponse) GetTotalOk() (*int32, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *CompetitorSuggestionsResponse) SetTotal(v int32)`

SetTotal sets Total field to given value.


### GetRequestId

`func (o *CompetitorSuggestionsResponse) GetRequestId() string`

GetRequestId returns the RequestId field if non-nil, zero value otherwise.

### GetRequestIdOk

`func (o *CompetitorSuggestionsResponse) GetRequestIdOk() (*string, bool)`

GetRequestIdOk returns a tuple with the RequestId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestId

`func (o *CompetitorSuggestionsResponse) SetRequestId(v string)`

SetRequestId sets RequestId field to given value.


### GetBasis

`func (o *CompetitorSuggestionsResponse) GetBasis() string`

GetBasis returns the Basis field if non-nil, zero value otherwise.

### GetBasisOk

`func (o *CompetitorSuggestionsResponse) GetBasisOk() (*string, bool)`

GetBasisOk returns a tuple with the Basis field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBasis

`func (o *CompetitorSuggestionsResponse) SetBasis(v string)`

SetBasis sets Basis field to given value.


### GetDiscovery

`func (o *CompetitorSuggestionsResponse) GetDiscovery() CompetitorDiscoveryState`

GetDiscovery returns the Discovery field if non-nil, zero value otherwise.

### GetDiscoveryOk

`func (o *CompetitorSuggestionsResponse) GetDiscoveryOk() (*CompetitorDiscoveryState, bool)`

GetDiscoveryOk returns a tuple with the Discovery field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDiscovery

`func (o *CompetitorSuggestionsResponse) SetDiscovery(v CompetitorDiscoveryState)`

SetDiscovery sets Discovery field to given value.


### GetData

`func (o *CompetitorSuggestionsResponse) GetData() []CompetitorSuggestion`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *CompetitorSuggestionsResponse) GetDataOk() (*[]CompetitorSuggestion, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *CompetitorSuggestionsResponse) SetData(v []CompetitorSuggestion)`

SetData sets Data field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


