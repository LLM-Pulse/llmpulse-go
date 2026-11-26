# CitingDomainMentionShareResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ProjectId** | **int32** |  | 
**Filters** | [**CitationIntelligenceFiltersEcho**](CitationIntelligenceFiltersEcho.md) |  | 
**Normalization** | **string** | How the shares are computed | 
**Data** | [**[]CitingDomainMentionShareResponseDataInner**](CitingDomainMentionShareResponseDataInner.md) | One row per requested domain (normalized, at most 50), in the order given | 
**RequestId** | **string** |  | 

## Methods

### NewCitingDomainMentionShareResponse

`func NewCitingDomainMentionShareResponse(projectId int32, filters CitationIntelligenceFiltersEcho, normalization string, data []CitingDomainMentionShareResponseDataInner, requestId string, ) *CitingDomainMentionShareResponse`

NewCitingDomainMentionShareResponse instantiates a new CitingDomainMentionShareResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCitingDomainMentionShareResponseWithDefaults

`func NewCitingDomainMentionShareResponseWithDefaults() *CitingDomainMentionShareResponse`

NewCitingDomainMentionShareResponseWithDefaults instantiates a new CitingDomainMentionShareResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProjectId

`func (o *CitingDomainMentionShareResponse) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *CitingDomainMentionShareResponse) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *CitingDomainMentionShareResponse) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.


### GetFilters

`func (o *CitingDomainMentionShareResponse) GetFilters() CitationIntelligenceFiltersEcho`

GetFilters returns the Filters field if non-nil, zero value otherwise.

### GetFiltersOk

`func (o *CitingDomainMentionShareResponse) GetFiltersOk() (*CitationIntelligenceFiltersEcho, bool)`

GetFiltersOk returns a tuple with the Filters field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFilters

`func (o *CitingDomainMentionShareResponse) SetFilters(v CitationIntelligenceFiltersEcho)`

SetFilters sets Filters field to given value.


### GetNormalization

`func (o *CitingDomainMentionShareResponse) GetNormalization() string`

GetNormalization returns the Normalization field if non-nil, zero value otherwise.

### GetNormalizationOk

`func (o *CitingDomainMentionShareResponse) GetNormalizationOk() (*string, bool)`

GetNormalizationOk returns a tuple with the Normalization field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNormalization

`func (o *CitingDomainMentionShareResponse) SetNormalization(v string)`

SetNormalization sets Normalization field to given value.


### GetData

`func (o *CitingDomainMentionShareResponse) GetData() []CitingDomainMentionShareResponseDataInner`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *CitingDomainMentionShareResponse) GetDataOk() (*[]CitingDomainMentionShareResponseDataInner, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *CitingDomainMentionShareResponse) SetData(v []CitingDomainMentionShareResponseDataInner)`

SetData sets Data field to given value.


### GetRequestId

`func (o *CitingDomainMentionShareResponse) GetRequestId() string`

GetRequestId returns the RequestId field if non-nil, zero value otherwise.

### GetRequestIdOk

`func (o *CitingDomainMentionShareResponse) GetRequestIdOk() (*string, bool)`

GetRequestIdOk returns a tuple with the RequestId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestId

`func (o *CitingDomainMentionShareResponse) SetRequestId(v string)`

SetRequestId sets RequestId field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


