# GroupedForecastRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Identifier** | **string** | Names the measure being forecast (e.g. \&quot;mrr\&quot;). The hierarchy&#39;s total is stored under this identifier exactly like a plain /v2/forecast for it — the total of the hierarchy IS the measure.  | 
**TenantContext** | Pointer to **NullableString** | Optional tenant scope, independent of segment — tenancy keeps meaning \&quot;whose data is this\&quot;, segment means \&quot;which slice\&quot;.  | [optional] 
**Hierarchy** | **[]string** | The dimensions of the hierarchy, outermost first. Each series&#39; segment must name exactly these dimensions. | 
**Reconciliation** | Pointer to **string** | - bottom_up (default): only the leaves are forecast; every aggregate is the   exact sum of its children. Fast and cheap; best when leaf histories are   substantial enough to forecast well on their own. - min_trace: every node — aggregates included — is forecast, then MinTrace   optimally redistributes the disagreement between levels into a coherent set.   Costs one forecast per node, but lets the usually-smoother aggregate series   inform the result, which tends to help when leaves are short or noisy.  top_down is not supported and is rejected by name.  | [optional] [default to "bottom_up"]
**Correlation** | Pointer to **float32** | bottom_up only — the assumed correlation between sibling errors when building aggregate confidence bands. 0 &#x3D; independent siblings, 1 &#x3D; perfectly correlated (equivalent to summing the bounds). Echoed back in the response and never labelled as measured.  | [optional] [default to 0.5]
**Frequency** | **string** | Data frequency, shared by every series in the hierarchy | 
**Periods** | **int32** | Number of periods to forecast, shared by every node | 
**DataType** | Pointer to **string** | Type of data (e.g., sales, demand, revenue). Sales-family types get non-negative reconciliation treatment. | [optional] [default to "sales"]
**Model** | Pointer to **string** | Forecasting engine used for every node. &#x60;auto&#x60; is not accepted here: it routes per series, and a hierarchy is reconciled under one model.  | [optional] [default to "standard"]
**Confidence** | Pointer to **float32** | Confidence level for prediction intervals, shared by every node | [optional] [default to 0.8]
**ConfidenceLevel** | Pointer to **float32** | Alias for &#x60;confidence&#x60;; if both are sent, &#x60;confidence&#x60; wins | [optional] 
**Series** | [**[]GroupedForecastSeries**](GroupedForecastSeries.md) | The leaves of the hierarchy — one entry per combination of dimension values, each combination exactly once. Up to 200 series on a paid plan, 10 on the free tier. Aggregate levels are derived by the API and must not be sent.  | 

## Methods

### NewGroupedForecastRequest

`func NewGroupedForecastRequest(identifier string, hierarchy []string, frequency string, periods int32, series []GroupedForecastSeries, ) *GroupedForecastRequest`

NewGroupedForecastRequest instantiates a new GroupedForecastRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGroupedForecastRequestWithDefaults

`func NewGroupedForecastRequestWithDefaults() *GroupedForecastRequest`

NewGroupedForecastRequestWithDefaults instantiates a new GroupedForecastRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetIdentifier

`func (o *GroupedForecastRequest) GetIdentifier() string`

GetIdentifier returns the Identifier field if non-nil, zero value otherwise.

### GetIdentifierOk

`func (o *GroupedForecastRequest) GetIdentifierOk() (*string, bool)`

GetIdentifierOk returns a tuple with the Identifier field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdentifier

`func (o *GroupedForecastRequest) SetIdentifier(v string)`

SetIdentifier sets Identifier field to given value.


### GetTenantContext

`func (o *GroupedForecastRequest) GetTenantContext() string`

GetTenantContext returns the TenantContext field if non-nil, zero value otherwise.

### GetTenantContextOk

`func (o *GroupedForecastRequest) GetTenantContextOk() (*string, bool)`

GetTenantContextOk returns a tuple with the TenantContext field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTenantContext

`func (o *GroupedForecastRequest) SetTenantContext(v string)`

SetTenantContext sets TenantContext field to given value.

### HasTenantContext

`func (o *GroupedForecastRequest) HasTenantContext() bool`

HasTenantContext returns a boolean if a field has been set.

### SetTenantContextNil

`func (o *GroupedForecastRequest) SetTenantContextNil(b bool)`

 SetTenantContextNil sets the value for TenantContext to be an explicit nil

### UnsetTenantContext
`func (o *GroupedForecastRequest) UnsetTenantContext()`

UnsetTenantContext ensures that no value is present for TenantContext, not even an explicit nil
### GetHierarchy

`func (o *GroupedForecastRequest) GetHierarchy() []string`

GetHierarchy returns the Hierarchy field if non-nil, zero value otherwise.

### GetHierarchyOk

`func (o *GroupedForecastRequest) GetHierarchyOk() (*[]string, bool)`

GetHierarchyOk returns a tuple with the Hierarchy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHierarchy

`func (o *GroupedForecastRequest) SetHierarchy(v []string)`

SetHierarchy sets Hierarchy field to given value.


### GetReconciliation

