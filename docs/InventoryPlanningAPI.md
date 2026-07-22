# \InventoryPlanningAPI

All URIs are relative to *https://forecastapi.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateInventoryPlan**](InventoryPlanningAPI.md#CreateInventoryPlan) | **Post** /v2/inventory-planning | Generate comprehensive inventory planning recommendations



## CreateInventoryPlan

> InventoryPlanningResponse CreateInventoryPlan(ctx).InventoryPlanningRequest(inventoryPlanningRequest).Execute()

Generate comprehensive inventory planning recommendations



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
	inventoryPlanningRequest := *openapiclient.NewInventoryPlanningRequest("SKU-12345", "M", int32(6), []openapiclient.InventoryPlanningRequestDataInner{*openapiclient.NewInventoryPlanningRequestDataInner(time.Now(), float32(150.5))}, *openapiclient.NewInventoryPlanningRequestInventorySettings(float32(250), float32(50), float32(0.95), []openapiclient.InventoryPlanningRequestInventorySettingsSuppliersInner{*openapiclient.NewInventoryPlanningRequestInventorySettingsSuppliersInner("supplier-a", float32(14), float32(100), float32(12.5))})) // InventoryPlanningRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.InventoryPlanningAPI.CreateInventoryPlan(context.Background()).InventoryPlanningRequest(inventoryPlanningRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InventoryPlanningAPI.CreateInventoryPlan``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateInventoryPlan`: InventoryPlanningResponse
	fmt.Fprintf(os.Stdout, "Response from `InventoryPlanningAPI.CreateInventoryPlan`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateInventoryPlanRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **inventoryPlanningRequest** | [**InventoryPlanningRequest**](InventoryPlanningRequest.md) |  | 

### Return type

[**InventoryPlanningResponse**](InventoryPlanningResponse.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

