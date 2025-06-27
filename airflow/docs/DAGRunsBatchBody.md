# DAGRunsBatchBody

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**OrderBy** | Pointer to **NullableString** |  | [optional] 
**PageOffset** | Pointer to **int32** |  | [optional] [default to 0]
**PageLimit** | Pointer to **int32** |  | [optional] [default to 100]
**DagIds** | Pointer to **[]string** |  | [optional] 
**States** | Pointer to [**[]DagRunState**](DagRunState.md) |  | [optional] 
**RunAfterGte** | Pointer to **NullableTime** |  | [optional] 
**RunAfterLte** | Pointer to **NullableTime** |  | [optional] 
**LogicalDateGte** | Pointer to **NullableTime** |  | [optional] 
**LogicalDateLte** | Pointer to **NullableTime** |  | [optional] 
**StartDateGte** | Pointer to **NullableTime** |  | [optional] 
**StartDateLte** | Pointer to **NullableTime** |  | [optional] 
**EndDateGte** | Pointer to **NullableTime** |  | [optional] 
**EndDateLte** | Pointer to **NullableTime** |  | [optional] 

## Methods

### NewDAGRunsBatchBody

`func NewDAGRunsBatchBody() *DAGRunsBatchBody`

NewDAGRunsBatchBody instantiates a new DAGRunsBatchBody object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDAGRunsBatchBodyWithDefaults

`func NewDAGRunsBatchBodyWithDefaults() *DAGRunsBatchBody`

NewDAGRunsBatchBodyWithDefaults instantiates a new DAGRunsBatchBody object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetOrderBy

`func (o *DAGRunsBatchBody) GetOrderBy() string`

GetOrderBy returns the OrderBy field if non-nil, zero value otherwise.

### GetOrderByOk

`func (o *DAGRunsBatchBody) GetOrderByOk() (*string, bool)`

GetOrderByOk returns a tuple with the OrderBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrderBy

`func (o *DAGRunsBatchBody) SetOrderBy(v string)`

SetOrderBy sets OrderBy field to given value.

### HasOrderBy

`func (o *DAGRunsBatchBody) HasOrderBy() bool`

HasOrderBy returns a boolean if a field has been set.

### SetOrderByNil

`func (o *DAGRunsBatchBody) SetOrderByNil(b bool)`

 SetOrderByNil sets the value for OrderBy to be an explicit nil

### UnsetOrderBy
`func (o *DAGRunsBatchBody) UnsetOrderBy()`

UnsetOrderBy ensures that no value is present for OrderBy, not even an explicit nil
### GetPageOffset

`func (o *DAGRunsBatchBody) GetPageOffset() int32`

GetPageOffset returns the PageOffset field if non-nil, zero value otherwise.

### GetPageOffsetOk

`func (o *DAGRunsBatchBody) GetPageOffsetOk() (*int32, bool)`

GetPageOffsetOk returns a tuple with the PageOffset field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPageOffset

`func (o *DAGRunsBatchBody) SetPageOffset(v int32)`

SetPageOffset sets PageOffset field to given value.

### HasPageOffset

`func (o *DAGRunsBatchBody) HasPageOffset() bool`

HasPageOffset returns a boolean if a field has been set.

### GetPageLimit

`func (o *DAGRunsBatchBody) GetPageLimit() int32`

GetPageLimit returns the PageLimit field if non-nil, zero value otherwise.

### GetPageLimitOk

`func (o *DAGRunsBatchBody) GetPageLimitOk() (*int32, bool)`

GetPageLimitOk returns a tuple with the PageLimit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPageLimit

`func (o *DAGRunsBatchBody) SetPageLimit(v int32)`

SetPageLimit sets PageLimit field to given value.

### HasPageLimit

`func (o *DAGRunsBatchBody) HasPageLimit() bool`

HasPageLimit returns a boolean if a field has been set.

### GetDagIds

`func (o *DAGRunsBatchBody) GetDagIds() []string`

GetDagIds returns the DagIds field if non-nil, zero value otherwise.

### GetDagIdsOk

`func (o *DAGRunsBatchBody) GetDagIdsOk() (*[]string, bool)`

GetDagIdsOk returns a tuple with the DagIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDagIds

`func (o *DAGRunsBatchBody) SetDagIds(v []string)`

SetDagIds sets DagIds field to given value.

### HasDagIds

`func (o *DAGRunsBatchBody) HasDagIds() bool`

HasDagIds returns a boolean if a field has been set.

### SetDagIdsNil

`func (o *DAGRunsBatchBody) SetDagIdsNil(b bool)`

 SetDagIdsNil sets the value for DagIds to be an explicit nil

### UnsetDagIds
`func (o *DAGRunsBatchBody) UnsetDagIds()`

UnsetDagIds ensures that no value is present for DagIds, not even an explicit nil
### GetStates

`func (o *DAGRunsBatchBody) GetStates() []DagRunState`

