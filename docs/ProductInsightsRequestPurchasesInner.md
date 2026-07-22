# ProductInsightsRequestPurchasesInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Date** | **string** |  | 
**QuantityPurchased** | **float32** |  | 
**CostPrice** | **float32** |  | 
**CostPriceConverted** | Pointer to **float32** |  | [optional] 
**Currency** | Pointer to **NullableString** |  | [optional] 
**SupplierId** | Pointer to **NullableString** |  | [optional] 
**PurchaseOrderDate** | Pointer to **NullableString** | Used for lead-time reliability analysis | [optional] 
**ExpectedDeliveryDate** | Pointer to **NullableString** |  | [optional] 
**ActualDeliveryDate** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewProductInsightsRequestPurchasesInner

`func NewProductInsightsRequestPurchasesInner(date string, quantityPurchased float32, costPrice float32, ) *ProductInsightsRequestPurchasesInner`

NewProductInsightsRequestPurchasesInner instantiates a new ProductInsightsRequestPurchasesInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProductInsightsRequestPurchasesInnerWithDefaults

`func NewProductInsightsRequestPurchasesInnerWithDefaults() *ProductInsightsRequestPurchasesInner`

NewProductInsightsRequestPurchasesInnerWithDefaults instantiates a new ProductInsightsRequestPurchasesInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDate

`func (o *ProductInsightsRequestPurchasesInner) GetDate() string`

GetDate returns the Date field if non-nil, zero value otherwise.

### GetDateOk

`func (o *ProductInsightsRequestPurchasesInner) GetDateOk() (*string, bool)`

GetDateOk returns a tuple with the Date field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDate

`func (o *ProductInsightsRequestPurchasesInner) SetDate(v string)`

SetDate sets Date field to given value.


### GetQuantityPurchased

`func (o *ProductInsightsRequestPurchasesInner) GetQuantityPurchased() float32`

GetQuantityPurchased returns the QuantityPurchased field if non-nil, zero value otherwise.

### GetQuantityPurchasedOk

`func (o *ProductInsightsRequestPurchasesInner) GetQuantityPurchasedOk() (*float32, bool)`

GetQuantityPurchasedOk returns a tuple with the QuantityPurchased field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantityPurchased

`func (o *ProductInsightsRequestPurchasesInner) SetQuantityPurchased(v float32)`

SetQuantityPurchased sets QuantityPurchased field to given value.


### GetCostPrice

`func (o *ProductInsightsRequestPurchasesInner) GetCostPrice() float32`

GetCostPrice returns the CostPrice field if non-nil, zero value otherwise.

### GetCostPriceOk

`func (o *ProductInsightsRequestPurchasesInner) GetCostPriceOk() (*float32, bool)`

GetCostPriceOk returns a tuple with the CostPrice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCostPrice

`func (o *ProductInsightsRequestPurchasesInner) SetCostPrice(v float32)`

SetCostPrice sets CostPrice field to given value.


### GetCostPriceConverted

`func (o *ProductInsightsRequestPurchasesInner) GetCostPriceConverted() float32`

GetCostPriceConverted returns the CostPriceConverted field if non-nil, zero value otherwise.

### GetCostPriceConvertedOk

`func (o *ProductInsightsRequestPurchasesInner) GetCostPriceConvertedOk() (*float32, bool)`

GetCostPriceConvertedOk returns a tuple with the CostPriceConverted field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCostPriceConverted

`func (o *ProductInsightsRequestPurchasesInner) SetCostPriceConverted(v float32)`

SetCostPriceConverted sets CostPriceConverted field to given value.

### HasCostPriceConverted

`func (o *ProductInsightsRequestPurchasesInner) HasCostPriceConverted() bool`

HasCostPriceConverted returns a boolean if a field has been set.

### GetCurrency

`func (o *ProductInsightsRequestPurchasesInner) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *ProductInsightsRequestPurchasesInner) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *ProductInsightsRequestPurchasesInner) SetCurrency(v string)`

SetCurrency sets Currency field to given value.

### HasCurrency

`func (o *ProductInsightsRequestPurchasesInner) HasCurrency() bool`

HasCurrency returns a boolean if a field has been set.

### SetCurrencyNil

`func (o *ProductInsightsRequestPurchasesInner) SetCurrencyNil(b bool)`

 SetCurrencyNil sets the value for Currency to be an explicit nil

### UnsetCurrency
`func (o *ProductInsightsRequestPurchasesInner) UnsetCurrency()`

UnsetCurrency ensures that no value is present for Currency, not even an explicit nil
### GetSupplierId

`func (o *ProductInsightsRequestPurchasesInner) GetSupplierId() string`

GetSupplierId returns the SupplierId field if non-nil, zero value otherwise.

### GetSupplierIdOk

`func (o *ProductInsightsRequestPurchasesInner) GetSupplierIdOk() (*string, bool)`

