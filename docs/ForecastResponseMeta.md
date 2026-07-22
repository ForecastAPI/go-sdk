# ForecastResponseMeta

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**SelectionMetric** | Pointer to **string** | The back-testing metric that actually chose the winning model | [optional] 
**Timing** | Pointer to [**ForecastResponseMetaTiming**](ForecastResponseMetaTiming.md) |  | [optional] 

## Methods

### NewForecastResponseMeta

`func NewForecastResponseMeta() *ForecastResponseMeta`

NewForecastResponseMeta instantiates a new ForecastResponseMeta object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewForecastResponseMetaWithDefaults

`func NewForecastResponseMetaWithDefaults() *ForecastResponseMeta`

NewForecastResponseMetaWithDefaults instantiates a new ForecastResponseMeta object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSelectionMetric

`func (o *ForecastResponseMeta) GetSelectionMetric() string`

GetSelectionMetric returns the SelectionMetric field if non-nil, zero value otherwise.

### GetSelectionMetricOk

`func (o *ForecastResponseMeta) GetSelectionMetricOk() (*string, bool)`

GetSelectionMetricOk returns a tuple with the SelectionMetric field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSelectionMetric

`func (o *ForecastResponseMeta) SetSelectionMetric(v string)`

SetSelectionMetric sets SelectionMetric field to given value.

### HasSelectionMetric

`func (o *ForecastResponseMeta) HasSelectionMetric() bool`

HasSelectionMetric returns a boolean if a field has been set.

### GetTiming

`func (o *ForecastResponseMeta) GetTiming() ForecastResponseMetaTiming`

GetTiming returns the Timing field if non-nil, zero value otherwise.

### GetTimingOk

`func (o *ForecastResponseMeta) GetTimingOk() (*ForecastResponseMetaTiming, bool)`

GetTimingOk returns a tuple with the Timing field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTiming

`func (o *ForecastResponseMeta) SetTiming(v ForecastResponseMetaTiming)`

SetTiming sets Timing field to given value.

### HasTiming

`func (o *ForecastResponseMeta) HasTiming() bool`

HasTiming returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


