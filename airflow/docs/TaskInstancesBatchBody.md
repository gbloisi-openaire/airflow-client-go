# TaskInstancesBatchBody

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DagIds** | Pointer to **[]string** |  | [optional] 
**DagRunIds** | Pointer to **[]string** |  | [optional] 
**TaskIds** | Pointer to **[]string** |  | [optional] 
**State** | Pointer to [**[]TaskInstanceState**](TaskInstanceState.md) |  | [optional] 
**RunAfterGte** | Pointer to **NullableTime** |  | [optional] 
**RunAfterLte** | Pointer to **NullableTime** |  | [optional] 
**LogicalDateGte** | Pointer to **NullableTime** |  | [optional] 
**LogicalDateLte** | Pointer to **NullableTime** |  | [optional] 
**StartDateGte** | Pointer to **NullableTime** |  | [optional] 
**StartDateLte** | Pointer to **NullableTime** |  | [optional] 
**EndDateGte** | Pointer to **NullableTime** |  | [optional] 
**EndDateLte** | Pointer to **NullableTime** |  | [optional] 
**DurationGte** | Pointer to **NullableFloat32** |  | [optional] 
**DurationLte** | Pointer to **NullableFloat32** |  | [optional] 
**Pool** | Pointer to **[]string** |  | [optional] 
**Queue** | Pointer to **[]string** |  | [optional] 
**Executor** | Pointer to **[]string** |  | [optional] 
**PageOffset** | Pointer to **int32** |  | [optional] [default to 0]
**PageLimit** | Pointer to **int32** |  | [optional] [default to 100]
**OrderBy** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewTaskInstancesBatchBody

`func NewTaskInstancesBatchBody() *TaskInstancesBatchBody`

NewTaskInstancesBatchBody instantiates a new TaskInstancesBatchBody object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTaskInstancesBatchBodyWithDefaults

`func NewTaskInstancesBatchBodyWithDefaults() *TaskInstancesBatchBody`

NewTaskInstancesBatchBodyWithDefaults instantiates a new TaskInstancesBatchBody object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDagIds

`func (o *TaskInstancesBatchBody) GetDagIds() []string`

GetDagIds returns the DagIds field if non-nil, zero value otherwise.

### GetDagIdsOk

`func (o *TaskInstancesBatchBody) GetDagIdsOk() (*[]string, bool)`

GetDagIdsOk returns a tuple with the DagIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDagIds

`func (o *TaskInstancesBatchBody) SetDagIds(v []string)`

SetDagIds sets DagIds field to given value.

### HasDagIds

`func (o *TaskInstancesBatchBody) HasDagIds() bool`

HasDagIds returns a boolean if a field has been set.

### SetDagIdsNil

`func (o *TaskInstancesBatchBody) SetDagIdsNil(b bool)`

 SetDagIdsNil sets the value for DagIds to be an explicit nil

### UnsetDagIds
`func (o *TaskInstancesBatchBody) UnsetDagIds()`

UnsetDagIds ensures that no value is present for DagIds, not even an explicit nil
### GetDagRunIds

`func (o *TaskInstancesBatchBody) GetDagRunIds() []string`

GetDagRunIds returns the DagRunIds field if non-nil, zero value otherwise.

### GetDagRunIdsOk

`func (o *TaskInstancesBatchBody) GetDagRunIdsOk() (*[]string, bool)`

GetDagRunIdsOk returns a tuple with the DagRunIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDagRunIds

`func (o *TaskInstancesBatchBody) SetDagRunIds(v []string)`

SetDagRunIds sets DagRunIds field to given value.

### HasDagRunIds

`func (o *TaskInstancesBatchBody) HasDagRunIds() bool`

HasDagRunIds returns a boolean if a field has been set.

### SetDagRunIdsNil

`func (o *TaskInstancesBatchBody) SetDagRunIdsNil(b bool)`

 SetDagRunIdsNil sets the value for DagRunIds to be an explicit nil

### UnsetDagRunIds
`func (o *TaskInstancesBatchBody) UnsetDagRunIds()`

UnsetDagRunIds ensures that no value is present for DagRunIds, not even an explicit nil
### GetTaskIds

`func (o *TaskInstancesBatchBody) GetTaskIds() []string`

GetTaskIds returns the TaskIds field if non-nil, zero value otherwise.

### GetTaskIdsOk

`func (o *TaskInstancesBatchBody) GetTaskIdsOk() (*[]string, bool)`

