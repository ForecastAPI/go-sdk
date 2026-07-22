# BatchSeriesResult

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Identifier** | Pointer to **string** |  | [optional] 
**TenantContext** | Pointer to **NullableString** |  | [optional] 
**Forecasts** | Pointer to [**[]ForecastPeriod**](ForecastPeriod.md) |  | [optional] 
**ModelInfo** | Pointer to **map[string]interface{}** |  | [optional] 
**Adjusted** | Pointer to [**AdjustedForecast**](AdjustedForecast.md) |  | [optional] 
**Accumulated** | Pointer to [**AccumulatedForecast**](AccumulatedForecast.md) |  | [optional] 
**Error** | Pointer to **string** | Present instead of forecasts when this series failed | [optional] 

## Methods

### NewBatchSeriesResult

`func NewBatchSeriesResult() *BatchSeriesResult`

NewBatchSeriesResult instantiates a new BatchSeriesResult object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewBatchSeriesResultWithDefaults

`func NewBatchSeriesResultWithDefaults() *BatchSeriesResult`

NewBatchSeriesResultWithDefaults instantiates a new BatchSeriesResult object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetIdentifier

`func (o *BatchSeriesResult) GetIdentifier() string`

GetIdentifier returns the Identifier field if non-nil, zero value otherwise.

### GetIdentifierOk

`func (o *BatchSeriesResult) GetIdentifierOk() (*string, bool)`

GetIdentifierOk returns a tuple with the Identifier field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdentifier

`func (o *BatchSeriesResult) SetIdentifier(v string)`

SetIdentifier sets Identifier field to given value.

### HasIdentifier

`func (o *BatchSeriesResult) HasIdentifier() bool`

HasIdentifier returns a boolean if a field has been set.

### GetTenantContext

`func (o *BatchSeriesResult) GetTenantContext() string`

GetTenantContext returns the TenantContext field if non-nil, zero value otherwise.

### GetTenantContextOk

`func (o *BatchSeriesResult) GetTenantContextOk() (*string, bool)`

GetTenantContextOk returns a tuple with the TenantContext field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTenantContext

`func (o *BatchSeriesResult) SetTenantContext(v string)`

SetTenantContext sets TenantContext field to given value.

### HasTenantContext

`func (o *BatchSeriesResult) HasTenantContext() bool`

HasTenantContext returns a boolean if a field has been set.

### SetTenantContextNil

`func (o *BatchSeriesResult) SetTenantContextNil(b bool)`

 SetTenantContextNil sets the value for TenantContext to be an explicit nil

### UnsetTenantContext
`func (o *BatchSeriesResult) UnsetTenantContext()`

UnsetTenantContext ensures that no value is present for TenantContext, not even an explicit nil
### GetForecasts

`func (o *BatchSeriesResult) GetForecasts() []ForecastPeriod`

GetForecasts returns the Forecasts field if non-nil, zero value otherwise.

### GetForecastsOk

`func (o *BatchSeriesResult) GetForecastsOk() (*[]ForecastPeriod, bool)`

GetForecastsOk returns a tuple with the Forecasts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetForecasts

`func (o *BatchSeriesResult) SetForecasts(v []ForecastPeriod)`

SetForecasts sets Forecasts field to given value.

### HasForecasts

`func (o *BatchSeriesResult) HasForecasts() bool`

HasForecasts returns a boolean if a field has been set.

### GetModelInfo

`func (o *BatchSeriesResult) GetModelInfo() map[string]interface{}`

GetModelInfo returns the ModelInfo field if non-nil, zero value otherwise.

### GetModelInfoOk

`func (o *BatchSeriesResult) GetModelInfoOk() (*map[string]interface{}, bool)`

GetModelInfoOk returns a tuple with the ModelInfo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModelInfo

`func (o *BatchSeriesResult) SetModelInfo(v map[string]interface{})`

SetModelInfo sets ModelInfo field to given value.

### HasModelInfo

`func (o *BatchSeriesResult) HasModelInfo() bool`

HasModelInfo returns a boolean if a field has been set.

### GetAdjusted

`func (o *BatchSeriesResult) GetAdjusted() AdjustedForecast`

GetAdjusted returns the Adjusted field if non-nil, zero value otherwise.

### GetAdjustedOk

`func (o *BatchSeriesResult) GetAdjustedOk() (*AdjustedForecast, bool)`

GetAdjustedOk returns a tuple with the Adjusted field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAdjusted

`func (o *BatchSeriesResult) SetAdjusted(v AdjustedForecast)`

SetAdjusted sets Adjusted field to given value.

### HasAdjusted

`func (o *BatchSeriesResult) HasAdjusted() bool`

HasAdjusted returns a boolean if a field has been set.

### GetAccumulated

`func (o *BatchSeriesResult) GetAccumulated() AccumulatedForecast`

GetAccumulated returns the Accumulated field if non-nil, zero value otherwise.

### GetAccumulatedOk

`func (o *BatchSeriesResult) GetAccumulatedOk() (*AccumulatedForecast, bool)`

GetAccumulatedOk returns a tuple with the Accumulated field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccumulated

`func (o *BatchSeriesResult) SetAccumulated(v AccumulatedForecast)`

SetAccumulated sets Accumulated field to given value.

### HasAccumulated

`func (o *BatchSeriesResult) HasAccumulated() bool`

HasAccumulated returns a boolean if a field has been set.

### GetError

`func (o *BatchSeriesResult) GetError() string`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *BatchSeriesResult) GetErrorOk() (*string, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *BatchSeriesResult) SetError(v string)`

SetError sets Error field to given value.

### HasError

`func (o *BatchSeriesResult) HasError() bool`

HasError returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


