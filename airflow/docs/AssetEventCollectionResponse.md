# AssetEventCollectionResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AssetEvents** | [**[]AssetEventResponse**](AssetEventResponse.md) |  | 
**TotalEntries** | **int32** |  | 

## Methods

### NewAssetEventCollectionResponse

`func NewAssetEventCollectionResponse(assetEvents []AssetEventResponse, totalEntries int32, ) *AssetEventCollectionResponse`

NewAssetEventCollectionResponse instantiates a new AssetEventCollectionResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAssetEventCollectionResponseWithDefaults

`func NewAssetEventCollectionResponseWithDefaults() *AssetEventCollectionResponse`

NewAssetEventCollectionResponseWithDefaults instantiates a new AssetEventCollectionResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAssetEvents

`func (o *AssetEventCollectionResponse) GetAssetEvents() []AssetEventResponse`

GetAssetEvents returns the AssetEvents field if non-nil, zero value otherwise.

### GetAssetEventsOk

`func (o *AssetEventCollectionResponse) GetAssetEventsOk() (*[]AssetEventResponse, bool)`

GetAssetEventsOk returns a tuple with the AssetEvents field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssetEvents

`func (o *AssetEventCollectionResponse) SetAssetEvents(v []AssetEventResponse)`

SetAssetEvents sets AssetEvents field to given value.


### GetTotalEntries

`func (o *AssetEventCollectionResponse) GetTotalEntries() int32`

GetTotalEntries returns the TotalEntries field if non-nil, zero value otherwise.

### GetTotalEntriesOk

`func (o *AssetEventCollectionResponse) GetTotalEntriesOk() (*int32, bool)`

GetTotalEntriesOk returns a tuple with the TotalEntries field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalEntries

`func (o *AssetEventCollectionResponse) SetTotalEntries(v int32)`

SetTotalEntries sets TotalEntries field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


