# GroupedForecastAccepted

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**GroupedForecastId** | Pointer to **string** | Id to poll via GET /v2/forecast/grouped/{grouped_forecast_id} | [optional] 
**Status** | Pointer to **string** |  | [optional] 
**SeriesCount** | Pointer to **int32** | Leaf series submitted | [optional] 
**NodeCount** | Pointer to **int32** | What will actually be forecast and reconciled — the leaves plus every derived aggregate and the total | [optional] 
**Reconciliation** | Pointer to **string** |  | [optional] 
**TimeTakenMs** | Pointer to **float32** |  | [optional] 

## Methods

### NewGroupedForecastAccepted

`func NewGroupedForecastAccepted() *GroupedForecastAccepted`

NewGroupedForecastAccepted instantiates a new GroupedForecastAccepted object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGroupedForecastAcceptedWithDefaults

`func NewGroupedForecastAcceptedWithDefaults() *GroupedForecastAccepted`

NewGroupedForecastAcceptedWithDefaults instantiates a new GroupedForecastAccepted object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetGroupedForecastId

`func (o *GroupedForecastAccepted) GetGroupedForecastId() string`

GetGroupedForecastId returns the GroupedForecastId field if non-nil, zero value otherwise.

### GetGroupedForecastIdOk

`func (o *GroupedForecastAccepted) GetGroupedForecastIdOk() (*string, bool)`

GetGroupedForecastIdOk returns a tuple with the GroupedForecastId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGroupedForecastId

`func (o *GroupedForecastAccepted) SetGroupedForecastId(v string)`

SetGroupedForecastId sets GroupedForecastId field to given value.

### HasGroupedForecastId

`func (o *GroupedForecastAccepted) HasGroupedForecastId() bool`

HasGroupedForecastId returns a boolean if a field has been set.

### GetStatus

`func (o *GroupedForecastAccepted) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *GroupedForecastAccepted) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *GroupedForecastAccepted) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *GroupedForecastAccepted) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetSeriesCount

`func (o *GroupedForecastAccepted) GetSeriesCount() int32`

GetSeriesCount returns the SeriesCount field if non-nil, zero value otherwise.

### GetSeriesCountOk

`func (o *GroupedForecastAccepted) GetSeriesCountOk() (*int32, bool)`

GetSeriesCountOk returns a tuple with the SeriesCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSeriesCount

`func (o *GroupedForecastAccepted) SetSeriesCount(v int32)`

SetSeriesCount sets SeriesCount field to given value.

### HasSeriesCount

`func (o *GroupedForecastAccepted) HasSeriesCount() bool`

HasSeriesCount returns a boolean if a field has been set.

### GetNodeCount

`func (o *GroupedForecastAccepted) GetNodeCount() int32`

GetNodeCount returns the NodeCount field if non-nil, zero value otherwise.

### GetNodeCountOk

`func (o *GroupedForecastAccepted) GetNodeCountOk() (*int32, bool)`

GetNodeCountOk returns a tuple with the NodeCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNodeCount

`func (o *GroupedForecastAccepted) SetNodeCount(v int32)`

SetNodeCount sets NodeCount field to given value.

### HasNodeCount

`func (o *GroupedForecastAccepted) HasNodeCount() bool`

HasNodeCount returns a boolean if a field has been set.

### GetReconciliation

`func (o *GroupedForecastAccepted) GetReconciliation() string`

GetReconciliation returns the Reconciliation field if non-nil, zero value otherwise.

### GetReconciliationOk

`func (o *GroupedForecastAccepted) GetReconciliationOk() (*string, bool)`

GetReconciliationOk returns a tuple with the Reconciliation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReconciliation

`func (o *GroupedForecastAccepted) SetReconciliation(v string)`

SetReconciliation sets Reconciliation field to given value.

### HasReconciliation

`func (o *GroupedForecastAccepted) HasReconciliation() bool`

HasReconciliation returns a boolean if a field has been set.

### GetTimeTakenMs

`func (o *GroupedForecastAccepted) GetTimeTakenMs() float32`

GetTimeTakenMs returns the TimeTakenMs field if non-nil, zero value otherwise.

### GetTimeTakenMsOk

`func (o *GroupedForecastAccepted) GetTimeTakenMsOk() (*float32, bool)`

GetTimeTakenMsOk returns a tuple with the TimeTakenMs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimeTakenMs

`func (o *GroupedForecastAccepted) SetTimeTakenMs(v float32)`

SetTimeTakenMs sets TimeTakenMs field to given value.

### HasTimeTakenMs

`func (o *GroupedForecastAccepted) HasTimeTakenMs() bool`

HasTimeTakenMs returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


