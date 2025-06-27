# PluginResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | **string** |  | 
**Macros** | **[]string** |  | 
**FlaskBlueprints** | **[]string** |  | 
**FastapiApps** | [**[]FastAPIAppResponse**](FastAPIAppResponse.md) |  | 
**FastapiRootMiddlewares** | [**[]FastAPIRootMiddlewareResponse**](FastAPIRootMiddlewareResponse.md) |  | 
**ExternalViews** | [**[]ExternalViewResponse**](ExternalViewResponse.md) | Aggregate all external views. Both &#39;external_views&#39; and &#39;appbuilder_menu_items&#39; are included here. | 
**ReactApps** | [**[]ReactAppResponse**](ReactAppResponse.md) |  | 
**AppbuilderViews** | [**[]AppBuilderViewResponse**](AppBuilderViewResponse.md) |  | 
**AppbuilderMenuItems** | [**[]AppBuilderMenuItemResponse**](AppBuilderMenuItemResponse.md) |  | 
**GlobalOperatorExtraLinks** | **[]string** |  | 
**OperatorExtraLinks** | **[]string** |  | 
**Source** | **string** |  | 
**Listeners** | **[]string** |  | 
**Timetables** | **[]string** |  | 

## Methods

### NewPluginResponse

`func NewPluginResponse(name string, macros []string, flaskBlueprints []string, fastapiApps []FastAPIAppResponse, fastapiRootMiddlewares []FastAPIRootMiddlewareResponse, externalViews []ExternalViewResponse, reactApps []ReactAppResponse, appbuilderViews []AppBuilderViewResponse, appbuilderMenuItems []AppBuilderMenuItemResponse, globalOperatorExtraLinks []string, operatorExtraLinks []string, source string, listeners []string, timetables []string, ) *PluginResponse`

NewPluginResponse instantiates a new PluginResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPluginResponseWithDefaults

`func NewPluginResponseWithDefaults() *PluginResponse`

