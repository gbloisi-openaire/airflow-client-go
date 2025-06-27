# BulkCreateActionBulkTaskInstanceBody

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Action** | **string** | The action to be performed on the entities. | 
**Entities** | [**[]BulkTaskInstanceBody**](BulkTaskInstanceBody.md) | A list of entities to be created. | 
**ActionOnExistence** | Pointer to [**BulkActionOnExistence**](BulkActionOnExistence.md) |  | [optional] 

## Methods

### NewBulkCreateActionBulkTaskInstanceBody

`func NewBulkCreateActionBulkTaskInstanceBody(action string, entities []BulkTaskInstanceBody, ) *BulkCreateActionBulkTaskInstanceBody`

NewBulkCreateActionBulkTaskInstanceBody instantiates a new BulkCreateActionBulkTaskInstanceBody object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewBulkCreateActionBulkTaskInstanceBodyWithDefaults

`func NewBulkCreateActionBulkTaskInstanceBodyWithDefaults() *BulkCreateActionBulkTaskInstanceBody`

NewBulkCreateActionBulkTaskInstanceBodyWithDefaults instantiates a new BulkCreateActionBulkTaskInstanceBody object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAction

`func (o *BulkCreateActionBulkTaskInstanceBody) GetAction() string`

GetAction returns the Action field if non-nil, zero value otherwise.

### GetActionOk

`func (o *BulkCreateActionBulkTaskInstanceBody) GetActionOk() (*string, bool)`

GetActionOk returns a tuple with the Action field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAction

`func (o *BulkCreateActionBulkTaskInstanceBody) SetAction(v string)`

SetAction sets Action field to given value.


### GetEntities

`func (o *BulkCreateActionBulkTaskInstanceBody) GetEntities() []BulkTaskInstanceBody`

GetEntities returns the Entities field if non-nil, zero value otherwise.

### GetEntitiesOk

`func (o *BulkCreateActionBulkTaskInstanceBody) GetEntitiesOk() (*[]BulkTaskInstanceBody, bool)`

GetEntitiesOk returns a tuple with the Entities field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEntities

`func (o *BulkCreateActionBulkTaskInstanceBody) SetEntities(v []BulkTaskInstanceBody)`

SetEntities sets Entities field to given value.


### GetActionOnExistence

`func (o *BulkCreateActionBulkTaskInstanceBody) GetActionOnExistence() BulkActionOnExistence`

GetActionOnExistence returns the ActionOnExistence field if non-nil, zero value otherwise.

### GetActionOnExistenceOk

`func (o *BulkCreateActionBulkTaskInstanceBody) GetActionOnExistenceOk() (*BulkActionOnExistence, bool)`

GetActionOnExistenceOk returns a tuple with the ActionOnExistence field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActionOnExistence

`func (o *BulkCreateActionBulkTaskInstanceBody) SetActionOnExistence(v BulkActionOnExistence)`

SetActionOnExistence sets ActionOnExistence field to given value.

### HasActionOnExistence

`func (o *BulkCreateActionBulkTaskInstanceBody) HasActionOnExistence() bool`

HasActionOnExistence returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


