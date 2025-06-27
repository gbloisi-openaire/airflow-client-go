# \DagRunAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ClearDagRun**](DagRunAPI.md#ClearDagRun) | **Post** /api/v2/dags/{dag_id}/dagRuns/{dag_run_id}/clear | Clear Dag Run
[**DeleteDagRun**](DagRunAPI.md#DeleteDagRun) | **Delete** /api/v2/dags/{dag_id}/dagRuns/{dag_run_id} | Delete Dag Run
[**GetDagRun**](DagRunAPI.md#GetDagRun) | **Get** /api/v2/dags/{dag_id}/dagRuns/{dag_run_id} | Get Dag Run
[**GetDagRuns**](DagRunAPI.md#GetDagRuns) | **Get** /api/v2/dags/{dag_id}/dagRuns | Get Dag Runs
[**GetListDagRunsBatch**](DagRunAPI.md#GetListDagRunsBatch) | **Post** /api/v2/dags/{dag_id}/dagRuns/list | Get List Dag Runs Batch
[**GetUpstreamAssetEvents**](DagRunAPI.md#GetUpstreamAssetEvents) | **Get** /api/v2/dags/{dag_id}/dagRuns/{dag_run_id}/upstreamAssetEvents | Get Upstream Asset Events
[**PatchDagRun**](DagRunAPI.md#PatchDagRun) | **Patch** /api/v2/dags/{dag_id}/dagRuns/{dag_run_id} | Patch Dag Run
[**TriggerDagRun**](DagRunAPI.md#TriggerDagRun) | **Post** /api/v2/dags/{dag_id}/dagRuns | Trigger Dag Run



## ClearDagRun

> ResponseClearDagRun ClearDagRun(ctx, dagId, dagRunId).DAGRunClearBody(dAGRunClearBody).Execute()

Clear Dag Run

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
	dAGRunClearBody := *openapiclient.NewDAGRunClearBody() // DAGRunClearBody | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DagRunAPI.ClearDagRun(context.Background(), dagId, dagRunId).DAGRunClearBody(dAGRunClearBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DagRunAPI.ClearDagRun``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ClearDagRun`: ResponseClearDagRun
	fmt.Fprintf(os.Stdout, "Response from `DagRunAPI.ClearDagRun`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**dagId** | **string** |  | 
**dagRunId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiClearDagRunRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **dAGRunClearBody** | [**DAGRunClearBody**](DAGRunClearBody.md) |  | 

### Return type

[**ResponseClearDagRun**](ResponseClearDagRun.md)

### Authorization

[OAuth2PasswordBearer](../README.md#OAuth2PasswordBearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteDagRun

> DeleteDagRun(ctx, dagId, dagRunId).Execute()

Delete Dag Run



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

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.DagRunAPI.DeleteDagRun(context.Background(), dagId, dagRunId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DagRunAPI.DeleteDagRun``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**dagId** | **string** |  | 
**dagRunId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteDagRunRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

 (empty response body)

### Authorization

[OAuth2PasswordBearer](../README.md#OAuth2PasswordBearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetDagRun

> DAGRunResponse GetDagRun(ctx, dagId, dagRunId).Execute()

Get Dag Run

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

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DagRunAPI.GetDagRun(context.Background(), dagId, dagRunId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DagRunAPI.GetDagRun``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetDagRun`: DAGRunResponse
	fmt.Fprintf(os.Stdout, "Response from `DagRunAPI.GetDagRun`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**dagId** | **string** |  | 
**dagRunId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetDagRunRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**DAGRunResponse**](DAGRunResponse.md)

### Authorization

[OAuth2PasswordBearer](../README.md#OAuth2PasswordBearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetDagRuns

> DAGRunCollectionResponse GetDagRuns(ctx, dagId).Limit(limit).Offset(offset).RunAfterGte(runAfterGte).RunAfterLte(runAfterLte).LogicalDateGte(logicalDateGte).LogicalDateLte(logicalDateLte).StartDateGte(startDateGte).StartDateLte(startDateLte).EndDateGte(endDateGte).EndDateLte(endDateLte).UpdatedAtGte(updatedAtGte).UpdatedAtLte(updatedAtLte).RunType(runType).State(state).OrderBy(orderBy).Execute()

Get Dag Runs



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
	limit := int32(56) // int32 |  (optional) (default to 50)
	offset := int32(56) // int32 |  (optional) (default to 0)
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
	runType := []*string{"Inner_example"} // []*string |  (optional)
	state := []*string{"Inner_example"} // []*string |  (optional)
	orderBy := "orderBy_example" // string |  (optional) (default to "id")

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DagRunAPI.GetDagRuns(context.Background(), dagId).Limit(limit).Offset(offset).RunAfterGte(runAfterGte).RunAfterLte(runAfterLte).LogicalDateGte(logicalDateGte).LogicalDateLte(logicalDateLte).StartDateGte(startDateGte).StartDateLte(startDateLte).EndDateGte(endDateGte).EndDateLte(endDateLte).UpdatedAtGte(updatedAtGte).UpdatedAtLte(updatedAtLte).RunType(runType).State(state).OrderBy(orderBy).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DagRunAPI.GetDagRuns``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetDagRuns`: DAGRunCollectionResponse
	fmt.Fprintf(os.Stdout, "Response from `DagRunAPI.GetDagRuns`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**dagId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetDagRunsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **limit** | **int32** |  | [default to 50]
 **offset** | **int32** |  | [default to 0]
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
 **runType** | **[]string** |  | 
 **state** | **[]string** |  | 
 **orderBy** | **string** |  | [default to &quot;id&quot;]

### Return type

[**DAGRunCollectionResponse**](DAGRunCollectionResponse.md)

### Authorization

[OAuth2PasswordBearer](../README.md#OAuth2PasswordBearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetListDagRunsBatch

> DAGRunCollectionResponse GetListDagRunsBatch(ctx, dagId).DAGRunsBatchBody(dAGRunsBatchBody).Execute()

Get List Dag Runs Batch



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
	dAGRunsBatchBody := *openapiclient.NewDAGRunsBatchBody() // DAGRunsBatchBody | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DagRunAPI.GetListDagRunsBatch(context.Background(), dagId).DAGRunsBatchBody(dAGRunsBatchBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DagRunAPI.GetListDagRunsBatch``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetListDagRunsBatch`: DAGRunCollectionResponse
	fmt.Fprintf(os.Stdout, "Response from `DagRunAPI.GetListDagRunsBatch`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**dagId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetListDagRunsBatchRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **dAGRunsBatchBody** | [**DAGRunsBatchBody**](DAGRunsBatchBody.md) |  | 

### Return type

[**DAGRunCollectionResponse**](DAGRunCollectionResponse.md)

### Authorization

[OAuth2PasswordBearer](../README.md#OAuth2PasswordBearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetUpstreamAssetEvents

> AssetEventCollectionResponse GetUpstreamAssetEvents(ctx, dagId, dagRunId).Execute()

Get Upstream Asset Events



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

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DagRunAPI.GetUpstreamAssetEvents(context.Background(), dagId, dagRunId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DagRunAPI.GetUpstreamAssetEvents``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetUpstreamAssetEvents`: AssetEventCollectionResponse
	fmt.Fprintf(os.Stdout, "Response from `DagRunAPI.GetUpstreamAssetEvents`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**dagId** | **string** |  | 
**dagRunId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetUpstreamAssetEventsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**AssetEventCollectionResponse**](AssetEventCollectionResponse.md)

### Authorization

[OAuth2PasswordBearer](../README.md#OAuth2PasswordBearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PatchDagRun

> DAGRunResponse PatchDagRun(ctx, dagId, dagRunId).DAGRunPatchBody(dAGRunPatchBody).UpdateMask(updateMask).Execute()

Patch Dag Run



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
	dAGRunPatchBody := *openapiclient.NewDAGRunPatchBody() // DAGRunPatchBody | 
	updateMask := []string{"Inner_example"} // []string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DagRunAPI.PatchDagRun(context.Background(), dagId, dagRunId).DAGRunPatchBody(dAGRunPatchBody).UpdateMask(updateMask).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DagRunAPI.PatchDagRun``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PatchDagRun`: DAGRunResponse
	fmt.Fprintf(os.Stdout, "Response from `DagRunAPI.PatchDagRun`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**dagId** | **string** |  | 
**dagRunId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiPatchDagRunRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **dAGRunPatchBody** | [**DAGRunPatchBody**](DAGRunPatchBody.md) |  | 
 **updateMask** | **[]string** |  | 

### Return type

[**DAGRunResponse**](DAGRunResponse.md)

### Authorization

[OAuth2PasswordBearer](../README.md#OAuth2PasswordBearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## TriggerDagRun

> DAGRunResponse TriggerDagRun(ctx, dagId).TriggerDAGRunPostBody(triggerDAGRunPostBody).Execute()

Trigger Dag Run



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
	dagId := TODO // interface{} | 
	triggerDAGRunPostBody := *openapiclient.NewTriggerDAGRunPostBody("TODO") // TriggerDAGRunPostBody | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DagRunAPI.TriggerDagRun(context.Background(), dagId).TriggerDAGRunPostBody(triggerDAGRunPostBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DagRunAPI.TriggerDagRun``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `TriggerDagRun`: DAGRunResponse
	fmt.Fprintf(os.Stdout, "Response from `DagRunAPI.TriggerDagRun`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**dagId** | [**interface{}**](.md) |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiTriggerDagRunRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **triggerDAGRunPostBody** | [**TriggerDAGRunPostBody**](TriggerDAGRunPostBody.md) |  | 

### Return type

[**DAGRunResponse**](DAGRunResponse.md)

### Authorization

[OAuth2PasswordBearer](../README.md#OAuth2PasswordBearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

