# DAGTagCollectionResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Tags** | **[]string** |  | 
**TotalEntries** | **int32** |  | 

## Methods

### NewDAGTagCollectionResponse

`func NewDAGTagCollectionResponse(tags []string, totalEntries int32, ) *DAGTagCollectionResponse`

NewDAGTagCollectionResponse instantiates a new DAGTagCollectionResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDAGTagCollectionResponseWithDefaults

`func NewDAGTagCollectionResponseWithDefaults() *DAGTagCollectionResponse`

NewDAGTagCollectionResponseWithDefaults instantiates a new DAGTagCollectionResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTags

`func (o *DAGTagCollectionResponse) GetTags() []string`

GetTags returns the Tags field if non-nil, zero value otherwise.

### GetTagsOk

`func (o *DAGTagCollectionResponse) GetTagsOk() (*[]string, bool)`

GetTagsOk returns a tuple with the Tags field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTags

`func (o *DAGTagCollectionResponse) SetTags(v []string)`

SetTags sets Tags field to given value.


### GetTotalEntries

`func (o *DAGTagCollectionResponse) GetTotalEntries() int32`

GetTotalEntries returns the TotalEntries field if non-nil, zero value otherwise.

### GetTotalEntriesOk

`func (o *DAGTagCollectionResponse) GetTotalEntriesOk() (*int32, bool)`

GetTotalEntriesOk returns a tuple with the TotalEntries field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalEntries

`func (o *DAGTagCollectionResponse) SetTotalEntries(v int32)`

SetTotalEntries sets TotalEntries field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


