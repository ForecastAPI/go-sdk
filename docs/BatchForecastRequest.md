# BatchForecastRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Series** | Pointer to [**[]BatchForecastSeries**](BatchForecastSeries.md) | The series to forecast — up to 100,000 per call on a paid plan, 10 on the free tier | [optional] 
**FileKey** | Pointer to **string** | Instead of inline &#x60;series&#x60; — the key returned by /v2/batch/forecast/presign, after uploading a JSON file of the same shape as this request body (an object with a &#x60;series&#x60; array). Series from a file are validated as they are streamed: an invalid series fails that series, not the whole batch.  | [optional] 
**Periods** | Pointer to **int32** | Default forecast horizon for series that don&#39;t set their own | [optional] [default to 6]
**Frequency** | Pointer to **string** | Default data frequency | [optional] 
**DataType** | Pointer to **string** | Default data type | [optional] 
**Model** | Pointer to **string** | Default forecasting engine for series that don&#39;t set their own. &#x60;auto&#x60; routes each series independently on its own realized-accuracy scorecard. Usage is billed per series at its effective model&#39;s rate.  | [optional] [default to "standard"]
**Confidence** | Pointer to **float32** | Default confidence level for prediction intervals | [optional] [default to 0.8]
**ConfidenceLevel** | Pointer to **float32** | Alias for &#x60;confidence&#x60; | [optional] 
**Quantiles** | Pointer to **[]float32** | Decile levels to return per period — only deciles between 0.1 and 0.9 are accepted, because those are the levels every backend produces natively; anything finer would be interpolation served under a label the model never predicted. Adds a &#x60;quantiles&#x60; object to each forecast row alongside the usual bounds. Honoured by /v2/forecast and /v2/batch/forecast (request-level default or per-series override); rejected on grouped forecasts; ignored by other endpoints sharing this request shape.  | [optional] 
**ValueBounds** | Pointer to [**ValueBounds**](ValueBounds.md) |  | [optional] 
**Adjustments** | Pointer to [**[]AdjustmentsInner**](AdjustmentsInner.md) | What-if scenario applied on top of the forecast (\&quot;assume we lose the enterprise deal\&quot;). Adjustments compose in array order — ×2 then +50 is not +50 then ×2. Each one moves the point, both bounds and any quantile fan together. Returns an &#x60;adjusted&#x60; block; the adjusted path is never stored or accuracy-tracked. Honoured by /v2/forecast and /v2/batch/forecast (request-level default or per-series override — period windows are checked against each series&#39; own horizon); rejected on grouped forecasts; ignored by other endpoints sharing this request shape.  | [optional] 
**Accumulate** | Pointer to [**AccumulateOptions**](AccumulateOptions.md) |  | [optional] 

## Methods

### NewBatchForecastRequest

`func NewBatchForecastRequest() *BatchForecastRequest`

NewBatchForecastRequest instantiates a new BatchForecastRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewBatchForecastRequestWithDefaults

`func NewBatchForecastRequestWithDefaults() *BatchForecastRequest`

NewBatchForecastRequestWithDefaults instantiates a new BatchForecastRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSeries

`func (o *BatchForecastRequest) GetSeries() []BatchForecastSeries`

GetSeries returns the Series field if non-nil, zero value otherwise.

### GetSeriesOk

`func (o *BatchForecastRequest) GetSeriesOk() (*[]BatchForecastSeries, bool)`

GetSeriesOk returns a tuple with the Series field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSeries

`func (o *BatchForecastRequest) SetSeries(v []BatchForecastSeries)`

SetSeries sets Series field to given value.

### HasSeries

`func (o *BatchForecastRequest) HasSeries() bool`

HasSeries returns a boolean if a field has been set.

### GetFileKey

`func (o *BatchForecastRequest) GetFileKey() string`

GetFileKey returns the FileKey field if non-nil, zero value otherwise.

### GetFileKeyOk

`func (o *BatchForecastRequest) GetFileKeyOk() (*string, bool)`

GetFileKeyOk returns a tuple with the FileKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFileKey

`func (o *BatchForecastRequest) SetFileKey(v string)`

SetFileKey sets FileKey field to given value.

### HasFileKey

`func (o *BatchForecastRequest) HasFileKey() bool`

HasFileKey returns a boolean if a field has been set.

### GetPeriods

`func (o *BatchForecastRequest) GetPeriods() int32`

GetPeriods returns the Periods field if non-nil, zero value otherwise.

### GetPeriodsOk

`func (o *BatchForecastRequest) GetPeriodsOk() (*int32, bool)`

GetPeriodsOk returns a tuple with the Periods field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPeriods

`func (o *BatchForecastRequest) SetPeriods(v int32)`

SetPeriods sets Periods field to given value.

### HasPeriods

`func (o *BatchForecastRequest) HasPeriods() bool`

HasPeriods returns a boolean if a field has been set.

### GetFrequency

`func (o *BatchForecastRequest) GetFrequency() string`

GetFrequency returns the Frequency field if non-nil, zero value otherwise.

### GetFrequencyOk

`func (o *BatchForecastRequest) GetFrequencyOk() (*string, bool)`

GetFrequencyOk returns a tuple with the Frequency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFrequency

`func (o *BatchForecastRequest) SetFrequency(v string)`

