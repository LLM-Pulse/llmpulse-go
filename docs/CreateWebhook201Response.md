# CreateWebhook201Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **int32** |  | [optional] 
**ProjectId** | Pointer to **int32** |  | [optional] 
**EventType** | Pointer to **string** |  | [optional] 
**TargetUrl** | Pointer to **string** |  | [optional] 
**Disabled** | Pointer to **bool** |  | [optional] 
**FailureCount** | Pointer to **int32** |  | [optional] 
**LastDeliveredAt** | Pointer to **NullableTime** |  | [optional] 
**CreatedAt** | Pointer to **time.Time** |  | [optional] 
**Secret** | Pointer to **string** | HMAC signing secret (whsec_...). Only returned on create. | [optional] 
**RequestId** | Pointer to **string** |  | [optional] 

## Methods

### NewCreateWebhook201Response

`func NewCreateWebhook201Response() *CreateWebhook201Response`

NewCreateWebhook201Response instantiates a new CreateWebhook201Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateWebhook201ResponseWithDefaults

`func NewCreateWebhook201ResponseWithDefaults() *CreateWebhook201Response`

NewCreateWebhook201ResponseWithDefaults instantiates a new CreateWebhook201Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *CreateWebhook201Response) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *CreateWebhook201Response) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *CreateWebhook201Response) SetId(v int32)`

SetId sets Id field to given value.

### HasId

`func (o *CreateWebhook201Response) HasId() bool`

HasId returns a boolean if a field has been set.

### GetProjectId

`func (o *CreateWebhook201Response) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *CreateWebhook201Response) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *CreateWebhook201Response) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.

### HasProjectId

`func (o *CreateWebhook201Response) HasProjectId() bool`

HasProjectId returns a boolean if a field has been set.

### GetEventType

`func (o *CreateWebhook201Response) GetEventType() string`

GetEventType returns the EventType field if non-nil, zero value otherwise.

### GetEventTypeOk

`func (o *CreateWebhook201Response) GetEventTypeOk() (*string, bool)`

GetEventTypeOk returns a tuple with the EventType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEventType

`func (o *CreateWebhook201Response) SetEventType(v string)`

SetEventType sets EventType field to given value.

### HasEventType

`func (o *CreateWebhook201Response) HasEventType() bool`

HasEventType returns a boolean if a field has been set.

### GetTargetUrl

`func (o *CreateWebhook201Response) GetTargetUrl() string`

GetTargetUrl returns the TargetUrl field if non-nil, zero value otherwise.

### GetTargetUrlOk

`func (o *CreateWebhook201Response) GetTargetUrlOk() (*string, bool)`

GetTargetUrlOk returns a tuple with the TargetUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTargetUrl

`func (o *CreateWebhook201Response) SetTargetUrl(v string)`

SetTargetUrl sets TargetUrl field to given value.

### HasTargetUrl

`func (o *CreateWebhook201Response) HasTargetUrl() bool`

HasTargetUrl returns a boolean if a field has been set.

### GetDisabled

`func (o *CreateWebhook201Response) GetDisabled() bool`

GetDisabled returns the Disabled field if non-nil, zero value otherwise.

### GetDisabledOk

`func (o *CreateWebhook201Response) GetDisabledOk() (*bool, bool)`

GetDisabledOk returns a tuple with the Disabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDisabled

`func (o *CreateWebhook201Response) SetDisabled(v bool)`

SetDisabled sets Disabled field to given value.

### HasDisabled

`func (o *CreateWebhook201Response) HasDisabled() bool`

HasDisabled returns a boolean if a field has been set.

### GetFailureCount

`func (o *CreateWebhook201Response) GetFailureCount() int32`

GetFailureCount returns the FailureCount field if non-nil, zero value otherwise.

### GetFailureCountOk

`func (o *CreateWebhook201Response) GetFailureCountOk() (*int32, bool)`

GetFailureCountOk returns a tuple with the FailureCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFailureCount

`func (o *CreateWebhook201Response) SetFailureCount(v int32)`

SetFailureCount sets FailureCount field to given value.

### HasFailureCount

`func (o *CreateWebhook201Response) HasFailureCount() bool`

HasFailureCount returns a boolean if a field has been set.

### GetLastDeliveredAt

`func (o *CreateWebhook201Response) GetLastDeliveredAt() time.Time`

GetLastDeliveredAt returns the LastDeliveredAt field if non-nil, zero value otherwise.

### GetLastDeliveredAtOk

`func (o *CreateWebhook201Response) GetLastDeliveredAtOk() (*time.Time, bool)`

GetLastDeliveredAtOk returns a tuple with the LastDeliveredAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastDeliveredAt

`func (o *CreateWebhook201Response) SetLastDeliveredAt(v time.Time)`

SetLastDeliveredAt sets LastDeliveredAt field to given value.

### HasLastDeliveredAt

`func (o *CreateWebhook201Response) HasLastDeliveredAt() bool`

HasLastDeliveredAt returns a boolean if a field has been set.

### SetLastDeliveredAtNil

`func (o *CreateWebhook201Response) SetLastDeliveredAtNil(b bool)`

 SetLastDeliveredAtNil sets the value for LastDeliveredAt to be an explicit nil

### UnsetLastDeliveredAt
`func (o *CreateWebhook201Response) UnsetLastDeliveredAt()`

UnsetLastDeliveredAt ensures that no value is present for LastDeliveredAt, not even an explicit nil
### GetCreatedAt

`func (o *CreateWebhook201Response) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *CreateWebhook201Response) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *CreateWebhook201Response) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *CreateWebhook201Response) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetSecret

`func (o *CreateWebhook201Response) GetSecret() string`

GetSecret returns the Secret field if non-nil, zero value otherwise.

### GetSecretOk

`func (o *CreateWebhook201Response) GetSecretOk() (*string, bool)`

GetSecretOk returns a tuple with the Secret field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSecret

`func (o *CreateWebhook201Response) SetSecret(v string)`

SetSecret sets Secret field to given value.

### HasSecret

`func (o *CreateWebhook201Response) HasSecret() bool`

HasSecret returns a boolean if a field has been set.

### GetRequestId

`func (o *CreateWebhook201Response) GetRequestId() string`

GetRequestId returns the RequestId field if non-nil, zero value otherwise.

### GetRequestIdOk

`func (o *CreateWebhook201Response) GetRequestIdOk() (*string, bool)`

GetRequestIdOk returns a tuple with the RequestId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestId

`func (o *CreateWebhook201Response) SetRequestId(v string)`

SetRequestId sets RequestId field to given value.

### HasRequestId

`func (o *CreateWebhook201Response) HasRequestId() bool`

HasRequestId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


