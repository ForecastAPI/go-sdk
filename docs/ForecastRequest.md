# ForecastRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Identifier** | **string** | SKU, Product ID, or other identifier for the data series | 
**TenantContext** | Pointer to **NullableString** | Optional segmentation dimension. A series is identified by the pair identifier + tenant_context, so \&quot;mrr\&quot; on \&quot;plan-pro\&quot; and \&quot;mrr\&quot; on \&quot;plan-free\&quot; are two independent series, each with its own history and accuracy tracking. Despite the name it isn&#39;t only for multi-tenancy — use it for any slice: plan, region, store, channel, cohort, device type.  | [optional] 
**Frequency** | **string** | Data frequency: - H: Hourly - D: Daily - W: Weekly - M: Monthly (end of month) - MS: Monthly (start of month) - ME: Monthly (end of month) - Q: Quarterly - Y: Yearly  | 
**StartDate** | Pointer to **NullableString** | Optional start date for the forecast | [optional] 
**DataType** | **string** | Type of data (e.g., sales, demand, inventory, web_traffic) | 
**Periods** | **int32** | Number of periods to forecast | 
**Model** | Pointer to **string** | Which forecasting engine to use. The advanced variants, ensemble and auto provide higher accuracy at a higher usage cost than standard.  &#x60;auto&#x60; routes each identifier to whichever model has proven most accurate on that series: a new identifier starts on the ensemble, and as actuals arrive for previously forecast dates, every model&#39;s realized accuracy is scored; once one clearly wins, that identifier is routed to it. The response reports the decision in &#x60;model_info.auto_selection&#x60;. Billed at the ensemble rate whichever model it routes to.  | [optional] [default to "standard"]
**ConfidenceLevel** | Pointer to **float32** | Confidence level for the prediction interval. Note that 0.80 is the widest band the foundation models (advanced-quantized, advanced-patched, ensemble) produce natively — for genuinely distinct levels beyond that, request a quantile fan via &#x60;quantiles&#x60; instead of repeating the call at several confidence levels.  | [optional] [default to 0.8]
**Quantiles** | Pointer to **[]float32** | Decile levels to return per period — only deciles between 0.1 and 0.9 are accepted, because those are the levels every backend produces natively; anything finer would be interpolation served under a label the model never predicted. Adds a &#x60;quantiles&#x60; object to each forecast row alongside the usual bounds. Honoured by /v2/forecast and /v2/batch/forecast (request-level default or per-series override); rejected on grouped forecasts; ignored by other endpoints sharing this request shape.  | [optional] 
**ValueBounds** | Pointer to [**ValueBounds**](ValueBounds.md) |  | [optional] 
**Adjustments** | Pointer to [**[]AdjustmentsInner**](AdjustmentsInner.md) | What-if scenario applied on top of the forecast (\&quot;assume we lose the enterprise deal\&quot;). Adjustments compose in array order — ×2 then +50 is not +50 then ×2. Each one moves the point, both bounds and any quantile fan together. Returns an &#x60;adjusted&#x60; block; the adjusted path is never stored or accuracy-tracked. Honoured by /v2/forecast and /v2/batch/forecast (request-level default or per-series override — period windows are checked against each series&#39; own horizon); rejected on grouped forecasts; ignored by other endpoints sharing this request shape.  | [optional] 
**Accumulate** | Pointer to [**AccumulateOptions**](AccumulateOptions.md) |  | [optional] 
**SelectionMetric** | Pointer to **NullableString** | Which back-testing error metric decides the winning model when candidates are compared: - auto: combined for demand/sales/inventory, sMAPE otherwise (default) - combined: 0.6·MASE + 0.4·sMAPE — balances accuracy and trend capture - mase: Mean Absolute Scaled Error — accuracy relative to a naive forecast - smape: Symmetric Mean Absolute Percentage Error  | [optional] 
**Data** | [**[]ForecastRequestDataInner**](ForecastRequestDataInner.md) | Historical time series data | 

## Methods

### NewForecastRequest

`func NewForecastRequest(identifier string, frequency string, dataType string, periods int32, data []ForecastRequestDataInner, ) *ForecastRequest`

NewForecastRequest instantiates a new ForecastRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewForecastRequestWithDefaults

`func NewForecastRequestWithDefaults() *ForecastRequest`

NewForecastRequestWithDefaults instantiates a new ForecastRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetIdentifier

