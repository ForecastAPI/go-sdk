# AutoSelection

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Requested** | Pointer to **string** |  | [optional] 
**Selected** | Pointer to **string** | The model that produced this response | [optional] 
**Reason** | Pointer to **string** | Why this model was selected. &#x60;scored_winner&#x60; means one model beat every alternative by a clear margin on realized accuracy for this identifier; everything else means the evidence-gathering default was served.  | [optional] 
**Scores** | Pointer to [**map[string]AutoSelectionScoresValue**](AutoSelectionScoresValue.md) | Per-model realized-accuracy scorecard for this identifier, when one exists | [optional] 

## Methods

### NewAutoSelection

`func NewAutoSelection() *AutoSelection`

NewAutoSelection instantiates a new AutoSelection object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAutoSelectionWithDefaults

`func NewAutoSelectionWithDefaults() *AutoSelection`

NewAutoSelectionWithDefaults instantiates a new AutoSelection object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetRequested

`func (o *AutoSelection) GetRequested() string`

GetRequested returns the Requested field if non-nil, zero value otherwise.

### GetRequestedOk

`func (o *AutoSelection) GetRequestedOk() (*string, bool)`

GetRequestedOk returns a tuple with the Requested field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequested

`func (o *AutoSelection) SetRequested(v string)`

SetRequested sets Requested field to given value.

### HasRequested

`func (o *AutoSelection) HasRequested() bool`

HasRequested returns a boolean if a field has been set.

### GetSelected

`func (o *AutoSelection) GetSelected() string`

GetSelected returns the Selected field if non-nil, zero value otherwise.

### GetSelectedOk

`func (o *AutoSelection) GetSelectedOk() (*string, bool)`

GetSelectedOk returns a tuple with the Selected field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSelected

`func (o *AutoSelection) SetSelected(v string)`

SetSelected sets Selected field to given value.

### HasSelected

`func (o *AutoSelection) HasSelected() bool`

HasSelected returns a boolean if a field has been set.

### GetReason

`func (o *AutoSelection) GetReason() string`

GetReason returns the Reason field if non-nil, zero value otherwise.

### GetReasonOk

`func (o *AutoSelection) GetReasonOk() (*string, bool)`

GetReasonOk returns a tuple with the Reason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReason

`func (o *AutoSelection) SetReason(v string)`

SetReason sets Reason field to given value.

### HasReason

`func (o *AutoSelection) HasReason() bool`

HasReason returns a boolean if a field has been set.

### GetScores

`func (o *AutoSelection) GetScores() map[string]AutoSelectionScoresValue`

GetScores returns the Scores field if non-nil, zero value otherwise.

### GetScoresOk

`func (o *AutoSelection) GetScoresOk() (*map[string]AutoSelectionScoresValue, bool)`

GetScoresOk returns a tuple with the Scores field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScores

`func (o *AutoSelection) SetScores(v map[string]AutoSelectionScoresValue)`

SetScores sets Scores field to given value.

### HasScores

`func (o *AutoSelection) HasScores() bool`

HasScores returns a boolean if a field has been set.

### SetScoresNil

`func (o *AutoSelection) SetScoresNil(b bool)`

 SetScoresNil sets the value for Scores to be an explicit nil

### UnsetScores
`func (o *AutoSelection) UnsetScores()`

UnsetScores ensures that no value is present for Scores, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


