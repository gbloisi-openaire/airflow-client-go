# BulkBodyConnectionBodyActionsInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Action** | **string** | The action to be performed on the entities. | 
**Entities** | **[]string** | A list of entity id/key to be deleted. | 
**ActionOnExistence** | Pointer to [**BulkActionOnExistence**](BulkActionOnExistence.md) |  | [optional] 
**ActionOnNonExistence** | Pointer to [**BulkActionNotOnExistence**](BulkActionNotOnExistence.md) |  | [optional] 

## Methods

### NewBulkBodyConnectionBodyActionsInner

`func NewBulkBodyConnectionBodyActionsInner(action string, entities []string, ) *BulkBodyConnectionBodyActionsInner`

NewBulkBodyConnectionBodyActionsInner instantiates a new BulkBodyConnectionBodyActionsInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewBulkBodyConnectionBodyActionsInnerWithDefaults

`func NewBulkBodyConnectionBodyActionsInnerWithDefaults() *BulkBodyConnectionBodyActionsInner`

NewBulkBodyConnectionBodyActionsInnerWithDefaults instantiates a new BulkBodyConnectionBodyActionsInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAction

`func (o *BulkBodyConnectionBodyActionsInner) GetAction() string`

GetAction returns the Action field if non-nil, zero value otherwise.

### GetActionOk

`func (o *BulkBodyConnectionBodyActionsInner) GetActionOk() (*string, bool)`

GetActionOk returns a tuple with the Action field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAction

`func (o *BulkBodyConnectionBodyActionsInner) SetAction(v string)`

SetAction sets Action field to given value.


### GetEntities

`func (o *BulkBodyConnectionBodyActionsInner) GetEntities() []string`

GetEntities returns the Entities field if non-nil, zero value otherwise.

### GetEntitiesOk

`func (o *BulkBodyConnectionBodyActionsInner) GetEntitiesOk() (*[]string, bool)`

GetEntitiesOk returns a tuple with the Entities field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEntities

`func (o *BulkBodyConnectionBodyActionsInner) SetEntities(v []string)`

SetEntities sets Entities field to given value.


### GetActionOnExistence

`func (o *BulkBodyConnectionBodyActionsInner) GetActionOnExistence() BulkActionOnExistence`

GetActionOnExistence returns the ActionOnExistence field if non-nil, zero value otherwise.

### GetActionOnExistenceOk

`func (o *BulkBodyConnectionBodyActionsInner) GetActionOnExistenceOk() (*BulkActionOnExistence, bool)`

GetActionOnExistenceOk returns a tuple with the ActionOnExistence field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActionOnExistence

`func (o *BulkBodyConnectionBodyActionsInner) SetActionOnExistence(v BulkActionOnExistence)`

SetActionOnExistence sets ActionOnExistence field to given value.

### HasActionOnExistence

`func (o *BulkBodyConnectionBodyActionsInner) HasActionOnExistence() bool`

HasActionOnExistence returns a boolean if a field has been set.

### GetActionOnNonExistence

`func (o *BulkBodyConnectionBodyActionsInner) GetActionOnNonExistence() BulkActionNotOnExistence`

GetActionOnNonExistence returns the ActionOnNonExistence field if non-nil, zero value otherwise.

### GetActionOnNonExistenceOk

`func (o *BulkBodyConnectionBodyActionsInner) GetActionOnNonExistenceOk() (*BulkActionNotOnExistence, bool)`

GetActionOnNonExistenceOk returns a tuple with the ActionOnNonExistence field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActionOnNonExistence

`func (o *BulkBodyConnectionBodyActionsInner) SetActionOnNonExistence(v BulkActionNotOnExistence)`

SetActionOnNonExistence sets ActionOnNonExistence field to given value.

### HasActionOnNonExistence

`func (o *BulkBodyConnectionBodyActionsInner) HasActionOnNonExistence() bool`

HasActionOnNonExistence returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


