# ResponseClearDagRun

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**TaskInstances** | [**[]TaskInstanceResponse**](TaskInstanceResponse.md) |  | 
**TotalEntries** | **int32** |  | 
**DagRunId** | **string** |  | 
**DagId** | **string** |  | 
**LogicalDate** | **time.Time** |  | 
**QueuedAt** | **time.Time** |  | 
**StartDate** | **time.Time** |  | 
**EndDate** | **time.Time** |  | 
**Duration** | **float32** |  | 
**DataIntervalStart** | **time.Time** |  | 
**DataIntervalEnd** | **time.Time** |  | 
**RunAfter** | **time.Time** |  | 
**LastSchedulingDecision** | **time.Time** |  | 
**RunType** | [**DagRunType**](DagRunType.md) |  | 
**State** | [**DagRunState**](DagRunState.md) |  | 
**TriggeredBy** | [**DagRunTriggeredByType**](DagRunTriggeredByType.md) |  | 
**Conf** | **map[string]interface{}** |  | 
**Note** | **string** |  | 
**DagVersions** | [**[]DagVersionResponse**](DagVersionResponse.md) |  | 
**BundleVersion** | **string** |  | 
**DagDisplayName** | **string** |  | 

## Methods

### NewResponseClearDagRun

`func NewResponseClearDagRun(taskInstances []TaskInstanceResponse, totalEntries int32, dagRunId string, dagId string, logicalDate time.Time, queuedAt time.Time, startDate time.Time, endDate time.Time, duration float32, dataIntervalStart time.Time, dataIntervalEnd time.Time, runAfter time.Time, lastSchedulingDecision time.Time, runType DagRunType, state DagRunState, triggeredBy DagRunTriggeredByType, conf map[string]interface{}, note string, dagVersions []DagVersionResponse, bundleVersion string, dagDisplayName string, ) *ResponseClearDagRun`

NewResponseClearDagRun instantiates a new ResponseClearDagRun object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewResponseClearDagRunWithDefaults

`func NewResponseClearDagRunWithDefaults() *ResponseClearDagRun`

NewResponseClearDagRunWithDefaults instantiates a new ResponseClearDagRun object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTaskInstances

`func (o *ResponseClearDagRun) GetTaskInstances() []TaskInstanceResponse`

GetTaskInstances returns the TaskInstances field if non-nil, zero value otherwise.

### GetTaskInstancesOk

`func (o *ResponseClearDagRun) GetTaskInstancesOk() (*[]TaskInstanceResponse, bool)`

GetTaskInstancesOk returns a tuple with the TaskInstances field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaskInstances

`func (o *ResponseClearDagRun) SetTaskInstances(v []TaskInstanceResponse)`

SetTaskInstances sets TaskInstances field to given value.


### GetTotalEntries

`func (o *ResponseClearDagRun) GetTotalEntries() int32`

GetTotalEntries returns the TotalEntries field if non-nil, zero value otherwise.

### GetTotalEntriesOk

`func (o *ResponseClearDagRun) GetTotalEntriesOk() (*int32, bool)`

GetTotalEntriesOk returns a tuple with the TotalEntries field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalEntries

`func (o *ResponseClearDagRun) SetTotalEntries(v int32)`

SetTotalEntries sets TotalEntries field to given value.


### GetDagRunId

`func (o *ResponseClearDagRun) GetDagRunId() string`

GetDagRunId returns the DagRunId field if non-nil, zero value otherwise.

### GetDagRunIdOk

`func (o *ResponseClearDagRun) GetDagRunIdOk() (*string, bool)`

GetDagRunIdOk returns a tuple with the DagRunId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDagRunId

`func (o *ResponseClearDagRun) SetDagRunId(v string)`

SetDagRunId sets DagRunId field to given value.


### GetDagId

`func (o *ResponseClearDagRun) GetDagId() string`

GetDagId returns the DagId field if non-nil, zero value otherwise.

### GetDagIdOk

`func (o *ResponseClearDagRun) GetDagIdOk() (*string, bool)`

GetDagIdOk returns a tuple with the DagId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDagId

`func (o *ResponseClearDagRun) SetDagId(v string)`

SetDagId sets DagId field to given value.


### GetLogicalDate

`func (o *ResponseClearDagRun) GetLogicalDate() time.Time`

