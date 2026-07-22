# ProductInsightsRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Identifier** | **string** | Product identifier | 
**TenantContext** | Pointer to **NullableString** |  | [optional] 
**ProductName** | Pointer to **NullableString** |  | [optional] 
**ProductGroupId** | Pointer to **NullableString** |  | [optional] 
**BaseCurrency** | Pointer to **NullableString** | ISO 4217 currency the analysis reports in | [optional] 
**BaselinePeriodDays** | Pointer to [**ProductInsightsRequestBaselinePeriodDays**](ProductInsightsRequestBaselinePeriodDays.md) |  | [optional] [default to auto]
**Locale** | Pointer to **string** | Locale for insight texts | [optional] [default to "en"]
**Sales** | Pointer to [**[]ProductInsightsRequestSalesInner**](ProductInsightsRequestSalesInner.md) |  | [optional] 
**Purchases** | Pointer to [**[]ProductInsightsRequestPurchasesInner**](ProductInsightsRequestPurchasesInner.md) |  | [optional] 
**CostHistory** | Pointer to [**[]ProductInsightsRequestCostHistoryInner**](ProductInsightsRequestCostHistoryInner.md) |  | [optional] 
**InsightSettings** | Pointer to [**NullableProductInsightsRequestInsightSettings**](ProductInsightsRequestInsightSettings.md) |  | [optional] 

## Methods

### NewProductInsightsRequest

`func NewProductInsightsRequest(identifier string, ) *ProductInsightsRequest`

NewProductInsightsRequest instantiates a new ProductInsightsRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProductInsightsRequestWithDefaults

`func NewProductInsightsRequestWithDefaults() *ProductInsightsRequest`

NewProductInsightsRequestWithDefaults instantiates a new ProductInsightsRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetIdentifier

`func (o *ProductInsightsRequest) GetIdentifier() string`

GetIdentifier returns the Identifier field if non-nil, zero value otherwise.

### GetIdentifierOk

`func (o *ProductInsightsRequest) GetIdentifierOk() (*string, bool)`

GetIdentifierOk returns a tuple with the Identifier field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdentifier

`func (o *ProductInsightsRequest) SetIdentifier(v string)`

SetIdentifier sets Identifier field to given value.


### GetTenantContext

`func (o *ProductInsightsRequest) GetTenantContext() string`

GetTenantContext returns the TenantContext field if non-nil, zero value otherwise.

### GetTenantContextOk

`func (o *ProductInsightsRequest) GetTenantContextOk() (*string, bool)`

GetTenantContextOk returns a tuple with the TenantContext field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTenantContext

`func (o *ProductInsightsRequest) SetTenantContext(v string)`

SetTenantContext sets TenantContext field to given value.

### HasTenantContext

`func (o *ProductInsightsRequest) HasTenantContext() bool`

HasTenantContext returns a boolean if a field has been set.

### SetTenantContextNil

`func (o *ProductInsightsRequest) SetTenantContextNil(b bool)`

 SetTenantContextNil sets the value for TenantContext to be an explicit nil

### UnsetTenantContext
`func (o *ProductInsightsRequest) UnsetTenantContext()`

UnsetTenantContext ensures that no value is present for TenantContext, not even an explicit nil
### GetProductName

`func (o *ProductInsightsRequest) GetProductName() string`

GetProductName returns the ProductName field if non-nil, zero value otherwise.

### GetProductNameOk

`func (o *ProductInsightsRequest) GetProductNameOk() (*string, bool)`

GetProductNameOk returns a tuple with the ProductName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProductName

`func (o *ProductInsightsRequest) SetProductName(v string)`

SetProductName sets ProductName field to given value.

### HasProductName

`func (o *ProductInsightsRequest) HasProductName() bool`

HasProductName returns a boolean if a field has been set.

### SetProductNameNil

`func (o *ProductInsightsRequest) SetProductNameNil(b bool)`

 SetProductNameNil sets the value for ProductName to be an explicit nil

### UnsetProductName
`func (o *ProductInsightsRequest) UnsetProductName()`

