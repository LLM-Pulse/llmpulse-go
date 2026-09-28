# ListWebhooks200ResponseDataInner

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

## Methods

### NewListWebhooks200ResponseDataInner

`func NewListWebhooks200ResponseDataInner() *ListWebhooks200ResponseDataInner`

NewListWebhooks200ResponseDataInner instantiates a new ListWebhooks200ResponseDataInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewListWebhooks200ResponseDataInnerWithDefaults

`func NewListWebhooks200ResponseDataInnerWithDefaults() *ListWebhooks200ResponseDataInner`

NewListWebhooks200ResponseDataInnerWithDefaults instantiates a new ListWebhooks200ResponseDataInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *ListWebhooks200ResponseDataInner) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ListWebhooks200ResponseDataInner) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ListWebhooks200ResponseDataInner) SetId(v int32)`

SetId sets Id field to given value.

### HasId

`func (o *ListWebhooks200ResponseDataInner) HasId() bool`

HasId returns a boolean if a field has been set.

### GetProjectId

`func (o *ListWebhooks200ResponseDataInner) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *ListWebhooks200ResponseDataInner) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *ListWebhooks200ResponseDataInner) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.

### HasProjectId

`func (o *ListWebhooks200ResponseDataInner) HasProjectId() bool`

HasProjectId returns a boolean if a field has been set.

### GetEventType

`func (o *ListWebhooks200ResponseDataInner) GetEventType() string`

GetEventType returns the EventType field if non-nil, zero value otherwise.

### GetEventTypeOk

`func (o *ListWebhooks200ResponseDataInner) GetEventTypeOk() (*string, bool)`

GetEventTypeOk returns a tuple with the EventType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEventType

`func (o *ListWebhooks200ResponseDataInner) SetEventType(v string)`

SetEventType sets EventType field to given value.

### HasEventType

`func (o *ListWebhooks200ResponseDataInner) HasEventType() bool`

HasEventType returns a boolean if a field has been set.

### GetTargetUrl

`func (o *ListWebhooks200ResponseDataInner) GetTargetUrl() string`

GetTargetUrl returns the TargetUrl field if non-nil, zero value otherwise.

### GetTargetUrlOk

`func (o *ListWebhooks200ResponseDataInner) GetTargetUrlOk() (*string, bool)`

GetTargetUrlOk returns a tuple with the TargetUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTargetUrl

`func (o *ListWebhooks200ResponseDataInner) SetTargetUrl(v string)`

SetTargetUrl sets TargetUrl field to given value.

### HasTargetUrl

`func (o *ListWebhooks200ResponseDataInner) HasTargetUrl() bool`

HasTargetUrl returns a boolean if a field has been set.

### GetDisabled

`func (o *ListWebhooks200ResponseDataInner) GetDisabled() bool`

GetDisabled returns the Disabled field if non-nil, zero value otherwise.

### GetDisabledOk

`func (o *ListWebhooks200ResponseDataInner) GetDisabledOk() (*bool, bool)`

GetDisabledOk returns a tuple with the Disabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDisabled

`func (o *ListWebhooks200ResponseDataInner) SetDisabled(v bool)`

SetDisabled sets Disabled field to given value.

### HasDisabled

`func (o *ListWebhooks200ResponseDataInner) HasDisabled() bool`

HasDisabled returns a boolean if a field has been set.

### GetFailureCount

`func (o *ListWebhooks200ResponseDataInner) GetFailureCount() int32`

GetFailureCount returns the FailureCount field if non-nil, zero value otherwise.

### GetFailureCountOk

`func (o *ListWebhooks200ResponseDataInner) GetFailureCountOk() (*int32, bool)`

GetFailureCountOk returns a tuple with the FailureCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFailureCount

`func (o *ListWebhooks200ResponseDataInner) SetFailureCount(v int32)`

SetFailureCount sets FailureCount field to given value.

### HasFailureCount

`func (o *ListWebhooks200ResponseDataInner) HasFailureCount() bool`

HasFailureCount returns a boolean if a field has been set.

### GetLastDeliveredAt

`func (o *ListWebhooks200ResponseDataInner) GetLastDeliveredAt() time.Time`

GetLastDeliveredAt returns the LastDeliveredAt field if non-nil, zero value otherwise.

### GetLastDeliveredAtOk

`func (o *ListWebhooks200ResponseDataInner) GetLastDeliveredAtOk() (*time.Time, bool)`

GetLastDeliveredAtOk returns a tuple with the LastDeliveredAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastDeliveredAt

`func (o *ListWebhooks200ResponseDataInner) SetLastDeliveredAt(v time.Time)`

SetLastDeliveredAt sets LastDeliveredAt field to given value.

### HasLastDeliveredAt

`func (o *ListWebhooks200ResponseDataInner) HasLastDeliveredAt() bool`

HasLastDeliveredAt returns a boolean if a field has been set.

### SetLastDeliveredAtNil

`func (o *ListWebhooks200ResponseDataInner) SetLastDeliveredAtNil(b bool)`

 SetLastDeliveredAtNil sets the value for LastDeliveredAt to be an explicit nil

### UnsetLastDeliveredAt
`func (o *ListWebhooks200ResponseDataInner) UnsetLastDeliveredAt()`

UnsetLastDeliveredAt ensures that no value is present for LastDeliveredAt, not even an explicit nil
### GetCreatedAt

`func (o *ListWebhooks200ResponseDataInner) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *ListWebhooks200ResponseDataInner) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *ListWebhooks200ResponseDataInner) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *ListWebhooks200ResponseDataInner) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


