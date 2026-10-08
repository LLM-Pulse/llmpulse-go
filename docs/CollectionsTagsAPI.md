# \CollectionsTagsAPI

All URIs are relative to *https://api.llmpulse.ai/api/v1*

Method | HTTP request | Description
------------- | ------------- | -------------
[**AssignPromptTags**](CollectionsTagsAPI.md#AssignPromptTags) | **Post** /prompts/assign_tags | Bulk-attach tags to prompts
[**CreateCollection**](CollectionsTagsAPI.md#CreateCollection) | **Post** /collections | Create a tag
[**DeleteCollection**](CollectionsTagsAPI.md#DeleteCollection) | **Delete** /collections/{id} | Delete a tag
[**ListCollections**](CollectionsTagsAPI.md#ListCollections) | **Get** /dimensions/collections | List tags/collections
[**ListTags**](CollectionsTagsAPI.md#ListTags) | **Get** /dimensions/tags | List tags (alias for /collections)
[**UpdateCollection**](CollectionsTagsAPI.md#UpdateCollection) | **Patch** /collections/{id} | Update a tag



## AssignPromptTags

> PromptTagsAssignResponse AssignPromptTags(ctx).AssignPromptTagsRequest(assignPromptTagsRequest).Execute()

Bulk-attach tags to prompts



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
	assignPromptTagsRequest := *openapiclient.NewAssignPromptTagsRequest(int32(123), []int32{int32(123)}) // AssignPromptTagsRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CollectionsTagsAPI.AssignPromptTags(context.Background()).AssignPromptTagsRequest(assignPromptTagsRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CollectionsTagsAPI.AssignPromptTags``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `AssignPromptTags`: PromptTagsAssignResponse
	fmt.Fprintf(os.Stdout, "Response from `CollectionsTagsAPI.AssignPromptTags`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiAssignPromptTagsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **assignPromptTagsRequest** | [**AssignPromptTagsRequest**](AssignPromptTagsRequest.md) |  | 

### Return type

[**PromptTagsAssignResponse**](PromptTagsAssignResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CreateCollection

> CollectionCreateResponse CreateCollection(ctx).CreateCollectionRequest(createCollectionRequest).Execute()

Create a tag



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
	createCollectionRequest := *openapiclient.NewCreateCollectionRequest(int32(123), "Name_example") // CreateCollectionRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CollectionsTagsAPI.CreateCollection(context.Background()).CreateCollectionRequest(createCollectionRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CollectionsTagsAPI.CreateCollection``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateCollection`: CollectionCreateResponse
	fmt.Fprintf(os.Stdout, "Response from `CollectionsTagsAPI.CreateCollection`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateCollectionRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createCollectionRequest** | [**CreateCollectionRequest**](CreateCollectionRequest.md) |  | 

### Return type

[**CollectionCreateResponse**](CollectionCreateResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteCollection

> DeleteCollection(ctx, id).ProjectId(projectId).Execute()

Delete a tag



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
	r, err := apiClient.CollectionsTagsAPI.DeleteCollection(context.Background(), id).ProjectId(projectId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CollectionsTagsAPI.DeleteCollection``: %v\n", err)
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

Other parameters are passed through a pointer to a apiDeleteCollectionRequest struct via the builder pattern


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


## ListCollections

> CollectionsResponse ListCollections(ctx).ProjectId(projectId).Output(output).Execute()

List tags/collections

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
	output := "output_example" // string | Rectangular output for BI tools (Tableau, Excel, Sheets, ELT). Omit for the default nested JSON. 'flat' returns the same metadata plus 'columns' and 'rows'; 'csv' returns those rows as text/csv. Errors are always returned as JSON. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CollectionsTagsAPI.ListCollections(context.Background()).ProjectId(projectId).Output(output).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CollectionsTagsAPI.ListCollections``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListCollections`: CollectionsResponse
	fmt.Fprintf(os.Stdout, "Response from `CollectionsTagsAPI.ListCollections`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListCollectionsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **projectId** | **int32** | Project ID | 
 **output** | **string** | Rectangular output for BI tools (Tableau, Excel, Sheets, ELT). Omit for the default nested JSON. &#39;flat&#39; returns the same metadata plus &#39;columns&#39; and &#39;rows&#39;; &#39;csv&#39; returns those rows as text/csv. Errors are always returned as JSON. | 

### Return type

[**CollectionsResponse**](CollectionsResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListTags

> CollectionsResponse ListTags(ctx).ProjectId(projectId).Output(output).Execute()

List tags (alias for /collections)

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
	output := "output_example" // string | Rectangular output for BI tools (Tableau, Excel, Sheets, ELT). Omit for the default nested JSON. 'flat' returns the same metadata plus 'columns' and 'rows'; 'csv' returns those rows as text/csv. Errors are always returned as JSON. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CollectionsTagsAPI.ListTags(context.Background()).ProjectId(projectId).Output(output).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CollectionsTagsAPI.ListTags``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListTags`: CollectionsResponse
	fmt.Fprintf(os.Stdout, "Response from `CollectionsTagsAPI.ListTags`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListTagsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **projectId** | **int32** | Project ID | 
 **output** | **string** | Rectangular output for BI tools (Tableau, Excel, Sheets, ELT). Omit for the default nested JSON. &#39;flat&#39; returns the same metadata plus &#39;columns&#39; and &#39;rows&#39;; &#39;csv&#39; returns those rows as text/csv. Errors are always returned as JSON. | 

### Return type

[**CollectionsResponse**](CollectionsResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateCollection

> UpdateCollection(ctx, id).UpdateCollectionRequest(updateCollectionRequest).Execute()

Update a tag



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
	updateCollectionRequest := *openapiclient.NewUpdateCollectionRequest(int32(123)) // UpdateCollectionRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.CollectionsTagsAPI.UpdateCollection(context.Background(), id).UpdateCollectionRequest(updateCollectionRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CollectionsTagsAPI.UpdateCollection``: %v\n", err)
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

Other parameters are passed through a pointer to a apiUpdateCollectionRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **updateCollectionRequest** | [**UpdateCollectionRequest**](UpdateCollectionRequest.md) |  | 

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

