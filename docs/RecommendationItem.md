# RecommendationItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **int32** |  | 
**RecommendationId** | **int32** |  | 
**RecommendationType** | **string** |  | 
**Category** | **string** |  | 
**Title** | **string** |  | 
**Description** | Pointer to **NullableString** |  | [optional] 
**Priority** | **string** |  | 
**EstimatedImpact** | Pointer to **NullableString** |  | [optional] 
**ActionItems** | **[]string** |  | 
**SourceRefs** | **[]string** | Evidence codes (e.g. P1, C2) resolved in resolved_source_refs | 
**Status** | **string** |  | 
**StatusChangedAt** | Pointer to **NullableTime** |  | [optional] 
**Position** | **int32** |  | 
**Metadata** | Pointer to **map[string]interface{}** |  | [optional] 
**CreatedAt** | **time.Time** |  | 
**UpdatedAt** | **time.Time** |  | 
**ResolvedSourceRefs** | Pointer to **[]map[string]interface{}** | The evidence each source_refs code points to (prompt, citation or own page) | [optional] 
**UnresolvedSourceRefs** | Pointer to **[]string** | Present only when a code points to no stored evidence | [optional] 

## Methods

### NewRecommendationItem

`func NewRecommendationItem(id int32, recommendationId int32, recommendationType string, category string, title string, priority string, actionItems []string, sourceRefs []string, status string, position int32, createdAt time.Time, updatedAt time.Time, ) *RecommendationItem`

NewRecommendationItem instantiates a new RecommendationItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRecommendationItemWithDefaults

`func NewRecommendationItemWithDefaults() *RecommendationItem`

NewRecommendationItemWithDefaults instantiates a new RecommendationItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *RecommendationItem) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *RecommendationItem) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *RecommendationItem) SetId(v int32)`

SetId sets Id field to given value.


### GetRecommendationId

`func (o *RecommendationItem) GetRecommendationId() int32`

GetRecommendationId returns the RecommendationId field if non-nil, zero value otherwise.

### GetRecommendationIdOk

`func (o *RecommendationItem) GetRecommendationIdOk() (*int32, bool)`

GetRecommendationIdOk returns a tuple with the RecommendationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRecommendationId

`func (o *RecommendationItem) SetRecommendationId(v int32)`

SetRecommendationId sets RecommendationId field to given value.


### GetRecommendationType

`func (o *RecommendationItem) GetRecommendationType() string`

GetRecommendationType returns the RecommendationType field if non-nil, zero value otherwise.

### GetRecommendationTypeOk

`func (o *RecommendationItem) GetRecommendationTypeOk() (*string, bool)`

GetRecommendationTypeOk returns a tuple with the RecommendationType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRecommendationType

`func (o *RecommendationItem) SetRecommendationType(v string)`

SetRecommendationType sets RecommendationType field to given value.


### GetCategory

`func (o *RecommendationItem) GetCategory() string`

GetCategory returns the Category field if non-nil, zero value otherwise.

### GetCategoryOk

`func (o *RecommendationItem) GetCategoryOk() (*string, bool)`

GetCategoryOk returns a tuple with the Category field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCategory

`func (o *RecommendationItem) SetCategory(v string)`

SetCategory sets Category field to given value.


### GetTitle

`func (o *RecommendationItem) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *RecommendationItem) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *RecommendationItem) SetTitle(v string)`

SetTitle sets Title field to given value.


### GetDescription

`func (o *RecommendationItem) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *RecommendationItem) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *RecommendationItem) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *RecommendationItem) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### SetDescriptionNil

`func (o *RecommendationItem) SetDescriptionNil(b bool)`

 SetDescriptionNil sets the value for Description to be an explicit nil

### UnsetDescription
`func (o *RecommendationItem) UnsetDescription()`

UnsetDescription ensures that no value is present for Description, not even an explicit nil
### GetPriority

`func (o *RecommendationItem) GetPriority() string`

GetPriority returns the Priority field if non-nil, zero value otherwise.

### GetPriorityOk

`func (o *RecommendationItem) GetPriorityOk() (*string, bool)`

GetPriorityOk returns a tuple with the Priority field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPriority

`func (o *RecommendationItem) SetPriority(v string)`

SetPriority sets Priority field to given value.


### GetEstimatedImpact

`func (o *RecommendationItem) GetEstimatedImpact() string`

GetEstimatedImpact returns the EstimatedImpact field if non-nil, zero value otherwise.

### GetEstimatedImpactOk

`func (o *RecommendationItem) GetEstimatedImpactOk() (*string, bool)`

GetEstimatedImpactOk returns a tuple with the EstimatedImpact field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEstimatedImpact

`func (o *RecommendationItem) SetEstimatedImpact(v string)`

SetEstimatedImpact sets EstimatedImpact field to given value.

### HasEstimatedImpact

`func (o *RecommendationItem) HasEstimatedImpact() bool`

HasEstimatedImpact returns a boolean if a field has been set.

### SetEstimatedImpactNil

`func (o *RecommendationItem) SetEstimatedImpactNil(b bool)`

 SetEstimatedImpactNil sets the value for EstimatedImpact to be an explicit nil

