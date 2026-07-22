# ForecastPeriod

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Period** | Pointer to **int32** | 1-based forecast period number | [optional] 
**Date** | Pointer to **string** | Date of this forecast period | [optional] 
**Forecast** | Pointer to **float32** | Point forecast for this period | [optional] 
**Lower** | Pointer to **float32** | Lower prediction bound at the requested confidence level | [optional] 
**Upper** | Pointer to **float32** | Upper prediction bound at the requested confidence level | [optional] 
**Quantiles** | Pointer to **map[string]float32** | Present only when &#x60;quantiles&#x60; was requested — the forecast at each requested decile level for this period | [optional] 

## Methods

### NewForecastPeriod

`func NewForecastPeriod() *ForecastPeriod`

NewForecastPeriod instantiates a new ForecastPeriod object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewForecastPeriodWithDefaults

`func NewForecastPeriodWithDefaults() *ForecastPeriod`

NewForecastPeriodWithDefaults instantiates a new ForecastPeriod object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPeriod

`func (o *ForecastPeriod) GetPeriod() int32`

GetPeriod returns the Period field if non-nil, zero value otherwise.

### GetPeriodOk

`func (o *ForecastPeriod) GetPeriodOk() (*int32, bool)`

GetPeriodOk returns a tuple with the Period field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPeriod

`func (o *ForecastPeriod) SetPeriod(v int32)`

SetPeriod sets Period field to given value.

### HasPeriod

`func (o *ForecastPeriod) HasPeriod() bool`

HasPeriod returns a boolean if a field has been set.

### GetDate

`func (o *ForecastPeriod) GetDate() string`

GetDate returns the Date field if non-nil, zero value otherwise.

### GetDateOk

`func (o *ForecastPeriod) GetDateOk() (*string, bool)`

GetDateOk returns a tuple with the Date field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDate

`func (o *ForecastPeriod) SetDate(v string)`

SetDate sets Date field to given value.

### HasDate

`func (o *ForecastPeriod) HasDate() bool`

HasDate returns a boolean if a field has been set.

### GetForecast

`func (o *ForecastPeriod) GetForecast() float32`

GetForecast returns the Forecast field if non-nil, zero value otherwise.

### GetForecastOk

`func (o *ForecastPeriod) GetForecastOk() (*float32, bool)`

GetForecastOk returns a tuple with the Forecast field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetForecast

`func (o *ForecastPeriod) SetForecast(v float32)`

SetForecast sets Forecast field to given value.

### HasForecast

`func (o *ForecastPeriod) HasForecast() bool`

HasForecast returns a boolean if a field has been set.

### GetLower

`func (o *ForecastPeriod) GetLower() float32`

GetLower returns the Lower field if non-nil, zero value otherwise.

### GetLowerOk

`func (o *ForecastPeriod) GetLowerOk() (*float32, bool)`

GetLowerOk returns a tuple with the Lower field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLower

`func (o *ForecastPeriod) SetLower(v float32)`

SetLower sets Lower field to given value.

### HasLower

`func (o *ForecastPeriod) HasLower() bool`

HasLower returns a boolean if a field has been set.

### GetUpper

`func (o *ForecastPeriod) GetUpper() float32`

GetUpper returns the Upper field if non-nil, zero value otherwise.

### GetUpperOk

`func (o *ForecastPeriod) GetUpperOk() (*float32, bool)`

GetUpperOk returns a tuple with the Upper field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpper

`func (o *ForecastPeriod) SetUpper(v float32)`

SetUpper sets Upper field to given value.

### HasUpper

`func (o *ForecastPeriod) HasUpper() bool`

HasUpper returns a boolean if a field has been set.

### GetQuantiles

`func (o *ForecastPeriod) GetQuantiles() map[string]float32`

GetQuantiles returns the Quantiles field if non-nil, zero value otherwise.

### GetQuantilesOk

`func (o *ForecastPeriod) GetQuantilesOk() (*map[string]float32, bool)`

GetQuantilesOk returns a tuple with the Quantiles field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantiles

`func (o *ForecastPeriod) SetQuantiles(v map[string]float32)`

SetQuantiles sets Quantiles field to given value.

### HasQuantiles

`func (o *ForecastPeriod) HasQuantiles() bool`

HasQuantiles returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


