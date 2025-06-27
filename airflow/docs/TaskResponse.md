# TaskResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**TaskId** | **NullableString** |  | 
**TaskDisplayName** | **NullableString** |  | 
**Owner** | **NullableString** |  | 
**StartDate** | **NullableTime** |  | 
**EndDate** | **NullableTime** |  | 
**TriggerRule** | **NullableString** |  | 
**DependsOnPast** | **bool** |  | 
**WaitForDownstream** | **bool** |  | 
**Retries** | **NullableFloat32** |  | 
**Queue** | **NullableString** |  | 
**Pool** | **NullableString** |  | 
**PoolSlots** | **NullableFloat32** |  | 
**ExecutionTimeout** | [**NullableTimeDelta**](TimeDelta.md) |  | 
**RetryDelay** | [**NullableTimeDelta**](TimeDelta.md) |  | 
**RetryExponentialBackoff** | **bool** |  | 
**PriorityWeight** | **NullableFloat32** |  | 
**WeightRule** | **NullableString** |  | 
**UiColor** | **NullableString** |  | 
**UiFgcolor** | **NullableString** |  | 
**TemplateFields** | **[]string** |  | 
**DownstreamTaskIds** | **[]string** |  | 
**DocMd** | **NullableString** |  | 
**OperatorName** | **NullableString** |  | 
**Params** | **map[string]interface{}** |  | 
**ClassRef** | **map[string]interface{}** |  | 
**IsMapped** | **NullableBool** |  | 
**ExtraLinks** | **[]string** | Extract and return extra_links. | 

## Methods

### NewTaskResponse

`func NewTaskResponse(taskId NullableString, taskDisplayName NullableString, owner NullableString, startDate NullableTime, endDate NullableTime, triggerRule NullableString, dependsOnPast bool, waitForDownstream bool, retries NullableFloat32, queue NullableString, pool NullableString, poolSlots NullableFloat32, executionTimeout NullableTimeDelta, retryDelay NullableTimeDelta, retryExponentialBackoff bool, priorityWeight NullableFloat32, weightRule NullableString, uiColor NullableString, uiFgcolor NullableString, templateFields []string, downstreamTaskIds []string, docMd NullableString, operatorName NullableString, params map[string]interface{}, classRef map[string]interface{}, isMapped NullableBool, extraLinks []string, ) *TaskResponse`

NewTaskResponse instantiates a new TaskResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTaskResponseWithDefaults

`func NewTaskResponseWithDefaults() *TaskResponse`

NewTaskResponseWithDefaults instantiates a new TaskResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTaskId

`func (o *TaskResponse) GetTaskId() string`

GetTaskId returns the TaskId field if non-nil, zero value otherwise.

### GetTaskIdOk

`func (o *TaskResponse) GetTaskIdOk() (*string, bool)`

GetTaskIdOk returns a tuple with the TaskId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaskId

`func (o *TaskResponse) SetTaskId(v string)`

SetTaskId sets TaskId field to given value.


### SetTaskIdNil

`func (o *TaskResponse) SetTaskIdNil(b bool)`

 SetTaskIdNil sets the value for TaskId to be an explicit nil

### UnsetTaskId
`func (o *TaskResponse) UnsetTaskId()`

UnsetTaskId ensures that no value is present for TaskId, not even an explicit nil
### GetTaskDisplayName

`func (o *TaskResponse) GetTaskDisplayName() string`

GetTaskDisplayName returns the TaskDisplayName field if non-nil, zero value otherwise.

### GetTaskDisplayNameOk

`func (o *TaskResponse) GetTaskDisplayNameOk() (*string, bool)`

GetTaskDisplayNameOk returns a tuple with the TaskDisplayName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaskDisplayName

`func (o *TaskResponse) SetTaskDisplayName(v string)`

SetTaskDisplayName sets TaskDisplayName field to given value.


### SetTaskDisplayNameNil

