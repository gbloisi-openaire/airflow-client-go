# DAGDetailsResponse

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
**Catchup** | **bool** |  | 
**DagRunTimeout** | **NullableString** |  | 
**AssetExpression** | **map[string]interface{}** |  | 
**DocMd** | **NullableString** |  | 
**StartDate** | **NullableTime** |  | 
**EndDate** | **NullableTime** |  | 
**IsPausedUponCreation** | **NullableBool** |  | 
**Params** | **map[string]interface{}** |  | 
**RenderTemplateAsNativeObj** | **bool** |  | 
**TemplateSearchPath** | **[]string** |  | 
**Timezone** | **NullableString** |  | 
**LastParsed** | **NullableTime** |  | 
**DefaultArgs** | **map[string]interface{}** |  | 
**OwnerLinks** | Pointer to **map[string]string** |  | [optional] 
**FileToken** | **string** | Return file token. | [readonly] 
**Concurrency** | **int32** | Return max_active_tasks as concurrency. | [readonly] 
**LatestDagVersion** | [**NullableDagVersionResponse**](DagVersionResponse.md) |  | 

## Methods

### NewDAGDetailsResponse

`func NewDAGDetailsResponse(dagId string, dagDisplayName string, isPaused bool, isStale bool, lastParsedTime NullableTime, lastExpired NullableTime, bundleName NullableString, bundleVersion NullableString, relativeFileloc NullableString, fileloc string, description NullableString, deadline []DeadlineAlertResponse, timetableSummary NullableString, timetableDescription NullableString, tags []DagTagResponse, maxActiveTasks int32, maxActiveRuns NullableInt32, maxConsecutiveFailedDagRuns int32, hasTaskConcurrencyLimits bool, hasImportErrors bool, nextDagrunLogicalDate NullableTime, nextDagrunDataIntervalStart NullableTime, nextDagrunDataIntervalEnd NullableTime, nextDagrunRunAfter NullableTime, owners []string, catchup bool, dagRunTimeout NullableString, assetExpression map[string]interface{}, docMd NullableString, startDate NullableTime, endDate NullableTime, isPausedUponCreation NullableBool, params map[string]interface{}, renderTemplateAsNativeObj bool, templateSearchPath []string, timezone NullableString, lastParsed NullableTime, defaultArgs map[string]interface{}, fileToken string, concurrency int32, latestDagVersion NullableDagVersionResponse, ) *DAGDetailsResponse`

NewDAGDetailsResponse instantiates a new DAGDetailsResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDAGDetailsResponseWithDefaults

`func NewDAGDetailsResponseWithDefaults() *DAGDetailsResponse`

NewDAGDetailsResponseWithDefaults instantiates a new DAGDetailsResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDagId

`func (o *DAGDetailsResponse) GetDagId() string`

GetDagId returns the DagId field if non-nil, zero value otherwise.

### GetDagIdOk

`func (o *DAGDetailsResponse) GetDagIdOk() (*string, bool)`

GetDagIdOk returns a tuple with the DagId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDagId

`func (o *DAGDetailsResponse) SetDagId(v string)`

SetDagId sets DagId field to given value.


### GetDagDisplayName

`func (o *DAGDetailsResponse) GetDagDisplayName() string`

GetDagDisplayName returns the DagDisplayName field if non-nil, zero value otherwise.

### GetDagDisplayNameOk

`func (o *DAGDetailsResponse) GetDagDisplayNameOk() (*string, bool)`

GetDagDisplayNameOk returns a tuple with the DagDisplayName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDagDisplayName

`func (o *DAGDetailsResponse) SetDagDisplayName(v string)`

SetDagDisplayName sets DagDisplayName field to given value.


### GetIsPaused

`func (o *DAGDetailsResponse) GetIsPaused() bool`

GetIsPaused returns the IsPaused field if non-nil, zero value otherwise.

### GetIsPausedOk

`func (o *DAGDetailsResponse) GetIsPausedOk() (*bool, bool)`

GetIsPausedOk returns a tuple with the IsPaused field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsPaused

`func (o *DAGDetailsResponse) SetIsPaused(v bool)`

SetIsPaused sets IsPaused field to given value.


### GetIsStale

`func (o *DAGDetailsResponse) GetIsStale() bool`

GetIsStale returns the IsStale field if non-nil, zero value otherwise.

### GetIsStaleOk

`func (o *DAGDetailsResponse) GetIsStaleOk() (*bool, bool)`

GetIsStaleOk returns a tuple with the IsStale field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsStale

`func (o *DAGDetailsResponse) SetIsStale(v bool)`

SetIsStale sets IsStale field to given value.


