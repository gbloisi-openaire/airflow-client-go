# JobResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **int32** |  | 
**DagId** | **NullableString** |  | 
**State** | **NullableString** |  | 
**JobType** | **NullableString** |  | 
**StartDate** | **NullableTime** |  | 
**EndDate** | **NullableTime** |  | 
**LatestHeartbeat** | **NullableTime** |  | 
**ExecutorClass** | **NullableString** |  | 
**Hostname** | **NullableString** |  | 
**Unixname** | **NullableString** |  | 
**DagDisplayName** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewJobResponse

`func NewJobResponse(id int32, dagId NullableString, state NullableString, jobType NullableString, startDate NullableTime, endDate NullableTime, latestHeartbeat NullableTime, executorClass NullableString, hostname NullableString, unixname NullableString, ) *JobResponse`

NewJobResponse instantiates a new JobResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewJobResponseWithDefaults

`func NewJobResponseWithDefaults() *JobResponse`

NewJobResponseWithDefaults instantiates a new JobResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *JobResponse) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *JobResponse) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *JobResponse) SetId(v int32)`

SetId sets Id field to given value.


### GetDagId

`func (o *JobResponse) GetDagId() string`

GetDagId returns the DagId field if non-nil, zero value otherwise.

### GetDagIdOk

`func (o *JobResponse) GetDagIdOk() (*string, bool)`

GetDagIdOk returns a tuple with the DagId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDagId

`func (o *JobResponse) SetDagId(v string)`

SetDagId sets DagId field to given value.


### SetDagIdNil

`func (o *JobResponse) SetDagIdNil(b bool)`

 SetDagIdNil sets the value for DagId to be an explicit nil

### UnsetDagId
`func (o *JobResponse) UnsetDagId()`

UnsetDagId ensures that no value is present for DagId, not even an explicit nil
### GetState

`func (o *JobResponse) GetState() string`

GetState returns the State field if non-nil, zero value otherwise.

### GetStateOk

`func (o *JobResponse) GetStateOk() (*string, bool)`

GetStateOk returns a tuple with the State field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetState

`func (o *JobResponse) SetState(v string)`

SetState sets State field to given value.


### SetStateNil

`func (o *JobResponse) SetStateNil(b bool)`

 SetStateNil sets the value for State to be an explicit nil

### UnsetState
`func (o *JobResponse) UnsetState()`

UnsetState ensures that no value is present for State, not even an explicit nil
### GetJobType

`func (o *JobResponse) GetJobType() string`

GetJobType returns the JobType field if non-nil, zero value otherwise.

### GetJobTypeOk

`func (o *JobResponse) GetJobTypeOk() (*string, bool)`

GetJobTypeOk returns a tuple with the JobType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJobType

`func (o *JobResponse) SetJobType(v string)`

SetJobType sets JobType field to given value.


### SetJobTypeNil

`func (o *JobResponse) SetJobTypeNil(b bool)`

 SetJobTypeNil sets the value for JobType to be an explicit nil

### UnsetJobType
`func (o *JobResponse) UnsetJobType()`

UnsetJobType ensures that no value is present for JobType, not even an explicit nil
### GetStartDate

`func (o *JobResponse) GetStartDate() time.Time`

GetStartDate returns the StartDate field if non-nil, zero value otherwise.

### GetStartDateOk

`func (o *JobResponse) GetStartDateOk() (*time.Time, bool)`

GetStartDateOk returns a tuple with the StartDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartDate

`func (o *JobResponse) SetStartDate(v time.Time)`

SetStartDate sets StartDate field to given value.


### SetStartDateNil

`func (o *JobResponse) SetStartDateNil(b bool)`

 SetStartDateNil sets the value for StartDate to be an explicit nil

### UnsetStartDate
`func (o *JobResponse) UnsetStartDate()`

UnsetStartDate ensures that no value is present for StartDate, not even an explicit nil
### GetEndDate

`func (o *JobResponse) GetEndDate() time.Time`

GetEndDate returns the EndDate field if non-nil, zero value otherwise.

### GetEndDateOk

`func (o *JobResponse) GetEndDateOk() (*time.Time, bool)`

GetEndDateOk returns a tuple with the EndDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEndDate

`func (o *JobResponse) SetEndDate(v time.Time)`

SetEndDate sets EndDate field to given value.


### SetEndDateNil

`func (o *JobResponse) SetEndDateNil(b bool)`

 SetEndDateNil sets the value for EndDate to be an explicit nil

### UnsetEndDate
`func (o *JobResponse) UnsetEndDate()`

UnsetEndDate ensures that no value is present for EndDate, not even an explicit nil
### GetLatestHeartbeat

`func (o *JobResponse) GetLatestHeartbeat() time.Time`

GetLatestHeartbeat returns the LatestHeartbeat field if non-nil, zero value otherwise.

### GetLatestHeartbeatOk

`func (o *JobResponse) GetLatestHeartbeatOk() (*time.Time, bool)`

GetLatestHeartbeatOk returns a tuple with the LatestHeartbeat field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLatestHeartbeat

`func (o *JobResponse) SetLatestHeartbeat(v time.Time)`

SetLatestHeartbeat sets LatestHeartbeat field to given value.


### SetLatestHeartbeatNil

`func (o *JobResponse) SetLatestHeartbeatNil(b bool)`

 SetLatestHeartbeatNil sets the value for LatestHeartbeat to be an explicit nil

### UnsetLatestHeartbeat
`func (o *JobResponse) UnsetLatestHeartbeat()`

UnsetLatestHeartbeat ensures that no value is present for LatestHeartbeat, not even an explicit nil
### GetExecutorClass

`func (o *JobResponse) GetExecutorClass() string`

GetExecutorClass returns the ExecutorClass field if non-nil, zero value otherwise.

### GetExecutorClassOk

`func (o *JobResponse) GetExecutorClassOk() (*string, bool)`

GetExecutorClassOk returns a tuple with the ExecutorClass field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExecutorClass

`func (o *JobResponse) SetExecutorClass(v string)`

SetExecutorClass sets ExecutorClass field to given value.


### SetExecutorClassNil

`func (o *JobResponse) SetExecutorClassNil(b bool)`

 SetExecutorClassNil sets the value for ExecutorClass to be an explicit nil

### UnsetExecutorClass
`func (o *JobResponse) UnsetExecutorClass()`

UnsetExecutorClass ensures that no value is present for ExecutorClass, not even an explicit nil
### GetHostname

`func (o *JobResponse) GetHostname() string`

GetHostname returns the Hostname field if non-nil, zero value otherwise.

### GetHostnameOk

`func (o *JobResponse) GetHostnameOk() (*string, bool)`

GetHostnameOk returns a tuple with the Hostname field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHostname

`func (o *JobResponse) SetHostname(v string)`

SetHostname sets Hostname field to given value.


### SetHostnameNil

`func (o *JobResponse) SetHostnameNil(b bool)`

 SetHostnameNil sets the value for Hostname to be an explicit nil

### UnsetHostname
`func (o *JobResponse) UnsetHostname()`

UnsetHostname ensures that no value is present for Hostname, not even an explicit nil
### GetUnixname

`func (o *JobResponse) GetUnixname() string`

GetUnixname returns the Unixname field if non-nil, zero value otherwise.

### GetUnixnameOk

`func (o *JobResponse) GetUnixnameOk() (*string, bool)`

GetUnixnameOk returns a tuple with the Unixname field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnixname

`func (o *JobResponse) SetUnixname(v string)`

SetUnixname sets Unixname field to given value.


### SetUnixnameNil

`func (o *JobResponse) SetUnixnameNil(b bool)`

 SetUnixnameNil sets the value for Unixname to be an explicit nil

### UnsetUnixname
`func (o *JobResponse) UnsetUnixname()`

UnsetUnixname ensures that no value is present for Unixname, not even an explicit nil
### GetDagDisplayName

`func (o *JobResponse) GetDagDisplayName() string`

GetDagDisplayName returns the DagDisplayName field if non-nil, zero value otherwise.

### GetDagDisplayNameOk

`func (o *JobResponse) GetDagDisplayNameOk() (*string, bool)`

GetDagDisplayNameOk returns a tuple with the DagDisplayName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDagDisplayName

`func (o *JobResponse) SetDagDisplayName(v string)`

SetDagDisplayName sets DagDisplayName field to given value.

### HasDagDisplayName

`func (o *JobResponse) HasDagDisplayName() bool`

HasDagDisplayName returns a boolean if a field has been set.

### SetDagDisplayNameNil

`func (o *JobResponse) SetDagDisplayNameNil(b bool)`

 SetDagDisplayNameNil sets the value for DagDisplayName to be an explicit nil

### UnsetDagDisplayName
`func (o *JobResponse) UnsetDagDisplayName()`

UnsetDagDisplayName ensures that no value is present for DagDisplayName, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


