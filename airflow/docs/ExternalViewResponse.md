# ExternalViewResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | **string** |  | 
**Icon** | Pointer to **NullableString** |  | [optional] 
**IconDarkMode** | Pointer to **NullableString** |  | [optional] 
**UrlRoute** | Pointer to **NullableString** |  | [optional] 
**Category** | Pointer to **NullableString** |  | [optional] 
**Destination** | Pointer to **string** |  | [optional] [default to "nav"]
**Href** | **string** |  | 

## Methods

### NewExternalViewResponse

`func NewExternalViewResponse(name string, href string, ) *ExternalViewResponse`

NewExternalViewResponse instantiates a new ExternalViewResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewExternalViewResponseWithDefaults

`func NewExternalViewResponseWithDefaults() *ExternalViewResponse`

NewExternalViewResponseWithDefaults instantiates a new ExternalViewResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *ExternalViewResponse) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ExternalViewResponse) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ExternalViewResponse) SetName(v string)`

SetName sets Name field to given value.


### GetIcon

`func (o *ExternalViewResponse) GetIcon() string`

GetIcon returns the Icon field if non-nil, zero value otherwise.

### GetIconOk

`func (o *ExternalViewResponse) GetIconOk() (*string, bool)`

GetIconOk returns a tuple with the Icon field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIcon

`func (o *ExternalViewResponse) SetIcon(v string)`

SetIcon sets Icon field to given value.

### HasIcon

`func (o *ExternalViewResponse) HasIcon() bool`

HasIcon returns a boolean if a field has been set.

### SetIconNil

`func (o *ExternalViewResponse) SetIconNil(b bool)`

 SetIconNil sets the value for Icon to be an explicit nil

### UnsetIcon
`func (o *ExternalViewResponse) UnsetIcon()`

UnsetIcon ensures that no value is present for Icon, not even an explicit nil
### GetIconDarkMode

`func (o *ExternalViewResponse) GetIconDarkMode() string`

GetIconDarkMode returns the IconDarkMode field if non-nil, zero value otherwise.

### GetIconDarkModeOk

`func (o *ExternalViewResponse) GetIconDarkModeOk() (*string, bool)`

GetIconDarkModeOk returns a tuple with the IconDarkMode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIconDarkMode

`func (o *ExternalViewResponse) SetIconDarkMode(v string)`

SetIconDarkMode sets IconDarkMode field to given value.

### HasIconDarkMode

`func (o *ExternalViewResponse) HasIconDarkMode() bool`

HasIconDarkMode returns a boolean if a field has been set.

### SetIconDarkModeNil

`func (o *ExternalViewResponse) SetIconDarkModeNil(b bool)`

 SetIconDarkModeNil sets the value for IconDarkMode to be an explicit nil

### UnsetIconDarkMode
`func (o *ExternalViewResponse) UnsetIconDarkMode()`

UnsetIconDarkMode ensures that no value is present for IconDarkMode, not even an explicit nil
### GetUrlRoute

`func (o *ExternalViewResponse) GetUrlRoute() string`

GetUrlRoute returns the UrlRoute field if non-nil, zero value otherwise.

### GetUrlRouteOk

`func (o *ExternalViewResponse) GetUrlRouteOk() (*string, bool)`

GetUrlRouteOk returns a tuple with the UrlRoute field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrlRoute

`func (o *ExternalViewResponse) SetUrlRoute(v string)`

SetUrlRoute sets UrlRoute field to given value.

### HasUrlRoute

`func (o *ExternalViewResponse) HasUrlRoute() bool`

HasUrlRoute returns a boolean if a field has been set.

### SetUrlRouteNil

`func (o *ExternalViewResponse) SetUrlRouteNil(b bool)`

 SetUrlRouteNil sets the value for UrlRoute to be an explicit nil

### UnsetUrlRoute
`func (o *ExternalViewResponse) UnsetUrlRoute()`

UnsetUrlRoute ensures that no value is present for UrlRoute, not even an explicit nil
### GetCategory

`func (o *ExternalViewResponse) GetCategory() string`

GetCategory returns the Category field if non-nil, zero value otherwise.

### GetCategoryOk

`func (o *ExternalViewResponse) GetCategoryOk() (*string, bool)`

GetCategoryOk returns a tuple with the Category field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCategory

`func (o *ExternalViewResponse) SetCategory(v string)`

SetCategory sets Category field to given value.

### HasCategory

`func (o *ExternalViewResponse) HasCategory() bool`

HasCategory returns a boolean if a field has been set.

### SetCategoryNil

`func (o *ExternalViewResponse) SetCategoryNil(b bool)`

 SetCategoryNil sets the value for Category to be an explicit nil

### UnsetCategory
`func (o *ExternalViewResponse) UnsetCategory()`

UnsetCategory ensures that no value is present for Category, not even an explicit nil
### GetDestination

`func (o *ExternalViewResponse) GetDestination() string`

GetDestination returns the Destination field if non-nil, zero value otherwise.

### GetDestinationOk

`func (o *ExternalViewResponse) GetDestinationOk() (*string, bool)`

GetDestinationOk returns a tuple with the Destination field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDestination

`func (o *ExternalViewResponse) SetDestination(v string)`

SetDestination sets Destination field to given value.

### HasDestination

`func (o *ExternalViewResponse) HasDestination() bool`

HasDestination returns a boolean if a field has been set.

### GetHref

`func (o *ExternalViewResponse) GetHref() string`

GetHref returns the Href field if non-nil, zero value otherwise.

### GetHrefOk

`func (o *ExternalViewResponse) GetHrefOk() (*string, bool)`

GetHrefOk returns a tuple with the Href field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHref

`func (o *ExternalViewResponse) SetHref(v string)`

SetHref sets Href field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


