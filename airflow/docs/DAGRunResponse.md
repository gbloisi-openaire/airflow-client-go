# DAGRunResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DagRunId** | **string** |  | 
**DagId** | **string** |  | 
**LogicalDate** | **NullableTime** |  | 
**QueuedAt** | **NullableTime** |  | 
**StartDate** | **NullableTime** |  | 
**EndDate** | **NullableTime** |  | 
**Duration** | **NullableFloat32** |  | 
**DataIntervalStart** | **NullableTime** |  | 
**DataIntervalEnd** | **NullableTime** |  | 
**RunAfter** | **time.Time** |  | 
**LastSchedulingDecision** | **NullableTime** |  | 
**RunType** | [**DagRunType**](DagRunType.md) |  | 
**State** | [**DagRunState**](DagRunState.md) |  | 
**TriggeredBy** | [**NullableDagRunTriggeredByType**](DagRunTriggeredByType.md) |  | 
**Conf** | **map[string]interface{}** |  | 
**Note** | **NullableString** |  | 
**DagVersions** | [**[]DagVersionResponse**](DagVersionResponse.md) |  | 
**BundleVersion** | **NullableString** |  | 
**DagDisplayName** | **string** |  | 

## Methods

### NewDAGRunResponse

`func NewDAGRunResponse(dagRunId string, dagId string, logicalDate NullableTime, queuedAt NullableTime, startDate NullableTime, endDate NullableTime, duration NullableFloat32, dataIntervalStart NullableTime, dataIntervalEnd NullableTime, runAfter time.Time, lastSchedulingDecision NullableTime, runType DagRunType, state DagRunState, triggeredBy NullableDagRunTriggeredByType, conf map[string]interface{}, note NullableString, dagVersions []DagVersionResponse, bundleVersion NullableString, dagDisplayName string, ) *DAGRunResponse`

NewDAGRunResponse instantiates a new DAGRunResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDAGRunResponseWithDefaults

`func NewDAGRunResponseWithDefaults() *DAGRunResponse`

NewDAGRunResponseWithDefaults instantiates a new DAGRunResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDagRunId

`func (o *DAGRunResponse) GetDagRunId() string`

GetDagRunId returns the DagRunId field if non-nil, zero value otherwise.

### GetDagRunIdOk

`func (o *DAGRunResponse) GetDagRunIdOk() (*string, bool)`

GetDagRunIdOk returns a tuple with the DagRunId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDagRunId

`func (o *DAGRunResponse) SetDagRunId(v string)`

SetDagRunId sets DagRunId field to given value.


### GetDagId

`func (o *DAGRunResponse) GetDagId() string`

GetDagId returns the DagId field if non-nil, zero value otherwise.

### GetDagIdOk

`func (o *DAGRunResponse) GetDagIdOk() (*string, bool)`

GetDagIdOk returns a tuple with the DagId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDagId

`func (o *DAGRunResponse) SetDagId(v string)`

SetDagId sets DagId field to given value.


### GetLogicalDate

`func (o *DAGRunResponse) GetLogicalDate() time.Time`

GetLogicalDate returns the LogicalDate field if non-nil, zero value otherwise.

### GetLogicalDateOk

`func (o *DAGRunResponse) GetLogicalDateOk() (*time.Time, bool)`

GetLogicalDateOk returns a tuple with the LogicalDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLogicalDate

`func (o *DAGRunResponse) SetLogicalDate(v time.Time)`

SetLogicalDate sets LogicalDate field to given value.


### SetLogicalDateNil

`func (o *DAGRunResponse) SetLogicalDateNil(b bool)`

 SetLogicalDateNil sets the value for LogicalDate to be an explicit nil

### UnsetLogicalDate
`func (o *DAGRunResponse) UnsetLogicalDate()`

UnsetLogicalDate ensures that no value is present for LogicalDate, not even an explicit nil
### GetQueuedAt

`func (o *DAGRunResponse) GetQueuedAt() time.Time`

