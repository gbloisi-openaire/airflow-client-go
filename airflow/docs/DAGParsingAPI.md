# \DAGParsingAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ReparseDagFile**](DAGParsingAPI.md#ReparseDagFile) | **Put** /api/v2/parseDagFile/{file_token} | Reparse Dag File



## ReparseDagFile

> interface{} ReparseDagFile(ctx, fileToken).Execute()

Reparse Dag File



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
	fileToken := "fileToken_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DAGParsingAPI.ReparseDagFile(context.Background(), fileToken).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DAGParsingAPI.ReparseDagFile``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ReparseDagFile`: interface{}
	fmt.Fprintf(os.Stdout, "Response from `DAGParsingAPI.ReparseDagFile`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**fileToken** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiReparseDagFileRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

**interface{}**

### Authorization

[OAuth2PasswordBearer](../README.md#OAuth2PasswordBearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

