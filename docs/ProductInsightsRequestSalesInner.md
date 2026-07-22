# ProductInsightsRequestSalesInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Date** | **string** |  | 
**QuantitySold** | **float32** |  | 
**SellingPrice** | **float32** |  | 
**SellingPriceConverted** | Pointer to **float32** | Price converted to base_currency, when the sale was in another currency | [optional] 
**Currency** | Pointer to **NullableString** |  | [optional] 
**CustomerId** | Pointer to **NullableString** |  | [optional] 
**CustomerSegment** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewProductInsightsRequestSalesInner

`func NewProductInsightsRequestSalesInner(date string, quantitySold float32, sellingPrice float32, ) *ProductInsightsRequestSalesInner`

NewProductInsightsRequestSalesInner instantiates a new ProductInsightsRequestSalesInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProductInsightsRequestSalesInnerWithDefaults

`func NewProductInsightsRequestSalesInnerWithDefaults() *ProductInsightsRequestSalesInner`

NewProductInsightsRequestSalesInnerWithDefaults instantiates a new ProductInsightsRequestSalesInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDate

`func (o *ProductInsightsRequestSalesInner) GetDate() string`

GetDate returns the Date field if non-nil, zero value otherwise.

### GetDateOk

`func (o *ProductInsightsRequestSalesInner) GetDateOk() (*string, bool)`

GetDateOk returns a tuple with the Date field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDate

`func (o *ProductInsightsRequestSalesInner) SetDate(v string)`

SetDate sets Date field to given value.


### GetQuantitySold

`func (o *ProductInsightsRequestSalesInner) GetQuantitySold() float32`

GetQuantitySold returns the QuantitySold field if non-nil, zero value otherwise.

### GetQuantitySoldOk

`func (o *ProductInsightsRequestSalesInner) GetQuantitySoldOk() (*float32, bool)`

GetQuantitySoldOk returns a tuple with the QuantitySold field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantitySold

`func (o *ProductInsightsRequestSalesInner) SetQuantitySold(v float32)`

SetQuantitySold sets QuantitySold field to given value.


### GetSellingPrice

`func (o *ProductInsightsRequestSalesInner) GetSellingPrice() float32`

GetSellingPrice returns the SellingPrice field if non-nil, zero value otherwise.

### GetSellingPriceOk

`func (o *ProductInsightsRequestSalesInner) GetSellingPriceOk() (*float32, bool)`

GetSellingPriceOk returns a tuple with the SellingPrice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSellingPrice

`func (o *ProductInsightsRequestSalesInner) SetSellingPrice(v float32)`

SetSellingPrice sets SellingPrice field to given value.


### GetSellingPriceConverted

`func (o *ProductInsightsRequestSalesInner) GetSellingPriceConverted() float32`

GetSellingPriceConverted returns the SellingPriceConverted field if non-nil, zero value otherwise.

### GetSellingPriceConvertedOk

`func (o *ProductInsightsRequestSalesInner) GetSellingPriceConvertedOk() (*float32, bool)`

GetSellingPriceConvertedOk returns a tuple with the SellingPriceConverted field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSellingPriceConverted

`func (o *ProductInsightsRequestSalesInner) SetSellingPriceConverted(v float32)`

SetSellingPriceConverted sets SellingPriceConverted field to given value.

### HasSellingPriceConverted

`func (o *ProductInsightsRequestSalesInner) HasSellingPriceConverted() bool`

HasSellingPriceConverted returns a boolean if a field has been set.

### GetCurrency

`func (o *ProductInsightsRequestSalesInner) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *ProductInsightsRequestSalesInner) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *ProductInsightsRequestSalesInner) SetCurrency(v string)`

SetCurrency sets Currency field to given value.

### HasCurrency

`func (o *ProductInsightsRequestSalesInner) HasCurrency() bool`

HasCurrency returns a boolean if a field has been set.

### SetCurrencyNil

`func (o *ProductInsightsRequestSalesInner) SetCurrencyNil(b bool)`

 SetCurrencyNil sets the value for Currency to be an explicit nil

### UnsetCurrency
`func (o *ProductInsightsRequestSalesInner) UnsetCurrency()`

UnsetCurrency ensures that no value is present for Currency, not even an explicit nil
### GetCustomerId

`func (o *ProductInsightsRequestSalesInner) GetCustomerId() string`

GetCustomerId returns the CustomerId field if non-nil, zero value otherwise.

### GetCustomerIdOk

`func (o *ProductInsightsRequestSalesInner) GetCustomerIdOk() (*string, bool)`

GetCustomerIdOk returns a tuple with the CustomerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerId

`func (o *ProductInsightsRequestSalesInner) SetCustomerId(v string)`

SetCustomerId sets CustomerId field to given value.

### HasCustomerId

`func (o *ProductInsightsRequestSalesInner) HasCustomerId() bool`

HasCustomerId returns a boolean if a field has been set.

### SetCustomerIdNil

`func (o *ProductInsightsRequestSalesInner) SetCustomerIdNil(b bool)`

 SetCustomerIdNil sets the value for CustomerId to be an explicit nil

### UnsetCustomerId
`func (o *ProductInsightsRequestSalesInner) UnsetCustomerId()`

UnsetCustomerId ensures that no value is present for CustomerId, not even an explicit nil
### GetCustomerSegment

`func (o *ProductInsightsRequestSalesInner) GetCustomerSegment() string`

GetCustomerSegment returns the CustomerSegment field if non-nil, zero value otherwise.

### GetCustomerSegmentOk

`func (o *ProductInsightsRequestSalesInner) GetCustomerSegmentOk() (*string, bool)`

GetCustomerSegmentOk returns a tuple with the CustomerSegment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerSegment

`func (o *ProductInsightsRequestSalesInner) SetCustomerSegment(v string)`

SetCustomerSegment sets CustomerSegment field to given value.

### HasCustomerSegment

`func (o *ProductInsightsRequestSalesInner) HasCustomerSegment() bool`

HasCustomerSegment returns a boolean if a field has been set.

### SetCustomerSegmentNil

`func (o *ProductInsightsRequestSalesInner) SetCustomerSegmentNil(b bool)`

 SetCustomerSegmentNil sets the value for CustomerSegment to be an explicit nil

### UnsetCustomerSegment
`func (o *ProductInsightsRequestSalesInner) UnsetCustomerSegment()`

UnsetCustomerSegment ensures that no value is present for CustomerSegment, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