`func (o *TaskResponse) SetTaskDisplayNameNil(b bool)`

 SetTaskDisplayNameNil sets the value for TaskDisplayName to be an explicit nil

### UnsetTaskDisplayName
`func (o *TaskResponse) UnsetTaskDisplayName()`

UnsetTaskDisplayName ensures that no value is present for TaskDisplayName, not even an explicit nil
### GetOwner

`func (o *TaskResponse) GetOwner() string`

GetOwner returns the Owner field if non-nil, zero value otherwise.

### GetOwnerOk

`func (o *TaskResponse) GetOwnerOk() (*string, bool)`

GetOwnerOk returns a tuple with the Owner field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOwner

`func (o *TaskResponse) SetOwner(v string)`

SetOwner sets Owner field to given value.


### SetOwnerNil

`func (o *TaskResponse) SetOwnerNil(b bool)`

 SetOwnerNil sets the value for Owner to be an explicit nil

### UnsetOwner
`func (o *TaskResponse) UnsetOwner()`

UnsetOwner ensures that no value is present for Owner, not even an explicit nil
### GetStartDate

`func (o *TaskResponse) GetStartDate() time.Time`

GetStartDate returns the StartDate field if non-nil, zero value otherwise.

### GetStartDateOk

`func (o *TaskResponse) GetStartDateOk() (*time.Time, bool)`

GetStartDateOk returns a tuple with the StartDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartDate

`func (o *TaskResponse) SetStartDate(v time.Time)`

SetStartDate sets StartDate field to given value.


### SetStartDateNil

`func (o *TaskResponse) SetStartDateNil(b bool)`

 SetStartDateNil sets the value for StartDate to be an explicit nil

### UnsetStartDate
`func (o *TaskResponse) UnsetStartDate()`

UnsetStartDate ensures that no value is present for StartDate, not even an explicit nil
### GetEndDate

`func (o *TaskResponse) GetEndDate() time.Time`

GetEndDate returns the EndDate field if non-nil, zero value otherwise.

### GetEndDateOk

`func (o *TaskResponse) GetEndDateOk() (*time.Time, bool)`

GetEndDateOk returns a tuple with the EndDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEndDate

`func (o *TaskResponse) SetEndDate(v time.Time)`

SetEndDate sets EndDate field to given value.


### SetEndDateNil

`func (o *TaskResponse) SetEndDateNil(b bool)`

 SetEndDateNil sets the value for EndDate to be an explicit nil

### UnsetEndDate
`func (o *TaskResponse) UnsetEndDate()`

UnsetEndDate ensures that no value is present for EndDate, not even an explicit nil
### GetTriggerRule

`func (o *TaskResponse) GetTriggerRule() string`

GetTriggerRule returns the TriggerRule field if non-nil, zero value otherwise.

### GetTriggerRuleOk

`func (o *TaskResponse) GetTriggerRuleOk() (*string, bool)`

GetTriggerRuleOk returns a tuple with the TriggerRule field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTriggerRule

`func (o *TaskResponse) SetTriggerRule(v string)`

SetTriggerRule sets TriggerRule field to given value.


### SetTriggerRuleNil

`func (o *TaskResponse) SetTriggerRuleNil(b bool)`

 SetTriggerRuleNil sets the value for TriggerRule to be an explicit nil

### UnsetTriggerRule
`func (o *TaskResponse) UnsetTriggerRule()`

UnsetTriggerRule ensures that no value is present for TriggerRule, not even an explicit nil
### GetDependsOnPast

`func (o *TaskResponse) GetDependsOnPast() bool`

GetDependsOnPast returns the DependsOnPast field if non-nil, zero value otherwise.

### GetDependsOnPastOk

`func (o *TaskResponse) GetDependsOnPastOk() (*bool, bool)`

GetDependsOnPastOk returns a tuple with the DependsOnPast field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDependsOnPast

`func (o *TaskResponse) SetDependsOnPast(v bool)`

SetDependsOnPast sets DependsOnPast field to given value.