SetFrequency sets Frequency field to given value.

### HasFrequency

`func (o *BatchForecastRequest) HasFrequency() bool`

HasFrequency returns a boolean if a field has been set.

### GetDataType

`func (o *BatchForecastRequest) GetDataType() string`

GetDataType returns the DataType field if non-nil, zero value otherwise.

### GetDataTypeOk

`func (o *BatchForecastRequest) GetDataTypeOk() (*string, bool)`

GetDataTypeOk returns a tuple with the DataType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDataType

`func (o *BatchForecastRequest) SetDataType(v string)`

SetDataType sets DataType field to given value.

### HasDataType

`func (o *BatchForecastRequest) HasDataType() bool`

HasDataType returns a boolean if a field has been set.

### GetModel

`func (o *BatchForecastRequest) GetModel() string`

GetModel returns the Model field if non-nil, zero value otherwise.

### GetModelOk

`func (o *BatchForecastRequest) GetModelOk() (*string, bool)`

GetModelOk returns a tuple with the Model field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModel

`func (o *BatchForecastRequest) SetModel(v string)`

SetModel sets Model field to given value.

### HasModel

`func (o *BatchForecastRequest) HasModel() bool`

HasModel returns a boolean if a field has been set.

### GetConfidence

`func (o *BatchForecastRequest) GetConfidence() float32`

GetConfidence returns the Confidence field if non-nil, zero value otherwise.

### GetConfidenceOk

`func (o *BatchForecastRequest) GetConfidenceOk() (*float32, bool)`

GetConfidenceOk returns a tuple with the Confidence field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConfidence

`func (o *BatchForecastRequest) SetConfidence(v float32)`

SetConfidence sets Confidence field to given value.

### HasConfidence

`func (o *BatchForecastRequest) HasConfidence() bool`

HasConfidence returns a boolean if a field has been set.

### GetConfidenceLevel

`func (o *BatchForecastRequest) GetConfidenceLevel() float32`

GetConfidenceLevel returns the ConfidenceLevel field if non-nil, zero value otherwise.

### GetConfidenceLevelOk

`func (o *BatchForecastRequest) GetConfidenceLevelOk() (*float32, bool)`

GetConfidenceLevelOk returns a tuple with the ConfidenceLevel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConfidenceLevel

`func (o *BatchForecastRequest) SetConfidenceLevel(v float32)`

SetConfidenceLevel sets ConfidenceLevel field to given value.

### HasConfidenceLevel

`func (o *BatchForecastRequest) HasConfidenceLevel() bool`

HasConfidenceLevel returns a boolean if a field has been set.

### GetQuantiles

`func (o *BatchForecastRequest) GetQuantiles() []float32`

GetQuantiles returns the Quantiles field if non-nil, zero value otherwise.

### GetQuantilesOk

`func (o *BatchForecastRequest) GetQuantilesOk() (*[]float32, bool)`

GetQuantilesOk returns a tuple with the Quantiles field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantiles

`func (o *BatchForecastRequest) SetQuantiles(v []float32)`

SetQuantiles sets Quantiles field to given value.

### HasQuantiles

`func (o *BatchForecastRequest) HasQuantiles() bool`

HasQuantiles returns a boolean if a field has been set.

### GetValueBounds

`func (o *BatchForecastRequest) GetValueBounds() ValueBounds`

GetValueBounds returns the ValueBounds field if non-nil, zero value otherwise.

### GetValueBoundsOk

`func (o *BatchForecastRequest) GetValueBoundsOk() (*ValueBounds, bool)`

GetValueBoundsOk returns a tuple with the ValueBounds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValueBounds

`func (o *BatchForecastRequest) SetValueBounds(v ValueBounds)`

SetValueBounds sets ValueBounds field to given value.

### HasValueBounds

`func (o *BatchForecastRequest) HasValueBounds() bool`

HasValueBounds returns a boolean if a field has been set.

### GetAdjustments

`func (o *BatchForecastRequest) GetAdjustments() []AdjustmentsInner`

GetAdjustments returns the Adjustments field if non-nil, zero value otherwise.

### GetAdjustmentsOk

`func (o *BatchForecastRequest) GetAdjustmentsOk() (*[]AdjustmentsInner, bool)`

GetAdjustmentsOk returns a tuple with the Adjustments field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAdjustments

`func (o *BatchForecastRequest) SetAdjustments(v []AdjustmentsInner)`

SetAdjustments sets Adjustments field to given value.

### HasAdjustments

`func (o *BatchForecastRequest) HasAdjustments() bool`

HasAdjustments returns a boolean if a field has been set.

### GetAccumulate

`func (o *BatchForecastRequest) GetAccumulate() AccumulateOptions`

GetAccumulate returns the Accumulate field if non-nil, zero value otherwise.

### GetAccumulateOk

`func (o *BatchForecastRequest) GetAccumulateOk() (*AccumulateOptions, bool)`

GetAccumulateOk returns a tuple with the Accumulate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccumulate

`func (o *BatchForecastRequest) SetAccumulate(v AccumulateOptions)`

SetAccumulate sets Accumulate field to given value.

### HasAccumulate

`func (o *BatchForecastRequest) HasAccumulate() bool`

HasAccumulate returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


