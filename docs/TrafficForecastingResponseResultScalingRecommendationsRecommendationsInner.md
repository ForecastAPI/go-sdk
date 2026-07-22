# TrafficForecastingResponseResultScalingRecommendationsRecommendationsInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Action** | Pointer to **string** | Recommended scaling action | [optional] 
**CurrentCapacity** | Pointer to **float32** | Current capacity | [optional] 
**RecommendedCapacity** | Pointer to **float32** | Recommended capacity | [optional] 
**ScalingFactor** | Pointer to **float32** | Scaling multiplier | [optional] 
**Reason** | Pointer to **string** | Explanation for the recommendation | [optional] 
**Urgency** | Pointer to **string** | Urgency level of the action | [optional] 
**EstimatedTimeToScale** | Pointer to **int32** | Estimated minutes needed for scaling | [optional] 
**PotentialSavings** | Pointer to **float32** | Potential cost savings (for scale down) | [optional] 

## Methods

### NewTrafficForecastingResponseResultScalingRecommendationsRecommendationsInner

`func NewTrafficForecastingResponseResultScalingRecommendationsRecommendationsInner() *TrafficForecastingResponseResultScalingRecommendationsRecommendationsInner`

NewTrafficForecastingResponseResultScalingRecommendationsRecommendationsInner instantiates a new TrafficForecastingResponseResultScalingRecommendationsRecommendationsInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTrafficForecastingResponseResultScalingRecommendationsRecommendationsInnerWithDefaults

`func NewTrafficForecastingResponseResultScalingRecommendationsRecommendationsInnerWithDefaults() *TrafficForecastingResponseResultScalingRecommendationsRecommendationsInner`

NewTrafficForecastingResponseResultScalingRecommendationsRecommendationsInnerWithDefaults instantiates a new TrafficForecastingResponseResultScalingRecommendationsRecommendationsInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAction

`func (o *TrafficForecastingResponseResultScalingRecommendationsRecommendationsInner) GetAction() string`

GetAction returns the Action field if non-nil, zero value otherwise.

### GetActionOk

`func (o *TrafficForecastingResponseResultScalingRecommendationsRecommendationsInner) GetActionOk() (*string, bool)`

GetActionOk returns a tuple with the Action field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAction

`func (o *TrafficForecastingResponseResultScalingRecommendationsRecommendationsInner) SetAction(v string)`

SetAction sets Action field to given value.

### HasAction

`func (o *TrafficForecastingResponseResultScalingRecommendationsRecommendationsInner) HasAction() bool`

HasAction returns a boolean if a field has been set.

### GetCurrentCapacity

`func (o *TrafficForecastingResponseResultScalingRecommendationsRecommendationsInner) GetCurrentCapacity() float32`

GetCurrentCapacity returns the CurrentCapacity field if non-nil, zero value otherwise.

### GetCurrentCapacityOk

`func (o *TrafficForecastingResponseResultScalingRecommendationsRecommendationsInner) GetCurrentCapacityOk() (*float32, bool)`

GetCurrentCapacityOk returns a tuple with the CurrentCapacity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrentCapacity

`func (o *TrafficForecastingResponseResultScalingRecommendationsRecommendationsInner) SetCurrentCapacity(v float32)`

SetCurrentCapacity sets CurrentCapacity field to given value.

### HasCurrentCapacity

`func (o *TrafficForecastingResponseResultScalingRecommendationsRecommendationsInner) HasCurrentCapacity() bool`

HasCurrentCapacity returns a boolean if a field has been set.

### GetRecommendedCapacity

`func (o *TrafficForecastingResponseResultScalingRecommendationsRecommendationsInner) GetRecommendedCapacity() float32`

GetRecommendedCapacity returns the RecommendedCapacity field if non-nil, zero value otherwise.

### GetRecommendedCapacityOk

`func (o *TrafficForecastingResponseResultScalingRecommendationsRecommendationsInner) GetRecommendedCapacityOk() (*float32, bool)`

GetRecommendedCapacityOk returns a tuple with the RecommendedCapacity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRecommendedCapacity

`func (o *TrafficForecastingResponseResultScalingRecommendationsRecommendationsInner) SetRecommendedCapacity(v float32)`

SetRecommendedCapacity sets RecommendedCapacity field to given value.

### HasRecommendedCapacity

`func (o *TrafficForecastingResponseResultScalingRecommendationsRecommendationsInner) HasRecommendedCapacity() bool`

