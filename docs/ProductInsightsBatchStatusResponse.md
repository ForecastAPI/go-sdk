# ProductInsightsBatchStatusResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Identifier** | Pointer to **string** | The batch id | [optional] 
**Status** | Pointer to **string** |  | [optional] 
**BatchParts** | Pointer to **NullableInt32** |  | [optional] 
**Results** | Pointer to **map[string]interface{}** | Summary and per-product analysis results as parts complete | [optional] 
**Parts** | Pointer to **[]map[string]interface{}** | Per-part progress, each carrying its analyses once processed | [optional] 
**StartedAt** | Pointer to **NullableTime** |  | [optional] 
**CompletedAt** | Pointer to **NullableTime** |  | [optional] 
**CreatedAt** | Pointer to **time.Time** |  | [optional] 
**UpdatedAt** | Pointer to **time.Time** |  | [optional] 

## Methods

### NewProductInsightsBatchStatusResponse

`func NewProductInsightsBatchStatusResponse() *ProductInsightsBatchStatusResponse`

NewProductInsightsBatchStatusResponse instantiates a new ProductInsightsBatchStatusResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProductInsightsBatchStatusResponseWithDefaults

`func NewProductInsightsBatchStatusResponseWithDefaults() *ProductInsightsBatchStatusResponse`

NewProductInsightsBatchStatusResponseWithDefaults instantiates a new ProductInsightsBatchStatusResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetIdentifier

`func (o *ProductInsightsBatchStatusResponse) GetIdentifier() string`

GetIdentifier returns the Identifier field if non-nil, zero value otherwise.

### GetIdentifierOk

`func (o *ProductInsightsBatchStatusResponse) GetIdentifierOk() (*string, bool)`

GetIdentifierOk returns a tuple with the Identifier field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdentifier

`func (o *ProductInsightsBatchStatusResponse) SetIdentifier(v string)`

SetIdentifier sets Identifier field to given value.

### HasIdentifier

`func (o *ProductInsightsBatchStatusResponse) HasIdentifier() bool`

HasIdentifier returns a boolean if a field has been set.

### GetStatus

`func (o *ProductInsightsBatchStatusResponse) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *ProductInsightsBatchStatusResponse) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *ProductInsightsBatchStatusResponse) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *ProductInsightsBatchStatusResponse) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetBatchParts

`func (o *ProductInsightsBatchStatusResponse) GetBatchParts() int32`

GetBatchParts returns the BatchParts field if non-nil, zero value otherwise.

### GetBatchPartsOk

`func (o *ProductInsightsBatchStatusResponse) GetBatchPartsOk() (*int32, bool)`

GetBatchPartsOk returns a tuple with the BatchParts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBatchParts

`func (o *ProductInsightsBatchStatusResponse) SetBatchParts(v int32)`

SetBatchParts sets BatchParts field to given value.

### HasBatchParts

`func (o *ProductInsightsBatchStatusResponse) HasBatchParts() bool`

HasBatchParts returns a boolean if a field has been set.

### SetBatchPartsNil

`func (o *ProductInsightsBatchStatusResponse) SetBatchPartsNil(b bool)`

 SetBatchPartsNil sets the value for BatchParts to be an explicit nil

### UnsetBatchParts
`func (o *ProductInsightsBatchStatusResponse) UnsetBatchParts()`

UnsetBatchParts ensures that no value is present for BatchParts, not even an explicit nil
### GetResults

`func (o *ProductInsightsBatchStatusResponse) GetResults() map[string]interface{}`

GetResults returns the Results field if non-nil, zero value otherwise.

### GetResultsOk

`func (o *ProductInsightsBatchStatusResponse) GetResultsOk() (*map[string]interface{}, bool)`

GetResultsOk returns a tuple with the Results field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResults

`func (o *ProductInsightsBatchStatusResponse) SetResults(v map[string]interface{})`

SetResults sets Results field to given value.

### HasResults

`func (o *ProductInsightsBatchStatusResponse) HasResults() bool`

HasResults returns a boolean if a field has been set.

### SetResultsNil

`func (o *ProductInsightsBatchStatusResponse) SetResultsNil(b bool)`

 SetResultsNil sets the value for Results to be an explicit nil

### UnsetResults
`func (o *ProductInsightsBatchStatusResponse) UnsetResults()`

UnsetResults ensures that no value is present for Results, not even an explicit nil
### GetParts

`func (o *ProductInsightsBatchStatusResponse) GetParts() []map[string]interface{}`

GetParts returns the Parts field if non-nil, zero value otherwise.

### GetPartsOk

`func (o *ProductInsightsBatchStatusResponse) GetPartsOk() (*[]map[string]interface{}, bool)`

GetPartsOk returns a tuple with the Parts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParts

`func (o *ProductInsightsBatchStatusResponse) SetParts(v []map[string]interface{})`

SetParts sets Parts field to given value.

### HasParts

`func (o *ProductInsightsBatchStatusResponse) HasParts() bool`

HasParts returns a boolean if a field has been set.

### GetStartedAt

`func (o *ProductInsightsBatchStatusResponse) GetStartedAt() time.Time`

GetStartedAt returns the StartedAt field if non-nil, zero value otherwise.

### GetStartedAtOk

`func (o *ProductInsightsBatchStatusResponse) GetStartedAtOk() (*time.Time, bool)`

GetStartedAtOk returns a tuple with the StartedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartedAt

`func (o *ProductInsightsBatchStatusResponse) SetStartedAt(v time.Time)`

SetStartedAt sets StartedAt field to given value.

### HasStartedAt

`func (o *ProductInsightsBatchStatusResponse) HasStartedAt() bool`

HasStartedAt returns a boolean if a field has been set.

### SetStartedAtNil

`func (o *ProductInsightsBatchStatusResponse) SetStartedAtNil(b bool)`

 SetStartedAtNil sets the value for StartedAt to be an explicit nil

### UnsetStartedAt
`func (o *ProductInsightsBatchStatusResponse) UnsetStartedAt()`

UnsetStartedAt ensures that no value is present for StartedAt, not even an explicit nil
### GetCompletedAt

`func (o *ProductInsightsBatchStatusResponse) GetCompletedAt() time.Time`

GetCompletedAt returns the CompletedAt field if non-nil, zero value otherwise.

### GetCompletedAtOk

`func (o *ProductInsightsBatchStatusResponse) GetCompletedAtOk() (*time.Time, bool)`

GetCompletedAtOk returns a tuple with the CompletedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompletedAt

`func (o *ProductInsightsBatchStatusResponse) SetCompletedAt(v time.Time)`

SetCompletedAt sets CompletedAt field to given value.

### HasCompletedAt

`func (o *ProductInsightsBatchStatusResponse) HasCompletedAt() bool`

HasCompletedAt returns a boolean if a field has been set.

### SetCompletedAtNil

`func (o *ProductInsightsBatchStatusResponse) SetCompletedAtNil(b bool)`

 SetCompletedAtNil sets the value for CompletedAt to be an explicit nil

### UnsetCompletedAt
`func (o *ProductInsightsBatchStatusResponse) UnsetCompletedAt()`

UnsetCompletedAt ensures that no value is present for CompletedAt, not even an explicit nil
### GetCreatedAt

`func (o *ProductInsightsBatchStatusResponse) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *ProductInsightsBatchStatusResponse) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *ProductInsightsBatchStatusResponse) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *ProductInsightsBatchStatusResponse) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetUpdatedAt

`func (o *ProductInsightsBatchStatusResponse) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *ProductInsightsBatchStatusResponse) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *ProductInsightsBatchStatusResponse) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *ProductInsightsBatchStatusResponse) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