GetTaskIdsOk returns a tuple with the TaskIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaskIds

`func (o *TaskInstancesBatchBody) SetTaskIds(v []string)`

SetTaskIds sets TaskIds field to given value.

### HasTaskIds

`func (o *TaskInstancesBatchBody) HasTaskIds() bool`

HasTaskIds returns a boolean if a field has been set.

### SetTaskIdsNil

`func (o *TaskInstancesBatchBody) SetTaskIdsNil(b bool)`

 SetTaskIdsNil sets the value for TaskIds to be an explicit nil

### UnsetTaskIds
`func (o *TaskInstancesBatchBody) UnsetTaskIds()`

UnsetTaskIds ensures that no value is present for TaskIds, not even an explicit nil
### GetState

`func (o *TaskInstancesBatchBody) GetState() []TaskInstanceState`

GetState returns the State field if non-nil, zero value otherwise.

### GetStateOk

`func (o *TaskInstancesBatchBody) GetStateOk() (*[]TaskInstanceState, bool)`

GetStateOk returns a tuple with the State field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetState

`func (o *TaskInstancesBatchBody) SetState(v []TaskInstanceState)`

SetState sets State field to given value.

### HasState

`func (o *TaskInstancesBatchBody) HasState() bool`

HasState returns a boolean if a field has been set.

### SetStateNil

`func (o *TaskInstancesBatchBody) SetStateNil(b bool)`

 SetStateNil sets the value for State to be an explicit nil

### UnsetState
`func (o *TaskInstancesBatchBody) UnsetState()`

UnsetState ensures that no value is present for State, not even an explicit nil
### GetRunAfterGte

`func (o *TaskInstancesBatchBody) GetRunAfterGte() time.Time`

GetRunAfterGte returns the RunAfterGte field if non-nil, zero value otherwise.

### GetRunAfterGteOk

`func (o *TaskInstancesBatchBody) GetRunAfterGteOk() (*time.Time, bool)`

GetRunAfterGteOk returns a tuple with the RunAfterGte field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRunAfterGte

`func (o *TaskInstancesBatchBody) SetRunAfterGte(v time.Time)`

SetRunAfterGte sets RunAfterGte field to given value.

### HasRunAfterGte

`func (o *TaskInstancesBatchBody) HasRunAfterGte() bool`

HasRunAfterGte returns a boolean if a field has been set.

### SetRunAfterGteNil

`func (o *TaskInstancesBatchBody) SetRunAfterGteNil(b bool)`

 SetRunAfterGteNil sets the value for RunAfterGte to be an explicit nil

### UnsetRunAfterGte
`func (o *TaskInstancesBatchBody) UnsetRunAfterGte()`

UnsetRunAfterGte ensures that no value is present for RunAfterGte, not even an explicit nil
### GetRunAfterLte

`func (o *TaskInstancesBatchBody) GetRunAfterLte() time.Time`

GetRunAfterLte returns the RunAfterLte field if non-nil, zero value otherwise.

### GetRunAfterLteOk

`func (o *TaskInstancesBatchBody) GetRunAfterLteOk() (*time.Time, bool)`

GetRunAfterLteOk returns a tuple with the RunAfterLte field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRunAfterLte

`func (o *TaskInstancesBatchBody) SetRunAfterLte(v time.Time)`

SetRunAfterLte sets RunAfterLte field to given value.

### HasRunAfterLte

`func (o *TaskInstancesBatchBody) HasRunAfterLte() bool`

HasRunAfterLte returns a boolean if a field has been set.

### SetRunAfterLteNil

`func (o *TaskInstancesBatchBody) SetRunAfterLteNil(b bool)`

 SetRunAfterLteNil sets the value for RunAfterLte to be an explicit nil

### UnsetRunAfterLte
`func (o *TaskInstancesBatchBody) UnsetRunAfterLte()`

UnsetRunAfterLte ensures that no value is present for RunAfterLte, not even an explicit nil
### GetLogicalDateGte

`func (o *TaskInstancesBatchBody) GetLogicalDateGte() time.Time`

GetLogicalDateGte returns the LogicalDateGte field if non-nil, zero value otherwise.

### GetLogicalDateGteOk

`func (o *TaskInstancesBatchBody) GetLogicalDateGteOk() (*time.Time, bool)`

GetLogicalDateGteOk returns a tuple with the LogicalDateGte field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLogicalDateGte

`func (o *TaskInstancesBatchBody) SetLogicalDateGte(v time.Time)`

