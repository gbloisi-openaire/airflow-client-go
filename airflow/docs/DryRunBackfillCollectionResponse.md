# DryRunBackfillCollectionResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Backfills** | [**[]DryRunBackfillResponse**](DryRunBackfillResponse.md) |  | 
**TotalEntries** | **int32** |  | 

## Methods

### NewDryRunBackfillCollectionResponse

`func NewDryRunBackfillCollectionResponse(backfills []DryRunBackfillResponse, totalEntries int32, ) *DryRunBackfillCollectionResponse`

NewDryRunBackfillCollectionResponse instantiates a new DryRunBackfillCollectionResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDryRunBackfillCollectionResponseWithDefaults

`func NewDryRunBackfillCollectionResponseWithDefaults() *DryRunBackfillCollectionResponse`

NewDryRunBackfillCollectionResponseWithDefaults instantiates a new DryRunBackfillCollectionResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBackfills

`func (o *DryRunBackfillCollectionResponse) GetBackfills() []DryRunBackfillResponse`

GetBackfills returns the Backfills field if non-nil, zero value otherwise.

### GetBackfillsOk

`func (o *DryRunBackfillCollectionResponse) GetBackfillsOk() (*[]DryRunBackfillResponse, bool)`

GetBackfillsOk returns a tuple with the Backfills field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBackfills

`func (o *DryRunBackfillCollectionResponse) SetBackfills(v []DryRunBackfillResponse)`

SetBackfills sets Backfills field to given value.


### GetTotalEntries

`func (o *DryRunBackfillCollectionResponse) GetTotalEntries() int32`

GetTotalEntries returns the TotalEntries field if non-nil, zero value otherwise.

### GetTotalEntriesOk

`func (o *DryRunBackfillCollectionResponse) GetTotalEntriesOk() (*int32, bool)`

GetTotalEntriesOk returns a tuple with the TotalEntries field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalEntries

`func (o *DryRunBackfillCollectionResponse) SetTotalEntries(v int32)`

SetTotalEntries sets TotalEntries field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