GetQueuedAt returns the QueuedAt field if non-nil, zero value otherwise.

### GetQueuedAtOk

`func (o *DAGRunResponse) GetQueuedAtOk() (*time.Time, bool)`

GetQueuedAtOk returns a tuple with the QueuedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQueuedAt

`func (o *DAGRunResponse) SetQueuedAt(v time.Time)`

SetQueuedAt sets QueuedAt field to given value.


### SetQueuedAtNil

`func (o *DAGRunResponse) SetQueuedAtNil(b bool)`

 SetQueuedAtNil sets the value for QueuedAt to be an explicit nil

### UnsetQueuedAt
`func (o *DAGRunResponse) UnsetQueuedAt()`

UnsetQueuedAt ensures that no value is present for QueuedAt, not even an explicit nil
### GetStartDate

`func (o *DAGRunResponse) GetStartDate() time.Time`

GetStartDate returns the StartDate field if non-nil, zero value otherwise.

### GetStartDateOk

`func (o *DAGRunResponse) GetStartDateOk() (*time.Time, bool)`

GetStartDateOk returns a tuple with the StartDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartDate

`func (o *DAGRunResponse) SetStartDate(v time.Time)`

SetStartDate sets StartDate field to given value.


### SetStartDateNil

`func (o *DAGRunResponse) SetStartDateNil(b bool)`

 SetStartDateNil sets the value for StartDate to be an explicit nil

### UnsetStartDate
`func (o *DAGRunResponse) UnsetStartDate()`

UnsetStartDate ensures that no value is present for StartDate, not even an explicit nil
### GetEndDate

`func (o *DAGRunResponse) GetEndDate() time.Time`

GetEndDate returns the EndDate field if non-nil, zero value otherwise.

### GetEndDateOk

`func (o *DAGRunResponse) GetEndDateOk() (*time.Time, bool)`

GetEndDateOk returns a tuple with the EndDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEndDate

`func (o *DAGRunResponse) SetEndDate(v time.Time)`

SetEndDate sets EndDate field to given value.


### SetEndDateNil

`func (o *DAGRunResponse) SetEndDateNil(b bool)`

 SetEndDateNil sets the value for EndDate to be an explicit nil

### UnsetEndDate
`func (o *DAGRunResponse) UnsetEndDate()`

UnsetEndDate ensures that no value is present for EndDate, not even an explicit nil
### GetDuration

`func (o *DAGRunResponse) GetDuration() float32`

GetDuration returns the Duration field if non-nil, zero value otherwise.

### GetDurationOk

`func (o *DAGRunResponse) GetDurationOk() (*float32, bool)`

GetDurationOk returns a tuple with the Duration field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDuration

`func (o *DAGRunResponse) SetDuration(v float32)`

SetDuration sets Duration field to given value.


### SetDurationNil

`func (o *DAGRunResponse) SetDurationNil(b bool)`

 SetDurationNil sets the value for Duration to be an explicit nil

### UnsetDuration
`func (o *DAGRunResponse) UnsetDuration()`

UnsetDuration ensures that no value is present for Duration, not even an explicit nil
### GetDataIntervalStart

`func (o *DAGRunResponse) GetDataIntervalStart() time.Time`

GetDataIntervalStart returns the DataIntervalStart field if non-nil, zero value otherwise.

### GetDataIntervalStartOk

`func (o *DAGRunResponse) GetDataIntervalStartOk() (*time.Time, bool)`

GetDataIntervalStartOk returns a tuple with the DataIntervalStart field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDataIntervalStart

`func (o *DAGRunResponse) SetDataIntervalStart(v time.Time)`

SetDataIntervalStart sets DataIntervalStart field to given value.


### SetDataIntervalStartNil

`func (o *DAGRunResponse) SetDataIntervalStartNil(b bool)`

 SetDataIntervalStartNil sets the value for DataIntervalStart to be an explicit nil

### UnsetDataIntervalStart
`func (o *DAGRunResponse) UnsetDataIntervalStart()`

