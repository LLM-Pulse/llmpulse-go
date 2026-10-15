# \RecommendationsAPI

All URIs are relative to *https://api.llmpulse.ai/api/v1*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetRecommendation**](RecommendationsAPI.md#GetRecommendation) | **Get** /recommendations/{id} | Get recommendation run with items
[**LaunchRecommendations**](RecommendationsAPI.md#LaunchRecommendations) | **Post** /recommendations | Launch a recommendations generation
[**ListRecommendations**](RecommendationsAPI.md#ListRecommendations) | **Get** /recommendations | List recommendation runs
[**UpdateRecommendationItem**](RecommendationsAPI.md#UpdateRecommendationItem) | **Patch** /recommendations/{id}/items/{item_id} | Complete, archive or restore a recommendation item



## GetRecommendation

> GetRecommendation(ctx, id).ProjectId(projectId).ItemStatus(itemStatus).ResolveSourceRefs(resolveSourceRefs).Execute()

Get recommendation run with items

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
	projectId := int32(56) // int32 | Project ID
	id := int32(56) // int32 | 
	itemStatus := "itemStatus_example" // string |  (optional)
	resolveSourceRefs := true // bool |  (optional) (default to true)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.RecommendationsAPI.GetRecommendation(context.Background(), id).ProjectId(projectId).ItemStatus(itemStatus).ResolveSourceRefs(resolveSourceRefs).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `RecommendationsAPI.GetRecommendation``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetRecommendationRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **projectId** | **int32** | Project ID | 

 **itemStatus** | **string** |  | 
 **resolveSourceRefs** | **bool** |  | [default to true]

### Return type

 (empty response body)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## LaunchRecommendations

> LaunchRecommendations(ctx).LaunchRecommendationsRequest(launchRecommendationsRequest).Execute()

Launch a recommendations generation



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
	launchRecommendationsRequest := *openapiclient.NewLaunchRecommendationsRequest(int32(123)) // LaunchRecommendationsRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.RecommendationsAPI.LaunchRecommendations(context.Background()).LaunchRecommendationsRequest(launchRecommendationsRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `RecommendationsAPI.LaunchRecommendations``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiLaunchRecommendationsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **launchRecommendationsRequest** | [**LaunchRecommendationsRequest**](LaunchRecommendationsRequest.md) |  | 

### Return type

 (empty response body)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListRecommendations

> RecommendationsResponse ListRecommendations(ctx).ProjectId(projectId).RecommendationType(recommendationType).Status(status).Page(page).PerPage(perPage).Execute()

List recommendation runs

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
	projectId := int32(56) // int32 | Project ID
	recommendationType := "recommendationType_example" // string |  (optional)
	status := "status_example" // string |  (optional)
	page := int32(56) // int32 |  (optional) (default to 1)
	perPage := int32(56) // int32 |  (optional) (default to 20)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.RecommendationsAPI.ListRecommendations(context.Background()).ProjectId(projectId).RecommendationType(recommendationType).Status(status).Page(page).PerPage(perPage).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `RecommendationsAPI.ListRecommendations``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListRecommendations`: RecommendationsResponse
	fmt.Fprintf(os.Stdout, "Response from `RecommendationsAPI.ListRecommendations`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListRecommendationsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **projectId** | **int32** | Project ID | 
 **recommendationType** | **string** |  | 
 **status** | **string** |  | 
 **page** | **int32** |  | [default to 1]
 **perPage** | **int32** |  | [default to 20]

### Return type

[**RecommendationsResponse**](RecommendationsResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateRecommendationItem

> RecommendationItemUpdateResponse UpdateRecommendationItem(ctx, id, itemId).UpdateRecommendationItemRequest(updateRecommendationItemRequest).Execute()

Complete, archive or restore a recommendation item



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
	id := int32(56) // int32 | Recommendation run id
	itemId := int32(56) // int32 | Item id, from the items of GET /recommendations/{id}
	updateRecommendationItemRequest := *openapiclient.NewUpdateRecommendationItemRequest(int32(123), "Status_example") // UpdateRecommendationItemRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.RecommendationsAPI.UpdateRecommendationItem(context.Background(), id, itemId).UpdateRecommendationItemRequest(updateRecommendationItemRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `RecommendationsAPI.UpdateRecommendationItem``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateRecommendationItem`: RecommendationItemUpdateResponse
	fmt.Fprintf(os.Stdout, "Response from `RecommendationsAPI.UpdateRecommendationItem`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | Recommendation run id | 
**itemId** | **int32** | Item id, from the items of GET /recommendations/{id} | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateRecommendationItemRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **updateRecommendationItemRequest** | [**UpdateRecommendationItemRequest**](UpdateRecommendationItemRequest.md) |  | 

### Return type

[**RecommendationItemUpdateResponse**](RecommendationItemUpdateResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

