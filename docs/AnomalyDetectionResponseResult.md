# AnomalyDetectionResponseResult

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Anomalies** | Pointer to [**[]AnomalyDetectionResponseResultAnomaliesInner**](AnomalyDetectionResponseResultAnomaliesInner.md) | Detected anomalies, most severe first | [optional] 
**Analysis** | Pointer to [**AnomalyDetectionResponseResultAnalysis**](AnomalyDetectionResponseResultAnalysis.md) |  | [optional] 
**Alternatives** | Pointer to **[]map[string]interface{}** | Other suitable methods (present on auto selection) | [optional] 
**Statistics** | Pointer to **map[string]interface{}** | Method statistics (present when a method was named in the request) | [optional] 
**Interpretation** | Pointer to **map[string]interface{}** | Human-readable interpretation (present when a method was named in the request) | [optional] 

## Methods

### NewAnomalyDetectionResponseResult

`func NewAnomalyDetectionResponseResult() *AnomalyDetectionResponseResult`

NewAnomalyDetectionResponseResult instantiates a new AnomalyDetectionResponseResult object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAnomalyDetectionResponseResultWithDefaults

`func NewAnomalyDetectionResponseResultWithDefaults() *AnomalyDetectionResponseResult`

NewAnomalyDetectionResponseResultWithDefaults instantiates a new AnomalyDetectionResponseResult object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAnomalies

`func (o *AnomalyDetectionResponseResult) GetAnomalies() []AnomalyDetectionResponseResultAnomaliesInner`

GetAnomalies returns the Anomalies field if non-nil, zero value otherwise.

### GetAnomaliesOk

`func (o *AnomalyDetectionResponseResult) GetAnomaliesOk() (*[]AnomalyDetectionResponseResultAnomaliesInner, bool)`

GetAnomaliesOk returns a tuple with the Anomalies field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAnomalies

`func (o *AnomalyDetectionResponseResult) SetAnomalies(v []AnomalyDetectionResponseResultAnomaliesInner)`

SetAnomalies sets Anomalies field to given value.

### HasAnomalies

`func (o *AnomalyDetectionResponseResult) HasAnomalies() bool`

HasAnomalies returns a boolean if a field has been set.

### GetAnalysis

`func (o *AnomalyDetectionResponseResult) GetAnalysis() AnomalyDetectionResponseResultAnalysis`

GetAnalysis returns the Analysis field if non-nil, zero value otherwise.

### GetAnalysisOk

`func (o *AnomalyDetectionResponseResult) GetAnalysisOk() (*AnomalyDetectionResponseResultAnalysis, bool)`

GetAnalysisOk returns a tuple with the Analysis field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAnalysis

`func (o *AnomalyDetectionResponseResult) SetAnalysis(v AnomalyDetectionResponseResultAnalysis)`

SetAnalysis sets Analysis field to given value.

### HasAnalysis

`func (o *AnomalyDetectionResponseResult) HasAnalysis() bool`

HasAnalysis returns a boolean if a field has been set.

### GetAlternatives

`func (o *AnomalyDetectionResponseResult) GetAlternatives() []map[string]interface{}`

GetAlternatives returns the Alternatives field if non-nil, zero value otherwise.

### GetAlternativesOk

`func (o *AnomalyDetectionResponseResult) GetAlternativesOk() (*[]map[string]interface{}, bool)`

GetAlternativesOk returns a tuple with the Alternatives field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAlternatives

`func (o *AnomalyDetectionResponseResult) SetAlternatives(v []map[string]interface{})`

SetAlternatives sets Alternatives field to given value.

### HasAlternatives

`func (o *AnomalyDetectionResponseResult) HasAlternatives() bool`

HasAlternatives returns a boolean if a field has been set.

### GetStatistics

`func (o *AnomalyDetectionResponseResult) GetStatistics() map[string]interface{}`

GetStatistics returns the Statistics field if non-nil, zero value otherwise.

### GetStatisticsOk

`func (o *AnomalyDetectionResponseResult) GetStatisticsOk() (*map[string]interface{}, bool)`

GetStatisticsOk returns a tuple with the Statistics field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatistics

`func (o *AnomalyDetectionResponseResult) SetStatistics(v map[string]interface{})`

SetStatistics sets Statistics field to given value.

### HasStatistics

`func (o *AnomalyDetectionResponseResult) HasStatistics() bool`

HasStatistics returns a boolean if a field has been set.

### GetInterpretation

`func (o *AnomalyDetectionResponseResult) GetInterpretation() map[string]interface{}`

GetInterpretation returns the Interpretation field if non-nil, zero value otherwise.

### GetInterpretationOk

`func (o *AnomalyDetectionResponseResult) GetInterpretationOk() (*map[string]interface{}, bool)`

GetInterpretationOk returns a tuple with the Interpretation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInterpretation

`func (o *AnomalyDetectionResponseResult) SetInterpretation(v map[string]interface{})`

SetInterpretation sets Interpretation field to given value.

### HasInterpretation

`func (o *AnomalyDetectionResponseResult) HasInterpretation() bool`

HasInterpretation returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