UnsetDataIntervalStart ensures that no value is present for DataIntervalStart, not even an explicit nil
### GetDataIntervalEnd

`func (o *DAGRunResponse) GetDataIntervalEnd() time.Time`

GetDataIntervalEnd returns the DataIntervalEnd field if non-nil, zero value otherwise.

### GetDataIntervalEndOk

`func (o *DAGRunResponse) GetDataIntervalEndOk() (*time.Time, bool)`

GetDataIntervalEndOk returns a tuple with the DataIntervalEnd field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDataIntervalEnd

`func (o *DAGRunResponse) SetDataIntervalEnd(v time.Time)`

SetDataIntervalEnd sets DataIntervalEnd field to given value.


### SetDataIntervalEndNil

`func (o *DAGRunResponse) SetDataIntervalEndNil(b bool)`

 SetDataIntervalEndNil sets the value for DataIntervalEnd to be an explicit nil

### UnsetDataIntervalEnd
`func (o *DAGRunResponse) UnsetDataIntervalEnd()`

UnsetDataIntervalEnd ensures that no value is present for DataIntervalEnd, not even an explicit nil
### GetRunAfter

`func (o *DAGRunResponse) GetRunAfter() time.Time`

GetRunAfter returns the RunAfter field if non-nil, zero value otherwise.

### GetRunAfterOk

`func (o *DAGRunResponse) GetRunAfterOk() (*time.Time, bool)`

GetRunAfterOk returns a tuple with the RunAfter field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRunAfter

`func (o *DAGRunResponse) SetRunAfter(v time.Time)`

SetRunAfter sets RunAfter field to given value.


### GetLastSchedulingDecision

`func (o *DAGRunResponse) GetLastSchedulingDecision() time.Time`

GetLastSchedulingDecision returns the LastSchedulingDecision field if non-nil, zero value otherwise.

### GetLastSchedulingDecisionOk

`func (o *DAGRunResponse) GetLastSchedulingDecisionOk() (*time.Time, bool)`

GetLastSchedulingDecisionOk returns a tuple with the LastSchedulingDecision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastSchedulingDecision

`func (o *DAGRunResponse) SetLastSchedulingDecision(v time.Time)`

SetLastSchedulingDecision sets LastSchedulingDecision field to given value.


### SetLastSchedulingDecisionNil

`func (o *DAGRunResponse) SetLastSchedulingDecisionNil(b bool)`

 SetLastSchedulingDecisionNil sets the value for LastSchedulingDecision to be an explicit nil

### UnsetLastSchedulingDecision
`func (o *DAGRunResponse) UnsetLastSchedulingDecision()`

UnsetLastSchedulingDecision ensures that no value is present for LastSchedulingDecision, not even an explicit nil
### GetRunType

`func (o *DAGRunResponse) GetRunType() DagRunType`

GetRunType returns the RunType field if non-nil, zero value otherwise.

### GetRunTypeOk

`func (o *DAGRunResponse) GetRunTypeOk() (*DagRunType, bool)`

GetRunTypeOk returns a tuple with the RunType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRunType

`func (o *DAGRunResponse) SetRunType(v DagRunType)`

SetRunType sets RunType field to given value.


### GetState

`func (o *DAGRunResponse) GetState() DagRunState`

GetState returns the State field if non-nil, zero value otherwise.

### GetStateOk

`func (o *DAGRunResponse) GetStateOk() (*DagRunState, bool)`

GetStateOk returns a tuple with the State field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetState

`func (o *DAGRunResponse) SetState(v DagRunState)`

SetState sets State field to given value.


### GetTriggeredBy

`func (o *DAGRunResponse) GetTriggeredBy() DagRunTriggeredByType`

GetTriggeredBy returns the TriggeredBy field if non-nil, zero value otherwise.

### GetTriggeredByOk

`func (o *DAGRunResponse) GetTriggeredByOk() (*DagRunTriggeredByType, bool)`