UnsetProductName ensures that no value is present for ProductName, not even an explicit nil
### GetProductGroupId

`func (o *ProductInsightsRequest) GetProductGroupId() string`

GetProductGroupId returns the ProductGroupId field if non-nil, zero value otherwise.

### GetProductGroupIdOk

`func (o *ProductInsightsRequest) GetProductGroupIdOk() (*string, bool)`

GetProductGroupIdOk returns a tuple with the ProductGroupId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProductGroupId

`func (o *ProductInsightsRequest) SetProductGroupId(v string)`

SetProductGroupId sets ProductGroupId field to given value.

### HasProductGroupId

`func (o *ProductInsightsRequest) HasProductGroupId() bool`

HasProductGroupId returns a boolean if a field has been set.

### SetProductGroupIdNil

`func (o *ProductInsightsRequest) SetProductGroupIdNil(b bool)`

 SetProductGroupIdNil sets the value for ProductGroupId to be an explicit nil

### UnsetProductGroupId
`func (o *ProductInsightsRequest) UnsetProductGroupId()`

UnsetProductGroupId ensures that no value is present for ProductGroupId, not even an explicit nil
### GetBaseCurrency

`func (o *ProductInsightsRequest) GetBaseCurrency() string`

GetBaseCurrency returns the BaseCurrency field if non-nil, zero value otherwise.

### GetBaseCurrencyOk

`func (o *ProductInsightsRequest) GetBaseCurrencyOk() (*string, bool)`

GetBaseCurrencyOk returns a tuple with the BaseCurrency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBaseCurrency

`func (o *ProductInsightsRequest) SetBaseCurrency(v string)`

SetBaseCurrency sets BaseCurrency field to given value.

### HasBaseCurrency

`func (o *ProductInsightsRequest) HasBaseCurrency() bool`

HasBaseCurrency returns a boolean if a field has been set.

### SetBaseCurrencyNil

`func (o *ProductInsightsRequest) SetBaseCurrencyNil(b bool)`

 SetBaseCurrencyNil sets the value for BaseCurrency to be an explicit nil

### UnsetBaseCurrency
`func (o *ProductInsightsRequest) UnsetBaseCurrency()`

UnsetBaseCurrency ensures that no value is present for BaseCurrency, not even an explicit nil
### GetBaselinePeriodDays

`func (o *ProductInsightsRequest) GetBaselinePeriodDays() ProductInsightsRequestBaselinePeriodDays`

GetBaselinePeriodDays returns the BaselinePeriodDays field if non-nil, zero value otherwise.

### GetBaselinePeriodDaysOk

`func (o *ProductInsightsRequest) GetBaselinePeriodDaysOk() (*ProductInsightsRequestBaselinePeriodDays, bool)`

GetBaselinePeriodDaysOk returns a tuple with the BaselinePeriodDays field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBaselinePeriodDays

`func (o *ProductInsightsRequest) SetBaselinePeriodDays(v ProductInsightsRequestBaselinePeriodDays)`

SetBaselinePeriodDays sets BaselinePeriodDays field to given value.

### HasBaselinePeriodDays

`func (o *ProductInsightsRequest) HasBaselinePeriodDays() bool`

HasBaselinePeriodDays returns a boolean if a field has been set.

### GetLocale

`func (o *ProductInsightsRequest) GetLocale() string`

GetLocale returns the Locale field if non-nil, zero value otherwise.

### GetLocaleOk

`func (o *ProductInsightsRequest) GetLocaleOk() (*string, bool)`

GetLocaleOk returns a tuple with the Locale field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocale

`func (o *ProductInsightsRequest) SetLocale(v string)`

SetLocale sets Locale field to given value.

### HasLocale

`func (o *ProductInsightsRequest) HasLocale() bool`

HasLocale returns a boolean if a field has been set.

### GetSales

`func (o *ProductInsightsRequest) GetSales() []ProductInsightsRequestSalesInner`

GetSales returns the Sales field if non-nil, zero value otherwise.

### GetSalesOk

`func (o *ProductInsightsRequest) GetSalesOk() (*[]ProductInsightsRequestSalesInner, bool)`

