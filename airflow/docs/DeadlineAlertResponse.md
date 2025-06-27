# DeadlineAlertResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Reference** | **string** |  | 
**Interval** | **string** |  | 
**Callback** | **string** |  | 
**CallbackKwargs** | Pointer to **map[string]interface{}** |  | [optional] 

## Methods

### NewDeadlineAlertResponse

`func NewDeadlineAlertResponse(reference string, interval string, callback string, ) *DeadlineAlertResponse`

NewDeadlineAlertResponse instantiates a new DeadlineAlertResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDeadlineAlertResponseWithDefaults

`func NewDeadlineAlertResponseWithDefaults() *DeadlineAlertResponse`

NewDeadlineAlertResponseWithDefaults instantiates a new DeadlineAlertResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetReference

`func (o *DeadlineAlertResponse) GetReference() string`

GetReference returns the Reference field if non-nil, zero value otherwise.

### GetReferenceOk

`func (o *DeadlineAlertResponse) GetReferenceOk() (*string, bool)`

GetReferenceOk returns a tuple with the Reference field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReference

`func (o *DeadlineAlertResponse) SetReference(v string)`

SetReference sets Reference field to given value.


### GetInterval

`func (o *DeadlineAlertResponse) GetInterval() string`

GetInterval returns the Interval field if non-nil, zero value otherwise.

### GetIntervalOk

`func (o *DeadlineAlertResponse) GetIntervalOk() (*string, bool)`

GetIntervalOk returns a tuple with the Interval field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInterval

`func (o *DeadlineAlertResponse) SetInterval(v string)`

SetInterval sets Interval field to given value.


### GetCallback

`func (o *DeadlineAlertResponse) GetCallback() string`

GetCallback returns the Callback field if non-nil, zero value otherwise.

### GetCallbackOk

`func (o *DeadlineAlertResponse) GetCallbackOk() (*string, bool)`

GetCallbackOk returns a tuple with the Callback field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCallback

`func (o *DeadlineAlertResponse) SetCallback(v string)`

SetCallback sets Callback field to given value.


### GetCallbackKwargs

`func (o *DeadlineAlertResponse) GetCallbackKwargs() map[string]interface{}`

GetCallbackKwargs returns the CallbackKwargs field if non-nil, zero value otherwise.

### GetCallbackKwargsOk

`func (o *DeadlineAlertResponse) GetCallbackKwargsOk() (*map[string]interface{}, bool)`

GetCallbackKwargsOk returns a tuple with the CallbackKwargs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCallbackKwargs

`func (o *DeadlineAlertResponse) SetCallbackKwargs(v map[string]interface{})`

SetCallbackKwargs sets CallbackKwargs field to given value.

### HasCallbackKwargs

`func (o *DeadlineAlertResponse) HasCallbackKwargs() bool`

HasCallbackKwargs returns a boolean if a field has been set.

### SetCallbackKwargsNil

`func (o *DeadlineAlertResponse) SetCallbackKwargsNil(b bool)`

 SetCallbackKwargsNil sets the value for CallbackKwargs to be an explicit nil

### UnsetCallbackKwargs
`func (o *DeadlineAlertResponse) UnsetCallbackKwargs()`

UnsetCallbackKwargs ensures that no value is present for CallbackKwargs, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