### GetLastParsedTime

`func (o *DAGDetailsResponse) GetLastParsedTime() time.Time`

GetLastParsedTime returns the LastParsedTime field if non-nil, zero value otherwise.

### GetLastParsedTimeOk

`func (o *DAGDetailsResponse) GetLastParsedTimeOk() (*time.Time, bool)`

GetLastParsedTimeOk returns a tuple with the LastParsedTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastParsedTime

`func (o *DAGDetailsResponse) SetLastParsedTime(v time.Time)`

SetLastParsedTime sets LastParsedTime field to given value.


### SetLastParsedTimeNil

`func (o *DAGDetailsResponse) SetLastParsedTimeNil(b bool)`

 SetLastParsedTimeNil sets the value for LastParsedTime to be an explicit nil

### UnsetLastParsedTime
`func (o *DAGDetailsResponse) UnsetLastParsedTime()`

UnsetLastParsedTime ensures that no value is present for LastParsedTime, not even an explicit nil
### GetLastExpired

`func (o *DAGDetailsResponse) GetLastExpired() time.Time`

GetLastExpired returns the LastExpired field if non-nil, zero value otherwise.

### GetLastExpiredOk

`func (o *DAGDetailsResponse) GetLastExpiredOk() (*time.Time, bool)`

GetLastExpiredOk returns a tuple with the LastExpired field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastExpired

`func (o *DAGDetailsResponse) SetLastExpired(v time.Time)`

SetLastExpired sets LastExpired field to given value.


### SetLastExpiredNil

`func (o *DAGDetailsResponse) SetLastExpiredNil(b bool)`

 SetLastExpiredNil sets the value for LastExpired to be an explicit nil

### UnsetLastExpired
`func (o *DAGDetailsResponse) UnsetLastExpired()`

UnsetLastExpired ensures that no value is present for LastExpired, not even an explicit nil
### GetBundleName

`func (o *DAGDetailsResponse) GetBundleName() string`

GetBundleName returns the BundleName field if non-nil, zero value otherwise.

### GetBundleNameOk

`func (o *DAGDetailsResponse) GetBundleNameOk() (*string, bool)`

GetBundleNameOk returns a tuple with the BundleName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBundleName

`func (o *DAGDetailsResponse) SetBundleName(v string)`

SetBundleName sets BundleName field to given value.


### SetBundleNameNil

`func (o *DAGDetailsResponse) SetBundleNameNil(b bool)`

 SetBundleNameNil sets the value for BundleName to be an explicit nil

### UnsetBundleName
`func (o *DAGDetailsResponse) UnsetBundleName()`

UnsetBundleName ensures that no value is present for BundleName, not even an explicit nil
### GetBundleVersion

`func (o *DAGDetailsResponse) GetBundleVersion() string`

GetBundleVersion returns the BundleVersion field if non-nil, zero value otherwise.

### GetBundleVersionOk

`func (o *DAGDetailsResponse) GetBundleVersionOk() (*string, bool)`

GetBundleVersionOk returns a tuple with the BundleVersion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBundleVersion

`func (o *DAGDetailsResponse) SetBundleVersion(v string)`

SetBundleVersion sets BundleVersion field to given value.


### SetBundleVersionNil

`func (o *DAGDetailsResponse) SetBundleVersionNil(b bool)`

 SetBundleVersionNil sets the value for BundleVersion to be an explicit nil

### UnsetBundleVersion
`func (o *DAGDetailsResponse) UnsetBundleVersion()`

UnsetBundleVersion ensures that no value is present for BundleVersion, not even an explicit nil
### GetRelativeFileloc

`func (o *DAGDetailsResponse) GetRelativeFileloc() string`

GetRelativeFileloc returns the RelativeFileloc field if non-nil, zero value otherwise.

### GetRelativeFilelocOk

`func (o *DAGDetailsResponse) GetRelativeFilelocOk() (*string, bool)`

GetRelativeFilelocOk returns a tuple with the RelativeFileloc field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRelativeFileloc

`func (o *DAGDetailsResponse) SetRelativeFileloc(v string)`

SetRelativeFileloc sets RelativeFileloc field to given value.


### SetRelativeFilelocNil

`func (o *DAGDetailsResponse) SetRelativeFilelocNil(b bool)`

 SetRelativeFilelocNil sets the value for RelativeFileloc to be an explicit nil

### UnsetRelativeFileloc
`func (o *DAGDetailsResponse) UnsetRelativeFileloc()`

UnsetRelativeFileloc ensures that no value is present for RelativeFileloc, not even an explicit nil
### GetFileloc

`func (o *DAGDetailsResponse) GetFileloc() string`

