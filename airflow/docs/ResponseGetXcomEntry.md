# ResponseGetXcomEntry

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Key** | **string** |  | 
**Timestamp** | **time.Time** |  | 
**LogicalDate** | **time.Time** |  | 
**MapIndex** | **int32** |  | 
**TaskId** | **string** |  | 
**DagId** | **string** |  | 
**RunId** | **string** |  | 
**DagDisplayName** | **string** |  | 
**Value** | **string** |  | 

## Methods

### NewResponseGetXcomEntry

`func NewResponseGetXcomEntry(key string, timestamp time.Time, logicalDate time.Time, mapIndex int32, taskId string, dagId string, runId string, dagDisplayName string, value string, ) *ResponseGetXcomEntry`

NewResponseGetXcomEntry instantiates a new ResponseGetXcomEntry object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewResponseGetXcomEntryWithDefaults

`func NewResponseGetXcomEntryWithDefaults() *ResponseGetXcomEntry`

NewResponseGetXcomEntryWithDefaults instantiates a new ResponseGetXcomEntry object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetKey

`func (o *ResponseGetXcomEntry) GetKey() string`

GetKey returns the Key field if non-nil, zero value otherwise.

### GetKeyOk

`func (o *ResponseGetXcomEntry) GetKeyOk() (*string, bool)`

GetKeyOk returns a tuple with the Key field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKey

`func (o *ResponseGetXcomEntry) SetKey(v string)`

SetKey sets Key field to given value.


### GetTimestamp

`func (o *ResponseGetXcomEntry) GetTimestamp() time.Time`

GetTimestamp returns the Timestamp field if non-nil, zero value otherwise.

### GetTimestampOk

`func (o *ResponseGetXcomEntry) GetTimestampOk() (*time.Time, bool)`

GetTimestampOk returns a tuple with the Timestamp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimestamp

`func (o *ResponseGetXcomEntry) SetTimestamp(v time.Time)`

SetTimestamp sets Timestamp field to given value.


### GetLogicalDate

`func (o *ResponseGetXcomEntry) GetLogicalDate() time.Time`

GetLogicalDate returns the LogicalDate field if non-nil, zero value otherwise.

### GetLogicalDateOk

`func (o *ResponseGetXcomEntry) GetLogicalDateOk() (*time.Time, bool)`

GetLogicalDateOk returns a tuple with the LogicalDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLogicalDate

`func (o *ResponseGetXcomEntry) SetLogicalDate(v time.Time)`

SetLogicalDate sets LogicalDate field to given value.


### GetMapIndex

`func (o *ResponseGetXcomEntry) GetMapIndex() int32`

GetMapIndex returns the MapIndex field if non-nil, zero value otherwise.

### GetMapIndexOk

`func (o *ResponseGetXcomEntry) GetMapIndexOk() (*int32, bool)`

GetMapIndexOk returns a tuple with the MapIndex field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMapIndex

`func (o *ResponseGetXcomEntry) SetMapIndex(v int32)`

SetMapIndex sets MapIndex field to given value.


### GetTaskId

`func (o *ResponseGetXcomEntry) GetTaskId() string`

GetTaskId returns the TaskId field if non-nil, zero value otherwise.

### GetTaskIdOk

`func (o *ResponseGetXcomEntry) GetTaskIdOk() (*string, bool)`

GetTaskIdOk returns a tuple with the TaskId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaskId

`func (o *ResponseGetXcomEntry) SetTaskId(v string)`

SetTaskId sets TaskId field to given value.


### GetDagId

`func (o *ResponseGetXcomEntry) GetDagId() string`

GetDagId returns the DagId field if non-nil, zero value otherwise.

### GetDagIdOk

`func (o *ResponseGetXcomEntry) GetDagIdOk() (*string, bool)`

GetDagIdOk returns a tuple with the DagId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDagId

`func (o *ResponseGetXcomEntry) SetDagId(v string)`

SetDagId sets DagId field to given value.


### GetRunId

`func (o *ResponseGetXcomEntry) GetRunId() string`

GetRunId returns the RunId field if non-nil, zero value otherwise.

### GetRunIdOk

`func (o *ResponseGetXcomEntry) GetRunIdOk() (*string, bool)`

GetRunIdOk returns a tuple with the RunId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRunId

`func (o *ResponseGetXcomEntry) SetRunId(v string)`

SetRunId sets RunId field to given value.


### GetDagDisplayName

`func (o *ResponseGetXcomEntry) GetDagDisplayName() string`

GetDagDisplayName returns the DagDisplayName field if non-nil, zero value otherwise.

### GetDagDisplayNameOk

`func (o *ResponseGetXcomEntry) GetDagDisplayNameOk() (*string, bool)`

GetDagDisplayNameOk returns a tuple with the DagDisplayName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDagDisplayName

`func (o *ResponseGetXcomEntry) SetDagDisplayName(v string)`

SetDagDisplayName sets DagDisplayName field to given value.


### GetValue

`func (o *ResponseGetXcomEntry) GetValue() string`

GetValue returns the Value field if non-nil, zero value otherwise.

### GetValueOk

`func (o *ResponseGetXcomEntry) GetValueOk() (*string, bool)`

GetValueOk returns a tuple with the Value field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValue

`func (o *ResponseGetXcomEntry) SetValue(v string)`

SetValue sets Value field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


