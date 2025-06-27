# \DAGAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**DeleteDag**](DAGAPI.md#DeleteDag) | **Delete** /api/v2/dags/{dag_id} | Delete Dag
[**GetDag**](DAGAPI.md#GetDag) | **Get** /api/v2/dags/{dag_id} | Get Dag
[**GetDagDetails**](DAGAPI.md#GetDagDetails) | **Get** /api/v2/dags/{dag_id}/details | Get Dag Details
[**GetDagTags**](DAGAPI.md#GetDagTags) | **Get** /api/v2/dagTags | Get Dag Tags
[**GetDags**](DAGAPI.md#GetDags) | **Get** /api/v2/dags | Get Dags
[**PatchDag**](DAGAPI.md#PatchDag) | **Patch** /api/v2/dags/{dag_id} | Patch Dag
[**PatchDags**](DAGAPI.md#PatchDags) | **Patch** /api/v2/dags | Patch Dags



## DeleteDag

> interface{} DeleteDag(ctx, dagId).Execute()

Delete Dag



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

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DAGAPI.DeleteDag(context.Background(), dagId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DAGAPI.DeleteDag``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DeleteDag`: interface{}
	fmt.Fprintf(os.Stdout, "Response from `DAGAPI.DeleteDag`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**dagId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteDagRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


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


## GetDag

> DAGResponse GetDag(ctx, dagId).Execute()

Get Dag



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

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DAGAPI.GetDag(context.Background(), dagId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DAGAPI.GetDag``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetDag`: DAGResponse
	fmt.Fprintf(os.Stdout, "Response from `DAGAPI.GetDag`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**dagId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetDagRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**DAGResponse**](DAGResponse.md)

### Authorization

[OAuth2PasswordBearer](../README.md#OAuth2PasswordBearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetDagDetails

> DAGDetailsResponse GetDagDetails(ctx, dagId).Execute()

Get Dag Details



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

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DAGAPI.GetDagDetails(context.Background(), dagId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DAGAPI.GetDagDetails``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetDagDetails`: DAGDetailsResponse
	fmt.Fprintf(os.Stdout, "Response from `DAGAPI.GetDagDetails`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**dagId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetDagDetailsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**DAGDetailsResponse**](DAGDetailsResponse.md)

### Authorization

[OAuth2PasswordBearer](../README.md#OAuth2PasswordBearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetDagTags

> DAGTagCollectionResponse GetDagTags(ctx).Limit(limit).Offset(offset).OrderBy(orderBy).TagNamePattern(tagNamePattern).Execute()

Get Dag Tags



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
	limit := int32(56) // int32 |  (optional) (default to 50)
	offset := int32(56) // int32 |  (optional) (default to 0)
	orderBy := "orderBy_example" // string |  (optional) (default to "name")
	tagNamePattern := "tagNamePattern_example" // string | SQL LIKE expression — use `%` / `_` wildcards (e.g. `%customer_%`). Regular expressions are **not** supported. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DAGAPI.GetDagTags(context.Background()).Limit(limit).Offset(offset).OrderBy(orderBy).TagNamePattern(tagNamePattern).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DAGAPI.GetDagTags``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetDagTags`: DAGTagCollectionResponse
	fmt.Fprintf(os.Stdout, "Response from `DAGAPI.GetDagTags`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetDagTagsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **limit** | **int32** |  | [default to 50]
 **offset** | **int32** |  | [default to 0]
 **orderBy** | **string** |  | [default to &quot;name&quot;]
 **tagNamePattern** | **string** | SQL LIKE expression — use &#x60;%&#x60; / &#x60;_&#x60; wildcards (e.g. &#x60;%customer_%&#x60;). Regular expressions are **not** supported. | 

### Return type

[**DAGTagCollectionResponse**](DAGTagCollectionResponse.md)

### Authorization

[OAuth2PasswordBearer](../README.md#OAuth2PasswordBearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetDags

> DAGCollectionResponse GetDags(ctx).Limit(limit).Offset(offset).Tags(tags).TagsMatchMode(tagsMatchMode).Owners(owners).DagIdPattern(dagIdPattern).DagDisplayNamePattern(dagDisplayNamePattern).ExcludeStale(excludeStale).Paused(paused).LastDagRunState(lastDagRunState).DagRunStartDateGte(dagRunStartDateGte).DagRunStartDateLte(dagRunStartDateLte).DagRunEndDateGte(dagRunEndDateGte).DagRunEndDateLte(dagRunEndDateLte).DagRunState(dagRunState).OrderBy(orderBy).Execute()

Get Dags



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
	limit := int32(56) // int32 |  (optional) (default to 50)
	offset := int32(56) // int32 |  (optional) (default to 0)
	tags := []*string{"Inner_example"} // []*string |  (optional)
	tagsMatchMode := "tagsMatchMode_example" // string |  (optional)
	owners := []*string{"Inner_example"} // []*string |  (optional)
	dagIdPattern := "dagIdPattern_example" // string | SQL LIKE expression — use `%` / `_` wildcards (e.g. `%customer_%`). Regular expressions are **not** supported. (optional)
	dagDisplayNamePattern := "dagDisplayNamePattern_example" // string | SQL LIKE expression — use `%` / `_` wildcards (e.g. `%customer_%`). Regular expressions are **not** supported. (optional)
	excludeStale := true // bool |  (optional) (default to true)
	paused := true // bool |  (optional)
	lastDagRunState := openapiclient.DagRunState("queued") // DagRunState |  (optional)
	dagRunStartDateGte := time.Now() // time.Time |  (optional)
	dagRunStartDateLte := time.Now() // time.Time |  (optional)
	dagRunEndDateGte := time.Now() // time.Time |  (optional)
	dagRunEndDateLte := time.Now() // time.Time |  (optional)
	dagRunState := []*string{"Inner_example"} // []*string |  (optional)
	orderBy := "orderBy_example" // string |  (optional) (default to "dag_id")

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DAGAPI.GetDags(context.Background()).Limit(limit).Offset(offset).Tags(tags).TagsMatchMode(tagsMatchMode).Owners(owners).DagIdPattern(dagIdPattern).DagDisplayNamePattern(dagDisplayNamePattern).ExcludeStale(excludeStale).Paused(paused).LastDagRunState(lastDagRunState).DagRunStartDateGte(dagRunStartDateGte).DagRunStartDateLte(dagRunStartDateLte).DagRunEndDateGte(dagRunEndDateGte).DagRunEndDateLte(dagRunEndDateLte).DagRunState(dagRunState).OrderBy(orderBy).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DAGAPI.GetDags``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetDags`: DAGCollectionResponse
	fmt.Fprintf(os.Stdout, "Response from `DAGAPI.GetDags`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetDagsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **limit** | **int32** |  | [default to 50]
 **offset** | **int32** |  | [default to 0]
 **tags** | **[]string** |  | 
 **tagsMatchMode** | **string** |  | 
 **owners** | **[]string** |  | 
 **dagIdPattern** | **string** | SQL LIKE expression — use &#x60;%&#x60; / &#x60;_&#x60; wildcards (e.g. &#x60;%customer_%&#x60;). Regular expressions are **not** supported. | 
 **dagDisplayNamePattern** | **string** | SQL LIKE expression — use &#x60;%&#x60; / &#x60;_&#x60; wildcards (e.g. &#x60;%customer_%&#x60;). Regular expressions are **not** supported. | 
 **excludeStale** | **bool** |  | [default to true]
 **paused** | **bool** |  | 
 **lastDagRunState** | [**DagRunState**](DagRunState.md) |  | 
 **dagRunStartDateGte** | **time.Time** |  | 
 **dagRunStartDateLte** | **time.Time** |  | 
 **dagRunEndDateGte** | **time.Time** |  | 
 **dagRunEndDateLte** | **time.Time** |  | 
 **dagRunState** | **[]string** |  | 
 **orderBy** | **string** |  | [default to &quot;dag_id&quot;]

### Return type

[**DAGCollectionResponse**](DAGCollectionResponse.md)

### Authorization

[OAuth2PasswordBearer](../README.md#OAuth2PasswordBearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PatchDag

> DAGResponse PatchDag(ctx, dagId).DAGPatchBody(dAGPatchBody).UpdateMask(updateMask).Execute()

Patch Dag



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
	dAGPatchBody := *openapiclient.NewDAGPatchBody(false) // DAGPatchBody | 
	updateMask := []string{"Inner_example"} // []string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DAGAPI.PatchDag(context.Background(), dagId).DAGPatchBody(dAGPatchBody).UpdateMask(updateMask).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DAGAPI.PatchDag``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PatchDag`: DAGResponse
	fmt.Fprintf(os.Stdout, "Response from `DAGAPI.PatchDag`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**dagId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiPatchDagRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **dAGPatchBody** | [**DAGPatchBody**](DAGPatchBody.md) |  | 
 **updateMask** | **[]string** |  | 

### Return type

[**DAGResponse**](DAGResponse.md)

### Authorization

[OAuth2PasswordBearer](../README.md#OAuth2PasswordBearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PatchDags

> DAGCollectionResponse PatchDags(ctx).DAGPatchBody(dAGPatchBody).UpdateMask(updateMask).Limit(limit).Offset(offset).Tags(tags).TagsMatchMode(tagsMatchMode).Owners(owners).DagIdPattern(dagIdPattern).ExcludeStale(excludeStale).Paused(paused).Execute()

Patch Dags



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
	dAGPatchBody := *openapiclient.NewDAGPatchBody(false) // DAGPatchBody | 
	updateMask := []string{"Inner_example"} // []string |  (optional)
	limit := int32(56) // int32 |  (optional) (default to 50)
	offset := int32(56) // int32 |  (optional) (default to 0)
	tags := []string{"Inner_example"} // []string |  (optional)
	tagsMatchMode := "tagsMatchMode_example" // string |  (optional)
	owners := []string{"Inner_example"} // []string |  (optional)
	dagIdPattern := "dagIdPattern_example" // string | SQL LIKE expression — use `%` / `_` wildcards (e.g. `%customer_%`). Regular expressions are **not** supported. (optional)
	excludeStale := true // bool |  (optional) (default to true)
	paused := true // bool |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DAGAPI.PatchDags(context.Background()).DAGPatchBody(dAGPatchBody).UpdateMask(updateMask).Limit(limit).Offset(offset).Tags(tags).TagsMatchMode(tagsMatchMode).Owners(owners).DagIdPattern(dagIdPattern).ExcludeStale(excludeStale).Paused(paused).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DAGAPI.PatchDags``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PatchDags`: DAGCollectionResponse
	fmt.Fprintf(os.Stdout, "Response from `DAGAPI.PatchDags`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiPatchDagsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **dAGPatchBody** | [**DAGPatchBody**](DAGPatchBody.md) |  | 
 **updateMask** | **[]string** |  | 
 **limit** | **int32** |  | [default to 50]
 **offset** | **int32** |  | [default to 0]
 **tags** | **[]string** |  | 
 **tagsMatchMode** | **string** |  | 
 **owners** | **[]string** |  | 
 **dagIdPattern** | **string** | SQL LIKE expression — use &#x60;%&#x60; / &#x60;_&#x60; wildcards (e.g. &#x60;%customer_%&#x60;). Regular expressions are **not** supported. | 
 **excludeStale** | **bool** |  | [default to true]
 **paused** | **bool** |  | 

### Return type

[**DAGCollectionResponse**](DAGCollectionResponse.md)

### Authorization

[OAuth2PasswordBearer](../README.md#OAuth2PasswordBearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

