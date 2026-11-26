# CitedUrlOccurrencesResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ProjectId** | **int32** |  | 
**Page** | **int32** |  | 
**PerPage** | **int32** |  | 
**Total** | **int32** | Rows matching the filters across every page | 
**RequestId** | **string** |  | 
**UrlSha256** | **string** |  | 
**Data** | [**[]CitedUrlOccurrencesResponseAllOfData**](CitedUrlOccurrencesResponseAllOfData.md) | One row per citation of the URL, latest answer first | 

## Methods

### NewCitedUrlOccurrencesResponse

`func NewCitedUrlOccurrencesResponse(projectId int32, page int32, perPage int32, total int32, requestId string, urlSha256 string, data []CitedUrlOccurrencesResponseAllOfData, ) *CitedUrlOccurrencesResponse`

NewCitedUrlOccurrencesResponse instantiates a new CitedUrlOccurrencesResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCitedUrlOccurrencesResponseWithDefaults

`func NewCitedUrlOccurrencesResponseWithDefaults() *CitedUrlOccurrencesResponse`

NewCitedUrlOccurrencesResponseWithDefaults instantiates a new CitedUrlOccurrencesResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProjectId

`func (o *CitedUrlOccurrencesResponse) GetProjectId() int32`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *CitedUrlOccurrencesResponse) GetProjectIdOk() (*int32, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *CitedUrlOccurrencesResponse) SetProjectId(v int32)`

SetProjectId sets ProjectId field to given value.


### GetPage

`func (o *CitedUrlOccurrencesResponse) GetPage() int32`

GetPage returns the Page field if non-nil, zero value otherwise.

### GetPageOk

`func (o *CitedUrlOccurrencesResponse) GetPageOk() (*int32, bool)`

GetPageOk returns a tuple with the Page field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPage

`func (o *CitedUrlOccurrencesResponse) SetPage(v int32)`

SetPage sets Page field to given value.


### GetPerPage

`func (o *CitedUrlOccurrencesResponse) GetPerPage() int32`

GetPerPage returns the PerPage field if non-nil, zero value otherwise.

### GetPerPageOk

`func (o *CitedUrlOccurrencesResponse) GetPerPageOk() (*int32, bool)`

GetPerPageOk returns a tuple with the PerPage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPerPage

`func (o *CitedUrlOccurrencesResponse) SetPerPage(v int32)`

SetPerPage sets PerPage field to given value.


### GetTotal

`func (o *CitedUrlOccurrencesResponse) GetTotal() int32`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *CitedUrlOccurrencesResponse) GetTotalOk() (*int32, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *CitedUrlOccurrencesResponse) SetTotal(v int32)`

SetTotal sets Total field to given value.


### GetRequestId

`func (o *CitedUrlOccurrencesResponse) GetRequestId() string`

GetRequestId returns the RequestId field if non-nil, zero value otherwise.

### GetRequestIdOk

`func (o *CitedUrlOccurrencesResponse) GetRequestIdOk() (*string, bool)`

GetRequestIdOk returns a tuple with the RequestId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestId

`func (o *CitedUrlOccurrencesResponse) SetRequestId(v string)`

SetRequestId sets RequestId field to given value.


### GetUrlSha256

`func (o *CitedUrlOccurrencesResponse) GetUrlSha256() string`

GetUrlSha256 returns the UrlSha256 field if non-nil, zero value otherwise.

### GetUrlSha256Ok

`func (o *CitedUrlOccurrencesResponse) GetUrlSha256Ok() (*string, bool)`

GetUrlSha256Ok returns a tuple with the UrlSha256 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrlSha256

`func (o *CitedUrlOccurrencesResponse) SetUrlSha256(v string)`

SetUrlSha256 sets UrlSha256 field to given value.


### GetData

`func (o *CitedUrlOccurrencesResponse) GetData() []CitedUrlOccurrencesResponseAllOfData`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *CitedUrlOccurrencesResponse) GetDataOk() (*[]CitedUrlOccurrencesResponseAllOfData, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *CitedUrlOccurrencesResponse) SetData(v []CitedUrlOccurrencesResponseAllOfData)`

SetData sets Data field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


