# TrafficForecastingResponseResult

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Metric** | Pointer to **string** | Metric identifier from the request | [optional] 
**CurrentCapacity** | Pointer to **float32** | Current infrastructure capacity | [optional] 
**BaselineTraffic** | Pointer to **float32** | Baseline traffic level | [optional] 
**ScalingRecommendations** | Pointer to [**TrafficForecastingResponseResultScalingRecommendations**](TrafficForecastingResponseResultScalingRecommendations.md) |  | [optional] 
**CapacityAnalysis** | Pointer to [**TrafficForecastingResponseResultCapacityAnalysis**](TrafficForecastingResponseResultCapacityAnalysis.md) |  | [optional] 
**TrafficAlerts** | Pointer to [**TrafficForecastingResponseResultTrafficAlerts**](TrafficForecastingResponseResultTrafficAlerts.md) |  | [optional] 
**CostOptimization** | Pointer to [**TrafficForecastingResponseResultCostOptimization**](TrafficForecastingResponseResultCostOptimization.md) |  | [optional] 
**ForecastData** | Pointer to [**[]TrafficForecastingResponseResultForecastDataInner**](TrafficForecastingResponseResultForecastDataInner.md) | Underlying forecast data used for analysis | [optional] 

## Methods

### NewTrafficForecastingResponseResult

`func NewTrafficForecastingResponseResult() *TrafficForecastingResponseResult`

NewTrafficForecastingResponseResult instantiates a new TrafficForecastingResponseResult object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTrafficForecastingResponseResultWithDefaults

`func NewTrafficForecastingResponseResultWithDefaults() *TrafficForecastingResponseResult`

NewTrafficForecastingResponseResultWithDefaults instantiates a new TrafficForecastingResponseResult object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMetric

`func (o *TrafficForecastingResponseResult) GetMetric() string`

GetMetric returns the Metric field if non-nil, zero value otherwise.

### GetMetricOk

`func (o *TrafficForecastingResponseResult) GetMetricOk() (*string, bool)`

GetMetricOk returns a tuple with the Metric field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetric

`func (o *TrafficForecastingResponseResult) SetMetric(v string)`

SetMetric sets Metric field to given value.

### HasMetric

`func (o *TrafficForecastingResponseResult) HasMetric() bool`

HasMetric returns a boolean if a field has been set.

### GetCurrentCapacity

`func (o *TrafficForecastingResponseResult) GetCurrentCapacity() float32`

GetCurrentCapacity returns the CurrentCapacity field if non-nil, zero value otherwise.

### GetCurrentCapacityOk

`func (o *TrafficForecastingResponseResult) GetCurrentCapacityOk() (*float32, bool)`

GetCurrentCapacityOk returns a tuple with the CurrentCapacity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrentCapacity

`func (o *TrafficForecastingResponseResult) SetCurrentCapacity(v float32)`

SetCurrentCapacity sets CurrentCapacity field to given value.

### HasCurrentCapacity

`func (o *TrafficForecastingResponseResult) HasCurrentCapacity() bool`

HasCurrentCapacity returns a boolean if a field has been set.

### GetBaselineTraffic

`func (o *TrafficForecastingResponseResult) GetBaselineTraffic() float32`

GetBaselineTraffic returns the BaselineTraffic field if non-nil, zero value otherwise.

### GetBaselineTrafficOk

`func (o *TrafficForecastingResponseResult) GetBaselineTrafficOk() (*float32, bool)`

GetBaselineTrafficOk returns a tuple with the BaselineTraffic field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBaselineTraffic

`func (o *TrafficForecastingResponseResult) SetBaselineTraffic(v float32)`

SetBaselineTraffic sets BaselineTraffic field to given value.

### HasBaselineTraffic

`func (o *TrafficForecastingResponseResult) HasBaselineTraffic() bool`

HasBaselineTraffic returns a boolean if a field has been set.

### GetScalingRecommendations

`func (o *TrafficForecastingResponseResult) GetScalingRecommendations() TrafficForecastingResponseResultScalingRecommendations`

GetScalingRecommendations returns the ScalingRecommendations field if non-nil, zero value otherwise.

### GetScalingRecommendationsOk

