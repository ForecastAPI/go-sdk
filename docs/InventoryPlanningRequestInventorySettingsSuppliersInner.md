# InventoryPlanningRequestInventorySettingsSuppliersInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Identifier** | **string** | Unique supplier identifier | 
**LeadTimeDays** | **float32** | Lead time in days for this supplier | 
**MinimumOrderQuantity** | **float32** | Minimum order quantity required by supplier | 
**CostPerUnit** | **float32** | Cost per unit from this supplier | 
**ReliabilityScore** | Pointer to **NullableFloat32** | Supplier reliability score (0.1-1.0, default 1.0) | [optional] 

## Methods

### NewInventoryPlanningRequestInventorySettingsSuppliersInner

`func NewInventoryPlanningRequestInventorySettingsSuppliersInner(identifier string, leadTimeDays float32, minimumOrderQuantity float32, costPerUnit float32, ) *InventoryPlanningRequestInventorySettingsSuppliersInner`

NewInventoryPlanningRequestInventorySettingsSuppliersInner instantiates a new InventoryPlanningRequestInventorySettingsSuppliersInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewInventoryPlanningRequestInventorySettingsSuppliersInnerWithDefaults

`func NewInventoryPlanningRequestInventorySettingsSuppliersInnerWithDefaults() *InventoryPlanningRequestInventorySettingsSuppliersInner`

NewInventoryPlanningRequestInventorySettingsSuppliersInnerWithDefaults instantiates a new InventoryPlanningRequestInventorySettingsSuppliersInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetIdentifier

`func (o *InventoryPlanningRequestInventorySettingsSuppliersInner) GetIdentifier() string`

GetIdentifier returns the Identifier field if non-nil, zero value otherwise.

### GetIdentifierOk

`func (o *InventoryPlanningRequestInventorySettingsSuppliersInner) GetIdentifierOk() (*string, bool)`

GetIdentifierOk returns a tuple with the Identifier field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdentifier

`func (o *InventoryPlanningRequestInventorySettingsSuppliersInner) SetIdentifier(v string)`

SetIdentifier sets Identifier field to given value.


### GetLeadTimeDays

`func (o *InventoryPlanningRequestInventorySettingsSuppliersInner) GetLeadTimeDays() float32`

GetLeadTimeDays returns the LeadTimeDays field if non-nil, zero value otherwise.

### GetLeadTimeDaysOk

`func (o *InventoryPlanningRequestInventorySettingsSuppliersInner) GetLeadTimeDaysOk() (*float32, bool)`

GetLeadTimeDaysOk returns a tuple with the LeadTimeDays field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLeadTimeDays

`func (o *InventoryPlanningRequestInventorySettingsSuppliersInner) SetLeadTimeDays(v float32)`

SetLeadTimeDays sets LeadTimeDays field to given value.


### GetMinimumOrderQuantity

`func (o *InventoryPlanningRequestInventorySettingsSuppliersInner) GetMinimumOrderQuantity() float32`

GetMinimumOrderQuantity returns the MinimumOrderQuantity field if non-nil, zero value otherwise.

### GetMinimumOrderQuantityOk

`func (o *InventoryPlanningRequestInventorySettingsSuppliersInner) GetMinimumOrderQuantityOk() (*float32, bool)`

GetMinimumOrderQuantityOk returns a tuple with the MinimumOrderQuantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMinimumOrderQuantity

`func (o *InventoryPlanningRequestInventorySettingsSuppliersInner) SetMinimumOrderQuantity(v float32)`

SetMinimumOrderQuantity sets MinimumOrderQuantity field to given value.


### GetCostPerUnit

`func (o *InventoryPlanningRequestInventorySettingsSuppliersInner) GetCostPerUnit() float32`

GetCostPerUnit returns the CostPerUnit field if non-nil, zero value otherwise.

### GetCostPerUnitOk

`func (o *InventoryPlanningRequestInventorySettingsSuppliersInner) GetCostPerUnitOk() (*float32, bool)`

GetCostPerUnitOk returns a tuple with the CostPerUnit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCostPerUnit

`func (o *InventoryPlanningRequestInventorySettingsSuppliersInner) SetCostPerUnit(v float32)`

SetCostPerUnit sets CostPerUnit field to given value.


### GetReliabilityScore

`func (o *InventoryPlanningRequestInventorySettingsSuppliersInner) GetReliabilityScore() float32`

GetReliabilityScore returns the ReliabilityScore field if non-nil, zero value otherwise.

### GetReliabilityScoreOk

`func (o *InventoryPlanningRequestInventorySettingsSuppliersInner) GetReliabilityScoreOk() (*float32, bool)`

GetReliabilityScoreOk returns a tuple with the ReliabilityScore field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReliabilityScore

`func (o *InventoryPlanningRequestInventorySettingsSuppliersInner) SetReliabilityScore(v float32)`

SetReliabilityScore sets ReliabilityScore field to given value.

### HasReliabilityScore

`func (o *InventoryPlanningRequestInventorySettingsSuppliersInner) HasReliabilityScore() bool`

HasReliabilityScore returns a boolean if a field has been set.

### SetReliabilityScoreNil

`func (o *InventoryPlanningRequestInventorySettingsSuppliersInner) SetReliabilityScoreNil(b bool)`

 SetReliabilityScoreNil sets the value for ReliabilityScore to be an explicit nil

### UnsetReliabilityScore
`func (o *InventoryPlanningRequestInventorySettingsSuppliersInner) UnsetReliabilityScore()`

UnsetReliabilityScore ensures that no value is present for ReliabilityScore, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


