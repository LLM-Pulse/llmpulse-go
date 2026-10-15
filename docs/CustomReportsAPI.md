# \CustomReportsAPI

All URIs are relative to *https://api.llmpulse.ai/api/v1*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetCustomReport**](CustomReportsAPI.md#GetCustomReport) | **Get** /custom_reports/{id} | Get a custom report with its widget data
[**ListCustomReports**](CustomReportsAPI.md#ListCustomReports) | **Get** /custom_reports | List custom reports
[**SendCustomReport**](CustomReportsAPI.md#SendCustomReport) | **Post** /custom_reports/{id}/send | Send a custom report now



## GetCustomReport

> CustomReportDetailResponse GetCustomReport(ctx, id).ProjectId(projectId).Execute()

Get a custom report with its widget data



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
	id := int32(56) // int32 | Custom report id, from GET /custom_reports

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CustomReportsAPI.GetCustomReport(context.Background(), id).ProjectId(projectId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CustomReportsAPI.GetCustomReport``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetCustomReport`: CustomReportDetailResponse
	fmt.Fprintf(os.Stdout, "Response from `CustomReportsAPI.GetCustomReport`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | Custom report id, from GET /custom_reports | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetCustomReportRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **projectId** | **int32** | Project ID | 


### Return type

[**CustomReportDetailResponse**](CustomReportDetailResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListCustomReports

> CustomReportsResponse ListCustomReports(ctx).ProjectId(projectId).Page(page).PerPage(perPage).Output(output).Execute()

List custom reports



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
	page := int32(56) // int32 |  (optional) (default to 1)
	perPage := int32(56) // int32 |  (optional) (default to 20)
	output := "output_example" // string | Rectangular output for BI tools (Tableau, Excel, Sheets, ELT). Omit for the default nested JSON. 'flat' returns the same metadata plus 'columns' and 'rows'; 'csv' returns those rows as text/csv. Errors are always returned as JSON. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CustomReportsAPI.ListCustomReports(context.Background()).ProjectId(projectId).Page(page).PerPage(perPage).Output(output).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CustomReportsAPI.ListCustomReports``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListCustomReports`: CustomReportsResponse
	fmt.Fprintf(os.Stdout, "Response from `CustomReportsAPI.ListCustomReports`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListCustomReportsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **projectId** | **int32** | Project ID | 
 **page** | **int32** |  | [default to 1]
 **perPage** | **int32** |  | [default to 20]
 **output** | **string** | Rectangular output for BI tools (Tableau, Excel, Sheets, ELT). Omit for the default nested JSON. &#39;flat&#39; returns the same metadata plus &#39;columns&#39; and &#39;rows&#39;; &#39;csv&#39; returns those rows as text/csv. Errors are always returned as JSON. | 

### Return type

[**CustomReportsResponse**](CustomReportsResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SendCustomReport

> CustomReportSendResponse SendCustomReport(ctx, id).SendCustomReportRequest(sendCustomReportRequest).Execute()

Send a custom report now



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
	id := int32(56) // int32 | Custom report id, from GET /custom_reports
	sendCustomReportRequest := *openapiclient.NewSendCustomReportRequest(int32(123)) // SendCustomReportRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CustomReportsAPI.SendCustomReport(context.Background(), id).SendCustomReportRequest(sendCustomReportRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CustomReportsAPI.SendCustomReport``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SendCustomReport`: CustomReportSendResponse
	fmt.Fprintf(os.Stdout, "Response from `CustomReportsAPI.SendCustomReport`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | Custom report id, from GET /custom_reports | 

### Other Parameters

Other parameters are passed through a pointer to a apiSendCustomReportRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **sendCustomReportRequest** | [**SendCustomReportRequest**](SendCustomReportRequest.md) |  | 

### Return type

[**CustomReportSendResponse**](CustomReportSendResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

