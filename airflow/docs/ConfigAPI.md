# \ConfigAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetConfig**](ConfigAPI.md#GetConfig) | **Get** /api/v2/config | Get Config
[**GetConfigValue**](ConfigAPI.md#GetConfigValue) | **Get** /api/v2/config/section/{section}/option/{option} | Get Config Value



## GetConfig

> Config GetConfig(ctx).Section(section).Accept(accept).Execute()

Get Config

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/gbloisi-openaire/airflow-client-go/airflow"
)

func main() {
	section := "section_example" // string |  (optional)
	accept := "accept_example" // string |  (optional) (default to "*_/_*")

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ConfigAPI.GetConfig(context.Background()).Section(section).Accept(accept).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConfigAPI.GetConfig``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetConfig`: Config
	fmt.Fprintf(os.Stdout, "Response from `ConfigAPI.GetConfig`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetConfigRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **section** | **string** |  | 
 **accept** | **string** |  | [default to &quot;*_/_*&quot;]

### Return type

[**Config**](Config.md)

### Authorization

[OAuth2PasswordBearer](../README.md#OAuth2PasswordBearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json, text/plain

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetConfigValue

> Config GetConfigValue(ctx, section, option).Accept(accept).Execute()

Get Config Value

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/gbloisi-openaire/airflow-client-go/airflow"
)

func main() {
	section := "section_example" // string | 
	option := "option_example" // string | 
	accept := "accept_example" // string |  (optional) (default to "*_/_*")

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ConfigAPI.GetConfigValue(context.Background(), section, option).Accept(accept).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConfigAPI.GetConfigValue``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetConfigValue`: Config
	fmt.Fprintf(os.Stdout, "Response from `ConfigAPI.GetConfigValue`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**section** | **string** |  | 
**option** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetConfigValueRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **accept** | **string** |  | [default to &quot;*_/_*&quot;]

### Return type

[**Config**](Config.md)

### Authorization

[OAuth2PasswordBearer](../README.md#OAuth2PasswordBearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json, text/plain

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

