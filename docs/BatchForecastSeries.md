# BatchForecastSeries

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Identifier** | **string** | SKU, Product ID, or other identifier for this series | 
**TenantContext** | Pointer to **NullableString** | Optional segmentation dimension — the same identifier may appear under several tenant_context values in one batch | [optional] 
**Data** | [**[]BatchForecastSeriesDataInner**](BatchForecastSeriesDataInner.md) | Historical data for this series (at most 1,000 points per series on the free tier) | 
**Periods** | Pointer to **int32** | Override of the request-level horizon for this series | [optional] 
**Frequency** | Pointer to **string** | Override of the request-level frequency | [optional] 
**DataType** | Pointer to **string** | Override of the request-level data type | [optional] 
**Confidence** | Pointer to **float32** | Override of the request-level confidence | [optional] 
**ConfidenceLevel** | Pointer to **float32** | Alias for &#x60;confidence&#x60; | [optional] 
**Model** | Pointer to **string** | Override of the request-level forecasting engine for this series | [optional] 
**Quantiles** | Pointer to **[]float32** | Decile levels to return per period — only deciles between 0.1 and 0.9 are accepted, because those are the levels every backend produces natively; anything finer would be interpolation served under a label the model never predicted. Adds a &#x60;quantiles&#x60; object to each forecast row alongside the usual bounds. Honoured by /v2/forecast and /v2/batch/forecast (request-level default or per-series override); rejected on grouped forecasts; ignored by other endpoints sharing this request shape.  | [optional] 
**ValueBounds** | Pointer to [**ValueBounds**](ValueBounds.md) |  | [optional] 
**Adjustments** | Pointer to [**[]AdjustmentsInner**](AdjustmentsInner.md) | What-if scenario applied on top of the forecast (\&quot;assume we lose the enterprise deal\&quot;). Adjustments compose in array order — ×2 then +50 is not +50 then ×2. Each one moves the point, both bounds and any quantile fan together. Returns an &#x60;adjusted&#x60; block; the adjusted path is never stored or accuracy-tracked. Honoured by /v2/forecast and /v2/batch/forecast (request-level default or per-series override — period windows are checked against each series&#39; own horizon); rejected on grouped forecasts; ignored by other endpoints sharing this request shape.  | [optional] 
**Accumulate** | Pointer to [**AccumulateOptions**](AccumulateOptions.md) |  | [optional] 

## Methods

### NewBatchForecastSeries

`func NewBatchForecastSeries(identifier string, data []BatchForecastSeriesDataInner, ) *BatchForecastSeries`

NewBatchForecastSeries instantiates a new BatchForecastSeries object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewBatchForecastSeriesWithDefaults

`func NewBatchForecastSeriesWithDefaults() *BatchForecastSeries`

NewBatchForecastSeriesWithDefaults instantiates a new BatchForecastSeries object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetIdentifier

`func (o *BatchForecastSeries) GetIdentifier() string`

GetIdentifier returns the Identifier field if non-nil, zero value otherwise.

### GetIdentifierOk

`func (o *BatchForecastSeries) GetIdentifierOk() (*string, bool)`

GetIdentifierOk returns a tuple with the Identifier field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdentifier

`func (o *BatchForecastSeries) SetIdentifier(v string)`

SetIdentifier sets Identifier field to given value.


### GetTenantContext

`func (o *BatchForecastSeries) GetTenantContext() string`

GetTenantContext returns the TenantContext field if non-nil, zero value otherwise.

### GetTenantContextOk

`func (o *BatchForecastSeries) GetTenantContextOk() (*string, bool)`

GetTenantContextOk returns a tuple with the TenantContext field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTenantContext

`func (o *BatchForecastSeries) SetTenantContext(v string)`

SetTenantContext sets TenantContext field to given value.

### HasTenantContext

`func (o *BatchForecastSeries) HasTenantContext() bool`

HasTenantContext returns a boolean if a field has been set.

### SetTenantContextNil

`func (o *BatchForecastSeries) SetTenantContextNil(b bool)`

 SetTenantContextNil sets the value for TenantContext to be an explicit nil

### UnsetTenantContext
`func (o *BatchForecastSeries) UnsetTenantContext()`

UnsetTenantContext ensures that no value is present for TenantContext, not even an explicit nil
### GetData

