# PoolBody

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | **string** |  | 
**Slots** | **int32** |  | 
**Description** | Pointer to **NullableString** |  | [optional] 
**IncludeDeferred** | Pointer to **bool** |  | [optional] [default to false]

## Methods

### NewPoolBody

`func NewPoolBody(name string, slots int32, ) *PoolBody`

NewPoolBody instantiates a new PoolBody object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPoolBodyWithDefaults

`func NewPoolBodyWithDefaults() *PoolBody`

NewPoolBodyWithDefaults instantiates a new PoolBody object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *PoolBody) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *PoolBody) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *PoolBody) SetName(v string)`

SetName sets Name field to given value.


### GetSlots

`func (o *PoolBody) GetSlots() int32`

GetSlots returns the Slots field if non-nil, zero value otherwise.

### GetSlotsOk

`func (o *PoolBody) GetSlotsOk() (*int32, bool)`

GetSlotsOk returns a tuple with the Slots field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSlots

`func (o *PoolBody) SetSlots(v int32)`

SetSlots sets Slots field to given value.


### GetDescription

`func (o *PoolBody) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *PoolBody) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *PoolBody) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *PoolBody) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### SetDescriptionNil

`func (o *PoolBody) SetDescriptionNil(b bool)`

 SetDescriptionNil sets the value for Description to be an explicit nil

### UnsetDescription
`func (o *PoolBody) UnsetDescription()`

UnsetDescription ensures that no value is present for Description, not even an explicit nil
### GetIncludeDeferred

`func (o *PoolBody) GetIncludeDeferred() bool`

GetIncludeDeferred returns the IncludeDeferred field if non-nil, zero value otherwise.

### GetIncludeDeferredOk

`func (o *PoolBody) GetIncludeDeferredOk() (*bool, bool)`

GetIncludeDeferredOk returns a tuple with the IncludeDeferred field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIncludeDeferred

`func (o *PoolBody) SetIncludeDeferred(v bool)`

SetIncludeDeferred sets IncludeDeferred field to given value.

### HasIncludeDeferred

`func (o *PoolBody) HasIncludeDeferred() bool`

HasIncludeDeferred returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


