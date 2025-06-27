# PluginImportErrorCollectionResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ImportErrors** | [**[]PluginImportErrorResponse**](PluginImportErrorResponse.md) |  | 
**TotalEntries** | **int32** |  | 

## Methods

### NewPluginImportErrorCollectionResponse

`func NewPluginImportErrorCollectionResponse(importErrors []PluginImportErrorResponse, totalEntries int32, ) *PluginImportErrorCollectionResponse`

NewPluginImportErrorCollectionResponse instantiates a new PluginImportErrorCollectionResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPluginImportErrorCollectionResponseWithDefaults

`func NewPluginImportErrorCollectionResponseWithDefaults() *PluginImportErrorCollectionResponse`

NewPluginImportErrorCollectionResponseWithDefaults instantiates a new PluginImportErrorCollectionResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetImportErrors

`func (o *PluginImportErrorCollectionResponse) GetImportErrors() []PluginImportErrorResponse`

GetImportErrors returns the ImportErrors field if non-nil, zero value otherwise.

### GetImportErrorsOk

`func (o *PluginImportErrorCollectionResponse) GetImportErrorsOk() (*[]PluginImportErrorResponse, bool)`

GetImportErrorsOk returns a tuple with the ImportErrors field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImportErrors

`func (o *PluginImportErrorCollectionResponse) SetImportErrors(v []PluginImportErrorResponse)`

SetImportErrors sets ImportErrors field to given value.


### GetTotalEntries

`func (o *PluginImportErrorCollectionResponse) GetTotalEntries() int32`

GetTotalEntries returns the TotalEntries field if non-nil, zero value otherwise.

### GetTotalEntriesOk

`func (o *PluginImportErrorCollectionResponse) GetTotalEntriesOk() (*int32, bool)`

GetTotalEntriesOk returns a tuple with the TotalEntries field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalEntries

`func (o *PluginImportErrorCollectionResponse) SetTotalEntries(v int32)`

SetTotalEntries sets TotalEntries field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


