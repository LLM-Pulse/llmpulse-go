# TeamMember

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **int32** |  | 
**Email** | **string** |  | 
**Name** | Pointer to **NullableString** |  | [optional] 
**Role** | **string** | The account owner is listed first; everyone else who joined is a member. | 
**Status** | **string** | A blocked member cannot sign in or use the API until unblocked in the app. | 
**PermissionRole** | **NullableString** | Access level of a member: full_access, view_only, custom or account_role. Null for the owner. | 
**AccountRole** | [**NullableTeamAccountRole**](TeamAccountRole.md) |  | 
**Permissions** | **map[string][]string** | What the person can do, feature key to the verbs granted (read, create, update, delete), resolved from their role. Null for the account owner, who can do everything. | 
**AccountAdmin** | **bool** | A co-owner, who can manage the team. | 
**BillingAccess** | **bool** | Can open Billing and Plans (always true for the owner). | 
**AllProjects** | **bool** | Has access to every project of the account, including future ones. | 
**ProjectIds** | **[]int32** | The projects a member is limited to; empty when all_projects is true. | 
**LastSignInAt** | Pointer to **NullableTime** |  | [optional] 
**JoinedAt** | Pointer to **NullableTime** | When the member accepted the invitation; null for the owner and for members added without one. | [optional] 
**CreatedAt** | Pointer to **time.Time** |  | [optional] 

## Methods

### NewTeamMember

`func NewTeamMember(id int32, email string, role string, status string, permissionRole NullableString, accountRole NullableTeamAccountRole, permissions map[string][]string, accountAdmin bool, billingAccess bool, allProjects bool, projectIds []int32, ) *TeamMember`

NewTeamMember instantiates a new TeamMember object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTeamMemberWithDefaults

`func NewTeamMemberWithDefaults() *TeamMember`

NewTeamMemberWithDefaults instantiates a new TeamMember object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *TeamMember) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *TeamMember) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *TeamMember) SetId(v int32)`

SetId sets Id field to given value.


### GetEmail

`func (o *TeamMember) GetEmail() string`

GetEmail returns the Email field if non-nil, zero value otherwise.

### GetEmailOk

`func (o *TeamMember) GetEmailOk() (*string, bool)`

GetEmailOk returns a tuple with the Email field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmail

`func (o *TeamMember) SetEmail(v string)`

SetEmail sets Email field to given value.


### GetName

`func (o *TeamMember) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *TeamMember) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *TeamMember) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *TeamMember) HasName() bool`

HasName returns a boolean if a field has been set.

### SetNameNil

`func (o *TeamMember) SetNameNil(b bool)`

 SetNameNil sets the value for Name to be an explicit nil

### UnsetName
`func (o *TeamMember) UnsetName()`

UnsetName ensures that no value is present for Name, not even an explicit nil
### GetRole

`func (o *TeamMember) GetRole() string`

GetRole returns the Role field if non-nil, zero value otherwise.

### GetRoleOk

`func (o *TeamMember) GetRoleOk() (*string, bool)`

GetRoleOk returns a tuple with the Role field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRole

`func (o *TeamMember) SetRole(v string)`

SetRole sets Role field to given value.


### GetStatus

`func (o *TeamMember) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *TeamMember) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *TeamMember) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetPermissionRole

`func (o *TeamMember) GetPermissionRole() string`

GetPermissionRole returns the PermissionRole field if non-nil, zero value otherwise.

### GetPermissionRoleOk

`func (o *TeamMember) GetPermissionRoleOk() (*string, bool)`

GetPermissionRoleOk returns a tuple with the PermissionRole field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPermissionRole

`func (o *TeamMember) SetPermissionRole(v string)`

SetPermissionRole sets PermissionRole field to given value.


### SetPermissionRoleNil

`func (o *TeamMember) SetPermissionRoleNil(b bool)`

 SetPermissionRoleNil sets the value for PermissionRole to be an explicit nil

### UnsetPermissionRole
`func (o *TeamMember) UnsetPermissionRole()`

UnsetPermissionRole ensures that no value is present for PermissionRole, not even an explicit nil
### GetAccountRole

`func (o *TeamMember) GetAccountRole() TeamAccountRole`

GetAccountRole returns the AccountRole field if non-nil, zero value otherwise.

### GetAccountRoleOk

`func (o *TeamMember) GetAccountRoleOk() (*TeamAccountRole, bool)`

GetAccountRoleOk returns a tuple with the AccountRole field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountRole

`func (o *TeamMember) SetAccountRole(v TeamAccountRole)`

SetAccountRole sets AccountRole field to given value.


### SetAccountRoleNil

`func (o *TeamMember) SetAccountRoleNil(b bool)`

 SetAccountRoleNil sets the value for AccountRole to be an explicit nil

### UnsetAccountRole
`func (o *TeamMember) UnsetAccountRole()`

