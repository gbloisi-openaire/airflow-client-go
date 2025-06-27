# JobCollectionResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Jobs** | [**[]JobResponse**](JobResponse.md) |  | 
**TotalEntries** | **int32** |  | 

## Methods

### NewJobCollectionResponse

`func NewJobCollectionResponse(jobs []JobResponse, totalEntries int32, ) *JobCollectionResponse`

NewJobCollectionResponse instantiates a new JobCollectionResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewJobCollectionResponseWithDefaults

`func NewJobCollectionResponseWithDefaults() *JobCollectionResponse`

NewJobCollectionResponseWithDefaults instantiates a new JobCollectionResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetJobs

`func (o *JobCollectionResponse) GetJobs() []JobResponse`

GetJobs returns the Jobs field if non-nil, zero value otherwise.

### GetJobsOk

`func (o *JobCollectionResponse) GetJobsOk() (*[]JobResponse, bool)`

GetJobsOk returns a tuple with the Jobs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJobs

`func (o *JobCollectionResponse) SetJobs(v []JobResponse)`

SetJobs sets Jobs field to given value.


### GetTotalEntries

`func (o *JobCollectionResponse) GetTotalEntries() int32`

GetTotalEntries returns the TotalEntries field if non-nil, zero value otherwise.

### GetTotalEntriesOk

`func (o *JobCollectionResponse) GetTotalEntriesOk() (*int32, bool)`

GetTotalEntriesOk returns a tuple with the TotalEntries field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalEntries

`func (o *JobCollectionResponse) SetTotalEntries(v int32)`

SetTotalEntries sets TotalEntries field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


