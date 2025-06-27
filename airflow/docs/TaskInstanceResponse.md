# TaskInstanceResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | 
**TaskId** | **string** |  | 
**DagId** | **string** |  | 
**DagRunId** | **string** |  | 
**MapIndex** | **int32** |  | 
**LogicalDate** | **NullableTime** |  | 
**RunAfter** | **time.Time** |  | 
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
**Note** | **NullableString** |  | 
**RenderedMapIndex** | **NullableString** |  | 
**RenderedFields** | Pointer to **map[string]interface{}** |  | [optional] 
**Trigger** | [**NullableTriggerResponse**](TriggerResponse.md) |  | 
**TriggererJob** | [**NullableJobResponse**](JobResponse.md) |  | 
**DagVersion** | [**NullableDagVersionResponse**](DagVersionResponse.md) |  | 

## Methods

### NewTaskInstanceResponse

`func NewTaskInstanceResponse(id string, taskId string, dagId string, dagRunId string, mapIndex int32, logicalDate NullableTime, runAfter time.Time, startDate NullableTime, endDate NullableTime, duration NullableFloat32, state NullableTaskInstanceState, tryNumber int32, maxTries int32, taskDisplayName string, dagDisplayName string, hostname NullableString, unixname NullableString, pool string, poolSlots int32, queue NullableString, priorityWeight NullableInt32, operator NullableString, queuedWhen NullableTime, scheduledWhen NullableTime, pid NullableInt32, executor NullableString, executorConfig string, note NullableString, renderedMapIndex NullableString, trigger NullableTriggerResponse, triggererJob NullableJobResponse, dagVersion NullableDagVersionResponse, ) *TaskInstanceResponse`

NewTaskInstanceResponse instantiates a new TaskInstanceResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTaskInstanceResponseWithDefaults

`func NewTaskInstanceResponseWithDefaults() *TaskInstanceResponse`

