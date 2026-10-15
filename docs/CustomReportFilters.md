# CustomReportFilters

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Models** | **[]string** | AI models the report covers; empty means every enabled model | 
**CollectionIds** | **[]int32** | Tags the report is limited to; empty means every prompt | 
**BrandKind** | Pointer to **NullableString** |  | [optional] 
**CompetitorIds** | **[]int32** | Competitors compared, the report&#39;s own choice or else the Overview selection | 

## Methods

### NewCustomReportFilters

`func NewCustomReportFilters(models []string, collectionIds []int32, competitorIds []int32, ) *CustomReportFilters`

NewCustomReportFilters instantiates a new CustomReportFilters object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCustomReportFiltersWithDefaults

`func NewCustomReportFiltersWithDefaults() *CustomReportFilters`

NewCustomReportFiltersWithDefaults instantiates a new CustomReportFilters object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetModels

`func (o *CustomReportFilters) GetModels() []string`

GetModels returns the Models field if non-nil, zero value otherwise.

### GetModelsOk

`func (o *CustomReportFilters) GetModelsOk() (*[]string, bool)`

GetModelsOk returns a tuple with the Models field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModels

`func (o *CustomReportFilters) SetModels(v []string)`

SetModels sets Models field to given value.


### GetCollectionIds

`func (o *CustomReportFilters) GetCollectionIds() []int32`

GetCollectionIds returns the CollectionIds field if non-nil, zero value otherwise.

### GetCollectionIdsOk

`func (o *CustomReportFilters) GetCollectionIdsOk() (*[]int32, bool)`

GetCollectionIdsOk returns a tuple with the CollectionIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCollectionIds

`func (o *CustomReportFilters) SetCollectionIds(v []int32)`

SetCollectionIds sets CollectionIds field to given value.


### GetBrandKind

`func (o *CustomReportFilters) GetBrandKind() string`

GetBrandKind returns the BrandKind field if non-nil, zero value otherwise.

### GetBrandKindOk

`func (o *CustomReportFilters) GetBrandKindOk() (*string, bool)`

GetBrandKindOk returns a tuple with the BrandKind field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBrandKind

`func (o *CustomReportFilters) SetBrandKind(v string)`

SetBrandKind sets BrandKind field to given value.

### HasBrandKind

`func (o *CustomReportFilters) HasBrandKind() bool`

HasBrandKind returns a boolean if a field has been set.

### SetBrandKindNil

`func (o *CustomReportFilters) SetBrandKindNil(b bool)`

 SetBrandKindNil sets the value for BrandKind to be an explicit nil

### UnsetBrandKind
`func (o *CustomReportFilters) UnsetBrandKind()`

UnsetBrandKind ensures that no value is present for BrandKind, not even an explicit nil
### GetCompetitorIds

`func (o *CustomReportFilters) GetCompetitorIds() []int32`

GetCompetitorIds returns the CompetitorIds field if non-nil, zero value otherwise.

### GetCompetitorIdsOk

`func (o *CustomReportFilters) GetCompetitorIdsOk() (*[]int32, bool)`

GetCompetitorIdsOk returns a tuple with the CompetitorIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompetitorIds

`func (o *CustomReportFilters) SetCompetitorIds(v []int32)`

SetCompetitorIds sets CompetitorIds field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


