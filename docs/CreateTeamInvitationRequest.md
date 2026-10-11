# CreateTeamInvitationRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Email** | **string** |  | 
**ProjectIds** | Pointer to **[]int32** | Projects the member can access. Send this or all_projects true. | [optional] 
**AllProjects** | Pointer to **bool** | Access to every project, including future ones | [optional] 
**PermissionRole** | Pointer to **string** | Default full_access. Owner and co-owners only. | [optional] 
**AccountRoleId** | Pointer to **int32** | One of the account&#39;s roles, with permission_role account_role | [optional] 
**Permissions** | Pointer to **map[string][]string** | With permission_role custom: feature key to the verbs granted (read, create, update, delete), for example {\&quot;overview\&quot;: [\&quot;read\&quot;], \&quot;prompts\&quot;: [\&quot;read\&quot;, \&quot;create\&quot;]} | [optional] 
**AccountAdmin** | Pointer to **bool** | Make the member a co-owner. Account owner only. | [optional] 
**BillingAccess** | Pointer to **bool** | Access to Billing and Plans. Account owner only. | [optional] 

## Methods

### NewCreateTeamInvitationRequest

`func NewCreateTeamInvitationRequest(email string, ) *CreateTeamInvitationRequest`

NewCreateTeamInvitationRequest instantiates a new CreateTeamInvitationRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateTeamInvitationRequestWithDefaults

`func NewCreateTeamInvitationRequestWithDefaults() *CreateTeamInvitationRequest`

NewCreateTeamInvitationRequestWithDefaults instantiates a new CreateTeamInvitationRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetEmail

`func (o *CreateTeamInvitationRequest) GetEmail() string`

GetEmail returns the Email field if non-nil, zero value otherwise.

### GetEmailOk

`func (o *CreateTeamInvitationRequest) GetEmailOk() (*string, bool)`

GetEmailOk returns a tuple with the Email field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmail

`func (o *CreateTeamInvitationRequest) SetEmail(v string)`

SetEmail sets Email field to given value.


### GetProjectIds

`func (o *CreateTeamInvitationRequest) GetProjectIds() []int32`

GetProjectIds returns the ProjectIds field if non-nil, zero value otherwise.

### GetProjectIdsOk

`func (o *CreateTeamInvitationRequest) GetProjectIdsOk() (*[]int32, bool)`

GetProjectIdsOk returns a tuple with the ProjectIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectIds

`func (o *CreateTeamInvitationRequest) SetProjectIds(v []int32)`

SetProjectIds sets ProjectIds field to given value.

### HasProjectIds

`func (o *CreateTeamInvitationRequest) HasProjectIds() bool`

HasProjectIds returns a boolean if a field has been set.

### GetAllProjects

`func (o *CreateTeamInvitationRequest) GetAllProjects() bool`

GetAllProjects returns the AllProjects field if non-nil, zero value otherwise.

### GetAllProjectsOk

`func (o *CreateTeamInvitationRequest) GetAllProjectsOk() (*bool, bool)`

GetAllProjectsOk returns a tuple with the AllProjects field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAllProjects

`func (o *CreateTeamInvitationRequest) SetAllProjects(v bool)`

SetAllProjects sets AllProjects field to given value.

### HasAllProjects

`func (o *CreateTeamInvitationRequest) HasAllProjects() bool`

HasAllProjects returns a boolean if a field has been set.

### GetPermissionRole

`func (o *CreateTeamInvitationRequest) GetPermissionRole() string`

GetPermissionRole returns the PermissionRole field if non-nil, zero value otherwise.

### GetPermissionRoleOk

`func (o *CreateTeamInvitationRequest) GetPermissionRoleOk() (*string, bool)`

GetPermissionRoleOk returns a tuple with the PermissionRole field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPermissionRole

`func (o *CreateTeamInvitationRequest) SetPermissionRole(v string)`

SetPermissionRole sets PermissionRole field to given value.

### HasPermissionRole

`func (o *CreateTeamInvitationRequest) HasPermissionRole() bool`

HasPermissionRole returns a boolean if a field has been set.

### GetAccountRoleId

`func (o *CreateTeamInvitationRequest) GetAccountRoleId() int32`

GetAccountRoleId returns the AccountRoleId field if non-nil, zero value otherwise.

### GetAccountRoleIdOk

`func (o *CreateTeamInvitationRequest) GetAccountRoleIdOk() (*int32, bool)`

GetAccountRoleIdOk returns a tuple with the AccountRoleId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountRoleId

`func (o *CreateTeamInvitationRequest) SetAccountRoleId(v int32)`

SetAccountRoleId sets AccountRoleId field to given value.

### HasAccountRoleId

`func (o *CreateTeamInvitationRequest) HasAccountRoleId() bool`

HasAccountRoleId returns a boolean if a field has been set.

### GetPermissions

`func (o *CreateTeamInvitationRequest) GetPermissions() map[string][]string`

GetPermissions returns the Permissions field if non-nil, zero value otherwise.

### GetPermissionsOk

`func (o *CreateTeamInvitationRequest) GetPermissionsOk() (*map[string][]string, bool)`

GetPermissionsOk returns a tuple with the Permissions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPermissions

`func (o *CreateTeamInvitationRequest) SetPermissions(v map[string][]string)`

SetPermissions sets Permissions field to given value.

### HasPermissions

`func (o *CreateTeamInvitationRequest) HasPermissions() bool`

HasPermissions returns a boolean if a field has been set.

### GetAccountAdmin

`func (o *CreateTeamInvitationRequest) GetAccountAdmin() bool`

GetAccountAdmin returns the AccountAdmin field if non-nil, zero value otherwise.

### GetAccountAdminOk

`func (o *CreateTeamInvitationRequest) GetAccountAdminOk() (*bool, bool)`

GetAccountAdminOk returns a tuple with the AccountAdmin field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountAdmin

`func (o *CreateTeamInvitationRequest) SetAccountAdmin(v bool)`

SetAccountAdmin sets AccountAdmin field to given value.

### HasAccountAdmin

`func (o *CreateTeamInvitationRequest) HasAccountAdmin() bool`

HasAccountAdmin returns a boolean if a field has been set.

### GetBillingAccess

`func (o *CreateTeamInvitationRequest) GetBillingAccess() bool`

GetBillingAccess returns the BillingAccess field if non-nil, zero value otherwise.

### GetBillingAccessOk

`func (o *CreateTeamInvitationRequest) GetBillingAccessOk() (*bool, bool)`

GetBillingAccessOk returns a tuple with the BillingAccess field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBillingAccess

`func (o *CreateTeamInvitationRequest) SetBillingAccess(v bool)`

SetBillingAccess sets BillingAccess field to given value.

### HasBillingAccess

`func (o *CreateTeamInvitationRequest) HasBillingAccess() bool`

HasBillingAccess returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


