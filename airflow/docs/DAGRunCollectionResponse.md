# DAGRunCollectionResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DagRuns** | [**[]DAGRunResponse**](DAGRunResponse.md) |  | 
**TotalEntries** | **int32** |  | 

## Methods

### NewDAGRunCollectionResponse

`func NewDAGRunCollectionResponse(dagRuns []DAGRunResponse, totalEntries int32, ) *DAGRunCollectionResponse`

NewDAGRunCollectionResponse instantiates a new DAGRunCollectionResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDAGRunCollectionResponseWithDefaults

`func NewDAGRunCollectionResponseWithDefaults() *DAGRunCollectionResponse`

NewDAGRunCollectionResponseWithDefaults instantiates a new DAGRunCollectionResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDagRuns

`func (o *DAGRunCollectionResponse) GetDagRuns() []DAGRunResponse`

GetDagRuns returns the DagRuns field if non-nil, zero value otherwise.

### GetDagRunsOk

`func (o *DAGRunCollectionResponse) GetDagRunsOk() (*[]DAGRunResponse, bool)`

GetDagRunsOk returns a tuple with the DagRuns field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDagRuns

`func (o *DAGRunCollectionResponse) SetDagRuns(v []DAGRunResponse)`

SetDagRuns sets DagRuns field to given value.


### GetTotalEntries

`func (o *DAGRunCollectionResponse) GetTotalEntries() int32`

GetTotalEntries returns the TotalEntries field if non-nil, zero value otherwise.

### GetTotalEntriesOk

`func (o *DAGRunCollectionResponse) GetTotalEntriesOk() (*int32, bool)`

GetTotalEntriesOk returns a tuple with the TotalEntries field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalEntries

`func (o *DAGRunCollectionResponse) SetTotalEntries(v int32)`

SetTotalEntries sets TotalEntries field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


