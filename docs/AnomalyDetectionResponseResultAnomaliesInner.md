# AnomalyDetectionResponseResultAnomaliesInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Index** | Pointer to **int32** | Position of the point in the submitted data | [optional] 
**Date** | Pointer to **string** |  | [optional] 
**Value** | Pointer to **float32** |  | [optional] 
**ExpectedRange** | Pointer to **map[string]interface{}** | The range the point was expected to fall within | [optional] 
**Severity** | Pointer to **string** |  | [optional] 
**Type** | Pointer to **string** | spike/dip for zscore, outlier_high/outlier_low for iqr, seasonal variants for seasonal | [optional] 

## Methods

### NewAnomalyDetectionResponseResultAnomaliesInner

`func NewAnomalyDetectionResponseResultAnomaliesInner() *AnomalyDetectionResponseResultAnomaliesInner`

NewAnomalyDetectionResponseResultAnomaliesInner instantiates a new AnomalyDetectionResponseResultAnomaliesInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAnomalyDetectionResponseResultAnomaliesInnerWithDefaults

`func NewAnomalyDetectionResponseResultAnomaliesInnerWithDefaults() *AnomalyDetectionResponseResultAnomaliesInner`

NewAnomalyDetectionResponseResultAnomaliesInnerWithDefaults instantiates a new AnomalyDetectionResponseResultAnomaliesInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetIndex

`func (o *AnomalyDetectionResponseResultAnomaliesInner) GetIndex() int32`

GetIndex returns the Index field if non-nil, zero value otherwise.

### GetIndexOk

`func (o *AnomalyDetectionResponseResultAnomaliesInner) GetIndexOk() (*int32, bool)`

GetIndexOk returns a tuple with the Index field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIndex

`func (o *AnomalyDetectionResponseResultAnomaliesInner) SetIndex(v int32)`

SetIndex sets Index field to given value.

### HasIndex

`func (o *AnomalyDetectionResponseResultAnomaliesInner) HasIndex() bool`

HasIndex returns a boolean if a field has been set.

### GetDate

`func (o *AnomalyDetectionResponseResultAnomaliesInner) GetDate() string`

GetDate returns the Date field if non-nil, zero value otherwise.

### GetDateOk

`func (o *AnomalyDetectionResponseResultAnomaliesInner) GetDateOk() (*string, bool)`

GetDateOk returns a tuple with the Date field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDate

`func (o *AnomalyDetectionResponseResultAnomaliesInner) SetDate(v string)`

SetDate sets Date field to given value.

### HasDate

`func (o *AnomalyDetectionResponseResultAnomaliesInner) HasDate() bool`

HasDate returns a boolean if a field has been set.

### GetValue

`func (o *AnomalyDetectionResponseResultAnomaliesInner) GetValue() float32`

GetValue returns the Value field if non-nil, zero value otherwise.

### GetValueOk

`func (o *AnomalyDetectionResponseResultAnomaliesInner) GetValueOk() (*float32, bool)`

GetValueOk returns a tuple with the Value field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValue

`func (o *AnomalyDetectionResponseResultAnomaliesInner) SetValue(v float32)`

SetValue sets Value field to given value.

### HasValue

`func (o *AnomalyDetectionResponseResultAnomaliesInner) HasValue() bool`

HasValue returns a boolean if a field has been set.

### GetExpectedRange

`func (o *AnomalyDetectionResponseResultAnomaliesInner) GetExpectedRange() map[string]interface{}`

GetExpectedRange returns the ExpectedRange field if non-nil, zero value otherwise.

### GetExpectedRangeOk

`func (o *AnomalyDetectionResponseResultAnomaliesInner) GetExpectedRangeOk() (*map[string]interface{}, bool)`

GetExpectedRangeOk returns a tuple with the ExpectedRange field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpectedRange

`func (o *AnomalyDetectionResponseResultAnomaliesInner) SetExpectedRange(v map[string]interface{})`

SetExpectedRange sets ExpectedRange field to given value.

### HasExpectedRange

`func (o *AnomalyDetectionResponseResultAnomaliesInner) HasExpectedRange() bool`

HasExpectedRange returns a boolean if a field has been set.

### GetSeverity

`func (o *AnomalyDetectionResponseResultAnomaliesInner) GetSeverity() string`

GetSeverity returns the Severity field if non-nil, zero value otherwise.

### GetSeverityOk

`func (o *AnomalyDetectionResponseResultAnomaliesInner) GetSeverityOk() (*string, bool)`

GetSeverityOk returns a tuple with the Severity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSeverity

`func (o *AnomalyDetectionResponseResultAnomaliesInner) SetSeverity(v string)`

SetSeverity sets Severity field to given value.

### HasSeverity

`func (o *AnomalyDetectionResponseResultAnomaliesInner) HasSeverity() bool`

HasSeverity returns a boolean if a field has been set.

### GetType

`func (o *AnomalyDetectionResponseResultAnomaliesInner) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *AnomalyDetectionResponseResultAnomaliesInner) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *AnomalyDetectionResponseResultAnomaliesInner) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *AnomalyDetectionResponseResultAnomaliesInner) HasType() bool`

HasType returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


