# \DagSourceAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetDagSource**](DagSourceAPI.md#GetDagSource) | **Get** /api/v2/dagSources/{dag_id} | Get Dag Source



## GetDagSource

> DAGSourceResponse GetDagSource(ctx, dagId).VersionNumber(versionNumber).Accept(accept).Execute()

Get Dag Source



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
	dagId := "dagId_example" // string | 
	versionNumber := int32(56) // int32 |  (optional)
	accept := "accept_example" // string |  (optional) (default to "*_/_*")

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DagSourceAPI.GetDagSource(context.Background(), dagId).VersionNumber(versionNumber).Accept(accept).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DagSourceAPI.GetDagSource``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetDagSource`: DAGSourceResponse
	fmt.Fprintf(os.Stdout, "Response from `DagSourceAPI.GetDagSource`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**dagId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetDagSourceRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **versionNumber** | **int32** |  | 
 **accept** | **string** |  | [default to &quot;*_/_*&quot;]

### Return type

[**DAGSourceResponse**](DAGSourceResponse.md)

### Authorization

[OAuth2PasswordBearer](../README.md#OAuth2PasswordBearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json, text/plain

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

