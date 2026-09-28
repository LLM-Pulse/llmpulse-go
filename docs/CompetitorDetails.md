# CompetitorDetails

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **int32** |  | [optional] 
**ProjectId** | Pointer to **int32** |  | [optional] 
**BrandName** | Pointer to **string** |  | [optional] 
**Domain** | Pointer to **string** |  | [optional] 
**MatchingNames** | Pointer to **[]string** |  | [optional] 
**GooglePlayId** | Pointer to **NullableString** |  | [optional] 
**AppStoreId** | Pointer to **NullableString** |  | [optional] 
**Color** | Pointer to **NullableString** |  | [optional] 
**CreatedAt** | Pointer to **time.Time** |  | [optional] 

## Methods

### NewCompetitorDetails

`func NewCompetitorDetails() *CompetitorDetails`

NewCompetitorDetails instantiates a new CompetitorDetails object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCompetitorDetailsWithDefaults

`func NewCompetitorDetailsWithDefaults() *CompetitorDetails`

NewCompetitorDetailsWithDefaults instantiates a new CompetitorDetails object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *CompetitorDetails) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *CompetitorDetails) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *CompetitorDetails) SetId(v int32)`

SetId sets Id field to given value.

### HasId

`func (o *CompetitorDetails) HasId() bool`

HasId returns a boolean if a field has been set.

### GetProjectId

`func (o *CompetitorDetails) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *CompetitorDetails) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *CompetitorDetails) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.

### HasProjectId

`func (o *CompetitorDetails) HasProjectId() bool`

HasProjectId returns a boolean if a field has been set.

### GetBrandName

`func (o *CompetitorDetails) GetBrandName() string`

GetBrandName returns the BrandName field if non-nil, zero value otherwise.

### GetBrandNameOk

`func (o *CompetitorDetails) GetBrandNameOk() (*string, bool)`

GetBrandNameOk returns a tuple with the BrandName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBrandName

`func (o *CompetitorDetails) SetBrandName(v string)`

SetBrandName sets BrandName field to given value.

### HasBrandName

`func (o *CompetitorDetails) HasBrandName() bool`

HasBrandName returns a boolean if a field has been set.

### GetDomain

`func (o *CompetitorDetails) GetDomain() string`

GetDomain returns the Domain field if non-nil, zero value otherwise.

### GetDomainOk

`func (o *CompetitorDetails) GetDomainOk() (*string, bool)`

GetDomainOk returns a tuple with the Domain field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDomain

`func (o *CompetitorDetails) SetDomain(v string)`

SetDomain sets Domain field to given value.

### HasDomain

`func (o *CompetitorDetails) HasDomain() bool`

HasDomain returns a boolean if a field has been set.

### GetMatchingNames

`func (o *CompetitorDetails) GetMatchingNames() []string`

GetMatchingNames returns the MatchingNames field if non-nil, zero value otherwise.

### GetMatchingNamesOk

`func (o *CompetitorDetails) GetMatchingNamesOk() (*[]string, bool)`

GetMatchingNamesOk returns a tuple with the MatchingNames field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMatchingNames

`func (o *CompetitorDetails) SetMatchingNames(v []string)`

SetMatchingNames sets MatchingNames field to given value.

### HasMatchingNames

`func (o *CompetitorDetails) HasMatchingNames() bool`

HasMatchingNames returns a boolean if a field has been set.

### SetMatchingNamesNil

`func (o *CompetitorDetails) SetMatchingNamesNil(b bool)`

 SetMatchingNamesNil sets the value for MatchingNames to be an explicit nil

### UnsetMatchingNames
`func (o *CompetitorDetails) UnsetMatchingNames()`

UnsetMatchingNames ensures that no value is present for MatchingNames, not even an explicit nil
### GetGooglePlayId

`func (o *CompetitorDetails) GetGooglePlayId() string`

GetGooglePlayId returns the GooglePlayId field if non-nil, zero value otherwise.

### GetGooglePlayIdOk

`func (o *CompetitorDetails) GetGooglePlayIdOk() (*string, bool)`

GetGooglePlayIdOk returns a tuple with the GooglePlayId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGooglePlayId

`func (o *CompetitorDetails) SetGooglePlayId(v string)`

SetGooglePlayId sets GooglePlayId field to given value.

### HasGooglePlayId

`func (o *CompetitorDetails) HasGooglePlayId() bool`

HasGooglePlayId returns a boolean if a field has been set.

### SetGooglePlayIdNil

`func (o *CompetitorDetails) SetGooglePlayIdNil(b bool)`

 SetGooglePlayIdNil sets the value for GooglePlayId to be an explicit nil

### UnsetGooglePlayId
`func (o *CompetitorDetails) UnsetGooglePlayId()`

UnsetGooglePlayId ensures that no value is present for GooglePlayId, not even an explicit nil
### GetAppStoreId

`func (o *CompetitorDetails) GetAppStoreId() string`

GetAppStoreId returns the AppStoreId field if non-nil, zero value otherwise.

### GetAppStoreIdOk

`func (o *CompetitorDetails) GetAppStoreIdOk() (*string, bool)`

GetAppStoreIdOk returns a tuple with the AppStoreId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAppStoreId

`func (o *CompetitorDetails) SetAppStoreId(v string)`

SetAppStoreId sets AppStoreId field to given value.

### HasAppStoreId

`func (o *CompetitorDetails) HasAppStoreId() bool`

HasAppStoreId returns a boolean if a field has been set.

### SetAppStoreIdNil

`func (o *CompetitorDetails) SetAppStoreIdNil(b bool)`

 SetAppStoreIdNil sets the value for AppStoreId to be an explicit nil

### UnsetAppStoreId
`func (o *CompetitorDetails) UnsetAppStoreId()`

UnsetAppStoreId ensures that no value is present for AppStoreId, not even an explicit nil
### GetColor

`func (o *CompetitorDetails) GetColor() string`

GetColor returns the Color field if non-nil, zero value otherwise.

### GetColorOk

`func (o *CompetitorDetails) GetColorOk() (*string, bool)`

GetColorOk returns a tuple with the Color field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetColor

`func (o *CompetitorDetails) SetColor(v string)`

SetColor sets Color field to given value.

### HasColor

`func (o *CompetitorDetails) HasColor() bool`

HasColor returns a boolean if a field has been set.

### SetColorNil

`func (o *CompetitorDetails) SetColorNil(b bool)`

 SetColorNil sets the value for Color to be an explicit nil

### UnsetColor
`func (o *CompetitorDetails) UnsetColor()`

UnsetColor ensures that no value is present for Color, not even an explicit nil
### GetCreatedAt

`func (o *CompetitorDetails) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *CompetitorDetails) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *CompetitorDetails) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *CompetitorDetails) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


