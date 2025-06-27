# HealthInfoResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Metadatabase** | [**BaseInfoResponse**](BaseInfoResponse.md) |  | 
**Scheduler** | [**SchedulerInfoResponse**](SchedulerInfoResponse.md) |  | 
**Triggerer** | [**TriggererInfoResponse**](TriggererInfoResponse.md) |  | 
**DagProcessor** | Pointer to [**NullableDagProcessorInfoResponse**](DagProcessorInfoResponse.md) |  | [optional] 

## Methods

### NewHealthInfoResponse

`func NewHealthInfoResponse(metadatabase BaseInfoResponse, scheduler SchedulerInfoResponse, triggerer TriggererInfoResponse, ) *HealthInfoResponse`

NewHealthInfoResponse instantiates a new HealthInfoResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewHealthInfoResponseWithDefaults

`func NewHealthInfoResponseWithDefaults() *HealthInfoResponse`

NewHealthInfoResponseWithDefaults instantiates a new HealthInfoResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMetadatabase

`func (o *HealthInfoResponse) GetMetadatabase() BaseInfoResponse`

GetMetadatabase returns the Metadatabase field if non-nil, zero value otherwise.

### GetMetadatabaseOk

`func (o *HealthInfoResponse) GetMetadatabaseOk() (*BaseInfoResponse, bool)`

GetMetadatabaseOk returns a tuple with the Metadatabase field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadatabase

`func (o *HealthInfoResponse) SetMetadatabase(v BaseInfoResponse)`

SetMetadatabase sets Metadatabase field to given value.


### GetScheduler

`func (o *HealthInfoResponse) GetScheduler() SchedulerInfoResponse`

GetScheduler returns the Scheduler field if non-nil, zero value otherwise.

### GetSchedulerOk

`func (o *HealthInfoResponse) GetSchedulerOk() (*SchedulerInfoResponse, bool)`

GetSchedulerOk returns a tuple with the Scheduler field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScheduler

`func (o *HealthInfoResponse) SetScheduler(v SchedulerInfoResponse)`

SetScheduler sets Scheduler field to given value.


### GetTriggerer

`func (o *HealthInfoResponse) GetTriggerer() TriggererInfoResponse`

GetTriggerer returns the Triggerer field if non-nil, zero value otherwise.

### GetTriggererOk

`func (o *HealthInfoResponse) GetTriggererOk() (*TriggererInfoResponse, bool)`

GetTriggererOk returns a tuple with the Triggerer field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTriggerer

`func (o *HealthInfoResponse) SetTriggerer(v TriggererInfoResponse)`

SetTriggerer sets Triggerer field to given value.


### GetDagProcessor

`func (o *HealthInfoResponse) GetDagProcessor() DagProcessorInfoResponse`

GetDagProcessor returns the DagProcessor field if non-nil, zero value otherwise.

### GetDagProcessorOk

`func (o *HealthInfoResponse) GetDagProcessorOk() (*DagProcessorInfoResponse, bool)`

GetDagProcessorOk returns a tuple with the DagProcessor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDagProcessor

`func (o *HealthInfoResponse) SetDagProcessor(v DagProcessorInfoResponse)`

SetDagProcessor sets DagProcessor field to given value.

### HasDagProcessor

`func (o *HealthInfoResponse) HasDagProcessor() bool`

HasDagProcessor returns a boolean if a field has been set.

### SetDagProcessorNil

`func (o *HealthInfoResponse) SetDagProcessorNil(b bool)`

 SetDagProcessorNil sets the value for DagProcessor to be an explicit nil

### UnsetDagProcessor
`func (o *HealthInfoResponse) UnsetDagProcessor()`

UnsetDagProcessor ensures that no value is present for DagProcessor, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


