# DAGResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DagId** | **string** |  | 
**DagDisplayName** | **string** |  | 
**IsPaused** | **bool** |  | 
**IsStale** | **bool** |  | 
**LastParsedTime** | **NullableTime** |  | 
**LastExpired** | **NullableTime** |  | 
**BundleName** | **NullableString** |  | 
**BundleVersion** | **NullableString** |  | 
**RelativeFileloc** | **NullableString** |  | 
**Fileloc** | **string** |  | 
**Description** | **NullableString** |  | 
**Deadline** | [**[]DeadlineAlertResponse**](DeadlineAlertResponse.md) |  | 
**TimetableSummary** | **NullableString** |  | 
**TimetableDescription** | **NullableString** |  | 
**Tags** | [**[]DagTagResponse**](DagTagResponse.md) |  | 
**MaxActiveTasks** | **int32** |  | 
**MaxActiveRuns** | **NullableInt32** |  | 
**MaxConsecutiveFailedDagRuns** | **int32** |  | 
**HasTaskConcurrencyLimits** | **bool** |  | 
**HasImportErrors** | **bool** |  | 
**NextDagrunLogicalDate** | **NullableTime** |  | 
**NextDagrunDataIntervalStart** | **NullableTime** |  | 
**NextDagrunDataIntervalEnd** | **NullableTime** |  | 
**NextDagrunRunAfter** | **NullableTime** |  | 
**Owners** | **[]string** |  | 
**FileToken** | **string** | Return file token. | [readonly] 

## Methods

### NewDAGResponse

`func NewDAGResponse(dagId string, dagDisplayName string, isPaused bool, isStale bool, lastParsedTime NullableTime, lastExpired NullableTime, bundleName NullableString, bundleVersion NullableString, relativeFileloc NullableString, fileloc string, description NullableString, deadline []DeadlineAlertResponse, timetableSummary NullableString, timetableDescription NullableString, tags []DagTagResponse, maxActiveTasks int32, maxActiveRuns NullableInt32, maxConsecutiveFailedDagRuns int32, hasTaskConcurrencyLimits bool, hasImportErrors bool, nextDagrunLogicalDate NullableTime, nextDagrunDataIntervalStart NullableTime, nextDagrunDataIntervalEnd NullableTime, nextDagrunRunAfter NullableTime, owners []string, fileToken string, ) *DAGResponse`

NewDAGResponse instantiates a new DAGResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDAGResponseWithDefaults

`func NewDAGResponseWithDefaults() *DAGResponse`

NewDAGResponseWithDefaults instantiates a new DAGResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDagId

`func (o *DAGResponse) GetDagId() string`

GetDagId returns the DagId field if non-nil, zero value otherwise.

### GetDagIdOk

`func (o *DAGResponse) GetDagIdOk() (*string, bool)`

GetDagIdOk returns a tuple with the DagId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDagId

`func (o *DAGResponse) SetDagId(v string)`

SetDagId sets DagId field to given value.


### GetDagDisplayName

`func (o *DAGResponse) GetDagDisplayName() string`

GetDagDisplayName returns the DagDisplayName field if non-nil, zero value otherwise.

### GetDagDisplayNameOk

`func (o *DAGResponse) GetDagDisplayNameOk() (*string, bool)`

GetDagDisplayNameOk returns a tuple with the DagDisplayName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDagDisplayName

`func (o *DAGResponse) SetDagDisplayName(v string)`

SetDagDisplayName sets DagDisplayName field to given value.


### GetIsPaused

`func (o *DAGResponse) GetIsPaused() bool`

GetIsPaused returns the IsPaused field if non-nil, zero value otherwise.

### GetIsPausedOk

`func (o *DAGResponse) GetIsPausedOk() (*bool, bool)`

GetIsPausedOk returns a tuple with the IsPaused field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsPaused

`func (o *DAGResponse) SetIsPaused(v bool)`

SetIsPaused sets IsPaused field to given value.


### GetIsStale

`func (o *DAGResponse) GetIsStale() bool`

GetIsStale returns the IsStale field if non-nil, zero value otherwise.

### GetIsStaleOk

`func (o *DAGResponse) GetIsStaleOk() (*bool, bool)`

GetIsStaleOk returns a tuple with the IsStale field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsStale

`func (o *DAGResponse) SetIsStale(v bool)`

SetIsStale sets IsStale field to given value.


### GetLastParsedTime