`func (o *ForecastRequest) GetIdentifier() string`

GetIdentifier returns the Identifier field if non-nil, zero value otherwise.

### GetIdentifierOk

`func (o *ForecastRequest) GetIdentifierOk() (*string, bool)`

GetIdentifierOk returns a tuple with the Identifier field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdentifier

`func (o *ForecastRequest) SetIdentifier(v string)`

SetIdentifier sets Identifier field to given value.


### GetTenantContext

`func (o *ForecastRequest) GetTenantContext() string`

GetTenantContext returns the TenantContext field if non-nil, zero value otherwise.

### GetTenantContextOk

`func (o *ForecastRequest) GetTenantContextOk() (*string, bool)`

GetTenantContextOk returns a tuple with the TenantContext field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTenantContext

`func (o *ForecastRequest) SetTenantContext(v string)`

SetTenantContext sets TenantContext field to given value.

### HasTenantContext

`func (o *ForecastRequest) HasTenantContext() bool`

HasTenantContext returns a boolean if a field has been set.

### SetTenantContextNil

`func (o *ForecastRequest) SetTenantContextNil(b bool)`

 SetTenantContextNil sets the value for TenantContext to be an explicit nil

### UnsetTenantContext
`func (o *ForecastRequest) UnsetTenantContext()`

UnsetTenantContext ensures that no value is present for TenantContext, not even an explicit nil
### GetFrequency

`func (o *ForecastRequest) GetFrequency() string`

GetFrequency returns the Frequency field if non-nil, zero value otherwise.

### GetFrequencyOk

`func (o *ForecastRequest) GetFrequencyOk() (*string, bool)`

GetFrequencyOk returns a tuple with the Frequency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFrequency

`func (o *ForecastRequest) SetFrequency(v string)`

SetFrequency sets Frequency field to given value.


### GetStartDate

`func (o *ForecastRequest) GetStartDate() string`

GetStartDate returns the StartDate field if non-nil, zero value otherwise.

### GetStartDateOk

`func (o *ForecastRequest) GetStartDateOk() (*string, bool)`

GetStartDateOk returns a tuple with the StartDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartDate

`func (o *ForecastRequest) SetStartDate(v string)`

SetStartDate sets StartDate field to given value.

### HasStartDate

`func (o *ForecastRequest) HasStartDate() bool`

HasStartDate returns a boolean if a field has been set.

### SetStartDateNil

`func (o *ForecastRequest) SetStartDateNil(b bool)`

 SetStartDateNil sets the value for StartDate to be an explicit nil

### UnsetStartDate
`func (o *ForecastRequest) UnsetStartDate()`

UnsetStartDate ensures that no value is present for StartDate, not even an explicit nil
### GetDataType

`func (o *ForecastRequest) GetDataType() string`

GetDataType returns the DataType field if non-nil, zero value otherwise.

### GetDataTypeOk

`func (o *ForecastRequest) GetDataTypeOk() (*string, bool)`

GetDataTypeOk returns a tuple with the DataType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDataType

`func (o *ForecastRequest) SetDataType(v string)`

SetDataType sets DataType field to given value.


### GetPeriods

`func (o *ForecastRequest) GetPeriods() int32`

GetPeriods returns the Periods field if non-nil, zero value otherwise.

### GetPeriodsOk

`func (o *ForecastRequest) GetPeriodsOk() (*int32, bool)`

GetPeriodsOk returns a tuple with the Periods field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPeriods

`func (o *ForecastRequest) SetPeriods(v int32)`

SetPeriods sets Periods field to given value.


### GetModel

`func (o *ForecastRequest) GetModel() string`

GetModel returns the Model field if non-nil, zero value otherwise.

### GetModelOk

`func (o *ForecastRequest) GetModelOk() (*string, bool)`

GetModelOk returns a tuple with the Model field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModel

`func (o *ForecastRequest) SetModel(v string)`

SetModel sets Model field to given value.

### HasModel

`func (o *ForecastRequest) HasModel() bool`

HasModel returns a boolean if a field has been set.

### GetConfidenceLevel

`func (o *ForecastRequest) GetConfidenceLevel() float32`

GetConfidenceLevel returns the ConfidenceLevel field if non-nil, zero value otherwise.

### GetConfidenceLevelOk

`func (o *ForecastRequest) GetConfidenceLevelOk() (*float32, bool)`

