# GeoAlert

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **int32** |  | [optional] 
**AuditId** | Pointer to **string** |  | [optional] 
**AuditType** | Pointer to **string** |  | [optional] 
**Target** | Pointer to **string** |  | [optional] 
**RunSequence** | Pointer to **int32** |  | [optional] 
**Severity** | Pointer to **string** |  | [optional] 
**Events** | Pointer to [**[]GeoAlertEventsInner**](GeoAlertEventsInner.md) |  | [optional] 
**CreatedAt** | Pointer to **time.Time** |  | [optional] 
**AppUrl** | Pointer to **string** |  | [optional] 

## Methods

### NewGeoAlert

`func NewGeoAlert() *GeoAlert`

NewGeoAlert instantiates a new GeoAlert object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGeoAlertWithDefaults

`func NewGeoAlertWithDefaults() *GeoAlert`

NewGeoAlertWithDefaults instantiates a new GeoAlert object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *GeoAlert) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *GeoAlert) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *GeoAlert) SetId(v int32)`

SetId sets Id field to given value.

### HasId

`func (o *GeoAlert) HasId() bool`

HasId returns a boolean if a field has been set.

### GetAuditId

`func (o *GeoAlert) GetAuditId() string`

GetAuditId returns the AuditId field if non-nil, zero value otherwise.

### GetAuditIdOk

`func (o *GeoAlert) GetAuditIdOk() (*string, bool)`

GetAuditIdOk returns a tuple with the AuditId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAuditId

`func (o *GeoAlert) SetAuditId(v string)`

SetAuditId sets AuditId field to given value.

### HasAuditId

`func (o *GeoAlert) HasAuditId() bool`

HasAuditId returns a boolean if a field has been set.

### GetAuditType

`func (o *GeoAlert) GetAuditType() string`

GetAuditType returns the AuditType field if non-nil, zero value otherwise.

### GetAuditTypeOk

`func (o *GeoAlert) GetAuditTypeOk() (*string, bool)`

GetAuditTypeOk returns a tuple with the AuditType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAuditType

`func (o *GeoAlert) SetAuditType(v string)`

SetAuditType sets AuditType field to given value.

### HasAuditType

`func (o *GeoAlert) HasAuditType() bool`

HasAuditType returns a boolean if a field has been set.

### GetTarget

`func (o *GeoAlert) GetTarget() string`

GetTarget returns the Target field if non-nil, zero value otherwise.

### GetTargetOk

`func (o *GeoAlert) GetTargetOk() (*string, bool)`

GetTargetOk returns a tuple with the Target field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTarget

`func (o *GeoAlert) SetTarget(v string)`

SetTarget sets Target field to given value.

### HasTarget

`func (o *GeoAlert) HasTarget() bool`

HasTarget returns a boolean if a field has been set.

### GetRunSequence

`func (o *GeoAlert) GetRunSequence() int32`

GetRunSequence returns the RunSequence field if non-nil, zero value otherwise.

### GetRunSequenceOk

`func (o *GeoAlert) GetRunSequenceOk() (*int32, bool)`

GetRunSequenceOk returns a tuple with the RunSequence field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRunSequence

`func (o *GeoAlert) SetRunSequence(v int32)`

SetRunSequence sets RunSequence field to given value.

### HasRunSequence

`func (o *GeoAlert) HasRunSequence() bool`

HasRunSequence returns a boolean if a field has been set.

### GetSeverity

`func (o *GeoAlert) GetSeverity() string`

GetSeverity returns the Severity field if non-nil, zero value otherwise.

### GetSeverityOk

`func (o *GeoAlert) GetSeverityOk() (*string, bool)`

GetSeverityOk returns a tuple with the Severity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSeverity

`func (o *GeoAlert) SetSeverity(v string)`

SetSeverity sets Severity field to given value.

### HasSeverity

`func (o *GeoAlert) HasSeverity() bool`

HasSeverity returns a boolean if a field has been set.

### GetEvents

`func (o *GeoAlert) GetEvents() []GeoAlertEventsInner`

GetEvents returns the Events field if non-nil, zero value otherwise.

### GetEventsOk

`func (o *GeoAlert) GetEventsOk() (*[]GeoAlertEventsInner, bool)`

GetEventsOk returns a tuple with the Events field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEvents

`func (o *GeoAlert) SetEvents(v []GeoAlertEventsInner)`

SetEvents sets Events field to given value.

### HasEvents

`func (o *GeoAlert) HasEvents() bool`

HasEvents returns a boolean if a field has been set.

### GetCreatedAt

`func (o *GeoAlert) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *GeoAlert) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *GeoAlert) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *GeoAlert) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetAppUrl

`func (o *GeoAlert) GetAppUrl() string`

GetAppUrl returns the AppUrl field if non-nil, zero value otherwise.

### GetAppUrlOk

`func (o *GeoAlert) GetAppUrlOk() (*string, bool)`

GetAppUrlOk returns a tuple with the AppUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAppUrl

`func (o *GeoAlert) SetAppUrl(v string)`

SetAppUrl sets AppUrl field to given value.

### HasAppUrl

`func (o *GeoAlert) HasAppUrl() bool`

HasAppUrl returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


