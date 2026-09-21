# \SentimentsAPI

All URIs are relative to *https://api.llmpulse.ai/api/v1*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ListSentimentCategories**](SentimentsAPI.md#ListSentimentCategories) | **Get** /dimensions/sentiments | List sentiment categories
[**ListSentimentRecords**](SentimentsAPI.md#ListSentimentRecords) | **Get** /sentiments | List sentiment records



## ListSentimentCategories

> ListSentimentCategories(ctx).ProjectId(projectId).Output(output).Execute()

List sentiment categories



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
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListSentimentRecords

> ListSentimentRecords(ctx).ProjectId(projectId).CompetitorId(competitorId).BrandOnly(brandOnly).Analysis(analysis).Model(model).CollectionId(collectionId).CountryCode(countryCode).LanguageCode(languageCode).From(from).To(to).Page(page).PerPage(perPage).Execute()

List sentiment records

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
	model := "model_example" // string | Filter by AI model. Models the API key's user has not enabled are silently dropped. (optional)
	collectionId := "12,34" // string | One collection/tag ID or a comma-separated list of IDs. A query value is always a string on the wire, so it is typed as one: the previous integer-or-string union made generators emit a wrapper type they could not serialize. (optional)
	countryCode := "countryCode_example" // string | One ISO country code or a comma-separated list (e.g. US,GB,DE) (optional)
	languageCode := "languageCode_example" // string | One ISO language code or a comma-separated list (e.g. en,es,de) (optional)
	from := time.Now() // time.Time |  (optional)
	to := time.Now() // time.Time | End of the window. A date-only value such as 2026-09-01 covers that whole day. Pass a full timestamp to end the window earlier. (optional)
	page := int32(56) // int32 |  (optional) (default to 1)
	perPage := int32(56) // int32 |  (optional) (default to 20)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.SentimentsAPI.ListSentimentRecords(context.Background()).ProjectId(projectId).CompetitorId(competitorId).BrandOnly(brandOnly).Analysis(analysis).Model(model).CollectionId(collectionId).CountryCode(countryCode).LanguageCode(languageCode).From(from).To(to).Page(page).PerPage(perPage).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SentimentsAPI.ListSentimentRecords``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
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
 **model** | **string** | Filter by AI model. Models the API key&#39;s user has not enabled are silently dropped. | 
 **collectionId** | **string** | One collection/tag ID or a comma-separated list of IDs. A query value is always a string on the wire, so it is typed as one: the previous integer-or-string union made generators emit a wrapper type they could not serialize. | 
 **countryCode** | **string** | One ISO country code or a comma-separated list (e.g. US,GB,DE) | 
 **languageCode** | **string** | One ISO language code or a comma-separated list (e.g. en,es,de) | 
 **from** | **time.Time** |  | 
 **to** | **time.Time** | End of the window. A date-only value such as 2026-09-01 covers that whole day. Pass a full timestamp to end the window earlier. | 
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