GetStates returns the States field if non-nil, zero value otherwise.

### GetStatesOk

`func (o *DAGRunsBatchBody) GetStatesOk() (*[]DagRunState, bool)`

GetStatesOk returns a tuple with the States field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStates

`func (o *DAGRunsBatchBody) SetStates(v []DagRunState)`

SetStates sets States field to given value.

### HasStates

`func (o *DAGRunsBatchBody) HasStates() bool`

HasStates returns a boolean if a field has been set.

### SetStatesNil

`func (o *DAGRunsBatchBody) SetStatesNil(b bool)`

 SetStatesNil sets the value for States to be an explicit nil

### UnsetStates
`func (o *DAGRunsBatchBody) UnsetStates()`

UnsetStates ensures that no value is present for States, not even an explicit nil
### GetRunAfterGte

`func (o *DAGRunsBatchBody) GetRunAfterGte() time.Time`

GetRunAfterGte returns the RunAfterGte field if non-nil, zero value otherwise.

### GetRunAfterGteOk

`func (o *DAGRunsBatchBody) GetRunAfterGteOk() (*time.Time, bool)`

GetRunAfterGteOk returns a tuple with the RunAfterGte field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRunAfterGte

`func (o *DAGRunsBatchBody) SetRunAfterGte(v time.Time)`

SetRunAfterGte sets RunAfterGte field to given value.

### HasRunAfterGte

`func (o *DAGRunsBatchBody) HasRunAfterGte() bool`

HasRunAfterGte returns a boolean if a field has been set.

### SetRunAfterGteNil

`func (o *DAGRunsBatchBody) SetRunAfterGteNil(b bool)`

 SetRunAfterGteNil sets the value for RunAfterGte to be an explicit nil

### UnsetRunAfterGte
`func (o *DAGRunsBatchBody) UnsetRunAfterGte()`

UnsetRunAfterGte ensures that no value is present for RunAfterGte, not even an explicit nil
### GetRunAfterLte

`func (o *DAGRunsBatchBody) GetRunAfterLte() time.Time`

GetRunAfterLte returns the RunAfterLte field if non-nil, zero value otherwise.

### GetRunAfterLteOk

`func (o *DAGRunsBatchBody) GetRunAfterLteOk() (*time.Time, bool)`

GetRunAfterLteOk returns a tuple with the RunAfterLte field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRunAfterLte

`func (o *DAGRunsBatchBody) SetRunAfterLte(v time.Time)`

SetRunAfterLte sets RunAfterLte field to given value.

### HasRunAfterLte

`func (o *DAGRunsBatchBody) HasRunAfterLte() bool`

HasRunAfterLte returns a boolean if a field has been set.

### SetRunAfterLteNil

`func (o *DAGRunsBatchBody) SetRunAfterLteNil(b bool)`

 SetRunAfterLteNil sets the value for RunAfterLte to be an explicit nil

### UnsetRunAfterLte
`func (o *DAGRunsBatchBody) UnsetRunAfterLte()`

UnsetRunAfterLte ensures that no value is present for RunAfterLte, not even an explicit nil
### GetLogicalDateGte

`func (o *DAGRunsBatchBody) GetLogicalDateGte() time.Time`

GetLogicalDateGte returns the LogicalDateGte field if non-nil, zero value otherwise.

### GetLogicalDateGteOk

`func (o *DAGRunsBatchBody) GetLogicalDateGteOk() (*time.Time, bool)`

GetLogicalDateGteOk returns a tuple with the LogicalDateGte field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLogicalDateGte

`func (o *DAGRunsBatchBody) SetLogicalDateGte(v time.Time)`

SetLogicalDateGte sets LogicalDateGte field to given value.

### HasLogicalDateGte

`func (o *DAGRunsBatchBody) HasLogicalDateGte() bool`

HasLogicalDateGte returns a boolean if a field has been set.

### SetLogicalDateGteNil

`func (o *DAGRunsBatchBody) SetLogicalDateGteNil(b bool)`

 SetLogicalDateGteNil sets the value for LogicalDateGte to be an explicit nil

### UnsetLogicalDateGte
`func (o *DAGRunsBatchBody) UnsetLogicalDateGte()`

UnsetLogicalDateGte ensures that no value is present for LogicalDateGte, not even an explicit nil
### GetLogicalDateLte

`func (o *DAGRunsBatchBody) GetLogicalDateLte() time.Time`

GetLogicalDateLte returns the LogicalDateLte field if non-nil, zero value otherwise.

### GetLogicalDateLteOk

`func (o *DAGRunsBatchBody) GetLogicalDateLteOk() (*time.Time, bool)`

GetLogicalDateLteOk returns a tuple with the LogicalDateLte field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLogicalDateLte

`func (o *DAGRunsBatchBody) SetLogicalDateLte(v time.Time)`

SetLogicalDateLte sets LogicalDateLte field to given value.

### HasLogicalDateLte

