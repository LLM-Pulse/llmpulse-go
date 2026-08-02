# \SentimentsAPI

All URIs are relative to *https://api.llmpulse.ai/api/v1*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ListSentimentRecords**](SentimentsAPI.md#ListSentimentRecords) | **Get** /sentiments | List sentiment records



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
	analysis := "analysis_example" // string |  (optional)
	model := "model_example" // string | Filter by AI model. Models the API key's user has not enabled are silently dropped. (optional)
	collectionId := int32(56) // int32 |  (optional)
	countryCode := "countryCode_example" // string | ISO country code (e.g. US, GB, DE) (optional)
	languageCode := "languageCode_example" // string | ISO language code (e.g. en, es, de) (optional)
	from := time.Now() // time.Time |  (optional)
	to := time.Now() // time.Time |  (optional)
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
 **analysis** | **string** |  | 
 **model** | **string** | Filter by AI model. Models the API key&#39;s user has not enabled are silently dropped. | 
 **collectionId** | **int32** |  | 
 **countryCode** | **string** | ISO country code (e.g. US, GB, DE) | 
 **languageCode** | **string** | ISO language code (e.g. en, es, de) | 
 **from** | **time.Time** |  | 
 **to** | **time.Time** |  | 
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

