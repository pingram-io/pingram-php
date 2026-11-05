# # WebhookEndpoint

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **string** | Unique identifier for this endpoint within the account. |
**webhook** | **string** | Destination URL that receives signed JSON event payloads. Credentials are not included in this URL. |
**events** | **string[]** | Subscribed event types for this endpoint. |
**secret** | **string** | HMAC secret for verifying X-Pingram-Signature. Returned on create and list; updates keep the same secret. Format: pingram_whsecret_... |
**basic_auth** | [**\Pingram\Model\WebhookEndpointBasicAuth**](WebhookEndpointBasicAuth.md) |  | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
