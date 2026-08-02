# \CitationIntelligenceAPI

All URIs are relative to *https://api.llmpulse.ai/api/v1*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetCitedUrlContent**](CitationIntelligenceAPI.md#GetCitedUrlContent) | **Get** /citation_intelligence/urls/{url_sha256}/content | Cited URL cached content
[**GetCitedUrlDetail**](CitationIntelligenceAPI.md#GetCitedUrlDetail) | **Get** /citation_intelligence/urls/{url_sha256} | Cited URL detail
[**GetMentionsByCitingDomain**](CitationIntelligenceAPI.md#GetMentionsByCitingDomain) | **Get** /citation_intelligence/mentions_by_domain | Mention share by citing domain
[**ListCitationGroups**](CitationIntelligenceAPI.md#ListCitationGroups) | **Get** /citation_intelligence/groups | Grouped citation intelligence
[**ListCitedUrlOccurrences**](CitationIntelligenceAPI.md#ListCitedUrlOccurrences) | **Get** /citation_intelligence/urls/{url_sha256}/occurrences | Cited URL occurrences



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
	r, err := apiClient.CitationIntelligenceAPI.GetCitedUrlContent(context.Background(), urlSha256).ProjectId(projectId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CitationIntelligenceAPI.GetCitedUrlContent``: %v\n", err)
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
	r, err := apiClient.CitationIntelligenceAPI.GetCitedUrlDetail(context.Background(), urlSha256).ProjectId(projectId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CitationIntelligenceAPI.GetCitedUrlDetail``: %v\n", err)
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

> GetMentionsByCitingDomain(ctx).ProjectId(projectId).Domains(domains).Model(model).CollectionId(collectionId).CountryCode(countryCode).LanguageCode(languageCode).Prompt(prompt).From(from).To(to).Execute()

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
	collectionId := int32(56) // int32 |  (optional)
	countryCode := "countryCode_example" // string | ISO country code (e.g. US, GB, DE) (optional)
	languageCode := "languageCode_example" // string | ISO language code (e.g. en, es, de) (optional)
	prompt := int32(56) // int32 | Filter by prompt ID (optional)
	from := time.Now() // time.Time |  (optional)
	to := time.Now() // time.Time |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.CitationIntelligenceAPI.GetMentionsByCitingDomain(context.Background()).ProjectId(projectId).Domains(domains).Model(model).CollectionId(collectionId).CountryCode(countryCode).LanguageCode(languageCode).Prompt(prompt).From(from).To(to).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CitationIntelligenceAPI.GetMentionsByCitingDomain``: %v\n", err)
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
 **collectionId** | **int32** |  | 
 **countryCode** | **string** | ISO country code (e.g. US, GB, DE) | 
 **languageCode** | **string** | ISO language code (e.g. en, es, de) | 
 **prompt** | **int32** | Filter by prompt ID | 
 **from** | **time.Time** |  | 
 **to** | **time.Time** |  | 

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
	collectionId := int32(56) // int32 |  (optional)
	countryCode := "countryCode_example" // string | ISO country code (e.g. US, GB, DE) (optional)
	languageCode := "languageCode_example" // string | ISO language code (e.g. en, es, de) (optional)
	prompt := int32(56) // int32 | Filter by prompt ID (optional)
	from := time.Now() // time.Time |  (optional)
	to := time.Now() // time.Time |  (optional)
	query := "query_example" // string |  (optional)
	sourceType := "sourceType_example" // string |  (optional)
	sentiment := "sentiment_example" // string |  (optional)
	contentGap := "contentGap_example" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.CitationIntelligenceAPI.ListCitationGroups(context.Background()).ProjectId(projectId).View(view).Page(page).PerPage(perPage).Order(order).Direction(direction).Model(model).CollectionId(collectionId).CountryCode(countryCode).LanguageCode(languageCode).Prompt(prompt).From(from).To(to).Query(query).SourceType(sourceType).Sentiment(sentiment).ContentGap(contentGap).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CitationIntelligenceAPI.ListCitationGroups``: %v\n", err)
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
 **collectionId** | **int32** |  | 
 **countryCode** | **string** | ISO country code (e.g. US, GB, DE) | 
 **languageCode** | **string** | ISO language code (e.g. en, es, de) | 
 **prompt** | **int32** | Filter by prompt ID | 
 **from** | **time.Time** |  | 
 **to** | **time.Time** |  | 
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
	r, err := apiClient.CitationIntelligenceAPI.ListCitedUrlOccurrences(context.Background(), urlSha256).ProjectId(projectId).Page(page).PerPage(perPage).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CitationIntelligenceAPI.ListCitedUrlOccurrences``: %v\n", err)
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

