# AssetResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **int32** |  | 
**Name** | **string** |  | 
**Uri** | **string** |  | 
**Group** | **string** |  | 
**Extra** | Pointer to **map[string]interface{}** |  | [optional] 
**CreatedAt** | **time.Time** |  | 
**UpdatedAt** | **time.Time** |  | 
**ScheduledDags** | [**[]DagScheduleAssetReference**](DagScheduleAssetReference.md) |  | 
**ProducingTasks** | [**[]TaskOutletAssetReference**](TaskOutletAssetReference.md) |  | 
**ConsumingTasks** | [**[]TaskInletAssetReference**](TaskInletAssetReference.md) |  | 
**Aliases** | [**[]AssetAliasResponse**](AssetAliasResponse.md) |  | 
**LastAssetEvent** | Pointer to [**NullableLastAssetEventResponse**](LastAssetEventResponse.md) |  | [optional] 

## Methods

### NewAssetResponse

`func NewAssetResponse(id int32, name string, uri string, group string, createdAt time.Time, updatedAt time.Time, scheduledDags []DagScheduleAssetReference, producingTasks []TaskOutletAssetReference, consumingTasks []TaskInletAssetReference, aliases []AssetAliasResponse, ) *AssetResponse`

NewAssetResponse instantiates a new AssetResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAssetResponseWithDefaults

`func NewAssetResponseWithDefaults() *AssetResponse`

NewAssetResponseWithDefaults instantiates a new AssetResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *AssetResponse) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *AssetResponse) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *AssetResponse) SetId(v int32)`

SetId sets Id field to given value.


### GetName

`func (o *AssetResponse) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *AssetResponse) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *AssetResponse) SetName(v string)`

SetName sets Name field to given value.


### GetUri

`func (o *AssetResponse) GetUri() string`

GetUri returns the Uri field if non-nil, zero value otherwise.

### GetUriOk

`func (o *AssetResponse) GetUriOk() (*string, bool)`

GetUriOk returns a tuple with the Uri field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUri

`func (o *AssetResponse) SetUri(v string)`

SetUri sets Uri field to given value.


### GetGroup

`func (o *AssetResponse) GetGroup() string`

GetGroup returns the Group field if non-nil, zero value otherwise.

### GetGroupOk

`func (o *AssetResponse) GetGroupOk() (*string, bool)`

GetGroupOk returns a tuple with the Group field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGroup

`func (o *AssetResponse) SetGroup(v string)`

SetGroup sets Group field to given value.


### GetExtra

`func (o *AssetResponse) GetExtra() map[string]interface{}`

GetExtra returns the Extra field if non-nil, zero value otherwise.

### GetExtraOk

`func (o *AssetResponse) GetExtraOk() (*map[string]interface{}, bool)`

GetExtraOk returns a tuple with the Extra field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExtra

`func (o *AssetResponse) SetExtra(v map[string]interface{})`

SetExtra sets Extra field to given value.

### HasExtra

`func (o *AssetResponse) HasExtra() bool`

HasExtra returns a boolean if a field has been set.

### SetExtraNil

`func (o *AssetResponse) SetExtraNil(b bool)`

 SetExtraNil sets the value for Extra to be an explicit nil

### UnsetExtra
`func (o *AssetResponse) UnsetExtra()`

UnsetExtra ensures that no value is present for Extra, not even an explicit nil
### GetCreatedAt

`func (o *AssetResponse) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *AssetResponse) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *AssetResponse) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetUpdatedAt

`func (o *AssetResponse) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *AssetResponse) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *AssetResponse) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.


### GetScheduledDags

`func (o *AssetResponse) GetScheduledDags() []DagScheduleAssetReference`

GetScheduledDags returns the ScheduledDags field if non-nil, zero value otherwise.

### GetScheduledDagsOk

`func (o *AssetResponse) GetScheduledDagsOk() (*[]DagScheduleAssetReference, bool)`

GetScheduledDagsOk returns a tuple with the ScheduledDags field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScheduledDags

`func (o *AssetResponse) SetScheduledDags(v []DagScheduleAssetReference)`

SetScheduledDags sets ScheduledDags field to given value.


### GetProducingTasks

`func (o *AssetResponse) GetProducingTasks() []TaskOutletAssetReference`

GetProducingTasks returns the ProducingTasks field if non-nil, zero value otherwise.

### GetProducingTasksOk

`func (o *AssetResponse) GetProducingTasksOk() (*[]TaskOutletAssetReference, bool)`

GetProducingTasksOk returns a tuple with the ProducingTasks field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProducingTasks

`func (o *AssetResponse) SetProducingTasks(v []TaskOutletAssetReference)`

SetProducingTasks sets ProducingTasks field to given value.


### GetConsumingTasks

`func (o *AssetResponse) GetConsumingTasks() []TaskInletAssetReference`

GetConsumingTasks returns the ConsumingTasks field if non-nil, zero value otherwise.

### GetConsumingTasksOk

`func (o *AssetResponse) GetConsumingTasksOk() (*[]TaskInletAssetReference, bool)`

GetConsumingTasksOk returns a tuple with the ConsumingTasks field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConsumingTasks

`func (o *AssetResponse) SetConsumingTasks(v []TaskInletAssetReference)`

SetConsumingTasks sets ConsumingTasks field to given value.


### GetAliases

`func (o *AssetResponse) GetAliases() []AssetAliasResponse`

GetAliases returns the Aliases field if non-nil, zero value otherwise.

### GetAliasesOk

`func (o *AssetResponse) GetAliasesOk() (*[]AssetAliasResponse, bool)`

GetAliasesOk returns a tuple with the Aliases field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAliases

`func (o *AssetResponse) SetAliases(v []AssetAliasResponse)`

SetAliases sets Aliases field to given value.


### GetLastAssetEvent

`func (o *AssetResponse) GetLastAssetEvent() LastAssetEventResponse`

GetLastAssetEvent returns the LastAssetEvent field if non-nil, zero value otherwise.

### GetLastAssetEventOk

`func (o *AssetResponse) GetLastAssetEventOk() (*LastAssetEventResponse, bool)`

GetLastAssetEventOk returns a tuple with the LastAssetEvent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastAssetEvent

`func (o *AssetResponse) SetLastAssetEvent(v LastAssetEventResponse)`

SetLastAssetEvent sets LastAssetEvent field to given value.

### HasLastAssetEvent

`func (o *AssetResponse) HasLastAssetEvent() bool`

HasLastAssetEvent returns a boolean if a field has been set.

### SetLastAssetEventNil

`func (o *AssetResponse) SetLastAssetEventNil(b bool)`

 SetLastAssetEventNil sets the value for LastAssetEvent to be an explicit nil

### UnsetLastAssetEvent
`func (o *AssetResponse) UnsetLastAssetEvent()`

UnsetLastAssetEvent ensures that no value is present for LastAssetEvent, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


