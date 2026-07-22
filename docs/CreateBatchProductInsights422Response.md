# CreateBatchProductInsights422Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Error** | Pointer to **string** |  | [optional] 
**ValidationErrors** | Pointer to [**map[string]map[string][]string**](map.md) | Failing entries, keyed by their index in &#x60;series&#x60; | [optional] 
**ValidCount** | Pointer to **int32** |  | [optional] 
**TotalCount** | Pointer to **int32** |  | [optional] 
**TimeTakenMs** | Pointer to **float32** |  | [optional] 

## Methods

### NewCreateBatchProductInsights422Response

`func NewCreateBatchProductInsights422Response() *CreateBatchProductInsights422Response`

NewCreateBatchProductInsights422Response instantiates a new CreateBatchProductInsights422Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateBatchProductInsights422ResponseWithDefaults

`func NewCreateBatchProductInsights422ResponseWithDefaults() *CreateBatchProductInsights422Response`

NewCreateBatchProductInsights422ResponseWithDefaults instantiates a new CreateBatchProductInsights422Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetError

`func (o *CreateBatchProductInsights422Response) GetError() string`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *CreateBatchProductInsights422Response) GetErrorOk() (*string, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *CreateBatchProductInsights422Response) SetError(v string)`

SetError sets Error field to given value.

### HasError

`func (o *CreateBatchProductInsights422Response) HasError() bool`

HasError returns a boolean if a field has been set.

### GetValidationErrors

`func (o *CreateBatchProductInsights422Response) GetValidationErrors() map[string]map[string][]string`

GetValidationErrors returns the ValidationErrors field if non-nil, zero value otherwise.

### GetValidationErrorsOk

`func (o *CreateBatchProductInsights422Response) GetValidationErrorsOk() (*map[string]map[string][]string, bool)`

GetValidationErrorsOk returns a tuple with the ValidationErrors field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValidationErrors

`func (o *CreateBatchProductInsights422Response) SetValidationErrors(v map[string]map[string][]string)`

SetValidationErrors sets ValidationErrors field to given value.

### HasValidationErrors

`func (o *CreateBatchProductInsights422Response) HasValidationErrors() bool`

HasValidationErrors returns a boolean if a field has been set.

### GetValidCount

`func (o *CreateBatchProductInsights422Response) GetValidCount() int32`

GetValidCount returns the ValidCount field if non-nil, zero value otherwise.

### GetValidCountOk

`func (o *CreateBatchProductInsights422Response) GetValidCountOk() (*int32, bool)`

GetValidCountOk returns a tuple with the ValidCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValidCount

`func (o *CreateBatchProductInsights422Response) SetValidCount(v int32)`

SetValidCount sets ValidCount field to given value.

### HasValidCount

`func (o *CreateBatchProductInsights422Response) HasValidCount() bool`

HasValidCount returns a boolean if a field has been set.

### GetTotalCount

`func (o *CreateBatchProductInsights422Response) GetTotalCount() int32`

GetTotalCount returns the TotalCount field if non-nil, zero value otherwise.

### GetTotalCountOk

`func (o *CreateBatchProductInsights422Response) GetTotalCountOk() (*int32, bool)`

GetTotalCountOk returns a tuple with the TotalCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalCount

`func (o *CreateBatchProductInsights422Response) SetTotalCount(v int32)`

SetTotalCount sets TotalCount field to given value.

### HasTotalCount

`func (o *CreateBatchProductInsights422Response) HasTotalCount() bool`

HasTotalCount returns a boolean if a field has been set.

### GetTimeTakenMs

`func (o *CreateBatchProductInsights422Response) GetTimeTakenMs() float32`

GetTimeTakenMs returns the TimeTakenMs field if non-nil, zero value otherwise.

### GetTimeTakenMsOk

`func (o *CreateBatchProductInsights422Response) GetTimeTakenMsOk() (*float32, bool)`

GetTimeTakenMsOk returns a tuple with the TimeTakenMs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimeTakenMs

`func (o *CreateBatchProductInsights422Response) SetTimeTakenMs(v float32)`

SetTimeTakenMs sets TimeTakenMs field to given value.

### HasTimeTakenMs

`func (o *CreateBatchProductInsights422Response) HasTimeTakenMs() bool`

HasTimeTakenMs returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


