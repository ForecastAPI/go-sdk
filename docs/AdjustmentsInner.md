# AdjustmentsInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Type** | **string** | multiplier scales the value; level_shift adds a constant | 
**Value** | **float32** | The factor or the offset. A multiplier must be zero or greater. | 
**FromPeriod** | Pointer to **int32** | Optional 1-based inclusive start of the window; omit to start at period 1 | [optional] 
**ToPeriod** | Pointer to **int32** | Optional 1-based inclusive end of the window; omit to run to the horizon. Must fall within &#x60;periods&#x60;. | [optional] 

## Methods

### NewAdjustmentsInner

`func NewAdjustmentsInner(type_ string, value float32, ) *AdjustmentsInner`

NewAdjustmentsInner instantiates a new AdjustmentsInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAdjustmentsInnerWithDefaults

`func NewAdjustmentsInnerWithDefaults() *AdjustmentsInner`

NewAdjustmentsInnerWithDefaults instantiates a new AdjustmentsInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetType

`func (o *AdjustmentsInner) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *AdjustmentsInner) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *AdjustmentsInner) SetType(v string)`

SetType sets Type field to given value.


### GetValue

`func (o *AdjustmentsInner) GetValue() float32`

GetValue returns the Value field if non-nil, zero value otherwise.

### GetValueOk

`func (o *AdjustmentsInner) GetValueOk() (*float32, bool)`

GetValueOk returns a tuple with the Value field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValue

`func (o *AdjustmentsInner) SetValue(v float32)`

SetValue sets Value field to given value.


### GetFromPeriod

`func (o *AdjustmentsInner) GetFromPeriod() int32`

GetFromPeriod returns the FromPeriod field if non-nil, zero value otherwise.

### GetFromPeriodOk

`func (o *AdjustmentsInner) GetFromPeriodOk() (*int32, bool)`

GetFromPeriodOk returns a tuple with the FromPeriod field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFromPeriod

`func (o *AdjustmentsInner) SetFromPeriod(v int32)`

SetFromPeriod sets FromPeriod field to given value.

### HasFromPeriod

`func (o *AdjustmentsInner) HasFromPeriod() bool`

HasFromPeriod returns a boolean if a field has been set.

### GetToPeriod

`func (o *AdjustmentsInner) GetToPeriod() int32`

GetToPeriod returns the ToPeriod field if non-nil, zero value otherwise.

### GetToPeriodOk

`func (o *AdjustmentsInner) GetToPeriodOk() (*int32, bool)`

GetToPeriodOk returns a tuple with the ToPeriod field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetToPeriod

`func (o *AdjustmentsInner) SetToPeriod(v int32)`

SetToPeriod sets ToPeriod field to given value.

### HasToPeriod

`func (o *AdjustmentsInner) HasToPeriod() bool`

HasToPeriod returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


