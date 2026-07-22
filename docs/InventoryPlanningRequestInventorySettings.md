# InventoryPlanningRequestInventorySettings

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CurrentStock** | **float32** | Current quantity in stock | 
**MinimumStock** | **float32** | Minimum stock level to maintain | 
**ServiceLevel** | **float32** | Target service level (probability of not stocking out) | 
**Suppliers** | [**[]InventoryPlanningRequestInventorySettingsSuppliersInner**](InventoryPlanningRequestInventorySettingsSuppliersInner.md) | Available suppliers with their characteristics | 

## Methods

### NewInventoryPlanningRequestInventorySettings

`func NewInventoryPlanningRequestInventorySettings(currentStock float32, minimumStock float32, serviceLevel float32, suppliers []InventoryPlanningRequestInventorySettingsSuppliersInner, ) *InventoryPlanningRequestInventorySettings`

NewInventoryPlanningRequestInventorySettings instantiates a new InventoryPlanningRequestInventorySettings object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewInventoryPlanningRequestInventorySettingsWithDefaults

`func NewInventoryPlanningRequestInventorySettingsWithDefaults() *InventoryPlanningRequestInventorySettings`

NewInventoryPlanningRequestInventorySettingsWithDefaults instantiates a new InventoryPlanningRequestInventorySettings object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCurrentStock

`func (o *InventoryPlanningRequestInventorySettings) GetCurrentStock() float32`

GetCurrentStock returns the CurrentStock field if non-nil, zero value otherwise.

### GetCurrentStockOk

`func (o *InventoryPlanningRequestInventorySettings) GetCurrentStockOk() (*float32, bool)`

GetCurrentStockOk returns a tuple with the CurrentStock field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrentStock

`func (o *InventoryPlanningRequestInventorySettings) SetCurrentStock(v float32)`

SetCurrentStock sets CurrentStock field to given value.


### GetMinimumStock

`func (o *InventoryPlanningRequestInventorySettings) GetMinimumStock() float32`

GetMinimumStock returns the MinimumStock field if non-nil, zero value otherwise.

### GetMinimumStockOk

`func (o *InventoryPlanningRequestInventorySettings) GetMinimumStockOk() (*float32, bool)`

GetMinimumStockOk returns a tuple with the MinimumStock field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMinimumStock

`func (o *InventoryPlanningRequestInventorySettings) SetMinimumStock(v float32)`

SetMinimumStock sets MinimumStock field to given value.


### GetServiceLevel

`func (o *InventoryPlanningRequestInventorySettings) GetServiceLevel() float32`

GetServiceLevel returns the ServiceLevel field if non-nil, zero value otherwise.

### GetServiceLevelOk

`func (o *InventoryPlanningRequestInventorySettings) GetServiceLevelOk() (*float32, bool)`

GetServiceLevelOk returns a tuple with the ServiceLevel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServiceLevel

`func (o *InventoryPlanningRequestInventorySettings) SetServiceLevel(v float32)`

SetServiceLevel sets ServiceLevel field to given value.


### GetSuppliers

`func (o *InventoryPlanningRequestInventorySettings) GetSuppliers() []InventoryPlanningRequestInventorySettingsSuppliersInner`

GetSuppliers returns the Suppliers field if non-nil, zero value otherwise.

### GetSuppliersOk

`func (o *InventoryPlanningRequestInventorySettings) GetSuppliersOk() (*[]InventoryPlanningRequestInventorySettingsSuppliersInner, bool)`

GetSuppliersOk returns a tuple with the Suppliers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuppliers

`func (o *InventoryPlanningRequestInventorySettings) SetSuppliers(v []InventoryPlanningRequestInventorySettingsSuppliersInner)`

SetSuppliers sets Suppliers field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


