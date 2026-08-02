# AgentBotsResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Bots** | Pointer to [**[]AgentBot**](AgentBot.md) |  | [optional] 
**Companies** | Pointer to **[]string** |  | [optional] 
**RequestId** | Pointer to **string** |  | [optional] 

## Methods

### NewAgentBotsResponse

`func NewAgentBotsResponse() *AgentBotsResponse`

NewAgentBotsResponse instantiates a new AgentBotsResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAgentBotsResponseWithDefaults

`func NewAgentBotsResponseWithDefaults() *AgentBotsResponse`

NewAgentBotsResponseWithDefaults instantiates a new AgentBotsResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBots

`func (o *AgentBotsResponse) GetBots() []AgentBot`

GetBots returns the Bots field if non-nil, zero value otherwise.

### GetBotsOk

`func (o *AgentBotsResponse) GetBotsOk() (*[]AgentBot, bool)`

GetBotsOk returns a tuple with the Bots field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBots

`func (o *AgentBotsResponse) SetBots(v []AgentBot)`

SetBots sets Bots field to given value.

### HasBots

`func (o *AgentBotsResponse) HasBots() bool`

HasBots returns a boolean if a field has been set.

### GetCompanies

`func (o *AgentBotsResponse) GetCompanies() []string`

GetCompanies returns the Companies field if non-nil, zero value otherwise.

### GetCompaniesOk

`func (o *AgentBotsResponse) GetCompaniesOk() (*[]string, bool)`

GetCompaniesOk returns a tuple with the Companies field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompanies

`func (o *AgentBotsResponse) SetCompanies(v []string)`

SetCompanies sets Companies field to given value.

### HasCompanies

`func (o *AgentBotsResponse) HasCompanies() bool`

HasCompanies returns a boolean if a field has been set.

### GetRequestId

`func (o *AgentBotsResponse) GetRequestId() string`

GetRequestId returns the RequestId field if non-nil, zero value otherwise.

### GetRequestIdOk

`func (o *AgentBotsResponse) GetRequestIdOk() (*string, bool)`

GetRequestIdOk returns a tuple with the RequestId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestId

`func (o *AgentBotsResponse) SetRequestId(v string)`

SetRequestId sets RequestId field to given value.

### HasRequestId

`func (o *AgentBotsResponse) HasRequestId() bool`

HasRequestId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


