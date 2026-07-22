# InventoryPlanningResponseMetaTiming

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Validation** | Pointer to **float32** | Time taken for request validation in milliseconds | [optional] 
**Planning** | Pointer to **float32** | Time taken for inventory planning in milliseconds | [optional] 
**Total** | Pointer to **float32** | Total processing time in milliseconds | [optional] 

## Methods

### NewInventoryPlanningResponseMetaTiming

`func NewInventoryPlanningResponseMetaTiming() *InventoryPlanningResponseMetaTiming`

NewInventoryPlanningResponseMetaTiming instantiates a new InventoryPlanningResponseMetaTiming object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewInventoryPlanningResponseMetaTimingWithDefaults

`func NewInventoryPlanningResponseMetaTimingWithDefaults() *InventoryPlanningResponseMetaTiming`

NewInventoryPlanningResponseMetaTimingWithDefaults instantiates a new InventoryPlanningResponseMetaTiming object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetValidation

`func (o *InventoryPlanningResponseMetaTiming) GetValidation() float32`

GetValidation returns the Validation field if non-nil, zero value otherwise.

### GetValidationOk

`func (o *InventoryPlanningResponseMetaTiming) GetValidationOk() (*float32, bool)`

GetValidationOk returns a tuple with the Validation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValidation

`func (o *InventoryPlanningResponseMetaTiming) SetValidation(v float32)`

SetValidation sets Validation field to given value.

### HasValidation

`func (o *InventoryPlanningResponseMetaTiming) HasValidation() bool`

HasValidation returns a boolean if a field has been set.

### GetPlanning

`func (o *InventoryPlanningResponseMetaTiming) GetPlanning() float32`

GetPlanning returns the Planning field if non-nil, zero value otherwise.

### GetPlanningOk

`func (o *InventoryPlanningResponseMetaTiming) GetPlanningOk() (*float32, bool)`

GetPlanningOk returns a tuple with the Planning field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlanning

`func (o *InventoryPlanningResponseMetaTiming) SetPlanning(v float32)`

SetPlanning sets Planning field to given value.

### HasPlanning

`func (o *InventoryPlanningResponseMetaTiming) HasPlanning() bool`

HasPlanning returns a boolean if a field has been set.

### GetTotal

`func (o *InventoryPlanningResponseMetaTiming) GetTotal() float32`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *InventoryPlanningResponseMetaTiming) GetTotalOk() (*float32, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *InventoryPlanningResponseMetaTiming) SetTotal(v float32)`

SetTotal sets Total field to given value.

### HasTotal

`func (o *InventoryPlanningResponseMetaTiming) HasTotal() bool`

HasTotal returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


