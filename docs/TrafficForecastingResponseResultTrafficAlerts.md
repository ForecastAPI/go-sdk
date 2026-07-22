# TrafficForecastingResponseResultTrafficAlerts

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**TotalAlerts** | Pointer to **int32** | Total number of alerts generated | [optional] 
**HighSeverity** | Pointer to **int32** | Number of high severity alerts | [optional] 
**MediumSeverity** | Pointer to **int32** | Number of medium severity alerts | [optional] 
**Alerts** | Pointer to [**[]TrafficForecastingResponseResultTrafficAlertsAlertsInner**](TrafficForecastingResponseResultTrafficAlertsAlertsInner.md) | Individual alert details | [optional] 

## Methods

### NewTrafficForecastingResponseResultTrafficAlerts

`func NewTrafficForecastingResponseResultTrafficAlerts() *TrafficForecastingResponseResultTrafficAlerts`

NewTrafficForecastingResponseResultTrafficAlerts instantiates a new TrafficForecastingResponseResultTrafficAlerts object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTrafficForecastingResponseResultTrafficAlertsWithDefaults

`func NewTrafficForecastingResponseResultTrafficAlertsWithDefaults() *TrafficForecastingResponseResultTrafficAlerts`

NewTrafficForecastingResponseResultTrafficAlertsWithDefaults instantiates a new TrafficForecastingResponseResultTrafficAlerts object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTotalAlerts

`func (o *TrafficForecastingResponseResultTrafficAlerts) GetTotalAlerts() int32`

GetTotalAlerts returns the TotalAlerts field if non-nil, zero value otherwise.

### GetTotalAlertsOk

`func (o *TrafficForecastingResponseResultTrafficAlerts) GetTotalAlertsOk() (*int32, bool)`

GetTotalAlertsOk returns a tuple with the TotalAlerts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalAlerts

`func (o *TrafficForecastingResponseResultTrafficAlerts) SetTotalAlerts(v int32)`

SetTotalAlerts sets TotalAlerts field to given value.

### HasTotalAlerts

`func (o *TrafficForecastingResponseResultTrafficAlerts) HasTotalAlerts() bool`

HasTotalAlerts returns a boolean if a field has been set.

### GetHighSeverity

`func (o *TrafficForecastingResponseResultTrafficAlerts) GetHighSeverity() int32`

GetHighSeverity returns the HighSeverity field if non-nil, zero value otherwise.

### GetHighSeverityOk

`func (o *TrafficForecastingResponseResultTrafficAlerts) GetHighSeverityOk() (*int32, bool)`

GetHighSeverityOk returns a tuple with the HighSeverity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHighSeverity

`func (o *TrafficForecastingResponseResultTrafficAlerts) SetHighSeverity(v int32)`

SetHighSeverity sets HighSeverity field to given value.

### HasHighSeverity

`func (o *TrafficForecastingResponseResultTrafficAlerts) HasHighSeverity() bool`

HasHighSeverity returns a boolean if a field has been set.

### GetMediumSeverity

`func (o *TrafficForecastingResponseResultTrafficAlerts) GetMediumSeverity() int32`

GetMediumSeverity returns the MediumSeverity field if non-nil, zero value otherwise.

### GetMediumSeverityOk

`func (o *TrafficForecastingResponseResultTrafficAlerts) GetMediumSeverityOk() (*int32, bool)`

GetMediumSeverityOk returns a tuple with the MediumSeverity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMediumSeverity

`func (o *TrafficForecastingResponseResultTrafficAlerts) SetMediumSeverity(v int32)`

SetMediumSeverity sets MediumSeverity field to given value.

### HasMediumSeverity

`func (o *TrafficForecastingResponseResultTrafficAlerts) HasMediumSeverity() bool`

HasMediumSeverity returns a boolean if a field has been set.

### GetAlerts

`func (o *TrafficForecastingResponseResultTrafficAlerts) GetAlerts() []TrafficForecastingResponseResultTrafficAlertsAlertsInner`

GetAlerts returns the Alerts field if non-nil, zero value otherwise.

### GetAlertsOk

`func (o *TrafficForecastingResponseResultTrafficAlerts) GetAlertsOk() (*[]TrafficForecastingResponseResultTrafficAlertsAlertsInner, bool)`

GetAlertsOk returns a tuple with the Alerts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAlerts

`func (o *TrafficForecastingResponseResultTrafficAlerts) SetAlerts(v []TrafficForecastingResponseResultTrafficAlertsAlertsInner)`

SetAlerts sets Alerts field to given value.

### HasAlerts

`func (o *TrafficForecastingResponseResultTrafficAlerts) HasAlerts() bool`

HasAlerts returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


