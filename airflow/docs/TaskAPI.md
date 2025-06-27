# \TaskAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetTask**](TaskAPI.md#GetTask) | **Get** /api/v2/dags/{dag_id}/tasks/{task_id} | Get Task
[**GetTasks**](TaskAPI.md#GetTasks) | **Get** /api/v2/dags/{dag_id}/tasks | Get Tasks



## GetTask

> TaskResponse GetTask(ctx, dagId, taskId).Execute()

Get Task



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
	taskId := TODO // interface{} | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TaskAPI.GetTask(context.Background(), dagId, taskId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TaskAPI.GetTask``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetTask`: TaskResponse
	fmt.Fprintf(os.Stdout, "Response from `TaskAPI.GetTask`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**dagId** | **string** |  | 
**taskId** | [**interface{}**](.md) |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetTaskRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**TaskResponse**](TaskResponse.md)

### Authorization

[OAuth2PasswordBearer](../README.md#OAuth2PasswordBearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetTasks

> TaskCollectionResponse GetTasks(ctx, dagId).OrderBy(orderBy).Execute()

Get Tasks



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
	orderBy := "orderBy_example" // string |  (optional) (default to "task_id")

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TaskAPI.GetTasks(context.Background(), dagId).OrderBy(orderBy).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TaskAPI.GetTasks``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetTasks`: TaskCollectionResponse
	fmt.Fprintf(os.Stdout, "Response from `TaskAPI.GetTasks`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**dagId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetTasksRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **orderBy** | **string** |  | [default to &quot;task_id&quot;]

### Return type

[**TaskCollectionResponse**](TaskCollectionResponse.md)

### Authorization

[OAuth2PasswordBearer](../README.md#OAuth2PasswordBearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

