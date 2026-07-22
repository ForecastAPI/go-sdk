# AnomalyDetectionResponseResultAnalysis

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**MethodUsed** | Pointer to **string** |  | [optional] 
**Confidence** | Pointer to **string** | Confidence in the method selection; \&quot;user_specified\&quot; when a method was named in the request | [optional] 
**Reason** | Pointer to **string** |  | [optional] 
**DataCharacteristics** | Pointer to **map[string]interface{}** | Statistical profile of the data (present on auto selection) | [optional] 
**DetectionSummary** | Pointer to [**AnomalyDetectionResponseResultAnalysisDetectionSummary**](AnomalyDetectionResponseResultAnalysisDetectionSummary.md) |  | [optional] 

## Methods

### NewAnomalyDetectionResponseResultAnalysis

`func NewAnomalyDetectionResponseResultAnalysis() *AnomalyDetectionResponseResultAnalysis`

NewAnomalyDetectionResponseResultAnalysis instantiates a new AnomalyDetectionResponseResultAnalysis object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAnomalyDetectionResponseResultAnalysisWithDefaults

`func NewAnomalyDetectionResponseResultAnalysisWithDefaults() *AnomalyDetectionResponseResultAnalysis`

NewAnomalyDetectionResponseResultAnalysisWithDefaults instantiates a new AnomalyDetectionResponseResultAnalysis object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMethodUsed

`func (o *AnomalyDetectionResponseResultAnalysis) GetMethodUsed() string`

GetMethodUsed returns the MethodUsed field if non-nil, zero value otherwise.

### GetMethodUsedOk

`func (o *AnomalyDetectionResponseResultAnalysis) GetMethodUsedOk() (*string, bool)`

GetMethodUsedOk returns a tuple with the MethodUsed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMethodUsed

`func (o *AnomalyDetectionResponseResultAnalysis) SetMethodUsed(v string)`

SetMethodUsed sets MethodUsed field to given value.

### HasMethodUsed

`func (o *AnomalyDetectionResponseResultAnalysis) HasMethodUsed() bool`

HasMethodUsed returns a boolean if a field has been set.

### GetConfidence

`func (o *AnomalyDetectionResponseResultAnalysis) GetConfidence() string`

GetConfidence returns the Confidence field if non-nil, zero value otherwise.

### GetConfidenceOk

`func (o *AnomalyDetectionResponseResultAnalysis) GetConfidenceOk() (*string, bool)`

GetConfidenceOk returns a tuple with the Confidence field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConfidence

`func (o *AnomalyDetectionResponseResultAnalysis) SetConfidence(v string)`

SetConfidence sets Confidence field to given value.

### HasConfidence

`func (o *AnomalyDetectionResponseResultAnalysis) HasConfidence() bool`

HasConfidence returns a boolean if a field has been set.

### GetReason

`func (o *AnomalyDetectionResponseResultAnalysis) GetReason() string`

GetReason returns the Reason field if non-nil, zero value otherwise.

### GetReasonOk

`func (o *AnomalyDetectionResponseResultAnalysis) GetReasonOk() (*string, bool)`

GetReasonOk returns a tuple with the Reason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReason

`func (o *AnomalyDetectionResponseResultAnalysis) SetReason(v string)`

SetReason sets Reason field to given value.

### HasReason

`func (o *AnomalyDetectionResponseResultAnalysis) HasReason() bool`

HasReason returns a boolean if a field has been set.

### GetDataCharacteristics

`func (o *AnomalyDetectionResponseResultAnalysis) GetDataCharacteristics() map[string]interface{}`

GetDataCharacteristics returns the DataCharacteristics field if non-nil, zero value otherwise.

### GetDataCharacteristicsOk

`func (o *AnomalyDetectionResponseResultAnalysis) GetDataCharacteristicsOk() (*map[string]interface{}, bool)`

GetDataCharacteristicsOk returns a tuple with the DataCharacteristics field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDataCharacteristics

`func (o *AnomalyDetectionResponseResultAnalysis) SetDataCharacteristics(v map[string]interface{})`

SetDataCharacteristics sets DataCharacteristics field to given value.

### HasDataCharacteristics

`func (o *AnomalyDetectionResponseResultAnalysis) HasDataCharacteristics() bool`

HasDataCharacteristics returns a boolean if a field has been set.

### GetDetectionSummary

`func (o *AnomalyDetectionResponseResultAnalysis) GetDetectionSummary() AnomalyDetectionResponseResultAnalysisDetectionSummary`

GetDetectionSummary returns the DetectionSummary field if non-nil, zero value otherwise.

### GetDetectionSummaryOk

`func (o *AnomalyDetectionResponseResultAnalysis) GetDetectionSummaryOk() (*AnomalyDetectionResponseResultAnalysisDetectionSummary, bool)`

GetDetectionSummaryOk returns a tuple with the DetectionSummary field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDetectionSummary

`func (o *AnomalyDetectionResponseResultAnalysis) SetDetectionSummary(v AnomalyDetectionResponseResultAnalysisDetectionSummary)`

SetDetectionSummary sets DetectionSummary field to given value.

### HasDetectionSummary

`func (o *AnomalyDetectionResponseResultAnalysis) HasDetectionSummary() bool`

HasDetectionSummary returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


