# DagStatsCollectionResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Dags** | [**[]DagStatsResponse**](DagStatsResponse.md) |  | 
**TotalEntries** | **int32** |  | 

## Methods

### NewDagStatsCollectionResponse

`func NewDagStatsCollectionResponse(dags []DagStatsResponse, totalEntries int32, ) *DagStatsCollectionResponse`

NewDagStatsCollectionResponse instantiates a new DagStatsCollectionResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDagStatsCollectionResponseWithDefaults

`func NewDagStatsCollectionResponseWithDefaults() *DagStatsCollectionResponse`

NewDagStatsCollectionResponseWithDefaults instantiates a new DagStatsCollectionResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDags

`func (o *DagStatsCollectionResponse) GetDags() []DagStatsResponse`

GetDags returns the Dags field if non-nil, zero value otherwise.

### GetDagsOk

`func (o *DagStatsCollectionResponse) GetDagsOk() (*[]DagStatsResponse, bool)`

GetDagsOk returns a tuple with the Dags field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDags

`func (o *DagStatsCollectionResponse) SetDags(v []DagStatsResponse)`

SetDags sets Dags field to given value.


### GetTotalEntries

`func (o *DagStatsCollectionResponse) GetTotalEntries() int32`

GetTotalEntries returns the TotalEntries field if non-nil, zero value otherwise.

### GetTotalEntriesOk

`func (o *DagStatsCollectionResponse) GetTotalEntriesOk() (*int32, bool)`

GetTotalEntriesOk returns a tuple with the TotalEntries field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalEntries

`func (o *DagStatsCollectionResponse) SetTotalEntries(v int32)`

SetTotalEntries sets TotalEntries field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


