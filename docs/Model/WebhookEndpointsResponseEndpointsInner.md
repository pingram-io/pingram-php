# # WebhookEndpointsResponseEndpointsInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **string** | Unique identifier for this endpoint within the account. |
**webhook** | **string** | Destination URL that receives signed JSON event payloads. |
**events** | **string[]** | Subscribed event types for this endpoint. |
**secret** | **string** | HMAC secret for verifying X-Pingram-Signature. Returned on create and list; updates keep the same secret. Format: pingram_whsecret_... |

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
