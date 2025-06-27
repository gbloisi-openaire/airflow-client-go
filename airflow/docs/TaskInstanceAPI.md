# \TaskInstanceAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**BulkTaskInstances**](TaskInstanceAPI.md#BulkTaskInstances) | **Patch** /api/v2/dags/{dag_id}/dagRuns/{dag_run_id}/taskInstances | Bulk Task Instances
[**DeleteTaskInstance**](TaskInstanceAPI.md#DeleteTaskInstance) | **Delete** /api/v2/dags/{dag_id}/dagRuns/{dag_run_id}/taskInstances/{task_id} | Delete Task Instance
[**GetExternalLogUrl**](TaskInstanceAPI.md#GetExternalLogUrl) | **Get** /api/v2/dags/{dag_id}/dagRuns/{dag_run_id}/taskInstances/{task_id}/externalLogUrl/{try_number} | Get External Log Url
[**GetExtraLinks**](TaskInstanceAPI.md#GetExtraLinks) | **Get** /api/v2/dags/{dag_id}/dagRuns/{dag_run_id}/taskInstances/{task_id}/links | Get Extra Links
[**GetLog**](TaskInstanceAPI.md#GetLog) | **Get** /api/v2/dags/{dag_id}/dagRuns/{dag_run_id}/taskInstances/{task_id}/logs/{try_number} | Get Log
[**GetMappedTaskInstance**](TaskInstanceAPI.md#GetMappedTaskInstance) | **Get** /api/v2/dags/{dag_id}/dagRuns/{dag_run_id}/taskInstances/{task_id}/{map_index} | Get Mapped Task Instance
[**GetMappedTaskInstanceTries**](TaskInstanceAPI.md#GetMappedTaskInstanceTries) | **Get** /api/v2/dags/{dag_id}/dagRuns/{dag_run_id}/taskInstances/{task_id}/{map_index}/tries | Get Mapped Task Instance Tries
[**GetMappedTaskInstanceTryDetails**](TaskInstanceAPI.md#GetMappedTaskInstanceTryDetails) | **Get** /api/v2/dags/{dag_id}/dagRuns/{dag_run_id}/taskInstances/{task_id}/{map_index}/tries/{task_try_number} | Get Mapped Task Instance Try Details
[**GetMappedTaskInstances**](TaskInstanceAPI.md#GetMappedTaskInstances) | **Get** /api/v2/dags/{dag_id}/dagRuns/{dag_run_id}/taskInstances/{task_id}/listMapped | Get Mapped Task Instances
[**GetTaskInstance**](TaskInstanceAPI.md#GetTaskInstance) | **Get** /api/v2/dags/{dag_id}/dagRuns/{dag_run_id}/taskInstances/{task_id} | Get Task Instance
[**GetTaskInstanceDependencies**](TaskInstanceAPI.md#GetTaskInstanceDependencies) | **Get** /api/v2/dags/{dag_id}/dagRuns/{dag_run_id}/taskInstances/{task_id}/dependencies | Get Task Instance Dependencies
[**GetTaskInstanceDependenciesByMapIndex**](TaskInstanceAPI.md#GetTaskInstanceDependenciesByMapIndex) | **Get** /api/v2/dags/{dag_id}/dagRuns/{dag_run_id}/taskInstances/{task_id}/{map_index}/dependencies | Get Task Instance Dependencies
[**GetTaskInstanceTries**](TaskInstanceAPI.md#GetTaskInstanceTries) | **Get** /api/v2/dags/{dag_id}/dagRuns/{dag_run_id}/taskInstances/{task_id}/tries | Get Task Instance Tries
[**GetTaskInstanceTryDetails**](TaskInstanceAPI.md#GetTaskInstanceTryDetails) | **Get** /api/v2/dags/{dag_id}/dagRuns/{dag_run_id}/taskInstances/{task_id}/tries/{task_try_number} | Get Task Instance Try Details
[**GetTaskInstances**](TaskInstanceAPI.md#GetTaskInstances) | **Get** /api/v2/dags/{dag_id}/dagRuns/{dag_run_id}/taskInstances | Get Task Instances
[**GetTaskInstancesBatch**](TaskInstanceAPI.md#GetTaskInstancesBatch) | **Post** /api/v2/dags/{dag_id}/dagRuns/{dag_run_id}/taskInstances/list | Get Task Instances Batch
[**PatchTaskInstance**](TaskInstanceAPI.md#PatchTaskInstance) | **Patch** /api/v2/dags/{dag_id}/dagRuns/{dag_run_id}/taskInstances/{task_id} | Patch Task Instance
[**PatchTaskInstanceByMapIndex**](TaskInstanceAPI.md#PatchTaskInstanceByMapIndex) | **Patch** /api/v2/dags/{dag_id}/dagRuns/{dag_run_id}/taskInstances/{task_id}/{map_index} | Patch Task Instance
[**PatchTaskInstanceDryRun**](TaskInstanceAPI.md#PatchTaskInstanceDryRun) | **Patch** /api/v2/dags/{dag_id}/dagRuns/{dag_run_id}/taskInstances/{task_id}/dry_run | Patch Task Instance Dry Run
[**PatchTaskInstanceDryRunByMapIndex**](TaskInstanceAPI.md#PatchTaskInstanceDryRunByMapIndex) | **Patch** /api/v2/dags/{dag_id}/dagRuns/{dag_run_id}/taskInstances/{task_id}/{map_index}/dry_run | Patch Task Instance Dry Run
[**PostClearTaskInstances**](TaskInstanceAPI.md#PostClearTaskInstances) | **Post** /api/v2/dags/{dag_id}/clearTaskInstances | Post Clear Task Instances



## BulkTaskInstances

> BulkResponse BulkTaskInstances(ctx, dagId, dagRunId).BulkBodyBulkTaskInstanceBody(bulkBodyBulkTaskInstanceBody).Execute()

Bulk Task Instances



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
	bulkBodyBulkTaskInstanceBody := *openapiclient.NewBulkBodyBulkTaskInstanceBody([]openapiclient.BulkBodyBulkTaskInstanceBodyActionsInner{openapiclient.BulkBody_BulkTaskInstanceBody__actions_inner{BulkCreateActionBulkTaskInstanceBody: openapiclient.NewBulkCreateActionBulkTaskInstanceBody("Action_example", []openapiclient.BulkTaskInstanceBody{*openapiclient.NewBulkTaskInstanceBody("TaskId_example")})}}) // BulkBodyBulkTaskInstanceBody | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TaskInstanceAPI.BulkTaskInstances(context.Background(), dagId, dagRunId).BulkBodyBulkTaskInstanceBody(bulkBodyBulkTaskInstanceBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TaskInstanceAPI.BulkTaskInstances``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `BulkTaskInstances`: BulkResponse
	fmt.Fprintf(os.Stdout, "Response from `TaskInstanceAPI.BulkTaskInstances`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**dagId** | **string** |  | 
**dagRunId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiBulkTaskInstancesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **bulkBodyBulkTaskInstanceBody** | [**BulkBodyBulkTaskInstanceBody**](BulkBodyBulkTaskInstanceBody.md) |  | 

### Return type

[**BulkResponse**](BulkResponse.md)

### Authorization

[OAuth2PasswordBearer](../README.md#OAuth2PasswordBearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteTaskInstance

> interface{} DeleteTaskInstance(ctx, dagId, dagRunId, taskId).MapIndex(mapIndex).Execute()

Delete Task Instance



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
	resp, r, err := apiClient.TaskInstanceAPI.DeleteTaskInstance(context.Background(), dagId, dagRunId, taskId).MapIndex(mapIndex).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TaskInstanceAPI.DeleteTaskInstance``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DeleteTaskInstance`: interface{}
	fmt.Fprintf(os.Stdout, "Response from `TaskInstanceAPI.DeleteTaskInstance`: %v\n", resp)
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

Other parameters are passed through a pointer to a apiDeleteTaskInstanceRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



 **mapIndex** | **int32** |  | [default to -1]

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


## GetExternalLogUrl

> ExternalLogUrlResponse GetExternalLogUrl(ctx, dagId, dagRunId, taskId, tryNumber).MapIndex(mapIndex).Execute()

Get External Log Url



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
	tryNumber := int32(56) // int32 | 
	mapIndex := int32(56) // int32 |  (optional) (default to -1)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TaskInstanceAPI.GetExternalLogUrl(context.Background(), dagId, dagRunId, taskId, tryNumber).MapIndex(mapIndex).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TaskInstanceAPI.GetExternalLogUrl``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetExternalLogUrl`: ExternalLogUrlResponse
	fmt.Fprintf(os.Stdout, "Response from `TaskInstanceAPI.GetExternalLogUrl`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**dagId** | **string** |  | 
**dagRunId** | **string** |  | 
**taskId** | **string** |  | 
**tryNumber** | **int32** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetExternalLogUrlRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------




 **mapIndex** | **int32** |  | [default to -1]

### Return type

[**ExternalLogUrlResponse**](ExternalLogUrlResponse.md)

### Authorization

[OAuth2PasswordBearer](../README.md#OAuth2PasswordBearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


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
	resp, r, err := apiClient.TaskInstanceAPI.GetExtraLinks(context.Background(), dagId, dagRunId, taskId).MapIndex(mapIndex).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TaskInstanceAPI.GetExtraLinks``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetExtraLinks`: ExtraLinkCollectionResponse
	fmt.Fprintf(os.Stdout, "Response from `TaskInstanceAPI.GetExtraLinks`: %v\n", resp)
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


## GetLog

> TaskInstancesLogResponse GetLog(ctx, dagId, dagRunId, taskId, tryNumber).FullContent(fullContent).MapIndex(mapIndex).Token(token).Accept(accept).Execute()

Get Log



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
	tryNumber := int32(56) // int32 | 
	fullContent := true // bool |  (optional) (default to false)
	mapIndex := int32(56) // int32 |  (optional) (default to -1)
	token := "token_example" // string |  (optional)
	accept := "accept_example" // string |  (optional) (default to "*_/_*")

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TaskInstanceAPI.GetLog(context.Background(), dagId, dagRunId, taskId, tryNumber).FullContent(fullContent).MapIndex(mapIndex).Token(token).Accept(accept).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TaskInstanceAPI.GetLog``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetLog`: TaskInstancesLogResponse
	fmt.Fprintf(os.Stdout, "Response from `TaskInstanceAPI.GetLog`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**dagId** | **string** |  | 
**dagRunId** | **string** |  | 
**taskId** | **string** |  | 
**tryNumber** | **int32** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetLogRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------




 **fullContent** | **bool** |  | [default to false]
 **mapIndex** | **int32** |  | [default to -1]
 **token** | **string** |  | 
 **accept** | **string** |  | [default to &quot;*_/_*&quot;]

### Return type

[**TaskInstancesLogResponse**](TaskInstancesLogResponse.md)

### Authorization

[OAuth2PasswordBearer](../README.md#OAuth2PasswordBearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json, application/x-ndjson

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetMappedTaskInstance

> TaskInstanceResponse GetMappedTaskInstance(ctx, dagId, dagRunId, taskId, mapIndex).Execute()

Get Mapped Task Instance



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
	mapIndex := int32(56) // int32 | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TaskInstanceAPI.GetMappedTaskInstance(context.Background(), dagId, dagRunId, taskId, mapIndex).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TaskInstanceAPI.GetMappedTaskInstance``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetMappedTaskInstance`: TaskInstanceResponse
	fmt.Fprintf(os.Stdout, "Response from `TaskInstanceAPI.GetMappedTaskInstance`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**dagId** | **string** |  | 
**dagRunId** | **string** |  | 
**taskId** | **string** |  | 
**mapIndex** | **int32** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetMappedTaskInstanceRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------





### Return type

[**TaskInstanceResponse**](TaskInstanceResponse.md)

### Authorization

[OAuth2PasswordBearer](../README.md#OAuth2PasswordBearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetMappedTaskInstanceTries

> TaskInstanceHistoryCollectionResponse GetMappedTaskInstanceTries(ctx, dagId, dagRunId, taskId, mapIndex).Execute()

Get Mapped Task Instance Tries

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
	mapIndex := int32(56) // int32 | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TaskInstanceAPI.GetMappedTaskInstanceTries(context.Background(), dagId, dagRunId, taskId, mapIndex).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TaskInstanceAPI.GetMappedTaskInstanceTries``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetMappedTaskInstanceTries`: TaskInstanceHistoryCollectionResponse
	fmt.Fprintf(os.Stdout, "Response from `TaskInstanceAPI.GetMappedTaskInstanceTries`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**dagId** | **string** |  | 
**dagRunId** | **string** |  | 
**taskId** | **string** |  | 
**mapIndex** | **int32** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetMappedTaskInstanceTriesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------





### Return type

[**TaskInstanceHistoryCollectionResponse**](TaskInstanceHistoryCollectionResponse.md)

### Authorization

[OAuth2PasswordBearer](../README.md#OAuth2PasswordBearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetMappedTaskInstanceTryDetails

> TaskInstanceHistoryResponse GetMappedTaskInstanceTryDetails(ctx, dagId, dagRunId, taskId, taskTryNumber, mapIndex).Execute()

Get Mapped Task Instance Try Details

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
	taskTryNumber := int32(56) // int32 | 
	mapIndex := int32(56) // int32 | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TaskInstanceAPI.GetMappedTaskInstanceTryDetails(context.Background(), dagId, dagRunId, taskId, taskTryNumber, mapIndex).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TaskInstanceAPI.GetMappedTaskInstanceTryDetails``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetMappedTaskInstanceTryDetails`: TaskInstanceHistoryResponse
	fmt.Fprintf(os.Stdout, "Response from `TaskInstanceAPI.GetMappedTaskInstanceTryDetails`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**dagId** | **string** |  | 
**dagRunId** | **string** |  | 
**taskId** | **string** |  | 
**taskTryNumber** | **int32** |  | 
**mapIndex** | **int32** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetMappedTaskInstanceTryDetailsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------






### Return type

[**TaskInstanceHistoryResponse**](TaskInstanceHistoryResponse.md)

### Authorization

[OAuth2PasswordBearer](../README.md#OAuth2PasswordBearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetMappedTaskInstances

> TaskInstanceCollectionResponse GetMappedTaskInstances(ctx, dagId, dagRunId, taskId).RunAfterGte(runAfterGte).RunAfterLte(runAfterLte).LogicalDateGte(logicalDateGte).LogicalDateLte(logicalDateLte).StartDateGte(startDateGte).StartDateLte(startDateLte).EndDateGte(endDateGte).EndDateLte(endDateLte).UpdatedAtGte(updatedAtGte).UpdatedAtLte(updatedAtLte).DurationGte(durationGte).DurationLte(durationLte).State(state).Pool(pool).Queue(queue).Executor(executor).VersionNumber(versionNumber).Limit(limit).Offset(offset).OrderBy(orderBy).Execute()

Get Mapped Task Instances



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
    "time"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	dagId := "dagId_example" // string | 
	dagRunId := "dagRunId_example" // string | 
	taskId := "taskId_example" // string | 
	runAfterGte := time.Now() // time.Time |  (optional)
	runAfterLte := time.Now() // time.Time |  (optional)
	logicalDateGte := time.Now() // time.Time |  (optional)
	logicalDateLte := time.Now() // time.Time |  (optional)
	startDateGte := time.Now() // time.Time |  (optional)
	startDateLte := time.Now() // time.Time |  (optional)
	endDateGte := time.Now() // time.Time |  (optional)
	endDateLte := time.Now() // time.Time |  (optional)
	updatedAtGte := time.Now() // time.Time |  (optional)
	updatedAtLte := time.Now() // time.Time |  (optional)
	durationGte := float32(8.14) // float32 |  (optional)
	durationLte := float32(8.14) // float32 |  (optional)
	state := []string{"Inner_example"} // []string |  (optional)
	pool := []*string{"Inner_example"} // []*string |  (optional)
	queue := []*string{"Inner_example"} // []*string |  (optional)
	executor := []*string{"Inner_example"} // []*string |  (optional)
	versionNumber := []*int32{int32(123)} // []*int32 |  (optional)
	limit := int32(56) // int32 |  (optional) (default to 50)
	offset := int32(56) // int32 |  (optional) (default to 0)
	orderBy := "orderBy_example" // string |  (optional) (default to "map_index")

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TaskInstanceAPI.GetMappedTaskInstances(context.Background(), dagId, dagRunId, taskId).RunAfterGte(runAfterGte).RunAfterLte(runAfterLte).LogicalDateGte(logicalDateGte).LogicalDateLte(logicalDateLte).StartDateGte(startDateGte).StartDateLte(startDateLte).EndDateGte(endDateGte).EndDateLte(endDateLte).UpdatedAtGte(updatedAtGte).UpdatedAtLte(updatedAtLte).DurationGte(durationGte).DurationLte(durationLte).State(state).Pool(pool).Queue(queue).Executor(executor).VersionNumber(versionNumber).Limit(limit).Offset(offset).OrderBy(orderBy).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TaskInstanceAPI.GetMappedTaskInstances``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetMappedTaskInstances`: TaskInstanceCollectionResponse
	fmt.Fprintf(os.Stdout, "Response from `TaskInstanceAPI.GetMappedTaskInstances`: %v\n", resp)
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

Other parameters are passed through a pointer to a apiGetMappedTaskInstancesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



 **runAfterGte** | **time.Time** |  | 
 **runAfterLte** | **time.Time** |  | 
 **logicalDateGte** | **time.Time** |  | 
 **logicalDateLte** | **time.Time** |  | 
 **startDateGte** | **time.Time** |  | 
 **startDateLte** | **time.Time** |  | 
 **endDateGte** | **time.Time** |  | 
 **endDateLte** | **time.Time** |  | 
 **updatedAtGte** | **time.Time** |  | 
 **updatedAtLte** | **time.Time** |  | 
 **durationGte** | **float32** |  | 
 **durationLte** | **float32** |  | 
 **state** | **[]string** |  | 
 **pool** | **[]string** |  | 
 **queue** | **[]string** |  | 
 **executor** | **[]string** |  | 
 **versionNumber** | **[]int32** |  | 
 **limit** | **int32** |  | [default to 50]
 **offset** | **int32** |  | [default to 0]
 **orderBy** | **string** |  | [default to &quot;map_index&quot;]

### Return type

[**TaskInstanceCollectionResponse**](TaskInstanceCollectionResponse.md)

### Authorization

[OAuth2PasswordBearer](../README.md#OAuth2PasswordBearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetTaskInstance

> TaskInstanceResponse GetTaskInstance(ctx, dagId, dagRunId, taskId).Execute()

Get Task Instance



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

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TaskInstanceAPI.GetTaskInstance(context.Background(), dagId, dagRunId, taskId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TaskInstanceAPI.GetTaskInstance``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetTaskInstance`: TaskInstanceResponse
	fmt.Fprintf(os.Stdout, "Response from `TaskInstanceAPI.GetTaskInstance`: %v\n", resp)
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

Other parameters are passed through a pointer to a apiGetTaskInstanceRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------




### Return type

[**TaskInstanceResponse**](TaskInstanceResponse.md)

### Authorization

[OAuth2PasswordBearer](../README.md#OAuth2PasswordBearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetTaskInstanceDependencies

> TaskDependencyCollectionResponse GetTaskInstanceDependencies(ctx, dagId, dagRunId, taskId).MapIndex(mapIndex).Execute()

Get Task Instance Dependencies



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
	resp, r, err := apiClient.TaskInstanceAPI.GetTaskInstanceDependencies(context.Background(), dagId, dagRunId, taskId).MapIndex(mapIndex).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TaskInstanceAPI.GetTaskInstanceDependencies``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetTaskInstanceDependencies`: TaskDependencyCollectionResponse
	fmt.Fprintf(os.Stdout, "Response from `TaskInstanceAPI.GetTaskInstanceDependencies`: %v\n", resp)
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

Other parameters are passed through a pointer to a apiGetTaskInstanceDependenciesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



 **mapIndex** | **int32** |  | [default to -1]

### Return type

[**TaskDependencyCollectionResponse**](TaskDependencyCollectionResponse.md)

### Authorization

[OAuth2PasswordBearer](../README.md#OAuth2PasswordBearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetTaskInstanceDependenciesByMapIndex

> TaskDependencyCollectionResponse GetTaskInstanceDependenciesByMapIndex(ctx, dagId, dagRunId, taskId, mapIndex).Execute()

Get Task Instance Dependencies



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
	mapIndex := int32(56) // int32 | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TaskInstanceAPI.GetTaskInstanceDependenciesByMapIndex(context.Background(), dagId, dagRunId, taskId, mapIndex).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TaskInstanceAPI.GetTaskInstanceDependenciesByMapIndex``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetTaskInstanceDependenciesByMapIndex`: TaskDependencyCollectionResponse
	fmt.Fprintf(os.Stdout, "Response from `TaskInstanceAPI.GetTaskInstanceDependenciesByMapIndex`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**dagId** | **string** |  | 
**dagRunId** | **string** |  | 
**taskId** | **string** |  | 
**mapIndex** | **int32** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetTaskInstanceDependenciesByMapIndexRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------





### Return type

[**TaskDependencyCollectionResponse**](TaskDependencyCollectionResponse.md)

### Authorization

[OAuth2PasswordBearer](../README.md#OAuth2PasswordBearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetTaskInstanceTries

> TaskInstanceHistoryCollectionResponse GetTaskInstanceTries(ctx, dagId, dagRunId, taskId).MapIndex(mapIndex).Execute()

Get Task Instance Tries



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
	resp, r, err := apiClient.TaskInstanceAPI.GetTaskInstanceTries(context.Background(), dagId, dagRunId, taskId).MapIndex(mapIndex).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TaskInstanceAPI.GetTaskInstanceTries``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetTaskInstanceTries`: TaskInstanceHistoryCollectionResponse
	fmt.Fprintf(os.Stdout, "Response from `TaskInstanceAPI.GetTaskInstanceTries`: %v\n", resp)
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

Other parameters are passed through a pointer to a apiGetTaskInstanceTriesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



 **mapIndex** | **int32** |  | [default to -1]

### Return type

[**TaskInstanceHistoryCollectionResponse**](TaskInstanceHistoryCollectionResponse.md)

### Authorization

[OAuth2PasswordBearer](../README.md#OAuth2PasswordBearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetTaskInstanceTryDetails

> TaskInstanceHistoryResponse GetTaskInstanceTryDetails(ctx, dagId, dagRunId, taskId, taskTryNumber).MapIndex(mapIndex).Execute()

Get Task Instance Try Details



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
	taskTryNumber := int32(56) // int32 | 
	mapIndex := int32(56) // int32 |  (optional) (default to -1)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TaskInstanceAPI.GetTaskInstanceTryDetails(context.Background(), dagId, dagRunId, taskId, taskTryNumber).MapIndex(mapIndex).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TaskInstanceAPI.GetTaskInstanceTryDetails``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetTaskInstanceTryDetails`: TaskInstanceHistoryResponse
	fmt.Fprintf(os.Stdout, "Response from `TaskInstanceAPI.GetTaskInstanceTryDetails`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**dagId** | **string** |  | 
**dagRunId** | **string** |  | 
**taskId** | **string** |  | 
**taskTryNumber** | **int32** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetTaskInstanceTryDetailsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------




 **mapIndex** | **int32** |  | [default to -1]

### Return type

[**TaskInstanceHistoryResponse**](TaskInstanceHistoryResponse.md)

### Authorization

[OAuth2PasswordBearer](../README.md#OAuth2PasswordBearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetTaskInstances

> TaskInstanceCollectionResponse GetTaskInstances(ctx, dagId, dagRunId).TaskId(taskId).RunAfterGte(runAfterGte).RunAfterLte(runAfterLte).LogicalDateGte(logicalDateGte).LogicalDateLte(logicalDateLte).StartDateGte(startDateGte).StartDateLte(startDateLte).EndDateGte(endDateGte).EndDateLte(endDateLte).UpdatedAtGte(updatedAtGte).UpdatedAtLte(updatedAtLte).DurationGte(durationGte).DurationLte(durationLte).TaskDisplayNamePattern(taskDisplayNamePattern).State(state).Pool(pool).Queue(queue).Executor(executor).VersionNumber(versionNumber).Limit(limit).Offset(offset).OrderBy(orderBy).Execute()

Get Task Instances



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
    "time"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	dagId := "dagId_example" // string | 
	dagRunId := "dagRunId_example" // string | 
	taskId := "taskId_example" // string |  (optional)
	runAfterGte := time.Now() // time.Time |  (optional)
	runAfterLte := time.Now() // time.Time |  (optional)
	logicalDateGte := time.Now() // time.Time |  (optional)
	logicalDateLte := time.Now() // time.Time |  (optional)
	startDateGte := time.Now() // time.Time |  (optional)
	startDateLte := time.Now() // time.Time |  (optional)
	endDateGte := time.Now() // time.Time |  (optional)
	endDateLte := time.Now() // time.Time |  (optional)
	updatedAtGte := time.Now() // time.Time |  (optional)
	updatedAtLte := time.Now() // time.Time |  (optional)
	durationGte := float32(8.14) // float32 |  (optional)
	durationLte := float32(8.14) // float32 |  (optional)
	taskDisplayNamePattern := "taskDisplayNamePattern_example" // string | SQL LIKE expression — use `%` / `_` wildcards (e.g. `%customer_%`). Regular expressions are **not** supported. (optional)
	state := []string{"Inner_example"} // []string |  (optional)
	pool := []string{"Inner_example"} // []string |  (optional)
	queue := []string{"Inner_example"} // []string |  (optional)
	executor := []string{"Inner_example"} // []string |  (optional)
	versionNumber := []int32{int32(123)} // []int32 |  (optional)
	limit := int32(56) // int32 |  (optional) (default to 50)
	offset := int32(56) // int32 |  (optional) (default to 0)
	orderBy := "orderBy_example" // string |  (optional) (default to "map_index")

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TaskInstanceAPI.GetTaskInstances(context.Background(), dagId, dagRunId).TaskId(taskId).RunAfterGte(runAfterGte).RunAfterLte(runAfterLte).LogicalDateGte(logicalDateGte).LogicalDateLte(logicalDateLte).StartDateGte(startDateGte).StartDateLte(startDateLte).EndDateGte(endDateGte).EndDateLte(endDateLte).UpdatedAtGte(updatedAtGte).UpdatedAtLte(updatedAtLte).DurationGte(durationGte).DurationLte(durationLte).TaskDisplayNamePattern(taskDisplayNamePattern).State(state).Pool(pool).Queue(queue).Executor(executor).VersionNumber(versionNumber).Limit(limit).Offset(offset).OrderBy(orderBy).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TaskInstanceAPI.GetTaskInstances``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetTaskInstances`: TaskInstanceCollectionResponse
	fmt.Fprintf(os.Stdout, "Response from `TaskInstanceAPI.GetTaskInstances`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**dagId** | **string** |  | 
**dagRunId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetTaskInstancesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **taskId** | **string** |  | 
 **runAfterGte** | **time.Time** |  | 
 **runAfterLte** | **time.Time** |  | 
 **logicalDateGte** | **time.Time** |  | 
 **logicalDateLte** | **time.Time** |  | 
 **startDateGte** | **time.Time** |  | 
 **startDateLte** | **time.Time** |  | 
 **endDateGte** | **time.Time** |  | 
 **endDateLte** | **time.Time** |  | 
 **updatedAtGte** | **time.Time** |  | 
 **updatedAtLte** | **time.Time** |  | 
 **durationGte** | **float32** |  | 
 **durationLte** | **float32** |  | 
 **taskDisplayNamePattern** | **string** | SQL LIKE expression — use &#x60;%&#x60; / &#x60;_&#x60; wildcards (e.g. &#x60;%customer_%&#x60;). Regular expressions are **not** supported. | 
 **state** | **[]string** |  | 
 **pool** | **[]string** |  | 
 **queue** | **[]string** |  | 
 **executor** | **[]string** |  | 
 **versionNumber** | **[]int32** |  | 
 **limit** | **int32** |  | [default to 50]
 **offset** | **int32** |  | [default to 0]
 **orderBy** | **string** |  | [default to &quot;map_index&quot;]

### Return type

[**TaskInstanceCollectionResponse**](TaskInstanceCollectionResponse.md)

### Authorization

[OAuth2PasswordBearer](../README.md#OAuth2PasswordBearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetTaskInstancesBatch

> TaskInstanceCollectionResponse GetTaskInstancesBatch(ctx, dagId, dagRunId).TaskInstancesBatchBody(taskInstancesBatchBody).Execute()

Get Task Instances Batch



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
	taskInstancesBatchBody := *openapiclient.NewTaskInstancesBatchBody() // TaskInstancesBatchBody | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TaskInstanceAPI.GetTaskInstancesBatch(context.Background(), dagId, dagRunId).TaskInstancesBatchBody(taskInstancesBatchBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TaskInstanceAPI.GetTaskInstancesBatch``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetTaskInstancesBatch`: TaskInstanceCollectionResponse
	fmt.Fprintf(os.Stdout, "Response from `TaskInstanceAPI.GetTaskInstancesBatch`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**dagId** | **string** |  | 
**dagRunId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetTaskInstancesBatchRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **taskInstancesBatchBody** | [**TaskInstancesBatchBody**](TaskInstancesBatchBody.md) |  | 

### Return type

[**TaskInstanceCollectionResponse**](TaskInstanceCollectionResponse.md)

### Authorization

[OAuth2PasswordBearer](../README.md#OAuth2PasswordBearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PatchTaskInstance

> TaskInstanceCollectionResponse PatchTaskInstance(ctx, dagId, dagRunId, taskId).PatchTaskInstanceBody(patchTaskInstanceBody).MapIndex(mapIndex).UpdateMask(updateMask).Execute()

Patch Task Instance



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
	patchTaskInstanceBody := *openapiclient.NewPatchTaskInstanceBody() // PatchTaskInstanceBody | 
	mapIndex := int32(56) // int32 |  (optional)
	updateMask := []string{"Inner_example"} // []string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TaskInstanceAPI.PatchTaskInstance(context.Background(), dagId, dagRunId, taskId).PatchTaskInstanceBody(patchTaskInstanceBody).MapIndex(mapIndex).UpdateMask(updateMask).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TaskInstanceAPI.PatchTaskInstance``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PatchTaskInstance`: TaskInstanceCollectionResponse
	fmt.Fprintf(os.Stdout, "Response from `TaskInstanceAPI.PatchTaskInstance`: %v\n", resp)
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

Other parameters are passed through a pointer to a apiPatchTaskInstanceRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



 **patchTaskInstanceBody** | [**PatchTaskInstanceBody**](PatchTaskInstanceBody.md) |  | 
 **mapIndex** | **int32** |  | 
 **updateMask** | **[]string** |  | 

### Return type

[**TaskInstanceCollectionResponse**](TaskInstanceCollectionResponse.md)

### Authorization

[OAuth2PasswordBearer](../README.md#OAuth2PasswordBearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PatchTaskInstanceByMapIndex

> TaskInstanceCollectionResponse PatchTaskInstanceByMapIndex(ctx, dagId, dagRunId, taskId, mapIndex).PatchTaskInstanceBody(patchTaskInstanceBody).UpdateMask(updateMask).Execute()

Patch Task Instance



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
	mapIndex := int32(56) // int32 | 
	patchTaskInstanceBody := *openapiclient.NewPatchTaskInstanceBody() // PatchTaskInstanceBody | 
	updateMask := []string{"Inner_example"} // []string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TaskInstanceAPI.PatchTaskInstanceByMapIndex(context.Background(), dagId, dagRunId, taskId, mapIndex).PatchTaskInstanceBody(patchTaskInstanceBody).UpdateMask(updateMask).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TaskInstanceAPI.PatchTaskInstanceByMapIndex``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PatchTaskInstanceByMapIndex`: TaskInstanceCollectionResponse
	fmt.Fprintf(os.Stdout, "Response from `TaskInstanceAPI.PatchTaskInstanceByMapIndex`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**dagId** | **string** |  | 
**dagRunId** | **string** |  | 
**taskId** | **string** |  | 
**mapIndex** | **int32** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiPatchTaskInstanceByMapIndexRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------




 **patchTaskInstanceBody** | [**PatchTaskInstanceBody**](PatchTaskInstanceBody.md) |  | 
 **updateMask** | **[]string** |  | 

### Return type

[**TaskInstanceCollectionResponse**](TaskInstanceCollectionResponse.md)

### Authorization

[OAuth2PasswordBearer](../README.md#OAuth2PasswordBearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PatchTaskInstanceDryRun

> TaskInstanceCollectionResponse PatchTaskInstanceDryRun(ctx, dagId, dagRunId, taskId).PatchTaskInstanceBody(patchTaskInstanceBody).MapIndex(mapIndex).UpdateMask(updateMask).Execute()

Patch Task Instance Dry Run



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
	patchTaskInstanceBody := *openapiclient.NewPatchTaskInstanceBody() // PatchTaskInstanceBody | 
	mapIndex := int32(56) // int32 |  (optional)
	updateMask := []string{"Inner_example"} // []string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TaskInstanceAPI.PatchTaskInstanceDryRun(context.Background(), dagId, dagRunId, taskId).PatchTaskInstanceBody(patchTaskInstanceBody).MapIndex(mapIndex).UpdateMask(updateMask).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TaskInstanceAPI.PatchTaskInstanceDryRun``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PatchTaskInstanceDryRun`: TaskInstanceCollectionResponse
	fmt.Fprintf(os.Stdout, "Response from `TaskInstanceAPI.PatchTaskInstanceDryRun`: %v\n", resp)
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

Other parameters are passed through a pointer to a apiPatchTaskInstanceDryRunRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



 **patchTaskInstanceBody** | [**PatchTaskInstanceBody**](PatchTaskInstanceBody.md) |  | 
 **mapIndex** | **int32** |  | 
 **updateMask** | **[]string** |  | 

### Return type

[**TaskInstanceCollectionResponse**](TaskInstanceCollectionResponse.md)

### Authorization

[OAuth2PasswordBearer](../README.md#OAuth2PasswordBearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PatchTaskInstanceDryRunByMapIndex

> TaskInstanceCollectionResponse PatchTaskInstanceDryRunByMapIndex(ctx, dagId, dagRunId, taskId, mapIndex).PatchTaskInstanceBody(patchTaskInstanceBody).UpdateMask(updateMask).Execute()

Patch Task Instance Dry Run



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
	mapIndex := int32(56) // int32 | 
	patchTaskInstanceBody := *openapiclient.NewPatchTaskInstanceBody() // PatchTaskInstanceBody | 
	updateMask := []string{"Inner_example"} // []string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TaskInstanceAPI.PatchTaskInstanceDryRunByMapIndex(context.Background(), dagId, dagRunId, taskId, mapIndex).PatchTaskInstanceBody(patchTaskInstanceBody).UpdateMask(updateMask).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TaskInstanceAPI.PatchTaskInstanceDryRunByMapIndex``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PatchTaskInstanceDryRunByMapIndex`: TaskInstanceCollectionResponse
	fmt.Fprintf(os.Stdout, "Response from `TaskInstanceAPI.PatchTaskInstanceDryRunByMapIndex`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**dagId** | **string** |  | 
**dagRunId** | **string** |  | 
**taskId** | **string** |  | 
**mapIndex** | **int32** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiPatchTaskInstanceDryRunByMapIndexRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------




 **patchTaskInstanceBody** | [**PatchTaskInstanceBody**](PatchTaskInstanceBody.md) |  | 
 **updateMask** | **[]string** |  | 

### Return type

[**TaskInstanceCollectionResponse**](TaskInstanceCollectionResponse.md)

### Authorization

[OAuth2PasswordBearer](../README.md#OAuth2PasswordBearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PostClearTaskInstances

> TaskInstanceCollectionResponse PostClearTaskInstances(ctx, dagId).ClearTaskInstancesBody(clearTaskInstancesBody).Execute()

Post Clear Task Instances



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
	clearTaskInstancesBody := *openapiclient.NewClearTaskInstancesBody() // ClearTaskInstancesBody | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TaskInstanceAPI.PostClearTaskInstances(context.Background(), dagId).ClearTaskInstancesBody(clearTaskInstancesBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TaskInstanceAPI.PostClearTaskInstances``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PostClearTaskInstances`: TaskInstanceCollectionResponse
	fmt.Fprintf(os.Stdout, "Response from `TaskInstanceAPI.PostClearTaskInstances`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**dagId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiPostClearTaskInstancesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **clearTaskInstancesBody** | [**ClearTaskInstancesBody**](ClearTaskInstancesBody.md) |  | 

### Return type

[**TaskInstanceCollectionResponse**](TaskInstanceCollectionResponse.md)

### Authorization

[OAuth2PasswordBearer](../README.md#OAuth2PasswordBearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

