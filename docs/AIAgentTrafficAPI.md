# \AIAgentTrafficAPI

All URIs are relative to *https://api.llmpulse.ai/api/v1*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetAgentTraffic**](AIAgentTrafficAPI.md#GetAgentTraffic) | **Get** /metrics/agent_traffic | AI bot crawler traffic (Scale plan or above, Beta)
[**GetAiTraffic**](AIAgentTrafficAPI.md#GetAiTraffic) | **Get** /metrics/ai_traffic | AI referral traffic (Scale plan or above)
[**GetWebAnalyticsSchema**](AIAgentTrafficAPI.md#GetWebAnalyticsSchema) | **Get** /web_analytics/schema | Web analytics query format (Growth+)
[**ListAgentBots**](AIAgentTrafficAPI.md#ListAgentBots) | **Get** /dimensions/agent_bots | AI bot catalog (Scale plan or above)
[**QueryWebAnalytics**](AIAgentTrafficAPI.md#QueryWebAnalytics) | **Post** /web_analytics/query | Live web analytics query (Growth+)



## GetAgentTraffic

> AgentTrafficResponse GetAgentTraffic(ctx).ProjectId(projectId).Range_(range_).From(from).To(to).Bot(bot).Company(company).GroupBy(groupBy).Granularity(granularity).Execute()

AI bot crawler traffic (Scale plan or above, Beta)



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
	range_ := int32(56) // int32 | Number of days to look back (alternative to from/to) (optional)
	from := time.Now() // time.Time |  (optional)
	to := time.Now() // time.Time | End of the window. A date-only value such as 2026-09-01 covers that whole day. Pass a full timestamp to end the window earlier. (optional)
	bot := "bot_example" // string | Filter by bot slug (e.g. gptbot, claudebot, perplexitybot) (optional)
	company := "company_example" // string | Filter by company (e.g. openai, anthropic, google) (optional)
	groupBy := "groupBy_example" // string |  (optional) (default to "bot")
	granularity := "granularity_example" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AIAgentTrafficAPI.GetAgentTraffic(context.Background()).ProjectId(projectId).Range_(range_).From(from).To(to).Bot(bot).Company(company).GroupBy(groupBy).Granularity(granularity).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AIAgentTrafficAPI.GetAgentTraffic``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetAgentTraffic`: AgentTrafficResponse
	fmt.Fprintf(os.Stdout, "Response from `AIAgentTrafficAPI.GetAgentTraffic`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetAgentTrafficRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **projectId** | **int32** | Project ID | 
 **range_** | **int32** | Number of days to look back (alternative to from/to) | 
 **from** | **time.Time** |  | 
 **to** | **time.Time** | End of the window. A date-only value such as 2026-09-01 covers that whole day. Pass a full timestamp to end the window earlier. | 
 **bot** | **string** | Filter by bot slug (e.g. gptbot, claudebot, perplexitybot) | 
 **company** | **string** | Filter by company (e.g. openai, anthropic, google) | 
 **groupBy** | **string** |  | [default to &quot;bot&quot;]
 **granularity** | **string** |  | 

### Return type

[**AgentTrafficResponse**](AgentTrafficResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetAiTraffic

> GetAiTraffic(ctx).ProjectId(projectId).Range_(range_).From(from).To(to).Source(source).Granularity(granularity).Execute()

AI referral traffic (Scale plan or above)



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
	range_ := int32(56) // int32 | Number of days to look back (alternative to from/to) (optional)
	from := time.Now() // time.Time |  (optional)
	to := time.Now() // time.Time | End of the window. A date-only value such as 2026-09-01 covers that whole day. Pass a full timestamp to end the window earlier. (optional)
	source := "source_example" // string | Filter by a single AI source slug (e.g. chatgpt, perplexity, gemini, claude) (optional)
	granularity := "granularity_example" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.AIAgentTrafficAPI.GetAiTraffic(context.Background()).ProjectId(projectId).Range_(range_).From(from).To(to).Source(source).Granularity(granularity).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AIAgentTrafficAPI.GetAiTraffic``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetAiTrafficRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **projectId** | **int32** | Project ID | 
 **range_** | **int32** | Number of days to look back (alternative to from/to) | 
 **from** | **time.Time** |  | 
 **to** | **time.Time** | End of the window. A date-only value such as 2026-09-01 covers that whole day. Pass a full timestamp to end the window earlier. | 
 **source** | **string** | Filter by a single AI source slug (e.g. chatgpt, perplexity, gemini, claude) | 
 **granularity** | **string** |  | 

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


## GetWebAnalyticsSchema

> WebAnalyticsSchemaResponse GetWebAnalyticsSchema(ctx).ProjectId(projectId).Execute()

Web analytics query format (Growth+)



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

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AIAgentTrafficAPI.GetWebAnalyticsSchema(context.Background()).ProjectId(projectId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AIAgentTrafficAPI.GetWebAnalyticsSchema``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetWebAnalyticsSchema`: WebAnalyticsSchemaResponse
	fmt.Fprintf(os.Stdout, "Response from `AIAgentTrafficAPI.GetWebAnalyticsSchema`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetWebAnalyticsSchemaRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **projectId** | **int32** | Project ID | 

### Return type

[**WebAnalyticsSchemaResponse**](WebAnalyticsSchemaResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListAgentBots

> AgentBotsResponse ListAgentBots(ctx).ProjectId(projectId).Output(output).Execute()

AI bot catalog (Scale plan or above)



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
	resp, r, err := apiClient.AIAgentTrafficAPI.ListAgentBots(context.Background()).ProjectId(projectId).Output(output).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AIAgentTrafficAPI.ListAgentBots``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListAgentBots`: AgentBotsResponse
	fmt.Fprintf(os.Stdout, "Response from `AIAgentTrafficAPI.ListAgentBots`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListAgentBotsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **projectId** | **int32** | Project ID | 
 **output** | **string** | Rectangular output for BI tools (Tableau, Excel, Sheets, ELT). Omit for the default nested JSON. &#39;flat&#39; returns the same metadata plus &#39;columns&#39; and &#39;rows&#39;; &#39;csv&#39; returns those rows as text/csv. Errors are always returned as JSON. | 

### Return type

[**AgentBotsResponse**](AgentBotsResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## QueryWebAnalytics

> WebAnalyticsQueryResponse QueryWebAnalytics(ctx).QueryWebAnalyticsRequest(queryWebAnalyticsRequest).Execute()

Live web analytics query (Growth+)



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
	queryWebAnalyticsRequest := *openapiclient.NewQueryWebAnalyticsRequest(int32(123), interface{}(123)) // QueryWebAnalyticsRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AIAgentTrafficAPI.QueryWebAnalytics(context.Background()).QueryWebAnalyticsRequest(queryWebAnalyticsRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AIAgentTrafficAPI.QueryWebAnalytics``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `QueryWebAnalytics`: WebAnalyticsQueryResponse
	fmt.Fprintf(os.Stdout, "Response from `AIAgentTrafficAPI.QueryWebAnalytics`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiQueryWebAnalyticsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **queryWebAnalyticsRequest** | [**QueryWebAnalyticsRequest**](QueryWebAnalyticsRequest.md) |  | 

### Return type

[**WebAnalyticsQueryResponse**](WebAnalyticsQueryResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

