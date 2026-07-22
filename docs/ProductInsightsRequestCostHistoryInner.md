# ProductInsightsRequestCostHistoryInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Date** | **string** |  | 
**CostPrice** | **float32** |  | 
**Currency** | Pointer to **NullableString** |  | [optional] 
**ChangeReason** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewProductInsightsRequestCostHistoryInner

`func NewProductInsightsRequestCostHistoryInner(date string, costPrice float32, ) *ProductInsightsRequestCostHistoryInner`

NewProductInsightsRequestCostHistoryInner instantiates a new ProductInsightsRequestCostHistoryInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProductInsightsRequestCostHistoryInnerWithDefaults

`func NewProductInsightsRequestCostHistoryInnerWithDefaults() *ProductInsightsRequestCostHistoryInner`

NewProductInsightsRequestCostHistoryInnerWithDefaults instantiates a new ProductInsightsRequestCostHistoryInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDate

`func (o *ProductInsightsRequestCostHistoryInner) GetDate() string`

GetDate returns the Date field if non-nil, zero value otherwise.

### GetDateOk

`func (o *ProductInsightsRequestCostHistoryInner) GetDateOk() (*string, bool)`

GetDateOk returns a tuple with the Date field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDate

`func (o *ProductInsightsRequestCostHistoryInner) SetDate(v string)`

SetDate sets Date field to given value.


### GetCostPrice

`func (o *ProductInsightsRequestCostHistoryInner) GetCostPrice() float32`

GetCostPrice returns the CostPrice field if non-nil, zero value otherwise.

### GetCostPriceOk

`func (o *ProductInsightsRequestCostHistoryInner) GetCostPriceOk() (*float32, bool)`

GetCostPriceOk returns a tuple with the CostPrice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCostPrice

`func (o *ProductInsightsRequestCostHistoryInner) SetCostPrice(v float32)`

SetCostPrice sets CostPrice field to given value.


### GetCurrency

`func (o *ProductInsightsRequestCostHistoryInner) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *ProductInsightsRequestCostHistoryInner) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *ProductInsightsRequestCostHistoryInner) SetCurrency(v string)`

SetCurrency sets Currency field to given value.

### HasCurrency

`func (o *ProductInsightsRequestCostHistoryInner) HasCurrency() bool`

HasCurrency returns a boolean if a field has been set.

### SetCurrencyNil

`func (o *ProductInsightsRequestCostHistoryInner) SetCurrencyNil(b bool)`

 SetCurrencyNil sets the value for Currency to be an explicit nil

### UnsetCurrency
`func (o *ProductInsightsRequestCostHistoryInner) UnsetCurrency()`

UnsetCurrency ensures that no value is present for Currency, not even an explicit nil
### GetChangeReason

`func (o *ProductInsightsRequestCostHistoryInner) GetChangeReason() string`

GetChangeReason returns the ChangeReason field if non-nil, zero value otherwise.

### GetChangeReasonOk

`func (o *ProductInsightsRequestCostHistoryInner) GetChangeReasonOk() (*string, bool)`

GetChangeReasonOk returns a tuple with the ChangeReason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChangeReason

`func (o *ProductInsightsRequestCostHistoryInner) SetChangeReason(v string)`

SetChangeReason sets ChangeReason field to given value.

### HasChangeReason

`func (o *ProductInsightsRequestCostHistoryInner) HasChangeReason() bool`

HasChangeReason returns a boolean if a field has been set.

### SetChangeReasonNil

`func (o *ProductInsightsRequestCostHistoryInner) SetChangeReasonNil(b bool)`

 SetChangeReasonNil sets the value for ChangeReason to be an explicit nil

### UnsetChangeReason
`func (o *ProductInsightsRequestCostHistoryInner) UnsetChangeReason()`

UnsetChangeReason ensures that no value is present for ChangeReason, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


