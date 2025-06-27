# DAGSourceResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Content** | **NullableString** |  | 
**DagId** | **string** |  | 
**VersionNumber** | **NullableInt32** |  | 
**DagDisplayName** | **string** |  | 

## Methods

### NewDAGSourceResponse

`func NewDAGSourceResponse(content NullableString, dagId string, versionNumber NullableInt32, dagDisplayName string, ) *DAGSourceResponse`

NewDAGSourceResponse instantiates a new DAGSourceResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDAGSourceResponseWithDefaults

`func NewDAGSourceResponseWithDefaults() *DAGSourceResponse`

NewDAGSourceResponseWithDefaults instantiates a new DAGSourceResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetContent

`func (o *DAGSourceResponse) GetContent() string`

GetContent returns the Content field if non-nil, zero value otherwise.

### GetContentOk

`func (o *DAGSourceResponse) GetContentOk() (*string, bool)`

GetContentOk returns a tuple with the Content field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContent

`func (o *DAGSourceResponse) SetContent(v string)`

SetContent sets Content field to given value.


### SetContentNil

`func (o *DAGSourceResponse) SetContentNil(b bool)`

 SetContentNil sets the value for Content to be an explicit nil

### UnsetContent
`func (o *DAGSourceResponse) UnsetContent()`

UnsetContent ensures that no value is present for Content, not even an explicit nil
### GetDagId

`func (o *DAGSourceResponse) GetDagId() string`

GetDagId returns the DagId field if non-nil, zero value otherwise.

### GetDagIdOk

`func (o *DAGSourceResponse) GetDagIdOk() (*string, bool)`

GetDagIdOk returns a tuple with the DagId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDagId

`func (o *DAGSourceResponse) SetDagId(v string)`

SetDagId sets DagId field to given value.


### GetVersionNumber

`func (o *DAGSourceResponse) GetVersionNumber() int32`

GetVersionNumber returns the VersionNumber field if non-nil, zero value otherwise.

### GetVersionNumberOk

`func (o *DAGSourceResponse) GetVersionNumberOk() (*int32, bool)`

GetVersionNumberOk returns a tuple with the VersionNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVersionNumber

`func (o *DAGSourceResponse) SetVersionNumber(v int32)`

SetVersionNumber sets VersionNumber field to given value.


### SetVersionNumberNil

`func (o *DAGSourceResponse) SetVersionNumberNil(b bool)`

 SetVersionNumberNil sets the value for VersionNumber to be an explicit nil

### UnsetVersionNumber
`func (o *DAGSourceResponse) UnsetVersionNumber()`

UnsetVersionNumber ensures that no value is present for VersionNumber, not even an explicit nil
### GetDagDisplayName

`func (o *DAGSourceResponse) GetDagDisplayName() string`

GetDagDisplayName returns the DagDisplayName field if non-nil, zero value otherwise.

### GetDagDisplayNameOk

`func (o *DAGSourceResponse) GetDagDisplayNameOk() (*string, bool)`

GetDagDisplayNameOk returns a tuple with the DagDisplayName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDagDisplayName

`func (o *DAGSourceResponse) SetDagDisplayName(v string)`

SetDagDisplayName sets DagDisplayName field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


