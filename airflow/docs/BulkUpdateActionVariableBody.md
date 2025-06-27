# BulkUpdateActionVariableBody

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Action** | **string** | The action to be performed on the entities. | 
**Entities** | [**[]VariableBody**](VariableBody.md) | A list of entities to be updated. | 
**ActionOnNonExistence** | Pointer to [**BulkActionNotOnExistence**](BulkActionNotOnExistence.md) |  | [optional] 

## Methods

### NewBulkUpdateActionVariableBody

`func NewBulkUpdateActionVariableBody(action string, entities []VariableBody, ) *BulkUpdateActionVariableBody`

NewBulkUpdateActionVariableBody instantiates a new BulkUpdateActionVariableBody object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewBulkUpdateActionVariableBodyWithDefaults

`func NewBulkUpdateActionVariableBodyWithDefaults() *BulkUpdateActionVariableBody`

NewBulkUpdateActionVariableBodyWithDefaults instantiates a new BulkUpdateActionVariableBody object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAction

`func (o *BulkUpdateActionVariableBody) GetAction() string`

GetAction returns the Action field if non-nil, zero value otherwise.

### GetActionOk

`func (o *BulkUpdateActionVariableBody) GetActionOk() (*string, bool)`

GetActionOk returns a tuple with the Action field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAction

`func (o *BulkUpdateActionVariableBody) SetAction(v string)`

SetAction sets Action field to given value.


### GetEntities

`func (o *BulkUpdateActionVariableBody) GetEntities() []VariableBody`

GetEntities returns the Entities field if non-nil, zero value otherwise.

### GetEntitiesOk

`func (o *BulkUpdateActionVariableBody) GetEntitiesOk() (*[]VariableBody, bool)`

GetEntitiesOk returns a tuple with the Entities field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEntities

`func (o *BulkUpdateActionVariableBody) SetEntities(v []VariableBody)`

SetEntities sets Entities field to given value.


### GetActionOnNonExistence

`func (o *BulkUpdateActionVariableBody) GetActionOnNonExistence() BulkActionNotOnExistence`

GetActionOnNonExistence returns the ActionOnNonExistence field if non-nil, zero value otherwise.

### GetActionOnNonExistenceOk

`func (o *BulkUpdateActionVariableBody) GetActionOnNonExistenceOk() (*BulkActionNotOnExistence, bool)`

GetActionOnNonExistenceOk returns a tuple with the ActionOnNonExistence field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActionOnNonExistence

`func (o *BulkUpdateActionVariableBody) SetActionOnNonExistence(v BulkActionNotOnExistence)`

SetActionOnNonExistence sets ActionOnNonExistence field to given value.

### HasActionOnNonExistence

`func (o *BulkUpdateActionVariableBody) HasActionOnNonExistence() bool`

HasActionOnNonExistence returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


