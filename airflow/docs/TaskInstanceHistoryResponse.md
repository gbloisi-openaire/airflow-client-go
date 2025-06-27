# TaskInstanceHistoryResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**TaskId** | **string** |  | 
**DagId** | **string** |  | 
**DagRunId** | **string** |  | 
**MapIndex** | **int32** |  | 
**StartDate** | **NullableTime** |  | 
**EndDate** | **NullableTime** |  | 
**Duration** | **NullableFloat32** |  | 
**State** | [**NullableTaskInstanceState**](TaskInstanceState.md) |  | 
**TryNumber** | **int32** |  | 
**MaxTries** | **int32** |  | 
**TaskDisplayName** | **string** |  | 
**DagDisplayName** | **string** |  | 
**Hostname** | **NullableString** |  | 
**Unixname** | **NullableString** |  | 
**Pool** | **string** |  | 
**PoolSlots** | **int32** |  | 
**Queue** | **NullableString** |  | 
**PriorityWeight** | **NullableInt32** |  | 
**Operator** | **NullableString** |  | 
**QueuedWhen** | **NullableTime** |  | 
**ScheduledWhen** | **NullableTime** |  | 
**Pid** | **NullableInt32** |  | 
**Executor** | **NullableString** |  | 
**ExecutorConfig** | **string** |  | 
**DagVersion** | [**NullableDagVersionResponse**](DagVersionResponse.md) |  | 

## Methods

### NewTaskInstanceHistoryResponse

`func NewTaskInstanceHistoryResponse(taskId string, dagId string, dagRunId string, mapIndex int32, startDate NullableTime, endDate NullableTime, duration NullableFloat32, state NullableTaskInstanceState, tryNumber int32, maxTries int32, taskDisplayName string, dagDisplayName string, hostname NullableString, unixname NullableString, pool string, poolSlots int32, queue NullableString, priorityWeight NullableInt32, operator NullableString, queuedWhen NullableTime, scheduledWhen NullableTime, pid NullableInt32, executor NullableString, executorConfig string, dagVersion NullableDagVersionResponse, ) *TaskInstanceHistoryResponse`

NewTaskInstanceHistoryResponse instantiates a new TaskInstanceHistoryResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTaskInstanceHistoryResponseWithDefaults

`func NewTaskInstanceHistoryResponseWithDefaults() *TaskInstanceHistoryResponse`

NewTaskInstanceHistoryResponseWithDefaults instantiates a new TaskInstanceHistoryResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTaskId

`func (o *TaskInstanceHistoryResponse) GetTaskId() string`

GetTaskId returns the TaskId field if non-nil, zero value otherwise.

### GetTaskIdOk

`func (o *TaskInstanceHistoryResponse) GetTaskIdOk() (*string, bool)`

GetTaskIdOk returns a tuple with the TaskId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaskId

`func (o *TaskInstanceHistoryResponse) SetTaskId(v string)`

SetTaskId sets TaskId field to given value.


### GetDagId

`func (o *TaskInstanceHistoryResponse) GetDagId() string`

GetDagId returns the DagId field if non-nil, zero value otherwise.

### GetDagIdOk

`func (o *TaskInstanceHistoryResponse) GetDagIdOk() (*string, bool)`

GetDagIdOk returns a tuple with the DagId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDagId

`func (o *TaskInstanceHistoryResponse) SetDagId(v string)`

SetDagId sets DagId field to given value.


### GetDagRunId

`func (o *TaskInstanceHistoryResponse) GetDagRunId() string`

GetDagRunId returns the DagRunId field if non-nil, zero value otherwise.

### GetDagRunIdOk

`func (o *TaskInstanceHistoryResponse) GetDagRunIdOk() (*string, bool)`

GetDagRunIdOk returns a tuple with the DagRunId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDagRunId

`func (o *TaskInstanceHistoryResponse) SetDagRunId(v string)`

SetDagRunId sets DagRunId field to given value.


### GetMapIndex

`func (o *TaskInstanceHistoryResponse) GetMapIndex() int32`

GetMapIndex returns the MapIndex field if non-nil, zero value otherwise.

