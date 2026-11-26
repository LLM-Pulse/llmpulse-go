# AiModelPositionDistributionBrandBucketsInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Key** | **string** |  | 
**Label** | **string** |  | 
**Color** | **string** | Hex color the app charts the bucket with | 
**Total** | **int32** | Mentions in the bucket over the window | 
**Data** | [**[]AiModelPositionDistributionBrandBucketsInnerDataInner**](AiModelPositionDistributionBrandBucketsInnerDataInner.md) | One point per period of the window, oldest first, 0 included | 

## Methods

### NewAiModelPositionDistributionBrandBucketsInner

`func NewAiModelPositionDistributionBrandBucketsInner(key string, label string, color string, total int32, data []AiModelPositionDistributionBrandBucketsInnerDataInner, ) *AiModelPositionDistributionBrandBucketsInner`

NewAiModelPositionDistributionBrandBucketsInner instantiates a new AiModelPositionDistributionBrandBucketsInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAiModelPositionDistributionBrandBucketsInnerWithDefaults

`func NewAiModelPositionDistributionBrandBucketsInnerWithDefaults() *AiModelPositionDistributionBrandBucketsInner`

NewAiModelPositionDistributionBrandBucketsInnerWithDefaults instantiates a new AiModelPositionDistributionBrandBucketsInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetKey

`func (o *AiModelPositionDistributionBrandBucketsInner) GetKey() string`

GetKey returns the Key field if non-nil, zero value otherwise.

### GetKeyOk

`func (o *AiModelPositionDistributionBrandBucketsInner) GetKeyOk() (*string, bool)`

GetKeyOk returns a tuple with the Key field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKey

`func (o *AiModelPositionDistributionBrandBucketsInner) SetKey(v string)`

SetKey sets Key field to given value.


### GetLabel

`func (o *AiModelPositionDistributionBrandBucketsInner) GetLabel() string`

GetLabel returns the Label field if non-nil, zero value otherwise.

### GetLabelOk

`func (o *AiModelPositionDistributionBrandBucketsInner) GetLabelOk() (*string, bool)`

GetLabelOk returns a tuple with the Label field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabel

`func (o *AiModelPositionDistributionBrandBucketsInner) SetLabel(v string)`

SetLabel sets Label field to given value.


### GetColor

`func (o *AiModelPositionDistributionBrandBucketsInner) GetColor() string`

GetColor returns the Color field if non-nil, zero value otherwise.

### GetColorOk

`func (o *AiModelPositionDistributionBrandBucketsInner) GetColorOk() (*string, bool)`

GetColorOk returns a tuple with the Color field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetColor

`func (o *AiModelPositionDistributionBrandBucketsInner) SetColor(v string)`

SetColor sets Color field to given value.


### GetTotal

`func (o *AiModelPositionDistributionBrandBucketsInner) GetTotal() int32`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *AiModelPositionDistributionBrandBucketsInner) GetTotalOk() (*int32, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *AiModelPositionDistributionBrandBucketsInner) SetTotal(v int32)`

SetTotal sets Total field to given value.


### GetData

`func (o *AiModelPositionDistributionBrandBucketsInner) GetData() []AiModelPositionDistributionBrandBucketsInnerDataInner`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *AiModelPositionDistributionBrandBucketsInner) GetDataOk() (*[]AiModelPositionDistributionBrandBucketsInnerDataInner, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *AiModelPositionDistributionBrandBucketsInner) SetData(v []AiModelPositionDistributionBrandBucketsInnerDataInner)`

SetData sets Data field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


