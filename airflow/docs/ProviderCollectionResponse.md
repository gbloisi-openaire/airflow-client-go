# ProviderCollectionResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Providers** | [**[]ProviderResponse**](ProviderResponse.md) |  | 
**TotalEntries** | **int32** |  | 

## Methods

### NewProviderCollectionResponse

`func NewProviderCollectionResponse(providers []ProviderResponse, totalEntries int32, ) *ProviderCollectionResponse`

NewProviderCollectionResponse instantiates a new ProviderCollectionResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProviderCollectionResponseWithDefaults

`func NewProviderCollectionResponseWithDefaults() *ProviderCollectionResponse`

NewProviderCollectionResponseWithDefaults instantiates a new ProviderCollectionResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProviders

`func (o *ProviderCollectionResponse) GetProviders() []ProviderResponse`

GetProviders returns the Providers field if non-nil, zero value otherwise.

### GetProvidersOk

`func (o *ProviderCollectionResponse) GetProvidersOk() (*[]ProviderResponse, bool)`

GetProvidersOk returns a tuple with the Providers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProviders

`func (o *ProviderCollectionResponse) SetProviders(v []ProviderResponse)`

SetProviders sets Providers field to given value.


### GetTotalEntries

`func (o *ProviderCollectionResponse) GetTotalEntries() int32`

GetTotalEntries returns the TotalEntries field if non-nil, zero value otherwise.

### GetTotalEntriesOk

`func (o *ProviderCollectionResponse) GetTotalEntriesOk() (*int32, bool)`

GetTotalEntriesOk returns a tuple with the TotalEntries field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalEntries

`func (o *ProviderCollectionResponse) SetTotalEntries(v int32)`

SetTotalEntries sets TotalEntries field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


