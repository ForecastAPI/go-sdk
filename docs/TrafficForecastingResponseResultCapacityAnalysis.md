# TrafficForecastingResponseResultCapacityAnalysis

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CurrentCapacity** | Pointer to **float32** | Current infrastructure capacity | [optional] 
**UtilizationPeriods** | Pointer to [**[]TrafficForecastingResponseResultCapacityAnalysisUtilizationPeriodsInner**](TrafficForecastingResponseResultCapacityAnalysisUtilizationPeriodsInner.md) | Capacity utilization for each forecast period | [optional] 
**OverCapacityPeriods** | Pointer to **int32** | Number of periods exceeding capacity | [optional] 
**CriticalPeriods** | Pointer to **int32** | Number of periods above 90% utilization | [optional] 
**ForecastDurationMinutes** | Pointer to **int32** | Total forecast duration in minutes | [optional] 
**NextCapacityBreach** | Pointer to **NullableString** | Date when capacity will be breached | [optional] 
**CapacityEfficiency** | Pointer to **float32** | Efficiency score (0-100, optimal around 75% utilization) | [optional] 

## Methods

### NewTrafficForecastingResponseResultCapacityAnalysis

`func NewTrafficForecastingResponseResultCapacityAnalysis() *TrafficForecastingResponseResultCapacityAnalysis`

NewTrafficForecastingResponseResultCapacityAnalysis instantiates a new TrafficForecastingResponseResultCapacityAnalysis object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTrafficForecastingResponseResultCapacityAnalysisWithDefaults

`func NewTrafficForecastingResponseResultCapacityAnalysisWithDefaults() *TrafficForecastingResponseResultCapacityAnalysis`

NewTrafficForecastingResponseResultCapacityAnalysisWithDefaults instantiates a new TrafficForecastingResponseResultCapacityAnalysis object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCurrentCapacity

`func (o *TrafficForecastingResponseResultCapacityAnalysis) GetCurrentCapacity() float32`

GetCurrentCapacity returns the CurrentCapacity field if non-nil, zero value otherwise.

### GetCurrentCapacityOk

`func (o *TrafficForecastingResponseResultCapacityAnalysis) GetCurrentCapacityOk() (*float32, bool)`

GetCurrentCapacityOk returns a tuple with the CurrentCapacity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrentCapacity

`func (o *TrafficForecastingResponseResultCapacityAnalysis) SetCurrentCapacity(v float32)`

SetCurrentCapacity sets CurrentCapacity field to given value.

### HasCurrentCapacity

`func (o *TrafficForecastingResponseResultCapacityAnalysis) HasCurrentCapacity() bool`

HasCurrentCapacity returns a boolean if a field has been set.

### GetUtilizationPeriods

`func (o *TrafficForecastingResponseResultCapacityAnalysis) GetUtilizationPeriods() []TrafficForecastingResponseResultCapacityAnalysisUtilizationPeriodsInner`

GetUtilizationPeriods returns the UtilizationPeriods field if non-nil, zero value otherwise.

### GetUtilizationPeriodsOk

`func (o *TrafficForecastingResponseResultCapacityAnalysis) GetUtilizationPeriodsOk() (*[]TrafficForecastingResponseResultCapacityAnalysisUtilizationPeriodsInner, bool)`

GetUtilizationPeriodsOk returns a tuple with the UtilizationPeriods field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUtilizationPeriods

`func (o *TrafficForecastingResponseResultCapacityAnalysis) SetUtilizationPeriods(v []TrafficForecastingResponseResultCapacityAnalysisUtilizationPeriodsInner)`

SetUtilizationPeriods sets UtilizationPeriods field to given value.

### HasUtilizationPeriods

`func (o *TrafficForecastingResponseResultCapacityAnalysis) HasUtilizationPeriods() bool`

HasUtilizationPeriods returns a boolean if a field has been set.

### GetOverCapacityPeriods

`func (o *TrafficForecastingResponseResultCapacityAnalysis) GetOverCapacityPeriods() int32`

GetOverCapacityPeriods returns the OverCapacityPeriods field if non-nil, zero value otherwise.

### GetOverCapacityPeriodsOk

`func (o *TrafficForecastingResponseResultCapacityAnalysis) GetOverCapacityPeriodsOk() (*int32, bool)`

GetOverCapacityPeriodsOk returns a tuple with the OverCapacityPeriods field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOverCapacityPeriods

`func (o *TrafficForecastingResponseResultCapacityAnalysis) SetOverCapacityPeriods(v int32)`