`func (o *DAGResponse) GetLastParsedTime() time.Time`

GetLastParsedTime returns the LastParsedTime field if non-nil, zero value otherwise.

### GetLastParsedTimeOk

`func (o *DAGResponse) GetLastParsedTimeOk() (*time.Time, bool)`

GetLastParsedTimeOk returns a tuple with the LastParsedTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastParsedTime

`func (o *DAGResponse) SetLastParsedTime(v time.Time)`

SetLastParsedTime sets LastParsedTime field to given value.


### SetLastParsedTimeNil

`func (o *DAGResponse) SetLastParsedTimeNil(b bool)`

 SetLastParsedTimeNil sets the value for LastParsedTime to be an explicit nil

### UnsetLastParsedTime
`func (o *DAGResponse) UnsetLastParsedTime()`

UnsetLastParsedTime ensures that no value is present for LastParsedTime, not even an explicit nil
### GetLastExpired

`func (o *DAGResponse) GetLastExpired() time.Time`

GetLastExpired returns the LastExpired field if non-nil, zero value otherwise.

### GetLastExpiredOk

`func (o *DAGResponse) GetLastExpiredOk() (*time.Time, bool)`

GetLastExpiredOk returns a tuple with the LastExpired field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastExpired

`func (o *DAGResponse) SetLastExpired(v time.Time)`

SetLastExpired sets LastExpired field to given value.


### SetLastExpiredNil

`func (o *DAGResponse) SetLastExpiredNil(b bool)`

 SetLastExpiredNil sets the value for LastExpired to be an explicit nil

### UnsetLastExpired
`func (o *DAGResponse) UnsetLastExpired()`

UnsetLastExpired ensures that no value is present for LastExpired, not even an explicit nil
### GetBundleName

`func (o *DAGResponse) GetBundleName() string`

GetBundleName returns the BundleName field if non-nil, zero value otherwise.

### GetBundleNameOk

`func (o *DAGResponse) GetBundleNameOk() (*string, bool)`

GetBundleNameOk returns a tuple with the BundleName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBundleName

`func (o *DAGResponse) SetBundleName(v string)`

SetBundleName sets BundleName field to given value.


### SetBundleNameNil

`func (o *DAGResponse) SetBundleNameNil(b bool)`

 SetBundleNameNil sets the value for BundleName to be an explicit nil

### UnsetBundleName
`func (o *DAGResponse) UnsetBundleName()`

UnsetBundleName ensures that no value is present for BundleName, not even an explicit nil
### GetBundleVersion

`func (o *DAGResponse) GetBundleVersion() string`

GetBundleVersion returns the BundleVersion field if non-nil, zero value otherwise.

### GetBundleVersionOk

`func (o *DAGResponse) GetBundleVersionOk() (*string, bool)`

GetBundleVersionOk returns a tuple with the BundleVersion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBundleVersion

`func (o *DAGResponse) SetBundleVersion(v string)`

SetBundleVersion sets BundleVersion field to given value.


### SetBundleVersionNil

`func (o *DAGResponse) SetBundleVersionNil(b bool)`

 SetBundleVersionNil sets the value for BundleVersion to be an explicit nil

### UnsetBundleVersion
`func (o *DAGResponse) UnsetBundleVersion()`

UnsetBundleVersion ensures that no value is present for BundleVersion, not even an explicit nil
### GetRelativeFileloc

`func (o *DAGResponse) GetRelativeFileloc() string`

GetRelativeFileloc returns the RelativeFileloc field if non-nil, zero value otherwise.

### GetRelativeFilelocOk

`func (o *DAGResponse) GetRelativeFilelocOk() (*string, bool)`

GetRelativeFilelocOk returns a tuple with the RelativeFileloc field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRelativeFileloc

`func (o *DAGResponse) SetRelativeFileloc(v string)`

SetRelativeFileloc sets RelativeFileloc field to given value.


### SetRelativeFilelocNil

`func (o *DAGResponse) SetRelativeFilelocNil(b bool)`

 SetRelativeFilelocNil sets the value for RelativeFileloc to be an explicit nil

### UnsetRelativeFileloc
`func (o *DAGResponse) UnsetRelativeFileloc()`

UnsetRelativeFileloc ensures that no value is present for RelativeFileloc, not even an explicit nil
### GetFileloc

`func (o *DAGResponse) GetFileloc() string`

GetFileloc returns the Fileloc field if non-nil, zero value otherwise.

