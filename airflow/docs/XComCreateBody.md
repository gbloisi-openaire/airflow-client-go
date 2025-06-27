# XComCreateBody

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Key** | **string** |  | 
**Value** | **interface{}** |  | 
**MapIndex** | Pointer to **int32** |  | [optional] [default to -1]

## Methods

### NewXComCreateBody

`func NewXComCreateBody(key string, value interface{}, ) *XComCreateBody`

NewXComCreateBody instantiates a new XComCreateBody object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewXComCreateBodyWithDefaults

`func NewXComCreateBodyWithDefaults() *XComCreateBody`

NewXComCreateBodyWithDefaults instantiates a new XComCreateBody object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetKey

`func (o *XComCreateBody) GetKey() string`

GetKey returns the Key field if non-nil, zero value otherwise.

### GetKeyOk

`func (o *XComCreateBody) GetKeyOk() (*string, bool)`

GetKeyOk returns a tuple with the Key field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKey

`func (o *XComCreateBody) SetKey(v string)`

SetKey sets Key field to given value.


### GetValue

`func (o *XComCreateBody) GetValue() interface{}`

GetValue returns the Value field if non-nil, zero value otherwise.

### GetValueOk

`func (o *XComCreateBody) GetValueOk() (*interface{}, bool)`

GetValueOk returns a tuple with the Value field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValue

`func (o *XComCreateBody) SetValue(v interface{})`

SetValue sets Value field to given value.


### SetValueNil

`func (o *XComCreateBody) SetValueNil(b bool)`

 SetValueNil sets the value for Value to be an explicit nil

### UnsetValue
`func (o *XComCreateBody) UnsetValue()`

UnsetValue ensures that no value is present for Value, not even an explicit nil
### GetMapIndex

`func (o *XComCreateBody) GetMapIndex() int32`

GetMapIndex returns the MapIndex field if non-nil, zero value otherwise.

### GetMapIndexOk

`func (o *XComCreateBody) GetMapIndexOk() (*int32, bool)`

GetMapIndexOk returns a tuple with the MapIndex field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMapIndex

`func (o *XComCreateBody) SetMapIndex(v int32)`

SetMapIndex sets MapIndex field to given value.

### HasMapIndex

`func (o *XComCreateBody) HasMapIndex() bool`

HasMapIndex returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


