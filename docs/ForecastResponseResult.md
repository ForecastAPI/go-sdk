# ForecastResponseResult

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Identifier** | Pointer to **string** | Echoes the series identifier from the request | [optional] 
**TenantContext** | Pointer to **NullableString** |  | [optional] 
**Forecasts** | Pointer to [**[]ForecastPeriod**](ForecastPeriod.md) | One row per forecast period. Each period carries its own bounds, and they widen with horizon. | [optional] 
**ModelInfo** | Pointer to **map[string]interface{}** | The selected model (&#x60;best_model&#x60;), the models evaluated, the interval source, and per-model back-testing scores (smape/mape/mase) when validation runs. Also carries &#x60;bounds_transform&#x60; when &#x60;value_bounds&#x60; was sent, &#x60;quantile_levels&#x60; when a fan was requested, and &#x60;auto_selection&#x60; (see the AutoSelection schema) when &#x60;model: auto&#x60; was requested.  | [optional] 

## Methods

### NewForecastResponseResult

`func NewForecastResponseResult() *ForecastResponseResult`

NewForecastResponseResult instantiates a new ForecastResponseResult object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewForecastResponseResultWithDefaults

`func NewForecastResponseResultWithDefaults() *ForecastResponseResult`

NewForecastResponseResultWithDefaults instantiates a new ForecastResponseResult object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetIdentifier

`func (o *ForecastResponseResult) GetIdentifier() string`

GetIdentifier returns the Identifier field if non-nil, zero value otherwise.

### GetIdentifierOk

`func (o *ForecastResponseResult) GetIdentifierOk() (*string, bool)`

GetIdentifierOk returns a tuple with the Identifier field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdentifier

`func (o *ForecastResponseResult) SetIdentifier(v string)`

SetIdentifier sets Identifier field to given value.

### HasIdentifier

`func (o *ForecastResponseResult) HasIdentifier() bool`

HasIdentifier returns a boolean if a field has been set.

### GetTenantContext

`func (o *ForecastResponseResult) GetTenantContext() string`

GetTenantContext returns the TenantContext field if non-nil, zero value otherwise.

### GetTenantContextOk

`func (o *ForecastResponseResult) GetTenantContextOk() (*string, bool)`

GetTenantContextOk returns a tuple with the TenantContext field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTenantContext

`func (o *ForecastResponseResult) SetTenantContext(v string)`

SetTenantContext sets TenantContext field to given value.

### HasTenantContext

`func (o *ForecastResponseResult) HasTenantContext() bool`

HasTenantContext returns a boolean if a field has been set.

### SetTenantContextNil

`func (o *ForecastResponseResult) SetTenantContextNil(b bool)`

 SetTenantContextNil sets the value for TenantContext to be an explicit nil

### UnsetTenantContext
`func (o *ForecastResponseResult) UnsetTenantContext()`

UnsetTenantContext ensures that no value is present for TenantContext, not even an explicit nil
### GetForecasts

`func (o *ForecastResponseResult) GetForecasts() []ForecastPeriod`

GetForecasts returns the Forecasts field if non-nil, zero value otherwise.

### GetForecastsOk

`func (o *ForecastResponseResult) GetForecastsOk() (*[]ForecastPeriod, bool)`

GetForecastsOk returns a tuple with the Forecasts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetForecasts

`func (o *ForecastResponseResult) SetForecasts(v []ForecastPeriod)`

SetForecasts sets Forecasts field to given value.

### HasForecasts

`func (o *ForecastResponseResult) HasForecasts() bool`

HasForecasts returns a boolean if a field has been set.

### GetModelInfo

`func (o *ForecastResponseResult) GetModelInfo() map[string]interface{}`

GetModelInfo returns the ModelInfo field if non-nil, zero value otherwise.

### GetModelInfoOk

`func (o *ForecastResponseResult) GetModelInfoOk() (*map[string]interface{}, bool)`

GetModelInfoOk returns a tuple with the ModelInfo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModelInfo

`func (o *ForecastResponseResult) SetModelInfo(v map[string]interface{})`

SetModelInfo sets ModelInfo field to given value.

### HasModelInfo

`func (o *ForecastResponseResult) HasModelInfo() bool`

HasModelInfo returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