### GetMapIndexOk

`func (o *TaskInstanceHistoryResponse) GetMapIndexOk() (*int32, bool)`

GetMapIndexOk returns a tuple with the MapIndex field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMapIndex

`func (o *TaskInstanceHistoryResponse) SetMapIndex(v int32)`

SetMapIndex sets MapIndex field to given value.


### GetStartDate

`func (o *TaskInstanceHistoryResponse) GetStartDate() time.Time`

GetStartDate returns the StartDate field if non-nil, zero value otherwise.

### GetStartDateOk

`func (o *TaskInstanceHistoryResponse) GetStartDateOk() (*time.Time, bool)`

GetStartDateOk returns a tuple with the StartDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartDate

`func (o *TaskInstanceHistoryResponse) SetStartDate(v time.Time)`

SetStartDate sets StartDate field to given value.


### SetStartDateNil

`func (o *TaskInstanceHistoryResponse) SetStartDateNil(b bool)`

 SetStartDateNil sets the value for StartDate to be an explicit nil

### UnsetStartDate
`func (o *TaskInstanceHistoryResponse) UnsetStartDate()`

UnsetStartDate ensures that no value is present for StartDate, not even an explicit nil
### GetEndDate

`func (o *TaskInstanceHistoryResponse) GetEndDate() time.Time`

GetEndDate returns the EndDate field if non-nil, zero value otherwise.

### GetEndDateOk

`func (o *TaskInstanceHistoryResponse) GetEndDateOk() (*time.Time, bool)`

GetEndDateOk returns a tuple with the EndDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEndDate

`func (o *TaskInstanceHistoryResponse) SetEndDate(v time.Time)`

SetEndDate sets EndDate field to given value.


### SetEndDateNil

`func (o *TaskInstanceHistoryResponse) SetEndDateNil(b bool)`

 SetEndDateNil sets the value for EndDate to be an explicit nil

### UnsetEndDate
`func (o *TaskInstanceHistoryResponse) UnsetEndDate()`

UnsetEndDate ensures that no value is present for EndDate, not even an explicit nil
### GetDuration

`func (o *TaskInstanceHistoryResponse) GetDuration() float32`

GetDuration returns the Duration field if non-nil, zero value otherwise.

### GetDurationOk

`func (o *TaskInstanceHistoryResponse) GetDurationOk() (*float32, bool)`

GetDurationOk returns a tuple with the Duration field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDuration

`func (o *TaskInstanceHistoryResponse) SetDuration(v float32)`

SetDuration sets Duration field to given value.


### SetDurationNil

`func (o *TaskInstanceHistoryResponse) SetDurationNil(b bool)`

 SetDurationNil sets the value for Duration to be an explicit nil

### UnsetDuration
`func (o *TaskInstanceHistoryResponse) UnsetDuration()`

UnsetDuration ensures that no value is present for Duration, not even an explicit nil
### GetState

`func (o *TaskInstanceHistoryResponse) GetState() TaskInstanceState`

GetState returns the State field if non-nil, zero value otherwise.

### GetStateOk

`func (o *TaskInstanceHistoryResponse) GetStateOk() (*TaskInstanceState, bool)`

GetStateOk returns a tuple with the State field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetState

`func (o *TaskInstanceHistoryResponse) SetState(v TaskInstanceState)`

SetState sets State field to given value.


### SetStateNil

`func (o *TaskInstanceHistoryResponse) SetStateNil(b bool)`

 SetStateNil sets the value for State to be an explicit nil

### UnsetState
`func (o *TaskInstanceHistoryResponse) UnsetState()`

UnsetState ensures that no value is present for State, not even an explicit nil
### GetTryNumber

`func (o *TaskInstanceHistoryResponse) GetTryNumber() int32`

GetTryNumber returns the TryNumber field if non-nil, zero value otherwise.

### GetTryNumberOk

`func (o *TaskInstanceHistoryResponse) GetTryNumberOk() (*int32, bool)`

GetTryNumberOk returns a tuple with the TryNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTryNumber

`func (o *TaskInstanceHistoryResponse) SetTryNumber(v int32)`

