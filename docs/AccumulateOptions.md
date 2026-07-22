# AccumulateOptions

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Decay** | Pointer to **float32** | Per-period survival factor — 0.95 means 5% attrition each period | [optional] [default to 1.0]
**DiscountRate** | Pointer to **float32** | Annual discount rate, converted to the series frequency (a 10% annual rate on monthly periods discounts period 2 by 1.10^(-1/12), not by 1.10) | [optional] [default to 0]
**Correlation** | Pointer to **float32** | How correlated the per-period errors are assumed to be; controls only the width of the total&#39;s band. 0 &#x3D; independent periods (measurably too narrow), 1 &#x3D; sum of the bounds (conservative envelope). The default 0.5 was measured across the benchmark suite; a value you supply is your assumption and is never labelled measured.  | [optional] [default to 0.5]

## Methods

### NewAccumulateOptions

`func NewAccumulateOptions() *AccumulateOptions`

NewAccumulateOptions instantiates a new AccumulateOptions object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAccumulateOptionsWithDefaults

`func NewAccumulateOptionsWithDefaults() *AccumulateOptions`

NewAccumulateOptionsWithDefaults instantiates a new AccumulateOptions object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDecay

`func (o *AccumulateOptions) GetDecay() float32`

GetDecay returns the Decay field if non-nil, zero value otherwise.

### GetDecayOk

`func (o *AccumulateOptions) GetDecayOk() (*float32, bool)`

GetDecayOk returns a tuple with the Decay field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDecay

`func (o *AccumulateOptions) SetDecay(v float32)`

SetDecay sets Decay field to given value.

### HasDecay

`func (o *AccumulateOptions) HasDecay() bool`

HasDecay returns a boolean if a field has been set.

### GetDiscountRate

`func (o *AccumulateOptions) GetDiscountRate() float32`

GetDiscountRate returns the DiscountRate field if non-nil, zero value otherwise.

### GetDiscountRateOk

`func (o *AccumulateOptions) GetDiscountRateOk() (*float32, bool)`

GetDiscountRateOk returns a tuple with the DiscountRate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDiscountRate

`func (o *AccumulateOptions) SetDiscountRate(v float32)`

SetDiscountRate sets DiscountRate field to given value.

### HasDiscountRate

`func (o *AccumulateOptions) HasDiscountRate() bool`

HasDiscountRate returns a boolean if a field has been set.

### GetCorrelation

`func (o *AccumulateOptions) GetCorrelation() float32`

GetCorrelation returns the Correlation field if non-nil, zero value otherwise.

### GetCorrelationOk

`func (o *AccumulateOptions) GetCorrelationOk() (*float32, bool)`

GetCorrelationOk returns a tuple with the Correlation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCorrelation

`func (o *AccumulateOptions) SetCorrelation(v float32)`

SetCorrelation sets Correlation field to given value.

### HasCorrelation

`func (o *AccumulateOptions) HasCorrelation() bool`

HasCorrelation returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


