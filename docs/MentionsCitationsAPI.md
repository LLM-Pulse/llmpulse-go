# \MentionsCitationsAPI

All URIs are relative to *https://api.llmpulse.ai/api/v1*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ListAllCitations**](MentionsCitationsAPI.md#ListAllCitations) | **Get** /dimensions/all_citations | List all citations (brand + competitor)
[**ListAllMentions**](MentionsCitationsAPI.md#ListAllMentions) | **Get** /dimensions/all_mentions | List all mentions (brand + competitor)
[**ListCitations**](MentionsCitationsAPI.md#ListCitations) | **Get** /dimensions/citations | List brand citations
[**ListCompetitorCitations**](MentionsCitationsAPI.md#ListCompetitorCitations) | **Get** /dimensions/competitor_citations | List competitor citations
[**ListCompetitorMentions**](MentionsCitationsAPI.md#ListCompetitorMentions) | **Get** /dimensions/competitor_mentions | List competitor mentions
[**ListMentions**](MentionsCitationsAPI.md#ListMentions) | **Get** /dimensions/mentions | List brand mentions



## ListAllCitations

> ListAllCitations(ctx).ProjectId(projectId).Competitors(competitors).Page(page).PerPage(perPage).Model(model).CollectionId(collectionId).Prompt(prompt).From(from).To(to).Output(output).Execute()

List all citations (brand + competitor)



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
	competitors := "competitors_example" // string | Comma-separated competitor IDs (unknown IDs return ERR_INVALID_PARAM) (optional)
	page := int32(56) // int32 |  (optional) (default to 1)
	perPage := int32(56) // int32 |  (optional) (default to 20)
	model := "model_example" // string | Filter by AI model. Models the API key's user has not enabled are silently dropped. (optional)
	collectionId := "12,34" // string | One collection/tag ID or a comma-separated list of IDs. A query value is always a string on the wire, so it is typed as one: the previous integer-or-string union made generators emit a wrapper type they could not serialize. (optional)
	prompt := int32(56) // int32 | Filter by prompt ID (optional)
	from := time.Now() // time.Time |  (optional)
	to := time.Now() // time.Time | End of the window. A date-only value such as 2026-09-01 covers that whole day. Pass a full timestamp to end the window earlier. (optional)
	output := "output_example" // string | Rectangular output for BI tools (Tableau, Excel, Sheets, ELT). Omit for the default nested JSON. 'flat' returns the same metadata plus 'columns' and 'rows'; 'csv' returns those rows as text/csv. Errors are always returned as JSON. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.MentionsCitationsAPI.ListAllCitations(context.Background()).ProjectId(projectId).Competitors(competitors).Page(page).PerPage(perPage).Model(model).CollectionId(collectionId).Prompt(prompt).From(from).To(to).Output(output).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MentionsCitationsAPI.ListAllCitations``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListAllCitationsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **projectId** | **int32** | Project ID | 
 **competitors** | **string** | Comma-separated competitor IDs (unknown IDs return ERR_INVALID_PARAM) | 
 **page** | **int32** |  | [default to 1]
 **perPage** | **int32** |  | [default to 20]
 **model** | **string** | Filter by AI model. Models the API key&#39;s user has not enabled are silently dropped. | 
 **collectionId** | **string** | One collection/tag ID or a comma-separated list of IDs. A query value is always a string on the wire, so it is typed as one: the previous integer-or-string union made generators emit a wrapper type they could not serialize. | 
 **prompt** | **int32** | Filter by prompt ID | 
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


## ListAllMentions

> ListAllMentions(ctx).ProjectId(projectId).Competitors(competitors).Page(page).PerPage(perPage).Model(model).CollectionId(collectionId).Prompt(prompt).From(from).To(to).Output(output).Execute()

List all mentions (brand + competitor)



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
	competitors := "competitors_example" // string | Comma-separated competitor IDs (unknown IDs return ERR_INVALID_PARAM) (optional)
	page := int32(56) // int32 |  (optional) (default to 1)
	perPage := int32(56) // int32 |  (optional) (default to 20)
	model := "model_example" // string | Filter by AI model. Models the API key's user has not enabled are silently dropped. (optional)
	collectionId := "12,34" // string | One collection/tag ID or a comma-separated list of IDs. A query value is always a string on the wire, so it is typed as one: the previous integer-or-string union made generators emit a wrapper type they could not serialize. (optional)
	prompt := int32(56) // int32 | Filter by prompt ID (optional)
	from := time.Now() // time.Time |  (optional)
	to := time.Now() // time.Time | End of the window. A date-only value such as 2026-09-01 covers that whole day. Pass a full timestamp to end the window earlier. (optional)
	output := "output_example" // string | Rectangular output for BI tools (Tableau, Excel, Sheets, ELT). Omit for the default nested JSON. 'flat' returns the same metadata plus 'columns' and 'rows'; 'csv' returns those rows as text/csv. Errors are always returned as JSON. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.MentionsCitationsAPI.ListAllMentions(context.Background()).ProjectId(projectId).Competitors(competitors).Page(page).PerPage(perPage).Model(model).CollectionId(collectionId).Prompt(prompt).From(from).To(to).Output(output).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MentionsCitationsAPI.ListAllMentions``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListAllMentionsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **projectId** | **int32** | Project ID | 
 **competitors** | **string** | Comma-separated competitor IDs (unknown IDs return ERR_INVALID_PARAM) | 
 **page** | **int32** |  | [default to 1]
 **perPage** | **int32** |  | [default to 20]
 **model** | **string** | Filter by AI model. Models the API key&#39;s user has not enabled are silently dropped. | 
 **collectionId** | **string** | One collection/tag ID or a comma-separated list of IDs. A query value is always a string on the wire, so it is typed as one: the previous integer-or-string union made generators emit a wrapper type they could not serialize. | 
 **prompt** | **int32** | Filter by prompt ID | 
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


## ListCitations

> CitationsResponse ListCitations(ctx).ProjectId(projectId).Page(page).PerPage(perPage).Model(model).CollectionId(collectionId).CountryCode(countryCode).LanguageCode(languageCode).Prompt(prompt).From(from).To(to).Output(output).Execute()

List brand citations



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
	collectionId := "12,34" // string | One collection/tag ID or a comma-separated list of IDs. A query value is always a string on the wire, so it is typed as one: the previous integer-or-string union made generators emit a wrapper type they could not serialize. (optional)
	countryCode := "countryCode_example" // string | One ISO country code or a comma-separated list (e.g. US,GB,DE) (optional)
	languageCode := "languageCode_example" // string | One ISO language code or a comma-separated list (e.g. en,es,de) (optional)
	prompt := int32(56) // int32 | Filter by prompt ID (optional)
	from := time.Now() // time.Time |  (optional)
	to := time.Now() // time.Time | End of the window. A date-only value such as 2026-09-01 covers that whole day. Pass a full timestamp to end the window earlier. (optional)
	output := "output_example" // string | Rectangular output for BI tools (Tableau, Excel, Sheets, ELT). Omit for the default nested JSON. 'flat' returns the same metadata plus 'columns' and 'rows'; 'csv' returns those rows as text/csv. Errors are always returned as JSON. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MentionsCitationsAPI.ListCitations(context.Background()).ProjectId(projectId).Page(page).PerPage(perPage).Model(model).CollectionId(collectionId).CountryCode(countryCode).LanguageCode(languageCode).Prompt(prompt).From(from).To(to).Output(output).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MentionsCitationsAPI.ListCitations``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListCitations`: CitationsResponse
	fmt.Fprintf(os.Stdout, "Response from `MentionsCitationsAPI.ListCitations`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListCitationsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **projectId** | **int32** | Project ID | 
 **page** | **int32** |  | [default to 1]
 **perPage** | **int32** |  | [default to 20]
 **model** | **string** | Filter by AI model. Models the API key&#39;s user has not enabled are silently dropped. | 
 **collectionId** | **string** | One collection/tag ID or a comma-separated list of IDs. A query value is always a string on the wire, so it is typed as one: the previous integer-or-string union made generators emit a wrapper type they could not serialize. | 
 **countryCode** | **string** | One ISO country code or a comma-separated list (e.g. US,GB,DE) | 
 **languageCode** | **string** | One ISO language code or a comma-separated list (e.g. en,es,de) | 
 **prompt** | **int32** | Filter by prompt ID | 
 **from** | **time.Time** |  | 
 **to** | **time.Time** | End of the window. A date-only value such as 2026-09-01 covers that whole day. Pass a full timestamp to end the window earlier. | 
 **output** | **string** | Rectangular output for BI tools (Tableau, Excel, Sheets, ELT). Omit for the default nested JSON. &#39;flat&#39; returns the same metadata plus &#39;columns&#39; and &#39;rows&#39;; &#39;csv&#39; returns those rows as text/csv. Errors are always returned as JSON. | 

### Return type

[**CitationsResponse**](CitationsResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListCompetitorCitations

> ListCompetitorCitations(ctx).ProjectId(projectId).Competitors(competitors).Page(page).PerPage(perPage).Model(model).CollectionId(collectionId).Prompt(prompt).From(from).To(to).Output(output).Execute()

List competitor citations



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
	competitors := "competitors_example" // string | Comma-separated competitor IDs (unknown IDs return ERR_INVALID_PARAM) (optional)
	page := int32(56) // int32 |  (optional) (default to 1)
	perPage := int32(56) // int32 |  (optional) (default to 20)
	model := "model_example" // string | Filter by AI model. Models the API key's user has not enabled are silently dropped. (optional)
	collectionId := "12,34" // string | One collection/tag ID or a comma-separated list of IDs. A query value is always a string on the wire, so it is typed as one: the previous integer-or-string union made generators emit a wrapper type they could not serialize. (optional)
	prompt := int32(56) // int32 | Filter by prompt ID (optional)
	from := time.Now() // time.Time |  (optional)
	to := time.Now() // time.Time | End of the window. A date-only value such as 2026-09-01 covers that whole day. Pass a full timestamp to end the window earlier. (optional)
	output := "output_example" // string | Rectangular output for BI tools (Tableau, Excel, Sheets, ELT). Omit for the default nested JSON. 'flat' returns the same metadata plus 'columns' and 'rows'; 'csv' returns those rows as text/csv. Errors are always returned as JSON. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.MentionsCitationsAPI.ListCompetitorCitations(context.Background()).ProjectId(projectId).Competitors(competitors).Page(page).PerPage(perPage).Model(model).CollectionId(collectionId).Prompt(prompt).From(from).To(to).Output(output).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MentionsCitationsAPI.ListCompetitorCitations``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListCompetitorCitationsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **projectId** | **int32** | Project ID | 
 **competitors** | **string** | Comma-separated competitor IDs (unknown IDs return ERR_INVALID_PARAM) | 
 **page** | **int32** |  | [default to 1]
 **perPage** | **int32** |  | [default to 20]
 **model** | **string** | Filter by AI model. Models the API key&#39;s user has not enabled are silently dropped. | 
 **collectionId** | **string** | One collection/tag ID or a comma-separated list of IDs. A query value is always a string on the wire, so it is typed as one: the previous integer-or-string union made generators emit a wrapper type they could not serialize. | 
 **prompt** | **int32** | Filter by prompt ID | 
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


## ListCompetitorMentions

> CompetitorMentionsResponse ListCompetitorMentions(ctx).ProjectId(projectId).Competitors(competitors).Page(page).PerPage(perPage).Model(model).CollectionId(collectionId).Prompt(prompt).From(from).To(to).Output(output).Execute()

List competitor mentions

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
	competitors := "competitors_example" // string | Comma-separated competitor IDs (unknown IDs return ERR_INVALID_PARAM) (optional)
	page := int32(56) // int32 |  (optional) (default to 1)
	perPage := int32(56) // int32 |  (optional) (default to 20)
	model := "model_example" // string | Filter by AI model. Models the API key's user has not enabled are silently dropped. (optional)
	collectionId := "12,34" // string | One collection/tag ID or a comma-separated list of IDs. A query value is always a string on the wire, so it is typed as one: the previous integer-or-string union made generators emit a wrapper type they could not serialize. (optional)
	prompt := int32(56) // int32 | Filter by prompt ID (optional)
	from := time.Now() // time.Time |  (optional)
	to := time.Now() // time.Time | End of the window. A date-only value such as 2026-09-01 covers that whole day. Pass a full timestamp to end the window earlier. (optional)
	output := "output_example" // string | Rectangular output for BI tools (Tableau, Excel, Sheets, ELT). Omit for the default nested JSON. 'flat' returns the same metadata plus 'columns' and 'rows'; 'csv' returns those rows as text/csv. Errors are always returned as JSON. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MentionsCitationsAPI.ListCompetitorMentions(context.Background()).ProjectId(projectId).Competitors(competitors).Page(page).PerPage(perPage).Model(model).CollectionId(collectionId).Prompt(prompt).From(from).To(to).Output(output).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MentionsCitationsAPI.ListCompetitorMentions``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListCompetitorMentions`: CompetitorMentionsResponse
	fmt.Fprintf(os.Stdout, "Response from `MentionsCitationsAPI.ListCompetitorMentions`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListCompetitorMentionsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **projectId** | **int32** | Project ID | 
 **competitors** | **string** | Comma-separated competitor IDs (unknown IDs return ERR_INVALID_PARAM) | 
 **page** | **int32** |  | [default to 1]
 **perPage** | **int32** |  | [default to 20]
 **model** | **string** | Filter by AI model. Models the API key&#39;s user has not enabled are silently dropped. | 
 **collectionId** | **string** | One collection/tag ID or a comma-separated list of IDs. A query value is always a string on the wire, so it is typed as one: the previous integer-or-string union made generators emit a wrapper type they could not serialize. | 
 **prompt** | **int32** | Filter by prompt ID | 
 **from** | **time.Time** |  | 
 **to** | **time.Time** | End of the window. A date-only value such as 2026-09-01 covers that whole day. Pass a full timestamp to end the window earlier. | 
 **output** | **string** | Rectangular output for BI tools (Tableau, Excel, Sheets, ELT). Omit for the default nested JSON. &#39;flat&#39; returns the same metadata plus &#39;columns&#39; and &#39;rows&#39;; &#39;csv&#39; returns those rows as text/csv. Errors are always returned as JSON. | 

### Return type

[**CompetitorMentionsResponse**](CompetitorMentionsResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListMentions

> MentionsResponse ListMentions(ctx).ProjectId(projectId).Page(page).PerPage(perPage).Model(model).CollectionId(collectionId).CountryCode(countryCode).LanguageCode(languageCode).Prompt(prompt).From(from).To(to).Output(output).Execute()

List brand mentions

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
	collectionId := "12,34" // string | One collection/tag ID or a comma-separated list of IDs. A query value is always a string on the wire, so it is typed as one: the previous integer-or-string union made generators emit a wrapper type they could not serialize. (optional)
	countryCode := "countryCode_example" // string | One ISO country code or a comma-separated list (e.g. US,GB,DE) (optional)
	languageCode := "languageCode_example" // string | One ISO language code or a comma-separated list (e.g. en,es,de) (optional)
	prompt := int32(56) // int32 | Filter by prompt ID (optional)
	from := time.Now() // time.Time |  (optional)
	to := time.Now() // time.Time | End of the window. A date-only value such as 2026-09-01 covers that whole day. Pass a full timestamp to end the window earlier. (optional)
	output := "output_example" // string | Rectangular output for BI tools (Tableau, Excel, Sheets, ELT). Omit for the default nested JSON. 'flat' returns the same metadata plus 'columns' and 'rows'; 'csv' returns those rows as text/csv. Errors are always returned as JSON. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MentionsCitationsAPI.ListMentions(context.Background()).ProjectId(projectId).Page(page).PerPage(perPage).Model(model).CollectionId(collectionId).CountryCode(countryCode).LanguageCode(languageCode).Prompt(prompt).From(from).To(to).Output(output).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MentionsCitationsAPI.ListMentions``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListMentions`: MentionsResponse
	fmt.Fprintf(os.Stdout, "Response from `MentionsCitationsAPI.ListMentions`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListMentionsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **projectId** | **int32** | Project ID | 
 **page** | **int32** |  | [default to 1]
 **perPage** | **int32** |  | [default to 20]
 **model** | **string** | Filter by AI model. Models the API key&#39;s user has not enabled are silently dropped. | 
 **collectionId** | **string** | One collection/tag ID or a comma-separated list of IDs. A query value is always a string on the wire, so it is typed as one: the previous integer-or-string union made generators emit a wrapper type they could not serialize. | 
 **countryCode** | **string** | One ISO country code or a comma-separated list (e.g. US,GB,DE) | 
 **languageCode** | **string** | One ISO language code or a comma-separated list (e.g. en,es,de) | 
 **prompt** | **int32** | Filter by prompt ID | 
 **from** | **time.Time** |  | 
 **to** | **time.Time** | End of the window. A date-only value such as 2026-09-01 covers that whole day. Pass a full timestamp to end the window earlier. | 
 **output** | **string** | Rectangular output for BI tools (Tableau, Excel, Sheets, ELT). Omit for the default nested JSON. &#39;flat&#39; returns the same metadata plus &#39;columns&#39; and &#39;rows&#39;; &#39;csv&#39; returns those rows as text/csv. Errors are always returned as JSON. | 

### Return type

[**MentionsResponse**](MentionsResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

