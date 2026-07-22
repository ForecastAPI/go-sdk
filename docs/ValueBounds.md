# ValueBounds

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Min** | Pointer to **NullableFloat32** | Floor the series cannot go below | [optional] 
**Max** | Pointer to **NullableFloat32** | Ceiling the series cannot exceed | [optional] 

## Methods

### NewValueBounds

`func NewValueBounds() *ValueBounds`

NewValueBounds instantiates a new ValueBounds object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewValueBoundsWithDefaults

`func NewValueBoundsWithDefaults() *ValueBounds`

NewValueBoundsWithDefaults instantiates a new ValueBounds object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMin

`func (o *ValueBounds) GetMin() float32`

GetMin returns the Min field if non-nil, zero value otherwise.

### GetMinOk

`func (o *ValueBounds) GetMinOk() (*float32, bool)`

GetMinOk returns a tuple with the Min field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMin

`func (o *ValueBounds) SetMin(v float32)`

SetMin sets Min field to given value.

### HasMin

`func (o *ValueBounds) HasMin() bool`

HasMin returns a boolean if a field has been set.

### SetMinNil

`func (o *ValueBounds) SetMinNil(b bool)`

 SetMinNil sets the value for Min to be an explicit nil

### UnsetMin
`func (o *ValueBounds) UnsetMin()`

UnsetMin ensures that no value is present for Min, not even an explicit nil
### GetMax

`func (o *ValueBounds) GetMax() float32`

GetMax returns the Max field if non-nil, zero value otherwise.

### GetMaxOk

`func (o *ValueBounds) GetMaxOk() (*float32, bool)`

GetMaxOk returns a tuple with the Max field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMax

`func (o *ValueBounds) SetMax(v float32)`

SetMax sets Max field to given value.

### HasMax

`func (o *ValueBounds) HasMax() bool`

HasMax returns a boolean if a field has been set.

### SetMaxNil

`func (o *ValueBounds) SetMaxNil(b bool)`

 SetMaxNil sets the value for Max to be an explicit nil

### UnsetMax
`func (o *ValueBounds) UnsetMax()`

UnsetMax ensures that no value is present for Max, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


