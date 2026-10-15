# \SentimentsAPI

All URIs are relative to *https://api.llmpulse.ai/api/v1*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetSentimentTags**](SentimentsAPI.md#GetSentimentTags) | **Get** /reports/sentiment/tags | Sentiment by tag (Growth plan or above)
[**GetSentimentTopics**](SentimentsAPI.md#GetSentimentTopics) | **Get** /reports/sentiment/topics | Sentiment by topic (Growth plan or above)
[**ListSentimentCategories**](SentimentsAPI.md#ListSentimentCategories) | **Get** /dimensions/sentiments | List sentiment categories (Growth plan or above)
[**ListSentimentRecords**](SentimentsAPI.md#ListSentimentRecords) | **Get** /sentiments | List sentiment records (Growth plan or above)



## GetSentimentTags

> SentimentTagsResponse GetSentimentTags(ctx).ProjectId(projectId).Range_(range_).From(from).To(to).Model(model).CollectionId(collectionId).CountryCode(countryCode).LanguageCode(languageCode).BrandKind(brandKind).Analysis(analysis).Topic(topic).Query(query).Brand(brand).Sort(sort).SortDir(sortDir).Page(page).PerPage(perPage).Output(output).Execute()

Sentiment by tag (Growth plan or above)



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
	range_ := int32(56) // int32 | Number of days to look back, today included (default 28, like the Sentiment page). Ignored when from or to is given. (optional)
	from := time.Now() // time.Time |  (optional)
	to := time.Now() // time.Time | End of the window. A date-only value such as 2026-09-01 covers that whole day. Pass a full timestamp to end the window earlier. (optional)
	model := "model_example" // string | Filter by one AI model. It must be a model enabled for the API key's user: an unknown value, or a model the user has not enabled, returns 422 ERR_INVALID_PARAM with the valid values in the message. (optional)
	collectionId := "12,34" // string | One collection/tag ID or a comma-separated list of IDs. A query value is always a string on the wire, so it is typed as one: the previous integer-or-string union made generators emit a wrapper type they could not serialize. (optional)
	countryCode := "countryCode_example" // string | One ISO country code or a comma-separated list (e.g. US,GB,DE) (optional)
	languageCode := "languageCode_example" // string | One ISO language code or a comma-separated list (e.g. en,es,de) (optional)
	brandKind := "brandKind_example" // string | Filter by brand kind: brand (own brand/products), brand_other (competitors/other brands), non_brand (generic, no brand named). For fair 1:1 brand-vs-competitor comparisons (visibility, share of voice), use non_brand: brand-focused prompts skew results toward the brand they name. The in-app Overview page applies non_brand by default. (optional)
	analysis := "analysis_example" // string | One sentiment level or a comma-separated list: very_positive, positive, neutral, negative, very_negative (optional)
	topic := "topic_example" // string | Only sentiments tagged with this topic (case-insensitive) (optional)
	query := "query_example" // string | Only sentiments whose answer or prompt text contains this text (optional)
	brand := "brand_example" // string | Whose sentiment to count. Empty or omitted for your own brand, all for every brand, or a competitor id (an unknown id returns ERR_INVALID_PARAM). (optional)
	sort := "sort_example" // string | Sort column: mentions, name (the topic or tag), positive, negative or neutral (their shares) or net_score. Ties sort by name. (optional) (default to "mentions")
	sortDir := "sortDir_example" // string |  (optional) (default to "desc")
	page := int32(56) // int32 |  (optional) (default to 1)
	perPage := int32(56) // int32 |  (optional) (default to 20)
	output := "output_example" // string | Rectangular output for BI tools (Tableau, Excel, Sheets, ELT). Omit for the default nested JSON. 'flat' returns the same metadata plus 'columns' and 'rows'; 'csv' returns those rows as text/csv. Errors are always returned as JSON. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SentimentsAPI.GetSentimentTags(context.Background()).ProjectId(projectId).Range_(range_).From(from).To(to).Model(model).CollectionId(collectionId).CountryCode(countryCode).LanguageCode(languageCode).BrandKind(brandKind).Analysis(analysis).Topic(topic).Query(query).Brand(brand).Sort(sort).SortDir(sortDir).Page(page).PerPage(perPage).Output(output).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SentimentsAPI.GetSentimentTags``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetSentimentTags`: SentimentTagsResponse
	fmt.Fprintf(os.Stdout, "Response from `SentimentsAPI.GetSentimentTags`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetSentimentTagsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **projectId** | **int32** | Project ID | 
 **range_** | **int32** | Number of days to look back, today included (default 28, like the Sentiment page). Ignored when from or to is given. | 
 **from** | **time.Time** |  | 
 **to** | **time.Time** | End of the window. A date-only value such as 2026-09-01 covers that whole day. Pass a full timestamp to end the window earlier. | 
 **model** | **string** | Filter by one AI model. It must be a model enabled for the API key&#39;s user: an unknown value, or a model the user has not enabled, returns 422 ERR_INVALID_PARAM with the valid values in the message. | 
 **collectionId** | **string** | One collection/tag ID or a comma-separated list of IDs. A query value is always a string on the wire, so it is typed as one: the previous integer-or-string union made generators emit a wrapper type they could not serialize. | 
 **countryCode** | **string** | One ISO country code or a comma-separated list (e.g. US,GB,DE) | 
 **languageCode** | **string** | One ISO language code or a comma-separated list (e.g. en,es,de) | 
 **brandKind** | **string** | Filter by brand kind: brand (own brand/products), brand_other (competitors/other brands), non_brand (generic, no brand named). For fair 1:1 brand-vs-competitor comparisons (visibility, share of voice), use non_brand: brand-focused prompts skew results toward the brand they name. The in-app Overview page applies non_brand by default. | 
 **analysis** | **string** | One sentiment level or a comma-separated list: very_positive, positive, neutral, negative, very_negative | 
 **topic** | **string** | Only sentiments tagged with this topic (case-insensitive) | 
 **query** | **string** | Only sentiments whose answer or prompt text contains this text | 
 **brand** | **string** | Whose sentiment to count. Empty or omitted for your own brand, all for every brand, or a competitor id (an unknown id returns ERR_INVALID_PARAM). | 
 **sort** | **string** | Sort column: mentions, name (the topic or tag), positive, negative or neutral (their shares) or net_score. Ties sort by name. | [default to &quot;mentions&quot;]
 **sortDir** | **string** |  | [default to &quot;desc&quot;]
 **page** | **int32** |  | [default to 1]
 **perPage** | **int32** |  | [default to 20]
 **output** | **string** | Rectangular output for BI tools (Tableau, Excel, Sheets, ELT). Omit for the default nested JSON. &#39;flat&#39; returns the same metadata plus &#39;columns&#39; and &#39;rows&#39;; &#39;csv&#39; returns those rows as text/csv. Errors are always returned as JSON. | 

### Return type

[**SentimentTagsResponse**](SentimentTagsResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetSentimentTopics

> SentimentTopicsResponse GetSentimentTopics(ctx).ProjectId(projectId).Range_(range_).From(from).To(to).Model(model).CollectionId(collectionId).CountryCode(countryCode).LanguageCode(languageCode).BrandKind(brandKind).Analysis(analysis).Topic(topic).Query(query).Brand(brand).Sort(sort).SortDir(sortDir).Page(page).PerPage(perPage).Output(output).Execute()

Sentiment by topic (Growth plan or above)



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
	range_ := int32(56) // int32 | Number of days to look back, today included (default 28, like the Sentiment page). Ignored when from or to is given. (optional)
	from := time.Now() // time.Time |  (optional)
	to := time.Now() // time.Time | End of the window. A date-only value such as 2026-09-01 covers that whole day. Pass a full timestamp to end the window earlier. (optional)
	model := "model_example" // string | Filter by one AI model. It must be a model enabled for the API key's user: an unknown value, or a model the user has not enabled, returns 422 ERR_INVALID_PARAM with the valid values in the message. (optional)
	collectionId := "12,34" // string | One collection/tag ID or a comma-separated list of IDs. A query value is always a string on the wire, so it is typed as one: the previous integer-or-string union made generators emit a wrapper type they could not serialize. (optional)
	countryCode := "countryCode_example" // string | One ISO country code or a comma-separated list (e.g. US,GB,DE) (optional)
	languageCode := "languageCode_example" // string | One ISO language code or a comma-separated list (e.g. en,es,de) (optional)
	brandKind := "brandKind_example" // string | Filter by brand kind: brand (own brand/products), brand_other (competitors/other brands), non_brand (generic, no brand named). For fair 1:1 brand-vs-competitor comparisons (visibility, share of voice), use non_brand: brand-focused prompts skew results toward the brand they name. The in-app Overview page applies non_brand by default. (optional)
	analysis := "analysis_example" // string | One sentiment level or a comma-separated list: very_positive, positive, neutral, negative, very_negative (optional)
	topic := "topic_example" // string | Only sentiments tagged with this topic (case-insensitive) (optional)
	query := "query_example" // string | Only sentiments whose answer or prompt text contains this text (optional)
	brand := "brand_example" // string | Whose sentiment to count. Empty or omitted for your own brand, all for every brand, or a competitor id (an unknown id returns ERR_INVALID_PARAM). (optional)
	sort := "sort_example" // string | Sort column: mentions, name (the topic or tag), positive, negative or neutral (their shares) or net_score. Ties sort by name. (optional) (default to "mentions")
	sortDir := "sortDir_example" // string |  (optional) (default to "desc")
	page := int32(56) // int32 |  (optional) (default to 1)
	perPage := int32(56) // int32 |  (optional) (default to 20)
	output := "output_example" // string | Rectangular output for BI tools (Tableau, Excel, Sheets, ELT). Omit for the default nested JSON. 'flat' returns the same metadata plus 'columns' and 'rows'; 'csv' returns those rows as text/csv. Errors are always returned as JSON. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SentimentsAPI.GetSentimentTopics(context.Background()).ProjectId(projectId).Range_(range_).From(from).To(to).Model(model).CollectionId(collectionId).CountryCode(countryCode).LanguageCode(languageCode).BrandKind(brandKind).Analysis(analysis).Topic(topic).Query(query).Brand(brand).Sort(sort).SortDir(sortDir).Page(page).PerPage(perPage).Output(output).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SentimentsAPI.GetSentimentTopics``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetSentimentTopics`: SentimentTopicsResponse
	fmt.Fprintf(os.Stdout, "Response from `SentimentsAPI.GetSentimentTopics`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetSentimentTopicsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **projectId** | **int32** | Project ID | 
 **range_** | **int32** | Number of days to look back, today included (default 28, like the Sentiment page). Ignored when from or to is given. | 
 **from** | **time.Time** |  | 
 **to** | **time.Time** | End of the window. A date-only value such as 2026-09-01 covers that whole day. Pass a full timestamp to end the window earlier. | 
 **model** | **string** | Filter by one AI model. It must be a model enabled for the API key&#39;s user: an unknown value, or a model the user has not enabled, returns 422 ERR_INVALID_PARAM with the valid values in the message. | 
 **collectionId** | **string** | One collection/tag ID or a comma-separated list of IDs. A query value is always a string on the wire, so it is typed as one: the previous integer-or-string union made generators emit a wrapper type they could not serialize. | 
 **countryCode** | **string** | One ISO country code or a comma-separated list (e.g. US,GB,DE) | 
 **languageCode** | **string** | One ISO language code or a comma-separated list (e.g. en,es,de) | 
 **brandKind** | **string** | Filter by brand kind: brand (own brand/products), brand_other (competitors/other brands), non_brand (generic, no brand named). For fair 1:1 brand-vs-competitor comparisons (visibility, share of voice), use non_brand: brand-focused prompts skew results toward the brand they name. The in-app Overview page applies non_brand by default. | 
 **analysis** | **string** | One sentiment level or a comma-separated list: very_positive, positive, neutral, negative, very_negative | 
 **topic** | **string** | Only sentiments tagged with this topic (case-insensitive) | 
 **query** | **string** | Only sentiments whose answer or prompt text contains this text | 
 **brand** | **string** | Whose sentiment to count. Empty or omitted for your own brand, all for every brand, or a competitor id (an unknown id returns ERR_INVALID_PARAM). | 
 **sort** | **string** | Sort column: mentions, name (the topic or tag), positive, negative or neutral (their shares) or net_score. Ties sort by name. | [default to &quot;mentions&quot;]
 **sortDir** | **string** |  | [default to &quot;desc&quot;]
 **page** | **int32** |  | [default to 1]
 **perPage** | **int32** |  | [default to 20]
 **output** | **string** | Rectangular output for BI tools (Tableau, Excel, Sheets, ELT). Omit for the default nested JSON. &#39;flat&#39; returns the same metadata plus &#39;columns&#39; and &#39;rows&#39;; &#39;csv&#39; returns those rows as text/csv. Errors are always returned as JSON. | 

### Return type

[**SentimentTopicsResponse**](SentimentTopicsResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListSentimentCategories

> ListSentimentCategories(ctx).ProjectId(projectId).Output(output).Execute()

List sentiment categories (Growth plan or above)



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
	r, err := apiClient.SentimentsAPI.ListSentimentCategories(context.Background()).ProjectId(projectId).Output(output).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SentimentsAPI.ListSentimentCategories``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListSentimentCategoriesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **projectId** | **int32** | Project ID | 
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


## ListSentimentRecords

> SentimentsResponse ListSentimentRecords(ctx).ProjectId(projectId).CompetitorId(competitorId).BrandOnly(brandOnly).Analysis(analysis).Model(model).CollectionId(collectionId).CountryCode(countryCode).LanguageCode(languageCode).From(from).To(to).Page(page).PerPage(perPage).Execute()

List sentiment records (Growth plan or above)



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
	competitorId := int32(56) // int32 |  (optional)
	brandOnly := true // bool |  (optional)
	analysis := "analysis_example" // string | One sentiment level or a comma-separated list: very_positive, positive, neutral, negative, very_negative (optional)
	model := "model_example" // string | Filter by one AI model. Here an unknown value, or a model the API key's user has not enabled, is ignored rather than rejected: the request succeeds and returns the records of every enabled model, as if model were omitted. (optional)
	collectionId := "12,34" // string | One collection/tag ID or a comma-separated list of IDs. A query value is always a string on the wire, so it is typed as one: the previous integer-or-string union made generators emit a wrapper type they could not serialize. (optional)
	countryCode := "countryCode_example" // string | One ISO country code or a comma-separated list (e.g. US,GB,DE) (optional)
	languageCode := "languageCode_example" // string | One ISO language code or a comma-separated list (e.g. en,es,de) (optional)
	from := time.Now() // time.Time |  (optional)
	to := time.Now() // time.Time | End of the window. A date-only value such as 2026-09-01 covers that whole day. Pass a full timestamp to end the window earlier. (optional)
	page := int32(56) // int32 |  (optional) (default to 1)
	perPage := int32(56) // int32 |  (optional) (default to 20)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SentimentsAPI.ListSentimentRecords(context.Background()).ProjectId(projectId).CompetitorId(competitorId).BrandOnly(brandOnly).Analysis(analysis).Model(model).CollectionId(collectionId).CountryCode(countryCode).LanguageCode(languageCode).From(from).To(to).Page(page).PerPage(perPage).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SentimentsAPI.ListSentimentRecords``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListSentimentRecords`: SentimentsResponse
	fmt.Fprintf(os.Stdout, "Response from `SentimentsAPI.ListSentimentRecords`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListSentimentRecordsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **projectId** | **int32** | Project ID | 
 **competitorId** | **int32** |  | 
 **brandOnly** | **bool** |  | 
 **analysis** | **string** | One sentiment level or a comma-separated list: very_positive, positive, neutral, negative, very_negative | 
 **model** | **string** | Filter by one AI model. Here an unknown value, or a model the API key&#39;s user has not enabled, is ignored rather than rejected: the request succeeds and returns the records of every enabled model, as if model were omitted. | 
 **collectionId** | **string** | One collection/tag ID or a comma-separated list of IDs. A query value is always a string on the wire, so it is typed as one: the previous integer-or-string union made generators emit a wrapper type they could not serialize. | 
 **countryCode** | **string** | One ISO country code or a comma-separated list (e.g. US,GB,DE) | 
 **languageCode** | **string** | One ISO language code or a comma-separated list (e.g. en,es,de) | 
 **from** | **time.Time** |  | 
 **to** | **time.Time** | End of the window. A date-only value such as 2026-09-01 covers that whole day. Pass a full timestamp to end the window earlier. | 
 **page** | **int32** |  | [default to 1]
 **perPage** | **int32** |  | [default to 20]

### Return type

[**SentimentsResponse**](SentimentsResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

