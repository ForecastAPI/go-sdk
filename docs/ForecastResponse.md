# ForecastResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Result** | Pointer to [**ForecastResponseResult**](ForecastResponseResult.md) |  | [optional] 
**Adjusted** | Pointer to [**AdjustedForecast**](AdjustedForecast.md) |  | [optional] 
**Accumulated** | Pointer to [**AccumulatedForecast**](AccumulatedForecast.md) |  | [optional] 
**Meta** | Pointer to [**ForecastResponseMeta**](ForecastResponseMeta.md) |  | [optional] 

## Methods

### NewForecastResponse

`func NewForecastResponse() *ForecastResponse`

NewForecastResponse instantiates a new ForecastResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewForecastResponseWithDefaults

`func NewForecastResponseWithDefaults() *ForecastResponse`

NewForecastResponseWithDefaults instantiates a new ForecastResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetResult

`func (o *ForecastResponse) GetResult() ForecastResponseResult`

GetResult returns the Result field if non-nil, zero value otherwise.

### GetResultOk

`func (o *ForecastResponse) GetResultOk() (*ForecastResponseResult, bool)`

GetResultOk returns a tuple with the Result field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResult

`func (o *ForecastResponse) SetResult(v ForecastResponseResult)`

SetResult sets Result field to given value.

### HasResult

`func (o *ForecastResponse) HasResult() bool`

HasResult returns a boolean if a field has been set.

### GetAdjusted

`func (o *ForecastResponse) GetAdjusted() AdjustedForecast`

GetAdjusted returns the Adjusted field if non-nil, zero value otherwise.

### GetAdjustedOk

`func (o *ForecastResponse) GetAdjustedOk() (*AdjustedForecast, bool)`

GetAdjustedOk returns a tuple with the Adjusted field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAdjusted

`func (o *ForecastResponse) SetAdjusted(v AdjustedForecast)`

SetAdjusted sets Adjusted field to given value.

### HasAdjusted

`func (o *ForecastResponse) HasAdjusted() bool`

HasAdjusted returns a boolean if a field has been set.

### GetAccumulated

`func (o *ForecastResponse) GetAccumulated() AccumulatedForecast`

GetAccumulated returns the Accumulated field if non-nil, zero value otherwise.

### GetAccumulatedOk

`func (o *ForecastResponse) GetAccumulatedOk() (*AccumulatedForecast, bool)`

GetAccumulatedOk returns a tuple with the Accumulated field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccumulated

`func (o *ForecastResponse) SetAccumulated(v AccumulatedForecast)`

SetAccumulated sets Accumulated field to given value.

### HasAccumulated

`func (o *ForecastResponse) HasAccumulated() bool`

HasAccumulated returns a boolean if a field has been set.

### GetMeta

`func (o *ForecastResponse) GetMeta() ForecastResponseMeta`

GetMeta returns the Meta field if non-nil, zero value otherwise.

### GetMetaOk

`func (o *ForecastResponse) GetMetaOk() (*ForecastResponseMeta, bool)`

GetMetaOk returns a tuple with the Meta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMeta

`func (o *ForecastResponse) SetMeta(v ForecastResponseMeta)`

SetMeta sets Meta field to given value.

### HasMeta

`func (o *ForecastResponse) HasMeta() bool`

HasMeta returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


