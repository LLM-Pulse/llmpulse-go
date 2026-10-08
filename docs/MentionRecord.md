# MentionRecord

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **int32** |  | 
**Name** | **string** | The project&#39;s brand name (its name when no brand name is set) | 
**PromptId** | **int32** |  | 
**PromptExecutionId** | **int32** |  | 
**CreatedAt** | **time.Time** |  | 

## Methods

### NewMentionRecord

`func NewMentionRecord(id int32, name string, promptId int32, promptExecutionId int32, createdAt time.Time, ) *MentionRecord`

NewMentionRecord instantiates a new MentionRecord object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewMentionRecordWithDefaults

`func NewMentionRecordWithDefaults() *MentionRecord`

NewMentionRecordWithDefaults instantiates a new MentionRecord object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *MentionRecord) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *MentionRecord) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *MentionRecord) SetId(v int32)`

SetId sets Id field to given value.


### GetName

`func (o *MentionRecord) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *MentionRecord) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *MentionRecord) SetName(v string)`

SetName sets Name field to given value.


### GetPromptId

`func (o *MentionRecord) GetPromptId() int32`

GetPromptId returns the PromptId field if non-nil, zero value otherwise.

### GetPromptIdOk

`func (o *MentionRecord) GetPromptIdOk() (*int32, bool)`

GetPromptIdOk returns a tuple with the PromptId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPromptId

`func (o *MentionRecord) SetPromptId(v int32)`

SetPromptId sets PromptId field to given value.


### GetPromptExecutionId

`func (o *MentionRecord) GetPromptExecutionId() int32`

GetPromptExecutionId returns the PromptExecutionId field if non-nil, zero value otherwise.

### GetPromptExecutionIdOk

`func (o *MentionRecord) GetPromptExecutionIdOk() (*int32, bool)`

GetPromptExecutionIdOk returns a tuple with the PromptExecutionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPromptExecutionId

`func (o *MentionRecord) SetPromptExecutionId(v int32)`

SetPromptExecutionId sets PromptExecutionId field to given value.


### GetCreatedAt

`func (o *MentionRecord) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *MentionRecord) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *MentionRecord) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