GetFileloc returns the Fileloc field if non-nil, zero value otherwise.

### GetFilelocOk

`func (o *DAGDetailsResponse) GetFilelocOk() (*string, bool)`

GetFilelocOk returns a tuple with the Fileloc field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFileloc

`func (o *DAGDetailsResponse) SetFileloc(v string)`

SetFileloc sets Fileloc field to given value.


### GetDescription

`func (o *DAGDetailsResponse) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *DAGDetailsResponse) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *DAGDetailsResponse) SetDescription(v string)`

SetDescription sets Description field to given value.


### SetDescriptionNil

`func (o *DAGDetailsResponse) SetDescriptionNil(b bool)`

 SetDescriptionNil sets the value for Description to be an explicit nil

### UnsetDescription
`func (o *DAGDetailsResponse) UnsetDescription()`

UnsetDescription ensures that no value is present for Description, not even an explicit nil
### GetDeadline

`func (o *DAGDetailsResponse) GetDeadline() []DeadlineAlertResponse`

GetDeadline returns the Deadline field if non-nil, zero value otherwise.

### GetDeadlineOk

`func (o *DAGDetailsResponse) GetDeadlineOk() (*[]DeadlineAlertResponse, bool)`

GetDeadlineOk returns a tuple with the Deadline field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeadline

`func (o *DAGDetailsResponse) SetDeadline(v []DeadlineAlertResponse)`

SetDeadline sets Deadline field to given value.


### SetDeadlineNil

`func (o *DAGDetailsResponse) SetDeadlineNil(b bool)`

 SetDeadlineNil sets the value for Deadline to be an explicit nil

### UnsetDeadline
`func (o *DAGDetailsResponse) UnsetDeadline()`

UnsetDeadline ensures that no value is present for Deadline, not even an explicit nil
### GetTimetableSummary

`func (o *DAGDetailsResponse) GetTimetableSummary() string`

GetTimetableSummary returns the TimetableSummary field if non-nil, zero value otherwise.

### GetTimetableSummaryOk

`func (o *DAGDetailsResponse) GetTimetableSummaryOk() (*string, bool)`

GetTimetableSummaryOk returns a tuple with the TimetableSummary field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimetableSummary

`func (o *DAGDetailsResponse) SetTimetableSummary(v string)`

SetTimetableSummary sets TimetableSummary field to given value.


### SetTimetableSummaryNil

`func (o *DAGDetailsResponse) SetTimetableSummaryNil(b bool)`

 SetTimetableSummaryNil sets the value for TimetableSummary to be an explicit nil

### UnsetTimetableSummary
`func (o *DAGDetailsResponse) UnsetTimetableSummary()`

UnsetTimetableSummary ensures that no value is present for TimetableSummary, not even an explicit nil
### GetTimetableDescription

`func (o *DAGDetailsResponse) GetTimetableDescription() string`

GetTimetableDescription returns the TimetableDescription field if non-nil, zero value otherwise.

### GetTimetableDescriptionOk

`func (o *DAGDetailsResponse) GetTimetableDescriptionOk() (*string, bool)`

GetTimetableDescriptionOk returns a tuple with the TimetableDescription field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimetableDescription

`func (o *DAGDetailsResponse) SetTimetableDescription(v string)`

SetTimetableDescription sets TimetableDescription field to given value.


### SetTimetableDescriptionNil

`func (o *DAGDetailsResponse) SetTimetableDescriptionNil(b bool)`

 SetTimetableDescriptionNil sets the value for TimetableDescription to be an explicit nil

### UnsetTimetableDescription
`func (o *DAGDetailsResponse) UnsetTimetableDescription()`

UnsetTimetableDescription ensures that no value is present for TimetableDescription, not even an explicit nil
### GetTags

`func (o *DAGDetailsResponse) GetTags() []DagTagResponse`

GetTags returns the Tags field if non-nil, zero value otherwise.

### GetTagsOk

`func (o *DAGDetailsResponse) GetTagsOk() (*[]DagTagResponse, bool)`

GetTagsOk returns a tuple with the Tags field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTags

`func (o *DAGDetailsResponse) SetTags(v []DagTagResponse)`

SetTags sets Tags field to given value.


### GetMaxActiveTasks

`func (o *DAGDetailsResponse) GetMaxActiveTasks() int32`

GetMaxActiveTasks returns the MaxActiveTasks field if non-nil, zero value otherwise.

### GetMaxActiveTasksOk

`func (o *DAGDetailsResponse) GetMaxActiveTasksOk() (*int32, bool)`

GetMaxActiveTasksOk returns a tuple with the MaxActiveTasks field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxActiveTasks

