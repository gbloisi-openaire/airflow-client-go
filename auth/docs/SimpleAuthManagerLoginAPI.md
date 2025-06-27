# \SimpleAuthManagerLoginAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateToken**](SimpleAuthManagerLoginAPI.md#CreateToken) | **Post** /auth/token | Create Token
[**CreateTokenAllAdmins**](SimpleAuthManagerLoginAPI.md#CreateTokenAllAdmins) | **Get** /auth/token | Create Token All Admins
[**CreateTokenCli**](SimpleAuthManagerLoginAPI.md#CreateTokenCli) | **Post** /auth/token/cli | Create Token Cli
[**LoginAllAdmins**](SimpleAuthManagerLoginAPI.md#LoginAllAdmins) | **Get** /auth/token/login | Login All Admins



## CreateToken

> LoginResponse CreateToken(ctx).LoginBody(loginBody).Execute()

Create Token



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
	loginBody := *openapiclient.NewLoginBody("Username_example", "Password_example") // LoginBody | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SimpleAuthManagerLoginAPI.CreateToken(context.Background()).LoginBody(loginBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SimpleAuthManagerLoginAPI.CreateToken``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateToken`: LoginResponse
	fmt.Fprintf(os.Stdout, "Response from `SimpleAuthManagerLoginAPI.CreateToken`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateTokenRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **loginBody** | [**LoginBody**](LoginBody.md) |  | 

### Return type

[**LoginResponse**](LoginResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CreateTokenAllAdmins

> LoginResponse CreateTokenAllAdmins(ctx).Execute()

Create Token All Admins



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

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SimpleAuthManagerLoginAPI.CreateTokenAllAdmins(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SimpleAuthManagerLoginAPI.CreateTokenAllAdmins``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateTokenAllAdmins`: LoginResponse
	fmt.Fprintf(os.Stdout, "Response from `SimpleAuthManagerLoginAPI.CreateTokenAllAdmins`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiCreateTokenAllAdminsRequest struct via the builder pattern


### Return type

[**LoginResponse**](LoginResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CreateTokenCli

> LoginResponse CreateTokenCli(ctx).LoginBody(loginBody).Execute()

Create Token Cli



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
	loginBody := *openapiclient.NewLoginBody("Username_example", "Password_example") // LoginBody | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SimpleAuthManagerLoginAPI.CreateTokenCli(context.Background()).LoginBody(loginBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SimpleAuthManagerLoginAPI.CreateTokenCli``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateTokenCli`: LoginResponse
	fmt.Fprintf(os.Stdout, "Response from `SimpleAuthManagerLoginAPI.CreateTokenCli`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateTokenCliRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **loginBody** | [**LoginBody**](LoginBody.md) |  | 

### Return type

[**LoginResponse**](LoginResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## LoginAllAdmins

> LoginAllAdmins(ctx).Execute()

Login All Admins



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

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.SimpleAuthManagerLoginAPI.LoginAllAdmins(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SimpleAuthManagerLoginAPI.LoginAllAdmins``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiLoginAllAdminsRequest struct via the builder pattern


### Return type

 (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