UnsetAccountRole ensures that no value is present for AccountRole, not even an explicit nil
### GetPermissions

`func (o *TeamMember) GetPermissions() map[string][]string`

GetPermissions returns the Permissions field if non-nil, zero value otherwise.

### GetPermissionsOk

`func (o *TeamMember) GetPermissionsOk() (*map[string][]string, bool)`

GetPermissionsOk returns a tuple with the Permissions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPermissions

`func (o *TeamMember) SetPermissions(v map[string][]string)`

SetPermissions sets Permissions field to given value.


### SetPermissionsNil

`func (o *TeamMember) SetPermissionsNil(b bool)`

 SetPermissionsNil sets the value for Permissions to be an explicit nil

### UnsetPermissions
`func (o *TeamMember) UnsetPermissions()`

UnsetPermissions ensures that no value is present for Permissions, not even an explicit nil
### GetAccountAdmin

`func (o *TeamMember) GetAccountAdmin() bool`

GetAccountAdmin returns the AccountAdmin field if non-nil, zero value otherwise.

### GetAccountAdminOk

`func (o *TeamMember) GetAccountAdminOk() (*bool, bool)`

GetAccountAdminOk returns a tuple with the AccountAdmin field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountAdmin

`func (o *TeamMember) SetAccountAdmin(v bool)`

SetAccountAdmin sets AccountAdmin field to given value.


### GetBillingAccess

`func (o *TeamMember) GetBillingAccess() bool`

GetBillingAccess returns the BillingAccess field if non-nil, zero value otherwise.

### GetBillingAccessOk

`func (o *TeamMember) GetBillingAccessOk() (*bool, bool)`

GetBillingAccessOk returns a tuple with the BillingAccess field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBillingAccess

`func (o *TeamMember) SetBillingAccess(v bool)`

SetBillingAccess sets BillingAccess field to given value.


### GetAllProjects

`func (o *TeamMember) GetAllProjects() bool`

GetAllProjects returns the AllProjects field if non-nil, zero value otherwise.

### GetAllProjectsOk

`func (o *TeamMember) GetAllProjectsOk() (*bool, bool)`

GetAllProjectsOk returns a tuple with the AllProjects field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAllProjects

`func (o *TeamMember) SetAllProjects(v bool)`

SetAllProjects sets AllProjects field to given value.


### GetProjectIds

`func (o *TeamMember) GetProjectIds() []int32`

GetProjectIds returns the ProjectIds field if non-nil, zero value otherwise.

### GetProjectIdsOk

`func (o *TeamMember) GetProjectIdsOk() (*[]int32, bool)`

GetProjectIdsOk returns a tuple with the ProjectIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectIds

`func (o *TeamMember) SetProjectIds(v []int32)`

SetProjectIds sets ProjectIds field to given value.


### GetLastSignInAt

`func (o *TeamMember) GetLastSignInAt() time.Time`

GetLastSignInAt returns the LastSignInAt field if non-nil, zero value otherwise.

### GetLastSignInAtOk

`func (o *TeamMember) GetLastSignInAtOk() (*time.Time, bool)`

GetLastSignInAtOk returns a tuple with the LastSignInAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastSignInAt

`func (o *TeamMember) SetLastSignInAt(v time.Time)`

SetLastSignInAt sets LastSignInAt field to given value.

### HasLastSignInAt

`func (o *TeamMember) HasLastSignInAt() bool`

HasLastSignInAt returns a boolean if a field has been set.

### SetLastSignInAtNil

`func (o *TeamMember) SetLastSignInAtNil(b bool)`

 SetLastSignInAtNil sets the value for LastSignInAt to be an explicit nil

### UnsetLastSignInAt
`func (o *TeamMember) UnsetLastSignInAt()`

UnsetLastSignInAt ensures that no value is present for LastSignInAt, not even an explicit nil
### GetJoinedAt

`func (o *TeamMember) GetJoinedAt() time.Time`

GetJoinedAt returns the JoinedAt field if non-nil, zero value otherwise.

### GetJoinedAtOk

`func (o *TeamMember) GetJoinedAtOk() (*time.Time, bool)`

GetJoinedAtOk returns a tuple with the JoinedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJoinedAt

`func (o *TeamMember) SetJoinedAt(v time.Time)`

SetJoinedAt sets JoinedAt field to given value.

### HasJoinedAt

`func (o *TeamMember) HasJoinedAt() bool`

HasJoinedAt returns a boolean if a field has been set.

### SetJoinedAtNil

`func (o *TeamMember) SetJoinedAtNil(b bool)`

 SetJoinedAtNil sets the value for JoinedAt to be an explicit nil

### UnsetJoinedAt
`func (o *TeamMember) UnsetJoinedAt()`

UnsetJoinedAt ensures that no value is present for JoinedAt, not even an explicit nil
### GetCreatedAt

`func (o *TeamMember) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *TeamMember) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *TeamMember) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *TeamMember) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