GetLogicalDate returns the LogicalDate field if non-nil, zero value otherwise.

### GetLogicalDateOk

`func (o *ResponseClearDagRun) GetLogicalDateOk() (*time.Time, bool)`

GetLogicalDateOk returns a tuple with the LogicalDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLogicalDate

`func (o *ResponseClearDagRun) SetLogicalDate(v time.Time)`

SetLogicalDate sets LogicalDate field to given value.


### GetQueuedAt

`func (o *ResponseClearDagRun) GetQueuedAt() time.Time`

GetQueuedAt returns the QueuedAt field if non-nil, zero value otherwise.

### GetQueuedAtOk

`func (o *ResponseClearDagRun) GetQueuedAtOk() (*time.Time, bool)`

GetQueuedAtOk returns a tuple with the QueuedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQueuedAt

`func (o *ResponseClearDagRun) SetQueuedAt(v time.Time)`

SetQueuedAt sets QueuedAt field to given value.


### GetStartDate

`func (o *ResponseClearDagRun) GetStartDate() time.Time`

GetStartDate returns the StartDate field if non-nil, zero value otherwise.

### GetStartDateOk

`func (o *ResponseClearDagRun) GetStartDateOk() (*time.Time, bool)`

GetStartDateOk returns a tuple with the StartDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartDate

`func (o *ResponseClearDagRun) SetStartDate(v time.Time)`

SetStartDate sets StartDate field to given value.


### GetEndDate

`func (o *ResponseClearDagRun) GetEndDate() time.Time`

GetEndDate returns the EndDate field if non-nil, zero value otherwise.

### GetEndDateOk

`func (o *ResponseClearDagRun) GetEndDateOk() (*time.Time, bool)`

GetEndDateOk returns a tuple with the EndDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEndDate

`func (o *ResponseClearDagRun) SetEndDate(v time.Time)`

SetEndDate sets EndDate field to given value.


### GetDuration

`func (o *ResponseClearDagRun) GetDuration() float32`

GetDuration returns the Duration field if non-nil, zero value otherwise.

### GetDurationOk

`func (o *ResponseClearDagRun) GetDurationOk() (*float32, bool)`

GetDurationOk returns a tuple with the Duration field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDuration

`func (o *ResponseClearDagRun) SetDuration(v float32)`

SetDuration sets Duration field to given value.


### GetDataIntervalStart

`func (o *ResponseClearDagRun) GetDataIntervalStart() time.Time`

GetDataIntervalStart returns the DataIntervalStart field if non-nil, zero value otherwise.

### GetDataIntervalStartOk

`func (o *ResponseClearDagRun) GetDataIntervalStartOk() (*time.Time, bool)`

GetDataIntervalStartOk returns a tuple with the DataIntervalStart field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDataIntervalStart

`func (o *ResponseClearDagRun) SetDataIntervalStart(v time.Time)`

SetDataIntervalStart sets DataIntervalStart field to given value.


### GetDataIntervalEnd

`func (o *ResponseClearDagRun) GetDataIntervalEnd() time.Time`

GetDataIntervalEnd returns the DataIntervalEnd field if non-nil, zero value otherwise.

### GetDataIntervalEndOk

`func (o *ResponseClearDagRun) GetDataIntervalEndOk() (*time.Time, bool)`

GetDataIntervalEndOk returns a tuple with the DataIntervalEnd field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDataIntervalEnd

`func (o *ResponseClearDagRun) SetDataIntervalEnd(v time.Time)`

SetDataIntervalEnd sets DataIntervalEnd field to given value.


### GetRunAfter

`func (o *ResponseClearDagRun) GetRunAfter() time.Time`

GetRunAfter returns the RunAfter field if non-nil, zero value otherwise.

### GetRunAfterOk

`func (o *ResponseClearDagRun) GetRunAfterOk() (*time.Time, bool)`

GetRunAfterOk returns a tuple with the RunAfter field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRunAfter

`func (o *ResponseClearDagRun) SetRunAfter(v time.Time)`

SetRunAfter sets RunAfter field to given value.


### GetLastSchedulingDecision

`func (o *ResponseClearDagRun) GetLastSchedulingDecision() time.Time`

GetLastSchedulingDecision returns the LastSchedulingDecision field if non-nil, zero value otherwise.

### GetLastSchedulingDecisionOk

