# BackfillResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **int32** |  | 
**DagId** | **string** |  | 
**FromDate** | **time.Time** |  | 
**ToDate** | **time.Time** |  | 
**DagRunConf** | **map[string]interface{}** |  | 
**IsPaused** | **bool** |  | 
**ReprocessBehavior** | [**ReprocessBehavior**](ReprocessBehavior.md) |  | 
**MaxActiveRuns** | **int32** |  | 
**CreatedAt** | **time.Time** |  | 
**CompletedAt** | **NullableTime** |  | 
**UpdatedAt** | **time.Time** |  | 
**DagDisplayName** | **string** |  | 

## Methods

### NewBackfillResponse

`func NewBackfillResponse(id int32, dagId string, fromDate time.Time, toDate time.Time, dagRunConf map[string]interface{}, isPaused bool, reprocessBehavior ReprocessBehavior, maxActiveRuns int32, createdAt time.Time, completedAt NullableTime, updatedAt time.Time, dagDisplayName string, ) *BackfillResponse`

NewBackfillResponse instantiates a new BackfillResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewBackfillResponseWithDefaults

`func NewBackfillResponseWithDefaults() *BackfillResponse`

NewBackfillResponseWithDefaults instantiates a new BackfillResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *BackfillResponse) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *BackfillResponse) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *BackfillResponse) SetId(v int32)`

SetId sets Id field to given value.


### GetDagId

`func (o *BackfillResponse) GetDagId() string`

GetDagId returns the DagId field if non-nil, zero value otherwise.

### GetDagIdOk

`func (o *BackfillResponse) GetDagIdOk() (*string, bool)`

GetDagIdOk returns a tuple with the DagId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDagId

`func (o *BackfillResponse) SetDagId(v string)`

SetDagId sets DagId field to given value.


### GetFromDate

`func (o *BackfillResponse) GetFromDate() time.Time`

GetFromDate returns the FromDate field if non-nil, zero value otherwise.

### GetFromDateOk

`func (o *BackfillResponse) GetFromDateOk() (*time.Time, bool)`

GetFromDateOk returns a tuple with the FromDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFromDate

`func (o *BackfillResponse) SetFromDate(v time.Time)`

SetFromDate sets FromDate field to given value.


### GetToDate

`func (o *BackfillResponse) GetToDate() time.Time`

GetToDate returns the ToDate field if non-nil, zero value otherwise.

### GetToDateOk

`func (o *BackfillResponse) GetToDateOk() (*time.Time, bool)`

GetToDateOk returns a tuple with the ToDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetToDate

`func (o *BackfillResponse) SetToDate(v time.Time)`

SetToDate sets ToDate field to given value.


### GetDagRunConf

`func (o *BackfillResponse) GetDagRunConf() map[string]interface{}`

GetDagRunConf returns the DagRunConf field if non-nil, zero value otherwise.

### GetDagRunConfOk

`func (o *BackfillResponse) GetDagRunConfOk() (*map[string]interface{}, bool)`

GetDagRunConfOk returns a tuple with the DagRunConf field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDagRunConf

`func (o *BackfillResponse) SetDagRunConf(v map[string]interface{})`

SetDagRunConf sets DagRunConf field to given value.


### GetIsPaused

`func (o *BackfillResponse) GetIsPaused() bool`

GetIsPaused returns the IsPaused field if non-nil, zero value otherwise.

### GetIsPausedOk

`func (o *BackfillResponse) GetIsPausedOk() (*bool, bool)`

GetIsPausedOk returns a tuple with the IsPaused field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsPaused

`func (o *BackfillResponse) SetIsPaused(v bool)`

SetIsPaused sets IsPaused field to given value.


### GetReprocessBehavior

`func (o *BackfillResponse) GetReprocessBehavior() ReprocessBehavior`

GetReprocessBehavior returns the ReprocessBehavior field if non-nil, zero value otherwise.

### GetReprocessBehaviorOk

`func (o *BackfillResponse) GetReprocessBehaviorOk() (*ReprocessBehavior, bool)`

GetReprocessBehaviorOk returns a tuple with the ReprocessBehavior field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReprocessBehavior

`func (o *BackfillResponse) SetReprocessBehavior(v ReprocessBehavior)`

SetReprocessBehavior sets ReprocessBehavior field to given value.


### GetMaxActiveRuns

`func (o *BackfillResponse) GetMaxActiveRuns() int32`

GetMaxActiveRuns returns the MaxActiveRuns field if non-nil, zero value otherwise.

### GetMaxActiveRunsOk

`func (o *BackfillResponse) GetMaxActiveRunsOk() (*int32, bool)`

GetMaxActiveRunsOk returns a tuple with the MaxActiveRuns field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxActiveRuns

`func (o *BackfillResponse) SetMaxActiveRuns(v int32)`

SetMaxActiveRuns sets MaxActiveRuns field to given value.


### GetCreatedAt

`func (o *BackfillResponse) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *BackfillResponse) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *BackfillResponse) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetCompletedAt

`func (o *BackfillResponse) GetCompletedAt() time.Time`

GetCompletedAt returns the CompletedAt field if non-nil, zero value otherwise.

### GetCompletedAtOk

`func (o *BackfillResponse) GetCompletedAtOk() (*time.Time, bool)`

GetCompletedAtOk returns a tuple with the CompletedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompletedAt

`func (o *BackfillResponse) SetCompletedAt(v time.Time)`

SetCompletedAt sets CompletedAt field to given value.


### SetCompletedAtNil

`func (o *BackfillResponse) SetCompletedAtNil(b bool)`

 SetCompletedAtNil sets the value for CompletedAt to be an explicit nil

### UnsetCompletedAt
`func (o *BackfillResponse) UnsetCompletedAt()`

UnsetCompletedAt ensures that no value is present for CompletedAt, not even an explicit nil
### GetUpdatedAt

`func (o *BackfillResponse) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *BackfillResponse) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *BackfillResponse) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.


### GetDagDisplayName

`func (o *BackfillResponse) GetDagDisplayName() string`

GetDagDisplayName returns the DagDisplayName field if non-nil, zero value otherwise.

### GetDagDisplayNameOk

`func (o *BackfillResponse) GetDagDisplayNameOk() (*string, bool)`

GetDagDisplayNameOk returns a tuple with the DagDisplayName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDagDisplayName

`func (o *BackfillResponse) SetDagDisplayName(v string)`

SetDagDisplayName sets DagDisplayName field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


