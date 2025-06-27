# BulkActionResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Success** | Pointer to **[]string** | A list of unique id/key representing successful operations. | [optional] [default to []]
**Errors** | Pointer to **[]map[string]interface{}** | A list of errors encountered during the operation, each containing details about the issue. | [optional] [default to []]

## Methods

### NewBulkActionResponse

`func NewBulkActionResponse() *BulkActionResponse`

NewBulkActionResponse instantiates a new BulkActionResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewBulkActionResponseWithDefaults

`func NewBulkActionResponseWithDefaults() *BulkActionResponse`

NewBulkActionResponseWithDefaults instantiates a new BulkActionResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSuccess

`func (o *BulkActionResponse) GetSuccess() []string`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *BulkActionResponse) GetSuccessOk() (*[]string, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *BulkActionResponse) SetSuccess(v []string)`

SetSuccess sets Success field to given value.

### HasSuccess

`func (o *BulkActionResponse) HasSuccess() bool`

HasSuccess returns a boolean if a field has been set.

### GetErrors

`func (o *BulkActionResponse) GetErrors() []map[string]interface{}`

GetErrors returns the Errors field if non-nil, zero value otherwise.

### GetErrorsOk

`func (o *BulkActionResponse) GetErrorsOk() (*[]map[string]interface{}, bool)`

GetErrorsOk returns a tuple with the Errors field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrors

`func (o *BulkActionResponse) SetErrors(v []map[string]interface{})`

SetErrors sets Errors field to given value.

### HasErrors

`func (o *BulkActionResponse) HasErrors() bool`

HasErrors returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


