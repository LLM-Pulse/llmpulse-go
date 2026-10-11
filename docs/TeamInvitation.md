# TeamInvitation

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **int32** | Kept by the member once they accept, when they move to GET /team_members. | 
**Email** | **string** |  | 
**PermissionRole** | **string** |  | 
**AccountRole** | [**NullableTeamAccountRole**](TeamAccountRole.md) |  | 
**Permissions** | **map[string][]string** | What the person can do, feature key to the verbs granted (read, create, update, delete), resolved from their role. Null for the account owner, who can do everything. | 
**AccountAdmin** | **bool** |  | 
**BillingAccess** | **bool** |  | 
**AllProjects** | **bool** |  | 
**ProjectIds** | **[]int32** |  | 
**InvitedAt** | Pointer to **NullableTime** | When the invitation email was last sent. | [optional] 
**ExpiresAt** | Pointer to **NullableTime** | When the invitation link stops working. | [optional] 
**CreatedAt** | Pointer to **time.Time** |  | [optional] 

## Methods

### NewTeamInvitation

`func NewTeamInvitation(id int32, email string, permissionRole string, accountRole NullableTeamAccountRole, permissions map[string][]string, accountAdmin bool, billingAccess bool, allProjects bool, projectIds []int32, ) *TeamInvitation`

NewTeamInvitation instantiates a new TeamInvitation object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTeamInvitationWithDefaults

`func NewTeamInvitationWithDefaults() *TeamInvitation`

