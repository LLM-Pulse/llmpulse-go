# \AnnotationsAPI

All URIs are relative to *https://api.llmpulse.ai/api/v1*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateAnnotation**](AnnotationsAPI.md#CreateAnnotation) | **Post** /annotations | Create a timeline annotation
[**DeleteAnnotation**](AnnotationsAPI.md#DeleteAnnotation) | **Delete** /annotations/{id} | Delete a timeline annotation
[**ListAnnotations**](AnnotationsAPI.md#ListAnnotations) | **Get** /annotations | List timeline annotations
[**UpdateAnnotation**](AnnotationsAPI.md#UpdateAnnotation) | **Patch** /annotations/{id} | Update a timeline annotation



## CreateAnnotation

> AnnotationCreateResponse CreateAnnotation(ctx).CreateAnnotationRequest(createAnnotationRequest).Execute()

Create a timeline annotation



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
	createAnnotationRequest := *openapiclient.NewCreateAnnotationRequest(int32(123), "Title_example") // CreateAnnotationRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AnnotationsAPI.CreateAnnotation(context.Background()).CreateAnnotationRequest(createAnnotationRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AnnotationsAPI.CreateAnnotation``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateAnnotation`: AnnotationCreateResponse
	fmt.Fprintf(os.Stdout, "Response from `AnnotationsAPI.CreateAnnotation`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateAnnotationRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createAnnotationRequest** | [**CreateAnnotationRequest**](CreateAnnotationRequest.md) |  | 

### Return type

[**AnnotationCreateResponse**](AnnotationCreateResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteAnnotation

> DeleteAnnotation(ctx, id).ProjectId(projectId).Execute()

Delete a timeline annotation



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

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.AnnotationsAPI.DeleteAnnotation(context.Background(), id).ProjectId(projectId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AnnotationsAPI.DeleteAnnotation``: %v\n", err)
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

Other parameters are passed through a pointer to a apiDeleteAnnotationRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **projectId** | **int32** | Project ID | 


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


## ListAnnotations

> ListAnnotations(ctx).ProjectId(projectId).From(from).To(to).AnnotationCategoryId(annotationCategoryId).Page(page).PerPage(perPage).Execute()

List timeline annotations



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
    "time"
	openapiclient "github.com/LLM-Pulse/llmpulse-go"
)

func main() {
	projectId := int32(56) // int32 | Project ID
	from := time.Now() // string |  (optional)
	to := time.Now() // string |  (optional)
	annotationCategoryId := int32(56) // int32 |  (optional)
	page := int32(56) // int32 |  (optional) (default to 1)
	perPage := int32(56) // int32 |  (optional) (default to 20)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.AnnotationsAPI.ListAnnotations(context.Background()).ProjectId(projectId).From(from).To(to).AnnotationCategoryId(annotationCategoryId).Page(page).PerPage(perPage).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AnnotationsAPI.ListAnnotations``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListAnnotationsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **projectId** | **int32** | Project ID | 
 **from** | **string** |  | 
 **to** | **string** |  | 
 **annotationCategoryId** | **int32** |  | 
 **page** | **int32** |  | [default to 1]
 **perPage** | **int32** |  | [default to 20]

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


## UpdateAnnotation

> UpdateAnnotation(ctx, id).UpdateAnnotationRequest(updateAnnotationRequest).Execute()

Update a timeline annotation



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
	id := int32(56) // int32 | 
	updateAnnotationRequest := *openapiclient.NewUpdateAnnotationRequest(int32(123)) // UpdateAnnotationRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.AnnotationsAPI.UpdateAnnotation(context.Background(), id).UpdateAnnotationRequest(updateAnnotationRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AnnotationsAPI.UpdateAnnotation``: %v\n", err)
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

Other parameters are passed through a pointer to a apiUpdateAnnotationRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **updateAnnotationRequest** | [**UpdateAnnotationRequest**](UpdateAnnotationRequest.md) |  | 

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

