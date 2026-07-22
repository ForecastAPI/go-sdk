# AnomalyDetectionRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Identifier** | **string** | SKU, Product ID, or other identifier for the data series | 
**TenantContext** | Pointer to **NullableString** | Optional segmentation dimension. A series is identified by the pair identifier + tenant_context, so \&quot;mrr\&quot; on \&quot;plan-pro\&quot; and \&quot;mrr\&quot; on \&quot;plan-free\&quot; are two independent series, each with its own history and accuracy tracking. Despite the name it isn&#39;t only for multi-tenancy — use it for any slice: plan, region, store, channel, cohort, device type.  | [optional] 
**Frequency** | **string** | Data frequency: - H: Hourly - D: Daily - W: Weekly - M: Monthly (end of month) - MS: Monthly (start of month) - ME: Monthly (end of month) - Q: Quarterly - Y: Yearly  | 
**StartDate** | Pointer to **NullableString** | Optional start date for the forecast | [optional] 
**DataType** | **string** | Type of data (e.g., sales, demand, inventory, web_traffic) | 
**Periods** | **int32** | Number of periods to forecast | 
**Model** | Pointer to **string** | Which forecasting engine to use. The advanced variants and ensemble provide higher accuracy at a higher usage cost than standard.  | [optional] [default to "standard"]
**ConfidenceLevel** | Pointer to **float32** | Confidence level for the prediction interval. Note that 0.80 is the widest band the foundation models (advanced-quantized, advanced-patched, ensemble) produce natively — for genuinely distinct levels beyond that, request a quantile fan via &#x60;quantiles&#x60; instead of repeating the call at several confidence levels.  | [optional] [default to 0.8]
**Quantiles** | Pointer to **[]float32** | Decile levels to return per period — only deciles between 0.1 and 0.9 are accepted, because those are the levels every backend produces natively; anything finer would be interpolation served under a label the model never predicted. Adds a &#x60;quantiles&#x60; object to each forecast row alongside the usual bounds. Honoured by /v2/forecast and /v2/batch/forecast (request-level default or per-series override); rejected on grouped forecasts; ignored by other endpoints sharing this request shape.  | [optional] 
**ValueBounds** | Pointer to [**ValueBounds**](ValueBounds.md) |  | [optional] 
**Adjustments** | Pointer to [**[]AdjustmentsInner**](AdjustmentsInner.md) | What-if scenario applied on top of the forecast (\&quot;assume we lose the enterprise deal\&quot;). Adjustments compose in array order — ×2 then +50 is not +50 then ×2. Each one moves the point, both bounds and any quantile fan together. Returns an &#x60;adjusted&#x60; block; the adjusted path is never stored or accuracy-tracked. Honoured by /v2/forecast and /v2/batch/forecast (request-level default or per-series override — period windows are checked against each series&#39; own horizon); rejected on grouped forecasts; ignored by other endpoints sharing this request shape.  | [optional] 
**Accumulate** | Pointer to [**AccumulateOptions**](AccumulateOptions.md) |  | [optional] 
**SelectionMetric** | Pointer to **NullableString** | Which back-testing error metric decides the winning model when candidates are compared: - auto: combined for demand/sales/inventory, sMAPE otherwise (default) - combined: 0.6·MASE + 0.4·sMAPE — balances accuracy and trend capture - mase: Mean Absolute Scaled Error — accuracy relative to a naive forecast - smape: Symmetric Mean Absolute Percentage Error  | [optional] 
**Data** | [**[]ForecastRequestDataInner**](ForecastRequestDataInner.md) | Historical time series data | 
**AnomalySettings** | Pointer to [**NullableAnomalyDetectionRequestAllOfAnomalySettings**](AnomalyDetectionRequestAllOfAnomalySettings.md) |  | [optional] 

## Methods

### NewAnomalyDetectionRequest

`func NewAnomalyDetectionRequest(identifier string, frequency string, dataType string, periods int32, data []ForecastRequestDataInner, ) *AnomalyDetectionRequest`

NewAnomalyDetectionRequest instantiates a new AnomalyDetectionRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAnomalyDetectionRequestWithDefaults

`func NewAnomalyDetectionRequestWithDefaults() *AnomalyDetectionRequest`

NewAnomalyDetectionRequestWithDefaults instantiates a new AnomalyDetectionRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetIdentifier

`func (o *AnomalyDetectionRequest) GetIdentifier() string`

GetIdentifier returns the Identifier field if non-nil, zero value otherwise.

### GetIdentifierOk

`func (o *AnomalyDetectionRequest) GetIdentifierOk() (*string, bool)`

GetIdentifierOk returns a tuple with the Identifier field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdentifier

`func (o *AnomalyDetectionRequest) SetIdentifier(v string)`

SetIdentifier sets Identifier field to given value.


### GetTenantContext

`func (o *AnomalyDetectionRequest) GetTenantContext() string`

GetTenantContext returns the TenantContext field if non-nil, zero value otherwise.

### GetTenantContextOk

