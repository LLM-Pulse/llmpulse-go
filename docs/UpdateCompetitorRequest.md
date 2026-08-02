# UpdateCompetitorRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ProjectId** | **int32** |  | 
**BrandName** | Pointer to **string** |  | [optional] 
**MatchingNames** | Pointer to **[]string** |  | [optional] 
**Color** | Pointer to **string** | Hex color, e.g. #1a2b3c | [optional] 

## Methods

### NewUpdateCompetitorRequest

`func NewUpdateCompetitorRequest(projectId int32, ) *UpdateCompetitorRequest`

NewUpdateCompetitorRequest instantiates a new UpdateCompetitorRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUpdateCompetitorRequestWithDefaults

`func NewUpdateCompetitorRequestWithDefaults() *UpdateCompetitorRequest`

NewUpdateCompetitorRequestWithDefaults instantiates a new UpdateCompetitorRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProjectId

`func (o *UpdateCompetitorRequest) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *UpdateCompetitorRequest) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *UpdateCompetitorRequest) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.


### GetBrandName

`func (o *UpdateCompetitorRequest) GetBrandName() string`

GetBrandName returns the BrandName field if non-nil, zero value otherwise.

### GetBrandNameOk

`func (o *UpdateCompetitorRequest) GetBrandNameOk() (*string, bool)`

GetBrandNameOk returns a tuple with the BrandName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBrandName

`func (o *UpdateCompetitorRequest) SetBrandName(v string)`

SetBrandName sets BrandName field to given value.

### HasBrandName

`func (o *UpdateCompetitorRequest) HasBrandName() bool`

HasBrandName returns a boolean if a field has been set.

### GetMatchingNames

`func (o *UpdateCompetitorRequest) GetMatchingNames() []string`

GetMatchingNames returns the MatchingNames field if non-nil, zero value otherwise.

### GetMatchingNamesOk

`func (o *UpdateCompetitorRequest) GetMatchingNamesOk() (*[]string, bool)`

GetMatchingNamesOk returns a tuple with the MatchingNames field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMatchingNames

`func (o *UpdateCompetitorRequest) SetMatchingNames(v []string)`

SetMatchingNames sets MatchingNames field to given value.

### HasMatchingNames

`func (o *UpdateCompetitorRequest) HasMatchingNames() bool`

HasMatchingNames returns a boolean if a field has been set.

### GetColor

`func (o *UpdateCompetitorRequest) GetColor() string`

GetColor returns the Color field if non-nil, zero value otherwise.

### GetColorOk

`func (o *UpdateCompetitorRequest) GetColorOk() (*string, bool)`

GetColorOk returns a tuple with the Color field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetColor

`func (o *UpdateCompetitorRequest) SetColor(v string)`

SetColor sets Color field to given value.

### HasColor

`func (o *UpdateCompetitorRequest) HasColor() bool`

HasColor returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


