# ProductInsightsResponseResultComparison

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**From** | Pointer to **time.Time** | Timestamp of the previous analysis | [optional] 
**To** | Pointer to **time.Time** |  | [optional] 
**Result** | Pointer to **map[string]interface{}** |  | [optional] 
**Developments** | Pointer to [**ProductInsightsResponseResultComparisonDevelopments**](ProductInsightsResponseResultComparisonDevelopments.md) |  | [optional] 

## Methods

### NewProductInsightsResponseResultComparison

`func NewProductInsightsResponseResultComparison() *ProductInsightsResponseResultComparison`

NewProductInsightsResponseResultComparison instantiates a new ProductInsightsResponseResultComparison object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProductInsightsResponseResultComparisonWithDefaults

`func NewProductInsightsResponseResultComparisonWithDefaults() *ProductInsightsResponseResultComparison`

NewProductInsightsResponseResultComparisonWithDefaults instantiates a new ProductInsightsResponseResultComparison object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetFrom

`func (o *ProductInsightsResponseResultComparison) GetFrom() time.Time`

GetFrom returns the From field if non-nil, zero value otherwise.

### GetFromOk

`func (o *ProductInsightsResponseResultComparison) GetFromOk() (*time.Time, bool)`

GetFromOk returns a tuple with the From field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFrom

`func (o *ProductInsightsResponseResultComparison) SetFrom(v time.Time)`

SetFrom sets From field to given value.

### HasFrom

`func (o *ProductInsightsResponseResultComparison) HasFrom() bool`

HasFrom returns a boolean if a field has been set.

### GetTo

`func (o *ProductInsightsResponseResultComparison) GetTo() time.Time`

GetTo returns the To field if non-nil, zero value otherwise.

### GetToOk

`func (o *ProductInsightsResponseResultComparison) GetToOk() (*time.Time, bool)`

GetToOk returns a tuple with the To field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTo

`func (o *ProductInsightsResponseResultComparison) SetTo(v time.Time)`

SetTo sets To field to given value.

### HasTo

`func (o *ProductInsightsResponseResultComparison) HasTo() bool`

HasTo returns a boolean if a field has been set.

### GetResult

`func (o *ProductInsightsResponseResultComparison) GetResult() map[string]interface{}`

GetResult returns the Result field if non-nil, zero value otherwise.

### GetResultOk

`func (o *ProductInsightsResponseResultComparison) GetResultOk() (*map[string]interface{}, bool)`

GetResultOk returns a tuple with the Result field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResult

`func (o *ProductInsightsResponseResultComparison) SetResult(v map[string]interface{})`

SetResult sets Result field to given value.

### HasResult

`func (o *ProductInsightsResponseResultComparison) HasResult() bool`

HasResult returns a boolean if a field has been set.

### GetDevelopments

`func (o *ProductInsightsResponseResultComparison) GetDevelopments() ProductInsightsResponseResultComparisonDevelopments`

GetDevelopments returns the Developments field if non-nil, zero value otherwise.

### GetDevelopmentsOk

`func (o *ProductInsightsResponseResultComparison) GetDevelopmentsOk() (*ProductInsightsResponseResultComparisonDevelopments, bool)`

GetDevelopmentsOk returns a tuple with the Developments field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDevelopments

`func (o *ProductInsightsResponseResultComparison) SetDevelopments(v ProductInsightsResponseResultComparisonDevelopments)`

SetDevelopments sets Developments field to given value.

### HasDevelopments

`func (o *ProductInsightsResponseResultComparison) HasDevelopments() bool`

HasDevelopments returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


