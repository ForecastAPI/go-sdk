# ProductInsightsBatchRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Series** | [**[]ProductInsightsRequest**](ProductInsightsRequest.md) | One entry per product, each the same shape as a single /v2/product-insights request | 
**Batch** | Pointer to **string** | Existing batch identifier to append this upload to, for submitting one logical batch in chunks | [optional] 
**Parts** | Pointer to **int32** | Total number of parts the batch will consist of, when submitting in chunks | [optional] 

## Methods

### NewProductInsightsBatchRequest

`func NewProductInsightsBatchRequest(series []ProductInsightsRequest, ) *ProductInsightsBatchRequest`

NewProductInsightsBatchRequest instantiates a new ProductInsightsBatchRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProductInsightsBatchRequestWithDefaults

`func NewProductInsightsBatchRequestWithDefaults() *ProductInsightsBatchRequest`

NewProductInsightsBatchRequestWithDefaults instantiates a new ProductInsightsBatchRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSeries

`func (o *ProductInsightsBatchRequest) GetSeries() []ProductInsightsRequest`

GetSeries returns the Series field if non-nil, zero value otherwise.

### GetSeriesOk

`func (o *ProductInsightsBatchRequest) GetSeriesOk() (*[]ProductInsightsRequest, bool)`

GetSeriesOk returns a tuple with the Series field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSeries

`func (o *ProductInsightsBatchRequest) SetSeries(v []ProductInsightsRequest)`

SetSeries sets Series field to given value.


### GetBatch

`func (o *ProductInsightsBatchRequest) GetBatch() string`

GetBatch returns the Batch field if non-nil, zero value otherwise.

### GetBatchOk

`func (o *ProductInsightsBatchRequest) GetBatchOk() (*string, bool)`

GetBatchOk returns a tuple with the Batch field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBatch

`func (o *ProductInsightsBatchRequest) SetBatch(v string)`

SetBatch sets Batch field to given value.

### HasBatch

`func (o *ProductInsightsBatchRequest) HasBatch() bool`

HasBatch returns a boolean if a field has been set.

### GetParts

`func (o *ProductInsightsBatchRequest) GetParts() int32`

GetParts returns the Parts field if non-nil, zero value otherwise.

### GetPartsOk

`func (o *ProductInsightsBatchRequest) GetPartsOk() (*int32, bool)`

GetPartsOk returns a tuple with the Parts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParts

`func (o *ProductInsightsBatchRequest) SetParts(v int32)`

SetParts sets Parts field to given value.

### HasParts

`func (o *ProductInsightsBatchRequest) HasParts() bool`

HasParts returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


