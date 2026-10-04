# \StoreIntegrationsAPI

All URIs are relative to *https://api.llmpulse.ai/api/v1*

Method | HTTP request | Description
------------- | ------------- | -------------
[**AcceptCatalogPromptSuggestions**](StoreIntegrationsAPI.md#AcceptCatalogPromptSuggestions) | **Post** /catalog_prompt_suggestions/accept | Accept catalog prompt suggestions
[**CreateCatalogPromptSuggestions**](StoreIntegrationsAPI.md#CreateCatalogPromptSuggestions) | **Post** /catalog_prompt_suggestions | Suggest buyer prompts from catalog products
[**GetStoreConnection**](StoreIntegrationsAPI.md#GetStoreConnection) | **Get** /store_connection | Match a store to a project
[**ListAiOrders**](StoreIntegrationsAPI.md#ListAiOrders) | **Get** /ai_orders | Read AI-referred store orders
[**ListCatalogPromptSuggestions**](StoreIntegrationsAPI.md#ListCatalogPromptSuggestions) | **Get** /catalog_prompt_suggestions | List catalog prompt suggestions
[**RejectCatalogPromptSuggestions**](StoreIntegrationsAPI.md#RejectCatalogPromptSuggestions) | **Post** /catalog_prompt_suggestions/reject | Reject catalog prompt suggestions
[**ReplaceAiOrders**](StoreIntegrationsAPI.md#ReplaceAiOrders) | **Put** /ai_orders | Replace AI-referred store orders for a window



## AcceptCatalogPromptSuggestions

> CatalogPromptSuggestionsAcceptResponse AcceptCatalogPromptSuggestions(ctx).CatalogPromptSuggestionIdsRequest(catalogPromptSuggestionIdsRequest).Execute()

Accept catalog prompt suggestions



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
	catalogPromptSuggestionIdsRequest := *openapiclient.NewCatalogPromptSuggestionIdsRequest(int32(123), []int32{int32(123)}) // CatalogPromptSuggestionIdsRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.StoreIntegrationsAPI.AcceptCatalogPromptSuggestions(context.Background()).CatalogPromptSuggestionIdsRequest(catalogPromptSuggestionIdsRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `StoreIntegrationsAPI.AcceptCatalogPromptSuggestions``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `AcceptCatalogPromptSuggestions`: CatalogPromptSuggestionsAcceptResponse
	fmt.Fprintf(os.Stdout, "Response from `StoreIntegrationsAPI.AcceptCatalogPromptSuggestions`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiAcceptCatalogPromptSuggestionsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **catalogPromptSuggestionIdsRequest** | [**CatalogPromptSuggestionIdsRequest**](CatalogPromptSuggestionIdsRequest.md) |  | 

### Return type

[**CatalogPromptSuggestionsAcceptResponse**](CatalogPromptSuggestionsAcceptResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CreateCatalogPromptSuggestions

> CatalogPromptSuggestionsCreateResponse CreateCatalogPromptSuggestions(ctx).CatalogPromptSuggestionsCreateRequest(catalogPromptSuggestionsCreateRequest).Execute()

Suggest buyer prompts from catalog products



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
	catalogPromptSuggestionsCreateRequest := *openapiclient.NewCatalogPromptSuggestionsCreateRequest(int32(123), "Platform_example", []openapiclient.CatalogProduct{*openapiclient.NewCatalogProduct("ExternalId_example", "Title_example")}) // CatalogPromptSuggestionsCreateRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.StoreIntegrationsAPI.CreateCatalogPromptSuggestions(context.Background()).CatalogPromptSuggestionsCreateRequest(catalogPromptSuggestionsCreateRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `StoreIntegrationsAPI.CreateCatalogPromptSuggestions``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateCatalogPromptSuggestions`: CatalogPromptSuggestionsCreateResponse
	fmt.Fprintf(os.Stdout, "Response from `StoreIntegrationsAPI.CreateCatalogPromptSuggestions`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateCatalogPromptSuggestionsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **catalogPromptSuggestionsCreateRequest** | [**CatalogPromptSuggestionsCreateRequest**](CatalogPromptSuggestionsCreateRequest.md) |  | 

### Return type

[**CatalogPromptSuggestionsCreateResponse**](CatalogPromptSuggestionsCreateResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetStoreConnection

> StoreConnectionResponse GetStoreConnection(ctx).Platform(platform).Domain(domain).Execute()

Match a store to a project



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
	platform := "platform_example" // string | Store platform
	domain := "domain_example" // string | Store domain, with or without scheme, e.g. acme-store.com

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.StoreIntegrationsAPI.GetStoreConnection(context.Background()).Platform(platform).Domain(domain).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `StoreIntegrationsAPI.GetStoreConnection``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetStoreConnection`: StoreConnectionResponse
	fmt.Fprintf(os.Stdout, "Response from `StoreIntegrationsAPI.GetStoreConnection`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetStoreConnectionRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **platform** | **string** | Store platform | 
 **domain** | **string** | Store domain, with or without scheme, e.g. acme-store.com | 

### Return type

[**StoreConnectionResponse**](StoreConnectionResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListAiOrders

> AiOrdersResponse ListAiOrders(ctx).ProjectId(projectId).Platform(platform).From(from).To(to).Execute()

Read AI-referred store orders



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
	platform := "platform_example" // string | Store platform (optional) (default to "shopify")
	from := time.Now() // string | First day (YYYY-MM-DD). Defaults to 89 days before to (optional)
	to := time.Now() // string | Last day (YYYY-MM-DD). Defaults to today; the window is at most 400 days (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.StoreIntegrationsAPI.ListAiOrders(context.Background()).ProjectId(projectId).Platform(platform).From(from).To(to).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `StoreIntegrationsAPI.ListAiOrders``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListAiOrders`: AiOrdersResponse
	fmt.Fprintf(os.Stdout, "Response from `StoreIntegrationsAPI.ListAiOrders`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListAiOrdersRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **projectId** | **int32** | Project ID | 
 **platform** | **string** | Store platform | [default to &quot;shopify&quot;]
 **from** | **string** | First day (YYYY-MM-DD). Defaults to 89 days before to | 
 **to** | **string** | Last day (YYYY-MM-DD). Defaults to today; the window is at most 400 days | 

### Return type

[**AiOrdersResponse**](AiOrdersResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListCatalogPromptSuggestions

> CatalogPromptSuggestionsResponse ListCatalogPromptSuggestions(ctx).ProjectId(projectId).Status(status).ProductExternalId(productExternalId).Page(page).PerPage(perPage).Execute()

List catalog prompt suggestions



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
	status := "status_example" // string | Only suggestions in this status (optional)
	productExternalId := "productExternalId_example" // string | Only suggestions for this store product id (optional)
	page := int32(56) // int32 |  (optional) (default to 1)
	perPage := int32(56) // int32 |  (optional) (default to 50)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.StoreIntegrationsAPI.ListCatalogPromptSuggestions(context.Background()).ProjectId(projectId).Status(status).ProductExternalId(productExternalId).Page(page).PerPage(perPage).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `StoreIntegrationsAPI.ListCatalogPromptSuggestions``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListCatalogPromptSuggestions`: CatalogPromptSuggestionsResponse
	fmt.Fprintf(os.Stdout, "Response from `StoreIntegrationsAPI.ListCatalogPromptSuggestions`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListCatalogPromptSuggestionsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **projectId** | **int32** | Project ID | 
 **status** | **string** | Only suggestions in this status | 
 **productExternalId** | **string** | Only suggestions for this store product id | 
 **page** | **int32** |  | [default to 1]
 **perPage** | **int32** |  | [default to 50]

### Return type

[**CatalogPromptSuggestionsResponse**](CatalogPromptSuggestionsResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RejectCatalogPromptSuggestions

> CatalogPromptSuggestionsRejectResponse RejectCatalogPromptSuggestions(ctx).CatalogPromptSuggestionIdsRequest(catalogPromptSuggestionIdsRequest).Execute()

Reject catalog prompt suggestions



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
	catalogPromptSuggestionIdsRequest := *openapiclient.NewCatalogPromptSuggestionIdsRequest(int32(123), []int32{int32(123)}) // CatalogPromptSuggestionIdsRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.StoreIntegrationsAPI.RejectCatalogPromptSuggestions(context.Background()).CatalogPromptSuggestionIdsRequest(catalogPromptSuggestionIdsRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `StoreIntegrationsAPI.RejectCatalogPromptSuggestions``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RejectCatalogPromptSuggestions`: CatalogPromptSuggestionsRejectResponse
	fmt.Fprintf(os.Stdout, "Response from `StoreIntegrationsAPI.RejectCatalogPromptSuggestions`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiRejectCatalogPromptSuggestionsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **catalogPromptSuggestionIdsRequest** | [**CatalogPromptSuggestionIdsRequest**](CatalogPromptSuggestionIdsRequest.md) |  | 

### Return type

[**CatalogPromptSuggestionsRejectResponse**](CatalogPromptSuggestionsRejectResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ReplaceAiOrders

> AiOrdersUpdateResponse ReplaceAiOrders(ctx).AiOrdersUpdateRequest(aiOrdersUpdateRequest).Execute()

Replace AI-referred store orders for a window



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
	aiOrdersUpdateRequest := *openapiclient.NewAiOrdersUpdateRequest(int32(123), "Platform_example", "Currency_example", time.Now(), time.Now(), []openapiclient.AiOrdersUpdateRequestDaysInner{*openapiclient.NewAiOrdersUpdateRequestDaysInner(time.Now(), "Referrer_example", int32(123), "Revenue_example")}) // AiOrdersUpdateRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.StoreIntegrationsAPI.ReplaceAiOrders(context.Background()).AiOrdersUpdateRequest(aiOrdersUpdateRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `StoreIntegrationsAPI.ReplaceAiOrders``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ReplaceAiOrders`: AiOrdersUpdateResponse
	fmt.Fprintf(os.Stdout, "Response from `StoreIntegrationsAPI.ReplaceAiOrders`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiReplaceAiOrdersRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **aiOrdersUpdateRequest** | [**AiOrdersUpdateRequest**](AiOrdersUpdateRequest.md) |  | 

### Return type

[**AiOrdersUpdateResponse**](AiOrdersUpdateResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

