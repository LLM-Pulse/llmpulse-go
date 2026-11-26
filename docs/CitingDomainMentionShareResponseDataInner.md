# CitingDomainMentionShareResponseDataInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Domain** | **string** |  | 
**ResponsesCiting** | **int32** | Answers citing the domain | 
**TotalMentions** | **int32** | Brand and competitor mentions in those answers, each answer counted once per brand | 
**Actors** | [**[]CitingDomainMentionShareResponseDataInnerActorsInner**](CitingDomainMentionShareResponseDataInnerActorsInner.md) | The brand and every competitor, most mentions first; empty when no answer cites the domain | 

## Methods

### NewCitingDomainMentionShareResponseDataInner

`func NewCitingDomainMentionShareResponseDataInner(domain string, responsesCiting int32, totalMentions int32, actors []CitingDomainMentionShareResponseDataInnerActorsInner, ) *CitingDomainMentionShareResponseDataInner`

NewCitingDomainMentionShareResponseDataInner instantiates a new CitingDomainMentionShareResponseDataInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCitingDomainMentionShareResponseDataInnerWithDefaults

`func NewCitingDomainMentionShareResponseDataInnerWithDefaults() *CitingDomainMentionShareResponseDataInner`

NewCitingDomainMentionShareResponseDataInnerWithDefaults instantiates a new CitingDomainMentionShareResponseDataInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDomain

`func (o *CitingDomainMentionShareResponseDataInner) GetDomain() string`

GetDomain returns the Domain field if non-nil, zero value otherwise.

### GetDomainOk

`func (o *CitingDomainMentionShareResponseDataInner) GetDomainOk() (*string, bool)`

GetDomainOk returns a tuple with the Domain field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDomain

`func (o *CitingDomainMentionShareResponseDataInner) SetDomain(v string)`

SetDomain sets Domain field to given value.


### GetResponsesCiting

`func (o *CitingDomainMentionShareResponseDataInner) GetResponsesCiting() int32`

GetResponsesCiting returns the ResponsesCiting field if non-nil, zero value otherwise.

### GetResponsesCitingOk

`func (o *CitingDomainMentionShareResponseDataInner) GetResponsesCitingOk() (*int32, bool)`

GetResponsesCitingOk returns a tuple with the ResponsesCiting field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResponsesCiting

`func (o *CitingDomainMentionShareResponseDataInner) SetResponsesCiting(v int32)`

SetResponsesCiting sets ResponsesCiting field to given value.


### GetTotalMentions

`func (o *CitingDomainMentionShareResponseDataInner) GetTotalMentions() int32`

GetTotalMentions returns the TotalMentions field if non-nil, zero value otherwise.

### GetTotalMentionsOk

`func (o *CitingDomainMentionShareResponseDataInner) GetTotalMentionsOk() (*int32, bool)`

GetTotalMentionsOk returns a tuple with the TotalMentions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalMentions

`func (o *CitingDomainMentionShareResponseDataInner) SetTotalMentions(v int32)`

SetTotalMentions sets TotalMentions field to given value.


### GetActors

`func (o *CitingDomainMentionShareResponseDataInner) GetActors() []CitingDomainMentionShareResponseDataInnerActorsInner`

GetActors returns the Actors field if non-nil, zero value otherwise.

### GetActorsOk

`func (o *CitingDomainMentionShareResponseDataInner) GetActorsOk() (*[]CitingDomainMentionShareResponseDataInnerActorsInner, bool)`

GetActorsOk returns a tuple with the Actors field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActors

`func (o *CitingDomainMentionShareResponseDataInner) SetActors(v []CitingDomainMentionShareResponseDataInnerActorsInner)`

SetActors sets Actors field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