HasRecommendedCapacity returns a boolean if a field has been set.

### GetScalingFactor

`func (o *TrafficForecastingResponseResultScalingRecommendationsRecommendationsInner) GetScalingFactor() float32`

GetScalingFactor returns the ScalingFactor field if non-nil, zero value otherwise.

### GetScalingFactorOk

`func (o *TrafficForecastingResponseResultScalingRecommendationsRecommendationsInner) GetScalingFactorOk() (*float32, bool)`

GetScalingFactorOk returns a tuple with the ScalingFactor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScalingFactor

`func (o *TrafficForecastingResponseResultScalingRecommendationsRecommendationsInner) SetScalingFactor(v float32)`

SetScalingFactor sets ScalingFactor field to given value.

### HasScalingFactor

`func (o *TrafficForecastingResponseResultScalingRecommendationsRecommendationsInner) HasScalingFactor() bool`

HasScalingFactor returns a boolean if a field has been set.

### GetReason

`func (o *TrafficForecastingResponseResultScalingRecommendationsRecommendationsInner) GetReason() string`

GetReason returns the Reason field if non-nil, zero value otherwise.

### GetReasonOk

`func (o *TrafficForecastingResponseResultScalingRecommendationsRecommendationsInner) GetReasonOk() (*string, bool)`

GetReasonOk returns a tuple with the Reason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReason

`func (o *TrafficForecastingResponseResultScalingRecommendationsRecommendationsInner) SetReason(v string)`

SetReason sets Reason field to given value.

### HasReason

`func (o *TrafficForecastingResponseResultScalingRecommendationsRecommendationsInner) HasReason() bool`

HasReason returns a boolean if a field has been set.

### GetUrgency

`func (o *TrafficForecastingResponseResultScalingRecommendationsRecommendationsInner) GetUrgency() string`

GetUrgency returns the Urgency field if non-nil, zero value otherwise.

### GetUrgencyOk

`func (o *TrafficForecastingResponseResultScalingRecommendationsRecommendationsInner) GetUrgencyOk() (*string, bool)`

GetUrgencyOk returns a tuple with the Urgency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrgency

`func (o *TrafficForecastingResponseResultScalingRecommendationsRecommendationsInner) SetUrgency(v string)`

SetUrgency sets Urgency field to given value.

### HasUrgency

`func (o *TrafficForecastingResponseResultScalingRecommendationsRecommendationsInner) HasUrgency() bool`

HasUrgency returns a boolean if a field has been set.

### GetEstimatedTimeToScale

`func (o *TrafficForecastingResponseResultScalingRecommendationsRecommendationsInner) GetEstimatedTimeToScale() int32`

GetEstimatedTimeToScale returns the EstimatedTimeToScale field if non-nil, zero value otherwise.

### GetEstimatedTimeToScaleOk

`func (o *TrafficForecastingResponseResultScalingRecommendationsRecommendationsInner) GetEstimatedTimeToScaleOk() (*int32, bool)`

GetEstimatedTimeToScaleOk returns a tuple with the EstimatedTimeToScale field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEstimatedTimeToScale

`func (o *TrafficForecastingResponseResultScalingRecommendationsRecommendationsInner) SetEstimatedTimeToScale(v int32)`

SetEstimatedTimeToScale sets EstimatedTimeToScale field to given value.

### HasEstimatedTimeToScale

`func (o *TrafficForecastingResponseResultScalingRecommendationsRecommendationsInner) HasEstimatedTimeToScale() bool`

HasEstimatedTimeToScale returns a boolean if a field has been set.

### GetPotentialSavings

`func (o *TrafficForecastingResponseResultScalingRecommendationsRecommendationsInner) GetPotentialSavings() float32`

GetPotentialSavings returns the PotentialSavings field if non-nil, zero value otherwise.

### GetPotentialSavingsOk

`func (o *TrafficForecastingResponseResultScalingRecommendationsRecommendationsInner) GetPotentialSavingsOk() (*float32, bool)`

GetPotentialSavingsOk returns a tuple with the PotentialSavings field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPotentialSavings

`func (o *TrafficForecastingResponseResultScalingRecommendationsRecommendationsInner) SetPotentialSavings(v float32)`

SetPotentialSavings sets PotentialSavings field to given value.

### HasPotentialSavings

`func (o *TrafficForecastingResponseResultScalingRecommendationsRecommendationsInner) HasPotentialSavings() bool`

HasPotentialSavings returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


