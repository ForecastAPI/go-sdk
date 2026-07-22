# ProductInsightsResponseResult

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Identifier** | Pointer to **string** |  | [optional] 
**TenantContext** | Pointer to **NullableString** |  | [optional] 
**ProductInfo** | Pointer to [**ProductInsightsResponseResultProductInfo**](ProductInsightsResponseResultProductInfo.md) |  | [optional] 
**BaseCurrency** | Pointer to **NullableString** |  | [optional] 
**Insights** | Pointer to [**[]ProductInsight**](ProductInsight.md) |  | [optional] 
**Summary** | Pointer to [**ProductInsightsResponseResultSummary**](ProductInsightsResponseResultSummary.md) |  | [optional] 
**Comparison** | Pointer to [**NullableProductInsightsResponseResultComparison**](ProductInsightsResponseResultComparison.md) |  | [optional] 

## Methods

### NewProductInsightsResponseResult

`func NewProductInsightsResponseResult() *ProductInsightsResponseResult`

NewProductInsightsResponseResult instantiates a new ProductInsightsResponseResult object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProductInsightsResponseResultWithDefaults

`func NewProductInsightsResponseResultWithDefaults() *ProductInsightsResponseResult`

NewProductInsightsResponseResultWithDefaults instantiates a new ProductInsightsResponseResult object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetIdentifier

`func (o *ProductInsightsResponseResult) GetIdentifier() string`

GetIdentifier returns the Identifier field if non-nil, zero value otherwise.

### GetIdentifierOk

`func (o *ProductInsightsResponseResult) GetIdentifierOk() (*string, bool)`

GetIdentifierOk returns a tuple with the Identifier field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdentifier

`func (o *ProductInsightsResponseResult) SetIdentifier(v string)`

SetIdentifier sets Identifier field to given value.

### HasIdentifier

`func (o *ProductInsightsResponseResult) HasIdentifier() bool`

HasIdentifier returns a boolean if a field has been set.

### GetTenantContext

`func (o *ProductInsightsResponseResult) GetTenantContext() string`

GetTenantContext returns the TenantContext field if non-nil, zero value otherwise.

### GetTenantContextOk

`func (o *ProductInsightsResponseResult) GetTenantContextOk() (*string, bool)`

GetTenantContextOk returns a tuple with the TenantContext field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTenantContext

`func (o *ProductInsightsResponseResult) SetTenantContext(v string)`

SetTenantContext sets TenantContext field to given value.

### HasTenantContext

`func (o *ProductInsightsResponseResult) HasTenantContext() bool`

HasTenantContext returns a boolean if a field has been set.

### SetTenantContextNil

`func (o *ProductInsightsResponseResult) SetTenantContextNil(b bool)`

 SetTenantContextNil sets the value for TenantContext to be an explicit nil

### UnsetTenantContext
`func (o *ProductInsightsResponseResult) UnsetTenantContext()`

UnsetTenantContext ensures that no value is present for TenantContext, not even an explicit nil
### GetProductInfo

`func (o *ProductInsightsResponseResult) GetProductInfo() ProductInsightsResponseResultProductInfo`

GetProductInfo returns the ProductInfo field if non-nil, zero value otherwise.

### GetProductInfoOk

`func (o *ProductInsightsResponseResult) GetProductInfoOk() (*ProductInsightsResponseResultProductInfo, bool)`

GetProductInfoOk returns a tuple with the ProductInfo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProductInfo

`func (o *ProductInsightsResponseResult) SetProductInfo(v ProductInsightsResponseResultProductInfo)`

SetProductInfo sets ProductInfo field to given value.

### HasProductInfo

`func (o *ProductInsightsResponseResult) HasProductInfo() bool`

HasProductInfo returns a boolean if a field has been set.

### GetBaseCurrency

`func (o *ProductInsightsResponseResult) GetBaseCurrency() string`

GetBaseCurrency returns the BaseCurrency field if non-nil, zero value otherwise.

### GetBaseCurrencyOk

`func (o *ProductInsightsResponseResult) GetBaseCurrencyOk() (*string, bool)`

GetBaseCurrencyOk returns a tuple with the BaseCurrency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBaseCurrency

`func (o *ProductInsightsResponseResult) SetBaseCurrency(v string)`

SetBaseCurrency sets BaseCurrency field to given value.

### HasBaseCurrency

`func (o *ProductInsightsResponseResult) HasBaseCurrency() bool`

HasBaseCurrency returns a boolean if a field has been set.

### SetBaseCurrencyNil

`func (o *ProductInsightsResponseResult) SetBaseCurrencyNil(b bool)`

 SetBaseCurrencyNil sets the value for BaseCurrency to be an explicit nil

### UnsetBaseCurrency
`func (o *ProductInsightsResponseResult) UnsetBaseCurrency()`

UnsetBaseCurrency ensures that no value is present for BaseCurrency, not even an explicit nil
### GetInsights

`func (o *ProductInsightsResponseResult) GetInsights() []ProductInsight`

GetInsights returns the Insights field if non-nil, zero value otherwise.

### GetInsightsOk

`func (o *ProductInsightsResponseResult) GetInsightsOk() (*[]ProductInsight, bool)`

GetInsightsOk returns a tuple with the Insights field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInsights

`func (o *ProductInsightsResponseResult) SetInsights(v []ProductInsight)`

SetInsights sets Insights field to given value.

### HasInsights

`func (o *ProductInsightsResponseResult) HasInsights() bool`

HasInsights returns a boolean if a field has been set.

### GetSummary

`func (o *ProductInsightsResponseResult) GetSummary() ProductInsightsResponseResultSummary`

GetSummary returns the Summary field if non-nil, zero value otherwise.

### GetSummaryOk

`func (o *ProductInsightsResponseResult) GetSummaryOk() (*ProductInsightsResponseResultSummary, bool)`

GetSummaryOk returns a tuple with the Summary field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSummary

`func (o *ProductInsightsResponseResult) SetSummary(v ProductInsightsResponseResultSummary)`

SetSummary sets Summary field to given value.

### HasSummary

`func (o *ProductInsightsResponseResult) HasSummary() bool`

HasSummary returns a boolean if a field has been set.

### GetComparison

`func (o *ProductInsightsResponseResult) GetComparison() ProductInsightsResponseResultComparison`

GetComparison returns the Comparison field if non-nil, zero value otherwise.

### GetComparisonOk

`func (o *ProductInsightsResponseResult) GetComparisonOk() (*ProductInsightsResponseResultComparison, bool)`

GetComparisonOk returns a tuple with the Comparison field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComparison

`func (o *ProductInsightsResponseResult) SetComparison(v ProductInsightsResponseResultComparison)`

SetComparison sets Comparison field to given value.

### HasComparison

`func (o *ProductInsightsResponseResult) HasComparison() bool`

HasComparison returns a boolean if a field has been set.

### SetComparisonNil

`func (o *ProductInsightsResponseResult) SetComparisonNil(b bool)`

 SetComparisonNil sets the value for Comparison to be an explicit nil

### UnsetComparison
`func (o *ProductInsightsResponseResult) UnsetComparison()`

UnsetComparison ensures that no value is present for Comparison, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


