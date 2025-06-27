# ConfigSection

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | **string** |  | 
**Options** | [**[]ConfigOption**](ConfigOption.md) |  | 

## Methods

### NewConfigSection

`func NewConfigSection(name string, options []ConfigOption, ) *ConfigSection`

NewConfigSection instantiates a new ConfigSection object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewConfigSectionWithDefaults

`func NewConfigSectionWithDefaults() *ConfigSection`

NewConfigSectionWithDefaults instantiates a new ConfigSection object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *ConfigSection) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ConfigSection) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ConfigSection) SetName(v string)`

SetName sets Name field to given value.


### GetOptions

`func (o *ConfigSection) GetOptions() []ConfigOption`

GetOptions returns the Options field if non-nil, zero value otherwise.

### GetOptionsOk

`func (o *ConfigSection) GetOptionsOk() (*[]ConfigOption, bool)`

GetOptionsOk returns a tuple with the Options field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOptions

`func (o *ConfigSection) SetOptions(v []ConfigOption)`

SetOptions sets Options field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


