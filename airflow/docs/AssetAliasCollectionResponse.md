# AssetAliasCollectionResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AssetAliases** | [**[]AssetAliasResponse**](AssetAliasResponse.md) |  | 
**TotalEntries** | **int32** |  | 

## Methods

### NewAssetAliasCollectionResponse

`func NewAssetAliasCollectionResponse(assetAliases []AssetAliasResponse, totalEntries int32, ) *AssetAliasCollectionResponse`

NewAssetAliasCollectionResponse instantiates a new AssetAliasCollectionResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAssetAliasCollectionResponseWithDefaults

`func NewAssetAliasCollectionResponseWithDefaults() *AssetAliasCollectionResponse`

NewAssetAliasCollectionResponseWithDefaults instantiates a new AssetAliasCollectionResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAssetAliases

`func (o *AssetAliasCollectionResponse) GetAssetAliases() []AssetAliasResponse`

GetAssetAliases returns the AssetAliases field if non-nil, zero value otherwise.

### GetAssetAliasesOk

`func (o *AssetAliasCollectionResponse) GetAssetAliasesOk() (*[]AssetAliasResponse, bool)`

GetAssetAliasesOk returns a tuple with the AssetAliases field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssetAliases

`func (o *AssetAliasCollectionResponse) SetAssetAliases(v []AssetAliasResponse)`

SetAssetAliases sets AssetAliases field to given value.


### GetTotalEntries

`func (o *AssetAliasCollectionResponse) GetTotalEntries() int32`

GetTotalEntries returns the TotalEntries field if non-nil, zero value otherwise.

### GetTotalEntriesOk

`func (o *AssetAliasCollectionResponse) GetTotalEntriesOk() (*int32, bool)`

GetTotalEntriesOk returns a tuple with the TotalEntries field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalEntries

`func (o *AssetAliasCollectionResponse) SetTotalEntries(v int32)`

SetTotalEntries sets TotalEntries field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


