# UpdateProjectRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | Pointer to **string** | Project name shown in the app. A label: it does not change mention detection unless brand_name is empty. Cannot be blank | [optional] 
**BrandName** | Pointer to **string** | Brand name used to detect mentions. Applies to future runs; it does not rewrite history | [optional] 
**Description** | Pointer to **string** | What the brand does. Context for Recommendations and GEO Writer (Brand Book) | [optional] 
**Industry** | Pointer to **string** | Single industry key (e.g. SAAS), stored as sent; an array of keys is also accepted and stored as an array, like the in-app multi-select. Unknown keys are rejected with the valid keys listed | [optional] 
**BusinessModel** | Pointer to **string** | Business model key (e.g. B2B_SAAS); unknown keys are rejected | [optional] 
**BusinessModelOther** | Pointer to **string** | Free-text business model, only accepted when business_model is OTHER; rejected against any other key | [optional] 
**TargetAudience** | Pointer to **string** | Who the brand sells to (Brand Book) | [optional] 
**BrandVoice** | Pointer to **string** | Tone of voice guidance for generated content (Brand Book) | [optional] 
**Goals** | Pointer to **string** | What the brand wants to achieve. Context for GEO Writer and prompt suggestions | [optional] 
**PrimaryProducts** | Pointer to **[]string** | Full replacement list of the main products or services | [optional] 
**MatchingNames** | Pointer to **[]string** | FULL replacement list of the brand-name variants used to detect mentions; send every variant to keep | [optional] 

## Methods

### NewUpdateProjectRequest

`func NewUpdateProjectRequest() *UpdateProjectRequest`

NewUpdateProjectRequest instantiates a new UpdateProjectRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUpdateProjectRequestWithDefaults

`func NewUpdateProjectRequestWithDefaults() *UpdateProjectRequest`

NewUpdateProjectRequestWithDefaults instantiates a new UpdateProjectRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *UpdateProjectRequest) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *UpdateProjectRequest) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *UpdateProjectRequest) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *UpdateProjectRequest) HasName() bool`

HasName returns a boolean if a field has been set.

### GetBrandName

`func (o *UpdateProjectRequest) GetBrandName() string`

GetBrandName returns the BrandName field if non-nil, zero value otherwise.

### GetBrandNameOk

`func (o *UpdateProjectRequest) GetBrandNameOk() (*string, bool)`

GetBrandNameOk returns a tuple with the BrandName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBrandName

`func (o *UpdateProjectRequest) SetBrandName(v string)`

SetBrandName sets BrandName field to given value.

### HasBrandName

`func (o *UpdateProjectRequest) HasBrandName() bool`

HasBrandName returns a boolean if a field has been set.

### GetDescription

`func (o *UpdateProjectRequest) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *UpdateProjectRequest) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *UpdateProjectRequest) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *UpdateProjectRequest) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetIndustry

`func (o *UpdateProjectRequest) GetIndustry() string`

GetIndustry returns the Industry field if non-nil, zero value otherwise.

### GetIndustryOk

`func (o *UpdateProjectRequest) GetIndustryOk() (*string, bool)`

GetIndustryOk returns a tuple with the Industry field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIndustry

`func (o *UpdateProjectRequest) SetIndustry(v string)`

SetIndustry sets Industry field to given value.

### HasIndustry

`func (o *UpdateProjectRequest) HasIndustry() bool`

HasIndustry returns a boolean if a field has been set.

### GetBusinessModel

`func (o *UpdateProjectRequest) GetBusinessModel() string`

GetBusinessModel returns the BusinessModel field if non-nil, zero value otherwise.

### GetBusinessModelOk

`func (o *UpdateProjectRequest) GetBusinessModelOk() (*string, bool)`

GetBusinessModelOk returns a tuple with the BusinessModel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBusinessModel

`func (o *UpdateProjectRequest) SetBusinessModel(v string)`

SetBusinessModel sets BusinessModel field to given value.

### HasBusinessModel

`func (o *UpdateProjectRequest) HasBusinessModel() bool`

HasBusinessModel returns a boolean if a field has been set.

