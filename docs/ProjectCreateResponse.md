# ProjectCreateResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Project** | Pointer to **map[string]interface{}** | Same shape as GET /dimensions/projects/{id} | [optional] 
**Prompts** | Pointer to [**ProjectCreateResponsePrompts**](ProjectCreateResponsePrompts.md) |  | [optional] 
**Competitors** | Pointer to [**ProjectCreateResponseCompetitors**](ProjectCreateResponseCompetitors.md) |  | [optional] 
**Collections** | Pointer to [**[]ProjectCreateResponseCollectionsInner**](ProjectCreateResponseCollectionsInner.md) | Collections created from the request&#39;s collections field (empty when none were sent; absent on an idempotent replay) | [optional] 
**SameDomainProjects** | Pointer to [**[]ProjectCreateResponseSameDomainProjectsInner**](ProjectCreateResponseSameDomainProjectsInner.md) | Projects the caller can already see on the same domain (absent on an idempotent replay). Informational only: the create is never blocked, since one domain tracked per market is a normal setup. | [optional] 
**EmailSubscription** | Pointer to [**ProjectCreateResponseEmailSubscription**](ProjectCreateResponseEmailSubscription.md) |  | [optional] 
**Limits** | Pointer to [**ProjectCreateResponseLimits**](ProjectCreateResponseLimits.md) |  | [optional] 
**Idempotent** | Pointer to **bool** | Present and true only on external_identifier replays | [optional] 
**RequestId** | Pointer to **string** |  | [optional] 

## Methods

### NewProjectCreateResponse

`func NewProjectCreateResponse() *ProjectCreateResponse`

NewProjectCreateResponse instantiates a new ProjectCreateResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProjectCreateResponseWithDefaults

`func NewProjectCreateResponseWithDefaults() *ProjectCreateResponse`

NewProjectCreateResponseWithDefaults instantiates a new ProjectCreateResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProject

`func (o *ProjectCreateResponse) GetProject() map[string]interface{}`

GetProject returns the Project field if non-nil, zero value otherwise.

### GetProjectOk

`func (o *ProjectCreateResponse) GetProjectOk() (*map[string]interface{}, bool)`

GetProjectOk returns a tuple with the Project field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProject

`func (o *ProjectCreateResponse) SetProject(v map[string]interface{})`

SetProject sets Project field to given value.

### HasProject

`func (o *ProjectCreateResponse) HasProject() bool`

HasProject returns a boolean if a field has been set.

### GetPrompts

`func (o *ProjectCreateResponse) GetPrompts() ProjectCreateResponsePrompts`

GetPrompts returns the Prompts field if non-nil, zero value otherwise.

### GetPromptsOk

`func (o *ProjectCreateResponse) GetPromptsOk() (*ProjectCreateResponsePrompts, bool)`

GetPromptsOk returns a tuple with the Prompts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrompts

`func (o *ProjectCreateResponse) SetPrompts(v ProjectCreateResponsePrompts)`

SetPrompts sets Prompts field to given value.

### HasPrompts

`func (o *ProjectCreateResponse) HasPrompts() bool`

HasPrompts returns a boolean if a field has been set.

### GetCompetitors

`func (o *ProjectCreateResponse) GetCompetitors() ProjectCreateResponseCompetitors`

GetCompetitors returns the Competitors field if non-nil, zero value otherwise.

### GetCompetitorsOk

`func (o *ProjectCreateResponse) GetCompetitorsOk() (*ProjectCreateResponseCompetitors, bool)`

GetCompetitorsOk returns a tuple with the Competitors field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompetitors

`func (o *ProjectCreateResponse) SetCompetitors(v ProjectCreateResponseCompetitors)`

SetCompetitors sets Competitors field to given value.

### HasCompetitors

`func (o *ProjectCreateResponse) HasCompetitors() bool`

HasCompetitors returns a boolean if a field has been set.

### GetCollections

`func (o *ProjectCreateResponse) GetCollections() []ProjectCreateResponseCollectionsInner`

GetCollections returns the Collections field if non-nil, zero value otherwise.

### GetCollectionsOk

