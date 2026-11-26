# ProjectDraftRecord

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DraftId** | **string** | Draft id (draft_...) | 
**Status** | **string** | open, finalized or expired | 
**CurrentStep** | **string** | The next step to submit (details, prompts, competitors, owned_media), or ready when the draft can be finalized | 
**StepsCompleted** | **[]string** |  | 
**StepsRemaining** | **[]string** | Required steps not submitted yet | 
**OptionalSteps** | **[]string** | Steps the plan allows but finalize does not require (owned_media from Growth) | 
**Finalizable** | **bool** |  | 
**WebsiteUrl** | **string** |  | 
**MainCountry** | **string** |  | 
**MainLanguage** | **string** |  | 
**UseSubdomain** | **bool** |  | 
**Name** | **NullableString** | Null until the details step | 
**BrandName** | **NullableString** |  | 
**Description** | **NullableString** |  | 
**Industry** | **[]string** |  | 
**MatchingNames** | **[]string** |  | 
**Prompts** | **[]string** |  | 
**Competitors** | [**[]ProjectDraftRecordCompetitorsInner**](ProjectDraftRecordCompetitorsInner.md) |  | 
**OwnedMedia** | [**ProjectDraftRecordOwnedMedia**](ProjectDraftRecordOwnedMedia.md) |  | 
**WeeklyEmailSubscribed** | **bool** |  | 
**ExternalIdentifier** | **NullableString** |  | 
**ExecutePromptsImmediately** | **bool** |  | 
**ProjectId** | **NullableInt32** | The project the draft became; null until finalized | 
**ExpiresAt** | **time.Time** |  | 
**CreatedAt** | **time.Time** |  | 

## Methods

### NewProjectDraftRecord

`func NewProjectDraftRecord(draftId string, status string, currentStep string, stepsCompleted []string, stepsRemaining []string, optionalSteps []string, finalizable bool, websiteUrl string, mainCountry string, mainLanguage string, useSubdomain bool, name NullableString, brandName NullableString, description NullableString, industry []string, matchingNames []string, prompts []string, competitors []ProjectDraftRecordCompetitorsInner, ownedMedia ProjectDraftRecordOwnedMedia, weeklyEmailSubscribed bool, externalIdentifier NullableString, executePromptsImmediately bool, projectId NullableInt32, expiresAt time.Time, createdAt time.Time, ) *ProjectDraftRecord`

NewProjectDraftRecord instantiates a new ProjectDraftRecord object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProjectDraftRecordWithDefaults

`func NewProjectDraftRecordWithDefaults() *ProjectDraftRecord`

NewProjectDraftRecordWithDefaults instantiates a new ProjectDraftRecord object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDraftId

`func (o *ProjectDraftRecord) GetDraftId() string`

GetDraftId returns the DraftId field if non-nil, zero value otherwise.

### GetDraftIdOk

`func (o *ProjectDraftRecord) GetDraftIdOk() (*string, bool)`

GetDraftIdOk returns a tuple with the DraftId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDraftId

`func (o *ProjectDraftRecord) SetDraftId(v string)`

SetDraftId sets DraftId field to given value.


### GetStatus

