# \BingWebmasterToolsAPI

All URIs are relative to *https://api.llmpulse.ai/api/v1*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetBingWebmasterPages**](BingWebmasterToolsAPI.md#GetBingWebmasterPages) | **Get** /bing_webmaster/pages | Top Bing Webmaster Tools pages (Growth+)
[**GetBingWebmasterQueries**](BingWebmasterToolsAPI.md#GetBingWebmasterQueries) | **Get** /bing_webmaster/queries | Top Bing Webmaster Tools queries (Growth+)
[**GetBingWebmasterSummary**](BingWebmasterToolsAPI.md#GetBingWebmasterSummary) | **Get** /bing_webmaster/summary | Bing Webmaster Tools summary (Growth+)
[**GetBingWebmasterTimeseries**](BingWebmasterToolsAPI.md#GetBingWebmasterTimeseries) | **Get** /bing_webmaster/timeseries | Bing Webmaster Tools time series (Growth+)



## GetBingWebmasterPages

> BingWebmasterListResponse GetBingWebmasterPages(ctx).ProjectId(projectId).Range_(range_).From(from).To(to).Sort(sort).Page(page).PerPage(perPage).Output(output).Execute()

Top Bing Webmaster Tools pages (Growth+)



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
	range_ := int32(56) // int32 | Number of days to look back, today included (alternative to from/to, which win when both are given). At most 487, the window the Search Console endpoints accept; about 13 months of Bing data are kept. A value that is not a plain positive number returns 422 ERR_INVALID_PARAM even beside from/to. (optional)
	from := time.Now() // string | Start date (YYYY-MM-DD). Without from and to, the window is the last 30 days, today included; with only to, from is 30 days before today. (optional)
	to := time.Now() // string | End date (YYYY-MM-DD), inclusive. Defaults to today. data_through in the response says how far the synced data reaches. (optional)
	sort := "sort_example" // string | Sort key. impressions, clicks and ctr sort descending, the two positions ascending; rows without a value sort last. (optional) (default to "impressions")
	page := int32(56) // int32 |  (optional) (default to 1)
	perPage := int32(56) // int32 |  (optional) (default to 20)
	output := "output_example" // string | Rectangular output for BI tools (Tableau, Excel, Sheets, ELT). Omit for the default nested JSON. 'flat' returns the same metadata plus 'columns' and 'rows'; 'csv' returns those rows as text/csv. Errors are always returned as JSON. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.BingWebmasterToolsAPI.GetBingWebmasterPages(context.Background()).ProjectId(projectId).Range_(range_).From(from).To(to).Sort(sort).Page(page).PerPage(perPage).Output(output).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BingWebmasterToolsAPI.GetBingWebmasterPages``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetBingWebmasterPages`: BingWebmasterListResponse
	fmt.Fprintf(os.Stdout, "Response from `BingWebmasterToolsAPI.GetBingWebmasterPages`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetBingWebmasterPagesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **projectId** | **int32** | Project ID | 
 **range_** | **int32** | Number of days to look back, today included (alternative to from/to, which win when both are given). At most 487, the window the Search Console endpoints accept; about 13 months of Bing data are kept. A value that is not a plain positive number returns 422 ERR_INVALID_PARAM even beside from/to. | 
 **from** | **string** | Start date (YYYY-MM-DD). Without from and to, the window is the last 30 days, today included; with only to, from is 30 days before today. | 
 **to** | **string** | End date (YYYY-MM-DD), inclusive. Defaults to today. data_through in the response says how far the synced data reaches. | 
 **sort** | **string** | Sort key. impressions, clicks and ctr sort descending, the two positions ascending; rows without a value sort last. | [default to &quot;impressions&quot;]
 **page** | **int32** |  | [default to 1]
 **perPage** | **int32** |  | [default to 20]
 **output** | **string** | Rectangular output for BI tools (Tableau, Excel, Sheets, ELT). Omit for the default nested JSON. &#39;flat&#39; returns the same metadata plus &#39;columns&#39; and &#39;rows&#39;; &#39;csv&#39; returns those rows as text/csv. Errors are always returned as JSON. | 

### Return type

[**BingWebmasterListResponse**](BingWebmasterListResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetBingWebmasterQueries

> BingWebmasterListResponse GetBingWebmasterQueries(ctx).ProjectId(projectId).Range_(range_).From(from).To(to).Sort(sort).Page(page).PerPage(perPage).Output(output).Execute()

Top Bing Webmaster Tools queries (Growth+)



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
	range_ := int32(56) // int32 | Number of days to look back, today included (alternative to from/to, which win when both are given). At most 487, the window the Search Console endpoints accept; about 13 months of Bing data are kept. A value that is not a plain positive number returns 422 ERR_INVALID_PARAM even beside from/to. (optional)
	from := time.Now() // string | Start date (YYYY-MM-DD). Without from and to, the window is the last 30 days, today included; with only to, from is 30 days before today. (optional)
	to := time.Now() // string | End date (YYYY-MM-DD), inclusive. Defaults to today. data_through in the response says how far the synced data reaches. (optional)
	sort := "sort_example" // string | Sort key. impressions, clicks and ctr sort descending, the two positions ascending; rows without a value sort last. (optional) (default to "impressions")
	page := int32(56) // int32 |  (optional) (default to 1)
	perPage := int32(56) // int32 |  (optional) (default to 20)
	output := "output_example" // string | Rectangular output for BI tools (Tableau, Excel, Sheets, ELT). Omit for the default nested JSON. 'flat' returns the same metadata plus 'columns' and 'rows'; 'csv' returns those rows as text/csv. Errors are always returned as JSON. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.BingWebmasterToolsAPI.GetBingWebmasterQueries(context.Background()).ProjectId(projectId).Range_(range_).From(from).To(to).Sort(sort).Page(page).PerPage(perPage).Output(output).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BingWebmasterToolsAPI.GetBingWebmasterQueries``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetBingWebmasterQueries`: BingWebmasterListResponse
	fmt.Fprintf(os.Stdout, "Response from `BingWebmasterToolsAPI.GetBingWebmasterQueries`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetBingWebmasterQueriesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **projectId** | **int32** | Project ID | 
 **range_** | **int32** | Number of days to look back, today included (alternative to from/to, which win when both are given). At most 487, the window the Search Console endpoints accept; about 13 months of Bing data are kept. A value that is not a plain positive number returns 422 ERR_INVALID_PARAM even beside from/to. | 
 **from** | **string** | Start date (YYYY-MM-DD). Without from and to, the window is the last 30 days, today included; with only to, from is 30 days before today. | 
 **to** | **string** | End date (YYYY-MM-DD), inclusive. Defaults to today. data_through in the response says how far the synced data reaches. | 
 **sort** | **string** | Sort key. impressions, clicks and ctr sort descending, the two positions ascending; rows without a value sort last. | [default to &quot;impressions&quot;]
 **page** | **int32** |  | [default to 1]
 **perPage** | **int32** |  | [default to 20]
 **output** | **string** | Rectangular output for BI tools (Tableau, Excel, Sheets, ELT). Omit for the default nested JSON. &#39;flat&#39; returns the same metadata plus &#39;columns&#39; and &#39;rows&#39;; &#39;csv&#39; returns those rows as text/csv. Errors are always returned as JSON. | 

### Return type

[**BingWebmasterListResponse**](BingWebmasterListResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetBingWebmasterSummary

> BingWebmasterSummaryResponse GetBingWebmasterSummary(ctx).ProjectId(projectId).Range_(range_).From(from).To(to).Execute()

Bing Webmaster Tools summary (Growth+)



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
	range_ := int32(56) // int32 | Number of days to look back, today included (alternative to from/to, which win when both are given). At most 487, the window the Search Console endpoints accept; about 13 months of Bing data are kept. A value that is not a plain positive number returns 422 ERR_INVALID_PARAM even beside from/to. (optional)
	from := time.Now() // string | Start date (YYYY-MM-DD). Without from and to, the window is the last 30 days, today included; with only to, from is 30 days before today. (optional)
	to := time.Now() // string | End date (YYYY-MM-DD), inclusive. Defaults to today. data_through in the response says how far the synced data reaches. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.BingWebmasterToolsAPI.GetBingWebmasterSummary(context.Background()).ProjectId(projectId).Range_(range_).From(from).To(to).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BingWebmasterToolsAPI.GetBingWebmasterSummary``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetBingWebmasterSummary`: BingWebmasterSummaryResponse
	fmt.Fprintf(os.Stdout, "Response from `BingWebmasterToolsAPI.GetBingWebmasterSummary`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetBingWebmasterSummaryRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **projectId** | **int32** | Project ID | 
 **range_** | **int32** | Number of days to look back, today included (alternative to from/to, which win when both are given). At most 487, the window the Search Console endpoints accept; about 13 months of Bing data are kept. A value that is not a plain positive number returns 422 ERR_INVALID_PARAM even beside from/to. | 
 **from** | **string** | Start date (YYYY-MM-DD). Without from and to, the window is the last 30 days, today included; with only to, from is 30 days before today. | 
 **to** | **string** | End date (YYYY-MM-DD), inclusive. Defaults to today. data_through in the response says how far the synced data reaches. | 

### Return type

[**BingWebmasterSummaryResponse**](BingWebmasterSummaryResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetBingWebmasterTimeseries

> BingWebmasterTimeseriesResponse GetBingWebmasterTimeseries(ctx).ProjectId(projectId).Range_(range_).From(from).To(to).Granularity(granularity).Output(output).Execute()

Bing Webmaster Tools time series (Growth+)



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
	range_ := int32(56) // int32 | Number of days to look back, today included (alternative to from/to, which win when both are given). At most 487, the window the Search Console endpoints accept; about 13 months of Bing data are kept. A value that is not a plain positive number returns 422 ERR_INVALID_PARAM even beside from/to. (optional)
	from := time.Now() // string | Start date (YYYY-MM-DD). Without from and to, the window is the last 30 days, today included; with only to, from is 30 days before today. (optional)
	to := time.Now() // string | End date (YYYY-MM-DD), inclusive. Defaults to today. data_through in the response says how far the synced data reaches. (optional)
	granularity := "granularity_example" // string |  (optional)
	output := "output_example" // string | Rectangular output for BI tools (Tableau, Excel, Sheets, ELT). Omit for the default nested JSON. 'flat' returns the same metadata plus 'columns' and 'rows'; 'csv' returns those rows as text/csv. Errors are always returned as JSON. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.BingWebmasterToolsAPI.GetBingWebmasterTimeseries(context.Background()).ProjectId(projectId).Range_(range_).From(from).To(to).Granularity(granularity).Output(output).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BingWebmasterToolsAPI.GetBingWebmasterTimeseries``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetBingWebmasterTimeseries`: BingWebmasterTimeseriesResponse
	fmt.Fprintf(os.Stdout, "Response from `BingWebmasterToolsAPI.GetBingWebmasterTimeseries`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetBingWebmasterTimeseriesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **projectId** | **int32** | Project ID | 
 **range_** | **int32** | Number of days to look back, today included (alternative to from/to, which win when both are given). At most 487, the window the Search Console endpoints accept; about 13 months of Bing data are kept. A value that is not a plain positive number returns 422 ERR_INVALID_PARAM even beside from/to. | 
 **from** | **string** | Start date (YYYY-MM-DD). Without from and to, the window is the last 30 days, today included; with only to, from is 30 days before today. | 
 **to** | **string** | End date (YYYY-MM-DD), inclusive. Defaults to today. data_through in the response says how far the synced data reaches. | 
 **granularity** | **string** |  | 
 **output** | **string** | Rectangular output for BI tools (Tableau, Excel, Sheets, ELT). Omit for the default nested JSON. &#39;flat&#39; returns the same metadata plus &#39;columns&#39; and &#39;rows&#39;; &#39;csv&#39; returns those rows as text/csv. Errors are always returned as JSON. | 

### Return type

[**BingWebmasterTimeseriesResponse**](BingWebmasterTimeseriesResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