`func (o *AnomalyDetectionRequest) GetTenantContextOk() (*string, bool)`

GetTenantContextOk returns a tuple with the TenantContext field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTenantContext

`func (o *AnomalyDetectionRequest) SetTenantContext(v string)`

SetTenantContext sets TenantContext field to given value.

### HasTenantContext

`func (o *AnomalyDetectionRequest) HasTenantContext() bool`

HasTenantContext returns a boolean if a field has been set.

### SetTenantContextNil

`func (o *AnomalyDetectionRequest) SetTenantContextNil(b bool)`

 SetTenantContextNil sets the value for TenantContext to be an explicit nil

### UnsetTenantContext
`func (o *AnomalyDetectionRequest) UnsetTenantContext()`

UnsetTenantContext ensures that no value is present for TenantContext, not even an explicit nil
### GetFrequency

`func (o *AnomalyDetectionRequest) GetFrequency() string`

GetFrequency returns the Frequency field if non-nil, zero value otherwise.

### GetFrequencyOk

`func (o *AnomalyDetectionRequest) GetFrequencyOk() (*string, bool)`

GetFrequencyOk returns a tuple with the Frequency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFrequency

`func (o *AnomalyDetectionRequest) SetFrequency(v string)`

SetFrequency sets Frequency field to given value.


### GetStartDate

`func (o *AnomalyDetectionRequest) GetStartDate() string`

GetStartDate returns the StartDate field if non-nil, zero value otherwise.

### GetStartDateOk

`func (o *AnomalyDetectionRequest) GetStartDateOk() (*string, bool)`

GetStartDateOk returns a tuple with the StartDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartDate

`func (o *AnomalyDetectionRequest) SetStartDate(v string)`

SetStartDate sets StartDate field to given value.

### HasStartDate

`func (o *AnomalyDetectionRequest) HasStartDate() bool`

HasStartDate returns a boolean if a field has been set.

### SetStartDateNil

`func (o *AnomalyDetectionRequest) SetStartDateNil(b bool)`

 SetStartDateNil sets the value for StartDate to be an explicit nil

### UnsetStartDate
`func (o *AnomalyDetectionRequest) UnsetStartDate()`

UnsetStartDate ensures that no value is present for StartDate, not even an explicit nil
### GetDataType

`func (o *AnomalyDetectionRequest) GetDataType() string`

GetDataType returns the DataType field if non-nil, zero value otherwise.

### GetDataTypeOk

`func (o *AnomalyDetectionRequest) GetDataTypeOk() (*string, bool)`

GetDataTypeOk returns a tuple with the DataType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDataType

`func (o *AnomalyDetectionRequest) SetDataType(v string)`

SetDataType sets DataType field to given value.


### GetPeriods

`func (o *AnomalyDetectionRequest) GetPeriods() int32`

GetPeriods returns the Periods field if non-nil, zero value otherwise.

### GetPeriodsOk

`func (o *AnomalyDetectionRequest) GetPeriodsOk() (*int32, bool)`

GetPeriodsOk returns a tuple with the Periods field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPeriods

`func (o *AnomalyDetectionRequest) SetPeriods(v int32)`

SetPeriods sets Periods field to given value.


### GetModel

`func (o *AnomalyDetectionRequest) GetModel() string`

GetModel returns the Model field if non-nil, zero value otherwise.

### GetModelOk

`func (o *AnomalyDetectionRequest) GetModelOk() (*string, bool)`

GetModelOk returns a tuple with the Model field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModel

`func (o *AnomalyDetectionRequest) SetModel(v string)`

SetModel sets Model field to given value.

### HasModel

`func (o *AnomalyDetectionRequest) HasModel() bool`

HasModel returns a boolean if a field has been set.

### GetConfidenceLevel

`func (o *AnomalyDetectionRequest) GetConfidenceLevel() float32`

GetConfidenceLevel returns the ConfidenceLevel field if non-nil, zero value otherwise.

### GetConfidenceLevelOk

`func (o *AnomalyDetectionRequest) GetConfidenceLevelOk() (*float32, bool)`

GetConfidenceLevelOk returns a tuple with the ConfidenceLevel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConfidenceLevel

`func (o *AnomalyDetectionRequest) SetConfidenceLevel(v float32)`

SetConfidenceLevel sets ConfidenceLevel field to given value.

### HasConfidenceLevel

`func (o *AnomalyDetectionRequest) HasConfidenceLevel() bool`

HasConfidenceLevel returns a boolean if a field has been set.

### GetQuantiles

`func (o *AnomalyDetectionRequest) GetQuantiles() []float32`

GetQuantiles returns the Quantiles field if non-nil, zero value otherwise.

### GetQuantilesOk

`func (o *AnomalyDetectionRequest) GetQuantilesOk() (*[]float32, bool)`

GetQuantilesOk returns a tuple with the Quantiles field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantiles

`func (o *AnomalyDetectionRequest) SetQuantiles(v []float32)`

SetQuantiles sets Quantiles field to given value.

### HasQuantiles