`func (o *DAGDetailsResponse) SetMaxActiveTasks(v int32)`

SetMaxActiveTasks sets MaxActiveTasks field to given value.


### GetMaxActiveRuns

`func (o *DAGDetailsResponse) GetMaxActiveRuns() int32`

GetMaxActiveRuns returns the MaxActiveRuns field if non-nil, zero value otherwise.

### GetMaxActiveRunsOk

`func (o *DAGDetailsResponse) GetMaxActiveRunsOk() (*int32, bool)`

GetMaxActiveRunsOk returns a tuple with the MaxActiveRuns field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxActiveRuns

`func (o *DAGDetailsResponse) SetMaxActiveRuns(v int32)`

SetMaxActiveRuns sets MaxActiveRuns field to given value.


### SetMaxActiveRunsNil

`func (o *DAGDetailsResponse) SetMaxActiveRunsNil(b bool)`

 SetMaxActiveRunsNil sets the value for MaxActiveRuns to be an explicit nil

### UnsetMaxActiveRuns
`func (o *DAGDetailsResponse) UnsetMaxActiveRuns()`

UnsetMaxActiveRuns ensures that no value is present for MaxActiveRuns, not even an explicit nil
### GetMaxConsecutiveFailedDagRuns

`func (o *DAGDetailsResponse) GetMaxConsecutiveFailedDagRuns() int32`

GetMaxConsecutiveFailedDagRuns returns the MaxConsecutiveFailedDagRuns field if non-nil, zero value otherwise.

### GetMaxConsecutiveFailedDagRunsOk

`func (o *DAGDetailsResponse) GetMaxConsecutiveFailedDagRunsOk() (*int32, bool)`

GetMaxConsecutiveFailedDagRunsOk returns a tuple with the MaxConsecutiveFailedDagRuns field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxConsecutiveFailedDagRuns

`func (o *DAGDetailsResponse) SetMaxConsecutiveFailedDagRuns(v int32)`

SetMaxConsecutiveFailedDagRuns sets MaxConsecutiveFailedDagRuns field to given value.


### GetHasTaskConcurrencyLimits

`func (o *DAGDetailsResponse) GetHasTaskConcurrencyLimits() bool`

GetHasTaskConcurrencyLimits returns the HasTaskConcurrencyLimits field if non-nil, zero value otherwise.

### GetHasTaskConcurrencyLimitsOk

`func (o *DAGDetailsResponse) GetHasTaskConcurrencyLimitsOk() (*bool, bool)`

GetHasTaskConcurrencyLimitsOk returns a tuple with the HasTaskConcurrencyLimits field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHasTaskConcurrencyLimits

`func (o *DAGDetailsResponse) SetHasTaskConcurrencyLimits(v bool)`

SetHasTaskConcurrencyLimits sets HasTaskConcurrencyLimits field to given value.


### GetHasImportErrors

`func (o *DAGDetailsResponse) GetHasImportErrors() bool`

GetHasImportErrors returns the HasImportErrors field if non-nil, zero value otherwise.

### GetHasImportErrorsOk

`func (o *DAGDetailsResponse) GetHasImportErrorsOk() (*bool, bool)`

GetHasImportErrorsOk returns a tuple with the HasImportErrors field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHasImportErrors

`func (o *DAGDetailsResponse) SetHasImportErrors(v bool)`

SetHasImportErrors sets HasImportErrors field to given value.


### GetNextDagrunLogicalDate

`func (o *DAGDetailsResponse) GetNextDagrunLogicalDate() time.Time`

GetNextDagrunLogicalDate returns the NextDagrunLogicalDate field if non-nil, zero value otherwise.

### GetNextDagrunLogicalDateOk

`func (o *DAGDetailsResponse) GetNextDagrunLogicalDateOk() (*time.Time, bool)`

GetNextDagrunLogicalDateOk returns a tuple with the NextDagrunLogicalDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNextDagrunLogicalDate

`func (o *DAGDetailsResponse) SetNextDagrunLogicalDate(v time.Time)`

SetNextDagrunLogicalDate sets NextDagrunLogicalDate field to given value.


### SetNextDagrunLogicalDateNil

`func (o *DAGDetailsResponse) SetNextDagrunLogicalDateNil(b bool)`

 SetNextDagrunLogicalDateNil sets the value for NextDagrunLogicalDate to be an explicit nil

### UnsetNextDagrunLogicalDate
`func (o *DAGDetailsResponse) UnsetNextDagrunLogicalDate()`

UnsetNextDagrunLogicalDate ensures that no value is present for NextDagrunLogicalDate, not even an explicit nil
### GetNextDagrunDataIntervalStart

