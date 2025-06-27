# DAGVersionCollectionResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DagVersions** | [**[]DagVersionResponse**](DagVersionResponse.md) |  | 
**TotalEntries** | **int32** |  | 

## Methods

### NewDAGVersionCollectionResponse

`func NewDAGVersionCollectionResponse(dagVersions []DagVersionResponse, totalEntries int32, ) *DAGVersionCollectionResponse`

NewDAGVersionCollectionResponse instantiates a new DAGVersionCollectionResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDAGVersionCollectionResponseWithDefaults

`func NewDAGVersionCollectionResponseWithDefaults() *DAGVersionCollectionResponse`

NewDAGVersionCollectionResponseWithDefaults instantiates a new DAGVersionCollectionResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDagVersions

`func (o *DAGVersionCollectionResponse) GetDagVersions() []DagVersionResponse`

GetDagVersions returns the DagVersions field if non-nil, zero value otherwise.

### GetDagVersionsOk

`func (o *DAGVersionCollectionResponse) GetDagVersionsOk() (*[]DagVersionResponse, bool)`

GetDagVersionsOk returns a tuple with the DagVersions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDagVersions

`func (o *DAGVersionCollectionResponse) SetDagVersions(v []DagVersionResponse)`

SetDagVersions sets DagVersions field to given value.


### GetTotalEntries

`func (o *DAGVersionCollectionResponse) GetTotalEntries() int32`

GetTotalEntries returns the TotalEntries field if non-nil, zero value otherwise.

### GetTotalEntriesOk

`func (o *DAGVersionCollectionResponse) GetTotalEntriesOk() (*int32, bool)`

GetTotalEntriesOk returns a tuple with the TotalEntries field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalEntries

`func (o *DAGVersionCollectionResponse) SetTotalEntries(v int32)`

SetTotalEntries sets TotalEntries field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


