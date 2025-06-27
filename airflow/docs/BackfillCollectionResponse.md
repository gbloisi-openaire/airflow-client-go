# BackfillCollectionResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Backfills** | [**[]BackfillResponse**](BackfillResponse.md) |  | 
**TotalEntries** | **int32** |  | 

## Methods

### NewBackfillCollectionResponse

`func NewBackfillCollectionResponse(backfills []BackfillResponse, totalEntries int32, ) *BackfillCollectionResponse`

NewBackfillCollectionResponse instantiates a new BackfillCollectionResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewBackfillCollectionResponseWithDefaults

`func NewBackfillCollectionResponseWithDefaults() *BackfillCollectionResponse`

NewBackfillCollectionResponseWithDefaults instantiates a new BackfillCollectionResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBackfills

`func (o *BackfillCollectionResponse) GetBackfills() []BackfillResponse`

GetBackfills returns the Backfills field if non-nil, zero value otherwise.

### GetBackfillsOk

`func (o *BackfillCollectionResponse) GetBackfillsOk() (*[]BackfillResponse, bool)`

GetBackfillsOk returns a tuple with the Backfills field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBackfills

`func (o *BackfillCollectionResponse) SetBackfills(v []BackfillResponse)`

SetBackfills sets Backfills field to given value.


### GetTotalEntries

`func (o *BackfillCollectionResponse) GetTotalEntries() int32`

GetTotalEntries returns the TotalEntries field if non-nil, zero value otherwise.

### GetTotalEntriesOk

`func (o *BackfillCollectionResponse) GetTotalEntriesOk() (*int32, bool)`

GetTotalEntriesOk returns a tuple with the TotalEntries field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalEntries

`func (o *BackfillCollectionResponse) SetTotalEntries(v int32)`

SetTotalEntries sets TotalEntries field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


