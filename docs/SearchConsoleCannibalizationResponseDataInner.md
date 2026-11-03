# SearchConsoleCannibalizationResponseDataInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Query** | Pointer to **string** |  | [optional] 
**Impressions** | Pointer to **int32** |  | [optional] 
**Clicks** | Pointer to **int32** |  | [optional] 
**Ctr** | Pointer to **float32** | 0..1 fraction | [optional] 
**Position** | Pointer to **float32** | Impression-weighted average position | [optional] 
**Pages** | Pointer to [**[]SearchConsoleCannibalizationResponseDataInnerPagesInner**](SearchConsoleCannibalizationResponseDataInnerPagesInner.md) | Pages taking at least min_share of the query&#39;s impressions, most impressions first | [optional] 

## Methods

### NewSearchConsoleCannibalizationResponseDataInner

`func NewSearchConsoleCannibalizationResponseDataInner() *SearchConsoleCannibalizationResponseDataInner`

NewSearchConsoleCannibalizationResponseDataInner instantiates a new SearchConsoleCannibalizationResponseDataInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSearchConsoleCannibalizationResponseDataInnerWithDefaults

`func NewSearchConsoleCannibalizationResponseDataInnerWithDefaults() *SearchConsoleCannibalizationResponseDataInner`

NewSearchConsoleCannibalizationResponseDataInnerWithDefaults instantiates a new SearchConsoleCannibalizationResponseDataInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetQuery

`func (o *SearchConsoleCannibalizationResponseDataInner) GetQuery() string`

GetQuery returns the Query field if non-nil, zero value otherwise.

### GetQueryOk

`func (o *SearchConsoleCannibalizationResponseDataInner) GetQueryOk() (*string, bool)`

GetQueryOk returns a tuple with the Query field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuery

`func (o *SearchConsoleCannibalizationResponseDataInner) SetQuery(v string)`

SetQuery sets Query field to given value.

### HasQuery

`func (o *SearchConsoleCannibalizationResponseDataInner) HasQuery() bool`

HasQuery returns a boolean if a field has been set.

### GetImpressions

`func (o *SearchConsoleCannibalizationResponseDataInner) GetImpressions() int32`

GetImpressions returns the Impressions field if non-nil, zero value otherwise.

### GetImpressionsOk

`func (o *SearchConsoleCannibalizationResponseDataInner) GetImpressionsOk() (*int32, bool)`

GetImpressionsOk returns a tuple with the Impressions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImpressions

`func (o *SearchConsoleCannibalizationResponseDataInner) SetImpressions(v int32)`

SetImpressions sets Impressions field to given value.

### HasImpressions

`func (o *SearchConsoleCannibalizationResponseDataInner) HasImpressions() bool`

HasImpressions returns a boolean if a field has been set.

### GetClicks

`func (o *SearchConsoleCannibalizationResponseDataInner) GetClicks() int32`

GetClicks returns the Clicks field if non-nil, zero value otherwise.

### GetClicksOk

`func (o *SearchConsoleCannibalizationResponseDataInner) GetClicksOk() (*int32, bool)`

GetClicksOk returns a tuple with the Clicks field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClicks

`func (o *SearchConsoleCannibalizationResponseDataInner) SetClicks(v int32)`

SetClicks sets Clicks field to given value.

### HasClicks

`func (o *SearchConsoleCannibalizationResponseDataInner) HasClicks() bool`

HasClicks returns a boolean if a field has been set.

### GetCtr

`func (o *SearchConsoleCannibalizationResponseDataInner) GetCtr() float32`

GetCtr returns the Ctr field if non-nil, zero value otherwise.

### GetCtrOk

`func (o *SearchConsoleCannibalizationResponseDataInner) GetCtrOk() (*float32, bool)`

GetCtrOk returns a tuple with the Ctr field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCtr

`func (o *SearchConsoleCannibalizationResponseDataInner) SetCtr(v float32)`

SetCtr sets Ctr field to given value.

### HasCtr

`func (o *SearchConsoleCannibalizationResponseDataInner) HasCtr() bool`

HasCtr returns a boolean if a field has been set.

### GetPosition

`func (o *SearchConsoleCannibalizationResponseDataInner) GetPosition() float32`

GetPosition returns the Position field if non-nil, zero value otherwise.

### GetPositionOk

`func (o *SearchConsoleCannibalizationResponseDataInner) GetPositionOk() (*float32, bool)`

GetPositionOk returns a tuple with the Position field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPosition

`func (o *SearchConsoleCannibalizationResponseDataInner) SetPosition(v float32)`

SetPosition sets Position field to given value.

### HasPosition

`func (o *SearchConsoleCannibalizationResponseDataInner) HasPosition() bool`

HasPosition returns a boolean if a field has been set.

### GetPages

`func (o *SearchConsoleCannibalizationResponseDataInner) GetPages() []SearchConsoleCannibalizationResponseDataInnerPagesInner`

GetPages returns the Pages field if non-nil, zero value otherwise.

### GetPagesOk

`func (o *SearchConsoleCannibalizationResponseDataInner) GetPagesOk() (*[]SearchConsoleCannibalizationResponseDataInnerPagesInner, bool)`

GetPagesOk returns a tuple with the Pages field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPages

`func (o *SearchConsoleCannibalizationResponseDataInner) SetPages(v []SearchConsoleCannibalizationResponseDataInnerPagesInner)`

SetPages sets Pages field to given value.

### HasPages

`func (o *SearchConsoleCannibalizationResponseDataInner) HasPages() bool`

HasPages returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


