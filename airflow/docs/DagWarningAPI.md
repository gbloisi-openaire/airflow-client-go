# \DagWarningAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ListDagWarnings**](DagWarningAPI.md#ListDagWarnings) | **Get** /api/v2/dagWarnings | List Dag Warnings



## ListDagWarnings

> DAGWarningCollectionResponse ListDagWarnings(ctx).DagId(dagId).WarningType(warningType).Limit(limit).Offset(offset).OrderBy(orderBy).Execute()

List Dag Warnings



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
	dagId := "dagId_example" // string |  (optional)
	warningType := openapiclient.DagWarningType("asset conflict") // DagWarningType |  (optional)
	limit := int32(56) // int32 |  (optional) (default to 50)
	offset := int32(56) // int32 |  (optional) (default to 0)
	orderBy := "orderBy_example" // string |  (optional) (default to "dag_id")

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DagWarningAPI.ListDagWarnings(context.Background()).DagId(dagId).WarningType(warningType).Limit(limit).Offset(offset).OrderBy(orderBy).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DagWarningAPI.ListDagWarnings``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListDagWarnings`: DAGWarningCollectionResponse
	fmt.Fprintf(os.Stdout, "Response from `DagWarningAPI.ListDagWarnings`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListDagWarningsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **dagId** | **string** |  | 
 **warningType** | [**DagWarningType**](DagWarningType.md) |  | 
 **limit** | **int32** |  | [default to 50]
 **offset** | **int32** |  | [default to 0]
 **orderBy** | **string** |  | [default to &quot;dag_id&quot;]

### Return type

[**DAGWarningCollectionResponse**](DAGWarningCollectionResponse.md)

### Authorization

[OAuth2PasswordBearer](../README.md#OAuth2PasswordBearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