### GetWaitForDownstream

`func (o *TaskResponse) GetWaitForDownstream() bool`

GetWaitForDownstream returns the WaitForDownstream field if non-nil, zero value otherwise.

### GetWaitForDownstreamOk

`func (o *TaskResponse) GetWaitForDownstreamOk() (*bool, bool)`

GetWaitForDownstreamOk returns a tuple with the WaitForDownstream field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWaitForDownstream

`func (o *TaskResponse) SetWaitForDownstream(v bool)`

SetWaitForDownstream sets WaitForDownstream field to given value.


### GetRetries

`func (o *TaskResponse) GetRetries() float32`

GetRetries returns the Retries field if non-nil, zero value otherwise.

### GetRetriesOk

`func (o *TaskResponse) GetRetriesOk() (*float32, bool)`

GetRetriesOk returns a tuple with the Retries field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRetries

`func (o *TaskResponse) SetRetries(v float32)`

SetRetries sets Retries field to given value.


### SetRetriesNil

`func (o *TaskResponse) SetRetriesNil(b bool)`

 SetRetriesNil sets the value for Retries to be an explicit nil

### UnsetRetries
`func (o *TaskResponse) UnsetRetries()`

UnsetRetries ensures that no value is present for Retries, not even an explicit nil
### GetQueue

`func (o *TaskResponse) GetQueue() string`

GetQueue returns the Queue field if non-nil, zero value otherwise.

### GetQueueOk

`func (o *TaskResponse) GetQueueOk() (*string, bool)`

GetQueueOk returns a tuple with the Queue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQueue

`func (o *TaskResponse) SetQueue(v string)`

SetQueue sets Queue field to given value.


### SetQueueNil

`func (o *TaskResponse) SetQueueNil(b bool)`

 SetQueueNil sets the value for Queue to be an explicit nil

### UnsetQueue
`func (o *TaskResponse) UnsetQueue()`

UnsetQueue ensures that no value is present for Queue, not even an explicit nil
### GetPool

`func (o *TaskResponse) GetPool() string`

GetPool returns the Pool field if non-nil, zero value otherwise.

### GetPoolOk

`func (o *TaskResponse) GetPoolOk() (*string, bool)`

GetPoolOk returns a tuple with the Pool field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPool

`func (o *TaskResponse) SetPool(v string)`

SetPool sets Pool field to given value.


### SetPoolNil

`func (o *TaskResponse) SetPoolNil(b bool)`

 SetPoolNil sets the value for Pool to be an explicit nil

### UnsetPool
`func (o *TaskResponse) UnsetPool()`

UnsetPool ensures that no value is present for Pool, not even an explicit nil
### GetPoolSlots

`func (o *TaskResponse) GetPoolSlots() float32`

GetPoolSlots returns the PoolSlots field if non-nil, zero value otherwise.

### GetPoolSlotsOk

`func (o *TaskResponse) GetPoolSlotsOk() (*float32, bool)`

GetPoolSlotsOk returns a tuple with the PoolSlots field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPoolSlots

`func (o *TaskResponse) SetPoolSlots(v float32)`

SetPoolSlots sets PoolSlots field to given value.


### SetPoolSlotsNil

`func (o *TaskResponse) SetPoolSlotsNil(b bool)`

 SetPoolSlotsNil sets the value for PoolSlots to be an explicit nil

### UnsetPoolSlots
`func (o *TaskResponse) UnsetPoolSlots()`

UnsetPoolSlots ensures that no value is present for PoolSlots, not even an explicit nil
### GetExecutionTimeout

`func (o *TaskResponse) GetExecutionTimeout() TimeDelta`

GetExecutionTimeout returns the ExecutionTimeout field if non-nil, zero value otherwise.

### GetExecutionTimeoutOk

`func (o *TaskResponse) GetExecutionTimeoutOk() (*TimeDelta, bool)`

GetExecutionTimeoutOk returns a tuple with the ExecutionTimeout field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExecutionTimeout

