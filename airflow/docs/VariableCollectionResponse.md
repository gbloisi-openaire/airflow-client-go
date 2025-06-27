# VariableCollectionResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Variables** | [**[]VariableResponse**](VariableResponse.md) |  | 
**TotalEntries** | **int32** |  | 

## Methods

### NewVariableCollectionResponse

`func NewVariableCollectionResponse(variables []VariableResponse, totalEntries int32, ) *VariableCollectionResponse`

NewVariableCollectionResponse instantiates a new VariableCollectionResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewVariableCollectionResponseWithDefaults

`func NewVariableCollectionResponseWithDefaults() *VariableCollectionResponse`

NewVariableCollectionResponseWithDefaults instantiates a new VariableCollectionResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetVariables

`func (o *VariableCollectionResponse) GetVariables() []VariableResponse`

GetVariables returns the Variables field if non-nil, zero value otherwise.

### GetVariablesOk

`func (o *VariableCollectionResponse) GetVariablesOk() (*[]VariableResponse, bool)`

GetVariablesOk returns a tuple with the Variables field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVariables

`func (o *VariableCollectionResponse) SetVariables(v []VariableResponse)`

SetVariables sets Variables field to given value.


### GetTotalEntries

`func (o *VariableCollectionResponse) GetTotalEntries() int32`

GetTotalEntries returns the TotalEntries field if non-nil, zero value otherwise.

### GetTotalEntriesOk

`func (o *VariableCollectionResponse) GetTotalEntriesOk() (*int32, bool)`

GetTotalEntriesOk returns a tuple with the TotalEntries field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalEntries

`func (o *VariableCollectionResponse) SetTotalEntries(v int32)`

SetTotalEntries sets TotalEntries field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


