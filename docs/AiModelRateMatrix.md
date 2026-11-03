# AiModelRateMatrix

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DenominatorsByModel** | Pointer to **map[string]int32** | Answers of each model in the window, keyed by model | [optional] 
**Actors** | Pointer to [**[]AiModelRateMatrixActor**](AiModelRateMatrixActor.md) | The project and each competitor with a mention (or citation) in the window (only the competitors given in competitors, when it is given), by total descending | [optional] 

## Methods

### NewAiModelRateMatrix

`func NewAiModelRateMatrix() *AiModelRateMatrix`

NewAiModelRateMatrix instantiates a new AiModelRateMatrix object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAiModelRateMatrixWithDefaults

`func NewAiModelRateMatrixWithDefaults() *AiModelRateMatrix`

NewAiModelRateMatrixWithDefaults instantiates a new AiModelRateMatrix object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDenominatorsByModel

`func (o *AiModelRateMatrix) GetDenominatorsByModel() map[string]int32`

GetDenominatorsByModel returns the DenominatorsByModel field if non-nil, zero value otherwise.

### GetDenominatorsByModelOk

`func (o *AiModelRateMatrix) GetDenominatorsByModelOk() (*map[string]int32, bool)`

GetDenominatorsByModelOk returns a tuple with the DenominatorsByModel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDenominatorsByModel

`func (o *AiModelRateMatrix) SetDenominatorsByModel(v map[string]int32)`

SetDenominatorsByModel sets DenominatorsByModel field to given value.

### HasDenominatorsByModel

`func (o *AiModelRateMatrix) HasDenominatorsByModel() bool`

HasDenominatorsByModel returns a boolean if a field has been set.

### GetActors

`func (o *AiModelRateMatrix) GetActors() []AiModelRateMatrixActor`

GetActors returns the Actors field if non-nil, zero value otherwise.

### GetActorsOk

`func (o *AiModelRateMatrix) GetActorsOk() (*[]AiModelRateMatrixActor, bool)`

GetActorsOk returns a tuple with the Actors field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActors

`func (o *AiModelRateMatrix) SetActors(v []AiModelRateMatrixActor)`

SetActors sets Actors field to given value.

### HasActors

`func (o *AiModelRateMatrix) HasActors() bool`

HasActors returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


