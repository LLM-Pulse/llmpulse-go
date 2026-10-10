# QueryWebAnalyticsRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ProjectId** | **int32** |  | 
**Query** | **interface{}** | The query in the provider&#39;s native format (see GET /web_analytics/schema): a JSON object for GA4, Adobe, Matomo, Plausible and Piano; for PostHog, {\&quot;query\&quot;: \&quot;&lt;HogQL&gt;\&quot;} or the HogQL string. Deliberately untyped so generated clients accept either shape. | 

## Methods

### NewQueryWebAnalyticsRequest

`func NewQueryWebAnalyticsRequest(projectId int32, query interface{}, ) *QueryWebAnalyticsRequest`

NewQueryWebAnalyticsRequest instantiates a new QueryWebAnalyticsRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewQueryWebAnalyticsRequestWithDefaults

`func NewQueryWebAnalyticsRequestWithDefaults() *QueryWebAnalyticsRequest`

NewQueryWebAnalyticsRequestWithDefaults instantiates a new QueryWebAnalyticsRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProjectId

`func (o *QueryWebAnalyticsRequest) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *QueryWebAnalyticsRequest) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *QueryWebAnalyticsRequest) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.


### GetQuery

`func (o *QueryWebAnalyticsRequest) GetQuery() interface{}`

GetQuery returns the Query field if non-nil, zero value otherwise.

### GetQueryOk

`func (o *QueryWebAnalyticsRequest) GetQueryOk() (*interface{}, bool)`

GetQueryOk returns a tuple with the Query field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuery

`func (o *QueryWebAnalyticsRequest) SetQuery(v interface{})`

SetQuery sets Query field to given value.


### SetQueryNil

`func (o *QueryWebAnalyticsRequest) SetQueryNil(b bool)`

 SetQueryNil sets the value for Query to be an explicit nil

### UnsetQuery
`func (o *QueryWebAnalyticsRequest) UnsetQuery()`

UnsetQuery ensures that no value is present for Query, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


