# XComResponse

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

## Methods

### NewXComResponse

`func NewXComResponse(key string, timestamp time.Time, logicalDate NullableTime, mapIndex int32, taskId string, dagId string, runId string, dagDisplayName string, ) *XComResponse`

NewXComResponse instantiates a new XComResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewXComResponseWithDefaults

`func NewXComResponseWithDefaults() *XComResponse`

NewXComResponseWithDefaults instantiates a new XComResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetKey

`func (o *XComResponse) GetKey() string`

GetKey returns the Key field if non-nil, zero value otherwise.

### GetKeyOk

`func (o *XComResponse) GetKeyOk() (*string, bool)`

GetKeyOk returns a tuple with the Key field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKey

`func (o *XComResponse) SetKey(v string)`

SetKey sets Key field to given value.


### GetTimestamp

`func (o *XComResponse) GetTimestamp() time.Time`

GetTimestamp returns the Timestamp field if non-nil, zero value otherwise.

### GetTimestampOk

`func (o *XComResponse) GetTimestampOk() (*time.Time, bool)`

GetTimestampOk returns a tuple with the Timestamp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimestamp

`func (o *XComResponse) SetTimestamp(v time.Time)`

SetTimestamp sets Timestamp field to given value.


### GetLogicalDate

`func (o *XComResponse) GetLogicalDate() time.Time`

GetLogicalDate returns the LogicalDate field if non-nil, zero value otherwise.

### GetLogicalDateOk

`func (o *XComResponse) GetLogicalDateOk() (*time.Time, bool)`

GetLogicalDateOk returns a tuple with the LogicalDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLogicalDate

`func (o *XComResponse) SetLogicalDate(v time.Time)`

SetLogicalDate sets LogicalDate field to given value.


### SetLogicalDateNil

`func (o *XComResponse) SetLogicalDateNil(b bool)`

 SetLogicalDateNil sets the value for LogicalDate to be an explicit nil

### UnsetLogicalDate
`func (o *XComResponse) UnsetLogicalDate()`

UnsetLogicalDate ensures that no value is present for LogicalDate, not even an explicit nil
### GetMapIndex

`func (o *XComResponse) GetMapIndex() int32`

GetMapIndex returns the MapIndex field if non-nil, zero value otherwise.

### GetMapIndexOk

`func (o *XComResponse) GetMapIndexOk() (*int32, bool)`

GetMapIndexOk returns a tuple with the MapIndex field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMapIndex

`func (o *XComResponse) SetMapIndex(v int32)`

SetMapIndex sets MapIndex field to given value.


### GetTaskId

`func (o *XComResponse) GetTaskId() string`

GetTaskId returns the TaskId field if non-nil, zero value otherwise.

### GetTaskIdOk

`func (o *XComResponse) GetTaskIdOk() (*string, bool)`

GetTaskIdOk returns a tuple with the TaskId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaskId

`func (o *XComResponse) SetTaskId(v string)`

SetTaskId sets TaskId field to given value.


### GetDagId

`func (o *XComResponse) GetDagId() string`

GetDagId returns the DagId field if non-nil, zero value otherwise.

### GetDagIdOk

`func (o *XComResponse) GetDagIdOk() (*string, bool)`

GetDagIdOk returns a tuple with the DagId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDagId

`func (o *XComResponse) SetDagId(v string)`

SetDagId sets DagId field to given value.


### GetRunId

`func (o *XComResponse) GetRunId() string`

GetRunId returns the RunId field if non-nil, zero value otherwise.

### GetRunIdOk

`func (o *XComResponse) GetRunIdOk() (*string, bool)`

GetRunIdOk returns a tuple with the RunId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRunId

`func (o *XComResponse) SetRunId(v string)`

SetRunId sets RunId field to given value.


### GetDagDisplayName

`func (o *XComResponse) GetDagDisplayName() string`

GetDagDisplayName returns the DagDisplayName field if non-nil, zero value otherwise.

### GetDagDisplayNameOk

`func (o *XComResponse) GetDagDisplayNameOk() (*string, bool)`

GetDagDisplayNameOk returns a tuple with the DagDisplayName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDagDisplayName

`func (o *XComResponse) SetDagDisplayName(v string)`

SetDagDisplayName sets DagDisplayName field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


