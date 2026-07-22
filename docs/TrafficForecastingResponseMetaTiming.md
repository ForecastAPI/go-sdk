# TrafficForecastingResponseMetaTiming

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Validation** | Pointer to **float32** | Time taken for request validation in milliseconds | [optional] 
**Forecasting** | Pointer to **float32** | Time taken for traffic forecasting in milliseconds | [optional] 
**Total** | Pointer to **float32** | Total processing time in milliseconds | [optional] 

## Methods

### NewTrafficForecastingResponseMetaTiming

`func NewTrafficForecastingResponseMetaTiming() *TrafficForecastingResponseMetaTiming`

NewTrafficForecastingResponseMetaTiming instantiates a new TrafficForecastingResponseMetaTiming object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTrafficForecastingResponseMetaTimingWithDefaults

`func NewTrafficForecastingResponseMetaTimingWithDefaults() *TrafficForecastingResponseMetaTiming`

NewTrafficForecastingResponseMetaTimingWithDefaults instantiates a new TrafficForecastingResponseMetaTiming object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetValidation

`func (o *TrafficForecastingResponseMetaTiming) GetValidation() float32`

GetValidation returns the Validation field if non-nil, zero value otherwise.

### GetValidationOk

`func (o *TrafficForecastingResponseMetaTiming) GetValidationOk() (*float32, bool)`

GetValidationOk returns a tuple with the Validation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValidation

`func (o *TrafficForecastingResponseMetaTiming) SetValidation(v float32)`

SetValidation sets Validation field to given value.

### HasValidation

`func (o *TrafficForecastingResponseMetaTiming) HasValidation() bool`

HasValidation returns a boolean if a field has been set.

### GetForecasting

`func (o *TrafficForecastingResponseMetaTiming) GetForecasting() float32`

GetForecasting returns the Forecasting field if non-nil, zero value otherwise.

### GetForecastingOk

`func (o *TrafficForecastingResponseMetaTiming) GetForecastingOk() (*float32, bool)`

GetForecastingOk returns a tuple with the Forecasting field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetForecasting

`func (o *TrafficForecastingResponseMetaTiming) SetForecasting(v float32)`

SetForecasting sets Forecasting field to given value.

### HasForecasting

`func (o *TrafficForecastingResponseMetaTiming) HasForecasting() bool`

HasForecasting returns a boolean if a field has been set.

### GetTotal

`func (o *TrafficForecastingResponseMetaTiming) GetTotal() float32`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *TrafficForecastingResponseMetaTiming) GetTotalOk() (*float32, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *TrafficForecastingResponseMetaTiming) SetTotal(v float32)`

SetTotal sets Total field to given value.

### HasTotal

`func (o *TrafficForecastingResponseMetaTiming) HasTotal() bool`

HasTotal returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