GetSupplierIdOk returns a tuple with the SupplierId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupplierId

`func (o *ProductInsightsRequestPurchasesInner) SetSupplierId(v string)`

SetSupplierId sets SupplierId field to given value.

### HasSupplierId

`func (o *ProductInsightsRequestPurchasesInner) HasSupplierId() bool`

HasSupplierId returns a boolean if a field has been set.

### SetSupplierIdNil

`func (o *ProductInsightsRequestPurchasesInner) SetSupplierIdNil(b bool)`

 SetSupplierIdNil sets the value for SupplierId to be an explicit nil

### UnsetSupplierId
`func (o *ProductInsightsRequestPurchasesInner) UnsetSupplierId()`

UnsetSupplierId ensures that no value is present for SupplierId, not even an explicit nil
### GetPurchaseOrderDate

`func (o *ProductInsightsRequestPurchasesInner) GetPurchaseOrderDate() string`

GetPurchaseOrderDate returns the PurchaseOrderDate field if non-nil, zero value otherwise.

### GetPurchaseOrderDateOk

`func (o *ProductInsightsRequestPurchasesInner) GetPurchaseOrderDateOk() (*string, bool)`

GetPurchaseOrderDateOk returns a tuple with the PurchaseOrderDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPurchaseOrderDate

`func (o *ProductInsightsRequestPurchasesInner) SetPurchaseOrderDate(v string)`

SetPurchaseOrderDate sets PurchaseOrderDate field to given value.

### HasPurchaseOrderDate

`func (o *ProductInsightsRequestPurchasesInner) HasPurchaseOrderDate() bool`

HasPurchaseOrderDate returns a boolean if a field has been set.

### SetPurchaseOrderDateNil

`func (o *ProductInsightsRequestPurchasesInner) SetPurchaseOrderDateNil(b bool)`

 SetPurchaseOrderDateNil sets the value for PurchaseOrderDate to be an explicit nil

### UnsetPurchaseOrderDate
`func (o *ProductInsightsRequestPurchasesInner) UnsetPurchaseOrderDate()`

UnsetPurchaseOrderDate ensures that no value is present for PurchaseOrderDate, not even an explicit nil
### GetExpectedDeliveryDate

`func (o *ProductInsightsRequestPurchasesInner) GetExpectedDeliveryDate() string`

GetExpectedDeliveryDate returns the ExpectedDeliveryDate field if non-nil, zero value otherwise.

### GetExpectedDeliveryDateOk

`func (o *ProductInsightsRequestPurchasesInner) GetExpectedDeliveryDateOk() (*string, bool)`

GetExpectedDeliveryDateOk returns a tuple with the ExpectedDeliveryDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpectedDeliveryDate

`func (o *ProductInsightsRequestPurchasesInner) SetExpectedDeliveryDate(v string)`

SetExpectedDeliveryDate sets ExpectedDeliveryDate field to given value.

### HasExpectedDeliveryDate

`func (o *ProductInsightsRequestPurchasesInner) HasExpectedDeliveryDate() bool`

HasExpectedDeliveryDate returns a boolean if a field has been set.

### SetExpectedDeliveryDateNil

`func (o *ProductInsightsRequestPurchasesInner) SetExpectedDeliveryDateNil(b bool)`

 SetExpectedDeliveryDateNil sets the value for ExpectedDeliveryDate to be an explicit nil

### UnsetExpectedDeliveryDate
`func (o *ProductInsightsRequestPurchasesInner) UnsetExpectedDeliveryDate()`

UnsetExpectedDeliveryDate ensures that no value is present for ExpectedDeliveryDate, not even an explicit nil
### GetActualDeliveryDate

`func (o *ProductInsightsRequestPurchasesInner) GetActualDeliveryDate() string`

GetActualDeliveryDate returns the ActualDeliveryDate field if non-nil, zero value otherwise.

### GetActualDeliveryDateOk

`func (o *ProductInsightsRequestPurchasesInner) GetActualDeliveryDateOk() (*string, bool)`

GetActualDeliveryDateOk returns a tuple with the ActualDeliveryDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActualDeliveryDate

`func (o *ProductInsightsRequestPurchasesInner) SetActualDeliveryDate(v string)`

SetActualDeliveryDate sets ActualDeliveryDate field to given value.

### HasActualDeliveryDate

`func (o *ProductInsightsRequestPurchasesInner) HasActualDeliveryDate() bool`

HasActualDeliveryDate returns a boolean if a field has been set.

### SetActualDeliveryDateNil

`func (o *ProductInsightsRequestPurchasesInner) SetActualDeliveryDateNil(b bool)`

 SetActualDeliveryDateNil sets the value for ActualDeliveryDate to be an explicit nil

### UnsetActualDeliveryDate
`func (o *ProductInsightsRequestPurchasesInner) UnsetActualDeliveryDate()`

UnsetActualDeliveryDate ensures that no value is present for ActualDeliveryDate, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


