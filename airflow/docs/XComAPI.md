# \XComAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateXcomEntry**](XComAPI.md#CreateXcomEntry) | **Post** /api/v2/dags/{dag_id}/dagRuns/{dag_run_id}/taskInstances/{task_id}/xcomEntries | Create Xcom Entry
[**GetXcomEntries**](XComAPI.md#GetXcomEntries) | **Get** /api/v2/dags/{dag_id}/dagRuns/{dag_run_id}/taskInstances/{task_id}/xcomEntries | Get Xcom Entries
[**GetXcomEntry**](XComAPI.md#GetXcomEntry) | **Get** /api/v2/dags/{dag_id}/dagRuns/{dag_run_id}/taskInstances/{task_id}/xcomEntries/{xcom_key} | Get Xcom Entry
[**UpdateXcomEntry**](XComAPI.md#UpdateXcomEntry) | **Patch** /api/v2/dags/{dag_id}/dagRuns/{dag_run_id}/taskInstances/{task_id}/xcomEntries/{xcom_key} | Update Xcom Entry



## CreateXcomEntry

> XComResponseNative CreateXcomEntry(ctx, dagId, taskId, dagRunId).XComCreateBody(xComCreateBody).Execute()

Create Xcom Entry



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
	taskId := "taskId_example" // string | 
	dagRunId := "dagRunId_example" // string | 
	xComCreateBody := *openapiclient.NewXComCreateBody("Key_example", interface{}(123)) // XComCreateBody | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.XComAPI.CreateXcomEntry(context.Background(), dagId, taskId, dagRunId).XComCreateBody(xComCreateBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `XComAPI.CreateXcomEntry``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateXcomEntry`: XComResponseNative
	fmt.Fprintf(os.Stdout, "Response from `XComAPI.CreateXcomEntry`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**dagId** | **string** |  | 
**taskId** | **string** |  | 
**dagRunId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiCreateXcomEntryRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



 **xComCreateBody** | [**XComCreateBody**](XComCreateBody.md) |  | 

### Return type

[**XComResponseNative**](XComResponseNative.md)

### Authorization

[OAuth2PasswordBearer](../README.md#OAuth2PasswordBearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetXcomEntries

> XComCollectionResponse GetXcomEntries(ctx, dagId, dagRunId, taskId).XcomKey(xcomKey).MapIndex(mapIndex).Limit(limit).Offset(offset).Execute()

Get Xcom Entries



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
	xcomKey := "xcomKey_example" // string |  (optional)
	mapIndex := int32(56) // int32 |  (optional)
	limit := int32(56) // int32 |  (optional) (default to 50)
	offset := int32(56) // int32 |  (optional) (default to 0)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.XComAPI.GetXcomEntries(context.Background(), dagId, dagRunId, taskId).XcomKey(xcomKey).MapIndex(mapIndex).Limit(limit).Offset(offset).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `XComAPI.GetXcomEntries``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetXcomEntries`: XComCollectionResponse
	fmt.Fprintf(os.Stdout, "Response from `XComAPI.GetXcomEntries`: %v\n", resp)
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

Other parameters are passed through a pointer to a apiGetXcomEntriesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



 **xcomKey** | **string** |  | 
 **mapIndex** | **int32** |  | 
 **limit** | **int32** |  | [default to 50]
 **offset** | **int32** |  | [default to 0]

### Return type

[**XComCollectionResponse**](XComCollectionResponse.md)

### Authorization

[OAuth2PasswordBearer](../README.md#OAuth2PasswordBearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetXcomEntry

> ResponseGetXcomEntry GetXcomEntry(ctx, dagId, taskId, dagRunId, xcomKey).MapIndex(mapIndex).Deserialize(deserialize).Stringify(stringify).Execute()

Get Xcom Entry



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
	taskId := "taskId_example" // string | 
	dagRunId := "dagRunId_example" // string | 
	xcomKey := "xcomKey_example" // string | 
	mapIndex := int32(56) // int32 |  (optional) (default to -1)
	deserialize := true // bool |  (optional) (default to false)
	stringify := true // bool |  (optional) (default to false)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.XComAPI.GetXcomEntry(context.Background(), dagId, taskId, dagRunId, xcomKey).MapIndex(mapIndex).Deserialize(deserialize).Stringify(stringify).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `XComAPI.GetXcomEntry``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetXcomEntry`: ResponseGetXcomEntry
	fmt.Fprintf(os.Stdout, "Response from `XComAPI.GetXcomEntry`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**dagId** | **string** |  | 
**taskId** | **string** |  | 
**dagRunId** | **string** |  | 
**xcomKey** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetXcomEntryRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------




 **mapIndex** | **int32** |  | [default to -1]
 **deserialize** | **bool** |  | [default to false]
 **stringify** | **bool** |  | [default to false]

### Return type

[**ResponseGetXcomEntry**](ResponseGetXcomEntry.md)

### Authorization

[OAuth2PasswordBearer](../README.md#OAuth2PasswordBearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateXcomEntry

> XComResponseNative UpdateXcomEntry(ctx, dagId, taskId, dagRunId, xcomKey).XComUpdateBody(xComUpdateBody).Execute()

Update Xcom Entry



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
	taskId := "taskId_example" // string | 
	dagRunId := "dagRunId_example" // string | 
	xcomKey := "xcomKey_example" // string | 
	xComUpdateBody := *openapiclient.NewXComUpdateBody(interface{}(123)) // XComUpdateBody | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.XComAPI.UpdateXcomEntry(context.Background(), dagId, taskId, dagRunId, xcomKey).XComUpdateBody(xComUpdateBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `XComAPI.UpdateXcomEntry``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateXcomEntry`: XComResponseNative
	fmt.Fprintf(os.Stdout, "Response from `XComAPI.UpdateXcomEntry`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**dagId** | **string** |  | 
**taskId** | **string** |  | 
**dagRunId** | **string** |  | 
**xcomKey** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateXcomEntryRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------




 **xComUpdateBody** | [**XComUpdateBody**](XComUpdateBody.md) |  | 

### Return type

[**XComResponseNative**](XComResponseNative.md)

### Authorization

[OAuth2PasswordBearer](../README.md#OAuth2PasswordBearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

