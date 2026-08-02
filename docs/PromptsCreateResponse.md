# PromptsCreateResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ProjectId** | Pointer to **int32** |  | [optional] 
**Created** | Pointer to **int32** |  | [optional] 
**Skipped** | Pointer to **int32** |  | [optional] 
**TotalAfter** | Pointer to **int32** |  | [optional] 
**PromptsAvailable** | Pointer to **int32** |  | [optional] 
**Data** | Pointer to [**[]PromptsCreateResponseDataInner**](PromptsCreateResponseDataInner.md) |  | [optional] 
**RequestId** | Pointer to **string** |  | [optional] 

## Methods

### NewPromptsCreateResponse

`func NewPromptsCreateResponse() *PromptsCreateResponse`

NewPromptsCreateResponse instantiates a new PromptsCreateResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPromptsCreateResponseWithDefaults

`func NewPromptsCreateResponseWithDefaults() *PromptsCreateResponse`

NewPromptsCreateResponseWithDefaults instantiates a new PromptsCreateResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProjectId

`func (o *PromptsCreateResponse) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *PromptsCreateResponse) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *PromptsCreateResponse) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.

### HasProjectId

`func (o *PromptsCreateResponse) HasProjectId() bool`

HasProjectId returns a boolean if a field has been set.

### GetCreated

`func (o *PromptsCreateResponse) GetCreated() int32`

GetCreated returns the Created field if non-nil, zero value otherwise.

### GetCreatedOk

`func (o *PromptsCreateResponse) GetCreatedOk() (*int32, bool)`

GetCreatedOk returns a tuple with the Created field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreated

`func (o *PromptsCreateResponse) SetCreated(v int32)`

SetCreated sets Created field to given value.

### HasCreated

`func (o *PromptsCreateResponse) HasCreated() bool`

HasCreated returns a boolean if a field has been set.

### GetSkipped

`func (o *PromptsCreateResponse) GetSkipped() int32`

GetSkipped returns the Skipped field if non-nil, zero value otherwise.

### GetSkippedOk

`func (o *PromptsCreateResponse) GetSkippedOk() (*int32, bool)`

GetSkippedOk returns a tuple with the Skipped field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSkipped

`func (o *PromptsCreateResponse) SetSkipped(v int32)`

SetSkipped sets Skipped field to given value.

### HasSkipped

`func (o *PromptsCreateResponse) HasSkipped() bool`

HasSkipped returns a boolean if a field has been set.

### GetTotalAfter

`func (o *PromptsCreateResponse) GetTotalAfter() int32`

GetTotalAfter returns the TotalAfter field if non-nil, zero value otherwise.

### GetTotalAfterOk

`func (o *PromptsCreateResponse) GetTotalAfterOk() (*int32, bool)`

GetTotalAfterOk returns a tuple with the TotalAfter field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalAfter

`func (o *PromptsCreateResponse) SetTotalAfter(v int32)`

SetTotalAfter sets TotalAfter field to given value.

### HasTotalAfter

`func (o *PromptsCreateResponse) HasTotalAfter() bool`

HasTotalAfter returns a boolean if a field has been set.

### GetPromptsAvailable

`func (o *PromptsCreateResponse) GetPromptsAvailable() int32`

GetPromptsAvailable returns the PromptsAvailable field if non-nil, zero value otherwise.

### GetPromptsAvailableOk

`func (o *PromptsCreateResponse) GetPromptsAvailableOk() (*int32, bool)`

GetPromptsAvailableOk returns a tuple with the PromptsAvailable field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPromptsAvailable

`func (o *PromptsCreateResponse) SetPromptsAvailable(v int32)`

SetPromptsAvailable sets PromptsAvailable field to given value.

### HasPromptsAvailable

`func (o *PromptsCreateResponse) HasPromptsAvailable() bool`

HasPromptsAvailable returns a boolean if a field has been set.

### GetData

`func (o *PromptsCreateResponse) GetData() []PromptsCreateResponseDataInner`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *PromptsCreateResponse) GetDataOk() (*[]PromptsCreateResponseDataInner, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *PromptsCreateResponse) SetData(v []PromptsCreateResponseDataInner)`

SetData sets Data field to given value.

### HasData

`func (o *PromptsCreateResponse) HasData() bool`

HasData returns a boolean if a field has been set.

### GetRequestId

`func (o *PromptsCreateResponse) GetRequestId() string`

GetRequestId returns the RequestId field if non-nil, zero value otherwise.

### GetRequestIdOk

`func (o *PromptsCreateResponse) GetRequestIdOk() (*string, bool)`

GetRequestIdOk returns a tuple with the RequestId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestId

`func (o *PromptsCreateResponse) SetRequestId(v string)`

SetRequestId sets RequestId field to given value.

### HasRequestId

`func (o *PromptsCreateResponse) HasRequestId() bool`

HasRequestId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


