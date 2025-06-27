# BulkCreateActionVariableBody

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Action** | **string** | The action to be performed on the entities. | 
**Entities** | [**[]VariableBody**](VariableBody.md) | A list of entities to be created. | 
**ActionOnExistence** | Pointer to [**BulkActionOnExistence**](BulkActionOnExistence.md) |  | [optional] 

## Methods

### NewBulkCreateActionVariableBody

`func NewBulkCreateActionVariableBody(action string, entities []VariableBody, ) *BulkCreateActionVariableBody`

NewBulkCreateActionVariableBody instantiates a new BulkCreateActionVariableBody object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewBulkCreateActionVariableBodyWithDefaults

`func NewBulkCreateActionVariableBodyWithDefaults() *BulkCreateActionVariableBody`

NewBulkCreateActionVariableBodyWithDefaults instantiates a new BulkCreateActionVariableBody object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAction

`func (o *BulkCreateActionVariableBody) GetAction() string`

GetAction returns the Action field if non-nil, zero value otherwise.

### GetActionOk

`func (o *BulkCreateActionVariableBody) GetActionOk() (*string, bool)`

GetActionOk returns a tuple with the Action field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAction

`func (o *BulkCreateActionVariableBody) SetAction(v string)`

SetAction sets Action field to given value.


### GetEntities

`func (o *BulkCreateActionVariableBody) GetEntities() []VariableBody`

GetEntities returns the Entities field if non-nil, zero value otherwise.

### GetEntitiesOk

`func (o *BulkCreateActionVariableBody) GetEntitiesOk() (*[]VariableBody, bool)`

GetEntitiesOk returns a tuple with the Entities field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEntities

`func (o *BulkCreateActionVariableBody) SetEntities(v []VariableBody)`

SetEntities sets Entities field to given value.


### GetActionOnExistence

`func (o *BulkCreateActionVariableBody) GetActionOnExistence() BulkActionOnExistence`

GetActionOnExistence returns the ActionOnExistence field if non-nil, zero value otherwise.

### GetActionOnExistenceOk

`func (o *BulkCreateActionVariableBody) GetActionOnExistenceOk() (*BulkActionOnExistence, bool)`

GetActionOnExistenceOk returns a tuple with the ActionOnExistence field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActionOnExistence

`func (o *BulkCreateActionVariableBody) SetActionOnExistence(v BulkActionOnExistence)`

SetActionOnExistence sets ActionOnExistence field to given value.

### HasActionOnExistence

`func (o *BulkCreateActionVariableBody) HasActionOnExistence() bool`

HasActionOnExistence returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


