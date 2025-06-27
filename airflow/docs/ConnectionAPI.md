# \ConnectionAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**BulkConnections**](ConnectionAPI.md#BulkConnections) | **Patch** /api/v2/connections | Bulk Connections
[**CreateDefaultConnections**](ConnectionAPI.md#CreateDefaultConnections) | **Post** /api/v2/connections/defaults | Create Default Connections
[**DeleteConnection**](ConnectionAPI.md#DeleteConnection) | **Delete** /api/v2/connections/{connection_id} | Delete Connection
[**GetConnection**](ConnectionAPI.md#GetConnection) | **Get** /api/v2/connections/{connection_id} | Get Connection
[**GetConnections**](ConnectionAPI.md#GetConnections) | **Get** /api/v2/connections | Get Connections
[**PatchConnection**](ConnectionAPI.md#PatchConnection) | **Patch** /api/v2/connections/{connection_id} | Patch Connection
[**PostConnection**](ConnectionAPI.md#PostConnection) | **Post** /api/v2/connections | Post Connection
[**TestConnection**](ConnectionAPI.md#TestConnection) | **Post** /api/v2/connections/test | Test Connection



## BulkConnections

> BulkResponse BulkConnections(ctx).BulkBodyConnectionBody(bulkBodyConnectionBody).Execute()

Bulk Connections



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
	bulkBodyConnectionBody := *openapiclient.NewBulkBodyConnectionBody([]openapiclient.BulkBodyConnectionBodyActionsInner{openapiclient.BulkBody_ConnectionBody__actions_inner{BulkCreateActionConnectionBody: openapiclient.NewBulkCreateActionConnectionBody("Action_example", []openapiclient.ConnectionBody{*openapiclient.NewConnectionBody("ConnectionId_example", "ConnType_example")})}}) // BulkBodyConnectionBody | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ConnectionAPI.BulkConnections(context.Background()).BulkBodyConnectionBody(bulkBodyConnectionBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConnectionAPI.BulkConnections``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `BulkConnections`: BulkResponse
	fmt.Fprintf(os.Stdout, "Response from `ConnectionAPI.BulkConnections`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiBulkConnectionsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **bulkBodyConnectionBody** | [**BulkBodyConnectionBody**](BulkBodyConnectionBody.md) |  | 

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


## CreateDefaultConnections

> CreateDefaultConnections(ctx).Execute()

Create Default Connections



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

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.ConnectionAPI.CreateDefaultConnections(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConnectionAPI.CreateDefaultConnections``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiCreateDefaultConnectionsRequest struct via the builder pattern


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


## DeleteConnection

> DeleteConnection(ctx, connectionId).Execute()

Delete Connection



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
	connectionId := "connectionId_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.ConnectionAPI.DeleteConnection(context.Background(), connectionId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConnectionAPI.DeleteConnection``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**connectionId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteConnectionRequest struct via the builder pattern


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


## GetConnection

> ConnectionResponse GetConnection(ctx, connectionId).Execute()

Get Connection



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
	connectionId := "connectionId_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ConnectionAPI.GetConnection(context.Background(), connectionId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConnectionAPI.GetConnection``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetConnection`: ConnectionResponse
	fmt.Fprintf(os.Stdout, "Response from `ConnectionAPI.GetConnection`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**connectionId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetConnectionRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**ConnectionResponse**](ConnectionResponse.md)

### Authorization

[OAuth2PasswordBearer](../README.md#OAuth2PasswordBearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetConnections

> ConnectionCollectionResponse GetConnections(ctx).Limit(limit).Offset(offset).OrderBy(orderBy).ConnectionIdPattern(connectionIdPattern).Execute()

Get Connections



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
	connectionIdPattern := "connectionIdPattern_example" // string | SQL LIKE expression — use `%` / `_` wildcards (e.g. `%customer_%`). Regular expressions are **not** supported. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ConnectionAPI.GetConnections(context.Background()).Limit(limit).Offset(offset).OrderBy(orderBy).ConnectionIdPattern(connectionIdPattern).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConnectionAPI.GetConnections``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetConnections`: ConnectionCollectionResponse
	fmt.Fprintf(os.Stdout, "Response from `ConnectionAPI.GetConnections`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetConnectionsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **limit** | **int32** |  | [default to 50]
 **offset** | **int32** |  | [default to 0]
 **orderBy** | **string** |  | [default to &quot;id&quot;]
 **connectionIdPattern** | **string** | SQL LIKE expression — use &#x60;%&#x60; / &#x60;_&#x60; wildcards (e.g. &#x60;%customer_%&#x60;). Regular expressions are **not** supported. | 

### Return type

[**ConnectionCollectionResponse**](ConnectionCollectionResponse.md)

### Authorization

[OAuth2PasswordBearer](../README.md#OAuth2PasswordBearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PatchConnection

> ConnectionResponse PatchConnection(ctx, connectionId).ConnectionBody(connectionBody).UpdateMask(updateMask).Execute()

Patch Connection



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
	connectionId := "connectionId_example" // string | 
	connectionBody := *openapiclient.NewConnectionBody("ConnectionId_example", "ConnType_example") // ConnectionBody | 
	updateMask := []*string{"Inner_example"} // []*string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ConnectionAPI.PatchConnection(context.Background(), connectionId).ConnectionBody(connectionBody).UpdateMask(updateMask).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConnectionAPI.PatchConnection``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PatchConnection`: ConnectionResponse
	fmt.Fprintf(os.Stdout, "Response from `ConnectionAPI.PatchConnection`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**connectionId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiPatchConnectionRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **connectionBody** | [**ConnectionBody**](ConnectionBody.md) |  | 
 **updateMask** | **[]string** |  | 

### Return type

[**ConnectionResponse**](ConnectionResponse.md)

### Authorization

[OAuth2PasswordBearer](../README.md#OAuth2PasswordBearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PostConnection

> ConnectionResponse PostConnection(ctx).ConnectionBody(connectionBody).Execute()

Post Connection



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
	connectionBody := *openapiclient.NewConnectionBody("ConnectionId_example", "ConnType_example") // ConnectionBody | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ConnectionAPI.PostConnection(context.Background()).ConnectionBody(connectionBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConnectionAPI.PostConnection``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PostConnection`: ConnectionResponse
	fmt.Fprintf(os.Stdout, "Response from `ConnectionAPI.PostConnection`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiPostConnectionRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **connectionBody** | [**ConnectionBody**](ConnectionBody.md) |  | 

### Return type

[**ConnectionResponse**](ConnectionResponse.md)

### Authorization

[OAuth2PasswordBearer](../README.md#OAuth2PasswordBearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## TestConnection

> ConnectionTestResponse TestConnection(ctx).ConnectionBody(connectionBody).Execute()

Test Connection



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
	connectionBody := *openapiclient.NewConnectionBody("ConnectionId_example", "ConnType_example") // ConnectionBody | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ConnectionAPI.TestConnection(context.Background()).ConnectionBody(connectionBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConnectionAPI.TestConnection``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `TestConnection`: ConnectionTestResponse
	fmt.Fprintf(os.Stdout, "Response from `ConnectionAPI.TestConnection`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiTestConnectionRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **connectionBody** | [**ConnectionBody**](ConnectionBody.md) |  | 

### Return type

[**ConnectionTestResponse**](ConnectionTestResponse.md)

### Authorization

[OAuth2PasswordBearer](../README.md#OAuth2PasswordBearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

