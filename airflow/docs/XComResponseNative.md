# XComResponseNative

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Key** | **string** |  | 
**Timestamp** | **time.Time** |  | 
**LogicalDate** | **NullableTime** |  | 
**MapIndex** | **int32** |  | 
**TaskId** | **string** |  | 
**DagId** | **string** |  | 
**RunId** | **string** |  | 
**DagDisplayName** | **string** |  | 
**Value** | **interface{}** |  | 

## Methods

### NewXComResponseNative

`func NewXComResponseNative(key string, timestamp time.Time, logicalDate NullableTime, mapIndex int32, taskId string, dagId string, runId string, dagDisplayName string, value interface{}, ) *XComResponseNative`

NewXComResponseNative instantiates a new XComResponseNative object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewXComResponseNativeWithDefaults

`func NewXComResponseNativeWithDefaults() *XComResponseNative`

NewXComResponseNativeWithDefaults instantiates a new XComResponseNative object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetKey

`func (o *XComResponseNative) GetKey() string`

GetKey returns the Key field if non-nil, zero value otherwise.

### GetKeyOk

`func (o *XComResponseNative) GetKeyOk() (*string, bool)`

GetKeyOk returns a tuple with the Key field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKey

`func (o *XComResponseNative) SetKey(v string)`

SetKey sets Key field to given value.


### GetTimestamp

`func (o *XComResponseNative) GetTimestamp() time.Time`

GetTimestamp returns the Timestamp field if non-nil, zero value otherwise.

### GetTimestampOk

`func (o *XComResponseNative) GetTimestampOk() (*time.Time, bool)`

GetTimestampOk returns a tuple with the Timestamp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimestamp

`func (o *XComResponseNative) SetTimestamp(v time.Time)`

SetTimestamp sets Timestamp field to given value.


### GetLogicalDate

`func (o *XComResponseNative) GetLogicalDate() time.Time`

GetLogicalDate returns the LogicalDate field if non-nil, zero value otherwise.

### GetLogicalDateOk

`func (o *XComResponseNative) GetLogicalDateOk() (*time.Time, bool)`

GetLogicalDateOk returns a tuple with the LogicalDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLogicalDate

`func (o *XComResponseNative) SetLogicalDate(v time.Time)`

SetLogicalDate sets LogicalDate field to given value.


### SetLogicalDateNil

`func (o *XComResponseNative) SetLogicalDateNil(b bool)`

 SetLogicalDateNil sets the value for LogicalDate to be an explicit nil

### UnsetLogicalDate
`func (o *XComResponseNative) UnsetLogicalDate()`

UnsetLogicalDate ensures that no value is present for LogicalDate, not even an explicit nil
### GetMapIndex

`func (o *XComResponseNative) GetMapIndex() int32`

GetMapIndex returns the MapIndex field if non-nil, zero value otherwise.

### GetMapIndexOk

`func (o *XComResponseNative) GetMapIndexOk() (*int32, bool)`

GetMapIndexOk returns a tuple with the MapIndex field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMapIndex

`func (o *XComResponseNative) SetMapIndex(v int32)`

SetMapIndex sets MapIndex field to given value.


### GetTaskId

`func (o *XComResponseNative) GetTaskId() string`

GetTaskId returns the TaskId field if non-nil, zero value otherwise.

### GetTaskIdOk

`func (o *XComResponseNative) GetTaskIdOk() (*string, bool)`

GetTaskIdOk returns a tuple with the TaskId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaskId

`func (o *XComResponseNative) SetTaskId(v string)`

SetTaskId sets TaskId field to given value.


### GetDagId

`func (o *XComResponseNative) GetDagId() string`

GetDagId returns the DagId field if non-nil, zero value otherwise.

### GetDagIdOk

`func (o *XComResponseNative) GetDagIdOk() (*string, bool)`

GetDagIdOk returns a tuple with the DagId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDagId

`func (o *XComResponseNative) SetDagId(v string)`

SetDagId sets DagId field to given value.


### GetRunId

`func (o *XComResponseNative) GetRunId() string`

GetRunId returns the RunId field if non-nil, zero value otherwise.

### GetRunIdOk

`func (o *XComResponseNative) GetRunIdOk() (*string, bool)`

GetRunIdOk returns a tuple with the RunId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRunId

`func (o *XComResponseNative) SetRunId(v string)`

SetRunId sets RunId field to given value.


### GetDagDisplayName

`func (o *XComResponseNative) GetDagDisplayName() string`

GetDagDisplayName returns the DagDisplayName field if non-nil, zero value otherwise.

### GetDagDisplayNameOk

`func (o *XComResponseNative) GetDagDisplayNameOk() (*string, bool)`

GetDagDisplayNameOk returns a tuple with the DagDisplayName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDagDisplayName

`func (o *XComResponseNative) SetDagDisplayName(v string)`

SetDagDisplayName sets DagDisplayName field to given value.


### GetValue

`func (o *XComResponseNative) GetValue() interface{}`

GetValue returns the Value field if non-nil, zero value otherwise.

### GetValueOk

`func (o *XComResponseNative) GetValueOk() (*interface{}, bool)`

GetValueOk returns a tuple with the Value field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValue

`func (o *XComResponseNative) SetValue(v interface{})`

SetValue sets Value field to given value.


### SetValueNil

`func (o *XComResponseNative) SetValueNil(b bool)`

 SetValueNil sets the value for Value to be an explicit nil

### UnsetValue
`func (o *XComResponseNative) UnsetValue()`

UnsetValue ensures that no value is present for Value, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