`func (o *DAGDetailsResponse) GetNextDagrunDataIntervalStart() time.Time`

GetNextDagrunDataIntervalStart returns the NextDagrunDataIntervalStart field if non-nil, zero value otherwise.

### GetNextDagrunDataIntervalStartOk

`func (o *DAGDetailsResponse) GetNextDagrunDataIntervalStartOk() (*time.Time, bool)`

GetNextDagrunDataIntervalStartOk returns a tuple with the NextDagrunDataIntervalStart field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNextDagrunDataIntervalStart

`func (o *DAGDetailsResponse) SetNextDagrunDataIntervalStart(v time.Time)`

SetNextDagrunDataIntervalStart sets NextDagrunDataIntervalStart field to given value.


### SetNextDagrunDataIntervalStartNil

`func (o *DAGDetailsResponse) SetNextDagrunDataIntervalStartNil(b bool)`

 SetNextDagrunDataIntervalStartNil sets the value for NextDagrunDataIntervalStart to be an explicit nil

### UnsetNextDagrunDataIntervalStart
`func (o *DAGDetailsResponse) UnsetNextDagrunDataIntervalStart()`

UnsetNextDagrunDataIntervalStart ensures that no value is present for NextDagrunDataIntervalStart, not even an explicit nil
### GetNextDagrunDataIntervalEnd

`func (o *DAGDetailsResponse) GetNextDagrunDataIntervalEnd() time.Time`

GetNextDagrunDataIntervalEnd returns the NextDagrunDataIntervalEnd field if non-nil, zero value otherwise.

### GetNextDagrunDataIntervalEndOk

`func (o *DAGDetailsResponse) GetNextDagrunDataIntervalEndOk() (*time.Time, bool)`

GetNextDagrunDataIntervalEndOk returns a tuple with the NextDagrunDataIntervalEnd field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNextDagrunDataIntervalEnd

`func (o *DAGDetailsResponse) SetNextDagrunDataIntervalEnd(v time.Time)`

SetNextDagrunDataIntervalEnd sets NextDagrunDataIntervalEnd field to given value.


### SetNextDagrunDataIntervalEndNil

`func (o *DAGDetailsResponse) SetNextDagrunDataIntervalEndNil(b bool)`

 SetNextDagrunDataIntervalEndNil sets the value for NextDagrunDataIntervalEnd to be an explicit nil

### UnsetNextDagrunDataIntervalEnd
`func (o *DAGDetailsResponse) UnsetNextDagrunDataIntervalEnd()`

UnsetNextDagrunDataIntervalEnd ensures that no value is present for NextDagrunDataIntervalEnd, not even an explicit nil
### GetNextDagrunRunAfter

`func (o *DAGDetailsResponse) GetNextDagrunRunAfter() time.Time`

GetNextDagrunRunAfter returns the NextDagrunRunAfter field if non-nil, zero value otherwise.

### GetNextDagrunRunAfterOk

`func (o *DAGDetailsResponse) GetNextDagrunRunAfterOk() (*time.Time, bool)`

GetNextDagrunRunAfterOk returns a tuple with the NextDagrunRunAfter field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNextDagrunRunAfter

`func (o *DAGDetailsResponse) SetNextDagrunRunAfter(v time.Time)`

SetNextDagrunRunAfter sets NextDagrunRunAfter field to given value.


### SetNextDagrunRunAfterNil

`func (o *DAGDetailsResponse) SetNextDagrunRunAfterNil(b bool)`

 SetNextDagrunRunAfterNil sets the value for NextDagrunRunAfter to be an explicit nil

### UnsetNextDagrunRunAfter
`func (o *DAGDetailsResponse) UnsetNextDagrunRunAfter()`

UnsetNextDagrunRunAfter ensures that no value is present for NextDagrunRunAfter, not even an explicit nil
### GetOwners

`func (o *DAGDetailsResponse) GetOwners() []string`

GetOwners returns the Owners field if non-nil, zero value otherwise.

### GetOwnersOk

`func (o *DAGDetailsResponse) GetOwnersOk() (*[]string, bool)`

GetOwnersOk returns a tuple with the Owners field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOwners

`func (o *DAGDetailsResponse) SetOwners(v []string)`

SetOwners sets Owners field to given value.


### GetCatchup

`func (o *DAGDetailsResponse) GetCatchup() bool`

GetCatchup returns the Catchup field if non-nil, zero value otherwise.

### GetCatchupOk

`func (o *DAGDetailsResponse) GetCatchupOk() (*bool, bool)`

GetCatchupOk returns a tuple with the Catchup field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCatchup

`func (o *DAGDetailsResponse) SetCatchup(v bool)`