GetSalesOk returns a tuple with the Sales field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSales

`func (o *ProductInsightsRequest) SetSales(v []ProductInsightsRequestSalesInner)`

SetSales sets Sales field to given value.

### HasSales

`func (o *ProductInsightsRequest) HasSales() bool`

HasSales returns a boolean if a field has been set.

### SetSalesNil

`func (o *ProductInsightsRequest) SetSalesNil(b bool)`

 SetSalesNil sets the value for Sales to be an explicit nil

### UnsetSales
`func (o *ProductInsightsRequest) UnsetSales()`

UnsetSales ensures that no value is present for Sales, not even an explicit nil
### GetPurchases

`func (o *ProductInsightsRequest) GetPurchases() []ProductInsightsRequestPurchasesInner`

GetPurchases returns the Purchases field if non-nil, zero value otherwise.

### GetPurchasesOk

`func (o *ProductInsightsRequest) GetPurchasesOk() (*[]ProductInsightsRequestPurchasesInner, bool)`

GetPurchasesOk returns a tuple with the Purchases field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPurchases

`func (o *ProductInsightsRequest) SetPurchases(v []ProductInsightsRequestPurchasesInner)`

SetPurchases sets Purchases field to given value.

### HasPurchases

`func (o *ProductInsightsRequest) HasPurchases() bool`

HasPurchases returns a boolean if a field has been set.

### SetPurchasesNil

`func (o *ProductInsightsRequest) SetPurchasesNil(b bool)`

 SetPurchasesNil sets the value for Purchases to be an explicit nil

### UnsetPurchases
`func (o *ProductInsightsRequest) UnsetPurchases()`

UnsetPurchases ensures that no value is present for Purchases, not even an explicit nil
### GetCostHistory

`func (o *ProductInsightsRequest) GetCostHistory() []ProductInsightsRequestCostHistoryInner`

GetCostHistory returns the CostHistory field if non-nil, zero value otherwise.

### GetCostHistoryOk

`func (o *ProductInsightsRequest) GetCostHistoryOk() (*[]ProductInsightsRequestCostHistoryInner, bool)`

GetCostHistoryOk returns a tuple with the CostHistory field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCostHistory

`func (o *ProductInsightsRequest) SetCostHistory(v []ProductInsightsRequestCostHistoryInner)`

SetCostHistory sets CostHistory field to given value.

### HasCostHistory

`func (o *ProductInsightsRequest) HasCostHistory() bool`

HasCostHistory returns a boolean if a field has been set.

### SetCostHistoryNil

`func (o *ProductInsightsRequest) SetCostHistoryNil(b bool)`

 SetCostHistoryNil sets the value for CostHistory to be an explicit nil

### UnsetCostHistory
`func (o *ProductInsightsRequest) UnsetCostHistory()`

UnsetCostHistory ensures that no value is present for CostHistory, not even an explicit nil
### GetInsightSettings

`func (o *ProductInsightsRequest) GetInsightSettings() ProductInsightsRequestInsightSettings`

GetInsightSettings returns the InsightSettings field if non-nil, zero value otherwise.

### GetInsightSettingsOk

`func (o *ProductInsightsRequest) GetInsightSettingsOk() (*ProductInsightsRequestInsightSettings, bool)`

GetInsightSettingsOk returns a tuple with the InsightSettings field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInsightSettings

`func (o *ProductInsightsRequest) SetInsightSettings(v ProductInsightsRequestInsightSettings)`

SetInsightSettings sets InsightSettings field to given value.

### HasInsightSettings

`func (o *ProductInsightsRequest) HasInsightSettings() bool`

HasInsightSettings returns a boolean if a field has been set.

### SetInsightSettingsNil

`func (o *ProductInsightsRequest) SetInsightSettingsNil(b bool)`

 SetInsightSettingsNil sets the value for InsightSettings to be an explicit nil

### UnsetInsightSettings
`func (o *ProductInsightsRequest) UnsetInsightSettings()`

UnsetInsightSettings ensures that no value is present for InsightSettings, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


