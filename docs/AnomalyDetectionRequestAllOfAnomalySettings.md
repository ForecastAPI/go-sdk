# AnomalyDetectionRequestAllOfAnomalySettings

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Method** | Pointer to **string** | Detection method; auto picks the best fit for the data&#39;s characteristics | [optional] [default to "auto"]
**Threshold** | Pointer to **float32** | Z-score threshold for the zscore method | [optional] 
**Multiplier** | Pointer to **float32** | IQR multiplier for the iqr method | [optional] 
**SeasonalPeriod** | Pointer to **int32** | Season length for the seasonal method; detected automatically when omitted | [optional] 
**MinimumPeriods** | Pointer to **int32** | Minimum data points required before detection runs | [optional] 

## Methods

### NewAnomalyDetectionRequestAllOfAnomalySettings

`func NewAnomalyDetectionRequestAllOfAnomalySettings() *AnomalyDetectionRequestAllOfAnomalySettings`

NewAnomalyDetectionRequestAllOfAnomalySettings instantiates a new AnomalyDetectionRequestAllOfAnomalySettings object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAnomalyDetectionRequestAllOfAnomalySettingsWithDefaults

`func NewAnomalyDetectionRequestAllOfAnomalySettingsWithDefaults() *AnomalyDetectionRequestAllOfAnomalySettings`

NewAnomalyDetectionRequestAllOfAnomalySettingsWithDefaults instantiates a new AnomalyDetectionRequestAllOfAnomalySettings object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMethod

`func (o *AnomalyDetectionRequestAllOfAnomalySettings) GetMethod() string`

GetMethod returns the Method field if non-nil, zero value otherwise.

### GetMethodOk

`func (o *AnomalyDetectionRequestAllOfAnomalySettings) GetMethodOk() (*string, bool)`

GetMethodOk returns a tuple with the Method field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMethod

`func (o *AnomalyDetectionRequestAllOfAnomalySettings) SetMethod(v string)`

SetMethod sets Method field to given value.

### HasMethod

`func (o *AnomalyDetectionRequestAllOfAnomalySettings) HasMethod() bool`

HasMethod returns a boolean if a field has been set.

### GetThreshold

`func (o *AnomalyDetectionRequestAllOfAnomalySettings) GetThreshold() float32`

GetThreshold returns the Threshold field if non-nil, zero value otherwise.

### GetThresholdOk

`func (o *AnomalyDetectionRequestAllOfAnomalySettings) GetThresholdOk() (*float32, bool)`

GetThresholdOk returns a tuple with the Threshold field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetThreshold

`func (o *AnomalyDetectionRequestAllOfAnomalySettings) SetThreshold(v float32)`

SetThreshold sets Threshold field to given value.

### HasThreshold

`func (o *AnomalyDetectionRequestAllOfAnomalySettings) HasThreshold() bool`

HasThreshold returns a boolean if a field has been set.

### GetMultiplier

`func (o *AnomalyDetectionRequestAllOfAnomalySettings) GetMultiplier() float32`

GetMultiplier returns the Multiplier field if non-nil, zero value otherwise.

### GetMultiplierOk

`func (o *AnomalyDetectionRequestAllOfAnomalySettings) GetMultiplierOk() (*float32, bool)`

GetMultiplierOk returns a tuple with the Multiplier field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMultiplier

`func (o *AnomalyDetectionRequestAllOfAnomalySettings) SetMultiplier(v float32)`

SetMultiplier sets Multiplier field to given value.

### HasMultiplier

`func (o *AnomalyDetectionRequestAllOfAnomalySettings) HasMultiplier() bool`

HasMultiplier returns a boolean if a field has been set.

### GetSeasonalPeriod

`func (o *AnomalyDetectionRequestAllOfAnomalySettings) GetSeasonalPeriod() int32`

GetSeasonalPeriod returns the SeasonalPeriod field if non-nil, zero value otherwise.

### GetSeasonalPeriodOk

`func (o *AnomalyDetectionRequestAllOfAnomalySettings) GetSeasonalPeriodOk() (*int32, bool)`

GetSeasonalPeriodOk returns a tuple with the SeasonalPeriod field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSeasonalPeriod

`func (o *AnomalyDetectionRequestAllOfAnomalySettings) SetSeasonalPeriod(v int32)`

SetSeasonalPeriod sets SeasonalPeriod field to given value.

### HasSeasonalPeriod

`func (o *AnomalyDetectionRequestAllOfAnomalySettings) HasSeasonalPeriod() bool`

HasSeasonalPeriod returns a boolean if a field has been set.

### GetMinimumPeriods

`func (o *AnomalyDetectionRequestAllOfAnomalySettings) GetMinimumPeriods() int32`

GetMinimumPeriods returns the MinimumPeriods field if non-nil, zero value otherwise.

### GetMinimumPeriodsOk

`func (o *AnomalyDetectionRequestAllOfAnomalySettings) GetMinimumPeriodsOk() (*int32, bool)`

GetMinimumPeriodsOk returns a tuple with the MinimumPeriods field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMinimumPeriods

`func (o *AnomalyDetectionRequestAllOfAnomalySettings) SetMinimumPeriods(v int32)`

SetMinimumPeriods sets MinimumPeriods field to given value.

### HasMinimumPeriods

`func (o *AnomalyDetectionRequestAllOfAnomalySettings) HasMinimumPeriods() bool`

HasMinimumPeriods returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


