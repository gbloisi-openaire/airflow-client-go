# XComResponseString

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
**Value** | **NullableString** |  | 

## Methods

### NewXComResponseString

`func NewXComResponseString(key string, timestamp time.Time, logicalDate NullableTime, mapIndex int32, taskId string, dagId string, runId string, dagDisplayName string, value NullableString, ) *XComResponseString`

NewXComResponseString instantiates a new XComResponseString object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewXComResponseStringWithDefaults

`func NewXComResponseStringWithDefaults() *XComResponseString`

NewXComResponseStringWithDefaults instantiates a new XComResponseString object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetKey

`func (o *XComResponseString) GetKey() string`

GetKey returns the Key field if non-nil, zero value otherwise.

### GetKeyOk

`func (o *XComResponseString) GetKeyOk() (*string, bool)`

GetKeyOk returns a tuple with the Key field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKey

`func (o *XComResponseString) SetKey(v string)`

SetKey sets Key field to given value.


### GetTimestamp

`func (o *XComResponseString) GetTimestamp() time.Time`

GetTimestamp returns the Timestamp field if non-nil, zero value otherwise.

### GetTimestampOk

`func (o *XComResponseString) GetTimestampOk() (*time.Time, bool)`

GetTimestampOk returns a tuple with the Timestamp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimestamp

`func (o *XComResponseString) SetTimestamp(v time.Time)`

SetTimestamp sets Timestamp field to given value.


### GetLogicalDate

`func (o *XComResponseString) GetLogicalDate() time.Time`

GetLogicalDate returns the LogicalDate field if non-nil, zero value otherwise.

### GetLogicalDateOk

`func (o *XComResponseString) GetLogicalDateOk() (*time.Time, bool)`

GetLogicalDateOk returns a tuple with the LogicalDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLogicalDate

`func (o *XComResponseString) SetLogicalDate(v time.Time)`

SetLogicalDate sets LogicalDate field to given value.


### SetLogicalDateNil

`func (o *XComResponseString) SetLogicalDateNil(b bool)`

 SetLogicalDateNil sets the value for LogicalDate to be an explicit nil

### UnsetLogicalDate
`func (o *XComResponseString) UnsetLogicalDate()`

UnsetLogicalDate ensures that no value is present for LogicalDate, not even an explicit nil
### GetMapIndex

`func (o *XComResponseString) GetMapIndex() int32`

GetMapIndex returns the MapIndex field if non-nil, zero value otherwise.

### GetMapIndexOk

`func (o *XComResponseString) GetMapIndexOk() (*int32, bool)`

GetMapIndexOk returns a tuple with the MapIndex field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMapIndex

`func (o *XComResponseString) SetMapIndex(v int32)`

SetMapIndex sets MapIndex field to given value.


### GetTaskId

`func (o *XComResponseString) GetTaskId() string`

GetTaskId returns the TaskId field if non-nil, zero value otherwise.

### GetTaskIdOk

`func (o *XComResponseString) GetTaskIdOk() (*string, bool)`

GetTaskIdOk returns a tuple with the TaskId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaskId

`func (o *XComResponseString) SetTaskId(v string)`

SetTaskId sets TaskId field to given value.


### GetDagId

`func (o *XComResponseString) GetDagId() string`

GetDagId returns the DagId field if non-nil, zero value otherwise.

### GetDagIdOk

`func (o *XComResponseString) GetDagIdOk() (*string, bool)`

GetDagIdOk returns a tuple with the DagId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDagId

`func (o *XComResponseString) SetDagId(v string)`

SetDagId sets DagId field to given value.


### GetRunId

`func (o *XComResponseString) GetRunId() string`

GetRunId returns the RunId field if non-nil, zero value otherwise.

### GetRunIdOk

`func (o *XComResponseString) GetRunIdOk() (*string, bool)`

GetRunIdOk returns a tuple with the RunId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRunId

`func (o *XComResponseString) SetRunId(v string)`

SetRunId sets RunId field to given value.


### GetDagDisplayName

`func (o *XComResponseString) GetDagDisplayName() string`

GetDagDisplayName returns the DagDisplayName field if non-nil, zero value otherwise.

### GetDagDisplayNameOk

`func (o *XComResponseString) GetDagDisplayNameOk() (*string, bool)`

GetDagDisplayNameOk returns a tuple with the DagDisplayName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDagDisplayName

`func (o *XComResponseString) SetDagDisplayName(v string)`

SetDagDisplayName sets DagDisplayName field to given value.


### GetValue

`func (o *XComResponseString) GetValue() string`

GetValue returns the Value field if non-nil, zero value otherwise.

### GetValueOk

`func (o *XComResponseString) GetValueOk() (*string, bool)`

GetValueOk returns a tuple with the Value field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValue

`func (o *XComResponseString) SetValue(v string)`

SetValue sets Value field to given value.


### SetValueNil

`func (o *XComResponseString) SetValueNil(b bool)`

 SetValueNil sets the value for Value to be an explicit nil

### UnsetValue
`func (o *XComResponseString) UnsetValue()`

UnsetValue ensures that no value is present for Value, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


