# ConnectionBody

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ConnectionId** | **string** |  | 
**ConnType** | **string** |  | 
**Description** | Pointer to **NullableString** |  | [optional] 
**Host** | Pointer to **NullableString** |  | [optional] 
**Login** | Pointer to **NullableString** |  | [optional] 
**Schema** | Pointer to **NullableString** |  | [optional] 
**Port** | Pointer to **NullableInt32** |  | [optional] 
**Password** | Pointer to **NullableString** |  | [optional] 
**Extra** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewConnectionBody

`func NewConnectionBody(connectionId string, connType string, ) *ConnectionBody`

NewConnectionBody instantiates a new ConnectionBody object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewConnectionBodyWithDefaults

`func NewConnectionBodyWithDefaults() *ConnectionBody`

NewConnectionBodyWithDefaults instantiates a new ConnectionBody object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetConnectionId

`func (o *ConnectionBody) GetConnectionId() string`

GetConnectionId returns the ConnectionId field if non-nil, zero value otherwise.

### GetConnectionIdOk

`func (o *ConnectionBody) GetConnectionIdOk() (*string, bool)`

GetConnectionIdOk returns a tuple with the ConnectionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConnectionId

`func (o *ConnectionBody) SetConnectionId(v string)`

SetConnectionId sets ConnectionId field to given value.


### GetConnType

`func (o *ConnectionBody) GetConnType() string`

GetConnType returns the ConnType field if non-nil, zero value otherwise.

### GetConnTypeOk

`func (o *ConnectionBody) GetConnTypeOk() (*string, bool)`

GetConnTypeOk returns a tuple with the ConnType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConnType

`func (o *ConnectionBody) SetConnType(v string)`

SetConnType sets ConnType field to given value.


### GetDescription

`func (o *ConnectionBody) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *ConnectionBody) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *ConnectionBody) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *ConnectionBody) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### SetDescriptionNil

`func (o *ConnectionBody) SetDescriptionNil(b bool)`

 SetDescriptionNil sets the value for Description to be an explicit nil

### UnsetDescription
`func (o *ConnectionBody) UnsetDescription()`

UnsetDescription ensures that no value is present for Description, not even an explicit nil
### GetHost

`func (o *ConnectionBody) GetHost() string`

GetHost returns the Host field if non-nil, zero value otherwise.

### GetHostOk

`func (o *ConnectionBody) GetHostOk() (*string, bool)`

GetHostOk returns a tuple with the Host field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHost

`func (o *ConnectionBody) SetHost(v string)`

SetHost sets Host field to given value.

### HasHost

`func (o *ConnectionBody) HasHost() bool`

HasHost returns a boolean if a field has been set.

### SetHostNil

`func (o *ConnectionBody) SetHostNil(b bool)`

 SetHostNil sets the value for Host to be an explicit nil

### UnsetHost
`func (o *ConnectionBody) UnsetHost()`

UnsetHost ensures that no value is present for Host, not even an explicit nil
### GetLogin

`func (o *ConnectionBody) GetLogin() string`

GetLogin returns the Login field if non-nil, zero value otherwise.

### GetLoginOk

`func (o *ConnectionBody) GetLoginOk() (*string, bool)`

GetLoginOk returns a tuple with the Login field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLogin

`func (o *ConnectionBody) SetLogin(v string)`

SetLogin sets Login field to given value.

### HasLogin

`func (o *ConnectionBody) HasLogin() bool`

HasLogin returns a boolean if a field has been set.

### SetLoginNil

`func (o *ConnectionBody) SetLoginNil(b bool)`

 SetLoginNil sets the value for Login to be an explicit nil

### UnsetLogin
`func (o *ConnectionBody) UnsetLogin()`

UnsetLogin ensures that no value is present for Login, not even an explicit nil
### GetSchema

`func (o *ConnectionBody) GetSchema() string`

GetSchema returns the Schema field if non-nil, zero value otherwise.

### GetSchemaOk

`func (o *ConnectionBody) GetSchemaOk() (*string, bool)`

GetSchemaOk returns a tuple with the Schema field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSchema

`func (o *ConnectionBody) SetSchema(v string)`

SetSchema sets Schema field to given value.

### HasSchema

`func (o *ConnectionBody) HasSchema() bool`

HasSchema returns a boolean if a field has been set.

### SetSchemaNil

`func (o *ConnectionBody) SetSchemaNil(b bool)`

 SetSchemaNil sets the value for Schema to be an explicit nil

### UnsetSchema
`func (o *ConnectionBody) UnsetSchema()`

UnsetSchema ensures that no value is present for Schema, not even an explicit nil
### GetPort

`func (o *ConnectionBody) GetPort() int32`

GetPort returns the Port field if non-nil, zero value otherwise.

### GetPortOk

`func (o *ConnectionBody) GetPortOk() (*int32, bool)`

GetPortOk returns a tuple with the Port field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPort

`func (o *ConnectionBody) SetPort(v int32)`

SetPort sets Port field to given value.

### HasPort

`func (o *ConnectionBody) HasPort() bool`

HasPort returns a boolean if a field has been set.

### SetPortNil

`func (o *ConnectionBody) SetPortNil(b bool)`

 SetPortNil sets the value for Port to be an explicit nil

### UnsetPort
`func (o *ConnectionBody) UnsetPort()`

UnsetPort ensures that no value is present for Port, not even an explicit nil
### GetPassword

`func (o *ConnectionBody) GetPassword() string`

GetPassword returns the Password field if non-nil, zero value otherwise.

### GetPasswordOk

`func (o *ConnectionBody) GetPasswordOk() (*string, bool)`

GetPasswordOk returns a tuple with the Password field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPassword

`func (o *ConnectionBody) SetPassword(v string)`

SetPassword sets Password field to given value.

### HasPassword

`func (o *ConnectionBody) HasPassword() bool`

HasPassword returns a boolean if a field has been set.

### SetPasswordNil

`func (o *ConnectionBody) SetPasswordNil(b bool)`

 SetPasswordNil sets the value for Password to be an explicit nil

### UnsetPassword
`func (o *ConnectionBody) UnsetPassword()`

UnsetPassword ensures that no value is present for Password, not even an explicit nil
### GetExtra

`func (o *ConnectionBody) GetExtra() string`

GetExtra returns the Extra field if non-nil, zero value otherwise.

### GetExtraOk

`func (o *ConnectionBody) GetExtraOk() (*string, bool)`

GetExtraOk returns a tuple with the Extra field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExtra

`func (o *ConnectionBody) SetExtra(v string)`

SetExtra sets Extra field to given value.

### HasExtra

`func (o *ConnectionBody) HasExtra() bool`

HasExtra returns a boolean if a field has been set.

### SetExtraNil

`func (o *ConnectionBody) SetExtraNil(b bool)`

 SetExtraNil sets the value for Extra to be an explicit nil

### UnsetExtra
`func (o *ConnectionBody) UnsetExtra()`

UnsetExtra ensures that no value is present for Extra, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