`func (o *ResponseClearDagRun) GetLastSchedulingDecisionOk() (*time.Time, bool)`

GetLastSchedulingDecisionOk returns a tuple with the LastSchedulingDecision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastSchedulingDecision

`func (o *ResponseClearDagRun) SetLastSchedulingDecision(v time.Time)`

SetLastSchedulingDecision sets LastSchedulingDecision field to given value.


### GetRunType

`func (o *ResponseClearDagRun) GetRunType() DagRunType`

GetRunType returns the RunType field if non-nil, zero value otherwise.

### GetRunTypeOk

`func (o *ResponseClearDagRun) GetRunTypeOk() (*DagRunType, bool)`

GetRunTypeOk returns a tuple with the RunType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRunType

`func (o *ResponseClearDagRun) SetRunType(v DagRunType)`

SetRunType sets RunType field to given value.


### GetState

`func (o *ResponseClearDagRun) GetState() DagRunState`

GetState returns the State field if non-nil, zero value otherwise.

### GetStateOk

`func (o *ResponseClearDagRun) GetStateOk() (*DagRunState, bool)`

GetStateOk returns a tuple with the State field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetState

`func (o *ResponseClearDagRun) SetState(v DagRunState)`

SetState sets State field to given value.


### GetTriggeredBy

`func (o *ResponseClearDagRun) GetTriggeredBy() DagRunTriggeredByType`

GetTriggeredBy returns the TriggeredBy field if non-nil, zero value otherwise.

### GetTriggeredByOk

`func (o *ResponseClearDagRun) GetTriggeredByOk() (*DagRunTriggeredByType, bool)`

GetTriggeredByOk returns a tuple with the TriggeredBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTriggeredBy

`func (o *ResponseClearDagRun) SetTriggeredBy(v DagRunTriggeredByType)`

SetTriggeredBy sets TriggeredBy field to given value.


### GetConf

`func (o *ResponseClearDagRun) GetConf() map[string]interface{}`

GetConf returns the Conf field if non-nil, zero value otherwise.

### GetConfOk

`func (o *ResponseClearDagRun) GetConfOk() (*map[string]interface{}, bool)`

GetConfOk returns a tuple with the Conf field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConf

`func (o *ResponseClearDagRun) SetConf(v map[string]interface{})`

SetConf sets Conf field to given value.


### GetNote

`func (o *ResponseClearDagRun) GetNote() string`

GetNote returns the Note field if non-nil, zero value otherwise.

### GetNoteOk

`func (o *ResponseClearDagRun) GetNoteOk() (*string, bool)`

GetNoteOk returns a tuple with the Note field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNote

`func (o *ResponseClearDagRun) SetNote(v string)`

SetNote sets Note field to given value.


### GetDagVersions

`func (o *ResponseClearDagRun) GetDagVersions() []DagVersionResponse`

GetDagVersions returns the DagVersions field if non-nil, zero value otherwise.

### GetDagVersionsOk

`func (o *ResponseClearDagRun) GetDagVersionsOk() (*[]DagVersionResponse, bool)`

GetDagVersionsOk returns a tuple with the DagVersions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDagVersions

`func (o *ResponseClearDagRun) SetDagVersions(v []DagVersionResponse)`

SetDagVersions sets DagVersions field to given value.


### GetBundleVersion

`func (o *ResponseClearDagRun) GetBundleVersion() string`

GetBundleVersion returns the BundleVersion field if non-nil, zero value otherwise.

### GetBundleVersionOk

`func (o *ResponseClearDagRun) GetBundleVersionOk() (*string, bool)`

GetBundleVersionOk returns a tuple with the BundleVersion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBundleVersion

`func (o *ResponseClearDagRun) SetBundleVersion(v string)`

SetBundleVersion sets BundleVersion field to given value.


### GetDagDisplayName

`func (o *ResponseClearDagRun) GetDagDisplayName() string`

GetDagDisplayName returns the DagDisplayName field if non-nil, zero value otherwise.

### GetDagDisplayNameOk

`func (o *ResponseClearDagRun) GetDagDisplayNameOk() (*string, bool)`

GetDagDisplayNameOk returns a tuple with the DagDisplayName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDagDisplayName

`func (o *ResponseClearDagRun) SetDagDisplayName(v string)`

SetDagDisplayName sets DagDisplayName field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