`func (o *DAGRunsBatchBody) HasLogicalDateLte() bool`

HasLogicalDateLte returns a boolean if a field has been set.

### SetLogicalDateLteNil

`func (o *DAGRunsBatchBody) SetLogicalDateLteNil(b bool)`

 SetLogicalDateLteNil sets the value for LogicalDateLte to be an explicit nil

### UnsetLogicalDateLte
`func (o *DAGRunsBatchBody) UnsetLogicalDateLte()`

UnsetLogicalDateLte ensures that no value is present for LogicalDateLte, not even an explicit nil
### GetStartDateGte

`func (o *DAGRunsBatchBody) GetStartDateGte() time.Time`

GetStartDateGte returns the StartDateGte field if non-nil, zero value otherwise.

### GetStartDateGteOk

`func (o *DAGRunsBatchBody) GetStartDateGteOk() (*time.Time, bool)`

GetStartDateGteOk returns a tuple with the StartDateGte field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartDateGte

`func (o *DAGRunsBatchBody) SetStartDateGte(v time.Time)`

SetStartDateGte sets StartDateGte field to given value.

### HasStartDateGte

`func (o *DAGRunsBatchBody) HasStartDateGte() bool`

HasStartDateGte returns a boolean if a field has been set.

### SetStartDateGteNil

`func (o *DAGRunsBatchBody) SetStartDateGteNil(b bool)`

 SetStartDateGteNil sets the value for StartDateGte to be an explicit nil

### UnsetStartDateGte
`func (o *DAGRunsBatchBody) UnsetStartDateGte()`

UnsetStartDateGte ensures that no value is present for StartDateGte, not even an explicit nil
### GetStartDateLte

`func (o *DAGRunsBatchBody) GetStartDateLte() time.Time`

GetStartDateLte returns the StartDateLte field if non-nil, zero value otherwise.

### GetStartDateLteOk

`func (o *DAGRunsBatchBody) GetStartDateLteOk() (*time.Time, bool)`

GetStartDateLteOk returns a tuple with the StartDateLte field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartDateLte

`func (o *DAGRunsBatchBody) SetStartDateLte(v time.Time)`

SetStartDateLte sets StartDateLte field to given value.

### HasStartDateLte

`func (o *DAGRunsBatchBody) HasStartDateLte() bool`

HasStartDateLte returns a boolean if a field has been set.

### SetStartDateLteNil

`func (o *DAGRunsBatchBody) SetStartDateLteNil(b bool)`

 SetStartDateLteNil sets the value for StartDateLte to be an explicit nil

### UnsetStartDateLte
`func (o *DAGRunsBatchBody) UnsetStartDateLte()`

UnsetStartDateLte ensures that no value is present for StartDateLte, not even an explicit nil
### GetEndDateGte

`func (o *DAGRunsBatchBody) GetEndDateGte() time.Time`

GetEndDateGte returns the EndDateGte field if non-nil, zero value otherwise.

### GetEndDateGteOk

`func (o *DAGRunsBatchBody) GetEndDateGteOk() (*time.Time, bool)`

GetEndDateGteOk returns a tuple with the EndDateGte field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEndDateGte

`func (o *DAGRunsBatchBody) SetEndDateGte(v time.Time)`

SetEndDateGte sets EndDateGte field to given value.

### HasEndDateGte

`func (o *DAGRunsBatchBody) HasEndDateGte() bool`

HasEndDateGte returns a boolean if a field has been set.

### SetEndDateGteNil

`func (o *DAGRunsBatchBody) SetEndDateGteNil(b bool)`

 SetEndDateGteNil sets the value for EndDateGte to be an explicit nil

### UnsetEndDateGte
`func (o *DAGRunsBatchBody) UnsetEndDateGte()`

UnsetEndDateGte ensures that no value is present for EndDateGte, not even an explicit nil
### GetEndDateLte

`func (o *DAGRunsBatchBody) GetEndDateLte() time.Time`

GetEndDateLte returns the EndDateLte field if non-nil, zero value otherwise.

### GetEndDateLteOk

`func (o *DAGRunsBatchBody) GetEndDateLteOk() (*time.Time, bool)`

GetEndDateLteOk returns a tuple with the EndDateLte field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEndDateLte

`func (o *DAGRunsBatchBody) SetEndDateLte(v time.Time)`

SetEndDateLte sets EndDateLte field to given value.

### HasEndDateLte

`func (o *DAGRunsBatchBody) HasEndDateLte() bool`

HasEndDateLte returns a boolean if a field has been set.

### SetEndDateLteNil

`func (o *DAGRunsBatchBody) SetEndDateLteNil(b bool)`

 SetEndDateLteNil sets the value for EndDateLte to be an explicit nil

### UnsetEndDateLte
`func (o *DAGRunsBatchBody) UnsetEndDateLte()`

UnsetEndDateLte ensures that no value is present for EndDateLte, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


