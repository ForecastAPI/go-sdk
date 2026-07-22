# \ProductInsightsAPI

All URIs are relative to *https://forecastapi.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateBatchProductInsights**](ProductInsightsAPI.md#CreateBatchProductInsights) | **Post** /v2/batch/product-insights | Submit a batch of products for insights analysis
[**CreateProductInsights**](ProductInsightsAPI.md#CreateProductInsights) | **Post** /v2/product-insights | Analyze product performance for anomalies, trends and business insights
[**GetProductInsightsBatch**](ProductInsightsAPI.md#GetProductInsightsBatch) | **Get** /v2/batch/product-insights/{batch_id} | Poll a product insights batch for status and results



## CreateBatchProductInsights

> ProductInsightsBatchStatusResponse CreateBatchProductInsights(ctx).ProductInsightsBatchRequest(productInsightsBatchRequest).Execute()

Submit a batch of products for insights analysis



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
	productInsightsBatchRequest := *openapiclient.NewProductInsightsBatchRequest([]openapiclient.ProductInsightsRequest{*openapiclient.NewProductInsightsRequest("SKU-12345")}) // ProductInsightsBatchRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProductInsightsAPI.CreateBatchProductInsights(context.Background()).ProductInsightsBatchRequest(productInsightsBatchRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProductInsightsAPI.CreateBatchProductInsights``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateBatchProductInsights`: ProductInsightsBatchStatusResponse
	fmt.Fprintf(os.Stdout, "Response from `ProductInsightsAPI.CreateBatchProductInsights`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateBatchProductInsightsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **productInsightsBatchRequest** | [**ProductInsightsBatchRequest**](ProductInsightsBatchRequest.md) |  | 

### Return type

[**ProductInsightsBatchStatusResponse**](ProductInsightsBatchStatusResponse.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CreateProductInsights

> ProductInsightsResponse CreateProductInsights(ctx).ProductInsightsRequest(productInsightsRequest).Execute()

Analyze product performance for anomalies, trends and business insights



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
	productInsightsRequest := *openapiclient.NewProductInsightsRequest("SKU-12345") // ProductInsightsRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProductInsightsAPI.CreateProductInsights(context.Background()).ProductInsightsRequest(productInsightsRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProductInsightsAPI.CreateProductInsights``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateProductInsights`: ProductInsightsResponse
	fmt.Fprintf(os.Stdout, "Response from `ProductInsightsAPI.CreateProductInsights`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateProductInsightsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **productInsightsRequest** | [**ProductInsightsRequest**](ProductInsightsRequest.md) |  | 

### Return type

[**ProductInsightsResponse**](ProductInsightsResponse.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetProductInsightsBatch

> ProductInsightsBatchStatusResponse GetProductInsightsBatch(ctx, batchId).Execute()

Poll a product insights batch for status and results

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
	batchId := "batchId_example" // string | The batch identifier returned on submission

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProductInsightsAPI.GetProductInsightsBatch(context.Background(), batchId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProductInsightsAPI.GetProductInsightsBatch``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetProductInsightsBatch`: ProductInsightsBatchStatusResponse
	fmt.Fprintf(os.Stdout, "Response from `ProductInsightsAPI.GetProductInsightsBatch`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**batchId** | **string** | The batch identifier returned on submission | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetProductInsightsBatchRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**ProductInsightsBatchStatusResponse**](ProductInsightsBatchStatusResponse.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

