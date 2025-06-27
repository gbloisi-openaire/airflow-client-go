# \ImportErrorAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetImportError**](ImportErrorAPI.md#GetImportError) | **Get** /api/v2/importErrors/{import_error_id} | Get Import Error
[**GetImportErrors**](ImportErrorAPI.md#GetImportErrors) | **Get** /api/v2/importErrors | Get Import Errors



## GetImportError

> ImportErrorResponse GetImportError(ctx, importErrorId).Execute()

Get Import Error



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
	importErrorId := int32(56) // int32 | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ImportErrorAPI.GetImportError(context.Background(), importErrorId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ImportErrorAPI.GetImportError``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetImportError`: ImportErrorResponse
	fmt.Fprintf(os.Stdout, "Response from `ImportErrorAPI.GetImportError`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**importErrorId** | **int32** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetImportErrorRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**ImportErrorResponse**](ImportErrorResponse.md)

### Authorization

[OAuth2PasswordBearer](../README.md#OAuth2PasswordBearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetImportErrors

> ImportErrorCollectionResponse GetImportErrors(ctx).Limit(limit).Offset(offset).OrderBy(orderBy).Execute()

Get Import Errors



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
	orderBy := "orderBy_example" // string |  (optional) (default to "id")

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ImportErrorAPI.GetImportErrors(context.Background()).Limit(limit).Offset(offset).OrderBy(orderBy).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ImportErrorAPI.GetImportErrors``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetImportErrors`: ImportErrorCollectionResponse
	fmt.Fprintf(os.Stdout, "Response from `ImportErrorAPI.GetImportErrors`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetImportErrorsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **limit** | **int32** |  | [default to 50]
 **offset** | **int32** |  | [default to 0]
 **orderBy** | **string** |  | [default to &quot;id&quot;]

### Return type

[**ImportErrorCollectionResponse**](ImportErrorCollectionResponse.md)

### Authorization

[OAuth2PasswordBearer](../README.md#OAuth2PasswordBearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

