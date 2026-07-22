# TrafficForecastingResponseResultTrafficAlertsAlertsInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Type** | Pointer to **string** | Type of alert | [optional] 
**Severity** | Pointer to **string** | Alert severity | [optional] 
**Period** | Pointer to **int32** | Period number where alert occurs | [optional] 
**Date** | Pointer to **time.Time** | Date/time of the alert | [optional] 
**PredictedTraffic** | Pointer to **float32** | Predicted traffic value | [optional] 
**BaselineTraffic** | Pointer to **float32** | Baseline traffic (for spikes) | [optional] 
**IncreaseFactor** | Pointer to **float32** | Traffic increase factor (for spikes) | [optional] 
**ZScore** | Pointer to **float32** | Z-score for anomaly detection | [optional] 
**Message** | Pointer to **string** | Alert message | [optional] 

## Methods

### NewTrafficForecastingResponseResultTrafficAlertsAlertsInner

`func NewTrafficForecastingResponseResultTrafficAlertsAlertsInner() *TrafficForecastingResponseResultTrafficAlertsAlertsInner`

NewTrafficForecastingResponseResultTrafficAlertsAlertsInner instantiates a new TrafficForecastingResponseResultTrafficAlertsAlertsInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTrafficForecastingResponseResultTrafficAlertsAlertsInnerWithDefaults

`func NewTrafficForecastingResponseResultTrafficAlertsAlertsInnerWithDefaults() *TrafficForecastingResponseResultTrafficAlertsAlertsInner`

NewTrafficForecastingResponseResultTrafficAlertsAlertsInnerWithDefaults instantiates a new TrafficForecastingResponseResultTrafficAlertsAlertsInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetType

`func (o *TrafficForecastingResponseResultTrafficAlertsAlertsInner) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *TrafficForecastingResponseResultTrafficAlertsAlertsInner) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *TrafficForecastingResponseResultTrafficAlertsAlertsInner) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *TrafficForecastingResponseResultTrafficAlertsAlertsInner) HasType() bool`

HasType returns a boolean if a field has been set.

### GetSeverity

`func (o *TrafficForecastingResponseResultTrafficAlertsAlertsInner) GetSeverity() string`

GetSeverity returns the Severity field if non-nil, zero value otherwise.

### GetSeverityOk

`func (o *TrafficForecastingResponseResultTrafficAlertsAlertsInner) GetSeverityOk() (*string, bool)`

GetSeverityOk returns a tuple with the Severity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSeverity

`func (o *TrafficForecastingResponseResultTrafficAlertsAlertsInner) SetSeverity(v string)`

SetSeverity sets Severity field to given value.

### HasSeverity

`func (o *TrafficForecastingResponseResultTrafficAlertsAlertsInner) HasSeverity() bool`

HasSeverity returns a boolean if a field has been set.

### GetPeriod

`func (o *TrafficForecastingResponseResultTrafficAlertsAlertsInner) GetPeriod() int32`

GetPeriod returns the Period field if non-nil, zero value otherwise.

### GetPeriodOk

`func (o *TrafficForecastingResponseResultTrafficAlertsAlertsInner) GetPeriodOk() (*int32, bool)`

GetPeriodOk returns a tuple with the Period field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPeriod

`func (o *TrafficForecastingResponseResultTrafficAlertsAlertsInner) SetPeriod(v int32)`

SetPeriod sets Period field to given value.

### HasPeriod

`func (o *TrafficForecastingResponseResultTrafficAlertsAlertsInner) HasPeriod() bool`

HasPeriod returns a boolean if a field has been set.

### GetDate

`func (o *TrafficForecastingResponseResultTrafficAlertsAlertsInner) GetDate() time.Time`

GetDate returns the Date field if non-nil, zero value otherwise.

### GetDateOk

`func (o *TrafficForecastingResponseResultTrafficAlertsAlertsInner) GetDateOk() (*time.Time, bool)`

GetDateOk returns a tuple with the Date field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDate

`func (o *TrafficForecastingResponseResultTrafficAlertsAlertsInner) SetDate(v time.Time)`

SetDate sets Date field to given value.

### HasDate

