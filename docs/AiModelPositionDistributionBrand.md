# AiModelPositionDistributionBrand

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Type** | **string** | project or competitor | 
**Id** | **int32** | Project id, or competitor id | 
**CompetitorId** | **NullableInt32** | Null for the project, the competitor id otherwise | 
**Name** | **string** |  | 
**Domain** | **NullableString** | Bare (scheme-less) domain. Null for the project when it has no URL. | 
**Buckets** | [**[]AiModelPositionDistributionBrandBucketsInner**](AiModelPositionDistributionBrandBucketsInner.md) | One per position bucket, in order: position_1, position_2_3, position_4_7 and position_8_plus | 
**MaxStackedValue** | **int32** | The brand&#39;s largest mentions count of one period, its buckets added up | 

## Methods

### NewAiModelPositionDistributionBrand

`func NewAiModelPositionDistributionBrand(type_ string, id int32, competitorId NullableInt32, name string, domain NullableString, buckets []AiModelPositionDistributionBrandBucketsInner, maxStackedValue int32, ) *AiModelPositionDistributionBrand`

NewAiModelPositionDistributionBrand instantiates a new AiModelPositionDistributionBrand object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAiModelPositionDistributionBrandWithDefaults

`func NewAiModelPositionDistributionBrandWithDefaults() *AiModelPositionDistributionBrand`

NewAiModelPositionDistributionBrandWithDefaults instantiates a new AiModelPositionDistributionBrand object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetType

`func (o *AiModelPositionDistributionBrand) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *AiModelPositionDistributionBrand) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *AiModelPositionDistributionBrand) SetType(v string)`

SetType sets Type field to given value.


### GetId

`func (o *AiModelPositionDistributionBrand) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *AiModelPositionDistributionBrand) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *AiModelPositionDistributionBrand) SetId(v int32)`

SetId sets Id field to given value.


### GetCompetitorId

`func (o *AiModelPositionDistributionBrand) GetCompetitorId() int32`

GetCompetitorId returns the CompetitorId field if non-nil, zero value otherwise.

### GetCompetitorIdOk

`func (o *AiModelPositionDistributionBrand) GetCompetitorIdOk() (*int32, bool)`

GetCompetitorIdOk returns a tuple with the CompetitorId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompetitorId

`func (o *AiModelPositionDistributionBrand) SetCompetitorId(v int32)`

SetCompetitorId sets CompetitorId field to given value.


### SetCompetitorIdNil

`func (o *AiModelPositionDistributionBrand) SetCompetitorIdNil(b bool)`

 SetCompetitorIdNil sets the value for CompetitorId to be an explicit nil

### UnsetCompetitorId
`func (o *AiModelPositionDistributionBrand) UnsetCompetitorId()`

UnsetCompetitorId ensures that no value is present for CompetitorId, not even an explicit nil
### GetName

`func (o *AiModelPositionDistributionBrand) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *AiModelPositionDistributionBrand) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *AiModelPositionDistributionBrand) SetName(v string)`

SetName sets Name field to given value.


### GetDomain

`func (o *AiModelPositionDistributionBrand) GetDomain() string`

GetDomain returns the Domain field if non-nil, zero value otherwise.

### GetDomainOk

`func (o *AiModelPositionDistributionBrand) GetDomainOk() (*string, bool)`

GetDomainOk returns a tuple with the Domain field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDomain

`func (o *AiModelPositionDistributionBrand) SetDomain(v string)`

SetDomain sets Domain field to given value.


### SetDomainNil

`func (o *AiModelPositionDistributionBrand) SetDomainNil(b bool)`

 SetDomainNil sets the value for Domain to be an explicit nil

### UnsetDomain
`func (o *AiModelPositionDistributionBrand) UnsetDomain()`

UnsetDomain ensures that no value is present for Domain, not even an explicit nil
### GetBuckets

`func (o *AiModelPositionDistributionBrand) GetBuckets() []AiModelPositionDistributionBrandBucketsInner`

GetBuckets returns the Buckets field if non-nil, zero value otherwise.

### GetBucketsOk

`func (o *AiModelPositionDistributionBrand) GetBucketsOk() (*[]AiModelPositionDistributionBrandBucketsInner, bool)`

GetBucketsOk returns a tuple with the Buckets field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBuckets

`func (o *AiModelPositionDistributionBrand) SetBuckets(v []AiModelPositionDistributionBrandBucketsInner)`

SetBuckets sets Buckets field to given value.


### GetMaxStackedValue

`func (o *AiModelPositionDistributionBrand) GetMaxStackedValue() int32`

GetMaxStackedValue returns the MaxStackedValue field if non-nil, zero value otherwise.

### GetMaxStackedValueOk

`func (o *AiModelPositionDistributionBrand) GetMaxStackedValueOk() (*int32, bool)`

GetMaxStackedValueOk returns a tuple with the MaxStackedValue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxStackedValue

`func (o *AiModelPositionDistributionBrand) SetMaxStackedValue(v int32)`

SetMaxStackedValue sets MaxStackedValue field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


