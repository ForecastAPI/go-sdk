# AutoSelectionScoresValue

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Mase** | Pointer to **NullableFloat32** | Realized MASE on this identifier (lower is better; &lt; 1 beats a naive forecast) | [optional] 
**MatchedPeriods** | Pointer to **int32** | Matured forecast/actual pairs behind the score | [optional] 
**ForecastRuns** | Pointer to **int32** | Separate forecast runs the evidence spans | [optional] 

## Methods

### NewAutoSelectionScoresValue

`func NewAutoSelectionScoresValue() *AutoSelectionScoresValue`

NewAutoSelectionScoresValue instantiates a new AutoSelectionScoresValue object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAutoSelectionScoresValueWithDefaults

`func NewAutoSelectionScoresValueWithDefaults() *AutoSelectionScoresValue`

NewAutoSelectionScoresValueWithDefaults instantiates a new AutoSelectionScoresValue object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMase

`func (o *AutoSelectionScoresValue) GetMase() float32`

GetMase returns the Mase field if non-nil, zero value otherwise.

### GetMaseOk

`func (o *AutoSelectionScoresValue) GetMaseOk() (*float32, bool)`

GetMaseOk returns a tuple with the Mase field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMase

`func (o *AutoSelectionScoresValue) SetMase(v float32)`

SetMase sets Mase field to given value.

### HasMase

`func (o *AutoSelectionScoresValue) HasMase() bool`

HasMase returns a boolean if a field has been set.

### SetMaseNil

`func (o *AutoSelectionScoresValue) SetMaseNil(b bool)`

 SetMaseNil sets the value for Mase to be an explicit nil

### UnsetMase
`func (o *AutoSelectionScoresValue) UnsetMase()`

UnsetMase ensures that no value is present for Mase, not even an explicit nil
### GetMatchedPeriods

`func (o *AutoSelectionScoresValue) GetMatchedPeriods() int32`

GetMatchedPeriods returns the MatchedPeriods field if non-nil, zero value otherwise.

### GetMatchedPeriodsOk

`func (o *AutoSelectionScoresValue) GetMatchedPeriodsOk() (*int32, bool)`

GetMatchedPeriodsOk returns a tuple with the MatchedPeriods field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMatchedPeriods

`func (o *AutoSelectionScoresValue) SetMatchedPeriods(v int32)`

SetMatchedPeriods sets MatchedPeriods field to given value.

### HasMatchedPeriods

`func (o *AutoSelectionScoresValue) HasMatchedPeriods() bool`

HasMatchedPeriods returns a boolean if a field has been set.

### GetForecastRuns

`func (o *AutoSelectionScoresValue) GetForecastRuns() int32`

GetForecastRuns returns the ForecastRuns field if non-nil, zero value otherwise.

### GetForecastRunsOk

`func (o *AutoSelectionScoresValue) GetForecastRunsOk() (*int32, bool)`

GetForecastRunsOk returns a tuple with the ForecastRuns field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetForecastRuns

`func (o *AutoSelectionScoresValue) SetForecastRuns(v int32)`

SetForecastRuns sets ForecastRuns field to given value.

### HasForecastRuns

`func (o *AutoSelectionScoresValue) HasForecastRuns() bool`

HasForecastRuns returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


