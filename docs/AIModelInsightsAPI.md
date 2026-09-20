# \AIModelInsightsAPI

All URIs are relative to *https://api.llmpulse.ai/api/v1*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetAiModelInsightsSummary**](AIModelInsightsAPI.md#GetAiModelInsightsSummary) | **Get** /reports/ai_model_insights/summary | AI Model Insights summary
[**GetAiModelPositionDistribution**](AIModelInsightsAPI.md#GetAiModelPositionDistribution) | **Get** /reports/ai_model_insights/position_distribution | Position distribution comparison
[**GetAiOverviewResults**](AIModelInsightsAPI.md#GetAiOverviewResults) | **Get** /reports/ai_model_insights/ai_overview_results | Google AI Overview result availability



## GetAiModelInsightsSummary

> GetAiModelInsightsSummary(ctx).ProjectId(projectId).Range_(range_).From(from).To(to).Granularity(granularity).CollectionId(collectionId).CountryCode(countryCode).LanguageCode(languageCode).PromptType(promptType).BrandKind(brandKind).Competitors(competitors).Execute()

AI Model Insights summary



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
	granularity := "granularity_example" // string |  (optional)
	collectionId := openapiclient.getTimeseries_collection_id_parameter{Int32: new(int32)} // GetTimeseriesCollectionIdParameter | One collection/tag ID or a comma-separated list of IDs (optional)
	countryCode := "countryCode_example" // string | One ISO country code or a comma-separated list (e.g. US,GB,DE) (optional)
	languageCode := "languageCode_example" // string | One ISO language code or a comma-separated list (e.g. en,es,de) (optional)
	promptType := "promptType_example" // string | One prompt type or a comma-separated list: informational, navigational, commercial, transactional (optional)
	brandKind := "brandKind_example" // string | Filter by brand kind: brand (own brand/products), brand_other (competitors/other brands), non_brand (generic, no brand named). For fair 1:1 brand-vs-competitor comparisons (visibility, share of voice), use non_brand: brand-focused prompts skew results toward the brand they name. The in-app Overview page applies non_brand by default. (optional)
	competitors := "competitors_example" // string | Comma-separated competitor IDs (unknown IDs return ERR_INVALID_PARAM) (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.AIModelInsightsAPI.GetAiModelInsightsSummary(context.Background()).ProjectId(projectId).Range_(range_).From(from).To(to).Granularity(granularity).CollectionId(collectionId).CountryCode(countryCode).LanguageCode(languageCode).PromptType(promptType).BrandKind(brandKind).Competitors(competitors).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AIModelInsightsAPI.GetAiModelInsightsSummary``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetAiModelInsightsSummaryRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **projectId** | **int32** | Project ID | 
 **range_** | **int32** | Number of days to look back (alternative to from/to) | 
 **from** | **time.Time** |  | 
 **to** | **time.Time** | End of the window. A date-only value such as 2026-09-01 covers that whole day. Pass a full timestamp to end the window earlier. | 
 **granularity** | **string** |  | 
 **collectionId** | [**GetTimeseriesCollectionIdParameter**](GetTimeseriesCollectionIdParameter.md) | One collection/tag ID or a comma-separated list of IDs | 
 **countryCode** | **string** | One ISO country code or a comma-separated list (e.g. US,GB,DE) | 
 **languageCode** | **string** | One ISO language code or a comma-separated list (e.g. en,es,de) | 
 **promptType** | **string** | One prompt type or a comma-separated list: informational, navigational, commercial, transactional | 
 **brandKind** | **string** | Filter by brand kind: brand (own brand/products), brand_other (competitors/other brands), non_brand (generic, no brand named). For fair 1:1 brand-vs-competitor comparisons (visibility, share of voice), use non_brand: brand-focused prompts skew results toward the brand they name. The in-app Overview page applies non_brand by default. | 
 **competitors** | **string** | Comma-separated competitor IDs (unknown IDs return ERR_INVALID_PARAM) | 

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


## GetAiModelPositionDistribution

> GetAiModelPositionDistribution(ctx).ProjectId(projectId).Range_(range_).From(from).To(to).Granularity(granularity).CollectionId(collectionId).CountryCode(countryCode).LanguageCode(languageCode).PromptType(promptType).BrandKind(brandKind).Model(model).Brand1(brand1).Brand2(brand2).Execute()

Position distribution comparison

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
	granularity := "granularity_example" // string |  (optional)
	collectionId := openapiclient.getTimeseries_collection_id_parameter{Int32: new(int32)} // GetTimeseriesCollectionIdParameter | One collection/tag ID or a comma-separated list of IDs (optional)
	countryCode := "countryCode_example" // string | One ISO country code or a comma-separated list (e.g. US,GB,DE) (optional)
	languageCode := "languageCode_example" // string | One ISO language code or a comma-separated list (e.g. en,es,de) (optional)
	promptType := "promptType_example" // string | One prompt type or a comma-separated list: informational, navigational, commercial, transactional (optional)
	brandKind := "brandKind_example" // string | Filter by brand kind: brand (own brand/products), brand_other (competitors/other brands), non_brand (generic, no brand named). For fair 1:1 brand-vs-competitor comparisons (visibility, share of voice), use non_brand: brand-focused prompts skew results toward the brand they name. The in-app Overview page applies non_brand by default. (optional)
	model := "model_example" // string | Filter by AI model. Models the API key's user has not enabled are silently dropped. (optional)
	brand1 := int32(56) // int32 | Competitor ID for the first comparison brand (omit to compare project brand) (optional)
	brand2 := int32(56) // int32 |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.AIModelInsightsAPI.GetAiModelPositionDistribution(context.Background()).ProjectId(projectId).Range_(range_).From(from).To(to).Granularity(granularity).CollectionId(collectionId).CountryCode(countryCode).LanguageCode(languageCode).PromptType(promptType).BrandKind(brandKind).Model(model).Brand1(brand1).Brand2(brand2).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AIModelInsightsAPI.GetAiModelPositionDistribution``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetAiModelPositionDistributionRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **projectId** | **int32** | Project ID | 
 **range_** | **int32** | Number of days to look back (alternative to from/to) | 
 **from** | **time.Time** |  | 
 **to** | **time.Time** | End of the window. A date-only value such as 2026-09-01 covers that whole day. Pass a full timestamp to end the window earlier. | 
 **granularity** | **string** |  | 
 **collectionId** | [**GetTimeseriesCollectionIdParameter**](GetTimeseriesCollectionIdParameter.md) | One collection/tag ID or a comma-separated list of IDs | 
 **countryCode** | **string** | One ISO country code or a comma-separated list (e.g. US,GB,DE) | 
 **languageCode** | **string** | One ISO language code or a comma-separated list (e.g. en,es,de) | 
 **promptType** | **string** | One prompt type or a comma-separated list: informational, navigational, commercial, transactional | 
 **brandKind** | **string** | Filter by brand kind: brand (own brand/products), brand_other (competitors/other brands), non_brand (generic, no brand named). For fair 1:1 brand-vs-competitor comparisons (visibility, share of voice), use non_brand: brand-focused prompts skew results toward the brand they name. The in-app Overview page applies non_brand by default. | 
 **model** | **string** | Filter by AI model. Models the API key&#39;s user has not enabled are silently dropped. | 
 **brand1** | **int32** | Competitor ID for the first comparison brand (omit to compare project brand) | 
 **brand2** | **int32** |  | 

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


## GetAiOverviewResults

> GetAiOverviewResults(ctx).ProjectId(projectId).Range_(range_).From(from).To(to).Granularity(granularity).CollectionId(collectionId).CountryCode(countryCode).LanguageCode(languageCode).PromptType(promptType).BrandKind(brandKind).Page(page).PerPage(perPage).Execute()

Google AI Overview result availability

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
	granularity := "granularity_example" // string |  (optional)
	collectionId := openapiclient.getTimeseries_collection_id_parameter{Int32: new(int32)} // GetTimeseriesCollectionIdParameter | One collection/tag ID or a comma-separated list of IDs (optional)
	countryCode := "countryCode_example" // string | One ISO country code or a comma-separated list (e.g. US,GB,DE) (optional)
	languageCode := "languageCode_example" // string | One ISO language code or a comma-separated list (e.g. en,es,de) (optional)
	promptType := "promptType_example" // string | One prompt type or a comma-separated list: informational, navigational, commercial, transactional (optional)
	brandKind := "brandKind_example" // string | Filter by brand kind: brand (own brand/products), brand_other (competitors/other brands), non_brand (generic, no brand named). For fair 1:1 brand-vs-competitor comparisons (visibility, share of voice), use non_brand: brand-focused prompts skew results toward the brand they name. The in-app Overview page applies non_brand by default. (optional)
	page := int32(56) // int32 |  (optional) (default to 1)
	perPage := int32(56) // int32 |  (optional) (default to 20)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.AIModelInsightsAPI.GetAiOverviewResults(context.Background()).ProjectId(projectId).Range_(range_).From(from).To(to).Granularity(granularity).CollectionId(collectionId).CountryCode(countryCode).LanguageCode(languageCode).PromptType(promptType).BrandKind(brandKind).Page(page).PerPage(perPage).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AIModelInsightsAPI.GetAiOverviewResults``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetAiOverviewResultsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **projectId** | **int32** | Project ID | 
 **range_** | **int32** | Number of days to look back (alternative to from/to) | 
 **from** | **time.Time** |  | 
 **to** | **time.Time** | End of the window. A date-only value such as 2026-09-01 covers that whole day. Pass a full timestamp to end the window earlier. | 
 **granularity** | **string** |  | 
 **collectionId** | [**GetTimeseriesCollectionIdParameter**](GetTimeseriesCollectionIdParameter.md) | One collection/tag ID or a comma-separated list of IDs | 
 **countryCode** | **string** | One ISO country code or a comma-separated list (e.g. US,GB,DE) | 
 **languageCode** | **string** | One ISO language code or a comma-separated list (e.g. en,es,de) | 
 **promptType** | **string** | One prompt type or a comma-separated list: informational, navigational, commercial, transactional | 
 **brandKind** | **string** | Filter by brand kind: brand (own brand/products), brand_other (competitors/other brands), non_brand (generic, no brand named). For fair 1:1 brand-vs-competitor comparisons (visibility, share of voice), use non_brand: brand-focused prompts skew results toward the brand they name. The in-app Overview page applies non_brand by default. | 
 **page** | **int32** |  | [default to 1]
 **perPage** | **int32** |  | [default to 20]

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

