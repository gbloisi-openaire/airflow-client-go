# PluginCollectionResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Plugins** | [**[]PluginResponse**](PluginResponse.md) |  | 
**TotalEntries** | **int32** |  | 

## Methods

### NewPluginCollectionResponse

`func NewPluginCollectionResponse(plugins []PluginResponse, totalEntries int32, ) *PluginCollectionResponse`

NewPluginCollectionResponse instantiates a new PluginCollectionResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPluginCollectionResponseWithDefaults

`func NewPluginCollectionResponseWithDefaults() *PluginCollectionResponse`

NewPluginCollectionResponseWithDefaults instantiates a new PluginCollectionResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPlugins

`func (o *PluginCollectionResponse) GetPlugins() []PluginResponse`

GetPlugins returns the Plugins field if non-nil, zero value otherwise.

### GetPluginsOk

`func (o *PluginCollectionResponse) GetPluginsOk() (*[]PluginResponse, bool)`

GetPluginsOk returns a tuple with the Plugins field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlugins

`func (o *PluginCollectionResponse) SetPlugins(v []PluginResponse)`

SetPlugins sets Plugins field to given value.


### GetTotalEntries

`func (o *PluginCollectionResponse) GetTotalEntries() int32`

GetTotalEntries returns the TotalEntries field if non-nil, zero value otherwise.

### GetTotalEntriesOk

`func (o *PluginCollectionResponse) GetTotalEntriesOk() (*int32, bool)`

GetTotalEntriesOk returns a tuple with the TotalEntries field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalEntries

`func (o *PluginCollectionResponse) SetTotalEntries(v int32)`

SetTotalEntries sets TotalEntries field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


