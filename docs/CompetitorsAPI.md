# \CompetitorsAPI

All URIs are relative to *https://api.llmpulse.ai/api/v1*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateCompetitor**](CompetitorsAPI.md#CreateCompetitor) | **Post** /competitors | Add a competitor
[**DeleteCompetitor**](CompetitorsAPI.md#DeleteCompetitor) | **Delete** /competitors/{id} | Delete a competitor
[**GetCompetitorDetails**](CompetitorsAPI.md#GetCompetitorDetails) | **Get** /dimensions/competitors/{id} | Competitor details
[**ListCompetitors**](CompetitorsAPI.md#ListCompetitors) | **Get** /dimensions/competitors | List competitors
[**UpdateCompetitor**](CompetitorsAPI.md#UpdateCompetitor) | **Patch** /competitors/{id} | Update a competitor



## CreateCompetitor

> CreateCompetitor(ctx).CreateCompetitorRequest(createCompetitorRequest).Execute()

Add a competitor



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
	createCompetitorRequest := *openapiclient.NewCreateCompetitorRequest(int32(123), "BrandName_example", "Domain_example") // CreateCompetitorRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.CompetitorsAPI.CreateCompetitor(context.Background()).CreateCompetitorRequest(createCompetitorRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CompetitorsAPI.CreateCompetitor``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateCompetitorRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createCompetitorRequest** | [**CreateCompetitorRequest**](CreateCompetitorRequest.md) |  | 

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


## DeleteCompetitor

> DeleteCompetitor(ctx, id).ProjectId(projectId).Execute()

Delete a competitor



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
	r, err := apiClient.CompetitorsAPI.DeleteCompetitor(context.Background(), id).ProjectId(projectId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CompetitorsAPI.DeleteCompetitor``: %v\n", err)
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

Other parameters are passed through a pointer to a apiDeleteCompetitorRequest struct via the builder pattern


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


## GetCompetitorDetails

> CompetitorDetails GetCompetitorDetails(ctx, id).ProjectId(projectId).Execute()

Competitor details

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
	resp, r, err := apiClient.CompetitorsAPI.GetCompetitorDetails(context.Background(), id).ProjectId(projectId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CompetitorsAPI.GetCompetitorDetails``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetCompetitorDetails`: CompetitorDetails
	fmt.Fprintf(os.Stdout, "Response from `CompetitorsAPI.GetCompetitorDetails`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetCompetitorDetailsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **projectId** | **int32** | Project ID | 


### Return type

[**CompetitorDetails**](CompetitorDetails.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListCompetitors

> ListCompetitors200Response ListCompetitors(ctx).ProjectId(projectId).IncludeProjectBrand(includeProjectBrand).Output(output).Execute()

List competitors

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
	includeProjectBrand := true // bool | When true, prepends the project brand with actor_type=project and is_own=true (optional) (default to false)
	output := "output_example" // string | Rectangular output for BI tools (Tableau, Excel, Sheets, ELT). Omit for the default nested JSON. 'flat' returns the same metadata plus 'columns' and 'rows'; 'csv' returns those rows as text/csv. Errors are always returned as JSON. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CompetitorsAPI.ListCompetitors(context.Background()).ProjectId(projectId).IncludeProjectBrand(includeProjectBrand).Output(output).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CompetitorsAPI.ListCompetitors``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListCompetitors`: ListCompetitors200Response
	fmt.Fprintf(os.Stdout, "Response from `CompetitorsAPI.ListCompetitors`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListCompetitorsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **projectId** | **int32** | Project ID | 
 **includeProjectBrand** | **bool** | When true, prepends the project brand with actor_type&#x3D;project and is_own&#x3D;true | [default to false]
 **output** | **string** | Rectangular output for BI tools (Tableau, Excel, Sheets, ELT). Omit for the default nested JSON. &#39;flat&#39; returns the same metadata plus &#39;columns&#39; and &#39;rows&#39;; &#39;csv&#39; returns those rows as text/csv. Errors are always returned as JSON. | 

### Return type

[**ListCompetitors200Response**](ListCompetitors200Response.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateCompetitor

> UpdateCompetitor(ctx, id).UpdateCompetitorRequest(updateCompetitorRequest).Execute()

Update a competitor



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
	updateCompetitorRequest := *openapiclient.NewUpdateCompetitorRequest(int32(123)) // UpdateCompetitorRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.CompetitorsAPI.UpdateCompetitor(context.Background(), id).UpdateCompetitorRequest(updateCompetitorRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CompetitorsAPI.UpdateCompetitor``: %v\n", err)
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

Other parameters are passed through a pointer to a apiUpdateCompetitorRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **updateCompetitorRequest** | [**UpdateCompetitorRequest**](UpdateCompetitorRequest.md) |  | 

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

