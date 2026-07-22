# TrafficForecastingResponseResultScalingRecommendations

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**PeakTraffic** | Pointer to **float32** | Predicted peak traffic across forecast periods | [optional] 
**AverageTraffic** | Pointer to **float32** | Average predicted traffic | [optional] 
**CurrentUtilization** | Pointer to **float32** | Peak utilization percentage of current capacity | [optional] 
**Recommendations** | Pointer to [**[]TrafficForecastingResponseResultScalingRecommendationsRecommendationsInner**](TrafficForecastingResponseResultScalingRecommendationsRecommendationsInner.md) | Scaling action recommendations | [optional] 

## Methods

### NewTrafficForecastingResponseResultScalingRecommendations

`func NewTrafficForecastingResponseResultScalingRecommendations() *TrafficForecastingResponseResultScalingRecommendations`

NewTrafficForecastingResponseResultScalingRecommendations instantiates a new TrafficForecastingResponseResultScalingRecommendations object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTrafficForecastingResponseResultScalingRecommendationsWithDefaults

`func NewTrafficForecastingResponseResultScalingRecommendationsWithDefaults() *TrafficForecastingResponseResultScalingRecommendations`

NewTrafficForecastingResponseResultScalingRecommendationsWithDefaults instantiates a new TrafficForecastingResponseResultScalingRecommendations object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPeakTraffic

`func (o *TrafficForecastingResponseResultScalingRecommendations) GetPeakTraffic() float32`

GetPeakTraffic returns the PeakTraffic field if non-nil, zero value otherwise.

### GetPeakTrafficOk

`func (o *TrafficForecastingResponseResultScalingRecommendations) GetPeakTrafficOk() (*float32, bool)`

GetPeakTrafficOk returns a tuple with the PeakTraffic field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPeakTraffic

`func (o *TrafficForecastingResponseResultScalingRecommendations) SetPeakTraffic(v float32)`

SetPeakTraffic sets PeakTraffic field to given value.

### HasPeakTraffic

`func (o *TrafficForecastingResponseResultScalingRecommendations) HasPeakTraffic() bool`

HasPeakTraffic returns a boolean if a field has been set.

### GetAverageTraffic

`func (o *TrafficForecastingResponseResultScalingRecommendations) GetAverageTraffic() float32`

GetAverageTraffic returns the AverageTraffic field if non-nil, zero value otherwise.

### GetAverageTrafficOk

`func (o *TrafficForecastingResponseResultScalingRecommendations) GetAverageTrafficOk() (*float32, bool)`

GetAverageTrafficOk returns a tuple with the AverageTraffic field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAverageTraffic

`func (o *TrafficForecastingResponseResultScalingRecommendations) SetAverageTraffic(v float32)`

SetAverageTraffic sets AverageTraffic field to given value.

### HasAverageTraffic

`func (o *TrafficForecastingResponseResultScalingRecommendations) HasAverageTraffic() bool`

HasAverageTraffic returns a boolean if a field has been set.

### GetCurrentUtilization

`func (o *TrafficForecastingResponseResultScalingRecommendations) GetCurrentUtilization() float32`

GetCurrentUtilization returns the CurrentUtilization field if non-nil, zero value otherwise.

### GetCurrentUtilizationOk

`func (o *TrafficForecastingResponseResultScalingRecommendations) GetCurrentUtilizationOk() (*float32, bool)`

GetCurrentUtilizationOk returns a tuple with the CurrentUtilization field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrentUtilization

`func (o *TrafficForecastingResponseResultScalingRecommendations) SetCurrentUtilization(v float32)`

SetCurrentUtilization sets CurrentUtilization field to given value.

### HasCurrentUtilization

`func (o *TrafficForecastingResponseResultScalingRecommendations) HasCurrentUtilization() bool`

HasCurrentUtilization returns a boolean if a field has been set.

### GetRecommendations

`func (o *TrafficForecastingResponseResultScalingRecommendations) GetRecommendations() []TrafficForecastingResponseResultScalingRecommendationsRecommendationsInner`

GetRecommendations returns the Recommendations field if non-nil, zero value otherwise.

### GetRecommendationsOk

`func (o *TrafficForecastingResponseResultScalingRecommendations) GetRecommendationsOk() (*[]TrafficForecastingResponseResultScalingRecommendationsRecommendationsInner, bool)`

GetRecommendationsOk returns a tuple with the Recommendations field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRecommendations

`func (o *TrafficForecastingResponseResultScalingRecommendations) SetRecommendations(v []TrafficForecastingResponseResultScalingRecommendationsRecommendationsInner)`

SetRecommendations sets Recommendations field to given value.

### HasRecommendations

`func (o *TrafficForecastingResponseResultScalingRecommendations) HasRecommendations() bool`

HasRecommendations returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


