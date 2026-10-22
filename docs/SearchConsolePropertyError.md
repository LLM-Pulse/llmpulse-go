# SearchConsolePropertyError

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** |  | [optional] 
**Name** | Pointer to **string** |  | [optional] 
**Code** | Pointer to **string** |  | [optional] 
**Message** | Pointer to **string** |  | [optional] 
**RetryAfter** | Pointer to **int32** | Seconds to wait before retrying, for ERR_SEARCH_CONSOLE_UPSTREAM | [optional] 

## Methods

### NewSearchConsolePropertyError

`func NewSearchConsolePropertyError() *SearchConsolePropertyError`

NewSearchConsolePropertyError instantiates a new SearchConsolePropertyError object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSearchConsolePropertyErrorWithDefaults

`func NewSearchConsolePropertyErrorWithDefaults() *SearchConsolePropertyError`

NewSearchConsolePropertyErrorWithDefaults instantiates a new SearchConsolePropertyError object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *SearchConsolePropertyError) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *SearchConsolePropertyError) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *SearchConsolePropertyError) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *SearchConsolePropertyError) HasId() bool`

HasId returns a boolean if a field has been set.

### GetName

`func (o *SearchConsolePropertyError) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *SearchConsolePropertyError) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *SearchConsolePropertyError) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *SearchConsolePropertyError) HasName() bool`

HasName returns a boolean if a field has been set.

### GetCode

`func (o *SearchConsolePropertyError) GetCode() string`

GetCode returns the Code field if non-nil, zero value otherwise.

### GetCodeOk

`func (o *SearchConsolePropertyError) GetCodeOk() (*string, bool)`

GetCodeOk returns a tuple with the Code field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCode

`func (o *SearchConsolePropertyError) SetCode(v string)`

SetCode sets Code field to given value.

### HasCode

`func (o *SearchConsolePropertyError) HasCode() bool`

HasCode returns a boolean if a field has been set.

### GetMessage

`func (o *SearchConsolePropertyError) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *SearchConsolePropertyError) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *SearchConsolePropertyError) SetMessage(v string)`

SetMessage sets Message field to given value.

### HasMessage

`func (o *SearchConsolePropertyError) HasMessage() bool`

HasMessage returns a boolean if a field has been set.

### GetRetryAfter

`func (o *SearchConsolePropertyError) GetRetryAfter() int32`

GetRetryAfter returns the RetryAfter field if non-nil, zero value otherwise.

### GetRetryAfterOk

`func (o *SearchConsolePropertyError) GetRetryAfterOk() (*int32, bool)`

GetRetryAfterOk returns a tuple with the RetryAfter field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRetryAfter

`func (o *SearchConsolePropertyError) SetRetryAfter(v int32)`

SetRetryAfter sets RetryAfter field to given value.

### HasRetryAfter

`func (o *SearchConsolePropertyError) HasRetryAfter() bool`

HasRetryAfter returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


