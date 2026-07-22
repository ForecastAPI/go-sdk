# TrafficForecastingRequestTrafficSettings

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CurrentCapacity** | **float32** | Current infrastructure capacity (requests, users, etc.) | 
**BaselineTraffic** | **float32** | Normal/expected traffic level for comparison | 
**ScalingBuffer** | Pointer to **NullableFloat32** | Buffer percentage for scaling decisions (default 0.2 &#x3D; 20%) | [optional] 
**ScaleUpThreshold** | Pointer to **NullableFloat32** | Utilization threshold to trigger scale up (default 0.8 &#x3D; 80%) | [optional] 
**ScaleDownThreshold** | Pointer to **NullableFloat32** | Utilization threshold to trigger scale down (default 0.3 &#x3D; 30%) | [optional] 
**AlertThreshold** | Pointer to **NullableFloat32** | Traffic spike alert threshold as multiplier of baseline (default 1.5 &#x3D; 150%) | [optional] 
**AnomalyThreshold** | Pointer to **NullableFloat32** | Standard deviations for anomaly detection (default 3.0) | [optional] 
**CostPerUnit** | Pointer to **NullableFloat32** | Variable cost per traffic unit (default 0.01) | [optional] 
**FixedCostPerCapacity** | Pointer to **NullableFloat32** | Fixed cost per capacity unit (default 0.1) | [optional] 
**BaseScalingTime** | Pointer to **NullableInt32** | Base time in minutes for scaling operations (default 5) | [optional] 
**EnableAutoScaling** | Pointer to **NullableBool** | Whether auto-scaling is currently enabled (default false) | [optional] 

## Methods

### NewTrafficForecastingRequestTrafficSettings

`func NewTrafficForecastingRequestTrafficSettings(currentCapacity float32, baselineTraffic float32, ) *TrafficForecastingRequestTrafficSettings`

NewTrafficForecastingRequestTrafficSettings instantiates a new TrafficForecastingRequestTrafficSettings object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTrafficForecastingRequestTrafficSettingsWithDefaults

`func NewTrafficForecastingRequestTrafficSettingsWithDefaults() *TrafficForecastingRequestTrafficSettings`

NewTrafficForecastingRequestTrafficSettingsWithDefaults instantiates a new TrafficForecastingRequestTrafficSettings object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCurrentCapacity

`func (o *TrafficForecastingRequestTrafficSettings) GetCurrentCapacity() float32`

GetCurrentCapacity returns the CurrentCapacity field if non-nil, zero value otherwise.

### GetCurrentCapacityOk

`func (o *TrafficForecastingRequestTrafficSettings) GetCurrentCapacityOk() (*float32, bool)`

GetCurrentCapacityOk returns a tuple with the CurrentCapacity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrentCapacity

`func (o *TrafficForecastingRequestTrafficSettings) SetCurrentCapacity(v float32)`

SetCurrentCapacity sets CurrentCapacity field to given value.


### GetBaselineTraffic

`func (o *TrafficForecastingRequestTrafficSettings) GetBaselineTraffic() float32`

GetBaselineTraffic returns the BaselineTraffic field if non-nil, zero value otherwise.

### GetBaselineTrafficOk

`func (o *TrafficForecastingRequestTrafficSettings) GetBaselineTrafficOk() (*float32, bool)`

GetBaselineTrafficOk returns a tuple with the BaselineTraffic field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBaselineTraffic

`func (o *TrafficForecastingRequestTrafficSettings) SetBaselineTraffic(v float32)`

SetBaselineTraffic sets BaselineTraffic field to given value.


### GetScalingBuffer

`func (o *TrafficForecastingRequestTrafficSettings) GetScalingBuffer() float32`

GetScalingBuffer returns the ScalingBuffer field if non-nil, zero value otherwise.

### GetScalingBufferOk

`func (o *TrafficForecastingRequestTrafficSettings) GetScalingBufferOk() (*float32, bool)`

GetScalingBufferOk returns a tuple with the ScalingBuffer field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScalingBuffer

`func (o *TrafficForecastingRequestTrafficSettings) SetScalingBuffer(v float32)`

SetScalingBuffer sets ScalingBuffer field to given value.

### HasScalingBuffer

`func (o *TrafficForecastingRequestTrafficSettings) HasScalingBuffer() bool`

HasScalingBuffer returns a boolean if a field has been set.

### SetScalingBufferNil

`func (o *TrafficForecastingRequestTrafficSettings) SetScalingBufferNil(b bool)`

 SetScalingBufferNil sets the value for ScalingBuffer to be an explicit nil

### UnsetScalingBuffer
`func (o *TrafficForecastingRequestTrafficSettings) UnsetScalingBuffer()`

UnsetScalingBuffer ensures that no value is present for ScalingBuffer, not even an explicit nil
### GetScaleUpThreshold

`func (o *TrafficForecastingRequestTrafficSettings) GetScaleUpThreshold() float32`

GetScaleUpThreshold returns the ScaleUpThreshold field if non-nil, zero value otherwise.

### GetScaleUpThresholdOk

`func (o *TrafficForecastingRequestTrafficSettings) GetScaleUpThresholdOk() (*float32, bool)`

GetScaleUpThresholdOk returns a tuple with the ScaleUpThreshold field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScaleUpThreshold

`func (o *TrafficForecastingRequestTrafficSettings) SetScaleUpThreshold(v float32)`

SetScaleUpThreshold sets ScaleUpThreshold field to given value.

### HasScaleUpThreshold

`func (o *TrafficForecastingRequestTrafficSettings) HasScaleUpThreshold() bool`

HasScaleUpThreshold returns a boolean if a field has been set.

### SetScaleUpThresholdNil

`func (o *TrafficForecastingRequestTrafficSettings) SetScaleUpThresholdNil(b bool)`

 SetScaleUpThresholdNil sets the value for ScaleUpThreshold to be an explicit nil

### UnsetScaleUpThreshold
`func (o *TrafficForecastingRequestTrafficSettings) UnsetScaleUpThreshold()`

UnsetScaleUpThreshold ensures that no value is present for ScaleUpThreshold, not even an explicit nil
### GetScaleDownThreshold

`func (o *TrafficForecastingRequestTrafficSettings) GetScaleDownThreshold() float32`

GetScaleDownThreshold returns the ScaleDownThreshold field if non-nil, zero value otherwise.

### GetScaleDownThresholdOk

`func (o *TrafficForecastingRequestTrafficSettings) GetScaleDownThresholdOk() (*float32, bool)`

GetScaleDownThresholdOk returns a tuple with the ScaleDownThreshold field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScaleDownThreshold

`func (o *TrafficForecastingRequestTrafficSettings) SetScaleDownThreshold(v float32)`

SetScaleDownThreshold sets ScaleDownThreshold field to given value.

### HasScaleDownThreshold

`func (o *TrafficForecastingRequestTrafficSettings) HasScaleDownThreshold() bool`

HasScaleDownThreshold returns a boolean if a field has been set.

### SetScaleDownThresholdNil

`func (o *TrafficForecastingRequestTrafficSettings) SetScaleDownThresholdNil(b bool)`

 SetScaleDownThresholdNil sets the value for ScaleDownThreshold to be an explicit nil

### UnsetScaleDownThreshold
`func (o *TrafficForecastingRequestTrafficSettings) UnsetScaleDownThreshold()`

UnsetScaleDownThreshold ensures that no value is present for ScaleDownThreshold, not even an explicit nil
### GetAlertThreshold

`func (o *TrafficForecastingRequestTrafficSettings) GetAlertThreshold() float32`

GetAlertThreshold returns the AlertThreshold field if non-nil, zero value otherwise.

### GetAlertThresholdOk

`func (o *TrafficForecastingRequestTrafficSettings) GetAlertThresholdOk() (*float32, bool)`

GetAlertThresholdOk returns a tuple with the AlertThreshold field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAlertThreshold

`func (o *TrafficForecastingRequestTrafficSettings) SetAlertThreshold(v float32)`

SetAlertThreshold sets AlertThreshold field to given value.

### HasAlertThreshold

`func (o *TrafficForecastingRequestTrafficSettings) HasAlertThreshold() bool`

HasAlertThreshold returns a boolean if a field has been set.

### SetAlertThresholdNil

`func (o *TrafficForecastingRequestTrafficSettings) SetAlertThresholdNil(b bool)`

 SetAlertThresholdNil sets the value for AlertThreshold to be an explicit nil

### UnsetAlertThreshold
`func (o *TrafficForecastingRequestTrafficSettings) UnsetAlertThreshold()`

UnsetAlertThreshold ensures that no value is present for AlertThreshold, not even an explicit nil
### GetAnomalyThreshold

`func (o *TrafficForecastingRequestTrafficSettings) GetAnomalyThreshold() float32`

GetAnomalyThreshold returns the AnomalyThreshold field if non-nil, zero value otherwise.

### GetAnomalyThresholdOk

`func (o *TrafficForecastingRequestTrafficSettings) GetAnomalyThresholdOk() (*float32, bool)`

GetAnomalyThresholdOk returns a tuple with the AnomalyThreshold field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAnomalyThreshold

`func (o *TrafficForecastingRequestTrafficSettings) SetAnomalyThreshold(v float32)`

SetAnomalyThreshold sets AnomalyThreshold field to given value.

### HasAnomalyThreshold

`func (o *TrafficForecastingRequestTrafficSettings) HasAnomalyThreshold() bool`

HasAnomalyThreshold returns a boolean if a field has been set.

### SetAnomalyThresholdNil

`func (o *TrafficForecastingRequestTrafficSettings) SetAnomalyThresholdNil(b bool)`

 SetAnomalyThresholdNil sets the value for AnomalyThreshold to be an explicit nil

### UnsetAnomalyThreshold
`func (o *TrafficForecastingRequestTrafficSettings) UnsetAnomalyThreshold()`

UnsetAnomalyThreshold ensures that no value is present for AnomalyThreshold, not even an explicit nil
### GetCostPerUnit

`func (o *TrafficForecastingRequestTrafficSettings) GetCostPerUnit() float32`

GetCostPerUnit returns the CostPerUnit field if non-nil, zero value otherwise.

### GetCostPerUnitOk

`func (o *TrafficForecastingRequestTrafficSettings) GetCostPerUnitOk() (*float32, bool)`

GetCostPerUnitOk returns a tuple with the CostPerUnit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCostPerUnit

`func (o *TrafficForecastingRequestTrafficSettings) SetCostPerUnit(v float32)`

SetCostPerUnit sets CostPerUnit field to given value.

### HasCostPerUnit

`func (o *TrafficForecastingRequestTrafficSettings) HasCostPerUnit() bool`

HasCostPerUnit returns a boolean if a field has been set.

### SetCostPerUnitNil

`func (o *TrafficForecastingRequestTrafficSettings) SetCostPerUnitNil(b bool)`

 SetCostPerUnitNil sets the value for CostPerUnit to be an explicit nil

### UnsetCostPerUnit
`func (o *TrafficForecastingRequestTrafficSettings) UnsetCostPerUnit()`

UnsetCostPerUnit ensures that no value is present for CostPerUnit, not even an explicit nil
### GetFixedCostPerCapacity

`func (o *TrafficForecastingRequestTrafficSettings) GetFixedCostPerCapacity() float32`

GetFixedCostPerCapacity returns the FixedCostPerCapacity field if non-nil, zero value otherwise.

### GetFixedCostPerCapacityOk

`func (o *TrafficForecastingRequestTrafficSettings) GetFixedCostPerCapacityOk() (*float32, bool)`

GetFixedCostPerCapacityOk returns a tuple with the FixedCostPerCapacity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFixedCostPerCapacity

`func (o *TrafficForecastingRequestTrafficSettings) SetFixedCostPerCapacity(v float32)`

SetFixedCostPerCapacity sets FixedCostPerCapacity field to given value.

### HasFixedCostPerCapacity

`func (o *TrafficForecastingRequestTrafficSettings) HasFixedCostPerCapacity() bool`

HasFixedCostPerCapacity returns a boolean if a field has been set.

### SetFixedCostPerCapacityNil

`func (o *TrafficForecastingRequestTrafficSettings) SetFixedCostPerCapacityNil(b bool)`

 SetFixedCostPerCapacityNil sets the value for FixedCostPerCapacity to be an explicit nil

### UnsetFixedCostPerCapacity
`func (o *TrafficForecastingRequestTrafficSettings) UnsetFixedCostPerCapacity()`

UnsetFixedCostPerCapacity ensures that no value is present for FixedCostPerCapacity, not even an explicit nil
### GetBaseScalingTime

`func (o *TrafficForecastingRequestTrafficSettings) GetBaseScalingTime() int32`

GetBaseScalingTime returns the BaseScalingTime field if non-nil, zero value otherwise.

### GetBaseScalingTimeOk

`func (o *TrafficForecastingRequestTrafficSettings) GetBaseScalingTimeOk() (*int32, bool)`

GetBaseScalingTimeOk returns a tuple with the BaseScalingTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBaseScalingTime

`func (o *TrafficForecastingRequestTrafficSettings) SetBaseScalingTime(v int32)`

SetBaseScalingTime sets BaseScalingTime field to given value.

### HasBaseScalingTime

`func (o *TrafficForecastingRequestTrafficSettings) HasBaseScalingTime() bool`

HasBaseScalingTime returns a boolean if a field has been set.

### SetBaseScalingTimeNil

`func (o *TrafficForecastingRequestTrafficSettings) SetBaseScalingTimeNil(b bool)`

 SetBaseScalingTimeNil sets the value for BaseScalingTime to be an explicit nil

### UnsetBaseScalingTime
`func (o *TrafficForecastingRequestTrafficSettings) UnsetBaseScalingTime()`

UnsetBaseScalingTime ensures that no value is present for BaseScalingTime, not even an explicit nil
### GetEnableAutoScaling

`func (o *TrafficForecastingRequestTrafficSettings) GetEnableAutoScaling() bool`

GetEnableAutoScaling returns the EnableAutoScaling field if non-nil, zero value otherwise.

### GetEnableAutoScalingOk

`func (o *TrafficForecastingRequestTrafficSettings) GetEnableAutoScalingOk() (*bool, bool)`

GetEnableAutoScalingOk returns a tuple with the EnableAutoScaling field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnableAutoScaling

`func (o *TrafficForecastingRequestTrafficSettings) SetEnableAutoScaling(v bool)`

SetEnableAutoScaling sets EnableAutoScaling field to given value.

### HasEnableAutoScaling

`func (o *TrafficForecastingRequestTrafficSettings) HasEnableAutoScaling() bool`

HasEnableAutoScaling returns a boolean if a field has been set.

### SetEnableAutoScalingNil

`func (o *TrafficForecastingRequestTrafficSettings) SetEnableAutoScalingNil(b bool)`

 SetEnableAutoScalingNil sets the value for EnableAutoScaling to be an explicit nil

### UnsetEnableAutoScaling
`func (o *TrafficForecastingRequestTrafficSettings) UnsetEnableAutoScaling()`

UnsetEnableAutoScaling ensures that no value is present for EnableAutoScaling, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