SetTryNumber sets TryNumber field to given value.


### GetMaxTries

`func (o *TaskInstanceHistoryResponse) GetMaxTries() int32`

GetMaxTries returns the MaxTries field if non-nil, zero value otherwise.

### GetMaxTriesOk

`func (o *TaskInstanceHistoryResponse) GetMaxTriesOk() (*int32, bool)`

GetMaxTriesOk returns a tuple with the MaxTries field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxTries

`func (o *TaskInstanceHistoryResponse) SetMaxTries(v int32)`

SetMaxTries sets MaxTries field to given value.


### GetTaskDisplayName

`func (o *TaskInstanceHistoryResponse) GetTaskDisplayName() string`

GetTaskDisplayName returns the TaskDisplayName field if non-nil, zero value otherwise.

### GetTaskDisplayNameOk

`func (o *TaskInstanceHistoryResponse) GetTaskDisplayNameOk() (*string, bool)`

GetTaskDisplayNameOk returns a tuple with the TaskDisplayName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaskDisplayName

`func (o *TaskInstanceHistoryResponse) SetTaskDisplayName(v string)`

SetTaskDisplayName sets TaskDisplayName field to given value.


### GetDagDisplayName

`func (o *TaskInstanceHistoryResponse) GetDagDisplayName() string`

GetDagDisplayName returns the DagDisplayName field if non-nil, zero value otherwise.

### GetDagDisplayNameOk

`func (o *TaskInstanceHistoryResponse) GetDagDisplayNameOk() (*string, bool)`

GetDagDisplayNameOk returns a tuple with the DagDisplayName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDagDisplayName

`func (o *TaskInstanceHistoryResponse) SetDagDisplayName(v string)`

SetDagDisplayName sets DagDisplayName field to given value.


### GetHostname

`func (o *TaskInstanceHistoryResponse) GetHostname() string`

GetHostname returns the Hostname field if non-nil, zero value otherwise.

### GetHostnameOk

`func (o *TaskInstanceHistoryResponse) GetHostnameOk() (*string, bool)`

GetHostnameOk returns a tuple with the Hostname field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHostname

`func (o *TaskInstanceHistoryResponse) SetHostname(v string)`

SetHostname sets Hostname field to given value.


### SetHostnameNil

`func (o *TaskInstanceHistoryResponse) SetHostnameNil(b bool)`

 SetHostnameNil sets the value for Hostname to be an explicit nil

### UnsetHostname
`func (o *TaskInstanceHistoryResponse) UnsetHostname()`

UnsetHostname ensures that no value is present for Hostname, not even an explicit nil
### GetUnixname

`func (o *TaskInstanceHistoryResponse) GetUnixname() string`

GetUnixname returns the Unixname field if non-nil, zero value otherwise.

### GetUnixnameOk

`func (o *TaskInstanceHistoryResponse) GetUnixnameOk() (*string, bool)`

GetUnixnameOk returns a tuple with the Unixname field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnixname

`func (o *TaskInstanceHistoryResponse) SetUnixname(v string)`

SetUnixname sets Unixname field to given value.


### SetUnixnameNil

`func (o *TaskInstanceHistoryResponse) SetUnixnameNil(b bool)`

 SetUnixnameNil sets the value for Unixname to be an explicit nil

### UnsetUnixname
`func (o *TaskInstanceHistoryResponse) UnsetUnixname()`

UnsetUnixname ensures that no value is present for Unixname, not even an explicit nil
### GetPool

`func (o *TaskInstanceHistoryResponse) GetPool() string`

GetPool returns the Pool field if non-nil, zero value otherwise.

### GetPoolOk

`func (o *TaskInstanceHistoryResponse) GetPoolOk() (*string, bool)`

GetPoolOk returns a tuple with the Pool field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPool

`func (o *TaskInstanceHistoryResponse) SetPool(v string)`

SetPool sets Pool field to given value.


### GetPoolSlots

`func (o *TaskInstanceHistoryResponse) GetPoolSlots() int32`

GetPoolSlots returns the PoolSlots field if non-nil, zero value otherwise.