`func (o *TrafficForecastingResponseResultTrafficAlertsAlertsInner) HasDate() bool`

HasDate returns a boolean if a field has been set.

### GetPredictedTraffic

`func (o *TrafficForecastingResponseResultTrafficAlertsAlertsInner) GetPredictedTraffic() float32`

GetPredictedTraffic returns the PredictedTraffic field if non-nil, zero value otherwise.

### GetPredictedTrafficOk

`func (o *TrafficForecastingResponseResultTrafficAlertsAlertsInner) GetPredictedTrafficOk() (*float32, bool)`

GetPredictedTrafficOk returns a tuple with the PredictedTraffic field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPredictedTraffic

`func (o *TrafficForecastingResponseResultTrafficAlertsAlertsInner) SetPredictedTraffic(v float32)`

SetPredictedTraffic sets PredictedTraffic field to given value.

### HasPredictedTraffic

`func (o *TrafficForecastingResponseResultTrafficAlertsAlertsInner) HasPredictedTraffic() bool`

HasPredictedTraffic returns a boolean if a field has been set.

### GetBaselineTraffic

`func (o *TrafficForecastingResponseResultTrafficAlertsAlertsInner) GetBaselineTraffic() float32`

GetBaselineTraffic returns the BaselineTraffic field if non-nil, zero value otherwise.

### GetBaselineTrafficOk

`func (o *TrafficForecastingResponseResultTrafficAlertsAlertsInner) GetBaselineTrafficOk() (*float32, bool)`

GetBaselineTrafficOk returns a tuple with the BaselineTraffic field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBaselineTraffic

`func (o *TrafficForecastingResponseResultTrafficAlertsAlertsInner) SetBaselineTraffic(v float32)`

SetBaselineTraffic sets BaselineTraffic field to given value.

### HasBaselineTraffic

`func (o *TrafficForecastingResponseResultTrafficAlertsAlertsInner) HasBaselineTraffic() bool`

HasBaselineTraffic returns a boolean if a field has been set.

### GetIncreaseFactor

`func (o *TrafficForecastingResponseResultTrafficAlertsAlertsInner) GetIncreaseFactor() float32`

GetIncreaseFactor returns the IncreaseFactor field if non-nil, zero value otherwise.

### GetIncreaseFactorOk

`func (o *TrafficForecastingResponseResultTrafficAlertsAlertsInner) GetIncreaseFactorOk() (*float32, bool)`

GetIncreaseFactorOk returns a tuple with the IncreaseFactor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIncreaseFactor

`func (o *TrafficForecastingResponseResultTrafficAlertsAlertsInner) SetIncreaseFactor(v float32)`

SetIncreaseFactor sets IncreaseFactor field to given value.

### HasIncreaseFactor

`func (o *TrafficForecastingResponseResultTrafficAlertsAlertsInner) HasIncreaseFactor() bool`

HasIncreaseFactor returns a boolean if a field has been set.

### GetZScore

`func (o *TrafficForecastingResponseResultTrafficAlertsAlertsInner) GetZScore() float32`

GetZScore returns the ZScore field if non-nil, zero value otherwise.

### GetZScoreOk

`func (o *TrafficForecastingResponseResultTrafficAlertsAlertsInner) GetZScoreOk() (*float32, bool)`

GetZScoreOk returns a tuple with the ZScore field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetZScore

`func (o *TrafficForecastingResponseResultTrafficAlertsAlertsInner) SetZScore(v float32)`

SetZScore sets ZScore field to given value.

### HasZScore

`func (o *TrafficForecastingResponseResultTrafficAlertsAlertsInner) HasZScore() bool`

HasZScore returns a boolean if a field has been set.

### GetMessage

`func (o *TrafficForecastingResponseResultTrafficAlertsAlertsInner) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *TrafficForecastingResponseResultTrafficAlertsAlertsInner) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *TrafficForecastingResponseResultTrafficAlertsAlertsInner) SetMessage(v string)`

SetMessage sets Message field to given value.

### HasMessage

`func (o *TrafficForecastingResponseResultTrafficAlertsAlertsInner) HasMessage() bool`

HasMessage returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