`func (o *TaskResponse) SetExecutionTimeout(v TimeDelta)`

SetExecutionTimeout sets ExecutionTimeout field to given value.


### SetExecutionTimeoutNil

`func (o *TaskResponse) SetExecutionTimeoutNil(b bool)`

 SetExecutionTimeoutNil sets the value for ExecutionTimeout to be an explicit nil

### UnsetExecutionTimeout
`func (o *TaskResponse) UnsetExecutionTimeout()`

UnsetExecutionTimeout ensures that no value is present for ExecutionTimeout, not even an explicit nil
### GetRetryDelay

`func (o *TaskResponse) GetRetryDelay() TimeDelta`

GetRetryDelay returns the RetryDelay field if non-nil, zero value otherwise.

### GetRetryDelayOk

`func (o *TaskResponse) GetRetryDelayOk() (*TimeDelta, bool)`

GetRetryDelayOk returns a tuple with the RetryDelay field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRetryDelay

`func (o *TaskResponse) SetRetryDelay(v TimeDelta)`

SetRetryDelay sets RetryDelay field to given value.


### SetRetryDelayNil

`func (o *TaskResponse) SetRetryDelayNil(b bool)`

 SetRetryDelayNil sets the value for RetryDelay to be an explicit nil

### UnsetRetryDelay
`func (o *TaskResponse) UnsetRetryDelay()`

UnsetRetryDelay ensures that no value is present for RetryDelay, not even an explicit nil
### GetRetryExponentialBackoff

`func (o *TaskResponse) GetRetryExponentialBackoff() bool`

GetRetryExponentialBackoff returns the RetryExponentialBackoff field if non-nil, zero value otherwise.

### GetRetryExponentialBackoffOk

`func (o *TaskResponse) GetRetryExponentialBackoffOk() (*bool, bool)`

GetRetryExponentialBackoffOk returns a tuple with the RetryExponentialBackoff field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRetryExponentialBackoff

`func (o *TaskResponse) SetRetryExponentialBackoff(v bool)`

SetRetryExponentialBackoff sets RetryExponentialBackoff field to given value.


### GetPriorityWeight

`func (o *TaskResponse) GetPriorityWeight() float32`

GetPriorityWeight returns the PriorityWeight field if non-nil, zero value otherwise.

### GetPriorityWeightOk

`func (o *TaskResponse) GetPriorityWeightOk() (*float32, bool)`

GetPriorityWeightOk returns a tuple with the PriorityWeight field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPriorityWeight

`func (o *TaskResponse) SetPriorityWeight(v float32)`

SetPriorityWeight sets PriorityWeight field to given value.


### SetPriorityWeightNil

`func (o *TaskResponse) SetPriorityWeightNil(b bool)`

 SetPriorityWeightNil sets the value for PriorityWeight to be an explicit nil

### UnsetPriorityWeight
`func (o *TaskResponse) UnsetPriorityWeight()`

UnsetPriorityWeight ensures that no value is present for PriorityWeight, not even an explicit nil
### GetWeightRule

`func (o *TaskResponse) GetWeightRule() string`

GetWeightRule returns the WeightRule field if non-nil, zero value otherwise.

### GetWeightRuleOk

`func (o *TaskResponse) GetWeightRuleOk() (*string, bool)`

GetWeightRuleOk returns a tuple with the WeightRule field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWeightRule

`func (o *TaskResponse) SetWeightRule(v string)`

SetWeightRule sets WeightRule field to given value.


### SetWeightRuleNil

`func (o *TaskResponse) SetWeightRuleNil(b bool)`

 SetWeightRuleNil sets the value for WeightRule to be an explicit nil

### UnsetWeightRule
`func (o *TaskResponse) UnsetWeightRule()`

UnsetWeightRule ensures that no value is present for WeightRule, not even an explicit nil
### GetUiColor

`func (o *TaskResponse) GetUiColor() string`

