# ClearTaskInstancesBody

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DryRun** | Pointer to **bool** |  | [optional] [default to true]
**StartDate** | Pointer to **NullableTime** |  | [optional] 
**EndDate** | Pointer to **NullableTime** |  | [optional] 
**OnlyFailed** | Pointer to **bool** |  | [optional] [default to true]
**OnlyRunning** | Pointer to **bool** |  | [optional] [default to false]
**ResetDagRuns** | Pointer to **bool** |  | [optional] [default to true]
**TaskIds** | Pointer to [**[]ClearTaskInstancesBodyTaskIdsInner**](ClearTaskInstancesBodyTaskIdsInner.md) |  | [optional] 
**DagRunId** | Pointer to **NullableString** |  | [optional] 
**IncludeUpstream** | Pointer to **bool** |  | [optional] [default to false]
**IncludeDownstream** | Pointer to **bool** |  | [optional] [default to false]
**IncludeFuture** | Pointer to **bool** |  | [optional] [default to false]
**IncludePast** | Pointer to **bool** |  | [optional] [default to false]

## Methods

### NewClearTaskInstancesBody

`func NewClearTaskInstancesBody() *ClearTaskInstancesBody`

NewClearTaskInstancesBody instantiates a new ClearTaskInstancesBody object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewClearTaskInstancesBodyWithDefaults

`func NewClearTaskInstancesBodyWithDefaults() *ClearTaskInstancesBody`

NewClearTaskInstancesBodyWithDefaults instantiates a new ClearTaskInstancesBody object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDryRun

`func (o *ClearTaskInstancesBody) GetDryRun() bool`

GetDryRun returns the DryRun field if non-nil, zero value otherwise.

### GetDryRunOk

`func (o *ClearTaskInstancesBody) GetDryRunOk() (*bool, bool)`

GetDryRunOk returns a tuple with the DryRun field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDryRun

`func (o *ClearTaskInstancesBody) SetDryRun(v bool)`

SetDryRun sets DryRun field to given value.

### HasDryRun

`func (o *ClearTaskInstancesBody) HasDryRun() bool`

HasDryRun returns a boolean if a field has been set.

### GetStartDate

`func (o *ClearTaskInstancesBody) GetStartDate() time.Time`

GetStartDate returns the StartDate field if non-nil, zero value otherwise.

### GetStartDateOk

`func (o *ClearTaskInstancesBody) GetStartDateOk() (*time.Time, bool)`

GetStartDateOk returns a tuple with the StartDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartDate

`func (o *ClearTaskInstancesBody) SetStartDate(v time.Time)`

SetStartDate sets StartDate field to given value.

### HasStartDate

`func (o *ClearTaskInstancesBody) HasStartDate() bool`

HasStartDate returns a boolean if a field has been set.

### SetStartDateNil

`func (o *ClearTaskInstancesBody) SetStartDateNil(b bool)`

 SetStartDateNil sets the value for StartDate to be an explicit nil

### UnsetStartDate
`func (o *ClearTaskInstancesBody) UnsetStartDate()`

UnsetStartDate ensures that no value is present for StartDate, not even an explicit nil
### GetEndDate

`func (o *ClearTaskInstancesBody) GetEndDate() time.Time`

GetEndDate returns the EndDate field if non-nil, zero value otherwise.

### GetEndDateOk

`func (o *ClearTaskInstancesBody) GetEndDateOk() (*time.Time, bool)`

GetEndDateOk returns a tuple with the EndDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEndDate

`func (o *ClearTaskInstancesBody) SetEndDate(v time.Time)`

SetEndDate sets EndDate field to given value.

### HasEndDate

`func (o *ClearTaskInstancesBody) HasEndDate() bool`

HasEndDate returns a boolean if a field has been set.

### SetEndDateNil

`func (o *ClearTaskInstancesBody) SetEndDateNil(b bool)`

 SetEndDateNil sets the value for EndDate to be an explicit nil

### UnsetEndDate
`func (o *ClearTaskInstancesBody) UnsetEndDate()`

UnsetEndDate ensures that no value is present for EndDate, not even an explicit nil
### GetOnlyFailed

`func (o *ClearTaskInstancesBody) GetOnlyFailed() bool`

GetOnlyFailed returns the OnlyFailed field if non-nil, zero value otherwise.

### GetOnlyFailedOk

`func (o *ClearTaskInstancesBody) GetOnlyFailedOk() (*bool, bool)`

GetOnlyFailedOk returns a tuple with the OnlyFailed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOnlyFailed

`func (o *ClearTaskInstancesBody) SetOnlyFailed(v bool)`

SetOnlyFailed sets OnlyFailed field to given value.

### HasOnlyFailed

`func (o *ClearTaskInstancesBody) HasOnlyFailed() bool`

HasOnlyFailed returns a boolean if a field has been set.

### GetOnlyRunning

`func (o *ClearTaskInstancesBody) GetOnlyRunning() bool`

GetOnlyRunning returns the OnlyRunning field if non-nil, zero value otherwise.

### GetOnlyRunningOk

`func (o *ClearTaskInstancesBody) GetOnlyRunningOk() (*bool, bool)`

GetOnlyRunningOk returns a tuple with the OnlyRunning field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOnlyRunning

`func (o *ClearTaskInstancesBody) SetOnlyRunning(v bool)`

SetOnlyRunning sets OnlyRunning field to given value.

### HasOnlyRunning

`func (o *ClearTaskInstancesBody) HasOnlyRunning() bool`

HasOnlyRunning returns a boolean if a field has been set.

### GetResetDagRuns

`func (o *ClearTaskInstancesBody) GetResetDagRuns() bool`

GetResetDagRuns returns the ResetDagRuns field if non-nil, zero value otherwise.

