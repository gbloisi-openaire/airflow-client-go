# ImportErrorCollectionResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ImportErrors** | [**[]ImportErrorResponse**](ImportErrorResponse.md) |  | 
**TotalEntries** | **int32** |  | 

## Methods

### NewImportErrorCollectionResponse

`func NewImportErrorCollectionResponse(importErrors []ImportErrorResponse, totalEntries int32, ) *ImportErrorCollectionResponse`

NewImportErrorCollectionResponse instantiates a new ImportErrorCollectionResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewImportErrorCollectionResponseWithDefaults

`func NewImportErrorCollectionResponseWithDefaults() *ImportErrorCollectionResponse`

NewImportErrorCollectionResponseWithDefaults instantiates a new ImportErrorCollectionResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetImportErrors

`func (o *ImportErrorCollectionResponse) GetImportErrors() []ImportErrorResponse`

GetImportErrors returns the ImportErrors field if non-nil, zero value otherwise.

### GetImportErrorsOk

`func (o *ImportErrorCollectionResponse) GetImportErrorsOk() (*[]ImportErrorResponse, bool)`

GetImportErrorsOk returns a tuple with the ImportErrors field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImportErrors

`func (o *ImportErrorCollectionResponse) SetImportErrors(v []ImportErrorResponse)`

SetImportErrors sets ImportErrors field to given value.


### GetTotalEntries

`func (o *ImportErrorCollectionResponse) GetTotalEntries() int32`

GetTotalEntries returns the TotalEntries field if non-nil, zero value otherwise.

### GetTotalEntriesOk

`func (o *ImportErrorCollectionResponse) GetTotalEntriesOk() (*int32, bool)`

GetTotalEntriesOk returns a tuple with the TotalEntries field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalEntries

`func (o *ImportErrorCollectionResponse) SetTotalEntries(v int32)`

SetTotalEntries sets TotalEntries field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


