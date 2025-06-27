# TaskCollectionResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Tasks** | [**[]TaskResponse**](TaskResponse.md) |  | 
**TotalEntries** | **int32** |  | 

## Methods

### NewTaskCollectionResponse

`func NewTaskCollectionResponse(tasks []TaskResponse, totalEntries int32, ) *TaskCollectionResponse`

NewTaskCollectionResponse instantiates a new TaskCollectionResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTaskCollectionResponseWithDefaults

`func NewTaskCollectionResponseWithDefaults() *TaskCollectionResponse`

NewTaskCollectionResponseWithDefaults instantiates a new TaskCollectionResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTasks

`func (o *TaskCollectionResponse) GetTasks() []TaskResponse`

GetTasks returns the Tasks field if non-nil, zero value otherwise.

### GetTasksOk

`func (o *TaskCollectionResponse) GetTasksOk() (*[]TaskResponse, bool)`

GetTasksOk returns a tuple with the Tasks field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTasks

`func (o *TaskCollectionResponse) SetTasks(v []TaskResponse)`

SetTasks sets Tasks field to given value.


### GetTotalEntries

`func (o *TaskCollectionResponse) GetTotalEntries() int32`

GetTotalEntries returns the TotalEntries field if non-nil, zero value otherwise.

### GetTotalEntriesOk

`func (o *TaskCollectionResponse) GetTotalEntriesOk() (*int32, bool)`

GetTotalEntriesOk returns a tuple with the TotalEntries field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalEntries

`func (o *TaskCollectionResponse) SetTotalEntries(v int32)`

SetTotalEntries sets TotalEntries field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


