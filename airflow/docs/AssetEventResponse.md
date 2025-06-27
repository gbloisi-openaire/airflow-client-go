# AssetEventResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **int32** |  | 
**AssetId** | **int32** |  | 
**Uri** | Pointer to **NullableString** |  | [optional] 
**Name** | Pointer to **NullableString** |  | [optional] 
**Group** | Pointer to **NullableString** |  | [optional] 
**Extra** | Pointer to **map[string]interface{}** |  | [optional] 
**SourceTaskId** | Pointer to **NullableString** |  | [optional] 
**SourceDagId** | Pointer to **NullableString** |  | [optional] 
**SourceRunId** | Pointer to **NullableString** |  | [optional] 
**SourceMapIndex** | **int32** |  | 
**CreatedDagruns** | [**[]DagRunAssetReference**](DagRunAssetReference.md) |  | 
**Timestamp** | **time.Time** |  | 

## Methods

### NewAssetEventResponse

`func NewAssetEventResponse(id int32, assetId int32, sourceMapIndex int32, createdDagruns []DagRunAssetReference, timestamp time.Time, ) *AssetEventResponse`

NewAssetEventResponse instantiates a new AssetEventResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAssetEventResponseWithDefaults

`func NewAssetEventResponseWithDefaults() *AssetEventResponse`

