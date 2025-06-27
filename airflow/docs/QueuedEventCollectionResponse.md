# QueuedEventCollectionResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**QueuedEvents** | [**[]QueuedEventResponse**](QueuedEventResponse.md) |  | 
**TotalEntries** | **int32** |  | 

## Methods

### NewQueuedEventCollectionResponse

`func NewQueuedEventCollectionResponse(queuedEvents []QueuedEventResponse, totalEntries int32, ) *QueuedEventCollectionResponse`

NewQueuedEventCollectionResponse instantiates a new QueuedEventCollectionResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewQueuedEventCollectionResponseWithDefaults

`func NewQueuedEventCollectionResponseWithDefaults() *QueuedEventCollectionResponse`

NewQueuedEventCollectionResponseWithDefaults instantiates a new QueuedEventCollectionResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetQueuedEvents

`func (o *QueuedEventCollectionResponse) GetQueuedEvents() []QueuedEventResponse`

GetQueuedEvents returns the QueuedEvents field if non-nil, zero value otherwise.

### GetQueuedEventsOk

`func (o *QueuedEventCollectionResponse) GetQueuedEventsOk() (*[]QueuedEventResponse, bool)`

GetQueuedEventsOk returns a tuple with the QueuedEvents field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQueuedEvents

`func (o *QueuedEventCollectionResponse) SetQueuedEvents(v []QueuedEventResponse)`

SetQueuedEvents sets QueuedEvents field to given value.


### GetTotalEntries

`func (o *QueuedEventCollectionResponse) GetTotalEntries() int32`

GetTotalEntries returns the TotalEntries field if non-nil, zero value otherwise.

### GetTotalEntriesOk

`func (o *QueuedEventCollectionResponse) GetTotalEntriesOk() (*int32, bool)`

GetTotalEntriesOk returns a tuple with the TotalEntries field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalEntries

`func (o *QueuedEventCollectionResponse) SetTotalEntries(v int32)`

SetTotalEntries sets TotalEntries field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