SetLogicalDateGte sets LogicalDateGte field to given value.

### HasLogicalDateGte

`func (o *TaskInstancesBatchBody) HasLogicalDateGte() bool`

HasLogicalDateGte returns a boolean if a field has been set.

### SetLogicalDateGteNil

`func (o *TaskInstancesBatchBody) SetLogicalDateGteNil(b bool)`

 SetLogicalDateGteNil sets the value for LogicalDateGte to be an explicit nil

### UnsetLogicalDateGte
`func (o *TaskInstancesBatchBody) UnsetLogicalDateGte()`

UnsetLogicalDateGte ensures that no value is present for LogicalDateGte, not even an explicit nil
### GetLogicalDateLte

`func (o *TaskInstancesBatchBody) GetLogicalDateLte() time.Time`

GetLogicalDateLte returns the LogicalDateLte field if non-nil, zero value otherwise.

### GetLogicalDateLteOk

`func (o *TaskInstancesBatchBody) GetLogicalDateLteOk() (*time.Time, bool)`

GetLogicalDateLteOk returns a tuple with the LogicalDateLte field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLogicalDateLte

`func (o *TaskInstancesBatchBody) SetLogicalDateLte(v time.Time)`

SetLogicalDateLte sets LogicalDateLte field to given value.

### HasLogicalDateLte

`func (o *TaskInstancesBatchBody) HasLogicalDateLte() bool`

HasLogicalDateLte returns a boolean if a field has been set.

### SetLogicalDateLteNil

`func (o *TaskInstancesBatchBody) SetLogicalDateLteNil(b bool)`

 SetLogicalDateLteNil sets the value for LogicalDateLte to be an explicit nil

### UnsetLogicalDateLte
`func (o *TaskInstancesBatchBody) UnsetLogicalDateLte()`

UnsetLogicalDateLte ensures that no value is present for LogicalDateLte, not even an explicit nil
### GetStartDateGte

`func (o *TaskInstancesBatchBody) GetStartDateGte() time.Time`

GetStartDateGte returns the StartDateGte field if non-nil, zero value otherwise.

### GetStartDateGteOk

`func (o *TaskInstancesBatchBody) GetStartDateGteOk() (*time.Time, bool)`

GetStartDateGteOk returns a tuple with the StartDateGte field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartDateGte

`func (o *TaskInstancesBatchBody) SetStartDateGte(v time.Time)`

SetStartDateGte sets StartDateGte field to given value.

### HasStartDateGte

`func (o *TaskInstancesBatchBody) HasStartDateGte() bool`

HasStartDateGte returns a boolean if a field has been set.

### SetStartDateGteNil

`func (o *TaskInstancesBatchBody) SetStartDateGteNil(b bool)`

 SetStartDateGteNil sets the value for StartDateGte to be an explicit nil

### UnsetStartDateGte
`func (o *TaskInstancesBatchBody) UnsetStartDateGte()`

UnsetStartDateGte ensures that no value is present for StartDateGte, not even an explicit nil
### GetStartDateLte

`func (o *TaskInstancesBatchBody) GetStartDateLte() time.Time`

GetStartDateLte returns the StartDateLte field if non-nil, zero value otherwise.

### GetStartDateLteOk

`func (o *TaskInstancesBatchBody) GetStartDateLteOk() (*time.Time, bool)`

GetStartDateLteOk returns a tuple with the StartDateLte field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartDateLte

`func (o *TaskInstancesBatchBody) SetStartDateLte(v time.Time)`

SetStartDateLte sets StartDateLte field to given value.

### HasStartDateLte

`func (o *TaskInstancesBatchBody) HasStartDateLte() bool`

HasStartDateLte returns a boolean if a field has been set.

### SetStartDateLteNil

`func (o *TaskInstancesBatchBody) SetStartDateLteNil(b bool)`

 SetStartDateLteNil sets the value for StartDateLte to be an explicit nil

### UnsetStartDateLte
`func (o *TaskInstancesBatchBody) UnsetStartDateLte()`

UnsetStartDateLte ensures that no value is present for StartDateLte, not even an explicit nil
### GetEndDateGte

`func (o *TaskInstancesBatchBody) GetEndDateGte() time.Time`

GetEndDateGte returns the EndDateGte field if non-nil, zero value otherwise.

### GetEndDateGteOk

`func (o *TaskInstancesBatchBody) GetEndDateGteOk() (*time.Time, bool)`

GetEndDateGteOk returns a tuple with the EndDateGte field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEndDateGte

