# \GEOAuditsAPI

All URIs are relative to *https://api.llmpulse.ai/api/v1*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CompareGeoAuditRuns**](GEOAuditsAPI.md#CompareGeoAuditRuns) | **Get** /geo_audits/{id}/comparison | Compare two GEO audit runs
[**CreateGeoAudits**](GEOAuditsAPI.md#CreateGeoAudits) | **Post** /geo_audits | Create GEO audits
[**DeleteGeoAudit**](GEOAuditsAPI.md#DeleteGeoAudit) | **Delete** /geo_audits/{id} | Delete (archive) a GEO audit
[**GetGeoAudit**](GEOAuditsAPI.md#GetGeoAudit) | **Get** /geo_audits/{id} | Get a GEO audit
[**GetGeoAuditRun**](GEOAuditsAPI.md#GetGeoAuditRun) | **Get** /geo_audits/{geo_audit_id}/runs/{sequence} | Get a GEO audit run
[**ListGeoAlerts**](GEOAuditsAPI.md#ListGeoAlerts) | **Get** /geo_alerts | List GEO audit alerts
[**ListGeoAuditFindings**](GEOAuditsAPI.md#ListGeoAuditFindings) | **Get** /geo_audits/{geo_audit_id}/runs/{sequence}/findings | List the findings of a GEO audit run
[**ListGeoAuditIssues**](GEOAuditsAPI.md#ListGeoAuditIssues) | **Get** /geo_audits/{geo_audit_id}/issues | List the issues of a GEO audit
[**ListGeoAuditRuns**](GEOAuditsAPI.md#ListGeoAuditRuns) | **Get** /geo_audits/{geo_audit_id}/runs | List the runs of a GEO audit
[**ListGeoAudits**](GEOAuditsAPI.md#ListGeoAudits) | **Get** /geo_audits | List GEO audits
[**RunGeoAudit**](GEOAuditsAPI.md#RunGeoAudit) | **Post** /geo_audits/{geo_audit_id}/runs | Run a GEO audit now
[**UpdateGeoAudit**](GEOAuditsAPI.md#UpdateGeoAudit) | **Patch** /geo_audits/{id} | Update a GEO audit
[**UpdateGeoAuditIssue**](GEOAuditsAPI.md#UpdateGeoAuditIssue) | **Patch** /geo_audits/{geo_audit_id}/issues/{id} | Accept or reopen a GEO audit issue



## CompareGeoAuditRuns

> GeoAuditComparison CompareGeoAuditRuns(ctx, id).ProjectId(projectId).FromRun(fromRun).ToRun(toRun).Execute()

Compare two GEO audit runs

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
	id := "id_example" // string | Audit id
	fromRun := int32(56) // int32 | Run number to compare from (default the run before to_run) (optional)
	toRun := int32(56) // int32 | Run number to compare to (default the latest completed run) (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GEOAuditsAPI.CompareGeoAuditRuns(context.Background(), id).ProjectId(projectId).FromRun(fromRun).ToRun(toRun).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GEOAuditsAPI.CompareGeoAuditRuns``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CompareGeoAuditRuns`: GeoAuditComparison
	fmt.Fprintf(os.Stdout, "Response from `GEOAuditsAPI.CompareGeoAuditRuns`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | Audit id | 

### Other Parameters

Other parameters are passed through a pointer to a apiCompareGeoAuditRunsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **projectId** | **int32** | Project ID | 

 **fromRun** | **int32** | Run number to compare from (default the run before to_run) | 
 **toRun** | **int32** | Run number to compare to (default the latest completed run) | 

### Return type

[**GeoAuditComparison**](GeoAuditComparison.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CreateGeoAudits

> GeoAuditCreateResponse CreateGeoAudits(ctx).GeoAuditCreateRequest(geoAuditCreateRequest).Execute()

Create GEO audits



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
	geoAuditCreateRequest := *openapiclient.NewGeoAuditCreateRequest(int32(123), "Target_example", []string{"AuditTypes_example"}) // GeoAuditCreateRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GEOAuditsAPI.CreateGeoAudits(context.Background()).GeoAuditCreateRequest(geoAuditCreateRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GEOAuditsAPI.CreateGeoAudits``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateGeoAudits`: GeoAuditCreateResponse
	fmt.Fprintf(os.Stdout, "Response from `GEOAuditsAPI.CreateGeoAudits`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateGeoAuditsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **geoAuditCreateRequest** | [**GeoAuditCreateRequest**](GeoAuditCreateRequest.md) |  | 

### Return type

[**GeoAuditCreateResponse**](GeoAuditCreateResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteGeoAudit

> GeoAuditArchived DeleteGeoAudit(ctx, id).ProjectId(projectId).Execute()

Delete (archive) a GEO audit



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
	id := "id_example" // string | Audit id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GEOAuditsAPI.DeleteGeoAudit(context.Background(), id).ProjectId(projectId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GEOAuditsAPI.DeleteGeoAudit``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DeleteGeoAudit`: GeoAuditArchived
	fmt.Fprintf(os.Stdout, "Response from `GEOAuditsAPI.DeleteGeoAudit`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | Audit id | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteGeoAuditRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **projectId** | **int32** | Project ID | 


### Return type

[**GeoAuditArchived**](GeoAuditArchived.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetGeoAudit

> GeoAuditResponse GetGeoAudit(ctx, id).ProjectId(projectId).Execute()

Get a GEO audit

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
	id := "id_example" // string | Audit id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GEOAuditsAPI.GetGeoAudit(context.Background(), id).ProjectId(projectId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GEOAuditsAPI.GetGeoAudit``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetGeoAudit`: GeoAuditResponse
	fmt.Fprintf(os.Stdout, "Response from `GEOAuditsAPI.GetGeoAudit`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | Audit id | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetGeoAuditRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **projectId** | **int32** | Project ID | 


### Return type

[**GeoAuditResponse**](GeoAuditResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetGeoAuditRun

> GeoAuditRunDetail GetGeoAuditRun(ctx, geoAuditId, sequence).ProjectId(projectId).Execute()

Get a GEO audit run

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
	geoAuditId := "geoAuditId_example" // string | Audit id
	sequence := int32(56) // int32 | Run number within the audit

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GEOAuditsAPI.GetGeoAuditRun(context.Background(), geoAuditId, sequence).ProjectId(projectId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GEOAuditsAPI.GetGeoAuditRun``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetGeoAuditRun`: GeoAuditRunDetail
	fmt.Fprintf(os.Stdout, "Response from `GEOAuditsAPI.GetGeoAuditRun`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**geoAuditId** | **string** | Audit id | 
**sequence** | **int32** | Run number within the audit | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetGeoAuditRunRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **projectId** | **int32** | Project ID | 



### Return type

[**GeoAuditRunDetail**](GeoAuditRunDetail.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListGeoAlerts

> GeoAlertList ListGeoAlerts(ctx).ProjectId(projectId).AuditId(auditId).Page(page).PerPage(perPage).Execute()

List GEO audit alerts

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
	auditId := "auditId_example" // string | Only alerts of this audit (optional)
	page := int32(56) // int32 |  (optional) (default to 1)
	perPage := int32(56) // int32 |  (optional) (default to 20)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GEOAuditsAPI.ListGeoAlerts(context.Background()).ProjectId(projectId).AuditId(auditId).Page(page).PerPage(perPage).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GEOAuditsAPI.ListGeoAlerts``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListGeoAlerts`: GeoAlertList
	fmt.Fprintf(os.Stdout, "Response from `GEOAuditsAPI.ListGeoAlerts`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListGeoAlertsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **projectId** | **int32** | Project ID | 
 **auditId** | **string** | Only alerts of this audit | 
 **page** | **int32** |  | [default to 1]
 **perPage** | **int32** |  | [default to 20]

### Return type

[**GeoAlertList**](GeoAlertList.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListGeoAuditFindings

> GeoAuditFindingList ListGeoAuditFindings(ctx, geoAuditId, sequence).ProjectId(projectId).Page(page).PerPage(perPage).Output(output).Execute()

List the findings of a GEO audit run

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
	geoAuditId := "geoAuditId_example" // string | Audit id
	sequence := int32(56) // int32 | Run number within the audit
	page := int32(56) // int32 |  (optional) (default to 1)
	perPage := int32(56) // int32 |  (optional) (default to 20)
	output := "output_example" // string | Rectangular output for BI tools (Tableau, Excel, Sheets, ELT). Omit for the default nested JSON. 'flat' returns the same metadata plus 'columns' and 'rows'; 'csv' returns those rows as text/csv. Errors are always returned as JSON. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GEOAuditsAPI.ListGeoAuditFindings(context.Background(), geoAuditId, sequence).ProjectId(projectId).Page(page).PerPage(perPage).Output(output).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GEOAuditsAPI.ListGeoAuditFindings``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListGeoAuditFindings`: GeoAuditFindingList
	fmt.Fprintf(os.Stdout, "Response from `GEOAuditsAPI.ListGeoAuditFindings`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**geoAuditId** | **string** | Audit id | 
**sequence** | **int32** | Run number within the audit | 

### Other Parameters

Other parameters are passed through a pointer to a apiListGeoAuditFindingsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **projectId** | **int32** | Project ID | 


 **page** | **int32** |  | [default to 1]
 **perPage** | **int32** |  | [default to 20]
 **output** | **string** | Rectangular output for BI tools (Tableau, Excel, Sheets, ELT). Omit for the default nested JSON. &#39;flat&#39; returns the same metadata plus &#39;columns&#39; and &#39;rows&#39;; &#39;csv&#39; returns those rows as text/csv. Errors are always returned as JSON. | 

### Return type

[**GeoAuditFindingList**](GeoAuditFindingList.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListGeoAuditIssues

> GeoAuditIssueList ListGeoAuditIssues(ctx, geoAuditId).ProjectId(projectId).State(state).Page(page).PerPage(perPage).Execute()

List the issues of a GEO audit

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
	geoAuditId := "geoAuditId_example" // string | Audit id
	state := "state_example" // string | open means open and not accepted; default all (optional)
	page := int32(56) // int32 |  (optional) (default to 1)
	perPage := int32(56) // int32 |  (optional) (default to 20)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GEOAuditsAPI.ListGeoAuditIssues(context.Background(), geoAuditId).ProjectId(projectId).State(state).Page(page).PerPage(perPage).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GEOAuditsAPI.ListGeoAuditIssues``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListGeoAuditIssues`: GeoAuditIssueList
	fmt.Fprintf(os.Stdout, "Response from `GEOAuditsAPI.ListGeoAuditIssues`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**geoAuditId** | **string** | Audit id | 

### Other Parameters

Other parameters are passed through a pointer to a apiListGeoAuditIssuesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **projectId** | **int32** | Project ID | 

 **state** | **string** | open means open and not accepted; default all | 
 **page** | **int32** |  | [default to 1]
 **perPage** | **int32** |  | [default to 20]

### Return type

[**GeoAuditIssueList**](GeoAuditIssueList.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListGeoAuditRuns

> GeoAuditRunList ListGeoAuditRuns(ctx, geoAuditId).ProjectId(projectId).Page(page).PerPage(perPage).Output(output).Execute()

List the runs of a GEO audit

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
	geoAuditId := "geoAuditId_example" // string | Audit id
	page := int32(56) // int32 |  (optional) (default to 1)
	perPage := int32(56) // int32 |  (optional) (default to 20)
	output := "output_example" // string | Rectangular output for BI tools (Tableau, Excel, Sheets, ELT). Omit for the default nested JSON. 'flat' returns the same metadata plus 'columns' and 'rows'; 'csv' returns those rows as text/csv. Errors are always returned as JSON. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GEOAuditsAPI.ListGeoAuditRuns(context.Background(), geoAuditId).ProjectId(projectId).Page(page).PerPage(perPage).Output(output).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GEOAuditsAPI.ListGeoAuditRuns``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListGeoAuditRuns`: GeoAuditRunList
	fmt.Fprintf(os.Stdout, "Response from `GEOAuditsAPI.ListGeoAuditRuns`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**geoAuditId** | **string** | Audit id | 

### Other Parameters

Other parameters are passed through a pointer to a apiListGeoAuditRunsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **projectId** | **int32** | Project ID | 

 **page** | **int32** |  | [default to 1]
 **perPage** | **int32** |  | [default to 20]
 **output** | **string** | Rectangular output for BI tools (Tableau, Excel, Sheets, ELT). Omit for the default nested JSON. &#39;flat&#39; returns the same metadata plus &#39;columns&#39; and &#39;rows&#39;; &#39;csv&#39; returns those rows as text/csv. Errors are always returned as JSON. | 

### Return type

[**GeoAuditRunList**](GeoAuditRunList.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListGeoAudits

> GeoAuditList ListGeoAudits(ctx).ProjectId(projectId).AuditType(auditType).Status(status).Cadence(cadence).Page(page).PerPage(perPage).Execute()

List GEO audits



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
	auditType := "auditType_example" // string |  (optional)
	status := "status_example" // string |  (optional)
	cadence := "cadence_example" // string |  (optional)
	page := int32(56) // int32 |  (optional) (default to 1)
	perPage := int32(56) // int32 |  (optional) (default to 20)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GEOAuditsAPI.ListGeoAudits(context.Background()).ProjectId(projectId).AuditType(auditType).Status(status).Cadence(cadence).Page(page).PerPage(perPage).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GEOAuditsAPI.ListGeoAudits``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListGeoAudits`: GeoAuditList
	fmt.Fprintf(os.Stdout, "Response from `GEOAuditsAPI.ListGeoAudits`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListGeoAuditsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **projectId** | **int32** | Project ID | 
 **auditType** | **string** |  | 
 **status** | **string** |  | 
 **cadence** | **string** |  | 
 **page** | **int32** |  | [default to 1]
 **perPage** | **int32** |  | [default to 20]

### Return type

[**GeoAuditList**](GeoAuditList.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RunGeoAudit

> GeoAuditRunResponse RunGeoAudit(ctx, geoAuditId).ProjectId(projectId).Execute()

Run a GEO audit now



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
	geoAuditId := "geoAuditId_example" // string | Audit id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GEOAuditsAPI.RunGeoAudit(context.Background(), geoAuditId).ProjectId(projectId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GEOAuditsAPI.RunGeoAudit``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RunGeoAudit`: GeoAuditRunResponse
	fmt.Fprintf(os.Stdout, "Response from `GEOAuditsAPI.RunGeoAudit`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**geoAuditId** | **string** | Audit id | 

### Other Parameters

Other parameters are passed through a pointer to a apiRunGeoAuditRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **projectId** | **int32** | Project ID | 


### Return type

[**GeoAuditRunResponse**](GeoAuditRunResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateGeoAudit

> GeoAuditResponse UpdateGeoAudit(ctx, id).GeoAuditUpdateRequest(geoAuditUpdateRequest).Execute()

Update a GEO audit



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
	id := "id_example" // string | Audit id
	geoAuditUpdateRequest := *openapiclient.NewGeoAuditUpdateRequest() // GeoAuditUpdateRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GEOAuditsAPI.UpdateGeoAudit(context.Background(), id).GeoAuditUpdateRequest(geoAuditUpdateRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GEOAuditsAPI.UpdateGeoAudit``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateGeoAudit`: GeoAuditResponse
	fmt.Fprintf(os.Stdout, "Response from `GEOAuditsAPI.UpdateGeoAudit`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | Audit id | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateGeoAuditRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **geoAuditUpdateRequest** | [**GeoAuditUpdateRequest**](GeoAuditUpdateRequest.md) |  | 

### Return type

[**GeoAuditResponse**](GeoAuditResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateGeoAuditIssue

> GeoAuditIssueResponse UpdateGeoAuditIssue(ctx, geoAuditId, id).GeoAuditIssueUpdateRequest(geoAuditIssueUpdateRequest).Execute()

Accept or reopen a GEO audit issue



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
	geoAuditId := "geoAuditId_example" // string | Audit id
	id := int32(56) // int32 | Issue id
	geoAuditIssueUpdateRequest := *openapiclient.NewGeoAuditIssueUpdateRequest(false) // GeoAuditIssueUpdateRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GEOAuditsAPI.UpdateGeoAuditIssue(context.Background(), geoAuditId, id).GeoAuditIssueUpdateRequest(geoAuditIssueUpdateRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GEOAuditsAPI.UpdateGeoAuditIssue``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateGeoAuditIssue`: GeoAuditIssueResponse
	fmt.Fprintf(os.Stdout, "Response from `GEOAuditsAPI.UpdateGeoAuditIssue`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**geoAuditId** | **string** | Audit id | 
**id** | **int32** | Issue id | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateGeoAuditIssueRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **geoAuditIssueUpdateRequest** | [**GeoAuditIssueUpdateRequest**](GeoAuditIssueUpdateRequest.md) |  | 

### Return type

[**GeoAuditIssueResponse**](GeoAuditIssueResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

