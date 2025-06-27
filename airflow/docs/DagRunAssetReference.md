# DagRunAssetReference

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**RunId** | **string** |  | 
**DagId** | **string** |  | 
**LogicalDate** | **NullableTime** |  | 
**StartDate** | **time.Time** |  | 
**EndDate** | **NullableTime** |  | 
**State** | **string** |  | 
**DataIntervalStart** | **NullableTime** |  | 
**DataIntervalEnd** | **NullableTime** |  | 

## Methods

### NewDagRunAssetReference

`func NewDagRunAssetReference(runId string, dagId string, logicalDate NullableTime, startDate time.Time, endDate NullableTime, state string, dataIntervalStart NullableTime, dataIntervalEnd NullableTime, ) *DagRunAssetReference`

NewDagRunAssetReference instantiates a new DagRunAssetReference object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDagRunAssetReferenceWithDefaults

`func NewDagRunAssetReferenceWithDefaults() *DagRunAssetReference`

NewDagRunAssetReferenceWithDefaults instantiates a new DagRunAssetReference object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetRunId

`func (o *DagRunAssetReference) GetRunId() string`

GetRunId returns the RunId field if non-nil, zero value otherwise.

### GetRunIdOk

`func (o *DagRunAssetReference) GetRunIdOk() (*string, bool)`

GetRunIdOk returns a tuple with the RunId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRunId

`func (o *DagRunAssetReference) SetRunId(v string)`

SetRunId sets RunId field to given value.


### GetDagId

`func (o *DagRunAssetReference) GetDagId() string`

GetDagId returns the DagId field if non-nil, zero value otherwise.

### GetDagIdOk

`func (o *DagRunAssetReference) GetDagIdOk() (*string, bool)`

GetDagIdOk returns a tuple with the DagId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDagId

`func (o *DagRunAssetReference) SetDagId(v string)`

SetDagId sets DagId field to given value.


### GetLogicalDate

`func (o *DagRunAssetReference) GetLogicalDate() time.Time`

GetLogicalDate returns the LogicalDate field if non-nil, zero value otherwise.

### GetLogicalDateOk

`func (o *DagRunAssetReference) GetLogicalDateOk() (*time.Time, bool)`

GetLogicalDateOk returns a tuple with the LogicalDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLogicalDate

`func (o *DagRunAssetReference) SetLogicalDate(v time.Time)`

SetLogicalDate sets LogicalDate field to given value.


### SetLogicalDateNil

`func (o *DagRunAssetReference) SetLogicalDateNil(b bool)`

 SetLogicalDateNil sets the value for LogicalDate to be an explicit nil

### UnsetLogicalDate
`func (o *DagRunAssetReference) UnsetLogicalDate()`

UnsetLogicalDate ensures that no value is present for LogicalDate, not even an explicit nil
### GetStartDate

`func (o *DagRunAssetReference) GetStartDate() time.Time`

GetStartDate returns the StartDate field if non-nil, zero value otherwise.

### GetStartDateOk

`func (o *DagRunAssetReference) GetStartDateOk() (*time.Time, bool)`

GetStartDateOk returns a tuple with the StartDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartDate

`func (o *DagRunAssetReference) SetStartDate(v time.Time)`

SetStartDate sets StartDate field to given value.


### GetEndDate

`func (o *DagRunAssetReference) GetEndDate() time.Time`

GetEndDate returns the EndDate field if non-nil, zero value otherwise.

### GetEndDateOk

`func (o *DagRunAssetReference) GetEndDateOk() (*time.Time, bool)`

GetEndDateOk returns a tuple with the EndDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEndDate

`func (o *DagRunAssetReference) SetEndDate(v time.Time)`

SetEndDate sets EndDate field to given value.


### SetEndDateNil

`func (o *DagRunAssetReference) SetEndDateNil(b bool)`

 SetEndDateNil sets the value for EndDate to be an explicit nil

### UnsetEndDate
`func (o *DagRunAssetReference) UnsetEndDate()`

UnsetEndDate ensures that no value is present for EndDate, not even an explicit nil
### GetState

`func (o *DagRunAssetReference) GetState() string`

GetState returns the State field if non-nil, zero value otherwise.

### GetStateOk

`func (o *DagRunAssetReference) GetStateOk() (*string, bool)`

GetStateOk returns a tuple with the State field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetState

`func (o *DagRunAssetReference) SetState(v string)`

SetState sets State field to given value.


### GetDataIntervalStart

`func (o *DagRunAssetReference) GetDataIntervalStart() time.Time`

GetDataIntervalStart returns the DataIntervalStart field if non-nil, zero value otherwise.

### GetDataIntervalStartOk

`func (o *DagRunAssetReference) GetDataIntervalStartOk() (*time.Time, bool)`

GetDataIntervalStartOk returns a tuple with the DataIntervalStart field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDataIntervalStart

`func (o *DagRunAssetReference) SetDataIntervalStart(v time.Time)`

SetDataIntervalStart sets DataIntervalStart field to given value.


### SetDataIntervalStartNil

`func (o *DagRunAssetReference) SetDataIntervalStartNil(b bool)`

 SetDataIntervalStartNil sets the value for DataIntervalStart to be an explicit nil

### UnsetDataIntervalStart
`func (o *DagRunAssetReference) UnsetDataIntervalStart()`

UnsetDataIntervalStart ensures that no value is present for DataIntervalStart, not even an explicit nil
### GetDataIntervalEnd

`func (o *DagRunAssetReference) GetDataIntervalEnd() time.Time`

GetDataIntervalEnd returns the DataIntervalEnd field if non-nil, zero value otherwise.

### GetDataIntervalEndOk

`func (o *DagRunAssetReference) GetDataIntervalEndOk() (*time.Time, bool)`

GetDataIntervalEndOk returns a tuple with the DataIntervalEnd field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDataIntervalEnd

`func (o *DagRunAssetReference) SetDataIntervalEnd(v time.Time)`

SetDataIntervalEnd sets DataIntervalEnd field to given value.


### SetDataIntervalEndNil

`func (o *DagRunAssetReference) SetDataIntervalEndNil(b bool)`

 SetDataIntervalEndNil sets the value for DataIntervalEnd to be an explicit nil

### UnsetDataIntervalEnd
`func (o *DagRunAssetReference) UnsetDataIntervalEnd()`

UnsetDataIntervalEnd ensures that no value is present for DataIntervalEnd, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