`func (o *GroupedForecastRequest) GetReconciliation() string`

GetReconciliation returns the Reconciliation field if non-nil, zero value otherwise.

### GetReconciliationOk

`func (o *GroupedForecastRequest) GetReconciliationOk() (*string, bool)`

GetReconciliationOk returns a tuple with the Reconciliation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReconciliation

`func (o *GroupedForecastRequest) SetReconciliation(v string)`

SetReconciliation sets Reconciliation field to given value.

### HasReconciliation

`func (o *GroupedForecastRequest) HasReconciliation() bool`

HasReconciliation returns a boolean if a field has been set.

### GetCorrelation

`func (o *GroupedForecastRequest) GetCorrelation() float32`

GetCorrelation returns the Correlation field if non-nil, zero value otherwise.

### GetCorrelationOk

`func (o *GroupedForecastRequest) GetCorrelationOk() (*float32, bool)`

GetCorrelationOk returns a tuple with the Correlation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCorrelation

`func (o *GroupedForecastRequest) SetCorrelation(v float32)`

SetCorrelation sets Correlation field to given value.

### HasCorrelation

`func (o *GroupedForecastRequest) HasCorrelation() bool`

HasCorrelation returns a boolean if a field has been set.

### GetFrequency

`func (o *GroupedForecastRequest) GetFrequency() string`

GetFrequency returns the Frequency field if non-nil, zero value otherwise.

### GetFrequencyOk

`func (o *GroupedForecastRequest) GetFrequencyOk() (*string, bool)`

GetFrequencyOk returns a tuple with the Frequency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFrequency

`func (o *GroupedForecastRequest) SetFrequency(v string)`

SetFrequency sets Frequency field to given value.


### GetPeriods

`func (o *GroupedForecastRequest) GetPeriods() int32`

GetPeriods returns the Periods field if non-nil, zero value otherwise.

### GetPeriodsOk

`func (o *GroupedForecastRequest) GetPeriodsOk() (*int32, bool)`

GetPeriodsOk returns a tuple with the Periods field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPeriods

`func (o *GroupedForecastRequest) SetPeriods(v int32)`

SetPeriods sets Periods field to given value.


### GetDataType

`func (o *GroupedForecastRequest) GetDataType() string`

GetDataType returns the DataType field if non-nil, zero value otherwise.

### GetDataTypeOk

`func (o *GroupedForecastRequest) GetDataTypeOk() (*string, bool)`

GetDataTypeOk returns a tuple with the DataType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDataType

`func (o *GroupedForecastRequest) SetDataType(v string)`

SetDataType sets DataType field to given value.

### HasDataType

`func (o *GroupedForecastRequest) HasDataType() bool`

HasDataType returns a boolean if a field has been set.

### GetModel

`func (o *GroupedForecastRequest) GetModel() string`

GetModel returns the Model field if non-nil, zero value otherwise.

### GetModelOk

`func (o *GroupedForecastRequest) GetModelOk() (*string, bool)`

GetModelOk returns a tuple with the Model field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModel

`func (o *GroupedForecastRequest) SetModel(v string)`

SetModel sets Model field to given value.

### HasModel

`func (o *GroupedForecastRequest) HasModel() bool`

HasModel returns a boolean if a field has been set.

### GetConfidence

`func (o *GroupedForecastRequest) GetConfidence() float32`

GetConfidence returns the Confidence field if non-nil, zero value otherwise.

### GetConfidenceOk

`func (o *GroupedForecastRequest) GetConfidenceOk() (*float32, bool)`

GetConfidenceOk returns a tuple with the Confidence field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConfidence

`func (o *GroupedForecastRequest) SetConfidence(v float32)`

SetConfidence sets Confidence field to given value.

### HasConfidence

`func (o *GroupedForecastRequest) HasConfidence() bool`

HasConfidence returns a boolean if a field has been set.

### GetConfidenceLevel

`func (o *GroupedForecastRequest) GetConfidenceLevel() float32`

GetConfidenceLevel returns the ConfidenceLevel field if non-nil, zero value otherwise.

### GetConfidenceLevelOk

`func (o *GroupedForecastRequest) GetConfidenceLevelOk() (*float32, bool)`

GetConfidenceLevelOk returns a tuple with the ConfidenceLevel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConfidenceLevel

`func (o *GroupedForecastRequest) SetConfidenceLevel(v float32)`

SetConfidenceLevel sets ConfidenceLevel field to given value.

### HasConfidenceLevel

`func (o *GroupedForecastRequest) HasConfidenceLevel() bool`

HasConfidenceLevel returns a boolean if a field has been set.

### GetSeries

`func (o *GroupedForecastRequest) GetSeries() []GroupedForecastSeries`

GetSeries returns the Series field if non-nil, zero value otherwise.

### GetSeriesOk

`func (o *GroupedForecastRequest) GetSeriesOk() (*[]GroupedForecastSeries, bool)`

GetSeriesOk returns a tuple with the Series field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSeries

`func (o *GroupedForecastRequest) SetSeries(v []GroupedForecastSeries)`

SetSeries sets Series field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


