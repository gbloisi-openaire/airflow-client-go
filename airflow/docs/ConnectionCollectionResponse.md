# ConnectionCollectionResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Connections** | [**[]ConnectionResponse**](ConnectionResponse.md) |  | 
**TotalEntries** | **int32** |  | 

## Methods

### NewConnectionCollectionResponse

`func NewConnectionCollectionResponse(connections []ConnectionResponse, totalEntries int32, ) *ConnectionCollectionResponse`

NewConnectionCollectionResponse instantiates a new ConnectionCollectionResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewConnectionCollectionResponseWithDefaults

`func NewConnectionCollectionResponseWithDefaults() *ConnectionCollectionResponse`

NewConnectionCollectionResponseWithDefaults instantiates a new ConnectionCollectionResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetConnections

`func (o *ConnectionCollectionResponse) GetConnections() []ConnectionResponse`

GetConnections returns the Connections field if non-nil, zero value otherwise.

### GetConnectionsOk

`func (o *ConnectionCollectionResponse) GetConnectionsOk() (*[]ConnectionResponse, bool)`

GetConnectionsOk returns a tuple with the Connections field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConnections

`func (o *ConnectionCollectionResponse) SetConnections(v []ConnectionResponse)`

SetConnections sets Connections field to given value.


### GetTotalEntries

`func (o *ConnectionCollectionResponse) GetTotalEntries() int32`

GetTotalEntries returns the TotalEntries field if non-nil, zero value otherwise.

### GetTotalEntriesOk

`func (o *ConnectionCollectionResponse) GetTotalEntriesOk() (*int32, bool)`

GetTotalEntriesOk returns a tuple with the TotalEntries field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalEntries

`func (o *ConnectionCollectionResponse) SetTotalEntries(v int32)`

SetTotalEntries sets TotalEntries field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


