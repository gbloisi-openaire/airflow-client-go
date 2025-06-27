# \EventLogAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetEventLog**](EventLogAPI.md#GetEventLog) | **Get** /api/v2/eventLogs/{event_log_id} | Get Event Log
[**GetEventLogs**](EventLogAPI.md#GetEventLogs) | **Get** /api/v2/eventLogs | Get Event Logs



## GetEventLog

> EventLogResponse GetEventLog(ctx, eventLogId).Execute()

Get Event Log

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
	eventLogId := int32(56) // int32 | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.EventLogAPI.GetEventLog(context.Background(), eventLogId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EventLogAPI.GetEventLog``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetEventLog`: EventLogResponse
	fmt.Fprintf(os.Stdout, "Response from `EventLogAPI.GetEventLog`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**eventLogId** | **int32** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetEventLogRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**EventLogResponse**](EventLogResponse.md)

### Authorization

[OAuth2PasswordBearer](../README.md#OAuth2PasswordBearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetEventLogs

> EventLogCollectionResponse GetEventLogs(ctx).Limit(limit).Offset(offset).OrderBy(orderBy).DagId(dagId).TaskId(taskId).RunId(runId).MapIndex(mapIndex).TryNumber(tryNumber).Owner(owner).Event(event).ExcludedEvents(excludedEvents).IncludedEvents(includedEvents).Before(before).After(after).Execute()

Get Event Logs



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
    "time"
	openapiclient "github.com/gbloisi-openaire/airflow-client-go/airflow"
)

func main() {
	limit := int32(56) // int32 |  (optional) (default to 50)
	offset := int32(56) // int32 |  (optional) (default to 0)
	orderBy := "orderBy_example" // string |  (optional) (default to "id")
	dagId := "dagId_example" // string |  (optional)
	taskId := "taskId_example" // string |  (optional)
	runId := "runId_example" // string |  (optional)
	mapIndex := int32(56) // int32 |  (optional)
	tryNumber := int32(56) // int32 |  (optional)
	owner := "owner_example" // string |  (optional)
	event := "event_example" // string |  (optional)
	excludedEvents := []string{"Inner_example"} // []string |  (optional)
	includedEvents := []string{"Inner_example"} // []string |  (optional)
	before := time.Now() // time.Time |  (optional)
	after := time.Now() // time.Time |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.EventLogAPI.GetEventLogs(context.Background()).Limit(limit).Offset(offset).OrderBy(orderBy).DagId(dagId).TaskId(taskId).RunId(runId).MapIndex(mapIndex).TryNumber(tryNumber).Owner(owner).Event(event).ExcludedEvents(excludedEvents).IncludedEvents(includedEvents).Before(before).After(after).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EventLogAPI.GetEventLogs``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetEventLogs`: EventLogCollectionResponse
	fmt.Fprintf(os.Stdout, "Response from `EventLogAPI.GetEventLogs`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetEventLogsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **limit** | **int32** |  | [default to 50]
 **offset** | **int32** |  | [default to 0]
 **orderBy** | **string** |  | [default to &quot;id&quot;]
 **dagId** | **string** |  | 
 **taskId** | **string** |  | 
 **runId** | **string** |  | 
 **mapIndex** | **int32** |  | 
 **tryNumber** | **int32** |  | 
 **owner** | **string** |  | 
 **event** | **string** |  | 
 **excludedEvents** | **[]string** |  | 
 **includedEvents** | **[]string** |  | 
 **before** | **time.Time** |  | 
 **after** | **time.Time** |  | 

### Return type

[**EventLogCollectionResponse**](EventLogCollectionResponse.md)

### Authorization

[OAuth2PasswordBearer](../README.md#OAuth2PasswordBearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

