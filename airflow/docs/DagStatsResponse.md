# DagStatsResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DagId** | **string** |  | 
**Stats** | [**[]DagStatsStateResponse**](DagStatsStateResponse.md) |  | 

## Methods

### NewDagStatsResponse

`func NewDagStatsResponse(dagId string, stats []DagStatsStateResponse, ) *DagStatsResponse`

NewDagStatsResponse instantiates a new DagStatsResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDagStatsResponseWithDefaults

`func NewDagStatsResponseWithDefaults() *DagStatsResponse`

NewDagStatsResponseWithDefaults instantiates a new DagStatsResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDagId

`func (o *DagStatsResponse) GetDagId() string`

GetDagId returns the DagId field if non-nil, zero value otherwise.

### GetDagIdOk

`func (o *DagStatsResponse) GetDagIdOk() (*string, bool)`

GetDagIdOk returns a tuple with the DagId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDagId

`func (o *DagStatsResponse) SetDagId(v string)`

SetDagId sets DagId field to given value.


### GetStats

`func (o *DagStatsResponse) GetStats() []DagStatsStateResponse`

GetStats returns the Stats field if non-nil, zero value otherwise.

### GetStatsOk

`func (o *DagStatsResponse) GetStatsOk() (*[]DagStatsStateResponse, bool)`

GetStatsOk returns a tuple with the Stats field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStats

`func (o *DagStatsResponse) SetStats(v []DagStatsStateResponse)`

SetStats sets Stats field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


