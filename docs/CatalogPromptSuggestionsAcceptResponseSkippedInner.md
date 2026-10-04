# CatalogPromptSuggestionsAcceptResponseSkippedInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**SuggestionId** | **int32** |  | 
**Reason** | **string** | accepted or rejected (the suggestion was no longer pending), or pending_deletion | 

## Methods

### NewCatalogPromptSuggestionsAcceptResponseSkippedInner

`func NewCatalogPromptSuggestionsAcceptResponseSkippedInner(suggestionId int32, reason string, ) *CatalogPromptSuggestionsAcceptResponseSkippedInner`

NewCatalogPromptSuggestionsAcceptResponseSkippedInner instantiates a new CatalogPromptSuggestionsAcceptResponseSkippedInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCatalogPromptSuggestionsAcceptResponseSkippedInnerWithDefaults

`func NewCatalogPromptSuggestionsAcceptResponseSkippedInnerWithDefaults() *CatalogPromptSuggestionsAcceptResponseSkippedInner`

NewCatalogPromptSuggestionsAcceptResponseSkippedInnerWithDefaults instantiates a new CatalogPromptSuggestionsAcceptResponseSkippedInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSuggestionId

`func (o *CatalogPromptSuggestionsAcceptResponseSkippedInner) GetSuggestionId() int32`

GetSuggestionId returns the SuggestionId field if non-nil, zero value otherwise.

### GetSuggestionIdOk

`func (o *CatalogPromptSuggestionsAcceptResponseSkippedInner) GetSuggestionIdOk() (*int32, bool)`

GetSuggestionIdOk returns a tuple with the SuggestionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuggestionId

`func (o *CatalogPromptSuggestionsAcceptResponseSkippedInner) SetSuggestionId(v int32)`

SetSuggestionId sets SuggestionId field to given value.


### GetReason

`func (o *CatalogPromptSuggestionsAcceptResponseSkippedInner) GetReason() string`

GetReason returns the Reason field if non-nil, zero value otherwise.

### GetReasonOk

`func (o *CatalogPromptSuggestionsAcceptResponseSkippedInner) GetReasonOk() (*string, bool)`

GetReasonOk returns a tuple with the Reason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReason

`func (o *CatalogPromptSuggestionsAcceptResponseSkippedInner) SetReason(v string)`

SetReason sets Reason field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