GetUiColor returns the UiColor field if non-nil, zero value otherwise.

### GetUiColorOk

`func (o *TaskResponse) GetUiColorOk() (*string, bool)`

GetUiColorOk returns a tuple with the UiColor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUiColor

`func (o *TaskResponse) SetUiColor(v string)`

SetUiColor sets UiColor field to given value.


### SetUiColorNil

`func (o *TaskResponse) SetUiColorNil(b bool)`

 SetUiColorNil sets the value for UiColor to be an explicit nil

### UnsetUiColor
`func (o *TaskResponse) UnsetUiColor()`

UnsetUiColor ensures that no value is present for UiColor, not even an explicit nil
### GetUiFgcolor

`func (o *TaskResponse) GetUiFgcolor() string`

GetUiFgcolor returns the UiFgcolor field if non-nil, zero value otherwise.

### GetUiFgcolorOk

`func (o *TaskResponse) GetUiFgcolorOk() (*string, bool)`

GetUiFgcolorOk returns a tuple with the UiFgcolor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUiFgcolor

`func (o *TaskResponse) SetUiFgcolor(v string)`

SetUiFgcolor sets UiFgcolor field to given value.


### SetUiFgcolorNil

`func (o *TaskResponse) SetUiFgcolorNil(b bool)`

 SetUiFgcolorNil sets the value for UiFgcolor to be an explicit nil

### UnsetUiFgcolor
`func (o *TaskResponse) UnsetUiFgcolor()`

UnsetUiFgcolor ensures that no value is present for UiFgcolor, not even an explicit nil
### GetTemplateFields

`func (o *TaskResponse) GetTemplateFields() []string`

GetTemplateFields returns the TemplateFields field if non-nil, zero value otherwise.

### GetTemplateFieldsOk

`func (o *TaskResponse) GetTemplateFieldsOk() (*[]string, bool)`

GetTemplateFieldsOk returns a tuple with the TemplateFields field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTemplateFields

`func (o *TaskResponse) SetTemplateFields(v []string)`

SetTemplateFields sets TemplateFields field to given value.


### SetTemplateFieldsNil

`func (o *TaskResponse) SetTemplateFieldsNil(b bool)`

 SetTemplateFieldsNil sets the value for TemplateFields to be an explicit nil

### UnsetTemplateFields
`func (o *TaskResponse) UnsetTemplateFields()`

UnsetTemplateFields ensures that no value is present for TemplateFields, not even an explicit nil
### GetDownstreamTaskIds

`func (o *TaskResponse) GetDownstreamTaskIds() []string`

GetDownstreamTaskIds returns the DownstreamTaskIds field if non-nil, zero value otherwise.

### GetDownstreamTaskIdsOk

`func (o *TaskResponse) GetDownstreamTaskIdsOk() (*[]string, bool)`

GetDownstreamTaskIdsOk returns a tuple with the DownstreamTaskIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDownstreamTaskIds

`func (o *TaskResponse) SetDownstreamTaskIds(v []string)`

SetDownstreamTaskIds sets DownstreamTaskIds field to given value.


### SetDownstreamTaskIdsNil

`func (o *TaskResponse) SetDownstreamTaskIdsNil(b bool)`

 SetDownstreamTaskIdsNil sets the value for DownstreamTaskIds to be an explicit nil

### UnsetDownstreamTaskIds
`func (o *TaskResponse) UnsetDownstreamTaskIds()`

UnsetDownstreamTaskIds ensures that no value is present for DownstreamTaskIds, not even an explicit nil
### GetDocMd

`func (o *TaskResponse) GetDocMd() string`

GetDocMd returns the DocMd field if non-nil, zero value otherwise.

### GetDocMdOk

`func (o *TaskResponse) GetDocMdOk() (*string, bool)`

GetDocMdOk returns a tuple with the DocMd field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDocMd

`func (o *TaskResponse) SetDocMd(v string)`

SetDocMd sets DocMd field to given value.


