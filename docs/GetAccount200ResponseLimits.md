# GetAccount200ResponseLimits

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Prompts** | Pointer to [**AccountQuota**](AccountQuota.md) |  | [optional] 
**Projects** | Pointer to [**AccountQuota**](AccountQuota.md) |  | [optional] 
**CompetitorsPerProject** | Pointer to [**AccountCapacity**](AccountCapacity.md) |  | [optional] 
**IntelligenceTasks** | Pointer to [**AccountQuota**](AccountQuota.md) |  | [optional] 
**TeamMembers** | Pointer to [**AccountCapacity**](AccountCapacity.md) |  | [optional] 
**RecurringGeoAudits** | Pointer to [**AccountQuota**](AccountQuota.md) |  | [optional] 
**GeoAuditManualRuns** | Pointer to [**AccountQuota**](AccountQuota.md) |  | [optional] 

## Methods

### NewGetAccount200ResponseLimits

`func NewGetAccount200ResponseLimits() *GetAccount200ResponseLimits`

NewGetAccount200ResponseLimits instantiates a new GetAccount200ResponseLimits object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGetAccount200ResponseLimitsWithDefaults

`func NewGetAccount200ResponseLimitsWithDefaults() *GetAccount200ResponseLimits`

NewGetAccount200ResponseLimitsWithDefaults instantiates a new GetAccount200ResponseLimits object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPrompts

`func (o *GetAccount200ResponseLimits) GetPrompts() AccountQuota`

GetPrompts returns the Prompts field if non-nil, zero value otherwise.

### GetPromptsOk

`func (o *GetAccount200ResponseLimits) GetPromptsOk() (*AccountQuota, bool)`

GetPromptsOk returns a tuple with the Prompts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrompts

`func (o *GetAccount200ResponseLimits) SetPrompts(v AccountQuota)`

SetPrompts sets Prompts field to given value.

### HasPrompts

`func (o *GetAccount200ResponseLimits) HasPrompts() bool`

HasPrompts returns a boolean if a field has been set.

### GetProjects

`func (o *GetAccount200ResponseLimits) GetProjects() AccountQuota`

GetProjects returns the Projects field if non-nil, zero value otherwise.

### GetProjectsOk

`func (o *GetAccount200ResponseLimits) GetProjectsOk() (*AccountQuota, bool)`

GetProjectsOk returns a tuple with the Projects field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjects

`func (o *GetAccount200ResponseLimits) SetProjects(v AccountQuota)`

SetProjects sets Projects field to given value.

### HasProjects

`func (o *GetAccount200ResponseLimits) HasProjects() bool`

HasProjects returns a boolean if a field has been set.

### GetCompetitorsPerProject

`func (o *GetAccount200ResponseLimits) GetCompetitorsPerProject() AccountCapacity`

GetCompetitorsPerProject returns the CompetitorsPerProject field if non-nil, zero value otherwise.

### GetCompetitorsPerProjectOk

`func (o *GetAccount200ResponseLimits) GetCompetitorsPerProjectOk() (*AccountCapacity, bool)`

GetCompetitorsPerProjectOk returns a tuple with the CompetitorsPerProject field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompetitorsPerProject

`func (o *GetAccount200ResponseLimits) SetCompetitorsPerProject(v AccountCapacity)`

SetCompetitorsPerProject sets CompetitorsPerProject field to given value.

### HasCompetitorsPerProject

`func (o *GetAccount200ResponseLimits) HasCompetitorsPerProject() bool`

HasCompetitorsPerProject returns a boolean if a field has been set.

### GetIntelligenceTasks

`func (o *GetAccount200ResponseLimits) GetIntelligenceTasks() AccountQuota`

GetIntelligenceTasks returns the IntelligenceTasks field if non-nil, zero value otherwise.

### GetIntelligenceTasksOk

`func (o *GetAccount200ResponseLimits) GetIntelligenceTasksOk() (*AccountQuota, bool)`

GetIntelligenceTasksOk returns a tuple with the IntelligenceTasks field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIntelligenceTasks

`func (o *GetAccount200ResponseLimits) SetIntelligenceTasks(v AccountQuota)`

SetIntelligenceTasks sets IntelligenceTasks field to given value.

### HasIntelligenceTasks

`func (o *GetAccount200ResponseLimits) HasIntelligenceTasks() bool`

HasIntelligenceTasks returns a boolean if a field has been set.

### GetTeamMembers

`func (o *GetAccount200ResponseLimits) GetTeamMembers() AccountCapacity`

GetTeamMembers returns the TeamMembers field if non-nil, zero value otherwise.

### GetTeamMembersOk

`func (o *GetAccount200ResponseLimits) GetTeamMembersOk() (*AccountCapacity, bool)`

GetTeamMembersOk returns a tuple with the TeamMembers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTeamMembers

`func (o *GetAccount200ResponseLimits) SetTeamMembers(v AccountCapacity)`

SetTeamMembers sets TeamMembers field to given value.

### HasTeamMembers

`func (o *GetAccount200ResponseLimits) HasTeamMembers() bool`

HasTeamMembers returns a boolean if a field has been set.

### GetRecurringGeoAudits

`func (o *GetAccount200ResponseLimits) GetRecurringGeoAudits() AccountQuota`

GetRecurringGeoAudits returns the RecurringGeoAudits field if non-nil, zero value otherwise.

### GetRecurringGeoAuditsOk

`func (o *GetAccount200ResponseLimits) GetRecurringGeoAuditsOk() (*AccountQuota, bool)`

GetRecurringGeoAuditsOk returns a tuple with the RecurringGeoAudits field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRecurringGeoAudits

`func (o *GetAccount200ResponseLimits) SetRecurringGeoAudits(v AccountQuota)`

SetRecurringGeoAudits sets RecurringGeoAudits field to given value.

### HasRecurringGeoAudits

`func (o *GetAccount200ResponseLimits) HasRecurringGeoAudits() bool`

HasRecurringGeoAudits returns a boolean if a field has been set.

### GetGeoAuditManualRuns

`func (o *GetAccount200ResponseLimits) GetGeoAuditManualRuns() AccountQuota`

GetGeoAuditManualRuns returns the GeoAuditManualRuns field if non-nil, zero value otherwise.

### GetGeoAuditManualRunsOk

`func (o *GetAccount200ResponseLimits) GetGeoAuditManualRunsOk() (*AccountQuota, bool)`

GetGeoAuditManualRunsOk returns a tuple with the GeoAuditManualRuns field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGeoAuditManualRuns

`func (o *GetAccount200ResponseLimits) SetGeoAuditManualRuns(v AccountQuota)`

SetGeoAuditManualRuns sets GeoAuditManualRuns field to given value.

### HasGeoAuditManualRuns

`func (o *GetAccount200ResponseLimits) HasGeoAuditManualRuns() bool`

HasGeoAuditManualRuns returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


