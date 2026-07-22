# \TrafficForecastingAPI

All URIs are relative to *https://forecastapi.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateTrafficForecast**](TrafficForecastingAPI.md#CreateTrafficForecast) | **Post** /v2/traffic-forecasting | Generate traffic forecasting with infrastructure scaling recommendations



## CreateTrafficForecast

> TrafficForecastingResponse CreateTrafficForecast(ctx).TrafficForecastingRequest(trafficForecastingRequest).Execute()

Generate traffic forecasting with infrastructure scaling recommendations



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
	trafficForecastingRequest := *openapiclient.NewTrafficForecastingRequest("api-endpoint-users", "H", int32(24), []openapiclient.TrafficForecastingRequestDataInner{*openapiclient.NewTrafficForecastingRequestDataInner("2023-12-01 14:00:00", float32(1500))}, *openapiclient.NewTrafficForecastingRequestTrafficSettings(float32(2000), float32(1000))) // TrafficForecastingRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TrafficForecastingAPI.CreateTrafficForecast(context.Background()).TrafficForecastingRequest(trafficForecastingRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TrafficForecastingAPI.CreateTrafficForecast``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateTrafficForecast`: TrafficForecastingResponse
	fmt.Fprintf(os.Stdout, "Response from `TrafficForecastingAPI.CreateTrafficForecast`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateTrafficForecastRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **trafficForecastingRequest** | [**TrafficForecastingRequest**](TrafficForecastingRequest.md) |  | 

### Return type

[**TrafficForecastingResponse**](TrafficForecastingResponse.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

