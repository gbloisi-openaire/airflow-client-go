# \DagStatsAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetDagStats**](DagStatsAPI.md#GetDagStats) | **Get** /api/v2/dagStats | Get Dag Stats



## GetDagStats

> DagStatsCollectionResponse GetDagStats(ctx).DagIds(dagIds).Execute()

Get Dag Stats



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
	dagIds := []string{"Inner_example"} // []string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DagStatsAPI.GetDagStats(context.Background()).DagIds(dagIds).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DagStatsAPI.GetDagStats``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetDagStats`: DagStatsCollectionResponse
	fmt.Fprintf(os.Stdout, "Response from `DagStatsAPI.GetDagStats`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetDagStatsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **dagIds** | **[]string** |  | 

### Return type

[**DagStatsCollectionResponse**](DagStatsCollectionResponse.md)

### Authorization

[OAuth2PasswordBearer](../README.md#OAuth2PasswordBearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

