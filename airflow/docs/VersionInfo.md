# VersionInfo

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Version** | **string** |  | 
**GitVersion** | **NullableString** |  | 

## Methods

### NewVersionInfo

`func NewVersionInfo(version string, gitVersion NullableString, ) *VersionInfo`

NewVersionInfo instantiates a new VersionInfo object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewVersionInfoWithDefaults

`func NewVersionInfoWithDefaults() *VersionInfo`

NewVersionInfoWithDefaults instantiates a new VersionInfo object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetVersion

`func (o *VersionInfo) GetVersion() string`

GetVersion returns the Version field if non-nil, zero value otherwise.

### GetVersionOk

`func (o *VersionInfo) GetVersionOk() (*string, bool)`

GetVersionOk returns a tuple with the Version field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVersion

`func (o *VersionInfo) SetVersion(v string)`

SetVersion sets Version field to given value.


### GetGitVersion

`func (o *VersionInfo) GetGitVersion() string`

GetGitVersion returns the GitVersion field if non-nil, zero value otherwise.

### GetGitVersionOk

`func (o *VersionInfo) GetGitVersionOk() (*string, bool)`

GetGitVersionOk returns a tuple with the GitVersion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGitVersion

`func (o *VersionInfo) SetGitVersion(v string)`

SetGitVersion sets GitVersion field to given value.


### SetGitVersionNil

`func (o *VersionInfo) SetGitVersionNil(b bool)`

 SetGitVersionNil sets the value for GitVersion to be an explicit nil

### UnsetGitVersion
`func (o *VersionInfo) UnsetGitVersion()`

UnsetGitVersion ensures that no value is present for GitVersion, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


