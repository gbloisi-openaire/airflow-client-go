# BulkResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Create** | Pointer to [**NullableBulkActionResponse**](BulkActionResponse.md) |  | [optional] 
**Update** | Pointer to [**NullableBulkActionResponse**](BulkActionResponse.md) |  | [optional] 
**Delete** | Pointer to [**NullableBulkActionResponse**](BulkActionResponse.md) |  | [optional] 

## Methods

### NewBulkResponse

`func NewBulkResponse() *BulkResponse`

NewBulkResponse instantiates a new BulkResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewBulkResponseWithDefaults

`func NewBulkResponseWithDefaults() *BulkResponse`

NewBulkResponseWithDefaults instantiates a new BulkResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCreate

`func (o *BulkResponse) GetCreate() BulkActionResponse`

GetCreate returns the Create field if non-nil, zero value otherwise.

### GetCreateOk

`func (o *BulkResponse) GetCreateOk() (*BulkActionResponse, bool)`

GetCreateOk returns a tuple with the Create field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreate

`func (o *BulkResponse) SetCreate(v BulkActionResponse)`

SetCreate sets Create field to given value.

### HasCreate

`func (o *BulkResponse) HasCreate() bool`

HasCreate returns a boolean if a field has been set.

### SetCreateNil

`func (o *BulkResponse) SetCreateNil(b bool)`

 SetCreateNil sets the value for Create to be an explicit nil

### UnsetCreate
`func (o *BulkResponse) UnsetCreate()`

UnsetCreate ensures that no value is present for Create, not even an explicit nil
### GetUpdate

`func (o *BulkResponse) GetUpdate() BulkActionResponse`

GetUpdate returns the Update field if non-nil, zero value otherwise.

### GetUpdateOk

`func (o *BulkResponse) GetUpdateOk() (*BulkActionResponse, bool)`

GetUpdateOk returns a tuple with the Update field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdate

`func (o *BulkResponse) SetUpdate(v BulkActionResponse)`

SetUpdate sets Update field to given value.

### HasUpdate

`func (o *BulkResponse) HasUpdate() bool`

HasUpdate returns a boolean if a field has been set.

### SetUpdateNil

`func (o *BulkResponse) SetUpdateNil(b bool)`

 SetUpdateNil sets the value for Update to be an explicit nil

### UnsetUpdate
`func (o *BulkResponse) UnsetUpdate()`

UnsetUpdate ensures that no value is present for Update, not even an explicit nil
### GetDelete

`func (o *BulkResponse) GetDelete() BulkActionResponse`

GetDelete returns the Delete field if non-nil, zero value otherwise.

### GetDeleteOk

`func (o *BulkResponse) GetDeleteOk() (*BulkActionResponse, bool)`

GetDeleteOk returns a tuple with the Delete field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDelete

`func (o *BulkResponse) SetDelete(v BulkActionResponse)`

SetDelete sets Delete field to given value.

### HasDelete

`func (o *BulkResponse) HasDelete() bool`

HasDelete returns a boolean if a field has been set.

### SetDeleteNil

`func (o *BulkResponse) SetDeleteNil(b bool)`

 SetDeleteNil sets the value for Delete to be an explicit nil

### UnsetDelete
`func (o *BulkResponse) UnsetDelete()`

UnsetDelete ensures that no value is present for Delete, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