### GetPoolSlotsOk

`func (o *TaskInstanceHistoryResponse) GetPoolSlotsOk() (*int32, bool)`

GetPoolSlotsOk returns a tuple with the PoolSlots field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPoolSlots

`func (o *TaskInstanceHistoryResponse) SetPoolSlots(v int32)`

SetPoolSlots sets PoolSlots field to given value.


### GetQueue

`func (o *TaskInstanceHistoryResponse) GetQueue() string`

GetQueue returns the Queue field if non-nil, zero value otherwise.

### GetQueueOk

`func (o *TaskInstanceHistoryResponse) GetQueueOk() (*string, bool)`

GetQueueOk returns a tuple with the Queue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQueue

`func (o *TaskInstanceHistoryResponse) SetQueue(v string)`

SetQueue sets Queue field to given value.


### SetQueueNil

`func (o *TaskInstanceHistoryResponse) SetQueueNil(b bool)`

 SetQueueNil sets the value for Queue to be an explicit nil

### UnsetQueue
`func (o *TaskInstanceHistoryResponse) UnsetQueue()`

UnsetQueue ensures that no value is present for Queue, not even an explicit nil
### GetPriorityWeight

`func (o *TaskInstanceHistoryResponse) GetPriorityWeight() int32`

GetPriorityWeight returns the PriorityWeight field if non-nil, zero value otherwise.

### GetPriorityWeightOk

`func (o *TaskInstanceHistoryResponse) GetPriorityWeightOk() (*int32, bool)`

GetPriorityWeightOk returns a tuple with the PriorityWeight field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPriorityWeight

`func (o *TaskInstanceHistoryResponse) SetPriorityWeight(v int32)`

SetPriorityWeight sets PriorityWeight field to given value.


### SetPriorityWeightNil

`func (o *TaskInstanceHistoryResponse) SetPriorityWeightNil(b bool)`

 SetPriorityWeightNil sets the value for PriorityWeight to be an explicit nil

### UnsetPriorityWeight
`func (o *TaskInstanceHistoryResponse) UnsetPriorityWeight()`

UnsetPriorityWeight ensures that no value is present for PriorityWeight, not even an explicit nil
### GetOperator

`func (o *TaskInstanceHistoryResponse) GetOperator() string`

GetOperator returns the Operator field if non-nil, zero value otherwise.

### GetOperatorOk

`func (o *TaskInstanceHistoryResponse) GetOperatorOk() (*string, bool)`

GetOperatorOk returns a tuple with the Operator field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperator

`func (o *TaskInstanceHistoryResponse) SetOperator(v string)`

SetOperator sets Operator field to given value.


### SetOperatorNil

`func (o *TaskInstanceHistoryResponse) SetOperatorNil(b bool)`

 SetOperatorNil sets the value for Operator to be an explicit nil

### UnsetOperator
`func (o *TaskInstanceHistoryResponse) UnsetOperator()`

UnsetOperator ensures that no value is present for Operator, not even an explicit nil
### GetQueuedWhen

`func (o *TaskInstanceHistoryResponse) GetQueuedWhen() time.Time`

GetQueuedWhen returns the QueuedWhen field if non-nil, zero value otherwise.

### GetQueuedWhenOk

`func (o *TaskInstanceHistoryResponse) GetQueuedWhenOk() (*time.Time, bool)`

GetQueuedWhenOk returns a tuple with the QueuedWhen field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQueuedWhen

`func (o *TaskInstanceHistoryResponse) SetQueuedWhen(v time.Time)`

SetQueuedWhen sets QueuedWhen field to given value.


### SetQueuedWhenNil

`func (o *TaskInstanceHistoryResponse) SetQueuedWhenNil(b bool)`

 SetQueuedWhenNil sets the value for QueuedWhen to be an explicit nil

### UnsetQueuedWhen
`func (o *TaskInstanceHistoryResponse) UnsetQueuedWhen()`

UnsetQueuedWhen ensures that no value is present for QueuedWhen, not even an explicit nil
### GetScheduledWhen