SetCatchup sets Catchup field to given value.


### GetDagRunTimeout

`func (o *DAGDetailsResponse) GetDagRunTimeout() string`

GetDagRunTimeout returns the DagRunTimeout field if non-nil, zero value otherwise.

### GetDagRunTimeoutOk

`func (o *DAGDetailsResponse) GetDagRunTimeoutOk() (*string, bool)`

GetDagRunTimeoutOk returns a tuple with the DagRunTimeout field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDagRunTimeout

`func (o *DAGDetailsResponse) SetDagRunTimeout(v string)`

SetDagRunTimeout sets DagRunTimeout field to given value.


### SetDagRunTimeoutNil

`func (o *DAGDetailsResponse) SetDagRunTimeoutNil(b bool)`

 SetDagRunTimeoutNil sets the value for DagRunTimeout to be an explicit nil

### UnsetDagRunTimeout
`func (o *DAGDetailsResponse) UnsetDagRunTimeout()`

UnsetDagRunTimeout ensures that no value is present for DagRunTimeout, not even an explicit nil
### GetAssetExpression

`func (o *DAGDetailsResponse) GetAssetExpression() map[string]interface{}`

GetAssetExpression returns the AssetExpression field if non-nil, zero value otherwise.

### GetAssetExpressionOk

`func (o *DAGDetailsResponse) GetAssetExpressionOk() (*map[string]interface{}, bool)`

GetAssetExpressionOk returns a tuple with the AssetExpression field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssetExpression

`func (o *DAGDetailsResponse) SetAssetExpression(v map[string]interface{})`

SetAssetExpression sets AssetExpression field to given value.


### SetAssetExpressionNil

`func (o *DAGDetailsResponse) SetAssetExpressionNil(b bool)`

 SetAssetExpressionNil sets the value for AssetExpression to be an explicit nil

### UnsetAssetExpression
`func (o *DAGDetailsResponse) UnsetAssetExpression()`

UnsetAssetExpression ensures that no value is present for AssetExpression, not even an explicit nil
### GetDocMd

`func (o *DAGDetailsResponse) GetDocMd() string`

GetDocMd returns the DocMd field if non-nil, zero value otherwise.

### GetDocMdOk

`func (o *DAGDetailsResponse) GetDocMdOk() (*string, bool)`

GetDocMdOk returns a tuple with the DocMd field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDocMd

`func (o *DAGDetailsResponse) SetDocMd(v string)`

SetDocMd sets DocMd field to given value.


### SetDocMdNil

`func (o *DAGDetailsResponse) SetDocMdNil(b bool)`

 SetDocMdNil sets the value for DocMd to be an explicit nil

### UnsetDocMd
`func (o *DAGDetailsResponse) UnsetDocMd()`

UnsetDocMd ensures that no value is present for DocMd, not even an explicit nil
### GetStartDate

`func (o *DAGDetailsResponse) GetStartDate() time.Time`

GetStartDate returns the StartDate field if non-nil, zero value otherwise.

### GetStartDateOk

`func (o *DAGDetailsResponse) GetStartDateOk() (*time.Time, bool)`

GetStartDateOk returns a tuple with the StartDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartDate

`func (o *DAGDetailsResponse) SetStartDate(v time.Time)`

SetStartDate sets StartDate field to given value.


### SetStartDateNil

`func (o *DAGDetailsResponse) SetStartDateNil(b bool)`

 SetStartDateNil sets the value for StartDate to be an explicit nil

### UnsetStartDate
`func (o *DAGDetailsResponse) UnsetStartDate()`

UnsetStartDate ensures that no value is present for StartDate, not even an explicit nil
### GetEndDate

`func (o *DAGDetailsResponse) GetEndDate() time.Time`

GetEndDate returns the EndDate field if non-nil, zero value otherwise.

### GetEndDateOk

`func (o *DAGDetailsResponse) GetEndDateOk() (*time.Time, bool)`

GetEndDateOk returns a tuple with the EndDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEndDate

`func (o *DAGDetailsResponse) SetEndDate(v time.Time)`

SetEndDate sets EndDate field to given value.


### SetEndDateNil

`func (o *DAGDetailsResponse) SetEndDateNil(b bool)`

 SetEndDateNil sets the value for EndDate to be an explicit nil

### UnsetEndDate
`func (o *DAGDetailsResponse) UnsetEndDate()`

UnsetEndDate ensures that no value is present for EndDate, not even an explicit nil
### GetIsPausedUponCreation

`func (o *DAGDetailsResponse) GetIsPausedUponCreation() bool`

GetIsPausedUponCreation returns the IsPausedUponCreation field if non-nil, zero value otherwise.

