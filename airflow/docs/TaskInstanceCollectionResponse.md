# TaskInstanceCollectionResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**TaskInstances** | [**[]TaskInstanceResponse**](TaskInstanceResponse.md) |  | 
**TotalEntries** | **int32** |  | 

## Methods

### NewTaskInstanceCollectionResponse

`func NewTaskInstanceCollectionResponse(taskInstances []TaskInstanceResponse, totalEntries int32, ) *TaskInstanceCollectionResponse`

NewTaskInstanceCollectionResponse instantiates a new TaskInstanceCollectionResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTaskInstanceCollectionResponseWithDefaults

`func NewTaskInstanceCollectionResponseWithDefaults() *TaskInstanceCollectionResponse`

NewTaskInstanceCollectionResponseWithDefaults instantiates a new TaskInstanceCollectionResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTaskInstances

`func (o *TaskInstanceCollectionResponse) GetTaskInstances() []TaskInstanceResponse`

GetTaskInstances returns the TaskInstances field if non-nil, zero value otherwise.

### GetTaskInstancesOk

`func (o *TaskInstanceCollectionResponse) GetTaskInstancesOk() (*[]TaskInstanceResponse, bool)`

GetTaskInstancesOk returns a tuple with the TaskInstances field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaskInstances

`func (o *TaskInstanceCollectionResponse) SetTaskInstances(v []TaskInstanceResponse)`

SetTaskInstances sets TaskInstances field to given value.


### GetTotalEntries

`func (o *TaskInstanceCollectionResponse) GetTotalEntries() int32`

GetTotalEntries returns the TotalEntries field if non-nil, zero value otherwise.

### GetTotalEntriesOk

`func (o *TaskInstanceCollectionResponse) GetTotalEntriesOk() (*int32, bool)`

GetTotalEntriesOk returns a tuple with the TotalEntries field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalEntries

`func (o *TaskInstanceCollectionResponse) SetTotalEntries(v int32)`

SetTotalEntries sets TotalEntries field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


