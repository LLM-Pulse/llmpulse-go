# CompetitorCreateResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ProjectId** | **int32** |  | 
**Competitor** | [**CompetitorCreateResponseCompetitor**](CompetitorCreateResponseCompetitor.md) |  | 
**CompetitorsRemaining** | **NullableInt32** | Competitors the plan still allows in this project; null when unlimited | 
**TotalCompetitors** | **int32** |  | 
**RequestId** | **string** |  | 

## Methods

### NewCompetitorCreateResponse

`func NewCompetitorCreateResponse(projectId int32, competitor CompetitorCreateResponseCompetitor, competitorsRemaining NullableInt32, totalCompetitors int32, requestId string, ) *CompetitorCreateResponse`

NewCompetitorCreateResponse instantiates a new CompetitorCreateResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCompetitorCreateResponseWithDefaults

`func NewCompetitorCreateResponseWithDefaults() *CompetitorCreateResponse`

NewCompetitorCreateResponseWithDefaults instantiates a new CompetitorCreateResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProjectId

`func (o *CompetitorCreateResponse) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *CompetitorCreateResponse) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *CompetitorCreateResponse) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.


### GetCompetitor

`func (o *CompetitorCreateResponse) GetCompetitor() CompetitorCreateResponseCompetitor`

GetCompetitor returns the Competitor field if non-nil, zero value otherwise.

### GetCompetitorOk

`func (o *CompetitorCreateResponse) GetCompetitorOk() (*CompetitorCreateResponseCompetitor, bool)`

GetCompetitorOk returns a tuple with the Competitor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompetitor

`func (o *CompetitorCreateResponse) SetCompetitor(v CompetitorCreateResponseCompetitor)`

SetCompetitor sets Competitor field to given value.


### GetCompetitorsRemaining

`func (o *CompetitorCreateResponse) GetCompetitorsRemaining() int32`

GetCompetitorsRemaining returns the CompetitorsRemaining field if non-nil, zero value otherwise.

### GetCompetitorsRemainingOk

`func (o *CompetitorCreateResponse) GetCompetitorsRemainingOk() (*int32, bool)`

GetCompetitorsRemainingOk returns a tuple with the CompetitorsRemaining field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompetitorsRemaining

`func (o *CompetitorCreateResponse) SetCompetitorsRemaining(v int32)`

SetCompetitorsRemaining sets CompetitorsRemaining field to given value.


### SetCompetitorsRemainingNil

`func (o *CompetitorCreateResponse) SetCompetitorsRemainingNil(b bool)`

 SetCompetitorsRemainingNil sets the value for CompetitorsRemaining to be an explicit nil

### UnsetCompetitorsRemaining
`func (o *CompetitorCreateResponse) UnsetCompetitorsRemaining()`

UnsetCompetitorsRemaining ensures that no value is present for CompetitorsRemaining, not even an explicit nil
### GetTotalCompetitors

`func (o *CompetitorCreateResponse) GetTotalCompetitors() int32`

GetTotalCompetitors returns the TotalCompetitors field if non-nil, zero value otherwise.

### GetTotalCompetitorsOk

`func (o *CompetitorCreateResponse) GetTotalCompetitorsOk() (*int32, bool)`

GetTotalCompetitorsOk returns a tuple with the TotalCompetitors field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalCompetitors

`func (o *CompetitorCreateResponse) SetTotalCompetitors(v int32)`

SetTotalCompetitors sets TotalCompetitors field to given value.


### GetRequestId

`func (o *CompetitorCreateResponse) GetRequestId() string`

GetRequestId returns the RequestId field if non-nil, zero value otherwise.

### GetRequestIdOk

`func (o *CompetitorCreateResponse) GetRequestIdOk() (*string, bool)`

GetRequestIdOk returns a tuple with the RequestId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestId

`func (o *CompetitorCreateResponse) SetRequestId(v string)`

SetRequestId sets RequestId field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


