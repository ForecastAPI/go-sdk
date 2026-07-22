# GroupedForecastResults

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Identifier** | Pointer to **string** |  | [optional] 
**TenantContext** | Pointer to **NullableString** |  | [optional] 
**Hierarchy** | Pointer to **[]string** |  | [optional] 
**Reconciliation** | Pointer to [**GroupedForecastResultsReconciliation**](GroupedForecastResultsReconciliation.md) |  | [optional] 
**ConfidenceLevel** | Pointer to **float32** |  | [optional] 
**NodeCount** | Pointer to **int32** |  | [optional] 
**Nodes** | Pointer to [**map[string]GroupedForecastNode**](GroupedForecastNode.md) | Every node of the hierarchy, keyed by segment key: &#x60;total&#x60; for the root, then e.g. &#x60;region&#x3D;eu&#x60; for aggregates and &#x60;plan&#x3D;pro|region&#x3D;eu&#x60; for leaves. Every parent equals the sum of its children in every period.  | [optional] 

## Methods

### NewGroupedForecastResults

`func NewGroupedForecastResults() *GroupedForecastResults`

NewGroupedForecastResults instantiates a new GroupedForecastResults object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGroupedForecastResultsWithDefaults

`func NewGroupedForecastResultsWithDefaults() *GroupedForecastResults`

NewGroupedForecastResultsWithDefaults instantiates a new GroupedForecastResults object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetIdentifier

`func (o *GroupedForecastResults) GetIdentifier() string`

GetIdentifier returns the Identifier field if non-nil, zero value otherwise.

### GetIdentifierOk

`func (o *GroupedForecastResults) GetIdentifierOk() (*string, bool)`

GetIdentifierOk returns a tuple with the Identifier field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdentifier

`func (o *GroupedForecastResults) SetIdentifier(v string)`

SetIdentifier sets Identifier field to given value.

### HasIdentifier

`func (o *GroupedForecastResults) HasIdentifier() bool`

HasIdentifier returns a boolean if a field has been set.

### GetTenantContext

`func (o *GroupedForecastResults) GetTenantContext() string`

GetTenantContext returns the TenantContext field if non-nil, zero value otherwise.

### GetTenantContextOk

`func (o *GroupedForecastResults) GetTenantContextOk() (*string, bool)`

GetTenantContextOk returns a tuple with the TenantContext field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTenantContext

`func (o *GroupedForecastResults) SetTenantContext(v string)`

SetTenantContext sets TenantContext field to given value.

### HasTenantContext

`func (o *GroupedForecastResults) HasTenantContext() bool`

HasTenantContext returns a boolean if a field has been set.

### SetTenantContextNil

`func (o *GroupedForecastResults) SetTenantContextNil(b bool)`

 SetTenantContextNil sets the value for TenantContext to be an explicit nil

### UnsetTenantContext
`func (o *GroupedForecastResults) UnsetTenantContext()`

UnsetTenantContext ensures that no value is present for TenantContext, not even an explicit nil
### GetHierarchy

`func (o *GroupedForecastResults) GetHierarchy() []string`

GetHierarchy returns the Hierarchy field if non-nil, zero value otherwise.

### GetHierarchyOk

`func (o *GroupedForecastResults) GetHierarchyOk() (*[]string, bool)`

GetHierarchyOk returns a tuple with the Hierarchy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHierarchy

`func (o *GroupedForecastResults) SetHierarchy(v []string)`

SetHierarchy sets Hierarchy field to given value.

### HasHierarchy

`func (o *GroupedForecastResults) HasHierarchy() bool`

HasHierarchy returns a boolean if a field has been set.

### GetReconciliation

`func (o *GroupedForecastResults) GetReconciliation() GroupedForecastResultsReconciliation`

GetReconciliation returns the Reconciliation field if non-nil, zero value otherwise.

### GetReconciliationOk

`func (o *GroupedForecastResults) GetReconciliationOk() (*GroupedForecastResultsReconciliation, bool)`

GetReconciliationOk returns a tuple with the Reconciliation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReconciliation

`func (o *GroupedForecastResults) SetReconciliation(v GroupedForecastResultsReconciliation)`

SetReconciliation sets Reconciliation field to given value.

### HasReconciliation

`func (o *GroupedForecastResults) HasReconciliation() bool`

HasReconciliation returns a boolean if a field has been set.

### GetConfidenceLevel

`func (o *GroupedForecastResults) GetConfidenceLevel() float32`

GetConfidenceLevel returns the ConfidenceLevel field if non-nil, zero value otherwise.

### GetConfidenceLevelOk

`func (o *GroupedForecastResults) GetConfidenceLevelOk() (*float32, bool)`

GetConfidenceLevelOk returns a tuple with the ConfidenceLevel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConfidenceLevel

`func (o *GroupedForecastResults) SetConfidenceLevel(v float32)`

SetConfidenceLevel sets ConfidenceLevel field to given value.

### HasConfidenceLevel

`func (o *GroupedForecastResults) HasConfidenceLevel() bool`

HasConfidenceLevel returns a boolean if a field has been set.

### GetNodeCount

`func (o *GroupedForecastResults) GetNodeCount() int32`

GetNodeCount returns the NodeCount field if non-nil, zero value otherwise.

### GetNodeCountOk

`func (o *GroupedForecastResults) GetNodeCountOk() (*int32, bool)`

GetNodeCountOk returns a tuple with the NodeCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNodeCount

`func (o *GroupedForecastResults) SetNodeCount(v int32)`

SetNodeCount sets NodeCount field to given value.

### HasNodeCount

`func (o *GroupedForecastResults) HasNodeCount() bool`

HasNodeCount returns a boolean if a field has been set.

### GetNodes

`func (o *GroupedForecastResults) GetNodes() map[string]GroupedForecastNode`

GetNodes returns the Nodes field if non-nil, zero value otherwise.

### GetNodesOk

`func (o *GroupedForecastResults) GetNodesOk() (*map[string]GroupedForecastNode, bool)`

GetNodesOk returns a tuple with the Nodes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNodes

`func (o *GroupedForecastResults) SetNodes(v map[string]GroupedForecastNode)`

SetNodes sets Nodes field to given value.

### HasNodes

`func (o *GroupedForecastResults) HasNodes() bool`

HasNodes returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


