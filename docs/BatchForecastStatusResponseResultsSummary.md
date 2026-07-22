# BatchForecastStatusResponseResultsSummary

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**TotalSeries** | Pointer to **int32** |  | [optional] 
**Completed** | Pointer to **int32** |  | [optional] 
**Failed** | Pointer to **int32** |  | [optional] 
**ModelDistribution** | Pointer to **map[string]int32** |  | [optional] 
**TotalProcessingTimeMs** | Pointer to **float32** |  | [optional] 
**AvgProcessingTimeMs** | Pointer to **float32** |  | [optional] 
**Error** | Pointer to **string** | Present only when the batch failed | [optional] 

## Methods

### NewBatchForecastStatusResponseResultsSummary

`func NewBatchForecastStatusResponseResultsSummary() *BatchForecastStatusResponseResultsSummary`

NewBatchForecastStatusResponseResultsSummary instantiates a new BatchForecastStatusResponseResultsSummary object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewBatchForecastStatusResponseResultsSummaryWithDefaults

`func NewBatchForecastStatusResponseResultsSummaryWithDefaults() *BatchForecastStatusResponseResultsSummary`

NewBatchForecastStatusResponseResultsSummaryWithDefaults instantiates a new BatchForecastStatusResponseResultsSummary object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTotalSeries

`func (o *BatchForecastStatusResponseResultsSummary) GetTotalSeries() int32`

GetTotalSeries returns the TotalSeries field if non-nil, zero value otherwise.

### GetTotalSeriesOk

`func (o *BatchForecastStatusResponseResultsSummary) GetTotalSeriesOk() (*int32, bool)`

GetTotalSeriesOk returns a tuple with the TotalSeries field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalSeries

`func (o *BatchForecastStatusResponseResultsSummary) SetTotalSeries(v int32)`

SetTotalSeries sets TotalSeries field to given value.

### HasTotalSeries

`func (o *BatchForecastStatusResponseResultsSummary) HasTotalSeries() bool`

HasTotalSeries returns a boolean if a field has been set.

### GetCompleted

`func (o *BatchForecastStatusResponseResultsSummary) GetCompleted() int32`

GetCompleted returns the Completed field if non-nil, zero value otherwise.

### GetCompletedOk

`func (o *BatchForecastStatusResponseResultsSummary) GetCompletedOk() (*int32, bool)`

GetCompletedOk returns a tuple with the Completed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompleted

`func (o *BatchForecastStatusResponseResultsSummary) SetCompleted(v int32)`

SetCompleted sets Completed field to given value.

### HasCompleted

`func (o *BatchForecastStatusResponseResultsSummary) HasCompleted() bool`

HasCompleted returns a boolean if a field has been set.

### GetFailed

`func (o *BatchForecastStatusResponseResultsSummary) GetFailed() int32`

GetFailed returns the Failed field if non-nil, zero value otherwise.

### GetFailedOk

`func (o *BatchForecastStatusResponseResultsSummary) GetFailedOk() (*int32, bool)`

GetFailedOk returns a tuple with the Failed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFailed

`func (o *BatchForecastStatusResponseResultsSummary) SetFailed(v int32)`

SetFailed sets Failed field to given value.

### HasFailed

`func (o *BatchForecastStatusResponseResultsSummary) HasFailed() bool`

HasFailed returns a boolean if a field has been set.

### GetModelDistribution

`func (o *BatchForecastStatusResponseResultsSummary) GetModelDistribution() map[string]int32`

GetModelDistribution returns the ModelDistribution field if non-nil, zero value otherwise.

### GetModelDistributionOk

`func (o *BatchForecastStatusResponseResultsSummary) GetModelDistributionOk() (*map[string]int32, bool)`

GetModelDistributionOk returns a tuple with the ModelDistribution field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModelDistribution

`func (o *BatchForecastStatusResponseResultsSummary) SetModelDistribution(v map[string]int32)`

SetModelDistribution sets ModelDistribution field to given value.

### HasModelDistribution

`func (o *BatchForecastStatusResponseResultsSummary) HasModelDistribution() bool`

HasModelDistribution returns a boolean if a field has been set.

### GetTotalProcessingTimeMs

`func (o *BatchForecastStatusResponseResultsSummary) GetTotalProcessingTimeMs() float32`

GetTotalProcessingTimeMs returns the TotalProcessingTimeMs field if non-nil, zero value otherwise.

### GetTotalProcessingTimeMsOk

`func (o *BatchForecastStatusResponseResultsSummary) GetTotalProcessingTimeMsOk() (*float32, bool)`

GetTotalProcessingTimeMsOk returns a tuple with the TotalProcessingTimeMs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalProcessingTimeMs

`func (o *BatchForecastStatusResponseResultsSummary) SetTotalProcessingTimeMs(v float32)`

SetTotalProcessingTimeMs sets TotalProcessingTimeMs field to given value.

### HasTotalProcessingTimeMs

`func (o *BatchForecastStatusResponseResultsSummary) HasTotalProcessingTimeMs() bool`

HasTotalProcessingTimeMs returns a boolean if a field has been set.

### GetAvgProcessingTimeMs

`func (o *BatchForecastStatusResponseResultsSummary) GetAvgProcessingTimeMs() float32`

GetAvgProcessingTimeMs returns the AvgProcessingTimeMs field if non-nil, zero value otherwise.

### GetAvgProcessingTimeMsOk

`func (o *BatchForecastStatusResponseResultsSummary) GetAvgProcessingTimeMsOk() (*float32, bool)`

GetAvgProcessingTimeMsOk returns a tuple with the AvgProcessingTimeMs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAvgProcessingTimeMs

`func (o *BatchForecastStatusResponseResultsSummary) SetAvgProcessingTimeMs(v float32)`

SetAvgProcessingTimeMs sets AvgProcessingTimeMs field to given value.

### HasAvgProcessingTimeMs

`func (o *BatchForecastStatusResponseResultsSummary) HasAvgProcessingTimeMs() bool`

HasAvgProcessingTimeMs returns a boolean if a field has been set.

### GetError

`func (o *BatchForecastStatusResponseResultsSummary) GetError() string`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *BatchForecastStatusResponseResultsSummary) GetErrorOk() (*string, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *BatchForecastStatusResponseResultsSummary) SetError(v string)`

SetError sets Error field to given value.

### HasError

`func (o *BatchForecastStatusResponseResultsSummary) HasError() bool`

HasError returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


