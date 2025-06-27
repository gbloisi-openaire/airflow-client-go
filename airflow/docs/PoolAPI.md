# \PoolAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**BulkPools**](PoolAPI.md#BulkPools) | **Patch** /api/v2/pools | Bulk Pools
[**DeletePool**](PoolAPI.md#DeletePool) | **Delete** /api/v2/pools/{pool_name} | Delete Pool
[**GetPool**](PoolAPI.md#GetPool) | **Get** /api/v2/pools/{pool_name} | Get Pool
[**GetPools**](PoolAPI.md#GetPools) | **Get** /api/v2/pools | Get Pools
[**PatchPool**](PoolAPI.md#PatchPool) | **Patch** /api/v2/pools/{pool_name} | Patch Pool
[**PostPool**](PoolAPI.md#PostPool) | **Post** /api/v2/pools | Post Pool



## BulkPools

> BulkResponse BulkPools(ctx).BulkBodyPoolBody(bulkBodyPoolBody).Execute()

Bulk Pools



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
	bulkBodyPoolBody := *openapiclient.NewBulkBodyPoolBody([]openapiclient.BulkBodyPoolBodyActionsInner{openapiclient.BulkBody_PoolBody__actions_inner{BulkCreateActionPoolBody: openapiclient.NewBulkCreateActionPoolBody("Action_example", []openapiclient.PoolBody{*openapiclient.NewPoolBody("Name_example", int32(123))})}}) // BulkBodyPoolBody | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PoolAPI.BulkPools(context.Background()).BulkBodyPoolBody(bulkBodyPoolBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PoolAPI.BulkPools``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `BulkPools`: BulkResponse
	fmt.Fprintf(os.Stdout, "Response from `PoolAPI.BulkPools`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiBulkPoolsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **bulkBodyPoolBody** | [**BulkBodyPoolBody**](BulkBodyPoolBody.md) |  | 

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


## DeletePool

> DeletePool(ctx, poolName).Execute()

Delete Pool



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
	poolName := "poolName_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.PoolAPI.DeletePool(context.Background(), poolName).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PoolAPI.DeletePool``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**poolName** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeletePoolRequest struct via the builder pattern


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


## GetPool

> PoolResponse GetPool(ctx, poolName).Execute()

Get Pool



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
	poolName := "poolName_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PoolAPI.GetPool(context.Background(), poolName).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PoolAPI.GetPool``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetPool`: PoolResponse
	fmt.Fprintf(os.Stdout, "Response from `PoolAPI.GetPool`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**poolName** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetPoolRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**PoolResponse**](PoolResponse.md)

### Authorization

[OAuth2PasswordBearer](../README.md#OAuth2PasswordBearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetPools

> PoolCollectionResponse GetPools(ctx).Limit(limit).Offset(offset).OrderBy(orderBy).PoolNamePattern(poolNamePattern).Execute()

Get Pools



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
	limit := int32(56) // int32 |  (optional) (default to 50)
	offset := int32(56) // int32 |  (optional) (default to 0)
	orderBy := "orderBy_example" // string |  (optional) (default to "id")
	poolNamePattern := "poolNamePattern_example" // string | SQL LIKE expression — use `%` / `_` wildcards (e.g. `%customer_%`). Regular expressions are **not** supported. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PoolAPI.GetPools(context.Background()).Limit(limit).Offset(offset).OrderBy(orderBy).PoolNamePattern(poolNamePattern).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PoolAPI.GetPools``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetPools`: PoolCollectionResponse
	fmt.Fprintf(os.Stdout, "Response from `PoolAPI.GetPools`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetPoolsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **limit** | **int32** |  | [default to 50]
 **offset** | **int32** |  | [default to 0]
 **orderBy** | **string** |  | [default to &quot;id&quot;]
 **poolNamePattern** | **string** | SQL LIKE expression — use &#x60;%&#x60; / &#x60;_&#x60; wildcards (e.g. &#x60;%customer_%&#x60;). Regular expressions are **not** supported. | 

### Return type

[**PoolCollectionResponse**](PoolCollectionResponse.md)

### Authorization

[OAuth2PasswordBearer](../README.md#OAuth2PasswordBearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PatchPool

> PoolResponse PatchPool(ctx, poolName).PoolPatchBody(poolPatchBody).UpdateMask(updateMask).Execute()

Patch Pool



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
	poolName := "poolName_example" // string | 
	poolPatchBody := *openapiclient.NewPoolPatchBody() // PoolPatchBody | 
	updateMask := []string{"Inner_example"} // []string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PoolAPI.PatchPool(context.Background(), poolName).PoolPatchBody(poolPatchBody).UpdateMask(updateMask).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PoolAPI.PatchPool``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PatchPool`: PoolResponse
	fmt.Fprintf(os.Stdout, "Response from `PoolAPI.PatchPool`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**poolName** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiPatchPoolRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **poolPatchBody** | [**PoolPatchBody**](PoolPatchBody.md) |  | 
 **updateMask** | **[]string** |  | 

### Return type

[**PoolResponse**](PoolResponse.md)

### Authorization

[OAuth2PasswordBearer](../README.md#OAuth2PasswordBearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PostPool

> PoolResponse PostPool(ctx).PoolBody(poolBody).Execute()

Post Pool



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
	poolBody := *openapiclient.NewPoolBody("Name_example", int32(123)) // PoolBody | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PoolAPI.PostPool(context.Background()).PoolBody(poolBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PoolAPI.PostPool``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PostPool`: PoolResponse
	fmt.Fprintf(os.Stdout, "Response from `PoolAPI.PostPool`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiPostPoolRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **poolBody** | [**PoolBody**](PoolBody.md) |  | 

### Return type

[**PoolResponse**](PoolResponse.md)

### Authorization

[OAuth2PasswordBearer](../README.md#OAuth2PasswordBearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

