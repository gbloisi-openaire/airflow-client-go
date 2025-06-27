# PoolResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | **string** |  | 
**Slots** | **int32** |  | 
**Description** | **NullableString** |  | 
**IncludeDeferred** | **bool** |  | 
**OccupiedSlots** | **int32** |  | 
**RunningSlots** | **int32** |  | 
**QueuedSlots** | **int32** |  | 
**ScheduledSlots** | **int32** |  | 
**OpenSlots** | **int32** |  | 
**DeferredSlots** | **int32** |  | 

## Methods

### NewPoolResponse

`func NewPoolResponse(name string, slots int32, description NullableString, includeDeferred bool, occupiedSlots int32, runningSlots int32, queuedSlots int32, scheduledSlots int32, openSlots int32, deferredSlots int32, ) *PoolResponse`

NewPoolResponse instantiates a new PoolResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPoolResponseWithDefaults

`func NewPoolResponseWithDefaults() *PoolResponse`

NewPoolResponseWithDefaults instantiates a new PoolResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *PoolResponse) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *PoolResponse) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *PoolResponse) SetName(v string)`

SetName sets Name field to given value.


### GetSlots

`func (o *PoolResponse) GetSlots() int32`

GetSlots returns the Slots field if non-nil, zero value otherwise.

### GetSlotsOk

`func (o *PoolResponse) GetSlotsOk() (*int32, bool)`

GetSlotsOk returns a tuple with the Slots field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSlots

`func (o *PoolResponse) SetSlots(v int32)`

SetSlots sets Slots field to given value.


### GetDescription

`func (o *PoolResponse) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *PoolResponse) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *PoolResponse) SetDescription(v string)`

SetDescription sets Description field to given value.


### SetDescriptionNil

`func (o *PoolResponse) SetDescriptionNil(b bool)`

 SetDescriptionNil sets the value for Description to be an explicit nil

### UnsetDescription
`func (o *PoolResponse) UnsetDescription()`

UnsetDescription ensures that no value is present for Description, not even an explicit nil
### GetIncludeDeferred

`func (o *PoolResponse) GetIncludeDeferred() bool`

GetIncludeDeferred returns the IncludeDeferred field if non-nil, zero value otherwise.

### GetIncludeDeferredOk

`func (o *PoolResponse) GetIncludeDeferredOk() (*bool, bool)`

GetIncludeDeferredOk returns a tuple with the IncludeDeferred field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIncludeDeferred

`func (o *PoolResponse) SetIncludeDeferred(v bool)`

SetIncludeDeferred sets IncludeDeferred field to given value.


### GetOccupiedSlots

`func (o *PoolResponse) GetOccupiedSlots() int32`

GetOccupiedSlots returns the OccupiedSlots field if non-nil, zero value otherwise.

### GetOccupiedSlotsOk

`func (o *PoolResponse) GetOccupiedSlotsOk() (*int32, bool)`

GetOccupiedSlotsOk returns a tuple with the OccupiedSlots field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOccupiedSlots

`func (o *PoolResponse) SetOccupiedSlots(v int32)`

SetOccupiedSlots sets OccupiedSlots field to given value.


### GetRunningSlots

`func (o *PoolResponse) GetRunningSlots() int32`

GetRunningSlots returns the RunningSlots field if non-nil, zero value otherwise.

### GetRunningSlotsOk

`func (o *PoolResponse) GetRunningSlotsOk() (*int32, bool)`

GetRunningSlotsOk returns a tuple with the RunningSlots field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRunningSlots

`func (o *PoolResponse) SetRunningSlots(v int32)`

SetRunningSlots sets RunningSlots field to given value.


### GetQueuedSlots

`func (o *PoolResponse) GetQueuedSlots() int32`

GetQueuedSlots returns the QueuedSlots field if non-nil, zero value otherwise.

### GetQueuedSlotsOk

`func (o *PoolResponse) GetQueuedSlotsOk() (*int32, bool)`

GetQueuedSlotsOk returns a tuple with the QueuedSlots field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQueuedSlots

`func (o *PoolResponse) SetQueuedSlots(v int32)`

SetQueuedSlots sets QueuedSlots field to given value.


### GetScheduledSlots

`func (o *PoolResponse) GetScheduledSlots() int32`

GetScheduledSlots returns the ScheduledSlots field if non-nil, zero value otherwise.

### GetScheduledSlotsOk

`func (o *PoolResponse) GetScheduledSlotsOk() (*int32, bool)`

GetScheduledSlotsOk returns a tuple with the ScheduledSlots field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScheduledSlots

`func (o *PoolResponse) SetScheduledSlots(v int32)`

SetScheduledSlots sets ScheduledSlots field to given value.


### GetOpenSlots

`func (o *PoolResponse) GetOpenSlots() int32`

GetOpenSlots returns the OpenSlots field if non-nil, zero value otherwise.

### GetOpenSlotsOk

`func (o *PoolResponse) GetOpenSlotsOk() (*int32, bool)`

GetOpenSlotsOk returns a tuple with the OpenSlots field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOpenSlots

`func (o *PoolResponse) SetOpenSlots(v int32)`

SetOpenSlots sets OpenSlots field to given value.


### GetDeferredSlots

`func (o *PoolResponse) GetDeferredSlots() int32`

GetDeferredSlots returns the DeferredSlots field if non-nil, zero value otherwise.

### GetDeferredSlotsOk

`func (o *PoolResponse) GetDeferredSlotsOk() (*int32, bool)`

GetDeferredSlotsOk returns a tuple with the DeferredSlots field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeferredSlots

`func (o *PoolResponse) SetDeferredSlots(v int32)`

SetDeferredSlots sets DeferredSlots field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