### GetFilelocOk

`func (o *DAGResponse) GetFilelocOk() (*string, bool)`

GetFilelocOk returns a tuple with the Fileloc field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFileloc

`func (o *DAGResponse) SetFileloc(v string)`

SetFileloc sets Fileloc field to given value.


### GetDescription

`func (o *DAGResponse) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *DAGResponse) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *DAGResponse) SetDescription(v string)`

SetDescription sets Description field to given value.


### SetDescriptionNil

`func (o *DAGResponse) SetDescriptionNil(b bool)`

 SetDescriptionNil sets the value for Description to be an explicit nil

### UnsetDescription
`func (o *DAGResponse) UnsetDescription()`

UnsetDescription ensures that no value is present for Description, not even an explicit nil
### GetDeadline

`func (o *DAGResponse) GetDeadline() []DeadlineAlertResponse`

GetDeadline returns the Deadline field if non-nil, zero value otherwise.

### GetDeadlineOk

`func (o *DAGResponse) GetDeadlineOk() (*[]DeadlineAlertResponse, bool)`

GetDeadlineOk returns a tuple with the Deadline field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeadline

`func (o *DAGResponse) SetDeadline(v []DeadlineAlertResponse)`

SetDeadline sets Deadline field to given value.


### SetDeadlineNil

`func (o *DAGResponse) SetDeadlineNil(b bool)`

 SetDeadlineNil sets the value for Deadline to be an explicit nil

### UnsetDeadline
`func (o *DAGResponse) UnsetDeadline()`

UnsetDeadline ensures that no value is present for Deadline, not even an explicit nil
### GetTimetableSummary

`func (o *DAGResponse) GetTimetableSummary() string`

GetTimetableSummary returns the TimetableSummary field if non-nil, zero value otherwise.

### GetTimetableSummaryOk

`func (o *DAGResponse) GetTimetableSummaryOk() (*string, bool)`

GetTimetableSummaryOk returns a tuple with the TimetableSummary field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimetableSummary

`func (o *DAGResponse) SetTimetableSummary(v string)`

SetTimetableSummary sets TimetableSummary field to given value.


### SetTimetableSummaryNil

`func (o *DAGResponse) SetTimetableSummaryNil(b bool)`

 SetTimetableSummaryNil sets the value for TimetableSummary to be an explicit nil

### UnsetTimetableSummary
`func (o *DAGResponse) UnsetTimetableSummary()`

UnsetTimetableSummary ensures that no value is present for TimetableSummary, not even an explicit nil
### GetTimetableDescription

`func (o *DAGResponse) GetTimetableDescription() string`

GetTimetableDescription returns the TimetableDescription field if non-nil, zero value otherwise.

### GetTimetableDescriptionOk

`func (o *DAGResponse) GetTimetableDescriptionOk() (*string, bool)`

GetTimetableDescriptionOk returns a tuple with the TimetableDescription field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimetableDescription

`func (o *DAGResponse) SetTimetableDescription(v string)`

SetTimetableDescription sets TimetableDescription field to given value.


### SetTimetableDescriptionNil

`func (o *DAGResponse) SetTimetableDescriptionNil(b bool)`

 SetTimetableDescriptionNil sets the value for TimetableDescription to be an explicit nil

### UnsetTimetableDescription
`func (o *DAGResponse) UnsetTimetableDescription()`

UnsetTimetableDescription ensures that no value is present for TimetableDescription, not even an explicit nil
### GetTags

`func (o *DAGResponse) GetTags() []DagTagResponse`

GetTags returns the Tags field if non-nil, zero value otherwise.

### GetTagsOk

`func (o *DAGResponse) GetTagsOk() (*[]DagTagResponse, bool)`

GetTagsOk returns a tuple with the Tags field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTags

`func (o *DAGResponse) SetTags(v []DagTagResponse)`

SetTags sets Tags field to given value.


### GetMaxActiveTasks

`func (o *DAGResponse) GetMaxActiveTasks() int32`

GetMaxActiveTasks returns the MaxActiveTasks field if non-nil, zero value otherwise.

### GetMaxActiveTasksOk

`func (o *DAGResponse) GetMaxActiveTasksOk() (*int32, bool)`

GetMaxActiveTasksOk returns a tuple with the MaxActiveTasks field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxActiveTasks

`func (o *DAGResponse) SetMaxActiveTasks(v int32)`

