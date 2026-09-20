# \PromptsAPI

All URIs are relative to *https://api.llmpulse.ai/api/v1*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreatePrompts**](PromptsAPI.md#CreatePrompts) | **Post** /prompts | Bulk-create prompts
[**DeletePrompt**](PromptsAPI.md#DeletePrompt) | **Delete** /prompts/{id} | Delete a prompt
[**ListPromptExecutions**](PromptsAPI.md#ListPromptExecutions) | **Get** /dimensions/prompt_executions | List prompt executions
[**ListPrompts**](PromptsAPI.md#ListPrompts) | **Get** /dimensions/prompts | List prompts
[**ListQueryFanOuts**](PromptsAPI.md#ListQueryFanOuts) | **Get** /dimensions/query_fan_outs | List query fan-out



## CreatePrompts

> PromptsCreateResponse CreatePrompts(ctx).PromptsCreateRequest(promptsCreateRequest).Execute()

Bulk-create prompts



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
	promptsCreateRequest := *openapiclient.NewPromptsCreateRequest(int32(123), []string{"Prompts_example"}, "CountryCode_example", "LanguageCode_example") // PromptsCreateRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PromptsAPI.CreatePrompts(context.Background()).PromptsCreateRequest(promptsCreateRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PromptsAPI.CreatePrompts``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreatePrompts`: PromptsCreateResponse
	fmt.Fprintf(os.Stdout, "Response from `PromptsAPI.CreatePrompts`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreatePromptsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **promptsCreateRequest** | [**PromptsCreateRequest**](PromptsCreateRequest.md) |  | 

### Return type

[**PromptsCreateResponse**](PromptsCreateResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeletePrompt

> DeletePrompt(ctx, id).ProjectId(projectId).Execute()

Delete a prompt



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
	r, err := apiClient.PromptsAPI.DeletePrompt(context.Background(), id).ProjectId(projectId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PromptsAPI.DeletePrompt``: %v\n", err)
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

Other parameters are passed through a pointer to a apiDeletePromptRequest struct via the builder pattern


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


## ListPromptExecutions

> ListPromptExecutions(ctx).ProjectId(projectId).Page(page).PerPage(perPage).Model(model).CollectionId(collectionId).CountryCode(countryCode).LanguageCode(languageCode).Prompt(prompt).From(from).To(to).MentionFilter(mentionFilter).CitationFilter(citationFilter).Competitors(competitors).Output(output).Execute()

List prompt executions

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
	page := int32(56) // int32 |  (optional) (default to 1)
	perPage := int32(56) // int32 |  (optional) (default to 20)
	model := "model_example" // string | Filter by AI model. Models the API key's user has not enabled are silently dropped. (optional)
	collectionId := openapiclient.getTimeseries_collection_id_parameter{Int32: new(int32)} // GetTimeseriesCollectionIdParameter | One collection/tag ID or a comma-separated list of IDs (optional)
	countryCode := "countryCode_example" // string | One ISO country code or a comma-separated list (e.g. US,GB,DE) (optional)
	languageCode := "languageCode_example" // string | One ISO language code or a comma-separated list (e.g. en,es,de) (optional)
	prompt := int32(56) // int32 | Filter by prompt ID (optional)
	from := time.Now() // time.Time |  (optional)
	to := time.Now() // time.Time | End of the window. A date-only value such as 2026-09-01 covers that whole day. Pass a full timestamp to end the window earlier. (optional)
	mentionFilter := "mentionFilter_example" // string | Filter by which brands are mentioned, as a two-axis matrix (your brand x competitors): mentions_you / not_mentions_you, mentions_competitor / not_mentions_competitor, and the four combined cells you_and_competitor, competitor_not_you (a rival wins and you are absent), you_not_competitor, no_brands (no tracked brand appears, i.e. open space). Combine with 'competitors' to narrow the competitor side to specific rivals; on a negative cell that reads 'none of these'. On /dimensions/sources it applies to the crawled content of each cited page instead of the answer text. The legacy value 'competitors_only' is still accepted as an alias of competitor_not_you. (optional)
	citationFilter := "citationFilter_example" // string | Same two-axis matrix applied to the domains cited in the answer instead of the brands named in it. Independent of mention_filter; pass both to intersect them (e.g. mentions_you + not_cites_you finds answers that talk about you without linking to you). (optional)
	competitors := "competitors_example" // string | Comma-separated competitor IDs (unknown IDs return ERR_INVALID_PARAM) (optional)
	output := "output_example" // string | Rectangular output for BI tools (Tableau, Excel, Sheets, ELT). Omit for the default nested JSON. 'flat' returns the same metadata plus 'columns' and 'rows'; 'csv' returns those rows as text/csv. Errors are always returned as JSON. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.PromptsAPI.ListPromptExecutions(context.Background()).ProjectId(projectId).Page(page).PerPage(perPage).Model(model).CollectionId(collectionId).CountryCode(countryCode).LanguageCode(languageCode).Prompt(prompt).From(from).To(to).MentionFilter(mentionFilter).CitationFilter(citationFilter).Competitors(competitors).Output(output).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PromptsAPI.ListPromptExecutions``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListPromptExecutionsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **projectId** | **int32** | Project ID | 
 **page** | **int32** |  | [default to 1]
 **perPage** | **int32** |  | [default to 20]
 **model** | **string** | Filter by AI model. Models the API key&#39;s user has not enabled are silently dropped. | 
 **collectionId** | [**GetTimeseriesCollectionIdParameter**](GetTimeseriesCollectionIdParameter.md) | One collection/tag ID or a comma-separated list of IDs | 
 **countryCode** | **string** | One ISO country code or a comma-separated list (e.g. US,GB,DE) | 
 **languageCode** | **string** | One ISO language code or a comma-separated list (e.g. en,es,de) | 
 **prompt** | **int32** | Filter by prompt ID | 
 **from** | **time.Time** |  | 
 **to** | **time.Time** | End of the window. A date-only value such as 2026-09-01 covers that whole day. Pass a full timestamp to end the window earlier. | 
 **mentionFilter** | **string** | Filter by which brands are mentioned, as a two-axis matrix (your brand x competitors): mentions_you / not_mentions_you, mentions_competitor / not_mentions_competitor, and the four combined cells you_and_competitor, competitor_not_you (a rival wins and you are absent), you_not_competitor, no_brands (no tracked brand appears, i.e. open space). Combine with &#39;competitors&#39; to narrow the competitor side to specific rivals; on a negative cell that reads &#39;none of these&#39;. On /dimensions/sources it applies to the crawled content of each cited page instead of the answer text. The legacy value &#39;competitors_only&#39; is still accepted as an alias of competitor_not_you. | 
 **citationFilter** | **string** | Same two-axis matrix applied to the domains cited in the answer instead of the brands named in it. Independent of mention_filter; pass both to intersect them (e.g. mentions_you + not_cites_you finds answers that talk about you without linking to you). | 
 **competitors** | **string** | Comma-separated competitor IDs (unknown IDs return ERR_INVALID_PARAM) | 
 **output** | **string** | Rectangular output for BI tools (Tableau, Excel, Sheets, ELT). Omit for the default nested JSON. &#39;flat&#39; returns the same metadata plus &#39;columns&#39; and &#39;rows&#39;; &#39;csv&#39; returns those rows as text/csv. Errors are always returned as JSON. | 

### Return type

 (empty response body)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListPrompts

> ListPrompts(ctx).ProjectId(projectId).Page(page).PerPage(perPage).Model(model).CollectionId(collectionId).CountryCode(countryCode).LanguageCode(languageCode).PromptType(promptType).BrandKind(brandKind).From(from).To(to).Output(output).Execute()

List prompts

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
	page := int32(56) // int32 |  (optional) (default to 1)
	perPage := int32(56) // int32 |  (optional) (default to 20)
	model := "model_example" // string | Filter by AI model. Models the API key's user has not enabled are silently dropped. (optional)
	collectionId := openapiclient.getTimeseries_collection_id_parameter{Int32: new(int32)} // GetTimeseriesCollectionIdParameter | One collection/tag ID or a comma-separated list of IDs (optional)
	countryCode := "countryCode_example" // string | One ISO country code or a comma-separated list (e.g. US,GB,DE) (optional)
	languageCode := "languageCode_example" // string | One ISO language code or a comma-separated list (e.g. en,es,de) (optional)
	promptType := "promptType_example" // string | One prompt type or a comma-separated list: informational, navigational, commercial, transactional (optional)
	brandKind := "brandKind_example" // string | Filter by brand kind: brand (own brand/products), brand_other (competitors/other brands), non_brand (generic, no brand named). For fair 1:1 brand-vs-competitor comparisons (visibility, share of voice), use non_brand: brand-focused prompts skew results toward the brand they name. The in-app Overview page applies non_brand by default. (optional)
	from := time.Now() // time.Time |  (optional)
	to := time.Now() // time.Time | End of the window. A date-only value such as 2026-09-01 covers that whole day. Pass a full timestamp to end the window earlier. (optional)
	output := "output_example" // string | Rectangular output for BI tools (Tableau, Excel, Sheets, ELT). Omit for the default nested JSON. 'flat' returns the same metadata plus 'columns' and 'rows'; 'csv' returns those rows as text/csv. Errors are always returned as JSON. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.PromptsAPI.ListPrompts(context.Background()).ProjectId(projectId).Page(page).PerPage(perPage).Model(model).CollectionId(collectionId).CountryCode(countryCode).LanguageCode(languageCode).PromptType(promptType).BrandKind(brandKind).From(from).To(to).Output(output).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PromptsAPI.ListPrompts``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListPromptsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **projectId** | **int32** | Project ID | 
 **page** | **int32** |  | [default to 1]
 **perPage** | **int32** |  | [default to 20]
 **model** | **string** | Filter by AI model. Models the API key&#39;s user has not enabled are silently dropped. | 
 **collectionId** | [**GetTimeseriesCollectionIdParameter**](GetTimeseriesCollectionIdParameter.md) | One collection/tag ID or a comma-separated list of IDs | 
 **countryCode** | **string** | One ISO country code or a comma-separated list (e.g. US,GB,DE) | 
 **languageCode** | **string** | One ISO language code or a comma-separated list (e.g. en,es,de) | 
 **promptType** | **string** | One prompt type or a comma-separated list: informational, navigational, commercial, transactional | 
 **brandKind** | **string** | Filter by brand kind: brand (own brand/products), brand_other (competitors/other brands), non_brand (generic, no brand named). For fair 1:1 brand-vs-competitor comparisons (visibility, share of voice), use non_brand: brand-focused prompts skew results toward the brand they name. The in-app Overview page applies non_brand by default. | 
 **from** | **time.Time** |  | 
 **to** | **time.Time** | End of the window. A date-only value such as 2026-09-01 covers that whole day. Pass a full timestamp to end the window earlier. | 
 **output** | **string** | Rectangular output for BI tools (Tableau, Excel, Sheets, ELT). Omit for the default nested JSON. &#39;flat&#39; returns the same metadata plus &#39;columns&#39; and &#39;rows&#39;; &#39;csv&#39; returns those rows as text/csv. Errors are always returned as JSON. | 

### Return type

 (empty response body)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListQueryFanOuts

> ListQueryFanOuts(ctx).ProjectId(projectId).Page(page).PerPage(perPage).View(view).Order(order).Direction(direction).Query(query).Model(model).CollectionId(collectionId).CountryCode(countryCode).LanguageCode(languageCode).Prompt(prompt).PromptType(promptType).BrandKind(brandKind).Range_(range_).From(from).To(to).Output(output).Execute()

List query fan-out



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
	page := int32(56) // int32 |  (optional) (default to 1)
	perPage := int32(56) // int32 |  (optional) (default to 20)
	view := "view_example" // string | Row shape: one per distinct sub-query, or one per prompt (optional) (default to "query")
	order := "order_example" // string | Sort field; the allowed set depends on view (optional)
	direction := "direction_example" // string |  (optional) (default to "desc")
	query := "query_example" // string | Case-insensitive substring filter on the sub-query text (optional)
	model := "model_example" // string | Filter by AI model. Models the API key's user has not enabled are silently dropped. (optional)
	collectionId := openapiclient.getTimeseries_collection_id_parameter{Int32: new(int32)} // GetTimeseriesCollectionIdParameter | One collection/tag ID or a comma-separated list of IDs (optional)
	countryCode := "countryCode_example" // string | One ISO country code or a comma-separated list (e.g. US,GB,DE) (optional)
	languageCode := "languageCode_example" // string | One ISO language code or a comma-separated list (e.g. en,es,de) (optional)
	prompt := int32(56) // int32 | Filter by prompt ID (optional)
	promptType := "promptType_example" // string | One prompt type or a comma-separated list: informational, navigational, commercial, transactional (optional)
	brandKind := "brandKind_example" // string | Filter by brand kind: brand (own brand/products), brand_other (competitors/other brands), non_brand (generic, no brand named). For fair 1:1 brand-vs-competitor comparisons (visibility, share of voice), use non_brand: brand-focused prompts skew results toward the brand they name. The in-app Overview page applies non_brand by default. (optional)
	range_ := int32(56) // int32 | Number of days to look back (alternative to from/to) (optional)
	from := time.Now() // time.Time |  (optional)
	to := time.Now() // time.Time | End of the window. A date-only value such as 2026-09-01 covers that whole day. Pass a full timestamp to end the window earlier. (optional)
	output := "output_example" // string | Rectangular output for BI tools (Tableau, Excel, Sheets, ELT). Omit for the default nested JSON. 'flat' returns the same metadata plus 'columns' and 'rows'; 'csv' returns those rows as text/csv. Errors are always returned as JSON. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.PromptsAPI.ListQueryFanOuts(context.Background()).ProjectId(projectId).Page(page).PerPage(perPage).View(view).Order(order).Direction(direction).Query(query).Model(model).CollectionId(collectionId).CountryCode(countryCode).LanguageCode(languageCode).Prompt(prompt).PromptType(promptType).BrandKind(brandKind).Range_(range_).From(from).To(to).Output(output).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PromptsAPI.ListQueryFanOuts``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListQueryFanOutsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **projectId** | **int32** | Project ID | 
 **page** | **int32** |  | [default to 1]
 **perPage** | **int32** |  | [default to 20]
 **view** | **string** | Row shape: one per distinct sub-query, or one per prompt | [default to &quot;query&quot;]
 **order** | **string** | Sort field; the allowed set depends on view | 
 **direction** | **string** |  | [default to &quot;desc&quot;]
 **query** | **string** | Case-insensitive substring filter on the sub-query text | 
 **model** | **string** | Filter by AI model. Models the API key&#39;s user has not enabled are silently dropped. | 
 **collectionId** | [**GetTimeseriesCollectionIdParameter**](GetTimeseriesCollectionIdParameter.md) | One collection/tag ID or a comma-separated list of IDs | 
 **countryCode** | **string** | One ISO country code or a comma-separated list (e.g. US,GB,DE) | 
 **languageCode** | **string** | One ISO language code or a comma-separated list (e.g. en,es,de) | 
 **prompt** | **int32** | Filter by prompt ID | 
 **promptType** | **string** | One prompt type or a comma-separated list: informational, navigational, commercial, transactional | 
 **brandKind** | **string** | Filter by brand kind: brand (own brand/products), brand_other (competitors/other brands), non_brand (generic, no brand named). For fair 1:1 brand-vs-competitor comparisons (visibility, share of voice), use non_brand: brand-focused prompts skew results toward the brand they name. The in-app Overview page applies non_brand by default. | 
 **range_** | **int32** | Number of days to look back (alternative to from/to) | 
 **from** | **time.Time** |  | 
 **to** | **time.Time** | End of the window. A date-only value such as 2026-09-01 covers that whole day. Pass a full timestamp to end the window earlier. | 
 **output** | **string** | Rectangular output for BI tools (Tableau, Excel, Sheets, ELT). Omit for the default nested JSON. &#39;flat&#39; returns the same metadata plus &#39;columns&#39; and &#39;rows&#39;; &#39;csv&#39; returns those rows as text/csv. Errors are always returned as JSON. | 

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

