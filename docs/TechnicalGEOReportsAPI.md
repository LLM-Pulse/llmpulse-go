# \TechnicalGEOReportsAPI

All URIs are relative to *https://api.llmpulse.ai/api/v1*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateTechnicalGeoReports**](TechnicalGEOReportsAPI.md#CreateTechnicalGeoReports) | **Post** /technical_geo_reports | Run technical GEO analysis
[**GetTechnicalGeoReport**](TechnicalGEOReportsAPI.md#GetTechnicalGeoReport) | **Get** /technical_geo_reports/{id} | Get a technical GEO report
[**ListTechnicalGeoReports**](TechnicalGEOReportsAPI.md#ListTechnicalGeoReports) | **Get** /technical_geo_reports | List technical GEO reports
[**RevertTechnicalGeoReportContent**](TechnicalGEOReportsAPI.md#RevertTechnicalGeoReportContent) | **Post** /technical_geo_reports/{id}/revert_content | Revert llms.txt report content
[**UpdateTechnicalGeoReportContent**](TechnicalGEOReportsAPI.md#UpdateTechnicalGeoReportContent) | **Patch** /technical_geo_reports/{id}/content | Edit llms.txt report content



## CreateTechnicalGeoReports

> CreateTechnicalGeoReports(ctx).CreateTechnicalGeoReportsRequest(createTechnicalGeoReportsRequest).Execute()

Run technical GEO analysis



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
	createTechnicalGeoReportsRequest := *openapiclient.NewCreateTechnicalGeoReportsRequest(int32(123), "Url_example") // CreateTechnicalGeoReportsRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.TechnicalGEOReportsAPI.CreateTechnicalGeoReports(context.Background()).CreateTechnicalGeoReportsRequest(createTechnicalGeoReportsRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TechnicalGEOReportsAPI.CreateTechnicalGeoReports``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateTechnicalGeoReportsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createTechnicalGeoReportsRequest** | [**CreateTechnicalGeoReportsRequest**](CreateTechnicalGeoReportsRequest.md) |  | 

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


## GetTechnicalGeoReport

> GetTechnicalGeoReport(ctx, id).ProjectId(projectId).ReportType(reportType).Execute()

Get a technical GEO report



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
	reportType := "reportType_example" // string | 
	id := int32(56) // int32 | Report id returned by POST /technical_geo_reports or GET /technical_geo_reports

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.TechnicalGEOReportsAPI.GetTechnicalGeoReport(context.Background(), id).ProjectId(projectId).ReportType(reportType).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TechnicalGEOReportsAPI.GetTechnicalGeoReport``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | Report id returned by POST /technical_geo_reports or GET /technical_geo_reports | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetTechnicalGeoReportRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **projectId** | **int32** | Project ID | 
 **reportType** | **string** |  | 


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


## ListTechnicalGeoReports

> ListTechnicalGeoReports(ctx).ProjectId(projectId).ReportType(reportType).Status(status).BatchId(batchId).Page(page).PerPage(perPage).Execute()

List technical GEO reports



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
	reportType := "reportType_example" // string | 
	status := "status_example" // string | Optional status filter; valid values depend on report_type (optional)
	batchId := int32(56) // int32 | Optional batch id returned when the report bundle was created (optional)
	page := int32(56) // int32 |  (optional) (default to 1)
	perPage := int32(56) // int32 |  (optional) (default to 20)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.TechnicalGEOReportsAPI.ListTechnicalGeoReports(context.Background()).ProjectId(projectId).ReportType(reportType).Status(status).BatchId(batchId).Page(page).PerPage(perPage).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TechnicalGEOReportsAPI.ListTechnicalGeoReports``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListTechnicalGeoReportsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **projectId** | **int32** | Project ID | 
 **reportType** | **string** |  | 
 **status** | **string** | Optional status filter; valid values depend on report_type | 
 **batchId** | **int32** | Optional batch id returned when the report bundle was created | 
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


## RevertTechnicalGeoReportContent

> LlmsTxtTechnicalGeoReport RevertTechnicalGeoReportContent(ctx, id).TechnicalGeoReportContentRevertRequest(technicalGeoReportContentRevertRequest).Execute()

Revert llms.txt report content



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
	id := int32(56) // int32 | Report id returned by POST /technical_geo_reports or GET /technical_geo_reports
	technicalGeoReportContentRevertRequest := *openapiclient.NewTechnicalGeoReportContentRevertRequest(int32(123), "ReportType_example") // TechnicalGeoReportContentRevertRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TechnicalGEOReportsAPI.RevertTechnicalGeoReportContent(context.Background(), id).TechnicalGeoReportContentRevertRequest(technicalGeoReportContentRevertRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TechnicalGEOReportsAPI.RevertTechnicalGeoReportContent``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RevertTechnicalGeoReportContent`: LlmsTxtTechnicalGeoReport
	fmt.Fprintf(os.Stdout, "Response from `TechnicalGEOReportsAPI.RevertTechnicalGeoReportContent`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | Report id returned by POST /technical_geo_reports or GET /technical_geo_reports | 

### Other Parameters

Other parameters are passed through a pointer to a apiRevertTechnicalGeoReportContentRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **technicalGeoReportContentRevertRequest** | [**TechnicalGeoReportContentRevertRequest**](TechnicalGeoReportContentRevertRequest.md) |  | 

### Return type

[**LlmsTxtTechnicalGeoReport**](LlmsTxtTechnicalGeoReport.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateTechnicalGeoReportContent

> TechnicalGeoReportContentUpdateResponse UpdateTechnicalGeoReportContent(ctx, id).TechnicalGeoReportContentUpdateRequest(technicalGeoReportContentUpdateRequest).Execute()

Edit llms.txt report content



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
	id := int32(56) // int32 | Report id returned by POST /technical_geo_reports or GET /technical_geo_reports
	technicalGeoReportContentUpdateRequest := *openapiclient.NewTechnicalGeoReportContentUpdateRequest(int32(123), "ReportType_example", "1790683200123456", *openapiclient.NewTechnicalGeoReportContentUpdateRequestEdits()) // TechnicalGeoReportContentUpdateRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TechnicalGEOReportsAPI.UpdateTechnicalGeoReportContent(context.Background(), id).TechnicalGeoReportContentUpdateRequest(technicalGeoReportContentUpdateRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TechnicalGEOReportsAPI.UpdateTechnicalGeoReportContent``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateTechnicalGeoReportContent`: TechnicalGeoReportContentUpdateResponse
	fmt.Fprintf(os.Stdout, "Response from `TechnicalGEOReportsAPI.UpdateTechnicalGeoReportContent`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | Report id returned by POST /technical_geo_reports or GET /technical_geo_reports | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateTechnicalGeoReportContentRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **technicalGeoReportContentUpdateRequest** | [**TechnicalGeoReportContentUpdateRequest**](TechnicalGeoReportContentUpdateRequest.md) |  | 

### Return type

[**TechnicalGeoReportContentUpdateResponse**](TechnicalGeoReportContentUpdateResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

