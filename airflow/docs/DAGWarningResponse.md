# DAGWarningResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DagId** | **string** |  | 
**WarningType** | [**DagWarningType**](DagWarningType.md) |  | 
**Message** | **string** |  | 
**Timestamp** | **time.Time** |  | 

## Methods

### NewDAGWarningResponse

`func NewDAGWarningResponse(dagId string, warningType DagWarningType, message string, timestamp time.Time, ) *DAGWarningResponse`

NewDAGWarningResponse instantiates a new DAGWarningResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDAGWarningResponseWithDefaults

`func NewDAGWarningResponseWithDefaults() *DAGWarningResponse`

NewDAGWarningResponseWithDefaults instantiates a new DAGWarningResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDagId

`func (o *DAGWarningResponse) GetDagId() string`

GetDagId returns the DagId field if non-nil, zero value otherwise.

### GetDagIdOk

`func (o *DAGWarningResponse) GetDagIdOk() (*string, bool)`

GetDagIdOk returns a tuple with the DagId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDagId

`func (o *DAGWarningResponse) SetDagId(v string)`

SetDagId sets DagId field to given value.


### GetWarningType

`func (o *DAGWarningResponse) GetWarningType() DagWarningType`

GetWarningType returns the WarningType field if non-nil, zero value otherwise.

### GetWarningTypeOk

`func (o *DAGWarningResponse) GetWarningTypeOk() (*DagWarningType, bool)`

GetWarningTypeOk returns a tuple with the WarningType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWarningType

`func (o *DAGWarningResponse) SetWarningType(v DagWarningType)`

SetWarningType sets WarningType field to given value.


### GetMessage

`func (o *DAGWarningResponse) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *DAGWarningResponse) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *DAGWarningResponse) SetMessage(v string)`

SetMessage sets Message field to given value.


### GetTimestamp

`func (o *DAGWarningResponse) GetTimestamp() time.Time`

GetTimestamp returns the Timestamp field if non-nil, zero value otherwise.

### GetTimestampOk

`func (o *DAGWarningResponse) GetTimestampOk() (*time.Time, bool)`

GetTimestampOk returns a tuple with the Timestamp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimestamp

`func (o *DAGWarningResponse) SetTimestamp(v time.Time)`

SetTimestamp sets Timestamp field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


