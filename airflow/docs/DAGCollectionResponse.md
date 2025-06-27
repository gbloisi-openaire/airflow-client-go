# DAGCollectionResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Dags** | [**[]DAGResponse**](DAGResponse.md) |  | 
**TotalEntries** | **int32** |  | 

## Methods

### NewDAGCollectionResponse

`func NewDAGCollectionResponse(dags []DAGResponse, totalEntries int32, ) *DAGCollectionResponse`

NewDAGCollectionResponse instantiates a new DAGCollectionResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDAGCollectionResponseWithDefaults

`func NewDAGCollectionResponseWithDefaults() *DAGCollectionResponse`

NewDAGCollectionResponseWithDefaults instantiates a new DAGCollectionResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDags

`func (o *DAGCollectionResponse) GetDags() []DAGResponse`

GetDags returns the Dags field if non-nil, zero value otherwise.

### GetDagsOk

`func (o *DAGCollectionResponse) GetDagsOk() (*[]DAGResponse, bool)`

GetDagsOk returns a tuple with the Dags field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDags

`func (o *DAGCollectionResponse) SetDags(v []DAGResponse)`

SetDags sets Dags field to given value.


### GetTotalEntries

`func (o *DAGCollectionResponse) GetTotalEntries() int32`

GetTotalEntries returns the TotalEntries field if non-nil, zero value otherwise.

### GetTotalEntriesOk

`func (o *DAGCollectionResponse) GetTotalEntriesOk() (*int32, bool)`

GetTotalEntriesOk returns a tuple with the TotalEntries field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalEntries

`func (o *DAGCollectionResponse) SetTotalEntries(v int32)`

SetTotalEntries sets TotalEntries field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


