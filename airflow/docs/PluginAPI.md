# \PluginAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetPlugins**](PluginAPI.md#GetPlugins) | **Get** /api/v2/plugins | Get Plugins
[**ImportErrors**](PluginAPI.md#ImportErrors) | **Get** /api/v2/plugins/importErrors | Import Errors



## GetPlugins

> PluginCollectionResponse GetPlugins(ctx).Limit(limit).Offset(offset).Execute()

Get Plugins

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
	limit := int32(56) // int32 |  (optional) (default to 50)
	offset := int32(56) // int32 |  (optional) (default to 0)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PluginAPI.GetPlugins(context.Background()).Limit(limit).Offset(offset).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PluginAPI.GetPlugins``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetPlugins`: PluginCollectionResponse
	fmt.Fprintf(os.Stdout, "Response from `PluginAPI.GetPlugins`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetPluginsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **limit** | **int32** |  | [default to 50]
 **offset** | **int32** |  | [default to 0]

### Return type

[**PluginCollectionResponse**](PluginCollectionResponse.md)

### Authorization

[OAuth2PasswordBearer](../README.md#OAuth2PasswordBearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ImportErrors

> PluginImportErrorCollectionResponse ImportErrors(ctx).Execute()

Import Errors

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

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PluginAPI.ImportErrors(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PluginAPI.ImportErrors``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ImportErrors`: PluginImportErrorCollectionResponse
	fmt.Fprintf(os.Stdout, "Response from `PluginAPI.ImportErrors`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiImportErrorsRequest struct via the builder pattern


### Return type

[**PluginImportErrorCollectionResponse**](PluginImportErrorCollectionResponse.md)

### Authorization

[OAuth2PasswordBearer](../README.md#OAuth2PasswordBearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

