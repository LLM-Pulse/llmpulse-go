# AiOrdersUpdateResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ProjectId** | **int32** |  | 
**Platform** | **string** |  | 
**Stored** | **int32** | Rows stored, one per day and AI assistant | 
**Ignored** | **int32** | Entries whose referrer is not an AI assistant | 
**RequestId** | **string** |  | 

## Methods

### NewAiOrdersUpdateResponse

`func NewAiOrdersUpdateResponse(projectId int32, platform string, stored int32, ignored int32, requestId string, ) *AiOrdersUpdateResponse`

NewAiOrdersUpdateResponse instantiates a new AiOrdersUpdateResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAiOrdersUpdateResponseWithDefaults

`func NewAiOrdersUpdateResponseWithDefaults() *AiOrdersUpdateResponse`

NewAiOrdersUpdateResponseWithDefaults instantiates a new AiOrdersUpdateResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProjectId

`func (o *AiOrdersUpdateResponse) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *AiOrdersUpdateResponse) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *AiOrdersUpdateResponse) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.


### GetPlatform

`func (o *AiOrdersUpdateResponse) GetPlatform() string`

GetPlatform returns the Platform field if non-nil, zero value otherwise.

### GetPlatformOk

`func (o *AiOrdersUpdateResponse) GetPlatformOk() (*string, bool)`

GetPlatformOk returns a tuple with the Platform field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlatform

`func (o *AiOrdersUpdateResponse) SetPlatform(v string)`

SetPlatform sets Platform field to given value.


### GetStored

`func (o *AiOrdersUpdateResponse) GetStored() int32`

GetStored returns the Stored field if non-nil, zero value otherwise.

### GetStoredOk

`func (o *AiOrdersUpdateResponse) GetStoredOk() (*int32, bool)`

GetStoredOk returns a tuple with the Stored field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStored

`func (o *AiOrdersUpdateResponse) SetStored(v int32)`

SetStored sets Stored field to given value.


### GetIgnored

`func (o *AiOrdersUpdateResponse) GetIgnored() int32`

GetIgnored returns the Ignored field if non-nil, zero value otherwise.

### GetIgnoredOk

`func (o *AiOrdersUpdateResponse) GetIgnoredOk() (*int32, bool)`

GetIgnoredOk returns a tuple with the Ignored field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIgnored

`func (o *AiOrdersUpdateResponse) SetIgnored(v int32)`

SetIgnored sets Ignored field to given value.


### GetRequestId

`func (o *AiOrdersUpdateResponse) GetRequestId() string`

GetRequestId returns the RequestId field if non-nil, zero value otherwise.

### GetRequestIdOk

`func (o *AiOrdersUpdateResponse) GetRequestIdOk() (*string, bool)`

GetRequestIdOk returns a tuple with the RequestId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestId

`func (o *AiOrdersUpdateResponse) SetRequestId(v string)`

SetRequestId sets RequestId field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