### GetBusinessModelOther

`func (o *UpdateProjectRequest) GetBusinessModelOther() string`

GetBusinessModelOther returns the BusinessModelOther field if non-nil, zero value otherwise.

### GetBusinessModelOtherOk

`func (o *UpdateProjectRequest) GetBusinessModelOtherOk() (*string, bool)`

GetBusinessModelOtherOk returns a tuple with the BusinessModelOther field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBusinessModelOther

`func (o *UpdateProjectRequest) SetBusinessModelOther(v string)`

SetBusinessModelOther sets BusinessModelOther field to given value.

### HasBusinessModelOther

`func (o *UpdateProjectRequest) HasBusinessModelOther() bool`

HasBusinessModelOther returns a boolean if a field has been set.

### GetTargetAudience

`func (o *UpdateProjectRequest) GetTargetAudience() string`

GetTargetAudience returns the TargetAudience field if non-nil, zero value otherwise.

### GetTargetAudienceOk

`func (o *UpdateProjectRequest) GetTargetAudienceOk() (*string, bool)`

GetTargetAudienceOk returns a tuple with the TargetAudience field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTargetAudience

`func (o *UpdateProjectRequest) SetTargetAudience(v string)`

SetTargetAudience sets TargetAudience field to given value.

### HasTargetAudience

`func (o *UpdateProjectRequest) HasTargetAudience() bool`

HasTargetAudience returns a boolean if a field has been set.

### GetBrandVoice

`func (o *UpdateProjectRequest) GetBrandVoice() string`

GetBrandVoice returns the BrandVoice field if non-nil, zero value otherwise.

### GetBrandVoiceOk

`func (o *UpdateProjectRequest) GetBrandVoiceOk() (*string, bool)`

GetBrandVoiceOk returns a tuple with the BrandVoice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBrandVoice

`func (o *UpdateProjectRequest) SetBrandVoice(v string)`

SetBrandVoice sets BrandVoice field to given value.

### HasBrandVoice

`func (o *UpdateProjectRequest) HasBrandVoice() bool`

HasBrandVoice returns a boolean if a field has been set.

### GetGoals

`func (o *UpdateProjectRequest) GetGoals() string`

GetGoals returns the Goals field if non-nil, zero value otherwise.

### GetGoalsOk

`func (o *UpdateProjectRequest) GetGoalsOk() (*string, bool)`

GetGoalsOk returns a tuple with the Goals field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGoals

`func (o *UpdateProjectRequest) SetGoals(v string)`

SetGoals sets Goals field to given value.

### HasGoals

`func (o *UpdateProjectRequest) HasGoals() bool`

HasGoals returns a boolean if a field has been set.

### GetPrimaryProducts

`func (o *UpdateProjectRequest) GetPrimaryProducts() []string`

GetPrimaryProducts returns the PrimaryProducts field if non-nil, zero value otherwise.

### GetPrimaryProductsOk

`func (o *UpdateProjectRequest) GetPrimaryProductsOk() (*[]string, bool)`

GetPrimaryProductsOk returns a tuple with the PrimaryProducts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrimaryProducts

`func (o *UpdateProjectRequest) SetPrimaryProducts(v []string)`

SetPrimaryProducts sets PrimaryProducts field to given value.

### HasPrimaryProducts

`func (o *UpdateProjectRequest) HasPrimaryProducts() bool`

HasPrimaryProducts returns a boolean if a field has been set.

### GetMatchingNames

`func (o *UpdateProjectRequest) GetMatchingNames() []string`

GetMatchingNames returns the MatchingNames field if non-nil, zero value otherwise.

### GetMatchingNamesOk

`func (o *UpdateProjectRequest) GetMatchingNamesOk() (*[]string, bool)`

GetMatchingNamesOk returns a tuple with the MatchingNames field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMatchingNames

`func (o *UpdateProjectRequest) SetMatchingNames(v []string)`

SetMatchingNames sets MatchingNames field to given value.

### HasMatchingNames

`func (o *UpdateProjectRequest) HasMatchingNames() bool`

HasMatchingNames returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


