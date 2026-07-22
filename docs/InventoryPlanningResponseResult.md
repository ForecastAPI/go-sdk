# InventoryPlanningResponseResult

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Identifier** | Pointer to **string** | Product identifier from the request | [optional] 
**CurrentStock** | Pointer to **float32** | Current stock level | [optional] 
**MinimumStock** | Pointer to **float32** | Minimum stock level to maintain | [optional] 
**ReorderPoint** | Pointer to **float32** | Recommended reorder point for optimal supplier | [optional] 
**SafetyStock** | Pointer to **float32** | Calculated safety stock for optimal supplier | [optional] 
**Suppliers** | Pointer to [**[]InventoryPlanningResponseResultSuppliersInner**](InventoryPlanningResponseResultSuppliersInner.md) | Analysis and recommendations for each supplier | [optional] 
**StockAnalysis** | Pointer to [**InventoryPlanningResponseResultStockAnalysis**](InventoryPlanningResponseResultStockAnalysis.md) |  | [optional] 
**ForecastData** | Pointer to [**[]InventoryPlanningResponseResultForecastDataInner**](InventoryPlanningResponseResultForecastDataInner.md) | Underlying forecast data used for planning | [optional] 

## Methods

### NewInventoryPlanningResponseResult

`func NewInventoryPlanningResponseResult() *InventoryPlanningResponseResult`

NewInventoryPlanningResponseResult instantiates a new InventoryPlanningResponseResult object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewInventoryPlanningResponseResultWithDefaults

`func NewInventoryPlanningResponseResultWithDefaults() *InventoryPlanningResponseResult`

NewInventoryPlanningResponseResultWithDefaults instantiates a new InventoryPlanningResponseResult object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetIdentifier

`func (o *InventoryPlanningResponseResult) GetIdentifier() string`

GetIdentifier returns the Identifier field if non-nil, zero value otherwise.

### GetIdentifierOk

`func (o *InventoryPlanningResponseResult) GetIdentifierOk() (*string, bool)`

GetIdentifierOk returns a tuple with the Identifier field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdentifier

`func (o *InventoryPlanningResponseResult) SetIdentifier(v string)`

SetIdentifier sets Identifier field to given value.

### HasIdentifier

`func (o *InventoryPlanningResponseResult) HasIdentifier() bool`

HasIdentifier returns a boolean if a field has been set.

### GetCurrentStock

`func (o *InventoryPlanningResponseResult) GetCurrentStock() float32`

GetCurrentStock returns the CurrentStock field if non-nil, zero value otherwise.

### GetCurrentStockOk

`func (o *InventoryPlanningResponseResult) GetCurrentStockOk() (*float32, bool)`

GetCurrentStockOk returns a tuple with the CurrentStock field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrentStock

`func (o *InventoryPlanningResponseResult) SetCurrentStock(v float32)`

SetCurrentStock sets CurrentStock field to given value.

### HasCurrentStock

`func (o *InventoryPlanningResponseResult) HasCurrentStock() bool`

HasCurrentStock returns a boolean if a field has been set.

### GetMinimumStock

`func (o *InventoryPlanningResponseResult) GetMinimumStock() float32`

GetMinimumStock returns the MinimumStock field if non-nil, zero value otherwise.

### GetMinimumStockOk

`func (o *InventoryPlanningResponseResult) GetMinimumStockOk() (*float32, bool)`

GetMinimumStockOk returns a tuple with the MinimumStock field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMinimumStock

`func (o *InventoryPlanningResponseResult) SetMinimumStock(v float32)`

SetMinimumStock sets MinimumStock field to given value.

### HasMinimumStock

`func (o *InventoryPlanningResponseResult) HasMinimumStock() bool`

HasMinimumStock returns a boolean if a field has been set.

### GetReorderPoint

`func (o *InventoryPlanningResponseResult) GetReorderPoint() float32`

GetReorderPoint returns the ReorderPoint field if non-nil, zero value otherwise.

### GetReorderPointOk

`func (o *InventoryPlanningResponseResult) GetReorderPointOk() (*float32, bool)`

GetReorderPointOk returns a tuple with the ReorderPoint field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReorderPoint

`func (o *InventoryPlanningResponseResult) SetReorderPoint(v float32)`

SetReorderPoint sets ReorderPoint field to given value.

### HasReorderPoint

`func (o *InventoryPlanningResponseResult) HasReorderPoint() bool`

HasReorderPoint returns a boolean if a field has been set.

### GetSafetyStock

`func (o *InventoryPlanningResponseResult) GetSafetyStock() float32`

GetSafetyStock returns the SafetyStock field if non-nil, zero value otherwise.

### GetSafetyStockOk

`func (o *InventoryPlanningResponseResult) GetSafetyStockOk() (*float32, bool)`

GetSafetyStockOk returns a tuple with the SafetyStock field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSafetyStock

`func (o *InventoryPlanningResponseResult) SetSafetyStock(v float32)`

SetSafetyStock sets SafetyStock field to given value.

### HasSafetyStock

`func (o *InventoryPlanningResponseResult) HasSafetyStock() bool`

HasSafetyStock returns a boolean if a field has been set.

### GetSuppliers

`func (o *InventoryPlanningResponseResult) GetSuppliers() []InventoryPlanningResponseResultSuppliersInner`

GetSuppliers returns the Suppliers field if non-nil, zero value otherwise.

### GetSuppliersOk

`func (o *InventoryPlanningResponseResult) GetSuppliersOk() (*[]InventoryPlanningResponseResultSuppliersInner, bool)`

GetSuppliersOk returns a tuple with the Suppliers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuppliers

`func (o *InventoryPlanningResponseResult) SetSuppliers(v []InventoryPlanningResponseResultSuppliersInner)`

SetSuppliers sets Suppliers field to given value.

### HasSuppliers

`func (o *InventoryPlanningResponseResult) HasSuppliers() bool`

HasSuppliers returns a boolean if a field has been set.

### GetStockAnalysis

`func (o *InventoryPlanningResponseResult) GetStockAnalysis() InventoryPlanningResponseResultStockAnalysis`

GetStockAnalysis returns the StockAnalysis field if non-nil, zero value otherwise.

### GetStockAnalysisOk

`func (o *InventoryPlanningResponseResult) GetStockAnalysisOk() (*InventoryPlanningResponseResultStockAnalysis, bool)`

GetStockAnalysisOk returns a tuple with the StockAnalysis field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStockAnalysis

`func (o *InventoryPlanningResponseResult) SetStockAnalysis(v InventoryPlanningResponseResultStockAnalysis)`

SetStockAnalysis sets StockAnalysis field to given value.

### HasStockAnalysis

`func (o *InventoryPlanningResponseResult) HasStockAnalysis() bool`

HasStockAnalysis returns a boolean if a field has been set.

### GetForecastData

`func (o *InventoryPlanningResponseResult) GetForecastData() []InventoryPlanningResponseResultForecastDataInner`

GetForecastData returns the ForecastData field if non-nil, zero value otherwise.

### GetForecastDataOk

`func (o *InventoryPlanningResponseResult) GetForecastDataOk() (*[]InventoryPlanningResponseResultForecastDataInner, bool)`

GetForecastDataOk returns a tuple with the ForecastData field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetForecastData

`func (o *InventoryPlanningResponseResult) SetForecastData(v []InventoryPlanningResponseResultForecastDataInner)`

SetForecastData sets ForecastData field to given value.

### HasForecastData

`func (o *InventoryPlanningResponseResult) HasForecastData() bool`

HasForecastData returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


