# BatchPresignResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**UploadUrl** | Pointer to **string** | Presigned URL — HTTP PUT the JSON file here, including any returned headers | [optional] 
**Headers** | Pointer to **map[string]string** | Headers that must be sent with the upload request | [optional] 
**FileKey** | Pointer to **string** | Pass this as &#x60;file_key&#x60; to POST /v2/batch/forecast after uploading | [optional] 
**ExpiresIn** | Pointer to **int32** | Seconds the upload URL stays valid | [optional] 

## Methods

### NewBatchPresignResponse

`func NewBatchPresignResponse() *BatchPresignResponse`

NewBatchPresignResponse instantiates a new BatchPresignResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewBatchPresignResponseWithDefaults

`func NewBatchPresignResponseWithDefaults() *BatchPresignResponse`

NewBatchPresignResponseWithDefaults instantiates a new BatchPresignResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUploadUrl

`func (o *BatchPresignResponse) GetUploadUrl() string`

GetUploadUrl returns the UploadUrl field if non-nil, zero value otherwise.

### GetUploadUrlOk

`func (o *BatchPresignResponse) GetUploadUrlOk() (*string, bool)`

GetUploadUrlOk returns a tuple with the UploadUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUploadUrl

`func (o *BatchPresignResponse) SetUploadUrl(v string)`

SetUploadUrl sets UploadUrl field to given value.

### HasUploadUrl

`func (o *BatchPresignResponse) HasUploadUrl() bool`

HasUploadUrl returns a boolean if a field has been set.

### GetHeaders

`func (o *BatchPresignResponse) GetHeaders() map[string]string`

GetHeaders returns the Headers field if non-nil, zero value otherwise.

### GetHeadersOk

`func (o *BatchPresignResponse) GetHeadersOk() (*map[string]string, bool)`

GetHeadersOk returns a tuple with the Headers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHeaders

`func (o *BatchPresignResponse) SetHeaders(v map[string]string)`

SetHeaders sets Headers field to given value.

### HasHeaders

`func (o *BatchPresignResponse) HasHeaders() bool`

HasHeaders returns a boolean if a field has been set.

### GetFileKey

`func (o *BatchPresignResponse) GetFileKey() string`

GetFileKey returns the FileKey field if non-nil, zero value otherwise.

### GetFileKeyOk

`func (o *BatchPresignResponse) GetFileKeyOk() (*string, bool)`

GetFileKeyOk returns a tuple with the FileKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFileKey

`func (o *BatchPresignResponse) SetFileKey(v string)`

SetFileKey sets FileKey field to given value.

### HasFileKey

`func (o *BatchPresignResponse) HasFileKey() bool`

HasFileKey returns a boolean if a field has been set.

### GetExpiresIn

`func (o *BatchPresignResponse) GetExpiresIn() int32`

GetExpiresIn returns the ExpiresIn field if non-nil, zero value otherwise.

### GetExpiresInOk

`func (o *BatchPresignResponse) GetExpiresInOk() (*int32, bool)`

GetExpiresInOk returns a tuple with the ExpiresIn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpiresIn

`func (o *BatchPresignResponse) SetExpiresIn(v int32)`

SetExpiresIn sets ExpiresIn field to given value.

### HasExpiresIn

`func (o *BatchPresignResponse) HasExpiresIn() bool`

HasExpiresIn returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