NewTeamInvitationWithDefaults instantiates a new TeamInvitation object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *TeamInvitation) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *TeamInvitation) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *TeamInvitation) SetId(v int32)`

SetId sets Id field to given value.


### GetEmail

`func (o *TeamInvitation) GetEmail() string`

GetEmail returns the Email field if non-nil, zero value otherwise.

### GetEmailOk

`func (o *TeamInvitation) GetEmailOk() (*string, bool)`

GetEmailOk returns a tuple with the Email field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmail

`func (o *TeamInvitation) SetEmail(v string)`

SetEmail sets Email field to given value.


### GetPermissionRole

`func (o *TeamInvitation) GetPermissionRole() string`

GetPermissionRole returns the PermissionRole field if non-nil, zero value otherwise.

### GetPermissionRoleOk

`func (o *TeamInvitation) GetPermissionRoleOk() (*string, bool)`

GetPermissionRoleOk returns a tuple with the PermissionRole field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPermissionRole

`func (o *TeamInvitation) SetPermissionRole(v string)`

SetPermissionRole sets PermissionRole field to given value.


### GetAccountRole

`func (o *TeamInvitation) GetAccountRole() TeamAccountRole`

GetAccountRole returns the AccountRole field if non-nil, zero value otherwise.

### GetAccountRoleOk

`func (o *TeamInvitation) GetAccountRoleOk() (*TeamAccountRole, bool)`

GetAccountRoleOk returns a tuple with the AccountRole field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountRole

`func (o *TeamInvitation) SetAccountRole(v TeamAccountRole)`

SetAccountRole sets AccountRole field to given value.


### SetAccountRoleNil

`func (o *TeamInvitation) SetAccountRoleNil(b bool)`

 SetAccountRoleNil sets the value for AccountRole to be an explicit nil

### UnsetAccountRole
`func (o *TeamInvitation) UnsetAccountRole()`

UnsetAccountRole ensures that no value is present for AccountRole, not even an explicit nil
### GetPermissions

`func (o *TeamInvitation) GetPermissions() map[string][]string`

GetPermissions returns the Permissions field if non-nil, zero value otherwise.

### GetPermissionsOk

`func (o *TeamInvitation) GetPermissionsOk() (*map[string][]string, bool)`

GetPermissionsOk returns a tuple with the Permissions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPermissions

`func (o *TeamInvitation) SetPermissions(v map[string][]string)`

SetPermissions sets Permissions field to given value.


### SetPermissionsNil

`func (o *TeamInvitation) SetPermissionsNil(b bool)`

 SetPermissionsNil sets the value for Permissions to be an explicit nil

### UnsetPermissions
`func (o *TeamInvitation) UnsetPermissions()`

UnsetPermissions ensures that no value is present for Permissions, not even an explicit nil
### GetAccountAdmin

`func (o *TeamInvitation) GetAccountAdmin() bool`

GetAccountAdmin returns the AccountAdmin field if non-nil, zero value otherwise.

### GetAccountAdminOk

`func (o *TeamInvitation) GetAccountAdminOk() (*bool, bool)`

GetAccountAdminOk returns a tuple with the AccountAdmin field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountAdmin

`func (o *TeamInvitation) SetAccountAdmin(v bool)`

SetAccountAdmin sets AccountAdmin field to given value.


### GetBillingAccess

`func (o *TeamInvitation) GetBillingAccess() bool`

GetBillingAccess returns the BillingAccess field if non-nil, zero value otherwise.

### GetBillingAccessOk

`func (o *TeamInvitation) GetBillingAccessOk() (*bool, bool)`

GetBillingAccessOk returns a tuple with the BillingAccess field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBillingAccess

`func (o *TeamInvitation) SetBillingAccess(v bool)`

SetBillingAccess sets BillingAccess field to given value.


### GetAllProjects

`func (o *TeamInvitation) GetAllProjects() bool`

GetAllProjects returns the AllProjects field if non-nil, zero value otherwise.

### GetAllProjectsOk

`func (o *TeamInvitation) GetAllProjectsOk() (*bool, bool)`

GetAllProjectsOk returns a tuple with the AllProjects field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAllProjects

`func (o *TeamInvitation) SetAllProjects(v bool)`

SetAllProjects sets AllProjects field to given value.


### GetProjectIds

`func (o *TeamInvitation) GetProjectIds() []int32`

GetProjectIds returns the ProjectIds field if non-nil, zero value otherwise.

### GetProjectIdsOk

`func (o *TeamInvitation) GetProjectIdsOk() (*[]int32, bool)`

GetProjectIdsOk returns a tuple with the ProjectIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectIds

`func (o *TeamInvitation) SetProjectIds(v []int32)`

SetProjectIds sets ProjectIds field to given value.


### GetInvitedAt

`func (o *TeamInvitation) GetInvitedAt() time.Time`

GetInvitedAt returns the InvitedAt field if non-nil, zero value otherwise.

### GetInvitedAtOk

`func (o *TeamInvitation) GetInvitedAtOk() (*time.Time, bool)`

GetInvitedAtOk returns a tuple with the InvitedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInvitedAt

`func (o *TeamInvitation) SetInvitedAt(v time.Time)`

SetInvitedAt sets InvitedAt field to given value.

### HasInvitedAt

`func (o *TeamInvitation) HasInvitedAt() bool`

HasInvitedAt returns a boolean if a field has been set.

### SetInvitedAtNil

`func (o *TeamInvitation) SetInvitedAtNil(b bool)`

 SetInvitedAtNil sets the value for InvitedAt to be an explicit nil

### UnsetInvitedAt
`func (o *TeamInvitation) UnsetInvitedAt()`

UnsetInvitedAt ensures that no value is present for InvitedAt, not even an explicit nil
### GetExpiresAt

`func (o *TeamInvitation) GetExpiresAt() time.Time`

GetExpiresAt returns the ExpiresAt field if non-nil, zero value otherwise.

### GetExpiresAtOk

`func (o *TeamInvitation) GetExpiresAtOk() (*time.Time, bool)`

GetExpiresAtOk returns a tuple with the ExpiresAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpiresAt

`func (o *TeamInvitation) SetExpiresAt(v time.Time)`

SetExpiresAt sets ExpiresAt field to given value.

### HasExpiresAt

`func (o *TeamInvitation) HasExpiresAt() bool`

HasExpiresAt returns a boolean if a field has been set.

### SetExpiresAtNil

`func (o *TeamInvitation) SetExpiresAtNil(b bool)`

 SetExpiresAtNil sets the value for ExpiresAt to be an explicit nil

### UnsetExpiresAt
`func (o *TeamInvitation) UnsetExpiresAt()`

UnsetExpiresAt ensures that no value is present for ExpiresAt, not even an explicit nil
### GetCreatedAt

`func (o *TeamInvitation) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *TeamInvitation) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *TeamInvitation) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *TeamInvitation) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


