# \GEOWriterAPI

All URIs are relative to *https://api.llmpulse.ai/api/v1*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateIntelligenceTask**](GEOWriterAPI.md#CreateIntelligenceTask) | **Post** /intelligence_tasks | Create a GEO Writer task
[**GetIntelligenceTask**](GEOWriterAPI.md#GetIntelligenceTask) | **Get** /intelligence_tasks/{id} | Get a GEO Writer task
[**ListIntelligenceTasks**](GEOWriterAPI.md#ListIntelligenceTasks) | **Get** /intelligence_tasks | List GEO Writer tasks
[**RevertIntelligenceTaskContent**](GEOWriterAPI.md#RevertIntelligenceTaskContent) | **Post** /intelligence_tasks/{id}/revert | Revert GEO Writer task content
[**UpdateIntelligenceTaskContent**](GEOWriterAPI.md#UpdateIntelligenceTaskContent) | **Patch** /intelligence_tasks/{id} | Edit GEO Writer task content



## CreateIntelligenceTask

> IntelligenceTask CreateIntelligenceTask(ctx).IntelligenceTaskCreateRequest(intelligenceTaskCreateRequest).Execute()

Create a GEO Writer task



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
	intelligenceTaskCreateRequest := *openapiclient.NewIntelligenceTaskCreateRequest(int32(123), "TaskType_example") // IntelligenceTaskCreateRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GEOWriterAPI.CreateIntelligenceTask(context.Background()).IntelligenceTaskCreateRequest(intelligenceTaskCreateRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GEOWriterAPI.CreateIntelligenceTask``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateIntelligenceTask`: IntelligenceTask
	fmt.Fprintf(os.Stdout, "Response from `GEOWriterAPI.CreateIntelligenceTask`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateIntelligenceTaskRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **intelligenceTaskCreateRequest** | [**IntelligenceTaskCreateRequest**](IntelligenceTaskCreateRequest.md) |  | 

### Return type

[**IntelligenceTask**](IntelligenceTask.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetIntelligenceTask

> IntelligenceTask GetIntelligenceTask(ctx, id).ProjectId(projectId).Execute()

Get a GEO Writer task

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
	id := "id_example" // string | Numeric task ID or public_id string token

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GEOWriterAPI.GetIntelligenceTask(context.Background(), id).ProjectId(projectId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GEOWriterAPI.GetIntelligenceTask``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetIntelligenceTask`: IntelligenceTask
	fmt.Fprintf(os.Stdout, "Response from `GEOWriterAPI.GetIntelligenceTask`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | Numeric task ID or public_id string token | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetIntelligenceTaskRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **projectId** | **int32** | Project ID | 


### Return type

[**IntelligenceTask**](IntelligenceTask.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListIntelligenceTasks

> ListIntelligenceTasks(ctx).ProjectId(projectId).TaskType(taskType).Status(status).Page(page).PerPage(perPage).Execute()

List GEO Writer tasks

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
	taskType := "taskType_example" // string |  (optional)
	status := "status_example" // string |  (optional)
	page := int32(56) // int32 |  (optional) (default to 1)
	perPage := int32(56) // int32 |  (optional) (default to 20)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.GEOWriterAPI.ListIntelligenceTasks(context.Background()).ProjectId(projectId).TaskType(taskType).Status(status).Page(page).PerPage(perPage).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GEOWriterAPI.ListIntelligenceTasks``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListIntelligenceTasksRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **projectId** | **int32** | Project ID | 
 **taskType** | **string** |  | 
 **status** | **string** |  | 
 **page** | **int32** |  | [default to 1]
 **perPage** | **int32** |  | [default to 20]

### Return type

 (empty response body)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RevertIntelligenceTaskContent

> IntelligenceTask RevertIntelligenceTaskContent(ctx, id).ProjectId(projectId).Execute()

Revert GEO Writer task content



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
	id := "id_example" // string | Numeric task ID or public_id string token

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GEOWriterAPI.RevertIntelligenceTaskContent(context.Background(), id).ProjectId(projectId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GEOWriterAPI.RevertIntelligenceTaskContent``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RevertIntelligenceTaskContent`: IntelligenceTask
	fmt.Fprintf(os.Stdout, "Response from `GEOWriterAPI.RevertIntelligenceTaskContent`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | Numeric task ID or public_id string token | 

### Other Parameters

Other parameters are passed through a pointer to a apiRevertIntelligenceTaskContentRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **projectId** | **int32** | Project ID | 


### Return type

[**IntelligenceTask**](IntelligenceTask.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateIntelligenceTaskContent

> IntelligenceTaskUpdateResponse UpdateIntelligenceTaskContent(ctx, id).IntelligenceTaskUpdateRequest(intelligenceTaskUpdateRequest).Execute()

Edit GEO Writer task content



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
	id := "id_example" // string | Numeric task ID or public_id string token
	intelligenceTaskUpdateRequest := *openapiclient.NewIntelligenceTaskUpdateRequest(int32(123), map[string]string{"key": "Inner_example"}) // IntelligenceTaskUpdateRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GEOWriterAPI.UpdateIntelligenceTaskContent(context.Background(), id).IntelligenceTaskUpdateRequest(intelligenceTaskUpdateRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GEOWriterAPI.UpdateIntelligenceTaskContent``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateIntelligenceTaskContent`: IntelligenceTaskUpdateResponse
	fmt.Fprintf(os.Stdout, "Response from `GEOWriterAPI.UpdateIntelligenceTaskContent`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | Numeric task ID or public_id string token | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateIntelligenceTaskContentRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **intelligenceTaskUpdateRequest** | [**IntelligenceTaskUpdateRequest**](IntelligenceTaskUpdateRequest.md) |  | 

### Return type

[**IntelligenceTaskUpdateResponse**](IntelligenceTaskUpdateResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