`func (o *TrafficForecastingResponseResult) GetScalingRecommendationsOk() (*TrafficForecastingResponseResultScalingRecommendations, bool)`

GetScalingRecommendationsOk returns a tuple with the ScalingRecommendations field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScalingRecommendations

`func (o *TrafficForecastingResponseResult) SetScalingRecommendations(v TrafficForecastingResponseResultScalingRecommendations)`

SetScalingRecommendations sets ScalingRecommendations field to given value.

### HasScalingRecommendations

`func (o *TrafficForecastingResponseResult) HasScalingRecommendations() bool`

HasScalingRecommendations returns a boolean if a field has been set.

### GetCapacityAnalysis

`func (o *TrafficForecastingResponseResult) GetCapacityAnalysis() TrafficForecastingResponseResultCapacityAnalysis`

GetCapacityAnalysis returns the CapacityAnalysis field if non-nil, zero value otherwise.

### GetCapacityAnalysisOk

`func (o *TrafficForecastingResponseResult) GetCapacityAnalysisOk() (*TrafficForecastingResponseResultCapacityAnalysis, bool)`

GetCapacityAnalysisOk returns a tuple with the CapacityAnalysis field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCapacityAnalysis

`func (o *TrafficForecastingResponseResult) SetCapacityAnalysis(v TrafficForecastingResponseResultCapacityAnalysis)`

SetCapacityAnalysis sets CapacityAnalysis field to given value.

### HasCapacityAnalysis

`func (o *TrafficForecastingResponseResult) HasCapacityAnalysis() bool`

HasCapacityAnalysis returns a boolean if a field has been set.

### GetTrafficAlerts

`func (o *TrafficForecastingResponseResult) GetTrafficAlerts() TrafficForecastingResponseResultTrafficAlerts`

GetTrafficAlerts returns the TrafficAlerts field if non-nil, zero value otherwise.

### GetTrafficAlertsOk

`func (o *TrafficForecastingResponseResult) GetTrafficAlertsOk() (*TrafficForecastingResponseResultTrafficAlerts, bool)`

GetTrafficAlertsOk returns a tuple with the TrafficAlerts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrafficAlerts

`func (o *TrafficForecastingResponseResult) SetTrafficAlerts(v TrafficForecastingResponseResultTrafficAlerts)`

SetTrafficAlerts sets TrafficAlerts field to given value.

### HasTrafficAlerts

`func (o *TrafficForecastingResponseResult) HasTrafficAlerts() bool`

HasTrafficAlerts returns a boolean if a field has been set.

### GetCostOptimization

`func (o *TrafficForecastingResponseResult) GetCostOptimization() TrafficForecastingResponseResultCostOptimization`

GetCostOptimization returns the CostOptimization field if non-nil, zero value otherwise.

### GetCostOptimizationOk

`func (o *TrafficForecastingResponseResult) GetCostOptimizationOk() (*TrafficForecastingResponseResultCostOptimization, bool)`

GetCostOptimizationOk returns a tuple with the CostOptimization field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCostOptimization

`func (o *TrafficForecastingResponseResult) SetCostOptimization(v TrafficForecastingResponseResultCostOptimization)`

SetCostOptimization sets CostOptimization field to given value.

### HasCostOptimization

`func (o *TrafficForecastingResponseResult) HasCostOptimization() bool`

HasCostOptimization returns a boolean if a field has been set.

### GetForecastData

`func (o *TrafficForecastingResponseResult) GetForecastData() []TrafficForecastingResponseResultForecastDataInner`

GetForecastData returns the ForecastData field if non-nil, zero value otherwise.

### GetForecastDataOk

`func (o *TrafficForecastingResponseResult) GetForecastDataOk() (*[]TrafficForecastingResponseResultForecastDataInner, bool)`

GetForecastDataOk returns a tuple with the ForecastData field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetForecastData

`func (o *TrafficForecastingResponseResult) SetForecastData(v []TrafficForecastingResponseResultForecastDataInner)`

SetForecastData sets ForecastData field to given value.

### HasForecastData

`func (o *TrafficForecastingResponseResult) HasForecastData() bool`

HasForecastData returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


