# BulkTaskInstanceBody

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**NewState** | Pointer to [**NullableTaskInstanceState**](TaskInstanceState.md) |  | [optional] 
**Note** | Pointer to **NullableString** |  | [optional] 
**IncludeUpstream** | Pointer to **bool** |  | [optional] [default to false]
**IncludeDownstream** | Pointer to **bool** |  | [optional] [default to false]
**IncludeFuture** | Pointer to **bool** |  | [optional] [default to false]
**IncludePast** | Pointer to **bool** |  | [optional] [default to false]
**TaskId** | **string** |  | 
**MapIndex** | Pointer to **NullableInt32** |  | [optional] 

## Methods

### NewBulkTaskInstanceBody

`func NewBulkTaskInstanceBody(taskId string, ) *BulkTaskInstanceBody`

NewBulkTaskInstanceBody instantiates a new BulkTaskInstanceBody object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewBulkTaskInstanceBodyWithDefaults

`func NewBulkTaskInstanceBodyWithDefaults() *BulkTaskInstanceBody`

NewBulkTaskInstanceBodyWithDefaults instantiates a new BulkTaskInstanceBody object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetNewState

`func (o *BulkTaskInstanceBody) GetNewState() TaskInstanceState`

GetNewState returns the NewState field if non-nil, zero value otherwise.

### GetNewStateOk

`func (o *BulkTaskInstanceBody) GetNewStateOk() (*TaskInstanceState, bool)`

GetNewStateOk returns a tuple with the NewState field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNewState

`func (o *BulkTaskInstanceBody) SetNewState(v TaskInstanceState)`

SetNewState sets NewState field to given value.

### HasNewState

`func (o *BulkTaskInstanceBody) HasNewState() bool`

HasNewState returns a boolean if a field has been set.

### SetNewStateNil

`func (o *BulkTaskInstanceBody) SetNewStateNil(b bool)`

 SetNewStateNil sets the value for NewState to be an explicit nil

### UnsetNewState
`func (o *BulkTaskInstanceBody) UnsetNewState()`

UnsetNewState ensures that no value is present for NewState, not even an explicit nil
### GetNote

`func (o *BulkTaskInstanceBody) GetNote() string`

GetNote returns the Note field if non-nil, zero value otherwise.

### GetNoteOk

`func (o *BulkTaskInstanceBody) GetNoteOk() (*string, bool)`

GetNoteOk returns a tuple with the Note field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNote

`func (o *BulkTaskInstanceBody) SetNote(v string)`

SetNote sets Note field to given value.

### HasNote

`func (o *BulkTaskInstanceBody) HasNote() bool`

HasNote returns a boolean if a field has been set.

### SetNoteNil

`func (o *BulkTaskInstanceBody) SetNoteNil(b bool)`

 SetNoteNil sets the value for Note to be an explicit nil

### UnsetNote
`func (o *BulkTaskInstanceBody) UnsetNote()`

UnsetNote ensures that no value is present for Note, not even an explicit nil
### GetIncludeUpstream

`func (o *BulkTaskInstanceBody) GetIncludeUpstream() bool`

GetIncludeUpstream returns the IncludeUpstream field if non-nil, zero value otherwise.

### GetIncludeUpstreamOk

`func (o *BulkTaskInstanceBody) GetIncludeUpstreamOk() (*bool, bool)`

GetIncludeUpstreamOk returns a tuple with the IncludeUpstream field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIncludeUpstream

`func (o *BulkTaskInstanceBody) SetIncludeUpstream(v bool)`

SetIncludeUpstream sets IncludeUpstream field to given value.

### HasIncludeUpstream

`func (o *BulkTaskInstanceBody) HasIncludeUpstream() bool`

HasIncludeUpstream returns a boolean if a field has been set.

### GetIncludeDownstream

`func (o *BulkTaskInstanceBody) GetIncludeDownstream() bool`

GetIncludeDownstream returns the IncludeDownstream field if non-nil, zero value otherwise.

### GetIncludeDownstreamOk

`func (o *BulkTaskInstanceBody) GetIncludeDownstreamOk() (*bool, bool)`

GetIncludeDownstreamOk returns a tuple with the IncludeDownstream field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIncludeDownstream

`func (o *BulkTaskInstanceBody) SetIncludeDownstream(v bool)`

SetIncludeDownstream sets IncludeDownstream field to given value.

### HasIncludeDownstream

`func (o *BulkTaskInstanceBody) HasIncludeDownstream() bool`

HasIncludeDownstream returns a boolean if a field has been set.

### GetIncludeFuture

`func (o *BulkTaskInstanceBody) GetIncludeFuture() bool`

GetIncludeFuture returns the IncludeFuture field if non-nil, zero value otherwise.

### GetIncludeFutureOk

`func (o *BulkTaskInstanceBody) GetIncludeFutureOk() (*bool, bool)`

GetIncludeFutureOk returns a tuple with the IncludeFuture field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIncludeFuture

`func (o *BulkTaskInstanceBody) SetIncludeFuture(v bool)`

SetIncludeFuture sets IncludeFuture field to given value.

### HasIncludeFuture

`func (o *BulkTaskInstanceBody) HasIncludeFuture() bool`

HasIncludeFuture returns a boolean if a field has been set.

### GetIncludePast

`func (o *BulkTaskInstanceBody) GetIncludePast() bool`

GetIncludePast returns the IncludePast field if non-nil, zero value otherwise.

### GetIncludePastOk

`func (o *BulkTaskInstanceBody) GetIncludePastOk() (*bool, bool)`

GetIncludePastOk returns a tuple with the IncludePast field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIncludePast

`func (o *BulkTaskInstanceBody) SetIncludePast(v bool)`

SetIncludePast sets IncludePast field to given value.

### HasIncludePast

`func (o *BulkTaskInstanceBody) HasIncludePast() bool`

HasIncludePast returns a boolean if a field has been set.

### GetTaskId

`func (o *BulkTaskInstanceBody) GetTaskId() string`

GetTaskId returns the TaskId field if non-nil, zero value otherwise.

### GetTaskIdOk

`func (o *BulkTaskInstanceBody) GetTaskIdOk() (*string, bool)`

GetTaskIdOk returns a tuple with the TaskId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaskId

`func (o *BulkTaskInstanceBody) SetTaskId(v string)`

SetTaskId sets TaskId field to given value.


### GetMapIndex

`func (o *BulkTaskInstanceBody) GetMapIndex() int32`

GetMapIndex returns the MapIndex field if non-nil, zero value otherwise.

### GetMapIndexOk

`func (o *BulkTaskInstanceBody) GetMapIndexOk() (*int32, bool)`

GetMapIndexOk returns a tuple with the MapIndex field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMapIndex

`func (o *BulkTaskInstanceBody) SetMapIndex(v int32)`

SetMapIndex sets MapIndex field to given value.

### HasMapIndex

`func (o *BulkTaskInstanceBody) HasMapIndex() bool`

HasMapIndex returns a boolean if a field has been set.

### SetMapIndexNil

`func (o *BulkTaskInstanceBody) SetMapIndexNil(b bool)`

 SetMapIndexNil sets the value for MapIndex to be an explicit nil

### UnsetMapIndex
`func (o *BulkTaskInstanceBody) UnsetMapIndex()`

UnsetMapIndex ensures that no value is present for MapIndex, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


