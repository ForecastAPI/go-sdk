# \AnomalyDetectionAPI

All URIs are relative to *https://forecastapi.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**DetectAnomalies**](AnomalyDetectionAPI.md#DetectAnomalies) | **Post** /v2/detect-anomalies | Detect anomalies in time series data



## DetectAnomalies

> AnomalyDetectionResponse DetectAnomalies(ctx).AnomalyDetectionRequest(anomalyDetectionRequest).Execute()

Detect anomalies in time series data



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
	anomalyDetectionRequest := *openapiclient.NewAnomalyDetectionRequest("SKU-12345", "M", "sales", int32(6), []openapiclient.ForecastRequestDataInner{*openapiclient.NewForecastRequestDataInner(time.Now(), float32(150.5))}) // AnomalyDetectionRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AnomalyDetectionAPI.DetectAnomalies(context.Background()).AnomalyDetectionRequest(anomalyDetectionRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AnomalyDetectionAPI.DetectAnomalies``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DetectAnomalies`: AnomalyDetectionResponse
	fmt.Fprintf(os.Stdout, "Response from `AnomalyDetectionAPI.DetectAnomalies`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiDetectAnomaliesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **anomalyDetectionRequest** | [**AnomalyDetectionRequest**](AnomalyDetectionRequest.md) |  | 

### Return type

[**AnomalyDetectionResponse**](AnomalyDetectionResponse.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

