# AnalysisResponseResult

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**PatternType** | Pointer to **string** |  | [optional] 
**Characteristics** | Pointer to [**AnalysisResponseResultCharacteristics**](AnalysisResponseResultCharacteristics.md) |  | [optional] 
**RecommendedMethods** | Pointer to **[]string** |  | [optional] 
**Confidence** | Pointer to **string** |  | [optional] 

## Methods

### NewAnalysisResponseResult

`func NewAnalysisResponseResult() *AnalysisResponseResult`

NewAnalysisResponseResult instantiates a new AnalysisResponseResult object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAnalysisResponseResultWithDefaults

`func NewAnalysisResponseResultWithDefaults() *AnalysisResponseResult`

NewAnalysisResponseResultWithDefaults instantiates a new AnalysisResponseResult object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPatternType

`func (o *AnalysisResponseResult) GetPatternType() string`

GetPatternType returns the PatternType field if non-nil, zero value otherwise.

### GetPatternTypeOk

`func (o *AnalysisResponseResult) GetPatternTypeOk() (*string, bool)`

GetPatternTypeOk returns a tuple with the PatternType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPatternType

`func (o *AnalysisResponseResult) SetPatternType(v string)`

SetPatternType sets PatternType field to given value.

### HasPatternType

`func (o *AnalysisResponseResult) HasPatternType() bool`

HasPatternType returns a boolean if a field has been set.

### GetCharacteristics

`func (o *AnalysisResponseResult) GetCharacteristics() AnalysisResponseResultCharacteristics`

GetCharacteristics returns the Characteristics field if non-nil, zero value otherwise.

### GetCharacteristicsOk

`func (o *AnalysisResponseResult) GetCharacteristicsOk() (*AnalysisResponseResultCharacteristics, bool)`

GetCharacteristicsOk returns a tuple with the Characteristics field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCharacteristics

`func (o *AnalysisResponseResult) SetCharacteristics(v AnalysisResponseResultCharacteristics)`

SetCharacteristics sets Characteristics field to given value.

### HasCharacteristics

`func (o *AnalysisResponseResult) HasCharacteristics() bool`

HasCharacteristics returns a boolean if a field has been set.

### GetRecommendedMethods

`func (o *AnalysisResponseResult) GetRecommendedMethods() []string`

GetRecommendedMethods returns the RecommendedMethods field if non-nil, zero value otherwise.

### GetRecommendedMethodsOk

`func (o *AnalysisResponseResult) GetRecommendedMethodsOk() (*[]string, bool)`

GetRecommendedMethodsOk returns a tuple with the RecommendedMethods field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRecommendedMethods

`func (o *AnalysisResponseResult) SetRecommendedMethods(v []string)`

SetRecommendedMethods sets RecommendedMethods field to given value.

### HasRecommendedMethods

`func (o *AnalysisResponseResult) HasRecommendedMethods() bool`

HasRecommendedMethods returns a boolean if a field has been set.

### GetConfidence

`func (o *AnalysisResponseResult) GetConfidence() string`

GetConfidence returns the Confidence field if non-nil, zero value otherwise.

### GetConfidenceOk

`func (o *AnalysisResponseResult) GetConfidenceOk() (*string, bool)`

GetConfidenceOk returns a tuple with the Confidence field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConfidence

`func (o *AnalysisResponseResult) SetConfidence(v string)`

SetConfidence sets Confidence field to given value.

### HasConfidence

`func (o *AnalysisResponseResult) HasConfidence() bool`

HasConfidence returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


