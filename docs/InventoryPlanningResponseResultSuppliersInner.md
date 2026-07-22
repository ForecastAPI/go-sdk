# InventoryPlanningResponseResultSuppliersInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Supplier** | Pointer to **string** | Supplier identifier | [optional] 
**OrderQuantity** | Pointer to **float32** | Recommended order quantity | [optional] 
**TotalCost** | Pointer to **float32** | Total cost for the recommended order | [optional] 
**CostPerUnit** | Pointer to **float32** | Cost per unit from this supplier | [optional] 
**ExpectedDelivery** | Pointer to **string** | Expected delivery date | [optional] 
**LeadTimeDays** | Pointer to **float32** | Lead time in days | [optional] 
**MinimumOrderQuantity** | Pointer to **float32** | Minimum order quantity | [optional] 
**ReliabilityScore** | Pointer to **float32** | Supplier reliability score | [optional] 
**LeadTimeDemand** | Pointer to **float32** | Expected demand during lead time | [optional] 
**SafetyStock** | Pointer to **float32** | Calculated safety stock for this supplier | [optional] 
**ReorderPoint** | Pointer to **float32** | Calculated reorder point for this supplier | [optional] 
**Reason** | Pointer to **string** | Explanation for the recommendation | [optional] 

## Methods

### NewInventoryPlanningResponseResultSuppliersInner

`func NewInventoryPlanningResponseResultSuppliersInner() *InventoryPlanningResponseResultSuppliersInner`

NewInventoryPlanningResponseResultSuppliersInner instantiates a new InventoryPlanningResponseResultSuppliersInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewInventoryPlanningResponseResultSuppliersInnerWithDefaults

`func NewInventoryPlanningResponseResultSuppliersInnerWithDefaults() *InventoryPlanningResponseResultSuppliersInner`

NewInventoryPlanningResponseResultSuppliersInnerWithDefaults instantiates a new InventoryPlanningResponseResultSuppliersInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSupplier

`func (o *InventoryPlanningResponseResultSuppliersInner) GetSupplier() string`

GetSupplier returns the Supplier field if non-nil, zero value otherwise.

### GetSupplierOk

`func (o *InventoryPlanningResponseResultSuppliersInner) GetSupplierOk() (*string, bool)`

GetSupplierOk returns a tuple with the Supplier field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupplier

`func (o *InventoryPlanningResponseResultSuppliersInner) SetSupplier(v string)`

SetSupplier sets Supplier field to given value.

### HasSupplier

`func (o *InventoryPlanningResponseResultSuppliersInner) HasSupplier() bool`

HasSupplier returns a boolean if a field has been set.

### GetOrderQuantity

`func (o *InventoryPlanningResponseResultSuppliersInner) GetOrderQuantity() float32`

GetOrderQuantity returns the OrderQuantity field if non-nil, zero value otherwise.

### GetOrderQuantityOk

`func (o *InventoryPlanningResponseResultSuppliersInner) GetOrderQuantityOk() (*float32, bool)`

GetOrderQuantityOk returns a tuple with the OrderQuantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrderQuantity

`func (o *InventoryPlanningResponseResultSuppliersInner) SetOrderQuantity(v float32)`

SetOrderQuantity sets OrderQuantity field to given value.

### HasOrderQuantity

`func (o *InventoryPlanningResponseResultSuppliersInner) HasOrderQuantity() bool`

HasOrderQuantity returns a boolean if a field has been set.

### GetTotalCost

`func (o *InventoryPlanningResponseResultSuppliersInner) GetTotalCost() float32`

GetTotalCost returns the TotalCost field if non-nil, zero value otherwise.

### GetTotalCostOk

`func (o *InventoryPlanningResponseResultSuppliersInner) GetTotalCostOk() (*float32, bool)`

GetTotalCostOk returns a tuple with the TotalCost field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalCost

`func (o *InventoryPlanningResponseResultSuppliersInner) SetTotalCost(v float32)`

SetTotalCost sets TotalCost field to given value.

### HasTotalCost

`func (o *InventoryPlanningResponseResultSuppliersInner) HasTotalCost() bool`

HasTotalCost returns a boolean if a field has been set.

### GetCostPerUnit

`func (o *InventoryPlanningResponseResultSuppliersInner) GetCostPerUnit() float32`

GetCostPerUnit returns the CostPerUnit field if non-nil, zero value otherwise.

### GetCostPerUnitOk

`func (o *InventoryPlanningResponseResultSuppliersInner) GetCostPerUnitOk() (*float32, bool)`

GetCostPerUnitOk returns a tuple with the CostPerUnit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCostPerUnit

`func (o *InventoryPlanningResponseResultSuppliersInner) SetCostPerUnit(v float32)`

SetCostPerUnit sets CostPerUnit field to given value.

### HasCostPerUnit

`func (o *InventoryPlanningResponseResultSuppliersInner) HasCostPerUnit() bool`

HasCostPerUnit returns a boolean if a field has been set.

### GetExpectedDelivery

`func (o *InventoryPlanningResponseResultSuppliersInner) GetExpectedDelivery() string`

GetExpectedDelivery returns the ExpectedDelivery field if non-nil, zero value otherwise.

### GetExpectedDeliveryOk

`func (o *InventoryPlanningResponseResultSuppliersInner) GetExpectedDeliveryOk() (*string, bool)`

GetExpectedDeliveryOk returns a tuple with the ExpectedDelivery field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpectedDelivery

`func (o *InventoryPlanningResponseResultSuppliersInner) SetExpectedDelivery(v string)`

SetExpectedDelivery sets ExpectedDelivery field to given value.

### HasExpectedDelivery

`func (o *InventoryPlanningResponseResultSuppliersInner) HasExpectedDelivery() bool`

