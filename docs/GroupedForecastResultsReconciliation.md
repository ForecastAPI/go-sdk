# GroupedForecastResultsReconciliation

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Method** | Pointer to **string** |  | [optional] 
**Correlation** | Pointer to **float32** | bottom_up only | [optional] 
**CorrelationSource** | Pointer to **string** | bottom_up only | [optional] 
**Measured** | Pointer to **bool** | bottom_up only — always false; the cross-sibling correlation is an assumption | [optional] 
**Variant** | Pointer to **NullableString** | min_trace only — the MinTrace weighting used | [optional] 
**Nonnegative** | Pointer to **bool** | min_trace only — whether the non-negative solve was applied | [optional] 

## Methods

### NewGroupedForecastResultsReconciliation

`func NewGroupedForecastResultsReconciliation() *GroupedForecastResultsReconciliation`

NewGroupedForecastResultsReconciliation instantiates a new GroupedForecastResultsReconciliation object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGroupedForecastResultsReconciliationWithDefaults

`func NewGroupedForecastResultsReconciliationWithDefaults() *GroupedForecastResultsReconciliation`

NewGroupedForecastResultsReconciliationWithDefaults instantiates a new GroupedForecastResultsReconciliation object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMethod

`func (o *GroupedForecastResultsReconciliation) GetMethod() string`

GetMethod returns the Method field if non-nil, zero value otherwise.

### GetMethodOk

`func (o *GroupedForecastResultsReconciliation) GetMethodOk() (*string, bool)`

GetMethodOk returns a tuple with the Method field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMethod

`func (o *GroupedForecastResultsReconciliation) SetMethod(v string)`

SetMethod sets Method field to given value.

### HasMethod

`func (o *GroupedForecastResultsReconciliation) HasMethod() bool`

HasMethod returns a boolean if a field has been set.

### GetCorrelation

`func (o *GroupedForecastResultsReconciliation) GetCorrelation() float32`

GetCorrelation returns the Correlation field if non-nil, zero value otherwise.

### GetCorrelationOk

`func (o *GroupedForecastResultsReconciliation) GetCorrelationOk() (*float32, bool)`

GetCorrelationOk returns a tuple with the Correlation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCorrelation

`func (o *GroupedForecastResultsReconciliation) SetCorrelation(v float32)`

SetCorrelation sets Correlation field to given value.

### HasCorrelation

`func (o *GroupedForecastResultsReconciliation) HasCorrelation() bool`

HasCorrelation returns a boolean if a field has been set.

### GetCorrelationSource

`func (o *GroupedForecastResultsReconciliation) GetCorrelationSource() string`

GetCorrelationSource returns the CorrelationSource field if non-nil, zero value otherwise.

### GetCorrelationSourceOk

`func (o *GroupedForecastResultsReconciliation) GetCorrelationSourceOk() (*string, bool)`

GetCorrelationSourceOk returns a tuple with the CorrelationSource field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCorrelationSource

`func (o *GroupedForecastResultsReconciliation) SetCorrelationSource(v string)`

SetCorrelationSource sets CorrelationSource field to given value.

### HasCorrelationSource

`func (o *GroupedForecastResultsReconciliation) HasCorrelationSource() bool`

HasCorrelationSource returns a boolean if a field has been set.

### GetMeasured

`func (o *GroupedForecastResultsReconciliation) GetMeasured() bool`

GetMeasured returns the Measured field if non-nil, zero value otherwise.

### GetMeasuredOk

`func (o *GroupedForecastResultsReconciliation) GetMeasuredOk() (*bool, bool)`

GetMeasuredOk returns a tuple with the Measured field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMeasured

`func (o *GroupedForecastResultsReconciliation) SetMeasured(v bool)`

SetMeasured sets Measured field to given value.

### HasMeasured

`func (o *GroupedForecastResultsReconciliation) HasMeasured() bool`

HasMeasured returns a boolean if a field has been set.

### GetVariant

`func (o *GroupedForecastResultsReconciliation) GetVariant() string`

GetVariant returns the Variant field if non-nil, zero value otherwise.

### GetVariantOk

`func (o *GroupedForecastResultsReconciliation) GetVariantOk() (*string, bool)`

GetVariantOk returns a tuple with the Variant field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVariant

`func (o *GroupedForecastResultsReconciliation) SetVariant(v string)`

SetVariant sets Variant field to given value.

### HasVariant

`func (o *GroupedForecastResultsReconciliation) HasVariant() bool`

HasVariant returns a boolean if a field has been set.

### SetVariantNil

`func (o *GroupedForecastResultsReconciliation) SetVariantNil(b bool)`

 SetVariantNil sets the value for Variant to be an explicit nil

### UnsetVariant
`func (o *GroupedForecastResultsReconciliation) UnsetVariant()`

UnsetVariant ensures that no value is present for Variant, not even an explicit nil
### GetNonnegative

`func (o *GroupedForecastResultsReconciliation) GetNonnegative() bool`

GetNonnegative returns the Nonnegative field if non-nil, zero value otherwise.

### GetNonnegativeOk

`func (o *GroupedForecastResultsReconciliation) GetNonnegativeOk() (*bool, bool)`

GetNonnegativeOk returns a tuple with the Nonnegative field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNonnegative

`func (o *GroupedForecastResultsReconciliation) SetNonnegative(v bool)`

SetNonnegative sets Nonnegative field to given value.

### HasNonnegative

`func (o *GroupedForecastResultsReconciliation) HasNonnegative() bool`

HasNonnegative returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


