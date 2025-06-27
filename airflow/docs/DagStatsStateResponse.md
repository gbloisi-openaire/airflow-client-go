# DagStatsStateResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**State** | [**DagRunState**](DagRunState.md) |  | 
**Count** | **int32** |  | 

## Methods

### NewDagStatsStateResponse

`func NewDagStatsStateResponse(state DagRunState, count int32, ) *DagStatsStateResponse`

NewDagStatsStateResponse instantiates a new DagStatsStateResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDagStatsStateResponseWithDefaults

`func NewDagStatsStateResponseWithDefaults() *DagStatsStateResponse`

NewDagStatsStateResponseWithDefaults instantiates a new DagStatsStateResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetState

`func (o *DagStatsStateResponse) GetState() DagRunState`

GetState returns the State field if non-nil, zero value otherwise.

### GetStateOk

`func (o *DagStatsStateResponse) GetStateOk() (*DagRunState, bool)`

GetStateOk returns a tuple with the State field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetState

`func (o *DagStatsStateResponse) SetState(v DagRunState)`

SetState sets State field to given value.


### GetCount

`func (o *DagStatsStateResponse) GetCount() int32`

GetCount returns the Count field if non-nil, zero value otherwise.

### GetCountOk

`func (o *DagStatsStateResponse) GetCountOk() (*int32, bool)`

GetCountOk returns a tuple with the Count field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCount

`func (o *DagStatsStateResponse) SetCount(v int32)`

SetCount sets Count field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