`func (o *ProjectCreateResponse) GetCollectionsOk() (*[]ProjectCreateResponseCollectionsInner, bool)`

GetCollectionsOk returns a tuple with the Collections field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCollections

`func (o *ProjectCreateResponse) SetCollections(v []ProjectCreateResponseCollectionsInner)`

SetCollections sets Collections field to given value.

### HasCollections

`func (o *ProjectCreateResponse) HasCollections() bool`

HasCollections returns a boolean if a field has been set.

### GetSameDomainProjects

`func (o *ProjectCreateResponse) GetSameDomainProjects() []ProjectCreateResponseSameDomainProjectsInner`

GetSameDomainProjects returns the SameDomainProjects field if non-nil, zero value otherwise.

### GetSameDomainProjectsOk

`func (o *ProjectCreateResponse) GetSameDomainProjectsOk() (*[]ProjectCreateResponseSameDomainProjectsInner, bool)`

GetSameDomainProjectsOk returns a tuple with the SameDomainProjects field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSameDomainProjects

`func (o *ProjectCreateResponse) SetSameDomainProjects(v []ProjectCreateResponseSameDomainProjectsInner)`

SetSameDomainProjects sets SameDomainProjects field to given value.

### HasSameDomainProjects

`func (o *ProjectCreateResponse) HasSameDomainProjects() bool`

HasSameDomainProjects returns a boolean if a field has been set.

### GetEmailSubscription

`func (o *ProjectCreateResponse) GetEmailSubscription() ProjectCreateResponseEmailSubscription`

GetEmailSubscription returns the EmailSubscription field if non-nil, zero value otherwise.

### GetEmailSubscriptionOk

`func (o *ProjectCreateResponse) GetEmailSubscriptionOk() (*ProjectCreateResponseEmailSubscription, bool)`

GetEmailSubscriptionOk returns a tuple with the EmailSubscription field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmailSubscription

`func (o *ProjectCreateResponse) SetEmailSubscription(v ProjectCreateResponseEmailSubscription)`

SetEmailSubscription sets EmailSubscription field to given value.

### HasEmailSubscription

`func (o *ProjectCreateResponse) HasEmailSubscription() bool`

HasEmailSubscription returns a boolean if a field has been set.

### GetLimits

`func (o *ProjectCreateResponse) GetLimits() ProjectCreateResponseLimits`

GetLimits returns the Limits field if non-nil, zero value otherwise.

### GetLimitsOk

`func (o *ProjectCreateResponse) GetLimitsOk() (*ProjectCreateResponseLimits, bool)`

GetLimitsOk returns a tuple with the Limits field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLimits

`func (o *ProjectCreateResponse) SetLimits(v ProjectCreateResponseLimits)`

SetLimits sets Limits field to given value.

### HasLimits

`func (o *ProjectCreateResponse) HasLimits() bool`

HasLimits returns a boolean if a field has been set.

### GetIdempotent

`func (o *ProjectCreateResponse) GetIdempotent() bool`

GetIdempotent returns the Idempotent field if non-nil, zero value otherwise.

### GetIdempotentOk

`func (o *ProjectCreateResponse) GetIdempotentOk() (*bool, bool)`

GetIdempotentOk returns a tuple with the Idempotent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdempotent

`func (o *ProjectCreateResponse) SetIdempotent(v bool)`

SetIdempotent sets Idempotent field to given value.

### HasIdempotent

`func (o *ProjectCreateResponse) HasIdempotent() bool`

HasIdempotent returns a boolean if a field has been set.

### GetRequestId

`func (o *ProjectCreateResponse) GetRequestId() string`

GetRequestId returns the RequestId field if non-nil, zero value otherwise.

### GetRequestIdOk

`func (o *ProjectCreateResponse) GetRequestIdOk() (*string, bool)`

GetRequestIdOk returns a tuple with the RequestId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestId

`func (o *ProjectCreateResponse) SetRequestId(v string)`

SetRequestId sets RequestId field to given value.

### HasRequestId

`func (o *ProjectCreateResponse) HasRequestId() bool`

HasRequestId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


