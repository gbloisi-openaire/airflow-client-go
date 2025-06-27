# \BackfillAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CancelBackfill**](BackfillAPI.md#CancelBackfill) | **Put** /api/v2/backfills/{backfill_id}/cancel | Cancel Backfill
[**CreateBackfill**](BackfillAPI.md#CreateBackfill) | **Post** /api/v2/backfills | Create Backfill
[**CreateBackfillDryRun**](BackfillAPI.md#CreateBackfillDryRun) | **Post** /api/v2/backfills/dry_run | Create Backfill Dry Run
[**GetBackfill**](BackfillAPI.md#GetBackfill) | **Get** /api/v2/backfills/{backfill_id} | Get Backfill
[**ListBackfills**](BackfillAPI.md#ListBackfills) | **Get** /api/v2/backfills | List Backfills
[**PauseBackfill**](BackfillAPI.md#PauseBackfill) | **Put** /api/v2/backfills/{backfill_id}/pause | Pause Backfill
[**UnpauseBackfill**](BackfillAPI.md#UnpauseBackfill) | **Put** /api/v2/backfills/{backfill_id}/unpause | Unpause Backfill



## CancelBackfill

> BackfillResponse CancelBackfill(ctx, backfillId).Execute()

Cancel Backfill

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
	backfillId := int32(56) // int32 | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.BackfillAPI.CancelBackfill(context.Background(), backfillId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BackfillAPI.CancelBackfill``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CancelBackfill`: BackfillResponse
	fmt.Fprintf(os.Stdout, "Response from `BackfillAPI.CancelBackfill`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**backfillId** | **int32** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiCancelBackfillRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**BackfillResponse**](BackfillResponse.md)

### Authorization

[OAuth2PasswordBearer](../README.md#OAuth2PasswordBearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CreateBackfill

> BackfillResponse CreateBackfill(ctx).BackfillPostBody(backfillPostBody).Execute()

Create Backfill

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
	backfillPostBody := *openapiclient.NewBackfillPostBody("DagId_example", time.Now(), time.Now()) // BackfillPostBody | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.BackfillAPI.CreateBackfill(context.Background()).BackfillPostBody(backfillPostBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BackfillAPI.CreateBackfill``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateBackfill`: BackfillResponse
	fmt.Fprintf(os.Stdout, "Response from `BackfillAPI.CreateBackfill`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateBackfillRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **backfillPostBody** | [**BackfillPostBody**](BackfillPostBody.md) |  | 

### Return type

[**BackfillResponse**](BackfillResponse.md)

### Authorization

[OAuth2PasswordBearer](../README.md#OAuth2PasswordBearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CreateBackfillDryRun

> DryRunBackfillCollectionResponse CreateBackfillDryRun(ctx).BackfillPostBody(backfillPostBody).Execute()

Create Backfill Dry Run

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
	backfillPostBody := *openapiclient.NewBackfillPostBody("DagId_example", time.Now(), time.Now()) // BackfillPostBody | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.BackfillAPI.CreateBackfillDryRun(context.Background()).BackfillPostBody(backfillPostBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BackfillAPI.CreateBackfillDryRun``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateBackfillDryRun`: DryRunBackfillCollectionResponse
	fmt.Fprintf(os.Stdout, "Response from `BackfillAPI.CreateBackfillDryRun`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateBackfillDryRunRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **backfillPostBody** | [**BackfillPostBody**](BackfillPostBody.md) |  | 

### Return type

[**DryRunBackfillCollectionResponse**](DryRunBackfillCollectionResponse.md)

### Authorization

[OAuth2PasswordBearer](../README.md#OAuth2PasswordBearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetBackfill

> BackfillResponse GetBackfill(ctx, backfillId).Execute()

Get Backfill

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
	backfillId := int32(56) // int32 | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.BackfillAPI.GetBackfill(context.Background(), backfillId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BackfillAPI.GetBackfill``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetBackfill`: BackfillResponse
	fmt.Fprintf(os.Stdout, "Response from `BackfillAPI.GetBackfill`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**backfillId** | **int32** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetBackfillRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**BackfillResponse**](BackfillResponse.md)

### Authorization

[OAuth2PasswordBearer](../README.md#OAuth2PasswordBearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListBackfills

> BackfillCollectionResponse ListBackfills(ctx).DagId(dagId).Limit(limit).Offset(offset).OrderBy(orderBy).Execute()

List Backfills

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
	limit := int32(56) // int32 |  (optional) (default to 50)
	offset := int32(56) // int32 |  (optional) (default to 0)
	orderBy := "orderBy_example" // string |  (optional) (default to "id")

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.BackfillAPI.ListBackfills(context.Background()).DagId(dagId).Limit(limit).Offset(offset).OrderBy(orderBy).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BackfillAPI.ListBackfills``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListBackfills`: BackfillCollectionResponse
	fmt.Fprintf(os.Stdout, "Response from `BackfillAPI.ListBackfills`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListBackfillsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **dagId** | **string** |  | 
 **limit** | **int32** |  | [default to 50]
 **offset** | **int32** |  | [default to 0]
 **orderBy** | **string** |  | [default to &quot;id&quot;]

### Return type

[**BackfillCollectionResponse**](BackfillCollectionResponse.md)

### Authorization

[OAuth2PasswordBearer](../README.md#OAuth2PasswordBearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PauseBackfill

> BackfillResponse PauseBackfill(ctx, backfillId).Execute()

Pause Backfill

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
	backfillId := int32(56) // int32 | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.BackfillAPI.PauseBackfill(context.Background(), backfillId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BackfillAPI.PauseBackfill``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PauseBackfill`: BackfillResponse
	fmt.Fprintf(os.Stdout, "Response from `BackfillAPI.PauseBackfill`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**backfillId** | **int32** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiPauseBackfillRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**BackfillResponse**](BackfillResponse.md)

### Authorization

[OAuth2PasswordBearer](../README.md#OAuth2PasswordBearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UnpauseBackfill

> BackfillResponse UnpauseBackfill(ctx, backfillId).Execute()

Unpause Backfill

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
	backfillId := int32(56) // int32 | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.BackfillAPI.UnpauseBackfill(context.Background(), backfillId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BackfillAPI.UnpauseBackfill``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UnpauseBackfill`: BackfillResponse
	fmt.Fprintf(os.Stdout, "Response from `BackfillAPI.UnpauseBackfill`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**backfillId** | **int32** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiUnpauseBackfillRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**BackfillResponse**](BackfillResponse.md)

### Authorization

[OAuth2PasswordBearer](../README.md#OAuth2PasswordBearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

