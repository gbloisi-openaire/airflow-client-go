# DAGWarningCollectionResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DagWarnings** | [**[]DAGWarningResponse**](DAGWarningResponse.md) |  | 
**TotalEntries** | **int32** |  | 

## Methods

### NewDAGWarningCollectionResponse

`func NewDAGWarningCollectionResponse(dagWarnings []DAGWarningResponse, totalEntries int32, ) *DAGWarningCollectionResponse`

NewDAGWarningCollectionResponse instantiates a new DAGWarningCollectionResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDAGWarningCollectionResponseWithDefaults

`func NewDAGWarningCollectionResponseWithDefaults() *DAGWarningCollectionResponse`

NewDAGWarningCollectionResponseWithDefaults instantiates a new DAGWarningCollectionResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDagWarnings

`func (o *DAGWarningCollectionResponse) GetDagWarnings() []DAGWarningResponse`

GetDagWarnings returns the DagWarnings field if non-nil, zero value otherwise.

### GetDagWarningsOk

`func (o *DAGWarningCollectionResponse) GetDagWarningsOk() (*[]DAGWarningResponse, bool)`

GetDagWarningsOk returns a tuple with the DagWarnings field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDagWarnings

`func (o *DAGWarningCollectionResponse) SetDagWarnings(v []DAGWarningResponse)`

SetDagWarnings sets DagWarnings field to given value.


### GetTotalEntries

`func (o *DAGWarningCollectionResponse) GetTotalEntries() int32`

GetTotalEntries returns the TotalEntries field if non-nil, zero value otherwise.

### GetTotalEntriesOk

`func (o *DAGWarningCollectionResponse) GetTotalEntriesOk() (*int32, bool)`

GetTotalEntriesOk returns a tuple with the TotalEntries field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalEntries

`func (o *DAGWarningCollectionResponse) SetTotalEntries(v int32)`

SetTotalEntries sets TotalEntries field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


