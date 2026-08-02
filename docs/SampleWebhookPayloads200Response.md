# SampleWebhookPayloads200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**EventType** | Pointer to **string** |  | [optional] 
**Data** | Pointer to [**[]SampleWebhookPayloads200ResponseDataInner**](SampleWebhookPayloads200ResponseDataInner.md) |  | [optional] 
**RequestId** | Pointer to **string** |  | [optional] 

## Methods

### NewSampleWebhookPayloads200Response

`func NewSampleWebhookPayloads200Response() *SampleWebhookPayloads200Response`

NewSampleWebhookPayloads200Response instantiates a new SampleWebhookPayloads200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSampleWebhookPayloads200ResponseWithDefaults

`func NewSampleWebhookPayloads200ResponseWithDefaults() *SampleWebhookPayloads200Response`

NewSampleWebhookPayloads200ResponseWithDefaults instantiates a new SampleWebhookPayloads200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetEventType

`func (o *SampleWebhookPayloads200Response) GetEventType() string`

GetEventType returns the EventType field if non-nil, zero value otherwise.

### GetEventTypeOk

`func (o *SampleWebhookPayloads200Response) GetEventTypeOk() (*string, bool)`

GetEventTypeOk returns a tuple with the EventType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEventType

`func (o *SampleWebhookPayloads200Response) SetEventType(v string)`

SetEventType sets EventType field to given value.

### HasEventType

`func (o *SampleWebhookPayloads200Response) HasEventType() bool`

HasEventType returns a boolean if a field has been set.

### GetData

`func (o *SampleWebhookPayloads200Response) GetData() []SampleWebhookPayloads200ResponseDataInner`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *SampleWebhookPayloads200Response) GetDataOk() (*[]SampleWebhookPayloads200ResponseDataInner, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *SampleWebhookPayloads200Response) SetData(v []SampleWebhookPayloads200ResponseDataInner)`

SetData sets Data field to given value.

### HasData

`func (o *SampleWebhookPayloads200Response) HasData() bool`

HasData returns a boolean if a field has been set.

### GetRequestId

`func (o *SampleWebhookPayloads200Response) GetRequestId() string`

GetRequestId returns the RequestId field if non-nil, zero value otherwise.

### GetRequestIdOk

`func (o *SampleWebhookPayloads200Response) GetRequestIdOk() (*string, bool)`

GetRequestIdOk returns a tuple with the RequestId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestId

`func (o *SampleWebhookPayloads200Response) SetRequestId(v string)`

SetRequestId sets RequestId field to given value.

### HasRequestId

`func (o *SampleWebhookPayloads200Response) HasRequestId() bool`

HasRequestId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


