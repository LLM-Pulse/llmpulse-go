# ProjectDetailsAllOfPitchRun

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Status** | Pointer to **string** | starting before the run begins, running while answers arrive, ready once every AI model has answered or stopped trying | [optional] 
**LaunchedAt** | Pointer to **NullableTime** |  | [optional] 
**SettledAt** | Pointer to **NullableTime** |  | [optional] 
**Models** | Pointer to **[]string** | The AI models the run asks, fixed when it starts | [optional] 
**AnswersExpected** | Pointer to **int32** |  | [optional] 
**AnswersReceived** | Pointer to **int32** |  | [optional] 

## Methods

### NewProjectDetailsAllOfPitchRun

`func NewProjectDetailsAllOfPitchRun() *ProjectDetailsAllOfPitchRun`

NewProjectDetailsAllOfPitchRun instantiates a new ProjectDetailsAllOfPitchRun object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProjectDetailsAllOfPitchRunWithDefaults

`func NewProjectDetailsAllOfPitchRunWithDefaults() *ProjectDetailsAllOfPitchRun`

NewProjectDetailsAllOfPitchRunWithDefaults instantiates a new ProjectDetailsAllOfPitchRun object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetStatus

`func (o *ProjectDetailsAllOfPitchRun) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *ProjectDetailsAllOfPitchRun) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *ProjectDetailsAllOfPitchRun) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *ProjectDetailsAllOfPitchRun) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetLaunchedAt

`func (o *ProjectDetailsAllOfPitchRun) GetLaunchedAt() time.Time`

GetLaunchedAt returns the LaunchedAt field if non-nil, zero value otherwise.

### GetLaunchedAtOk

`func (o *ProjectDetailsAllOfPitchRun) GetLaunchedAtOk() (*time.Time, bool)`

GetLaunchedAtOk returns a tuple with the LaunchedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLaunchedAt

`func (o *ProjectDetailsAllOfPitchRun) SetLaunchedAt(v time.Time)`

SetLaunchedAt sets LaunchedAt field to given value.

### HasLaunchedAt

`func (o *ProjectDetailsAllOfPitchRun) HasLaunchedAt() bool`

HasLaunchedAt returns a boolean if a field has been set.

### SetLaunchedAtNil

`func (o *ProjectDetailsAllOfPitchRun) SetLaunchedAtNil(b bool)`

 SetLaunchedAtNil sets the value for LaunchedAt to be an explicit nil

### UnsetLaunchedAt
`func (o *ProjectDetailsAllOfPitchRun) UnsetLaunchedAt()`

UnsetLaunchedAt ensures that no value is present for LaunchedAt, not even an explicit nil
### GetSettledAt

`func (o *ProjectDetailsAllOfPitchRun) GetSettledAt() time.Time`

GetSettledAt returns the SettledAt field if non-nil, zero value otherwise.

### GetSettledAtOk

`func (o *ProjectDetailsAllOfPitchRun) GetSettledAtOk() (*time.Time, bool)`

GetSettledAtOk returns a tuple with the SettledAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSettledAt

`func (o *ProjectDetailsAllOfPitchRun) SetSettledAt(v time.Time)`

SetSettledAt sets SettledAt field to given value.

### HasSettledAt

`func (o *ProjectDetailsAllOfPitchRun) HasSettledAt() bool`

HasSettledAt returns a boolean if a field has been set.

### SetSettledAtNil

`func (o *ProjectDetailsAllOfPitchRun) SetSettledAtNil(b bool)`

 SetSettledAtNil sets the value for SettledAt to be an explicit nil

### UnsetSettledAt
`func (o *ProjectDetailsAllOfPitchRun) UnsetSettledAt()`

UnsetSettledAt ensures that no value is present for SettledAt, not even an explicit nil
### GetModels

`func (o *ProjectDetailsAllOfPitchRun) GetModels() []string`

GetModels returns the Models field if non-nil, zero value otherwise.

### GetModelsOk

`func (o *ProjectDetailsAllOfPitchRun) GetModelsOk() (*[]string, bool)`

GetModelsOk returns a tuple with the Models field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModels

`func (o *ProjectDetailsAllOfPitchRun) SetModels(v []string)`

SetModels sets Models field to given value.

### HasModels

`func (o *ProjectDetailsAllOfPitchRun) HasModels() bool`

HasModels returns a boolean if a field has been set.

### GetAnswersExpected

`func (o *ProjectDetailsAllOfPitchRun) GetAnswersExpected() int32`

GetAnswersExpected returns the AnswersExpected field if non-nil, zero value otherwise.

### GetAnswersExpectedOk

`func (o *ProjectDetailsAllOfPitchRun) GetAnswersExpectedOk() (*int32, bool)`

GetAnswersExpectedOk returns a tuple with the AnswersExpected field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAnswersExpected

`func (o *ProjectDetailsAllOfPitchRun) SetAnswersExpected(v int32)`

SetAnswersExpected sets AnswersExpected field to given value.

### HasAnswersExpected

`func (o *ProjectDetailsAllOfPitchRun) HasAnswersExpected() bool`

HasAnswersExpected returns a boolean if a field has been set.

### GetAnswersReceived

`func (o *ProjectDetailsAllOfPitchRun) GetAnswersReceived() int32`

GetAnswersReceived returns the AnswersReceived field if non-nil, zero value otherwise.

### GetAnswersReceivedOk

`func (o *ProjectDetailsAllOfPitchRun) GetAnswersReceivedOk() (*int32, bool)`

GetAnswersReceivedOk returns a tuple with the AnswersReceived field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAnswersReceived

`func (o *ProjectDetailsAllOfPitchRun) SetAnswersReceived(v int32)`

SetAnswersReceived sets AnswersReceived field to given value.

### HasAnswersReceived

`func (o *ProjectDetailsAllOfPitchRun) HasAnswersReceived() bool`

HasAnswersReceived returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


