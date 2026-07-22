# ForecastResponseMetaTiming

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Validation** | Pointer to **float32** | Time taken for validation in milliseconds | [optional] 
**Selection** | Pointer to **float32** | Time taken for method selection in milliseconds | [optional] 
**Forecasting** | Pointer to **float32** | Time taken for forecasting in milliseconds | [optional] 
**Total** | Pointer to **float32** | Total processing time in milliseconds | [optional] 

## Methods

### NewForecastResponseMetaTiming

`func NewForecastResponseMetaTiming() *ForecastResponseMetaTiming`

NewForecastResponseMetaTiming instantiates a new ForecastResponseMetaTiming object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewForecastResponseMetaTimingWithDefaults

`func NewForecastResponseMetaTimingWithDefaults() *ForecastResponseMetaTiming`

NewForecastResponseMetaTimingWithDefaults instantiates a new ForecastResponseMetaTiming object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetValidation

`func (o *ForecastResponseMetaTiming) GetValidation() float32`

GetValidation returns the Validation field if non-nil, zero value otherwise.

### GetValidationOk

`func (o *ForecastResponseMetaTiming) GetValidationOk() (*float32, bool)`

GetValidationOk returns a tuple with the Validation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValidation

`func (o *ForecastResponseMetaTiming) SetValidation(v float32)`

SetValidation sets Validation field to given value.

### HasValidation

`func (o *ForecastResponseMetaTiming) HasValidation() bool`

HasValidation returns a boolean if a field has been set.

### GetSelection

`func (o *ForecastResponseMetaTiming) GetSelection() float32`

GetSelection returns the Selection field if non-nil, zero value otherwise.

### GetSelectionOk

`func (o *ForecastResponseMetaTiming) GetSelectionOk() (*float32, bool)`

GetSelectionOk returns a tuple with the Selection field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSelection

`func (o *ForecastResponseMetaTiming) SetSelection(v float32)`

SetSelection sets Selection field to given value.

### HasSelection

`func (o *ForecastResponseMetaTiming) HasSelection() bool`

HasSelection returns a boolean if a field has been set.

### GetForecasting

`func (o *ForecastResponseMetaTiming) GetForecasting() float32`

GetForecasting returns the Forecasting field if non-nil, zero value otherwise.

### GetForecastingOk

`func (o *ForecastResponseMetaTiming) GetForecastingOk() (*float32, bool)`

GetForecastingOk returns a tuple with the Forecasting field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetForecasting

`func (o *ForecastResponseMetaTiming) SetForecasting(v float32)`

SetForecasting sets Forecasting field to given value.

### HasForecasting

`func (o *ForecastResponseMetaTiming) HasForecasting() bool`

HasForecasting returns a boolean if a field has been set.

### GetTotal

`func (o *ForecastResponseMetaTiming) GetTotal() float32`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *ForecastResponseMetaTiming) GetTotalOk() (*float32, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *ForecastResponseMetaTiming) SetTotal(v float32)`

SetTotal sets Total field to given value.

### HasTotal

`func (o *ForecastResponseMetaTiming) HasTotal() bool`

HasTotal returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