### SetDocMdNil

`func (o *TaskResponse) SetDocMdNil(b bool)`

 SetDocMdNil sets the value for DocMd to be an explicit nil

### UnsetDocMd
`func (o *TaskResponse) UnsetDocMd()`

UnsetDocMd ensures that no value is present for DocMd, not even an explicit nil
### GetOperatorName

`func (o *TaskResponse) GetOperatorName() string`

GetOperatorName returns the OperatorName field if non-nil, zero value otherwise.

### GetOperatorNameOk

`func (o *TaskResponse) GetOperatorNameOk() (*string, bool)`

GetOperatorNameOk returns a tuple with the OperatorName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperatorName

`func (o *TaskResponse) SetOperatorName(v string)`

SetOperatorName sets OperatorName field to given value.


### SetOperatorNameNil

`func (o *TaskResponse) SetOperatorNameNil(b bool)`

 SetOperatorNameNil sets the value for OperatorName to be an explicit nil

### UnsetOperatorName
`func (o *TaskResponse) UnsetOperatorName()`

UnsetOperatorName ensures that no value is present for OperatorName, not even an explicit nil
### GetParams

`func (o *TaskResponse) GetParams() map[string]interface{}`

GetParams returns the Params field if non-nil, zero value otherwise.

### GetParamsOk

`func (o *TaskResponse) GetParamsOk() (*map[string]interface{}, bool)`

GetParamsOk returns a tuple with the Params field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParams

`func (o *TaskResponse) SetParams(v map[string]interface{})`

SetParams sets Params field to given value.


### SetParamsNil

`func (o *TaskResponse) SetParamsNil(b bool)`

 SetParamsNil sets the value for Params to be an explicit nil

### UnsetParams
`func (o *TaskResponse) UnsetParams()`

UnsetParams ensures that no value is present for Params, not even an explicit nil
### GetClassRef

`func (o *TaskResponse) GetClassRef() map[string]interface{}`

GetClassRef returns the ClassRef field if non-nil, zero value otherwise.

### GetClassRefOk

`func (o *TaskResponse) GetClassRefOk() (*map[string]interface{}, bool)`

GetClassRefOk returns a tuple with the ClassRef field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClassRef

`func (o *TaskResponse) SetClassRef(v map[string]interface{})`

SetClassRef sets ClassRef field to given value.


### SetClassRefNil

`func (o *TaskResponse) SetClassRefNil(b bool)`

 SetClassRefNil sets the value for ClassRef to be an explicit nil

### UnsetClassRef
`func (o *TaskResponse) UnsetClassRef()`

UnsetClassRef ensures that no value is present for ClassRef, not even an explicit nil
### GetIsMapped

`func (o *TaskResponse) GetIsMapped() bool`

GetIsMapped returns the IsMapped field if non-nil, zero value otherwise.

### GetIsMappedOk

`func (o *TaskResponse) GetIsMappedOk() (*bool, bool)`

GetIsMappedOk returns a tuple with the IsMapped field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsMapped

`func (o *TaskResponse) SetIsMapped(v bool)`

SetIsMapped sets IsMapped field to given value.


### SetIsMappedNil

`func (o *TaskResponse) SetIsMappedNil(b bool)`

 SetIsMappedNil sets the value for IsMapped to be an explicit nil

### UnsetIsMapped
`func (o *TaskResponse) UnsetIsMapped()`

UnsetIsMapped ensures that no value is present for IsMapped, not even an explicit nil
### GetExtraLinks

`func (o *TaskResponse) GetExtraLinks() []string`

GetExtraLinks returns the ExtraLinks field if non-nil, zero value otherwise.

### GetExtraLinksOk

`func (o *TaskResponse) GetExtraLinksOk() (*[]string, bool)`

GetExtraLinksOk returns a tuple with the ExtraLinks field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExtraLinks

`func (o *TaskResponse) SetExtraLinks(v []string)`

SetExtraLinks sets ExtraLinks field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


