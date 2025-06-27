# \VariableAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**BulkVariables**](VariableAPI.md#BulkVariables) | **Patch** /api/v2/variables | Bulk Variables
[**DeleteVariable**](VariableAPI.md#DeleteVariable) | **Delete** /api/v2/variables/{variable_key} | Delete Variable
[**GetVariable**](VariableAPI.md#GetVariable) | **Get** /api/v2/variables/{variable_key} | Get Variable
[**GetVariables**](VariableAPI.md#GetVariables) | **Get** /api/v2/variables | Get Variables
[**PatchVariable**](VariableAPI.md#PatchVariable) | **Patch** /api/v2/variables/{variable_key} | Patch Variable
[**PostVariable**](VariableAPI.md#PostVariable) | **Post** /api/v2/variables | Post Variable



## BulkVariables

> BulkResponse BulkVariables(ctx).BulkBodyVariableBody(bulkBodyVariableBody).Execute()

Bulk Variables



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
	bulkBodyVariableBody := *openapiclient.NewBulkBodyVariableBody([]openapiclient.BulkBodyVariableBodyActionsInner{openapiclient.BulkBody_VariableBody__actions_inner{BulkCreateActionVariableBody: openapiclient.NewBulkCreateActionVariableBody("Action_example", []openapiclient.VariableBody{*openapiclient.NewVariableBody("Key_example", interface{}(123))})}}) // BulkBodyVariableBody | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.VariableAPI.BulkVariables(context.Background()).BulkBodyVariableBody(bulkBodyVariableBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `VariableAPI.BulkVariables``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `BulkVariables`: BulkResponse
	fmt.Fprintf(os.Stdout, "Response from `VariableAPI.BulkVariables`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiBulkVariablesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **bulkBodyVariableBody** | [**BulkBodyVariableBody**](BulkBodyVariableBody.md) |  | 

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


## DeleteVariable

> DeleteVariable(ctx, variableKey).Execute()

Delete Variable



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
	variableKey := "variableKey_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.VariableAPI.DeleteVariable(context.Background(), variableKey).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `VariableAPI.DeleteVariable``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**variableKey** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteVariableRequest struct via the builder pattern


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


## GetVariable

> VariableResponse GetVariable(ctx, variableKey).Execute()

Get Variable



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
	variableKey := "variableKey_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.VariableAPI.GetVariable(context.Background(), variableKey).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `VariableAPI.GetVariable``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetVariable`: VariableResponse
	fmt.Fprintf(os.Stdout, "Response from `VariableAPI.GetVariable`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**variableKey** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetVariableRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**VariableResponse**](VariableResponse.md)

### Authorization

[OAuth2PasswordBearer](../README.md#OAuth2PasswordBearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetVariables

> VariableCollectionResponse GetVariables(ctx).Limit(limit).Offset(offset).OrderBy(orderBy).VariableKeyPattern(variableKeyPattern).Execute()

Get Variables



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
	orderBy := "orderBy_example" // string |  (optional) (default to "id")
	variableKeyPattern := "variableKeyPattern_example" // string | SQL LIKE expression — use `%` / `_` wildcards (e.g. `%customer_%`). Regular expressions are **not** supported. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.VariableAPI.GetVariables(context.Background()).Limit(limit).Offset(offset).OrderBy(orderBy).VariableKeyPattern(variableKeyPattern).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `VariableAPI.GetVariables``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetVariables`: VariableCollectionResponse
	fmt.Fprintf(os.Stdout, "Response from `VariableAPI.GetVariables`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetVariablesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **limit** | **int32** |  | [default to 50]
 **offset** | **int32** |  | [default to 0]
 **orderBy** | **string** |  | [default to &quot;id&quot;]
 **variableKeyPattern** | **string** | SQL LIKE expression — use &#x60;%&#x60; / &#x60;_&#x60; wildcards (e.g. &#x60;%customer_%&#x60;). Regular expressions are **not** supported. | 

### Return type

[**VariableCollectionResponse**](VariableCollectionResponse.md)

### Authorization

[OAuth2PasswordBearer](../README.md#OAuth2PasswordBearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PatchVariable

> VariableResponse PatchVariable(ctx, variableKey).VariableBody(variableBody).UpdateMask(updateMask).Execute()

Patch Variable



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
	variableKey := "variableKey_example" // string | 
	variableBody := *openapiclient.NewVariableBody("Key_example", interface{}(123)) // VariableBody | 
	updateMask := []string{"Inner_example"} // []string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.VariableAPI.PatchVariable(context.Background(), variableKey).VariableBody(variableBody).UpdateMask(updateMask).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `VariableAPI.PatchVariable``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PatchVariable`: VariableResponse
	fmt.Fprintf(os.Stdout, "Response from `VariableAPI.PatchVariable`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**variableKey** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiPatchVariableRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **variableBody** | [**VariableBody**](VariableBody.md) |  | 
 **updateMask** | **[]string** |  | 

### Return type

[**VariableResponse**](VariableResponse.md)

### Authorization

[OAuth2PasswordBearer](../README.md#OAuth2PasswordBearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PostVariable

> VariableResponse PostVariable(ctx).VariableBody(variableBody).Execute()

Post Variable



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
	variableBody := *openapiclient.NewVariableBody("Key_example", interface{}(123)) // VariableBody | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.VariableAPI.PostVariable(context.Background()).VariableBody(variableBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `VariableAPI.PostVariable``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PostVariable`: VariableResponse
	fmt.Fprintf(os.Stdout, "Response from `VariableAPI.PostVariable`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiPostVariableRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **variableBody** | [**VariableBody**](VariableBody.md) |  | 

### Return type

[**VariableResponse**](VariableResponse.md)

### Authorization

[OAuth2PasswordBearer](../README.md#OAuth2PasswordBearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

