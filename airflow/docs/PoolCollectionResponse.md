# PoolCollectionResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Pools** | [**[]PoolResponse**](PoolResponse.md) |  | 
**TotalEntries** | **int32** |  | 

## Methods

### NewPoolCollectionResponse

`func NewPoolCollectionResponse(pools []PoolResponse, totalEntries int32, ) *PoolCollectionResponse`

NewPoolCollectionResponse instantiates a new PoolCollectionResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPoolCollectionResponseWithDefaults

`func NewPoolCollectionResponseWithDefaults() *PoolCollectionResponse`

NewPoolCollectionResponseWithDefaults instantiates a new PoolCollectionResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPools

`func (o *PoolCollectionResponse) GetPools() []PoolResponse`

GetPools returns the Pools field if non-nil, zero value otherwise.

### GetPoolsOk

`func (o *PoolCollectionResponse) GetPoolsOk() (*[]PoolResponse, bool)`

GetPoolsOk returns a tuple with the Pools field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPools

`func (o *PoolCollectionResponse) SetPools(v []PoolResponse)`

SetPools sets Pools field to given value.


### GetTotalEntries

`func (o *PoolCollectionResponse) GetTotalEntries() int32`

GetTotalEntries returns the TotalEntries field if non-nil, zero value otherwise.

### GetTotalEntriesOk

`func (o *PoolCollectionResponse) GetTotalEntriesOk() (*int32, bool)`

GetTotalEntriesOk returns a tuple with the TotalEntries field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalEntries

`func (o *PoolCollectionResponse) SetTotalEntries(v int32)`

SetTotalEntries sets TotalEntries field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


