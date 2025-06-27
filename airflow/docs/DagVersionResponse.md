# DagVersionResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | 
**VersionNumber** | **int32** |  | 
**DagId** | **string** |  | 
**BundleName** | **NullableString** |  | 
**BundleVersion** | **NullableString** |  | 
**CreatedAt** | **time.Time** |  | 
**DagDisplayName** | **string** |  | 
**BundleUrl** | **NullableString** |  | 

## Methods

### NewDagVersionResponse

`func NewDagVersionResponse(id string, versionNumber int32, dagId string, bundleName NullableString, bundleVersion NullableString, createdAt time.Time, dagDisplayName string, bundleUrl NullableString, ) *DagVersionResponse`

NewDagVersionResponse instantiates a new DagVersionResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDagVersionResponseWithDefaults

`func NewDagVersionResponseWithDefaults() *DagVersionResponse`

NewDagVersionResponseWithDefaults instantiates a new DagVersionResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *DagVersionResponse) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *DagVersionResponse) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *DagVersionResponse) SetId(v string)`

SetId sets Id field to given value.


### GetVersionNumber

`func (o *DagVersionResponse) GetVersionNumber() int32`

GetVersionNumber returns the VersionNumber field if non-nil, zero value otherwise.

### GetVersionNumberOk

`func (o *DagVersionResponse) GetVersionNumberOk() (*int32, bool)`

GetVersionNumberOk returns a tuple with the VersionNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVersionNumber

`func (o *DagVersionResponse) SetVersionNumber(v int32)`

SetVersionNumber sets VersionNumber field to given value.


### GetDagId

`func (o *DagVersionResponse) GetDagId() string`

GetDagId returns the DagId field if non-nil, zero value otherwise.

### GetDagIdOk

`func (o *DagVersionResponse) GetDagIdOk() (*string, bool)`

GetDagIdOk returns a tuple with the DagId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDagId

`func (o *DagVersionResponse) SetDagId(v string)`

SetDagId sets DagId field to given value.


### GetBundleName

`func (o *DagVersionResponse) GetBundleName() string`

GetBundleName returns the BundleName field if non-nil, zero value otherwise.

### GetBundleNameOk

`func (o *DagVersionResponse) GetBundleNameOk() (*string, bool)`

GetBundleNameOk returns a tuple with the BundleName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBundleName

`func (o *DagVersionResponse) SetBundleName(v string)`

SetBundleName sets BundleName field to given value.


### SetBundleNameNil

`func (o *DagVersionResponse) SetBundleNameNil(b bool)`

 SetBundleNameNil sets the value for BundleName to be an explicit nil

### UnsetBundleName
`func (o *DagVersionResponse) UnsetBundleName()`

UnsetBundleName ensures that no value is present for BundleName, not even an explicit nil
### GetBundleVersion

`func (o *DagVersionResponse) GetBundleVersion() string`

GetBundleVersion returns the BundleVersion field if non-nil, zero value otherwise.

### GetBundleVersionOk

`func (o *DagVersionResponse) GetBundleVersionOk() (*string, bool)`

GetBundleVersionOk returns a tuple with the BundleVersion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBundleVersion

`func (o *DagVersionResponse) SetBundleVersion(v string)`

SetBundleVersion sets BundleVersion field to given value.


### SetBundleVersionNil

`func (o *DagVersionResponse) SetBundleVersionNil(b bool)`

 SetBundleVersionNil sets the value for BundleVersion to be an explicit nil

### UnsetBundleVersion
`func (o *DagVersionResponse) UnsetBundleVersion()`

UnsetBundleVersion ensures that no value is present for BundleVersion, not even an explicit nil
### GetCreatedAt

`func (o *DagVersionResponse) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *DagVersionResponse) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *DagVersionResponse) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetDagDisplayName

`func (o *DagVersionResponse) GetDagDisplayName() string`

GetDagDisplayName returns the DagDisplayName field if non-nil, zero value otherwise.

### GetDagDisplayNameOk

`func (o *DagVersionResponse) GetDagDisplayNameOk() (*string, bool)`

GetDagDisplayNameOk returns a tuple with the DagDisplayName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDagDisplayName

`func (o *DagVersionResponse) SetDagDisplayName(v string)`

SetDagDisplayName sets DagDisplayName field to given value.


### GetBundleUrl

`func (o *DagVersionResponse) GetBundleUrl() string`

GetBundleUrl returns the BundleUrl field if non-nil, zero value otherwise.

### GetBundleUrlOk

`func (o *DagVersionResponse) GetBundleUrlOk() (*string, bool)`

GetBundleUrlOk returns a tuple with the BundleUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBundleUrl

`func (o *DagVersionResponse) SetBundleUrl(v string)`

SetBundleUrl sets BundleUrl field to given value.


### SetBundleUrlNil

`func (o *DagVersionResponse) SetBundleUrlNil(b bool)`

 SetBundleUrlNil sets the value for BundleUrl to be an explicit nil

### UnsetBundleUrl
`func (o *DagVersionResponse) UnsetBundleUrl()`

UnsetBundleUrl ensures that no value is present for BundleUrl, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


