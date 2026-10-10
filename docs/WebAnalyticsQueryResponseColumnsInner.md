# WebAnalyticsQueryResponseColumnsInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | Pointer to **string** |  | [optional] 
**Kind** | Pointer to **string** | dimension or metric, when the provider says. | [optional] 
**Type** | Pointer to **string** | The provider&#39;s column type, when it says (PostHog). | [optional] 
**Label** | Pointer to **string** | The provider&#39;s display label, when it sends one (Piano). | [optional] 

## Methods

### NewWebAnalyticsQueryResponseColumnsInner

`func NewWebAnalyticsQueryResponseColumnsInner() *WebAnalyticsQueryResponseColumnsInner`

NewWebAnalyticsQueryResponseColumnsInner instantiates a new WebAnalyticsQueryResponseColumnsInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewWebAnalyticsQueryResponseColumnsInnerWithDefaults

`func NewWebAnalyticsQueryResponseColumnsInnerWithDefaults() *WebAnalyticsQueryResponseColumnsInner`

NewWebAnalyticsQueryResponseColumnsInnerWithDefaults instantiates a new WebAnalyticsQueryResponseColumnsInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *WebAnalyticsQueryResponseColumnsInner) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *WebAnalyticsQueryResponseColumnsInner) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *WebAnalyticsQueryResponseColumnsInner) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *WebAnalyticsQueryResponseColumnsInner) HasName() bool`

HasName returns a boolean if a field has been set.

### GetKind

`func (o *WebAnalyticsQueryResponseColumnsInner) GetKind() string`

GetKind returns the Kind field if non-nil, zero value otherwise.

### GetKindOk

`func (o *WebAnalyticsQueryResponseColumnsInner) GetKindOk() (*string, bool)`

GetKindOk returns a tuple with the Kind field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKind

`func (o *WebAnalyticsQueryResponseColumnsInner) SetKind(v string)`

SetKind sets Kind field to given value.

### HasKind

`func (o *WebAnalyticsQueryResponseColumnsInner) HasKind() bool`

HasKind returns a boolean if a field has been set.

### GetType

`func (o *WebAnalyticsQueryResponseColumnsInner) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *WebAnalyticsQueryResponseColumnsInner) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *WebAnalyticsQueryResponseColumnsInner) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *WebAnalyticsQueryResponseColumnsInner) HasType() bool`

HasType returns a boolean if a field has been set.

### GetLabel

`func (o *WebAnalyticsQueryResponseColumnsInner) GetLabel() string`

GetLabel returns the Label field if non-nil, zero value otherwise.

### GetLabelOk

`func (o *WebAnalyticsQueryResponseColumnsInner) GetLabelOk() (*string, bool)`

GetLabelOk returns a tuple with the Label field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabel

`func (o *WebAnalyticsQueryResponseColumnsInner) SetLabel(v string)`

SetLabel sets Label field to given value.

### HasLabel

`func (o *WebAnalyticsQueryResponseColumnsInner) HasLabel() bool`

HasLabel returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


