# AssetCollectionResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Assets** | [**[]AssetResponse**](AssetResponse.md) |  | 
**TotalEntries** | **int32** |  | 

## Methods

### NewAssetCollectionResponse

`func NewAssetCollectionResponse(assets []AssetResponse, totalEntries int32, ) *AssetCollectionResponse`

NewAssetCollectionResponse instantiates a new AssetCollectionResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAssetCollectionResponseWithDefaults

`func NewAssetCollectionResponseWithDefaults() *AssetCollectionResponse`

NewAssetCollectionResponseWithDefaults instantiates a new AssetCollectionResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAssets

`func (o *AssetCollectionResponse) GetAssets() []AssetResponse`

GetAssets returns the Assets field if non-nil, zero value otherwise.

### GetAssetsOk

`func (o *AssetCollectionResponse) GetAssetsOk() (*[]AssetResponse, bool)`

GetAssetsOk returns a tuple with the Assets field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssets

`func (o *AssetCollectionResponse) SetAssets(v []AssetResponse)`

SetAssets sets Assets field to given value.


### GetTotalEntries

`func (o *AssetCollectionResponse) GetTotalEntries() int32`

GetTotalEntries returns the TotalEntries field if non-nil, zero value otherwise.

### GetTotalEntriesOk

`func (o *AssetCollectionResponse) GetTotalEntriesOk() (*int32, bool)`

GetTotalEntriesOk returns a tuple with the TotalEntries field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalEntries

`func (o *AssetCollectionResponse) SetTotalEntries(v int32)`

SetTotalEntries sets TotalEntries field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