SetMaxActiveTasks sets MaxActiveTasks field to given value.


### GetMaxActiveRuns

`func (o *DAGResponse) GetMaxActiveRuns() int32`

GetMaxActiveRuns returns the MaxActiveRuns field if non-nil, zero value otherwise.

### GetMaxActiveRunsOk

`func (o *DAGResponse) GetMaxActiveRunsOk() (*int32, bool)`

GetMaxActiveRunsOk returns a tuple with the MaxActiveRuns field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxActiveRuns

`func (o *DAGResponse) SetMaxActiveRuns(v int32)`

SetMaxActiveRuns sets MaxActiveRuns field to given value.


### SetMaxActiveRunsNil

`func (o *DAGResponse) SetMaxActiveRunsNil(b bool)`

 SetMaxActiveRunsNil sets the value for MaxActiveRuns to be an explicit nil

### UnsetMaxActiveRuns
`func (o *DAGResponse) UnsetMaxActiveRuns()`

UnsetMaxActiveRuns ensures that no value is present for MaxActiveRuns, not even an explicit nil
### GetMaxConsecutiveFailedDagRuns

`func (o *DAGResponse) GetMaxConsecutiveFailedDagRuns() int32`

GetMaxConsecutiveFailedDagRuns returns the MaxConsecutiveFailedDagRuns field if non-nil, zero value otherwise.

### GetMaxConsecutiveFailedDagRunsOk

`func (o *DAGResponse) GetMaxConsecutiveFailedDagRunsOk() (*int32, bool)`

GetMaxConsecutiveFailedDagRunsOk returns a tuple with the MaxConsecutiveFailedDagRuns field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxConsecutiveFailedDagRuns

`func (o *DAGResponse) SetMaxConsecutiveFailedDagRuns(v int32)`

SetMaxConsecutiveFailedDagRuns sets MaxConsecutiveFailedDagRuns field to given value.


### GetHasTaskConcurrencyLimits

`func (o *DAGResponse) GetHasTaskConcurrencyLimits() bool`

GetHasTaskConcurrencyLimits returns the HasTaskConcurrencyLimits field if non-nil, zero value otherwise.

### GetHasTaskConcurrencyLimitsOk

`func (o *DAGResponse) GetHasTaskConcurrencyLimitsOk() (*bool, bool)`

GetHasTaskConcurrencyLimitsOk returns a tuple with the HasTaskConcurrencyLimits field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHasTaskConcurrencyLimits

`func (o *DAGResponse) SetHasTaskConcurrencyLimits(v bool)`

SetHasTaskConcurrencyLimits sets HasTaskConcurrencyLimits field to given value.


### GetHasImportErrors

`func (o *DAGResponse) GetHasImportErrors() bool`

GetHasImportErrors returns the HasImportErrors field if non-nil, zero value otherwise.

### GetHasImportErrorsOk

`func (o *DAGResponse) GetHasImportErrorsOk() (*bool, bool)`

GetHasImportErrorsOk returns a tuple with the HasImportErrors field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHasImportErrors

`func (o *DAGResponse) SetHasImportErrors(v bool)`

SetHasImportErrors sets HasImportErrors field to given value.


### GetNextDagrunLogicalDate

`func (o *DAGResponse) GetNextDagrunLogicalDate() time.Time`

GetNextDagrunLogicalDate returns the NextDagrunLogicalDate field if non-nil, zero value otherwise.

### GetNextDagrunLogicalDateOk

`func (o *DAGResponse) GetNextDagrunLogicalDateOk() (*time.Time, bool)`

GetNextDagrunLogicalDateOk returns a tuple with the NextDagrunLogicalDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNextDagrunLogicalDate

`func (o *DAGResponse) SetNextDagrunLogicalDate(v time.Time)`

SetNextDagrunLogicalDate sets NextDagrunLogicalDate field to given value.


### SetNextDagrunLogicalDateNil

`func (o *DAGResponse) SetNextDagrunLogicalDateNil(b bool)`

 SetNextDagrunLogicalDateNil sets the value for NextDagrunLogicalDate to be an explicit nil

### UnsetNextDagrunLogicalDate
`func (o *DAGResponse) UnsetNextDagrunLogicalDate()`

UnsetNextDagrunLogicalDate ensures that no value is present for NextDagrunLogicalDate, not even an explicit nil
### GetNextDagrunDataIntervalStart

`func (o *DAGResponse) GetNextDagrunDataIntervalStart() time.Time`

