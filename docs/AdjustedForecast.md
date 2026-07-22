# AdjustedForecast

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Forecasts** | Pointer to [**[]ForecastPeriod**](ForecastPeriod.md) | The baseline path with every adjustment applied, in array order | [optional] 
**AdjustmentsApplied** | Pointer to [**[]AdjustedForecastAdjustmentsAppliedInner**](AdjustedForecastAdjustmentsAppliedInner.md) | Echo of each adjustment as applied, in order | [optional] 
**Stored** | Pointer to **bool** | Always false — only the baseline in &#x60;result&#x60; is persisted and scored for accuracy | [optional] 

## Methods

### NewAdjustedForecast

`func NewAdjustedForecast() *AdjustedForecast`

NewAdjustedForecast instantiates a new AdjustedForecast object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAdjustedForecastWithDefaults

`func NewAdjustedForecastWithDefaults() *AdjustedForecast`

NewAdjustedForecastWithDefaults instantiates a new AdjustedForecast object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetForecasts

`func (o *AdjustedForecast) GetForecasts() []ForecastPeriod`

GetForecasts returns the Forecasts field if non-nil, zero value otherwise.

### GetForecastsOk

`func (o *AdjustedForecast) GetForecastsOk() (*[]ForecastPeriod, bool)`

GetForecastsOk returns a tuple with the Forecasts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetForecasts

`func (o *AdjustedForecast) SetForecasts(v []ForecastPeriod)`

SetForecasts sets Forecasts field to given value.

### HasForecasts

`func (o *AdjustedForecast) HasForecasts() bool`

HasForecasts returns a boolean if a field has been set.

### GetAdjustmentsApplied

`func (o *AdjustedForecast) GetAdjustmentsApplied() []AdjustedForecastAdjustmentsAppliedInner`

GetAdjustmentsApplied returns the AdjustmentsApplied field if non-nil, zero value otherwise.

### GetAdjustmentsAppliedOk

`func (o *AdjustedForecast) GetAdjustmentsAppliedOk() (*[]AdjustedForecastAdjustmentsAppliedInner, bool)`

GetAdjustmentsAppliedOk returns a tuple with the AdjustmentsApplied field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAdjustmentsApplied

`func (o *AdjustedForecast) SetAdjustmentsApplied(v []AdjustedForecastAdjustmentsAppliedInner)`

SetAdjustmentsApplied sets AdjustmentsApplied field to given value.

### HasAdjustmentsApplied

`func (o *AdjustedForecast) HasAdjustmentsApplied() bool`

HasAdjustmentsApplied returns a boolean if a field has been set.

### GetStored

`func (o *AdjustedForecast) GetStored() bool`

GetStored returns the Stored field if non-nil, zero value otherwise.

### GetStoredOk

`func (o *AdjustedForecast) GetStoredOk() (*bool, bool)`

GetStoredOk returns a tuple with the Stored field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStored

`func (o *AdjustedForecast) SetStored(v bool)`

SetStored sets Stored field to given value.

### HasStored

`func (o *AdjustedForecast) HasStored() bool`

HasStored returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


