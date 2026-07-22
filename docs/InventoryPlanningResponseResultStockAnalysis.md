# InventoryPlanningResponseResultStockAnalysis

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DaysOfCoverage** | Pointer to **int32** | Number of days current stock will last | [optional] 
**StockoutRisk** | Pointer to **float32** | Risk of stockout (0-1, where 1 is certain stockout) | [optional] 
**NextOrderDate** | Pointer to **string** | Recommended date for next order | [optional] 
**DailyDemandRate** | Pointer to **float32** | Average daily demand rate | [optional] 
**StockStatus** | Pointer to **string** | Current stock status assessment | [optional] 

## Methods

### NewInventoryPlanningResponseResultStockAnalysis

`func NewInventoryPlanningResponseResultStockAnalysis() *InventoryPlanningResponseResultStockAnalysis`

NewInventoryPlanningResponseResultStockAnalysis instantiates a new InventoryPlanningResponseResultStockAnalysis object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewInventoryPlanningResponseResultStockAnalysisWithDefaults

`func NewInventoryPlanningResponseResultStockAnalysisWithDefaults() *InventoryPlanningResponseResultStockAnalysis`

NewInventoryPlanningResponseResultStockAnalysisWithDefaults instantiates a new InventoryPlanningResponseResultStockAnalysis object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDaysOfCoverage

`func (o *InventoryPlanningResponseResultStockAnalysis) GetDaysOfCoverage() int32`

GetDaysOfCoverage returns the DaysOfCoverage field if non-nil, zero value otherwise.

### GetDaysOfCoverageOk

`func (o *InventoryPlanningResponseResultStockAnalysis) GetDaysOfCoverageOk() (*int32, bool)`

GetDaysOfCoverageOk returns a tuple with the DaysOfCoverage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDaysOfCoverage

`func (o *InventoryPlanningResponseResultStockAnalysis) SetDaysOfCoverage(v int32)`

SetDaysOfCoverage sets DaysOfCoverage field to given value.

### HasDaysOfCoverage

`func (o *InventoryPlanningResponseResultStockAnalysis) HasDaysOfCoverage() bool`

HasDaysOfCoverage returns a boolean if a field has been set.

### GetStockoutRisk

`func (o *InventoryPlanningResponseResultStockAnalysis) GetStockoutRisk() float32`

GetStockoutRisk returns the StockoutRisk field if non-nil, zero value otherwise.

### GetStockoutRiskOk

`func (o *InventoryPlanningResponseResultStockAnalysis) GetStockoutRiskOk() (*float32, bool)`

GetStockoutRiskOk returns a tuple with the StockoutRisk field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStockoutRisk

`func (o *InventoryPlanningResponseResultStockAnalysis) SetStockoutRisk(v float32)`

SetStockoutRisk sets StockoutRisk field to given value.

### HasStockoutRisk

`func (o *InventoryPlanningResponseResultStockAnalysis) HasStockoutRisk() bool`

HasStockoutRisk returns a boolean if a field has been set.

### GetNextOrderDate

`func (o *InventoryPlanningResponseResultStockAnalysis) GetNextOrderDate() string`

GetNextOrderDate returns the NextOrderDate field if non-nil, zero value otherwise.

### GetNextOrderDateOk

`func (o *InventoryPlanningResponseResultStockAnalysis) GetNextOrderDateOk() (*string, bool)`

GetNextOrderDateOk returns a tuple with the NextOrderDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNextOrderDate

`func (o *InventoryPlanningResponseResultStockAnalysis) SetNextOrderDate(v string)`

SetNextOrderDate sets NextOrderDate field to given value.

### HasNextOrderDate

`func (o *InventoryPlanningResponseResultStockAnalysis) HasNextOrderDate() bool`

HasNextOrderDate returns a boolean if a field has been set.

### GetDailyDemandRate

`func (o *InventoryPlanningResponseResultStockAnalysis) GetDailyDemandRate() float32`

GetDailyDemandRate returns the DailyDemandRate field if non-nil, zero value otherwise.

### GetDailyDemandRateOk

`func (o *InventoryPlanningResponseResultStockAnalysis) GetDailyDemandRateOk() (*float32, bool)`

GetDailyDemandRateOk returns a tuple with the DailyDemandRate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDailyDemandRate

`func (o *InventoryPlanningResponseResultStockAnalysis) SetDailyDemandRate(v float32)`

SetDailyDemandRate sets DailyDemandRate field to given value.

### HasDailyDemandRate

`func (o *InventoryPlanningResponseResultStockAnalysis) HasDailyDemandRate() bool`

HasDailyDemandRate returns a boolean if a field has been set.

### GetStockStatus

`func (o *InventoryPlanningResponseResultStockAnalysis) GetStockStatus() string`

GetStockStatus returns the StockStatus field if non-nil, zero value otherwise.

### GetStockStatusOk

`func (o *InventoryPlanningResponseResultStockAnalysis) GetStockStatusOk() (*string, bool)`

GetStockStatusOk returns a tuple with the StockStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStockStatus

`func (o *InventoryPlanningResponseResultStockAnalysis) SetStockStatus(v string)`

SetStockStatus sets StockStatus field to given value.

### HasStockStatus

`func (o *InventoryPlanningResponseResultStockAnalysis) HasStockStatus() bool`

HasStockStatus returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