`func (o *TaskInstancesBatchBody) SetEndDateGte(v time.Time)`

SetEndDateGte sets EndDateGte field to given value.

### HasEndDateGte

`func (o *TaskInstancesBatchBody) HasEndDateGte() bool`

HasEndDateGte returns a boolean if a field has been set.

### SetEndDateGteNil

`func (o *TaskInstancesBatchBody) SetEndDateGteNil(b bool)`

 SetEndDateGteNil sets the value for EndDateGte to be an explicit nil

### UnsetEndDateGte
`func (o *TaskInstancesBatchBody) UnsetEndDateGte()`

UnsetEndDateGte ensures that no value is present for EndDateGte, not even an explicit nil
### GetEndDateLte

`func (o *TaskInstancesBatchBody) GetEndDateLte() time.Time`

GetEndDateLte returns the EndDateLte field if non-nil, zero value otherwise.

### GetEndDateLteOk

`func (o *TaskInstancesBatchBody) GetEndDateLteOk() (*time.Time, bool)`

GetEndDateLteOk returns a tuple with the EndDateLte field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEndDateLte

`func (o *TaskInstancesBatchBody) SetEndDateLte(v time.Time)`

SetEndDateLte sets EndDateLte field to given value.

### HasEndDateLte

`func (o *TaskInstancesBatchBody) HasEndDateLte() bool`

HasEndDateLte returns a boolean if a field has been set.

### SetEndDateLteNil

`func (o *TaskInstancesBatchBody) SetEndDateLteNil(b bool)`

 SetEndDateLteNil sets the value for EndDateLte to be an explicit nil

### UnsetEndDateLte
`func (o *TaskInstancesBatchBody) UnsetEndDateLte()`

UnsetEndDateLte ensures that no value is present for EndDateLte, not even an explicit nil
### GetDurationGte

`func (o *TaskInstancesBatchBody) GetDurationGte() float32`

GetDurationGte returns the DurationGte field if non-nil, zero value otherwise.

### GetDurationGteOk

`func (o *TaskInstancesBatchBody) GetDurationGteOk() (*float32, bool)`

GetDurationGteOk returns a tuple with the DurationGte field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDurationGte

`func (o *TaskInstancesBatchBody) SetDurationGte(v float32)`

SetDurationGte sets DurationGte field to given value.

### HasDurationGte

`func (o *TaskInstancesBatchBody) HasDurationGte() bool`

HasDurationGte returns a boolean if a field has been set.

### SetDurationGteNil

`func (o *TaskInstancesBatchBody) SetDurationGteNil(b bool)`

 SetDurationGteNil sets the value for DurationGte to be an explicit nil

### UnsetDurationGte
`func (o *TaskInstancesBatchBody) UnsetDurationGte()`

UnsetDurationGte ensures that no value is present for DurationGte, not even an explicit nil
### GetDurationLte

`func (o *TaskInstancesBatchBody) GetDurationLte() float32`

GetDurationLte returns the DurationLte field if non-nil, zero value otherwise.

### GetDurationLteOk

`func (o *TaskInstancesBatchBody) GetDurationLteOk() (*float32, bool)`

GetDurationLteOk returns a tuple with the DurationLte field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDurationLte

`func (o *TaskInstancesBatchBody) SetDurationLte(v float32)`

SetDurationLte sets DurationLte field to given value.

### HasDurationLte

`func (o *TaskInstancesBatchBody) HasDurationLte() bool`

HasDurationLte returns a boolean if a field has been set.

### SetDurationLteNil

`func (o *TaskInstancesBatchBody) SetDurationLteNil(b bool)`

 SetDurationLteNil sets the value for DurationLte to be an explicit nil

### UnsetDurationLte
`func (o *TaskInstancesBatchBody) UnsetDurationLte()`

UnsetDurationLte ensures that no value is present for DurationLte, not even an explicit nil
### GetPool

`func (o *TaskInstancesBatchBody) GetPool() []string`

GetPool returns the Pool field if non-nil, zero value otherwise.

### GetPoolOk

`func (o *TaskInstancesBatchBody) GetPoolOk() (*[]string, bool)`

GetPoolOk returns a tuple with the Pool field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPool

`func (o *TaskInstancesBatchBody) SetPool(v []string)`

SetPool sets Pool field to given value.

### HasPool

`func (o *TaskInstancesBatchBody) HasPool() bool`

HasPool returns a boolean if a field has been set.

### SetPoolNil