GetNextDagrunDataIntervalStart returns the NextDagrunDataIntervalStart field if non-nil, zero value otherwise.

### GetNextDagrunDataIntervalStartOk

`func (o *DAGResponse) GetNextDagrunDataIntervalStartOk() (*time.Time, bool)`

GetNextDagrunDataIntervalStartOk returns a tuple with the NextDagrunDataIntervalStart field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNextDagrunDataIntervalStart

`func (o *DAGResponse) SetNextDagrunDataIntervalStart(v time.Time)`

SetNextDagrunDataIntervalStart sets NextDagrunDataIntervalStart field to given value.


### SetNextDagrunDataIntervalStartNil

`func (o *DAGResponse) SetNextDagrunDataIntervalStartNil(b bool)`

 SetNextDagrunDataIntervalStartNil sets the value for NextDagrunDataIntervalStart to be an explicit nil

### UnsetNextDagrunDataIntervalStart
`func (o *DAGResponse) UnsetNextDagrunDataIntervalStart()`

UnsetNextDagrunDataIntervalStart ensures that no value is present for NextDagrunDataIntervalStart, not even an explicit nil
### GetNextDagrunDataIntervalEnd

`func (o *DAGResponse) GetNextDagrunDataIntervalEnd() time.Time`

GetNextDagrunDataIntervalEnd returns the NextDagrunDataIntervalEnd field if non-nil, zero value otherwise.

### GetNextDagrunDataIntervalEndOk

`func (o *DAGResponse) GetNextDagrunDataIntervalEndOk() (*time.Time, bool)`

GetNextDagrunDataIntervalEndOk returns a tuple with the NextDagrunDataIntervalEnd field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNextDagrunDataIntervalEnd

`func (o *DAGResponse) SetNextDagrunDataIntervalEnd(v time.Time)`

SetNextDagrunDataIntervalEnd sets NextDagrunDataIntervalEnd field to given value.


### SetNextDagrunDataIntervalEndNil

`func (o *DAGResponse) SetNextDagrunDataIntervalEndNil(b bool)`

 SetNextDagrunDataIntervalEndNil sets the value for NextDagrunDataIntervalEnd to be an explicit nil

### UnsetNextDagrunDataIntervalEnd
`func (o *DAGResponse) UnsetNextDagrunDataIntervalEnd()`

UnsetNextDagrunDataIntervalEnd ensures that no value is present for NextDagrunDataIntervalEnd, not even an explicit nil
### GetNextDagrunRunAfter

`func (o *DAGResponse) GetNextDagrunRunAfter() time.Time`

GetNextDagrunRunAfter returns the NextDagrunRunAfter field if non-nil, zero value otherwise.

### GetNextDagrunRunAfterOk

`func (o *DAGResponse) GetNextDagrunRunAfterOk() (*time.Time, bool)`

GetNextDagrunRunAfterOk returns a tuple with the NextDagrunRunAfter field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNextDagrunRunAfter

`func (o *DAGResponse) SetNextDagrunRunAfter(v time.Time)`

SetNextDagrunRunAfter sets NextDagrunRunAfter field to given value.


### SetNextDagrunRunAfterNil

`func (o *DAGResponse) SetNextDagrunRunAfterNil(b bool)`

 SetNextDagrunRunAfterNil sets the value for NextDagrunRunAfter to be an explicit nil

### UnsetNextDagrunRunAfter
`func (o *DAGResponse) UnsetNextDagrunRunAfter()`

UnsetNextDagrunRunAfter ensures that no value is present for NextDagrunRunAfter, not even an explicit nil
### GetOwners

`func (o *DAGResponse) GetOwners() []string`

GetOwners returns the Owners field if non-nil, zero value otherwise.

### GetOwnersOk

`func (o *DAGResponse) GetOwnersOk() (*[]string, bool)`

GetOwnersOk returns a tuple with the Owners field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOwners

`func (o *DAGResponse) SetOwners(v []string)`

SetOwners sets Owners field to given value.


### GetFileToken

`func (o *DAGResponse) GetFileToken() string`

GetFileToken returns the FileToken field if non-nil, zero value otherwise.

### GetFileTokenOk

`func (o *DAGResponse) GetFileTokenOk() (*string, bool)`

GetFileTokenOk returns a tuple with the FileToken field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFileToken

`func (o *DAGResponse) SetFileToken(v string)`

SetFileToken sets FileToken field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


