# TrafficForecastingResponseResultCostOptimization

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CurrentCost** | Pointer to **float32** | Current total cost based on capacity | [optional] 
**OptimizedCost** | Pointer to **float32** | Optimized cost after recommendations | [optional] 
**PotentialSavings** | Pointer to **float32** | Potential cost savings | [optional] 
**SavingsPercentage** | Pointer to **float32** | Savings as percentage of current cost | [optional] 
**CostBreakdown** | Pointer to [**TrafficForecastingResponseResultCostOptimizationCostBreakdown**](TrafficForecastingResponseResultCostOptimizationCostBreakdown.md) |  | [optional] 
**Recommendations** | Pointer to [**[]TrafficForecastingResponseResultCostOptimizationRecommendationsInner**](TrafficForecastingResponseResultCostOptimizationRecommendationsInner.md) | Cost optimization recommendations | [optional] 

## Methods

### NewTrafficForecastingResponseResultCostOptimization

`func NewTrafficForecastingResponseResultCostOptimization() *TrafficForecastingResponseResultCostOptimization`

NewTrafficForecastingResponseResultCostOptimization instantiates a new TrafficForecastingResponseResultCostOptimization object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTrafficForecastingResponseResultCostOptimizationWithDefaults

`func NewTrafficForecastingResponseResultCostOptimizationWithDefaults() *TrafficForecastingResponseResultCostOptimization`

NewTrafficForecastingResponseResultCostOptimizationWithDefaults instantiates a new TrafficForecastingResponseResultCostOptimization object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCurrentCost

`func (o *TrafficForecastingResponseResultCostOptimization) GetCurrentCost() float32`

GetCurrentCost returns the CurrentCost field if non-nil, zero value otherwise.

### GetCurrentCostOk

`func (o *TrafficForecastingResponseResultCostOptimization) GetCurrentCostOk() (*float32, bool)`

GetCurrentCostOk returns a tuple with the CurrentCost field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrentCost

`func (o *TrafficForecastingResponseResultCostOptimization) SetCurrentCost(v float32)`

SetCurrentCost sets CurrentCost field to given value.

### HasCurrentCost

`func (o *TrafficForecastingResponseResultCostOptimization) HasCurrentCost() bool`

HasCurrentCost returns a boolean if a field has been set.

### GetOptimizedCost

`func (o *TrafficForecastingResponseResultCostOptimization) GetOptimizedCost() float32`

GetOptimizedCost returns the OptimizedCost field if non-nil, zero value otherwise.

### GetOptimizedCostOk

`func (o *TrafficForecastingResponseResultCostOptimization) GetOptimizedCostOk() (*float32, bool)`

GetOptimizedCostOk returns a tuple with the OptimizedCost field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOptimizedCost

`func (o *TrafficForecastingResponseResultCostOptimization) SetOptimizedCost(v float32)`

SetOptimizedCost sets OptimizedCost field to given value.

### HasOptimizedCost

`func (o *TrafficForecastingResponseResultCostOptimization) HasOptimizedCost() bool`

HasOptimizedCost returns a boolean if a field has been set.

### GetPotentialSavings

`func (o *TrafficForecastingResponseResultCostOptimization) GetPotentialSavings() float32`

GetPotentialSavings returns the PotentialSavings field if non-nil, zero value otherwise.

### GetPotentialSavingsOk

`func (o *TrafficForecastingResponseResultCostOptimization) GetPotentialSavingsOk() (*float32, bool)`

GetPotentialSavingsOk returns a tuple with the PotentialSavings field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPotentialSavings

`func (o *TrafficForecastingResponseResultCostOptimization) SetPotentialSavings(v float32)`

SetPotentialSavings sets PotentialSavings field to given value.

### HasPotentialSavings

`func (o *TrafficForecastingResponseResultCostOptimization) HasPotentialSavings() bool`

HasPotentialSavings returns a boolean if a field has been set.

### GetSavingsPercentage

`func (o *TrafficForecastingResponseResultCostOptimization) GetSavingsPercentage() float32`

GetSavingsPercentage returns the SavingsPercentage field if non-nil, zero value otherwise.

### GetSavingsPercentageOk

`func (o *TrafficForecastingResponseResultCostOptimization) GetSavingsPercentageOk() (*float32, bool)`

GetSavingsPercentageOk returns a tuple with the SavingsPercentage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSavingsPercentage

`func (o *TrafficForecastingResponseResultCostOptimization) SetSavingsPercentage(v float32)`

SetSavingsPercentage sets SavingsPercentage field to given value.

### HasSavingsPercentage

`func (o *TrafficForecastingResponseResultCostOptimization) HasSavingsPercentage() bool`

HasSavingsPercentage returns a boolean if a field has been set.

### GetCostBreakdown

`func (o *TrafficForecastingResponseResultCostOptimization) GetCostBreakdown() TrafficForecastingResponseResultCostOptimizationCostBreakdown`

GetCostBreakdown returns the CostBreakdown field if non-nil, zero value otherwise.

### GetCostBreakdownOk

`func (o *TrafficForecastingResponseResultCostOptimization) GetCostBreakdownOk() (*TrafficForecastingResponseResultCostOptimizationCostBreakdown, bool)`

GetCostBreakdownOk returns a tuple with the CostBreakdown field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCostBreakdown

`func (o *TrafficForecastingResponseResultCostOptimization) SetCostBreakdown(v TrafficForecastingResponseResultCostOptimizationCostBreakdown)`

SetCostBreakdown sets CostBreakdown field to given value.

### HasCostBreakdown

`func (o *TrafficForecastingResponseResultCostOptimization) HasCostBreakdown() bool`

HasCostBreakdown returns a boolean if a field has been set.

### GetRecommendations

`func (o *TrafficForecastingResponseResultCostOptimization) GetRecommendations() []TrafficForecastingResponseResultCostOptimizationRecommendationsInner`

GetRecommendations returns the Recommendations field if non-nil, zero value otherwise.

### GetRecommendationsOk

`func (o *TrafficForecastingResponseResultCostOptimization) GetRecommendationsOk() (*[]TrafficForecastingResponseResultCostOptimizationRecommendationsInner, bool)`

GetRecommendationsOk returns a tuple with the Recommendations field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRecommendations

`func (o *TrafficForecastingResponseResultCostOptimization) SetRecommendations(v []TrafficForecastingResponseResultCostOptimizationRecommendationsInner)`

SetRecommendations sets Recommendations field to given value.

### HasRecommendations

`func (o *TrafficForecastingResponseResultCostOptimization) HasRecommendations() bool`

HasRecommendations returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