### GetIsPausedUponCreationOk

`func (o *DAGDetailsResponse) GetIsPausedUponCreationOk() (*bool, bool)`

GetIsPausedUponCreationOk returns a tuple with the IsPausedUponCreation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsPausedUponCreation

`func (o *DAGDetailsResponse) SetIsPausedUponCreation(v bool)`

SetIsPausedUponCreation sets IsPausedUponCreation field to given value.


### SetIsPausedUponCreationNil

`func (o *DAGDetailsResponse) SetIsPausedUponCreationNil(b bool)`

 SetIsPausedUponCreationNil sets the value for IsPausedUponCreation to be an explicit nil

### UnsetIsPausedUponCreation
`func (o *DAGDetailsResponse) UnsetIsPausedUponCreation()`

UnsetIsPausedUponCreation ensures that no value is present for IsPausedUponCreation, not even an explicit nil
### GetParams

`func (o *DAGDetailsResponse) GetParams() map[string]interface{}`

GetParams returns the Params field if non-nil, zero value otherwise.

### GetParamsOk

`func (o *DAGDetailsResponse) GetParamsOk() (*map[string]interface{}, bool)`

GetParamsOk returns a tuple with the Params field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParams

`func (o *DAGDetailsResponse) SetParams(v map[string]interface{})`

SetParams sets Params field to given value.


### SetParamsNil

`func (o *DAGDetailsResponse) SetParamsNil(b bool)`

 SetParamsNil sets the value for Params to be an explicit nil

### UnsetParams
`func (o *DAGDetailsResponse) UnsetParams()`

UnsetParams ensures that no value is present for Params, not even an explicit nil
### GetRenderTemplateAsNativeObj

`func (o *DAGDetailsResponse) GetRenderTemplateAsNativeObj() bool`

GetRenderTemplateAsNativeObj returns the RenderTemplateAsNativeObj field if non-nil, zero value otherwise.

### GetRenderTemplateAsNativeObjOk

`func (o *DAGDetailsResponse) GetRenderTemplateAsNativeObjOk() (*bool, bool)`

GetRenderTemplateAsNativeObjOk returns a tuple with the RenderTemplateAsNativeObj field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRenderTemplateAsNativeObj

`func (o *DAGDetailsResponse) SetRenderTemplateAsNativeObj(v bool)`

SetRenderTemplateAsNativeObj sets RenderTemplateAsNativeObj field to given value.


### GetTemplateSearchPath

`func (o *DAGDetailsResponse) GetTemplateSearchPath() []string`

GetTemplateSearchPath returns the TemplateSearchPath field if non-nil, zero value otherwise.

### GetTemplateSearchPathOk

`func (o *DAGDetailsResponse) GetTemplateSearchPathOk() (*[]string, bool)`

GetTemplateSearchPathOk returns a tuple with the TemplateSearchPath field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTemplateSearchPath

`func (o *DAGDetailsResponse) SetTemplateSearchPath(v []string)`

SetTemplateSearchPath sets TemplateSearchPath field to given value.


### SetTemplateSearchPathNil

`func (o *DAGDetailsResponse) SetTemplateSearchPathNil(b bool)`

 SetTemplateSearchPathNil sets the value for TemplateSearchPath to be an explicit nil

### UnsetTemplateSearchPath
`func (o *DAGDetailsResponse) UnsetTemplateSearchPath()`

UnsetTemplateSearchPath ensures that no value is present for TemplateSearchPath, not even an explicit nil
### GetTimezone

`func (o *DAGDetailsResponse) GetTimezone() string`

GetTimezone returns the Timezone field if non-nil, zero value otherwise.

### GetTimezoneOk

`func (o *DAGDetailsResponse) GetTimezoneOk() (*string, bool)`

GetTimezoneOk returns a tuple with the Timezone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimezone

`func (o *DAGDetailsResponse) SetTimezone(v string)`

SetTimezone sets Timezone field to given value.


### SetTimezoneNil

`func (o *DAGDetailsResponse) SetTimezoneNil(b bool)`

 SetTimezoneNil sets the value for Timezone to be an explicit nil

### UnsetTimezone
`func (o *DAGDetailsResponse) UnsetTimezone()`

UnsetTimezone ensures that no value is present for Timezone, not even an explicit nil
### GetLastParsed

`func (o *DAGDetailsResponse) GetLastParsed() time.Time`

GetLastParsed returns the LastParsed field if non-nil, zero value otherwise.

### GetLastParsedOk

`func (o *DAGDetailsResponse) GetLastParsedOk() (*time.Time, bool)`

GetLastParsedOk returns a tuple with the LastParsed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastParsed

`func (o *DAGDetailsResponse) SetLastParsed(v time.Time)`

SetLastParsed sets LastParsed field to given value.


### SetLastParsedNil

`func (o *DAGDetailsResponse) SetLastParsedNil(b bool)`

 SetLastParsedNil sets the value for LastParsed to be an explicit nil

### UnsetLastParsed
`func (o *DAGDetailsResponse) UnsetLastParsed()`

UnsetLastParsed ensures that no value is present for LastParsed, not even an explicit nil
### GetDefaultArgs

`func (o *DAGDetailsResponse) GetDefaultArgs() map[string]interface{}`

GetDefaultArgs returns the DefaultArgs field if non-nil, zero value otherwise.

### GetDefaultArgsOk

`func (o *DAGDetailsResponse) GetDefaultArgsOk() (*map[string]interface{}, bool)`

GetDefaultArgsOk returns a tuple with the DefaultArgs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefaultArgs

`func (o *DAGDetailsResponse) SetDefaultArgs(v map[string]interface{})`

SetDefaultArgs sets DefaultArgs field to given value.


### SetDefaultArgsNil

`func (o *DAGDetailsResponse) SetDefaultArgsNil(b bool)`

 SetDefaultArgsNil sets the value for DefaultArgs to be an explicit nil

### UnsetDefaultArgs
`func (o *DAGDetailsResponse) UnsetDefaultArgs()`

UnsetDefaultArgs ensures that no value is present for DefaultArgs, not even an explicit nil
### GetOwnerLinks

`func (o *DAGDetailsResponse) GetOwnerLinks() map[string]string`

GetOwnerLinks returns the OwnerLinks field if non-nil, zero value otherwise.

### GetOwnerLinksOk

`func (o *DAGDetailsResponse) GetOwnerLinksOk() (*map[string]string, bool)`

GetOwnerLinksOk returns a tuple with the OwnerLinks field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOwnerLinks

`func (o *DAGDetailsResponse) SetOwnerLinks(v map[string]string)`

SetOwnerLinks sets OwnerLinks field to given value.

### HasOwnerLinks

`func (o *DAGDetailsResponse) HasOwnerLinks() bool`

HasOwnerLinks returns a boolean if a field has been set.

### SetOwnerLinksNil

`func (o *DAGDetailsResponse) SetOwnerLinksNil(b bool)`

 SetOwnerLinksNil sets the value for OwnerLinks to be an explicit nil

### UnsetOwnerLinks
`func (o *DAGDetailsResponse) UnsetOwnerLinks()`

UnsetOwnerLinks ensures that no value is present for OwnerLinks, not even an explicit nil
### GetFileToken

`func (o *DAGDetailsResponse) GetFileToken() string`

GetFileToken returns the FileToken field if non-nil, zero value otherwise.

### GetFileTokenOk

`func (o *DAGDetailsResponse) GetFileTokenOk() (*string, bool)`

GetFileTokenOk returns a tuple with the FileToken field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFileToken

`func (o *DAGDetailsResponse) SetFileToken(v string)`

SetFileToken sets FileToken field to given value.


### GetConcurrency

`func (o *DAGDetailsResponse) GetConcurrency() int32`

GetConcurrency returns the Concurrency field if non-nil, zero value otherwise.

### GetConcurrencyOk

`func (o *DAGDetailsResponse) GetConcurrencyOk() (*int32, bool)`

GetConcurrencyOk returns a tuple with the Concurrency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConcurrency

`func (o *DAGDetailsResponse) SetConcurrency(v int32)`

SetConcurrency sets Concurrency field to given value.


### GetLatestDagVersion

`func (o *DAGDetailsResponse) GetLatestDagVersion() DagVersionResponse`

GetLatestDagVersion returns the LatestDagVersion field if non-nil, zero value otherwise.

### GetLatestDagVersionOk

`func (o *DAGDetailsResponse) GetLatestDagVersionOk() (*DagVersionResponse, bool)`

GetLatestDagVersionOk returns a tuple with the LatestDagVersion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLatestDagVersion

`func (o *DAGDetailsResponse) SetLatestDagVersion(v DagVersionResponse)`

SetLatestDagVersion sets LatestDagVersion field to given value.


### SetLatestDagVersionNil

`func (o *DAGDetailsResponse) SetLatestDagVersionNil(b bool)`

 SetLatestDagVersionNil sets the value for LatestDagVersion to be an explicit nil

### UnsetLatestDagVersion
`func (o *DAGDetailsResponse) UnsetLatestDagVersion()`

UnsetLatestDagVersion ensures that no value is present for LatestDagVersion, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