NewTaskInstanceResponseWithDefaults instantiates a new TaskInstanceResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *TaskInstanceResponse) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *TaskInstanceResponse) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *TaskInstanceResponse) SetId(v string)`

SetId sets Id field to given value.


### GetTaskId

`func (o *TaskInstanceResponse) GetTaskId() string`

GetTaskId returns the TaskId field if non-nil, zero value otherwise.

### GetTaskIdOk

`func (o *TaskInstanceResponse) GetTaskIdOk() (*string, bool)`

GetTaskIdOk returns a tuple with the TaskId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaskId

`func (o *TaskInstanceResponse) SetTaskId(v string)`

SetTaskId sets TaskId field to given value.


### GetDagId

`func (o *TaskInstanceResponse) GetDagId() string`

GetDagId returns the DagId field if non-nil, zero value otherwise.

### GetDagIdOk

`func (o *TaskInstanceResponse) GetDagIdOk() (*string, bool)`

GetDagIdOk returns a tuple with the DagId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDagId

`func (o *TaskInstanceResponse) SetDagId(v string)`

SetDagId sets DagId field to given value.


### GetDagRunId

`func (o *TaskInstanceResponse) GetDagRunId() string`

GetDagRunId returns the DagRunId field if non-nil, zero value otherwise.

### GetDagRunIdOk

`func (o *TaskInstanceResponse) GetDagRunIdOk() (*string, bool)`

GetDagRunIdOk returns a tuple with the DagRunId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDagRunId

`func (o *TaskInstanceResponse) SetDagRunId(v string)`

SetDagRunId sets DagRunId field to given value.


### GetMapIndex

`func (o *TaskInstanceResponse) GetMapIndex() int32`

GetMapIndex returns the MapIndex field if non-nil, zero value otherwise.

### GetMapIndexOk

`func (o *TaskInstanceResponse) GetMapIndexOk() (*int32, bool)`

GetMapIndexOk returns a tuple with the MapIndex field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMapIndex

`func (o *TaskInstanceResponse) SetMapIndex(v int32)`

SetMapIndex sets MapIndex field to given value.


### GetLogicalDate

`func (o *TaskInstanceResponse) GetLogicalDate() time.Time`

GetLogicalDate returns the LogicalDate field if non-nil, zero value otherwise.

### GetLogicalDateOk

`func (o *TaskInstanceResponse) GetLogicalDateOk() (*time.Time, bool)`

GetLogicalDateOk returns a tuple with the LogicalDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLogicalDate

`func (o *TaskInstanceResponse) SetLogicalDate(v time.Time)`

SetLogicalDate sets LogicalDate field to given value.


### SetLogicalDateNil

`func (o *TaskInstanceResponse) SetLogicalDateNil(b bool)`

 SetLogicalDateNil sets the value for LogicalDate to be an explicit nil

### UnsetLogicalDate
`func (o *TaskInstanceResponse) UnsetLogicalDate()`

UnsetLogicalDate ensures that no value is present for LogicalDate, not even an explicit nil
### GetRunAfter

`func (o *TaskInstanceResponse) GetRunAfter() time.Time`

GetRunAfter returns the RunAfter field if non-nil, zero value otherwise.

### GetRunAfterOk

`func (o *TaskInstanceResponse) GetRunAfterOk() (*time.Time, bool)`

GetRunAfterOk returns a tuple with the RunAfter field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRunAfter

`func (o *TaskInstanceResponse) SetRunAfter(v time.Time)`

SetRunAfter sets RunAfter field to given value.


### GetStartDate

`func (o *TaskInstanceResponse) GetStartDate() time.Time`

GetStartDate returns the StartDate field if non-nil, zero value otherwise.

### GetStartDateOk

`func (o *TaskInstanceResponse) GetStartDateOk() (*time.Time, bool)`

GetStartDateOk returns a tuple with the StartDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartDate

`func (o *TaskInstanceResponse) SetStartDate(v time.Time)`

SetStartDate sets StartDate field to given value.


### SetStartDateNil

`func (o *TaskInstanceResponse) SetStartDateNil(b bool)`

 SetStartDateNil sets the value for StartDate to be an explicit nil

### UnsetStartDate
`func (o *TaskInstanceResponse) UnsetStartDate()`

UnsetStartDate ensures that no value is present for StartDate, not even an explicit nil
### GetEndDate

`func (o *TaskInstanceResponse) GetEndDate() time.Time`

GetEndDate returns the EndDate field if non-nil, zero value otherwise.

### GetEndDateOk

`func (o *TaskInstanceResponse) GetEndDateOk() (*time.Time, bool)`

GetEndDateOk returns a tuple with the EndDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEndDate

`func (o *TaskInstanceResponse) SetEndDate(v time.Time)`

SetEndDate sets EndDate field to given value.


### SetEndDateNil

`func (o *TaskInstanceResponse) SetEndDateNil(b bool)`

 SetEndDateNil sets the value for EndDate to be an explicit nil

### UnsetEndDate
`func (o *TaskInstanceResponse) UnsetEndDate()`

UnsetEndDate ensures that no value is present for EndDate, not even an explicit nil
### GetDuration

`func (o *TaskInstanceResponse) GetDuration() float32`

GetDuration returns the Duration field if non-nil, zero value otherwise.

### GetDurationOk

`func (o *TaskInstanceResponse) GetDurationOk() (*float32, bool)`

GetDurationOk returns a tuple with the Duration field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDuration

`func (o *TaskInstanceResponse) SetDuration(v float32)`

SetDuration sets Duration field to given value.


### SetDurationNil

`func (o *TaskInstanceResponse) SetDurationNil(b bool)`

 SetDurationNil sets the value for Duration to be an explicit nil

### UnsetDuration
`func (o *TaskInstanceResponse) UnsetDuration()`

UnsetDuration ensures that no value is present for Duration, not even an explicit nil
### GetState

`func (o *TaskInstanceResponse) GetState() TaskInstanceState`

GetState returns the State field if non-nil, zero value otherwise.

### GetStateOk

`func (o *TaskInstanceResponse) GetStateOk() (*TaskInstanceState, bool)`

GetStateOk returns a tuple with the State field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetState

`func (o *TaskInstanceResponse) SetState(v TaskInstanceState)`

SetState sets State field to given value.


### SetStateNil

`func (o *TaskInstanceResponse) SetStateNil(b bool)`

 SetStateNil sets the value for State to be an explicit nil

### UnsetState
`func (o *TaskInstanceResponse) UnsetState()`

UnsetState ensures that no value is present for State, not even an explicit nil
### GetTryNumber

`func (o *TaskInstanceResponse) GetTryNumber() int32`

GetTryNumber returns the TryNumber field if non-nil, zero value otherwise.

### GetTryNumberOk

`func (o *TaskInstanceResponse) GetTryNumberOk() (*int32, bool)`

GetTryNumberOk returns a tuple with the TryNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTryNumber

`func (o *TaskInstanceResponse) SetTryNumber(v int32)`

SetTryNumber sets TryNumber field to given value.


### GetMaxTries

`func (o *TaskInstanceResponse) GetMaxTries() int32`

GetMaxTries returns the MaxTries field if non-nil, zero value otherwise.

### GetMaxTriesOk

`func (o *TaskInstanceResponse) GetMaxTriesOk() (*int32, bool)`

GetMaxTriesOk returns a tuple with the MaxTries field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxTries

`func (o *TaskInstanceResponse) SetMaxTries(v int32)`

SetMaxTries sets MaxTries field to given value.


### GetTaskDisplayName

`func (o *TaskInstanceResponse) GetTaskDisplayName() string`

GetTaskDisplayName returns the TaskDisplayName field if non-nil, zero value otherwise.

### GetTaskDisplayNameOk

`func (o *TaskInstanceResponse) GetTaskDisplayNameOk() (*string, bool)`

GetTaskDisplayNameOk returns a tuple with the TaskDisplayName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaskDisplayName

`func (o *TaskInstanceResponse) SetTaskDisplayName(v string)`

SetTaskDisplayName sets TaskDisplayName field to given value.


### GetDagDisplayName

`func (o *TaskInstanceResponse) GetDagDisplayName() string`

GetDagDisplayName returns the DagDisplayName field if non-nil, zero value otherwise.

### GetDagDisplayNameOk

`func (o *TaskInstanceResponse) GetDagDisplayNameOk() (*string, bool)`

GetDagDisplayNameOk returns a tuple with the DagDisplayName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDagDisplayName

`func (o *TaskInstanceResponse) SetDagDisplayName(v string)`

SetDagDisplayName sets DagDisplayName field to given value.


### GetHostname

`func (o *TaskInstanceResponse) GetHostname() string`

GetHostname returns the Hostname field if non-nil, zero value otherwise.

### GetHostnameOk

`func (o *TaskInstanceResponse) GetHostnameOk() (*string, bool)`

GetHostnameOk returns a tuple with the Hostname field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHostname

`func (o *TaskInstanceResponse) SetHostname(v string)`

SetHostname sets Hostname field to given value.


### SetHostnameNil

`func (o *TaskInstanceResponse) SetHostnameNil(b bool)`

 SetHostnameNil sets the value for Hostname to be an explicit nil

### UnsetHostname
`func (o *TaskInstanceResponse) UnsetHostname()`

UnsetHostname ensures that no value is present for Hostname, not even an explicit nil
### GetUnixname

`func (o *TaskInstanceResponse) GetUnixname() string`

GetUnixname returns the Unixname field if non-nil, zero value otherwise.

### GetUnixnameOk

`func (o *TaskInstanceResponse) GetUnixnameOk() (*string, bool)`

GetUnixnameOk returns a tuple with the Unixname field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnixname

`func (o *TaskInstanceResponse) SetUnixname(v string)`

SetUnixname sets Unixname field to given value.


### SetUnixnameNil

`func (o *TaskInstanceResponse) SetUnixnameNil(b bool)`

 SetUnixnameNil sets the value for Unixname to be an explicit nil

### UnsetUnixname
`func (o *TaskInstanceResponse) UnsetUnixname()`

UnsetUnixname ensures that no value is present for Unixname, not even an explicit nil
### GetPool

`func (o *TaskInstanceResponse) GetPool() string`

GetPool returns the Pool field if non-nil, zero value otherwise.

### GetPoolOk

`func (o *TaskInstanceResponse) GetPoolOk() (*string, bool)`

GetPoolOk returns a tuple with the Pool field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPool

`func (o *TaskInstanceResponse) SetPool(v string)`

SetPool sets Pool field to given value.


### GetPoolSlots

`func (o *TaskInstanceResponse) GetPoolSlots() int32`

GetPoolSlots returns the PoolSlots field if non-nil, zero value otherwise.

### GetPoolSlotsOk

`func (o *TaskInstanceResponse) GetPoolSlotsOk() (*int32, bool)`

GetPoolSlotsOk returns a tuple with the PoolSlots field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPoolSlots

`func (o *TaskInstanceResponse) SetPoolSlots(v int32)`

SetPoolSlots sets PoolSlots field to given value.


### GetQueue

`func (o *TaskInstanceResponse) GetQueue() string`

GetQueue returns the Queue field if non-nil, zero value otherwise.

### GetQueueOk

`func (o *TaskInstanceResponse) GetQueueOk() (*string, bool)`

GetQueueOk returns a tuple with the Queue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQueue

`func (o *TaskInstanceResponse) SetQueue(v string)`

SetQueue sets Queue field to given value.


### SetQueueNil

`func (o *TaskInstanceResponse) SetQueueNil(b bool)`

 SetQueueNil sets the value for Queue to be an explicit nil

### UnsetQueue
`func (o *TaskInstanceResponse) UnsetQueue()`

UnsetQueue ensures that no value is present for Queue, not even an explicit nil
### GetPriorityWeight

`func (o *TaskInstanceResponse) GetPriorityWeight() int32`

GetPriorityWeight returns the PriorityWeight field if non-nil, zero value otherwise.

### GetPriorityWeightOk

`func (o *TaskInstanceResponse) GetPriorityWeightOk() (*int32, bool)`

GetPriorityWeightOk returns a tuple with the PriorityWeight field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPriorityWeight

`func (o *TaskInstanceResponse) SetPriorityWeight(v int32)`

SetPriorityWeight sets PriorityWeight field to given value.


### SetPriorityWeightNil

`func (o *TaskInstanceResponse) SetPriorityWeightNil(b bool)`

 SetPriorityWeightNil sets the value for PriorityWeight to be an explicit nil

### UnsetPriorityWeight
`func (o *TaskInstanceResponse) UnsetPriorityWeight()`

UnsetPriorityWeight ensures that no value is present for PriorityWeight, not even an explicit nil
### GetOperator

`func (o *TaskInstanceResponse) GetOperator() string`

GetOperator returns the Operator field if non-nil, zero value otherwise.

### GetOperatorOk

`func (o *TaskInstanceResponse) GetOperatorOk() (*string, bool)`

GetOperatorOk returns a tuple with the Operator field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperator

`func (o *TaskInstanceResponse) SetOperator(v string)`

SetOperator sets Operator field to given value.


### SetOperatorNil

`func (o *TaskInstanceResponse) SetOperatorNil(b bool)`

 SetOperatorNil sets the value for Operator to be an explicit nil

### UnsetOperator
`func (o *TaskInstanceResponse) UnsetOperator()`

UnsetOperator ensures that no value is present for Operator, not even an explicit nil
### GetQueuedWhen

`func (o *TaskInstanceResponse) GetQueuedWhen() time.Time`

GetQueuedWhen returns the QueuedWhen field if non-nil, zero value otherwise.

### GetQueuedWhenOk

`func (o *TaskInstanceResponse) GetQueuedWhenOk() (*time.Time, bool)`

GetQueuedWhenOk returns a tuple with the QueuedWhen field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQueuedWhen

`func (o *TaskInstanceResponse) SetQueuedWhen(v time.Time)`

SetQueuedWhen sets QueuedWhen field to given value.


### SetQueuedWhenNil

`func (o *TaskInstanceResponse) SetQueuedWhenNil(b bool)`

 SetQueuedWhenNil sets the value for QueuedWhen to be an explicit nil

### UnsetQueuedWhen
`func (o *TaskInstanceResponse) UnsetQueuedWhen()`

UnsetQueuedWhen ensures that no value is present for QueuedWhen, not even an explicit nil
### GetScheduledWhen

`func (o *TaskInstanceResponse) GetScheduledWhen() time.Time`

GetScheduledWhen returns the ScheduledWhen field if non-nil, zero value otherwise.

### GetScheduledWhenOk

`func (o *TaskInstanceResponse) GetScheduledWhenOk() (*time.Time, bool)`

GetScheduledWhenOk returns a tuple with the ScheduledWhen field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScheduledWhen

`func (o *TaskInstanceResponse) SetScheduledWhen(v time.Time)`

SetScheduledWhen sets ScheduledWhen field to given value.


### SetScheduledWhenNil

`func (o *TaskInstanceResponse) SetScheduledWhenNil(b bool)`

 SetScheduledWhenNil sets the value for ScheduledWhen to be an explicit nil

### UnsetScheduledWhen
`func (o *TaskInstanceResponse) UnsetScheduledWhen()`

UnsetScheduledWhen ensures that no value is present for ScheduledWhen, not even an explicit nil
### GetPid

`func (o *TaskInstanceResponse) GetPid() int32`

GetPid returns the Pid field if non-nil, zero value otherwise.

### GetPidOk

`func (o *TaskInstanceResponse) GetPidOk() (*int32, bool)`

GetPidOk returns a tuple with the Pid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPid

`func (o *TaskInstanceResponse) SetPid(v int32)`

SetPid sets Pid field to given value.


### SetPidNil

`func (o *TaskInstanceResponse) SetPidNil(b bool)`

 SetPidNil sets the value for Pid to be an explicit nil

### UnsetPid
`func (o *TaskInstanceResponse) UnsetPid()`

UnsetPid ensures that no value is present for Pid, not even an explicit nil
### GetExecutor

`func (o *TaskInstanceResponse) GetExecutor() string`

GetExecutor returns the Executor field if non-nil, zero value otherwise.

### GetExecutorOk

`func (o *TaskInstanceResponse) GetExecutorOk() (*string, bool)`

GetExecutorOk returns a tuple with the Executor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExecutor

`func (o *TaskInstanceResponse) SetExecutor(v string)`

SetExecutor sets Executor field to given value.


### SetExecutorNil

`func (o *TaskInstanceResponse) SetExecutorNil(b bool)`

 SetExecutorNil sets the value for Executor to be an explicit nil

### UnsetExecutor
`func (o *TaskInstanceResponse) UnsetExecutor()`

UnsetExecutor ensures that no value is present for Executor, not even an explicit nil
### GetExecutorConfig

`func (o *TaskInstanceResponse) GetExecutorConfig() string`

GetExecutorConfig returns the ExecutorConfig field if non-nil, zero value otherwise.

### GetExecutorConfigOk

`func (o *TaskInstanceResponse) GetExecutorConfigOk() (*string, bool)`

GetExecutorConfigOk returns a tuple with the ExecutorConfig field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExecutorConfig

`func (o *TaskInstanceResponse) SetExecutorConfig(v string)`

SetExecutorConfig sets ExecutorConfig field to given value.


### GetNote

`func (o *TaskInstanceResponse) GetNote() string`

GetNote returns the Note field if non-nil, zero value otherwise.

### GetNoteOk

`func (o *TaskInstanceResponse) GetNoteOk() (*string, bool)`

GetNoteOk returns a tuple with the Note field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNote

`func (o *TaskInstanceResponse) SetNote(v string)`

SetNote sets Note field to given value.


### SetNoteNil

`func (o *TaskInstanceResponse) SetNoteNil(b bool)`

 SetNoteNil sets the value for Note to be an explicit nil

### UnsetNote
`func (o *TaskInstanceResponse) UnsetNote()`

UnsetNote ensures that no value is present for Note, not even an explicit nil
### GetRenderedMapIndex

`func (o *TaskInstanceResponse) GetRenderedMapIndex() string`

GetRenderedMapIndex returns the RenderedMapIndex field if non-nil, zero value otherwise.

### GetRenderedMapIndexOk

`func (o *TaskInstanceResponse) GetRenderedMapIndexOk() (*string, bool)`

GetRenderedMapIndexOk returns a tuple with the RenderedMapIndex field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRenderedMapIndex

`func (o *TaskInstanceResponse) SetRenderedMapIndex(v string)`

SetRenderedMapIndex sets RenderedMapIndex field to given value.


### SetRenderedMapIndexNil

`func (o *TaskInstanceResponse) SetRenderedMapIndexNil(b bool)`

 SetRenderedMapIndexNil sets the value for RenderedMapIndex to be an explicit nil

### UnsetRenderedMapIndex
`func (o *TaskInstanceResponse) UnsetRenderedMapIndex()`

UnsetRenderedMapIndex ensures that no value is present for RenderedMapIndex, not even an explicit nil
### GetRenderedFields

`func (o *TaskInstanceResponse) GetRenderedFields() map[string]interface{}`

GetRenderedFields returns the RenderedFields field if non-nil, zero value otherwise.

### GetRenderedFieldsOk

`func (o *TaskInstanceResponse) GetRenderedFieldsOk() (*map[string]interface{}, bool)`

GetRenderedFieldsOk returns a tuple with the RenderedFields field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRenderedFields

`func (o *TaskInstanceResponse) SetRenderedFields(v map[string]interface{})`

SetRenderedFields sets RenderedFields field to given value.

### HasRenderedFields

`func (o *TaskInstanceResponse) HasRenderedFields() bool`

HasRenderedFields returns a boolean if a field has been set.

### GetTrigger

`func (o *TaskInstanceResponse) GetTrigger() TriggerResponse`

GetTrigger returns the Trigger field if non-nil, zero value otherwise.

### GetTriggerOk

`func (o *TaskInstanceResponse) GetTriggerOk() (*TriggerResponse, bool)`

GetTriggerOk returns a tuple with the Trigger field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrigger

`func (o *TaskInstanceResponse) SetTrigger(v TriggerResponse)`

SetTrigger sets Trigger field to given value.


### SetTriggerNil

`func (o *TaskInstanceResponse) SetTriggerNil(b bool)`

 SetTriggerNil sets the value for Trigger to be an explicit nil

### UnsetTrigger
`func (o *TaskInstanceResponse) UnsetTrigger()`

UnsetTrigger ensures that no value is present for Trigger, not even an explicit nil
### GetTriggererJob

`func (o *TaskInstanceResponse) GetTriggererJob() JobResponse`

GetTriggererJob returns the TriggererJob field if non-nil, zero value otherwise.

### GetTriggererJobOk

`func (o *TaskInstanceResponse) GetTriggererJobOk() (*JobResponse, bool)`

GetTriggererJobOk returns a tuple with the TriggererJob field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTriggererJob

`func (o *TaskInstanceResponse) SetTriggererJob(v JobResponse)`

SetTriggererJob sets TriggererJob field to given value.


### SetTriggererJobNil

`func (o *TaskInstanceResponse) SetTriggererJobNil(b bool)`

 SetTriggererJobNil sets the value for TriggererJob to be an explicit nil

### UnsetTriggererJob
`func (o *TaskInstanceResponse) UnsetTriggererJob()`

UnsetTriggererJob ensures that no value is present for TriggererJob, not even an explicit nil
### GetDagVersion

`func (o *TaskInstanceResponse) GetDagVersion() DagVersionResponse`

GetDagVersion returns the DagVersion field if non-nil, zero value otherwise.

### GetDagVersionOk

`func (o *TaskInstanceResponse) GetDagVersionOk() (*DagVersionResponse, bool)`

GetDagVersionOk returns a tuple with the DagVersion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDagVersion

`func (o *TaskInstanceResponse) SetDagVersion(v DagVersionResponse)`

SetDagVersion sets DagVersion field to given value.


### SetDagVersionNil

`func (o *TaskInstanceResponse) SetDagVersionNil(b bool)`

 SetDagVersionNil sets the value for DagVersion to be an explicit nil

### UnsetDagVersion
`func (o *TaskInstanceResponse) UnsetDagVersion()`

UnsetDagVersion ensures that no value is present for DagVersion, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