HasExpectedDelivery returns a boolean if a field has been set.

### GetLeadTimeDays

`func (o *InventoryPlanningResponseResultSuppliersInner) GetLeadTimeDays() float32`

GetLeadTimeDays returns the LeadTimeDays field if non-nil, zero value otherwise.

### GetLeadTimeDaysOk

`func (o *InventoryPlanningResponseResultSuppliersInner) GetLeadTimeDaysOk() (*float32, bool)`

GetLeadTimeDaysOk returns a tuple with the LeadTimeDays field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLeadTimeDays

`func (o *InventoryPlanningResponseResultSuppliersInner) SetLeadTimeDays(v float32)`

SetLeadTimeDays sets LeadTimeDays field to given value.

### HasLeadTimeDays

`func (o *InventoryPlanningResponseResultSuppliersInner) HasLeadTimeDays() bool`

HasLeadTimeDays returns a boolean if a field has been set.

### GetMinimumOrderQuantity

`func (o *InventoryPlanningResponseResultSuppliersInner) GetMinimumOrderQuantity() float32`

GetMinimumOrderQuantity returns the MinimumOrderQuantity field if non-nil, zero value otherwise.

### GetMinimumOrderQuantityOk

`func (o *InventoryPlanningResponseResultSuppliersInner) GetMinimumOrderQuantityOk() (*float32, bool)`

GetMinimumOrderQuantityOk returns a tuple with the MinimumOrderQuantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMinimumOrderQuantity

`func (o *InventoryPlanningResponseResultSuppliersInner) SetMinimumOrderQuantity(v float32)`

SetMinimumOrderQuantity sets MinimumOrderQuantity field to given value.

### HasMinimumOrderQuantity

`func (o *InventoryPlanningResponseResultSuppliersInner) HasMinimumOrderQuantity() bool`

HasMinimumOrderQuantity returns a boolean if a field has been set.

### GetReliabilityScore

`func (o *InventoryPlanningResponseResultSuppliersInner) GetReliabilityScore() float32`

GetReliabilityScore returns the ReliabilityScore field if non-nil, zero value otherwise.

### GetReliabilityScoreOk

`func (o *InventoryPlanningResponseResultSuppliersInner) GetReliabilityScoreOk() (*float32, bool)`

GetReliabilityScoreOk returns a tuple with the ReliabilityScore field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReliabilityScore

`func (o *InventoryPlanningResponseResultSuppliersInner) SetReliabilityScore(v float32)`

SetReliabilityScore sets ReliabilityScore field to given value.

### HasReliabilityScore

`func (o *InventoryPlanningResponseResultSuppliersInner) HasReliabilityScore() bool`

HasReliabilityScore returns a boolean if a field has been set.

### GetLeadTimeDemand

`func (o *InventoryPlanningResponseResultSuppliersInner) GetLeadTimeDemand() float32`

GetLeadTimeDemand returns the LeadTimeDemand field if non-nil, zero value otherwise.

### GetLeadTimeDemandOk

`func (o *InventoryPlanningResponseResultSuppliersInner) GetLeadTimeDemandOk() (*float32, bool)`

GetLeadTimeDemandOk returns a tuple with the LeadTimeDemand field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLeadTimeDemand

`func (o *InventoryPlanningResponseResultSuppliersInner) SetLeadTimeDemand(v float32)`

SetLeadTimeDemand sets LeadTimeDemand field to given value.

### HasLeadTimeDemand

`func (o *InventoryPlanningResponseResultSuppliersInner) HasLeadTimeDemand() bool`

HasLeadTimeDemand returns a boolean if a field has been set.

### GetSafetyStock

`func (o *InventoryPlanningResponseResultSuppliersInner) GetSafetyStock() float32`

GetSafetyStock returns the SafetyStock field if non-nil, zero value otherwise.

### GetSafetyStockOk

`func (o *InventoryPlanningResponseResultSuppliersInner) GetSafetyStockOk() (*float32, bool)`

GetSafetyStockOk returns a tuple with the SafetyStock field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSafetyStock

`func (o *InventoryPlanningResponseResultSuppliersInner) SetSafetyStock(v float32)`

SetSafetyStock sets SafetyStock field to given value.

### HasSafetyStock

`func (o *InventoryPlanningResponseResultSuppliersInner) HasSafetyStock() bool`

HasSafetyStock returns a boolean if a field has been set.

### GetReorderPoint

`func (o *InventoryPlanningResponseResultSuppliersInner) GetReorderPoint() float32`

GetReorderPoint returns the ReorderPoint field if non-nil, zero value otherwise.

### GetReorderPointOk

`func (o *InventoryPlanningResponseResultSuppliersInner) GetReorderPointOk() (*float32, bool)`

GetReorderPointOk returns a tuple with the ReorderPoint field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReorderPoint

`func (o *InventoryPlanningResponseResultSuppliersInner) SetReorderPoint(v float32)`

SetReorderPoint sets ReorderPoint field to given value.

### HasReorderPoint

`func (o *InventoryPlanningResponseResultSuppliersInner) HasReorderPoint() bool`

HasReorderPoint returns a boolean if a field has been set.

### GetReason

`func (o *InventoryPlanningResponseResultSuppliersInner) GetReason() string`

GetReason returns the Reason field if non-nil, zero value otherwise.

### GetReasonOk

`func (o *InventoryPlanningResponseResultSuppliersInner) GetReasonOk() (*string, bool)`

GetReasonOk returns a tuple with the Reason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReason

`func (o *InventoryPlanningResponseResultSuppliersInner) SetReason(v string)`

SetReason sets Reason field to given value.

### HasReason

`func (o *InventoryPlanningResponseResultSuppliersInner) HasReason() bool`

HasReason returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


