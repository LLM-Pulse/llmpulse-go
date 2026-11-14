# \SearchConsoleAPI

All URIs are relative to *https://api.llmpulse.ai/api/v1*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetSearchConsoleAiVisibilityGaps**](SearchConsoleAPI.md#GetSearchConsoleAiVisibilityGaps) | **Get** /search_console/ai_visibility_gaps | Search Console queries vs AI tracking (Growth+)
[**GetSearchConsoleBrandSplit**](SearchConsoleAPI.md#GetSearchConsoleBrandSplit) | **Get** /search_console/brand_split | Search Console branded vs non-branded split (Growth+)
[**GetSearchConsoleCannibalization**](SearchConsoleAPI.md#GetSearchConsoleCannibalization) | **Get** /search_console/cannibalization | Search Console keyword cannibalization (Growth+)
[**GetSearchConsoleDecay**](SearchConsoleAPI.md#GetSearchConsoleDecay) | **Get** /search_console/decay | Search Console content decay (Growth+)
[**GetSearchConsoleOpportunities**](SearchConsoleAPI.md#GetSearchConsoleOpportunities) | **Get** /search_console/opportunities | Search Console ranking opportunities (Growth+)
[**GetSearchConsolePages**](SearchConsoleAPI.md#GetSearchConsolePages) | **Get** /search_console/pages | Top Search Console pages (Growth+)
[**GetSearchConsoleQueries**](SearchConsoleAPI.md#GetSearchConsoleQueries) | **Get** /search_console/queries | Top Search Console queries (Growth+)
[**GetSearchConsoleRows**](SearchConsoleAPI.md#GetSearchConsoleRows) | **Get** /search_console/rows | Search Console rows by several dimensions (Growth+)
[**GetSearchConsoleSummary**](SearchConsoleAPI.md#GetSearchConsoleSummary) | **Get** /search_console/summary | Search Console summary (Growth+)
[**GetSearchConsoleTimeseries**](SearchConsoleAPI.md#GetSearchConsoleTimeseries) | **Get** /search_console/timeseries | Search Console time series (Growth+)
[**ListSearchConsoleProperties**](SearchConsoleAPI.md#ListSearchConsoleProperties) | **Get** /search_console/properties | List Search Console properties (Growth+)



## GetSearchConsoleAiVisibilityGaps

> SearchConsoleAiVisibilityGapsResponse GetSearchConsoleAiVisibilityGaps(ctx).ProjectId(projectId).Property(property).Range_(range_).From(from).To(to).MinImpressions(minImpressions).UnmatchedOnly(unmatchedOnly).Page(page).PerPage(perPage).Output(output).SearchType(searchType).Filters(filters).DataState(dataState).AggregationType(aggregationType).Execute()

Search Console queries vs AI tracking (Growth+)



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
	property := "all" // string | Which Search Console properties to read; /search_console/properties lists them. Omit it for the primary property, or pass one property id (e.g. sc-domain:example.com) to read that one; both answer with property. A comma-separated list of ids, or all, combines several and answers with properties, excluded_properties and property_errors instead: excluded_properties are left out because another selected property already counts them (a URL-prefix property under a domain property), so no click is counted twice; property_errors are properties Google refused, left out of the figures and also named in the X-Search-Console-Property-Errors header. When Google refuses every property, the request fails as a single-property read would. (optional)
	range_ := int32(56) // int32 | Number of days to look back, today included (alternative to from/to, which win when both are given). At most 487, Google's retention. A value that is not a plain positive number returns 422 ERR_INVALID_PARAM even beside from/to. (optional)
	from := time.Now() // string | Start date (YYYY-MM-DD). Defaults to 30 days ago. (optional)
	to := time.Now() // string | End date (YYYY-MM-DD), inclusive. Defaults to today. Google publishes data with a 2-3 day lag, so data_through in the response says how far it reaches. (optional)
	minImpressions := int32(56) // int32 | Smallest impressions a query needs. (optional) (default to 100)
	unmatchedOnly := true // bool | List only the queries no prompt of the project matches (true or false). (optional) (default to false)
	page := int32(56) // int32 |  (optional) (default to 1)
	perPage := int32(56) // int32 |  (optional) (default to 20)
	output := "output_example" // string | Rectangular output for BI tools (Tableau, Excel, Sheets, ELT). Omit for the default nested JSON. 'flat' returns the same metadata plus 'columns' and 'rows'; 'csv' returns those rows as text/csv. Errors are always returned as JSON. (optional)
	searchType := "searchType_example" // string | Which search surface to measure. Defaults to web. discover and googleNews carry no query dimension, so Google rejects /search_console/queries for them. (optional) (default to "web")
	filters := "[{\"dimension\":\"page\",\"operator\":\"contains\",\"expression\":\"/blog/\"}]" // string | Narrow the query; every entry must match (AND). Send the whole list as one JSON value: filters=[{\"dimension\":\"page\",\"operator\":\"contains\",\"expression\":\"/blog/\"}] (URL-encoded). An array of objects has no query-parameter form a generated client can produce, so the string is what the official SDKs send; see the SearchConsoleFilters schema for the shape it encodes. includingRegex and excludingRegex take RE2 syntax. At most 10 entries, expression at most 500 characters. The bracket form filters[][dimension]=page&filters[][operator]=contains&filters[][expression]=/blog/ is also accepted. (optional)
	dataState := "dataState_example" // string | final (default) counts only rows Google has finalized. all also counts the most recent days, which are still being filled in and will change. (optional) (default to "final")
	aggregationType := "aggregationType_example" // string | How Google counts impressions. auto (default) is what Search Console shows (by page when page is grouped or filtered, else by property). Google rejects byProperty with a page dimension or filter. (optional) (default to "auto")

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SearchConsoleAPI.GetSearchConsoleAiVisibilityGaps(context.Background()).ProjectId(projectId).Property(property).Range_(range_).From(from).To(to).MinImpressions(minImpressions).UnmatchedOnly(unmatchedOnly).Page(page).PerPage(perPage).Output(output).SearchType(searchType).Filters(filters).DataState(dataState).AggregationType(aggregationType).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SearchConsoleAPI.GetSearchConsoleAiVisibilityGaps``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetSearchConsoleAiVisibilityGaps`: SearchConsoleAiVisibilityGapsResponse
	fmt.Fprintf(os.Stdout, "Response from `SearchConsoleAPI.GetSearchConsoleAiVisibilityGaps`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetSearchConsoleAiVisibilityGapsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **projectId** | **int32** | Project ID | 
 **property** | **string** | Which Search Console properties to read; /search_console/properties lists them. Omit it for the primary property, or pass one property id (e.g. sc-domain:example.com) to read that one; both answer with property. A comma-separated list of ids, or all, combines several and answers with properties, excluded_properties and property_errors instead: excluded_properties are left out because another selected property already counts them (a URL-prefix property under a domain property), so no click is counted twice; property_errors are properties Google refused, left out of the figures and also named in the X-Search-Console-Property-Errors header. When Google refuses every property, the request fails as a single-property read would. | 
 **range_** | **int32** | Number of days to look back, today included (alternative to from/to, which win when both are given). At most 487, Google&#39;s retention. A value that is not a plain positive number returns 422 ERR_INVALID_PARAM even beside from/to. | 
 **from** | **string** | Start date (YYYY-MM-DD). Defaults to 30 days ago. | 
 **to** | **string** | End date (YYYY-MM-DD), inclusive. Defaults to today. Google publishes data with a 2-3 day lag, so data_through in the response says how far it reaches. | 
 **minImpressions** | **int32** | Smallest impressions a query needs. | [default to 100]
 **unmatchedOnly** | **bool** | List only the queries no prompt of the project matches (true or false). | [default to false]
 **page** | **int32** |  | [default to 1]
 **perPage** | **int32** |  | [default to 20]
 **output** | **string** | Rectangular output for BI tools (Tableau, Excel, Sheets, ELT). Omit for the default nested JSON. &#39;flat&#39; returns the same metadata plus &#39;columns&#39; and &#39;rows&#39;; &#39;csv&#39; returns those rows as text/csv. Errors are always returned as JSON. | 
 **searchType** | **string** | Which search surface to measure. Defaults to web. discover and googleNews carry no query dimension, so Google rejects /search_console/queries for them. | [default to &quot;web&quot;]
 **filters** | **string** | Narrow the query; every entry must match (AND). Send the whole list as one JSON value: filters&#x3D;[{\&quot;dimension\&quot;:\&quot;page\&quot;,\&quot;operator\&quot;:\&quot;contains\&quot;,\&quot;expression\&quot;:\&quot;/blog/\&quot;}] (URL-encoded). An array of objects has no query-parameter form a generated client can produce, so the string is what the official SDKs send; see the SearchConsoleFilters schema for the shape it encodes. includingRegex and excludingRegex take RE2 syntax. At most 10 entries, expression at most 500 characters. The bracket form filters[][dimension]&#x3D;page&amp;filters[][operator]&#x3D;contains&amp;filters[][expression]&#x3D;/blog/ is also accepted. | 
 **dataState** | **string** | final (default) counts only rows Google has finalized. all also counts the most recent days, which are still being filled in and will change. | [default to &quot;final&quot;]
 **aggregationType** | **string** | How Google counts impressions. auto (default) is what Search Console shows (by page when page is grouped or filtered, else by property). Google rejects byProperty with a page dimension or filter. | [default to &quot;auto&quot;]

### Return type

[**SearchConsoleAiVisibilityGapsResponse**](SearchConsoleAiVisibilityGapsResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetSearchConsoleBrandSplit

> SearchConsoleBrandSplitResponse GetSearchConsoleBrandSplit(ctx).ProjectId(projectId).Property(property).Range_(range_).From(from).To(to).SearchType(searchType).Filters(filters).DataState(dataState).AggregationType(aggregationType).Execute()

Search Console branded vs non-branded split (Growth+)



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
	property := "all" // string | Which Search Console properties to read; /search_console/properties lists them. Omit it for the primary property, or pass one property id (e.g. sc-domain:example.com) to read that one; both answer with property. A comma-separated list of ids, or all, combines several and answers with properties, excluded_properties and property_errors instead: excluded_properties are left out because another selected property already counts them (a URL-prefix property under a domain property), so no click is counted twice; property_errors are properties Google refused, left out of the figures and also named in the X-Search-Console-Property-Errors header. When Google refuses every property, the request fails as a single-property read would. (optional)
	range_ := int32(56) // int32 | Number of days to look back, today included (alternative to from/to, which win when both are given). At most 487, Google's retention. A value that is not a plain positive number returns 422 ERR_INVALID_PARAM even beside from/to. (optional)
	from := time.Now() // string | Start date (YYYY-MM-DD). Defaults to 30 days ago. (optional)
	to := time.Now() // string | End date (YYYY-MM-DD), inclusive. Defaults to today. Google publishes data with a 2-3 day lag, so data_through in the response says how far it reaches. (optional)
	searchType := "searchType_example" // string | Which search surface to measure. Defaults to web. discover and googleNews carry no query dimension, so Google rejects /search_console/queries for them. (optional) (default to "web")
	filters := "[{\"dimension\":\"page\",\"operator\":\"contains\",\"expression\":\"/blog/\"}]" // string | Narrow the query; every entry must match (AND). Send the whole list as one JSON value: filters=[{\"dimension\":\"page\",\"operator\":\"contains\",\"expression\":\"/blog/\"}] (URL-encoded). An array of objects has no query-parameter form a generated client can produce, so the string is what the official SDKs send; see the SearchConsoleFilters schema for the shape it encodes. includingRegex and excludingRegex take RE2 syntax. At most 10 entries, expression at most 500 characters. The bracket form filters[][dimension]=page&filters[][operator]=contains&filters[][expression]=/blog/ is also accepted. (optional)
	dataState := "dataState_example" // string | final (default) counts only rows Google has finalized. all also counts the most recent days, which are still being filled in and will change. (optional) (default to "final")
	aggregationType := "aggregationType_example" // string | How Google counts impressions. auto (default) is what Search Console shows (by page when page is grouped or filtered, else by property). Google rejects byProperty with a page dimension or filter. (optional) (default to "auto")

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SearchConsoleAPI.GetSearchConsoleBrandSplit(context.Background()).ProjectId(projectId).Property(property).Range_(range_).From(from).To(to).SearchType(searchType).Filters(filters).DataState(dataState).AggregationType(aggregationType).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SearchConsoleAPI.GetSearchConsoleBrandSplit``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetSearchConsoleBrandSplit`: SearchConsoleBrandSplitResponse
	fmt.Fprintf(os.Stdout, "Response from `SearchConsoleAPI.GetSearchConsoleBrandSplit`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetSearchConsoleBrandSplitRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **projectId** | **int32** | Project ID | 
 **property** | **string** | Which Search Console properties to read; /search_console/properties lists them. Omit it for the primary property, or pass one property id (e.g. sc-domain:example.com) to read that one; both answer with property. A comma-separated list of ids, or all, combines several and answers with properties, excluded_properties and property_errors instead: excluded_properties are left out because another selected property already counts them (a URL-prefix property under a domain property), so no click is counted twice; property_errors are properties Google refused, left out of the figures and also named in the X-Search-Console-Property-Errors header. When Google refuses every property, the request fails as a single-property read would. | 
 **range_** | **int32** | Number of days to look back, today included (alternative to from/to, which win when both are given). At most 487, Google&#39;s retention. A value that is not a plain positive number returns 422 ERR_INVALID_PARAM even beside from/to. | 
 **from** | **string** | Start date (YYYY-MM-DD). Defaults to 30 days ago. | 
 **to** | **string** | End date (YYYY-MM-DD), inclusive. Defaults to today. Google publishes data with a 2-3 day lag, so data_through in the response says how far it reaches. | 
 **searchType** | **string** | Which search surface to measure. Defaults to web. discover and googleNews carry no query dimension, so Google rejects /search_console/queries for them. | [default to &quot;web&quot;]
 **filters** | **string** | Narrow the query; every entry must match (AND). Send the whole list as one JSON value: filters&#x3D;[{\&quot;dimension\&quot;:\&quot;page\&quot;,\&quot;operator\&quot;:\&quot;contains\&quot;,\&quot;expression\&quot;:\&quot;/blog/\&quot;}] (URL-encoded). An array of objects has no query-parameter form a generated client can produce, so the string is what the official SDKs send; see the SearchConsoleFilters schema for the shape it encodes. includingRegex and excludingRegex take RE2 syntax. At most 10 entries, expression at most 500 characters. The bracket form filters[][dimension]&#x3D;page&amp;filters[][operator]&#x3D;contains&amp;filters[][expression]&#x3D;/blog/ is also accepted. | 
 **dataState** | **string** | final (default) counts only rows Google has finalized. all also counts the most recent days, which are still being filled in and will change. | [default to &quot;final&quot;]
 **aggregationType** | **string** | How Google counts impressions. auto (default) is what Search Console shows (by page when page is grouped or filtered, else by property). Google rejects byProperty with a page dimension or filter. | [default to &quot;auto&quot;]

### Return type

[**SearchConsoleBrandSplitResponse**](SearchConsoleBrandSplitResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetSearchConsoleCannibalization

> SearchConsoleCannibalizationResponse GetSearchConsoleCannibalization(ctx).ProjectId(projectId).Property(property).Range_(range_).From(from).To(to).MinImpressions(minImpressions).MinShare(minShare).Page(page).PerPage(perPage).Output(output).SearchType(searchType).Filters(filters).DataState(dataState).AggregationType(aggregationType).Execute()

Search Console keyword cannibalization (Growth+)



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
	property := "all" // string | Which Search Console properties to read; /search_console/properties lists them. Omit it for the primary property, or pass one property id (e.g. sc-domain:example.com) to read that one; both answer with property. A comma-separated list of ids, or all, combines several and answers with properties, excluded_properties and property_errors instead: excluded_properties are left out because another selected property already counts them (a URL-prefix property under a domain property), so no click is counted twice; property_errors are properties Google refused, left out of the figures and also named in the X-Search-Console-Property-Errors header. When Google refuses every property, the request fails as a single-property read would. (optional)
	range_ := int32(56) // int32 | Number of days to look back, today included (alternative to from/to, which win when both are given). At most 487, Google's retention. A value that is not a plain positive number returns 422 ERR_INVALID_PARAM even beside from/to. (optional)
	from := time.Now() // string | Start date (YYYY-MM-DD). Defaults to 30 days ago. (optional)
	to := time.Now() // string | End date (YYYY-MM-DD), inclusive. Defaults to today. Google publishes data with a 2-3 day lag, so data_through in the response says how far it reaches. (optional)
	minImpressions := int32(56) // int32 | Smallest impressions a query needs. (optional) (default to 100)
	minShare := float32(8.14) // float32 | Smallest fraction (0.01 to 0.5) of the query's impressions a page needs to count as competing. (optional) (default to 0.1)
	page := int32(56) // int32 |  (optional) (default to 1)
	perPage := int32(56) // int32 |  (optional) (default to 20)
	output := "output_example" // string | Rectangular output for BI tools (Tableau, Excel, Sheets, ELT). Omit for the default nested JSON. 'flat' returns the same metadata plus 'columns' and 'rows'; 'csv' returns those rows as text/csv. Errors are always returned as JSON. (optional)
	searchType := "searchType_example" // string | Which search surface to measure. Defaults to web. discover and googleNews carry no query dimension, so Google rejects /search_console/queries for them. (optional) (default to "web")
	filters := "[{\"dimension\":\"page\",\"operator\":\"contains\",\"expression\":\"/blog/\"}]" // string | Narrow the query; every entry must match (AND). Send the whole list as one JSON value: filters=[{\"dimension\":\"page\",\"operator\":\"contains\",\"expression\":\"/blog/\"}] (URL-encoded). An array of objects has no query-parameter form a generated client can produce, so the string is what the official SDKs send; see the SearchConsoleFilters schema for the shape it encodes. includingRegex and excludingRegex take RE2 syntax. At most 10 entries, expression at most 500 characters. The bracket form filters[][dimension]=page&filters[][operator]=contains&filters[][expression]=/blog/ is also accepted. (optional)
	dataState := "dataState_example" // string | final (default) counts only rows Google has finalized. all also counts the most recent days, which are still being filled in and will change. (optional) (default to "final")
	aggregationType := "aggregationType_example" // string | How Google counts impressions. auto (default) is what Search Console shows (by page when page is grouped or filtered, else by property). Google rejects byProperty with a page dimension or filter. (optional) (default to "auto")

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SearchConsoleAPI.GetSearchConsoleCannibalization(context.Background()).ProjectId(projectId).Property(property).Range_(range_).From(from).To(to).MinImpressions(minImpressions).MinShare(minShare).Page(page).PerPage(perPage).Output(output).SearchType(searchType).Filters(filters).DataState(dataState).AggregationType(aggregationType).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SearchConsoleAPI.GetSearchConsoleCannibalization``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetSearchConsoleCannibalization`: SearchConsoleCannibalizationResponse
	fmt.Fprintf(os.Stdout, "Response from `SearchConsoleAPI.GetSearchConsoleCannibalization`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetSearchConsoleCannibalizationRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **projectId** | **int32** | Project ID | 
 **property** | **string** | Which Search Console properties to read; /search_console/properties lists them. Omit it for the primary property, or pass one property id (e.g. sc-domain:example.com) to read that one; both answer with property. A comma-separated list of ids, or all, combines several and answers with properties, excluded_properties and property_errors instead: excluded_properties are left out because another selected property already counts them (a URL-prefix property under a domain property), so no click is counted twice; property_errors are properties Google refused, left out of the figures and also named in the X-Search-Console-Property-Errors header. When Google refuses every property, the request fails as a single-property read would. | 
 **range_** | **int32** | Number of days to look back, today included (alternative to from/to, which win when both are given). At most 487, Google&#39;s retention. A value that is not a plain positive number returns 422 ERR_INVALID_PARAM even beside from/to. | 
 **from** | **string** | Start date (YYYY-MM-DD). Defaults to 30 days ago. | 
 **to** | **string** | End date (YYYY-MM-DD), inclusive. Defaults to today. Google publishes data with a 2-3 day lag, so data_through in the response says how far it reaches. | 
 **minImpressions** | **int32** | Smallest impressions a query needs. | [default to 100]
 **minShare** | **float32** | Smallest fraction (0.01 to 0.5) of the query&#39;s impressions a page needs to count as competing. | [default to 0.1]
 **page** | **int32** |  | [default to 1]
 **perPage** | **int32** |  | [default to 20]
 **output** | **string** | Rectangular output for BI tools (Tableau, Excel, Sheets, ELT). Omit for the default nested JSON. &#39;flat&#39; returns the same metadata plus &#39;columns&#39; and &#39;rows&#39;; &#39;csv&#39; returns those rows as text/csv. Errors are always returned as JSON. | 
 **searchType** | **string** | Which search surface to measure. Defaults to web. discover and googleNews carry no query dimension, so Google rejects /search_console/queries for them. | [default to &quot;web&quot;]
 **filters** | **string** | Narrow the query; every entry must match (AND). Send the whole list as one JSON value: filters&#x3D;[{\&quot;dimension\&quot;:\&quot;page\&quot;,\&quot;operator\&quot;:\&quot;contains\&quot;,\&quot;expression\&quot;:\&quot;/blog/\&quot;}] (URL-encoded). An array of objects has no query-parameter form a generated client can produce, so the string is what the official SDKs send; see the SearchConsoleFilters schema for the shape it encodes. includingRegex and excludingRegex take RE2 syntax. At most 10 entries, expression at most 500 characters. The bracket form filters[][dimension]&#x3D;page&amp;filters[][operator]&#x3D;contains&amp;filters[][expression]&#x3D;/blog/ is also accepted. | 
 **dataState** | **string** | final (default) counts only rows Google has finalized. all also counts the most recent days, which are still being filled in and will change. | [default to &quot;final&quot;]
 **aggregationType** | **string** | How Google counts impressions. auto (default) is what Search Console shows (by page when page is grouped or filtered, else by property). Google rejects byProperty with a page dimension or filter. | [default to &quot;auto&quot;]

### Return type

[**SearchConsoleCannibalizationResponse**](SearchConsoleCannibalizationResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetSearchConsoleDecay

> SearchConsoleDecayResponse GetSearchConsoleDecay(ctx).ProjectId(projectId).Property(property).Range_(range_).From(from).To(to).Dimension(dimension).MinClicks(minClicks).Page(page).PerPage(perPage).Output(output).SearchType(searchType).Filters(filters).DataState(dataState).AggregationType(aggregationType).Execute()

Search Console content decay (Growth+)



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
	property := "all" // string | Which Search Console properties to read; /search_console/properties lists them. Omit it for the primary property, or pass one property id (e.g. sc-domain:example.com) to read that one; both answer with property. A comma-separated list of ids, or all, combines several and answers with properties, excluded_properties and property_errors instead: excluded_properties are left out because another selected property already counts them (a URL-prefix property under a domain property), so no click is counted twice; property_errors are properties Google refused, left out of the figures and also named in the X-Search-Console-Property-Errors header. When Google refuses every property, the request fails as a single-property read would. (optional)
	range_ := int32(56) // int32 | Number of days to look back, today included (alternative to from/to, which win when both are given). At most 487, Google's retention. A value that is not a plain positive number returns 422 ERR_INVALID_PARAM even beside from/to. (optional)
	from := time.Now() // string | Start date (YYYY-MM-DD). Defaults to 30 days ago. (optional)
	to := time.Now() // string | End date (YYYY-MM-DD), inclusive. Defaults to today. Google publishes data with a 2-3 day lag, so data_through in the response says how far it reaches. (optional)
	dimension := "dimension_example" // string | Compare pages or queries. (optional) (default to "page")
	minClicks := int32(56) // int32 | Smallest clicks in the previous window. (optional) (default to 10)
	page := int32(56) // int32 |  (optional) (default to 1)
	perPage := int32(56) // int32 |  (optional) (default to 20)
	output := "output_example" // string | Rectangular output for BI tools (Tableau, Excel, Sheets, ELT). Omit for the default nested JSON. 'flat' returns the same metadata plus 'columns' and 'rows'; 'csv' returns those rows as text/csv. Errors are always returned as JSON. (optional)
	searchType := "searchType_example" // string | Which search surface to measure. Defaults to web. discover and googleNews carry no query dimension, so Google rejects /search_console/queries for them. (optional) (default to "web")
	filters := "[{\"dimension\":\"page\",\"operator\":\"contains\",\"expression\":\"/blog/\"}]" // string | Narrow the query; every entry must match (AND). Send the whole list as one JSON value: filters=[{\"dimension\":\"page\",\"operator\":\"contains\",\"expression\":\"/blog/\"}] (URL-encoded). An array of objects has no query-parameter form a generated client can produce, so the string is what the official SDKs send; see the SearchConsoleFilters schema for the shape it encodes. includingRegex and excludingRegex take RE2 syntax. At most 10 entries, expression at most 500 characters. The bracket form filters[][dimension]=page&filters[][operator]=contains&filters[][expression]=/blog/ is also accepted. (optional)
	dataState := "dataState_example" // string | final (default) counts only rows Google has finalized. all also counts the most recent days, which are still being filled in and will change. (optional) (default to "final")
	aggregationType := "aggregationType_example" // string | How Google counts impressions. auto (default) is what Search Console shows (by page when page is grouped or filtered, else by property). Google rejects byProperty with a page dimension or filter. (optional) (default to "auto")

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SearchConsoleAPI.GetSearchConsoleDecay(context.Background()).ProjectId(projectId).Property(property).Range_(range_).From(from).To(to).Dimension(dimension).MinClicks(minClicks).Page(page).PerPage(perPage).Output(output).SearchType(searchType).Filters(filters).DataState(dataState).AggregationType(aggregationType).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SearchConsoleAPI.GetSearchConsoleDecay``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetSearchConsoleDecay`: SearchConsoleDecayResponse
	fmt.Fprintf(os.Stdout, "Response from `SearchConsoleAPI.GetSearchConsoleDecay`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetSearchConsoleDecayRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **projectId** | **int32** | Project ID | 
 **property** | **string** | Which Search Console properties to read; /search_console/properties lists them. Omit it for the primary property, or pass one property id (e.g. sc-domain:example.com) to read that one; both answer with property. A comma-separated list of ids, or all, combines several and answers with properties, excluded_properties and property_errors instead: excluded_properties are left out because another selected property already counts them (a URL-prefix property under a domain property), so no click is counted twice; property_errors are properties Google refused, left out of the figures and also named in the X-Search-Console-Property-Errors header. When Google refuses every property, the request fails as a single-property read would. | 
 **range_** | **int32** | Number of days to look back, today included (alternative to from/to, which win when both are given). At most 487, Google&#39;s retention. A value that is not a plain positive number returns 422 ERR_INVALID_PARAM even beside from/to. | 
 **from** | **string** | Start date (YYYY-MM-DD). Defaults to 30 days ago. | 
 **to** | **string** | End date (YYYY-MM-DD), inclusive. Defaults to today. Google publishes data with a 2-3 day lag, so data_through in the response says how far it reaches. | 
 **dimension** | **string** | Compare pages or queries. | [default to &quot;page&quot;]
 **minClicks** | **int32** | Smallest clicks in the previous window. | [default to 10]
 **page** | **int32** |  | [default to 1]
 **perPage** | **int32** |  | [default to 20]
 **output** | **string** | Rectangular output for BI tools (Tableau, Excel, Sheets, ELT). Omit for the default nested JSON. &#39;flat&#39; returns the same metadata plus &#39;columns&#39; and &#39;rows&#39;; &#39;csv&#39; returns those rows as text/csv. Errors are always returned as JSON. | 
 **searchType** | **string** | Which search surface to measure. Defaults to web. discover and googleNews carry no query dimension, so Google rejects /search_console/queries for them. | [default to &quot;web&quot;]
 **filters** | **string** | Narrow the query; every entry must match (AND). Send the whole list as one JSON value: filters&#x3D;[{\&quot;dimension\&quot;:\&quot;page\&quot;,\&quot;operator\&quot;:\&quot;contains\&quot;,\&quot;expression\&quot;:\&quot;/blog/\&quot;}] (URL-encoded). An array of objects has no query-parameter form a generated client can produce, so the string is what the official SDKs send; see the SearchConsoleFilters schema for the shape it encodes. includingRegex and excludingRegex take RE2 syntax. At most 10 entries, expression at most 500 characters. The bracket form filters[][dimension]&#x3D;page&amp;filters[][operator]&#x3D;contains&amp;filters[][expression]&#x3D;/blog/ is also accepted. | 
 **dataState** | **string** | final (default) counts only rows Google has finalized. all also counts the most recent days, which are still being filled in and will change. | [default to &quot;final&quot;]
 **aggregationType** | **string** | How Google counts impressions. auto (default) is what Search Console shows (by page when page is grouped or filtered, else by property). Google rejects byProperty with a page dimension or filter. | [default to &quot;auto&quot;]

### Return type

[**SearchConsoleDecayResponse**](SearchConsoleDecayResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetSearchConsoleOpportunities

> SearchConsoleOpportunitiesResponse GetSearchConsoleOpportunities(ctx).ProjectId(projectId).Property(property).Range_(range_).From(from).To(to).MinImpressions(minImpressions).MinPosition(minPosition).MaxPosition(maxPosition).Page(page).PerPage(perPage).Output(output).SearchType(searchType).Filters(filters).DataState(dataState).AggregationType(aggregationType).Execute()

Search Console ranking opportunities (Growth+)



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
	property := "all" // string | Which Search Console properties to read; /search_console/properties lists them. Omit it for the primary property, or pass one property id (e.g. sc-domain:example.com) to read that one; both answer with property. A comma-separated list of ids, or all, combines several and answers with properties, excluded_properties and property_errors instead: excluded_properties are left out because another selected property already counts them (a URL-prefix property under a domain property), so no click is counted twice; property_errors are properties Google refused, left out of the figures and also named in the X-Search-Console-Property-Errors header. When Google refuses every property, the request fails as a single-property read would. (optional)
	range_ := int32(56) // int32 | Number of days to look back, today included (alternative to from/to, which win when both are given). At most 487, Google's retention. A value that is not a plain positive number returns 422 ERR_INVALID_PARAM even beside from/to. (optional)
	from := time.Now() // string | Start date (YYYY-MM-DD). Defaults to 30 days ago. (optional)
	to := time.Now() // string | End date (YYYY-MM-DD), inclusive. Defaults to today. Google publishes data with a 2-3 day lag, so data_through in the response says how far it reaches. (optional)
	minImpressions := int32(56) // int32 | Smallest impressions a query needs. (optional) (default to 100)
	minPosition := float32(8.14) // float32 | Best average position to include. (optional) (default to 4)
	maxPosition := float32(8.14) // float32 | Worst average position to include; at least min_position. (optional) (default to 20)
	page := int32(56) // int32 |  (optional) (default to 1)
	perPage := int32(56) // int32 |  (optional) (default to 20)
	output := "output_example" // string | Rectangular output for BI tools (Tableau, Excel, Sheets, ELT). Omit for the default nested JSON. 'flat' returns the same metadata plus 'columns' and 'rows'; 'csv' returns those rows as text/csv. Errors are always returned as JSON. (optional)
	searchType := "searchType_example" // string | Which search surface to measure. Defaults to web. discover and googleNews carry no query dimension, so Google rejects /search_console/queries for them. (optional) (default to "web")
	filters := "[{\"dimension\":\"page\",\"operator\":\"contains\",\"expression\":\"/blog/\"}]" // string | Narrow the query; every entry must match (AND). Send the whole list as one JSON value: filters=[{\"dimension\":\"page\",\"operator\":\"contains\",\"expression\":\"/blog/\"}] (URL-encoded). An array of objects has no query-parameter form a generated client can produce, so the string is what the official SDKs send; see the SearchConsoleFilters schema for the shape it encodes. includingRegex and excludingRegex take RE2 syntax. At most 10 entries, expression at most 500 characters. The bracket form filters[][dimension]=page&filters[][operator]=contains&filters[][expression]=/blog/ is also accepted. (optional)
	dataState := "dataState_example" // string | final (default) counts only rows Google has finalized. all also counts the most recent days, which are still being filled in and will change. (optional) (default to "final")
	aggregationType := "aggregationType_example" // string | How Google counts impressions. auto (default) is what Search Console shows (by page when page is grouped or filtered, else by property). Google rejects byProperty with a page dimension or filter. (optional) (default to "auto")

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SearchConsoleAPI.GetSearchConsoleOpportunities(context.Background()).ProjectId(projectId).Property(property).Range_(range_).From(from).To(to).MinImpressions(minImpressions).MinPosition(minPosition).MaxPosition(maxPosition).Page(page).PerPage(perPage).Output(output).SearchType(searchType).Filters(filters).DataState(dataState).AggregationType(aggregationType).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SearchConsoleAPI.GetSearchConsoleOpportunities``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetSearchConsoleOpportunities`: SearchConsoleOpportunitiesResponse
	fmt.Fprintf(os.Stdout, "Response from `SearchConsoleAPI.GetSearchConsoleOpportunities`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetSearchConsoleOpportunitiesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **projectId** | **int32** | Project ID | 
 **property** | **string** | Which Search Console properties to read; /search_console/properties lists them. Omit it for the primary property, or pass one property id (e.g. sc-domain:example.com) to read that one; both answer with property. A comma-separated list of ids, or all, combines several and answers with properties, excluded_properties and property_errors instead: excluded_properties are left out because another selected property already counts them (a URL-prefix property under a domain property), so no click is counted twice; property_errors are properties Google refused, left out of the figures and also named in the X-Search-Console-Property-Errors header. When Google refuses every property, the request fails as a single-property read would. | 
 **range_** | **int32** | Number of days to look back, today included (alternative to from/to, which win when both are given). At most 487, Google&#39;s retention. A value that is not a plain positive number returns 422 ERR_INVALID_PARAM even beside from/to. | 
 **from** | **string** | Start date (YYYY-MM-DD). Defaults to 30 days ago. | 
 **to** | **string** | End date (YYYY-MM-DD), inclusive. Defaults to today. Google publishes data with a 2-3 day lag, so data_through in the response says how far it reaches. | 
 **minImpressions** | **int32** | Smallest impressions a query needs. | [default to 100]
 **minPosition** | **float32** | Best average position to include. | [default to 4]
 **maxPosition** | **float32** | Worst average position to include; at least min_position. | [default to 20]
 **page** | **int32** |  | [default to 1]
 **perPage** | **int32** |  | [default to 20]
 **output** | **string** | Rectangular output for BI tools (Tableau, Excel, Sheets, ELT). Omit for the default nested JSON. &#39;flat&#39; returns the same metadata plus &#39;columns&#39; and &#39;rows&#39;; &#39;csv&#39; returns those rows as text/csv. Errors are always returned as JSON. | 
 **searchType** | **string** | Which search surface to measure. Defaults to web. discover and googleNews carry no query dimension, so Google rejects /search_console/queries for them. | [default to &quot;web&quot;]
 **filters** | **string** | Narrow the query; every entry must match (AND). Send the whole list as one JSON value: filters&#x3D;[{\&quot;dimension\&quot;:\&quot;page\&quot;,\&quot;operator\&quot;:\&quot;contains\&quot;,\&quot;expression\&quot;:\&quot;/blog/\&quot;}] (URL-encoded). An array of objects has no query-parameter form a generated client can produce, so the string is what the official SDKs send; see the SearchConsoleFilters schema for the shape it encodes. includingRegex and excludingRegex take RE2 syntax. At most 10 entries, expression at most 500 characters. The bracket form filters[][dimension]&#x3D;page&amp;filters[][operator]&#x3D;contains&amp;filters[][expression]&#x3D;/blog/ is also accepted. | 
 **dataState** | **string** | final (default) counts only rows Google has finalized. all also counts the most recent days, which are still being filled in and will change. | [default to &quot;final&quot;]
 **aggregationType** | **string** | How Google counts impressions. auto (default) is what Search Console shows (by page when page is grouped or filtered, else by property). Google rejects byProperty with a page dimension or filter. | [default to &quot;auto&quot;]

### Return type

[**SearchConsoleOpportunitiesResponse**](SearchConsoleOpportunitiesResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetSearchConsolePages

> SearchConsoleListResponse GetSearchConsolePages(ctx).ProjectId(projectId).Range_(range_).From(from).To(to).Sort(sort).Page(page).PerPage(perPage).StartRow(startRow).Output(output).SearchType(searchType).Filters(filters).DataState(dataState).AggregationType(aggregationType).Property(property).Execute()

Top Search Console pages (Growth+)



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
	range_ := int32(56) // int32 | Number of days to look back, today included (alternative to from/to, which win when both are given). At most 487, Google's retention. A value that is not a plain positive number returns 422 ERR_INVALID_PARAM even beside from/to. (optional)
	from := time.Now() // string | Start date (YYYY-MM-DD). Defaults to 30 days ago. (optional)
	to := time.Now() // string | End date (YYYY-MM-DD), inclusive. Defaults to today. Google publishes data with a 2-3 day lag, so data_through in the response says how far it reaches. (optional)
	sort := "sort_example" // string |  (optional) (default to "impressions")
	page := int32(56) // int32 |  (optional) (default to 1)
	perPage := int32(56) // int32 |  (optional) (default to 20)
	startRow := int32(56) // int32 | Google ranks rows by clicks and returns at most 25,000 per request. start_row moves that window down the ranking (e.g. 25000 for the next block); sort and pagination apply within the window. (optional) (default to 0)
	output := "output_example" // string | Rectangular output for BI tools (Tableau, Excel, Sheets, ELT). Omit for the default nested JSON. 'flat' returns the same metadata plus 'columns' and 'rows'; 'csv' returns those rows as text/csv. Errors are always returned as JSON. (optional)
	searchType := "searchType_example" // string | Which search surface to measure. Defaults to web. discover and googleNews carry no query dimension, so Google rejects /search_console/queries for them. (optional) (default to "web")
	filters := "[{\"dimension\":\"page\",\"operator\":\"contains\",\"expression\":\"/blog/\"}]" // string | Narrow the query; every entry must match (AND). Send the whole list as one JSON value: filters=[{\"dimension\":\"page\",\"operator\":\"contains\",\"expression\":\"/blog/\"}] (URL-encoded). An array of objects has no query-parameter form a generated client can produce, so the string is what the official SDKs send; see the SearchConsoleFilters schema for the shape it encodes. includingRegex and excludingRegex take RE2 syntax. At most 10 entries, expression at most 500 characters. The bracket form filters[][dimension]=page&filters[][operator]=contains&filters[][expression]=/blog/ is also accepted. (optional)
	dataState := "dataState_example" // string | final (default) counts only rows Google has finalized. all also counts the most recent days, which are still being filled in and will change. (optional) (default to "final")
	aggregationType := "aggregationType_example" // string | How Google counts impressions. auto (default) is what Search Console shows (by page when page is grouped or filtered, else by property). Google rejects byProperty with a page dimension or filter. (optional) (default to "auto")
	property := "all" // string | Which Search Console properties to read; /search_console/properties lists them. Omit it for the primary property, or pass one property id (e.g. sc-domain:example.com) to read that one; both answer with property. A comma-separated list of ids, or all, combines several and answers with properties, excluded_properties and property_errors instead: excluded_properties are left out because another selected property already counts them (a URL-prefix property under a domain property), so no click is counted twice; property_errors are properties Google refused, left out of the figures and also named in the X-Search-Console-Property-Errors header. When Google refuses every property, the request fails as a single-property read would. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SearchConsoleAPI.GetSearchConsolePages(context.Background()).ProjectId(projectId).Range_(range_).From(from).To(to).Sort(sort).Page(page).PerPage(perPage).StartRow(startRow).Output(output).SearchType(searchType).Filters(filters).DataState(dataState).AggregationType(aggregationType).Property(property).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SearchConsoleAPI.GetSearchConsolePages``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetSearchConsolePages`: SearchConsoleListResponse
	fmt.Fprintf(os.Stdout, "Response from `SearchConsoleAPI.GetSearchConsolePages`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetSearchConsolePagesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **projectId** | **int32** | Project ID | 
 **range_** | **int32** | Number of days to look back, today included (alternative to from/to, which win when both are given). At most 487, Google&#39;s retention. A value that is not a plain positive number returns 422 ERR_INVALID_PARAM even beside from/to. | 
 **from** | **string** | Start date (YYYY-MM-DD). Defaults to 30 days ago. | 
 **to** | **string** | End date (YYYY-MM-DD), inclusive. Defaults to today. Google publishes data with a 2-3 day lag, so data_through in the response says how far it reaches. | 
 **sort** | **string** |  | [default to &quot;impressions&quot;]
 **page** | **int32** |  | [default to 1]
 **perPage** | **int32** |  | [default to 20]
 **startRow** | **int32** | Google ranks rows by clicks and returns at most 25,000 per request. start_row moves that window down the ranking (e.g. 25000 for the next block); sort and pagination apply within the window. | [default to 0]
 **output** | **string** | Rectangular output for BI tools (Tableau, Excel, Sheets, ELT). Omit for the default nested JSON. &#39;flat&#39; returns the same metadata plus &#39;columns&#39; and &#39;rows&#39;; &#39;csv&#39; returns those rows as text/csv. Errors are always returned as JSON. | 
 **searchType** | **string** | Which search surface to measure. Defaults to web. discover and googleNews carry no query dimension, so Google rejects /search_console/queries for them. | [default to &quot;web&quot;]
 **filters** | **string** | Narrow the query; every entry must match (AND). Send the whole list as one JSON value: filters&#x3D;[{\&quot;dimension\&quot;:\&quot;page\&quot;,\&quot;operator\&quot;:\&quot;contains\&quot;,\&quot;expression\&quot;:\&quot;/blog/\&quot;}] (URL-encoded). An array of objects has no query-parameter form a generated client can produce, so the string is what the official SDKs send; see the SearchConsoleFilters schema for the shape it encodes. includingRegex and excludingRegex take RE2 syntax. At most 10 entries, expression at most 500 characters. The bracket form filters[][dimension]&#x3D;page&amp;filters[][operator]&#x3D;contains&amp;filters[][expression]&#x3D;/blog/ is also accepted. | 
 **dataState** | **string** | final (default) counts only rows Google has finalized. all also counts the most recent days, which are still being filled in and will change. | [default to &quot;final&quot;]
 **aggregationType** | **string** | How Google counts impressions. auto (default) is what Search Console shows (by page when page is grouped or filtered, else by property). Google rejects byProperty with a page dimension or filter. | [default to &quot;auto&quot;]
 **property** | **string** | Which Search Console properties to read; /search_console/properties lists them. Omit it for the primary property, or pass one property id (e.g. sc-domain:example.com) to read that one; both answer with property. A comma-separated list of ids, or all, combines several and answers with properties, excluded_properties and property_errors instead: excluded_properties are left out because another selected property already counts them (a URL-prefix property under a domain property), so no click is counted twice; property_errors are properties Google refused, left out of the figures and also named in the X-Search-Console-Property-Errors header. When Google refuses every property, the request fails as a single-property read would. | 

### Return type

[**SearchConsoleListResponse**](SearchConsoleListResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetSearchConsoleQueries

> SearchConsoleListResponse GetSearchConsoleQueries(ctx).ProjectId(projectId).Range_(range_).From(from).To(to).Sort(sort).Page(page).PerPage(perPage).StartRow(startRow).Output(output).SearchType(searchType).Filters(filters).DataState(dataState).AggregationType(aggregationType).Property(property).Execute()

Top Search Console queries (Growth+)



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
	range_ := int32(56) // int32 | Number of days to look back, today included (alternative to from/to, which win when both are given). At most 487, Google's retention. A value that is not a plain positive number returns 422 ERR_INVALID_PARAM even beside from/to. (optional)
	from := time.Now() // string | Start date (YYYY-MM-DD). Defaults to 30 days ago. (optional)
	to := time.Now() // string | End date (YYYY-MM-DD), inclusive. Defaults to today. Google publishes data with a 2-3 day lag, so data_through in the response says how far it reaches. (optional)
	sort := "sort_example" // string |  (optional) (default to "impressions")
	page := int32(56) // int32 |  (optional) (default to 1)
	perPage := int32(56) // int32 |  (optional) (default to 20)
	startRow := int32(56) // int32 | Google ranks rows by clicks and returns at most 25,000 per request. start_row moves that window down the ranking (e.g. 25000 for the next block); sort and pagination apply within the window. (optional) (default to 0)
	output := "output_example" // string | Rectangular output for BI tools (Tableau, Excel, Sheets, ELT). Omit for the default nested JSON. 'flat' returns the same metadata plus 'columns' and 'rows'; 'csv' returns those rows as text/csv. Errors are always returned as JSON. (optional)
	searchType := "searchType_example" // string | Which search surface to measure. Defaults to web. discover and googleNews carry no query dimension, so Google rejects /search_console/queries for them. (optional) (default to "web")
	filters := "[{\"dimension\":\"page\",\"operator\":\"contains\",\"expression\":\"/blog/\"}]" // string | Narrow the query; every entry must match (AND). Send the whole list as one JSON value: filters=[{\"dimension\":\"page\",\"operator\":\"contains\",\"expression\":\"/blog/\"}] (URL-encoded). An array of objects has no query-parameter form a generated client can produce, so the string is what the official SDKs send; see the SearchConsoleFilters schema for the shape it encodes. includingRegex and excludingRegex take RE2 syntax. At most 10 entries, expression at most 500 characters. The bracket form filters[][dimension]=page&filters[][operator]=contains&filters[][expression]=/blog/ is also accepted. (optional)
	dataState := "dataState_example" // string | final (default) counts only rows Google has finalized. all also counts the most recent days, which are still being filled in and will change. (optional) (default to "final")
	aggregationType := "aggregationType_example" // string | How Google counts impressions. auto (default) is what Search Console shows (by page when page is grouped or filtered, else by property). Google rejects byProperty with a page dimension or filter. (optional) (default to "auto")
	property := "all" // string | Which Search Console properties to read; /search_console/properties lists them. Omit it for the primary property, or pass one property id (e.g. sc-domain:example.com) to read that one; both answer with property. A comma-separated list of ids, or all, combines several and answers with properties, excluded_properties and property_errors instead: excluded_properties are left out because another selected property already counts them (a URL-prefix property under a domain property), so no click is counted twice; property_errors are properties Google refused, left out of the figures and also named in the X-Search-Console-Property-Errors header. When Google refuses every property, the request fails as a single-property read would. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SearchConsoleAPI.GetSearchConsoleQueries(context.Background()).ProjectId(projectId).Range_(range_).From(from).To(to).Sort(sort).Page(page).PerPage(perPage).StartRow(startRow).Output(output).SearchType(searchType).Filters(filters).DataState(dataState).AggregationType(aggregationType).Property(property).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SearchConsoleAPI.GetSearchConsoleQueries``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetSearchConsoleQueries`: SearchConsoleListResponse
	fmt.Fprintf(os.Stdout, "Response from `SearchConsoleAPI.GetSearchConsoleQueries`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetSearchConsoleQueriesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **projectId** | **int32** | Project ID | 
 **range_** | **int32** | Number of days to look back, today included (alternative to from/to, which win when both are given). At most 487, Google&#39;s retention. A value that is not a plain positive number returns 422 ERR_INVALID_PARAM even beside from/to. | 
 **from** | **string** | Start date (YYYY-MM-DD). Defaults to 30 days ago. | 
 **to** | **string** | End date (YYYY-MM-DD), inclusive. Defaults to today. Google publishes data with a 2-3 day lag, so data_through in the response says how far it reaches. | 
 **sort** | **string** |  | [default to &quot;impressions&quot;]
 **page** | **int32** |  | [default to 1]
 **perPage** | **int32** |  | [default to 20]
 **startRow** | **int32** | Google ranks rows by clicks and returns at most 25,000 per request. start_row moves that window down the ranking (e.g. 25000 for the next block); sort and pagination apply within the window. | [default to 0]
 **output** | **string** | Rectangular output for BI tools (Tableau, Excel, Sheets, ELT). Omit for the default nested JSON. &#39;flat&#39; returns the same metadata plus &#39;columns&#39; and &#39;rows&#39;; &#39;csv&#39; returns those rows as text/csv. Errors are always returned as JSON. | 
 **searchType** | **string** | Which search surface to measure. Defaults to web. discover and googleNews carry no query dimension, so Google rejects /search_console/queries for them. | [default to &quot;web&quot;]
 **filters** | **string** | Narrow the query; every entry must match (AND). Send the whole list as one JSON value: filters&#x3D;[{\&quot;dimension\&quot;:\&quot;page\&quot;,\&quot;operator\&quot;:\&quot;contains\&quot;,\&quot;expression\&quot;:\&quot;/blog/\&quot;}] (URL-encoded). An array of objects has no query-parameter form a generated client can produce, so the string is what the official SDKs send; see the SearchConsoleFilters schema for the shape it encodes. includingRegex and excludingRegex take RE2 syntax. At most 10 entries, expression at most 500 characters. The bracket form filters[][dimension]&#x3D;page&amp;filters[][operator]&#x3D;contains&amp;filters[][expression]&#x3D;/blog/ is also accepted. | 
 **dataState** | **string** | final (default) counts only rows Google has finalized. all also counts the most recent days, which are still being filled in and will change. | [default to &quot;final&quot;]
 **aggregationType** | **string** | How Google counts impressions. auto (default) is what Search Console shows (by page when page is grouped or filtered, else by property). Google rejects byProperty with a page dimension or filter. | [default to &quot;auto&quot;]
 **property** | **string** | Which Search Console properties to read; /search_console/properties lists them. Omit it for the primary property, or pass one property id (e.g. sc-domain:example.com) to read that one; both answer with property. A comma-separated list of ids, or all, combines several and answers with properties, excluded_properties and property_errors instead: excluded_properties are left out because another selected property already counts them (a URL-prefix property under a domain property), so no click is counted twice; property_errors are properties Google refused, left out of the figures and also named in the X-Search-Console-Property-Errors header. When Google refuses every property, the request fails as a single-property read would. | 

### Return type

[**SearchConsoleListResponse**](SearchConsoleListResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetSearchConsoleRows

> SearchConsoleRowsResponse GetSearchConsoleRows(ctx).ProjectId(projectId).Dimensions(dimensions).Range_(range_).From(from).To(to).Sort(sort).Page(page).PerPage(perPage).StartRow(startRow).Output(output).SearchType(searchType).Filters(filters).DataState(dataState).AggregationType(aggregationType).Property(property).Execute()

Search Console rows by several dimensions (Growth+)



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
	dimensions := "page,query" // string | Comma-separated dimensions to group by, 1 to 3 of date, country, device, page, query, searchAppearance, property. Each becomes a field of every row; country and device values are lowercase. property is the Search Console property the row comes from (see the property parameter).
	range_ := int32(56) // int32 | Number of days to look back, today included (alternative to from/to, which win when both are given). At most 487, Google's retention. A value that is not a plain positive number returns 422 ERR_INVALID_PARAM even beside from/to. (optional)
	from := time.Now() // string | Start date (YYYY-MM-DD). Defaults to 30 days ago. (optional)
	to := time.Now() // string | End date (YYYY-MM-DD), inclusive. Defaults to today. Google publishes data with a 2-3 day lag, so data_through in the response says how far it reaches. (optional)
	sort := "sort_example" // string |  (optional) (default to "impressions")
	page := int32(56) // int32 |  (optional) (default to 1)
	perPage := int32(56) // int32 |  (optional) (default to 20)
	startRow := int32(56) // int32 | Google ranks rows by clicks and returns at most 25,000 per request. start_row moves that window down the ranking (e.g. 25000 for the next block); sort and pagination apply within the window. (optional) (default to 0)
	output := "output_example" // string | Rectangular output for BI tools (Tableau, Excel, Sheets, ELT). Omit for the default nested JSON. 'flat' returns the same metadata plus 'columns' and 'rows'; 'csv' returns those rows as text/csv. Errors are always returned as JSON. (optional)
	searchType := "searchType_example" // string | Which search surface to measure. Defaults to web. discover and googleNews carry no query dimension, so Google rejects /search_console/queries for them. (optional) (default to "web")
	filters := "[{\"dimension\":\"page\",\"operator\":\"contains\",\"expression\":\"/blog/\"}]" // string | Narrow the query; every entry must match (AND). Send the whole list as one JSON value: filters=[{\"dimension\":\"page\",\"operator\":\"contains\",\"expression\":\"/blog/\"}] (URL-encoded). An array of objects has no query-parameter form a generated client can produce, so the string is what the official SDKs send; see the SearchConsoleFilters schema for the shape it encodes. includingRegex and excludingRegex take RE2 syntax. At most 10 entries, expression at most 500 characters. The bracket form filters[][dimension]=page&filters[][operator]=contains&filters[][expression]=/blog/ is also accepted. (optional)
	dataState := "dataState_example" // string | final (default) counts only rows Google has finalized. all also counts the most recent days, which are still being filled in and will change. (optional) (default to "final")
	aggregationType := "aggregationType_example" // string | How Google counts impressions. auto (default) is what Search Console shows (by page when page is grouped or filtered, else by property). Google rejects byProperty with a page dimension or filter. (optional) (default to "auto")
	property := "all" // string | Which Search Console properties to read; /search_console/properties lists them. Omit it for the primary property, or pass one property id (e.g. sc-domain:example.com) to read that one; both answer with property. A comma-separated list of ids, or all, combines several and answers with properties, excluded_properties and property_errors instead: excluded_properties are left out because another selected property already counts them (a URL-prefix property under a domain property), so no click is counted twice; property_errors are properties Google refused, left out of the figures and also named in the X-Search-Console-Property-Errors header. When Google refuses every property, the request fails as a single-property read would. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SearchConsoleAPI.GetSearchConsoleRows(context.Background()).ProjectId(projectId).Dimensions(dimensions).Range_(range_).From(from).To(to).Sort(sort).Page(page).PerPage(perPage).StartRow(startRow).Output(output).SearchType(searchType).Filters(filters).DataState(dataState).AggregationType(aggregationType).Property(property).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SearchConsoleAPI.GetSearchConsoleRows``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetSearchConsoleRows`: SearchConsoleRowsResponse
	fmt.Fprintf(os.Stdout, "Response from `SearchConsoleAPI.GetSearchConsoleRows`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetSearchConsoleRowsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **projectId** | **int32** | Project ID | 
 **dimensions** | **string** | Comma-separated dimensions to group by, 1 to 3 of date, country, device, page, query, searchAppearance, property. Each becomes a field of every row; country and device values are lowercase. property is the Search Console property the row comes from (see the property parameter). | 
 **range_** | **int32** | Number of days to look back, today included (alternative to from/to, which win when both are given). At most 487, Google&#39;s retention. A value that is not a plain positive number returns 422 ERR_INVALID_PARAM even beside from/to. | 
 **from** | **string** | Start date (YYYY-MM-DD). Defaults to 30 days ago. | 
 **to** | **string** | End date (YYYY-MM-DD), inclusive. Defaults to today. Google publishes data with a 2-3 day lag, so data_through in the response says how far it reaches. | 
 **sort** | **string** |  | [default to &quot;impressions&quot;]
 **page** | **int32** |  | [default to 1]
 **perPage** | **int32** |  | [default to 20]
 **startRow** | **int32** | Google ranks rows by clicks and returns at most 25,000 per request. start_row moves that window down the ranking (e.g. 25000 for the next block); sort and pagination apply within the window. | [default to 0]
 **output** | **string** | Rectangular output for BI tools (Tableau, Excel, Sheets, ELT). Omit for the default nested JSON. &#39;flat&#39; returns the same metadata plus &#39;columns&#39; and &#39;rows&#39;; &#39;csv&#39; returns those rows as text/csv. Errors are always returned as JSON. | 
 **searchType** | **string** | Which search surface to measure. Defaults to web. discover and googleNews carry no query dimension, so Google rejects /search_console/queries for them. | [default to &quot;web&quot;]
 **filters** | **string** | Narrow the query; every entry must match (AND). Send the whole list as one JSON value: filters&#x3D;[{\&quot;dimension\&quot;:\&quot;page\&quot;,\&quot;operator\&quot;:\&quot;contains\&quot;,\&quot;expression\&quot;:\&quot;/blog/\&quot;}] (URL-encoded). An array of objects has no query-parameter form a generated client can produce, so the string is what the official SDKs send; see the SearchConsoleFilters schema for the shape it encodes. includingRegex and excludingRegex take RE2 syntax. At most 10 entries, expression at most 500 characters. The bracket form filters[][dimension]&#x3D;page&amp;filters[][operator]&#x3D;contains&amp;filters[][expression]&#x3D;/blog/ is also accepted. | 
 **dataState** | **string** | final (default) counts only rows Google has finalized. all also counts the most recent days, which are still being filled in and will change. | [default to &quot;final&quot;]
 **aggregationType** | **string** | How Google counts impressions. auto (default) is what Search Console shows (by page when page is grouped or filtered, else by property). Google rejects byProperty with a page dimension or filter. | [default to &quot;auto&quot;]
 **property** | **string** | Which Search Console properties to read; /search_console/properties lists them. Omit it for the primary property, or pass one property id (e.g. sc-domain:example.com) to read that one; both answer with property. A comma-separated list of ids, or all, combines several and answers with properties, excluded_properties and property_errors instead: excluded_properties are left out because another selected property already counts them (a URL-prefix property under a domain property), so no click is counted twice; property_errors are properties Google refused, left out of the figures and also named in the X-Search-Console-Property-Errors header. When Google refuses every property, the request fails as a single-property read would. | 

### Return type

[**SearchConsoleRowsResponse**](SearchConsoleRowsResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetSearchConsoleSummary

> SearchConsoleSummaryResponse GetSearchConsoleSummary(ctx).ProjectId(projectId).Range_(range_).From(from).To(to).Dimension(dimension).Limit(limit).SearchType(searchType).Filters(filters).DataState(dataState).AggregationType(aggregationType).Property(property).Execute()

Search Console summary (Growth+)



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
	range_ := int32(56) // int32 | Number of days to look back, today included (alternative to from/to, which win when both are given). At most 487, Google's retention. A value that is not a plain positive number returns 422 ERR_INVALID_PARAM even beside from/to. (optional)
	from := time.Now() // string | Start date (YYYY-MM-DD). Defaults to 30 days ago. (optional)
	to := time.Now() // string | End date (YYYY-MM-DD), inclusive. Defaults to today. Google publishes data with a 2-3 day lag, so data_through in the response says how far it reaches. (optional)
	dimension := "dimension_example" // string | Optional breakdown aggregated over the range. country and device are lowercased; page and query keep the casing Google returns, because a page URL is case sensitive. property gives one row per property read (see the property parameter). (optional)
	limit := int32(56) // int32 | Maximum breakdown rows, sorted by impressions descending. Default and maximum 1000. Use /search_console/queries or /search_console/pages to page through up to 25,000 rows. (optional)
	searchType := "searchType_example" // string | Which search surface to measure. Defaults to web. discover and googleNews carry no query dimension, so Google rejects /search_console/queries for them. (optional) (default to "web")
	filters := "[{\"dimension\":\"page\",\"operator\":\"contains\",\"expression\":\"/blog/\"}]" // string | Narrow the query; every entry must match (AND). Send the whole list as one JSON value: filters=[{\"dimension\":\"page\",\"operator\":\"contains\",\"expression\":\"/blog/\"}] (URL-encoded). An array of objects has no query-parameter form a generated client can produce, so the string is what the official SDKs send; see the SearchConsoleFilters schema for the shape it encodes. includingRegex and excludingRegex take RE2 syntax. At most 10 entries, expression at most 500 characters. The bracket form filters[][dimension]=page&filters[][operator]=contains&filters[][expression]=/blog/ is also accepted. (optional)
	dataState := "dataState_example" // string | final (default) counts only rows Google has finalized. all also counts the most recent days, which are still being filled in and will change. (optional) (default to "final")
	aggregationType := "aggregationType_example" // string | How Google counts impressions. auto (default) is what Search Console shows (by page when page is grouped or filtered, else by property). Google rejects byProperty with a page dimension or filter. (optional) (default to "auto")
	property := "all" // string | Which Search Console properties to read; /search_console/properties lists them. Omit it for the primary property, or pass one property id (e.g. sc-domain:example.com) to read that one; both answer with property. A comma-separated list of ids, or all, combines several and answers with properties, excluded_properties and property_errors instead: excluded_properties are left out because another selected property already counts them (a URL-prefix property under a domain property), so no click is counted twice; property_errors are properties Google refused, left out of the figures and also named in the X-Search-Console-Property-Errors header. When Google refuses every property, the request fails as a single-property read would. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SearchConsoleAPI.GetSearchConsoleSummary(context.Background()).ProjectId(projectId).Range_(range_).From(from).To(to).Dimension(dimension).Limit(limit).SearchType(searchType).Filters(filters).DataState(dataState).AggregationType(aggregationType).Property(property).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SearchConsoleAPI.GetSearchConsoleSummary``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetSearchConsoleSummary`: SearchConsoleSummaryResponse
	fmt.Fprintf(os.Stdout, "Response from `SearchConsoleAPI.GetSearchConsoleSummary`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetSearchConsoleSummaryRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **projectId** | **int32** | Project ID | 
 **range_** | **int32** | Number of days to look back, today included (alternative to from/to, which win when both are given). At most 487, Google&#39;s retention. A value that is not a plain positive number returns 422 ERR_INVALID_PARAM even beside from/to. | 
 **from** | **string** | Start date (YYYY-MM-DD). Defaults to 30 days ago. | 
 **to** | **string** | End date (YYYY-MM-DD), inclusive. Defaults to today. Google publishes data with a 2-3 day lag, so data_through in the response says how far it reaches. | 
 **dimension** | **string** | Optional breakdown aggregated over the range. country and device are lowercased; page and query keep the casing Google returns, because a page URL is case sensitive. property gives one row per property read (see the property parameter). | 
 **limit** | **int32** | Maximum breakdown rows, sorted by impressions descending. Default and maximum 1000. Use /search_console/queries or /search_console/pages to page through up to 25,000 rows. | 
 **searchType** | **string** | Which search surface to measure. Defaults to web. discover and googleNews carry no query dimension, so Google rejects /search_console/queries for them. | [default to &quot;web&quot;]
 **filters** | **string** | Narrow the query; every entry must match (AND). Send the whole list as one JSON value: filters&#x3D;[{\&quot;dimension\&quot;:\&quot;page\&quot;,\&quot;operator\&quot;:\&quot;contains\&quot;,\&quot;expression\&quot;:\&quot;/blog/\&quot;}] (URL-encoded). An array of objects has no query-parameter form a generated client can produce, so the string is what the official SDKs send; see the SearchConsoleFilters schema for the shape it encodes. includingRegex and excludingRegex take RE2 syntax. At most 10 entries, expression at most 500 characters. The bracket form filters[][dimension]&#x3D;page&amp;filters[][operator]&#x3D;contains&amp;filters[][expression]&#x3D;/blog/ is also accepted. | 
 **dataState** | **string** | final (default) counts only rows Google has finalized. all also counts the most recent days, which are still being filled in and will change. | [default to &quot;final&quot;]
 **aggregationType** | **string** | How Google counts impressions. auto (default) is what Search Console shows (by page when page is grouped or filtered, else by property). Google rejects byProperty with a page dimension or filter. | [default to &quot;auto&quot;]
 **property** | **string** | Which Search Console properties to read; /search_console/properties lists them. Omit it for the primary property, or pass one property id (e.g. sc-domain:example.com) to read that one; both answer with property. A comma-separated list of ids, or all, combines several and answers with properties, excluded_properties and property_errors instead: excluded_properties are left out because another selected property already counts them (a URL-prefix property under a domain property), so no click is counted twice; property_errors are properties Google refused, left out of the figures and also named in the X-Search-Console-Property-Errors header. When Google refuses every property, the request fails as a single-property read would. | 

### Return type

[**SearchConsoleSummaryResponse**](SearchConsoleSummaryResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetSearchConsoleTimeseries

> SearchConsoleTimeseriesResponse GetSearchConsoleTimeseries(ctx).ProjectId(projectId).Range_(range_).From(from).To(to).Granularity(granularity).Output(output).SearchType(searchType).Filters(filters).DataState(dataState).AggregationType(aggregationType).Property(property).Execute()

Search Console time series (Growth+)



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
	range_ := int32(56) // int32 | Number of days to look back, today included (alternative to from/to, which win when both are given). At most 487, Google's retention. A value that is not a plain positive number returns 422 ERR_INVALID_PARAM even beside from/to. (optional)
	from := time.Now() // string | Start date (YYYY-MM-DD). Defaults to 30 days ago. (optional)
	to := time.Now() // string | End date (YYYY-MM-DD), inclusive. Defaults to today. Google publishes data with a 2-3 day lag, so data_through in the response says how far it reaches. (optional)
	granularity := "granularity_example" // string |  (optional)
	output := "output_example" // string | Rectangular output for BI tools (Tableau, Excel, Sheets, ELT). Omit for the default nested JSON. 'flat' returns the same metadata plus 'columns' and 'rows'; 'csv' returns those rows as text/csv. Errors are always returned as JSON. (optional)
	searchType := "searchType_example" // string | Which search surface to measure. Defaults to web. discover and googleNews carry no query dimension, so Google rejects /search_console/queries for them. (optional) (default to "web")
	filters := "[{\"dimension\":\"page\",\"operator\":\"contains\",\"expression\":\"/blog/\"}]" // string | Narrow the query; every entry must match (AND). Send the whole list as one JSON value: filters=[{\"dimension\":\"page\",\"operator\":\"contains\",\"expression\":\"/blog/\"}] (URL-encoded). An array of objects has no query-parameter form a generated client can produce, so the string is what the official SDKs send; see the SearchConsoleFilters schema for the shape it encodes. includingRegex and excludingRegex take RE2 syntax. At most 10 entries, expression at most 500 characters. The bracket form filters[][dimension]=page&filters[][operator]=contains&filters[][expression]=/blog/ is also accepted. (optional)
	dataState := "dataState_example" // string | final (default) counts only rows Google has finalized. all also counts the most recent days, which are still being filled in and will change. (optional) (default to "final")
	aggregationType := "aggregationType_example" // string | How Google counts impressions. auto (default) is what Search Console shows (by page when page is grouped or filtered, else by property). Google rejects byProperty with a page dimension or filter. (optional) (default to "auto")
	property := "all" // string | Which Search Console properties to read; /search_console/properties lists them. Omit it for the primary property, or pass one property id (e.g. sc-domain:example.com) to read that one; both answer with property. A comma-separated list of ids, or all, combines several and answers with properties, excluded_properties and property_errors instead: excluded_properties are left out because another selected property already counts them (a URL-prefix property under a domain property), so no click is counted twice; property_errors are properties Google refused, left out of the figures and also named in the X-Search-Console-Property-Errors header. When Google refuses every property, the request fails as a single-property read would. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SearchConsoleAPI.GetSearchConsoleTimeseries(context.Background()).ProjectId(projectId).Range_(range_).From(from).To(to).Granularity(granularity).Output(output).SearchType(searchType).Filters(filters).DataState(dataState).AggregationType(aggregationType).Property(property).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SearchConsoleAPI.GetSearchConsoleTimeseries``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetSearchConsoleTimeseries`: SearchConsoleTimeseriesResponse
	fmt.Fprintf(os.Stdout, "Response from `SearchConsoleAPI.GetSearchConsoleTimeseries`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetSearchConsoleTimeseriesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **projectId** | **int32** | Project ID | 
 **range_** | **int32** | Number of days to look back, today included (alternative to from/to, which win when both are given). At most 487, Google&#39;s retention. A value that is not a plain positive number returns 422 ERR_INVALID_PARAM even beside from/to. | 
 **from** | **string** | Start date (YYYY-MM-DD). Defaults to 30 days ago. | 
 **to** | **string** | End date (YYYY-MM-DD), inclusive. Defaults to today. Google publishes data with a 2-3 day lag, so data_through in the response says how far it reaches. | 
 **granularity** | **string** |  | 
 **output** | **string** | Rectangular output for BI tools (Tableau, Excel, Sheets, ELT). Omit for the default nested JSON. &#39;flat&#39; returns the same metadata plus &#39;columns&#39; and &#39;rows&#39;; &#39;csv&#39; returns those rows as text/csv. Errors are always returned as JSON. | 
 **searchType** | **string** | Which search surface to measure. Defaults to web. discover and googleNews carry no query dimension, so Google rejects /search_console/queries for them. | [default to &quot;web&quot;]
 **filters** | **string** | Narrow the query; every entry must match (AND). Send the whole list as one JSON value: filters&#x3D;[{\&quot;dimension\&quot;:\&quot;page\&quot;,\&quot;operator\&quot;:\&quot;contains\&quot;,\&quot;expression\&quot;:\&quot;/blog/\&quot;}] (URL-encoded). An array of objects has no query-parameter form a generated client can produce, so the string is what the official SDKs send; see the SearchConsoleFilters schema for the shape it encodes. includingRegex and excludingRegex take RE2 syntax. At most 10 entries, expression at most 500 characters. The bracket form filters[][dimension]&#x3D;page&amp;filters[][operator]&#x3D;contains&amp;filters[][expression]&#x3D;/blog/ is also accepted. | 
 **dataState** | **string** | final (default) counts only rows Google has finalized. all also counts the most recent days, which are still being filled in and will change. | [default to &quot;final&quot;]
 **aggregationType** | **string** | How Google counts impressions. auto (default) is what Search Console shows (by page when page is grouped or filtered, else by property). Google rejects byProperty with a page dimension or filter. | [default to &quot;auto&quot;]
 **property** | **string** | Which Search Console properties to read; /search_console/properties lists them. Omit it for the primary property, or pass one property id (e.g. sc-domain:example.com) to read that one; both answer with property. A comma-separated list of ids, or all, combines several and answers with properties, excluded_properties and property_errors instead: excluded_properties are left out because another selected property already counts them (a URL-prefix property under a domain property), so no click is counted twice; property_errors are properties Google refused, left out of the figures and also named in the X-Search-Console-Property-Errors header. When Google refuses every property, the request fails as a single-property read would. | 

### Return type

[**SearchConsoleTimeseriesResponse**](SearchConsoleTimeseriesResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListSearchConsoleProperties

> SearchConsolePropertiesResponse ListSearchConsoleProperties(ctx).ProjectId(projectId).Output(output).Execute()

List Search Console properties (Growth+)



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
	resp, r, err := apiClient.SearchConsoleAPI.ListSearchConsoleProperties(context.Background()).ProjectId(projectId).Output(output).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SearchConsoleAPI.ListSearchConsoleProperties``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListSearchConsoleProperties`: SearchConsolePropertiesResponse
	fmt.Fprintf(os.Stdout, "Response from `SearchConsoleAPI.ListSearchConsoleProperties`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListSearchConsolePropertiesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **projectId** | **int32** | Project ID | 
 **output** | **string** | Rectangular output for BI tools (Tableau, Excel, Sheets, ELT). Omit for the default nested JSON. &#39;flat&#39; returns the same metadata plus &#39;columns&#39; and &#39;rows&#39;; &#39;csv&#39; returns those rows as text/csv. Errors are always returned as JSON. | 

### Return type

[**SearchConsolePropertiesResponse**](SearchConsolePropertiesResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

