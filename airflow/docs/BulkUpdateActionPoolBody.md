# BulkUpdateActionPoolBody

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Action** | **string** | The action to be performed on the entities. | 
**Entities** | [**[]PoolBody**](PoolBody.md) | A list of entities to be updated. | 
**ActionOnNonExistence** | Pointer to [**BulkActionNotOnExistence**](BulkActionNotOnExistence.md) |  | [optional] 

## Methods

### NewBulkUpdateActionPoolBody

`func NewBulkUpdateActionPoolBody(action string, entities []PoolBody, ) *BulkUpdateActionPoolBody`

NewBulkUpdateActionPoolBody instantiates a new BulkUpdateActionPoolBody object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewBulkUpdateActionPoolBodyWithDefaults

`func NewBulkUpdateActionPoolBodyWithDefaults() *BulkUpdateActionPoolBody`

NewBulkUpdateActionPoolBodyWithDefaults instantiates a new BulkUpdateActionPoolBody object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAction

`func (o *BulkUpdateActionPoolBody) GetAction() string`

GetAction returns the Action field if non-nil, zero value otherwise.

### GetActionOk

`func (o *BulkUpdateActionPoolBody) GetActionOk() (*string, bool)`

GetActionOk returns a tuple with the Action field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAction

`func (o *BulkUpdateActionPoolBody) SetAction(v string)`

SetAction sets Action field to given value.


### GetEntities

`func (o *BulkUpdateActionPoolBody) GetEntities() []PoolBody`

GetEntities returns the Entities field if non-nil, zero value otherwise.

### GetEntitiesOk

`func (o *BulkUpdateActionPoolBody) GetEntitiesOk() (*[]PoolBody, bool)`

GetEntitiesOk returns a tuple with the Entities field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEntities

`func (o *BulkUpdateActionPoolBody) SetEntities(v []PoolBody)`

SetEntities sets Entities field to given value.


### GetActionOnNonExistence

`func (o *BulkUpdateActionPoolBody) GetActionOnNonExistence() BulkActionNotOnExistence`

GetActionOnNonExistence returns the ActionOnNonExistence field if non-nil, zero value otherwise.

### GetActionOnNonExistenceOk

`func (o *BulkUpdateActionPoolBody) GetActionOnNonExistenceOk() (*BulkActionNotOnExistence, bool)`

GetActionOnNonExistenceOk returns a tuple with the ActionOnNonExistence field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActionOnNonExistence

`func (o *BulkUpdateActionPoolBody) SetActionOnNonExistence(v BulkActionNotOnExistence)`

SetActionOnNonExistence sets ActionOnNonExistence field to given value.

### HasActionOnNonExistence

`func (o *BulkUpdateActionPoolBody) HasActionOnNonExistence() bool`

HasActionOnNonExistence returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


