# ConnectionResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ConnectionId** | **string** |  | 
**ConnType** | **string** |  | 
**Description** | **NullableString** |  | 
**Host** | **NullableString** |  | 
**Login** | **NullableString** |  | 
**Schema** | **NullableString** |  | 
**Port** | **NullableInt32** |  | 
**Password** | **NullableString** |  | 
**Extra** | **NullableString** |  | 

## Methods

### NewConnectionResponse

`func NewConnectionResponse(connectionId string, connType string, description NullableString, host NullableString, login NullableString, schema NullableString, port NullableInt32, password NullableString, extra NullableString, ) *ConnectionResponse`

NewConnectionResponse instantiates a new ConnectionResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewConnectionResponseWithDefaults

`func NewConnectionResponseWithDefaults() *ConnectionResponse`

NewConnectionResponseWithDefaults instantiates a new ConnectionResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetConnectionId

`func (o *ConnectionResponse) GetConnectionId() string`

GetConnectionId returns the ConnectionId field if non-nil, zero value otherwise.

### GetConnectionIdOk

`func (o *ConnectionResponse) GetConnectionIdOk() (*string, bool)`

GetConnectionIdOk returns a tuple with the ConnectionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConnectionId

`func (o *ConnectionResponse) SetConnectionId(v string)`

SetConnectionId sets ConnectionId field to given value.


### GetConnType

`func (o *ConnectionResponse) GetConnType() string`

GetConnType returns the ConnType field if non-nil, zero value otherwise.

### GetConnTypeOk

`func (o *ConnectionResponse) GetConnTypeOk() (*string, bool)`

GetConnTypeOk returns a tuple with the ConnType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConnType

`func (o *ConnectionResponse) SetConnType(v string)`

SetConnType sets ConnType field to given value.


### GetDescription

`func (o *ConnectionResponse) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *ConnectionResponse) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *ConnectionResponse) SetDescription(v string)`

SetDescription sets Description field to given value.


### SetDescriptionNil

`func (o *ConnectionResponse) SetDescriptionNil(b bool)`

 SetDescriptionNil sets the value for Description to be an explicit nil

### UnsetDescription
`func (o *ConnectionResponse) UnsetDescription()`

UnsetDescription ensures that no value is present for Description, not even an explicit nil
### GetHost

`func (o *ConnectionResponse) GetHost() string`

GetHost returns the Host field if non-nil, zero value otherwise.

### GetHostOk

`func (o *ConnectionResponse) GetHostOk() (*string, bool)`

GetHostOk returns a tuple with the Host field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHost

`func (o *ConnectionResponse) SetHost(v string)`

SetHost sets Host field to given value.


### SetHostNil

`func (o *ConnectionResponse) SetHostNil(b bool)`

 SetHostNil sets the value for Host to be an explicit nil

### UnsetHost
`func (o *ConnectionResponse) UnsetHost()`

UnsetHost ensures that no value is present for Host, not even an explicit nil
### GetLogin

`func (o *ConnectionResponse) GetLogin() string`

GetLogin returns the Login field if non-nil, zero value otherwise.

### GetLoginOk

`func (o *ConnectionResponse) GetLoginOk() (*string, bool)`

GetLoginOk returns a tuple with the Login field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLogin

`func (o *ConnectionResponse) SetLogin(v string)`

SetLogin sets Login field to given value.


### SetLoginNil

`func (o *ConnectionResponse) SetLoginNil(b bool)`

 SetLoginNil sets the value for Login to be an explicit nil

### UnsetLogin
`func (o *ConnectionResponse) UnsetLogin()`

UnsetLogin ensures that no value is present for Login, not even an explicit nil
### GetSchema

`func (o *ConnectionResponse) GetSchema() string`

GetSchema returns the Schema field if non-nil, zero value otherwise.

### GetSchemaOk

`func (o *ConnectionResponse) GetSchemaOk() (*string, bool)`

GetSchemaOk returns a tuple with the Schema field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSchema

`func (o *ConnectionResponse) SetSchema(v string)`

SetSchema sets Schema field to given value.


### SetSchemaNil

`func (o *ConnectionResponse) SetSchemaNil(b bool)`

 SetSchemaNil sets the value for Schema to be an explicit nil

### UnsetSchema
`func (o *ConnectionResponse) UnsetSchema()`

UnsetSchema ensures that no value is present for Schema, not even an explicit nil
### GetPort

`func (o *ConnectionResponse) GetPort() int32`

GetPort returns the Port field if non-nil, zero value otherwise.

### GetPortOk

`func (o *ConnectionResponse) GetPortOk() (*int32, bool)`

GetPortOk returns a tuple with the Port field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPort

`func (o *ConnectionResponse) SetPort(v int32)`

SetPort sets Port field to given value.


### SetPortNil

`func (o *ConnectionResponse) SetPortNil(b bool)`

 SetPortNil sets the value for Port to be an explicit nil

### UnsetPort
`func (o *ConnectionResponse) UnsetPort()`

UnsetPort ensures that no value is present for Port, not even an explicit nil
### GetPassword

`func (o *ConnectionResponse) GetPassword() string`

GetPassword returns the Password field if non-nil, zero value otherwise.

### GetPasswordOk

`func (o *ConnectionResponse) GetPasswordOk() (*string, bool)`

GetPasswordOk returns a tuple with the Password field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPassword

`func (o *ConnectionResponse) SetPassword(v string)`

SetPassword sets Password field to given value.


### SetPasswordNil

`func (o *ConnectionResponse) SetPasswordNil(b bool)`

 SetPasswordNil sets the value for Password to be an explicit nil

### UnsetPassword
`func (o *ConnectionResponse) UnsetPassword()`

UnsetPassword ensures that no value is present for Password, not even an explicit nil
### GetExtra

`func (o *ConnectionResponse) GetExtra() string`

GetExtra returns the Extra field if non-nil, zero value otherwise.

### GetExtraOk

`func (o *ConnectionResponse) GetExtraOk() (*string, bool)`

GetExtraOk returns a tuple with the Extra field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExtra

`func (o *ConnectionResponse) SetExtra(v string)`

SetExtra sets Extra field to given value.


### SetExtraNil

`func (o *ConnectionResponse) SetExtraNil(b bool)`

 SetExtraNil sets the value for Extra to be an explicit nil

### UnsetExtra
`func (o *ConnectionResponse) UnsetExtra()`

UnsetExtra ensures that no value is present for Extra, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


