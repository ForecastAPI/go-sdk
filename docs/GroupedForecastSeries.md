# GroupedForecastSeries

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Segment** | **map[string]interface{}** | Names exactly the declared hierarchy dimensions — no more, no fewer. Values are non-empty scalars of at most 128 characters.  | 
**Data** | [**[]GroupedForecastSeriesDataInner**](GroupedForecastSeriesDataInner.md) | Historical data for this leaf (at most 1,000 points per series on the free tier) | 

## Methods

### NewGroupedForecastSeries

`func NewGroupedForecastSeries(segment map[string]interface{}, data []GroupedForecastSeriesDataInner, ) *GroupedForecastSeries`

NewGroupedForecastSeries instantiates a new GroupedForecastSeries object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGroupedForecastSeriesWithDefaults

`func NewGroupedForecastSeriesWithDefaults() *GroupedForecastSeries`

NewGroupedForecastSeriesWithDefaults instantiates a new GroupedForecastSeries object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSegment

`func (o *GroupedForecastSeries) GetSegment() map[string]interface{}`

GetSegment returns the Segment field if non-nil, zero value otherwise.

### GetSegmentOk

`func (o *GroupedForecastSeries) GetSegmentOk() (*map[string]interface{}, bool)`

GetSegmentOk returns a tuple with the Segment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSegment

`func (o *GroupedForecastSeries) SetSegment(v map[string]interface{})`

SetSegment sets Segment field to given value.


### GetData

`func (o *GroupedForecastSeries) GetData() []GroupedForecastSeriesDataInner`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *GroupedForecastSeries) GetDataOk() (*[]GroupedForecastSeriesDataInner, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *GroupedForecastSeries) SetData(v []GroupedForecastSeriesDataInner)`

SetData sets Data field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