`func (o *TaskInstanceHistoryResponse) GetScheduledWhen() time.Time`

GetScheduledWhen returns the ScheduledWhen field if non-nil, zero value otherwise.

### GetScheduledWhenOk

`func (o *TaskInstanceHistoryResponse) GetScheduledWhenOk() (*time.Time, bool)`

GetScheduledWhenOk returns a tuple with the ScheduledWhen field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScheduledWhen

`func (o *TaskInstanceHistoryResponse) SetScheduledWhen(v time.Time)`

SetScheduledWhen sets ScheduledWhen field to given value.


### SetScheduledWhenNil

`func (o *TaskInstanceHistoryResponse) SetScheduledWhenNil(b bool)`

 SetScheduledWhenNil sets the value for ScheduledWhen to be an explicit nil

### UnsetScheduledWhen
`func (o *TaskInstanceHistoryResponse) UnsetScheduledWhen()`

UnsetScheduledWhen ensures that no value is present for ScheduledWhen, not even an explicit nil
### GetPid

`func (o *TaskInstanceHistoryResponse) GetPid() int32`

GetPid returns the Pid field if non-nil, zero value otherwise.

### GetPidOk

`func (o *TaskInstanceHistoryResponse) GetPidOk() (*int32, bool)`

GetPidOk returns a tuple with the Pid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPid

`func (o *TaskInstanceHistoryResponse) SetPid(v int32)`

SetPid sets Pid field to given value.


### SetPidNil

`func (o *TaskInstanceHistoryResponse) SetPidNil(b bool)`

 SetPidNil sets the value for Pid to be an explicit nil

### UnsetPid
`func (o *TaskInstanceHistoryResponse) UnsetPid()`

UnsetPid ensures that no value is present for Pid, not even an explicit nil
### GetExecutor

`func (o *TaskInstanceHistoryResponse) GetExecutor() string`

GetExecutor returns the Executor field if non-nil, zero value otherwise.

### GetExecutorOk

`func (o *TaskInstanceHistoryResponse) GetExecutorOk() (*string, bool)`

GetExecutorOk returns a tuple with the Executor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExecutor

`func (o *TaskInstanceHistoryResponse) SetExecutor(v string)`

SetExecutor sets Executor field to given value.


### SetExecutorNil

`func (o *TaskInstanceHistoryResponse) SetExecutorNil(b bool)`

 SetExecutorNil sets the value for Executor to be an explicit nil

### UnsetExecutor
`func (o *TaskInstanceHistoryResponse) UnsetExecutor()`

UnsetExecutor ensures that no value is present for Executor, not even an explicit nil
### GetExecutorConfig

`func (o *TaskInstanceHistoryResponse) GetExecutorConfig() string`

GetExecutorConfig returns the ExecutorConfig field if non-nil, zero value otherwise.

### GetExecutorConfigOk

`func (o *TaskInstanceHistoryResponse) GetExecutorConfigOk() (*string, bool)`

GetExecutorConfigOk returns a tuple with the ExecutorConfig field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExecutorConfig

`func (o *TaskInstanceHistoryResponse) SetExecutorConfig(v string)`

SetExecutorConfig sets ExecutorConfig field to given value.


### GetDagVersion

`func (o *TaskInstanceHistoryResponse) GetDagVersion() DagVersionResponse`

GetDagVersion returns the DagVersion field if non-nil, zero value otherwise.

### GetDagVersionOk

`func (o *TaskInstanceHistoryResponse) GetDagVersionOk() (*DagVersionResponse, bool)`

GetDagVersionOk returns a tuple with the DagVersion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDagVersion

`func (o *TaskInstanceHistoryResponse) SetDagVersion(v DagVersionResponse)`

SetDagVersion sets DagVersion field to given value.


### SetDagVersionNil

`func (o *TaskInstanceHistoryResponse) SetDagVersionNil(b bool)`

 SetDagVersionNil sets the value for DagVersion to be an explicit nil

### UnsetDagVersion
`func (o *TaskInstanceHistoryResponse) UnsetDagVersion()`

UnsetDagVersion ensures that no value is present for DagVersion, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


