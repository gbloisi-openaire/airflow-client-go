# EventLogCollectionResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**EventLogs** | [**[]EventLogResponse**](EventLogResponse.md) |  | 
**TotalEntries** | **int32** |  | 

## Methods

### NewEventLogCollectionResponse

`func NewEventLogCollectionResponse(eventLogs []EventLogResponse, totalEntries int32, ) *EventLogCollectionResponse`

NewEventLogCollectionResponse instantiates a new EventLogCollectionResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewEventLogCollectionResponseWithDefaults

`func NewEventLogCollectionResponseWithDefaults() *EventLogCollectionResponse`

NewEventLogCollectionResponseWithDefaults instantiates a new EventLogCollectionResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetEventLogs

`func (o *EventLogCollectionResponse) GetEventLogs() []EventLogResponse`

GetEventLogs returns the EventLogs field if non-nil, zero value otherwise.

### GetEventLogsOk

`func (o *EventLogCollectionResponse) GetEventLogsOk() (*[]EventLogResponse, bool)`

GetEventLogsOk returns a tuple with the EventLogs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEventLogs

`func (o *EventLogCollectionResponse) SetEventLogs(v []EventLogResponse)`

SetEventLogs sets EventLogs field to given value.


### GetTotalEntries

`func (o *EventLogCollectionResponse) GetTotalEntries() int32`

GetTotalEntries returns the TotalEntries field if non-nil, zero value otherwise.

### GetTotalEntriesOk

`func (o *EventLogCollectionResponse) GetTotalEntriesOk() (*int32, bool)`

GetTotalEntriesOk returns a tuple with the TotalEntries field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalEntries

`func (o *EventLogCollectionResponse) SetTotalEntries(v int32)`

SetTotalEntries sets TotalEntries field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


