# \DagVersionAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetDagVersion**](DagVersionAPI.md#GetDagVersion) | **Get** /api/v2/dags/{dag_id}/dagVersions/{version_number} | Get Dag Version
[**GetDagVersions**](DagVersionAPI.md#GetDagVersions) | **Get** /api/v2/dags/{dag_id}/dagVersions | Get Dag Versions



## GetDagVersion

> DagVersionResponse GetDagVersion(ctx, dagId, versionNumber).Execute()

Get Dag Version



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
	versionNumber := int32(56) // int32 | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DagVersionAPI.GetDagVersion(context.Background(), dagId, versionNumber).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DagVersionAPI.GetDagVersion``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetDagVersion`: DagVersionResponse
	fmt.Fprintf(os.Stdout, "Response from `DagVersionAPI.GetDagVersion`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**dagId** | **string** |  | 
**versionNumber** | **int32** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetDagVersionRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**DagVersionResponse**](DagVersionResponse.md)

### Authorization

[OAuth2PasswordBearer](../README.md#OAuth2PasswordBearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetDagVersions

> DAGVersionCollectionResponse GetDagVersions(ctx, dagId).Limit(limit).Offset(offset).VersionNumber(versionNumber).BundleName(bundleName).BundleVersion(bundleVersion).OrderBy(orderBy).Execute()

Get Dag Versions



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
	limit := int32(56) // int32 |  (optional) (default to 50)
	offset := int32(56) // int32 |  (optional) (default to 0)
	versionNumber := int32(56) // int32 |  (optional)
	bundleName := "bundleName_example" // string |  (optional)
	bundleVersion := "bundleVersion_example" // string |  (optional)
	orderBy := "orderBy_example" // string |  (optional) (default to "id")

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DagVersionAPI.GetDagVersions(context.Background(), dagId).Limit(limit).Offset(offset).VersionNumber(versionNumber).BundleName(bundleName).BundleVersion(bundleVersion).OrderBy(orderBy).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DagVersionAPI.GetDagVersions``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetDagVersions`: DAGVersionCollectionResponse
	fmt.Fprintf(os.Stdout, "Response from `DagVersionAPI.GetDagVersions`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**dagId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetDagVersionsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **limit** | **int32** |  | [default to 50]
 **offset** | **int32** |  | [default to 0]
 **versionNumber** | **int32** |  | 
 **bundleName** | **string** |  | 
 **bundleVersion** | **string** |  | 
 **orderBy** | **string** |  | [default to &quot;id&quot;]

### Return type

[**DAGVersionCollectionResponse**](DAGVersionCollectionResponse.md)

### Authorization

[OAuth2PasswordBearer](../README.md#OAuth2PasswordBearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