GetConfidenceLevelOk returns a tuple with the ConfidenceLevel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConfidenceLevel

`func (o *ForecastRequest) SetConfidenceLevel(v float32)`

SetConfidenceLevel sets ConfidenceLevel field to given value.

### HasConfidenceLevel

`func (o *ForecastRequest) HasConfidenceLevel() bool`

HasConfidenceLevel returns a boolean if a field has been set.

### GetQuantiles

`func (o *ForecastRequest) GetQuantiles() []float32`

GetQuantiles returns the Quantiles field if non-nil, zero value otherwise.

### GetQuantilesOk

`func (o *ForecastRequest) GetQuantilesOk() (*[]float32, bool)`

GetQuantilesOk returns a tuple with the Quantiles field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantiles

`func (o *ForecastRequest) SetQuantiles(v []float32)`

SetQuantiles sets Quantiles field to given value.

### HasQuantiles

`func (o *ForecastRequest) HasQuantiles() bool`

HasQuantiles returns a boolean if a field has been set.

### GetValueBounds

`func (o *ForecastRequest) GetValueBounds() ValueBounds`

GetValueBounds returns the ValueBounds field if non-nil, zero value otherwise.

### GetValueBoundsOk

`func (o *ForecastRequest) GetValueBoundsOk() (*ValueBounds, bool)`

GetValueBoundsOk returns a tuple with the ValueBounds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValueBounds

`func (o *ForecastRequest) SetValueBounds(v ValueBounds)`

SetValueBounds sets ValueBounds field to given value.

### HasValueBounds

`func (o *ForecastRequest) HasValueBounds() bool`

HasValueBounds returns a boolean if a field has been set.

### GetAdjustments

`func (o *ForecastRequest) GetAdjustments() []AdjustmentsInner`

GetAdjustments returns the Adjustments field if non-nil, zero value otherwise.

### GetAdjustmentsOk

`func (o *ForecastRequest) GetAdjustmentsOk() (*[]AdjustmentsInner, bool)`

GetAdjustmentsOk returns a tuple with the Adjustments field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAdjustments

`func (o *ForecastRequest) SetAdjustments(v []AdjustmentsInner)`

SetAdjustments sets Adjustments field to given value.

### HasAdjustments

`func (o *ForecastRequest) HasAdjustments() bool`

HasAdjustments returns a boolean if a field has been set.

### GetAccumulate

`func (o *ForecastRequest) GetAccumulate() AccumulateOptions`

GetAccumulate returns the Accumulate field if non-nil, zero value otherwise.

### GetAccumulateOk

`func (o *ForecastRequest) GetAccumulateOk() (*AccumulateOptions, bool)`

GetAccumulateOk returns a tuple with the Accumulate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccumulate

`func (o *ForecastRequest) SetAccumulate(v AccumulateOptions)`

SetAccumulate sets Accumulate field to given value.

### HasAccumulate

`func (o *ForecastRequest) HasAccumulate() bool`

HasAccumulate returns a boolean if a field has been set.

### GetSelectionMetric

`func (o *ForecastRequest) GetSelectionMetric() string`

GetSelectionMetric returns the SelectionMetric field if non-nil, zero value otherwise.

### GetSelectionMetricOk

`func (o *ForecastRequest) GetSelectionMetricOk() (*string, bool)`

GetSelectionMetricOk returns a tuple with the SelectionMetric field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSelectionMetric

`func (o *ForecastRequest) SetSelectionMetric(v string)`

SetSelectionMetric sets SelectionMetric field to given value.

### HasSelectionMetric

`func (o *ForecastRequest) HasSelectionMetric() bool`

HasSelectionMetric returns a boolean if a field has been set.

### SetSelectionMetricNil

`func (o *ForecastRequest) SetSelectionMetricNil(b bool)`

 SetSelectionMetricNil sets the value for SelectionMetric to be an explicit nil

### UnsetSelectionMetric
`func (o *ForecastRequest) UnsetSelectionMetric()`

UnsetSelectionMetric ensures that no value is present for SelectionMetric, not even an explicit nil
### GetData

`func (o *ForecastRequest) GetData() []ForecastRequestDataInner`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *ForecastRequest) GetDataOk() (*[]ForecastRequestDataInner, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *ForecastRequest) SetData(v []ForecastRequestDataInner)`

SetData sets Data field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


