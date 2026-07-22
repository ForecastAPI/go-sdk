# AccumulatedForecastByPeriodInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Date** | Pointer to **string** |  | [optional] 
**Weight** | Pointer to **float32** | survival × discount weight applied to this period (period 1 is 1.0) | [optional] 
**Cumulative** | Pointer to **float32** | Running weighted total through this period | [optional] 
**CumulativeLower** | Pointer to **float32** | Running lower bound; present only when every period so far has a usable band | [optional] 
**CumulativeUpper** | Pointer to **float32** |  | [optional] 

## Methods

### NewAccumulatedForecastByPeriodInner

`func NewAccumulatedForecastByPeriodInner() *AccumulatedForecastByPeriodInner`

NewAccumulatedForecastByPeriodInner instantiates a new AccumulatedForecastByPeriodInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAccumulatedForecastByPeriodInnerWithDefaults

`func NewAccumulatedForecastByPeriodInnerWithDefaults() *AccumulatedForecastByPeriodInner`

NewAccumulatedForecastByPeriodInnerWithDefaults instantiates a new AccumulatedForecastByPeriodInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDate

`func (o *AccumulatedForecastByPeriodInner) GetDate() string`

GetDate returns the Date field if non-nil, zero value otherwise.

### GetDateOk

`func (o *AccumulatedForecastByPeriodInner) GetDateOk() (*string, bool)`

GetDateOk returns a tuple with the Date field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDate

`func (o *AccumulatedForecastByPeriodInner) SetDate(v string)`

SetDate sets Date field to given value.

### HasDate

`func (o *AccumulatedForecastByPeriodInner) HasDate() bool`

HasDate returns a boolean if a field has been set.

### GetWeight

`func (o *AccumulatedForecastByPeriodInner) GetWeight() float32`

GetWeight returns the Weight field if non-nil, zero value otherwise.

### GetWeightOk

`func (o *AccumulatedForecastByPeriodInner) GetWeightOk() (*float32, bool)`

GetWeightOk returns a tuple with the Weight field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWeight

`func (o *AccumulatedForecastByPeriodInner) SetWeight(v float32)`

SetWeight sets Weight field to given value.

### HasWeight

`func (o *AccumulatedForecastByPeriodInner) HasWeight() bool`

HasWeight returns a boolean if a field has been set.

### GetCumulative

`func (o *AccumulatedForecastByPeriodInner) GetCumulative() float32`

GetCumulative returns the Cumulative field if non-nil, zero value otherwise.

### GetCumulativeOk

`func (o *AccumulatedForecastByPeriodInner) GetCumulativeOk() (*float32, bool)`

GetCumulativeOk returns a tuple with the Cumulative field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCumulative

`func (o *AccumulatedForecastByPeriodInner) SetCumulative(v float32)`

SetCumulative sets Cumulative field to given value.

### HasCumulative

`func (o *AccumulatedForecastByPeriodInner) HasCumulative() bool`

HasCumulative returns a boolean if a field has been set.

### GetCumulativeLower

`func (o *AccumulatedForecastByPeriodInner) GetCumulativeLower() float32`

GetCumulativeLower returns the CumulativeLower field if non-nil, zero value otherwise.

### GetCumulativeLowerOk

`func (o *AccumulatedForecastByPeriodInner) GetCumulativeLowerOk() (*float32, bool)`

GetCumulativeLowerOk returns a tuple with the CumulativeLower field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCumulativeLower

`func (o *AccumulatedForecastByPeriodInner) SetCumulativeLower(v float32)`

SetCumulativeLower sets CumulativeLower field to given value.

### HasCumulativeLower

`func (o *AccumulatedForecastByPeriodInner) HasCumulativeLower() bool`

HasCumulativeLower returns a boolean if a field has been set.

### GetCumulativeUpper

`func (o *AccumulatedForecastByPeriodInner) GetCumulativeUpper() float32`

GetCumulativeUpper returns the CumulativeUpper field if non-nil, zero value otherwise.

### GetCumulativeUpperOk

`func (o *AccumulatedForecastByPeriodInner) GetCumulativeUpperOk() (*float32, bool)`

GetCumulativeUpperOk returns a tuple with the CumulativeUpper field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCumulativeUpper

`func (o *AccumulatedForecastByPeriodInner) SetCumulativeUpper(v float32)`

SetCumulativeUpper sets CumulativeUpper field to given value.

### HasCumulativeUpper

`func (o *AccumulatedForecastByPeriodInner) HasCumulativeUpper() bool`

HasCumulativeUpper returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


