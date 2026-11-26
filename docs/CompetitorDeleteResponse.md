# CompetitorDeleteResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ProjectId** | **int32** |  | 
**Deleted** | **bool** | Always true | 
**Id** | **int32** |  | 
**BrandName** | **string** |  | 
**Domain** | **string** |  | 
**TotalCompetitors** | **int32** | Competitors left in the project | 
**RequestId** | **string** |  | 

## Methods

### NewCompetitorDeleteResponse

`func NewCompetitorDeleteResponse(projectId int32, deleted bool, id int32, brandName string, domain string, totalCompetitors int32, requestId string, ) *CompetitorDeleteResponse`

NewCompetitorDeleteResponse instantiates a new CompetitorDeleteResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCompetitorDeleteResponseWithDefaults

`func NewCompetitorDeleteResponseWithDefaults() *CompetitorDeleteResponse`

NewCompetitorDeleteResponseWithDefaults instantiates a new CompetitorDeleteResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProjectId

`func (o *CompetitorDeleteResponse) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *CompetitorDeleteResponse) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *CompetitorDeleteResponse) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.


### GetDeleted

`func (o *CompetitorDeleteResponse) GetDeleted() bool`

GetDeleted returns the Deleted field if non-nil, zero value otherwise.

### GetDeletedOk

`func (o *CompetitorDeleteResponse) GetDeletedOk() (*bool, bool)`

GetDeletedOk returns a tuple with the Deleted field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeleted

`func (o *CompetitorDeleteResponse) SetDeleted(v bool)`

SetDeleted sets Deleted field to given value.


### GetId

`func (o *CompetitorDeleteResponse) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *CompetitorDeleteResponse) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *CompetitorDeleteResponse) SetId(v int32)`

SetId sets Id field to given value.


### GetBrandName

`func (o *CompetitorDeleteResponse) GetBrandName() string`

GetBrandName returns the BrandName field if non-nil, zero value otherwise.

### GetBrandNameOk

`func (o *CompetitorDeleteResponse) GetBrandNameOk() (*string, bool)`

GetBrandNameOk returns a tuple with the BrandName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBrandName

`func (o *CompetitorDeleteResponse) SetBrandName(v string)`

SetBrandName sets BrandName field to given value.


### GetDomain

`func (o *CompetitorDeleteResponse) GetDomain() string`

GetDomain returns the Domain field if non-nil, zero value otherwise.

### GetDomainOk

`func (o *CompetitorDeleteResponse) GetDomainOk() (*string, bool)`

GetDomainOk returns a tuple with the Domain field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDomain

`func (o *CompetitorDeleteResponse) SetDomain(v string)`

SetDomain sets Domain field to given value.


### GetTotalCompetitors

`func (o *CompetitorDeleteResponse) GetTotalCompetitors() int32`

GetTotalCompetitors returns the TotalCompetitors field if non-nil, zero value otherwise.

### GetTotalCompetitorsOk

`func (o *CompetitorDeleteResponse) GetTotalCompetitorsOk() (*int32, bool)`

GetTotalCompetitorsOk returns a tuple with the TotalCompetitors field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalCompetitors

`func (o *CompetitorDeleteResponse) SetTotalCompetitors(v int32)`

SetTotalCompetitors sets TotalCompetitors field to given value.


### GetRequestId

`func (o *CompetitorDeleteResponse) GetRequestId() string`

GetRequestId returns the RequestId field if non-nil, zero value otherwise.

### GetRequestIdOk

`func (o *CompetitorDeleteResponse) GetRequestIdOk() (*string, bool)`

GetRequestIdOk returns a tuple with the RequestId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestId

`func (o *CompetitorDeleteResponse) SetRequestId(v string)`

SetRequestId sets RequestId field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