`func (o *TaskInstancesBatchBody) SetPoolNil(b bool)`

 SetPoolNil sets the value for Pool to be an explicit nil

### UnsetPool
`func (o *TaskInstancesBatchBody) UnsetPool()`

UnsetPool ensures that no value is present for Pool, not even an explicit nil
### GetQueue

`func (o *TaskInstancesBatchBody) GetQueue() []string`

GetQueue returns the Queue field if non-nil, zero value otherwise.

### GetQueueOk

`func (o *TaskInstancesBatchBody) GetQueueOk() (*[]string, bool)`

GetQueueOk returns a tuple with the Queue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQueue

`func (o *TaskInstancesBatchBody) SetQueue(v []string)`

SetQueue sets Queue field to given value.

### HasQueue

`func (o *TaskInstancesBatchBody) HasQueue() bool`

HasQueue returns a boolean if a field has been set.

### SetQueueNil

`func (o *TaskInstancesBatchBody) SetQueueNil(b bool)`

 SetQueueNil sets the value for Queue to be an explicit nil

### UnsetQueue
`func (o *TaskInstancesBatchBody) UnsetQueue()`

UnsetQueue ensures that no value is present for Queue, not even an explicit nil
### GetExecutor

`func (o *TaskInstancesBatchBody) GetExecutor() []string`

GetExecutor returns the Executor field if non-nil, zero value otherwise.

### GetExecutorOk

`func (o *TaskInstancesBatchBody) GetExecutorOk() (*[]string, bool)`

GetExecutorOk returns a tuple with the Executor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExecutor

`func (o *TaskInstancesBatchBody) SetExecutor(v []string)`

SetExecutor sets Executor field to given value.

### HasExecutor

`func (o *TaskInstancesBatchBody) HasExecutor() bool`

HasExecutor returns a boolean if a field has been set.

### SetExecutorNil

`func (o *TaskInstancesBatchBody) SetExecutorNil(b bool)`

 SetExecutorNil sets the value for Executor to be an explicit nil

### UnsetExecutor
`func (o *TaskInstancesBatchBody) UnsetExecutor()`

UnsetExecutor ensures that no value is present for Executor, not even an explicit nil
### GetPageOffset

`func (o *TaskInstancesBatchBody) GetPageOffset() int32`

GetPageOffset returns the PageOffset field if non-nil, zero value otherwise.

### GetPageOffsetOk

`func (o *TaskInstancesBatchBody) GetPageOffsetOk() (*int32, bool)`

GetPageOffsetOk returns a tuple with the PageOffset field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPageOffset

`func (o *TaskInstancesBatchBody) SetPageOffset(v int32)`

SetPageOffset sets PageOffset field to given value.

### HasPageOffset

`func (o *TaskInstancesBatchBody) HasPageOffset() bool`

HasPageOffset returns a boolean if a field has been set.

### GetPageLimit

`func (o *TaskInstancesBatchBody) GetPageLimit() int32`

GetPageLimit returns the PageLimit field if non-nil, zero value otherwise.

### GetPageLimitOk

`func (o *TaskInstancesBatchBody) GetPageLimitOk() (*int32, bool)`

GetPageLimitOk returns a tuple with the PageLimit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPageLimit

`func (o *TaskInstancesBatchBody) SetPageLimit(v int32)`

SetPageLimit sets PageLimit field to given value.

### HasPageLimit

`func (o *TaskInstancesBatchBody) HasPageLimit() bool`

HasPageLimit returns a boolean if a field has been set.

### GetOrderBy

`func (o *TaskInstancesBatchBody) GetOrderBy() string`

GetOrderBy returns the OrderBy field if non-nil, zero value otherwise.

### GetOrderByOk

`func (o *TaskInstancesBatchBody) GetOrderByOk() (*string, bool)`

GetOrderByOk returns a tuple with the OrderBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrderBy

`func (o *TaskInstancesBatchBody) SetOrderBy(v string)`

SetOrderBy sets OrderBy field to given value.

### HasOrderBy

`func (o *TaskInstancesBatchBody) HasOrderBy() bool`

HasOrderBy returns a boolean if a field has been set.

### SetOrderByNil

`func (o *TaskInstancesBatchBody) SetOrderByNil(b bool)`

 SetOrderByNil sets the value for OrderBy to be an explicit nil

### UnsetOrderBy
`func (o *TaskInstancesBatchBody) UnsetOrderBy()`

UnsetOrderBy ensures that no value is present for OrderBy, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


