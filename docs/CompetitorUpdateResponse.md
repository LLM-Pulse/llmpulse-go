# CompetitorUpdateResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ProjectId** | **int32** |  | 
**Competitor** | [**CompetitorUpdateResponseCompetitor**](CompetitorUpdateResponseCompetitor.md) |  | 
**RequestId** | **string** |  | 

## Methods

### NewCompetitorUpdateResponse

`func NewCompetitorUpdateResponse(projectId int32, competitor CompetitorUpdateResponseCompetitor, requestId string, ) *CompetitorUpdateResponse`

NewCompetitorUpdateResponse instantiates a new CompetitorUpdateResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCompetitorUpdateResponseWithDefaults

`func NewCompetitorUpdateResponseWithDefaults() *CompetitorUpdateResponse`

NewCompetitorUpdateResponseWithDefaults instantiates a new CompetitorUpdateResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProjectId

`func (o *CompetitorUpdateResponse) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *CompetitorUpdateResponse) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *CompetitorUpdateResponse) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.


### GetCompetitor

`func (o *CompetitorUpdateResponse) GetCompetitor() CompetitorUpdateResponseCompetitor`

GetCompetitor returns the Competitor field if non-nil, zero value otherwise.

### GetCompetitorOk

`func (o *CompetitorUpdateResponse) GetCompetitorOk() (*CompetitorUpdateResponseCompetitor, bool)`

GetCompetitorOk returns a tuple with the Competitor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompetitor

`func (o *CompetitorUpdateResponse) SetCompetitor(v CompetitorUpdateResponseCompetitor)`

SetCompetitor sets Competitor field to given value.


### GetRequestId

`func (o *CompetitorUpdateResponse) GetRequestId() string`

GetRequestId returns the RequestId field if non-nil, zero value otherwise.

### GetRequestIdOk

`func (o *CompetitorUpdateResponse) GetRequestIdOk() (*string, bool)`

GetRequestIdOk returns a tuple with the RequestId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestId

`func (o *CompetitorUpdateResponse) SetRequestId(v string)`

SetRequestId sets RequestId field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


