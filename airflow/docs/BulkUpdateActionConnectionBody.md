# BulkUpdateActionConnectionBody

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Action** | **string** | The action to be performed on the entities. | 
**Entities** | [**[]ConnectionBody**](ConnectionBody.md) | A list of entities to be updated. | 
**ActionOnNonExistence** | Pointer to [**BulkActionNotOnExistence**](BulkActionNotOnExistence.md) |  | [optional] 

## Methods

### NewBulkUpdateActionConnectionBody

`func NewBulkUpdateActionConnectionBody(action string, entities []ConnectionBody, ) *BulkUpdateActionConnectionBody`

NewBulkUpdateActionConnectionBody instantiates a new BulkUpdateActionConnectionBody object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewBulkUpdateActionConnectionBodyWithDefaults

`func NewBulkUpdateActionConnectionBodyWithDefaults() *BulkUpdateActionConnectionBody`

NewBulkUpdateActionConnectionBodyWithDefaults instantiates a new BulkUpdateActionConnectionBody object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAction

`func (o *BulkUpdateActionConnectionBody) GetAction() string`

GetAction returns the Action field if non-nil, zero value otherwise.

### GetActionOk

`func (o *BulkUpdateActionConnectionBody) GetActionOk() (*string, bool)`

GetActionOk returns a tuple with the Action field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAction

`func (o *BulkUpdateActionConnectionBody) SetAction(v string)`

SetAction sets Action field to given value.


### GetEntities

`func (o *BulkUpdateActionConnectionBody) GetEntities() []ConnectionBody`

GetEntities returns the Entities field if non-nil, zero value otherwise.

### GetEntitiesOk

`func (o *BulkUpdateActionConnectionBody) GetEntitiesOk() (*[]ConnectionBody, bool)`

GetEntitiesOk returns a tuple with the Entities field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEntities

`func (o *BulkUpdateActionConnectionBody) SetEntities(v []ConnectionBody)`

SetEntities sets Entities field to given value.


### GetActionOnNonExistence

`func (o *BulkUpdateActionConnectionBody) GetActionOnNonExistence() BulkActionNotOnExistence`

GetActionOnNonExistence returns the ActionOnNonExistence field if non-nil, zero value otherwise.

### GetActionOnNonExistenceOk

`func (o *BulkUpdateActionConnectionBody) GetActionOnNonExistenceOk() (*BulkActionNotOnExistence, bool)`

GetActionOnNonExistenceOk returns a tuple with the ActionOnNonExistence field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActionOnNonExistence

`func (o *BulkUpdateActionConnectionBody) SetActionOnNonExistence(v BulkActionNotOnExistence)`

SetActionOnNonExistence sets ActionOnNonExistence field to given value.

### HasActionOnNonExistence

`func (o *BulkUpdateActionConnectionBody) HasActionOnNonExistence() bool`

HasActionOnNonExistence returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


