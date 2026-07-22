# AccumulatedForecastAssumptions

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Correlation** | Pointer to **float32** |  | [optional] 
**CorrelationSource** | Pointer to **string** |  | [optional] 
**Measured** | Pointer to **bool** | True only when the correlation in force is our measured default — a caller-supplied value is never labelled measured | [optional] 
**Basis** | Pointer to **string** | The statistical model behind the total&#39;s band | [optional] 
**Decay** | Pointer to **float32** |  | [optional] 
**DiscountRate** | Pointer to **float32** |  | [optional] 
**PeriodsPerYear** | Pointer to **float32** | How the annual discount rate was converted to the series frequency | [optional] 
**Timing** | Pointer to **string** |  | [optional] 

## Methods

### NewAccumulatedForecastAssumptions

`func NewAccumulatedForecastAssumptions() *AccumulatedForecastAssumptions`

NewAccumulatedForecastAssumptions instantiates a new AccumulatedForecastAssumptions object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAccumulatedForecastAssumptionsWithDefaults

`func NewAccumulatedForecastAssumptionsWithDefaults() *AccumulatedForecastAssumptions`

NewAccumulatedForecastAssumptionsWithDefaults instantiates a new AccumulatedForecastAssumptions object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCorrelation

`func (o *AccumulatedForecastAssumptions) GetCorrelation() float32`

GetCorrelation returns the Correlation field if non-nil, zero value otherwise.

### GetCorrelationOk

`func (o *AccumulatedForecastAssumptions) GetCorrelationOk() (*float32, bool)`

GetCorrelationOk returns a tuple with the Correlation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCorrelation

`func (o *AccumulatedForecastAssumptions) SetCorrelation(v float32)`

SetCorrelation sets Correlation field to given value.

### HasCorrelation

`func (o *AccumulatedForecastAssumptions) HasCorrelation() bool`

HasCorrelation returns a boolean if a field has been set.

### GetCorrelationSource

`func (o *AccumulatedForecastAssumptions) GetCorrelationSource() string`

GetCorrelationSource returns the CorrelationSource field if non-nil, zero value otherwise.

### GetCorrelationSourceOk

`func (o *AccumulatedForecastAssumptions) GetCorrelationSourceOk() (*string, bool)`

GetCorrelationSourceOk returns a tuple with the CorrelationSource field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCorrelationSource

`func (o *AccumulatedForecastAssumptions) SetCorrelationSource(v string)`

SetCorrelationSource sets CorrelationSource field to given value.

### HasCorrelationSource

`func (o *AccumulatedForecastAssumptions) HasCorrelationSource() bool`

HasCorrelationSource returns a boolean if a field has been set.

### GetMeasured

`func (o *AccumulatedForecastAssumptions) GetMeasured() bool`

GetMeasured returns the Measured field if non-nil, zero value otherwise.

### GetMeasuredOk

`func (o *AccumulatedForecastAssumptions) GetMeasuredOk() (*bool, bool)`

GetMeasuredOk returns a tuple with the Measured field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMeasured

`func (o *AccumulatedForecastAssumptions) SetMeasured(v bool)`

SetMeasured sets Measured field to given value.

### HasMeasured

`func (o *AccumulatedForecastAssumptions) HasMeasured() bool`

HasMeasured returns a boolean if a field has been set.

### GetBasis

`func (o *AccumulatedForecastAssumptions) GetBasis() string`

GetBasis returns the Basis field if non-nil, zero value otherwise.

### GetBasisOk

`func (o *AccumulatedForecastAssumptions) GetBasisOk() (*string, bool)`

GetBasisOk returns a tuple with the Basis field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBasis

`func (o *AccumulatedForecastAssumptions) SetBasis(v string)`

SetBasis sets Basis field to given value.

### HasBasis

`func (o *AccumulatedForecastAssumptions) HasBasis() bool`

HasBasis returns a boolean if a field has been set.

### GetDecay

`func (o *AccumulatedForecastAssumptions) GetDecay() float32`

GetDecay returns the Decay field if non-nil, zero value otherwise.

### GetDecayOk

`func (o *AccumulatedForecastAssumptions) GetDecayOk() (*float32, bool)`

GetDecayOk returns a tuple with the Decay field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDecay

`func (o *AccumulatedForecastAssumptions) SetDecay(v float32)`

SetDecay sets Decay field to given value.

### HasDecay

`func (o *AccumulatedForecastAssumptions) HasDecay() bool`

HasDecay returns a boolean if a field has been set.

### GetDiscountRate

`func (o *AccumulatedForecastAssumptions) GetDiscountRate() float32`

GetDiscountRate returns the DiscountRate field if non-nil, zero value otherwise.

### GetDiscountRateOk

`func (o *AccumulatedForecastAssumptions) GetDiscountRateOk() (*float32, bool)`

GetDiscountRateOk returns a tuple with the DiscountRate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDiscountRate

`func (o *AccumulatedForecastAssumptions) SetDiscountRate(v float32)`

SetDiscountRate sets DiscountRate field to given value.

### HasDiscountRate

`func (o *AccumulatedForecastAssumptions) HasDiscountRate() bool`

HasDiscountRate returns a boolean if a field has been set.

### GetPeriodsPerYear

`func (o *AccumulatedForecastAssumptions) GetPeriodsPerYear() float32`

GetPeriodsPerYear returns the PeriodsPerYear field if non-nil, zero value otherwise.

### GetPeriodsPerYearOk

`func (o *AccumulatedForecastAssumptions) GetPeriodsPerYearOk() (*float32, bool)`

GetPeriodsPerYearOk returns a tuple with the PeriodsPerYear field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPeriodsPerYear

`func (o *AccumulatedForecastAssumptions) SetPeriodsPerYear(v float32)`

SetPeriodsPerYear sets PeriodsPerYear field to given value.

### HasPeriodsPerYear

`func (o *AccumulatedForecastAssumptions) HasPeriodsPerYear() bool`

HasPeriodsPerYear returns a boolean if a field has been set.

### GetTiming

`func (o *AccumulatedForecastAssumptions) GetTiming() string`

GetTiming returns the Timing field if non-nil, zero value otherwise.

### GetTimingOk

`func (o *AccumulatedForecastAssumptions) GetTimingOk() (*string, bool)`

GetTimingOk returns a tuple with the Timing field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTiming

`func (o *AccumulatedForecastAssumptions) SetTiming(v string)`

SetTiming sets Timing field to given value.

### HasTiming

`func (o *AccumulatedForecastAssumptions) HasTiming() bool`

HasTiming returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


