# TaskInstanceHistoryCollectionResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**TaskInstances** | [**[]TaskInstanceHistoryResponse**](TaskInstanceHistoryResponse.md) |  | 
**TotalEntries** | **int32** |  | 

## Methods

### NewTaskInstanceHistoryCollectionResponse

`func NewTaskInstanceHistoryCollectionResponse(taskInstances []TaskInstanceHistoryResponse, totalEntries int32, ) *TaskInstanceHistoryCollectionResponse`

NewTaskInstanceHistoryCollectionResponse instantiates a new TaskInstanceHistoryCollectionResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTaskInstanceHistoryCollectionResponseWithDefaults

`func NewTaskInstanceHistoryCollectionResponseWithDefaults() *TaskInstanceHistoryCollectionResponse`

NewTaskInstanceHistoryCollectionResponseWithDefaults instantiates a new TaskInstanceHistoryCollectionResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTaskInstances

`func (o *TaskInstanceHistoryCollectionResponse) GetTaskInstances() []TaskInstanceHistoryResponse`

GetTaskInstances returns the TaskInstances field if non-nil, zero value otherwise.

### GetTaskInstancesOk

`func (o *TaskInstanceHistoryCollectionResponse) GetTaskInstancesOk() (*[]TaskInstanceHistoryResponse, bool)`

GetTaskInstancesOk returns a tuple with the TaskInstances field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaskInstances

`func (o *TaskInstanceHistoryCollectionResponse) SetTaskInstances(v []TaskInstanceHistoryResponse)`

SetTaskInstances sets TaskInstances field to given value.


### GetTotalEntries

`func (o *TaskInstanceHistoryCollectionResponse) GetTotalEntries() int32`

GetTotalEntries returns the TotalEntries field if non-nil, zero value otherwise.

### GetTotalEntriesOk

`func (o *TaskInstanceHistoryCollectionResponse) GetTotalEntriesOk() (*int32, bool)`

GetTotalEntriesOk returns a tuple with the TotalEntries field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalEntries

`func (o *TaskInstanceHistoryCollectionResponse) SetTotalEntries(v int32)`

SetTotalEntries sets TotalEntries field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


