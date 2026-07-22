# AccumulatedForecast

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Total** | Pointer to **NullableFloat32** | Σ (value × survival × discount) over the horizon. Null when a period lacks a usable point forecast (see &#x60;total_reason&#x60;). | [optional] 
**TotalReason** | Pointer to **NullableString** | Why &#x60;total&#x60; is null; null when the total is usable | [optional] 
**Lower** | Pointer to **NullableFloat32** | Lower bound of the total under the stated correlation assumption. Null with an &#x60;interval_reason&#x60; when any period lacks a band or its coverage is unknown — rather than a band built from a partial set of variances.  | [optional] 
**Upper** | Pointer to **NullableFloat32** |  | [optional] 
**IntervalReason** | Pointer to **NullableString** | Why the total&#39;s band is absent; null when the band is present | [optional] 
**ConfidenceLevel** | Pointer to **float32** | Coverage the total&#39;s band targets | [optional] 
**Path** | Pointer to **string** | Which path was accumulated — &#x60;adjusted&#x60; when &#x60;adjustments&#x60; was also sent, otherwise &#x60;baseline&#x60; | [optional] 
**Assumptions** | Pointer to [**AccumulatedForecastAssumptions**](AccumulatedForecastAssumptions.md) |  | [optional] 
**ByPeriod** | Pointer to [**[]AccumulatedForecastByPeriodInner**](AccumulatedForecastByPeriodInner.md) | Running accumulation per period — &#x60;cumulative&#x60; through period L is the number a lead-time/safety-stock calculation reads | [optional] 

## Methods

### NewAccumulatedForecast

`func NewAccumulatedForecast() *AccumulatedForecast`

NewAccumulatedForecast instantiates a new AccumulatedForecast object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAccumulatedForecastWithDefaults

`func NewAccumulatedForecastWithDefaults() *AccumulatedForecast`

NewAccumulatedForecastWithDefaults instantiates a new AccumulatedForecast object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTotal

`func (o *AccumulatedForecast) GetTotal() float32`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *AccumulatedForecast) GetTotalOk() (*float32, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *AccumulatedForecast) SetTotal(v float32)`

SetTotal sets Total field to given value.

### HasTotal

`func (o *AccumulatedForecast) HasTotal() bool`

HasTotal returns a boolean if a field has been set.

### SetTotalNil

`func (o *AccumulatedForecast) SetTotalNil(b bool)`

 SetTotalNil sets the value for Total to be an explicit nil

### UnsetTotal
`func (o *AccumulatedForecast) UnsetTotal()`

UnsetTotal ensures that no value is present for Total, not even an explicit nil
### GetTotalReason

`func (o *AccumulatedForecast) GetTotalReason() string`

GetTotalReason returns the TotalReason field if non-nil, zero value otherwise.

### GetTotalReasonOk

`func (o *AccumulatedForecast) GetTotalReasonOk() (*string, bool)`

GetTotalReasonOk returns a tuple with the TotalReason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalReason

`func (o *AccumulatedForecast) SetTotalReason(v string)`

SetTotalReason sets TotalReason field to given value.

### HasTotalReason

`func (o *AccumulatedForecast) HasTotalReason() bool`

HasTotalReason returns a boolean if a field has been set.

### SetTotalReasonNil

`func (o *AccumulatedForecast) SetTotalReasonNil(b bool)`

 SetTotalReasonNil sets the value for TotalReason to be an explicit nil

### UnsetTotalReason
`func (o *AccumulatedForecast) UnsetTotalReason()`

UnsetTotalReason ensures that no value is present for TotalReason, not even an explicit nil
### GetLower

`func (o *AccumulatedForecast) GetLower() float32`

GetLower returns the Lower field if non-nil, zero value otherwise.

### GetLowerOk

`func (o *AccumulatedForecast) GetLowerOk() (*float32, bool)`

GetLowerOk returns a tuple with the Lower field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLower

`func (o *AccumulatedForecast) SetLower(v float32)`

SetLower sets Lower field to given value.

### HasLower

`func (o *AccumulatedForecast) HasLower() bool`

HasLower returns a boolean if a field has been set.

### SetLowerNil

`func (o *AccumulatedForecast) SetLowerNil(b bool)`

 SetLowerNil sets the value for Lower to be an explicit nil

### UnsetLower
`func (o *AccumulatedForecast) UnsetLower()`

UnsetLower ensures that no value is present for Lower, not even an explicit nil
### GetUpper

`func (o *AccumulatedForecast) GetUpper() float32`

GetUpper returns the Upper field if non-nil, zero value otherwise.

### GetUpperOk

`func (o *AccumulatedForecast) GetUpperOk() (*float32, bool)`

GetUpperOk returns a tuple with the Upper field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpper

`func (o *AccumulatedForecast) SetUpper(v float32)`

SetUpper sets Upper field to given value.

### HasUpper

`func (o *AccumulatedForecast) HasUpper() bool`

HasUpper returns a boolean if a field has been set.

### SetUpperNil

`func (o *AccumulatedForecast) SetUpperNil(b bool)`

 SetUpperNil sets the value for Upper to be an explicit nil

### UnsetUpper
`func (o *AccumulatedForecast) UnsetUpper()`

UnsetUpper ensures that no value is present for Upper, not even an explicit nil
### GetIntervalReason

`func (o *AccumulatedForecast) GetIntervalReason() string`

GetIntervalReason returns the IntervalReason field if non-nil, zero value otherwise.

### GetIntervalReasonOk

`func (o *AccumulatedForecast) GetIntervalReasonOk() (*string, bool)`

GetIntervalReasonOk returns a tuple with the IntervalReason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIntervalReason

`func (o *AccumulatedForecast) SetIntervalReason(v string)`

SetIntervalReason sets IntervalReason field to given value.

### HasIntervalReason

`func (o *AccumulatedForecast) HasIntervalReason() bool`

HasIntervalReason returns a boolean if a field has been set.

### SetIntervalReasonNil

`func (o *AccumulatedForecast) SetIntervalReasonNil(b bool)`

 SetIntervalReasonNil sets the value for IntervalReason to be an explicit nil

### UnsetIntervalReason
`func (o *AccumulatedForecast) UnsetIntervalReason()`

UnsetIntervalReason ensures that no value is present for IntervalReason, not even an explicit nil
### GetConfidenceLevel

`func (o *AccumulatedForecast) GetConfidenceLevel() float32`

GetConfidenceLevel returns the ConfidenceLevel field if non-nil, zero value otherwise.

### GetConfidenceLevelOk

`func (o *AccumulatedForecast) GetConfidenceLevelOk() (*float32, bool)`

GetConfidenceLevelOk returns a tuple with the ConfidenceLevel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConfidenceLevel

`func (o *AccumulatedForecast) SetConfidenceLevel(v float32)`

SetConfidenceLevel sets ConfidenceLevel field to given value.

### HasConfidenceLevel

`func (o *AccumulatedForecast) HasConfidenceLevel() bool`

HasConfidenceLevel returns a boolean if a field has been set.

### GetPath

`func (o *AccumulatedForecast) GetPath() string`

GetPath returns the Path field if non-nil, zero value otherwise.

### GetPathOk

`func (o *AccumulatedForecast) GetPathOk() (*string, bool)`

GetPathOk returns a tuple with the Path field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPath

`func (o *AccumulatedForecast) SetPath(v string)`

SetPath sets Path field to given value.

### HasPath

`func (o *AccumulatedForecast) HasPath() bool`

HasPath returns a boolean if a field has been set.

### GetAssumptions

`func (o *AccumulatedForecast) GetAssumptions() AccumulatedForecastAssumptions`

GetAssumptions returns the Assumptions field if non-nil, zero value otherwise.

### GetAssumptionsOk

`func (o *AccumulatedForecast) GetAssumptionsOk() (*AccumulatedForecastAssumptions, bool)`

GetAssumptionsOk returns a tuple with the Assumptions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssumptions

`func (o *AccumulatedForecast) SetAssumptions(v AccumulatedForecastAssumptions)`

SetAssumptions sets Assumptions field to given value.

### HasAssumptions

`func (o *AccumulatedForecast) HasAssumptions() bool`

HasAssumptions returns a boolean if a field has been set.

### GetByPeriod

`func (o *AccumulatedForecast) GetByPeriod() []AccumulatedForecastByPeriodInner`

GetByPeriod returns the ByPeriod field if non-nil, zero value otherwise.

### GetByPeriodOk

`func (o *AccumulatedForecast) GetByPeriodOk() (*[]AccumulatedForecastByPeriodInner, bool)`

GetByPeriodOk returns a tuple with the ByPeriod field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetByPeriod

`func (o *AccumulatedForecast) SetByPeriod(v []AccumulatedForecastByPeriodInner)`

SetByPeriod sets ByPeriod field to given value.

### HasByPeriod

`func (o *AccumulatedForecast) HasByPeriod() bool`

HasByPeriod returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