`func (o *BatchForecastSeries) GetData() []BatchForecastSeriesDataInner`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *BatchForecastSeries) GetDataOk() (*[]BatchForecastSeriesDataInner, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *BatchForecastSeries) SetData(v []BatchForecastSeriesDataInner)`

SetData sets Data field to given value.


### GetPeriods

`func (o *BatchForecastSeries) GetPeriods() int32`

GetPeriods returns the Periods field if non-nil, zero value otherwise.

### GetPeriodsOk

`func (o *BatchForecastSeries) GetPeriodsOk() (*int32, bool)`

GetPeriodsOk returns a tuple with the Periods field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPeriods

`func (o *BatchForecastSeries) SetPeriods(v int32)`

SetPeriods sets Periods field to given value.

### HasPeriods

`func (o *BatchForecastSeries) HasPeriods() bool`

HasPeriods returns a boolean if a field has been set.

### GetFrequency

`func (o *BatchForecastSeries) GetFrequency() string`

GetFrequency returns the Frequency field if non-nil, zero value otherwise.

### GetFrequencyOk

`func (o *BatchForecastSeries) GetFrequencyOk() (*string, bool)`

GetFrequencyOk returns a tuple with the Frequency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFrequency

`func (o *BatchForecastSeries) SetFrequency(v string)`

SetFrequency sets Frequency field to given value.

### HasFrequency

`func (o *BatchForecastSeries) HasFrequency() bool`

HasFrequency returns a boolean if a field has been set.

### GetDataType

`func (o *BatchForecastSeries) GetDataType() string`

GetDataType returns the DataType field if non-nil, zero value otherwise.

### GetDataTypeOk

`func (o *BatchForecastSeries) GetDataTypeOk() (*string, bool)`

GetDataTypeOk returns a tuple with the DataType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDataType

`func (o *BatchForecastSeries) SetDataType(v string)`

SetDataType sets DataType field to given value.

### HasDataType

`func (o *BatchForecastSeries) HasDataType() bool`

HasDataType returns a boolean if a field has been set.

### GetConfidence

`func (o *BatchForecastSeries) GetConfidence() float32`

GetConfidence returns the Confidence field if non-nil, zero value otherwise.

### GetConfidenceOk

`func (o *BatchForecastSeries) GetConfidenceOk() (*float32, bool)`

GetConfidenceOk returns a tuple with the Confidence field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConfidence

`func (o *BatchForecastSeries) SetConfidence(v float32)`

SetConfidence sets Confidence field to given value.

### HasConfidence

`func (o *BatchForecastSeries) HasConfidence() bool`

HasConfidence returns a boolean if a field has been set.

### GetConfidenceLevel

`func (o *BatchForecastSeries) GetConfidenceLevel() float32`

GetConfidenceLevel returns the ConfidenceLevel field if non-nil, zero value otherwise.

### GetConfidenceLevelOk

`func (o *BatchForecastSeries) GetConfidenceLevelOk() (*float32, bool)`

GetConfidenceLevelOk returns a tuple with the ConfidenceLevel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConfidenceLevel

`func (o *BatchForecastSeries) SetConfidenceLevel(v float32)`

SetConfidenceLevel sets ConfidenceLevel field to given value.

### HasConfidenceLevel

`func (o *BatchForecastSeries) HasConfidenceLevel() bool`

HasConfidenceLevel returns a boolean if a field has been set.

### GetModel

`func (o *BatchForecastSeries) GetModel() string`

GetModel returns the Model field if non-nil, zero value otherwise.

### GetModelOk

`func (o *BatchForecastSeries) GetModelOk() (*string, bool)`

GetModelOk returns a tuple with the Model field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModel

`func (o *BatchForecastSeries) SetModel(v string)`

SetModel sets Model field to given value.

### HasModel

`func (o *BatchForecastSeries) HasModel() bool`

HasModel returns a boolean if a field has been set.

### GetQuantiles

`func (o *BatchForecastSeries) GetQuantiles() []float32`

GetQuantiles returns the Quantiles field if non-nil, zero value otherwise.

### GetQuantilesOk

`func (o *BatchForecastSeries) GetQuantilesOk() (*[]float32, bool)`

GetQuantilesOk returns a tuple with the Quantiles field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantiles

`func (o *BatchForecastSeries) SetQuantiles(v []float32)`

SetQuantiles sets Quantiles field to given value.

### HasQuantiles

`func (o *BatchForecastSeries) HasQuantiles() bool`

HasQuantiles returns a boolean if a field has been set.

### GetValueBounds

`func (o *BatchForecastSeries) GetValueBounds() ValueBounds`

GetValueBounds returns the ValueBounds field if non-nil, zero value otherwise.

### GetValueBoundsOk

`func (o *BatchForecastSeries) GetValueBoundsOk() (*ValueBounds, bool)`

GetValueBoundsOk returns a tuple with the ValueBounds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValueBounds

`func (o *BatchForecastSeries) SetValueBounds(v ValueBounds)`

SetValueBounds sets ValueBounds field to given value.

### HasValueBounds

`func (o *BatchForecastSeries) HasValueBounds() bool`

HasValueBounds returns a boolean if a field has been set.

### GetAdjustments

`func (o *BatchForecastSeries) GetAdjustments() []AdjustmentsInner`

GetAdjustments returns the Adjustments field if non-nil, zero value otherwise.

### GetAdjustmentsOk

`func (o *BatchForecastSeries) GetAdjustmentsOk() (*[]AdjustmentsInner, bool)`

GetAdjustmentsOk returns a tuple with the Adjustments field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAdjustments

`func (o *BatchForecastSeries) SetAdjustments(v []AdjustmentsInner)`

SetAdjustments sets Adjustments field to given value.

### HasAdjustments

`func (o *BatchForecastSeries) HasAdjustments() bool`

HasAdjustments returns a boolean if a field has been set.

### GetAccumulate

`func (o *BatchForecastSeries) GetAccumulate() AccumulateOptions`

GetAccumulate returns the Accumulate field if non-nil, zero value otherwise.

### GetAccumulateOk

`func (o *BatchForecastSeries) GetAccumulateOk() (*AccumulateOptions, bool)`

GetAccumulateOk returns a tuple with the Accumulate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccumulate

`func (o *BatchForecastSeries) SetAccumulate(v AccumulateOptions)`

SetAccumulate sets Accumulate field to given value.

### HasAccumulate

`func (o *BatchForecastSeries) HasAccumulate() bool`

HasAccumulate returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


