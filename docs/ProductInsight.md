# ProductInsight

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Class** | Pointer to **string** | Insight family (e.g. margin, sales, cost, lead_time) | [optional] 
**Type** | Pointer to **string** |  | [optional] 
**Severity** | Pointer to **string** |  | [optional] 
**Title** | Pointer to **string** |  | [optional] 
**Description** | Pointer to **string** |  | [optional] 
**Metrics** | Pointer to **map[string]interface{}** | The numbers behind the insight | [optional] 
**Recommendation** | Pointer to [**ProductInsightRecommendation**](ProductInsightRecommendation.md) |  | [optional] 
**Confidence** | Pointer to **string** |  | [optional] 
**Date** | Pointer to **string** |  | [optional] 
**ChangeStatus** | Pointer to **string** | How this insight compares to the previous analysis of the same product — every insight is \&quot;new\&quot; on the first analysis | [optional] 

## Methods

### NewProductInsight

`func NewProductInsight() *ProductInsight`

NewProductInsight instantiates a new ProductInsight object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProductInsightWithDefaults

`func NewProductInsightWithDefaults() *ProductInsight`

NewProductInsightWithDefaults instantiates a new ProductInsight object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetClass

`func (o *ProductInsight) GetClass() string`

GetClass returns the Class field if non-nil, zero value otherwise.

### GetClassOk

`func (o *ProductInsight) GetClassOk() (*string, bool)`

GetClassOk returns a tuple with the Class field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClass

`func (o *ProductInsight) SetClass(v string)`

SetClass sets Class field to given value.

### HasClass

`func (o *ProductInsight) HasClass() bool`

HasClass returns a boolean if a field has been set.

### GetType

`func (o *ProductInsight) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *ProductInsight) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *ProductInsight) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *ProductInsight) HasType() bool`

HasType returns a boolean if a field has been set.

### GetSeverity

`func (o *ProductInsight) GetSeverity() string`

GetSeverity returns the Severity field if non-nil, zero value otherwise.

### GetSeverityOk

`func (o *ProductInsight) GetSeverityOk() (*string, bool)`

GetSeverityOk returns a tuple with the Severity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSeverity

`func (o *ProductInsight) SetSeverity(v string)`

SetSeverity sets Severity field to given value.

### HasSeverity

`func (o *ProductInsight) HasSeverity() bool`

HasSeverity returns a boolean if a field has been set.

### GetTitle

`func (o *ProductInsight) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *ProductInsight) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *ProductInsight) SetTitle(v string)`

SetTitle sets Title field to given value.

### HasTitle

`func (o *ProductInsight) HasTitle() bool`

HasTitle returns a boolean if a field has been set.

### GetDescription

`func (o *ProductInsight) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *ProductInsight) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *ProductInsight) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *ProductInsight) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetMetrics

`func (o *ProductInsight) GetMetrics() map[string]interface{}`

GetMetrics returns the Metrics field if non-nil, zero value otherwise.

### GetMetricsOk

`func (o *ProductInsight) GetMetricsOk() (*map[string]interface{}, bool)`

GetMetricsOk returns a tuple with the Metrics field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetrics

`func (o *ProductInsight) SetMetrics(v map[string]interface{})`

SetMetrics sets Metrics field to given value.

### HasMetrics

`func (o *ProductInsight) HasMetrics() bool`

HasMetrics returns a boolean if a field has been set.

### GetRecommendation

`func (o *ProductInsight) GetRecommendation() ProductInsightRecommendation`

GetRecommendation returns the Recommendation field if non-nil, zero value otherwise.

### GetRecommendationOk

`func (o *ProductInsight) GetRecommendationOk() (*ProductInsightRecommendation, bool)`

GetRecommendationOk returns a tuple with the Recommendation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRecommendation

`func (o *ProductInsight) SetRecommendation(v ProductInsightRecommendation)`

SetRecommendation sets Recommendation field to given value.

### HasRecommendation

`func (o *ProductInsight) HasRecommendation() bool`

HasRecommendation returns a boolean if a field has been set.

### GetConfidence

`func (o *ProductInsight) GetConfidence() string`

GetConfidence returns the Confidence field if non-nil, zero value otherwise.

### GetConfidenceOk

`func (o *ProductInsight) GetConfidenceOk() (*string, bool)`

GetConfidenceOk returns a tuple with the Confidence field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConfidence

`func (o *ProductInsight) SetConfidence(v string)`

SetConfidence sets Confidence field to given value.

### HasConfidence

`func (o *ProductInsight) HasConfidence() bool`

HasConfidence returns a boolean if a field has been set.

### GetDate

`func (o *ProductInsight) GetDate() string`

GetDate returns the Date field if non-nil, zero value otherwise.

### GetDateOk

`func (o *ProductInsight) GetDateOk() (*string, bool)`

GetDateOk returns a tuple with the Date field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDate

`func (o *ProductInsight) SetDate(v string)`

SetDate sets Date field to given value.

### HasDate

`func (o *ProductInsight) HasDate() bool`

HasDate returns a boolean if a field has been set.

### GetChangeStatus

`func (o *ProductInsight) GetChangeStatus() string`

GetChangeStatus returns the ChangeStatus field if non-nil, zero value otherwise.

### GetChangeStatusOk

`func (o *ProductInsight) GetChangeStatusOk() (*string, bool)`

GetChangeStatusOk returns a tuple with the ChangeStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChangeStatus

`func (o *ProductInsight) SetChangeStatus(v string)`

SetChangeStatus sets ChangeStatus field to given value.

### HasChangeStatus

`func (o *ProductInsight) HasChangeStatus() bool`

HasChangeStatus returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


