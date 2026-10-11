# CreateTeamInvitation201Response

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
**EmailSent** | **bool** | False when the email provider refused the invitation email | 
**RequestId** | Pointer to **string** |  | [optional] 

## Methods

### NewCreateTeamInvitation201Response

`func NewCreateTeamInvitation201Response(id int32, email string, permissionRole string, accountRole NullableTeamAccountRole, permissions map[string][]string, accountAdmin bool, billingAccess bool, allProjects bool, projectIds []int32, emailSent bool, ) *CreateTeamInvitation201Response`

NewCreateTeamInvitation201Response instantiates a new CreateTeamInvitation201Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateTeamInvitation201ResponseWithDefaults

`func NewCreateTeamInvitation201ResponseWithDefaults() *CreateTeamInvitation201Response`

NewCreateTeamInvitation201ResponseWithDefaults instantiates a new CreateTeamInvitation201Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *CreateTeamInvitation201Response) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *CreateTeamInvitation201Response) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *CreateTeamInvitation201Response) SetId(v int32)`

SetId sets Id field to given value.


### GetEmail

`func (o *CreateTeamInvitation201Response) GetEmail() string`

GetEmail returns the Email field if non-nil, zero value otherwise.

### GetEmailOk

`func (o *CreateTeamInvitation201Response) GetEmailOk() (*string, bool)`

GetEmailOk returns a tuple with the Email field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmail

`func (o *CreateTeamInvitation201Response) SetEmail(v string)`

SetEmail sets Email field to given value.


### GetPermissionRole

`func (o *CreateTeamInvitation201Response) GetPermissionRole() string`

GetPermissionRole returns the PermissionRole field if non-nil, zero value otherwise.

### GetPermissionRoleOk

`func (o *CreateTeamInvitation201Response) GetPermissionRoleOk() (*string, bool)`

GetPermissionRoleOk returns a tuple with the PermissionRole field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPermissionRole

`func (o *CreateTeamInvitation201Response) SetPermissionRole(v string)`

SetPermissionRole sets PermissionRole field to given value.


### GetAccountRole

`func (o *CreateTeamInvitation201Response) GetAccountRole() TeamAccountRole`

GetAccountRole returns the AccountRole field if non-nil, zero value otherwise.

### GetAccountRoleOk

`func (o *CreateTeamInvitation201Response) GetAccountRoleOk() (*TeamAccountRole, bool)`

GetAccountRoleOk returns a tuple with the AccountRole field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountRole

`func (o *CreateTeamInvitation201Response) SetAccountRole(v TeamAccountRole)`

SetAccountRole sets AccountRole field to given value.


### SetAccountRoleNil

`func (o *CreateTeamInvitation201Response) SetAccountRoleNil(b bool)`

 SetAccountRoleNil sets the value for AccountRole to be an explicit nil

### UnsetAccountRole
`func (o *CreateTeamInvitation201Response) UnsetAccountRole()`

UnsetAccountRole ensures that no value is present for AccountRole, not even an explicit nil
### GetPermissions

`func (o *CreateTeamInvitation201Response) GetPermissions() map[string][]string`

GetPermissions returns the Permissions field if non-nil, zero value otherwise.

### GetPermissionsOk

`func (o *CreateTeamInvitation201Response) GetPermissionsOk() (*map[string][]string, bool)`

GetPermissionsOk returns a tuple with the Permissions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPermissions

`func (o *CreateTeamInvitation201Response) SetPermissions(v map[string][]string)`

SetPermissions sets Permissions field to given value.


### SetPermissionsNil

`func (o *CreateTeamInvitation201Response) SetPermissionsNil(b bool)`

 SetPermissionsNil sets the value for Permissions to be an explicit nil

### UnsetPermissions
`func (o *CreateTeamInvitation201Response) UnsetPermissions()`

UnsetPermissions ensures that no value is present for Permissions, not even an explicit nil
### GetAccountAdmin

`func (o *CreateTeamInvitation201Response) GetAccountAdmin() bool`

GetAccountAdmin returns the AccountAdmin field if non-nil, zero value otherwise.

### GetAccountAdminOk

`func (o *CreateTeamInvitation201Response) GetAccountAdminOk() (*bool, bool)`

GetAccountAdminOk returns a tuple with the AccountAdmin field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountAdmin

`func (o *CreateTeamInvitation201Response) SetAccountAdmin(v bool)`

SetAccountAdmin sets AccountAdmin field to given value.


### GetBillingAccess

`func (o *CreateTeamInvitation201Response) GetBillingAccess() bool`

GetBillingAccess returns the BillingAccess field if non-nil, zero value otherwise.

### GetBillingAccessOk

`func (o *CreateTeamInvitation201Response) GetBillingAccessOk() (*bool, bool)`

GetBillingAccessOk returns a tuple with the BillingAccess field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBillingAccess

`func (o *CreateTeamInvitation201Response) SetBillingAccess(v bool)`

SetBillingAccess sets BillingAccess field to given value.


### GetAllProjects

`func (o *CreateTeamInvitation201Response) GetAllProjects() bool`

GetAllProjects returns the AllProjects field if non-nil, zero value otherwise.

### GetAllProjectsOk

`func (o *CreateTeamInvitation201Response) GetAllProjectsOk() (*bool, bool)`

GetAllProjectsOk returns a tuple with the AllProjects field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAllProjects

`func (o *CreateTeamInvitation201Response) SetAllProjects(v bool)`

SetAllProjects sets AllProjects field to given value.


### GetProjectIds

`func (o *CreateTeamInvitation201Response) GetProjectIds() []int32`

GetProjectIds returns the ProjectIds field if non-nil, zero value otherwise.

### GetProjectIdsOk

`func (o *CreateTeamInvitation201Response) GetProjectIdsOk() (*[]int32, bool)`

GetProjectIdsOk returns a tuple with the ProjectIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectIds

`func (o *CreateTeamInvitation201Response) SetProjectIds(v []int32)`

SetProjectIds sets ProjectIds field to given value.


### GetInvitedAt

`func (o *CreateTeamInvitation201Response) GetInvitedAt() time.Time`

GetInvitedAt returns the InvitedAt field if non-nil, zero value otherwise.

### GetInvitedAtOk

`func (o *CreateTeamInvitation201Response) GetInvitedAtOk() (*time.Time, bool)`

GetInvitedAtOk returns a tuple with the InvitedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInvitedAt

`func (o *CreateTeamInvitation201Response) SetInvitedAt(v time.Time)`

SetInvitedAt sets InvitedAt field to given value.

### HasInvitedAt

`func (o *CreateTeamInvitation201Response) HasInvitedAt() bool`

HasInvitedAt returns a boolean if a field has been set.

### SetInvitedAtNil

`func (o *CreateTeamInvitation201Response) SetInvitedAtNil(b bool)`

 SetInvitedAtNil sets the value for InvitedAt to be an explicit nil

### UnsetInvitedAt
`func (o *CreateTeamInvitation201Response) UnsetInvitedAt()`

UnsetInvitedAt ensures that no value is present for InvitedAt, not even an explicit nil
### GetExpiresAt

`func (o *CreateTeamInvitation201Response) GetExpiresAt() time.Time`

GetExpiresAt returns the ExpiresAt field if non-nil, zero value otherwise.

### GetExpiresAtOk

`func (o *CreateTeamInvitation201Response) GetExpiresAtOk() (*time.Time, bool)`

GetExpiresAtOk returns a tuple with the ExpiresAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpiresAt

`func (o *CreateTeamInvitation201Response) SetExpiresAt(v time.Time)`

SetExpiresAt sets ExpiresAt field to given value.

### HasExpiresAt

`func (o *CreateTeamInvitation201Response) HasExpiresAt() bool`

HasExpiresAt returns a boolean if a field has been set.

### SetExpiresAtNil

`func (o *CreateTeamInvitation201Response) SetExpiresAtNil(b bool)`

 SetExpiresAtNil sets the value for ExpiresAt to be an explicit nil

### UnsetExpiresAt
`func (o *CreateTeamInvitation201Response) UnsetExpiresAt()`

UnsetExpiresAt ensures that no value is present for ExpiresAt, not even an explicit nil
### GetCreatedAt

`func (o *CreateTeamInvitation201Response) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *CreateTeamInvitation201Response) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *CreateTeamInvitation201Response) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *CreateTeamInvitation201Response) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetEmailSent

`func (o *CreateTeamInvitation201Response) GetEmailSent() bool`

GetEmailSent returns the EmailSent field if non-nil, zero value otherwise.

### GetEmailSentOk

`func (o *CreateTeamInvitation201Response) GetEmailSentOk() (*bool, bool)`

GetEmailSentOk returns a tuple with the EmailSent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmailSent

`func (o *CreateTeamInvitation201Response) SetEmailSent(v bool)`

SetEmailSent sets EmailSent field to given value.


### GetRequestId

`func (o *CreateTeamInvitation201Response) GetRequestId() string`

GetRequestId returns the RequestId field if non-nil, zero value otherwise.

### GetRequestIdOk

`func (o *CreateTeamInvitation201Response) GetRequestIdOk() (*string, bool)`

GetRequestIdOk returns a tuple with the RequestId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestId

`func (o *CreateTeamInvitation201Response) SetRequestId(v string)`

SetRequestId sets RequestId field to given value.

### HasRequestId

`func (o *CreateTeamInvitation201Response) HasRequestId() bool`

HasRequestId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


