# BulkCreateActionConnectionBody

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Action** | **string** | The action to be performed on the entities. | 
**Entities** | [**[]ConnectionBody**](ConnectionBody.md) | A list of entities to be created. | 
**ActionOnExistence** | Pointer to [**BulkActionOnExistence**](BulkActionOnExistence.md) |  | [optional] 

## Methods

### NewBulkCreateActionConnectionBody

`func NewBulkCreateActionConnectionBody(action string, entities []ConnectionBody, ) *BulkCreateActionConnectionBody`

NewBulkCreateActionConnectionBody instantiates a new BulkCreateActionConnectionBody object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewBulkCreateActionConnectionBodyWithDefaults

`func NewBulkCreateActionConnectionBodyWithDefaults() *BulkCreateActionConnectionBody`

NewBulkCreateActionConnectionBodyWithDefaults instantiates a new BulkCreateActionConnectionBody object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAction

`func (o *BulkCreateActionConnectionBody) GetAction() string`

GetAction returns the Action field if non-nil, zero value otherwise.

### GetActionOk

`func (o *BulkCreateActionConnectionBody) GetActionOk() (*string, bool)`

GetActionOk returns a tuple with the Action field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAction

`func (o *BulkCreateActionConnectionBody) SetAction(v string)`

SetAction sets Action field to given value.


### GetEntities

`func (o *BulkCreateActionConnectionBody) GetEntities() []ConnectionBody`

GetEntities returns the Entities field if non-nil, zero value otherwise.

### GetEntitiesOk

`func (o *BulkCreateActionConnectionBody) GetEntitiesOk() (*[]ConnectionBody, bool)`

GetEntitiesOk returns a tuple with the Entities field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEntities

`func (o *BulkCreateActionConnectionBody) SetEntities(v []ConnectionBody)`

SetEntities sets Entities field to given value.


### GetActionOnExistence

`func (o *BulkCreateActionConnectionBody) GetActionOnExistence() BulkActionOnExistence`

GetActionOnExistence returns the ActionOnExistence field if non-nil, zero value otherwise.

### GetActionOnExistenceOk

`func (o *BulkCreateActionConnectionBody) GetActionOnExistenceOk() (*BulkActionOnExistence, bool)`

GetActionOnExistenceOk returns a tuple with the ActionOnExistence field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActionOnExistence

`func (o *BulkCreateActionConnectionBody) SetActionOnExistence(v BulkActionOnExistence)`

SetActionOnExistence sets ActionOnExistence field to given value.

### HasActionOnExistence

`func (o *BulkCreateActionConnectionBody) HasActionOnExistence() bool`

HasActionOnExistence returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


