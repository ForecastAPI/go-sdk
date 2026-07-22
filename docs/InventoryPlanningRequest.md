# InventoryPlanningRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Identifier** | **string** | SKU, Product ID, or other identifier for the inventory item | 
**Frequency** | **string** | Data frequency for forecasting: - D: Daily - W: Weekly - M: Monthly (end of month) - MS: Monthly (start of month) - ME: Monthly (end of month) - Q: Quarterly - Y: Yearly  | 
**StartDate** | Pointer to **NullableString** | Optional start date for the forecast period | [optional] 
**Periods** | **int32** | Number of periods to forecast ahead | 
**EnableIntelligentAggregation** | Pointer to **bool** | Enable intelligent data aggregation for improved forecasting | [optional] 
**ConfidenceLevel** | Pointer to **float32** | Confidence level for forecast intervals (default 0.95) | [optional] 
**Data** | [**[]InventoryPlanningRequestDataInner**](InventoryPlanningRequestDataInner.md) | Historical demand/sales data for forecasting | 
**InventorySettings** | [**InventoryPlanningRequestInventorySettings**](InventoryPlanningRequestInventorySettings.md) |  | 

## Methods

### NewInventoryPlanningRequest

`func NewInventoryPlanningRequest(identifier string, frequency string, periods int32, data []InventoryPlanningRequestDataInner, inventorySettings InventoryPlanningRequestInventorySettings, ) *InventoryPlanningRequest`

NewInventoryPlanningRequest instantiates a new InventoryPlanningRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewInventoryPlanningRequestWithDefaults

`func NewInventoryPlanningRequestWithDefaults() *InventoryPlanningRequest`

NewInventoryPlanningRequestWithDefaults instantiates a new InventoryPlanningRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetIdentifier

`func (o *InventoryPlanningRequest) GetIdentifier() string`

GetIdentifier returns the Identifier field if non-nil, zero value otherwise.

### GetIdentifierOk

`func (o *InventoryPlanningRequest) GetIdentifierOk() (*string, bool)`

GetIdentifierOk returns a tuple with the Identifier field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdentifier

`func (o *InventoryPlanningRequest) SetIdentifier(v string)`

SetIdentifier sets Identifier field to given value.


### GetFrequency

`func (o *InventoryPlanningRequest) GetFrequency() string`

GetFrequency returns the Frequency field if non-nil, zero value otherwise.

### GetFrequencyOk

`func (o *InventoryPlanningRequest) GetFrequencyOk() (*string, bool)`

GetFrequencyOk returns a tuple with the Frequency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFrequency

`func (o *InventoryPlanningRequest) SetFrequency(v string)`

SetFrequency sets Frequency field to given value.


### GetStartDate

`func (o *InventoryPlanningRequest) GetStartDate() string`

GetStartDate returns the StartDate field if non-nil, zero value otherwise.

### GetStartDateOk

`func (o *InventoryPlanningRequest) GetStartDateOk() (*string, bool)`

GetStartDateOk returns a tuple with the StartDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartDate

`func (o *InventoryPlanningRequest) SetStartDate(v string)`

SetStartDate sets StartDate field to given value.

### HasStartDate

`func (o *InventoryPlanningRequest) HasStartDate() bool`

HasStartDate returns a boolean if a field has been set.

### SetStartDateNil

`func (o *InventoryPlanningRequest) SetStartDateNil(b bool)`

 SetStartDateNil sets the value for StartDate to be an explicit nil

### UnsetStartDate
`func (o *InventoryPlanningRequest) UnsetStartDate()`

UnsetStartDate ensures that no value is present for StartDate, not even an explicit nil
### GetPeriods

`func (o *InventoryPlanningRequest) GetPeriods() int32`

GetPeriods returns the Periods field if non-nil, zero value otherwise.

### GetPeriodsOk

`func (o *InventoryPlanningRequest) GetPeriodsOk() (*int32, bool)`

GetPeriodsOk returns a tuple with the Periods field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPeriods

`func (o *InventoryPlanningRequest) SetPeriods(v int32)`

SetPeriods sets Periods field to given value.


### GetEnableIntelligentAggregation

`func (o *InventoryPlanningRequest) GetEnableIntelligentAggregation() bool`

GetEnableIntelligentAggregation returns the EnableIntelligentAggregation field if non-nil, zero value otherwise.

### GetEnableIntelligentAggregationOk

`func (o *InventoryPlanningRequest) GetEnableIntelligentAggregationOk() (*bool, bool)`

GetEnableIntelligentAggregationOk returns a tuple with the EnableIntelligentAggregation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnableIntelligentAggregation

`func (o *InventoryPlanningRequest) SetEnableIntelligentAggregation(v bool)`

SetEnableIntelligentAggregation sets EnableIntelligentAggregation field to given value.

### HasEnableIntelligentAggregation

`func (o *InventoryPlanningRequest) HasEnableIntelligentAggregation() bool`

HasEnableIntelligentAggregation returns a boolean if a field has been set.

### GetConfidenceLevel

`func (o *InventoryPlanningRequest) GetConfidenceLevel() float32`

GetConfidenceLevel returns the ConfidenceLevel field if non-nil, zero value otherwise.

### GetConfidenceLevelOk

`func (o *InventoryPlanningRequest) GetConfidenceLevelOk() (*float32, bool)`

GetConfidenceLevelOk returns a tuple with the ConfidenceLevel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConfidenceLevel

`func (o *InventoryPlanningRequest) SetConfidenceLevel(v float32)`

SetConfidenceLevel sets ConfidenceLevel field to given value.

### HasConfidenceLevel

`func (o *InventoryPlanningRequest) HasConfidenceLevel() bool`

HasConfidenceLevel returns a boolean if a field has been set.

### GetData

`func (o *InventoryPlanningRequest) GetData() []InventoryPlanningRequestDataInner`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *InventoryPlanningRequest) GetDataOk() (*[]InventoryPlanningRequestDataInner, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *InventoryPlanningRequest) SetData(v []InventoryPlanningRequestDataInner)`

SetData sets Data field to given value.


### GetInventorySettings

`func (o *InventoryPlanningRequest) GetInventorySettings() InventoryPlanningRequestInventorySettings`

GetInventorySettings returns the InventorySettings field if non-nil, zero value otherwise.

### GetInventorySettingsOk

`func (o *InventoryPlanningRequest) GetInventorySettingsOk() (*InventoryPlanningRequestInventorySettings, bool)`

GetInventorySettingsOk returns a tuple with the InventorySettings field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInventorySettings

`func (o *InventoryPlanningRequest) SetInventorySettings(v InventoryPlanningRequestInventorySettings)`

SetInventorySettings sets InventorySettings field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


