# TrafficForecastingRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Identifier** | **string** | Metric identifier (e.g., endpoint name, service name) | 
**Frequency** | **string** | Data frequency for forecasting: - M: Minute (for real-time traffic) - H: Hourly - D: Daily - W: Weekly - MS: Monthly (start of month) - ME: Monthly (end of month) - Q: Quarterly - Y: Yearly  | 
**StartDate** | Pointer to **NullableTime** | Optional start date for the forecast period | [optional] 
**Periods** | **int32** | Number of periods to forecast ahead | 
**Model** | Pointer to **string** | Forecasting model behind the plan. &#x60;auto&#x60; routes the identifier to whichever model has proven most accurate on it, sharing the scorecard built by /v2/forecast and /v2/batch/forecast; on this endpoint auto&#39;s ensemble default runs as &#x60;standard&#x60; until a winner emerges, and the decision is reported in &#x60;meta.auto_selection&#x60;. Advanced variants, ensemble and auto cost 25% more usage.  | [optional] [default to "standard"]
**EnableIntelligentAggregation** | Pointer to **bool** | Enable intelligent data aggregation for improved forecasting | [optional] 
**ConfidenceLevel** | Pointer to **float32** | Confidence level for forecast intervals (default 0.95) | [optional] 
**Data** | [**[]TrafficForecastingRequestDataInner**](TrafficForecastingRequestDataInner.md) | Historical traffic data for forecasting | 
**TrafficSettings** | [**TrafficForecastingRequestTrafficSettings**](TrafficForecastingRequestTrafficSettings.md) |  | 

## Methods

### NewTrafficForecastingRequest

`func NewTrafficForecastingRequest(identifier string, frequency string, periods int32, data []TrafficForecastingRequestDataInner, trafficSettings TrafficForecastingRequestTrafficSettings, ) *TrafficForecastingRequest`

NewTrafficForecastingRequest instantiates a new TrafficForecastingRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTrafficForecastingRequestWithDefaults

`func NewTrafficForecastingRequestWithDefaults() *TrafficForecastingRequest`

NewTrafficForecastingRequestWithDefaults instantiates a new TrafficForecastingRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetIdentifier

`func (o *TrafficForecastingRequest) GetIdentifier() string`

GetIdentifier returns the Identifier field if non-nil, zero value otherwise.

### GetIdentifierOk

`func (o *TrafficForecastingRequest) GetIdentifierOk() (*string, bool)`

GetIdentifierOk returns a tuple with the Identifier field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdentifier

`func (o *TrafficForecastingRequest) SetIdentifier(v string)`

SetIdentifier sets Identifier field to given value.


### GetFrequency

`func (o *TrafficForecastingRequest) GetFrequency() string`

GetFrequency returns the Frequency field if non-nil, zero value otherwise.

### GetFrequencyOk

`func (o *TrafficForecastingRequest) GetFrequencyOk() (*string, bool)`

GetFrequencyOk returns a tuple with the Frequency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFrequency

`func (o *TrafficForecastingRequest) SetFrequency(v string)`

SetFrequency sets Frequency field to given value.


### GetStartDate

`func (o *TrafficForecastingRequest) GetStartDate() time.Time`

GetStartDate returns the StartDate field if non-nil, zero value otherwise.

### GetStartDateOk

`func (o *TrafficForecastingRequest) GetStartDateOk() (*time.Time, bool)`

GetStartDateOk returns a tuple with the StartDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartDate

`func (o *TrafficForecastingRequest) SetStartDate(v time.Time)`

SetStartDate sets StartDate field to given value.

### HasStartDate

`func (o *TrafficForecastingRequest) HasStartDate() bool`

HasStartDate returns a boolean if a field has been set.

### SetStartDateNil

`func (o *TrafficForecastingRequest) SetStartDateNil(b bool)`

 SetStartDateNil sets the value for StartDate to be an explicit nil

### UnsetStartDate
`func (o *TrafficForecastingRequest) UnsetStartDate()`

UnsetStartDate ensures that no value is present for StartDate, not even an explicit nil
### GetPeriods

`func (o *TrafficForecastingRequest) GetPeriods() int32`

GetPeriods returns the Periods field if non-nil, zero value otherwise.

### GetPeriodsOk

`func (o *TrafficForecastingRequest) GetPeriodsOk() (*int32, bool)`

GetPeriodsOk returns a tuple with the Periods field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPeriods

`func (o *TrafficForecastingRequest) SetPeriods(v int32)`

SetPeriods sets Periods field to given value.


### GetModel

`func (o *TrafficForecastingRequest) GetModel() string`

GetModel returns the Model field if non-nil, zero value otherwise.

### GetModelOk

`func (o *TrafficForecastingRequest) GetModelOk() (*string, bool)`

GetModelOk returns a tuple with the Model field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModel

`func (o *TrafficForecastingRequest) SetModel(v string)`

SetModel sets Model field to given value.

### HasModel

`func (o *TrafficForecastingRequest) HasModel() bool`

HasModel returns a boolean if a field has been set.

### GetEnableIntelligentAggregation

`func (o *TrafficForecastingRequest) GetEnableIntelligentAggregation() bool`

GetEnableIntelligentAggregation returns the EnableIntelligentAggregation field if non-nil, zero value otherwise.

### GetEnableIntelligentAggregationOk

`func (o *TrafficForecastingRequest) GetEnableIntelligentAggregationOk() (*bool, bool)`

GetEnableIntelligentAggregationOk returns a tuple with the EnableIntelligentAggregation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnableIntelligentAggregation

`func (o *TrafficForecastingRequest) SetEnableIntelligentAggregation(v bool)`

SetEnableIntelligentAggregation sets EnableIntelligentAggregation field to given value.

### HasEnableIntelligentAggregation

`func (o *TrafficForecastingRequest) HasEnableIntelligentAggregation() bool`

HasEnableIntelligentAggregation returns a boolean if a field has been set.

### GetConfidenceLevel

`func (o *TrafficForecastingRequest) GetConfidenceLevel() float32`

GetConfidenceLevel returns the ConfidenceLevel field if non-nil, zero value otherwise.

### GetConfidenceLevelOk

`func (o *TrafficForecastingRequest) GetConfidenceLevelOk() (*float32, bool)`

GetConfidenceLevelOk returns a tuple with the ConfidenceLevel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConfidenceLevel

`func (o *TrafficForecastingRequest) SetConfidenceLevel(v float32)`

SetConfidenceLevel sets ConfidenceLevel field to given value.

### HasConfidenceLevel

`func (o *TrafficForecastingRequest) HasConfidenceLevel() bool`

HasConfidenceLevel returns a boolean if a field has been set.

### GetData

`func (o *TrafficForecastingRequest) GetData() []TrafficForecastingRequestDataInner`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *TrafficForecastingRequest) GetDataOk() (*[]TrafficForecastingRequestDataInner, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *TrafficForecastingRequest) SetData(v []TrafficForecastingRequestDataInner)`

SetData sets Data field to given value.


### GetTrafficSettings

`func (o *TrafficForecastingRequest) GetTrafficSettings() TrafficForecastingRequestTrafficSettings`

GetTrafficSettings returns the TrafficSettings field if non-nil, zero value otherwise.

### GetTrafficSettingsOk

`func (o *TrafficForecastingRequest) GetTrafficSettingsOk() (*TrafficForecastingRequestTrafficSettings, bool)`

GetTrafficSettingsOk returns a tuple with the TrafficSettings field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrafficSettings

`func (o *TrafficForecastingRequest) SetTrafficSettings(v TrafficForecastingRequestTrafficSettings)`

SetTrafficSettings sets TrafficSettings field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


