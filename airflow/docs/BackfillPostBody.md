# BackfillPostBody

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DagId** | **string** |  | 
**FromDate** | **time.Time** |  | 
**ToDate** | **time.Time** |  | 
**RunBackwards** | Pointer to **bool** |  | [optional] [default to false]
**DagRunConf** | Pointer to **map[string]interface{}** |  | [optional] [default to {}]
**ReprocessBehavior** | Pointer to [**ReprocessBehavior**](ReprocessBehavior.md) |  | [optional] 
**MaxActiveRuns** | Pointer to **int32** |  | [optional] [default to 10]

## Methods

### NewBackfillPostBody

`func NewBackfillPostBody(dagId string, fromDate time.Time, toDate time.Time, ) *BackfillPostBody`

NewBackfillPostBody instantiates a new BackfillPostBody object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewBackfillPostBodyWithDefaults

`func NewBackfillPostBodyWithDefaults() *BackfillPostBody`

NewBackfillPostBodyWithDefaults instantiates a new BackfillPostBody object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDagId

`func (o *BackfillPostBody) GetDagId() string`

GetDagId returns the DagId field if non-nil, zero value otherwise.

### GetDagIdOk

`func (o *BackfillPostBody) GetDagIdOk() (*string, bool)`

GetDagIdOk returns a tuple with the DagId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDagId

`func (o *BackfillPostBody) SetDagId(v string)`

SetDagId sets DagId field to given value.


### GetFromDate

`func (o *BackfillPostBody) GetFromDate() time.Time`

GetFromDate returns the FromDate field if non-nil, zero value otherwise.

### GetFromDateOk

`func (o *BackfillPostBody) GetFromDateOk() (*time.Time, bool)`

GetFromDateOk returns a tuple with the FromDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFromDate

`func (o *BackfillPostBody) SetFromDate(v time.Time)`

SetFromDate sets FromDate field to given value.


### GetToDate

`func (o *BackfillPostBody) GetToDate() time.Time`

GetToDate returns the ToDate field if non-nil, zero value otherwise.

### GetToDateOk

`func (o *BackfillPostBody) GetToDateOk() (*time.Time, bool)`

GetToDateOk returns a tuple with the ToDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetToDate

`func (o *BackfillPostBody) SetToDate(v time.Time)`

SetToDate sets ToDate field to given value.


### GetRunBackwards

`func (o *BackfillPostBody) GetRunBackwards() bool`

GetRunBackwards returns the RunBackwards field if non-nil, zero value otherwise.

### GetRunBackwardsOk

`func (o *BackfillPostBody) GetRunBackwardsOk() (*bool, bool)`

GetRunBackwardsOk returns a tuple with the RunBackwards field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRunBackwards

`func (o *BackfillPostBody) SetRunBackwards(v bool)`

SetRunBackwards sets RunBackwards field to given value.

### HasRunBackwards

`func (o *BackfillPostBody) HasRunBackwards() bool`

HasRunBackwards returns a boolean if a field has been set.

### GetDagRunConf

`func (o *BackfillPostBody) GetDagRunConf() map[string]interface{}`

GetDagRunConf returns the DagRunConf field if non-nil, zero value otherwise.

### GetDagRunConfOk

`func (o *BackfillPostBody) GetDagRunConfOk() (*map[string]interface{}, bool)`

GetDagRunConfOk returns a tuple with the DagRunConf field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDagRunConf

`func (o *BackfillPostBody) SetDagRunConf(v map[string]interface{})`

SetDagRunConf sets DagRunConf field to given value.

### HasDagRunConf

`func (o *BackfillPostBody) HasDagRunConf() bool`

HasDagRunConf returns a boolean if a field has been set.

### GetReprocessBehavior

`func (o *BackfillPostBody) GetReprocessBehavior() ReprocessBehavior`

GetReprocessBehavior returns the ReprocessBehavior field if non-nil, zero value otherwise.

### GetReprocessBehaviorOk

`func (o *BackfillPostBody) GetReprocessBehaviorOk() (*ReprocessBehavior, bool)`

GetReprocessBehaviorOk returns a tuple with the ReprocessBehavior field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReprocessBehavior

`func (o *BackfillPostBody) SetReprocessBehavior(v ReprocessBehavior)`

SetReprocessBehavior sets ReprocessBehavior field to given value.

### HasReprocessBehavior

`func (o *BackfillPostBody) HasReprocessBehavior() bool`

HasReprocessBehavior returns a boolean if a field has been set.

### GetMaxActiveRuns

`func (o *BackfillPostBody) GetMaxActiveRuns() int32`

GetMaxActiveRuns returns the MaxActiveRuns field if non-nil, zero value otherwise.

### GetMaxActiveRunsOk

`func (o *BackfillPostBody) GetMaxActiveRunsOk() (*int32, bool)`

GetMaxActiveRunsOk returns a tuple with the MaxActiveRuns field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxActiveRuns

`func (o *BackfillPostBody) SetMaxActiveRuns(v int32)`

SetMaxActiveRuns sets MaxActiveRuns field to given value.

### HasMaxActiveRuns

`func (o *BackfillPostBody) HasMaxActiveRuns() bool`

HasMaxActiveRuns returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


