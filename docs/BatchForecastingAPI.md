# \BatchForecastingAPI

All URIs are relative to *https://forecastapi.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateBatchForecast**](BatchForecastingAPI.md#CreateBatchForecast) | **Post** /v2/batch/forecast | Submit a batch of series for forecasting
[**GetBatchForecast**](BatchForecastingAPI.md#GetBatchForecast) | **Get** /v2/batch/forecast/{batch_id} | Poll a batch forecast for status and results
[**PresignBatchForecast**](BatchForecastingAPI.md#PresignBatchForecast) | **Post** /v2/batch/forecast/presign | Get a presigned URL for a file-based batch upload



## CreateBatchForecast

> BatchForecastAccepted CreateBatchForecast(ctx).BatchForecastRequest(batchForecastRequest).Execute()

Submit a batch of series for forecasting



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com-henrikns92/henrikns92/go-sdk"
)

func main() {
	batchForecastRequest := *openapiclient.NewBatchForecastRequest() // BatchForecastRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.BatchForecastingAPI.CreateBatchForecast(context.Background()).BatchForecastRequest(batchForecastRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BatchForecastingAPI.CreateBatchForecast``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateBatchForecast`: BatchForecastAccepted
	fmt.Fprintf(os.Stdout, "Response from `BatchForecastingAPI.CreateBatchForecast`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateBatchForecastRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **batchForecastRequest** | [**BatchForecastRequest**](BatchForecastRequest.md) |  | 

### Return type

[**BatchForecastAccepted**](BatchForecastAccepted.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetBatchForecast

> BatchForecastStatusResponse GetBatchForecast(ctx, batchId).Execute()

Poll a batch forecast for status and results



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com-henrikns92/henrikns92/go-sdk"
)

func main() {
	batchId := "batchId_example" // string | The id returned by POST /v2/batch/forecast

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.BatchForecastingAPI.GetBatchForecast(context.Background(), batchId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BatchForecastingAPI.GetBatchForecast``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetBatchForecast`: BatchForecastStatusResponse
	fmt.Fprintf(os.Stdout, "Response from `BatchForecastingAPI.GetBatchForecast`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**batchId** | **string** | The id returned by POST /v2/batch/forecast | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetBatchForecastRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**BatchForecastStatusResponse**](BatchForecastStatusResponse.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PresignBatchForecast

> BatchPresignResponse PresignBatchForecast(ctx).Execute()

Get a presigned URL for a file-based batch upload



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com-henrikns92/henrikns92/go-sdk"
)

func main() {

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.BatchForecastingAPI.PresignBatchForecast(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BatchForecastingAPI.PresignBatchForecast``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PresignBatchForecast`: BatchPresignResponse
	fmt.Fprintf(os.Stdout, "Response from `BatchForecastingAPI.PresignBatchForecast`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiPresignBatchForecastRequest struct via the builder pattern


### Return type

[**BatchPresignResponse**](BatchPresignResponse.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