### GetResetDagRunsOk

`func (o *ClearTaskInstancesBody) GetResetDagRunsOk() (*bool, bool)`

GetResetDagRunsOk returns a tuple with the ResetDagRuns field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResetDagRuns

`func (o *ClearTaskInstancesBody) SetResetDagRuns(v bool)`

SetResetDagRuns sets ResetDagRuns field to given value.

### HasResetDagRuns

`func (o *ClearTaskInstancesBody) HasResetDagRuns() bool`

HasResetDagRuns returns a boolean if a field has been set.

### GetTaskIds

`func (o *ClearTaskInstancesBody) GetTaskIds() []ClearTaskInstancesBodyTaskIdsInner`

GetTaskIds returns the TaskIds field if non-nil, zero value otherwise.

### GetTaskIdsOk

`func (o *ClearTaskInstancesBody) GetTaskIdsOk() (*[]ClearTaskInstancesBodyTaskIdsInner, bool)`

GetTaskIdsOk returns a tuple with the TaskIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaskIds

`func (o *ClearTaskInstancesBody) SetTaskIds(v []ClearTaskInstancesBodyTaskIdsInner)`

SetTaskIds sets TaskIds field to given value.

### HasTaskIds

`func (o *ClearTaskInstancesBody) HasTaskIds() bool`

HasTaskIds returns a boolean if a field has been set.

### SetTaskIdsNil

`func (o *ClearTaskInstancesBody) SetTaskIdsNil(b bool)`

 SetTaskIdsNil sets the value for TaskIds to be an explicit nil

### UnsetTaskIds
`func (o *ClearTaskInstancesBody) UnsetTaskIds()`

UnsetTaskIds ensures that no value is present for TaskIds, not even an explicit nil
### GetDagRunId

`func (o *ClearTaskInstancesBody) GetDagRunId() string`

GetDagRunId returns the DagRunId field if non-nil, zero value otherwise.

### GetDagRunIdOk

`func (o *ClearTaskInstancesBody) GetDagRunIdOk() (*string, bool)`

GetDagRunIdOk returns a tuple with the DagRunId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDagRunId

`func (o *ClearTaskInstancesBody) SetDagRunId(v string)`

SetDagRunId sets DagRunId field to given value.

### HasDagRunId

`func (o *ClearTaskInstancesBody) HasDagRunId() bool`

HasDagRunId returns a boolean if a field has been set.

### SetDagRunIdNil

`func (o *ClearTaskInstancesBody) SetDagRunIdNil(b bool)`

 SetDagRunIdNil sets the value for DagRunId to be an explicit nil

### UnsetDagRunId
`func (o *ClearTaskInstancesBody) UnsetDagRunId()`

UnsetDagRunId ensures that no value is present for DagRunId, not even an explicit nil
### GetIncludeUpstream

`func (o *ClearTaskInstancesBody) GetIncludeUpstream() bool`

GetIncludeUpstream returns the IncludeUpstream field if non-nil, zero value otherwise.

### GetIncludeUpstreamOk

`func (o *ClearTaskInstancesBody) GetIncludeUpstreamOk() (*bool, bool)`

GetIncludeUpstreamOk returns a tuple with the IncludeUpstream field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIncludeUpstream

`func (o *ClearTaskInstancesBody) SetIncludeUpstream(v bool)`

SetIncludeUpstream sets IncludeUpstream field to given value.

### HasIncludeUpstream

`func (o *ClearTaskInstancesBody) HasIncludeUpstream() bool`

HasIncludeUpstream returns a boolean if a field has been set.

### GetIncludeDownstream

`func (o *ClearTaskInstancesBody) GetIncludeDownstream() bool`

GetIncludeDownstream returns the IncludeDownstream field if non-nil, zero value otherwise.

### GetIncludeDownstreamOk

`func (o *ClearTaskInstancesBody) GetIncludeDownstreamOk() (*bool, bool)`

GetIncludeDownstreamOk returns a tuple with the IncludeDownstream field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIncludeDownstream

`func (o *ClearTaskInstancesBody) SetIncludeDownstream(v bool)`

SetIncludeDownstream sets IncludeDownstream field to given value.

### HasIncludeDownstream

`func (o *ClearTaskInstancesBody) HasIncludeDownstream() bool`

HasIncludeDownstream returns a boolean if a field has been set.

### GetIncludeFuture

`func (o *ClearTaskInstancesBody) GetIncludeFuture() bool`

GetIncludeFuture returns the IncludeFuture field if non-nil, zero value otherwise.

### GetIncludeFutureOk

`func (o *ClearTaskInstancesBody) GetIncludeFutureOk() (*bool, bool)`

GetIncludeFutureOk returns a tuple with the IncludeFuture field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIncludeFuture

`func (o *ClearTaskInstancesBody) SetIncludeFuture(v bool)`

SetIncludeFuture sets IncludeFuture field to given value.

### HasIncludeFuture

`func (o *ClearTaskInstancesBody) HasIncludeFuture() bool`

HasIncludeFuture returns a boolean if a field has been set.

### GetIncludePast

`func (o *ClearTaskInstancesBody) GetIncludePast() bool`

GetIncludePast returns the IncludePast field if non-nil, zero value otherwise.

### GetIncludePastOk

`func (o *ClearTaskInstancesBody) GetIncludePastOk() (*bool, bool)`

GetIncludePastOk returns a tuple with the IncludePast field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIncludePast

`func (o *ClearTaskInstancesBody) SetIncludePast(v bool)`

SetIncludePast sets IncludePast field to given value.

### HasIncludePast

`func (o *ClearTaskInstancesBody) HasIncludePast() bool`

HasIncludePast returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


