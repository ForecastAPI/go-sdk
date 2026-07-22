# GroupedForecastNode

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Identifier** | Pointer to **string** | The measure — the same for every node | [optional] 
**Segment** | Pointer to **map[string]interface{}** | The dimension values this node covers — empty for the total, all declared dimensions for a leaf | [optional] 
**Level** | Pointer to **int32** | Depth in the tree; 0 is the total | [optional] 
**IsLeaf** | Pointer to **bool** |  | [optional] 
**Parent** | Pointer to **NullableString** | Segment key of the parent node; null for the total | [optional] 
**Children** | Pointer to **[]string** | Segment keys of the children; empty for leaves | [optional] 
**Forecasts** | Pointer to [**[]ForecastPeriod**](ForecastPeriod.md) | The reconciled path — this is what is stored and accuracy-tracked per node | [optional] 
**ModelInfo** | Pointer to **map[string]interface{}** | Method and reconciliation details for this node. With min_trace, the node&#39;s unreconciled path is reported under &#x60;reconciliation.base_forecast&#x60;. When an aggregate band cannot be built honestly (a child&#39;s band coverage is unknown), the band is omitted and &#x60;reconciliation.interval_reason&#x60; states why.  | [optional] 

## Methods

### NewGroupedForecastNode

`func NewGroupedForecastNode() *GroupedForecastNode`

NewGroupedForecastNode instantiates a new GroupedForecastNode object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGroupedForecastNodeWithDefaults

`func NewGroupedForecastNodeWithDefaults() *GroupedForecastNode`

NewGroupedForecastNodeWithDefaults instantiates a new GroupedForecastNode object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetIdentifier

`func (o *GroupedForecastNode) GetIdentifier() string`

GetIdentifier returns the Identifier field if non-nil, zero value otherwise.

### GetIdentifierOk

`func (o *GroupedForecastNode) GetIdentifierOk() (*string, bool)`

GetIdentifierOk returns a tuple with the Identifier field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdentifier

`func (o *GroupedForecastNode) SetIdentifier(v string)`

SetIdentifier sets Identifier field to given value.

### HasIdentifier

`func (o *GroupedForecastNode) HasIdentifier() bool`

HasIdentifier returns a boolean if a field has been set.

### GetSegment

`func (o *GroupedForecastNode) GetSegment() map[string]interface{}`

GetSegment returns the Segment field if non-nil, zero value otherwise.

### GetSegmentOk

`func (o *GroupedForecastNode) GetSegmentOk() (*map[string]interface{}, bool)`

GetSegmentOk returns a tuple with the Segment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSegment

`func (o *GroupedForecastNode) SetSegment(v map[string]interface{})`

SetSegment sets Segment field to given value.

### HasSegment

`func (o *GroupedForecastNode) HasSegment() bool`

HasSegment returns a boolean if a field has been set.

### GetLevel

`func (o *GroupedForecastNode) GetLevel() int32`

GetLevel returns the Level field if non-nil, zero value otherwise.

### GetLevelOk

`func (o *GroupedForecastNode) GetLevelOk() (*int32, bool)`

GetLevelOk returns a tuple with the Level field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLevel

`func (o *GroupedForecastNode) SetLevel(v int32)`

SetLevel sets Level field to given value.

### HasLevel

`func (o *GroupedForecastNode) HasLevel() bool`

HasLevel returns a boolean if a field has been set.

### GetIsLeaf

`func (o *GroupedForecastNode) GetIsLeaf() bool`

GetIsLeaf returns the IsLeaf field if non-nil, zero value otherwise.

### GetIsLeafOk

`func (o *GroupedForecastNode) GetIsLeafOk() (*bool, bool)`

GetIsLeafOk returns a tuple with the IsLeaf field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsLeaf

`func (o *GroupedForecastNode) SetIsLeaf(v bool)`

SetIsLeaf sets IsLeaf field to given value.

### HasIsLeaf

`func (o *GroupedForecastNode) HasIsLeaf() bool`

HasIsLeaf returns a boolean if a field has been set.

### GetParent

`func (o *GroupedForecastNode) GetParent() string`

GetParent returns the Parent field if non-nil, zero value otherwise.

### GetParentOk

`func (o *GroupedForecastNode) GetParentOk() (*string, bool)`

GetParentOk returns a tuple with the Parent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParent

`func (o *GroupedForecastNode) SetParent(v string)`

SetParent sets Parent field to given value.

### HasParent

`func (o *GroupedForecastNode) HasParent() bool`

HasParent returns a boolean if a field has been set.

### SetParentNil

`func (o *GroupedForecastNode) SetParentNil(b bool)`

 SetParentNil sets the value for Parent to be an explicit nil

### UnsetParent
`func (o *GroupedForecastNode) UnsetParent()`

UnsetParent ensures that no value is present for Parent, not even an explicit nil
### GetChildren

`func (o *GroupedForecastNode) GetChildren() []string`

GetChildren returns the Children field if non-nil, zero value otherwise.

### GetChildrenOk

`func (o *GroupedForecastNode) GetChildrenOk() (*[]string, bool)`

GetChildrenOk returns a tuple with the Children field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChildren

`func (o *GroupedForecastNode) SetChildren(v []string)`

SetChildren sets Children field to given value.

### HasChildren

`func (o *GroupedForecastNode) HasChildren() bool`

HasChildren returns a boolean if a field has been set.

### GetForecasts

`func (o *GroupedForecastNode) GetForecasts() []ForecastPeriod`

GetForecasts returns the Forecasts field if non-nil, zero value otherwise.

### GetForecastsOk

`func (o *GroupedForecastNode) GetForecastsOk() (*[]ForecastPeriod, bool)`

GetForecastsOk returns a tuple with the Forecasts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetForecasts

`func (o *GroupedForecastNode) SetForecasts(v []ForecastPeriod)`

SetForecasts sets Forecasts field to given value.

### HasForecasts

`func (o *GroupedForecastNode) HasForecasts() bool`

HasForecasts returns a boolean if a field has been set.

### GetModelInfo

`func (o *GroupedForecastNode) GetModelInfo() map[string]interface{}`

GetModelInfo returns the ModelInfo field if non-nil, zero value otherwise.

### GetModelInfoOk

`func (o *GroupedForecastNode) GetModelInfoOk() (*map[string]interface{}, bool)`

GetModelInfoOk returns a tuple with the ModelInfo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModelInfo

`func (o *GroupedForecastNode) SetModelInfo(v map[string]interface{})`

SetModelInfo sets ModelInfo field to given value.

### HasModelInfo

`func (o *GroupedForecastNode) HasModelInfo() bool`

HasModelInfo returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


