# TaskInstancesLogResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Content** | [**Content**](Content.md) |  | 
**ContinuationToken** | **NullableString** |  | 

## Methods

### NewTaskInstancesLogResponse

`func NewTaskInstancesLogResponse(content Content, continuationToken NullableString, ) *TaskInstancesLogResponse`

NewTaskInstancesLogResponse instantiates a new TaskInstancesLogResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTaskInstancesLogResponseWithDefaults

`func NewTaskInstancesLogResponseWithDefaults() *TaskInstancesLogResponse`

NewTaskInstancesLogResponseWithDefaults instantiates a new TaskInstancesLogResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetContent

`func (o *TaskInstancesLogResponse) GetContent() Content`

GetContent returns the Content field if non-nil, zero value otherwise.

### GetContentOk

`func (o *TaskInstancesLogResponse) GetContentOk() (*Content, bool)`

GetContentOk returns a tuple with the Content field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContent

`func (o *TaskInstancesLogResponse) SetContent(v Content)`

SetContent sets Content field to given value.


### GetContinuationToken

`func (o *TaskInstancesLogResponse) GetContinuationToken() string`

GetContinuationToken returns the ContinuationToken field if non-nil, zero value otherwise.

### GetContinuationTokenOk

`func (o *TaskInstancesLogResponse) GetContinuationTokenOk() (*string, bool)`

GetContinuationTokenOk returns a tuple with the ContinuationToken field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContinuationToken

`func (o *TaskInstancesLogResponse) SetContinuationToken(v string)`

SetContinuationToken sets ContinuationToken field to given value.


### SetContinuationTokenNil

`func (o *TaskInstancesLogResponse) SetContinuationTokenNil(b bool)`

 SetContinuationTokenNil sets the value for ContinuationToken to be an explicit nil

### UnsetContinuationToken
`func (o *TaskInstancesLogResponse) UnsetContinuationToken()`

UnsetContinuationToken ensures that no value is present for ContinuationToken, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


