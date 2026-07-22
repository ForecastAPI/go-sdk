# GroupedForecastStatusResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**GroupedForecastId** | Pointer to **string** |  | [optional] 
**Status** | Pointer to **string** | The run is all-or-nothing — there is no per-node failure state | [optional] 
**NodeCount** | Pointer to **int32** |  | [optional] 
**Results** | Pointer to [**NullableGroupedForecastResults**](GroupedForecastResults.md) | Populated once status is &#x60;completed&#x60;; null before that and on failure | [optional] 
**Error** | Pointer to **NullableString** | Failure reason when status is &#x60;failed&#x60; | [optional] 
**StartedAt** | Pointer to **NullableTime** |  | [optional] 
**CompletedAt** | Pointer to **NullableTime** |  | [optional] 
**CreatedAt** | Pointer to **NullableTime** |  | [optional] 

## Methods

### NewGroupedForecastStatusResponse

`func NewGroupedForecastStatusResponse() *GroupedForecastStatusResponse`

NewGroupedForecastStatusResponse instantiates a new GroupedForecastStatusResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGroupedForecastStatusResponseWithDefaults

`func NewGroupedForecastStatusResponseWithDefaults() *GroupedForecastStatusResponse`

NewGroupedForecastStatusResponseWithDefaults instantiates a new GroupedForecastStatusResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetGroupedForecastId

`func (o *GroupedForecastStatusResponse) GetGroupedForecastId() string`

GetGroupedForecastId returns the GroupedForecastId field if non-nil, zero value otherwise.

### GetGroupedForecastIdOk

`func (o *GroupedForecastStatusResponse) GetGroupedForecastIdOk() (*string, bool)`

GetGroupedForecastIdOk returns a tuple with the GroupedForecastId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGroupedForecastId

`func (o *GroupedForecastStatusResponse) SetGroupedForecastId(v string)`

SetGroupedForecastId sets GroupedForecastId field to given value.

### HasGroupedForecastId

`func (o *GroupedForecastStatusResponse) HasGroupedForecastId() bool`

HasGroupedForecastId returns a boolean if a field has been set.

### GetStatus

`func (o *GroupedForecastStatusResponse) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *GroupedForecastStatusResponse) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *GroupedForecastStatusResponse) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *GroupedForecastStatusResponse) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetNodeCount

`func (o *GroupedForecastStatusResponse) GetNodeCount() int32`

GetNodeCount returns the NodeCount field if non-nil, zero value otherwise.

### GetNodeCountOk

`func (o *GroupedForecastStatusResponse) GetNodeCountOk() (*int32, bool)`

GetNodeCountOk returns a tuple with the NodeCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNodeCount

`func (o *GroupedForecastStatusResponse) SetNodeCount(v int32)`

SetNodeCount sets NodeCount field to given value.

### HasNodeCount

`func (o *GroupedForecastStatusResponse) HasNodeCount() bool`

HasNodeCount returns a boolean if a field has been set.

### GetResults

`func (o *GroupedForecastStatusResponse) GetResults() GroupedForecastResults`

GetResults returns the Results field if non-nil, zero value otherwise.

### GetResultsOk

`func (o *GroupedForecastStatusResponse) GetResultsOk() (*GroupedForecastResults, bool)`

GetResultsOk returns a tuple with the Results field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResults

`func (o *GroupedForecastStatusResponse) SetResults(v GroupedForecastResults)`

SetResults sets Results field to given value.

### HasResults

`func (o *GroupedForecastStatusResponse) HasResults() bool`

HasResults returns a boolean if a field has been set.

### SetResultsNil

`func (o *GroupedForecastStatusResponse) SetResultsNil(b bool)`

 SetResultsNil sets the value for Results to be an explicit nil

### UnsetResults
`func (o *GroupedForecastStatusResponse) UnsetResults()`

UnsetResults ensures that no value is present for Results, not even an explicit nil
### GetError

`func (o *GroupedForecastStatusResponse) GetError() string`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *GroupedForecastStatusResponse) GetErrorOk() (*string, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *GroupedForecastStatusResponse) SetError(v string)`

SetError sets Error field to given value.

### HasError

`func (o *GroupedForecastStatusResponse) HasError() bool`

HasError returns a boolean if a field has been set.

### SetErrorNil

`func (o *GroupedForecastStatusResponse) SetErrorNil(b bool)`

 SetErrorNil sets the value for Error to be an explicit nil

### UnsetError
`func (o *GroupedForecastStatusResponse) UnsetError()`

UnsetError ensures that no value is present for Error, not even an explicit nil
### GetStartedAt

`func (o *GroupedForecastStatusResponse) GetStartedAt() time.Time`

GetStartedAt returns the StartedAt field if non-nil, zero value otherwise.

### GetStartedAtOk

`func (o *GroupedForecastStatusResponse) GetStartedAtOk() (*time.Time, bool)`

GetStartedAtOk returns a tuple with the StartedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartedAt

`func (o *GroupedForecastStatusResponse) SetStartedAt(v time.Time)`

SetStartedAt sets StartedAt field to given value.

### HasStartedAt

`func (o *GroupedForecastStatusResponse) HasStartedAt() bool`

HasStartedAt returns a boolean if a field has been set.

### SetStartedAtNil

`func (o *GroupedForecastStatusResponse) SetStartedAtNil(b bool)`

 SetStartedAtNil sets the value for StartedAt to be an explicit nil

### UnsetStartedAt
`func (o *GroupedForecastStatusResponse) UnsetStartedAt()`

UnsetStartedAt ensures that no value is present for StartedAt, not even an explicit nil
### GetCompletedAt

`func (o *GroupedForecastStatusResponse) GetCompletedAt() time.Time`

GetCompletedAt returns the CompletedAt field if non-nil, zero value otherwise.

### GetCompletedAtOk

`func (o *GroupedForecastStatusResponse) GetCompletedAtOk() (*time.Time, bool)`

GetCompletedAtOk returns a tuple with the CompletedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompletedAt

`func (o *GroupedForecastStatusResponse) SetCompletedAt(v time.Time)`

SetCompletedAt sets CompletedAt field to given value.

### HasCompletedAt

`func (o *GroupedForecastStatusResponse) HasCompletedAt() bool`

HasCompletedAt returns a boolean if a field has been set.

### SetCompletedAtNil

`func (o *GroupedForecastStatusResponse) SetCompletedAtNil(b bool)`

 SetCompletedAtNil sets the value for CompletedAt to be an explicit nil

### UnsetCompletedAt
`func (o *GroupedForecastStatusResponse) UnsetCompletedAt()`

UnsetCompletedAt ensures that no value is present for CompletedAt, not even an explicit nil
### GetCreatedAt

`func (o *GroupedForecastStatusResponse) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *GroupedForecastStatusResponse) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *GroupedForecastStatusResponse) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *GroupedForecastStatusResponse) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### SetCreatedAtNil

`func (o *GroupedForecastStatusResponse) SetCreatedAtNil(b bool)`

 SetCreatedAtNil sets the value for CreatedAt to be an explicit nil

### UnsetCreatedAt
`func (o *GroupedForecastStatusResponse) UnsetCreatedAt()`

UnsetCreatedAt ensures that no value is present for CreatedAt, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


