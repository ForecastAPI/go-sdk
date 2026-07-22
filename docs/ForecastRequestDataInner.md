# ForecastRequestDataInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Date** | **string** | Date of the data point | 
**Value** | **float32** | Numeric value for the data point | 

## Methods

### NewForecastRequestDataInner

`func NewForecastRequestDataInner(date string, value float32, ) *ForecastRequestDataInner`

NewForecastRequestDataInner instantiates a new ForecastRequestDataInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewForecastRequestDataInnerWithDefaults

`func NewForecastRequestDataInnerWithDefaults() *ForecastRequestDataInner`

NewForecastRequestDataInnerWithDefaults instantiates a new ForecastRequestDataInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDate

`func (o *ForecastRequestDataInner) GetDate() string`

GetDate returns the Date field if non-nil, zero value otherwise.

### GetDateOk

`func (o *ForecastRequestDataInner) GetDateOk() (*string, bool)`

GetDateOk returns a tuple with the Date field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDate

`func (o *ForecastRequestDataInner) SetDate(v string)`

SetDate sets Date field to given value.


### GetValue

`func (o *ForecastRequestDataInner) GetValue() float32`

GetValue returns the Value field if non-nil, zero value otherwise.

### GetValueOk

`func (o *ForecastRequestDataInner) GetValueOk() (*float32, bool)`

GetValueOk returns a tuple with the Value field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValue

`func (o *ForecastRequestDataInner) SetValue(v float32)`

SetValue sets Value field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