SetOverCapacityPeriods sets OverCapacityPeriods field to given value.

### HasOverCapacityPeriods

`func (o *TrafficForecastingResponseResultCapacityAnalysis) HasOverCapacityPeriods() bool`

HasOverCapacityPeriods returns a boolean if a field has been set.

### GetCriticalPeriods

`func (o *TrafficForecastingResponseResultCapacityAnalysis) GetCriticalPeriods() int32`

GetCriticalPeriods returns the CriticalPeriods field if non-nil, zero value otherwise.

### GetCriticalPeriodsOk

`func (o *TrafficForecastingResponseResultCapacityAnalysis) GetCriticalPeriodsOk() (*int32, bool)`

GetCriticalPeriodsOk returns a tuple with the CriticalPeriods field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCriticalPeriods

`func (o *TrafficForecastingResponseResultCapacityAnalysis) SetCriticalPeriods(v int32)`

SetCriticalPeriods sets CriticalPeriods field to given value.

### HasCriticalPeriods

`func (o *TrafficForecastingResponseResultCapacityAnalysis) HasCriticalPeriods() bool`

HasCriticalPeriods returns a boolean if a field has been set.

### GetForecastDurationMinutes

`func (o *TrafficForecastingResponseResultCapacityAnalysis) GetForecastDurationMinutes() int32`

GetForecastDurationMinutes returns the ForecastDurationMinutes field if non-nil, zero value otherwise.

### GetForecastDurationMinutesOk

`func (o *TrafficForecastingResponseResultCapacityAnalysis) GetForecastDurationMinutesOk() (*int32, bool)`

GetForecastDurationMinutesOk returns a tuple with the ForecastDurationMinutes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetForecastDurationMinutes

`func (o *TrafficForecastingResponseResultCapacityAnalysis) SetForecastDurationMinutes(v int32)`

SetForecastDurationMinutes sets ForecastDurationMinutes field to given value.

### HasForecastDurationMinutes

`func (o *TrafficForecastingResponseResultCapacityAnalysis) HasForecastDurationMinutes() bool`

HasForecastDurationMinutes returns a boolean if a field has been set.

### GetNextCapacityBreach

`func (o *TrafficForecastingResponseResultCapacityAnalysis) GetNextCapacityBreach() string`

GetNextCapacityBreach returns the NextCapacityBreach field if non-nil, zero value otherwise.

### GetNextCapacityBreachOk

`func (o *TrafficForecastingResponseResultCapacityAnalysis) GetNextCapacityBreachOk() (*string, bool)`

GetNextCapacityBreachOk returns a tuple with the NextCapacityBreach field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNextCapacityBreach

`func (o *TrafficForecastingResponseResultCapacityAnalysis) SetNextCapacityBreach(v string)`

SetNextCapacityBreach sets NextCapacityBreach field to given value.

### HasNextCapacityBreach

`func (o *TrafficForecastingResponseResultCapacityAnalysis) HasNextCapacityBreach() bool`

HasNextCapacityBreach returns a boolean if a field has been set.

### SetNextCapacityBreachNil

`func (o *TrafficForecastingResponseResultCapacityAnalysis) SetNextCapacityBreachNil(b bool)`

 SetNextCapacityBreachNil sets the value for NextCapacityBreach to be an explicit nil

### UnsetNextCapacityBreach
`func (o *TrafficForecastingResponseResultCapacityAnalysis) UnsetNextCapacityBreach()`

UnsetNextCapacityBreach ensures that no value is present for NextCapacityBreach, not even an explicit nil
### GetCapacityEfficiency

`func (o *TrafficForecastingResponseResultCapacityAnalysis) GetCapacityEfficiency() float32`

GetCapacityEfficiency returns the CapacityEfficiency field if non-nil, zero value otherwise.

### GetCapacityEfficiencyOk

`func (o *TrafficForecastingResponseResultCapacityAnalysis) GetCapacityEfficiencyOk() (*float32, bool)`

GetCapacityEfficiencyOk returns a tuple with the CapacityEfficiency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCapacityEfficiency

`func (o *TrafficForecastingResponseResultCapacityAnalysis) SetCapacityEfficiency(v float32)`

SetCapacityEfficiency sets CapacityEfficiency field to given value.

### HasCapacityEfficiency

`func (o *TrafficForecastingResponseResultCapacityAnalysis) HasCapacityEfficiency() bool`

HasCapacityEfficiency returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


