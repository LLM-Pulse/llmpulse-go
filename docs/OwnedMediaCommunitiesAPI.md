# \OwnedMediaCommunitiesAPI

All URIs are relative to *https://api.llmpulse.ai/api/v1*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ListOwnedMedia**](OwnedMediaCommunitiesAPI.md#ListOwnedMedia) | **Get** /dimensions/owned_media | List owned-media citations
[**ListRedditCitations**](OwnedMediaCommunitiesAPI.md#ListRedditCitations) | **Get** /dimensions/reddit | List cited Reddit content



## ListOwnedMedia

> ListOwnedMedia(ctx).ProjectId(projectId).Provider(provider).Page(page).PerPage(perPage).View(view).Store(store).Owned(owned).Model(model).CollectionId(collectionId).CountryCode(countryCode).LanguageCode(languageCode).BrandKind(brandKind).Range_(range_).From(from).To(to).Output(output).Execute()

List owned-media citations



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
	provider := "provider_example" // string | The platform to report on
	page := int32(56) // int32 |  (optional) (default to 1)
	perPage := int32(56) // int32 |  (optional) (default to 20)
	view := "view_example" // string | Row shape; the allowed set depends on provider (optional)
	store := "store_example" // string | provider=mobile_apps only (optional) (default to "google_play")
	owned := true // bool | Return only rows belonging to the account's own connected profile (optional)
	model := "model_example" // string | Filter by AI model. Models the API key's user has not enabled are silently dropped. (optional)
	collectionId := openapiclient.getTimeseries_collection_id_parameter{Int32: new(int32)} // GetTimeseriesCollectionIdParameter | One collection/tag ID or a comma-separated list of IDs (optional)
	countryCode := "countryCode_example" // string | One ISO country code or a comma-separated list (e.g. US,GB,DE) (optional)
	languageCode := "languageCode_example" // string | One ISO language code or a comma-separated list (e.g. en,es,de) (optional)
	brandKind := "brandKind_example" // string | Filter by brand kind: brand (own brand/products), brand_other (competitors/other brands), non_brand (generic, no brand named). For fair 1:1 brand-vs-competitor comparisons (visibility, share of voice), use non_brand: brand-focused prompts skew results toward the brand they name. The in-app Overview page applies non_brand by default. (optional)
	range_ := int32(56) // int32 | Number of days to look back (alternative to from/to) (optional)
	from := time.Now() // time.Time |  (optional)
	to := time.Now() // time.Time | End of the window. A date-only value such as 2026-09-01 covers that whole day. Pass a full timestamp to end the window earlier. (optional)
	output := "output_example" // string | Rectangular output for BI tools (Tableau, Excel, Sheets, ELT). Omit for the default nested JSON. 'flat' returns the same metadata plus 'columns' and 'rows'; 'csv' returns those rows as text/csv. Errors are always returned as JSON. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.OwnedMediaCommunitiesAPI.ListOwnedMedia(context.Background()).ProjectId(projectId).Provider(provider).Page(page).PerPage(perPage).View(view).Store(store).Owned(owned).Model(model).CollectionId(collectionId).CountryCode(countryCode).LanguageCode(languageCode).BrandKind(brandKind).Range_(range_).From(from).To(to).Output(output).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OwnedMediaCommunitiesAPI.ListOwnedMedia``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListOwnedMediaRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **projectId** | **int32** | Project ID | 
 **provider** | **string** | The platform to report on | 
 **page** | **int32** |  | [default to 1]
 **perPage** | **int32** |  | [default to 20]
 **view** | **string** | Row shape; the allowed set depends on provider | 
 **store** | **string** | provider&#x3D;mobile_apps only | [default to &quot;google_play&quot;]
 **owned** | **bool** | Return only rows belonging to the account&#39;s own connected profile | 
 **model** | **string** | Filter by AI model. Models the API key&#39;s user has not enabled are silently dropped. | 
 **collectionId** | [**GetTimeseriesCollectionIdParameter**](GetTimeseriesCollectionIdParameter.md) | One collection/tag ID or a comma-separated list of IDs | 
 **countryCode** | **string** | One ISO country code or a comma-separated list (e.g. US,GB,DE) | 
 **languageCode** | **string** | One ISO language code or a comma-separated list (e.g. en,es,de) | 
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


## ListRedditCitations

> ListRedditCitations(ctx).ProjectId(projectId).Page(page).PerPage(perPage).View(view).Subreddit(subreddit).Author(author).Status(status).Owned(owned).Brand(brand).Order(order).Direction(direction).Model(model).CollectionId(collectionId).CountryCode(countryCode).LanguageCode(languageCode).BrandKind(brandKind).Range_(range_).From(from).To(to).Output(output).Execute()

List cited Reddit content



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
	view := "view_example" // string |  (optional) (default to "subreddits")
	subreddit := "subreddit_example" // string | Filter to one subreddit (name without the r/ prefix) (optional)
	author := "author_example" // string | Filter to one Reddit author (optional)
	status := "status_example" // string | view=threads only (optional)
	owned := true // bool | Return only subreddits/authors the account has claimed as its own (optional)
	brand := "brand_example" // string | Filter to citations whose scraped Reddit content mentions a brand: 'brand' for the tracked brand, or a competitor id. Reads the page content, not the AI answer. (optional)
	order := "order_example" // string | Sort field; the allowed set depends on view (optional)
	direction := "direction_example" // string |  (optional) (default to "desc")
	model := "model_example" // string | Filter by AI model. Models the API key's user has not enabled are silently dropped. (optional)
	collectionId := openapiclient.getTimeseries_collection_id_parameter{Int32: new(int32)} // GetTimeseriesCollectionIdParameter | One collection/tag ID or a comma-separated list of IDs (optional)
	countryCode := "countryCode_example" // string | One ISO country code or a comma-separated list (e.g. US,GB,DE) (optional)
	languageCode := "languageCode_example" // string | One ISO language code or a comma-separated list (e.g. en,es,de) (optional)
	brandKind := "brandKind_example" // string | Filter by brand kind: brand (own brand/products), brand_other (competitors/other brands), non_brand (generic, no brand named). For fair 1:1 brand-vs-competitor comparisons (visibility, share of voice), use non_brand: brand-focused prompts skew results toward the brand they name. The in-app Overview page applies non_brand by default. (optional)
	range_ := int32(56) // int32 | Number of days to look back (alternative to from/to) (optional)
	from := time.Now() // time.Time |  (optional)
	to := time.Now() // time.Time | End of the window. A date-only value such as 2026-09-01 covers that whole day. Pass a full timestamp to end the window earlier. (optional)
	output := "output_example" // string | Rectangular output for BI tools (Tableau, Excel, Sheets, ELT). Omit for the default nested JSON. 'flat' returns the same metadata plus 'columns' and 'rows'; 'csv' returns those rows as text/csv. Errors are always returned as JSON. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.OwnedMediaCommunitiesAPI.ListRedditCitations(context.Background()).ProjectId(projectId).Page(page).PerPage(perPage).View(view).Subreddit(subreddit).Author(author).Status(status).Owned(owned).Brand(brand).Order(order).Direction(direction).Model(model).CollectionId(collectionId).CountryCode(countryCode).LanguageCode(languageCode).BrandKind(brandKind).Range_(range_).From(from).To(to).Output(output).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OwnedMediaCommunitiesAPI.ListRedditCitations``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListRedditCitationsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **projectId** | **int32** | Project ID | 
 **page** | **int32** |  | [default to 1]
 **perPage** | **int32** |  | [default to 20]
 **view** | **string** |  | [default to &quot;subreddits&quot;]
 **subreddit** | **string** | Filter to one subreddit (name without the r/ prefix) | 
 **author** | **string** | Filter to one Reddit author | 
 **status** | **string** | view&#x3D;threads only | 
 **owned** | **bool** | Return only subreddits/authors the account has claimed as its own | 
 **brand** | **string** | Filter to citations whose scraped Reddit content mentions a brand: &#39;brand&#39; for the tracked brand, or a competitor id. Reads the page content, not the AI answer. | 
 **order** | **string** | Sort field; the allowed set depends on view | 
 **direction** | **string** |  | [default to &quot;desc&quot;]
 **model** | **string** | Filter by AI model. Models the API key&#39;s user has not enabled are silently dropped. | 
 **collectionId** | [**GetTimeseriesCollectionIdParameter**](GetTimeseriesCollectionIdParameter.md) | One collection/tag ID or a comma-separated list of IDs | 
 **countryCode** | **string** | One ISO country code or a comma-separated list (e.g. US,GB,DE) | 
 **languageCode** | **string** | One ISO language code or a comma-separated list (e.g. en,es,de) | 
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