`func (o *ProjectDraftRecord) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *ProjectDraftRecord) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *ProjectDraftRecord) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetCurrentStep

`func (o *ProjectDraftRecord) GetCurrentStep() string`

GetCurrentStep returns the CurrentStep field if non-nil, zero value otherwise.

### GetCurrentStepOk

`func (o *ProjectDraftRecord) GetCurrentStepOk() (*string, bool)`

GetCurrentStepOk returns a tuple with the CurrentStep field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrentStep

`func (o *ProjectDraftRecord) SetCurrentStep(v string)`

SetCurrentStep sets CurrentStep field to given value.


### GetStepsCompleted

`func (o *ProjectDraftRecord) GetStepsCompleted() []string`

GetStepsCompleted returns the StepsCompleted field if non-nil, zero value otherwise.

### GetStepsCompletedOk

`func (o *ProjectDraftRecord) GetStepsCompletedOk() (*[]string, bool)`

GetStepsCompletedOk returns a tuple with the StepsCompleted field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStepsCompleted

`func (o *ProjectDraftRecord) SetStepsCompleted(v []string)`

SetStepsCompleted sets StepsCompleted field to given value.


### GetStepsRemaining

`func (o *ProjectDraftRecord) GetStepsRemaining() []string`

GetStepsRemaining returns the StepsRemaining field if non-nil, zero value otherwise.

### GetStepsRemainingOk

`func (o *ProjectDraftRecord) GetStepsRemainingOk() (*[]string, bool)`

GetStepsRemainingOk returns a tuple with the StepsRemaining field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStepsRemaining

`func (o *ProjectDraftRecord) SetStepsRemaining(v []string)`

SetStepsRemaining sets StepsRemaining field to given value.


### GetOptionalSteps

`func (o *ProjectDraftRecord) GetOptionalSteps() []string`

GetOptionalSteps returns the OptionalSteps field if non-nil, zero value otherwise.

### GetOptionalStepsOk

`func (o *ProjectDraftRecord) GetOptionalStepsOk() (*[]string, bool)`

GetOptionalStepsOk returns a tuple with the OptionalSteps field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOptionalSteps

`func (o *ProjectDraftRecord) SetOptionalSteps(v []string)`

SetOptionalSteps sets OptionalSteps field to given value.


### GetFinalizable

`func (o *ProjectDraftRecord) GetFinalizable() bool`

GetFinalizable returns the Finalizable field if non-nil, zero value otherwise.

### GetFinalizableOk

`func (o *ProjectDraftRecord) GetFinalizableOk() (*bool, bool)`

GetFinalizableOk returns a tuple with the Finalizable field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFinalizable

`func (o *ProjectDraftRecord) SetFinalizable(v bool)`

SetFinalizable sets Finalizable field to given value.


### GetWebsiteUrl

`func (o *ProjectDraftRecord) GetWebsiteUrl() string`

GetWebsiteUrl returns the WebsiteUrl field if non-nil, zero value otherwise.

### GetWebsiteUrlOk

`func (o *ProjectDraftRecord) GetWebsiteUrlOk() (*string, bool)`

GetWebsiteUrlOk returns a tuple with the WebsiteUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWebsiteUrl

`func (o *ProjectDraftRecord) SetWebsiteUrl(v string)`

SetWebsiteUrl sets WebsiteUrl field to given value.


### GetMainCountry

`func (o *ProjectDraftRecord) GetMainCountry() string`

GetMainCountry returns the MainCountry field if non-nil, zero value otherwise.

### GetMainCountryOk

`func (o *ProjectDraftRecord) GetMainCountryOk() (*string, bool)`

GetMainCountryOk returns a tuple with the MainCountry field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMainCountry

`func (o *ProjectDraftRecord) SetMainCountry(v string)`

SetMainCountry sets MainCountry field to given value.


### GetMainLanguage

`func (o *ProjectDraftRecord) GetMainLanguage() string`

GetMainLanguage returns the MainLanguage field if non-nil, zero value otherwise.

### GetMainLanguageOk

`func (o *ProjectDraftRecord) GetMainLanguageOk() (*string, bool)`

GetMainLanguageOk returns a tuple with the MainLanguage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMainLanguage

`func (o *ProjectDraftRecord) SetMainLanguage(v string)`

SetMainLanguage sets MainLanguage field to given value.


### GetUseSubdomain

`func (o *ProjectDraftRecord) GetUseSubdomain() bool`

GetUseSubdomain returns the UseSubdomain field if non-nil, zero value otherwise.

### GetUseSubdomainOk

`func (o *ProjectDraftRecord) GetUseSubdomainOk() (*bool, bool)`

GetUseSubdomainOk returns a tuple with the UseSubdomain field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUseSubdomain

`func (o *ProjectDraftRecord) SetUseSubdomain(v bool)`

SetUseSubdomain sets UseSubdomain field to given value.


### GetName

`func (o *ProjectDraftRecord) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ProjectDraftRecord) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ProjectDraftRecord) SetName(v string)`

SetName sets Name field to given value.


### SetNameNil

`func (o *ProjectDraftRecord) SetNameNil(b bool)`

 SetNameNil sets the value for Name to be an explicit nil

### UnsetName
`func (o *ProjectDraftRecord) UnsetName()`

UnsetName ensures that no value is present for Name, not even an explicit nil
### GetBrandName

`func (o *ProjectDraftRecord) GetBrandName() string`

GetBrandName returns the BrandName field if non-nil, zero value otherwise.

### GetBrandNameOk

`func (o *ProjectDraftRecord) GetBrandNameOk() (*string, bool)`

GetBrandNameOk returns a tuple with the BrandName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBrandName

`func (o *ProjectDraftRecord) SetBrandName(v string)`

SetBrandName sets BrandName field to given value.


### SetBrandNameNil

`func (o *ProjectDraftRecord) SetBrandNameNil(b bool)`

 SetBrandNameNil sets the value for BrandName to be an explicit nil

### UnsetBrandName
`func (o *ProjectDraftRecord) UnsetBrandName()`

UnsetBrandName ensures that no value is present for BrandName, not even an explicit nil
### GetDescription

`func (o *ProjectDraftRecord) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *ProjectDraftRecord) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *ProjectDraftRecord) SetDescription(v string)`

SetDescription sets Description field to given value.


### SetDescriptionNil

`func (o *ProjectDraftRecord) SetDescriptionNil(b bool)`

 SetDescriptionNil sets the value for Description to be an explicit nil

### UnsetDescription
`func (o *ProjectDraftRecord) UnsetDescription()`

UnsetDescription ensures that no value is present for Description, not even an explicit nil
### GetIndustry

`func (o *ProjectDraftRecord) GetIndustry() []string`

GetIndustry returns the Industry field if non-nil, zero value otherwise.

### GetIndustryOk

`func (o *ProjectDraftRecord) GetIndustryOk() (*[]string, bool)`

GetIndustryOk returns a tuple with the Industry field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIndustry

`func (o *ProjectDraftRecord) SetIndustry(v []string)`

SetIndustry sets Industry field to given value.


### GetMatchingNames

`func (o *ProjectDraftRecord) GetMatchingNames() []string`

GetMatchingNames returns the MatchingNames field if non-nil, zero value otherwise.

### GetMatchingNamesOk

`func (o *ProjectDraftRecord) GetMatchingNamesOk() (*[]string, bool)`

GetMatchingNamesOk returns a tuple with the MatchingNames field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMatchingNames

`func (o *ProjectDraftRecord) SetMatchingNames(v []string)`

SetMatchingNames sets MatchingNames field to given value.


### GetPrompts

`func (o *ProjectDraftRecord) GetPrompts() []string`

GetPrompts returns the Prompts field if non-nil, zero value otherwise.

### GetPromptsOk

`func (o *ProjectDraftRecord) GetPromptsOk() (*[]string, bool)`

GetPromptsOk returns a tuple with the Prompts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrompts

`func (o *ProjectDraftRecord) SetPrompts(v []string)`

SetPrompts sets Prompts field to given value.


### GetCompetitors

`func (o *ProjectDraftRecord) GetCompetitors() []ProjectDraftRecordCompetitorsInner`

GetCompetitors returns the Competitors field if non-nil, zero value otherwise.

### GetCompetitorsOk

`func (o *ProjectDraftRecord) GetCompetitorsOk() (*[]ProjectDraftRecordCompetitorsInner, bool)`

GetCompetitorsOk returns a tuple with the Competitors field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompetitors

`func (o *ProjectDraftRecord) SetCompetitors(v []ProjectDraftRecordCompetitorsInner)`

SetCompetitors sets Competitors field to given value.


### GetOwnedMedia

`func (o *ProjectDraftRecord) GetOwnedMedia() ProjectDraftRecordOwnedMedia`

GetOwnedMedia returns the OwnedMedia field if non-nil, zero value otherwise.

### GetOwnedMediaOk

`func (o *ProjectDraftRecord) GetOwnedMediaOk() (*ProjectDraftRecordOwnedMedia, bool)`

GetOwnedMediaOk returns a tuple with the OwnedMedia field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOwnedMedia

`func (o *ProjectDraftRecord) SetOwnedMedia(v ProjectDraftRecordOwnedMedia)`

SetOwnedMedia sets OwnedMedia field to given value.


### GetWeeklyEmailSubscribed

`func (o *ProjectDraftRecord) GetWeeklyEmailSubscribed() bool`

GetWeeklyEmailSubscribed returns the WeeklyEmailSubscribed field if non-nil, zero value otherwise.

### GetWeeklyEmailSubscribedOk

`func (o *ProjectDraftRecord) GetWeeklyEmailSubscribedOk() (*bool, bool)`

GetWeeklyEmailSubscribedOk returns a tuple with the WeeklyEmailSubscribed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWeeklyEmailSubscribed

`func (o *ProjectDraftRecord) SetWeeklyEmailSubscribed(v bool)`

SetWeeklyEmailSubscribed sets WeeklyEmailSubscribed field to given value.


### GetExternalIdentifier

`func (o *ProjectDraftRecord) GetExternalIdentifier() string`

GetExternalIdentifier returns the ExternalIdentifier field if non-nil, zero value otherwise.

### GetExternalIdentifierOk

`func (o *ProjectDraftRecord) GetExternalIdentifierOk() (*string, bool)`

GetExternalIdentifierOk returns a tuple with the ExternalIdentifier field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExternalIdentifier

`func (o *ProjectDraftRecord) SetExternalIdentifier(v string)`

SetExternalIdentifier sets ExternalIdentifier field to given value.


### SetExternalIdentifierNil

`func (o *ProjectDraftRecord) SetExternalIdentifierNil(b bool)`

 SetExternalIdentifierNil sets the value for ExternalIdentifier to be an explicit nil

### UnsetExternalIdentifier
`func (o *ProjectDraftRecord) UnsetExternalIdentifier()`

UnsetExternalIdentifier ensures that no value is present for ExternalIdentifier, not even an explicit nil
### GetExecutePromptsImmediately

`func (o *ProjectDraftRecord) GetExecutePromptsImmediately() bool`

GetExecutePromptsImmediately returns the ExecutePromptsImmediately field if non-nil, zero value otherwise.

### GetExecutePromptsImmediatelyOk

`func (o *ProjectDraftRecord) GetExecutePromptsImmediatelyOk() (*bool, bool)`

GetExecutePromptsImmediatelyOk returns a tuple with the ExecutePromptsImmediately field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExecutePromptsImmediately

`func (o *ProjectDraftRecord) SetExecutePromptsImmediately(v bool)`

SetExecutePromptsImmediately sets ExecutePromptsImmediately field to given value.


### GetProjectId

`func (o *ProjectDraftRecord) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *ProjectDraftRecord) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *ProjectDraftRecord) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.


### SetProjectIdNil

`func (o *ProjectDraftRecord) SetProjectIdNil(b bool)`

 SetProjectIdNil sets the value for ProjectId to be an explicit nil

### UnsetProjectId
`func (o *ProjectDraftRecord) UnsetProjectId()`

UnsetProjectId ensures that no value is present for ProjectId, not even an explicit nil
### GetExpiresAt

`func (o *ProjectDraftRecord) GetExpiresAt() time.Time`

GetExpiresAt returns the ExpiresAt field if non-nil, zero value otherwise.

### GetExpiresAtOk

`func (o *ProjectDraftRecord) GetExpiresAtOk() (*time.Time, bool)`

GetExpiresAtOk returns a tuple with the ExpiresAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpiresAt

`func (o *ProjectDraftRecord) SetExpiresAt(v time.Time)`

SetExpiresAt sets ExpiresAt field to given value.


### GetCreatedAt

`func (o *ProjectDraftRecord) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *ProjectDraftRecord) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *ProjectDraftRecord) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