GetTriggeredByOk returns a tuple with the TriggeredBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTriggeredBy

`func (o *DAGRunResponse) SetTriggeredBy(v DagRunTriggeredByType)`

SetTriggeredBy sets TriggeredBy field to given value.


### SetTriggeredByNil

`func (o *DAGRunResponse) SetTriggeredByNil(b bool)`

 SetTriggeredByNil sets the value for TriggeredBy to be an explicit nil

### UnsetTriggeredBy
`func (o *DAGRunResponse) UnsetTriggeredBy()`

UnsetTriggeredBy ensures that no value is present for TriggeredBy, not even an explicit nil
### GetConf

`func (o *DAGRunResponse) GetConf() map[string]interface{}`

GetConf returns the Conf field if non-nil, zero value otherwise.

### GetConfOk

`func (o *DAGRunResponse) GetConfOk() (*map[string]interface{}, bool)`

GetConfOk returns a tuple with the Conf field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConf

`func (o *DAGRunResponse) SetConf(v map[string]interface{})`

SetConf sets Conf field to given value.


### SetConfNil

`func (o *DAGRunResponse) SetConfNil(b bool)`

 SetConfNil sets the value for Conf to be an explicit nil

### UnsetConf
`func (o *DAGRunResponse) UnsetConf()`

UnsetConf ensures that no value is present for Conf, not even an explicit nil
### GetNote

`func (o *DAGRunResponse) GetNote() string`

GetNote returns the Note field if non-nil, zero value otherwise.

### GetNoteOk

`func (o *DAGRunResponse) GetNoteOk() (*string, bool)`

GetNoteOk returns a tuple with the Note field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNote

`func (o *DAGRunResponse) SetNote(v string)`

SetNote sets Note field to given value.


### SetNoteNil

`func (o *DAGRunResponse) SetNoteNil(b bool)`

 SetNoteNil sets the value for Note to be an explicit nil

### UnsetNote
`func (o *DAGRunResponse) UnsetNote()`

UnsetNote ensures that no value is present for Note, not even an explicit nil
### GetDagVersions

`func (o *DAGRunResponse) GetDagVersions() []DagVersionResponse`

GetDagVersions returns the DagVersions field if non-nil, zero value otherwise.

### GetDagVersionsOk

`func (o *DAGRunResponse) GetDagVersionsOk() (*[]DagVersionResponse, bool)`

GetDagVersionsOk returns a tuple with the DagVersions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDagVersions

`func (o *DAGRunResponse) SetDagVersions(v []DagVersionResponse)`

SetDagVersions sets DagVersions field to given value.


### GetBundleVersion

`func (o *DAGRunResponse) GetBundleVersion() string`

GetBundleVersion returns the BundleVersion field if non-nil, zero value otherwise.

### GetBundleVersionOk

`func (o *DAGRunResponse) GetBundleVersionOk() (*string, bool)`

GetBundleVersionOk returns a tuple with the BundleVersion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBundleVersion

`func (o *DAGRunResponse) SetBundleVersion(v string)`

SetBundleVersion sets BundleVersion field to given value.


### SetBundleVersionNil

`func (o *DAGRunResponse) SetBundleVersionNil(b bool)`

 SetBundleVersionNil sets the value for BundleVersion to be an explicit nil

### UnsetBundleVersion
`func (o *DAGRunResponse) UnsetBundleVersion()`

UnsetBundleVersion ensures that no value is present for BundleVersion, not even an explicit nil
### GetDagDisplayName

`func (o *DAGRunResponse) GetDagDisplayName() string`

GetDagDisplayName returns the DagDisplayName field if non-nil, zero value otherwise.

### GetDagDisplayNameOk

`func (o *DAGRunResponse) GetDagDisplayNameOk() (*string, bool)`

GetDagDisplayNameOk returns a tuple with the DagDisplayName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDagDisplayName

`func (o *DAGRunResponse) SetDagDisplayName(v string)`

SetDagDisplayName sets DagDisplayName field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


