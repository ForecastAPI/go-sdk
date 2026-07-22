# ProductInsightsResponseResultSummary

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**TotalInsights** | Pointer to **int32** |  | [optional] 
**SeverityDistribution** | Pointer to **map[string]int32** |  | [optional] 
**Categories** | Pointer to **[]string** |  | [optional] 
**AnalysisPeriod** | Pointer to [**ProductInsightsResponseResultSummaryAnalysisPeriod**](ProductInsightsResponseResultSummaryAnalysisPeriod.md) |  | [optional] 
**DataSourcesAnalyzed** | Pointer to **[]string** |  | [optional] 

## Methods

### NewProductInsightsResponseResultSummary

`func NewProductInsightsResponseResultSummary() *ProductInsightsResponseResultSummary`

NewProductInsightsResponseResultSummary instantiates a new ProductInsightsResponseResultSummary object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProductInsightsResponseResultSummaryWithDefaults

`func NewProductInsightsResponseResultSummaryWithDefaults() *ProductInsightsResponseResultSummary`

NewProductInsightsResponseResultSummaryWithDefaults instantiates a new ProductInsightsResponseResultSummary object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTotalInsights

`func (o *ProductInsightsResponseResultSummary) GetTotalInsights() int32`

GetTotalInsights returns the TotalInsights field if non-nil, zero value otherwise.

### GetTotalInsightsOk

`func (o *ProductInsightsResponseResultSummary) GetTotalInsightsOk() (*int32, bool)`

GetTotalInsightsOk returns a tuple with the TotalInsights field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalInsights

`func (o *ProductInsightsResponseResultSummary) SetTotalInsights(v int32)`

SetTotalInsights sets TotalInsights field to given value.

### HasTotalInsights

`func (o *ProductInsightsResponseResultSummary) HasTotalInsights() bool`

HasTotalInsights returns a boolean if a field has been set.

### GetSeverityDistribution

`func (o *ProductInsightsResponseResultSummary) GetSeverityDistribution() map[string]int32`

GetSeverityDistribution returns the SeverityDistribution field if non-nil, zero value otherwise.

### GetSeverityDistributionOk

`func (o *ProductInsightsResponseResultSummary) GetSeverityDistributionOk() (*map[string]int32, bool)`

GetSeverityDistributionOk returns a tuple with the SeverityDistribution field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSeverityDistribution

`func (o *ProductInsightsResponseResultSummary) SetSeverityDistribution(v map[string]int32)`

SetSeverityDistribution sets SeverityDistribution field to given value.

### HasSeverityDistribution

`func (o *ProductInsightsResponseResultSummary) HasSeverityDistribution() bool`

HasSeverityDistribution returns a boolean if a field has been set.

### GetCategories

`func (o *ProductInsightsResponseResultSummary) GetCategories() []string`

GetCategories returns the Categories field if non-nil, zero value otherwise.

### GetCategoriesOk

`func (o *ProductInsightsResponseResultSummary) GetCategoriesOk() (*[]string, bool)`

GetCategoriesOk returns a tuple with the Categories field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCategories

`func (o *ProductInsightsResponseResultSummary) SetCategories(v []string)`

SetCategories sets Categories field to given value.

### HasCategories

`func (o *ProductInsightsResponseResultSummary) HasCategories() bool`

HasCategories returns a boolean if a field has been set.

### GetAnalysisPeriod

`func (o *ProductInsightsResponseResultSummary) GetAnalysisPeriod() ProductInsightsResponseResultSummaryAnalysisPeriod`

GetAnalysisPeriod returns the AnalysisPeriod field if non-nil, zero value otherwise.

### GetAnalysisPeriodOk

`func (o *ProductInsightsResponseResultSummary) GetAnalysisPeriodOk() (*ProductInsightsResponseResultSummaryAnalysisPeriod, bool)`

GetAnalysisPeriodOk returns a tuple with the AnalysisPeriod field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAnalysisPeriod

`func (o *ProductInsightsResponseResultSummary) SetAnalysisPeriod(v ProductInsightsResponseResultSummaryAnalysisPeriod)`

SetAnalysisPeriod sets AnalysisPeriod field to given value.

### HasAnalysisPeriod

`func (o *ProductInsightsResponseResultSummary) HasAnalysisPeriod() bool`

HasAnalysisPeriod returns a boolean if a field has been set.

### GetDataSourcesAnalyzed

`func (o *ProductInsightsResponseResultSummary) GetDataSourcesAnalyzed() []string`

GetDataSourcesAnalyzed returns the DataSourcesAnalyzed field if non-nil, zero value otherwise.

### GetDataSourcesAnalyzedOk

`func (o *ProductInsightsResponseResultSummary) GetDataSourcesAnalyzedOk() (*[]string, bool)`

GetDataSourcesAnalyzedOk returns a tuple with the DataSourcesAnalyzed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDataSourcesAnalyzed

`func (o *ProductInsightsResponseResultSummary) SetDataSourcesAnalyzed(v []string)`

SetDataSourcesAnalyzed sets DataSourcesAnalyzed field to given value.

### HasDataSourcesAnalyzed

`func (o *ProductInsightsResponseResultSummary) HasDataSourcesAnalyzed() bool`

HasDataSourcesAnalyzed returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


