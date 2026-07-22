# ValidationFailedResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Error** | Pointer to **string** |  | [optional] 
**Errors** | Pointer to **map[string][]string** |  | [optional] 
**TimeTakenMs** | Pointer to **float32** |  | [optional] 

## Methods

### NewValidationFailedResponse

`func NewValidationFailedResponse() *ValidationFailedResponse`

NewValidationFailedResponse instantiates a new ValidationFailedResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewValidationFailedResponseWithDefaults

`func NewValidationFailedResponseWithDefaults() *ValidationFailedResponse`

NewValidationFailedResponseWithDefaults instantiates a new ValidationFailedResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetError

`func (o *ValidationFailedResponse) GetError() string`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *ValidationFailedResponse) GetErrorOk() (*string, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *ValidationFailedResponse) SetError(v string)`

SetError sets Error field to given value.

### HasError

`func (o *ValidationFailedResponse) HasError() bool`

HasError returns a boolean if a field has been set.

### GetErrors

`func (o *ValidationFailedResponse) GetErrors() map[string][]string`

GetErrors returns the Errors field if non-nil, zero value otherwise.

### GetErrorsOk

`func (o *ValidationFailedResponse) GetErrorsOk() (*map[string][]string, bool)`

GetErrorsOk returns a tuple with the Errors field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrors

`func (o *ValidationFailedResponse) SetErrors(v map[string][]string)`

SetErrors sets Errors field to given value.

### HasErrors

`func (o *ValidationFailedResponse) HasErrors() bool`

HasErrors returns a boolean if a field has been set.

### GetTimeTakenMs

`func (o *ValidationFailedResponse) GetTimeTakenMs() float32`

GetTimeTakenMs returns the TimeTakenMs field if non-nil, zero value otherwise.

### GetTimeTakenMsOk

`func (o *ValidationFailedResponse) GetTimeTakenMsOk() (*float32, bool)`

GetTimeTakenMsOk returns a tuple with the TimeTakenMs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimeTakenMs

`func (o *ValidationFailedResponse) SetTimeTakenMs(v float32)`

SetTimeTakenMs sets TimeTakenMs field to given value.

### HasTimeTakenMs

`func (o *ValidationFailedResponse) HasTimeTakenMs() bool`

HasTimeTakenMs returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