`func (o *AnomalyDetectionRequest) HasQuantiles() bool`

HasQuantiles returns a boolean if a field has been set.

### GetValueBounds

`func (o *AnomalyDetectionRequest) GetValueBounds() ValueBounds`

GetValueBounds returns the ValueBounds field if non-nil, zero value otherwise.

### GetValueBoundsOk

`func (o *AnomalyDetectionRequest) GetValueBoundsOk() (*ValueBounds, bool)`

GetValueBoundsOk returns a tuple with the ValueBounds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValueBounds

`func (o *AnomalyDetectionRequest) SetValueBounds(v ValueBounds)`

SetValueBounds sets ValueBounds field to given value.

### HasValueBounds

`func (o *AnomalyDetectionRequest) HasValueBounds() bool`

HasValueBounds returns a boolean if a field has been set.

### GetAdjustments

`func (o *AnomalyDetectionRequest) GetAdjustments() []AdjustmentsInner`

GetAdjustments returns the Adjustments field if non-nil, zero value otherwise.

### GetAdjustmentsOk

`func (o *AnomalyDetectionRequest) GetAdjustmentsOk() (*[]AdjustmentsInner, bool)`

GetAdjustmentsOk returns a tuple with the Adjustments field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAdjustments

`func (o *AnomalyDetectionRequest) SetAdjustments(v []AdjustmentsInner)`

SetAdjustments sets Adjustments field to given value.

### HasAdjustments

`func (o *AnomalyDetectionRequest) HasAdjustments() bool`

HasAdjustments returns a boolean if a field has been set.

### GetAccumulate

`func (o *AnomalyDetectionRequest) GetAccumulate() AccumulateOptions`

GetAccumulate returns the Accumulate field if non-nil, zero value otherwise.

### GetAccumulateOk

`func (o *AnomalyDetectionRequest) GetAccumulateOk() (*AccumulateOptions, bool)`

GetAccumulateOk returns a tuple with the Accumulate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccumulate

`func (o *AnomalyDetectionRequest) SetAccumulate(v AccumulateOptions)`

SetAccumulate sets Accumulate field to given value.

### HasAccumulate

`func (o *AnomalyDetectionRequest) HasAccumulate() bool`

HasAccumulate returns a boolean if a field has been set.

### GetSelectionMetric

`func (o *AnomalyDetectionRequest) GetSelectionMetric() string`

GetSelectionMetric returns the SelectionMetric field if non-nil, zero value otherwise.

### GetSelectionMetricOk

`func (o *AnomalyDetectionRequest) GetSelectionMetricOk() (*string, bool)`

GetSelectionMetricOk returns a tuple with the SelectionMetric field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSelectionMetric

`func (o *AnomalyDetectionRequest) SetSelectionMetric(v string)`

SetSelectionMetric sets SelectionMetric field to given value.

### HasSelectionMetric

`func (o *AnomalyDetectionRequest) HasSelectionMetric() bool`

HasSelectionMetric returns a boolean if a field has been set.

### SetSelectionMetricNil

`func (o *AnomalyDetectionRequest) SetSelectionMetricNil(b bool)`

 SetSelectionMetricNil sets the value for SelectionMetric to be an explicit nil

### UnsetSelectionMetric
`func (o *AnomalyDetectionRequest) UnsetSelectionMetric()`

UnsetSelectionMetric ensures that no value is present for SelectionMetric, not even an explicit nil
### GetData

`func (o *AnomalyDetectionRequest) GetData() []ForecastRequestDataInner`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *AnomalyDetectionRequest) GetDataOk() (*[]ForecastRequestDataInner, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *AnomalyDetectionRequest) SetData(v []ForecastRequestDataInner)`

SetData sets Data field to given value.


### GetAnomalySettings

`func (o *AnomalyDetectionRequest) GetAnomalySettings() AnomalyDetectionRequestAllOfAnomalySettings`

GetAnomalySettings returns the AnomalySettings field if non-nil, zero value otherwise.

### GetAnomalySettingsOk

`func (o *AnomalyDetectionRequest) GetAnomalySettingsOk() (*AnomalyDetectionRequestAllOfAnomalySettings, bool)`

GetAnomalySettingsOk returns a tuple with the AnomalySettings field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAnomalySettings

`func (o *AnomalyDetectionRequest) SetAnomalySettings(v AnomalyDetectionRequestAllOfAnomalySettings)`

SetAnomalySettings sets AnomalySettings field to given value.

### HasAnomalySettings

`func (o *AnomalyDetectionRequest) HasAnomalySettings() bool`

HasAnomalySettings returns a boolean if a field has been set.

### SetAnomalySettingsNil

`func (o *AnomalyDetectionRequest) SetAnomalySettingsNil(b bool)`

 SetAnomalySettingsNil sets the value for AnomalySettings to be an explicit nil

### UnsetAnomalySettings
`func (o *AnomalyDetectionRequest) UnsetAnomalySettings()`

UnsetAnomalySettings ensures that no value is present for AnomalySettings, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


