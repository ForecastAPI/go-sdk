# BatchForecastAccepted

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**BatchId** | Pointer to **string** | Id to poll via GET /v2/batch/forecast/{batch_id} | [optional] 
**Status** | Pointer to **string** |  | [optional] 
**SeriesCount** | Pointer to **int32** | Number of series accepted. Present on inline submissions; a file-based submission counts its series during processing. | [optional] 
**TimeTakenMs** | Pointer to **float32** |  | [optional] 

## Methods

### NewBatchForecastAccepted

`func NewBatchForecastAccepted() *BatchForecastAccepted`

NewBatchForecastAccepted instantiates a new BatchForecastAccepted object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewBatchForecastAcceptedWithDefaults

`func NewBatchForecastAcceptedWithDefaults() *BatchForecastAccepted`

NewBatchForecastAcceptedWithDefaults instantiates a new BatchForecastAccepted object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBatchId

`func (o *BatchForecastAccepted) GetBatchId() string`

GetBatchId returns the BatchId field if non-nil, zero value otherwise.

### GetBatchIdOk

`func (o *BatchForecastAccepted) GetBatchIdOk() (*string, bool)`

GetBatchIdOk returns a tuple with the BatchId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBatchId

`func (o *BatchForecastAccepted) SetBatchId(v string)`

SetBatchId sets BatchId field to given value.

### HasBatchId

`func (o *BatchForecastAccepted) HasBatchId() bool`

HasBatchId returns a boolean if a field has been set.

### GetStatus

`func (o *BatchForecastAccepted) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *BatchForecastAccepted) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *BatchForecastAccepted) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *BatchForecastAccepted) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetSeriesCount

`func (o *BatchForecastAccepted) GetSeriesCount() int32`

GetSeriesCount returns the SeriesCount field if non-nil, zero value otherwise.

### GetSeriesCountOk

`func (o *BatchForecastAccepted) GetSeriesCountOk() (*int32, bool)`

GetSeriesCountOk returns a tuple with the SeriesCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSeriesCount

`func (o *BatchForecastAccepted) SetSeriesCount(v int32)`

SetSeriesCount sets SeriesCount field to given value.

### HasSeriesCount

`func (o *BatchForecastAccepted) HasSeriesCount() bool`

HasSeriesCount returns a boolean if a field has been set.

### GetTimeTakenMs

`func (o *BatchForecastAccepted) GetTimeTakenMs() float32`

GetTimeTakenMs returns the TimeTakenMs field if non-nil, zero value otherwise.

### GetTimeTakenMsOk

`func (o *BatchForecastAccepted) GetTimeTakenMsOk() (*float32, bool)`

GetTimeTakenMsOk returns a tuple with the TimeTakenMs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimeTakenMs

`func (o *BatchForecastAccepted) SetTimeTakenMs(v float32)`

SetTimeTakenMs sets TimeTakenMs field to given value.

### HasTimeTakenMs

`func (o *BatchForecastAccepted) HasTimeTakenMs() bool`

HasTimeTakenMs returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


