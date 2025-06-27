# ImportErrorResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ImportErrorId** | **int32** |  | 
**Timestamp** | **time.Time** |  | 
**Filename** | **string** |  | 
**BundleName** | **NullableString** |  | 
**StackTrace** | **string** |  | 

## Methods

### NewImportErrorResponse

`func NewImportErrorResponse(importErrorId int32, timestamp time.Time, filename string, bundleName NullableString, stackTrace string, ) *ImportErrorResponse`

NewImportErrorResponse instantiates a new ImportErrorResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewImportErrorResponseWithDefaults

`func NewImportErrorResponseWithDefaults() *ImportErrorResponse`

NewImportErrorResponseWithDefaults instantiates a new ImportErrorResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetImportErrorId

`func (o *ImportErrorResponse) GetImportErrorId() int32`

GetImportErrorId returns the ImportErrorId field if non-nil, zero value otherwise.

### GetImportErrorIdOk

`func (o *ImportErrorResponse) GetImportErrorIdOk() (*int32, bool)`

GetImportErrorIdOk returns a tuple with the ImportErrorId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImportErrorId

`func (o *ImportErrorResponse) SetImportErrorId(v int32)`

SetImportErrorId sets ImportErrorId field to given value.


### GetTimestamp

`func (o *ImportErrorResponse) GetTimestamp() time.Time`

GetTimestamp returns the Timestamp field if non-nil, zero value otherwise.

### GetTimestampOk

`func (o *ImportErrorResponse) GetTimestampOk() (*time.Time, bool)`

GetTimestampOk returns a tuple with the Timestamp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimestamp

`func (o *ImportErrorResponse) SetTimestamp(v time.Time)`

SetTimestamp sets Timestamp field to given value.


### GetFilename

`func (o *ImportErrorResponse) GetFilename() string`

GetFilename returns the Filename field if non-nil, zero value otherwise.

### GetFilenameOk

`func (o *ImportErrorResponse) GetFilenameOk() (*string, bool)`

GetFilenameOk returns a tuple with the Filename field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFilename

`func (o *ImportErrorResponse) SetFilename(v string)`

SetFilename sets Filename field to given value.


### GetBundleName

`func (o *ImportErrorResponse) GetBundleName() string`

GetBundleName returns the BundleName field if non-nil, zero value otherwise.

### GetBundleNameOk

`func (o *ImportErrorResponse) GetBundleNameOk() (*string, bool)`

GetBundleNameOk returns a tuple with the BundleName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBundleName

`func (o *ImportErrorResponse) SetBundleName(v string)`

SetBundleName sets BundleName field to given value.


### SetBundleNameNil

`func (o *ImportErrorResponse) SetBundleNameNil(b bool)`

 SetBundleNameNil sets the value for BundleName to be an explicit nil

### UnsetBundleName
`func (o *ImportErrorResponse) UnsetBundleName()`

UnsetBundleName ensures that no value is present for BundleName, not even an explicit nil
### GetStackTrace

`func (o *ImportErrorResponse) GetStackTrace() string`

GetStackTrace returns the StackTrace field if non-nil, zero value otherwise.

### GetStackTraceOk

`func (o *ImportErrorResponse) GetStackTraceOk() (*string, bool)`

GetStackTraceOk returns a tuple with the StackTrace field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStackTrace

`func (o *ImportErrorResponse) SetStackTrace(v string)`

SetStackTrace sets StackTrace field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


