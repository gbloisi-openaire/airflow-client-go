# TriggerResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **int32** |  | 
**Classpath** | **string** |  | 
**Kwargs** | **string** |  | 
**CreatedDate** | **time.Time** |  | 
**TriggererId** | **NullableInt32** |  | 

## Methods

### NewTriggerResponse

`func NewTriggerResponse(id int32, classpath string, kwargs string, createdDate time.Time, triggererId NullableInt32, ) *TriggerResponse`

NewTriggerResponse instantiates a new TriggerResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTriggerResponseWithDefaults

`func NewTriggerResponseWithDefaults() *TriggerResponse`

NewTriggerResponseWithDefaults instantiates a new TriggerResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *TriggerResponse) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *TriggerResponse) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *TriggerResponse) SetId(v int32)`

SetId sets Id field to given value.


### GetClasspath

`func (o *TriggerResponse) GetClasspath() string`

GetClasspath returns the Classpath field if non-nil, zero value otherwise.

### GetClasspathOk

`func (o *TriggerResponse) GetClasspathOk() (*string, bool)`

GetClasspathOk returns a tuple with the Classpath field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClasspath

`func (o *TriggerResponse) SetClasspath(v string)`

SetClasspath sets Classpath field to given value.


### GetKwargs

`func (o *TriggerResponse) GetKwargs() string`

GetKwargs returns the Kwargs field if non-nil, zero value otherwise.

### GetKwargsOk

`func (o *TriggerResponse) GetKwargsOk() (*string, bool)`

GetKwargsOk returns a tuple with the Kwargs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKwargs

`func (o *TriggerResponse) SetKwargs(v string)`

SetKwargs sets Kwargs field to given value.


### GetCreatedDate

`func (o *TriggerResponse) GetCreatedDate() time.Time`

GetCreatedDate returns the CreatedDate field if non-nil, zero value otherwise.

### GetCreatedDateOk

`func (o *TriggerResponse) GetCreatedDateOk() (*time.Time, bool)`

GetCreatedDateOk returns a tuple with the CreatedDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedDate

`func (o *TriggerResponse) SetCreatedDate(v time.Time)`

SetCreatedDate sets CreatedDate field to given value.


### GetTriggererId

`func (o *TriggerResponse) GetTriggererId() int32`

GetTriggererId returns the TriggererId field if non-nil, zero value otherwise.

### GetTriggererIdOk

`func (o *TriggerResponse) GetTriggererIdOk() (*int32, bool)`

GetTriggererIdOk returns a tuple with the TriggererId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTriggererId

`func (o *TriggerResponse) SetTriggererId(v int32)`

SetTriggererId sets TriggererId field to given value.


### SetTriggererIdNil

`func (o *TriggerResponse) SetTriggererIdNil(b bool)`

 SetTriggererIdNil sets the value for TriggererId to be an explicit nil

### UnsetTriggererId
`func (o *TriggerResponse) UnsetTriggererId()`

UnsetTriggererId ensures that no value is present for TriggererId, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


