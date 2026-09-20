# \SourcesCitationIntelligenceAPI

All URIs are relative to *https://api.llmpulse.ai/api/v1*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetCitedUrlContent**](SourcesCitationIntelligenceAPI.md#GetCitedUrlContent) | **Get** /citation_intelligence/urls/{url_sha256}/content | Cited URL cached content
[**GetCitedUrlDetail**](SourcesCitationIntelligenceAPI.md#GetCitedUrlDetail) | **Get** /citation_intelligence/urls/{url_sha256} | Cited URL detail
[**GetMentionsByCitingDomain**](SourcesCitationIntelligenceAPI.md#GetMentionsByCitingDomain) | **Get** /citation_intelligence/mentions_by_domain | Mention share by citing domain
[**ListCitationGroups**](SourcesCitationIntelligenceAPI.md#ListCitationGroups) | **Get** /citation_intelligence/groups | Grouped citation intelligence
[**ListCitedUrlOccurrences**](SourcesCitationIntelligenceAPI.md#ListCitedUrlOccurrences) | **Get** /citation_intelligence/urls/{url_sha256}/occurrences | Cited URL occurrences
[**ListSources**](SourcesCitationIntelligenceAPI.md#ListSources) | **Get** /dimensions/sources | List source URLs



## GetCitedUrlContent

> GetCitedUrlContent(ctx, urlSha256).ProjectId(projectId).Execute()

Cited URL cached content



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
	urlSha256 := "urlSha256_example" // string | 64-character hex SHA-256 of the cited URL

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.SourcesCitationIntelligenceAPI.GetCitedUrlContent(context.Background(), urlSha256).ProjectId(projectId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SourcesCitationIntelligenceAPI.GetCitedUrlContent``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**urlSha256** | **string** | 64-character hex SHA-256 of the cited URL | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetCitedUrlContentRequest struct via the builder pattern


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


## GetCitedUrlDetail

> GetCitedUrlDetail(ctx, urlSha256).ProjectId(projectId).Execute()

Cited URL detail



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
	urlSha256 := "urlSha256_example" // string | 64-character hex SHA-256 of the cited URL

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.SourcesCitationIntelligenceAPI.GetCitedUrlDetail(context.Background(), urlSha256).ProjectId(projectId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SourcesCitationIntelligenceAPI.GetCitedUrlDetail``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**urlSha256** | **string** | 64-character hex SHA-256 of the cited URL | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetCitedUrlDetailRequest struct via the builder pattern


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


## GetMentionsByCitingDomain

> GetMentionsByCitingDomain(ctx).ProjectId(projectId).Domains(domains).Model(model).CollectionId(collectionId).CountryCode(countryCode).LanguageCode(languageCode).Prompt(prompt).BrandKind(brandKind).From(from).To(to).Execute()

Mention share by citing domain



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
	domains := []string{"Inner_example"} // []string | Source domains to analyze, e.g. domains[]=gmac.com&domains[]=educaweb.com
	model := "model_example" // string | Filter by AI model. Models the API key's user has not enabled are silently dropped. (optional)
	collectionId := openapiclient.getTimeseries_collection_id_parameter{Int32: new(int32)} // GetTimeseriesCollectionIdParameter | One collection/tag ID or a comma-separated list of IDs (optional)
	countryCode := "countryCode_example" // string | One ISO country code or a comma-separated list (e.g. US,GB,DE) (optional)
	languageCode := "languageCode_example" // string | One ISO language code or a comma-separated list (e.g. en,es,de) (optional)
	prompt := int32(56) // int32 | Filter by prompt ID (optional)
	brandKind := "brandKind_example" // string | Filter by brand kind: brand (own brand/products), brand_other (competitors/other brands), non_brand (generic, no brand named). For fair 1:1 brand-vs-competitor comparisons (visibility, share of voice), use non_brand: brand-focused prompts skew results toward the brand they name. The in-app Overview page applies non_brand by default. (optional)
	from := time.Now() // time.Time |  (optional)
	to := time.Now() // time.Time | End of the window. A date-only value such as 2026-09-01 covers that whole day. Pass a full timestamp to end the window earlier. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.SourcesCitationIntelligenceAPI.GetMentionsByCitingDomain(context.Background()).ProjectId(projectId).Domains(domains).Model(model).CollectionId(collectionId).CountryCode(countryCode).LanguageCode(languageCode).Prompt(prompt).BrandKind(brandKind).From(from).To(to).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SourcesCitationIntelligenceAPI.GetMentionsByCitingDomain``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetMentionsByCitingDomainRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **projectId** | **int32** | Project ID | 
 **domains** | **[]string** | Source domains to analyze, e.g. domains[]&#x3D;gmac.com&amp;domains[]&#x3D;educaweb.com | 
 **model** | **string** | Filter by AI model. Models the API key&#39;s user has not enabled are silently dropped. | 
 **collectionId** | [**GetTimeseriesCollectionIdParameter**](GetTimeseriesCollectionIdParameter.md) | One collection/tag ID or a comma-separated list of IDs | 
 **countryCode** | **string** | One ISO country code or a comma-separated list (e.g. US,GB,DE) | 
 **languageCode** | **string** | One ISO language code or a comma-separated list (e.g. en,es,de) | 
 **prompt** | **int32** | Filter by prompt ID | 
 **brandKind** | **string** | Filter by brand kind: brand (own brand/products), brand_other (competitors/other brands), non_brand (generic, no brand named). For fair 1:1 brand-vs-competitor comparisons (visibility, share of voice), use non_brand: brand-focused prompts skew results toward the brand they name. The in-app Overview page applies non_brand by default. | 
 **from** | **time.Time** |  | 
 **to** | **time.Time** | End of the window. A date-only value such as 2026-09-01 covers that whole day. Pass a full timestamp to end the window earlier. | 

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


## ListCitationGroups

> ListCitationGroups(ctx).ProjectId(projectId).View(view).Page(page).PerPage(perPage).Order(order).Direction(direction).Model(model).CollectionId(collectionId).CountryCode(countryCode).LanguageCode(languageCode).Prompt(prompt).From(from).To(to).Query(query).SourceType(sourceType).Sentiment(sentiment).ContentGap(contentGap).Execute()

Grouped citation intelligence



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
	view := "view_example" // string |  (optional) (default to "url")
	page := int32(56) // int32 |  (optional) (default to 1)
	perPage := int32(56) // int32 |  (optional) (default to 20)
	order := "order_example" // string |  (optional)
	direction := "direction_example" // string |  (optional)
	model := "model_example" // string | Filter by AI model. Models the API key's user has not enabled are silently dropped. (optional)
	collectionId := openapiclient.getTimeseries_collection_id_parameter{Int32: new(int32)} // GetTimeseriesCollectionIdParameter | One collection/tag ID or a comma-separated list of IDs (optional)
	countryCode := "countryCode_example" // string | One ISO country code or a comma-separated list (e.g. US,GB,DE) (optional)
	languageCode := "languageCode_example" // string | One ISO language code or a comma-separated list (e.g. en,es,de) (optional)
	prompt := int32(56) // int32 | Filter by prompt ID (optional)
	from := time.Now() // time.Time |  (optional)
	to := time.Now() // time.Time | End of the window. A date-only value such as 2026-09-01 covers that whole day. Pass a full timestamp to end the window earlier. (optional)
	query := "query_example" // string |  (optional)
	sourceType := "sourceType_example" // string |  (optional)
	sentiment := "sentiment_example" // string |  (optional)
	contentGap := "contentGap_example" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.SourcesCitationIntelligenceAPI.ListCitationGroups(context.Background()).ProjectId(projectId).View(view).Page(page).PerPage(perPage).Order(order).Direction(direction).Model(model).CollectionId(collectionId).CountryCode(countryCode).LanguageCode(languageCode).Prompt(prompt).From(from).To(to).Query(query).SourceType(sourceType).Sentiment(sentiment).ContentGap(contentGap).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SourcesCitationIntelligenceAPI.ListCitationGroups``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListCitationGroupsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **projectId** | **int32** | Project ID | 
 **view** | **string** |  | [default to &quot;url&quot;]
 **page** | **int32** |  | [default to 1]
 **perPage** | **int32** |  | [default to 20]
 **order** | **string** |  | 
 **direction** | **string** |  | 
 **model** | **string** | Filter by AI model. Models the API key&#39;s user has not enabled are silently dropped. | 
 **collectionId** | [**GetTimeseriesCollectionIdParameter**](GetTimeseriesCollectionIdParameter.md) | One collection/tag ID or a comma-separated list of IDs | 
 **countryCode** | **string** | One ISO country code or a comma-separated list (e.g. US,GB,DE) | 
 **languageCode** | **string** | One ISO language code or a comma-separated list (e.g. en,es,de) | 
 **prompt** | **int32** | Filter by prompt ID | 
 **from** | **time.Time** |  | 
 **to** | **time.Time** | End of the window. A date-only value such as 2026-09-01 covers that whole day. Pass a full timestamp to end the window earlier. | 
 **query** | **string** |  | 
 **sourceType** | **string** |  | 
 **sentiment** | **string** |  | 
 **contentGap** | **string** |  | 

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


## ListCitedUrlOccurrences

> ListCitedUrlOccurrences(ctx, urlSha256).ProjectId(projectId).Page(page).PerPage(perPage).Execute()

Cited URL occurrences

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
	urlSha256 := "urlSha256_example" // string | 64-character hex SHA-256 of the cited URL
	page := int32(56) // int32 |  (optional) (default to 1)
	perPage := int32(56) // int32 |  (optional) (default to 20)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.SourcesCitationIntelligenceAPI.ListCitedUrlOccurrences(context.Background(), urlSha256).ProjectId(projectId).Page(page).PerPage(perPage).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SourcesCitationIntelligenceAPI.ListCitedUrlOccurrences``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**urlSha256** | **string** | 64-character hex SHA-256 of the cited URL | 

### Other Parameters

Other parameters are passed through a pointer to a apiListCitedUrlOccurrencesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **projectId** | **int32** | Project ID | 

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


## ListSources

> ListSources(ctx).ProjectId(projectId).Page(page).PerPage(perPage).Model(model).CollectionId(collectionId).CountryCode(countryCode).LanguageCode(languageCode).Prompt(prompt).From(from).To(to).SourceType(sourceType).MentionFilter(mentionFilter).Competitors(competitors).Output(output).Execute()

List source URLs

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
	sourceType := "sourceType_example" // string | Filter by source ownership. Owned and competitor matching honor the project's exact-subdomain setting. (optional)
	mentionFilter := "mentionFilter_example" // string | Filter by which brands are mentioned, as a two-axis matrix (your brand x competitors): mentions_you / not_mentions_you, mentions_competitor / not_mentions_competitor, and the four combined cells you_and_competitor, competitor_not_you (a rival wins and you are absent), you_not_competitor, no_brands (no tracked brand appears, i.e. open space). Combine with 'competitors' to narrow the competitor side to specific rivals; on a negative cell that reads 'none of these'. On /dimensions/sources it applies to the crawled content of each cited page instead of the answer text. The legacy value 'competitors_only' is still accepted as an alias of competitor_not_you. (optional)
	competitors := "competitors_example" // string | Comma-separated competitor IDs (unknown IDs return ERR_INVALID_PARAM) (optional)
	output := "output_example" // string | Rectangular output for BI tools (Tableau, Excel, Sheets, ELT). Omit for the default nested JSON. 'flat' returns the same metadata plus 'columns' and 'rows'; 'csv' returns those rows as text/csv. Errors are always returned as JSON. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.SourcesCitationIntelligenceAPI.ListSources(context.Background()).ProjectId(projectId).Page(page).PerPage(perPage).Model(model).CollectionId(collectionId).CountryCode(countryCode).LanguageCode(languageCode).Prompt(prompt).From(from).To(to).SourceType(sourceType).MentionFilter(mentionFilter).Competitors(competitors).Output(output).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SourcesCitationIntelligenceAPI.ListSources``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListSourcesRequest struct via the builder pattern


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
 **sourceType** | **string** | Filter by source ownership. Owned and competitor matching honor the project&#39;s exact-subdomain setting. | 
 **mentionFilter** | **string** | Filter by which brands are mentioned, as a two-axis matrix (your brand x competitors): mentions_you / not_mentions_you, mentions_competitor / not_mentions_competitor, and the four combined cells you_and_competitor, competitor_not_you (a rival wins and you are absent), you_not_competitor, no_brands (no tracked brand appears, i.e. open space). Combine with &#39;competitors&#39; to narrow the competitor side to specific rivals; on a negative cell that reads &#39;none of these&#39;. On /dimensions/sources it applies to the crawled content of each cited page instead of the answer text. The legacy value &#39;competitors_only&#39; is still accepted as an alias of competitor_not_you. | 
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

