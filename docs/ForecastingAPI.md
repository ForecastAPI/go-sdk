# \ForecastingAPI

All URIs are relative to *https://forecastapi.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateForecast**](ForecastingAPI.md#CreateForecast) | **Post** /v2/forecast | Generate forecast for time series data



## CreateForecast

> ForecastResponse CreateForecast(ctx).ForecastRequest(forecastRequest).Execute()

Generate forecast for time series data

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
    "time"
	openapiclient "github.com/ForecastAPI/go-sdk"
)

func main() {
	forecastRequest := *openapiclient.NewForecastRequest("SKU-12345", "M", "sales", int32(6), []openapiclient.ForecastRequestDataInner{*openapiclient.NewForecastRequestDataInner(time.Now(), float32(150.5))}) // ForecastRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ForecastingAPI.CreateForecast(context.Background()).ForecastRequest(forecastRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ForecastingAPI.CreateForecast``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateForecast`: ForecastResponse
	fmt.Fprintf(os.Stdout, "Response from `ForecastingAPI.CreateForecast`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateForecastRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **forecastRequest** | [**ForecastRequest**](ForecastRequest.md) |  | 

### Return type

[**ForecastResponse**](ForecastResponse.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

