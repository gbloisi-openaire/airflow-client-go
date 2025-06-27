# TriggerDAGRunPostBody

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DagRunId** | Pointer to [**DagRunId**](DagRunId.md) |  | [optional] 
**DataIntervalStart** | Pointer to [**DataIntervalStart**](DataIntervalStart.md) |  | [optional] 
**DataIntervalEnd** | Pointer to [**DataIntervalEnd**](DataIntervalEnd.md) |  | [optional] 
**LogicalDate** | [**NullableLogicalDate**](LogicalDate.md) |  | 
**RunAfter** | Pointer to [**RunAfter**](RunAfter.md) |  | [optional] 
**Conf** | Pointer to **map[string]interface{}** |  | [optional] 
**Note** | Pointer to [**NullableNote**](Note.md) |  | [optional] 

## Methods

### NewTriggerDAGRunPostBody

`func NewTriggerDAGRunPostBody(logicalDate NullableLogicalDate, ) *TriggerDAGRunPostBody`

NewTriggerDAGRunPostBody instantiates a new TriggerDAGRunPostBody object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTriggerDAGRunPostBodyWithDefaults

`func NewTriggerDAGRunPostBodyWithDefaults() *TriggerDAGRunPostBody`

NewTriggerDAGRunPostBodyWithDefaults instantiates a new TriggerDAGRunPostBody object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDagRunId

`func (o *TriggerDAGRunPostBody) GetDagRunId() DagRunId`

GetDagRunId returns the DagRunId field if non-nil, zero value otherwise.

### GetDagRunIdOk

`func (o *TriggerDAGRunPostBody) GetDagRunIdOk() (*DagRunId, bool)`

GetDagRunIdOk returns a tuple with the DagRunId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDagRunId

`func (o *TriggerDAGRunPostBody) SetDagRunId(v DagRunId)`

SetDagRunId sets DagRunId field to given value.

### HasDagRunId

`func (o *TriggerDAGRunPostBody) HasDagRunId() bool`

HasDagRunId returns a boolean if a field has been set.

### GetDataIntervalStart

`func (o *TriggerDAGRunPostBody) GetDataIntervalStart() DataIntervalStart`

GetDataIntervalStart returns the DataIntervalStart field if non-nil, zero value otherwise.

### GetDataIntervalStartOk

`func (o *TriggerDAGRunPostBody) GetDataIntervalStartOk() (*DataIntervalStart, bool)`

GetDataIntervalStartOk returns a tuple with the DataIntervalStart field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDataIntervalStart

`func (o *TriggerDAGRunPostBody) SetDataIntervalStart(v DataIntervalStart)`

SetDataIntervalStart sets DataIntervalStart field to given value.

### HasDataIntervalStart

`func (o *TriggerDAGRunPostBody) HasDataIntervalStart() bool`

HasDataIntervalStart returns a boolean if a field has been set.

### GetDataIntervalEnd

`func (o *TriggerDAGRunPostBody) GetDataIntervalEnd() DataIntervalEnd`

GetDataIntervalEnd returns the DataIntervalEnd field if non-nil, zero value otherwise.

### GetDataIntervalEndOk

`func (o *TriggerDAGRunPostBody) GetDataIntervalEndOk() (*DataIntervalEnd, bool)`

GetDataIntervalEndOk returns a tuple with the DataIntervalEnd field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDataIntervalEnd

`func (o *TriggerDAGRunPostBody) SetDataIntervalEnd(v DataIntervalEnd)`

SetDataIntervalEnd sets DataIntervalEnd field to given value.

### HasDataIntervalEnd

`func (o *TriggerDAGRunPostBody) HasDataIntervalEnd() bool`

HasDataIntervalEnd returns a boolean if a field has been set.

### GetLogicalDate

`func (o *TriggerDAGRunPostBody) GetLogicalDate() LogicalDate`

GetLogicalDate returns the LogicalDate field if non-nil, zero value otherwise.

### GetLogicalDateOk

`func (o *TriggerDAGRunPostBody) GetLogicalDateOk() (*LogicalDate, bool)`

GetLogicalDateOk returns a tuple with the LogicalDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLogicalDate

`func (o *TriggerDAGRunPostBody) SetLogicalDate(v LogicalDate)`

SetLogicalDate sets LogicalDate field to given value.


### SetLogicalDateNil

`func (o *TriggerDAGRunPostBody) SetLogicalDateNil(b bool)`

 SetLogicalDateNil sets the value for LogicalDate to be an explicit nil

### UnsetLogicalDate
`func (o *TriggerDAGRunPostBody) UnsetLogicalDate()`

UnsetLogicalDate ensures that no value is present for LogicalDate, not even an explicit nil
### GetRunAfter

`func (o *TriggerDAGRunPostBody) GetRunAfter() RunAfter`

GetRunAfter returns the RunAfter field if non-nil, zero value otherwise.

### GetRunAfterOk

`func (o *TriggerDAGRunPostBody) GetRunAfterOk() (*RunAfter, bool)`

GetRunAfterOk returns a tuple with the RunAfter field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRunAfter

`func (o *TriggerDAGRunPostBody) SetRunAfter(v RunAfter)`

SetRunAfter sets RunAfter field to given value.

### HasRunAfter

`func (o *TriggerDAGRunPostBody) HasRunAfter() bool`

HasRunAfter returns a boolean if a field has been set.

### GetConf

`func (o *TriggerDAGRunPostBody) GetConf() map[string]interface{}`

GetConf returns the Conf field if non-nil, zero value otherwise.

### GetConfOk

`func (o *TriggerDAGRunPostBody) GetConfOk() (*map[string]interface{}, bool)`

GetConfOk returns a tuple with the Conf field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConf

`func (o *TriggerDAGRunPostBody) SetConf(v map[string]interface{})`

SetConf sets Conf field to given value.

### HasConf

`func (o *TriggerDAGRunPostBody) HasConf() bool`

HasConf returns a boolean if a field has been set.

### GetNote

`func (o *TriggerDAGRunPostBody) GetNote() Note`

GetNote returns the Note field if non-nil, zero value otherwise.

### GetNoteOk

`func (o *TriggerDAGRunPostBody) GetNoteOk() (*Note, bool)`

GetNoteOk returns a tuple with the Note field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNote

`func (o *TriggerDAGRunPostBody) SetNote(v Note)`

SetNote sets Note field to given value.

### HasNote

`func (o *TriggerDAGRunPostBody) HasNote() bool`

HasNote returns a boolean if a field has been set.

### SetNoteNil

`func (o *TriggerDAGRunPostBody) SetNoteNil(b bool)`

 SetNoteNil sets the value for Note to be an explicit nil

### UnsetNote
`func (o *TriggerDAGRunPostBody) UnsetNote()`

UnsetNote ensures that no value is present for Note, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