### UnsetEstimatedImpact
`func (o *RecommendationItem) UnsetEstimatedImpact()`

UnsetEstimatedImpact ensures that no value is present for EstimatedImpact, not even an explicit nil
### GetActionItems

`func (o *RecommendationItem) GetActionItems() []string`

GetActionItems returns the ActionItems field if non-nil, zero value otherwise.

### GetActionItemsOk

`func (o *RecommendationItem) GetActionItemsOk() (*[]string, bool)`

GetActionItemsOk returns a tuple with the ActionItems field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActionItems

`func (o *RecommendationItem) SetActionItems(v []string)`

SetActionItems sets ActionItems field to given value.


### GetSourceRefs

`func (o *RecommendationItem) GetSourceRefs() []string`

GetSourceRefs returns the SourceRefs field if non-nil, zero value otherwise.

### GetSourceRefsOk

`func (o *RecommendationItem) GetSourceRefsOk() (*[]string, bool)`

GetSourceRefsOk returns a tuple with the SourceRefs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSourceRefs

`func (o *RecommendationItem) SetSourceRefs(v []string)`

SetSourceRefs sets SourceRefs field to given value.


### GetStatus

`func (o *RecommendationItem) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *RecommendationItem) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *RecommendationItem) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetStatusChangedAt

`func (o *RecommendationItem) GetStatusChangedAt() time.Time`

GetStatusChangedAt returns the StatusChangedAt field if non-nil, zero value otherwise.

### GetStatusChangedAtOk

`func (o *RecommendationItem) GetStatusChangedAtOk() (*time.Time, bool)`

GetStatusChangedAtOk returns a tuple with the StatusChangedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatusChangedAt

`func (o *RecommendationItem) SetStatusChangedAt(v time.Time)`

SetStatusChangedAt sets StatusChangedAt field to given value.

### HasStatusChangedAt

`func (o *RecommendationItem) HasStatusChangedAt() bool`

HasStatusChangedAt returns a boolean if a field has been set.

### SetStatusChangedAtNil

`func (o *RecommendationItem) SetStatusChangedAtNil(b bool)`

 SetStatusChangedAtNil sets the value for StatusChangedAt to be an explicit nil

### UnsetStatusChangedAt
`func (o *RecommendationItem) UnsetStatusChangedAt()`

UnsetStatusChangedAt ensures that no value is present for StatusChangedAt, not even an explicit nil
### GetPosition

`func (o *RecommendationItem) GetPosition() int32`

GetPosition returns the Position field if non-nil, zero value otherwise.

### GetPositionOk

`func (o *RecommendationItem) GetPositionOk() (*int32, bool)`

GetPositionOk returns a tuple with the Position field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPosition

`func (o *RecommendationItem) SetPosition(v int32)`

SetPosition sets Position field to given value.


### GetMetadata

`func (o *RecommendationItem) GetMetadata() map[string]interface{}`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *RecommendationItem) GetMetadataOk() (*map[string]interface{}, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *RecommendationItem) SetMetadata(v map[string]interface{})`

SetMetadata sets Metadata field to given value.

### HasMetadata

`func (o *RecommendationItem) HasMetadata() bool`

HasMetadata returns a boolean if a field has been set.

### GetCreatedAt

`func (o *RecommendationItem) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *RecommendationItem) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *RecommendationItem) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetUpdatedAt

`func (o *RecommendationItem) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *RecommendationItem) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *RecommendationItem) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.


### GetResolvedSourceRefs

`func (o *RecommendationItem) GetResolvedSourceRefs() []map[string]interface{}`

GetResolvedSourceRefs returns the ResolvedSourceRefs field if non-nil, zero value otherwise.

### GetResolvedSourceRefsOk

`func (o *RecommendationItem) GetResolvedSourceRefsOk() (*[]map[string]interface{}, bool)`

GetResolvedSourceRefsOk returns a tuple with the ResolvedSourceRefs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResolvedSourceRefs

`func (o *RecommendationItem) SetResolvedSourceRefs(v []map[string]interface{})`

SetResolvedSourceRefs sets ResolvedSourceRefs field to given value.

### HasResolvedSourceRefs

`func (o *RecommendationItem) HasResolvedSourceRefs() bool`

HasResolvedSourceRefs returns a boolean if a field has been set.

### GetUnresolvedSourceRefs

`func (o *RecommendationItem) GetUnresolvedSourceRefs() []string`

GetUnresolvedSourceRefs returns the UnresolvedSourceRefs field if non-nil, zero value otherwise.

### GetUnresolvedSourceRefsOk

`func (o *RecommendationItem) GetUnresolvedSourceRefsOk() (*[]string, bool)`

GetUnresolvedSourceRefsOk returns a tuple with the UnresolvedSourceRefs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnresolvedSourceRefs

`func (o *RecommendationItem) SetUnresolvedSourceRefs(v []string)`

SetUnresolvedSourceRefs sets UnresolvedSourceRefs field to given value.

### HasUnresolvedSourceRefs

`func (o *RecommendationItem) HasUnresolvedSourceRefs() bool`

HasUnresolvedSourceRefs returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


