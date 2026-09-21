# \ShoppingAdsAPI

All URIs are relative to *https://api.llmpulse.ai/api/v1*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ListAds**](ShoppingAdsAPI.md#ListAds) | **Get** /dimensions/ads | List AI ad placements
[**ListShopping**](ShoppingAdsAPI.md#ListShopping) | **Get** /dimensions/shopping | List shopping results



## ListAds

> ListAds(ctx).ProjectId(projectId).Page(page).PerPage(perPage).View(view).Owned(owned).Order(order).Direction(direction).Query(query).Model(model).CollectionId(collectionId).CountryCode(countryCode).LanguageCode(languageCode).Prompt(prompt).PromptType(promptType).BrandKind(brandKind).Range_(range_).From(from).To(to).Output(output).Execute()

List AI ad placements



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
	view := "view_example" // string | Row shape: one per advertising domain, or one per placement (optional) (default to "advertisers")
	owned := true // bool | Return only placements identified as the tracked brand's own (view=ads) (optional)
	order := "order_example" // string | Sort field; the allowed set depends on view (optional)
	direction := "direction_example" // string | Sort direction for view=advertisers. Defaults to desc, except avg_position and domain which default to asc. (optional)
	query := "query_example" // string | Case-insensitive substring filter on the ad title, domain or snippet (optional)
	model := "model_example" // string | Filter by AI model. Models the API key's user has not enabled are silently dropped. (optional)
	collectionId := "12,34" // string | One collection/tag ID or a comma-separated list of IDs. A query value is always a string on the wire, so it is typed as one: the previous integer-or-string union made generators emit a wrapper type they could not serialize. (optional)
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
	r, err := apiClient.ShoppingAdsAPI.ListAds(context.Background()).ProjectId(projectId).Page(page).PerPage(perPage).View(view).Owned(owned).Order(order).Direction(direction).Query(query).Model(model).CollectionId(collectionId).CountryCode(countryCode).LanguageCode(languageCode).Prompt(prompt).PromptType(promptType).BrandKind(brandKind).Range_(range_).From(from).To(to).Output(output).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ShoppingAdsAPI.ListAds``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListAdsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **projectId** | **int32** | Project ID | 
 **page** | **int32** |  | [default to 1]
 **perPage** | **int32** |  | [default to 20]
 **view** | **string** | Row shape: one per advertising domain, or one per placement | [default to &quot;advertisers&quot;]
 **owned** | **bool** | Return only placements identified as the tracked brand&#39;s own (view&#x3D;ads) | 
 **order** | **string** | Sort field; the allowed set depends on view | 
 **direction** | **string** | Sort direction for view&#x3D;advertisers. Defaults to desc, except avg_position and domain which default to asc. | 
 **query** | **string** | Case-insensitive substring filter on the ad title, domain or snippet | 
 **model** | **string** | Filter by AI model. Models the API key&#39;s user has not enabled are silently dropped. | 
 **collectionId** | **string** | One collection/tag ID or a comma-separated list of IDs. A query value is always a string on the wire, so it is typed as one: the previous integer-or-string union made generators emit a wrapper type they could not serialize. | 
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


## ListShopping

> ListShopping(ctx).ProjectId(projectId).Page(page).PerPage(perPage).View(view).Owned(owned).Order(order).Direction(direction).Query(query).Model(model).CollectionId(collectionId).CountryCode(countryCode).LanguageCode(languageCode).Prompt(prompt).PromptType(promptType).BrandKind(brandKind).Range_(range_).From(from).To(to).Output(output).Execute()

List shopping results



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
	view := "view_example" // string | Row shape: one per distinct product, or one per merchant (optional) (default to "products")
	owned := true // bool | Return only products identified as the tracked brand's own. On view=merchants this narrows to the merchants selling those products; the totals block stays account-wide. (optional)
	order := "order_example" // string | Sort field; the allowed set depends on view (optional)
	direction := "direction_example" // string |  (optional) (default to "desc")
	query := "query_example" // string | Case-insensitive substring filter on the product title (optional)
	model := "model_example" // string | Filter by AI model. Models the API key's user has not enabled are silently dropped. (optional)
	collectionId := "12,34" // string | One collection/tag ID or a comma-separated list of IDs. A query value is always a string on the wire, so it is typed as one: the previous integer-or-string union made generators emit a wrapper type they could not serialize. (optional)
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
	r, err := apiClient.ShoppingAdsAPI.ListShopping(context.Background()).ProjectId(projectId).Page(page).PerPage(perPage).View(view).Owned(owned).Order(order).Direction(direction).Query(query).Model(model).CollectionId(collectionId).CountryCode(countryCode).LanguageCode(languageCode).Prompt(prompt).PromptType(promptType).BrandKind(brandKind).Range_(range_).From(from).To(to).Output(output).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ShoppingAdsAPI.ListShopping``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListShoppingRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **projectId** | **int32** | Project ID | 
 **page** | **int32** |  | [default to 1]
 **perPage** | **int32** |  | [default to 20]
 **view** | **string** | Row shape: one per distinct product, or one per merchant | [default to &quot;products&quot;]
 **owned** | **bool** | Return only products identified as the tracked brand&#39;s own. On view&#x3D;merchants this narrows to the merchants selling those products; the totals block stays account-wide. | 
 **order** | **string** | Sort field; the allowed set depends on view | 
 **direction** | **string** |  | [default to &quot;desc&quot;]
 **query** | **string** | Case-insensitive substring filter on the product title | 
 **model** | **string** | Filter by AI model. Models the API key&#39;s user has not enabled are silently dropped. | 
 **collectionId** | **string** | One collection/tag ID or a comma-separated list of IDs. A query value is always a string on the wire, so it is typed as one: the previous integer-or-string union made generators emit a wrapper type they could not serialize. | 
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

