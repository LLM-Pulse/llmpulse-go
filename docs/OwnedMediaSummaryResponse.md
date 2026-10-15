# OwnedMediaSummaryResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ProjectId** | Pointer to **int32** |  | [optional] 
**Provider** | Pointer to **string** |  | [optional] 
**From** | Pointer to **time.Time** |  | [optional] 
**To** | Pointer to **time.Time** |  | [optional] 
**Connected** | Pointer to **bool** | Whether a profile is claimed on the platform (on overview, on any platform) | [optional] 
**Kpis** | Pointer to [**OwnedMediaKpis**](OwnedMediaKpis.md) |  | [optional] 
**Previous** | Pointer to [**OwnedMediaSummaryResponsePrevious**](OwnedMediaSummaryResponsePrevious.md) |  | [optional] 
**Changes** | Pointer to [**OwnedMediaKpiChanges**](OwnedMediaKpiChanges.md) |  | [optional] 
**Weekly** | Pointer to [**[]OwnedMediaWeek**](OwnedMediaWeek.md) |  | [optional] 
**ByModel** | Pointer to [**[]OwnedMediaModelShare**](OwnedMediaModelShare.md) | Null for provider&#x3D;overview | [optional] 
**ByCountry** | Pointer to [**[]OwnedMediaCountryShare**](OwnedMediaCountryShare.md) | Null for provider&#x3D;overview | [optional] 
**ContentTypes** | Pointer to [**[]OwnedMediaContentTypeShare**](OwnedMediaContentTypeShare.md) | Social and YouTube providers only | [optional] 
**AgeBuckets** | Pointer to [**[]OwnedMediaAgeBucketShare**](OwnedMediaAgeBucketShare.md) | Social and YouTube providers only. Posts or videos without a known publication date are left out | [optional] 
**Stores** | Pointer to [**[]OwnedMediaStoreTotals**](OwnedMediaStoreTotals.md) | provider&#x3D;mobile_apps only | [optional] 
**Platforms** | Pointer to [**[]OwnedMediaPlatformRollup**](OwnedMediaPlatformRollup.md) | provider&#x3D;overview only, one row per platform the caller can read | [optional] 
**RequestId** | Pointer to **string** |  | [optional] 

## Methods

### NewOwnedMediaSummaryResponse

`func NewOwnedMediaSummaryResponse() *OwnedMediaSummaryResponse`

NewOwnedMediaSummaryResponse instantiates a new OwnedMediaSummaryResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOwnedMediaSummaryResponseWithDefaults

`func NewOwnedMediaSummaryResponseWithDefaults() *OwnedMediaSummaryResponse`

NewOwnedMediaSummaryResponseWithDefaults instantiates a new OwnedMediaSummaryResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProjectId

