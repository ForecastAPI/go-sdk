# InventoryPlanningRequestDataInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Date** | **string** | Date of the data point (YYYY-MM-DD format) | 
**Value** | **float32** | Demand/sales quantity for the date | 

## Methods

### NewInventoryPlanningRequestDataInner

`func NewInventoryPlanningRequestDataInner(date string, value float32, ) *InventoryPlanningRequestDataInner`

NewInventoryPlanningRequestDataInner instantiates a new InventoryPlanningRequestDataInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewInventoryPlanningRequestDataInnerWithDefaults

`func NewInventoryPlanningRequestDataInnerWithDefaults() *InventoryPlanningRequestDataInner`

NewInventoryPlanningRequestDataInnerWithDefaults instantiates a new InventoryPlanningRequestDataInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDate

`func (o *InventoryPlanningRequestDataInner) GetDate() string`

GetDate returns the Date field if non-nil, zero value otherwise.

### GetDateOk

`func (o *InventoryPlanningRequestDataInner) GetDateOk() (*string, bool)`

GetDateOk returns a tuple with the Date field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDate

`func (o *InventoryPlanningRequestDataInner) SetDate(v string)`

SetDate sets Date field to given value.


### GetValue

`func (o *InventoryPlanningRequestDataInner) GetValue() float32`

GetValue returns the Value field if non-nil, zero value otherwise.

### GetValueOk

`func (o *InventoryPlanningRequestDataInner) GetValueOk() (*float32, bool)`

GetValueOk returns a tuple with the Value field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValue

`func (o *InventoryPlanningRequestDataInner) SetValue(v float32)`

SetValue sets Value field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


