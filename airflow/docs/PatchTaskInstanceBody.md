# PatchTaskInstanceBody

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**NewState** | Pointer to [**NullableTaskInstanceState**](TaskInstanceState.md) |  | [optional] 
**Note** | Pointer to **NullableString** |  | [optional] 
**IncludeUpstream** | Pointer to **bool** |  | [optional] [default to false]
**IncludeDownstream** | Pointer to **bool** |  | [optional] [default to false]
**IncludeFuture** | Pointer to **bool** |  | [optional] [default to false]
**IncludePast** | Pointer to **bool** |  | [optional] [default to false]

## Methods

### NewPatchTaskInstanceBody

`func NewPatchTaskInstanceBody() *PatchTaskInstanceBody`

NewPatchTaskInstanceBody instantiates a new PatchTaskInstanceBody object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPatchTaskInstanceBodyWithDefaults

`func NewPatchTaskInstanceBodyWithDefaults() *PatchTaskInstanceBody`

NewPatchTaskInstanceBodyWithDefaults instantiates a new PatchTaskInstanceBody object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetNewState

`func (o *PatchTaskInstanceBody) GetNewState() TaskInstanceState`

GetNewState returns the NewState field if non-nil, zero value otherwise.

### GetNewStateOk

`func (o *PatchTaskInstanceBody) GetNewStateOk() (*TaskInstanceState, bool)`

GetNewStateOk returns a tuple with the NewState field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNewState

`func (o *PatchTaskInstanceBody) SetNewState(v TaskInstanceState)`

SetNewState sets NewState field to given value.

### HasNewState

`func (o *PatchTaskInstanceBody) HasNewState() bool`

HasNewState returns a boolean if a field has been set.

### SetNewStateNil

`func (o *PatchTaskInstanceBody) SetNewStateNil(b bool)`

 SetNewStateNil sets the value for NewState to be an explicit nil

### UnsetNewState
`func (o *PatchTaskInstanceBody) UnsetNewState()`

UnsetNewState ensures that no value is present for NewState, not even an explicit nil
### GetNote

`func (o *PatchTaskInstanceBody) GetNote() string`

GetNote returns the Note field if non-nil, zero value otherwise.

### GetNoteOk

`func (o *PatchTaskInstanceBody) GetNoteOk() (*string, bool)`

GetNoteOk returns a tuple with the Note field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNote

`func (o *PatchTaskInstanceBody) SetNote(v string)`

SetNote sets Note field to given value.

### HasNote

`func (o *PatchTaskInstanceBody) HasNote() bool`

HasNote returns a boolean if a field has been set.

### SetNoteNil

`func (o *PatchTaskInstanceBody) SetNoteNil(b bool)`

 SetNoteNil sets the value for Note to be an explicit nil

### UnsetNote
`func (o *PatchTaskInstanceBody) UnsetNote()`

UnsetNote ensures that no value is present for Note, not even an explicit nil
### GetIncludeUpstream

`func (o *PatchTaskInstanceBody) GetIncludeUpstream() bool`

GetIncludeUpstream returns the IncludeUpstream field if non-nil, zero value otherwise.

### GetIncludeUpstreamOk

`func (o *PatchTaskInstanceBody) GetIncludeUpstreamOk() (*bool, bool)`

GetIncludeUpstreamOk returns a tuple with the IncludeUpstream field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIncludeUpstream

`func (o *PatchTaskInstanceBody) SetIncludeUpstream(v bool)`

SetIncludeUpstream sets IncludeUpstream field to given value.

### HasIncludeUpstream

`func (o *PatchTaskInstanceBody) HasIncludeUpstream() bool`

HasIncludeUpstream returns a boolean if a field has been set.

### GetIncludeDownstream

`func (o *PatchTaskInstanceBody) GetIncludeDownstream() bool`

GetIncludeDownstream returns the IncludeDownstream field if non-nil, zero value otherwise.

### GetIncludeDownstreamOk

`func (o *PatchTaskInstanceBody) GetIncludeDownstreamOk() (*bool, bool)`

GetIncludeDownstreamOk returns a tuple with the IncludeDownstream field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIncludeDownstream

`func (o *PatchTaskInstanceBody) SetIncludeDownstream(v bool)`

SetIncludeDownstream sets IncludeDownstream field to given value.

### HasIncludeDownstream

`func (o *PatchTaskInstanceBody) HasIncludeDownstream() bool`

HasIncludeDownstream returns a boolean if a field has been set.

### GetIncludeFuture

`func (o *PatchTaskInstanceBody) GetIncludeFuture() bool`

GetIncludeFuture returns the IncludeFuture field if non-nil, zero value otherwise.

### GetIncludeFutureOk

`func (o *PatchTaskInstanceBody) GetIncludeFutureOk() (*bool, bool)`

GetIncludeFutureOk returns a tuple with the IncludeFuture field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIncludeFuture

`func (o *PatchTaskInstanceBody) SetIncludeFuture(v bool)`

SetIncludeFuture sets IncludeFuture field to given value.

### HasIncludeFuture

`func (o *PatchTaskInstanceBody) HasIncludeFuture() bool`

HasIncludeFuture returns a boolean if a field has been set.

### GetIncludePast

`func (o *PatchTaskInstanceBody) GetIncludePast() bool`

GetIncludePast returns the IncludePast field if non-nil, zero value otherwise.

### GetIncludePastOk

`func (o *PatchTaskInstanceBody) GetIncludePastOk() (*bool, bool)`

GetIncludePastOk returns a tuple with the IncludePast field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIncludePast

`func (o *PatchTaskInstanceBody) SetIncludePast(v bool)`

SetIncludePast sets IncludePast field to given value.

### HasIncludePast

`func (o *PatchTaskInstanceBody) HasIncludePast() bool`

HasIncludePast returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


