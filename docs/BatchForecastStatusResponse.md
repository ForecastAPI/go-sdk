# BatchForecastStatusResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Identifier** | Pointer to **string** | The batch id | [optional] 
**Status** | Pointer to **string** |  | [optional] 
**BatchParts** | Pointer to **NullableInt32** | Number of parts the batch was split into for processing | [optional] 
**Results** | Pointer to [**BatchForecastStatusResponseResults**](BatchForecastStatusResponseResults.md) |  | [optional] 
**Parts** | Pointer to [**[]BatchForecastStatusResponsePartsInner**](BatchForecastStatusResponsePartsInner.md) | Per-part progress metadata (the forecasts themselves live under results.data) | [optional] 
**StartedAt** | Pointer to **NullableTime** |  | [optional] 
**CompletedAt** | Pointer to **NullableTime** |  | [optional] 
**CreatedAt** | Pointer to **time.Time** |  | [optional] 
**UpdatedAt** | Pointer to **time.Time** |  | [optional] 

## Methods

### NewBatchForecastStatusResponse

`func NewBatchForecastStatusResponse() *BatchForecastStatusResponse`

NewBatchForecastStatusResponse instantiates a new BatchForecastStatusResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewBatchForecastStatusResponseWithDefaults

`func NewBatchForecastStatusResponseWithDefaults() *BatchForecastStatusResponse`

NewBatchForecastStatusResponseWithDefaults instantiates a new BatchForecastStatusResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetIdentifier

`func (o *BatchForecastStatusResponse) GetIdentifier() string`

GetIdentifier returns the Identifier field if non-nil, zero value otherwise.

### GetIdentifierOk

`func (o *BatchForecastStatusResponse) GetIdentifierOk() (*string, bool)`

GetIdentifierOk returns a tuple with the Identifier field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdentifier

`func (o *BatchForecastStatusResponse) SetIdentifier(v string)`

SetIdentifier sets Identifier field to given value.

### HasIdentifier

`func (o *BatchForecastStatusResponse) HasIdentifier() bool`

HasIdentifier returns a boolean if a field has been set.

### GetStatus

`func (o *BatchForecastStatusResponse) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *BatchForecastStatusResponse) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *BatchForecastStatusResponse) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *BatchForecastStatusResponse) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetBatchParts

`func (o *BatchForecastStatusResponse) GetBatchParts() int32`

GetBatchParts returns the BatchParts field if non-nil, zero value otherwise.

### GetBatchPartsOk

`func (o *BatchForecastStatusResponse) GetBatchPartsOk() (*int32, bool)`

GetBatchPartsOk returns a tuple with the BatchParts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBatchParts

`func (o *BatchForecastStatusResponse) SetBatchParts(v int32)`

SetBatchParts sets BatchParts field to given value.

### HasBatchParts

`func (o *BatchForecastStatusResponse) HasBatchParts() bool`

HasBatchParts returns a boolean if a field has been set.

### SetBatchPartsNil

`func (o *BatchForecastStatusResponse) SetBatchPartsNil(b bool)`

 SetBatchPartsNil sets the value for BatchParts to be an explicit nil

### UnsetBatchParts
`func (o *BatchForecastStatusResponse) UnsetBatchParts()`

UnsetBatchParts ensures that no value is present for BatchParts, not even an explicit nil
### GetResults

`func (o *BatchForecastStatusResponse) GetResults() BatchForecastStatusResponseResults`

GetResults returns the Results field if non-nil, zero value otherwise.

### GetResultsOk

`func (o *BatchForecastStatusResponse) GetResultsOk() (*BatchForecastStatusResponseResults, bool)`

GetResultsOk returns a tuple with the Results field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResults

`func (o *BatchForecastStatusResponse) SetResults(v BatchForecastStatusResponseResults)`

SetResults sets Results field to given value.

### HasResults

`func (o *BatchForecastStatusResponse) HasResults() bool`

HasResults returns a boolean if a field has been set.

### GetParts

`func (o *BatchForecastStatusResponse) GetParts() []BatchForecastStatusResponsePartsInner`

GetParts returns the Parts field if non-nil, zero value otherwise.

### GetPartsOk

`func (o *BatchForecastStatusResponse) GetPartsOk() (*[]BatchForecastStatusResponsePartsInner, bool)`

GetPartsOk returns a tuple with the Parts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParts

`func (o *BatchForecastStatusResponse) SetParts(v []BatchForecastStatusResponsePartsInner)`

SetParts sets Parts field to given value.

### HasParts

`func (o *BatchForecastStatusResponse) HasParts() bool`

HasParts returns a boolean if a field has been set.

### GetStartedAt

`func (o *BatchForecastStatusResponse) GetStartedAt() time.Time`

GetStartedAt returns the StartedAt field if non-nil, zero value otherwise.

### GetStartedAtOk

`func (o *BatchForecastStatusResponse) GetStartedAtOk() (*time.Time, bool)`

GetStartedAtOk returns a tuple with the StartedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartedAt

`func (o *BatchForecastStatusResponse) SetStartedAt(v time.Time)`

SetStartedAt sets StartedAt field to given value.

### HasStartedAt

`func (o *BatchForecastStatusResponse) HasStartedAt() bool`

HasStartedAt returns a boolean if a field has been set.

### SetStartedAtNil

`func (o *BatchForecastStatusResponse) SetStartedAtNil(b bool)`

 SetStartedAtNil sets the value for StartedAt to be an explicit nil

### UnsetStartedAt
`func (o *BatchForecastStatusResponse) UnsetStartedAt()`

UnsetStartedAt ensures that no value is present for StartedAt, not even an explicit nil
### GetCompletedAt

`func (o *BatchForecastStatusResponse) GetCompletedAt() time.Time`

GetCompletedAt returns the CompletedAt field if non-nil, zero value otherwise.

### GetCompletedAtOk

`func (o *BatchForecastStatusResponse) GetCompletedAtOk() (*time.Time, bool)`

GetCompletedAtOk returns a tuple with the CompletedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompletedAt

`func (o *BatchForecastStatusResponse) SetCompletedAt(v time.Time)`

SetCompletedAt sets CompletedAt field to given value.

### HasCompletedAt

`func (o *BatchForecastStatusResponse) HasCompletedAt() bool`

HasCompletedAt returns a boolean if a field has been set.

### SetCompletedAtNil

`func (o *BatchForecastStatusResponse) SetCompletedAtNil(b bool)`

 SetCompletedAtNil sets the value for CompletedAt to be an explicit nil

### UnsetCompletedAt
`func (o *BatchForecastStatusResponse) UnsetCompletedAt()`

UnsetCompletedAt ensures that no value is present for CompletedAt, not even an explicit nil
### GetCreatedAt

`func (o *BatchForecastStatusResponse) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *BatchForecastStatusResponse) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *BatchForecastStatusResponse) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *BatchForecastStatusResponse) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetUpdatedAt

`func (o *BatchForecastStatusResponse) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *BatchForecastStatusResponse) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *BatchForecastStatusResponse) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *BatchForecastStatusResponse) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


