# InventoryPlanningResponseResultForecastDataInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Period** | Pointer to **int32** | Forecast period number | [optional] 
**Date** | Pointer to **string** | Date for this forecast period | [optional] 
**Forecast** | Pointer to **float32** | Forecasted demand for this period | [optional] 
**Lower** | Pointer to **float32** | Lower confidence bound | [optional] 
**Upper** | Pointer to **float32** | Upper confidence bound | [optional] 

## Methods

### NewInventoryPlanningResponseResultForecastDataInner

`func NewInventoryPlanningResponseResultForecastDataInner() *InventoryPlanningResponseResultForecastDataInner`

NewInventoryPlanningResponseResultForecastDataInner instantiates a new InventoryPlanningResponseResultForecastDataInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewInventoryPlanningResponseResultForecastDataInnerWithDefaults

`func NewInventoryPlanningResponseResultForecastDataInnerWithDefaults() *InventoryPlanningResponseResultForecastDataInner`

NewInventoryPlanningResponseResultForecastDataInnerWithDefaults instantiates a new InventoryPlanningResponseResultForecastDataInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPeriod

`func (o *InventoryPlanningResponseResultForecastDataInner) GetPeriod() int32`

GetPeriod returns the Period field if non-nil, zero value otherwise.

### GetPeriodOk

`func (o *InventoryPlanningResponseResultForecastDataInner) GetPeriodOk() (*int32, bool)`

GetPeriodOk returns a tuple with the Period field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPeriod

`func (o *InventoryPlanningResponseResultForecastDataInner) SetPeriod(v int32)`

SetPeriod sets Period field to given value.

### HasPeriod

`func (o *InventoryPlanningResponseResultForecastDataInner) HasPeriod() bool`

HasPeriod returns a boolean if a field has been set.

### GetDate

`func (o *InventoryPlanningResponseResultForecastDataInner) GetDate() string`

GetDate returns the Date field if non-nil, zero value otherwise.

### GetDateOk

`func (o *InventoryPlanningResponseResultForecastDataInner) GetDateOk() (*string, bool)`

GetDateOk returns a tuple with the Date field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDate

`func (o *InventoryPlanningResponseResultForecastDataInner) SetDate(v string)`

SetDate sets Date field to given value.

### HasDate

`func (o *InventoryPlanningResponseResultForecastDataInner) HasDate() bool`

HasDate returns a boolean if a field has been set.

### GetForecast

`func (o *InventoryPlanningResponseResultForecastDataInner) GetForecast() float32`

GetForecast returns the Forecast field if non-nil, zero value otherwise.

### GetForecastOk

`func (o *InventoryPlanningResponseResultForecastDataInner) GetForecastOk() (*float32, bool)`

GetForecastOk returns a tuple with the Forecast field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetForecast

`func (o *InventoryPlanningResponseResultForecastDataInner) SetForecast(v float32)`

SetForecast sets Forecast field to given value.

### HasForecast

`func (o *InventoryPlanningResponseResultForecastDataInner) HasForecast() bool`

HasForecast returns a boolean if a field has been set.

### GetLower

`func (o *InventoryPlanningResponseResultForecastDataInner) GetLower() float32`

GetLower returns the Lower field if non-nil, zero value otherwise.

### GetLowerOk

`func (o *InventoryPlanningResponseResultForecastDataInner) GetLowerOk() (*float32, bool)`

GetLowerOk returns a tuple with the Lower field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLower

`func (o *InventoryPlanningResponseResultForecastDataInner) SetLower(v float32)`

SetLower sets Lower field to given value.

### HasLower

`func (o *InventoryPlanningResponseResultForecastDataInner) HasLower() bool`

HasLower returns a boolean if a field has been set.

### GetUpper

`func (o *InventoryPlanningResponseResultForecastDataInner) GetUpper() float32`

GetUpper returns the Upper field if non-nil, zero value otherwise.

### GetUpperOk

`func (o *InventoryPlanningResponseResultForecastDataInner) GetUpperOk() (*float32, bool)`

GetUpperOk returns a tuple with the Upper field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpper

`func (o *InventoryPlanningResponseResultForecastDataInner) SetUpper(v float32)`

SetUpper sets Upper field to given value.

### HasUpper

`func (o *InventoryPlanningResponseResultForecastDataInner) HasUpper() bool`

HasUpper returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


