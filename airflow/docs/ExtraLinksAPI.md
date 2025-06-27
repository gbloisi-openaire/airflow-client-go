# \ExtraLinksAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetExtraLinks**](ExtraLinksAPI.md#GetExtraLinks) | **Get** /api/v2/dags/{dag_id}/dagRuns/{dag_run_id}/taskInstances/{task_id}/links | Get Extra Links



## GetExtraLinks

> ExtraLinkCollectionResponse GetExtraLinks(ctx, dagId, dagRunId, taskId).MapIndex(mapIndex).Execute()

Get Extra Links



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
	dagId := "dagId_example" // string | 
	dagRunId := "dagRunId_example" // string | 
	taskId := "taskId_example" // string | 
	mapIndex := int32(56) // int32 |  (optional) (default to -1)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ExtraLinksAPI.GetExtraLinks(context.Background(), dagId, dagRunId, taskId).MapIndex(mapIndex).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ExtraLinksAPI.GetExtraLinks``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetExtraLinks`: ExtraLinkCollectionResponse
	fmt.Fprintf(os.Stdout, "Response from `ExtraLinksAPI.GetExtraLinks`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**dagId** | **string** |  | 
**dagRunId** | **string** |  | 
**taskId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetExtraLinksRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



 **mapIndex** | **int32** |  | [default to -1]

### Return type

[**ExtraLinkCollectionResponse**](ExtraLinkCollectionResponse.md)

### Authorization

[OAuth2PasswordBearer](../README.md#OAuth2PasswordBearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