NewAssetEventResponseWithDefaults instantiates a new AssetEventResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *AssetEventResponse) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *AssetEventResponse) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *AssetEventResponse) SetId(v int32)`

SetId sets Id field to given value.


### GetAssetId

`func (o *AssetEventResponse) GetAssetId() int32`

GetAssetId returns the AssetId field if non-nil, zero value otherwise.

### GetAssetIdOk

`func (o *AssetEventResponse) GetAssetIdOk() (*int32, bool)`

GetAssetIdOk returns a tuple with the AssetId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssetId

`func (o *AssetEventResponse) SetAssetId(v int32)`

SetAssetId sets AssetId field to given value.


### GetUri

`func (o *AssetEventResponse) GetUri() string`

GetUri returns the Uri field if non-nil, zero value otherwise.

### GetUriOk

`func (o *AssetEventResponse) GetUriOk() (*string, bool)`

GetUriOk returns a tuple with the Uri field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUri

`func (o *AssetEventResponse) SetUri(v string)`

SetUri sets Uri field to given value.

### HasUri

`func (o *AssetEventResponse) HasUri() bool`

HasUri returns a boolean if a field has been set.

### SetUriNil

`func (o *AssetEventResponse) SetUriNil(b bool)`

 SetUriNil sets the value for Uri to be an explicit nil

### UnsetUri
`func (o *AssetEventResponse) UnsetUri()`

UnsetUri ensures that no value is present for Uri, not even an explicit nil
### GetName

`func (o *AssetEventResponse) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *AssetEventResponse) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *AssetEventResponse) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *AssetEventResponse) HasName() bool`

HasName returns a boolean if a field has been set.

### SetNameNil

`func (o *AssetEventResponse) SetNameNil(b bool)`

 SetNameNil sets the value for Name to be an explicit nil

### UnsetName
`func (o *AssetEventResponse) UnsetName()`

UnsetName ensures that no value is present for Name, not even an explicit nil
### GetGroup

`func (o *AssetEventResponse) GetGroup() string`

GetGroup returns the Group field if non-nil, zero value otherwise.

### GetGroupOk

`func (o *AssetEventResponse) GetGroupOk() (*string, bool)`

GetGroupOk returns a tuple with the Group field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGroup

`func (o *AssetEventResponse) SetGroup(v string)`

SetGroup sets Group field to given value.

### HasGroup

`func (o *AssetEventResponse) HasGroup() bool`

HasGroup returns a boolean if a field has been set.

### SetGroupNil

`func (o *AssetEventResponse) SetGroupNil(b bool)`

 SetGroupNil sets the value for Group to be an explicit nil

### UnsetGroup
`func (o *AssetEventResponse) UnsetGroup()`

UnsetGroup ensures that no value is present for Group, not even an explicit nil
### GetExtra

`func (o *AssetEventResponse) GetExtra() map[string]interface{}`

GetExtra returns the Extra field if non-nil, zero value otherwise.

### GetExtraOk

`func (o *AssetEventResponse) GetExtraOk() (*map[string]interface{}, bool)`

GetExtraOk returns a tuple with the Extra field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExtra

`func (o *AssetEventResponse) SetExtra(v map[string]interface{})`

SetExtra sets Extra field to given value.

### HasExtra

`func (o *AssetEventResponse) HasExtra() bool`

HasExtra returns a boolean if a field has been set.

### SetExtraNil

`func (o *AssetEventResponse) SetExtraNil(b bool)`

 SetExtraNil sets the value for Extra to be an explicit nil

### UnsetExtra
`func (o *AssetEventResponse) UnsetExtra()`

UnsetExtra ensures that no value is present for Extra, not even an explicit nil
### GetSourceTaskId

`func (o *AssetEventResponse) GetSourceTaskId() string`

GetSourceTaskId returns the SourceTaskId field if non-nil, zero value otherwise.

### GetSourceTaskIdOk

`func (o *AssetEventResponse) GetSourceTaskIdOk() (*string, bool)`

GetSourceTaskIdOk returns a tuple with the SourceTaskId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSourceTaskId

`func (o *AssetEventResponse) SetSourceTaskId(v string)`

SetSourceTaskId sets SourceTaskId field to given value.

### HasSourceTaskId

`func (o *AssetEventResponse) HasSourceTaskId() bool`

HasSourceTaskId returns a boolean if a field has been set.

### SetSourceTaskIdNil

`func (o *AssetEventResponse) SetSourceTaskIdNil(b bool)`

 SetSourceTaskIdNil sets the value for SourceTaskId to be an explicit nil

### UnsetSourceTaskId
`func (o *AssetEventResponse) UnsetSourceTaskId()`

UnsetSourceTaskId ensures that no value is present for SourceTaskId, not even an explicit nil
### GetSourceDagId

`func (o *AssetEventResponse) GetSourceDagId() string`

GetSourceDagId returns the SourceDagId field if non-nil, zero value otherwise.

### GetSourceDagIdOk

`func (o *AssetEventResponse) GetSourceDagIdOk() (*string, bool)`

GetSourceDagIdOk returns a tuple with the SourceDagId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSourceDagId

`func (o *AssetEventResponse) SetSourceDagId(v string)`

SetSourceDagId sets SourceDagId field to given value.

### HasSourceDagId

`func (o *AssetEventResponse) HasSourceDagId() bool`

HasSourceDagId returns a boolean if a field has been set.

### SetSourceDagIdNil

`func (o *AssetEventResponse) SetSourceDagIdNil(b bool)`

 SetSourceDagIdNil sets the value for SourceDagId to be an explicit nil

### UnsetSourceDagId
`func (o *AssetEventResponse) UnsetSourceDagId()`

UnsetSourceDagId ensures that no value is present for SourceDagId, not even an explicit nil
### GetSourceRunId

`func (o *AssetEventResponse) GetSourceRunId() string`

GetSourceRunId returns the SourceRunId field if non-nil, zero value otherwise.

### GetSourceRunIdOk

`func (o *AssetEventResponse) GetSourceRunIdOk() (*string, bool)`

GetSourceRunIdOk returns a tuple with the SourceRunId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSourceRunId

`func (o *AssetEventResponse) SetSourceRunId(v string)`

SetSourceRunId sets SourceRunId field to given value.

### HasSourceRunId

`func (o *AssetEventResponse) HasSourceRunId() bool`

HasSourceRunId returns a boolean if a field has been set.

### SetSourceRunIdNil

`func (o *AssetEventResponse) SetSourceRunIdNil(b bool)`

 SetSourceRunIdNil sets the value for SourceRunId to be an explicit nil

### UnsetSourceRunId
`func (o *AssetEventResponse) UnsetSourceRunId()`

UnsetSourceRunId ensures that no value is present for SourceRunId, not even an explicit nil
### GetSourceMapIndex

`func (o *AssetEventResponse) GetSourceMapIndex() int32`

GetSourceMapIndex returns the SourceMapIndex field if non-nil, zero value otherwise.

### GetSourceMapIndexOk

`func (o *AssetEventResponse) GetSourceMapIndexOk() (*int32, bool)`

GetSourceMapIndexOk returns a tuple with the SourceMapIndex field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSourceMapIndex

`func (o *AssetEventResponse) SetSourceMapIndex(v int32)`

SetSourceMapIndex sets SourceMapIndex field to given value.


### GetCreatedDagruns

`func (o *AssetEventResponse) GetCreatedDagruns() []DagRunAssetReference`

GetCreatedDagruns returns the CreatedDagruns field if non-nil, zero value otherwise.

### GetCreatedDagrunsOk

`func (o *AssetEventResponse) GetCreatedDagrunsOk() (*[]DagRunAssetReference, bool)`

GetCreatedDagrunsOk returns a tuple with the CreatedDagruns field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedDagruns

`func (o *AssetEventResponse) SetCreatedDagruns(v []DagRunAssetReference)`

SetCreatedDagruns sets CreatedDagruns field to given value.


### GetTimestamp

`func (o *AssetEventResponse) GetTimestamp() time.Time`

GetTimestamp returns the Timestamp field if non-nil, zero value otherwise.

### GetTimestampOk

`func (o *AssetEventResponse) GetTimestampOk() (*time.Time, bool)`

GetTimestampOk returns a tuple with the Timestamp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimestamp

`func (o *AssetEventResponse) SetTimestamp(v time.Time)`

SetTimestamp sets Timestamp field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


