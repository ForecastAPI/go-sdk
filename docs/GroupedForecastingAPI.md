# \GroupedForecastingAPI

All URIs are relative to *https://forecastapi.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateGroupedForecast**](GroupedForecastingAPI.md#CreateGroupedForecast) | **Post** /v2/forecast/grouped | Submit a grouped (hierarchical) forecast with reconciliation
[**GetGroupedForecast**](GroupedForecastingAPI.md#GetGroupedForecast) | **Get** /v2/forecast/grouped/{grouped_forecast_id} | Poll a grouped forecast for status and results



## CreateGroupedForecast

> GroupedForecastAccepted CreateGroupedForecast(ctx).GroupedForecastRequest(groupedForecastRequest).Execute()

Submit a grouped (hierarchical) forecast with reconciliation



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
	groupedForecastRequest := *openapiclient.NewGroupedForecastRequest("mrr", []string{"Hierarchy_example"}, "M", int32(6), []openapiclient.GroupedForecastSeries{*openapiclient.NewGroupedForecastSeries(map[string]interface{}{"key": interface{}(123)}, []openapiclient.GroupedForecastSeriesDataInner{*openapiclient.NewGroupedForecastSeriesDataInner(time.Now(), float32(42000))})}) // GroupedForecastRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GroupedForecastingAPI.CreateGroupedForecast(context.Background()).GroupedForecastRequest(groupedForecastRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GroupedForecastingAPI.CreateGroupedForecast``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateGroupedForecast`: GroupedForecastAccepted
	fmt.Fprintf(os.Stdout, "Response from `GroupedForecastingAPI.CreateGroupedForecast`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateGroupedForecastRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **groupedForecastRequest** | [**GroupedForecastRequest**](GroupedForecastRequest.md) |  | 

### Return type

[**GroupedForecastAccepted**](GroupedForecastAccepted.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetGroupedForecast

> GroupedForecastStatusResponse GetGroupedForecast(ctx, groupedForecastId).Execute()

Poll a grouped forecast for status and results



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/ForecastAPI/go-sdk"
)

func main() {
	groupedForecastId := "k3n9x2m4p8q1w5r7" // string | The id returned by POST /v2/forecast/grouped

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GroupedForecastingAPI.GetGroupedForecast(context.Background(), groupedForecastId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GroupedForecastingAPI.GetGroupedForecast``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetGroupedForecast`: GroupedForecastStatusResponse
	fmt.Fprintf(os.Stdout, "Response from `GroupedForecastingAPI.GetGroupedForecast`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**groupedForecastId** | **string** | The id returned by POST /v2/forecast/grouped | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetGroupedForecastRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**GroupedForecastStatusResponse**](GroupedForecastStatusResponse.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

