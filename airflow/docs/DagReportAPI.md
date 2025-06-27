# \DagReportAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetDagReports**](DagReportAPI.md#GetDagReports) | **Get** /api/v2/dagReports | Get Dag Reports



## GetDagReports

> interface{} GetDagReports(ctx).Subdir(subdir).Execute()

Get Dag Reports



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	subdir := "subdir_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DagReportAPI.GetDagReports(context.Background()).Subdir(subdir).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DagReportAPI.GetDagReports``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetDagReports`: interface{}
	fmt.Fprintf(os.Stdout, "Response from `DagReportAPI.GetDagReports`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetDagReportsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **subdir** | **string** |  | 

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

