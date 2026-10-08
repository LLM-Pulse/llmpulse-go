# GeoAuditIssueUpdateRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ProjectId** | Pointer to **int32** |  | [optional] 
**Accepted** | **bool** | true accepts the issue (it stays listed but leaves the open count until its evidence changes); false reopens it | 

## Methods

### NewGeoAuditIssueUpdateRequest

`func NewGeoAuditIssueUpdateRequest(accepted bool, ) *GeoAuditIssueUpdateRequest`

NewGeoAuditIssueUpdateRequest instantiates a new GeoAuditIssueUpdateRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGeoAuditIssueUpdateRequestWithDefaults

`func NewGeoAuditIssueUpdateRequestWithDefaults() *GeoAuditIssueUpdateRequest`

NewGeoAuditIssueUpdateRequestWithDefaults instantiates a new GeoAuditIssueUpdateRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProjectId

`func (o *GeoAuditIssueUpdateRequest) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *GeoAuditIssueUpdateRequest) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *GeoAuditIssueUpdateRequest) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.

### HasProjectId

`func (o *GeoAuditIssueUpdateRequest) HasProjectId() bool`

HasProjectId returns a boolean if a field has been set.

### GetAccepted

`func (o *GeoAuditIssueUpdateRequest) GetAccepted() bool`

GetAccepted returns the Accepted field if non-nil, zero value otherwise.

### GetAcceptedOk

`func (o *GeoAuditIssueUpdateRequest) GetAcceptedOk() (*bool, bool)`

GetAcceptedOk returns a tuple with the Accepted field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccepted

`func (o *GeoAuditIssueUpdateRequest) SetAccepted(v bool)`

SetAccepted sets Accepted field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


