# PromptsCreateResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ProjectId** | Pointer to **int32** |  | [optional] 
**Created** | Pointer to **int32** |  | [optional] 
**Skipped** | Pointer to **int32** |  | [optional] 
**TotalAfter** | Pointer to **int32** |  | [optional] 
**PromptsAvailable** | Pointer to **int32** |  | [optional] 
**Tracked** | Pointer to **bool** | Whether scheduled runs include the project the prompts were added to. False when it is paused or beyond the plan&#39;s project limit, so the new prompts do not run until that changes | [optional] 
**UntrackedReason** | Pointer to **NullableString** | Why tracked is false: paused or project_limit. Null when tracked | [optional] 
**Warning** | Pointer to **NullableString** | What to do when tracked is false. Null when tracked | [optional] 
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

### GetTracked

`func (o *PromptsCreateResponse) GetTracked() bool`

GetTracked returns the Tracked field if non-nil, zero value otherwise.

### GetTrackedOk

`func (o *PromptsCreateResponse) GetTrackedOk() (*bool, bool)`

GetTrackedOk returns a tuple with the Tracked field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTracked

`func (o *PromptsCreateResponse) SetTracked(v bool)`

SetTracked sets Tracked field to given value.

### HasTracked

`func (o *PromptsCreateResponse) HasTracked() bool`

HasTracked returns a boolean if a field has been set.

### GetUntrackedReason

`func (o *PromptsCreateResponse) GetUntrackedReason() string`

GetUntrackedReason returns the UntrackedReason field if non-nil, zero value otherwise.

### GetUntrackedReasonOk

`func (o *PromptsCreateResponse) GetUntrackedReasonOk() (*string, bool)`

GetUntrackedReasonOk returns a tuple with the UntrackedReason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUntrackedReason

`func (o *PromptsCreateResponse) SetUntrackedReason(v string)`

SetUntrackedReason sets UntrackedReason field to given value.

### HasUntrackedReason

`func (o *PromptsCreateResponse) HasUntrackedReason() bool`

HasUntrackedReason returns a boolean if a field has been set.

### SetUntrackedReasonNil

`func (o *PromptsCreateResponse) SetUntrackedReasonNil(b bool)`

 SetUntrackedReasonNil sets the value for UntrackedReason to be an explicit nil

### UnsetUntrackedReason
`func (o *PromptsCreateResponse) UnsetUntrackedReason()`

UnsetUntrackedReason ensures that no value is present for UntrackedReason, not even an explicit nil
### GetWarning

`func (o *PromptsCreateResponse) GetWarning() string`

GetWarning returns the Warning field if non-nil, zero value otherwise.

### GetWarningOk

`func (o *PromptsCreateResponse) GetWarningOk() (*string, bool)`

GetWarningOk returns a tuple with the Warning field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWarning

`func (o *PromptsCreateResponse) SetWarning(v string)`

SetWarning sets Warning field to given value.

### HasWarning

`func (o *PromptsCreateResponse) HasWarning() bool`

HasWarning returns a boolean if a field has been set.

### SetWarningNil

`func (o *PromptsCreateResponse) SetWarningNil(b bool)`

 SetWarningNil sets the value for Warning to be an explicit nil

### UnsetWarning
`func (o *PromptsCreateResponse) UnsetWarning()`

UnsetWarning ensures that no value is present for Warning, not even an explicit nil
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


