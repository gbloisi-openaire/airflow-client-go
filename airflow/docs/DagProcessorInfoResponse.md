# DagProcessorInfoResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Status** | **NullableString** |  | 
**LatestDagProcessorHeartbeat** | **NullableString** |  | 

## Methods

### NewDagProcessorInfoResponse

`func NewDagProcessorInfoResponse(status NullableString, latestDagProcessorHeartbeat NullableString, ) *DagProcessorInfoResponse`

NewDagProcessorInfoResponse instantiates a new DagProcessorInfoResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDagProcessorInfoResponseWithDefaults

`func NewDagProcessorInfoResponseWithDefaults() *DagProcessorInfoResponse`

NewDagProcessorInfoResponseWithDefaults instantiates a new DagProcessorInfoResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetStatus

`func (o *DagProcessorInfoResponse) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *DagProcessorInfoResponse) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *DagProcessorInfoResponse) SetStatus(v string)`

SetStatus sets Status field to given value.


### SetStatusNil

`func (o *DagProcessorInfoResponse) SetStatusNil(b bool)`

 SetStatusNil sets the value for Status to be an explicit nil

### UnsetStatus
`func (o *DagProcessorInfoResponse) UnsetStatus()`

UnsetStatus ensures that no value is present for Status, not even an explicit nil
### GetLatestDagProcessorHeartbeat

`func (o *DagProcessorInfoResponse) GetLatestDagProcessorHeartbeat() string`

GetLatestDagProcessorHeartbeat returns the LatestDagProcessorHeartbeat field if non-nil, zero value otherwise.

### GetLatestDagProcessorHeartbeatOk

`func (o *DagProcessorInfoResponse) GetLatestDagProcessorHeartbeatOk() (*string, bool)`

GetLatestDagProcessorHeartbeatOk returns a tuple with the LatestDagProcessorHeartbeat field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLatestDagProcessorHeartbeat

`func (o *DagProcessorInfoResponse) SetLatestDagProcessorHeartbeat(v string)`

SetLatestDagProcessorHeartbeat sets LatestDagProcessorHeartbeat field to given value.


### SetLatestDagProcessorHeartbeatNil

`func (o *DagProcessorInfoResponse) SetLatestDagProcessorHeartbeatNil(b bool)`

 SetLatestDagProcessorHeartbeatNil sets the value for LatestDagProcessorHeartbeat to be an explicit nil

### UnsetLatestDagProcessorHeartbeat
`func (o *DagProcessorInfoResponse) UnsetLatestDagProcessorHeartbeat()`

UnsetLatestDagProcessorHeartbeat ensures that no value is present for LatestDagProcessorHeartbeat, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


