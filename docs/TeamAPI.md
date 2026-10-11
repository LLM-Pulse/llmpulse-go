# \TeamAPI

All URIs are relative to *https://api.llmpulse.ai/api/v1*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateTeamInvitation**](TeamAPI.md#CreateTeamInvitation) | **Post** /team_invitations | Invite a team member
[**ListTeamInvitations**](TeamAPI.md#ListTeamInvitations) | **Get** /team_invitations | List pending team invitations
[**ListTeamMembers**](TeamAPI.md#ListTeamMembers) | **Get** /team_members | List team members
[**RemoveTeamMember**](TeamAPI.md#RemoveTeamMember) | **Delete** /team_members/{id} | Remove a team member
[**RevokeTeamInvitation**](TeamAPI.md#RevokeTeamInvitation) | **Delete** /team_invitations/{id} | Revoke a pending team invitation



## CreateTeamInvitation

> CreateTeamInvitation201Response CreateTeamInvitation(ctx).CreateTeamInvitationRequest(createTeamInvitationRequest).Execute()

Invite a team member



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/LLM-Pulse/llmpulse-go"
)

func main() {
	createTeamInvitationRequest := *openapiclient.NewCreateTeamInvitationRequest("Email_example") // CreateTeamInvitationRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TeamAPI.CreateTeamInvitation(context.Background()).CreateTeamInvitationRequest(createTeamInvitationRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TeamAPI.CreateTeamInvitation``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateTeamInvitation`: CreateTeamInvitation201Response
	fmt.Fprintf(os.Stdout, "Response from `TeamAPI.CreateTeamInvitation`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateTeamInvitationRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createTeamInvitationRequest** | [**CreateTeamInvitationRequest**](CreateTeamInvitationRequest.md) |  | 

### Return type

[**CreateTeamInvitation201Response**](CreateTeamInvitation201Response.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListTeamInvitations

> ListTeamInvitations200Response ListTeamInvitations(ctx).Page(page).PerPage(perPage).Execute()

List pending team invitations



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/LLM-Pulse/llmpulse-go"
)

func main() {
	page := int32(56) // int32 |  (optional)
	perPage := int32(56) // int32 | Default 20, max 100 (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TeamAPI.ListTeamInvitations(context.Background()).Page(page).PerPage(perPage).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TeamAPI.ListTeamInvitations``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListTeamInvitations`: ListTeamInvitations200Response
	fmt.Fprintf(os.Stdout, "Response from `TeamAPI.ListTeamInvitations`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListTeamInvitationsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **page** | **int32** |  | 
 **perPage** | **int32** | Default 20, max 100 | 

### Return type

[**ListTeamInvitations200Response**](ListTeamInvitations200Response.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListTeamMembers

> ListTeamMembers200Response ListTeamMembers(ctx).Page(page).PerPage(perPage).Execute()

List team members



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/LLM-Pulse/llmpulse-go"
)

func main() {
	page := int32(56) // int32 |  (optional)
	perPage := int32(56) // int32 | Default 20, max 100 (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TeamAPI.ListTeamMembers(context.Background()).Page(page).PerPage(perPage).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TeamAPI.ListTeamMembers``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListTeamMembers`: ListTeamMembers200Response
	fmt.Fprintf(os.Stdout, "Response from `TeamAPI.ListTeamMembers`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListTeamMembersRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **page** | **int32** |  | 
 **perPage** | **int32** | Default 20, max 100 | 

### Return type

[**ListTeamMembers200Response**](ListTeamMembers200Response.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RemoveTeamMember

> RemoveTeamMember200Response RemoveTeamMember(ctx, id).Execute()

Remove a team member



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/LLM-Pulse/llmpulse-go"
)

func main() {
	id := int32(56) // int32 | The member id from GET /team_members

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TeamAPI.RemoveTeamMember(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TeamAPI.RemoveTeamMember``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RemoveTeamMember`: RemoveTeamMember200Response
	fmt.Fprintf(os.Stdout, "Response from `TeamAPI.RemoveTeamMember`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | The member id from GET /team_members | 

### Other Parameters

Other parameters are passed through a pointer to a apiRemoveTeamMemberRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**RemoveTeamMember200Response**](RemoveTeamMember200Response.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RevokeTeamInvitation

> RevokeTeamInvitation200Response RevokeTeamInvitation(ctx, id).Execute()

Revoke a pending team invitation



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/LLM-Pulse/llmpulse-go"
)

func main() {
	id := int32(56) // int32 | The invitation id from GET /team_invitations

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TeamAPI.RevokeTeamInvitation(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TeamAPI.RevokeTeamInvitation``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RevokeTeamInvitation`: RevokeTeamInvitation200Response
	fmt.Fprintf(os.Stdout, "Response from `TeamAPI.RevokeTeamInvitation`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | The invitation id from GET /team_invitations | 

### Other Parameters

Other parameters are passed through a pointer to a apiRevokeTeamInvitationRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**RevokeTeamInvitation200Response**](RevokeTeamInvitation200Response.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

