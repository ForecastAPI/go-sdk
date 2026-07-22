# BatchForecastStatusResponseResults

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Summary** | Pointer to [**BatchForecastStatusResponseResultsSummary**](BatchForecastStatusResponseResultsSummary.md) |  | [optional] 
**Data** | Pointer to [**map[string]BatchSeriesResult**](BatchSeriesResult.md) | Each series&#39; results, keyed by ENTITY id rather than by your identifier — one batch may legitimately contain the same identifier under several tenant_context values, so the identifier alone would not be unique. Match series via the identifier and tenant_context echoed inside each result.  | [optional] 

## Methods

### NewBatchForecastStatusResponseResults

`func NewBatchForecastStatusResponseResults() *BatchForecastStatusResponseResults`

NewBatchForecastStatusResponseResults instantiates a new BatchForecastStatusResponseResults object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewBatchForecastStatusResponseResultsWithDefaults

`func NewBatchForecastStatusResponseResultsWithDefaults() *BatchForecastStatusResponseResults`

NewBatchForecastStatusResponseResultsWithDefaults instantiates a new BatchForecastStatusResponseResults object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSummary

`func (o *BatchForecastStatusResponseResults) GetSummary() BatchForecastStatusResponseResultsSummary`

GetSummary returns the Summary field if non-nil, zero value otherwise.

### GetSummaryOk

`func (o *BatchForecastStatusResponseResults) GetSummaryOk() (*BatchForecastStatusResponseResultsSummary, bool)`

GetSummaryOk returns a tuple with the Summary field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSummary

`func (o *BatchForecastStatusResponseResults) SetSummary(v BatchForecastStatusResponseResultsSummary)`

SetSummary sets Summary field to given value.

### HasSummary

`func (o *BatchForecastStatusResponseResults) HasSummary() bool`

HasSummary returns a boolean if a field has been set.

### GetData

`func (o *BatchForecastStatusResponseResults) GetData() map[string]BatchSeriesResult`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *BatchForecastStatusResponseResults) GetDataOk() (*map[string]BatchSeriesResult, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *BatchForecastStatusResponseResults) SetData(v map[string]BatchSeriesResult)`

SetData sets Data field to given value.

### HasData

`func (o *BatchForecastStatusResponseResults) HasData() bool`

HasData returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


