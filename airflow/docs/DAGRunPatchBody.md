# DAGRunPatchBody

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**State** | Pointer to [**NullableDAGRunPatchStates**](DAGRunPatchStates.md) |  | [optional] 
**Note** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewDAGRunPatchBody

`func NewDAGRunPatchBody() *DAGRunPatchBody`

NewDAGRunPatchBody instantiates a new DAGRunPatchBody object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDAGRunPatchBodyWithDefaults

`func NewDAGRunPatchBodyWithDefaults() *DAGRunPatchBody`

NewDAGRunPatchBodyWithDefaults instantiates a new DAGRunPatchBody object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetState

`func (o *DAGRunPatchBody) GetState() DAGRunPatchStates`

GetState returns the State field if non-nil, zero value otherwise.

### GetStateOk

`func (o *DAGRunPatchBody) GetStateOk() (*DAGRunPatchStates, bool)`

GetStateOk returns a tuple with the State field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetState

`func (o *DAGRunPatchBody) SetState(v DAGRunPatchStates)`

SetState sets State field to given value.

### HasState

`func (o *DAGRunPatchBody) HasState() bool`

HasState returns a boolean if a field has been set.

### SetStateNil

`func (o *DAGRunPatchBody) SetStateNil(b bool)`

 SetStateNil sets the value for State to be an explicit nil

### UnsetState
`func (o *DAGRunPatchBody) UnsetState()`

UnsetState ensures that no value is present for State, not even an explicit nil
### GetNote

`func (o *DAGRunPatchBody) GetNote() string`

GetNote returns the Note field if non-nil, zero value otherwise.

### GetNoteOk

`func (o *DAGRunPatchBody) GetNoteOk() (*string, bool)`

GetNoteOk returns a tuple with the Note field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNote

`func (o *DAGRunPatchBody) SetNote(v string)`

SetNote sets Note field to given value.

### HasNote

`func (o *DAGRunPatchBody) HasNote() bool`

HasNote returns a boolean if a field has been set.

### SetNoteNil

`func (o *DAGRunPatchBody) SetNoteNil(b bool)`

 SetNoteNil sets the value for Note to be an explicit nil

### UnsetNote
`func (o *DAGRunPatchBody) UnsetNote()`

UnsetNote ensures that no value is present for Note, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


