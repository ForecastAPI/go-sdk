# TrafficForecastingResponseResultForecastDataInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Period** | Pointer to **int32** | Forecast period number | [optional] 
**Date** | Pointer to **time.Time** | Date/time for this forecast period | [optional] 
**Forecast** | Pointer to **float32** | Forecasted traffic value | [optional] 
**Lower** | Pointer to **float32** | Lower confidence bound | [optional] 
**Upper** | Pointer to **float32** | Upper confidence bound | [optional] 

## Methods

### NewTrafficForecastingResponseResultForecastDataInner

`func NewTrafficForecastingResponseResultForecastDataInner() *TrafficForecastingResponseResultForecastDataInner`

NewTrafficForecastingResponseResultForecastDataInner instantiates a new TrafficForecastingResponseResultForecastDataInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTrafficForecastingResponseResultForecastDataInnerWithDefaults

`func NewTrafficForecastingResponseResultForecastDataInnerWithDefaults() *TrafficForecastingResponseResultForecastDataInner`

NewTrafficForecastingResponseResultForecastDataInnerWithDefaults instantiates a new TrafficForecastingResponseResultForecastDataInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPeriod

`func (o *TrafficForecastingResponseResultForecastDataInner) GetPeriod() int32`

GetPeriod returns the Period field if non-nil, zero value otherwise.

### GetPeriodOk

`func (o *TrafficForecastingResponseResultForecastDataInner) GetPeriodOk() (*int32, bool)`

GetPeriodOk returns a tuple with the Period field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPeriod

`func (o *TrafficForecastingResponseResultForecastDataInner) SetPeriod(v int32)`

SetPeriod sets Period field to given value.

### HasPeriod

`func (o *TrafficForecastingResponseResultForecastDataInner) HasPeriod() bool`

HasPeriod returns a boolean if a field has been set.

### GetDate

`func (o *TrafficForecastingResponseResultForecastDataInner) GetDate() time.Time`

GetDate returns the Date field if non-nil, zero value otherwise.

### GetDateOk

`func (o *TrafficForecastingResponseResultForecastDataInner) GetDateOk() (*time.Time, bool)`

GetDateOk returns a tuple with the Date field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDate

`func (o *TrafficForecastingResponseResultForecastDataInner) SetDate(v time.Time)`

SetDate sets Date field to given value.

### HasDate

`func (o *TrafficForecastingResponseResultForecastDataInner) HasDate() bool`

HasDate returns a boolean if a field has been set.

### GetForecast

`func (o *TrafficForecastingResponseResultForecastDataInner) GetForecast() float32`

GetForecast returns the Forecast field if non-nil, zero value otherwise.

### GetForecastOk

`func (o *TrafficForecastingResponseResultForecastDataInner) GetForecastOk() (*float32, bool)`

GetForecastOk returns a tuple with the Forecast field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetForecast

`func (o *TrafficForecastingResponseResultForecastDataInner) SetForecast(v float32)`

SetForecast sets Forecast field to given value.

### HasForecast

`func (o *TrafficForecastingResponseResultForecastDataInner) HasForecast() bool`

HasForecast returns a boolean if a field has been set.

### GetLower

`func (o *TrafficForecastingResponseResultForecastDataInner) GetLower() float32`

GetLower returns the Lower field if non-nil, zero value otherwise.

### GetLowerOk

`func (o *TrafficForecastingResponseResultForecastDataInner) GetLowerOk() (*float32, bool)`

GetLowerOk returns a tuple with the Lower field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLower

`func (o *TrafficForecastingResponseResultForecastDataInner) SetLower(v float32)`

SetLower sets Lower field to given value.

### HasLower

`func (o *TrafficForecastingResponseResultForecastDataInner) HasLower() bool`

HasLower returns a boolean if a field has been set.

### GetUpper

`func (o *TrafficForecastingResponseResultForecastDataInner) GetUpper() float32`

GetUpper returns the Upper field if non-nil, zero value otherwise.

### GetUpperOk

`func (o *TrafficForecastingResponseResultForecastDataInner) GetUpperOk() (*float32, bool)`

GetUpperOk returns a tuple with the Upper field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpper

`func (o *TrafficForecastingResponseResultForecastDataInner) SetUpper(v float32)`

SetUpper sets Upper field to given value.

### HasUpper

`func (o *TrafficForecastingResponseResultForecastDataInner) HasUpper() bool`

HasUpper returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