`func (o *OwnedMediaSummaryResponse) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *OwnedMediaSummaryResponse) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *OwnedMediaSummaryResponse) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.

### HasProjectId

`func (o *OwnedMediaSummaryResponse) HasProjectId() bool`

HasProjectId returns a boolean if a field has been set.

### GetProvider

`func (o *OwnedMediaSummaryResponse) GetProvider() string`

GetProvider returns the Provider field if non-nil, zero value otherwise.

### GetProviderOk

`func (o *OwnedMediaSummaryResponse) GetProviderOk() (*string, bool)`

GetProviderOk returns a tuple with the Provider field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProvider

`func (o *OwnedMediaSummaryResponse) SetProvider(v string)`

SetProvider sets Provider field to given value.

### HasProvider

`func (o *OwnedMediaSummaryResponse) HasProvider() bool`

HasProvider returns a boolean if a field has been set.

### GetFrom

`func (o *OwnedMediaSummaryResponse) GetFrom() time.Time`

GetFrom returns the From field if non-nil, zero value otherwise.

### GetFromOk

`func (o *OwnedMediaSummaryResponse) GetFromOk() (*time.Time, bool)`

GetFromOk returns a tuple with the From field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFrom

`func (o *OwnedMediaSummaryResponse) SetFrom(v time.Time)`

SetFrom sets From field to given value.

### HasFrom

`func (o *OwnedMediaSummaryResponse) HasFrom() bool`

HasFrom returns a boolean if a field has been set.

### GetTo

`func (o *OwnedMediaSummaryResponse) GetTo() time.Time`

GetTo returns the To field if non-nil, zero value otherwise.

### GetToOk

`func (o *OwnedMediaSummaryResponse) GetToOk() (*time.Time, bool)`

GetToOk returns a tuple with the To field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTo

`func (o *OwnedMediaSummaryResponse) SetTo(v time.Time)`

SetTo sets To field to given value.

### HasTo

`func (o *OwnedMediaSummaryResponse) HasTo() bool`

HasTo returns a boolean if a field has been set.

### GetConnected

`func (o *OwnedMediaSummaryResponse) GetConnected() bool`

GetConnected returns the Connected field if non-nil, zero value otherwise.

### GetConnectedOk

`func (o *OwnedMediaSummaryResponse) GetConnectedOk() (*bool, bool)`

GetConnectedOk returns a tuple with the Connected field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConnected

`func (o *OwnedMediaSummaryResponse) SetConnected(v bool)`

SetConnected sets Connected field to given value.

### HasConnected

`func (o *OwnedMediaSummaryResponse) HasConnected() bool`

HasConnected returns a boolean if a field has been set.

### GetKpis

`func (o *OwnedMediaSummaryResponse) GetKpis() OwnedMediaKpis`

GetKpis returns the Kpis field if non-nil, zero value otherwise.

### GetKpisOk

`func (o *OwnedMediaSummaryResponse) GetKpisOk() (*OwnedMediaKpis, bool)`

GetKpisOk returns a tuple with the Kpis field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKpis

`func (o *OwnedMediaSummaryResponse) SetKpis(v OwnedMediaKpis)`

SetKpis sets Kpis field to given value.

### HasKpis

`func (o *OwnedMediaSummaryResponse) HasKpis() bool`

HasKpis returns a boolean if a field has been set.

### GetPrevious

`func (o *OwnedMediaSummaryResponse) GetPrevious() OwnedMediaSummaryResponsePrevious`

GetPrevious returns the Previous field if non-nil, zero value otherwise.

### GetPreviousOk

`func (o *OwnedMediaSummaryResponse) GetPreviousOk() (*OwnedMediaSummaryResponsePrevious, bool)`

GetPreviousOk returns a tuple with the Previous field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrevious

`func (o *OwnedMediaSummaryResponse) SetPrevious(v OwnedMediaSummaryResponsePrevious)`

SetPrevious sets Previous field to given value.

### HasPrevious

`func (o *OwnedMediaSummaryResponse) HasPrevious() bool`

HasPrevious returns a boolean if a field has been set.

### GetChanges

`func (o *OwnedMediaSummaryResponse) GetChanges() OwnedMediaKpiChanges`

GetChanges returns the Changes field if non-nil, zero value otherwise.

### GetChangesOk

`func (o *OwnedMediaSummaryResponse) GetChangesOk() (*OwnedMediaKpiChanges, bool)`

GetChangesOk returns a tuple with the Changes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChanges

`func (o *OwnedMediaSummaryResponse) SetChanges(v OwnedMediaKpiChanges)`

SetChanges sets Changes field to given value.

### HasChanges

`func (o *OwnedMediaSummaryResponse) HasChanges() bool`

HasChanges returns a boolean if a field has been set.

### GetWeekly

`func (o *OwnedMediaSummaryResponse) GetWeekly() []OwnedMediaWeek`

GetWeekly returns the Weekly field if non-nil, zero value otherwise.

### GetWeeklyOk

`func (o *OwnedMediaSummaryResponse) GetWeeklyOk() (*[]OwnedMediaWeek, bool)`

GetWeeklyOk returns a tuple with the Weekly field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWeekly

`func (o *OwnedMediaSummaryResponse) SetWeekly(v []OwnedMediaWeek)`

SetWeekly sets Weekly field to given value.

### HasWeekly

`func (o *OwnedMediaSummaryResponse) HasWeekly() bool`

HasWeekly returns a boolean if a field has been set.

### GetByModel

`func (o *OwnedMediaSummaryResponse) GetByModel() []OwnedMediaModelShare`

GetByModel returns the ByModel field if non-nil, zero value otherwise.

### GetByModelOk

`func (o *OwnedMediaSummaryResponse) GetByModelOk() (*[]OwnedMediaModelShare, bool)`

GetByModelOk returns a tuple with the ByModel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetByModel

`func (o *OwnedMediaSummaryResponse) SetByModel(v []OwnedMediaModelShare)`

SetByModel sets ByModel field to given value.

### HasByModel

`func (o *OwnedMediaSummaryResponse) HasByModel() bool`

HasByModel returns a boolean if a field has been set.

### SetByModelNil

`func (o *OwnedMediaSummaryResponse) SetByModelNil(b bool)`

 SetByModelNil sets the value for ByModel to be an explicit nil

### UnsetByModel
`func (o *OwnedMediaSummaryResponse) UnsetByModel()`

UnsetByModel ensures that no value is present for ByModel, not even an explicit nil
### GetByCountry

`func (o *OwnedMediaSummaryResponse) GetByCountry() []OwnedMediaCountryShare`

GetByCountry returns the ByCountry field if non-nil, zero value otherwise.

### GetByCountryOk

`func (o *OwnedMediaSummaryResponse) GetByCountryOk() (*[]OwnedMediaCountryShare, bool)`

GetByCountryOk returns a tuple with the ByCountry field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetByCountry

`func (o *OwnedMediaSummaryResponse) SetByCountry(v []OwnedMediaCountryShare)`

SetByCountry sets ByCountry field to given value.

### HasByCountry

`func (o *OwnedMediaSummaryResponse) HasByCountry() bool`

HasByCountry returns a boolean if a field has been set.

### SetByCountryNil

`func (o *OwnedMediaSummaryResponse) SetByCountryNil(b bool)`

 SetByCountryNil sets the value for ByCountry to be an explicit nil

### UnsetByCountry
`func (o *OwnedMediaSummaryResponse) UnsetByCountry()`

UnsetByCountry ensures that no value is present for ByCountry, not even an explicit nil
### GetContentTypes

`func (o *OwnedMediaSummaryResponse) GetContentTypes() []OwnedMediaContentTypeShare`

GetContentTypes returns the ContentTypes field if non-nil, zero value otherwise.

### GetContentTypesOk

`func (o *OwnedMediaSummaryResponse) GetContentTypesOk() (*[]OwnedMediaContentTypeShare, bool)`

GetContentTypesOk returns a tuple with the ContentTypes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContentTypes

`func (o *OwnedMediaSummaryResponse) SetContentTypes(v []OwnedMediaContentTypeShare)`

SetContentTypes sets ContentTypes field to given value.

### HasContentTypes

`func (o *OwnedMediaSummaryResponse) HasContentTypes() bool`

HasContentTypes returns a boolean if a field has been set.

### SetContentTypesNil

`func (o *OwnedMediaSummaryResponse) SetContentTypesNil(b bool)`

 SetContentTypesNil sets the value for ContentTypes to be an explicit nil

### UnsetContentTypes
`func (o *OwnedMediaSummaryResponse) UnsetContentTypes()`

UnsetContentTypes ensures that no value is present for ContentTypes, not even an explicit nil
### GetAgeBuckets

`func (o *OwnedMediaSummaryResponse) GetAgeBuckets() []OwnedMediaAgeBucketShare`

GetAgeBuckets returns the AgeBuckets field if non-nil, zero value otherwise.

### GetAgeBucketsOk

`func (o *OwnedMediaSummaryResponse) GetAgeBucketsOk() (*[]OwnedMediaAgeBucketShare, bool)`

GetAgeBucketsOk returns a tuple with the AgeBuckets field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAgeBuckets

`func (o *OwnedMediaSummaryResponse) SetAgeBuckets(v []OwnedMediaAgeBucketShare)`

SetAgeBuckets sets AgeBuckets field to given value.

### HasAgeBuckets

`func (o *OwnedMediaSummaryResponse) HasAgeBuckets() bool`

HasAgeBuckets returns a boolean if a field has been set.

### SetAgeBucketsNil

`func (o *OwnedMediaSummaryResponse) SetAgeBucketsNil(b bool)`

 SetAgeBucketsNil sets the value for AgeBuckets to be an explicit nil

### UnsetAgeBuckets
`func (o *OwnedMediaSummaryResponse) UnsetAgeBuckets()`

UnsetAgeBuckets ensures that no value is present for AgeBuckets, not even an explicit nil
### GetStores

`func (o *OwnedMediaSummaryResponse) GetStores() []OwnedMediaStoreTotals`

GetStores returns the Stores field if non-nil, zero value otherwise.

### GetStoresOk

`func (o *OwnedMediaSummaryResponse) GetStoresOk() (*[]OwnedMediaStoreTotals, bool)`

GetStoresOk returns a tuple with the Stores field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStores

`func (o *OwnedMediaSummaryResponse) SetStores(v []OwnedMediaStoreTotals)`

SetStores sets Stores field to given value.

### HasStores

`func (o *OwnedMediaSummaryResponse) HasStores() bool`

HasStores returns a boolean if a field has been set.

### SetStoresNil

`func (o *OwnedMediaSummaryResponse) SetStoresNil(b bool)`

 SetStoresNil sets the value for Stores to be an explicit nil

### UnsetStores
`func (o *OwnedMediaSummaryResponse) UnsetStores()`

UnsetStores ensures that no value is present for Stores, not even an explicit nil
### GetPlatforms

`func (o *OwnedMediaSummaryResponse) GetPlatforms() []OwnedMediaPlatformRollup`

GetPlatforms returns the Platforms field if non-nil, zero value otherwise.

### GetPlatformsOk

`func (o *OwnedMediaSummaryResponse) GetPlatformsOk() (*[]OwnedMediaPlatformRollup, bool)`

GetPlatformsOk returns a tuple with the Platforms field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlatforms

`func (o *OwnedMediaSummaryResponse) SetPlatforms(v []OwnedMediaPlatformRollup)`

SetPlatforms sets Platforms field to given value.

### HasPlatforms

`func (o *OwnedMediaSummaryResponse) HasPlatforms() bool`

HasPlatforms returns a boolean if a field has been set.

### SetPlatformsNil

`func (o *OwnedMediaSummaryResponse) SetPlatformsNil(b bool)`

 SetPlatformsNil sets the value for Platforms to be an explicit nil

### UnsetPlatforms
`func (o *OwnedMediaSummaryResponse) UnsetPlatforms()`

UnsetPlatforms ensures that no value is present for Platforms, not even an explicit nil
### GetRequestId

`func (o *OwnedMediaSummaryResponse) GetRequestId() string`

GetRequestId returns the RequestId field if non-nil, zero value otherwise.

### GetRequestIdOk

`func (o *OwnedMediaSummaryResponse) GetRequestIdOk() (*string, bool)`

GetRequestIdOk returns a tuple with the RequestId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestId

`func (o *OwnedMediaSummaryResponse) SetRequestId(v string)`

SetRequestId sets RequestId field to given value.

### HasRequestId

`func (o *OwnedMediaSummaryResponse) HasRequestId() bool`

HasRequestId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


