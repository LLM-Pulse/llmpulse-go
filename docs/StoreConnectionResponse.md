# StoreConnectionResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Platform** | **string** | The store platform, e.g. shopify | 
**Domain** | **string** | The store domain as compared: lowercase, without scheme, www or path | 
**Project** | [**NullableStoreConnectionResponseProject**](StoreConnectionResponseProject.md) |  | 
**Ambiguous** | **bool** | True when several live projects match the store domain (for example one project per market). project is then null and the app asks the key holder to pick from candidates. | 
**Candidates** | [**[]StoreConnectionResponseCandidatesInner**](StoreConnectionResponseCandidatesInner.md) | Every live project of the account, for a project picker | 
**Account** | [**StoreConnectionResponseAccount**](StoreConnectionResponseAccount.md) |  | 
**RequestId** | **string** |  | 

## Methods

### NewStoreConnectionResponse

`func NewStoreConnectionResponse(platform string, domain string, project NullableStoreConnectionResponseProject, ambiguous bool, candidates []StoreConnectionResponseCandidatesInner, account StoreConnectionResponseAccount, requestId string, ) *StoreConnectionResponse`

NewStoreConnectionResponse instantiates a new StoreConnectionResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewStoreConnectionResponseWithDefaults

`func NewStoreConnectionResponseWithDefaults() *StoreConnectionResponse`

NewStoreConnectionResponseWithDefaults instantiates a new StoreConnectionResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPlatform

`func (o *StoreConnectionResponse) GetPlatform() string`

GetPlatform returns the Platform field if non-nil, zero value otherwise.

### GetPlatformOk

`func (o *StoreConnectionResponse) GetPlatformOk() (*string, bool)`

GetPlatformOk returns a tuple with the Platform field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlatform

`func (o *StoreConnectionResponse) SetPlatform(v string)`

SetPlatform sets Platform field to given value.


### GetDomain

`func (o *StoreConnectionResponse) GetDomain() string`

GetDomain returns the Domain field if non-nil, zero value otherwise.

### GetDomainOk

`func (o *StoreConnectionResponse) GetDomainOk() (*string, bool)`

GetDomainOk returns a tuple with the Domain field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDomain

`func (o *StoreConnectionResponse) SetDomain(v string)`

SetDomain sets Domain field to given value.


### GetProject

`func (o *StoreConnectionResponse) GetProject() StoreConnectionResponseProject`

GetProject returns the Project field if non-nil, zero value otherwise.

### GetProjectOk

`func (o *StoreConnectionResponse) GetProjectOk() (*StoreConnectionResponseProject, bool)`

GetProjectOk returns a tuple with the Project field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProject

`func (o *StoreConnectionResponse) SetProject(v StoreConnectionResponseProject)`

SetProject sets Project field to given value.


### SetProjectNil

`func (o *StoreConnectionResponse) SetProjectNil(b bool)`

 SetProjectNil sets the value for Project to be an explicit nil

### UnsetProject
`func (o *StoreConnectionResponse) UnsetProject()`

UnsetProject ensures that no value is present for Project, not even an explicit nil
### GetAmbiguous

`func (o *StoreConnectionResponse) GetAmbiguous() bool`

GetAmbiguous returns the Ambiguous field if non-nil, zero value otherwise.

### GetAmbiguousOk

`func (o *StoreConnectionResponse) GetAmbiguousOk() (*bool, bool)`

GetAmbiguousOk returns a tuple with the Ambiguous field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAmbiguous

`func (o *StoreConnectionResponse) SetAmbiguous(v bool)`

SetAmbiguous sets Ambiguous field to given value.


### GetCandidates

`func (o *StoreConnectionResponse) GetCandidates() []StoreConnectionResponseCandidatesInner`

GetCandidates returns the Candidates field if non-nil, zero value otherwise.

### GetCandidatesOk

`func (o *StoreConnectionResponse) GetCandidatesOk() (*[]StoreConnectionResponseCandidatesInner, bool)`

GetCandidatesOk returns a tuple with the Candidates field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCandidates

`func (o *StoreConnectionResponse) SetCandidates(v []StoreConnectionResponseCandidatesInner)`

SetCandidates sets Candidates field to given value.


### GetAccount

`func (o *StoreConnectionResponse) GetAccount() StoreConnectionResponseAccount`

GetAccount returns the Account field if non-nil, zero value otherwise.

### GetAccountOk

`func (o *StoreConnectionResponse) GetAccountOk() (*StoreConnectionResponseAccount, bool)`

GetAccountOk returns a tuple with the Account field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccount

`func (o *StoreConnectionResponse) SetAccount(v StoreConnectionResponseAccount)`

SetAccount sets Account field to given value.


### GetRequestId

`func (o *StoreConnectionResponse) GetRequestId() string`

GetRequestId returns the RequestId field if non-nil, zero value otherwise.

### GetRequestIdOk

`func (o *StoreConnectionResponse) GetRequestIdOk() (*string, bool)`

GetRequestIdOk returns a tuple with the RequestId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestId

`func (o *StoreConnectionResponse) SetRequestId(v string)`

SetRequestId sets RequestId field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


