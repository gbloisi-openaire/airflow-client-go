# XComCollectionResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**XcomEntries** | [**[]XComResponse**](XComResponse.md) |  | 
**TotalEntries** | **int32** |  | 

## Methods

### NewXComCollectionResponse

`func NewXComCollectionResponse(xcomEntries []XComResponse, totalEntries int32, ) *XComCollectionResponse`

NewXComCollectionResponse instantiates a new XComCollectionResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewXComCollectionResponseWithDefaults

`func NewXComCollectionResponseWithDefaults() *XComCollectionResponse`

NewXComCollectionResponseWithDefaults instantiates a new XComCollectionResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetXcomEntries

`func (o *XComCollectionResponse) GetXcomEntries() []XComResponse`

GetXcomEntries returns the XcomEntries field if non-nil, zero value otherwise.

### GetXcomEntriesOk

`func (o *XComCollectionResponse) GetXcomEntriesOk() (*[]XComResponse, bool)`

GetXcomEntriesOk returns a tuple with the XcomEntries field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetXcomEntries

`func (o *XComCollectionResponse) SetXcomEntries(v []XComResponse)`

SetXcomEntries sets XcomEntries field to given value.


### GetTotalEntries

`func (o *XComCollectionResponse) GetTotalEntries() int32`

GetTotalEntries returns the TotalEntries field if non-nil, zero value otherwise.

### GetTotalEntriesOk

`func (o *XComCollectionResponse) GetTotalEntriesOk() (*int32, bool)`

GetTotalEntriesOk returns a tuple with the TotalEntries field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalEntries

`func (o *XComCollectionResponse) SetTotalEntries(v int32)`

SetTotalEntries sets TotalEntries field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