NewPluginResponseWithDefaults instantiates a new PluginResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *PluginResponse) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *PluginResponse) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *PluginResponse) SetName(v string)`

SetName sets Name field to given value.


### GetMacros

`func (o *PluginResponse) GetMacros() []string`

GetMacros returns the Macros field if non-nil, zero value otherwise.

### GetMacrosOk

`func (o *PluginResponse) GetMacrosOk() (*[]string, bool)`

GetMacrosOk returns a tuple with the Macros field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMacros

`func (o *PluginResponse) SetMacros(v []string)`

SetMacros sets Macros field to given value.


### GetFlaskBlueprints

`func (o *PluginResponse) GetFlaskBlueprints() []string`

GetFlaskBlueprints returns the FlaskBlueprints field if non-nil, zero value otherwise.

### GetFlaskBlueprintsOk

`func (o *PluginResponse) GetFlaskBlueprintsOk() (*[]string, bool)`

GetFlaskBlueprintsOk returns a tuple with the FlaskBlueprints field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFlaskBlueprints

`func (o *PluginResponse) SetFlaskBlueprints(v []string)`

SetFlaskBlueprints sets FlaskBlueprints field to given value.


### GetFastapiApps

`func (o *PluginResponse) GetFastapiApps() []FastAPIAppResponse`

GetFastapiApps returns the FastapiApps field if non-nil, zero value otherwise.

### GetFastapiAppsOk

`func (o *PluginResponse) GetFastapiAppsOk() (*[]FastAPIAppResponse, bool)`

GetFastapiAppsOk returns a tuple with the FastapiApps field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFastapiApps

`func (o *PluginResponse) SetFastapiApps(v []FastAPIAppResponse)`

SetFastapiApps sets FastapiApps field to given value.


### GetFastapiRootMiddlewares

`func (o *PluginResponse) GetFastapiRootMiddlewares() []FastAPIRootMiddlewareResponse`

GetFastapiRootMiddlewares returns the FastapiRootMiddlewares field if non-nil, zero value otherwise.

### GetFastapiRootMiddlewaresOk

`func (o *PluginResponse) GetFastapiRootMiddlewaresOk() (*[]FastAPIRootMiddlewareResponse, bool)`

GetFastapiRootMiddlewaresOk returns a tuple with the FastapiRootMiddlewares field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFastapiRootMiddlewares

`func (o *PluginResponse) SetFastapiRootMiddlewares(v []FastAPIRootMiddlewareResponse)`

SetFastapiRootMiddlewares sets FastapiRootMiddlewares field to given value.


### GetExternalViews

`func (o *PluginResponse) GetExternalViews() []ExternalViewResponse`

GetExternalViews returns the ExternalViews field if non-nil, zero value otherwise.

### GetExternalViewsOk

`func (o *PluginResponse) GetExternalViewsOk() (*[]ExternalViewResponse, bool)`

GetExternalViewsOk returns a tuple with the ExternalViews field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExternalViews

`func (o *PluginResponse) SetExternalViews(v []ExternalViewResponse)`

SetExternalViews sets ExternalViews field to given value.


### GetReactApps

`func (o *PluginResponse) GetReactApps() []ReactAppResponse`

GetReactApps returns the ReactApps field if non-nil, zero value otherwise.

### GetReactAppsOk

`func (o *PluginResponse) GetReactAppsOk() (*[]ReactAppResponse, bool)`

GetReactAppsOk returns a tuple with the ReactApps field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReactApps

`func (o *PluginResponse) SetReactApps(v []ReactAppResponse)`

SetReactApps sets ReactApps field to given value.


### GetAppbuilderViews

`func (o *PluginResponse) GetAppbuilderViews() []AppBuilderViewResponse`

GetAppbuilderViews returns the AppbuilderViews field if non-nil, zero value otherwise.

### GetAppbuilderViewsOk

`func (o *PluginResponse) GetAppbuilderViewsOk() (*[]AppBuilderViewResponse, bool)`

GetAppbuilderViewsOk returns a tuple with the AppbuilderViews field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAppbuilderViews

`func (o *PluginResponse) SetAppbuilderViews(v []AppBuilderViewResponse)`

SetAppbuilderViews sets AppbuilderViews field to given value.


### GetAppbuilderMenuItems

`func (o *PluginResponse) GetAppbuilderMenuItems() []AppBuilderMenuItemResponse`

GetAppbuilderMenuItems returns the AppbuilderMenuItems field if non-nil, zero value otherwise.

### GetAppbuilderMenuItemsOk

`func (o *PluginResponse) GetAppbuilderMenuItemsOk() (*[]AppBuilderMenuItemResponse, bool)`

GetAppbuilderMenuItemsOk returns a tuple with the AppbuilderMenuItems field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAppbuilderMenuItems

`func (o *PluginResponse) SetAppbuilderMenuItems(v []AppBuilderMenuItemResponse)`

SetAppbuilderMenuItems sets AppbuilderMenuItems field to given value.


### GetGlobalOperatorExtraLinks

`func (o *PluginResponse) GetGlobalOperatorExtraLinks() []string`

GetGlobalOperatorExtraLinks returns the GlobalOperatorExtraLinks field if non-nil, zero value otherwise.

### GetGlobalOperatorExtraLinksOk

`func (o *PluginResponse) GetGlobalOperatorExtraLinksOk() (*[]string, bool)`

GetGlobalOperatorExtraLinksOk returns a tuple with the GlobalOperatorExtraLinks field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGlobalOperatorExtraLinks

`func (o *PluginResponse) SetGlobalOperatorExtraLinks(v []string)`

SetGlobalOperatorExtraLinks sets GlobalOperatorExtraLinks field to given value.


### GetOperatorExtraLinks

`func (o *PluginResponse) GetOperatorExtraLinks() []string`

GetOperatorExtraLinks returns the OperatorExtraLinks field if non-nil, zero value otherwise.

### GetOperatorExtraLinksOk

`func (o *PluginResponse) GetOperatorExtraLinksOk() (*[]string, bool)`

GetOperatorExtraLinksOk returns a tuple with the OperatorExtraLinks field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperatorExtraLinks

`func (o *PluginResponse) SetOperatorExtraLinks(v []string)`

SetOperatorExtraLinks sets OperatorExtraLinks field to given value.


### GetSource

`func (o *PluginResponse) GetSource() string`

GetSource returns the Source field if non-nil, zero value otherwise.

### GetSourceOk

`func (o *PluginResponse) GetSourceOk() (*string, bool)`

GetSourceOk returns a tuple with the Source field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSource

`func (o *PluginResponse) SetSource(v string)`

SetSource sets Source field to given value.


### GetListeners

`func (o *PluginResponse) GetListeners() []string`

GetListeners returns the Listeners field if non-nil, zero value otherwise.

### GetListenersOk

`func (o *PluginResponse) GetListenersOk() (*[]string, bool)`

GetListenersOk returns a tuple with the Listeners field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetListeners

`func (o *PluginResponse) SetListeners(v []string)`

SetListeners sets Listeners field to given value.


### GetTimetables

`func (o *PluginResponse) GetTimetables() []string`

GetTimetables returns the Timetables field if non-nil, zero value otherwise.

### GetTimetablesOk

`func (o *PluginResponse) GetTimetablesOk() (*[]string, bool)`

GetTimetablesOk returns a tuple with the Timetables field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimetables

`func (o *PluginResponse) SetTimetables(v []string)`

SetTimetables sets Timetables field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


